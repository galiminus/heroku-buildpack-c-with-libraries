Simple buildpack based on heroku-builpack-C, external libraries and
header files can be included in the `lib/` and `include/` directories.

You need to add `LD_LIBRARY_PATH` in your Heroku environment keys:

```
LD_LIBRARY_PATH=/app/lib
```
