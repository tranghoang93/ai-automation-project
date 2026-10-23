Run claude with this command:
```
ollama launch claude --model gemma4:cloud
```

npx playwright test tests/auth.spec.ts \
  --project=chromium \
  --grep "TC-SCRUM-2-01" \
  --workers=1 \
  --repeat-each=5