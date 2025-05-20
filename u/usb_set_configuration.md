# Function: <code>usb_set_configuration</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int usb_set_configuration(struct usb_device *dev, int configuration);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81612e20)
Location: drivers/usb/core/message.c:1729
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/generic.c:generic_disconnect
  - drivers/usb/core/generic.c:generic_probe
```
**Symbols:**

```
ffffffff81612e20-ffffffff81613701: usb_set_configuration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int usb_set_configuration(struct usb_device *dev, int configuration);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81672db0)
Location: drivers/usb/core/message.c:1726
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/generic.c:generic_disconnect
  - drivers/usb/core/generic.c:generic_probe
```
**Symbols:**

```
ffffffff81672db0-ffffffff816736dd: usb_set_configuration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int usb_set_configuration(struct usb_device *dev, int configuration);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff816a0a60)
Location: drivers/usb/core/message.c:1729
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/generic.c:generic_disconnect
  - drivers/usb/core/generic.c:generic_probe
```
**Symbols:**

```
ffffffff816a0a60-ffffffff816a136a: usb_set_configuration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int usb_set_configuration(struct usb_device *dev, int configuration);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff816b5c20)
Location: drivers/usb/core/message.c:1727
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/generic.c:generic_disconnect
  - drivers/usb/core/generic.c:generic_probe
```
**Symbols:**

```
ffffffff816b5c20-ffffffff816b6464: usb_set_configuration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int usb_set_configuration(struct usb_device *dev, int configuration);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff817214b0)
Location: drivers/usb/core/message.c:1766
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/generic.c:generic_disconnect
  - drivers/usb/core/generic.c:generic_probe
```
**Symbols:**

```
ffffffff817214b0-ffffffff81721cfa: usb_set_configuration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int usb_set_configuration(struct usb_device *dev, int configuration);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff817602b0)
Location: drivers/usb/core/message.c:1803
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/generic.c:generic_disconnect
  - drivers/usb/core/generic.c:generic_probe
```
**Symbols:**

```
ffffffff817602b0-ffffffff81760b30: usb_set_configuration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int usb_set_configuration(struct usb_device *dev, int configuration);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81784870)
Location: drivers/usb/core/message.c:1803
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/generic.c:generic_disconnect
  - drivers/usb/core/generic.c:generic_probe
```
**Symbols:**

```
ffffffff81784870-ffffffff8178511b: usb_set_configuration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int usb_set_configuration(struct usb_device *dev, int configuration);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/message.c (0)
Location: drivers/usb/core/message.c:1805
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/generic.c:generic_disconnect
  - drivers/usb/core/generic.c:generic_probe
```
**Symbols:**

```
ffffffff817c36aa-ffffffff817c37ca: usb_set_configuration.cold (STB_LOCAL)
ffffffff817c2ae0-ffffffff817c32a6: usb_set_configuration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int usb_set_configuration(struct usb_device *dev, int configuration);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/message.c (0)
Location: drivers/usb/core/message.c:1805
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/generic.c:generic_disconnect
  - drivers/usb/core/generic.c:generic_probe
```
**Symbols:**

```
ffffffff817f402a-ffffffff817f414a: usb_set_configuration.cold (STB_LOCAL)
ffffffff817f3460-ffffffff817f3c26: usb_set_configuration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int usb_set_configuration(struct usb_device *dev, int configuration);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/message.c (0)
Location: drivers/usb/core/message.c:1806
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/devio.c:proc_setconfig
  - drivers/usb/core/generic.c:usb_generic_driver_disconnect
  - drivers/usb/core/generic.c:usb_generic_driver_probe
```
**Symbols:**

```
ffffffff818c3bac-ffffffff818c3cad: usb_set_configuration.cold (STB_LOCAL)
ffffffff818c2f50-ffffffff818c37a2: usb_set_configuration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int usb_set_configuration(struct usb_device *dev, int configuration);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/message.c (0)
Location: drivers/usb/core/message.c:1951
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/devio.c:proc_setconfig
  - drivers/usb/core/generic.c:usb_generic_driver_disconnect
  - drivers/usb/core/generic.c:usb_generic_driver_probe
```
**Symbols:**

```
ffffffff81c1d16a-ffffffff81c1d269: usb_set_configuration.cold (STB_LOCAL)
ffffffff818cf260-ffffffff818cfa7f: usb_set_configuration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int usb_set_configuration(struct usb_device *dev, int configuration);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/message.c (0)
Location: drivers/usb/core/message.c:1957
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/generic.c:usb_generic_driver_disconnect
  - drivers/usb/core/generic.c:usb_generic_driver_probe
```
**Symbols:**

```
ffffffff81c0f030-ffffffff81c0f12f: usb_set_configuration.cold (STB_LOCAL)
ffffffff818b2890-ffffffff818b30ab: usb_set_configuration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int usb_set_configuration(struct usb_device *dev, int configuration);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/message.c (0)
Location: drivers/usb/core/message.c:1957
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/generic.c:usb_generic_driver_disconnect
  - drivers/usb/core/generic.c:usb_generic_driver_probe
