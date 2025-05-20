# Function: <code>checkintf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int checkintf(struct usb_dev_state *ps, unsigned int ifnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff8161a520)
Location: drivers/usb/core/devio.c:674
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:check_ctrlrecip
  - drivers/usb/core/devio.c:check_ctrlrecip
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff8161a520-ffffffff8161a59a: checkintf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int checkintf(struct usb_dev_state *ps, unsigned int ifnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff81679fd0)
Location: drivers/usb/core/devio.c:788
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:check_ctrlrecip
  - drivers/usb/core/devio.c:check_ctrlrecip
```
**Symbols:**

```
ffffffff81679fd0-ffffffff8167a04a: checkintf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int checkintf(struct usb_dev_state *ps, unsigned int ifnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff816a7ca0)
Location: drivers/usb/core/devio.c:788
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:check_ctrlrecip
  - drivers/usb/core/devio.c:check_ctrlrecip
```
**Symbols:**

```
ffffffff816a7ca0-ffffffff816a7d1a: checkintf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int checkintf(struct usb_dev_state *ps, unsigned int ifnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff816bce80)
Location: drivers/usb/core/devio.c:782
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
```
**Symbols:**

```
ffffffff816bce80-ffffffff816bcefb: checkintf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int checkintf(struct usb_dev_state *ps, unsigned int ifnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff81728850)
Location: drivers/usb/core/devio.c:772
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
```
**Symbols:**

```
ffffffff81728850-ffffffff817288c9: checkintf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int checkintf(struct usb_dev_state *ps, unsigned int ifnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff817676a0)
Location: drivers/usb/core/devio.c:768
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:check_ctrlrecip
  - drivers/usb/core/devio.c:check_ctrlrecip
```
**Symbols:**

```
ffffffff817676a0-ffffffff8176771e: checkintf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int checkintf(struct usb_dev_state *ps, unsigned int ifnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff8178c020)
Location: drivers/usb/core/devio.c:769
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:check_ctrlrecip
  - drivers/usb/core/devio.c:check_ctrlrecip
```
**Symbols:**

```
ffffffff8178c020-ffffffff8178c09e: checkintf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int checkintf(struct usb_dev_state *ps, unsigned int ifnum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff817cdee2)
Location: drivers/usb/core/devio.c:764
Inline: True
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:check_ctrlrecip
  - drivers/usb/core/devio.c:check_ctrlrecip
```
**Symbols:**

```
ffffffff817ca9d0-ffffffff817caa17: checkintf (STB_LOCAL)
ffffffff817cdee2-ffffffff817cdf22: checkintf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int checkintf(struct usb_dev_state *ps, unsigned int ifnum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff817fecd2)
Location: drivers/usb/core/devio.c:807
Inline: True
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:check_ctrlrecip
  - drivers/usb/core/devio.c:check_ctrlrecip
```
**Symbols:**

```
ffffffff817fb5a0-ffffffff817fb5e7: checkintf (STB_LOCAL)
ffffffff817fecd2-ffffffff817fed12: checkintf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int checkintf(struct usb_dev_state *ps, unsigned int ifnum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff818cf2de)
Location: drivers/usb/core/devio.c:816
Inline: True
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_clearhalt
  - drivers/usb/core/devio.c:proc_resetep
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:check_ctrlrecip
  - drivers/usb/core/devio.c:check_ctrlrecip
```
**Symbols:**

```
ffffffff818cb9b0-ffffffff818cb9f7: checkintf (STB_LOCAL)
ffffffff818cf2de-ffffffff818cf31e: checkintf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int checkintf(struct usb_dev_state *ps, unsigned int ifnum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff81c1e1cc)
Location: drivers/usb/core/devio.c:816
Inline: True
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_clearhalt
  - drivers/usb/core/devio.c:proc_resetep
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:check_ctrlrecip
  - drivers/usb/core/devio.c:check_ctrlrecip
```
**Symbols:**

```
ffffffff818d6ca0-ffffffff818d6ce7: checkintf (STB_LOCAL)
ffffffff81c1e1cc-ffffffff81c1e20c: checkintf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int checkintf(struct usb_dev_state *ps, unsigned int ifnum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff81c0fff3)
Location: drivers/usb/core/devio.c:816
Inline: True
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:check_ctrlrecip
  - drivers/usb/core/devio.c:check_ctrlrecip
```
**Symbols:**

```
ffffffff818b9d60-ffffffff818b9da7: checkintf (STB_LOCAL)
ffffffff81c0fff3-ffffffff81c10033: checkintf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int checkintf(struct usb_dev_state *ps, unsigned int ifnum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff81d170e7)
Location: drivers/usb/core/devio.c:817
Inline: True
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:check_ctrlrecip
  - drivers/usb/core/devio.c:check_ctrlrecip
