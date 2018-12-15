## Install ##

```bash
git clone $URL ~/.vifm
```

## Machine-specific configuration ##

All local settings should be kept in two files:

* `$VIFM/vifmrc_settings` -- place to set `$VIFMRC_HAS_*` variables
* `$VIFM/vifmrc_local`    -- place to do additional configuration

Both files are assumed to exist.  They might be empty, but it's better to have
them anyway as it prevents vifm from displaying errors on the status bar.
