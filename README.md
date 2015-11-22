Please note that one must change the solarized theme as per:
https://github.com/altercation/vim-colors-solarized/issues/130

 elseif g:solarized_termcolors != 256 && &t_Co >= 16
needs to be
 elseif g:solarized_termcolors != 256 && &t_Co >= 8
