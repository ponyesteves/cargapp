# Carga Usage

* Clone This Repo

* Replace globally carga with newName
* Replace globally carga with newname
* Replace globally Carga with NewName
* Manually rename file and folder lib/carga_web to lib/newName_web
* Manually rename file and folder lib/carga to lib/newName
* Manually rename file and folder test/carga_web to test/newName_web
* Manually rename file and folder test/carga to test/newName_web


* cd assets
* npm install
* Create .gitignore with this content

```bash
# App artifacts
/_build
/db
/deps
/*.ez

priv/static/
node_modules

# Generated on crash by the VM
erl_crash.dump

# Files matching config/*.secret.exs pattern contain sensitive
# data and you should not commit them into version control.
#
# Alternatively, you may comment the line below and commit the
# secrets files as long as you replace their contents by environment
# variables.
/config/*.secret.exs
```
* Create Git Repo
* Remove .git folder
* Push to github

# Start Server
To start your Phoenix server:

  * Install dependencies with `mix deps.get`
  * Create and migrate your database with `mix ecto.create && mix ecto.migrate`
  * Start Phoenix endpoint with `mix phx.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.

Ready to run in production? Please [check our deployment guides](http://www.phoenixframework.org/docs/deployment).

## Learn more

  * Official website: http://www.phoenixframework.org/
  * Guides: http://phoenixframework.org/docs/overview
  * Docs: https://hexdocs.pm/phoenix
  * Mailing list: http://groups.google.com/group/phoenix-talk
  * Source: https://github.com/phoenixframework/phoenix
