# Function: <code>usb_ifnum_to_if</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct usb_interface *usb_ifnum_to_if(const struct usb_device *dev, unsigned int ifnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81602f20)
Location: drivers/usb/core/usb.c:139
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
  - drivers/usb/core/devio.c:proc_ioctl
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
```
**Symbols:**

```
ffffffff81602f20-ffffffff81602f7f: usb_ifnum_to_if (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct usb_interface *usb_ifnum_to_if(const struct usb_device *dev, unsigned int ifnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81662be0)
Location: drivers/usb/core/usb.c:135
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:proc_ioctl
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
```
**Symbols:**

```
ffffffff81662be0-ffffffff81662c3f: usb_ifnum_to_if (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct usb_interface *usb_ifnum_to_if(const struct usb_device *dev, unsigned int ifnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff816909d0)
Location: drivers/usb/core/usb.c:138
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:proc_ioctl
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
```
**Symbols:**

```
ffffffff816909d0-ffffffff81690a2f: usb_ifnum_to_if (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct usb_interface *usb_ifnum_to_if(const struct usb_device *dev, unsigned int ifnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff816a5f20)
Location: drivers/usb/core/usb.c:272
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:proc_ioctl
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
```
**Symbols:**

```
ffffffff816a5f20-ffffffff816a5f7a: usb_ifnum_to_if (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct usb_interface *usb_ifnum_to_if(const struct usb_device *dev, unsigned int ifnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff817112f0)
Location: drivers/usb/core/usb.c:272
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:proc_ioctl
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
```
**Symbols:**

```
ffffffff817112f0-ffffffff8171134a: usb_ifnum_to_if (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct usb_interface *usb_ifnum_to_if(const struct usb_device *dev, unsigned int ifnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81750070)
Location: drivers/usb/core/usb.c:274
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:proc_ioctl
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
```
**Symbols:**

```
ffffffff81750070-ffffffff817500ca: usb_ifnum_to_if (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct usb_interface *usb_ifnum_to_if(const struct usb_device *dev, unsigned int ifnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff817744a0)
Location: drivers/usb/core/usb.c:274
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:proc_ioctl
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
```
**Symbols:**

```
ffffffff817744a0-ffffffff817744ff: usb_ifnum_to_if (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct usb_interface *usb_ifnum_to_if(const struct usb_device *dev, unsigned int ifnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff817b25d0)
Location: drivers/usb/core/usb.c:273
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
```
**Symbols:**

```
ffffffff817b25d0-ffffffff817b2626: usb_ifnum_to_if (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct usb_interface *usb_ifnum_to_if(const struct usb_device *dev, unsigned int ifnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff817e2d00)
Location: drivers/usb/core/usb.c:273
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
```
**Symbols:**

```
ffffffff817e2d00-ffffffff817e2d56: usb_ifnum_to_if (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct usb_interface *usb_ifnum_to_if(const struct usb_device *dev, unsigned int ifnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff818b1850)
Location: drivers/usb/core/usb.c:273
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:proc_getdriver
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
```
**Symbols:**

```
ffffffff818b1850-ffffffff818b18a6: usb_ifnum_to_if (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct usb_interface *usb_ifnum_to_if(const struct usb_device *dev, unsigned int ifnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff818c0200)
Location: drivers/usb/core/usb.c:271
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:proc_getdriver
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
```
**Symbols:**

```
ffffffff818c0200-ffffffff818c0256: usb_ifnum_to_if (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct usb_interface *usb_ifnum_to_if(const struct usb_device *dev, unsigned int ifnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff818a33f0)
Location: drivers/usb/core/usb.c:271
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:proc_getdriver
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
```
**Symbols:**

```
ffffffff818a33f0-ffffffff818a3446: usb_ifnum_to_if (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct usb_interface *usb_ifnum_to_if(const struct usb_device *dev, unsigned int ifnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81937f70)
Location: drivers/usb/core/usb.c:271
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:proc_getdriver
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
```
**Symbols:**

```
ffffffff81937f70-ffffffff8193800a: usb_ifnum_to_if (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct usb_interface *usb_ifnum_to_if(const struct usb_device *dev, unsigned int ifnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81a8f700)
Location: drivers/usb/core/usb.c:271
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:proc_ioctl
  - drivers/usb/core/devio.c:proc_getdriver
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
```
**Symbols:**

```
ffffffff81a8f700-ffffffff81a8f7a4: usb_ifnum_to_if (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct usb_interface *usb_ifnum_to_if(const struct usb_device *dev, unsigned int ifnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81c113c0)
Location: drivers/usb/core/usb.c:271
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:proc_ioctl
  - drivers/usb/core/devio.c:proc_getdriver
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
```
**Symbols:**

```
ffffffff81c113c0-ffffffff81c11464: usb_ifnum_to_if (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct usb_interface *usb_ifnum_to_if(const struct usb_device *dev, unsigned int ifnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81c78180)
Location: drivers/usb/core/usb.c:347
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:proc_ioctl
  - drivers/usb/core/devio.c:proc_getdriver
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
```
**Symbols:**

```
ffffffff81c78180-ffffffff81c78224: usb_ifnum_to_if (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct usb_interface *usb_ifnum_to_if(const struct usb_device *dev, unsigned int ifnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81d2cb80)
Location: drivers/usb/core/usb.c:348
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:proc_ioctl
  - drivers/usb/core/devio.c:proc_getdriver
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
```
**Symbols:**

```
ffffffff81d2cb80-ffffffff81d2cc24: usb_ifnum_to_if (STB_GLOBAL)
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
struct usb_interface *usb_ifnum_to_if(const struct usb_device *dev, unsigned int ifnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffff800010a11048)
Location: drivers/usb/core/usb.c:273
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
```
**Symbols:**

```
ffff800010a11048-ffff800010a110c4: usb_ifnum_to_if (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct usb_interface *usb_ifnum_to_if(const struct usb_device *dev, unsigned int ifnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (c0ae973c)
Location: drivers/usb/core/usb.c:273
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:proc_getdriver
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
```
**Symbols:**

```
c0ae973c-c0ae9798: usb_ifnum_to_if (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct usb_interface *usb_ifnum_to_if(const struct usb_device *dev, unsigned int ifnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (c000000000ac7ff0)
Location: drivers/usb/core/usb.c:273
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:proc_getdriver
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
```
**Symbols:**

```
c000000000ac7ff0-c000000000ac8054: usb_ifnum_to_if (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct usb_interface *usb_ifnum_to_if(const struct usb_device *dev, unsigned int ifnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffe000636c6c)
Location: drivers/usb/core/usb.c:273
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:proc_getdriver
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
```
**Symbols:**

```
ffffffe000636c6c-ffffffe000636cd2: usb_ifnum_to_if (STB_GLOBAL)
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
struct usb_interface *usb_ifnum_to_if(const struct usb_device *dev, unsigned int ifnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff8179b0e0)
Location: drivers/usb/core/usb.c:273
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
```
**Symbols:**

```
ffffffff8179b0e0-ffffffff8179b136: usb_ifnum_to_if (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct usb_interface *usb_ifnum_to_if(const struct usb_device *dev, unsigned int ifnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff8178cd70)
Location: drivers/usb/core/usb.c:273
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
```
**Symbols:**

```
ffffffff8178cd70-ffffffff8178cdc6: usb_ifnum_to_if (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct usb_interface *usb_ifnum_to_if(const struct usb_device *dev, unsigned int ifnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff817d7b80)
Location: drivers/usb/core/usb.c:273
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
```
**Symbols:**

```
ffffffff817d7b80-ffffffff817d7bd6: usb_ifnum_to_if (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct usb_interface *usb_ifnum_to_if(const struct usb_device *dev, unsigned int ifnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff817f1e20)
Location: drivers/usb/core/usb.c:273
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
```
**Symbols:**

```
ffffffff817f1e20-ffffffff817f1e76: usb_ifnum_to_if (STB_GLOBAL)
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
