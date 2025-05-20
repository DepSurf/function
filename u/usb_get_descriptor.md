# Function: <code>usb_get_descriptor</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int usb_get_descriptor(struct usb_device *dev, unsigned char type, unsigned char index, void *buf, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81611920)
Location: drivers/usb/core/message.c:633
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:descriptors_changed
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/message.c:usb_get_device_descriptor
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
```
**Symbols:**

```
ffffffff81611920-ffffffff816119d5: usb_get_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int usb_get_descriptor(struct usb_device *dev, unsigned char type, unsigned char index, void *buf, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81671520)
Location: drivers/usb/core/message.c:630
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:descriptors_changed
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/message.c:usb_get_device_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
ffffffff81671520-ffffffff816715d5: usb_get_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int usb_get_descriptor(struct usb_device *dev, unsigned char type, unsigned char index, void *buf, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff8169f1d0)
Location: drivers/usb/core/message.c:633
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/message.c:usb_get_device_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
ffffffff8169f1d0-ffffffff8169f285: usb_get_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int usb_get_descriptor(struct usb_device *dev, unsigned char type, unsigned char index, void *buf, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff816b43f0)
Location: drivers/usb/core/message.c:631
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:descriptors_changed
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/message.c:usb_get_device_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
ffffffff816b43f0-ffffffff816b449f: usb_get_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int usb_get_descriptor(struct usb_device *dev, unsigned char type, unsigned char index, void *buf, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff8171fc20)
Location: drivers/usb/core/message.c:635
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:descriptors_changed
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/message.c:usb_get_device_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
ffffffff8171fc20-ffffffff8171fccf: usb_get_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int usb_get_descriptor(struct usb_device *dev, unsigned char type, unsigned char index, void *buf, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff8175e580)
Location: drivers/usb/core/message.c:636
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:descriptors_changed
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/message.c:usb_get_device_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
ffffffff8175e580-ffffffff8175e63e: usb_get_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int usb_get_descriptor(struct usb_device *dev, unsigned char type, unsigned char index, void *buf, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81782d00)
Location: drivers/usb/core/message.c:637
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:descriptors_changed
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/message.c:usb_get_device_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
ffffffff81782d00-ffffffff81782dbe: usb_get_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int usb_get_descriptor(struct usb_device *dev, unsigned char type, unsigned char index, void *buf, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff817c1120)
Location: drivers/usb/core/message.c:637
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:descriptors_changed
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/message.c:usb_get_device_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
ffffffff817c1120-ffffffff817c11df: usb_get_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int usb_get_descriptor(struct usb_device *dev, unsigned char type, unsigned char index, void *buf, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff817f1aa0)
Location: drivers/usb/core/message.c:637
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:descriptors_changed
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/message.c:usb_get_device_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
ffffffff817f1aa0-ffffffff817f1b5f: usb_get_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int usb_get_descriptor(struct usb_device *dev, unsigned char type, unsigned char index, void *buf, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff818c1420)
Location: drivers/usb/core/message.c:645
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/message.c:usb_get_device_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
ffffffff818c1420-ffffffff818c14df: usb_get_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int usb_get_descriptor(struct usb_device *dev, unsigned char type, unsigned char index, void *buf, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff818cd6d0)
Location: drivers/usb/core/message.c:780
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/message.c:usb_get_device_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
ffffffff818cd6d0-ffffffff818cd78f: usb_get_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int usb_get_descriptor(struct usb_device *dev, unsigned char type, unsigned char index, void *buf, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff818b0cf0)
Location: drivers/usb/core/message.c:780
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/message.c:usb_get_device_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
ffffffff818b0cf0-ffffffff818b0dc3: usb_get_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int usb_get_descriptor(struct usb_device *dev, unsigned char type, unsigned char index, void *buf, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81945f50)
Location: drivers/usb/core/message.c:780
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/message.c:usb_get_device_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
ffffffff81945f50-ffffffff81946023: usb_get_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int usb_get_descriptor(struct usb_device *dev, unsigned char type, unsigned char index, void *buf, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81a9e6d0)
Location: drivers/usb/core/message.c:780
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:descriptors_changed
  - drivers/usb/core/message.c:usb_get_device_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
ffffffff81a9e6d0-ffffffff81a9e7c2: usb_get_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int usb_get_descriptor(struct usb_device *dev, unsigned char type, unsigned char index, void *buf, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81c237c0)
Location: drivers/usb/core/message.c:780
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:descriptors_changed
  - drivers/usb/core/message.c:usb_get_device_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
ffffffff81c237c0-ffffffff81c238b2: usb_get_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int usb_get_descriptor(struct usb_device *dev, unsigned char type, unsigned char index, void *buf, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81c8a740)
Location: drivers/usb/core/message.c:780
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:descriptors_changed
  - drivers/usb/core/message.c:usb_get_device_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
ffffffff81c8a740-ffffffff81c8a832: usb_get_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int usb_get_descriptor(struct usb_device *dev, unsigned char type, unsigned char index, void *buf, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81d3f160)
Location: drivers/usb/core/message.c:781
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:descriptors_changed
  - drivers/usb/core/message.c:usb_get_device_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
ffffffff81d3f160-ffffffff81d3f252: usb_get_descriptor (STB_GLOBAL)
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
int usb_get_descriptor(struct usb_device *dev, unsigned char type, unsigned char index, void *buf, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffff800010a21d78)
Location: drivers/usb/core/message.c:637
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:descriptors_changed
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/message.c:usb_get_device_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
ffff800010a21d78-ffff800010a21e7c: usb_get_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int usb_get_descriptor(struct usb_device *dev, unsigned char type, unsigned char index, void *buf, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (c0af8b94)
Location: drivers/usb/core/message.c:637
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:descriptors_changed
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/message.c:usb_get_device_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
c0af8b94-c0af8c68: usb_get_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int usb_get_descriptor(struct usb_device *dev, unsigned char type, unsigned char index, void *buf, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (c000000000adc5e0)
Location: drivers/usb/core/message.c:637
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:descriptors_changed
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/message.c:usb_get_device_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
c000000000adc5e0-c000000000adc734: usb_get_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int usb_get_descriptor(struct usb_device *dev, unsigned char type, unsigned char index, void *buf, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffe000644aae)
Location: drivers/usb/core/message.c:637
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/message.c:usb_get_device_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
ffffffe000644aae-ffffffe000644b84: usb_get_descriptor (STB_GLOBAL)
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
int usb_get_descriptor(struct usb_device *dev, unsigned char type, unsigned char index, void *buf, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff817a9e80)
Location: drivers/usb/core/message.c:637
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:descriptors_changed
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/message.c:usb_get_device_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
ffffffff817a9e80-ffffffff817a9f3f: usb_get_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int usb_get_descriptor(struct usb_device *dev, unsigned char type, unsigned char index, void *buf, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff8179b880)
Location: drivers/usb/core/message.c:637
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:descriptors_changed
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/message.c:usb_get_device_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
ffffffff8179b880-ffffffff8179b93f: usb_get_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int usb_get_descriptor(struct usb_device *dev, unsigned char type, unsigned char index, void *buf, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff817e6920)
Location: drivers/usb/core/message.c:637
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:descriptors_changed
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/message.c:usb_get_device_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
ffffffff817e6920-ffffffff817e69df: usb_get_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int usb_get_descriptor(struct usb_device *dev, unsigned char type, unsigned char index, void *buf, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81800ce0)
Location: drivers/usb/core/message.c:637
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:descriptors_changed
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/message.c:usb_get_device_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
ffffffff81800ce0-ffffffff81800d9f: usb_get_descriptor (STB_GLOBAL)
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
