#kif
A simple system for remote encrypted backups.

##Setup

  * Copy `kifrc` to `~/.kifrc` on the client
  * Edit `kifrc` and set the values inside
  * On the host machine, `mkdir -p ~/kif/store`
  * Copy `kif.schema` to the host and use it to create an SQLite3 database at `~/kif/kif.db`

You should now be ready to go.

