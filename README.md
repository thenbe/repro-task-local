### PNPM

```bash
# this fails silently. Running the test script shows that the binary is not found
rm -rf node_modules && pnpm install && pnpm test

# look for a binary named "task"
pnpm test
```

# NPM

```bash
# exits with error
rm -rf node_modules && npm install
```
