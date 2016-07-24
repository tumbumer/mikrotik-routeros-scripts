# mikrotik-routeros-scripts
Several [MikroTik](http://www.mikrotik.com) [RouterOS](http://wiki.mikrotik.com/wiki/Manual:TOC) scripts

## Script list

### backup

The script makes a backup of the [system and configuration files](http://wiki.mikrotik.com/wiki/Manual:Configuration_Management)

    sysname_yyyymmddhhnnss.backup
    sysname_yyyymmddhhnnss.rsc

where "sysname" is the system name (`/system identity get name`)

Usage:

`/system script run backup`
