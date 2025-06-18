dar git 3 stage gharar dare: 
    1. Working directory ke file haye ma dar onjast va ma morataban darim unha ro develop va avaz mikonim.
    2. stage: baad az develop un file haii ke mmikhaiim sabt beshan ro vared stage mikonim (ba dastoor "git add" be in stage ezafe mishan).
    3. commit: baad az review va taiid unha ro commit va sabt nahaii mikonim (ba dastoor "git commit" ezafe mishan).

baad az inke commit kardim va khstim az local khodemoon code haro befrestim rooye hosting service ha mitoonim az github va gitlab estefade konim (ba dastoor "git push" ferestade mishan be in hosting service ha).

baraye config git:
    1. git bash ro run mikonim.
    2. git config --global user.name "Parsa Sorsori" --> baraye sabt esm khodemoon tooye project haye ayande
    3. git config --global user.email "gwparsa@gmail.com" --> baraye sabt email khod dar project haye ayande

braye sakht yek project ba git:
    1. dar folder khod yek cmd run konid va benevisid "git init"

baraye sakht branch jadid:
    1. git branch "esm branch jadid" --> yek branch jadid misazad
    2. git checkout "esm branch" --> vorood be an branch

baraye merge kardan mohtavaye yek branch rooye master:
    1. rooye branch mster mirim.
    2. git merge "esm branchi ke mikhaii merge she roo master"
    3. git branch -d "esm branch" --> baraye hazf krdn yek branch

baraye connect va ferestadan commit ha be repository github az local git:
    1. yek repository dar github.com misazim.
    2. link remote repository ro copy mikonim.
    3. git remote add origin https://github.com/gwparsa/git-learning.git --> connect kardan repository be git
    4. git branch -M main --> tabdil kardan esm branch master be main(be khater masael nezhadparasti)
    5. git push -u origin main --> ferestadan commit haye dakhel branch main be repository github
    6. dafe haye baad faghad az git push baraye push kardan commit ha estefade mikonim

baraye ezafe kardan taghirat project rooye code haye khodemoon vaghti kas digeii code ha ro taghir dade:
    1. git pull --> kol taghirat code ha va file ha ro be project local ma ezafe mikone

baraye sakht pull request:
    1. yek branch dige besazim va code haye morede nazar ro benevisim.
    2. az dakhel hamoon branch taghirat ro commit va rooye github push mikonim.
    3. dakhel repository ye pull request jadid misazim va montazer mishim ta shakhs morede nazar un ro merge kone rooye branch main.

vaghti shoma va hamkar shoma dar hal kar rooye yek bakhsh az project hastid va motevajeh nmishid ke code ha ba ham tadakhol dare github be shoma error conflict mide. vaghti push mikonim behemoon error mide ke bayad un taghirat digari ro pull konim va baad az tasmimgiri dobare push konim.

baraye ignore ye seri file ha:
    1. yek file ba esm .gitignore misazim
    2. dakhel in file esm file ya directory haii ke nmiakhaiim git un ro dar nazar begire ro minevisim.

baraye dastresi be yek project va download un dar pc khodemoon:
    1. yek directory jadid misazim va ba git vared un mishim
    2. git clone https://github.com/... --> project rooye github ro download mikonim
    