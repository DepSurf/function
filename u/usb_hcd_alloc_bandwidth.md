# Function: <code>usb_hcd_alloc_bandwidth</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int usb_hcd_alloc_bandwidth(struct usb_device *udev, struct usb_host_config *new_config, struct usb_host_interface *cur_alt, struct usb_host_interface *new_alt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8160f510)
Location: drivers/usb/core/hcd.c:1958
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
```
**Symbols:**

```
ffffffff8160f510-ffffffff8160f81b: usb_hcd_alloc_bandwidth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int usb_hcd_alloc_bandwidth(struct usb_device *udev, struct usb_host_config *new_config, struct usb_host_interface *cur_alt, struct usb_host_interface *new_alt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8166f0e0)
Location: drivers/usb/core/hcd.c:1954
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
ffffffff8166f0e0-ffffffff8166f3f1: usb_hcd_alloc_bandwidth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int usb_hcd_alloc_bandwidth(struct usb_device *udev, struct usb_host_config *new_config, struct usb_host_interface *cur_alt, struct usb_host_interface *new_alt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8169cdc0)
Location: drivers/usb/core/hcd.c:1955
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
ffffffff8169cdc0-ffffffff8169d0d1: usb_hcd_alloc_bandwidth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int usb_hcd_alloc_bandwidth(struct usb_device *udev, struct usb_host_config *new_config, struct usb_host_interface *cur_alt, struct usb_host_interface *new_alt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff816b2190)
Location: drivers/usb/core/hcd.c:1969
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
ffffffff816b2190-ffffffff816b24a5: usb_hcd_alloc_bandwidth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int usb_hcd_alloc_bandwidth(struct usb_device *udev, struct usb_host_config *new_config, struct usb_host_interface *cur_alt, struct usb_host_interface *new_alt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8171d7d0)
Location: drivers/usb/core/hcd.c:1958
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
ffffffff8171d7d0-ffffffff8171db2a: usb_hcd_alloc_bandwidth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int usb_hcd_alloc_bandwidth(struct usb_device *udev, struct usb_host_config *new_config, struct usb_host_interface *cur_alt, struct usb_host_interface *new_alt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8175c420)
Location: drivers/usb/core/hcd.c:1960
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
ffffffff8175c420-ffffffff8175c78f: usb_hcd_alloc_bandwidth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int usb_hcd_alloc_bandwidth(struct usb_device *udev, struct usb_host_config *new_config, struct usb_host_interface *cur_alt, struct usb_host_interface *new_alt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817809e0)
Location: drivers/usb/core/hcd.c:1944
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
ffffffff817809e0-ffffffff81780d4f: usb_hcd_alloc_bandwidth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int usb_hcd_alloc_bandwidth(struct usb_device *udev, struct usb_host_config *new_config, struct usb_host_interface *cur_alt, struct usb_host_interface *new_alt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817be3f0)
Location: drivers/usb/core/hcd.c:1833
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
ffffffff817be3f0-ffffffff817be755: usb_hcd_alloc_bandwidth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int usb_hcd_alloc_bandwidth(struct usb_device *udev, struct usb_host_config *new_config, struct usb_host_interface *cur_alt, struct usb_host_interface *new_alt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817eed50)
Location: drivers/usb/core/hcd.c:1830
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
ffffffff817eed50-ffffffff817ef0b5: usb_hcd_alloc_bandwidth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int usb_hcd_alloc_bandwidth(struct usb_device *udev, struct usb_host_config *new_config, struct usb_host_interface *cur_alt, struct usb_host_interface *new_alt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff818be380)
Location: drivers/usb/core/hcd.c:1827
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_disable_device_endpoints
```
**Symbols:**

```
ffffffff818be380-ffffffff818be6e5: usb_hcd_alloc_bandwidth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int usb_hcd_alloc_bandwidth(struct usb_device *udev, struct usb_host_config *new_config, struct usb_host_interface *cur_alt, struct usb_host_interface *new_alt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff818caf80)
Location: drivers/usb/core/hcd.c:1837
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_disable_device_endpoints
```
**Symbols:**

```
ffffffff818caf80-ffffffff818cb2e5: usb_hcd_alloc_bandwidth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int usb_hcd_alloc_bandwidth(struct usb_device *udev, struct usb_host_config *new_config, struct usb_host_interface *cur_alt, struct usb_host_interface *new_alt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff818ae5a0)
Location: drivers/usb/core/hcd.c:1837
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_disable_device_endpoints
```
**Symbols:**

```
ffffffff818ae5a0-ffffffff818ae905: usb_hcd_alloc_bandwidth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int usb_hcd_alloc_bandwidth(struct usb_device *udev, struct usb_host_config *new_config, struct usb_host_interface *cur_alt, struct usb_host_interface *new_alt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81943670)
Location: drivers/usb/core/hcd.c:1858
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_disable_device_endpoints
```
**Symbols:**

```
ffffffff81943670-ffffffff81943a65: usb_hcd_alloc_bandwidth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int usb_hcd_alloc_bandwidth(struct usb_device *udev, struct usb_host_config *new_config, struct usb_host_interface *cur_alt, struct usb_host_interface *new_alt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81a9bad0)
Location: drivers/usb/core/hcd.c:1861
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_disable_device_endpoints
```
**Symbols:**

```
ffffffff81a9bad0-ffffffff81a9bed8: usb_hcd_alloc_bandwidth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int usb_hcd_alloc_bandwidth(struct usb_device *udev, struct usb_host_config *new_config, struct usb_host_interface *cur_alt, struct usb_host_interface *new_alt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81c20950)
Location: drivers/usb/core/hcd.c:1862
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_disable_device_endpoints
```
**Symbols:**

```
ffffffff81c20950-ffffffff81c20d58: usb_hcd_alloc_bandwidth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int usb_hcd_alloc_bandwidth(struct usb_device *udev, struct usb_host_config *new_config, struct usb_host_interface *cur_alt, struct usb_host_interface *new_alt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81c878d0)
Location: drivers/usb/core/hcd.c:1866
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_disable_device_endpoints
```
**Symbols:**

```
ffffffff81c878d0-ffffffff81c87cd8: usb_hcd_alloc_bandwidth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int usb_hcd_alloc_bandwidth(struct usb_device *udev, struct usb_host_config *new_config, struct usb_host_interface *cur_alt, struct usb_host_interface *new_alt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81d3c320)
Location: drivers/usb/core/hcd.c:1841
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_disable_device_endpoints
```
**Symbols:**

```
ffffffff81d3c320-ffffffff81d3c728: usb_hcd_alloc_bandwidth (STB_GLOBAL)
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
int usb_hcd_alloc_bandwidth(struct usb_device *udev, struct usb_host_config *new_config, struct usb_host_interface *cur_alt, struct usb_host_interface *new_alt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffff800010a1eaf8)
Location: drivers/usb/core/hcd.c:1830
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
ffff800010a1eaf8-ffff800010a1ee44: usb_hcd_alloc_bandwidth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int usb_hcd_alloc_bandwidth(struct usb_device *udev, struct usb_host_config *new_config, struct usb_host_interface *cur_alt, struct usb_host_interface *new_alt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (c0af6230)
Location: drivers/usb/core/hcd.c:1830
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
c0af6230-c0af654c: usb_hcd_alloc_bandwidth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int usb_hcd_alloc_bandwidth(struct usb_device *udev, struct usb_host_config *new_config, struct usb_host_interface *cur_alt, struct usb_host_interface *new_alt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (c000000000ad8bd0)
Location: drivers/usb/core/hcd.c:1830
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
c000000000ad8bd0-c000000000ad9048: usb_hcd_alloc_bandwidth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int usb_hcd_alloc_bandwidth(struct usb_device *udev, struct usb_host_config *new_config, struct usb_host_interface *cur_alt, struct usb_host_interface *new_alt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffe000642528)
Location: drivers/usb/core/hcd.c:1830
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
ffffffe000642528-ffffffe000642750: usb_hcd_alloc_bandwidth (STB_GLOBAL)
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
int usb_hcd_alloc_bandwidth(struct usb_device *udev, struct usb_host_config *new_config, struct usb_host_interface *cur_alt, struct usb_host_interface *new_alt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817a7130)
Location: drivers/usb/core/hcd.c:1830
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
ffffffff817a7130-ffffffff817a7495: usb_hcd_alloc_bandwidth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int usb_hcd_alloc_bandwidth(struct usb_device *udev, struct usb_host_config *new_config, struct usb_host_interface *cur_alt, struct usb_host_interface *new_alt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81798b80)
Location: drivers/usb/core/hcd.c:1830
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
ffffffff81798b80-ffffffff81798ee5: usb_hcd_alloc_bandwidth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int usb_hcd_alloc_bandwidth(struct usb_device *udev, struct usb_host_config *new_config, struct usb_host_interface *cur_alt, struct usb_host_interface *new_alt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817e3bd0)
Location: drivers/usb/core/hcd.c:1830
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
ffffffff817e3bd0-ffffffff817e3f35: usb_hcd_alloc_bandwidth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int usb_hcd_alloc_bandwidth(struct usb_device *udev, struct usb_host_config *new_config, struct usb_host_interface *cur_alt, struct usb_host_interface *new_alt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817fde80)
Location: drivers/usb/core/hcd.c:1830
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
ffffffff817fde80-ffffffff817fe1e5: usb_hcd_alloc_bandwidth (STB_GLOBAL)
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
