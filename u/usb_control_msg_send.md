# Function: <code>usb_control_msg_send</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int usb_control_msg_send(struct usb_device *dev, __u8 endpoint, __u8 request, __u8 requesttype, __u16 value, __u16 index, const void *driver_data, __u16 size, int timeout, gfp_t memflags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff818ce17c)
Location: drivers/usb/core/message.c:198
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_set_isoch_delay
Direct callers:
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
```
**Symbols:**

```
ffffffff818cd2b0-ffffffff818cd377: usb_control_msg_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int usb_control_msg_send(struct usb_device *dev, __u8 endpoint, __u8 request, __u8 requesttype, __u16 value, __u16 index, const void *driver_data, __u16 size, int timeout, gfp_t memflags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff818b1822)
Location: drivers/usb/core/message.c:198
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_set_isoch_delay
Direct callers:
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
```
**Symbols:**

```
ffffffff818b08d0-ffffffff818b0994: usb_control_msg_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int usb_control_msg_send(struct usb_device *dev, __u8 endpoint, __u8 request, __u8 requesttype, __u16 value, __u16 index, const void *driver_data, __u16 size, int timeout, gfp_t memflags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81946a72)
Location: drivers/usb/core/message.c:198
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_set_isoch_delay
Direct callers:
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
```
**Symbols:**

```
ffffffff81945b30-ffffffff81945bf4: usb_control_msg_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int usb_control_msg_send(struct usb_device *dev, __u8 endpoint, __u8 request, __u8 requesttype, __u16 value, __u16 index, const void *driver_data, __u16 size, int timeout, gfp_t memflags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81a9f55d)
Location: drivers/usb/core/message.c:198
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_set_isoch_delay
Direct callers:
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
```
**Symbols:**

```
ffffffff81a9e280-ffffffff81a9e35d: usb_control_msg_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int usb_control_msg_send(struct usb_device *dev, __u8 endpoint, __u8 request, __u8 requesttype, __u16 value, __u16 index, const void *driver_data, __u16 size, int timeout, gfp_t memflags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81c249ed)
Location: drivers/usb/core/message.c:198
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_set_isoch_delay
Direct callers:
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
```
**Symbols:**

```
ffffffff81c233b0-ffffffff81c2348d: usb_control_msg_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int usb_control_msg_send(struct usb_device *dev, __u8 endpoint, __u8 request, __u8 requesttype, __u16 value, __u16 index, const void *driver_data, __u16 size, int timeout, gfp_t memflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81c8a330)
Location: drivers/usb/core/message.c:198
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_set_isoch_delay
```
**Symbols:**

```
ffffffff81c8a330-ffffffff81c8a40d: usb_control_msg_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int usb_control_msg_send(struct usb_device *dev, __u8 endpoint, __u8 request, __u8 requesttype, __u16 value, __u16 index, const void *driver_data, __u16 size, int timeout, gfp_t memflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81d3ed50)
Location: drivers/usb/core/message.c:199
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_set_isoch_delay
```
**Symbols:**

```
ffffffff81d3ed50-ffffffff81d3ee2d: usb_control_msg_send (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
