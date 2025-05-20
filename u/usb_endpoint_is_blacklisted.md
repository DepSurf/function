# Function: <code>usb_endpoint_is_blacklisted</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool usb_endpoint_is_blacklisted(struct usb_device *udev, struct usb_host_interface *intf, struct usb_endpoint_descriptor *epd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/quirks.c (ffffffff817fff20)
Location: drivers/usb/core/quirks.c:502
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
```
**Symbols:**

```
ffffffff817fff20-ffffffff817fff80: usb_endpoint_is_blacklisted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool usb_endpoint_is_blacklisted(struct usb_device *udev, struct usb_host_interface *intf, struct usb_endpoint_descriptor *epd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/quirks.c (ffffffff818d05e0)
Location: drivers/usb/core/quirks.c:526
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
```
**Symbols:**

```
ffffffff818d05e0-ffffffff818d064e: usb_endpoint_is_blacklisted (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
bool usb_endpoint_is_blacklisted(struct usb_device *udev, struct usb_host_interface *intf, struct usb_endpoint_descriptor *epd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/quirks.c (ffff800010a33d28)
Location: drivers/usb/core/quirks.c:502
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
```
**Symbols:**

```
ffff800010a33d28-ffff800010a33db0: usb_endpoint_is_blacklisted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool usb_endpoint_is_blacklisted(struct usb_device *udev, struct usb_host_interface *intf, struct usb_endpoint_descriptor *epd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/quirks.c (c0b075a8)
Location: drivers/usb/core/quirks.c:502
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
```
**Symbols:**

```
c0b075a8-c0b07614: usb_endpoint_is_blacklisted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool usb_endpoint_is_blacklisted(struct usb_device *udev, struct usb_host_interface *intf, struct usb_endpoint_descriptor *epd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/quirks.c (c000000000af14f0)
Location: drivers/usb/core/quirks.c:502
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
```
**Symbols:**

```
c000000000af14f0-c000000000af15b4: usb_endpoint_is_blacklisted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool usb_endpoint_is_blacklisted(struct usb_device *udev, struct usb_host_interface *intf, struct usb_endpoint_descriptor *epd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/quirks.c (ffffffe0006519d2)
Location: drivers/usb/core/quirks.c:502
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
```
**Symbols:**

```
ffffffe0006519d2-ffffffe000651a46: usb_endpoint_is_blacklisted (STB_GLOBAL)
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
bool usb_endpoint_is_blacklisted(struct usb_device *udev, struct usb_host_interface *intf, struct usb_endpoint_descriptor *epd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/quirks.c (ffffffff817b8300)
Location: drivers/usb/core/quirks.c:502
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
```
**Symbols:**

```
ffffffff817b8300-ffffffff817b8360: usb_endpoint_is_blacklisted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool usb_endpoint_is_blacklisted(struct usb_device *udev, struct usb_host_interface *intf, struct usb_endpoint_descriptor *epd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/quirks.c (ffffffff817a9d30)
Location: drivers/usb/core/quirks.c:502
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
```
**Symbols:**

```
ffffffff817a9d30-ffffffff817a9d90: usb_endpoint_is_blacklisted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool usb_endpoint_is_blacklisted(struct usb_device *udev, struct usb_host_interface *intf, struct usb_endpoint_descriptor *epd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/quirks.c (ffffffff817f4da0)
Location: drivers/usb/core/quirks.c:502
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
```
**Symbols:**

```
ffffffff817f4da0-ffffffff817f4e00: usb_endpoint_is_blacklisted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool usb_endpoint_is_blacklisted(struct usb_device *udev, struct usb_host_interface *intf, struct usb_endpoint_descriptor *epd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/quirks.c (ffffffff8180efe0)
Location: drivers/usb/core/quirks.c:502
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
```
**Symbols:**

```
ffffffff8180efe0-ffffffff8180f040: usb_endpoint_is_blacklisted (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
