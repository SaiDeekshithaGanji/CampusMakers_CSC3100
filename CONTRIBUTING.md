# Contributing to Campus Makers

## Before you start

1. Pull the latest `main` branch before beginning work.
2. Work on a branch for feature work unless the team has agreed
   that the change belongs directly on `main`.
3. Keep each commit focused and use a short, descriptive commit
   message.
4. Do not commit `node_modules`, build output, or environment
   files. These are ignored by the root `.gitignore`.

## Formatting with Prettier

Prettier is installed at the repository root. Run the formatter
before committing changes:

```sh
npm run format
```

Our shared Prettier settings use four spaces, semicolons, double
quotes, a 64-character print width, and no trailing commas. Do
not manually reformat unrelated files; formatting only files you
changed helps prevent merge conflicts.

## Linting

The React frontend uses ESLint. From the `frontend` directory,
run:

```sh
npm run lint
```

Fix lint errors before opening a pull request or pushing shared
work. Warnings should also be reviewed and addressed when
practical.

## Pull requests and shared work

- Describe what changed and how you checked it.
- Pull the latest `main` branch again before pushing.
- Resolve merge conflicts carefully; do not force-push shared
  branches.
- Review changes in Source Control before committing to make
  sure generated files and secrets are not included.

## Editor setup

Each contributor should enable Prettier formatting and ESLint
diagnostics in their editor. Configure the editor to use this
repository's `.prettierrc` and to show ESLint problems in
JavaScript and JSX files.
