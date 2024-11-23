git clone https://github.com/ELGOUMRIYASSINE/ODC_TASK.git 


![Capture](https://github.com/user-attachments/assets/7246581a-9678-4ebb-acf7-a99cd040f967)


git checkout -b master 
mkdir TASK1 
cd TASK1 
touch README.md 


![2](https://github.com/user-attachments/assets/b3dde49c-88c7-4766-8e37-8ae5f521cabd)


cd ..
git add TASK1 


![3](https://github.com/user-attachments/assets/f37aec20-58c7-4796-9bac-17891369774d)


git commit -m "add TASK1>README.file to master branch"
git push origin master 


![4](https://github.com/user-attachments/assets/e66d3e57-058f-49f1-b20b-08622d34e05a)


git checkout -b dev 
touch test.txt 
git add test.txt 
git commit -m "add test.txt file to dev branch"
git push origin dev


![5](https://github.com/user-attachments/assets/d149d16e-f245-4bd4-accd-01cfaab34843)



FOR /F "tokens=*" %u IN ('git config user.name') DO git checkout -b %u-new_feature 


![6](https://github.com/user-attachments/assets/25f7ce59-48fa-4500-9578-f89b86475d37)


touch README.md
git add README.md 
git status


![7](https://github.com/user-attachments/assets/c16649bf-9078-4c2d-8416-7ab3e5f80e31)


echo ".*" > .gitignore 
git add .gitignore 
git commit -m "add README.md add .gitignore files to yassine-new_feature branch" 


![8](https://github.com/user-attachments/assets/98a86909-bd8c-4d9f-aa38-d33c8bf1dc61)


git push origin yassine-new_feature 


![9](https://github.com/user-attachments/assets/bbdad8ab-d649-450b-9140-79ac3785c955)


. Create Pull Request to the dev branch.


![10](https://github.com/user-attachments/assets/640f1ae8-cdb4-4a35-ad01-51bf303783b7)


Merge your branch with the dev


![11](https://github.com/user-attachments/assets/8c0ffec6-ceef-4b8e-b498-b6b301154fd2)


create Pull Request to the master branch.


![12](https://github.com/user-attachments/assets/646764eb-3f6d-49a2-81ee-527736aa691a)


Merge dev with master. 


![13](https://github.com/user-attachments/assets/d98d0f01-0ce6-4bd2-af2e-0e45e25e58c5)


git pull 
echo "changes two" > README.md 
git add README.md 
git commit -m "add changes to the README.md file in yassine-new_feature branch"


![14](https://github.com/user-attachments/assets/d845b389-bbf9-4fdc-b169-e2c51c5c493d)


git revert HEAD 


![15](https://github.com/user-attachments/assets/e8e21ab6-2119-46c4-976c-37a3b9785cf2)


git log > log.txt 


![16](https://github.com/user-attachments/assets/260d1959-9184-4572-b526-4cd103028225)


git add log.txt 

git branch -D yassine-new_feature 

git push origin --delete yassine-new_feature

git push 
















