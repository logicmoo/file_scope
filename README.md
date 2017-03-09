# file_scope
File local scoped efects


```prolog

:- pack_install('https://github.com/TeamSPoon/file_scope.git').

```


```prolog

:- use_module(library(file_scope)).

:- set_prolog_flag_until_eof(access_level,system).

:- assert_until_eof(( term_expansion(.,.) :- .. )).

```


# Some TODOs

Document this pack!
Write tests
Untangle the 'pack' install deps
Still in progress (Moving predicates over here from logicmoo_base)



[BSD 2-Clause License](LICENSE.md)

Copyright (c) 2017, 
Douglas Miles <logicmoo@gmail.com> and
TeamSPoon - All rights reserved.

# Not _obligated_ to maintain a git fork just to contribute

Dislike having tons of forks that are several commits behind the main git repo?

Be old school - Please ask to be added to TeamSPoon and Contribute directly !
Still, we wont stop you from doing it the Fork+PullRequest method




