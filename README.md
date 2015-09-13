# NAME

vim-build - vim builder

# SYNOPSIS

```
  1. install as vimenv plugin
    $ git clone git://gihub.com/yasu-n/vim-build.git ~/.vimenv/plugins/vim-build

  2. show tagname
    $ vimenv install -l
    
    Required git command.

  3. install vim
    [latest version]
    $ vimenv install -n [-- <BUILD_OPTIONS>]
    
    [tagname version]
    $ vimenv install -t <TAG_NAME> [-- <BUILD_OPTIONS>]
    
    [tarball version]
    $ vimenv install -f vim.tar.bz2 [-- <BUILD_OPTIONS>]
  
```

# DESCRIPTION

  vim-build is an [vimenv](https://github.com/raa0121/vimenv) plugin that
  provides an `vimenv install` command to compile and install latest version
  of vim on Unix-like systems.

