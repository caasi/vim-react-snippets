vim-react-snippets
==================

A set of snippets for Vim to work with Facebook's [React](http://facebook.github.io/react/) library in ES6.

A direct port of the awesome snippets from 
[jgebhardt/sublime-react](https://github.com/jgebhardt/sublime-react).

Requires [vim-snipmate](https://github.com/garbas/vim-snipmate).

Installation
============

Use your preferred Vim plugin installation method.
I like [Vundle](http://github.com/gmarik/vundle), but other options like
[pathogen](https://github.com/tpope/vim-pathogen) should work fine as well.

If you're using Vundle, and you don't currently have SnipMate, you will need to
add the following to your `.vimrc` (taken from the [SnipMate README](https://github.com/garbas/vim-snipmate/blob/master/README.md)):

```
" vim-react-snippets:
Plugin "caasi/vim-react-snippets"

" SnipMate and its dependencies:
Plugin "MarcWeber/vim-addon-mw-utils"
Plugin "tomtom/tlib_vim"
Plugin "garbas/vim-snipmate"

" Other sets of snippets (optional):
Plugin "honza/vim-snippets"
```

Usage
=====

Within any Javascript or JSX file, you should be able to do the following:

(in insert mode)
```
gdp<Tab>
```

expanding to

```
getDefaultProps: function() {
    return {

    };
},
```

And a bunch of others!
Check `snippets/javascript.snippets` to see the full list.
