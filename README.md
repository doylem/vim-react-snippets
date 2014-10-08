vim-react-snippets
==================

A set of snippets for Vim to work with Facebook's [React](http://facebook.github.io/react/) library.

A direct port of the awesome snippets from 
[jgebhardt/sublime-react](https://github.com/jgebhardt/sublime-react).

Requires [vim-snipmate](https://github.com/garbas/vim-snipmate).

Installation
============

Use your preferred Vim plugin installation method. I use [pathogen](https://github.com/tpope/vim-pathogen).


Usage
=====

Within any Javascript, JSX or CJSX file, you should be able to do the following:

(in insert mode)
```
gdp<Tab>
```

expanding to (JSX)
```
getDefaultProps: function() {
  return {
    $1
  };
},
```

or (CJSX)
```
getDefaultProps: ->
  $1
```

And a bunch of others!
Check `snippets/javascript.snippets` and `snippets/coffee.snippets` to see the full list.
