# `.tools` a.k.a dot-tools

A repo for all those various little tools yak shavers needed across multiple systems that is kept in `.tools/bin` and added to the `PATH`

Mostly a test now.. Will likely be integrated into my dots repo depending on direction it evolves.

### Homegrown organic tools

* [`bin/bleach`](https://gist.github.com/dayne/dde91c992771c4e590937a003dd39018) - a silly, but handy, interface to `vagrant global status` I used to check and purge running test kitchens
* [`bin/ckblock`](https://gist.github.com/dayne/dde91c992771c4e590937a003dd39018) - chef knife block checker I use in my .bash_it custom prompt

### Tools adopted from others

* [`bin/vagrant-update-all-boxes.sh`](https://gist.github.com/sc250024/05a5aa1a1ee2db02080f8714226986e9) - [sc250024](https://gist.github.com/sc250024) gist which is derived from [thom8](https://gist.github.com/thom8)'s [original gist](https://gist.github.com/thom8/791f6c9978abda5e4e84)

# Usage

```
# clone as .tools
git clone https://gist.github.com/dayne/dde91c992771c4e590937a003dd39018 .tools
# add (like this or your prefered way) to your path
echo 'export PATH=$PATH:$HOME/.tools' >> ~/.bashrc
```

# Updating

git submodules are used for some of the tools.  A full update of `dot-tools` will need the following:

```
git pull 
git submodule pull --recursive

```

# Contributors

Feel free to help improve and expand this with Pull Requests!

* [@dayne](https://github.com/dayne)
