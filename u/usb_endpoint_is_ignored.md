# Function: <code>usb_endpoint_is_ignored</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
bool usb_endpoint_is_ignored(struct usb_device *udev, struct usb_host_interface *intf, struct usb_endpoint_descriptor *epd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/quirks.c (ffffffff818daa40)
Location: drivers/usb/core/quirks.c:549
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
```
**Symbols:**

```
ffffffff818daa40-ffffffff818daaae: usb_endpoint_is_ignored (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool usb_endpoint_is_ignored(struct usb_device *udev, struct usb_host_interface *intf, struct usb_endpoint_descriptor *epd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/quirks.c (ffffffff818bdea0)
Location: drivers/usb/core/quirks.c:548
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
```
**Symbols:**

```
ffffffff818bdea0-ffffffff818bdf0e: usb_endpoint_is_ignored (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool usb_endpoint_is_ignored(struct usb_device *udev, struct usb_host_interface *intf, struct usb_endpoint_descriptor *epd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/quirks.c (ffffffff81954200)
Location: drivers/usb/core/quirks.c:554
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
```
**Symbols:**

```
ffffffff81954200-ffffffff8195426e: usb_endpoint_is_ignored (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool usb_endpoint_is_ignored(struct usb_device *udev, struct usb_host_interface *intf, struct usb_endpoint_descriptor *epd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/quirks.c (ffffffff81aadb00)
Location: drivers/usb/core/quirks.c:563
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
```
**Symbols:**

```
ffffffff81aadb00-ffffffff81aadb82: usb_endpoint_is_ignored (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool usb_endpoint_is_ignored(struct usb_device *udev, struct usb_host_interface *intf, struct usb_endpoint_descriptor *epd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/quirks.c (ffffffff81c354d0)
Location: drivers/usb/core/quirks.c:582
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
```
**Symbols:**

```
ffffffff81c354d0-ffffffff81c35552: usb_endpoint_is_ignored (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool usb_endpoint_is_ignored(struct usb_device *udev, struct usb_host_interface *intf, struct usb_endpoint_descriptor *epd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/quirks.c (ffffffff81c9c7f0)
Location: drivers/usb/core/quirks.c:586
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
```
**Symbols:**

```
ffffffff81c9c7f0-ffffffff81c9c872: usb_endpoint_is_ignored (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool usb_endpoint_is_ignored(struct usb_device *udev, struct usb_host_interface *intf, struct usb_endpoint_descriptor *epd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/quirks.c (ffffffff81d513a0)
Location: drivers/usb/core/quirks.c:593
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
```
**Symbols:**

```
ffffffff81d513a0-ffffffff81d51422: usb_endpoint_is_ignored (STB_GLOBAL)
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
