<pre><font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~</b></font>$ sudo apt update &amp;&amp; sudo apt upgrade -y
[sudo] password for devs: 
Hit:1 http://au.archive.ubuntu.com/ubuntu jammy InRelease
Hit:2 http://au.archive.ubuntu.com/ubuntu jammy-updates InRelease
Hit:3 http://au.archive.ubuntu.com/ubuntu jammy-backports InRelease
Hit:4 https://download.docker.com/linux/ubuntu jammy InRelease
Get:5 http://security.ubuntu.com/ubuntu jammy-security InRelease [129 kB]
Hit:6 https://packages.microsoft.com/repos/edge stable InRelease
Fetched 129 kB in 2s (61.9 kB/s)<font color="#A2734C">                 </font>
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
All packages are up to date.
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
Calculating upgrade... Done
Get more security updates through Ubuntu Pro with &apos;esm-apps&apos; enabled:
  libzvbi-common libpostproc55 libavcodec58 libgstreamer-plugins-bad1.0-0
  libavutil56 libswscale5 libswresample3 libavformat58 libzvbi0 libavfilter7
Learn more about Ubuntu Pro at https://ubuntu.com/pro
0 to upgrade, 0 to newly install, 0 to remove and 0 not to upgrade.
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~</b></font>$ sudo apt install -y git curl wget unzip build-essential zlib1g-dev libssl-dev libreadline-dev libyaml-dev libffi-dev libgdbm-dev libncurses5-dev libgmp-dev autoconf bison libgdbm-compat-dev libsqlite3-dev
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
curl is already the newest version (7.81.0-1ubuntu1.20).
git is already the newest version (1:2.34.1-1ubuntu1.15).
unzip is already the newest version (6.0-26ubuntu3.2).
unzip set to manually installed.
wget is already the newest version (1.21.2-2ubuntu1.1).
wget set to manually installed.
The following additional packages will be installed:
  automake autotools-dev binutils
  binutils-common binutils-x86-64-linux-gnu
  dpkg-dev fakeroot g++ g++-11 gcc gcc-11
  libalgorithm-diff-perl
  libalgorithm-diff-xs-perl
  libalgorithm-merge-perl libasan6 libbinutils
  libc-dev-bin libc-devtools libc6-dev libcc1-0
  libcrypt-dev libctf-nobfd0 libctf0
  libdpkg-perl libfakeroot
  libfile-fcntllock-perl libgcc-11-dev
  libgmpxx4ldbl libitm1 liblsan0 libncurses-dev
  libnsl-dev libsigsegv2 libstdc++-11-dev
  libtirpc-dev libtsan0 libubsan1 linux-libc-dev
  lto-disabled-list m4 make manpages-dev
  rpcsvc-proto
Suggested packages:
  autoconf-archive gnu-standards autoconf-doc
  libtool gettext binutils-doc bison-doc
  debian-keyring g++-multilib g++-11-multilib
  gcc-11-doc gcc-multilib flex gcc-doc
  gcc-11-multilib gcc-11-locales glibc-doc bzr
  gmp-doc libgmp10-doc libmpfr-dev ncurses-doc
  readline-doc sqlite3-doc libssl-doc
  libstdc++-11-doc libyaml-doc m4-doc make-doc
The following NEW packages will be installed:
  autoconf automake autotools-dev binutils
  binutils-common binutils-x86-64-linux-gnu
  bison build-essential dpkg-dev fakeroot g++
  g++-11 gcc gcc-11 libalgorithm-diff-perl
  libalgorithm-diff-xs-perl
  libalgorithm-merge-perl libasan6 libbinutils
  libc-dev-bin libc-devtools libc6-dev libcc1-0
  libcrypt-dev libctf-nobfd0 libctf0
  libdpkg-perl libfakeroot libffi-dev
  libfile-fcntllock-perl libgcc-11-dev
  libgdbm-compat-dev libgdbm-dev libgmp-dev
  libgmpxx4ldbl libitm1 liblsan0 libncurses-dev
  libncurses5-dev libnsl-dev libreadline-dev
  libsigsegv2 libsqlite3-dev libssl-dev
  libstdc++-11-dev libtirpc-dev libtsan0
  libubsan1 libyaml-dev linux-libc-dev
  lto-disabled-list m4 make manpages-dev
  rpcsvc-proto zlib1g-dev
0 to upgrade, 56 to newly install, 0 to remove and 0 not to upgrade.
Need to get 60.5 MB of archives.
After this operation, 215 MB of additional disk space will be used.
Get:1 http://au.archive.ubuntu.com/ubuntu jammy/main amd64 libsigsegv2 amd64 2.13-1ubuntu3 [14.6 kB]
Get:2 http://au.archive.ubuntu.com/ubuntu jammy/main amd64 m4 amd64 1.4.18-5ubuntu2 [199 kB]
Get:3 http://au.archive.ubuntu.com/ubuntu jammy/main amd64 autoconf all 2.71-2 [338 kB]
Get:4 http://au.archive.ubuntu.com/ubuntu jammy/main amd64 autotools-dev all 20220109.1 [44.9 kB]
Get:5 http://au.archive.ubuntu.com/ubuntu jammy/main amd64 automake all 1:1.16.5-1.3 [558 kB]
Get:6 http://au.archive.ubuntu.com/ubuntu jammy-updates/main amd64 binutils-common amd64 2.38-4ubuntu2.8 [223 kB]
Get:7 http://au.archive.ubuntu.com/ubuntu jammy-updates/main amd64 libbinutils amd64 2.38-4ubuntu2.8 [661 kB]
Get:8 http://au.archive.ubuntu.com/ubuntu jammy-updates/main amd64 libctf-nobfd0 amd64 2.38-4ubuntu2.8 [108 kB]
Get:9 http://au.archive.ubuntu.com/ubuntu jammy-updates/main amd64 libctf0 amd64 2.38-4ubuntu2.8 [103 kB]
Get:10 http://au.archive.ubuntu.com/ubuntu jammy-updates/main amd64 binutils-x86-64-linux-gnu amd64 2.38-4ubuntu2.8 [2,324 kB]
Get:11 http://au.archive.ubuntu.com/ubuntu jammy-updates/main amd64 binutils amd64 2.38-4ubuntu2.8 [3,196 B]
Get:12 http://au.archive.ubuntu.com/ubuntu jammy/main amd64 bison amd64 2:3.8.2+dfsg-1build1 [748 kB]
Get:13 http://au.archive.ubuntu.com/ubuntu jammy-updates/main amd64 libc-dev-bin amd64 2.35-0ubuntu3.10 [20.3 kB]
Get:14 http://au.archive.ubuntu.com/ubuntu jammy-updates/main amd64 linux-libc-dev amd64 5.15.0-151.161 [1,318 kB]
Get:15 http://au.archive.ubuntu.com/ubuntu jammy/main amd64 libcrypt-dev amd64 1:4.4.27-1 [112 kB]
Get:16 http://au.archive.ubuntu.com/ubuntu jammy/main amd64 rpcsvc-proto amd64 1.4.2-0ubuntu6 [68.5 kB]
Get:17 http://au.archive.ubuntu.com/ubuntu jammy-updates/main amd64 libtirpc-dev amd64 1.3.2-2ubuntu0.1 [192 kB]
Get:18 http://au.archive.ubuntu.com/ubuntu jammy/main amd64 libnsl-dev amd64 1.3.0-2build2 [71.3 kB]
Get:19 http://au.archive.ubuntu.com/ubuntu jammy-updates/main amd64 libc6-dev amd64 2.35-0ubuntu3.10 [2,100 kB]
Get:20 http://au.archive.ubuntu.com/ubuntu jammy-updates/main amd64 libcc1-0 amd64 12.3.0-1ubuntu1~22.04 [48.3 kB]
Get:21 http://au.archive.ubuntu.com/ubuntu jammy-updates/main amd64 libitm1 amd64 12.3.0-1ubuntu1~22.04 [30.2 kB]
Get:22 http://au.archive.ubuntu.com/ubuntu jammy-updates/main amd64 libasan6 amd64 11.4.0-1ubuntu1~22.04 [2,282 kB]
Get:23 http://au.archive.ubuntu.com/ubuntu jammy-updates/main amd64 liblsan0 amd64 12.3.0-1ubuntu1~22.04 [1,069 kB]
Get:24 http://au.archive.ubuntu.com/ubuntu jammy-updates/main amd64 libtsan0 amd64 11.4.0-1ubuntu1~22.04 [2,260 kB]
Get:25 http://au.archive.ubuntu.com/ubuntu jammy-updates/main amd64 libubsan1 amd64 12.3.0-1ubuntu1~22.04 [976 kB]
Get:26 http://au.archive.ubuntu.com/ubuntu jammy-updates/main amd64 libgcc-11-dev amd64 11.4.0-1ubuntu1~22.04 [2,517 kB]
Get:27 http://au.archive.ubuntu.com/ubuntu jammy-updates/main amd64 gcc-11 amd64 11.4.0-1ubuntu1~22.04 [20.1 MB]
Get:28 http://au.archive.ubuntu.com/ubuntu jammy/main amd64 gcc amd64 4:11.2.0-1ubuntu1 [5,112 B]
Get:29 http://au.archive.ubuntu.com/ubuntu jammy-updates/main amd64 libstdc++-11-dev amd64 11.4.0-1ubuntu1~22.04 [2,101 kB]
Get:30 http://au.archive.ubuntu.com/ubuntu jammy-updates/main amd64 g++-11 amd64 11.4.0-1ubuntu1~22.04 [11.4 MB]
Get:31 http://au.archive.ubuntu.com/ubuntu jammy/main amd64 g++ amd64 4:11.2.0-1ubuntu1 [1,412 B]
Get:32 http://au.archive.ubuntu.com/ubuntu jammy/main amd64 make amd64 4.3-4.1build1 [180 kB]
Get:33 http://au.archive.ubuntu.com/ubuntu jammy-updates/main amd64 libdpkg-perl all 1.21.1ubuntu2.3 [237 kB]
Get:34 http://au.archive.ubuntu.com/ubuntu jammy/main amd64 lto-disabled-list all 24 [12.5 kB]
Get:35 http://au.archive.ubuntu.com/ubuntu jammy-updates/main amd64 dpkg-dev all 1.21.1ubuntu2.3 [922 kB]
Get:36 http://au.archive.ubuntu.com/ubuntu jammy/main amd64 build-essential amd64 12.9ubuntu3 [4,744 B]
Get:37 http://au.archive.ubuntu.com/ubuntu jammy/main amd64 libfakeroot amd64 1.28-1ubuntu1 [31.5 kB]
Get:38 http://au.archive.ubuntu.com/ubuntu jammy/main amd64 fakeroot amd64 1.28-1ubuntu1 [60.4 kB]
Get:39 http://au.archive.ubuntu.com/ubuntu jammy/main amd64 libalgorithm-diff-perl all 1.201-1 [41.8 kB]
Get:40 http://au.archive.ubuntu.com/ubuntu jammy/main amd64 libalgorithm-diff-xs-perl amd64 0.04-6build3 [11.9 kB]
Get:41 http://au.archive.ubuntu.com/ubuntu jammy/main amd64 libalgorithm-merge-perl all 0.08-3 [12.0 kB]
Get:42 http://au.archive.ubuntu.com/ubuntu jammy-updates/main amd64 libc-devtools amd64 2.35-0ubuntu3.10 [29.0 kB]
Get:43 http://au.archive.ubuntu.com/ubuntu jammy/main amd64 libfile-fcntllock-perl amd64 0.22-3build7 [33.9 kB]
Get:44 http://au.archive.ubuntu.com/ubuntu jammy/main amd64 libgdbm-compat-dev amd64 1.23-1 [6,672 B]
Get:45 http://au.archive.ubuntu.com/ubuntu jammy/main amd64 libgdbm-dev amd64 1.23-1 [117 kB]
Get:46 http://au.archive.ubuntu.com/ubuntu jammy/main amd64 libgmpxx4ldbl amd64 2:6.2.1+dfsg-3ubuntu1 [9,580 B]
Get:47 http://au.archive.ubuntu.com/ubuntu jammy/main amd64 libgmp-dev amd64 2:6.2.1+dfsg-3ubuntu1 [337 kB]
Get:48 http://au.archive.ubuntu.com/ubuntu jammy-updates/main amd64 libncurses-dev amd64 6.3-2ubuntu0.1 [381 kB]
Get:49 http://au.archive.ubuntu.com/ubuntu jammy-updates/main amd64 libncurses5-dev amd64 6.3-2ubuntu0.1 [790 B]
Get:50 http://au.archive.ubuntu.com/ubuntu jammy/main amd64 libreadline-dev amd64 8.1.2-1 [166 kB]
Get:51 http://au.archive.ubuntu.com/ubuntu jammy-updates/main amd64 libsqlite3-dev amd64 3.37.2-2ubuntu0.5 [847 kB]
Get:52 http://au.archive.ubuntu.com/ubuntu jammy-updates/main amd64 libssl-dev amd64 3.0.2-0ubuntu1.19 [2,376 kB]
Get:53 http://au.archive.ubuntu.com/ubuntu jammy/main amd64 manpages-dev all 5.10-1ubuntu1 [2,309 kB]
Get:54 http://au.archive.ubuntu.com/ubuntu jammy-updates/main amd64 zlib1g-dev amd64 1:1.2.11.dfsg-2ubuntu9.2 [164 kB]
Get:55 http://au.archive.ubuntu.com/ubuntu jammy/main amd64 libffi-dev amd64 3.4.2-4 [63.7 kB]
Get:56 http://au.archive.ubuntu.com/ubuntu jammy/main amd64 libyaml-dev amd64 0.2.2-1build2 [62.8 kB]
Fetched 60.5 MB in 18s (3,364 kB/s)              
Extracting templates from packages: 100%
Selecting previously unselected package libsigsegv
2:amd64.
(Reading database ... 183656 files and directories
 currently installed.)
Preparing to unpack .../00-libsigsegv2_2.13-1ubunt
u3_amd64.deb ...
Unpacking libsigsegv2:amd64 (2.13-1ubuntu3) ...
Selecting previously unselected package m4.
Preparing to unpack .../01-m4_1.4.18-5ubuntu2_amd6
4.deb ...
Unpacking m4 (1.4.18-5ubuntu2) ...
Selecting previously unselected package autoconf.
Preparing to unpack .../02-autoconf_2.71-2_all.deb
 ...
Unpacking autoconf (2.71-2) ...
Selecting previously unselected package autotools-
dev.
Preparing to unpack .../03-autotools-dev_20220109.
1_all.deb ...
Unpacking autotools-dev (20220109.1) ...
Selecting previously unselected package automake.
Preparing to unpack .../04-automake_1%3a1.16.5-1.3
_all.deb ...
Unpacking automake (1:1.16.5-1.3) ...
Selecting previously unselected package binutils-c
ommon:amd64.
Preparing to unpack .../05-binutils-common_2.38-4u
buntu2.8_amd64.deb ...
Unpacking binutils-common:amd64 (2.38-4ubuntu2.8) 
...
Selecting previously unselected package libbinutil
s:amd64.
Preparing to unpack .../06-libbinutils_2.38-4ubunt
u2.8_amd64.deb ...
Unpacking libbinutils:amd64 (2.38-4ubuntu2.8) ...
Selecting previously unselected package libctf-nob
fd0:amd64.
Preparing to unpack .../07-libctf-nobfd0_2.38-4ubu
ntu2.8_amd64.deb ...
Unpacking libctf-nobfd0:amd64 (2.38-4ubuntu2.8) ..
.
Selecting previously unselected package libctf0:am
d64.
Preparing to unpack .../08-libctf0_2.38-4ubuntu2.8
_amd64.deb ...
Unpacking libctf0:amd64 (2.38-4ubuntu2.8) ...
Selecting previously unselected package binutils-x
86-64-linux-gnu.
Preparing to unpack .../09-binutils-x86-64-linux-g
nu_2.38-4ubuntu2.8_amd64.deb ...
Unpacking binutils-x86-64-linux-gnu (2.38-4ubuntu2
.8) ...
Selecting previously unselected package binutils.
Preparing to unpack .../10-binutils_2.38-4ubuntu2.
8_amd64.deb ...
Unpacking binutils (2.38-4ubuntu2.8) ...
Selecting previously unselected package bison.
Preparing to unpack .../11-bison_2%3a3.8.2+dfsg-1b
uild1_amd64.deb ...
Unpacking bison (2:3.8.2+dfsg-1build1) ...
Selecting previously unselected package libc-dev-b
in.
Preparing to unpack .../12-libc-dev-bin_2.35-0ubun
tu3.10_amd64.deb ...
Unpacking libc-dev-bin (2.35-0ubuntu3.10) ...
Selecting previously unselected package linux-libc
-dev:amd64.
Preparing to unpack .../13-linux-libc-dev_5.15.0-1
51.161_amd64.deb ...
Unpacking linux-libc-dev:amd64 (5.15.0-151.161) ..
.
Selecting previously unselected package libcrypt-d
ev:amd64.
Preparing to unpack .../14-libcrypt-dev_1%3a4.4.27
-1_amd64.deb ...
Unpacking libcrypt-dev:amd64 (1:4.4.27-1) ...
Selecting previously unselected package rpcsvc-pro
to.
Preparing to unpack .../15-rpcsvc-proto_1.4.2-0ubu
ntu6_amd64.deb ...
Unpacking rpcsvc-proto (1.4.2-0ubuntu6) ...
Selecting previously unselected package libtirpc-d
ev:amd64.
Preparing to unpack .../16-libtirpc-dev_1.3.2-2ubu
ntu0.1_amd64.deb ...
Unpacking libtirpc-dev:amd64 (1.3.2-2ubuntu0.1) ..
.
Selecting previously unselected package libnsl-dev
:amd64.
Preparing to unpack .../17-libnsl-dev_1.3.0-2build
2_amd64.deb ...
Unpacking libnsl-dev:amd64 (1.3.0-2build2) ...
Selecting previously unselected package libc6-dev:
amd64.
Preparing to unpack .../18-libc6-dev_2.35-0ubuntu3
.10_amd64.deb ...
Unpacking libc6-dev:amd64 (2.35-0ubuntu3.10) ...
Selecting previously unselected package libcc1-0:a
md64.
Preparing to unpack .../19-libcc1-0_12.3.0-1ubuntu
1~22.04_amd64.deb ...
Unpacking libcc1-0:amd64 (12.3.0-1ubuntu1~22.04) .
..
Selecting previously unselected package libitm1:am
d64.
Preparing to unpack .../20-libitm1_12.3.0-1ubuntu1
~22.04_amd64.deb ...
Unpacking libitm1:amd64 (12.3.0-1ubuntu1~22.04) ..
.
Selecting previously unselected package libasan6:a
md64.
Preparing to unpack .../21-libasan6_11.4.0-1ubuntu
1~22.04_amd64.deb ...
Unpacking libasan6:amd64 (11.4.0-1ubuntu1~22.04) .
..
Selecting previously unselected package liblsan0:a
md64.
Preparing to unpack .../22-liblsan0_12.3.0-1ubuntu
1~22.04_amd64.deb ...
Unpacking liblsan0:amd64 (12.3.0-1ubuntu1~22.04) .
..
Selecting previously unselected package libtsan0:a
md64.
Preparing to unpack .../23-libtsan0_11.4.0-1ubuntu
1~22.04_amd64.deb ...
Unpacking libtsan0:amd64 (11.4.0-1ubuntu1~22.04) .
..
Selecting previously unselected package libubsan1:
amd64.
Preparing to unpack .../24-libubsan1_12.3.0-1ubunt
u1~22.04_amd64.deb ...
Unpacking libubsan1:amd64 (12.3.0-1ubuntu1~22.04) 
...
Selecting previously unselected package libgcc-11-
dev:amd64.
Preparing to unpack .../25-libgcc-11-dev_11.4.0-1u
buntu1~22.04_amd64.deb ...
Unpacking libgcc-11-dev:amd64 (11.4.0-1ubuntu1~22.
04) ...
Selecting previously unselected package gcc-11.
Preparing to unpack .../26-gcc-11_11.4.0-1ubuntu1~
22.04_amd64.deb ...
Unpacking gcc-11 (11.4.0-1ubuntu1~22.04) ...
Selecting previously unselected package gcc.
Preparing to unpack .../27-gcc_4%3a11.2.0-1ubuntu1
_amd64.deb ...
Unpacking gcc (4:11.2.0-1ubuntu1) ...
Selecting previously unselected package libstdc++-
11-dev:amd64.
Preparing to unpack .../28-libstdc++-11-dev_11.4.0
-1ubuntu1~22.04_amd64.deb ...
Unpacking libstdc++-11-dev:amd64 (11.4.0-1ubuntu1~
22.04) ...
Selecting previously unselected package g++-11.
Preparing to unpack .../29-g++-11_11.4.0-1ubuntu1~
22.04_amd64.deb ...
Unpacking g++-11 (11.4.0-1ubuntu1~22.04) ...
Selecting previously unselected package g++.
Preparing to unpack .../30-g++_4%3a11.2.0-1ubuntu1
_amd64.deb ...
Unpacking g++ (4:11.2.0-1ubuntu1) ...
Selecting previously unselected package make.
Preparing to unpack .../31-make_4.3-4.1build1_amd6
4.deb ...
Unpacking make (4.3-4.1build1) ...
Selecting previously unselected package libdpkg-pe
rl.
Preparing to unpack .../32-libdpkg-perl_1.21.1ubun
tu2.3_all.deb ...
Unpacking libdpkg-perl (1.21.1ubuntu2.3) ...
Selecting previously unselected package lto-disabl
ed-list.
Preparing to unpack .../33-lto-disabled-list_24_al
l.deb ...
Unpacking lto-disabled-list (24) ...
Selecting previously unselected package dpkg-dev.
Preparing to unpack .../34-dpkg-dev_1.21.1ubuntu2.
3_all.deb ...
Unpacking dpkg-dev (1.21.1ubuntu2.3) ...
Selecting previously unselected package build-esse
ntial.
Preparing to unpack .../35-build-essential_12.9ubu
ntu3_amd64.deb ...
Unpacking build-essential (12.9ubuntu3) ...
Selecting previously unselected package libfakeroo
t:amd64.
Preparing to unpack .../36-libfakeroot_1.28-1ubunt
u1_amd64.deb ...
Unpacking libfakeroot:amd64 (1.28-1ubuntu1) ...
Selecting previously unselected package fakeroot.
Preparing to unpack .../37-fakeroot_1.28-1ubuntu1_
amd64.deb ...
Unpacking fakeroot (1.28-1ubuntu1) ...
Selecting previously unselected package libalgorit
hm-diff-perl.
Preparing to unpack .../38-libalgorithm-diff-perl_
1.201-1_all.deb ...
Unpacking libalgorithm-diff-perl (1.201-1) ...
Selecting previously unselected package libalgorit
hm-diff-xs-perl.
Preparing to unpack .../39-libalgorithm-diff-xs-pe
rl_0.04-6build3_amd64.deb ...
Unpacking libalgorithm-diff-xs-perl (0.04-6build3)
 ...
