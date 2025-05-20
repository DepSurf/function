# Function: <code>usb_free_urb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void usb_free_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff816108ad)
Location: drivers/usb/core/urb.c:90
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
Direct callers:
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/message.c:sg_clean
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff81610a00-ffffffff81610a1d: usb_free_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void usb_free_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff81670807)
Location: drivers/usb/core/urb.c:90
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
Direct callers:
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/message.c:sg_clean
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
**Symbols:**

```
ffffffff816706c0-ffffffff816706dd: usb_free_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void usb_free_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff8169e4b7)
Location: drivers/usb/core/urb.c:93
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
Direct callers:
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/message.c:sg_clean
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
**Symbols:**

```
ffffffff8169e370-ffffffff8169e38d: usb_free_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void usb_free_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff816b2bb0)
Location: drivers/usb/core/urb.c:93
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/message.c:sg_clean
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
**Symbols:**

```
ffffffff816b2bb0-ffffffff816b2be5: usb_free_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void usb_free_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff8171ef07)
Location: drivers/usb/core/urb.c:93
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
Direct callers:
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/message.c:sg_clean
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
**Symbols:**

```
ffffffff8171ef30-ffffffff8171ef52: usb_free_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void usb_free_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff8175db87)
Location: drivers/usb/core/urb.c:93
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
Direct callers:
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/message.c:sg_clean
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
**Symbols:**

```
ffffffff8175d900-ffffffff8175d923: usb_free_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void usb_free_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff81782267)
Location: drivers/usb/core/urb.c:93
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
Direct callers:
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/message.c:sg_clean
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
**Symbols:**

```
ffffffff81782290-ffffffff817822b3: usb_free_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void usb_free_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff817c0707)
Location: drivers/usb/core/urb.c:92
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
Direct callers:
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/message.c:sg_clean
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
**Symbols:**

```
ffffffff817c0740-ffffffff817c0761: usb_free_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void usb_free_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff817f1087)
Location: drivers/usb/core/urb.c:93
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
Direct callers:
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/message.c:sg_clean
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
**Symbols:**

```
ffffffff817f10c0-ffffffff817f10e1: usb_free_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void usb_free_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff818c0514)
Location: drivers/usb/core/urb.c:93
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_scuttle_anchored_urbs
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
Direct callers:
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:cancel_bulk_urbs
  - drivers/usb/core/devio.c:free_async
```
**Symbols:**

```
ffffffff818c05b0-ffffffff818c0607: usb_free_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void usb_free_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff818cbee1)
Location: drivers/usb/core/urb.c:93
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_scuttle_anchored_urbs
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
Direct callers:
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:cancel_bulk_urbs
  - drivers/usb/core/devio.c:free_async
```
**Symbols:**

```
ffffffff818cc470-ffffffff818cc4c7: usb_free_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void usb_free_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff818af501)
Location: drivers/usb/core/urb.c:93
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_scuttle_anchored_urbs
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
Direct callers:
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
**Symbols:**

```
ffffffff818af880-ffffffff818af8d7: usb_free_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void usb_free_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff81944651)
Location: drivers/usb/core/urb.c:93
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_scuttle_anchored_urbs
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
Direct callers:
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
**Symbols:**

```
ffffffff819449d0-ffffffff81944a27: usb_free_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void usb_free_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff81a9d207)
Location: drivers/usb/core/urb.c:93
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_scuttle_anchored_urbs
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
Direct callers:
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/urb.c:usb_scuttle_anchored_urbs
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
**Symbols:**

```
ffffffff81a9cec0-ffffffff81a9cf32: usb_free_urb.part.0 (STB_LOCAL)
ffffffff81a9d290-ffffffff81a9d304: usb_free_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void usb_free_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff81c222a7)
Location: drivers/usb/core/urb.c:94
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_scuttle_anchored_urbs
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
Direct callers:
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/urb.c:usb_scuttle_anchored_urbs
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
**Symbols:**

```
ffffffff81c21f10-ffffffff81c21f82: usb_free_urb.part.0 (STB_LOCAL)
ffffffff81c22340-ffffffff81c223b4: usb_free_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void usb_free_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff81c89217)
Location: drivers/usb/core/urb.c:94
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_scuttle_anchored_urbs
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
Direct callers:
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/urb.c:usb_scuttle_anchored_urbs
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
**Symbols:**

```
ffffffff81c88e80-ffffffff81c88ef2: usb_free_urb.part.0 (STB_LOCAL)
ffffffff81c892b0-ffffffff81c89324: usb_free_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void usb_free_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff81d3dc67)
Location: drivers/usb/core/urb.c:94
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_scuttle_anchored_urbs
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
Direct callers:
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/urb.c:usb_scuttle_anchored_urbs
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
**Symbols:**

```
ffffffff81d3d8d0-ffffffff81d3d942: usb_free_urb.part.0 (STB_LOCAL)
ffffffff81d3dd00-ffffffff81d3dd74: usb_free_urb (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void usb_free_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/urb.c (ffff800010a21248)
Location: drivers/usb/core/urb.c:93
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
Direct callers:
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/message.c:sg_clean
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
**Symbols:**

```
ffff800010a20768-ffff800010a207c4: usb_free_urb.part.0 (STB_LOCAL)
ffff800010a207c8-ffff800010a207f8: usb_free_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void usb_free_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/urb.c (c0af7ebc)
Location: drivers/usb/core/urb.c:93
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
Direct callers:
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/message.c:sg_clean
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
**Symbols:**

```
c0af7924-c0af796c: usb_free_urb.part.0 (STB_LOCAL)
c0af796c-c0af7990: usb_free_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void usb_free_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (c000000000ada170)
Location: drivers/usb/core/urb.c:93
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/message.c:sg_clean
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
**Symbols:**

```
c000000000ada170-c000000000ada210: usb_free_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void usb_free_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffe000643bd2)
Location: drivers/usb/core/urb.c:93
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
Direct callers:
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/message.c:sg_clean
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
**Symbols:**

```
ffffffe000643328-ffffffe00064336c: usb_free_urb (STB_GLOBAL)
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
void usb_free_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff817a9467)
Location: drivers/usb/core/urb.c:93
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
Direct callers:
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/message.c:sg_clean
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
**Symbols:**

```
ffffffff817a94a0-ffffffff817a94c1: usb_free_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void usb_free_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff8179ae67)
Location: drivers/usb/core/urb.c:93
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
Direct callers:
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/message.c:sg_clean
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
**Symbols:**

```
ffffffff8179aea0-ffffffff8179aec1: usb_free_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void usb_free_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff817e5f07)
Location: drivers/usb/core/urb.c:93
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
Direct callers:
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/message.c:sg_clean
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
**Symbols:**

```
ffffffff817e5f40-ffffffff817e5f61: usb_free_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void usb_free_urb(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff81800167)
Location: drivers/usb/core/urb.c:93
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
Direct callers:
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/message.c:sg_clean
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
**Symbols:**

```
ffffffff818001a0-ffffffff818001c1: usb_free_urb (STB_GLOBAL)
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
