# pages-password
Password-protected GitHub pages

## Make hash directory

```
$ node mkdir.js yourpassword
"docs/e3c652f0ba0b4801205814f8b6bc49672c4c74e25b497770bb89b22cdeb4e951" is created.
```

### if not given password

```bash
$ node mkdir.js
Error: No password provided.
```
### if existing password

```bash
$ node mkdir.js yourpassword
"docs/e3c652f0ba0b4801205814f8b6bc49672c4c74e25b497770bb89b22cdeb4e951" already exists.
```
