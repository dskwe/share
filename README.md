# What's Git
* Version Control System， VCS
* content-addressable
* BLOB Tree commit
```
Key = sha1(file_header + file_content)

Value = zlib(file_content)
```
* benefit vs svn(or other traditional cvs)
```
1.Distribution
2.Branch
```
* Author: Linus(version 1 two week, 2005)
# Git commands

### Frequent use for everyone:
* add       
* branch    
* checkout   
* clone     
* commit    
* diff      
* fetch     
* merge     
* pull      
* push      
* log       
* status     
### Frequent use for me:
* stash
* stash pop
### Maybe useful:
* blame
* rebase     Forward-port local commits to the updated upstream head
* reset      
* grep       
* init       
* mv          
* rm         
* show       
* tag        


# Practice

### E1
```
git init --bare share.git
```
### E2
```
git clone url
```
### E3
```
git checkout -b test
```
### E4
```
vim .gitignore
git add
git commit -m'First commit'
git push origin test:test
```
### E5
```
git reset
```
### E6
```
git diff
git merge
```
### E7
```
git blame
```
### E8
```
git pull
git push
```
