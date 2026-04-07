# 使用方法
```bash
gpg --import public
gpg --verify test.txt.asc test.txt
# 看到 Good signature from .... 就證明這個簽署確實是屬於此公鑰對應的私鑰的持有者本人簽署的
```