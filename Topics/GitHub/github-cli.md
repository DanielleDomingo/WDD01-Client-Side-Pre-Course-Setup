# GitHub Command Line Interface

GitHub provides a handy command-line interface that helps you connect your computer to GitHub, and also makes some configuration easy

## Install the GitHub CLI

Install the [GitHub CLI](https://github.com/cli/cli#installation) for your operating system

## Login to the GitHub CLI

Once installed, open your Terminal, and login to GitHub.

```shell
gh auth login
```

Follow the prompts and provide the following answers to the prompts:

- **What account do you want to log into?** GitHub.com
- **What is your preferred protocol for Git operations?** SSH
- **Generate a new SSH key to add to your GitHub account?** Yes
- **Enter a passphrase for your new SSH key (Optional)** (push enter)
- **How would you like to authenticate GitHub CLI?** Login with a web browser

You can also watch the [tutorial video for the GitHub CLI](https://www.loom.com/share/96e4794d3ec6475285d23781bcdeef3e)

Once you've completed the steps above, open your terminal / command-line and type `ssh -T git@github.com` 

- You may or may not have a message that comes up at this point saying `The authenticity of host github.com (##) can't be established. Are you sure you want to continue connecting (yes/no/fingerprint)?`  If this happens, just type `yes`.


**You should then see a response that says something like: "Hi [YOUR GITHUB USERNAME]! You've successfully authenticated, but GitHub does not provide shell access."**

## Set VS Code as your default Git editor

Sometimes when using git you need to tell it what to do in a code editor. We need to configure git to use VS Code as it's code editor. 

Type the following command into your terminal:

```shell
gh config set editor code
```
