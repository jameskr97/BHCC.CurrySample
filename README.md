# MathInput Sample

## Getting Started
Run `bun install` inside the directory on your 

## Important commands
```bash
bun run dev  # run development server
bun run preview # run production server
bun run build  # build production version of app 
```

## Bun Setup (locally only)

bun.lockb is a binary file. The following two commands are recommended to convert it into text, and to ensure a diff is taken correctly.

```bash
git config diff.lockb.textconv bun
git config diff.lockb.binary true
```

You can view the page by visiting `http://localhost:8080`
