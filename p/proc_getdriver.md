# Function: <code>proc_getdriver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff8161b710)
Location: drivers/usb/core/devio.c:1185
Inline: True
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff8161b710-ffffffff8161b7cd: proc_getdriver.isra.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff8167b1f0)
Location: drivers/usb/core/devio.c:1299
Inline: True
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff8167b1f0-ffffffff8167b2ad: proc_getdriver.isra.26 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff816a8eb0)
Location: drivers/usb/core/devio.c:1299
Inline: True
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff816a8eb0-ffffffff816a8f6d: proc_getdriver.isra.28 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff816bd7d0)
Location: drivers/usb/core/devio.c:1293
Inline: True
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff816bd7d0-ffffffff816bd927: proc_getdriver.isra.24 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff817291a0)
Location: drivers/usb/core/devio.c:1283
Inline: True
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff817291a0-ffffffff817292f7: proc_getdriver.isra.24 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff81767f70)
Location: drivers/usb/core/devio.c:1278
Inline: True
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff81767f70-ffffffff817680c7: proc_getdriver.isra.27 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff8178c7c0)
Location: drivers/usb/core/devio.c:1279
Inline: True
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff8178c7c0-ffffffff8178c917: proc_getdriver.isra.28 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff817ca890)
Location: drivers/usb/core/devio.c:1268
Inline: True
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff817ca890-ffffffff817ca9cb: proc_getdriver.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff817fb460)
Location: drivers/usb/core/devio.c:1312
Inline: True
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff817fb460-ffffffff817fb59b: proc_getdriver.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int proc_getdriver(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff818cb030)
Location: drivers/usb/core/devio.c:1312
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff818cb030-ffffffff818cb16c: proc_getdriver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int proc_getdriver(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff818d6120)
Location: drivers/usb/core/devio.c:1326
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff818d6120-ffffffff818d625c: proc_getdriver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int proc_getdriver(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff818b9650)
Location: drivers/usb/core/devio.c:1331
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff818b9650-ffffffff818b9791: proc_getdriver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int proc_getdriver(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff8194f150)
Location: drivers/usb/core/devio.c:1409
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff8194f150-ffffffff8194f291: proc_getdriver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int proc_getdriver(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff81aa8160)
Location: drivers/usb/core/devio.c:1425
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff81aa8160-ffffffff81aa82e7: proc_getdriver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int proc_getdriver(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff81c2f1b0)
Location: drivers/usb/core/devio.c:1425
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff81c2f1b0-ffffffff81c2f2f2: proc_getdriver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int proc_getdriver(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff81c96420)
Location: drivers/usb/core/devio.c:1434
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff81c96420-ffffffff81c96562: proc_getdriver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int proc_getdriver(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff81d4af00)
Location: drivers/usb/core/devio.c:1434
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff81d4af00-ffffffff81d4b042: proc_getdriver (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (ffff800010a30540)
Location: drivers/usb/core/devio.c:1312
Inline: True
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffff800010a30540-ffff800010a307bc: proc_getdriver.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int proc_getdriver(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (c0b030d0)
Location: drivers/usb/core/devio.c:1312
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
c0b030d0-c0b0323c: proc_getdriver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int proc_getdriver(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (c000000000ae9f90)
Location: drivers/usb/core/devio.c:1312
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
c000000000ae9f90-c000000000aea0c0: proc_getdriver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int proc_getdriver(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffe00064df70)
Location: drivers/usb/core/devio.c:1312
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffe00064df70-ffffffe00064dff0: proc_getdriver (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff817b3840)
Location: drivers/usb/core/devio.c:1312
Inline: True
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff817b3840-ffffffff817b397b: proc_getdriver.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff817a5270)
Location: drivers/usb/core/devio.c:1312
Inline: True
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff817a5270-ffffffff817a53ab: proc_getdriver.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff817f02e0)
Location: drivers/usb/core/devio.c:1312
Inline: True
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff817f02e0-ffffffff817f041b: proc_getdriver.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff8180a520)
Location: drivers/usb/core/devio.c:1312
Inline: True
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff8180a520-ffffffff8180a65b: proc_getdriver.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
