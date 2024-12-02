# Omar Derwy - Day2 Task
## how to delete branch locally and remotely
```bash
git push origin --delete dev
git push origin --delete test
git branch -d dev
git branch -d test
```
## to checkout without commit changes
```bash
git checkout -f
```
or to preserve changes in a stash before checkingout
```bash
git stash -m "Saving these files to work on them later"
```
## how to list tags
```bash
git tag
```
## to delete tag remotely and locally
```bash
git push origin --delete v1.7
git tag -d 1.7
```
## to add an image
```
![Spongbob](https://imgs.search.brave.com/MVA0tq1GyxSw0JHHpqv57g80RsbYXKGzdpXYEZK3-L8/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly9zdGF0/aWMxLnRoZWdhbWVy/aW1hZ2VzLmNvbS93/b3JkcHJlc3Mvd3At/Y29udGVudC91cGxv/YWRzLzIwMjEvMDgv/SGFuZHNvbWUtU3F1/aWR3YXJkLmpwZw)
```
![Spongbob](https://imgs.search.brave.com/MVA0tq1GyxSw0JHHpqv57g80RsbYXKGzdpXYEZK3-L8/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly9zdGF0/aWMxLnRoZWdhbWVy/aW1hZ2VzLmNvbS93/b3JkcHJlc3Mvd3At/Y29udGVudC91cGxv/YWRzLzIwMjEvMDgv/SGFuZHNvbWUtU3F1/aWR3YXJkLmpwZw)
