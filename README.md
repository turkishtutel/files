# Autodroid
> pip install autodroid

-- Usage --

**swipe()**
> swipe(x1, y1, x2, y2, duration)
x1, y1, x2, y2 = position, from - to (must be integer).
duration = amount of time swiped (in miliseconds not seconds).
*E.g.*
> swipe(520, 1730, 520, 400, 1000)
swipe up, for 1s

**tap()**
> tap(x, y)
x, y = position (must be integer).
*E.g.*
> tap(173, 200)

**screenshot()**
> screenshot()
saves to /sdcard/autodroid/screencap

**holdtap()**
> holdtap(x, y, duration)
x, y = position (must be integer),
duration = amount of time held (in miliseconds)
*E.g.*
> holdtap(167, 853, 4000)

**type()**
> type(text)
text = the text you want to type (must be string).
*E.g.*
> type("hello world")

**checkConnected()**
> checkConnected()
prints the connected device S/N

**scrcpy()**
> scrcpy()
starts a session of scrcpy

**key()**
> key(key)
text = the key you want to execute

| Key Name      | Alternate Names | Key Code |
|---------------|----------------|----------|
| Home          | –              | 3        |
| Back          | –              | 4        |
| Recent Apps   | recent, recents| 187      |
| Power         | pwr            | 26       |
| Volume Up     | v_up, vol_up   | 24       |
| Volume Down   | v_down, vol_down| 25      |
| Mute          | –              | 164      |
| Media Play    | mplay, play    | 85       |
| Wake          | wakeup         | 224      |

*E.g.*
> key("pwr")
key combos dont work yet

# not recommended to use with 2 devices, havent intergrated 2 devices