Selecting previously unselected package libalgorit
hm-merge-perl.
Preparing to unpack .../40-libalgorithm-merge-perl
_0.08-3_all.deb ...
Unpacking libalgorithm-merge-perl (0.08-3) ...
Selecting previously unselected package libc-devto
ols.
Preparing to unpack .../41-libc-devtools_2.35-0ubu
ntu3.10_amd64.deb ...
Unpacking libc-devtools (2.35-0ubuntu3.10) ...
Selecting previously unselected package libfile-fc
ntllock-perl.
Preparing to unpack .../42-libfile-fcntllock-perl_
0.22-3build7_amd64.deb ...
Unpacking libfile-fcntllock-perl (0.22-3build7) ..
.
Selecting previously unselected package libgdbm-co
mpat-dev:amd64.
Preparing to unpack .../43-libgdbm-compat-dev_1.23
-1_amd64.deb ...
Unpacking libgdbm-compat-dev:amd64 (1.23-1) ...
Selecting previously unselected package libgdbm-de
v:amd64.
Preparing to unpack .../44-libgdbm-dev_1.23-1_amd6
4.deb ...
Unpacking libgdbm-dev:amd64 (1.23-1) ...
Selecting previously unselected package libgmpxx4l
dbl:amd64.
Preparing to unpack .../45-libgmpxx4ldbl_2%3a6.2.1
+dfsg-3ubuntu1_amd64.deb ...
Unpacking libgmpxx4ldbl:amd64 (2:6.2.1+dfsg-3ubunt
u1) ...
Selecting previously unselected package libgmp-dev
:amd64.
Preparing to unpack .../46-libgmp-dev_2%3a6.2.1+df
sg-3ubuntu1_amd64.deb ...
Unpacking libgmp-dev:amd64 (2:6.2.1+dfsg-3ubuntu1)
 ...
Selecting previously unselected package libncurses
-dev:amd64.
Preparing to unpack .../47-libncurses-dev_6.3-2ubu
ntu0.1_amd64.deb ...
Unpacking libncurses-dev:amd64 (6.3-2ubuntu0.1) ..
.
Selecting previously unselected package libncurses
5-dev:amd64.
Preparing to unpack .../48-libncurses5-dev_6.3-2ub
untu0.1_amd64.deb ...
Unpacking libncurses5-dev:amd64 (6.3-2ubuntu0.1) .
..
Selecting previously unselected package libreadlin
e-dev:amd64.
Preparing to unpack .../49-libreadline-dev_8.1.2-1
_amd64.deb ...
Unpacking libreadline-dev:amd64 (8.1.2-1) ...
Selecting previously unselected package libsqlite3
-dev:amd64.
Preparing to unpack .../50-libsqlite3-dev_3.37.2-2
ubuntu0.5_amd64.deb ...
Unpacking libsqlite3-dev:amd64 (3.37.2-2ubuntu0.5)
 ...
Selecting previously unselected package libssl-dev
:amd64.
Preparing to unpack .../51-libssl-dev_3.0.2-0ubunt
u1.19_amd64.deb ...
Unpacking libssl-dev:amd64 (3.0.2-0ubuntu1.19) ...
Selecting previously unselected package manpages-d
ev.
Preparing to unpack .../52-manpages-dev_5.10-1ubun
tu1_all.deb ...
Unpacking manpages-dev (5.10-1ubuntu1) ...
Selecting previously unselected package zlib1g-dev
:amd64.
Preparing to unpack .../53-zlib1g-dev_1%3a1.2.11.d
fsg-2ubuntu9.2_amd64.deb ...
Unpacking zlib1g-dev:amd64 (1:1.2.11.dfsg-2ubuntu9
.2) ...
Selecting previously unselected package libffi-dev
:amd64.
Preparing to unpack .../54-libffi-dev_3.4.2-4_amd6
4.deb ...
Unpacking libffi-dev:amd64 (3.4.2-4) ...
Selecting previously unselected package libyaml-de
v:amd64.
Preparing to unpack .../55-libyaml-dev_0.2.2-1buil
d2_amd64.deb ...
Unpacking libyaml-dev:amd64 (0.2.2-1build2) ...
Setting up manpages-dev (5.10-1ubuntu1) ...
Setting up lto-disabled-list (24) ...
Setting up libyaml-dev:amd64 (0.2.2-1build2) ...
Setting up libfile-fcntllock-perl (0.22-3build7) .
..
Setting up libalgorithm-diff-perl (1.201-1) ...
Setting up binutils-common:amd64 (2.38-4ubuntu2.8)
 ...
Setting up linux-libc-dev:amd64 (5.15.0-151.161) .
..
Setting up libctf-nobfd0:amd64 (2.38-4ubuntu2.8) .
..
Setting up libffi-dev:amd64 (3.4.2-4) ...
Setting up libfakeroot:amd64 (1.28-1ubuntu1) ...
Setting up libasan6:amd64 (11.4.0-1ubuntu1~22.04) 
...
Setting up fakeroot (1.28-1ubuntu1) ...
update-alternatives: using /usr/bin/fakeroot-sysv 
to provide /usr/bin/fakeroot (fakeroot) in auto mo
de
Setting up autotools-dev (20220109.1) ...
Setting up libtirpc-dev:amd64 (1.3.2-2ubuntu0.1) .
..
Setting up libgmpxx4ldbl:amd64 (2:6.2.1+dfsg-3ubun
tu1) ...
Setting up rpcsvc-proto (1.4.2-0ubuntu6) ...
Setting up make (4.3-4.1build1) ...
Setting up libsigsegv2:amd64 (2.13-1ubuntu3) ...
Setting up libssl-dev:amd64 (3.0.2-0ubuntu1.19) ..
.
Setting up libdpkg-perl (1.21.1ubuntu2.3) ...
Setting up libubsan1:amd64 (12.3.0-1ubuntu1~22.04)
 ...
Setting up libnsl-dev:amd64 (1.3.0-2build2) ...
Setting up libcrypt-dev:amd64 (1:4.4.27-1) ...
Setting up libbinutils:amd64 (2.38-4ubuntu2.8) ...
Setting up libc-dev-bin (2.35-0ubuntu3.10) ...
Setting up libalgorithm-diff-xs-perl (0.04-6build3
) ...
Setting up libcc1-0:amd64 (12.3.0-1ubuntu1~22.04) 
...
Setting up liblsan0:amd64 (12.3.0-1ubuntu1~22.04) 
...
Setting up libitm1:amd64 (12.3.0-1ubuntu1~22.04) .
..
Setting up libc-devtools (2.35-0ubuntu3.10) ...
Setting up libalgorithm-merge-perl (0.08-3) ...
Setting up libtsan0:amd64 (11.4.0-1ubuntu1~22.04) 
...
Setting up libctf0:amd64 (2.38-4ubuntu2.8) ...
Setting up libgmp-dev:amd64 (2:6.2.1+dfsg-3ubuntu1
) ...
Setting up m4 (1.4.18-5ubuntu2) ...
Setting up autoconf (2.71-2) ...
Setting up libgcc-11-dev:amd64 (11.4.0-1ubuntu1~22
.04) ...
Setting up bison (2:3.8.2+dfsg-1build1) ...
update-alternatives: using /usr/bin/bison.yacc to 
provide /usr/bin/yacc (yacc) in auto mode
Setting up libc6-dev:amd64 (2.35-0ubuntu3.10) ...
Setting up libgdbm-dev:amd64 (1.23-1) ...
Setting up binutils-x86-64-linux-gnu (2.38-4ubuntu
2.8) ...
Setting up automake (1:1.16.5-1.3) ...
update-alternatives: using /usr/bin/automake-1.16 
to provide /usr/bin/automake (automake) in auto mo
de
Setting up libncurses-dev:amd64 (6.3-2ubuntu0.1) .
..
Setting up libgdbm-compat-dev:amd64 (1.23-1) ...
Setting up binutils (2.38-4ubuntu2.8) ...
Setting up libreadline-dev:amd64 (8.1.2-1) ...
Setting up dpkg-dev (1.21.1ubuntu2.3) ...
Setting up libsqlite3-dev:amd64 (3.37.2-2ubuntu0.5
) ...
Setting up libstdc++-11-dev:amd64 (11.4.0-1ubuntu1
~22.04) ...
Setting up zlib1g-dev:amd64 (1:1.2.11.dfsg-2ubuntu
9.2) ...
Setting up gcc-11 (11.4.0-1ubuntu1~22.04) ...
Setting up libncurses5-dev:amd64 (6.3-2ubuntu0.1) 
...
Setting up g++-11 (11.4.0-1ubuntu1~22.04) ...
Setting up gcc (4:11.2.0-1ubuntu1) ...
Setting up g++ (4:11.2.0-1ubuntu1) ...
update-alternatives: using /usr/bin/g++ to provide
 /usr/bin/c++ (c++) in auto mode
Setting up build-essential (12.9ubuntu3) ...
Processing triggers for libc-bin (2.35-0ubuntu3.10
) ...
Processing triggers for man-db (2.10.2-1) ...
Processing triggers for install-info (6.8-4build1)
 ...
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~</b></font>$ git config --global user.name &quot;Dev Singh&quot;
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~</b></font>$ git config --global user.email &quot;devsingh.videos@gmail.com&quot;
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~</b></font>$ git config --global init.defaultBranch main
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~</b></font>$ git config --list
user.name=Dev Singh
user.email=devsingh.videos@gmail.com
init.defaultbranch=main
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~</b></font>$ git clone https://github.com/rbenv/rbenv.git ~/.rbenv
Cloning into &apos;/home/devs/.rbenv&apos;...
remote: Enumerating objects: 3395, done.
remote: Counting objects: 100% (289/289), done.
remote: Compressing objects: 100% (123/123), done.
remote: Total 3395 (delta 228), reused 167 (delta 166), pack-reused 3106 (from 4)
Receiving objects: 100% (3395/3395), 723.73 KiB | 3.01 MiB/s, done.
Resolving deltas: 100% (2086/2086), done.
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~</b></font>$ echo &apos;export PATH=&quot;$HOME/.rbenv/bin:$PATH&quot;&apos; &gt;&gt; ~/.bashrc
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~</b></font>$ echo &apos;eval &quot;$(rbenv init - bash)&quot;&apos; &gt;&gt; ~/.bashrc
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~</b></font>$ source ~/.bashrc
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~</b></font>$ git clone https://github.com/rbenv/ruby-build.git ~/.rbenv/plugins/ruby-build
Cloning into &apos;/home/devs/.rbenv/plugins/ruby-build&apos;...
remote: Enumerating objects: 17080, done.
remote: Counting objects: 100% (4697/4697), done.
remote: Compressing objects: 100% (291/291), done.
Receiving objects:  53% (9053/17080), 1.58 MiB | 3Receiving objects:  54% (9224/17080), 1.58 MiB | 3Receiving objects:  55% (9394/17080), 1.58 MiB | 3Receiving objects:  56% (9565/17080), 1.58 MiB | 3Receiving objects:  57% (9736/17080), 1.58 MiB | 3Receiving objects:  58% (9907/17080), 1.58 MiB | 3Receiving objects:  59% (10078/17080), 1.58 MiB | Receiving objects:  60% (10248/17080), 1.58 MiB | Receiving objects:  61% (10419/17080), 1.58 MiB | Receiving objects:  62% (10590/17080), 1.58 MiB | Receiving objects:  63% (10761/17080), 1.58 MiB | Receiving objects:  64% (10932/17080), 1.58 MiB | Receiving objects:  65% (11102/17080), 1.58 MiB | Receiving objects:  66% (11273/17080), 1.58 MiB | Receiving objects:  67% (11444/17080), 1.58 MiB | Receiving objects:  68% (11615/17080), 1.58 MiB | Receiving objects:  69% (11786/17080), 1.58 MiB | Receiving objects:  70% (11956/17080), 1.58 MiB | Receiving objects:  71% (12127/17080), 1.58 MiB | Receiving objects:  72% (12298/17080), 1.58 MiB | Receiving objects:  73% (12469/17080), 1.58 MiB | Receiving objects:  74% (12640/17080), 1.58 MiB | Receiving objects:  75% (12810/17080), 1.58 MiB | Receiving objects:  76% (12981/17080), 1.58 MiB | Receiving objects:  77% (13152/17080), 1.58 MiB | Receiving objects:  78% (13323/17080), 1.58 MiB | Receiving objects:  79% (13494/17080), 1.58 MiB | Receiving objects:  80% (13664/17080), 1.58 MiB | Receiving objects:  81% (13835/17080), 1.58 MiB | Receiving objects:  82% (14006/17080), 1.58 MiB | Receiving objects:  83% (14177/17080), 1.58 MiB | Receiving objects:  84% (14348/17080), 1.58 MiB | Receiving objects:  85% (14518/17080), 1.58 MiB | Receiving objects:  86% (14689/17080), 1.58 MiB | Receiving objects:  87% (14860/17080), 1.58 MiB | Receiving objects:  88% (15031/17080), 1.58 MiB | Receiving objects:  89% (15202/17080), 1.58 MiB | Receiving objects:  90% (15372/17080), 1.58 MiB | Receiving objects:  91% (15543/17080), 1.58 MiB | Receiving objects:  92% (15714/17080), 1.58 MiB | Receiving objects:  93% (15885/17080), 1.58 MiB | Receiving objects:  94% (16056/17080), 1.58 MiB | Receiving objects:  95% (16226/17080), 1.58 MiB | Receiving objects:  96% (16397/17080), 1.58 MiB | Receiving objects:  96% (16566/17080), 1.58 MiB | Receiving objects:  97% (16568/17080), 3.15 MiB | Receiving objects:  98% (16739/17080), 3.15 MiB | Receiving objects:  99% (16910/17080), 3.15 MiB | remote: Total 17080 (delta 4592), reused 4406 (delta 4406), pack-reused 12383 (from 4)
Receiving objects: 100% (17080/17080), 3.15 MiB | Receiving objects: 100% (17080/17080), 3.36 MiB | 3.14 MiB/s, done.
Resolving deltas: 100% (12062/12062), done.
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~</b></font>$ rbenv install 3.2.2
<b>==&gt; Downloading ruby-3.2.2.tar.gz...</b>
<font color="#2AA1B3">-&gt; curl -q -fL -o ruby-3.2.2.tar.gz https://cache.ruby-lang.org/pub/ruby/3.2/ruby-3.2.2.tar.gz</font>
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:-  0     0    0     0    0     0      0      0 --:-  0     0    0     0    0     0      0      0 --:-  0 19.5M    0 49134    0     0  19780      0  0:1 14 19.5M   14 2943k    0     0   845k      0  0:0 31 19.5M   31 6239k    0     0  1391k      0  0:0 47 19.5M   47 9535k    0     0  1739k      0  0:0 63 19.5M   63 12.4M    0     0  1966k      0  0:0 79 19.5M   79 15.5M    0     0  2127k      0  0:0 95 19.5M   95 18.7M    0     0  2257k      0  0:0100 19.5M  100 19.5M    0     0  2287k      0  0:00:08  0:00:08 --:--:-- 3233k
<b>==&gt; Installing ruby-3.2.2...</b>
<font color="#2AA1B3">-&gt; ./configure &quot;--prefix=$HOME/.rbenv/versions/3.2.2&quot; --enable-shared --with-ext=openssl,psych,+</font>
<font color="#2AA1B3">-&gt; make -j 2</font>
<font color="#2AA1B3">-&gt; make install</font>
<b>==&gt; Installed ruby-3.2.2 to /home/devs/.rbenv/versions/3.2.2</b>

