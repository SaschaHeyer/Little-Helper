# Obfuscate logs

```bash
find . -type f -exec sed -i '' -e 's/find/replace/g' {} +
```