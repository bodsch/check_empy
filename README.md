
This should be an monitoring plugin to check a [emby media server](https://emby.media/).

Should work with icinga2 or nagios.


# available checks

## version

```
$ ./check_emby -H emby-server --check version --api ${API_KEY}
```

## update

```
$ ./check_emby -H emby-server --check update --api ${API_KEY}
```

## now playing
```
$ ./check_emby -H emby-server --check nowplaying --api ${API_KEY}
```
