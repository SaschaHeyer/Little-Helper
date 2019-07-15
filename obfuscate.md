# Obfuscate logs

## Replace text
```bash
find . -type f -exec sed -i '' -e 's/find/obfuscated/g' {} +
```

## Remove urls
```bash
find . -type f -exec sed -i '' -e 's/http[^ ]*/obfuscated/g' {} +
```

