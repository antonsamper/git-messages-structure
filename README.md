# git-messages-structure
An opinionated format for git commit messages

The format for git commit messages is as follows: `action(area): message`. The **area** is the part of the project your commit relates to, for example a component name - use a '*' for something that affects everything

## Actions
* `feat` - general work that is noticeable via the project's intended audience (ie. if it's a website, something that affects something visible)
* `fix` - something that fixes something
* `chore` - general work that does not affect the the project's intended audience (back end stuff, etc.)
* `refactor` - any refactoring work (i.e. nothing is added - stuff is moved around)
* `docs` - documentation
* `note` - internal commenting
* `todo` - added todo tags
* `bug` - added bug tags
* `hack` - added hack tags (and/or did something hack-y that's meant to be replaced later)

## Examples
* `feat(posts): admin can now create posts`
* `fix(login): fixed bug with login form`
* `chore(*): done some laborious upgraded to something that affects everything`
* `refactor(navbar): moved the navbar into its own partial view file`
* `semantics(*): added a load of comments`
* `hack(ideas): i'm not happy with this, but it works (for now)`
* `docs(*): added comments about comments about comments about...`
* `todo(blog): remove things that aren't supposed to be there`
