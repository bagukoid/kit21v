# kit21v
test repo

Проверка работы с git
-- Login as it to linux
cd 

ssh-keygen -t ed25519 -C "vadim.veeremaa@tptlive.ee"
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_ed25519
-- Copy public key content from file ~/.ssh/id_ed25519 to github.com "Security->Deploy keys-> Add deploy key"
-- Paste copied key to big text windiws and name it in above row
git clone git@github.com:bagukoid/kit21v.git
-- new folder is created with repo files from github.com from user=baguka and repo=kit21v

-- add some files it add . && git commit -m "initial commit"
touch aaa.py
-- put some content to it
git add . && git commit -m "initial commit"
git push
