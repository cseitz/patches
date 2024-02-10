[README](/README.md)

```json
  "pnpm": {
    "patchedDependencies": {
      "next@14.1.0": ".pnpm/patches/next/14.1.0/next@14.1.0.patch"
    }
  }
```

## Features

- Patches Watchpack's DirectoryWatcher with `lstat -> stat` to support symlinked pages in Next.js dev mode
