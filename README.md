# NAME

vim-build - vim builder

# SYNOPSIS

  ## install as vimenv plugin
  `git clone git://gihub.com/yasu-n/vim-build.git ~/.vimenv/plugins/vim-build`

  ## install latest version vim binary
  `vimenv install [configure-options]`

  ## change output directory( in ~/.vimenv/versions/).
  `VIM_VERSION=test vimenv install`
  vim binary was output ~/.vimenv/versions/test.

# DESCRIPTION

  vim-build is an [vimenv](https://github.com/raa0121/vimenv) plugin that
  provides an `vimenv install` command to compile and install latest version
  of vim on Unix-like systems.
