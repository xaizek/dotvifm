## Install ##

```bash
git clone $URL ~/.vifm
```

## Machine-specific configuration ##

All local settings should be kept in two files:

* `$VIFM/vifmrc_settings` -- place to set `$VIFMRC_HAS_*` variables
* `$VIFM/vifmrc_local`    -- place to do additional configuration

Neither file needs to exist or be non-empty, they are sourced with `:source`
when present.
