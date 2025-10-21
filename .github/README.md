My CLAUDE SETUP

I am only inteested in the `.claude` directory, to hide everyting else
I use the `sparse-checkout` git feature  in my local repo:

```
git sparse-checkout init --cone
git sparse-checkout add /.claude
git sparse-checkout add /LICENSE
git sparse-checkout add /.gitignore
git sparse-checkout add /.github
```

Verify with 
```
git sparse-checkout list 
```


