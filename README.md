### Git Learning
`in Persian(Farsi)`

------

### 0. Quick Usage:
```
git init
git status
git log
---
git add .
git add "file name"
git commit -m "commit description"
---
git config --global user.name "Parsa Sorsori"
git config --global user.email "gwparsa@gmail.com"
---
git branch "esm branch jadid"
git checkout "esm branch"
git merge "esm branch"
git branch -d "esm branch"
git branch -M main
---
git remote add origin https://github.com/gwparsa/...
git push -u origin main
git push
---
git pull
---
git clone https://github.com/gwparsa/...
```

### 1. Stage haye git:</br>
1. Working directory: file haye ma dar onjast va ma morataban darim unha ro develop va taghir midim.</br>
2. stage: baad az develop un file hayi ke mmikhaim sabt beshan ro vared stage mikonim (ba command `git add` be in stage ezafe mishan).</br>
3. commit: baad az review va taiid unha ro commit va sabt nahaii mikonim (ba command `git commit` ezafe mishan).</br>
> [!NOTE]
> baad az inke commit kardim va khstim az local khodemoon code haro befrestim rooye hosting service ha mitoonim az github va gitlab estefade konim (ba dastoor `git push` ferestade mishan).

</br>

### 2. Baraye config git:</br>
faghad yekbar bayad in command ha ro dar git bash run konid:</br>
```
git config --global user.name "Parsa Sorsori"
git config --global user.email "gwparsa@gmail.com"
```
    
</br>

### 3. Sakhtar monaseb baraye commit haye git:</br>
bareye inke commit haye tamiz tar va khana tari dashte bashim, bayad az formul `"type": "tozih kootah"` estefade konim:</br>
```
git commit -m "fix: resolved the bug when user logs in"
git commit -m "style: added some button styles for navbar"

fix -> fix kardan bug
style -> taghirat zaheri
feat -> ezafe kardan ghabeliat jadid
refactor, perf -> behine sazi code bedoon taghir
docs -> taghirat mostanadat project
test -> behbood ya taghir test ha
chore -> peykarbandi build ha va kar haye janebi
```

</br>

### 4. Baraye sakht yek project ba git:</br>
dar folder khod yek cmd baz konid va command zir ra run konid:</br>
```
git init
```
    
</br>

### 5. Baraye sakht branch jadid:</br>
```
git branch "esm branch jadid" --> yek branch jadid misazad.
git checkout "esm branch" --> vorood be yek branch.
```

</br>

### 6. Baraye merge kardan mohtavaye yek branch rooye master:</br>
be branch main mirim:
```
git merge "esm branch" --> baraye merge kardan yek branch rooye main.
git branch -d "esm branch" --> baraye hazf krdn yek branch.
```

</br>

### 7. Baraye connect va ferestadan commit ha be repository Github:</br>
yek repository dar github.com misazim, link remote repository ro copy mikonim:
```
git remote add origin https://github.com/gwparsa/git-learning.git -> connect kardan repository be local git.
git branch -M main -> tabdil kardan esm branch master be main(be khater masael nezhadparasti).
git push -u origin main -> ferestadan commit haye dakhel branch main be repository github baraye avalin bar.
git push -> dafe haye baad faghad ba in command commit haro push mikonim.
```

</br>

### 8. Baraye ezafe kardan taghirat project rooye code haye khodemoon vaghti kas digeii code ha ro taghir dade:</br>
```
git pull --> kol taghirat code ha va file ha ro be project local ma ezafe mikone.
```

</br>

### 9. Baraye sakht pull request:</br>
1. yek branch dige besazim va code haye morede nazar ro benevisim.</br>
2. az dakhel hamoon branch taghirat ro commit va rooye github push mikonim.</br>
3. dakhel repository ye pull request jadid misazim va montazer mishim ta shakhs morede nazar un ro merge kone rooye branch main.</br>

> [!NOTE]
> vaghti shoma va hamkar shoma dar hal kar rooye yek bakhsh az project hastid va motevajeh nmishid ke code ha ba ham tadakhol dare github be shoma error conflict mide. vaghti push mikonim behemoon error mide ke bayad un taghirat digari ro pull konim va baad az tasmimgiri dobare push konim.

</br>

### 10. gitignore file:
1. yek file ba esm .gitignore misazim.
2. dakhel in file esm file ya directory hayi ke nmiakhaiim git un ro dar nazar begire ro minevisim.

</br>

### 11. Baraye dastresi be yek project va download un dar pc khodemoon:
yek directory jadid misazim va ba git vared un mishim:
```
git clone https://github.com/... --> project rooye github ro download mikonim.
```
