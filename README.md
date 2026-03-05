# github_neto_hw_git

## changed 1
[**`First commit link`**](https://github.com/eldyear/github_neto_hw_git/commit/3adf9368a40de5d076fce75b0e59759aca03f3e6)
[**`gitignore added/modified`**](https://github.com/eldyear/github_neto_hw_git/commit/92fc32a7b22375ca068774bfa99b8815ee70b4eb)
[**`Network graph`**](https://github.com/eldyear/github_neto_hw_git/network)

Не вижу в `GitHub Networks` ответвления и слияния от ветки `conflict` хотя вижу в `git log --graph`
```zsh
eldyear@Macbook--eldyear github_neto_hw_git % git log --graph
*   commit 9e958ebda99c6d40ac89b9c16b54bdce08871271 (HEAD -> main, origin/main, origin/HEAD)
|\  Merge: 2eadc4d 56c99c7
| | Author: eldyear <eldyear@yandex.ru>
| | Date:   Fri Mar 6 00:31:23 2026 +0600
| |
| |     choosen theirs
| |
| * commit 56c99c75e479cca922f5ce2da3a261de2bc2ecd2 (origin/conflict, conflict)
| | Author: eldyear <eldyear@yandex.ru>
| | Date:   Fri Mar 6 00:29:52 2026 +0600
| |
| |     conflict_4
| |
* | commit 2eadc4d974e63c2eee7ab0b2146fd78089798b1e
| | Author: eldyear <eldyear@yandex.ru>
| | Date:   Fri Mar 6 00:28:27 2026 +0600
| |
| |     conflict_3
| |
* | commit 115930414ece1b79662750109db2fa51401e2325
|\| Merge: 71fd0a8 4756ce2
| | Author: eldyear <eldyear@yandex.ru>
| | Date:   Fri Mar 6 00:17:09 2026 +0600
| |
| |     theirs
| |
| * commit 4756ce2db2a243a173d184393e112de36319dee3
| | Author: eldyear <eldyear@yandex.ru>
| | Date:   Fri Mar 6 00:10:11 2026 +0600
| |
| |     testing conflict_2
| |
* | commit 71fd0a824f24ce31cab20b7e82099d0faba9089a
| | Author: eldyear <eldyear@yandex.ru>
| | Date:   Fri Mar 6 00:11:21 2026 +0600
| |
| |     testing conflict_3
| |
* | commit 0084b63c2680374ebe5be7cb86867d1a2f41c4c1
|\| Merge: 71e8136 c8bf8f0
| | Author: eldyear <eldyear@yandex.ru>
| | Date:   Fri Mar 6 00:08:05 2026 +0600
| |
| |     Merge branch 'conflict'
| |     merging?
| |
| * commit c8bf8f0ff35ef8addd998cf5ce9b13e273e38cc5
| | Author: eldyear <eldyear@yandex.ru>
| | Date:   Fri Mar 6 00:00:08 2026 +0600
| |
| |     testing conficts
| |
* | commit 71e81361572472a79da73a0c5e9e6f1e5b893014
|/  Author: eldyear <eldyear@yandex.ru>
|   Date:   Fri Mar 6 00:07:33 2026 +0600
|
|       testing conflicts
|
* commit b0c603eaf6ee89f548a9edb4fdffdf6bcd737df6
| Author: eldyear <eldyear@yandex.ru>
| Date:   Thu Mar 5 23:56:44 2026 +0600
|
|     added url to Network graph in README.md
|
*   commit e0d1d2ab0729595ae3405e5918c5c5cd3b253102
|\  Merge: 39045df ffa8a44
| | Author: eldyear <eldyear@yandex.ru>
| | Date:   Thu Mar 5 23:46:04 2026 +0600
| |
| |     Merge branch 'dev'
| |     Hello! This is my first merge
| |
| * commit ffa8a449f41786c2ed78817c9b4e25439bdecba5 (origin/dev, dev)
| | Author: eldyear <eldyear@yandex.ru>
| | Date:   Thu Mar 5 23:42:03 2026 +0600
| |
| |     test.sh modified test_5
| |
| * commit 22e439646b6a6d8616daf91307fb9b43cca5c86a
| | Author: eldyear <eldyear@yandex.ru>
| | Date:   Thu Mar 5 23:41:01 2026 +0600
| |
| |     test.sh modified test_4
| |
| * commit 9fd44c3ad7e4bc2eed7311d11d76376b427c8ff0
| | Author: eldyear <eldyear@yandex.ru>
| | Date:   Thu Mar 5 23:39:57 2026 +0600
| |
| |     test.sh created
| |
* | commit 39045df0db5ba60ce5ff919062aed36a5f4acea3
|/  Author: eldyear <eldyear@yandex.ru>
|   Date:   Thu Mar 5 23:44:30 2026 +0600
|
|       main.sh added
|
* commit 573600c168ee9fa19c27da78cc80df60a742722f
| Author: eldyear <eldyear@yandex.ru>
| Date:   Thu Mar 5 23:33:27 2026 +0600
|
|     added url to commit gitignore
|
* commit 92fc32a7b22375ca068774bfa99b8815ee70b4eb
| Author: eldyear <eldyear@yandex.ru>
| Date:   Thu Mar 5 23:30:23 2026 +0600
|
|     gitignore added/modified
|
* commit be98b14d5dd5bcf43e22ee31d3962686afc904b7
| Author: eldyear <eldyear@yandex.ru>
| Date:   Thu Mar 5 23:19:17 2026 +0600
|
|     First commit to First commit
|
* commit 3adf9368a40de5d076fce75b0e59759aca03f3e6
| Author: eldyear <eldyear@yandex.ru>
| Date:   Thu Mar 5 23:12:11 2026 +0600
|
|     First commit
|
* commit 2bdecc45bab76f2ceddc6df128fe55aa10af364d
  Author: eldyear <eldyear.akmat@gmail.com>
  Date:   Thu Mar 5 23:06:15 2026 +0600

      Initial commit
```