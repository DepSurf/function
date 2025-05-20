# Function: <code>check_reset_of_active_ep</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void check_reset_of_active_ep(struct usb_device *udev, unsigned int epnum, char *ioctl_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff816198b0)
Location: drivers/usb/core/devio.c:1130
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff816198b0-ffffffff81619919: check_reset_of_active_ep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void check_reset_of_active_ep(struct usb_device *udev, unsigned int epnum, char *ioctl_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff81679ac0)
Location: drivers/usb/core/devio.c:1244
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff81679ac0-ffffffff81679b2c: check_reset_of_active_ep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void check_reset_of_active_ep(struct usb_device *udev, unsigned int epnum, char *ioctl_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff816a77a0)
Location: drivers/usb/core/devio.c:1244
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff816a77a0-ffffffff816a780c: check_reset_of_active_ep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void check_reset_of_active_ep(struct usb_device *udev, unsigned int epnum, char *ioctl_name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff816bd760)
Location: drivers/usb/core/devio.c:1238
Inline: True
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff816bd760-ffffffff816bd7cd: check_reset_of_active_ep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void check_reset_of_active_ep(struct usb_device *udev, unsigned int epnum, char *ioctl_name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff81729130)
Location: drivers/usb/core/devio.c:1228
Inline: True
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff81729130-ffffffff8172919d: check_reset_of_active_ep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void check_reset_of_active_ep(struct usb_device *udev, unsigned int epnum, char *ioctl_name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff81767f00)
Location: drivers/usb/core/devio.c:1223
Inline: True
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff81767f00-ffffffff81767f6c: check_reset_of_active_ep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void check_reset_of_active_ep(struct usb_device *udev, unsigned int epnum, char *ioctl_name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff8178c750)
Location: drivers/usb/core/devio.c:1224
Inline: True
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff8178c750-ffffffff8178c7bc: check_reset_of_active_ep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void check_reset_of_active_ep(struct usb_device *udev, unsigned int epnum, char *ioctl_name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff817cdeaa)
Location: drivers/usb/core/devio.c:1213
Inline: True
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff817ca840-ffffffff817ca881: check_reset_of_active_ep (STB_LOCAL)
ffffffff817cdeaa-ffffffff817cdee2: check_reset_of_active_ep.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void check_reset_of_active_ep(struct usb_device *udev, unsigned int epnum, char *ioctl_name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff817fec9a)
Location: drivers/usb/core/devio.c:1257
Inline: True
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff817fb410-ffffffff817fb451: check_reset_of_active_ep (STB_LOCAL)
ffffffff817fec9a-ffffffff817fecd2: check_reset_of_active_ep.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff818cc18a)
Location: drivers/usb/core/devio.c:1257
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_clearhalt
  - drivers/usb/core/devio.c:proc_resetep
Direct callers:
  - drivers/usb/core/devio.c:proc_clearhalt
  - drivers/usb/core/devio.c:proc_clearhalt
  - drivers/usb/core/devio.c:proc_resetep
```
**Symbols:**

```
ffffffff818cf199-ffffffff818cf1d3: check_reset_of_active_ep.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff818d736a)
Location: drivers/usb/core/devio.c:1271
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_clearhalt
  - drivers/usb/core/devio.c:proc_resetep
Direct callers:
  - drivers/usb/core/devio.c:proc_clearhalt
  - drivers/usb/core/devio.c:proc_clearhalt
  - drivers/usb/core/devio.c:proc_resetep
```
**Symbols:**

```
ffffffff81c1e016-ffffffff81c1e050: check_reset_of_active_ep.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff818bcd1e)
Location: drivers/usb/core/devio.c:1276
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff81c0febc-ffffffff81c0fef6: check_reset_of_active_ep.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff81952f07)
Location: drivers/usb/core/devio.c:1354
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff81d16f97-ffffffff81d16fd1: check_reset_of_active_ep.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff81aac466)
Location: drivers/usb/core/devio.c:1370
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff81ee1f0d-ffffffff81ee1f5b: check_reset_of_active_ep.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void check_reset_of_active_ep(struct usb_device *udev, unsigned int epnum, char *ioctl_name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff81c2ff60)
Location: drivers/usb/core/devio.c:1370
Inline: True
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff81c2ff60-ffffffff81c2fff4: check_reset_of_active_ep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void check_reset_of_active_ep(struct usb_device *udev, unsigned int epnum, char *ioctl_name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff81c971e0)
Location: drivers/usb/core/devio.c:1379
Inline: True
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff81c971e0-ffffffff81c97274: check_reset_of_active_ep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void check_reset_of_active_ep(struct usb_device *udev, unsigned int epnum, char *ioctl_name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff81d4bcc0)
Location: drivers/usb/core/devio.c:1379
Inline: True
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff81d4bcc0-ffffffff81d4bd54: check_reset_of_active_ep (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void check_reset_of_active_ep(struct usb_device *udev, unsigned int epnum, char *ioctl_name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffff800010a2c198)
Location: drivers/usb/core/devio.c:1257
Inline: True
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffff800010a2c198-ffff800010a2c21c: check_reset_of_active_ep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void check_reset_of_active_ep(struct usb_device *udev, unsigned int epnum, char *ioctl_name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (c0b02588)
Location: drivers/usb/core/devio.c:1257
Inline: True
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
c0b02588-c0b02604: check_reset_of_active_ep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void check_reset_of_active_ep(struct usb_device *udev, unsigned int epnum, char *ioctl_name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (c000000000aea660)
Location: drivers/usb/core/devio.c:1257
Inline: True
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
c000000000aea660-c000000000aea6f8: check_reset_of_active_ep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void check_reset_of_active_ep(struct usb_device *udev, unsigned int epnum, char *ioctl_name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffe00064e1bc)
Location: drivers/usb/core/devio.c:1257
Inline: True
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffe00064e1bc-ffffffe00064e22c: check_reset_of_active_ep (STB_LOCAL)
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
void check_reset_of_active_ep(struct usb_device *udev, unsigned int epnum, char *ioctl_name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff817b707a)
Location: drivers/usb/core/devio.c:1257
Inline: True
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff817b37f0-ffffffff817b3831: check_reset_of_active_ep (STB_LOCAL)
ffffffff817b707a-ffffffff817b70b2: check_reset_of_active_ep.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void check_reset_of_active_ep(struct usb_device *udev, unsigned int epnum, char *ioctl_name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff817a8a9a)
Location: drivers/usb/core/devio.c:1257
Inline: True
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff817a5220-ffffffff817a5261: check_reset_of_active_ep (STB_LOCAL)
ffffffff817a8a9a-ffffffff817a8ad2: check_reset_of_active_ep.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void check_reset_of_active_ep(struct usb_device *udev, unsigned int epnum, char *ioctl_name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff817f3b1a)
Location: drivers/usb/core/devio.c:1257
Inline: True
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff817f0290-ffffffff817f02d1: check_reset_of_active_ep (STB_LOCAL)
ffffffff817f3b1a-ffffffff817f3b52: check_reset_of_active_ep.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void check_reset_of_active_ep(struct usb_device *udev, unsigned int epnum, char *ioctl_name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff8180dd9a)
Location: drivers/usb/core/devio.c:1257
Inline: True
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff8180a4d0-ffffffff8180a511: check_reset_of_active_ep (STB_LOCAL)
ffffffff8180dd9a-ffffffff8180ddd2: check_reset_of_active_ep.cold (STB_LOCAL)
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