```
**Symbols:**

```
ffffffff81d161d0-ffffffff81d162ce: usb_set_configuration.cold (STB_LOCAL)
ffffffff81947ba0-ffffffff819484f4: usb_set_configuration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int usb_set_configuration(struct usb_device *dev, int configuration);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/message.c (0)
Location: drivers/usb/core/message.c:1957
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/generic.c:usb_generic_driver_probe
```
**Symbols:**

```
ffffffff81ee0d8f-ffffffff81ee0ead: usb_set_configuration.cold (STB_LOCAL)
ffffffff81aa0510-ffffffff81aa0e9e: usb_set_configuration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int usb_set_configuration(struct usb_device *dev, int configuration);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81c25a40)
Location: drivers/usb/core/message.c:1958
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/generic.c:usb_generic_driver_probe
  - drivers/usb/core/generic.c:usb_generic_driver_probe
```
**Symbols:**

```
ffffffff81c25a40-ffffffff81c264a6: usb_set_configuration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int usb_set_configuration(struct usb_device *dev, int configuration);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81c8c9e0)
Location: drivers/usb/core/message.c:1992
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/generic.c:usb_generic_driver_probe
  - drivers/usb/core/generic.c:usb_generic_driver_probe
```
**Symbols:**

```
ffffffff81c8c9e0-ffffffff81c8d465: usb_set_configuration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int usb_set_configuration(struct usb_device *dev, int configuration);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81d414c0)
Location: drivers/usb/core/message.c:1993
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/generic.c:usb_generic_driver_probe
```
**Symbols:**

```
ffffffff81d414c0-ffffffff81d41f9f: usb_set_configuration (STB_GLOBAL)
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
int usb_set_configuration(struct usb_device *dev, int configuration);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffff800010a24008)
Location: drivers/usb/core/message.c:1805
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/generic.c:generic_disconnect
  - drivers/usb/core/generic.c:generic_probe
```
**Symbols:**

```
ffff800010a24008-ffff800010a248f8: usb_set_configuration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int usb_set_configuration(struct usb_device *dev, int configuration);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (c0afa514)
Location: drivers/usb/core/message.c:1805
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/generic.c:generic_disconnect
  - drivers/usb/core/generic.c:generic_probe
```
**Symbols:**

```
c0afa514-c0afadb4: usb_set_configuration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int usb_set_configuration(struct usb_device *dev, int configuration);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (c000000000adecd0)
Location: drivers/usb/core/message.c:1805
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/generic.c:generic_disconnect
  - drivers/usb/core/generic.c:generic_probe
```
**Symbols:**

```
c000000000adecd0-c000000000adf71c: usb_set_configuration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int usb_set_configuration(struct usb_device *dev, int configuration);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffe0006465c0)
Location: drivers/usb/core/message.c:1805
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/generic.c:generic_disconnect
  - drivers/usb/core/generic.c:generic_probe
```
**Symbols:**

```
ffffffe0006465c0-ffffffe000646d0a: usb_set_configuration (STB_GLOBAL)
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
int usb_set_configuration(struct usb_device *dev, int configuration);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/message.c (0)
Location: drivers/usb/core/message.c:1805
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/generic.c:generic_disconnect
  - drivers/usb/core/generic.c:generic_probe
```
**Symbols:**

```
ffffffff817ac40a-ffffffff817ac52a: usb_set_configuration.cold (STB_LOCAL)
ffffffff817ab840-ffffffff817ac006: usb_set_configuration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int usb_set_configuration(struct usb_device *dev, int configuration);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/message.c (0)
Location: drivers/usb/core/message.c:1805
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/generic.c:generic_disconnect
  - drivers/usb/core/generic.c:generic_probe
```
**Symbols:**

```
ffffffff8179de0a-ffffffff8179df2a: usb_set_configuration.cold (STB_LOCAL)
ffffffff8179d240-ffffffff8179da06: usb_set_configuration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int usb_set_configuration(struct usb_device *dev, int configuration);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/message.c (0)
Location: drivers/usb/core/message.c:1805
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/generic.c:generic_disconnect
  - drivers/usb/core/generic.c:generic_probe
```
**Symbols:**

```
ffffffff817e8eaa-ffffffff817e8fca: usb_set_configuration.cold (STB_LOCAL)
ffffffff817e82e0-ffffffff817e8aa6: usb_set_configuration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int usb_set_configuration(struct usb_device *dev, int configuration);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/message.c (0)
Location: drivers/usb/core/message.c:1805
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/generic.c:generic_disconnect
  - drivers/usb/core/generic.c:generic_probe
```
**Symbols:**

```
ffffffff818030fa-ffffffff8180321a: usb_set_configuration.cold (STB_LOCAL)
ffffffff81802530-ffffffff81802cf4: usb_set_configuration (STB_GLOBAL)
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
