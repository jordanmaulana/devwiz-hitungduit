# Project LinkWiz
## How to use

Please follow the steps below to run the project.

```bash
git clone git@github.com:jordanmaulana/linkwiz.git
```

```bash
cd linkwiz
```

```bash
npm install
```


```
⚠️⚠️⚠️
rename .env.example into .env and fill the credentials from your own Neon DB
⚠️⚠️⚠️
```


```bash
npm run dev
```

## How to contribute

### UI Design

- Prioritize functionality over UI design
- Use NextUI for UI components
- Use TailwindCSS for styling

### Functionality

- Create a new branch for each feature
- Create a pull request for each feature
- DO NOT merge your own pull request

## Commit Message Format

You have to follow the following format for commit message.

```bash
git commit -m "type: subject"
```

### Type

Must be one of the following:

- **feat**: A new feature
- **fix**: A bug fix
- **chore**: Changes to the build process or auxiliary tools and libraries such as documentation generation

### Subject

The subject contains succinct description of the change:

- use the imperative, present tense: “change” not “changed” nor “changes”
- don't capitalize first letter
- no dot (.) at the end

### Examples

```bash
git commit -m "feat: add login page"
```

```bash
git commit -m "fix: login page not working"
```

```bash
git commit -m "chore: update readme"
```
