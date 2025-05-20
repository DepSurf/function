# Function: <code>register_chrdev_region</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int register_chrdev_region(dev_t from, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81210d50)
Location: fs/char_dev.c:174
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/usb/core/devio.c:usb_devio_init
```
**Symbols:**

```
ffffffff81210d50-ffffffff81210e11: register_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int register_chrdev_region(dev_t from, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81237870)
Location: fs/char_dev.c:178
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
```
**Symbols:**

```
ffffffff81237870-ffffffff81237931: register_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int register_chrdev_region(dev_t from, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff8124a520)
Location: fs/char_dev.c:178
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
```
**Symbols:**

```
ffffffff8124a520-ffffffff8124a5e1: register_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int register_chrdev_region(dev_t from, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812560d0)
Location: fs/char_dev.c:178
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
```
**Symbols:**

```
ffffffff812560d0-ffffffff81256191: register_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int register_chrdev_region(dev_t from, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812782e0)
Location: fs/char_dev.c:203
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
```
**Symbols:**

```
ffffffff812782e0-ffffffff812783a1: register_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int register_chrdev_region(dev_t from, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff8129ea60)
Location: fs/char_dev.c:203
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/scsi/sg.c:init_sg
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/input.c:input_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
```
**Symbols:**

```
ffffffff8129ea60-ffffffff8129eb2d: register_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int register_chrdev_region(dev_t from, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812b3770)
Location: fs/char_dev.c:203
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/scsi/sg.c:init_sg
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/input.c:input_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
```
**Symbols:**

```
ffffffff812b3770-ffffffff812b383d: register_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int register_chrdev_region(dev_t from, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812d0480)
Location: fs/char_dev.c:200
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/scsi/sg.c:init_sg
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/input.c:input_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
```
**Symbols:**

```
ffffffff812d0480-ffffffff812d053b: register_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int register_chrdev_region(dev_t from, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812e2020)
Location: fs/char_dev.c:200
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/scsi/sg.c:init_sg
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/input.c:input_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
```
**Symbols:**

```
ffffffff812e2020-ffffffff812e20db: register_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int register_chrdev_region(dev_t from, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81319410)
Location: fs/char_dev.c:200
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/scsi/sg.c:init_sg
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/input.c:input_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
```
**Symbols:**

```
ffffffff81319410-ffffffff813194cb: register_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int register_chrdev_region(dev_t from, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81324af0)
Location: fs/char_dev.c:200
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/scsi/sg.c:init_sg
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/input.c:input_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
```
**Symbols:**

```
ffffffff81324af0-ffffffff81324bab: register_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int register_chrdev_region(dev_t from, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff8132ac10)
Location: fs/char_dev.c:200
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/scsi/sg.c:init_sg
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/input.c:input_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
```
**Symbols:**

```
ffffffff8132ac10-ffffffff8132accb: register_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int register_chrdev_region(dev_t from, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81378320)
Location: fs/char_dev.c:200
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/scsi/sg.c:init_sg
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/input.c:input_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
```
**Symbols:**

```
ffffffff81378320-ffffffff813783db: register_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int register_chrdev_region(dev_t from, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff813f7650)
Location: fs/char_dev.c:200
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/scsi/sg.c:init_sg
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/input.c:input_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
```
**Symbols:**

```
ffffffff813f7650-ffffffff813f7727: register_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int register_chrdev_region(dev_t from, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff814809a0)
Location: fs/char_dev.c:200
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/scsi/sg.c:init_sg
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/input.c:input_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
```
**Symbols:**

```
ffffffff814809a0-ffffffff81480a77: register_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int register_chrdev_region(dev_t from, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff814b55c0)
Location: fs/char_dev.c:200
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/scsi/sg.c:init_sg
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/input.c:input_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
```
**Symbols:**

```
ffffffff814b55c0-ffffffff814b5697: register_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int register_chrdev_region(dev_t from, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff814e78d0)
Location: fs/char_dev.c:200
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/scsi/sg.c:init_sg
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/input.c:input_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
```
**Symbols:**

```
ffffffff814e78d0-ffffffff814e79a7: register_chrdev_region (STB_GLOBAL)
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
int register_chrdev_region(dev_t from, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffff8000103896a0)
Location: fs/char_dev.c:200
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/scsi/sg.c:init_sg
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/input.c:input_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
```
**Symbols:**

```
ffff8000103896a0-ffff800010389770: register_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int register_chrdev_region(dev_t from, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (c0571a64)
Location: fs/char_dev.c:200
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/scsi/sg.c:init_sg
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/input.c:input_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
```
**Symbols:**

```
c0571a64-c0571b0c: register_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int register_chrdev_region(dev_t from, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (c000000000480f10)
Location: fs/char_dev.c:200
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/scsi/sg.c:init_sg
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/input.c:input_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
```
**Symbols:**

```
c000000000480f10-c000000000481074: register_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int register_chrdev_region(dev_t from, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffe00025b882)
Location: fs/char_dev.c:200
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/scsi/sg.c:init_sg
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/input.c:input_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
```
**Symbols:**

```
ffffffe00025b882-ffffffe00025b950: register_chrdev_region (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int register_chrdev_region(dev_t from, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812da600)
Location: fs/char_dev.c:200
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/scsi/sg.c:init_sg
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/input.c:input_init
```
**Symbols:**

```
ffffffff812da600-ffffffff812da6bb: register_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int register_chrdev_region(dev_t from, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812cb280)
Location: fs/char_dev.c:200
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/scsi/sg.c:init_sg
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/input.c:input_init
```
**Symbols:**

```
ffffffff812cb280-ffffffff812cb33b: register_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int register_chrdev_region(dev_t from, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812d8410)
Location: fs/char_dev.c:200
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/scsi/sg.c:init_sg
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/input.c:input_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
```
**Symbols:**

```
ffffffff812d8410-ffffffff812d84cb: register_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int register_chrdev_region(dev_t from, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812e92b0)
Location: fs/char_dev.c:200
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/scsi/sg.c:init_sg
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/input.c:input_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
```
**Symbols:**

```
ffffffff812e92b0-ffffffff812e936b: register_chrdev_region (STB_GLOBAL)
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
