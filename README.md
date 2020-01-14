Git Basic Command
Description: Git Basic CommandMarch 2, 2019

Basic Command

git init :- Initialize A Local Git Repository.
git clone ssh://git@github.com/[username]/[repository-name].git :- Create A Local Copy Of A Remote Repository.
git status :- Check status.
git add [file-name] :- Add A File To The Staging Area.
git add -A :- Add All New And Changed Files To The Staging Area.
git commit -m [commit message] :- Commit Changes.
git rm -r [file-name/Dir-name] :- Remove A File (or Folder).
git branch :- List Branches.
git branch -a :- List All Branches.
git branch [branch-name] :- Create A New Branch.
git branch -d [branch-name] :- Delete A Branch.
git push origin --delete [branch-Name] :- Delete A Remote Branch.
git checkout -b [branch-name] :- Create A New Branch And Switch To It.
git checkout -b [branch-name] origin/[branch-name] :- Clone A Remote Branch And Switch To It.
git checkout [branch-name] :- Switch To A Branch.
git checkout [file-name] :- Discard Changes To A File.
git merge [branch-name] :- Merge A Branch Into The Active Branch.
git merge [source-branch] [target-branch] :- Merge A Branch Into A Target Branch.
git stash :- Stash Changes In A Dirty Working Directory.
git stash clear :- Remove All Stashed Entries.
git push origin [branch-name] :- Push A Branch To Your Remote Repository.
git push -u origin [branch-name] :- Push Changes To Remote Repository And Remember The Branch.
git pull origin [branch-name] :- Pull Changes From Remote Repository.
git pull --rebase [branch-name] :- Pull Changes From Remote Repository.
git log :- View changes.
git diff [source-branch] [target-branch] :- Preview Changes Before Merging.
git diff :- Preview Current Changes Before Merging.
git checkout HEAD -- my-file.txt :- To reset file.
