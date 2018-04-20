# network-engine

This role provides the foundation for building network roles by providing
modules and plugins that are common to all Ansible Network roles.  All of
the artifacts in this role can be used independent of the platform that is
being managed.

Any open bugs and/or feature requests are tracked in [GitHub issues](../../issues).

Interested in contributing to this role, please see [CONTRIBUTING](CONTRIBUTING.md)

## Documentation

* User guide: [[Parser Directives]](docs/directives/parser_directives.md)
* Development guide: [[How to test]](docs/tests/test_guide.md)

For module documentation see the [modules](#modules) section.

## Requirements

* Ansible 2.5.0 (or higher)

## Tasks

The following are the available tasks provided by this role for use in
playbooks.

None

## Variables

The following are the list of variables this role accepts

None

## Modules

The following is a list of modules that are provided by this role.

* `cli` [[source]](action_plugin/cli.py)
* `text_parser` [[source]](library/text_parser.py)
* `textfsm` [[source]](library/textfsm.py)

## Plugins

The following is a list of plugins that are provided by this role.

### Lookup

* `json_template` [[source]](lookup_plugins/json_template.py)

## Dependencies

The following is the list of dependencies on other roles this role requires.

None

## License

GPLv3

## Author Information

Ansible Network Engineering Team
