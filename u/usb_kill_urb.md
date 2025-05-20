# Function: <code>usb_kill_urb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void usb_kill_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff81610710)
Location: drivers/usb/core/urb.c:660
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff81610710-ffffffff816107d0: usb_kill_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void usb_kill_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff816702b0)
Location: drivers/usb/core/urb.c:660
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:destroy_async
```
**Symbols:**

```
ffffffff816702b0-ffffffff81670377: usb_kill_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void usb_kill_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff8169df80)
Location: drivers/usb/core/urb.c:660
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:destroy_async
```
**Symbols:**

```
ffffffff8169df80-ffffffff8169e03b: usb_kill_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void usb_kill_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff816b3340)
Location: drivers/usb/core/urb.c:660
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:destroy_async
```
**Symbols:**

```
ffffffff816b3340-ffffffff816b33fb: usb_kill_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void usb_kill_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff8171ea50)
Location: drivers/usb/core/urb.c:683
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:destroy_async
```
**Symbols:**

```
ffffffff8171ea50-ffffffff8171eb0b: usb_kill_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void usb_kill_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff8175d760)
Location: drivers/usb/core/urb.c:688
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:destroy_async
```
**Symbols:**

```
ffffffff8175d760-ffffffff8175d81b: usb_kill_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void usb_kill_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff81781da0)
Location: drivers/usb/core/urb.c:688
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:destroy_async
```
**Symbols:**

```
ffffffff81781da0-ffffffff81781e5b: usb_kill_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void usb_kill_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff817c0260)
Location: drivers/usb/core/urb.c:687
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:destroy_async
```
**Symbols:**

```
ffffffff817c0260-ffffffff817c0314: usb_kill_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void usb_kill_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff817f0be0)
Location: drivers/usb/core/urb.c:688
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:destroy_async
```
**Symbols:**

```
ffffffff817f0be0-ffffffff817f0c94: usb_kill_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void usb_kill_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff818c0724)
Location: drivers/usb/core/urb.c:688
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
Direct callers:
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:destroy_async
```
**Symbols:**

```
ffffffff818c00f0-ffffffff818c0188: usb_kill_urb.part.0 (STB_LOCAL)
ffffffff818c0190-ffffffff818c01c6: usb_kill_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void usb_kill_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff818cc015)
Location: drivers/usb/core/urb.c:703
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
Direct callers:
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:destroy_async
```
**Symbols:**

```
ffffffff818cbbb0-ffffffff818cbc48: usb_kill_urb.part.0 (STB_LOCAL)
ffffffff818cbc50-ffffffff818cbc86: usb_kill_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void usb_kill_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff818af955)
Location: drivers/usb/core/urb.c:703
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
Direct callers:
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:destroy_async
```
**Symbols:**

```
ffffffff818af1d0-ffffffff818af268: usb_kill_urb.part.0 (STB_LOCAL)
ffffffff818af270-ffffffff818af2a6: usb_kill_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void usb_kill_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff81944aa5)
Location: drivers/usb/core/urb.c:712
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
Direct callers:
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbfs_start_wait_urb
  - drivers/usb/core/devio.c:destroy_async
```
**Symbols:**

```
ffffffff81944320-ffffffff819443b8: usb_kill_urb.part.0 (STB_LOCAL)
ffffffff819443c0-ffffffff819443f6: usb_kill_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void usb_kill_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff81a9cd62)
Location: drivers/usb/core/urb.c:712
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
Direct callers:
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbfs_start_wait_urb
  - drivers/usb/core/devio.c:destroy_async
```
**Symbols:**

```
ffffffff81a9c8e0-ffffffff81a9c9af: usb_kill_urb.part.0 (STB_LOCAL)
ffffffff81a9c9b0-ffffffff81a9c9eb: usb_kill_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void usb_kill_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff81c21d92)
Location: drivers/usb/core/urb.c:714
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
Direct callers:
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbfs_start_wait_urb
  - drivers/usb/core/devio.c:destroy_async
```
**Symbols:**

```
ffffffff81c218a0-ffffffff81c2196f: usb_kill_urb.part.0 (STB_LOCAL)
ffffffff81c21980-ffffffff81c219bb: usb_kill_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void usb_kill_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff81c88d1e)
Location: drivers/usb/core/urb.c:714
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
Direct callers:
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbfs_start_wait_urb
  - drivers/usb/core/devio.c:destroy_async
```
**Symbols:**

```
ffffffff81c88820-ffffffff81c888ef: usb_kill_urb.part.0 (STB_LOCAL)
ffffffff81c88900-ffffffff81c8893b: usb_kill_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void usb_kill_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff81d3d76e)
Location: drivers/usb/core/urb.c:699
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
Direct callers:
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbfs_start_wait_urb
  - drivers/usb/core/devio.c:destroy_async
```
**Symbols:**

```
ffffffff81d3d270-ffffffff81d3d33f: usb_kill_urb.part.0 (STB_LOCAL)
ffffffff81d3d350-ffffffff81d3d38b: usb_kill_urb (STB_GLOBAL)
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
void usb_kill_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffff800010a20bd0)
Location: drivers/usb/core/urb.c:688
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:destroy_async
```
**Symbols:**

```
ffff800010a20bd0-ffff800010a20cfc: usb_kill_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void usb_kill_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (c0af79f4)
Location: drivers/usb/core/urb.c:688
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:destroy_async
```
**Symbols:**

```
c0af79f4-c0af7b08: usb_kill_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void usb_kill_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (c000000000adb070)
Location: drivers/usb/core/urb.c:688
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:destroy_async
```
**Symbols:**

```
c000000000adb070-c000000000adb1c4: usb_kill_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void usb_kill_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffe000643c86)
Location: drivers/usb/core/urb.c:688
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:destroy_async
```
**Symbols:**

```
ffffffe000643c86-ffffffe000643d36: usb_kill_urb (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void usb_kill_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff817a8fc0)
Location: drivers/usb/core/urb.c:688
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:destroy_async
```
**Symbols:**

```
ffffffff817a8fc0-ffffffff817a9074: usb_kill_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void usb_kill_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff8179a9d0)
Location: drivers/usb/core/urb.c:688
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:destroy_async
```
**Symbols:**

```
ffffffff8179a9d0-ffffffff8179aa84: usb_kill_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void usb_kill_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff817e5a60)
Location: drivers/usb/core/urb.c:688
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:destroy_async
```
**Symbols:**

```
ffffffff817e5a60-ffffffff817e5b14: usb_kill_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void usb_kill_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff81800068)
Location: drivers/usb/core/urb.c:688
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
Direct callers:
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:destroy_async
```
**Symbols:**

```
ffffffff817ffcc0-ffffffff817ffd54: usb_kill_urb.part.0 (STB_LOCAL)
ffffffff817ffd60-ffffffff817ffd84: usb_kill_urb (STB_GLOBAL)
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
