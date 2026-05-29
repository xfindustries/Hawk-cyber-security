# Hawk-cyber-security

Hawk Cybersecurity website

## Steps to rebuild css each push

- Any time you edit HTML and add new Tailwind classes, re-run the build before pushing:

```bash
./tailwindcss -i ./input.css -o assets/css/hawk.css --minify

# Short command
npm run build
```

- Run `--watch` while editing so it rebuilds automatically

```bash
./tailwindcss -i ./input.css -o assets/css/hawk.css --watch

# short command
npm run watch
```
