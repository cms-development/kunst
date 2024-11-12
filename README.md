# Craft boilerplate code

Forked from [KUNST](https://github.com/ishetnogferre/KUNST) by [ishetnogferre](https://github.com/ishetnogferre)

*This is a boilerplate code. This repo is updated for Craft CMS 5*

## Cloning

```bash
git clone https://github.com/cms-development/kunst.git
```

## Installation with DDEV

### Setup

```bash
ddev start
ddev composer i
ddev craft setup/keys
```

### Importing database

First, copy the database dump from the `_snapshots` folder to the `.ddev/db_snapshots` folder.

Then run the following command:

```bash
ddev snapshot restore --latest
```

### Login

- Username: admin
- Password: retrograde