```
**Symbols:**

```
ffffffff8194fa10-ffffffff8194fa57: checkintf (STB_LOCAL)
ffffffff81d170e7-ffffffff81d17127: checkintf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int checkintf(struct usb_dev_state *ps, unsigned int ifnum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff81ee1f5b)
Location: drivers/usb/core/devio.c:829
Inline: True
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:check_ctrlrecip
  - drivers/usb/core/devio.c:check_ctrlrecip
```
**Symbols:**

```
ffffffff81aa8cb0-ffffffff81aa8d13: checkintf (STB_LOCAL)
ffffffff81ee1f5b-ffffffff81ee1f9b: checkintf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int checkintf(struct usb_dev_state *ps, unsigned int ifnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff81c2f800)
Location: drivers/usb/core/devio.c:829
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:check_ctrlrecip
  - drivers/usb/core/devio.c:check_ctrlrecip
```
**Symbols:**

```
ffffffff81c2f800-ffffffff81c2f8b9: checkintf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int checkintf(struct usb_dev_state *ps, unsigned int ifnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff81c96a80)
Location: drivers/usb/core/devio.c:838
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:check_ctrlrecip
  - drivers/usb/core/devio.c:check_ctrlrecip
```
**Symbols:**

```
ffffffff81c96a80-ffffffff81c96b39: checkintf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int checkintf(struct usb_dev_state *ps, unsigned int ifnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff81d4b560)
Location: drivers/usb/core/devio.c:838
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:check_ctrlrecip
  - drivers/usb/core/devio.c:check_ctrlrecip
```
**Symbols:**

```
ffffffff81d4b560-ffffffff81d4b619: checkintf (STB_LOCAL)
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
int checkintf(struct usb_dev_state *ps, unsigned int ifnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffff800010a2c818)
Location: drivers/usb/core/devio.c:807
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:check_ctrlrecip
  - drivers/usb/core/devio.c:check_ctrlrecip
```
**Symbols:**

```
ffff800010a2c818-ffff800010a2c8a8: checkintf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int checkintf(struct usb_dev_state *ps, unsigned int ifnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (c0b0218c)
Location: drivers/usb/core/devio.c:807
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:check_ctrlrecip
  - drivers/usb/core/devio.c:check_ctrlrecip
```
**Symbols:**

```
c0b0218c-c0b0222c: checkintf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int checkintf(struct usb_dev_state *ps, unsigned int ifnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (c000000000ae9a10)
Location: drivers/usb/core/devio.c:807
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:check_ctrlrecip
```
**Symbols:**

```
c000000000ae9a10-c000000000ae9ad4: checkintf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int checkintf(struct usb_dev_state *ps, unsigned int ifnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffe00064dcaa)
Location: drivers/usb/core/devio.c:807
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:check_ctrlrecip
  - drivers/usb/core/devio.c:check_ctrlrecip
```
**Symbols:**

```
ffffffe00064dcaa-ffffffe00064dd28: checkintf (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int checkintf(struct usb_dev_state *ps, unsigned int ifnum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff817b70b2)
Location: drivers/usb/core/devio.c:807
Inline: True
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:check_ctrlrecip
  - drivers/usb/core/devio.c:check_ctrlrecip
```
**Symbols:**

```
ffffffff817b3980-ffffffff817b39c7: checkintf (STB_LOCAL)
ffffffff817b70b2-ffffffff817b70f2: checkintf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int checkintf(struct usb_dev_state *ps, unsigned int ifnum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff817a8ad2)
Location: drivers/usb/core/devio.c:807
Inline: True
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:check_ctrlrecip
  - drivers/usb/core/devio.c:check_ctrlrecip
```
**Symbols:**

```
ffffffff817a53b0-ffffffff817a53f7: checkintf (STB_LOCAL)
ffffffff817a8ad2-ffffffff817a8b12: checkintf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int checkintf(struct usb_dev_state *ps, unsigned int ifnum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff817f3b52)
Location: drivers/usb/core/devio.c:807
Inline: True
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:check_ctrlrecip
  - drivers/usb/core/devio.c:check_ctrlrecip
```
**Symbols:**

```
ffffffff817f0420-ffffffff817f0467: checkintf (STB_LOCAL)
ffffffff817f3b52-ffffffff817f3b92: checkintf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int checkintf(struct usb_dev_state *ps, unsigned int ifnum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff8180ddd2)
Location: drivers/usb/core/devio.c:807
Inline: True
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:check_ctrlrecip
  - drivers/usb/core/devio.c:check_ctrlrecip
```
**Symbols:**

```
ffffffff8180a660-ffffffff8180a6a7: checkintf (STB_LOCAL)
ffffffff8180ddd2-ffffffff8180de12: checkintf.cold (STB_LOCAL)
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
