# GIT CHEAT SHEET

## Porcelain commands

###  CREATE REPOSITORIES

<dl>
    <dt>git init</dt>
    <dd>Create a new local resository</dd>
    <dt>git clone [url]</dt>
    <dd>Download a project</dd>
</dl>

###  TRACKING CHANGES

<dl>
    <dt>git add [file/folder]</dt>
    <dd>Prepare the file or folder to commit</dd>
    <dt>git status</dt>
    <dd>Show all modification to be committed</dd>
    <dt>git commit -m "[message]"</dt>
    <dd></dd>
</dl>




```
git add [file]
```

```
git status
```

```
git commit
```

```
git push
```

```
git pull
```

```
git branch
```

```
git checkout
```

```
git merge
```

```
git rebase
```
## Plumbing commands

```
git cat-file -p [hash]
```

```
git hash-object
```

```
echo 'Git Cheat Sheet' | git hash-object --stdin
```

```
git count-ojects
```

```
git show-ref [branch]
```
```
 git commit
 ``` 
| Adiciona uma marcador par ser rastreado


<dl>
    <dt>Bread</dt>
    <dd>A baked food made of flour.</dd>
    <dt>Coffee</dt>
    <dd>A drink made from roasted coffee beans.</dd>
</dl>

<style> 
dl > *{
    margin: 0;
    padding: 8px 12px;
    display: block;
}

dt{
    background-color: #E8E8E8;
    font-weight: 600;
}

dt::before{
    content: "\0024 ";    
    padding-right: 8px;
}

dd{
    background-color: #F8F8F8;
    border-bottom: 1px solid #BEBEBE;
}
</style>