<b>NOTE:</b><font color="#A2734C"> to activate this Ruby version as the new default, ru</font>n: <font color="#A2734C">rbenv global 3.2.2</font>
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~</b></font>$ rbenv global 3.2.2
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~</b></font>$ ruby -v
ruby 3.2.2 (2023-03-30 revision e51014f9c0) [x86_64-linux]
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~</b></font>$ curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.0/install.sh | bash
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:-100 14984  100 14984    0     0  20107      0 --:--:-- --:--:-- --:--:-- 20112
=&gt; Downloading nvm from git to &apos;/home/devs/.nvm&apos;
=&gt; Cloning into &apos;/home/devs/.nvm&apos;...
remote: Enumerating objects: 383, done.
remote: Counting objects: 100% (383/383), done.
remote: Compressing objects: 100% (326/326), done.
remote: Total 383 (delta 43), reused 178 (delta 29), pack-reused 0 (from 0)
Receiving objects: 100% (383/383), 392.12 KiB | 2.95 MiB/s, done.
Resolving deltas: 100% (43/43), done.
* <font color="#26A269">(HEAD detached at FETCH_HEAD)</font>
  master
=&gt; Compressing and cleaning up git repository

=&gt; Appending nvm source string to /home/devs/.bashrc
=&gt; Appending bash_completion source string to /home/devs/.bashrc
=&gt; Close and reopen your terminal to start using nvm or run the following to use it now:

export NVM_DIR=&quot;$HOME/.nvm&quot;
[ -s &quot;$NVM_DIR/nvm.sh&quot; ] &amp;&amp; \. &quot;$NVM_DIR/nvm.sh&quot;  # This loads nvm
[ -s &quot;$NVM_DIR/bash_completion&quot; ] &amp;&amp; \. &quot;$NVM_DIR/bash_completion&quot;  # This loads nvm bash_completion
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~</b></font>$ source ~/.bashrc
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~</b></font>$ nvm install 18
Downloading and installing node v18.20.8...
Downloading https://nodejs.org/dist/v18.20.8/node-v18.20.8-linux-x64.tar.xz...
########################################### 100.0%
Computing checksum with sha256sum
Checksums matched!
Now using node v18.20.8 (npm v10.8.2)
Creating default alias: <font color="#26A269">default</font> <font color="#5E5C64">-&gt;</font> <font color="#26A269">18</font> (<font color="#5E5C64">-&gt;</font> <font color="#26A269">v18.20.8</font>)
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~</b></font>$ nvm use 18
Now using node v18.20.8 (npm v10.8.2)
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~</b></font>$ nvm alias default 18
<font color="#26A269">default</font> <font color="#5E5C64">-&gt;</font> <font color="#26A269">18</font> (<font color="#5E5C64">-&gt;</font> <font color="#26A269">v18.20.8</font>)
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~</b></font>$ node -v
v18.20.8
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~</b></font>$ cd ~/Documents
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents</b></font>$ git clone https://github.com/devsgh-vid/devsgh-vid.github.io.git
Cloning into &apos;devsgh-vid.github.io&apos;...
warning: You appear to have cloned an empty repository.
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents</b></font>$ ls -la
total 12
drwxr-xr-x  3 devs devs 4096 Aug  7 16:28 <font color="#12488B"><b>.</b></font>
drwxr-x--- 21 devs devs 4096 Aug  7 16:16 <font color="#12488B"><b>..</b></font>
drwxrwxr-x  3 devs devs 4096 Aug  7 16:28 <font color="#12488B"><b>devsgh-vid.github.io</b></font>
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents</b></font>$ cd ~/Documents/devsgh-vid.github.io
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ curl -L https://github.com/cotes2020/jekyll-theme-chirpy/archive/refs/heads/master.zip -o chirpy.zip
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:-  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0
  0     0    0     0    0     0      0      0 --:-100  318k    0  318k    0     0   348k      0 --:--:-- --:--:-- --:--:-- 1072k
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ unzip chirpy.zip
Archive:  chirpy.zip
eaf5e574493776212be4ed14a2ddd2d60f7f4094
   creating: jekyll-theme-chirpy-master/
   creating: jekyll-theme-chirpy-master/.devcontainer/
  inflating: jekyll-theme-chirpy-master/.devcontainer/devcontainer.json  
  inflating: jekyll-theme-chirpy-master/.devcontainer/post-create.sh  
  inflating: jekyll-theme-chirpy-master/.editorconfig  
  inflating: jekyll-theme-chirpy-master/.gitattributes  
   creating: jekyll-theme-chirpy-master/.github/
   creating: jekyll-theme-chirpy-master/.github/DISCUSSION_TEMPLATE/
  inflating: jekyll-theme-chirpy-master/.github/DISCUSSION_TEMPLATE/general.yml  
  inflating: jekyll-theme-chirpy-master/.github/DISCUSSION_TEMPLATE/ideas.yml  
  inflating: jekyll-theme-chirpy-master/.github/DISCUSSION_TEMPLATE/q-a.yml  
  inflating: jekyll-theme-chirpy-master/.github/FUNDING.yml  
   creating: jekyll-theme-chirpy-master/.github/ISSUE_TEMPLATE/
  inflating: jekyll-theme-chirpy-master/.github/ISSUE_TEMPLATE/bug_report.yml  
  inflating: jekyll-theme-chirpy-master/.github/ISSUE_TEMPLATE/config.yml  
  inflating: jekyll-theme-chirpy-master/.github/ISSUE_TEMPLATE/feature_request.yml  
  inflating: jekyll-theme-chirpy-master/.github/PULL_REQUEST_TEMPLATE.md  
   creating: jekyll-theme-chirpy-master/.github/codeql/
 extracting: jekyll-theme-chirpy-master/.github/codeql/codeql-config.yml  
  inflating: jekyll-theme-chirpy-master/.github/dependabot.yml  
   creating: jekyll-theme-chirpy-master/.github/workflows/
  inflating: jekyll-theme-chirpy-master/.github/workflows/cd.yml  
  inflating: jekyll-theme-chirpy-master/.github/workflows/ci.yml  
  inflating: jekyll-theme-chirpy-master/.github/workflows/codeql.yml  
  inflating: jekyll-theme-chirpy-master/.github/workflows/commitlint.yml  
  inflating: jekyll-theme-chirpy-master/.github/workflows/lint-js.yml  
  inflating: jekyll-theme-chirpy-master/.github/workflows/lint-scss.yml  
  inflating: jekyll-theme-chirpy-master/.github/workflows/pr-filter.yml  
  inflating: jekyll-theme-chirpy-master/.github/workflows/publish.yml  
   creating: jekyll-theme-chirpy-master/.github/workflows/scripts/
  inflating: jekyll-theme-chirpy-master/.github/workflows/scripts/pr-filter.js  
  inflating: jekyll-theme-chirpy-master/.github/workflows/stale.yml  
   creating: jekyll-theme-chirpy-master/.github/workflows/starter/
  inflating: jekyll-theme-chirpy-master/.github/workflows/starter/pages-deploy.yml  
  inflating: jekyll-theme-chirpy-master/.gitignore  
  inflating: jekyll-theme-chirpy-master/.gitmodules  
   creating: jekyll-theme-chirpy-master/.husky/
  inflating: jekyll-theme-chirpy-master/.husky/commit-msg  
  inflating: jekyll-theme-chirpy-master/.markdownlint.json  
 extracting: jekyll-theme-chirpy-master/.nojekyll  
  inflating: jekyll-theme-chirpy-master/.stylelintrc.json  
   creating: jekyll-theme-chirpy-master/.vscode/
  inflating: jekyll-theme-chirpy-master/.vscode/extensions.json  
  inflating: jekyll-theme-chirpy-master/.vscode/settings.json  
  inflating: jekyll-theme-chirpy-master/.vscode/tasks.json  
  inflating: jekyll-theme-chirpy-master/Gemfile  
  inflating: jekyll-theme-chirpy-master/LICENSE  
  inflating: jekyll-theme-chirpy-master/README.md  
  inflating: jekyll-theme-chirpy-master/_config.yml  
   creating: jekyll-theme-chirpy-master/_data/
  inflating: jekyll-theme-chirpy-master/_data/authors.yml  
  inflating: jekyll-theme-chirpy-master/_data/contact.yml  
   creating: jekyll-theme-chirpy-master/_data/locales/
  inflating: jekyll-theme-chirpy-master/_data/locales/ar.yml  
  inflating: jekyll-theme-chirpy-master/_data/locales/bg-BG.yml  
  inflating: jekyll-theme-chirpy-master/_data/locales/ca-ES.yml  
  inflating: jekyll-theme-chirpy-master/_data/locales/cs-CZ.yml  
  inflating: jekyll-theme-chirpy-master/_data/locales/da-DK.yml  
  inflating: jekyll-theme-chirpy-master/_data/locales/de-DE.yml  
  inflating: jekyll-theme-chirpy-master/_data/locales/dv‑MV.yml  
  inflating: jekyll-theme-chirpy-master/_data/locales/el-GR.yml  
  inflating: jekyll-theme-chirpy-master/_data/locales/en.yml  
  inflating: jekyll-theme-chirpy-master/_data/locales/es-ES.yml  
  inflating: jekyll-theme-chirpy-master/_data/locales/fa-IR.yml  
  inflating: jekyll-theme-chirpy-master/_data/locales/fi-FI.yml  
  inflating: jekyll-theme-chirpy-master/_data/locales/fr-FR.yml  
  inflating: jekyll-theme-chirpy-master/_data/locales/hu-HU.yml  
  inflating: jekyll-theme-chirpy-master/_data/locales/id-ID.yml  
  inflating: jekyll-theme-chirpy-master/_data/locales/it-IT.yml  
  inflating: jekyll-theme-chirpy-master/_data/locales/ja-JP.yml  
  inflating: jekyll-theme-chirpy-master/_data/locales/ko-KR.yml  
  inflating: jekyll-theme-chirpy-master/_data/locales/ku-IQ.yml  
  inflating: jekyll-theme-chirpy-master/_data/locales/my-MM.yml  
  inflating: jekyll-theme-chirpy-master/_data/locales/nl-NL.yml  
  inflating: jekyll-theme-chirpy-master/_data/locales/ps‑AF.yml  
  inflating: jekyll-theme-chirpy-master/_data/locales/pt-BR.yml  
  inflating: jekyll-theme-chirpy-master/_data/locales/ru-RU.yml  
  inflating: jekyll-theme-chirpy-master/_data/locales/sl-SI.yml  
  inflating: jekyll-theme-chirpy-master/_data/locales/sv-SE.yml  
  inflating: jekyll-theme-chirpy-master/_data/locales/th.yml  
  inflating: jekyll-theme-chirpy-master/_data/locales/tr-TR.yml  
  inflating: jekyll-theme-chirpy-master/_data/locales/uk-UA.yml  
  inflating: jekyll-theme-chirpy-master/_data/locales/ur-PK.yml  
  inflating: jekyll-theme-chirpy-master/_data/locales/vi-VN.yml  
  inflating: jekyll-theme-chirpy-master/_data/locales/zh-CN.yml  
  inflating: jekyll-theme-chirpy-master/_data/locales/zh-TW.yml  
  inflating: jekyll-theme-chirpy-master/_data/media.yml  
   creating: jekyll-theme-chirpy-master/_data/origin/
  inflating: jekyll-theme-chirpy-master/_data/origin/basic.yml  
  inflating: jekyll-theme-chirpy-master/_data/origin/cors.yml  
  inflating: jekyll-theme-chirpy-master/_data/share.yml  
   creating: jekyll-theme-chirpy-master/_includes/
   creating: jekyll-theme-chirpy-master/_includes/analytics/
  inflating: jekyll-theme-chirpy-master/_includes/analytics/cloudflare.html  
  inflating: jekyll-theme-chirpy-master/_includes/analytics/fathom.html  
  inflating: jekyll-theme-chirpy-master/_includes/analytics/goatcounter.html  
  inflating: jekyll-theme-chirpy-master/_includes/analytics/google.html  
  inflating: jekyll-theme-chirpy-master/_includes/analytics/matomo.html  
  inflating: jekyll-theme-chirpy-master/_includes/analytics/umami.html  
  inflating: jekyll-theme-chirpy-master/_includes/comment.html  
   creating: jekyll-theme-chirpy-master/_includes/comments/
  inflating: jekyll-theme-chirpy-master/_includes/comments/disqus.html  
  inflating: jekyll-theme-chirpy-master/_includes/comments/giscus.html  
  inflating: jekyll-theme-chirpy-master/_includes/comments/utterances.html  
  inflating: jekyll-theme-chirpy-master/_includes/datetime.html  
   creating: jekyll-theme-chirpy-master/_includes/embed/
  inflating: jekyll-theme-chirpy-master/_includes/embed/audio.html  
  inflating: jekyll-theme-chirpy-master/_includes/embed/bilibili.html  
  inflating: jekyll-theme-chirpy-master/_includes/embed/twitch.html  
  inflating: jekyll-theme-chirpy-master/_includes/embed/video.html  
  inflating: jekyll-theme-chirpy-master/_includes/embed/youtube.html  
  inflating: jekyll-theme-chirpy-master/_includes/favicons.html  
  inflating: jekyll-theme-chirpy-master/_includes/footer.html  
  inflating: jekyll-theme-chirpy-master/_includes/head.html  
  inflating: jekyll-theme-chirpy-master/_includes/js-selector.html  
  inflating: jekyll-theme-chirpy-master/_includes/jsdelivr-combine.html  
  inflating: jekyll-theme-chirpy-master/_includes/lang.html  
  inflating: jekyll-theme-chirpy-master/_includes/language-alias.html  
  inflating: jekyll-theme-chirpy-master/_includes/media-url.html  
 extracting: jekyll-theme-chirpy-master/_includes/metadata-hook.html  
  inflating: jekyll-theme-chirpy-master/_includes/notification.html  
  inflating: jekyll-theme-chirpy-master/_includes/origin-type.html  
   creating: jekyll-theme-chirpy-master/_includes/pageviews/
  inflating: jekyll-theme-chirpy-master/_includes/pageviews/goatcounter.html  
  inflating: jekyll-theme-chirpy-master/_includes/post-description.html  
  inflating: jekyll-theme-chirpy-master/_includes/post-nav.html  
  inflating: jekyll-theme-chirpy-master/_includes/post-paginator.html  
  inflating: jekyll-theme-chirpy-master/_includes/post-sharing.html  
  inflating: jekyll-theme-chirpy-master/_includes/read-time.html  
  inflating: jekyll-theme-chirpy-master/_includes/refactor-content.html  
  inflating: jekyll-theme-chirpy-master/_includes/related-posts.html  
  inflating: jekyll-theme-chirpy-master/_includes/search-loader.html  
  inflating: jekyll-theme-chirpy-master/_includes/search-results.html  
  inflating: jekyll-theme-chirpy-master/_includes/sidebar.html  
  inflating: jekyll-theme-chirpy-master/_includes/toc-status.html  
  inflating: jekyll-theme-chirpy-master/_includes/toc.html  
  inflating: jekyll-theme-chirpy-master/_includes/topbar.html  
  inflating: jekyll-theme-chirpy-master/_includes/trending-tags.html  
  inflating: jekyll-theme-chirpy-master/_includes/update-list.html  
   creating: jekyll-theme-chirpy-master/_javascript/
  inflating: jekyll-theme-chirpy-master/_javascript/categories.js  
  inflating: jekyll-theme-chirpy-master/_javascript/commons.js  
  inflating: jekyll-theme-chirpy-master/_javascript/home.js  
  inflating: jekyll-theme-chirpy-master/_javascript/misc.js  
   creating: jekyll-theme-chirpy-master/_javascript/modules/
  inflating: jekyll-theme-chirpy-master/_javascript/modules/components.js  
   creating: jekyll-theme-chirpy-master/_javascript/modules/components/
  inflating: jekyll-theme-chirpy-master/_javascript/modules/components/back-to-top.js  
  inflating: jekyll-theme-chirpy-master/_javascript/modules/components/category-collapse.js  
  inflating: jekyll-theme-chirpy-master/_javascript/modules/components/clipboard.js  
  inflating: jekyll-theme-chirpy-master/_javascript/modules/components/img-loading.js  
  inflating: jekyll-theme-chirpy-master/_javascript/modules/components/img-popup.js  
  inflating: jekyll-theme-chirpy-master/_javascript/modules/components/locale-datetime.js  
  inflating: jekyll-theme-chirpy-master/_javascript/modules/components/mermaid.js  
  inflating: jekyll-theme-chirpy-master/_javascript/modules/components/mode-toggle.js  
  inflating: jekyll-theme-chirpy-master/_javascript/modules/components/search-display.js  
  inflating: jekyll-theme-chirpy-master/_javascript/modules/components/toc.js  
   creating: jekyll-theme-chirpy-master/_javascript/modules/components/toc/
  inflating: jekyll-theme-chirpy-master/_javascript/modules/components/toc/toc-desktop.js  
  inflating: jekyll-theme-chirpy-master/_javascript/modules/components/toc/toc-mobile.js  
  inflating: jekyll-theme-chirpy-master/_javascript/modules/components/tooltip-loader.js  
  inflating: jekyll-theme-chirpy-master/_javascript/modules/layouts.js  
   creating: jekyll-theme-chirpy-master/_javascript/modules/layouts/
  inflating: jekyll-theme-chirpy-master/_javascript/modules/layouts/basic.js  
  inflating: jekyll-theme-chirpy-master/_javascript/modules/layouts/sidebar.js  
  inflating: jekyll-theme-chirpy-master/_javascript/modules/layouts/topbar.js  
  inflating: jekyll-theme-chirpy-master/_javascript/page.js  
  inflating: jekyll-theme-chirpy-master/_javascript/post.js  
   creating: jekyll-theme-chirpy-master/_javascript/pwa/
  inflating: jekyll-theme-chirpy-master/_javascript/pwa/app.js  
  inflating: jekyll-theme-chirpy-master/_javascript/pwa/sw.js  
  inflating: jekyll-theme-chirpy-master/_javascript/theme.js  
   creating: jekyll-theme-chirpy-master/_layouts/
  inflating: jekyll-theme-chirpy-master/_layouts/archives.html  
  inflating: jekyll-theme-chirpy-master/_layouts/categories.html  
  inflating: jekyll-theme-chirpy-master/_layouts/category.html  
  inflating: jekyll-theme-chirpy-master/_layouts/compress.html  
  inflating: jekyll-theme-chirpy-master/_layouts/default.html  
  inflating: jekyll-theme-chirpy-master/_layouts/home.html  
  inflating: jekyll-theme-chirpy-master/_layouts/page.html  
  inflating: jekyll-theme-chirpy-master/_layouts/post.html  
  inflating: jekyll-theme-chirpy-master/_layouts/tag.html  
  inflating: jekyll-theme-chirpy-master/_layouts/tags.html  
   creating: jekyll-theme-chirpy-master/_plugins/
  inflating: jekyll-theme-chirpy-master/_plugins/posts-lastmod-hook.rb  
   creating: jekyll-theme-chirpy-master/_posts/
  inflating: jekyll-theme-chirpy-master/_posts/2019-08-08-text-and-typography.md  
  inflating: jekyll-theme-chirpy-master/_posts/2019-08-08-write-a-new-post.md  
  inflating: jekyll-theme-chirpy-master/_posts/2019-08-09-getting-started.md  
  inflating: jekyll-theme-chirpy-master/_posts/2019-08-11-customize-the-favicon.md  
   creating: jekyll-theme-chirpy-master/_sass/
   creating: jekyll-theme-chirpy-master/_sass/abstracts/
  inflating: jekyll-theme-chirpy-master/_sass/abstracts/_breakpoints.scss  
  inflating: jekyll-theme-chirpy-master/_sass/abstracts/_index.scss  
  inflating: jekyll-theme-chirpy-master/_sass/abstracts/_mixins.scss  
  inflating: jekyll-theme-chirpy-master/_sass/abstracts/_placeholders.scss  
  inflating: jekyll-theme-chirpy-master/_sass/abstracts/_variables.scss  
   creating: jekyll-theme-chirpy-master/_sass/base/
  inflating: jekyll-theme-chirpy-master/_sass/base/_base.scss  
  inflating: jekyll-theme-chirpy-master/_sass/base/_index.scss  
  inflating: jekyll-theme-chirpy-master/_sass/base/_reset.scss  
  inflating: jekyll-theme-chirpy-master/_sass/base/_syntax.scss  
  inflating: jekyll-theme-chirpy-master/_sass/base/_typography.scss  
   creating: jekyll-theme-chirpy-master/_sass/components/
  inflating: jekyll-theme-chirpy-master/_sass/components/_buttons.scss  
  inflating: jekyll-theme-chirpy-master/_sass/components/_index.scss  
  inflating: jekyll-theme-chirpy-master/_sass/components/_popups.scss  
   creating: jekyll-theme-chirpy-master/_sass/layout/
  inflating: jekyll-theme-chirpy-master/_sass/layout/_footer.scss  
  inflating: jekyll-theme-chirpy-master/_sass/layout/_index.scss  
  inflating: jekyll-theme-chirpy-master/_sass/layout/_panel.scss  
  inflating: jekyll-theme-chirpy-master/_sass/layout/_sidebar.scss  
  inflating: jekyll-theme-chirpy-master/_sass/layout/_topbar.scss  
  inflating: jekyll-theme-chirpy-master/_sass/main.bundle.scss  
  inflating: jekyll-theme-chirpy-master/_sass/main.scss  
   creating: jekyll-theme-chirpy-master/_sass/pages/
  inflating: jekyll-theme-chirpy-master/_sass/pages/_archives.scss  
  inflating: jekyll-theme-chirpy-master/_sass/pages/_categories.scss  
  inflating: jekyll-theme-chirpy-master/_sass/pages/_category-tag.scss  
  inflating: jekyll-theme-chirpy-master/_sass/pages/_home.scss  
  inflating: jekyll-theme-chirpy-master/_sass/pages/_index.scss  
  inflating: jekyll-theme-chirpy-master/_sass/pages/_post.scss  
  inflating: jekyll-theme-chirpy-master/_sass/pages/_search.scss  
  inflating: jekyll-theme-chirpy-master/_sass/pages/_tags.scss  
   creating: jekyll-theme-chirpy-master/_sass/themes/
  inflating: jekyll-theme-chirpy-master/_sass/themes/_dark.scss  
  inflating: jekyll-theme-chirpy-master/_sass/themes/_light.scss  
   creating: jekyll-theme-chirpy-master/_tabs/
  inflating: jekyll-theme-chirpy-master/_tabs/about.md  
  inflating: jekyll-theme-chirpy-master/_tabs/archives.md  
  inflating: jekyll-theme-chirpy-master/_tabs/categories.md  
  inflating: jekyll-theme-chirpy-master/_tabs/tags.md  
   creating: jekyll-theme-chirpy-master/assets/
  inflating: jekyll-theme-chirpy-master/assets/404.html  
   creating: jekyll-theme-chirpy-master/assets/css/
  inflating: jekyll-theme-chirpy-master/assets/css/jekyll-theme-chirpy.scss  
  inflating: jekyll-theme-chirpy-master/assets/feed.xml  
   creating: jekyll-theme-chirpy-master/assets/img/
   creating: jekyll-theme-chirpy-master/assets/img/favicons/
  inflating: jekyll-theme-chirpy-master/assets/img/favicons/android-chrome-192x192.png  
  inflating: jekyll-theme-chirpy-master/assets/img/favicons/android-chrome-512x512.png  
  inflating: jekyll-theme-chirpy-master/assets/img/favicons/apple-touch-icon.png  
  inflating: jekyll-theme-chirpy-master/assets/img/favicons/browserconfig.xml  
  inflating: jekyll-theme-chirpy-master/assets/img/favicons/favicon-16x16.png  
  inflating: jekyll-theme-chirpy-master/assets/img/favicons/favicon-32x32.png  
  inflating: jekyll-theme-chirpy-master/assets/img/favicons/favicon.ico  
  inflating: jekyll-theme-chirpy-master/assets/img/favicons/mstile-150x150.png  
  inflating: jekyll-theme-chirpy-master/assets/img/favicons/site.webmanifest  
   creating: jekyll-theme-chirpy-master/assets/js/
   creating: jekyll-theme-chirpy-master/assets/js/data/
  inflating: jekyll-theme-chirpy-master/assets/js/data/mathjax.js  
  inflating: jekyll-theme-chirpy-master/assets/js/data/search.json  
  inflating: jekyll-theme-chirpy-master/assets/js/data/swconf.js  
   creating: jekyll-theme-chirpy-master/assets/lib/
  inflating: jekyll-theme-chirpy-master/assets/robots.txt  
   creating: jekyll-theme-chirpy-master/docs/
  inflating: jekyll-theme-chirpy-master/docs/CHANGELOG.md  
  inflating: jekyll-theme-chirpy-master/docs/CODE_OF_CONDUCT.md  
  inflating: jekyll-theme-chirpy-master/docs/CONTRIBUTING.md  
  inflating: jekyll-theme-chirpy-master/docs/SECURITY.md  
  inflating: jekyll-theme-chirpy-master/eslint.config.js  
 extracting: jekyll-theme-chirpy-master/index.html  
  inflating: jekyll-theme-chirpy-master/jekyll-theme-chirpy.gemspec  
  inflating: jekyll-theme-chirpy-master/package.json  
  inflating: jekyll-theme-chirpy-master/purgecss.js  
  inflating: jekyll-theme-chirpy-master/rollup.config.js  
   creating: jekyll-theme-chirpy-master/tools/
  inflating: jekyll-theme-chirpy-master/tools/init.sh  
  inflating: jekyll-theme-chirpy-master/tools/release.sh  
  inflating: jekyll-theme-chirpy-master/tools/run.sh  
  inflating: jekyll-theme-chirpy-master/tools/test.dedddde<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ cp -r jekyll-theme-chirpy-master/_layouts .
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ cp -r jekyll-theme-chirpy-master/_includes .
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ cp -r jekyll-theme-chirpy-master/_sass .
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ cp -r jekyll-theme-chirpy-master/assets .
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ cp -r jekyll-theme-chirpy-master/_data .
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ cp -r jekyll-theme-chirpy-master/_plugins .
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ rm -rf chirpy.zip jekyll-theme-chirpy-master
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ cat &gt; Gemfile &lt;&lt; &apos;EOF&apos;
source &quot;https://rubygems.org&quot;
gem &quot;github-pages&quot;, &quot;~&gt; 228&quot;, group: :jekyll_plugins
gem &quot;jekyll-include-cache&quot;
EOF
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ cat &gt; _config.yml &lt;&lt; &apos;EOF&apos;
title: DevSGH CloudSec
description: Cloud Security &amp; DevOps Engineering
url: &quot;https://devsgh-vid.github.io&quot;
theme: jekyll-theme-chirpy
plugins:
  - jekyll-include-cache
  - jekyll-paginate
