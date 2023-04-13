# CC4D Website

A modified version of [Bootstrap Clean Blog Jekyll](https://github.com/StartBootstrap/startbootstrap-clean-blog-jekyll) to be used for Community Creativity 4 Development.

## Download and Installation

To run the website locally, you must first install Jekyll and git:
- [Download and install docker](https://docs.docker.com/get-docker/)
- [Download and install docker compose](https://docs.docker.com/compose/install/)
- [Download and install the latest release of git](https://git-scm.com/downloads)
    - If you are installing git for MacOS or Linux follow [these instructions to install the Git Credential Manager](https://github.com/git-ecosystem/git-credential-manager/blob/release/docs/install.md)
    - If you are installing git for Windows make sure Git Credential Manager Core is enabled.
    ![GCM image](https://user-images.githubusercontent.com/5658207/140082529-1ac133c1-0922-4a24-af03-067e27b3988b.png)

## Running the Website Locally 

- Open Command Prompt
- Navigate to desktop: `cd desktop`
- Clone the repo: `git clone https://github.com/mrponuk/CC4D.git`
    - If this is your first time cloning a repo this should bring up the Github Credential Manager, make sure to sign in.
- Navigate to the CC4D root directory: `cd CC4D`
- Run `docker compose up -d`
    - The website is now live (this may take a few minutes). Go to your browser and enter: `http://127.0.0.1:4000/CC4D/`
- To stop the website run `docker compose down`

## Bugs and Issues

Have a bug or an issue with the website? [Open a new issue](https://github.com/mrponuk/CC4D/issues) here on GitHub.
