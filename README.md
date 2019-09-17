# Fork of Noboru-i's [BrakemanTranslateCheckstyleFormat](https://github.com/noboru-i/brakeman_translate_checkstyle_format)

## Reason for forking

Change format of warning message from

### Old Style

```
[Confidence][Warning type] Descrption
```

to

### New style

```
Confidence/Warning-Type: Description
```

As Jenkins Warning plugin wasn't picking up types correctly

