# Kurs GIT dla koła naukowego SOIP

## Co to git?

Rozproszony system kontroli wersji!

### Instalacja

- [git-scm.com](https://git-scm.com/install/)
- [github.com](https://github.com/git-guides/install-git)

### Konfiguracja

- [GitHub CLI](https://cli.github.com/manual/gh)
Połączenie konta GitHub i Git - `gh auth login`
Sprawdzenie statusu - `gh auth status`

## Podstawy

### `git init`

Polecenie tworzy puste repozytorium git we wskazanym katalogu. Tworzony jest ukryty plik `.git`, który przechowuje wszystkie informacje o repozytorium. Git przechowuje pliki całościowo, aby łatwiej było je odtworzyć. 
Git opiera się na wskaźnikach na konkretne migawki - `HEAD` pokazuje na jakiej zmianie jest obecnie użytkownik, natomiast np. `feat/new-page` informuje nas o gałęzi (serii migawek). Każda migawka zawiera wskaźnik do poprzedniej migawki.

### `git add`

Domyślnie pliki nie są śledzone. Programista musi wskazać systemowi, które pliki ma śledzić. Do tego służy polecenie `git add`.

### `git commit`

Pliki z poczekalni są utrwalane w migawce. 

### `git status`

Sprawdzenie statusu repozytorium.

### `git branch`

Sprawdzenie gałęzi w projekcie. 

### `git checkout`

Przełączenie się na gałąź w projekcie.

### `git push | git pull | git fetch`

#### `git push --force`

### `git reset`

## Zdalne repozytoria

### GitHub

GitHub to nie jest Git! Jest to platforma do zarządzania repozytoriami .git. Umożliwia:
- przechowywanie repozytoriów zdalnie
- udzielanie dostępu do repozytoriów
- wdrażanie i łączenie zmian w projekcie
- ...

#### Stworzenie publicznego repozytorium

#### Stworzenie prywatnego repozytorium i dodanie użytkowników

#### Wstawianie zmian na zdalny serwer

#### Praca na gałęziach

### GitLab

### GitGud.io'

### Origin

### Co to jest Pull Request?

### `git merge` vs `git rebase`

## GitFlow

## Aplikacje graficzne

### GitHub Desktop

### Gitk

### LazyGit

### JetBrains/VSCode

# Autorzy

- Kamil "Kamyk2003" Kosior
- Kacper "DScraftPL" Wiącek
