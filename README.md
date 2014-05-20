# CouchDB role - Ansible


## Requirements

Tested for Ansible 1.4 and higher. Even if it has been developed for Debian systems, it is assumed to work on Ubuntu as well.


## Dependencies

- [Ansibles.erlang](https://github.com/Ansibles/erlang)


## Installation

```
$ ansible-galaxy install guillaumededrie.couchdb
```

## Variables

### Role

```yaml
erlang_version: "R16B03"

couchdb_version: "1.5.0"
couchdb_version_installed: 0 # used to compare requested version and installed
couchdb_install_method: "source" # can be "package"
```


### Source installation parameters

```yaml
couchdb_file_tag: ...
couchdb_file_name: ...
couchdb_base_url: ...
couchdb_tarball_url: ...
couchdb_shasum_url: ...
couchdb_tmp_dir: ...
```


## License

License under GPLv3. See the LICENSE file for details.


