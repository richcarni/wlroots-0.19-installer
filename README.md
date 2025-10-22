After installed wlroots, set these environment variables before installing qtile + wayland backend:

```
export QTILE_WLROOTS_PATH=/opt/wlroots-0.19/include/wlroots-0.19
export LDFLAGS="-L/opt/wlroots-0.19/lib/x86_64-linux-gnu -Wl,-rpath,/opt/wlroots-0.19/lib/x86_64-linux-gnu"
```
