ansible role: set-icons
=========

Automates the process of setting custom icons for applications and folders on your mac.

Requirements
------------

None

Role Variables
--------------

Restore old firefox logo from 2013
```
icons:
  - { name: "Firefox.app", url: "https://upload.wikimedia.org/wikipedia/commons/thumb/7/76/Mozilla_Firefox_logo_2013.svg/1024px-Mozilla_Firefox_logo_2013.svg.png"}
  - { name: "YourApp.app", url: "https://download.url/youricon.png"}
  ...
```

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: noranraskin.set-icons }

License
-------

MIT / BSD

Author Information
------------------

This role was created in 2021 by Noran Raskin.

Thanks
------

Thank you [@pingortle](https://github.com/pingortle) for the [script](https://github.com/pingortle/dotfiles/blob/master/bash/.bin/set-finder-icon) to update icons.
