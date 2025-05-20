# Function: <code>proc_bulk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int proc_bulk(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff8161af00)
Location: drivers/usb/core/devio.c:1056
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff8161af00-ffffffff8161b27c: proc_bulk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int proc_bulk(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff8167ab10)
Location: drivers/usb/core/devio.c:1170
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff8167ab10-ffffffff8167aeac: proc_bulk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int proc_bulk(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff816a87d0)
Location: drivers/usb/core/devio.c:1170
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff816a87d0-ffffffff816a8b6d: proc_bulk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int proc_bulk(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff816bdb90)
Location: drivers/usb/core/devio.c:1164
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff816bdb90-ffffffff816bdf0c: proc_bulk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int proc_bulk(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff81729560)
Location: drivers/usb/core/devio.c:1154
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff81729560-ffffffff817298dc: proc_bulk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int proc_bulk(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff817681f0)
Location: drivers/usb/core/devio.c:1149
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff817681f0-ffffffff8176853d: proc_bulk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int proc_bulk(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff8178ca40)
Location: drivers/usb/core/devio.c:1150
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff8178ca40-ffffffff8178cd8d: proc_bulk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int proc_bulk(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:1139
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff817cbf50-ffffffff817cc268: proc_bulk (STB_LOCAL)
ffffffff817ce214-ffffffff817ce2bc: proc_bulk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int proc_bulk(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:1183
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff817fcbb0-ffffffff817fcee1: proc_bulk (STB_LOCAL)
ffffffff817ff004-ffffffff817ff0ac: proc_bulk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int proc_bulk(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:1187
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_bulk_compat
```
**Symbols:**

```
ffffffff818cbd90-ffffffff818cc082: proc_bulk (STB_LOCAL)
ffffffff818cf4a6-ffffffff818cf548: proc_bulk.cold (STB_LOCAL)
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
In drivers/usb/core/devio.c (ffffffff818d9462)
Location: drivers/usb/core/devio.c:1262
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
In drivers/usb/core/devio.c (ffffffff818bc5f2)
Location: drivers/usb/core/devio.c:1267
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
In drivers/usb/core/devio.c (ffffffff81952607)
Location: drivers/usb/core/devio.c:1345
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
In drivers/usb/core/devio.c (ffffffff81aabcc1)
Location: drivers/usb/core/devio.c:1361
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
In drivers/usb/core/devio.c (ffffffff81c331d3)
Location: drivers/usb/core/devio.c:1361
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
In drivers/usb/core/devio.c (ffffffff81c9ab7c)
Location: drivers/usb/core/devio.c:1370
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
In drivers/usb/core/devio.c (ffffffff81d4f741)
Location: drivers/usb/core/devio.c:1370
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
int proc_bulk(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffff800010a2dca8)
Location: drivers/usb/core/devio.c:1183
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_bulk_compat
```
**Symbols:**

```
ffff800010a2dca8-ffff800010a2e164: proc_bulk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int proc_bulk(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (c0b03b78)
Location: drivers/usb/core/devio.c:1183
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
c0b03b78-c0b0403c: proc_bulk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int proc_bulk(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (c000000000aec910)
Location: drivers/usb/core/devio.c:1183
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_bulk_compat
```
**Symbols:**

```
c000000000aec910-c000000000aecdc0: proc_bulk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int proc_bulk(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffe00064e5ee)
Location: drivers/usb/core/devio.c:1183
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffe00064e5ee-ffffffe00064e908: proc_bulk (STB_LOCAL)
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
int proc_bulk(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:1183
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff817b4f90-ffffffff817b52c1: proc_bulk (STB_LOCAL)
ffffffff817b73e4-ffffffff817b748c: proc_bulk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int proc_bulk(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:1183
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff817a69c0-ffffffff817a6cf1: proc_bulk (STB_LOCAL)
ffffffff817a8e04-ffffffff817a8eac: proc_bulk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int proc_bulk(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:1183
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff817f1a30-ffffffff817f1d61: proc_bulk (STB_LOCAL)
ffffffff817f3e84-ffffffff817f3f2c: proc_bulk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int proc_bulk(struct usb_dev_state *ps, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:1183
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff8180bc70-ffffffff8180bfa1: proc_bulk (STB_LOCAL)
ffffffff8180e104-ffffffff8180e1ac: proc_bulk.cold (STB_LOCAL)
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
