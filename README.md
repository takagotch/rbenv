### rbenv rvm - linux only, not windows
---

https://github.com/rbenv/rbenv

###### https://github.com/rbenv/ruby-build/wiki - wiki
```
// centos
yum install -y gcc-6 bzip2 openssl-devel libyaml-devel libffi-devel readline-devel zlib-devel gdbm-devel ncurses-devel

// ubuntu,devian,mint
 sudo apt-get install autoconf bison build-essential libssl-dev libyaml-dev libreadline-dev zlib1g-dev libncurses5-dev libffi-dev libgdbm-dev libdb-dev

```

https://github.com/capistrano/rbenv

```rb
# ruby
cd ~
touch .bashprofile
touch .bashrc
vi .bash_profile
eval "$(rbenv init -)"

source .bash_profile
ruby -v
rbenv --version

```

```
// git clone
// $HOME : ~/.
//

// rbenv
$HOME/.rbenv
// ruby-build
$HOME/.rbenv/plugins/ruby-build


```

```
.bash_profile
.bashrc
.profile

git clone https://github.com/sstephenson/rbenv.git ~/.rbenv       # git clone https://github.com/rbenv/rbenv.git ~/.rbenv
git clone https://github.com/sstephenson/ruby-build.git ~/.rbenv/plugins/ruby-build
git clone https://github.com/sstephenson/rbenv-gem-rehash.git ~/.rbenv/plugins/rbenv-gem-rehash

vi ~/.bashrc
export PATH="$HOME/.rbenv/bin:$PATH"
~/.rbenv/bin/rbenv init

rbenv --version
ruby --version
```

```
// windows buliding ubuntu from virtualbox
// $HOME: ~/.
//
git clone https:://github.com/rbenv/rbenv.git
echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.bashrc
eval "$(rbenv init -)"  // ~/.rbenv/bin/rbenv init




```


