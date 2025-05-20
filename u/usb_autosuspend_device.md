# Function: <code>usb_autosuspend_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void usb_autosuspend_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff816146dd)
Location: drivers/usb/core/driver.c:1533
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/devio.c:usbdev_release
```
**Symbols:**

```
ffffffff81614c00-ffffffff81614c2a: usb_autosuspend_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void usb_autosuspend_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81674dee)
Location: drivers/usb/core/driver.c:1543
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/devio.c:usbdev_release
```
**Symbols:**

```
ffffffff81674bb0-ffffffff81674bda: usb_autosuspend_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void usb_autosuspend_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff816a2a7e)
Location: drivers/usb/core/driver.c:1546
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/devio.c:usbdev_release
```
**Symbols:**

```
ffffffff816a2840-ffffffff816a286a: usb_autosuspend_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void usb_autosuspend_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff816b7b9e)
Location: drivers/usb/core/driver.c:1564
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/devio.c:usbdev_release
```
**Symbols:**

```
ffffffff816b79d0-ffffffff816b79fa: usb_autosuspend_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void usb_autosuspend_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81723463)
Location: drivers/usb/core/driver.c:1572
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/devio.c:usbdev_release
```
**Symbols:**

```
ffffffff81723290-ffffffff817232ba: usb_autosuspend_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void usb_autosuspend_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff817621fa)
Location: drivers/usb/core/driver.c:1572
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/devio.c:usbdev_release
```
**Symbols:**

```
ffffffff81761f40-ffffffff81761f6a: usb_autosuspend_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void usb_autosuspend_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff8178680a)
Location: drivers/usb/core/driver.c:1569
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/devio.c:usbdev_release
```
**Symbols:**

```
ffffffff81786550-ffffffff8178657d: usb_autosuspend_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void usb_autosuspend_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff817c4cb6)
Location: drivers/usb/core/driver.c:1564
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/devio.c:usbdev_release
```
**Symbols:**

```
ffffffff817c4a40-ffffffff817c4a6d: usb_autosuspend_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void usb_autosuspend_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff817f5656)
Location: drivers/usb/core/driver.c:1566
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_release
```
**Symbols:**

```
ffffffff817f53e0-ffffffff817f540d: usb_autosuspend_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void usb_autosuspend_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff818c4cd2)
Location: drivers/usb/core/driver.c:1664
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_unbind_device
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_release
```
**Symbols:**

```
ffffffff818c5c20-ffffffff818c5c50: usb_autosuspend_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void usb_autosuspend_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff818d0bba)
Location: drivers/usb/core/driver.c:1674
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_unbind_device
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_release
```
**Symbols:**

```
ffffffff818d1af0-ffffffff818d1b20: usb_autosuspend_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void usb_autosuspend_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff818b40e7)
Location: drivers/usb/core/driver.c:1670
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_unbind_device
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_release
```
**Symbols:**

```
ffffffff818b5110-ffffffff818b5140: usb_autosuspend_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void usb_autosuspend_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81949617)
Location: drivers/usb/core/driver.c:1670
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_unbind_device
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_release
```
**Symbols:**

```
ffffffff8194a690-ffffffff8194a6c0: usb_autosuspend_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void usb_autosuspend_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81aa2474)
Location: drivers/usb/core/driver.c:1672
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_unbind_device
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_release
```
**Symbols:**

```
ffffffff81aa3350-ffffffff81aa338a: usb_autosuspend_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void usb_autosuspend_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81c27e44)
Location: drivers/usb/core/driver.c:1672
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_unbind_device
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_release
```
**Symbols:**

```
ffffffff81c28eb0-ffffffff81c28eea: usb_autosuspend_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void usb_autosuspend_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81c8edf4)
Location: drivers/usb/core/driver.c:1672
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_unbind_device
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_release
```
**Symbols:**

```
ffffffff81c8fe80-ffffffff81c8feba: usb_autosuspend_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void usb_autosuspend_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81d43974)
Location: drivers/usb/core/driver.c:1678
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_unbind_device
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_release
```
**Symbols:**

```
ffffffff81d44a30-ffffffff81d44a6a: usb_autosuspend_device (STB_GLOBAL)
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
void usb_autosuspend_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffff800010a2654c)
Location: drivers/usb/core/driver.c:1566
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_release
```
**Symbols:**

```
ffff800010a262b8-ffff800010a262f0: usb_autosuspend_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void usb_autosuspend_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (c0afc3c8)
Location: drivers/usb/core/driver.c:1566
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_unbind_device
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_release
```
**Symbols:**

```
c0afc3c8-c0afc404: usb_autosuspend_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void usb_autosuspend_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (c000000000ae1b70)
Location: drivers/usb/core/driver.c:1566
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_release
```
**Symbols:**

```
c000000000ae17f0-c000000000ae1848: usb_autosuspend_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void usb_autosuspend_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffe000648426)
Location: drivers/usb/core/driver.c:1566
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_release
```
**Symbols:**

```
ffffffe0006481f4-ffffffe00064822e: usb_autosuspend_device (STB_GLOBAL)
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
void usb_autosuspend_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff817ada36)
Location: drivers/usb/core/driver.c:1566
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_release
```
**Symbols:**

```
ffffffff817ad7c0-ffffffff817ad7ed: usb_autosuspend_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void usb_autosuspend_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff8179f436)
Location: drivers/usb/core/driver.c:1566
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_release
```
**Symbols:**

```
ffffffff8179f1c0-ffffffff8179f1ed: usb_autosuspend_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void usb_autosuspend_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff817ea4d6)
Location: drivers/usb/core/driver.c:1566
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_release
```
**Symbols:**

```
ffffffff817ea260-ffffffff817ea28d: usb_autosuspend_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void usb_autosuspend_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81804716)
Location: drivers/usb/core/driver.c:1566
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_release
```
**Symbols:**

```
ffffffff818044a0-ffffffff818044cd: usb_autosuspend_device (STB_GLOBAL)
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