EOF
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ cat &gt; index.md &lt;&lt; &apos;EOF&apos;
---
layout: home
---
EOF
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ ls -l
total 36
drwxrwxr-x 6 devs devs 4096 Aug  7 16:31 <font color="#12488B"><b>assets</b></font>
-rw-rw-r-- 1 devs devs  189 Aug  7 16:33 _config.yml
drwxrwxr-x 4 devs devs 4096 Aug  7 16:31 <font color="#12488B"><b>_data</b></font>
-rw-rw-r-- 1 devs devs  110 Aug  7 16:32 Gemfile
drwxrwxr-x 6 devs devs 4096 Aug  7 16:31 <font color="#12488B"><b>_includes</b></font>
-rw-rw-r-- 1 devs devs   21 Aug  7 16:33 index.md
drwxrwxr-x 2 devs devs 4096 Aug  7 16:31 <font color="#12488B"><b>_layouts</b></font>
drwxrwxr-x 2 devs devs 4096 Aug  7 16:31 <font color="#12488B"><b>_plugins</b></font>
drwxrwxr-x 8 devs devs 4096 Aug  7 16:31 <font color="#12488B"><b>_sass</b></font>
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ bundle install
Fetching gem metadata from https://rubygems.org/...........
Resolving dependencies...
<font color="#26A269">Fetching base64 0.2.0</font>
<font color="#26A269">Fetching benchmark 0.4.1</font>
<font color="#26A269">Installing base64 0.2.0</font>
<font color="#26A269">Installing benchmark 0.4.1</font>
<font color="#26A269">Fetching bigdecimal 3.2.2</font>
<font color="#26A269">Fetching concurrent-ruby 1.3.5</font>
<font color="#26A269">Installing bigdecimal 3.2.2 with native extensions</font>
<font color="#26A269">Installing concurrent-ruby 1.3.5</font>
<font color="#26A269">Fetching connection_pool 2.5.3</font>
<font color="#26A269">Installing connection_pool 2.5.3</font>
<font color="#26A269">Fetching drb 2.2.3</font>
<font color="#26A269">Installing drb 2.2.3</font>
<font color="#26A269">Fetching logger 1.6.6</font>
<font color="#26A269">Installing logger 1.6.6</font>
<font color="#26A269">Fetching minitest 5.25.5</font>
<font color="#26A269">Installing minitest 5.25.5</font>
<font color="#26A269">Fetching securerandom 0.4.1</font>
<font color="#26A269">Installing securerandom 0.4.1</font>
<font color="#26A269">Fetching uri 1.0.3</font>
<font color="#26A269">Installing uri 1.0.3</font>
<font color="#26A269">Fetching public_suffix 4.0.7</font>
<font color="#26A269">Installing public_suffix 4.0.7</font>
Using bundler 2.4.10
<font color="#26A269">Fetching coffee-script-source 1.11.1</font>
<font color="#26A269">Installing coffee-script-source 1.11.1</font>
<font color="#26A269">Fetching execjs 2.10.0</font>
<font color="#26A269">Installing execjs 2.10.0</font>
<font color="#26A269">Fetching colorator 1.1.0</font>
<font color="#26A269">Installing colorator 1.1.0</font>
<font color="#26A269">Fetching commonmarker 0.23.11</font>
<font color="#26A269">Installing commonmarker 0.23.11 with native extensions</font>
<font color="#26A269">Fetching simpleidn 0.2.3</font>
<font color="#26A269">Installing simpleidn 0.2.3</font>
<font color="#26A269">Fetching eventmachine 1.2.7</font>
<font color="#26A269">Installing eventmachine 1.2.7 with native extensions</font>
<font color="#26A269">Fetching http_parser.rb 0.8.0</font>
<font color="#26A269">Installing http_parser.rb 0.8.0 with native extensions</font>
<font color="#26A269">Fetching ffi 1.17.2 (x86_64-linux-gnu)</font>
<font color="#26A269">Installing ffi 1.17.2 (x86_64-linux-gnu)</font>
<font color="#26A269">Fetching json 2.13.2</font>
<font color="#26A269">Installing json 2.13.2 with native extensions</font>
<font color="#26A269">Fetching forwardable-extended 2.6.0</font>
<font color="#26A269">Installing forwardable-extended 2.6.0</font>
<font color="#26A269">Fetching gemoji 3.0.1</font>
<font color="#26A269">Installing gemoji 3.0.1</font>
<font color="#26A269">Fetching rb-fsevent 0.11.2</font>
<font color="#26A269">Installing rb-fsevent 0.11.2</font>
<font color="#26A269">Fetching rexml 3.4.1</font>
<font color="#26A269">Installing rexml 3.4.1</font>
<font color="#26A269">Fetching liquid 4.0.4</font>
<font color="#26A269">Installing liquid 4.0.4</font>
<font color="#26A269">Fetching mercenary 0.3.6</font>
<font color="#26A269">Installing mercenary 0.3.6</font>
<font color="#26A269">Fetching rouge 3.26.0</font>
<font color="#26A269">Installing rouge 3.26.0</font>
<font color="#26A269">Fetching safe_yaml 1.0.5</font>
<font color="#26A269">Installing safe_yaml 1.0.5</font>
<font color="#26A269">Fetching racc 1.8.1</font>
<font color="#26A269">Installing racc 1.8.1 with native extensions</font>
<font color="#26A269">Fetching jekyll-paginate 1.1.0</font>
<font color="#26A269">Installing jekyll-paginate 1.1.0</font>
<font color="#26A269">Fetching rubyzip 2.4.1</font>
<font color="#26A269">Installing rubyzip 2.4.1</font>
<font color="#26A269">Fetching jekyll-swiss 1.0.0</font>
<font color="#26A269">Installing jekyll-swiss 1.0.0</font>
<font color="#26A269">Fetching unicode-display_width 1.8.0</font>
<font color="#26A269">Installing unicode-display_width 1.8.0</font>
<font color="#26A269">Fetching i18n 1.14.7</font>
<font color="#26A269">Installing i18n 1.14.7</font>
<font color="#26A269">Fetching tzinfo 2.0.6</font>
<font color="#26A269">Installing tzinfo 2.0.6</font>
<font color="#26A269">Fetching net-http 0.6.0</font>
<font color="#26A269">Installing net-http 0.6.0</font>
<font color="#26A269">Fetching addressable 2.8.7</font>
<font color="#26A269">Installing addressable 2.8.7</font>
<font color="#26A269">Fetching coffee-script 2.4.1</font>
<font color="#26A269">Installing coffee-script 2.4.1</font>
<font color="#26A269">Fetching jekyll-commonmark 1.4.0</font>
<font color="#26A269">Installing jekyll-commonmark 1.4.0</font>
<font color="#26A269">Fetching dnsruby 1.72.4</font>
<font color="#26A269">Installing dnsruby 1.72.4</font>
<font color="#26A269">Fetching ethon 0.16.0</font>
<font color="#26A269">Installing ethon 0.16.0</font>
<font color="#26A269">Fetching rb-inotify 0.11.1</font>
<font color="#26A269">Installing rb-inotify 0.11.1</font>
<font color="#26A269">Fetching pathutil 0.16.2</font>
<font color="#26A269">Installing pathutil 0.16.2</font>
<font color="#26A269">Fetching kramdown 2.3.2</font>
<font color="#26A269">Installing kramdown 2.3.2</font>
<font color="#26A269">Fetching nokogiri 1.18.9 (x86_64-linux-gnu)</font>
<font color="#26A269">Installing nokogiri 1.18.9 (x86_64-linux-gnu)</font>
<font color="#26A269">Fetching terminal-table 1.8.0</font>
<font color="#26A269">Installing terminal-table 1.8.0</font>
<font color="#26A269">Fetching activesupport 8.0.2</font>
<font color="#26A269">Installing activesupport 8.0.2</font>
<font color="#26A269">Fetching faraday-net_http 3.4.1</font>
<font color="#26A269">Installing faraday-net_http 3.4.1</font>
<font color="#26A269">Fetching jekyll-coffeescript 1.1.1</font>
<font color="#26A269">Installing jekyll-coffeescript 1.1.1</font>
<font color="#26A269">Fetching typhoeus 1.4.1</font>
<font color="#26A269">Installing typhoeus 1.4.1</font>
<font color="#26A269">Fetching sass-listen 4.0.0</font>
<font color="#26A269">Installing sass-listen 4.0.0</font>
<font color="#26A269">Fetching listen 3.9.0</font>
<font color="#26A269">Installing listen 3.9.0</font>
<font color="#26A269">Fetching kramdown-parser-gfm 1.1.0</font>
<font color="#26A269">Installing kramdown-parser-gfm 1.1.0</font>
<font color="#26A269">Fetching html-pipeline 2.14.3</font>
<font color="#26A269">Installing html-pipeline 2.14.3</font>
<font color="#26A269">Fetching faraday 2.13.4</font>
<font color="#26A269">Installing faraday 2.13.4</font>
<font color="#26A269">Fetching sass 3.7.4</font>
<font color="#26A269">Installing sass 3.7.4</font>
<font color="#26A269">Fetching jekyll-watch 2.2.1</font>
<font color="#26A269">Installing jekyll-watch 2.2.1</font>
<font color="#26A269">Fetching sawyer 0.9.2</font>
<font color="#26A269">Installing sawyer 0.9.2</font>
<font color="#26A269">Fetching jekyll-sass-converter 1.5.2</font>
<font color="#26A269">Installing jekyll-sass-converter 1.5.2</font>
<font color="#26A269">Fetching octokit 4.25.1</font>
<font color="#26A269">Installing octokit 4.25.1</font>
<font color="#26A269">Fetching github-pages-health-check 1.17.9</font>
<font color="#26A269">Installing github-pages-health-check 1.17.9</font>
<font color="#26A269">Fetching jekyll-gist 1.5.0</font>
<font color="#26A269">Installing jekyll-gist 1.5.0</font>
<font color="#26A269">Fetching em-websocket 0.5.3</font>
<font color="#26A269">Installing em-websocket 0.5.3</font>
<font color="#26A269">Fetching jekyll 3.9.3</font>
<font color="#26A269">Installing jekyll 3.9.3</font>
<font color="#26A269">Fetching jekyll-avatar 0.7.0</font>
<font color="#26A269">Fetching jekyll-commonmark-ghpages 0.4.0</font>
<font color="#26A269">Installing jekyll-commonmark-ghpages 0.4.0</font>
<font color="#26A269">Fetching jekyll-default-layout 0.1.4</font>
<font color="#26A269">Installing jekyll-avatar 0.7.0</font>
<font color="#26A269">Fetching jekyll-feed 0.15.1</font>
<font color="#26A269">Installing jekyll-default-layout 0.1.4</font>
<font color="#26A269">Fetching jekyll-github-metadata 2.13.0</font>
<font color="#26A269">Installing jekyll-github-metadata 2.13.0</font>
<font color="#26A269">Fetching jekyll-include-cache 0.2.1</font>
<font color="#26A269">Installing jekyll-include-cache 0.2.1</font>
<font color="#26A269">Fetching jekyll-mentions 1.6.0</font>
<font color="#26A269">Installing jekyll-mentions 1.6.0</font>
<font color="#26A269">Fetching jekyll-optional-front-matter 0.3.2</font>
<font color="#26A269">Installing jekyll-optional-front-matter 0.3.2</font>
<font color="#26A269">Fetching jekyll-readme-index 0.3.0</font>
<font color="#26A269">Installing jekyll-readme-index 0.3.0</font>
<font color="#26A269">Fetching jekyll-redirect-from 0.16.0</font>
<font color="#26A269">Installing jekyll-redirect-from 0.16.0</font>
<font color="#26A269">Installing jekyll-feed 0.15.1</font>
<font color="#26A269">Fetching jekyll-relative-links 0.6.1</font>
<font color="#26A269">Fetching jekyll-remote-theme 0.4.3</font>
<font color="#26A269">Installing jekyll-relative-links 0.6.1</font>
<font color="#26A269">Fetching jekyll-seo-tag 2.8.0</font>
<font color="#26A269">Installing jekyll-remote-theme 0.4.3</font>
<font color="#26A269">Fetching jekyll-sitemap 1.4.0</font>
<font color="#26A269">Installing jekyll-seo-tag 2.8.0</font>
<font color="#26A269">Fetching jekyll-titles-from-headings 0.5.3</font>
<font color="#26A269">Installing jekyll-sitemap 1.4.0</font>
<font color="#26A269">Installing jekyll-titles-from-headings 0.5.3</font>
<font color="#26A269">Fetching jemoji 0.12.0</font>
<font color="#26A269">Fetching jekyll-theme-architect 0.2.0</font>
<font color="#26A269">Installing jekyll-theme-architect 0.2.0</font>
<font color="#26A269">Fetching jekyll-theme-cayman 0.2.0</font>
<font color="#26A269">Installing jekyll-theme-cayman 0.2.0</font>
<font color="#26A269">Fetching jekyll-theme-dinky 0.2.0</font>
<font color="#26A269">Installing jekyll-theme-dinky 0.2.0</font>
<font color="#26A269">Fetching jekyll-theme-hacker 0.2.0</font>
<font color="#26A269">Installing jekyll-theme-hacker 0.2.0</font>
<font color="#26A269">Fetching jekyll-theme-leap-day 0.2.0</font>
<font color="#26A269">Installing jemoji 0.12.0</font>
<font color="#26A269">Fetching jekyll-theme-merlot 0.2.0</font>
<font color="#26A269">Installing jekyll-theme-leap-day 0.2.0</font>
<font color="#26A269">Fetching jekyll-theme-midnight 0.2.0</font>
<font color="#26A269">Installing jekyll-theme-merlot 0.2.0</font>
<font color="#26A269">Fetching jekyll-theme-minimal 0.2.0</font>
<font color="#26A269">Installing jekyll-theme-minimal 0.2.0</font>
<font color="#26A269">Fetching jekyll-theme-modernist 0.2.0</font>
<font color="#26A269">Installing jekyll-theme-modernist 0.2.0</font>
<font color="#26A269">Fetching jekyll-theme-primer 0.6.0</font>
<font color="#26A269">Installing jekyll-theme-primer 0.6.0</font>
<font color="#26A269">Fetching jekyll-theme-slate 0.2.0</font>
<font color="#26A269">Installing jekyll-theme-slate 0.2.0</font>
<font color="#26A269">Fetching jekyll-theme-tactile 0.2.0</font>
<font color="#26A269">Installing jekyll-theme-tactile 0.2.0</font>
<font color="#26A269">Fetching jekyll-theme-time-machine 0.2.0</font>
<font color="#26A269">Installing jekyll-theme-time-machine 0.2.0</font>
<font color="#26A269">Fetching minima 2.5.1</font>
<font color="#26A269">Installing minima 2.5.1</font>
<font color="#26A269">Installing jekyll-theme-midnight 0.2.0</font>
<font color="#26A269">Fetching github-pages 228</font>
<font color="#26A269">Installing github-pages 228</font>
<font color="#26A269">Bundle complete! 2 Gemfile dependencies, 96 gems now installed.</font>
<font color="#26A269">Use `bundle info [gemname]` to see where a bundled gem is installed.</font>
<font color="#26A269">Post-install message from dnsruby:</font>
Installing dnsruby...
  For issues and source code: https://github.com/alexdalitz/dnsruby
  For general discussion (please tell us how you use dnsruby): https://groups.google.com/forum/#!forum/dnsruby
