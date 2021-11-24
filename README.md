mtail
=====

This ansible role installs and configures
[mtail](https://github.com/google/mtail).

There are two installation methods:

  * On openSUSE/SLE systems native OS package is used for installation:
    [server:monitoring/mtail](https://build.opensuse.org/package/show/server:monitoring/mtail)
  * On other systems the pre-compiled binary archive is downloaded and extracted.

Some hardening is done by default by using systemd-sandboxing options
and an AppArmor profile.

See defaults/main.yml how to tweak installation and configuration.
