# Works

```
$ npm i
$ npm test

> @ test issue-ava-pnpm
> ava


   2 passed
```

# Doesn't work

```
$ pnpm i
$ npm test

> @ test issue-ava-pnpm
> ava

WARNING: `npm link ava` and the `--preserve-symlink` flag are incompatible. We have detected that AVA is linked via `npm link`, and that you are using either an early version of Node 6, or the `--preserve-symlink` flag. This breaks AVA. You should upgrade to Node 6.2.0+, avoid the `--preserve-symlink` flag, or avoid using `npm link ava`.

   1 exception


   ✖ No tests found in test.js, make sure to import "ava" at the top of your test file
```