<font color="#26A269">Post-install message from sass:</font>

Ruby Sass has reached end-of-life and should no longer be used.

* If you use Sass as a command-line tool, we recommend using Dart Sass, the new
  primary implementation: https://sass-lang.com/install

* If you use Sass as a plug-in for a Ruby web framework, we recommend using the
  sassc gem: https://github.com/sass/sassc-ruby#readme

* For more details, please refer to the Sass blog:
  https://sass-lang.com/blog/posts/7828841

<font color="#26A269">Post-install message from html-pipeline:</font>
-------------------------------------------------
Thank you for installing html-pipeline!
You must bundle Filter gem dependencies.
See html-pipeline README.md for more details.
https://github.com/jch/html-pipeline#dependencies
-------------------------------------------------
<font color="#26A269">Post-install message from rubyzip:</font>
RubyZip 3.0 is coming!
**********************

The public API of some Rubyzip classes has been modernized to use named
parameters for optional arguments. Please check your usage of the
following classes:
  * `Zip::File`
  * `Zip::Entry`
  * `Zip::InputStream`
  * `Zip::OutputStream`
  * `Zip::DOSTime`

Run your test suite with the `RUBYZIP_V3_API_WARN` environment
variable set to see warnings about usage of the old API. This will
help you to identify any changes that you need to make to your code.
See https://github.com/rubyzip/rubyzip/wiki/Updating-to-version-3.x for
more information.

Please ensure that your Gemfiles and .gemspecs are suitably restrictive
to avoid an unexpected breakage when 3.0 is released (e.g. ~&gt; 2.3.0).
See https://github.com/rubyzip/rubyzip for details. The Changelog also
lists other enhancements and bugfixes that have been implemented since
version 2.3.0.
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ bundle exec jekyll serve --livereload
Configuration file: /home/devs/Documents/devsgh-vid.github.io/_config.yml
jekyll 3.9.3 | Error:  The jekyll-theme-chirpy theme could not be found.
/home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/theme.rb:84:in `rescue in gemspec&apos;: <b>The jekyll-theme-chirpy theme could not be found. (</b><u style="text-decoration-style:single"><b>Jekyll::Errors::MissingDependencyException</b></u><b>)</b>
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/theme.rb:81:in `gemspec&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/theme.rb:19:in `root&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/theme.rb:12:in `initialize&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/site.rb:439:in `new&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/site.rb:439:in `configure_theme&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/site.rb:55:in `config=&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/site.rb:23:in `initialize&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/commands/build.rb:30:in `new&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/commands/build.rb:30:in `process&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/commands/serve.rb:93:in `block in start&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/commands/serve.rb:93:in `each&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/commands/serve.rb:93:in `start&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/commands/serve.rb:75:in `block (2 levels) in init_with_program&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.3.6/lib/mercenary/command.rb:220:in `block in execute&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.3.6/lib/mercenary/command.rb:220:in `each&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.3.6/lib/mercenary/command.rb:220:in `execute&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.3.6/lib/mercenary/program.rb:42:in `go&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.3.6/lib/mercenary.rb:19:in `program&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/exe/jekyll:15:in `&lt;top (required)&gt;&apos;
	from /home/devs/.rbenv/versions/3.2.2/bin/jekyll:25:in `load&apos;
	from /home/devs/.rbenv/versions/3.2.2/bin/jekyll:25:in `&lt;top (required)&gt;&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli/exec.rb:58:in `load&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli/exec.rb:58:in `kernel_load&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli/exec.rb:23:in `run&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli.rb:492:in `exec&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/vendor/thor/lib/thor/command.rb:27:in `run&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/vendor/thor/lib/thor/invocation.rb:127:in `invoke_command&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/vendor/thor/lib/thor.rb:392:in `dispatch&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli.rb:34:in `dispatch&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/vendor/thor/lib/thor/base.rb:485:in `start&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli.rb:28:in `start&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.10/libexec/bundle:45:in `block in &lt;top (required)&gt;&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/friendly_errors.rb:117:in `with_friendly_errors&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.10/libexec/bundle:33:in `&lt;top (required)&gt;&apos;
	from /home/devs/.rbenv/versions/3.2.2/bin/bundle:25:in `load&apos;
	from /home/devs/.rbenv/versions/3.2.2/bin/bundle:25:in `&lt;main&gt;&apos;
/home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/rubygems/dependency.rb:314:in `to_specs&apos;: <b>Could not find &apos;jekyll-theme-chirpy&apos; (&gt;= 0) among 156 total gem(s) (</b><u style="text-decoration-style:single"><b>Gem::MissingSpecError</b></u><b>)</b>
<b>Checked in &apos;GEM_PATH=/home/devs/.local/share/gem/ruby/3.2.0:/home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0&apos; , execute `gem env` for more information</b>
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/rubygems/dependency.rb:326:in `to_spec&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/rubygems/specification.rb:1021:in `find_by_name&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/theme.rb:82:in `gemspec&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/theme.rb:19:in `root&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/theme.rb:12:in `initialize&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/site.rb:439:in `new&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/site.rb:439:in `configure_theme&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/site.rb:55:in `config=&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/site.rb:23:in `initialize&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/commands/build.rb:30:in `new&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/commands/build.rb:30:in `process&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/commands/serve.rb:93:in `block in start&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/commands/serve.rb:93:in `each&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/commands/serve.rb:93:in `start&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/commands/serve.rb:75:in `block (2 levels) in init_with_program&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.3.6/lib/mercenary/command.rb:220:in `block in execute&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.3.6/lib/mercenary/command.rb:220:in `each&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.3.6/lib/mercenary/command.rb:220:in `execute&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.3.6/lib/mercenary/program.rb:42:in `go&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.3.6/lib/mercenary.rb:19:in `program&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/exe/jekyll:15:in `&lt;top (required)&gt;&apos;
	from /home/devs/.rbenv/versions/3.2.2/bin/jekyll:25:in `load&apos;
	from /home/devs/.rbenv/versions/3.2.2/bin/jekyll:25:in `&lt;top (required)&gt;&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli/exec.rb:58:in `load&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli/exec.rb:58:in `kernel_load&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli/exec.rb:23:in `run&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli.rb:492:in `exec&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/vendor/thor/lib/thor/command.rb:27:in `run&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/vendor/thor/lib/thor/invocation.rb:127:in `invoke_command&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/vendor/thor/lib/thor.rb:392:in `dispatch&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli.rb:34:in `dispatch&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/vendor/thor/lib/thor/base.rb:485:in `start&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli.rb:28:in `start&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.10/libexec/bundle:45:in `block in &lt;top (required)&gt;&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/friendly_errors.rb:117:in `with_friendly_errors&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.10/libexec/bundle:33:in `&lt;top (required)&gt;&apos;
	from /home/devs/.rbenv/versions/3.2.2/bin/bundle:25:in `load&apos;
	from /home/devs/.rbenv/versions/3.2.2/bin/bundle:25:in `&lt;main&gt;&apos;
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ nano _config.yml
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ nano Gemfile
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ bundle install
Fetching gem metadata from https://rubygems.org/.........
Resolving dependencies...
Using benchmark 0.4.1
Using base64 0.2.0
Using concurrent-ruby 1.3.5
Using connection_pool 2.5.3
Using bigdecimal 3.2.2
Using logger 1.6.6
Using drb 2.2.3
Using securerandom 0.4.1
Using minitest 5.25.5
Using uri 1.0.3
Using bundler 2.4.10
Using public_suffix 4.0.7
Using coffee-script-source 1.11.1
Using colorator 1.1.0
Using commonmarker 0.23.11
Using execjs 2.10.0
Using simpleidn 0.2.3
Using http_parser.rb 0.8.0
Using eventmachine 1.2.7
Using json 2.13.2
Using ffi 1.17.2 (x86_64-linux-gnu)
Using forwardable-extended 2.6.0
Using rb-fsevent 0.11.2
Using rexml 3.4.1
Using gemoji 3.0.1
Using mercenary 0.3.6
Using rouge 3.26.0
Using safe_yaml 1.0.5
Using racc 1.8.1
Using jekyll-paginate 1.1.0
Using rubyzip 2.4.1
Using jekyll-swiss 1.0.0
Using unicode-display_width 1.8.0
Using i18n 1.14.7
Using tzinfo 2.0.6
Using addressable 2.8.7
Using net-http 0.6.0
Using coffee-script 2.4.1
Using dnsruby 1.72.4
Using jekyll-commonmark 1.4.0
Using em-websocket 0.5.3
Using ethon 0.16.0
Using rb-inotify 0.11.1
Using liquid 4.0.4
Using pathutil 0.16.2
Using activesupport 8.0.2
Using faraday-net_http 3.4.1
Using sass-listen 4.0.0
Using typhoeus 1.4.1
Using kramdown 2.3.2
Using jekyll-coffeescript 1.1.1
Using nokogiri 1.18.9 (x86_64-linux-gnu)
Using terminal-table 1.8.0
Using faraday 2.13.4
Using sass 3.7.4
Using listen 3.9.0
Using jekyll-sass-converter 1.5.2
Using sawyer 0.9.2
Using kramdown-parser-gfm 1.1.0
Using jekyll-watch 2.2.1
Using html-pipeline 2.14.3
Using octokit 4.25.1
Using jekyll 3.9.3
Using jekyll-gist 1.5.0
Using jekyll-avatar 0.7.0
Using jekyll-commonmark-ghpages 0.4.0
Using github-pages-health-check 1.17.9
Using jekyll-feed 0.15.1
Using jekyll-default-layout 0.1.4
Using jekyll-include-cache 0.2.1
Using jekyll-github-metadata 2.13.0
Using jekyll-mentions 1.6.0
Using jekyll-readme-index 0.3.0
Using jekyll-redirect-from 0.16.0
Using jekyll-relative-links 0.6.1
Using jekyll-optional-front-matter 0.3.2
Using jekyll-seo-tag 2.8.0
Using jekyll-sitemap 1.4.0
Using jekyll-titles-from-headings 0.5.3
Using jekyll-remote-theme 0.4.3
Using jemoji 0.12.0
Using jekyll-theme-architect 0.2.0
Using jekyll-theme-cayman 0.2.0
Using jekyll-theme-dinky 0.2.0
Using jekyll-theme-hacker 0.2.0
Using jekyll-theme-leap-day 0.2.0
Using jekyll-theme-merlot 0.2.0
Using jekyll-theme-midnight 0.2.0
Using jekyll-theme-minimal 0.2.0
<font color="#26A269">Fetching jekyll-archives 2.3.0</font>
Using jekyll-theme-modernist 0.2.0
Using jekyll-theme-primer 0.6.0
Using jekyll-theme-slate 0.2.0
Using jekyll-theme-tactile 0.2.0
Using jekyll-theme-time-machine 0.2.0
Using minima 2.5.1
Using github-pages 228
<font color="#26A269">Installing jekyll-archives 2.3.0</font>
<font color="#26A269">Bundle complete! 6 Gemfile dependencies, 97 gems now installed.</font>
<font color="#26A269">Use `bundle info [gemname]` to see where a bundled gem is installed.</font>
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ bundle exec jekyll serve --livereload
Configuration file: /home/devs/Documents/devsgh-vid.github.io/_config.yml
To use retry middleware with Faraday v2.0+, install `faraday-retry` gem
<font color="#A2734C">   GitHub Metadata: No GitHub API authentication could be found. Some fields may be missing or have incorrect data.</font>
fatal: ambiguous argument &apos;HEAD&apos;: unknown revision or path not in the working tree.
Use &apos;--&apos; to separate paths from revisions, like this:
&apos;git &lt;command&gt; [&lt;revision&gt;...] -- [&lt;file&gt;...]&apos;
            Source: /home/devs/Documents/devsgh-vid.github.io
       Destination: /home/devs/Documents/devsgh-vid.github.io/_site
 Incremental build: disabled. Enable with --incremental
      Generating... 
       Jekyll Feed: Generating feed for posts
