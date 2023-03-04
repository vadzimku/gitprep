`gitprep` is the tool to simplify the process of initialization of git repository including adding git hooks

## Installation

`$ brew tap vadiku/gitprep` \
`$ brew install gitprep`

## Usage

`gitprep` [`options...`]

`options`:

```
  -h | --help                       print this help message
  -v | --version                    print utility version
  -p | --path      [path]           path to git repo to prepare; if not passed current directory is used
  -n | --name      [user_name]      user name to set to git config: git config user.name <user_name>
  -e | --email     [user_email]     user email to set to git config: git config user.email <user_email>
  -t | --ticket    [ticket_regex]   regex for the ticket to extract from the branch name
  -r | --rm                         remove selected options actions
```
