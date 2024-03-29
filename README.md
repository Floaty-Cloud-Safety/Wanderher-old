### Getting Started

npm install - Will install all dependencies outlined in package.json
npm start - Will start the server

### Dev Tools
* ESLint, install it using (`npm i -g eslint`)
* NVM (Node Version Manager), we are all using Node.js on v8.11.1

### Building for production

npm run build (creates a dist folder)


### Git Control
Fork the github repository to your own repository.

Follow the following to submit a pull requests
1. Create a feature branch on your own repo (`Git branch {Team}-{label}-name-of-your-branch`)
2. Switch to feature branch (`Git checkout name-of-your-branch`)
3. Make changes as your assigned (`Remember update changelog.md`)
4. Stash your changes (`git stash`)
5. Sync your local repo with team develop (`git pull upstream develop`)
6. Apply the stashed changes (`git stash apply`)
7. Resolve any merge conflicts
8. Commit your change with signing (`git -S -m "Commit messages`)
9. push your local repo to your personal repo (`git push --set-upstream origin {feature/fix}-name-of-your-branch`)
10. Create a pull request on github from your personal repo