<font color="#C01C28">  Liquid Exception: Liquid syntax error (line 4): Expected end_of_string but found id in /_layouts/home.html</font>
jekyll 3.9.3 | Error:  Liquid syntax error (line 4): Expected end_of_string but found id
/home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/liquid-4.0.4/lib/liquid/parser.rb:16:in `consume&apos;: <b>Liquid syntax error (line 4): Expected end_of_string but found id (</b><u style="text-decoration-style:single"><b>Liquid::SyntaxError</b></u><b>)</b>
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/filters.rb:369:in `parse_condition&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/filters.rb:200:in `where_exp&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/liquid-4.0.4/lib/liquid/strainer.rb:56:in `invoke&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/liquid-4.0.4/lib/liquid/context.rb:86:in `invoke&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/liquid-4.0.4/lib/liquid/variable.rb:84:in `block in render&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/liquid-4.0.4/lib/liquid/variable.rb:82:in `each&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/liquid-4.0.4/lib/liquid/variable.rb:82:in `inject&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/liquid-4.0.4/lib/liquid/variable.rb:82:in `render&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/liquid-4.0.4/lib/liquid/tags/assign.rb:26:in `render&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/liquid-4.0.4/lib/liquid/block_body.rb:103:in `render_node_to_output&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/liquid-4.0.4/lib/liquid/block_body.rb:91:in `render&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/liquid-4.0.4/lib/liquid/template.rb:206:in `block in render&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/liquid-4.0.4/lib/liquid/template.rb:240:in `with_profiling&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/liquid-4.0.4/lib/liquid/template.rb:205:in `render&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/liquid-4.0.4/lib/liquid/template.rb:218:in `render!&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/liquid_renderer/file.rb:30:in `block (2 levels) in render!&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/liquid_renderer/file.rb:42:in `measure_bytes&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/liquid_renderer/file.rb:29:in `block in render!&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/liquid_renderer/file.rb:49:in `measure_time&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/liquid_renderer/file.rb:28:in `render!&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/renderer.rb:126:in `render_liquid&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/renderer.rb:195:in `render_layout&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/renderer.rb:158:in `place_in_layouts&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/renderer.rb:88:in `render_document&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/renderer.rb:62:in `run&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/site.rb:479:in `render_regenerated&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/site.rb:472:in `block in render_pages&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/site.rb:471:in `each&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/site.rb:471:in `render_pages&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/site.rb:192:in `render&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/site.rb:71:in `process&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/command.rb:28:in `process_site&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/commands/build.rb:65:in `build&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/commands/build.rb:36:in `process&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/commands/serve.rb:93:in `block in start&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/commands/serve.rb:93:in `each&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/commands/serve.rb:93:in `start&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/commands/serve.rb:75:in `block (2 levels) in init_with_program&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.3.6/lib/mercenary/command.rb:220:in `block in execute&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.3.6/lib/mercenary/command.rb:220:in `each&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.3.6/lib/mercenary/command.rb:220:in `execute&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.3.6/lib/mercenary/program.rb:42:in `go&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.3.6/lib/mercenary.rb:19:in `program&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/exe/jekyll:15:in `&lt;top (required)&gt;&apos;
	from /home/devs/.rbenv/versions/3.2.2/bin/jekyll:25:in `load&apos;
	from /home/devs/.rbenv/versions/3.2.2/bin/jekyll:25:in `&lt;top (required)&gt;&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli/exec.rb:58:in `load&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli/exec.rb:58:in `kernel_load&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli/exec.rb:23:in `run&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli.rb:492:in `exec&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/vendor/thor/lib/thor/command.rb:27:in `run&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/vendor/thor/lib/thor/invocation.rb:127:in `invoke_command&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/vendor/thor/lib/thor.rb:392:in `dispatch&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli.rb:34:in `dispatch&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/vendor/thor/lib/thor/base.rb:485:in `start&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli.rb:28:in `start&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.10/libexec/bundle:45:in `block in &lt;top (required)&gt;&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/friendly_errors.rb:117:in `with_friendly_errors&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.10/libexec/bundle:33:in `&lt;top (required)&gt;&apos;
	from /home/devs/.rbenv/versions/3.2.2/bin/bundle:25:in `load&apos;
	from /home/devs/.rbenv/versions/3.2.2/bin/bundle:25:in `&lt;main&gt;&apos;
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ nano _layouts/home.html
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ cat &gt; _layouts/home.html &lt;&lt; &apos;EOF&apos;
---
layout: default
refactor: true
---

{% include lang.html %}

{% assign all_pinned = site.posts | where: &apos;pin&apos;, &apos;true&apos; %}
{% assign all_normal = site.posts | where_exp: &apos;item&apos;, &apos;item.pin != true&apos; %}

{% assign posts = &apos;&apos; | split: &apos;&apos; %}

&lt;!-- Get pinned posts on current page --&gt;
{% assign visible_start = paginator.page | minus: 1 | times: paginator.per_page %}
{% assign visible_end = visible_start | plus: paginator.per_page %}

{% if all_pinned.size &gt; visible_start %}
  {% if all_pinned.size &gt; visible_end %}
    {% assign pinned_size = paginator.per_page %}
  {% else %}
    {% assign pinned_size = all_pinned.size | minus: visibEOFain&gt;&gt;ndif %}e.data.locales[lang].no_posts }}&lt;/p&gt;%}eft %
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ cat &gt; _layouts/home.html &lt;&lt; &apos;EOF&apos;
---
layout: default
refactor: true
---

{% include lang.html %}

{% assign all_pinned = site.posts | where: &apos;pin&apos;, &apos;true&apos; %}
{% assign all_normal = site.posts | where_exp: &apos;item&apos;, &apos;item.pin != true&apos; %}

{% assign posts = &apos;&apos; | split: &apos;&apos; %}

&lt;!-- Get pinned posts on current page --&gt;
{% assign visible_start = paginator.page | minus: 1 | times: paginator.per_page %}
{% assign visible_end = visible_start | plus: paginator.per_page %}

{% if all_pinned.size &gt; visible_start %}
  {% if all_pinned.size &gt; visible_end %}
    {% assign pinned_size = paginator.per_page %}
  {% else %}
    {% assign pinned_size = all_pinned.size | minus: visibEOFain&gt;&gt;ndif %}e.data.locales[lang].no_posts }}&lt;/p&gt;%}eft %
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ bundle exec jekyll serve --trace
Configuration file: /home/devs/Documents/devsgh-vid.github.io/_config.yml
To use retry middleware with Faraday v2.0+, install `faraday-retry` gem
<font color="#A2734C">   GitHub Metadata: No GitHub API authentication could be found. Some fields may be missing or have incorrect data.</font>
fatal: ambiguous argument &apos;HEAD&apos;: unknown revision or path not in the working tree.
Use &apos;--&apos; to separate paths from revisions, like this:
&apos;git &lt;command&gt; [&lt;revision&gt;...] -- [&lt;file&gt;...]&apos;
            Source: /home/devs/Documents/devsgh-vid.github.io
       Destination: /home/devs/Documents/devsgh-vid.github.io/_site
 Incremental build: disabled. Enable with --incremental
      Generating... 
       Jekyll Feed: Generating feed for posts
                    done in 1.387 seconds.
 Auto-regeneration: enabled for &apos;/home/devs/Documents/devsgh-vid.github.io&apos;
<font color="#C01C28">bundler: failed to load command: jekyll (/home/devs/.rbenv/versions/3.2.2/bin/jekyll)</font>
&lt;internal:/home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/rubygems/core_ext/kernel_require.rb&gt;:37:in `require&apos;: <b>cannot load such file -- webrick (</b><u style="text-decoration-style:single"><b>LoadError</b></u><b>)</b>
	from &lt;internal:/home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/rubygems/core_ext/kernel_require.rb&gt;:37:in `require&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/commands/serve/servlet.rb:3:in `&lt;top (required)&gt;&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/commands/serve.rb:184:in `require_relative&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/commands/serve.rb:184:in `setup&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/commands/serve.rb:102:in `process&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/commands/serve.rb:93:in `block in start&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/commands/serve.rb:93:in `each&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/commands/serve.rb:93:in `start&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/lib/jekyll/commands/serve.rb:75:in `block (2 levels) in init_with_program&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.3.6/lib/mercenary/command.rb:220:in `block in execute&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.3.6/lib/mercenary/command.rb:220:in `each&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.3.6/lib/mercenary/command.rb:220:in `execute&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.3.6/lib/mercenary/program.rb:42:in `go&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.3.6/lib/mercenary.rb:19:in `program&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-3.9.3/exe/jekyll:15:in `&lt;top (required)&gt;&apos;
	from /home/devs/.rbenv/versions/3.2.2/bin/jekyll:25:in `load&apos;
	from /home/devs/.rbenv/versions/3.2.2/bin/jekyll:25:in `&lt;top (required)&gt;&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli/exec.rb:58:in `load&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli/exec.rb:58:in `kernel_load&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli/exec.rb:23:in `run&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli.rb:492:in `exec&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/vendor/thor/lib/thor/command.rb:27:in `run&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/vendor/thor/lib/thor/invocation.rb:127:in `invoke_command&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/vendor/thor/lib/thor.rb:392:in `dispatch&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli.rb:34:in `dispatch&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/vendor/thor/lib/thor/base.rb:485:in `start&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli.rb:28:in `start&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.10/libexec/bundle:45:in `block in &lt;top (required)&gt;&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/friendly_errors.rb:117:in `with_friendly_errors&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.10/libexec/bundle:33:in `&lt;top (required)&gt;&apos;
	from /home/devs/.rbenv/versions/3.2.2/bin/bundle:25:in `load&apos;
	from /home/devs/.rbenv/versions/3.2.2/bin/bundle:25:in `&lt;main&gt;&apos;
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ bundle add webrick
Fetching gem metadata from https://rubygems.org/.........
Resolving dependencies...
Fetching gem metadata from https://rubygems.org/.........
Resolving dependencies...
Using base64 0.2.0
Using benchmark 0.4.1
Using concurrent-ruby 1.3.5
Using connection_pool 2.5.3
Using drb 2.2.3
Using logger 1.6.6
Using minitest 5.25.5
Using securerandom 0.4.1
Using uri 1.0.3
Using public_suffix 4.0.7
Using bundler 2.4.10
Using coffee-script-source 1.11.1
Using execjs 2.10.0
Using colorator 1.1.0
Using bigdecimal 3.2.2
Using simpleidn 0.2.3
Using commonmarker 0.23.11
Using eventmachine 1.2.7
Using http_parser.rb 0.8.0
Using ffi 1.17.2 (x86_64-linux-gnu)
Using json 2.13.2
Using gemoji 3.0.1
Using rb-fsevent 0.11.2
Using forwardable-extended 2.6.0
Using rexml 3.4.1
Using liquid 4.0.4
Using mercenary 0.3.6
Using safe_yaml 1.0.5
Using rouge 3.26.0
Using racc 1.8.1
Using jekyll-paginate 1.1.0
Using rubyzip 2.4.1
Using unicode-display_width 1.8.0
<font color="#26A269">Fetching webrick 1.9.1</font>
Using jekyll-swiss 1.0.0
Using i18n 1.14.7
Using tzinfo 2.0.6
Using addressable 2.8.7
Using net-http 0.6.0
Using coffee-script 2.4.1
Using dnsruby 1.72.4
Using em-websocket 0.5.3
Using ethon 0.16.0
Using rb-inotify 0.11.1
Using jekyll-commonmark 1.4.0
Using pathutil 0.16.2
Using kramdown 2.3.2
Using nokogiri 1.18.9 (x86_64-linux-gnu)
Using terminal-table 1.8.0
Using activesupport 8.0.2
Using faraday-net_http 3.4.1
Using jekyll-coffeescript 1.1.1
Using typhoeus 1.4.1
Using sass-listen 4.0.0
Using listen 3.9.0
Using kramdown-parser-gfm 1.1.0
Using html-pipeline 2.14.3
Using faraday 2.13.4
Using sass 3.7.4
Using jekyll-watch 2.2.1
Using sawyer 0.9.2
Using jekyll-sass-converter 1.5.2
Using octokit 4.25.1
Using jekyll 3.9.3
Using github-pages-health-check 1.17.9
Using jekyll-gist 1.5.0
Using jekyll-avatar 0.7.0
Using jekyll-commonmark-ghpages 0.4.0
Using jekyll-default-layout 0.1.4
Using jekyll-feed 0.15.1
Using jekyll-github-metadata 2.13.0
Using jekyll-include-cache 0.2.1
Using jekyll-mentions 1.6.0
Using jekyll-optional-front-matter 0.3.2
Using jekyll-readme-index 0.3.0
Using jekyll-redirect-from 0.16.0
Using jekyll-relative-links 0.6.1
Using jekyll-remote-theme 0.4.3
Using jekyll-seo-tag 2.8.0
Using jekyll-sitemap 1.4.0
Using jekyll-titles-from-headings 0.5.3
Using jemoji 0.12.0
Using jekyll-archives 2.3.0
Using jekyll-theme-architect 0.2.0
Using jekyll-theme-cayman 0.2.0
Using jekyll-theme-dinky 0.2.0
Using jekyll-theme-hacker 0.2.0
Using jekyll-theme-leap-day 0.2.0
Using jekyll-theme-merlot 0.2.0
Using jekyll-theme-midnight 0.2.0
Using jekyll-theme-minimal 0.2.0
Using jekyll-theme-modernist 0.2.0
Using jekyll-theme-primer 0.6.0
Using jekyll-theme-slate 0.2.0
Using jekyll-theme-tactile 0.2.0
Using jekyll-theme-time-machine 0.2.0
Using minima 2.5.1
Using github-pages 228
<font color="#26A269">Installing webrick 1.9.1</font>
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ cat &gt; Gemfile &lt;&lt; &apos;EOF&apos;
source &quot;https://rubygems.org&quot;

# Core
gem &quot;jekyll&quot;, &quot;~&gt; 4.3.0&quot;
gem &quot;webrick&quot;

# GitHub Pages compatibility
gem &quot;github-pages&quot;, group: :jekyll_plugins

# Required plugins for Chirpy
group :jekyll_plugins do
  gem &quot;jekyll-paginate&quot;
  gem &quot;jekyll-sitemap&quot;
  gem &quot;jekyll-feed&quot;
  gem &quot;jekyll-include-cache&quot;
  gem &quot;jekyll-archives&quot;
end

# Windows support
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem &quot;tzinfo&quot;
  gem &quot;tzinfo-data&quot;
end
EOF
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ bundle install
Fetching gem metadata from https://rubygems.org/.........
Resolving dependencies...
<font color="#C01C28">Could not find compatible versions</font>

<font color="#C01C28">Because github-pages &lt; 9 depends on kramdown = 1.0.2</font>
<font color="#C01C28">  and github-pages &gt;= 9, &lt; 14 depends on kramdown = 1.2.0,</font>
<font color="#C01C28">  github-pages &lt; 14 requires kramdown = 1.0.2 OR = 1.2.0.</font>
<font color="#C01C28">And because github-pages &gt;= 14, &lt; 32 depends on kramdown =</font>
<font color="#C01C28">1.3.1,</font>
<font color="#C01C28">github-pages &lt; 32 requires kramdown = 1.0.2 OR = 1.2.0</font>
<font color="#C01C28">OR = 1.3.1.</font>
<font color="#C01C28">Because github-pages &gt;= 35, &lt; 44 depends on liquid = 2.6.2</font>
<font color="#C01C28">  and github-pages &gt;= 21, &lt; 35 depends on liquid = 2.6.1,</font>
<font color="#C01C28">github-pages &gt;= 21, &lt; 44 requires liquid = 2.6.1 OR =</font>
<font color="#C01C28">2.6.2.</font>
<font color="#C01C28">Thus, github-pages &lt; 44 requires liquid = 2.6.1 OR = 2.6.2</font>
<font color="#C01C28">or kramdown = 1.0.2 OR = 1.2.0 OR = 1.3.1.</font>
<font color="#C01C28">And because github-pages &gt;= 44, &lt; 86 depends on rouge =</font>
<font color="#C01C28">1.10.1,</font>
<font color="#C01C28">github-pages &lt; 86 requires liquid = 2.6.1 OR = 2.6.2 or</font>
<font color="#C01C28">kramdown = 1.0.2 OR = 1.2.0 OR = 1.3.1 or rouge = 1.10.1.</font>
<font color="#C01C28">Because github-pages &gt;= 117, &lt; 178 depends on</font>
<font color="#C01C28">jekyll-sass-converter = 1.5.0</font>
<font color="#C01C28">  and github-pages &gt;= 44, &lt; 147 depends on liquid = 3.0.6,</font>
<font color="#C01C28">github-pages &gt;= 44, &lt; 178 requires jekyll-sass-converter</font>
<font color="#C01C28">= 1.5.0 or liquid = 3.0.6.</font>
<font color="#C01C28">Thus, github-pages &lt; 178 requires jekyll-sass-converter =</font>
<font color="#C01C28">1.5.0 or liquid = 2.6.1 OR = 2.6.2 OR = 3.0.6 or kramdown</font>
<font color="#C01C28">= 1.0.2 OR = 1.2.0 OR = 1.3.1 or rouge = 1.10.1.</font>
<font color="#C01C28">And because github-pages &gt;= 178 depends on</font>
<font color="#C01C28">jekyll-sass-converter = 1.5.2</font>
<font color="#C01C28">and jekyll &gt;= 4.3.0 depends on jekyll-sass-converter &gt;=</font>
<font color="#C01C28">2.0, &lt; 4.0,</font>
<font color="#C01C28">jekyll &gt;= 4.3.0 requires liquid = 2.6.1 OR = 2.6.2 OR =</font>
<font color="#C01C28">3.0.6 or kramdown = 1.0.2 OR = 1.2.0 OR = 1.3.1 or rouge =</font>
<font color="#C01C28">1.10.1.</font>
<font color="#C01C28">And because jekyll &gt;= 4.3.0 depends on kramdown &gt;= 2.3.1,</font>
<font color="#C01C28">&lt; 3.A</font>
<font color="#C01C28">  and jekyll &gt;= 3.5.0 depends on liquid ~&gt; 4.0,</font>
<font color="#C01C28">  jekyll &gt;= 4.3.0 requires rouge = 1.10.1.</font>
<font color="#C01C28">So, because jekyll &gt;= 4.3.0 depends on rouge &gt;= 3.0, &lt; 5.0</font>
<font color="#C01C28">  and Gemfile depends on jekyll ~&gt; 4.3.0,</font>
<font color="#C01C28">  version solving has failed.</font>
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ cat &gt; Gemfile &lt;&lt; &apos;EOF&apos;
source &quot;https://rubygems.org&quot;

# Core
gem &quot;jekyll&quot;, &quot;~&gt; 4.3.0&quot;
gem &quot;webrick&quot;

# Required plugins for Chirpy
group :jekyll_plugins do
  gem &quot;jekyll-paginate&quot;, &quot;~&gt; 1.1&quot;
  gem &quot;jekyll-sitemap&quot;, &quot;~&gt; 1.4&quot;
  gem &quot;jekyll-feed&quot;, &quot;~&gt; 0.17&quot;
  gem &quot;jekyll-include-cache&quot;, &quot;~&gt; 0.2&quot;
  gem &quot;jekyll-archives&quot;, &quot;~&gt; 2.2&quot;
end

# Markdown processor
gem &quot;kramdown&quot;, &quot;~&gt; 2.4&quot;

# Syntax highlighting
gem &quot;rouge&quot;, &quot;~&gt; 4.1&quot;

# Windows support
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem &quot;tzinfo&quot;, &quot;~&gt; 1.2&quot;
EOFem &quot;tzinfo-data&quot;
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ bundle clean --force
<font color="#C01C28">Could not find gem &apos;jekyll (~&gt; 4.3.0)&apos; in locally</font>
<font color="#C01C28">installed gems.</font>

<font color="#C01C28">The source contains the following gems matching &apos;jekyll&apos;:</font>
<font color="#C01C28">  * jekyll-3.9.3</font>
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ bundle install
Fetching gem metadata from https://rubygems.org/.........
Resolving dependencies...
<font color="#26A269">Fetching rake 13.3.0</font>
<font color="#26A269">Installing rake 13.3.0</font>
<font color="#26A269">Fetching public_suffix 6.0.2 (was 4.0.7)</font>
Using bigdecimal 3.2.2
Using bundler 2.4.10
Using colorator 1.1.0
Using concurrent-ruby 1.3.5
Using eventmachine 1.2.7
Using http_parser.rb 0.8.0
Using ffi 1.17.2 (x86_64-linux-gnu)
Using forwardable-extended 2.6.0
Using rb-fsevent 0.11.2
Using rexml 3.4.1
Using liquid 4.0.4
<font color="#26A269">Fetching mercenary 0.4.0 (was 0.3.6)</font>
<font color="#26A269">Installing mercenary 0.4.0 (was 0.3.6)</font>
<font color="#26A269">Fetching rouge 4.6.0 (was 3.26.0)</font>
<font color="#26A269">Installing public_suffix 6.0.2 (was 4.0.7)</font>
Using safe_yaml 1.0.5
<font color="#26A269">Fetching unicode-display_width 2.6.0 (was 1.8.0)</font>
<font color="#26A269">Installing unicode-display_width 2.6.0 (was 1.8.0)</font>
Using webrick 1.9.1
Using jekyll-paginate 1.1.0
<font color="#26A269">Fetching google-protobuf 4.31.1 (x86_64-linux-gnu)</font>
<font color="#26A269">Installing rouge 4.6.0 (was 3.26.0)</font>
Using em-websocket 0.5.3
Using i18n 1.14.7
Using rb-inotify 0.11.1
<font color="#26A269">Fetching kramdown 2.5.1 (was 2.3.2)</font>
<font color="#26A269">Installing kramdown 2.5.1 (was 2.3.2)</font>
<font color="#26A269">Installing google-protobuf 4.31.1 (x86_64-linux-gnu)</font>
Using pathutil 0.16.2
Using addressable 2.8.7
<font color="#26A269">Fetching terminal-table 3.0.2 (was 1.8.0)</font>
<font color="#26A269">Installing terminal-table 3.0.2 (was 1.8.0)</font>
Using listen 3.9.0
<font color="#26A269">Fetching sass-embedded 1.90.0 (x86_64-linux-gnu)</font>
Using jekyll-watch 2.2.1
Using kramdown-parser-gfm 1.1.0
<font color="#26A269">Installing sass-embedded 1.90.0 (x86_64-linux-gnu)</font>
<font color="#26A269">Fetching jekyll-sass-converter 3.1.0 (was 1.5.2)</font>
<font color="#26A269">Installing jekyll-sass-converter 3.1.0 (was 1.5.2)</font>
<font color="#26A269">Fetching jekyll 4.3.4 (was 3.9.3)</font>
<font color="#26A269">Installing jekyll 4.3.4 (was 3.9.3)</font>
Using jekyll-archives 2.3.0
Using jekyll-include-cache 0.2.1
Using jekyll-sitemap 1.4.0
<font color="#26A269">Fetching jekyll-feed 0.17.0 (was 0.15.1)</font>
<font color="#26A269">Installing jekyll-feed 0.17.0 (was 0.15.1)</font>
<font color="#26A269">Bundle complete! 11 Gemfile dependencies, 37 gems now installed.</font>
<font color="#26A269">Use `bundle info [gemname]` to see where a bundled gem is installed.</font>
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ nano _config.yml
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ cp _config.yml _config.yml.bak
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ cat &gt; _config.yml &lt;&lt; &apos;EOF&apos;
# ===== Core Settings =====
title: DevSGH CloudSec
tagline: Cloud Security &amp; DevOps Engineering
description: &gt;-
  Professional insights on cloud security, DevOps practices,
  and infrastructure automation.
url: &quot;https://devsgh-vid.github.io&quot;
baseurl: &quot;&quot;
timezone: Australia/Melbourne
lang: en

# ===== Author =====
author:
  name: Dev Singh
  email: devsingh.videos@gmail.com
  github: devsgh-vid

# ===== Build =====
markdown: kramdown
highlighter: rouge
permalink: /posts/:title/
incremental: false
EOF tag: /tags/:name/ries/:name/hives) =====
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ cat _config.yml
# ===== Core Settings =====
title: DevSGH CloudSec
tagline: Cloud Security &amp; DevOps Engineering
description: &gt;-
  Professional insights on cloud security, DevOps practices,
  and infrastructure automation.
url: &quot;https://devsgh-vid.github.io&quot;
baseurl: &quot;&quot;
timezone: Australia/Melbourne
lang: en

# ===== Author =====
author:
  name: Dev Singh
  email: devsingh.videos@gmail.com
  github: devsgh-vid

# ===== Build =====
markdown: kramdown
highlighter: rouge
permalink: /posts/:title/
incremental: false
future: false

# ===== Plugins =====
plugins:
  - jekyll-paginate
  - jekyll-sitemap
  - jekyll-feed
  - jekyll-include-cache
  - jekyll-archives

# ===== Chirpy-Specific =====
theme: jekyll-theme-chirpy
paginate: 10
paginate_path: &quot;/page:num/&quot;

# ===== Collections =====
collections:
  tabs:
    output: true
    sort_by: order

# ===== Defaults =====
defaults:
  - scope:
      path: &quot;&quot;
      type: posts
    values:
      layout: post
      comments: true
      toc: true
  - scope:
      path: _tabs
    values:
      layout: page

# ===== Archives (for jekyll-archives) =====
jekyll-archives:
  enabled:
    - categories
    - tags
  layouts:
    category: category
    tag: tag
  permalinks:
    category: /categories/:name/
    tag: /tags/:name/
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ bundle exec jekyll build --trace
Configuration file: /home/devs/Documents/devsgh-vid.github.io/_config.yml
<font color="#C01C28">bundler: failed to load command: jekyll (/home/devs/.rbenv/versions/3.2.2/bin/jekyll)</font>
/home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/theme.rb:86:in `rescue in gemspec&apos;: <b>The jekyll-theme-chirpy theme could not be found. (</b><u style="text-decoration-style:single"><b>Jekyll::Errors::MissingDependencyException</b></u><b>)</b>
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/theme.rb:83:in `gemspec&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/theme.rb:19:in `root&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/theme.rb:13:in `initialize&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/site.rb:535:in `new&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/site.rb:535:in `configure_theme&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/site.rb:60:in `config=&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/site.rb:23:in `initialize&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/commands/build.rb:30:in `new&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/commands/build.rb:30:in `process&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/command.rb:91:in `block in process_with_graceful_fail&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/command.rb:91:in `each&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/command.rb:91:in `process_with_graceful_fail&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/commands/build.rb:18:in `block (2 levels) in init_with_program&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.4.0/lib/mercenary/command.rb:221:in `block in execute&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.4.0/lib/mercenary/command.rb:221:in `each&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.4.0/lib/mercenary/command.rb:221:in `execute&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.4.0/lib/mercenary/program.rb:44:in `go&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.4.0/lib/mercenary.rb:21:in `program&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/exe/jekyll:15:in `&lt;top (required)&gt;&apos;
	from /home/devs/.rbenv/versions/3.2.2/bin/jekyll:25:in `load&apos;
	from /home/devs/.rbenv/versions/3.2.2/bin/jekyll:25:in `&lt;top (required)&gt;&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli/exec.rb:58:in `load&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli/exec.rb:58:in `kernel_load&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli/exec.rb:23:in `run&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli.rb:492:in `exec&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/vendor/thor/lib/thor/command.rb:27:in `run&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/vendor/thor/lib/thor/invocation.rb:127:in `invoke_command&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/vendor/thor/lib/thor.rb:392:in `dispatch&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli.rb:34:in `dispatch&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/vendor/thor/lib/thor/base.rb:485:in `start&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli.rb:28:in `start&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.10/libexec/bundle:45:in `block in &lt;top (required)&gt;&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/friendly_errors.rb:117:in `with_friendly_errors&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.10/libexec/bundle:33:in `&lt;top (required)&gt;&apos;
	from /home/devs/.rbenv/versions/3.2.2/bin/bundle:25:in `load&apos;
	from /home/devs/.rbenv/versions/3.2.2/bin/bundle:25:in `&lt;main&gt;&apos;
