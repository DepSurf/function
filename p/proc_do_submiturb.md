# Function: <code>proc_do_submiturb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int proc_do_submiturb(struct usb_dev_state *ps, struct usbdevfs_urb *uurb, struct usbdevfs_iso_packet_desc *iso_frame_desc, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff8161bda0)
Location: drivers/usb/core/devio.c:1286
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff8161bda0-ffffffff8161c955: proc_do_submiturb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int proc_do_submiturb(struct usb_dev_state *ps, struct usbdevfs_urb *uurb, struct usbdevfs_iso_packet_desc *iso_frame_desc, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff8167bf10)
Location: drivers/usb/core/devio.c:1448
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff8167bf10-ffffffff8167cc52: proc_do_submiturb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int proc_do_submiturb(struct usb_dev_state *ps, struct usbdevfs_urb *uurb, struct usbdevfs_iso_packet_desc *iso_frame_desc, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff816a9bd0)
Location: drivers/usb/core/devio.c:1448
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff816a9bd0-ffffffff816aa9d8: proc_do_submiturb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int proc_do_submiturb(struct usb_dev_state *ps, struct usbdevfs_urb *uurb, struct usbdevfs_iso_packet_desc *iso_frame_desc, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff816bec10)
Location: drivers/usb/core/devio.c:1442
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_submiturb_compat
```
**Symbols:**

```
ffffffff816bec10-ffffffff816bf91e: proc_do_submiturb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int proc_do_submiturb(struct usb_dev_state *ps, struct usbdevfs_urb *uurb, struct usbdevfs_iso_packet_desc *iso_frame_desc, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff8172a5e0)
Location: drivers/usb/core/devio.c:1432
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_submiturb_compat
```
**Symbols:**

```
ffffffff8172a5e0-ffffffff8172b2cc: proc_do_submiturb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int proc_do_submiturb(struct usb_dev_state *ps, struct usbdevfs_urb *uurb, struct usbdevfs_iso_packet_desc *iso_frame_desc, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff817690d0)
Location: drivers/usb/core/devio.c:1427
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_submiturb_compat
```
**Symbols:**

```
ffffffff817690d0-ffffffff81769e5a: proc_do_submiturb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int proc_do_submiturb(struct usb_dev_state *ps, struct usbdevfs_urb *uurb, struct usbdevfs_iso_packet_desc *iso_frame_desc, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff8178d750)
Location: drivers/usb/core/devio.c:1428
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_submiturb_compat
```
**Symbols:**

```
ffffffff8178d750-ffffffff8178e506: proc_do_submiturb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int proc_do_submiturb(struct usb_dev_state *ps, struct usbdevfs_urb *uurb, struct usbdevfs_iso_packet_desc *iso_frame_desc, void *arg, sigval_t userurb_sigval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:1450
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff817cc270-ffffffff817ccefa: proc_do_submiturb (STB_LOCAL)
ffffffff817ce2bc-ffffffff817ce41c: proc_do_submiturb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int proc_do_submiturb(struct usb_dev_state *ps, struct usbdevfs_urb *uurb, struct usbdevfs_iso_packet_desc *iso_frame_desc, void *arg, sigval_t userurb_sigval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:1494
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff817fcef0-ffffffff817fdb85: proc_do_submiturb (STB_LOCAL)
ffffffff817ff0ac-ffffffff817ff210: proc_do_submiturb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int proc_do_submiturb(struct usb_dev_state *ps, struct usbdevfs_urb *uurb, struct usbdevfs_iso_packet_desc *iso_frame_desc, void *arg, sigval_t userurb_sigval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:1494
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff818cc510-ffffffff818cd1d3: proc_do_submiturb (STB_LOCAL)
ffffffff818cf596-ffffffff818cf6fa: proc_do_submiturb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int proc_do_submiturb(struct usb_dev_state *ps, struct usbdevfs_urb *uurb, struct usbdevfs_iso_packet_desc *iso_frame_desc, void *arg, sigval_t userurb_sigval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:1508
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff818d76f0-ffffffff818d83cb: proc_do_submiturb (STB_LOCAL)
ffffffff81c1e484-ffffffff81c1e5e8: proc_do_submiturb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int proc_do_submiturb(struct usb_dev_state *ps, struct usbdevfs_urb *uurb, struct usbdevfs_iso_packet_desc *iso_frame_desc, void *arg, sigval_t userurb_sigval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:1513
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff818ba610-ffffffff818bb2ba: proc_do_submiturb (STB_LOCAL)
ffffffff81c1022c-ffffffff81c10390: proc_do_submiturb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int proc_do_submiturb(struct usb_dev_state *ps, struct usbdevfs_urb *uurb, struct usbdevfs_iso_packet_desc *iso_frame_desc, void *arg, sigval_t userurb_sigval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:1591
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff81950d90-ffffffff81951a65: proc_do_submiturb (STB_LOCAL)
ffffffff81d17243-ffffffff81d17381: proc_do_submiturb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int proc_do_submiturb(struct usb_dev_state *ps, struct usbdevfs_urb *uurb, struct usbdevfs_iso_packet_desc *iso_frame_desc, void *arg, sigval_t userurb_sigval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:1607
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff81aa9db0-ffffffff81aaab78: proc_do_submiturb (STB_LOCAL)
ffffffff81ee2177-ffffffff81ee2225: proc_do_submiturb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int proc_do_submiturb(struct usb_dev_state *ps, struct usbdevfs_urb *uurb, struct usbdevfs_iso_packet_desc *iso_frame_desc, void *arg, sigval_t userurb_sigval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:1607
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff81c31130-ffffffff81c31fa3: proc_do_submiturb (STB_LOCAL)
ffffffff8209eab1-ffffffff8209eac6: proc_do_submiturb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int proc_do_submiturb(struct usb_dev_state *ps, struct usbdevfs_urb *uurb, struct usbdevfs_iso_packet_desc *iso_frame_desc, void *arg, sigval_t userurb_sigval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:1616
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff81c983d0-ffffffff81c99283: proc_do_submiturb (STB_LOCAL)
ffffffff8212003e-ffffffff82120053: proc_do_submiturb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int proc_do_submiturb(struct usb_dev_state *ps, struct usbdevfs_urb *uurb, struct usbdevfs_iso_packet_desc *iso_frame_desc, void *arg, sigval_t userurb_sigval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:1616
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff81d4cee0-ffffffff81d4ddf3: proc_do_submiturb (STB_LOCAL)
ffffffff82201815-ffffffff8220182a: proc_do_submiturb.cold (STB_LOCAL)
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
int proc_do_submiturb(struct usb_dev_state *ps, struct usbdevfs_urb *uurb, struct usbdevfs_iso_packet_desc *iso_frame_desc, void *arg, sigval_t userurb_sigval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffff800010a2e580)
Location: drivers/usb/core/devio.c:1494
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffff800010a2e580-ffff800010a2f31c: proc_do_submiturb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int proc_do_submiturb(struct usb_dev_state *ps, struct usbdevfs_urb *uurb, struct usbdevfs_iso_packet_desc *iso_frame_desc, void *arg, sigval_t userurb_sigval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (c0b0428c)
Location: drivers/usb/core/devio.c:1494
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
c0b0428c-c0b051a0: proc_do_submiturb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int proc_do_submiturb(struct usb_dev_state *ps, struct usbdevfs_urb *uurb, struct usbdevfs_iso_packet_desc *iso_frame_desc, void *arg, sigval_t userurb_sigval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (c000000000aed670)
Location: drivers/usb/core/devio.c:1494
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
c000000000aed670-c000000000aee704: proc_do_submiturb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int proc_do_submiturb(struct usb_dev_state *ps, struct usbdevfs_urb *uurb, struct usbdevfs_iso_packet_desc *iso_frame_desc, void *arg, sigval_t userurb_sigval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffe00064e908)
Location: drivers/usb/core/devio.c:1494
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffe00064e908-ffffffe00064f4ba: proc_do_submiturb (STB_LOCAL)
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
int proc_do_submiturb(struct usb_dev_state *ps, struct usbdevfs_urb *uurb, struct usbdevfs_iso_packet_desc *iso_frame_desc, void *arg, sigval_t userurb_sigval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:1494
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff817b52d0-ffffffff817b5f65: proc_do_submiturb (STB_LOCAL)
ffffffff817b748c-ffffffff817b75f0: proc_do_submiturb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int proc_do_submiturb(struct usb_dev_state *ps, struct usbdevfs_urb *uurb, struct usbdevfs_iso_packet_desc *iso_frame_desc, void *arg, sigval_t userurb_sigval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:1494
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff817a6d00-ffffffff817a798f: proc_do_submiturb (STB_LOCAL)
ffffffff817a8eac-ffffffff817a9010: proc_do_submiturb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int proc_do_submiturb(struct usb_dev_state *ps, struct usbdevfs_urb *uurb, struct usbdevfs_iso_packet_desc *iso_frame_desc, void *arg, sigval_t userurb_sigval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:1494
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff817f1d70-ffffffff817f2a05: proc_do_submiturb (STB_LOCAL)
ffffffff817f3f2c-ffffffff817f4090: proc_do_submiturb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int proc_do_submiturb(struct usb_dev_state *ps, struct usbdevfs_urb *uurb, struct usbdevfs_iso_packet_desc *iso_frame_desc, void *arg, sigval_t userurb_sigval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/devio.c (0)
Location: drivers/usb/core/devio.c:1494
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff8180bfb0-ffffffff8180cc84: proc_do_submiturb (STB_LOCAL)
ffffffff8180e1ac-ffffffff8180e2cc: proc_do_submiturb.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>sigval_t userurb_sigval</code>
</li>
</ul>
</details>
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
