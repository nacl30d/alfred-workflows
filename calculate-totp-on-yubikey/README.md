# Calculate TOTP on Yubikey

## Required

- [ykman](https://docs.yubico.com/software/yubikey/tools/ykman/)

## Usage

### Select an entry to calculate TOTP

```.txt
yk amazon
```

- Keyword: `yk` [required]
  - The keyword to launch this workflow.
- Argument: (string) [optional]
  - Partial match search from the results.

Then, you get calculated code on your clipboard.