/home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/rubygems/dependency.rb:314:in `to_specs&apos;: <b>Could not find &apos;jekyll-theme-chirpy&apos; (&gt;= 0) among 106 total gem(s) (</b><u style="text-decoration-style:single"><b>Gem::MissingSpecError</b></u><b>)</b>
<b>Checked in &apos;GEM_PATH=/home/devs/.local/share/gem/ruby/3.2.0:/home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0&apos; , execute `gem env` for more information</b>
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/rubygems/dependency.rb:326:in `to_spec&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/rubygems/specification.rb:1021:in `find_by_name&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/theme.rb:84:in `gemspec&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/theme.rb:19:in `root&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/theme.rb:13:in `initialize&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/site.rb:535:in `new&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/site.rb:535:in `configure_theme&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/site.rb:60:in `config=&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/site.rb:23:in `initialize&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/commands/build.rb:30:in `new&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/commands/build.rb:30:in `process&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/command.rb:91:in `block in process_with_graceful_fail&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/command.rb:91:in `each&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/command.rb:91:in `process_with_graceful_fail&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/commands/build.rb:18:in `block (2 levels) in init_with_program&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.4.0/lib/mercenary/command.rb:221:in `block in execute&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.4.0/lib/mercenary/command.rb:221:in `each&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.4.0/lib/mercenary/command.rb:221:in `execute&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.4.0/lib/mercenary/program.rb:44:in `go&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.4.0/lib/mercenary.rb:21:in `program&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/exe/jekyll:15:in `&lt;top (required)&gt;&apos;
	from /home/devs/.rbenv/versions/3.2.2/bin/jekyll:25:in `load&apos;
	from /home/devs/.rbenv/versions/3.2.2/bin/jekyll:25:in `&lt;top (required)&gt;&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli/exec.rb:58:in `load&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli/exec.rb:58:in `kernel_load&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli/exec.rb:23:in `run&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli.rb:492:in `exec&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/vendor/thor/lib/thor/command.rb:27:in `run&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/vendor/thor/lib/thor/invocation.rb:127:in `invoke_command&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/vendor/thor/lib/thor.rb:392:in `dispatch&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli.rb:34:in `dispatch&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/vendor/thor/lib/thor/base.rb:485:in `start&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli.rb:28:in `start&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.10/libexec/bundle:45:in `block in &lt;top (required)&gt;&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/friendly_errors.rb:117:in `with_friendly_errors&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.10/libexec/bundle:33:in `&lt;top (required)&gt;&apos;
	from /home/devs/.rbenv/versions/3.2.2/bin/bundle:25:in `load&apos;
	from /home/devs/.rbenv/versions/3.2.2/bin/bundle:25:in `&lt;main&gt;&apos;
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ cat &gt; _config.yml &lt;&lt; &apos;EOF&apos;
# ===== Core Settings =====
title: DevSGH CloudSec
tagline: Cloud Security &amp; DevOps Engineering
description: &gt;-
  Professional insights on cloud security, DevOps practices,
  and infrastructure automation.
url: &quot;https://devsgh-vid.github.io&quot;
baseurl: &quot;&quot;
timezone: Australia/Melbourne
lang: en

# ===== File Includes =====
include:
  - _layouts
  - _includes
  - _sass
  - assets
  - _plugins
  - _data

# ===== Author =====
author:
  name: Dev Singh
EOF tag: /tags/:name/ries/:name/om
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ ls -la _layouts/ _includes/ _sass/ assets/
assets/:
total 36
drwxrwxr-x  6 devs devs 4096 Aug  7 16:31 <font color="#12488B"><b>.</b></font>
drwxrwxr-x 11 devs devs 4096 Aug  7 17:13 <font color="#12488B"><b>..</b></font>
-rw-rw-r--  1 devs devs  166 Aug  7 16:31 404.html
drwxrwxr-x  2 devs devs 4096 Aug  7 16:31 <font color="#12488B"><b>css</b></font>
-rw-rw-r--  1 devs devs 1978 Aug  7 16:31 feed.xml
drwxrwxr-x  3 devs devs 4096 Aug  7 16:31 <font color="#12488B"><b>img</b></font>
drwxrwxr-x  3 devs devs 4096 Aug  7 16:31 <font color="#12488B"><b>js</b></font>
drwxrwxr-x  2 devs devs 4096 Aug  7 16:31 <font color="#12488B"><b>lib</b></font>
-rw-rw-r--  1 devs devs  133 Aug  7 16:31 robots.txt

_includes/:
total 148
drwxrwxr-x  6 devs devs 4096 Aug  7 16:31 <font color="#12488B"><b>.</b></font>
drwxrwxr-x 11 devs devs 4096 Aug  7 17:13 <font color="#12488B"><b>..</b></font>
drwxrwxr-x  2 devs devs 4096 Aug  7 16:31 <font color="#12488B"><b>analytics</b></font>
-rw-rw-r--  1 devs devs  199 Aug  7 16:31 comment.html
drwxrwxr-x  2 devs devs 4096 Aug  7 16:31 <font color="#12488B"><b>comments</b></font>
-rw-rw-r--  1 devs devs  563 Aug  7 16:31 datetime.html
drwxrwxr-x  2 devs devs 4096 Aug  7 16:31 <font color="#12488B"><b>embed</b></font>
-rw-rw-r--  1 devs devs  979 Aug  7 16:31 favicons.html
-rw-rw-r--  1 devs devs 1333 Aug  7 16:31 footer.html
-rw-rw-r--  1 devs devs 4284 Aug  7 16:31 head.html
-rw-rw-r--  1 devs devs  745 Aug  7 16:31 jsdelivr-combine.html
-rw-rw-r--  1 devs devs 2643 Aug  7 16:31 js-selector.html
-rw-rw-r--  1 devs devs  291 Aug  7 16:31 lang.html
-rw-rw-r--  1 devs devs 1810 Aug  7 16:31 language-alias.html
-rw-rw-r--  1 devs devs 1112 Aug  7 16:31 media-url.html
-rw-rw-r--  1 devs devs   57 Aug  7 16:31 metadata-hook.html
-rw-rw-r--  1 devs devs  635 Aug  7 16:31 notification.html
-rw-rw-r--  1 devs devs  349 Aug  7 16:31 origin-type.html
drwxrwxr-x  2 devs devs 4096 Aug  7 16:31 <font color="#12488B"><b>pageviews</b></font>
-rw-rw-r--  1 devs devs 1098 Aug  7 16:31 post-description.html
-rw-rw-r--  1 devs devs  981 Aug  7 16:31 post-nav.html
-rw-rw-r--  1 devs devs 3002 Aug  7 16:31 post-paginator.html
-rw-rw-r--  1 devs devs 1894 Aug  7 16:31 post-sharing.html
-rw-rw-r--  1 devs devs  978 Aug  7 16:31 read-time.html
-rw-rw-r--  1 devs devs 9528 Aug  7 16:31 refactor-content.html
-rw-rw-r--  1 devs devs 2824 Aug  7 16:31 related-posts.html
-rw-rw-r--  1 devs devs 1561 Aug  7 16:31 search-loader.html
-rw-rw-r--  1 devs devs  357 Aug  7 16:31 search-results.html
-rw-rw-r--  1 devs devs 3386 Aug  7 16:31 sidebar.html
-rw-rw-r--  1 devs devs  322 Aug  7 16:31 toc.html
-rw-rw-r--  1 devs devs  292 Aug  7 16:31 toc-status.html
-rw-rw-r--  1 devs devs 2749 Aug  7 16:31 topbar.html
-rw-rw-r--  1 devs devs 1456 Aug  7 16:31 trending-tags.html
-rw-rw-r--  1 devs devs 1181 Aug  7 16:31 update-list.html

_layouts/:
total 60
drwxrwxr-x  2 devs devs 4096 Aug  7 16:43 <font color="#12488B"><b>.</b></font>
drwxrwxr-x 11 devs devs 4096 Aug  7 17:13 <font color="#12488B"><b>..</b></font>
-rw-rw-r--  1 devs devs 1073 Aug  7 16:31 archives.html
-rw-rw-r--  1 devs devs 4941 Aug  7 16:31 categories.html
-rw-rw-r--  1 devs devs  650 Aug  7 16:31 category.html
-rw-rw-r--  1 devs devs 4568 Aug  7 16:31 compress.html
-rw-rw-r--  1 devs devs 2676 Aug  7 16:31 default.html
-rw-rw-r--  1 devs devs 1789 Aug  7 16:44 home.html
-rw-rw-r--  1 devs devs  441 Aug  7 16:31 page.html
-rw-rw-r--  1 devs devs 5838 Aug  7 16:31 post.html
-rw-rw-r--  1 devs devs  639 Aug  7 16:31 tag.html
-rw-rw-r--  1 devs devs  541 Aug  7 16:31 tags.html

_sass/:
total 40
drwxrwxr-x  8 devs devs 4096 Aug  7 16:31 <font color="#12488B"><b>.</b></font>
drwxrwxr-x 11 devs devs 4096 Aug  7 17:13 <font color="#12488B"><b>..</b></font>
drwxrwxr-x  2 devs devs 4096 Aug  7 16:31 <font color="#12488B"><b>abstracts</b></font>
drwxrwxr-x  2 devs devs 4096 Aug  7 16:31 <font color="#12488B"><b>base</b></font>
drwxrwxr-x  2 devs devs 4096 Aug  7 16:31 <font color="#12488B"><b>components</b></font>
drwxrwxr-x  2 devs devs 4096 Aug  7 16:31 <font color="#12488B"><b>layout</b></font>
-rw-rw-r--  1 devs devs   39 Aug  7 16:31 main.bundle.scss
-rw-rw-r--  1 devs devs   77 Aug  7 16:31 main.scss
drwxrwxr-x  2 devs devs 4096 Aug  7 16:31 <font color="#12488B"><b>pages</b></font>
drwxrwxr-x  2 devs devs 4096 Aug  7 16:31 <font color="#12488B"><b>themes</b></font>
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ bundle exec jekyll clean
Configuration file: /home/devs/Documents/devsgh-vid.github.io/_config.yml
           Cleaner: Removing /home/devs/Documents/devsgh-vid.github.io/_site...
           Cleaner: Nothing to do for /home/devs/Documents/devsgh-vid.github.io/.jekyll-metadata.
           Cleaner: Removing /home/devs/Documents/devsgh-vid.github.io/.jekyll-cache...
           Cleaner: Nothing to do for .sass-cache.
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ bundle exec jekyll build --trace
Configuration file: /home/devs/Documents/devsgh-vid.github.io/_config.yml
            Source: /home/devs/Documents/devsgh-vid.github.io
       Destination: /home/devs/Documents/devsgh-vid.github.io/_site
 Incremental build: disabled. Enable with --incremental
      Generating... 
<font color="#A2734C">        Pagination: Pagination is enabled, but I couldn&apos;t find an index.html page to use as the pagination template. Skipping pagination.</font>
       Jekyll Feed: Generating feed for posts
<font color="#C01C28">  Liquid Exception: Liquid syntax error (/home/devs/Documents/devsgh-vid.github.io/_includes/head.html line 13): Unknown tag &apos;seo&apos; included in /home/devs/Documents/devsgh-vid.github.io/_layouts/default.html</font>
<font color="#C01C28">bundler: failed to load command: jekyll (/home/devs/.rbenv/versions/3.2.2/bin/jekyll)</font>
/home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/liquid-4.0.4/lib/liquid/block.rb:38:in `unknown_tag&apos;: <b>Liquid syntax error (/home/devs/Documents/devsgh-vid.github.io/_includes/head.html line 13): Unknown tag &apos;seo&apos; included  (</b><u style="text-decoration-style:single"><b>Liquid::SyntaxError</b></u><b>)</b>
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/liquid-4.0.4/lib/liquid/block.rb:68:in `block in parse_body&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/liquid-4.0.4/lib/liquid/block_body.rb:32:in `parse&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/liquid-4.0.4/lib/liquid/block.rb:58:in `parse_body&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/liquid-4.0.4/lib/liquid/block.rb:12:in `parse&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/liquid-4.0.4/lib/liquid/tag.rb:10:in `parse&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/liquid-4.0.4/lib/liquid/block_body.rb:34:in `parse&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/liquid-4.0.4/lib/liquid/document.rb:10:in `parse&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/liquid-4.0.4/lib/liquid/document.rb:5:in `parse&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/liquid-4.0.4/lib/liquid/template.rb:130:in `parse&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/liquid-4.0.4/lib/liquid/template.rb:114:in `parse&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/liquid_renderer/file.rb:13:in `block in parse&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/liquid_renderer/file.rb:70:in `measure_time&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/liquid_renderer/file.rb:12:in `parse&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/inclusion.rb:15:in `render&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/tags/include.rb:208:in `block in render&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/liquid-4.0.4/lib/liquid/context.rb:123:in `stack&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/tags/include.rb:206:in `render&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/liquid-4.0.4/lib/liquid/block_body.rb:103:in `render_node_to_output&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/liquid-4.0.4/lib/liquid/block_body.rb:91:in `render&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/liquid-4.0.4/lib/liquid/template.rb:206:in `block in render&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/liquid-4.0.4/lib/liquid/template.rb:240:in `with_profiling&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/liquid-4.0.4/lib/liquid/template.rb:205:in `render&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/liquid-4.0.4/lib/liquid/template.rb:218:in `render!&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/liquid_renderer/file.rb:39:in `block (3 levels) in render!&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/liquid_renderer/file.rb:59:in `measure_counts&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/liquid_renderer/file.rb:38:in `block (2 levels) in render!&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/liquid_renderer/file.rb:63:in `measure_bytes&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/liquid_renderer/file.rb:37:in `block in render!&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/liquid_renderer/file.rb:70:in `measure_time&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/liquid_renderer/file.rb:36:in `render!&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/renderer.rb:129:in `render_liquid&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/renderer.rb:192:in `render_layout&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/renderer.rb:161:in `place_in_layouts&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/renderer.rb:93:in `render_document&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/renderer.rb:63:in `run&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/site.rb:572:in `render_regenerated&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/site.rb:564:in `block in render_pages&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/site.rb:563:in `each&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/site.rb:563:in `render_pages&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/site.rb:211:in `render&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/site.rb:80:in `process&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/command.rb:28:in `process_site&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/commands/build.rb:65:in `build&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/commands/build.rb:36:in `process&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/command.rb:91:in `block in process_with_graceful_fail&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/command.rb:91:in `each&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/command.rb:91:in `process_with_graceful_fail&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/commands/build.rb:18:in `block (2 levels) in init_with_program&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.4.0/lib/mercenary/command.rb:221:in `block in execute&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.4.0/lib/mercenary/command.rb:221:in `each&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.4.0/lib/mercenary/command.rb:221:in `execute&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.4.0/lib/mercenary/program.rb:44:in `go&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.4.0/lib/mercenary.rb:21:in `program&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/exe/jekyll:15:in `&lt;top (required)&gt;&apos;
	from /home/devs/.rbenv/versions/3.2.2/bin/jekyll:25:in `load&apos;
	from /home/devs/.rbenv/versions/3.2.2/bin/jekyll:25:in `&lt;top (required)&gt;&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli/exec.rb:58:in `load&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli/exec.rb:58:in `kernel_load&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli/exec.rb:23:in `run&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli.rb:492:in `exec&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/vendor/thor/lib/thor/command.rb:27:in `run&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/vendor/thor/lib/thor/invocation.rb:127:in `invoke_command&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/vendor/thor/lib/thor.rb:392:in `dispatch&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli.rb:34:in `dispatch&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/vendor/thor/lib/thor/base.rb:485:in `start&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli.rb:28:in `start&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.10/libexec/bundle:45:in `block in &lt;top (required)&gt;&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/friendly_errors.rb:117:in `with_friendly_errors&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.10/libexec/bundle:33:in `&lt;top (required)&gt;&apos;
	from /home/devs/.rbenv/versions/3.2.2/bin/bundle:25:in `load&apos;
	from /home/devs/.rbenv/versions/3.2.2/bin/bundle:25:in `&lt;main&gt;&apos;
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ cat &gt;&gt; Gemfile &lt;&lt; &apos;EOF&apos;

# SEO Plugin (required by Chirpy)
gem &quot;jekyll-seo-tag&quot;, &quot;~&gt; 2.8&quot;
EOF
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ nano _config.yml
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ bundle install
Fetching gem metadata from https://rubygems.org/..........
Resolving dependencies...
Using rake 13.3.0
Using public_suffix 6.0.2
Using bundler 2.4.10
Using bigdecimal 3.2.2
Using concurrent-ruby 1.3.5
Using colorator 1.1.0
Using http_parser.rb 0.8.0
Using eventmachine 1.2.7
Using forwardable-extended 2.6.0
Using ffi 1.17.2 (x86_64-linux-gnu)
Using rexml 3.4.1
Using rb-fsevent 0.11.2
Using mercenary 0.4.0
Using rouge 4.6.0
Using liquid 4.0.4
Using unicode-display_width 2.6.0
Using safe_yaml 1.0.5
Using jekyll-paginate 1.1.0
Using webrick 1.9.1
Using addressable 2.8.7
Using google-protobuf 4.31.1 (x86_64-linux-gnu)
Using em-websocket 0.5.3
Using i18n 1.14.7
Using rb-inotify 0.11.1
Using pathutil 0.16.2
Using terminal-table 3.0.2
Using kramdown 2.5.1
Using listen 3.9.0
Using sass-embedded 1.90.0 (x86_64-linux-gnu)
Using kramdown-parser-gfm 1.1.0
Using jekyll-watch 2.2.1
Using jekyll-sass-converter 3.1.0
Using jekyll 4.3.4
Using jekyll-archives 2.3.0
Using jekyll-feed 0.17.0
Using jekyll-include-cache 0.2.1
Using jekyll-sitemap 1.4.0
Using jekyll-seo-tag 2.8.0
<font color="#26A269">Bundle complete! 12 Gemfile dependencies, 38 gems now installed.</font>
<font color="#26A269">Use `bundle info [gemname]` to see where a bundled gem is installed.</font>
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ nano _includes/head.html
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ cat &gt; _includes/head.html
^C
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ cat &gt; _includes/head.html &lt;&lt; &apos;EOF&apos;
&lt;meta charset=&quot;utf-8&quot;&gt;
&lt;meta name=&quot;viewport&quot; content=&quot;width=device-width, initial-scale=1, shrink-to-fit=no&quot;&gt;
{% seo title=false %}
&lt;link rel=&quot;stylesheet&quot; href=&quot;{{ &apos;/assets/css/main.css&apos; | relative_url }}&quot;&gt;
{% include head/custom.html %}
EOF
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ bundle exec jekyll clean
Configuration file: /home/devs/Documents/devsgh-vid.github.io/_config.yml
           Cleaner: Nothing to do for /home/devs/Documents/devsgh-vid.github.io/_site.
           Cleaner: Nothing to do for /home/devs/Documents/devsgh-vid.github.io/.jekyll-metadata.
           Cleaner: Removing /home/devs/Documents/devsgh-vid.github.io/.jekyll-cache...
           Cleaner: Nothing to do for .sass-cache.
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ bundle exec jekyll build --trace
Configuration file: /home/devs/Documents/devsgh-vid.github.io/_config.yml
            Source: /home/devs/Documents/devsgh-vid.github.io
       Destination: /home/devs/Documents/devsgh-vid.github.io/_site
 Incremental build: disabled. Enable with --incremental
      Generating... 
<font color="#A2734C">        Pagination: Pagination is enabled, but I couldn&apos;t find an index.html page to use as the pagination template. Skipping pagination.</font>
       Jekyll Feed: Generating feed for posts
<font color="#C01C28">  Liquid Exception: Could not locate the included file &apos;head/custom.html&apos; in any of [&quot;/home/devs/Documents/devsgh-vid.github.io/_includes&quot;]. Ensure it exists in one of those directories and, if it is a symlink, does not point outside your site source. in /home/devs/Documents/devsgh-vid.github.io/_layouts/default.html</font>
<font color="#C01C28">bundler: failed to load command: jekyll (/home/devs/.rbenv/versions/3.2.2/bin/jekyll)</font>
/home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/tags/include.rb:219:in `locate_include_file&apos;: <b>Could not locate the included file &apos;head/custom.html&apos; in any of [&quot;/home/devs/Documents/devsgh-vid.github.io/_includes&quot;]. Ensure it exists in one of those directories and, if it is a symlink, does not point outside your site source. (</b><u style="text-decoration-style:single"><b>IOError</b></u><b>)</b>
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/tags/include.rb:201:in `render&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/liquid-4.0.4/lib/liquid/block_body.rb:103:in `render_node_to_output&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/liquid-4.0.4/lib/liquid/block_body.rb:91:in `render&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/liquid-4.0.4/lib/liquid/template.rb:206:in `block in render&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/liquid-4.0.4/lib/liquid/template.rb:240:in `with_profiling&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/liquid-4.0.4/lib/liquid/template.rb:205:in `render&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/liquid-4.0.4/lib/liquid/template.rb:218:in `render!&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/liquid_renderer/file.rb:39:in `block (3 levels) in render!&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/liquid_renderer/file.rb:59:in `measure_counts&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/liquid_renderer/file.rb:38:in `block (2 levels) in render!&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/liquid_renderer/file.rb:63:in `measure_bytes&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/liquid_renderer/file.rb:37:in `block in render!&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/liquid_renderer/file.rb:70:in `measure_time&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/liquid_renderer/file.rb:36:in `render!&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/inclusion.rb:16:in `render&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/tags/include.rb:208:in `block in render&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/liquid-4.0.4/lib/liquid/context.rb:123:in `stack&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/tags/include.rb:206:in `render&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/liquid-4.0.4/lib/liquid/block_body.rb:103:in `render_node_to_output&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/liquid-4.0.4/lib/liquid/block_body.rb:91:in `render&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/liquid-4.0.4/lib/liquid/template.rb:206:in `block in render&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/liquid-4.0.4/lib/liquid/template.rb:240:in `with_profiling&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/liquid-4.0.4/lib/liquid/template.rb:205:in `render&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/liquid-4.0.4/lib/liquid/template.rb:218:in `render!&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/liquid_renderer/file.rb:39:in `block (3 levels) in render!&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/liquid_renderer/file.rb:59:in `measure_counts&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/liquid_renderer/file.rb:38:in `block (2 levels) in render!&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/liquid_renderer/file.rb:63:in `measure_bytes&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/liquid_renderer/file.rb:37:in `block in render!&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/liquid_renderer/file.rb:70:in `measure_time&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/liquid_renderer/file.rb:36:in `render!&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/renderer.rb:129:in `render_liquid&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/renderer.rb:192:in `render_layout&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/renderer.rb:161:in `place_in_layouts&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/renderer.rb:93:in `render_document&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/renderer.rb:63:in `run&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/site.rb:572:in `render_regenerated&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/site.rb:564:in `block in render_pages&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/site.rb:563:in `each&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/site.rb:563:in `render_pages&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/site.rb:211:in `render&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/site.rb:80:in `process&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/command.rb:28:in `process_site&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/commands/build.rb:65:in `build&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/commands/build.rb:36:in `process&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/command.rb:91:in `block in process_with_graceful_fail&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/command.rb:91:in `each&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/command.rb:91:in `process_with_graceful_fail&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/lib/jekyll/commands/build.rb:18:in `block (2 levels) in init_with_program&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.4.0/lib/mercenary/command.rb:221:in `block in execute&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.4.0/lib/mercenary/command.rb:221:in `each&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.4.0/lib/mercenary/command.rb:221:in `execute&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.4.0/lib/mercenary/program.rb:44:in `go&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/mercenary-0.4.0/lib/mercenary.rb:21:in `program&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/jekyll-4.3.4/exe/jekyll:15:in `&lt;top (required)&gt;&apos;
	from /home/devs/.rbenv/versions/3.2.2/bin/jekyll:25:in `load&apos;
	from /home/devs/.rbenv/versions/3.2.2/bin/jekyll:25:in `&lt;top (required)&gt;&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli/exec.rb:58:in `load&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli/exec.rb:58:in `kernel_load&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli/exec.rb:23:in `run&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli.rb:492:in `exec&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/vendor/thor/lib/thor/command.rb:27:in `run&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/vendor/thor/lib/thor/invocation.rb:127:in `invoke_command&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/vendor/thor/lib/thor.rb:392:in `dispatch&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli.rb:34:in `dispatch&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/vendor/thor/lib/thor/base.rb:485:in `start&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/cli.rb:28:in `start&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.10/libexec/bundle:45:in `block in &lt;top (required)&gt;&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/3.2.0/bundler/friendly_errors.rb:117:in `with_friendly_errors&apos;
	from /home/devs/.rbenv/versions/3.2.2/lib/ruby/gems/3.2.0/gems/bundler-2.4.10/libexec/bundle:33:in `&lt;top (required)&gt;&apos;
	from /home/devs/.rbenv/versions/3.2.2/bin/bundle:25:in `load&apos;
	from /home/devs/.rbenv/versions/3.2.2/bin/bundle:25:in `&lt;main&gt;&apos;
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ mkdir -p _includes/head
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ cat &gt; _includes/head/custom.html &lt;&lt; &apos;EOF&apos;
&lt;!-- Custom head content (can be left empty) --&gt;
EOF
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ cat &gt; _includes/head/custom.html &lt;&lt; &apos;EOF&apos;
{% if site.google_analytics %}
  {% include google-analytics.html %}
{% endif %}
EOF
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ ls _includes/head/custom.html
_includes/head/custom.html
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ bundle exec jekyll clean
Configuration file: /home/devs/Documents/devsgh-vid.github.io/_config.yml
           Cleaner: Nothing to do for /home/devs/Documents/devsgh-vid.github.io/_site.
           Cleaner: Nothing to do for /home/devs/Documents/devsgh-vid.github.io/.jekyll-metadata.
           Cleaner: Removing /home/devs/Documents/devsgh-vid.github.io/.jekyll-cache...
           Cleaner: Nothing to do for .sass-cache.
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ bundle exec jekyll build --trace
Configuration file: /home/devs/Documents/devsgh-vid.github.io/_config.yml
            Source: /home/devs/Documents/devsgh-vid.github.io
       Destination: /home/devs/Documents/devsgh-vid.github.io/_site
 Incremental build: disabled. Enable with --incremental
      Generating... 
