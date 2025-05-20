# Function: <code>usb_put_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void usb_put_dev(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff816030d0)
Location: drivers/usb/core/usb.c:547
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_release
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb
  - drivers/usb/core/message.c:usb_release_interface
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_release
```
**Symbols:**

```
ffffffff816030d0-ffffffff816030ed: usb_put_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void usb_put_dev(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81662d90)
Location: drivers/usb/core/usb.c:552
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_release
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_release_interface
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
ffffffff81662d90-ffffffff81662dad: usb_put_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void usb_put_dev(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81690b80)
Location: drivers/usb/core/usb.c:566
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_release
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_release_interface
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
ffffffff81690b80-ffffffff81690b9d: usb_put_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void usb_put_dev(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff816a6090)
Location: drivers/usb/core/usb.c:702
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_release
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_release_interface
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
ffffffff816a6090-ffffffff816a60ae: usb_put_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void usb_put_dev(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81711460)
Location: drivers/usb/core/usb.c:702
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_release
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_release_interface
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
ffffffff81711460-ffffffff8171147e: usb_put_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void usb_put_dev(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81750190)
Location: drivers/usb/core/usb.c:703
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_release
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_release_interface
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
ffffffff81750190-ffffffff817501ad: usb_put_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void usb_put_dev(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81774650)
Location: drivers/usb/core/usb.c:703
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_release
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_release_interface
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
ffffffff81774650-ffffffff8177466d: usb_put_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void usb_put_dev(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff817b2760)
Location: drivers/usb/core/usb.c:722
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_release
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_release_interface
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
ffffffff817b2760-ffffffff817b277d: usb_put_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void usb_put_dev(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff817e2e90)
Location: drivers/usb/core/usb.c:722
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_release
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_release_interface
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
ffffffff817e2e90-ffffffff817e2ead: usb_put_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void usb_put_dev(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff818b19e0)
Location: drivers/usb/core/usb.c:722
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:usb_put_invalidate_rhdev
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_release_interface
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
ffffffff818b19e0-ffffffff818b19fd: usb_put_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void usb_put_dev(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff818c0390)
Location: drivers/usb/core/usb.c:709
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:usb_put_invalidate_rhdev
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_release_interface
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
ffffffff818c0390-ffffffff818c03ad: usb_put_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void usb_put_dev(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff818a3570)
Location: drivers/usb/core/usb.c:755
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:usb_put_invalidate_rhdev
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_release_interface
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
ffffffff818a3570-ffffffff818a358d: usb_put_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void usb_put_dev(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81938130)
Location: drivers/usb/core/usb.c:755
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:usb_put_invalidate_rhdev
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_release_interface
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
ffffffff81938130-ffffffff8193814d: usb_put_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void usb_put_dev(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81a8fa50)
Location: drivers/usb/core/usb.c:713
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:usb_put_invalidate_rhdev
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_release_interface
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
ffffffff81a8fa50-ffffffff81a8fa79: usb_put_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void usb_put_dev(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81c117d0)
Location: drivers/usb/core/usb.c:713
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_release_interface
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
ffffffff81c117d0-ffffffff81c117f9: usb_put_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void usb_put_dev(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81c78590)
Location: drivers/usb/core/usb.c:789
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_release_interface
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
ffffffff81c78590-ffffffff81c785b9: usb_put_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void usb_put_dev(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81d2cf90)
Location: drivers/usb/core/usb.c:777
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_release_interface
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
ffffffff81d2cf90-ffffffff81d2cfb9: usb_put_dev (STB_GLOBAL)
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
void usb_put_dev(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffff800010a112c0)
Location: drivers/usb/core/usb.c:722
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_release
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_release_interface
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
ffff800010a112c0-ffff800010a112f0: usb_put_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void usb_put_dev(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (c0ae9928)
Location: drivers/usb/core/usb.c:722
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_release
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_release_interface
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
c0ae9928-c0ae9950: usb_put_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void usb_put_dev(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (c000000000ac8240)
Location: drivers/usb/core/usb.c:722
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_release
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_release_interface
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
c000000000ac8240-c000000000ac8280: usb_put_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void usb_put_dev(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffe000636e38)
Location: drivers/usb/core/usb.c:722
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_release
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_release_interface
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
ffffffe000636e38-ffffffe000636e66: usb_put_dev (STB_GLOBAL)
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
void usb_put_dev(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff8179b270)
Location: drivers/usb/core/usb.c:722
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_release
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_release_interface
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
ffffffff8179b270-ffffffff8179b28d: usb_put_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void usb_put_dev(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff8178cf00)
Location: drivers/usb/core/usb.c:722
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_release
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_release_interface
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
ffffffff8178cf00-ffffffff8178cf1d: usb_put_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void usb_put_dev(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff817d7d10)
Location: drivers/usb/core/usb.c:722
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_release
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_release_interface
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
ffffffff817d7d10-ffffffff817d7d2d: usb_put_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void usb_put_dev(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff817f1fb0)
Location: drivers/usb/core/usb.c:722
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_release
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_release_interface
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
ffffffff817f1fb0-ffffffff817f1fcd: usb_put_dev (STB_GLOBAL)
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
