# Setup

Make sure you have installed/configured:

- git http://git-scm.com/downloads
- Node.js 18 < https://github.com/nvm-sh/nvm
- Docker https://docs.docker.com/engine/install/
- React Developer Tools https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi
- VSCode or other code editor of your choice https://code.visualstudio.com/download
    - Prettier https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode
    - ESlint https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint
    - SASS https://marketplace.visualstudio.com/items?itemName=mrmlnc.vscode-scss
- Slack https://slack.com/downloads
- GitHub account with configured keys https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account

Check if all of them work correctly:

- `git --version`
- `node --version`
- `npm --version`
- `docker run --name some-postgres -e POSTGRES_PASSWORD=mysecretpassword -d postgres`

Windows:
- https://docs.microsoft.com/en-us/windows/wsl/install-win10
- https://docs.microsoft.com/en-us/windows/nodejs/setup-on-wsl2