<font color="#A2734C">        Pagination: Pagination is enabled, but I couldn&apos;t find an index.html page to use as the pagination template. Skipping pagination.</font>
       Jekyll Feed: Generating feed for posts
<font color="#A2734C">          Conflict: The following destination is shared by multiple files.</font>
<font color="#A2734C">                    The written file may end up with unexpected contents.</font>
<font color="#A2734C">                    </font><font color="#2AA1B3">/home/devs/Documents/devsgh-vid.github.io/_site/feed.xml</font>
<font color="#A2734C">                     - assets/feed.xml</font>
<font color="#A2734C">                     - feed.xml</font>
<font color="#A2734C">                    </font>
                    done in 0.251 seconds.
 Auto-regeneration: disabled. Use --watch to enable.
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ rm assets/feed.xml 
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ ls _site
404.html  feed.xml    <font color="#12488B"><b>_layouts</b></font>    <font color="#12488B"><b>_sass</b></font>
<font color="#12488B"><b>assets</b></font>    <font color="#12488B"><b>_includes</b></font>   <font color="#12488B"><b>_plugins</b></font>    sitemap.xml
<font color="#12488B"><b>_data</b></font>     index.html  robots.txt
<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ bundle exec jekyll serve
Configuration file: /home/devs/Documents/devsgh-vid.github.io/_config.yml
            Source: /home/devs/Documents/devsgh-vid.github.io
       Destination: /home/devs/Documents/devsgh-vid.github.io/_site
 Incremental build: disabled. Enable with --incremental
      Generating... 
<font color="#A2734C">        Pagination: Pagination is enabled, but I couldn&apos;t find an index.html page to use as the pagination template. Skipping pagination.</font>
       Jekyll Feed: Generating feed for posts
                    done in 0.255 seconds.
 Auto-regeneration: enabled for &apos;/home/devs/Documents/devsgh-vid.github.io&apos;
    Server address: http://127.0.0.1:4000/
  Server running... press ctrl-c to stop.
[2025-08-07 17:45:47] ERROR &apos;/assets/css/main.css&apos; not found.
[2025-08-07 17:45:47] ERROR &apos;/favicon.ico&apos; not found.
[2025-08-07 17:46:03] ERROR &apos;/assets/css/main.css&apos; not found.
[2025-08-07 17:49:15] ERROR &apos;/assets/css/main.css&apos; not found.
[2025-08-07 17:49:15] ERROR &apos;/assets/css/main.css&apos; not found.
^C<font color="#26A269"><b>devs@Ubuntu-22D</b></font>:<font color="#12488B"><b>~/Documents/devsgh-vid.github.io</b></font>$ 
</pre>
