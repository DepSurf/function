# Function: <code>usb_autoresume_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int usb_autoresume_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81614c30)
Location: drivers/usb/core/driver.c:1564
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_device
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
ffffffff81614c30-ffffffff81614c79: usb_autoresume_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int usb_autoresume_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81674be0)
Location: drivers/usb/core/driver.c:1574
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
  - drivers/usb/core/driver.c:usb_probe_device
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
ffffffff81674be0-ffffffff81674c27: usb_autoresume_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int usb_autoresume_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff816a2870)
Location: drivers/usb/core/driver.c:1577
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
  - drivers/usb/core/driver.c:usb_probe_device
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
ffffffff816a2870-ffffffff816a28b7: usb_autoresume_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int usb_autoresume_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff816b7a00)
Location: drivers/usb/core/driver.c:1595
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
  - drivers/usb/core/driver.c:usb_probe_device
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
ffffffff816b7a00-ffffffff816b7a47: usb_autoresume_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int usb_autoresume_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff817232c0)
Location: drivers/usb/core/driver.c:1603
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
  - drivers/usb/core/driver.c:usb_probe_device
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
ffffffff817232c0-ffffffff81723307: usb_autoresume_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int usb_autoresume_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81761f70)
Location: drivers/usb/core/driver.c:1603
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
  - drivers/usb/core/driver.c:usb_probe_device
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
ffffffff81761f70-ffffffff81761fb7: usb_autoresume_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int usb_autoresume_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81786580)
Location: drivers/usb/core/driver.c:1600
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
  - drivers/usb/core/driver.c:usb_probe_device
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
ffffffff81786580-ffffffff817865c7: usb_autoresume_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int usb_autoresume_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff817c4a70)
Location: drivers/usb/core/driver.c:1595
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
  - drivers/usb/core/driver.c:usb_probe_device
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
ffffffff817c4a70-ffffffff817c4ac1: usb_autoresume_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int usb_autoresume_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff817f5410)
Location: drivers/usb/core/driver.c:1597
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
  - drivers/usb/core/driver.c:usb_probe_device
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
ffffffff817f5410-ffffffff817f5461: usb_autoresume_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int usb_autoresume_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff818c4af4)
Location: drivers/usb/core/driver.c:1695
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_device
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_wait_for_resume
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
ffffffff818c5c50-ffffffff818c5ca1: usb_autoresume_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int usb_autoresume_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff818d09e4)
Location: drivers/usb/core/driver.c:1705
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_device
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_wait_for_resume
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
ffffffff818d1b20-ffffffff818d1b71: usb_autoresume_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int usb_autoresume_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff818b3f14)
Location: drivers/usb/core/driver.c:1701
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_device
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
ffffffff818b5140-ffffffff818b518b: usb_autoresume_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int usb_autoresume_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81949444)
Location: drivers/usb/core/driver.c:1701
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_device
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
ffffffff8194a6c0-ffffffff8194a70b: usb_autoresume_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int usb_autoresume_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81aa2294)
Location: drivers/usb/core/driver.c:1703
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_device
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
ffffffff81aa3390-ffffffff81aa33eb: usb_autoresume_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int usb_autoresume_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81c27c64)
Location: drivers/usb/core/driver.c:1703
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_device
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
ffffffff81c28f00-ffffffff81c28f5b: usb_autoresume_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int usb_autoresume_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81c8ec14)
Location: drivers/usb/core/driver.c:1703
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_device
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
ffffffff81c8fed0-ffffffff81c8ff2b: usb_autoresume_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int usb_autoresume_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81d43764)
Location: drivers/usb/core/driver.c:1709
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_device
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
ffffffff81d44a80-ffffffff81d44adb: usb_autoresume_device (STB_GLOBAL)
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
int usb_autoresume_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffff800010a262f0)
Location: drivers/usb/core/driver.c:1597
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
  - drivers/usb/core/driver.c:usb_probe_device
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
ffff800010a262f0-ffff800010a26354: usb_autoresume_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int usb_autoresume_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (c0afc450)
Location: drivers/usb/core/driver.c:1597
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
  - drivers/usb/core/driver.c:usb_probe_device
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
c0afc450-c0afc498: usb_autoresume_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int usb_autoresume_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (c000000000ae1850)
Location: drivers/usb/core/driver.c:1597
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_device
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
c000000000ae1850-c000000000ae18e4: usb_autoresume_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int usb_autoresume_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffe00064822e)
Location: drivers/usb/core/driver.c:1597
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_device
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
ffffffe00064822e-ffffffe000648282: usb_autoresume_device (STB_GLOBAL)
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
int usb_autoresume_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff817ad7f0)
Location: drivers/usb/core/driver.c:1597
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
  - drivers/usb/core/driver.c:usb_probe_device
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
ffffffff817ad7f0-ffffffff817ad841: usb_autoresume_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int usb_autoresume_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff8179f1f0)
Location: drivers/usb/core/driver.c:1597
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
  - drivers/usb/core/driver.c:usb_probe_device
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
ffffffff8179f1f0-ffffffff8179f241: usb_autoresume_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int usb_autoresume_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff817ea290)
Location: drivers/usb/core/driver.c:1597
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
  - drivers/usb/core/driver.c:usb_probe_device
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
ffffffff817ea290-ffffffff817ea2e1: usb_autoresume_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int usb_autoresume_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff818044d0)
Location: drivers/usb/core/driver.c:1597
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
  - drivers/usb/core/driver.c:usb_probe_device
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
ffffffff818044d0-ffffffff81804521: usb_autoresume_device (STB_GLOBAL)
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
