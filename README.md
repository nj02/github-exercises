## Github basic tutorial

1. Bring the repository to your local machine
```
git clone https://github.com/soniarodriguez/github-exercises.git
```

2. Move to the repository folder
```
cd github-exercises
```

3. Check the status of your local repository
```
git status
```

Expected output should be
```
On branch master
Your branch is up-to-date with 'origin/master'.
nothing to commit, working tree clean
```

4. Move to your feature branch

  4a. Create you own feature branch if you are working in a new feature, for instance, `adding-london`
  ```
  git checkout -b adding-london
  ```
  4b. Move to an existing feature branch, to work in a work-in-progress feature, for instance, `adding-march-destinations`
  ```
  adding-march-destinations 
  ```
  If you move to a feature branch, first pull the last changes in case someone else has committed something to that branch:
  ```
  git pull
  ```

5. Do some modifications to the repository. For example, add your dream destination to `index.html`

6. Add your changes to the working branch

  6a. Track all the changes
  ```
  git add .
  ```
  6b. Track the change of a file modified, for instance:
  ```
  git add index.html
  ```

7. Package your changes in a commit and label them with a meaningful message
```
git commit -m “Added Thailand destination”
  ```

8. Add your changes to the remote repository. Then, check the status
```
git push
git status
```

9. Open the browser and visit: https://github.com/soniarodriguez/github-exercises/

10. Check that your changes are under your working branch

11. When you think that your new or working feature branch is ready to by merge with master, create a pull request

12. Merge the master branch with the master branch

13. Your changes should be visible at: https://soniarodriguez.github.io/github-exercises/
