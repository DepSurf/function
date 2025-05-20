# Function: <code>proc_control</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int proc_control(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff8161b7d0)
Location: drivers/usb/core/devio.c:969
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff8161b7d0-ffffffff8161bb7d: proc_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int proc_control(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff8167b2b0)
Location: drivers/usb/core/devio.c:1083
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff8167b2b0-ffffffff8167b686: proc_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int proc_control(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff816a9130)
Location: drivers/usb/core/devio.c:1083
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff816a9130-ffffffff816a9506: proc_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int proc_control(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff816be3e0)
Location: drivers/usb/core/devio.c:1077
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff816be3e0-ffffffff816be7b2: proc_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int proc_control(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff81729db0)
Location: drivers/usb/core/devio.c:1067
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff81729db0-ffffffff8172a182: proc_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int proc_control(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff81768700)
Location: drivers/usb/core/devio.c:1062
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff81768700-ffffffff81768a96: proc_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int proc_control(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff8178d070)
Location: drivers/usb/core/devio.c:1063
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff8178d070-ffffffff8178d406: proc_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int proc_control(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:1052
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff817cab20-ffffffff817cadd1: proc_control (STB_LOCAL)
ffffffff817ce076-ffffffff817ce18d: proc_control.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int proc_control(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:1096
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff817fb6f0-ffffffff817fb9a1: proc_control (STB_LOCAL)
ffffffff817fee66-ffffffff817fef7d: proc_control.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int proc_control(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:1105
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff818cbb00-ffffffff818cbd87: proc_control (STB_LOCAL)
ffffffff818cf35f-ffffffff818cf4a6: proc_control.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff818d9a5a)
Location: drivers/usb/core/devio.c:1185
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff818bcec8)
Location: drivers/usb/core/devio.c:1185
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff81953030)
Location: drivers/usb/core/devio.c:1246
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff81aac65e)
Location: drivers/usb/core/devio.c:1262
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff81c33c7a)
Location: drivers/usb/core/devio.c:1262
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff81c9abd5)
Location: drivers/usb/core/devio.c:1271
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff81d4f796)
Location: drivers/usb/core/devio.c:1271
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
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
int proc_control(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffff800010a30f90)
Location: drivers/usb/core/devio.c:1096
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffff800010a30f90-ffff800010a314a8: proc_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int proc_control(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (c0b03668)
Location: drivers/usb/core/devio.c:1096
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
c0b03668-c0b03b78: proc_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int proc_control(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (c000000000aea700)
Location: drivers/usb/core/devio.c:1096
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
c000000000aea700-c000000000aeac20: proc_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int proc_control(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffe00064e292)
Location: drivers/usb/core/devio.c:1096
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffe00064e292-ffffffe00064e5ee: proc_control (STB_LOCAL)
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
int proc_control(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:1096
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff817b3ad0-ffffffff817b3d81: proc_control (STB_LOCAL)
ffffffff817b7246-ffffffff817b735d: proc_control.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int proc_control(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:1096
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff817a5500-ffffffff817a57b1: proc_control (STB_LOCAL)
ffffffff817a8c66-ffffffff817a8d7d: proc_control.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int proc_control(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:1096
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff817f0570-ffffffff817f0821: proc_control (STB_LOCAL)
ffffffff817f3ce6-ffffffff817f3dfd: proc_control.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int proc_control(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:1096
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff8180a7b0-ffffffff8180aa61: proc_control (STB_LOCAL)
ffffffff8180df66-ffffffff8180e07d: proc_control.cold (STB_LOCAL)
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
