# Function: <code>input_register_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int input_register_device(struct input_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81667a60)
Location: drivers/input/input.c:2087
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/input/keyboard/atkbd.c:atkbd_connect
```
**Symbols:**

```
ffffffff81667a60-ffffffff81667f61: input_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int input_register_device(struct input_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff816c9380)
Location: drivers/input/input.c:2086
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/input/keyboard/atkbd.c:atkbd_connect
```
**Symbols:**

```
ffffffff816c9380-ffffffff816c9877: input_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int input_register_device(struct input_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff816f7360)
Location: drivers/input/input.c:2086
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
**Symbols:**

```
ffffffff816f7360-ffffffff816f7857: input_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int input_register_device(struct input_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff8170ce60)
Location: drivers/input/input.c:2086
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
**Symbols:**

```
ffffffff8170ce60-ffffffff8170d30e: input_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int input_register_device(struct input_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff8177e0a0)
Location: drivers/input/input.c:2079
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
**Symbols:**

```
ffffffff8177e0a0-ffffffff8177e547: input_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int input_register_device(struct input_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (0)
Location: drivers/input/input.c:2086
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
**Symbols:**

```
ffffffff817c00d9-ffffffff817c01f3: input_register_device.cold.21 (STB_LOCAL)
ffffffff817bf1c0-ffffffff817bf55e: input_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int input_register_device(struct input_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (0)
Location: drivers/input/input.c:2086
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
**Symbols:**

```
ffffffff817e75e9-ffffffff817e7703: input_register_device.cold.21 (STB_LOCAL)
ffffffff817e6620-ffffffff817e69be: input_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int input_register_device(struct input_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (0)
Location: drivers/input/input.c:2082
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
**Symbols:**

```
ffffffff818280eb-ffffffff81828223: input_register_device.cold (STB_LOCAL)
ffffffff81827230-ffffffff818275ea: input_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int input_register_device(struct input_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (0)
Location: drivers/input/input.c:2155
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
**Symbols:**

```
ffffffff8185962f-ffffffff81859767: input_register_device.cold (STB_LOCAL)
ffffffff81858760-ffffffff81858b23: input_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int input_register_device(struct input_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (0)
Location: drivers/input/input.c:2153
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/misc/uinput.c:uinput_create_device
```
**Symbols:**

```
ffffffff8192c19f-ffffffff8192c2bd: input_register_device.cold (STB_LOCAL)
ffffffff81929a80-ffffffff81929c4d: input_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int input_register_device(struct input_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (0)
Location: drivers/input/input.c:2259
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/misc/uinput.c:uinput_create_device
```
**Symbols:**

```
ffffffff81c231b4-ffffffff81c232d2: input_register_device.cold (STB_LOCAL)
ffffffff81930ff0-ffffffff819311bd: input_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int input_register_device(struct input_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (0)
Location: drivers/input/input.c:2259
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/misc/uinput.c:uinput_create_device
```
**Symbols:**

```
ffffffff81c152aa-ffffffff81c153c8: input_register_device.cold (STB_LOCAL)
ffffffff81914270-ffffffff8191443d: input_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int input_register_device(struct input_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (0)
Location: drivers/input/input.c:2259
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/misc/uinput.c:uinput_create_device
```
**Symbols:**

```
ffffffff81d23100-ffffffff81d2324d: input_register_device.cold (STB_LOCAL)
ffffffff819b6380-ffffffff819b658a: input_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int input_register_device(struct input_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (0)
Location: drivers/input/input.c:2309
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/misc/uinput.c:uinput_create_device
```
**Symbols:**

```
ffffffff81eeee9f-ffffffff81eeefec: input_register_device.cold (STB_LOCAL)
ffffffff81b15b80-ffffffff81b15d7c: input_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int input_register_device(struct input_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (0)
Location: drivers/input/input.c:2321
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/misc/uinput.c:uinput_create_device
```
**Symbols:**

```
ffffffff820a6719-ffffffff820a6743: input_register_device.cold (STB_LOCAL)
ffffffff81ca7440-ffffffff81ca77a9: input_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int input_register_device(struct input_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (0)
Location: drivers/input/input.c:2320
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/misc/uinput.c:uinput_create_device
```
**Symbols:**

```
ffffffff82127b20-ffffffff82127b4a: input_register_device.cold (STB_LOCAL)
ffffffff81d0e610-ffffffff81d0e977: input_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int input_register_device(struct input_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (0)
Location: drivers/input/input.c:2320
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/misc/uinput.c:uinput_create_device
```
**Symbols:**

```
ffffffff822094a1-ffffffff822094cb: input_register_device.cold (STB_LOCAL)
ffffffff81dc4260-ffffffff81dc45c7: input_register_device (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int input_register_device(struct input_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffff800010a974a0)
Location: drivers/input/input.c:2155
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/input/keyboard/atkbd.c:atkbd_connect
```
**Symbols:**

```
ffff800010a974a0-ffff800010a97938: input_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int input_register_device(struct input_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (c0b7a5a4)
Location: drivers/input/input.c:2155
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - sound/core/jack.c:snd_jack_dev_register
```
**Symbols:**

```
c0b7a5a4-c0b7a9fc: input_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int input_register_device(struct input_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (c000000000b78000)
Location: drivers/input/input.c:2155
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
```
**Symbols:**

```
c000000000b78000-c000000000b785fc: input_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int input_register_device(struct input_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffe0006a8a08)
Location: drivers/input/input.c:2155
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
```
**Symbols:**

```
ffffffe0006a8a08-ffffffe0006a8f16: input_register_device (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int input_register_device(struct input_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (0)
Location: drivers/input/input.c:2155
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/input/keyboard/atkbd.c:atkbd_connect
```
**Symbols:**

```
ffffffff8180e63f-ffffffff8180e777: input_register_device.cold (STB_LOCAL)
ffffffff8180d770-ffffffff8180db33: input_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int input_register_device(struct input_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (0)
Location: drivers/input/input.c:2155
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/input/keyboard/atkbd.c:atkbd_connect
```
**Symbols:**

```
ffffffff817d5d8f-ffffffff817d5ec7: input_register_device.cold (STB_LOCAL)
ffffffff817d4ee0-ffffffff817d52a3: input_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int input_register_device(struct input_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (0)
Location: drivers/input/input.c:2155
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
**Symbols:**

```
ffffffff8184d7bf-ffffffff8184d8f7: input_register_device.cold (STB_LOCAL)
ffffffff8184c8f0-ffffffff8184ccb3: input_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int input_register_device(struct input_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (0)
Location: drivers/input/input.c:2155
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
  - drivers/input/keyboard/atkbd.c:atkbd_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_set_extra
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
**Symbols:**

```
ffffffff81868999-ffffffff81868ad1: input_register_device.cold (STB_LOCAL)
ffffffff81867be0-ffffffff81867fa3: input_register_device (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
