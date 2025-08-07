Here’s the **corrected, foolproof guide** with exact GitHub UI steps and manual Chirpy zip installation. All commands and versions are pinned for your setup (`devsgh-vid.github.io`).

---

### **Complete Chirpy Jekyll Setup Guide**  
**For GitHub Pages:** `https://devsgh-vid.github.io`  
**Author:** Dev Singh (`devsingh.videos@gmail.com`)  

---

### **System Requirements**  
- Ubuntu 22.04  
- GitHub account: `devsgh-vid`  

---

### **Step 1: System Setup (Local Machine)**  
```bash
sudo apt update && sudo apt upgrade -y
sudo apt install -y git curl wget unzip build-essential zlib1g-dev libssl-dev libreadline-dev libyaml-dev libffi-dev libgdbm-dev libncurses5-dev libgmp-dev autoconf bison libgdbm-compat-dev libsqlite3-dev
```

---

### **Step 2: Configure Git**  
```bash
git config --global user.name "Dev Singh"
git config --global user.email "devsingh.videos@gmail.com"
git config --global init.defaultBranch main
```

---

### **Step 3: Install Ruby 3.2.2 (Critical for Chirpy)**  
```bash
# Install rbenv
git clone https://github.com/rbenv/rbenv.git ~/.rbenv
echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.bashrc
echo 'eval "$(rbenv init - bash)"' >> ~/.bashrc
source ~/.bashrc

# Install ruby-build plugin
git clone https://github.com/rbenv/ruby-build.git ~/.rbenv/plugins/ruby-build

# Install Ruby 3.2.2 (exact version)
rbenv install 3.2.2
rbenv global 3.2.2
```

**Verify:**  
```bash
ruby -v  # Must show: ruby 3.2.2
```

---

### **Step 4: Install Node.js 18 (For Asset Compilation)**  
```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.0/install.sh | bash
source ~/.bashrc
nvm install 18
nvm use 18
nvm alias default 18
```

**Verify:**  
```bash
node -v  # Must show: v18.x.x
```

---

### **Step 5: Create GitHub Repository (UI Steps)**  
1. Go to: [https://github.com/new](https://github.com/new)  
2. **Repository name**: `devsgh-vid.github.io` (must match exactly).  
3. **Visibility**: Public.  
4. **DO NOT** initialize with README, .gitignore, or license.  
5. Click **Create repository**.  

---

### **Step 6: Clone Your Repository (Local Machine)**  
```bash
cd ~/Documents
git clone https://github.com/devsgh-vid/devsgh-vid.github.io.git
cd devsgh-vid.github.io
```

---

### **Step 7: Download and Install Chirpy Theme (Manual Zip)**  
```bash
# Download Chirpy zip (no git clone)
curl -L https://github.com/cotes2020/jekyll-theme-chirpy/archive/refs/heads/master.zip -o chirpy.zip
unzip chirpy.zip

# Copy ONLY required theme files (no .git/)
cp -r jekyll-theme-chirpy-master/_layouts .
cp -r jekyll-theme-chirpy-master/_includes .
cp -r jekyll-theme-chirpy-master/_sass .
cp -r jekyll-theme-chirpy-master/assets .
cp -r jekyll-theme-chirpy-master/_data .
cp -r jekyll-theme-chirpy-master/_plugins .

# Clean up
rm -rf chirpy.zip jekyll-theme-chirpy-master
```

---

### **Step 8: Create Gemfile (Critical for GitHub Pages)**  
```bash
cat > Gemfile << 'EOF'
source "https://rubygems.org"

# GitHub Pages compatibility
gem "github-pages", "~> 231", group: :jekyll_plugins

# Chirpy plugins
group :jekyll_plugins do
  gem "jekyll-paginate"
  gem "jekyll-sitemap"
  gem "jekyll-feed"
  gem "jekyll-include-cache"
  gem "jekyll-archives"
end

# Windows support
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Testing
gem "html-proofer", "~> 5.0", group: :test
EOF
```

---

### **Step 9: Install Bundler 2.5.6**  
```bash
gem install bundler -v 2.5.6
bundle _2.5.6_ install
```

---

### **Step 10: Configure `_config.yml`**  
```bash
cat > _config.yml << 'EOF'
title: DevSGH CloudSec
tagline: Cloud Security & DevOps Engineering
url: "https://devsgh-vid.github.io"
baseurl: ""

author:
  name: Dev Singh
  email: devsingh.videos@gmail.com

github:
  username: devsgh-vid

plugins:
  - jekyll-paginate
  - jekyll-sitemap
  - jekyll-feed
  - jekyll-include-cache
  - jekyll-archives

defaults:
  - scope:
      path: ""
      type: posts
    values:
      layout: post
      toc: true
EOF
```

---

### **Step 11: Create Homepage**  
```bash
cat > index.md << 'EOF'
---
layout: home
---
EOF
```

---

### **Step 12: Test Locally**  
```bash
bundle _2.5.6_ exec jekyll serve --livereload
```
- Visit `http://localhost:4000` to verify the theme loads.  
- **Expected**: Chirpy theme with sidebar, correct title, and no errors.  

---

### **Step 13: Deploy to GitHub Pages**  
#### **1. Create GitHub Actions Workflow**  
```bash
mkdir -p .github/workflows
cat > .github/workflows/pages.yml << 'EOF'
name: Deploy to GitHub Pages
on:
  push:
    branches: [main]
jobs:
  build-and-deploy:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: ruby/setup-ruby@v1
        with:
          ruby-version: 3.2
          bundler-cache: true
      - run: bundle _2.5.6_ exec jekyll build
      - uses: actions/upload-pages-artifact@v3
        with:
          path: '_site/'
      - uses: actions/deploy-pages@v4
EOF
```

#### **2. Push to GitHub**  
```bash
git add .
git commit -m "Initial Chirpy setup"
git push origin main
```

---

### **Step 14: Enable GitHub Pages (UI Steps)**  
1. Go to: `https://github.com/devsgh-vid/devsgh-vid.github.io/settings/pages`  
2. Under **Build and deployment**:  
   - **Source**: Select `GitHub Actions`  
3. Wait 2-3 minutes for deployment.  
4. Visit: `https://devsgh-vid.github.io`  

---

### **Troubleshooting**  
#### **1. 404 Error After Deployment**  
- **Fix**:  
  - Verify repository name is **exactly** `devsgh-vid.github.io`.  
  - Go to `Settings > Pages` and confirm "Your site is published at...".  

#### **2. Missing CSS/Stlyling**  
- **Fix**:  
  - Ensure `_config.yml` **does not** include `theme: jekyll-theme-chirpy`.  
  - Re-run `bundle _2.5.6_ exec jekyll build` locally to test.  

#### **3. "Unknown tag 'include_cached'"**  
- **Fix**:  
  - Confirm `jekyll-include-cache` is in your `Gemfile`.  

---

### **Final Verification**  
✅ Local: `http://localhost:4000` works  
✅ GitHub Actions: Green checkmark in `Actions` tab  
✅ Live: `https://devsgh-vid.github.io` loads Chirpy theme  

Let me know if you hit any snags! This guide avoids all known pitfalls in your original setup.
