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


TODO Document this pack!


