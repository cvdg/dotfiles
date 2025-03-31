# dotfiles

Manage my personal dotfiles with `ansible`.

```shell
$ ansible-pull -o -U https://www.github.com/cvdg/dotfiles/
Starting Ansible Pull at 2025-03-31 19:06:46
/usr/bin/ansible-pull -o -U https://www.github.com/cvdg/dotfiles/
[WARNING]: Could not match supplied host pattern, ignoring: laptop01
[WARNING]: Could not match supplied host pattern, ignoring: laptop01.griend.dev
localhost | SUCCESS => {
    "after": "f0751472a071c7e778aacc1e2974d7f57600d77b",
    "before": "f0751472a071c7e778aacc1e2974d7f57600d77b",
    "changed": false,
    "remote_url_changed": false
}
```
