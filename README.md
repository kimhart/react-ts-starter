# React + Typescript Starter Kit

Spin up React + Typescript projects complete with basic routing setup with a top nav, component shells, and the following packages & tools installed:

- [Create React App](https://facebook.github.io/create-react-app/docs/getting-started)
- [React Query](https://react-query.tanstack.com/overview)
- [React Router](https://reactrouter.com/docs/en/v6/getting-started/overview)
- [Dart Sass](https://sass-lang.com/documentation)

## Setup

### 1. Clone this repo and remove old `.git` references:

```bash
  cd react-ts-starter
  rm -rf .git
```

### 2. Setup Your New Project
Rename your folder + app, update your `README` & `package.json`.

### 3. Point to Your New Repo

```bash
# Create new .git history with "main" branch
git init -b main

# Add and commit your files
git add .
git commit -m "first commit"

# Set origin to your new repo
git remote add origin <NEW_REMOTE_URL> (e.g: git@github.com:org/repo.git)

# Double-check the URL
git remote -v 

# Set the main branch
git branch -M main

# Push your changes
git push -u origin main
```

### 4. Install Party 🎉
```
yarn install && yarn upgrade all
```

You're ready to go!

## Development

In the project directory, you can run:

#### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

#### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

#### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.
