> git branch
```
  develop
  featureA
  featureB
  hotfix
* main
  release
```

> git log --graph --decorate --oneline
```
* 6b0ca6f (HEAD -> main, origin/main) Adicionar ARQUIVO21.txt
*   6fada53 (origin/develop, develop) Merge branch 'featureB' into develop
|\  
| * 3cb2581 (origin/featureB, featureB) Adicionar ARQUIVO20.txt
| * eeefcd7 Adicionar ARQUIVO19.txt
| * 6fea908 Adicionar ARQUIVO14.txt
| * 8164b57 Adicionar ARQUIVO11.txt
| * baf1cce Adicionar ARQUIVO10.txt
| * b7df61d Adicionar ARQUIVO06.txt
| * 37badde Adicionar ARQUIVO05.txt
* | b50ae74 (origin/release, release) Adicionar ARQUIVO18.txt
* |   7cb7fd8 Merge branch 'main' into release
|\ \  
| * | a86ea5e Adicionar ARQUIVO17.txt
* | | 31f7fec Adicionar ARQUIVO16.txt
* | | f3b2540 Adicionar ARQUIVO15.txt
* | |   2352169 Merge branch 'featureA' into develop
|\ \ \  
| * | | 0358d0f (origin/featureA, featureA) Adicionar ARQUIVO13.txt
| * | | 7603b26 Adicionar ARQUIVO12.txt
* | | |   74206b2 Merge branch 'hotfix' into develop
|\ \ \ \  
| |/ / /  
|/| / /   
| |/ /    
| * | 51a4791 (origin/hotfix, hotfix) Adicionar ARQUIVO08.txt
| * | 4bcf03d Adicionar ARQUIVO07.txt
* | | d4b7bdd Adicionar ARQUIVO09.txt
| |/  
|/|   
* | 9ad0197 Adicionar ARQUIVO04.txt
|/  
* 2d921f0 Adicionar ARQUIVO03.txt
* 2ee1f73 Adicionar ARQUIVO02.txt
* 31652ef Adicionar ARQUIVO01.txt
```
