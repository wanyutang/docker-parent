# docker-parent

```bash
git submodule add https://github.com/wanyutang/docker-nodejs-website.git
git submodule add https://github.com/wanyutang/docker-compose.git
git submodule add https://github.com/wanyutang/docker-fun3w.git
git submodule update --init --recursive
```

# fix already exists in the index by submodule add

```bash
git ls-files --stage
git rm --cached [Project Name]
```

# Git Submodule 移除

```bash
git rm -fr [Project Name]
git commit -m "Remove submodule" -a
vi .git/config # 移除 facebook-php-sdk 那兩行
```