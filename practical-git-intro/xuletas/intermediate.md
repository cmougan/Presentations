


```
git branch mi-rama
git checkout mi-rama
```

Modify file examples/your-name.txt

```
git add examples/your-name.txt
git commit -m "My other comment"
git push --set-upstream origin mi-rama


# Go to master
git checkout master
git merge mi-rama
git push


```

