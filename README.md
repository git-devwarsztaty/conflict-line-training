# Conflict-line-training

Jak rozwiązywać konflikty w pliku (za pomocą kdiff3 - instrukcja konfiguracji https://krzysztofmorcinek.wordpress.com/2018/05/17/wstepna-konfiguracja-gita/#kdiff3)


## Kroki

- sklonuj to repozytorium
- przejdź na branch 'tomek-path' -> 'git checkout tomek-path'
- (po sklonowaniu ten branch będzie u Ciebie początkowo niewidoczny, ale ^powyższa^ komenda się wykona i ściągnie ten branch. Wszystkie branche zdalne można sprawdzić poleceniem 'git branch -r')
- zrób rebase aktualnego brancha na branch **master**: 'git rebase master'
