```bash
git submodule add --name pnpm-patches https://github.com/cseitz/patches ./.pnpm/patches
```

```json
  "pnpm": {
    "patchedDependencies": {
      "next@14.1.0": ".pnpm/patches/next/14.1.0/next@14.1.0.patch"
    }
  }
```
