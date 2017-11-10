# Ansible Role: teamviewer-quicksupport

## Description

Ansible Role which TeamViewer QS stores on all desktops.

## Installation

```
$ ansible-galaxy install sbaerlocher.teamviewer-quicksupport
```

## Requirements

None

## Role Variables

| Variable             | Default     | Comments (type)                                   |
| :---                 | :---        | :---                                              |
| teamviewer_quicksupport_url | "https://download.teamviewer.com/download/TeamViewerQS.exe" | |
| teamviewer_path | "C:\{{ windows_managet_folder | default('Source') }}\Tools\TeamViewerQS.exe" | |

## Dependencies

None

## Example Playbook

```yml
- hosts: all
  roles:
     - sbaerlocher.teamviewer-quicksupport
```

## Changelog

## Author

* [Simon Bärlocher](https://sbaerlocher.ch)
 
## License

This project is under the MIT License. See the [LICENSE](https://sbaerlo.ch/licence) file for the full license text.

## Copyright

(c) 2017, Simon Bärlocher