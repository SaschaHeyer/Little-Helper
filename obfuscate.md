# Obfuscate logs

## Replace text
```bash
find . -type f -exec sed -i '' -e 's/find/replace/g' {} +
```

## Remove urls
```bash
. -type f -exec sed -i '' -e 's/http[^ ]*//g' {} +
```

