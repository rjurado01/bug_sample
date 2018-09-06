# Reproduce

Commands:

```
cd client

yarn install

cd ..

rails c
```

Output:

```
** ERROR: directory is already being watched! **

Directory: /home/.../bug_sample/client/node_modules/.bin/mini-css-extract-plugin

is already being watched through: /home/.../bug_sample/client/node_modules/mini-css-extract-plugin

MORE INFO: https://github.com/guard/listen/wiki/Duplicate-directory-errors
** ERROR: directory is already being watched! **

Directory: /home/.../bug_sample/client/node_modules/.bin/file-loader

is already being watched through: /home/.../bug_sample/client/node_modules/file-loader

MORE INFO: https://github.com/guard/listen/wiki/Duplicate-directory-errors
Loading development environment (Rails 5.2.1)
```
