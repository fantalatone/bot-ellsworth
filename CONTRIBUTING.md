# Contributing to ÜNOG - Ellsworth

Thank you for your interest in contributing to our Discord Bot, Codename
Ellsworth. We welcome contributions from the community! The Discord Bot is the
backbone of a Discord server, this repository holds the source code for the
newest iteration of our own bot.

## Principles

As is with community-driven projects, it should be stardard practice to keep the
codebase easily managable. Which is why we insist that our contributors must
follow the principles as stated in this document.

- **Keep it Simple:** It is common for software projects to turn into a maze for
  maintainers to manage, so this project must be documented clearly. It must
  follow standard coding practices for readability. Such as meaningful names,
  useful comments, modularized code, etc. Remember that you are not coding for
  yourself, so please don't overcomplicate a future developer's maintanence
  work.

- **Modularize Functionality:** Due to the bot's nature of handling different
  types of tasks, we should structure our code such that each functionality
  (think commands, message actions, event management, application systems, etc.)
  should be kept in seperate files. Those files must be properly named and
  categorized under distinct directories (think services, commands, functions,
  for example.) In the case of functionality that might be inseperable, it
  should be documented clearly.

- **Be Patient:** Your PR will take time for us to respond to because we test
  them in a designated test server before pushing it to production. If you want
  to be a part of our tests, contact us.

- **Take Permissions Seriously:** We try to keep our bot with the minimal amount
  of permissions possible for online safety. You can check the README for a live
  overview of which permissions we have enabled along with the functionality it
  serves. In case the bot might need extra permissions for the next commit, it
  must be documented in the PR. Keep in mind that this will take longer to
  respond to the PR as we need to discuss significant changes like these with
  our board before we come to a conclusion.

- **Easy to Port:** To not be bound to a specific machine when hosting our
  Discord bot, we will be using Docker containers to keep our project portable.
  This also allows us to implement smarter CI/CD solutions in the future.

## Tech Stack

_Disclaimer: The technologies included in this project are subject to change._

- Discord Developer Portal (Maintainers only)
- Node.js
- TypeScript
- Deployment: TBD, locally for now.
- Formatting: Prettier
- Editor: Your preferred editor (VSCode, JetBrains, Vim, etc.)
- Database: Firebase

## Getting Started

TBA

## Project Structure

todo: replace these when we actually have code Keep commands, services and other
functionality in seperate files and well categorized.

## How Can You Contribute?

You can contribute to:

- Bug fixes and performance improvements
- New commands, services, capabiltiies.
- Documentation improvements (Comments, README, CONTRIBUTING)

## Deployment

We have yet to discuss where to actually host the new Discord bot, of course we
will run it on our own machines but we will actually get a VDS by the time we
replace the old bot with the new one.
