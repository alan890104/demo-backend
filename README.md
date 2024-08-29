# How to use yarn link


## 1. Install the package
```bash
yarn link ../local/path/to/package
```

## 2. Add devDependencies for the package
```json
{
  "devDependencies": {
    "YourPackageName": "*"
  }
}
```