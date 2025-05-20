# Function: <code>usb_decode_interval</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int usb_decode_interval(const struct usb_endpoint_descriptor *epd, enum usb_device_speed speed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/common/common.c (ffffffff818a2b20)
Location: drivers/usb/common/common.c:211
Inline: False
Direct callers:
  - drivers/usb/core/endpoint.c:interval_show
  - drivers/usb/core/devices.c:usb_dump_config
```
**Symbols:**

```
ffffffff818a2b20-ffffffff818a2b95: usb_decode_interval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
unsigned int usb_decode_interval(const struct usb_endpoint_descriptor *epd, enum usb_device_speed speed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/common/common.c (0)
Location: drivers/usb/common/common.c:231
Inline: False
Direct callers:
  - drivers/usb/core/endpoint.c:interval_show
  - drivers/usb/core/devices.c:usb_dump_config
```
**Symbols:**

```
ffffffff81d1359f-ffffffff81d135df: usb_decode_interval.cold (STB_LOCAL)
ffffffff81937810-ffffffff819378ae: usb_decode_interval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
unsigned int usb_decode_interval(const struct usb_endpoint_descriptor *epd, enum usb_device_speed speed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/common/common.c (0)
Location: drivers/usb/common/common.c:231
Inline: False
Direct callers:
  - drivers/usb/core/endpoint.c:interval_show
  - drivers/usb/core/devices.c:usb_dump_config
```
**Symbols:**

```
ffffffff81ede358-ffffffff81ede398: usb_decode_interval.cold (STB_LOCAL)
ffffffff81a8eeb0-ffffffff81a8ef82: usb_decode_interval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
unsigned int usb_decode_interval(const struct usb_endpoint_descriptor *epd, enum usb_device_speed speed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/common/common.c (0)
Location: drivers/usb/common/common.c:231
Inline: False
Direct callers:
  - drivers/usb/core/endpoint.c:interval_show
  - drivers/usb/core/devices.c:usb_dump_config
```
**Symbols:**

```
ffffffff8209e652-ffffffff8209e692: usb_decode_interval.cold (STB_LOCAL)
ffffffff81c10880-ffffffff81c10952: usb_decode_interval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
unsigned int usb_decode_interval(const struct usb_endpoint_descriptor *epd, enum usb_device_speed speed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/common/common.c (0)
Location: drivers/usb/common/common.c:231
Inline: False
Direct callers:
  - drivers/usb/core/endpoint.c:interval_show
  - drivers/usb/core/devices.c:usb_dump_config
```
**Symbols:**

```
ffffffff8211fbd9-ffffffff8211fc19: usb_decode_interval.cold (STB_LOCAL)
ffffffff81c77510-ffffffff81c775e4: usb_decode_interval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
unsigned int usb_decode_interval(const struct usb_endpoint_descriptor *epd, enum usb_device_speed speed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/common/common.c (0)
Location: drivers/usb/common/common.c:232
Inline: False
Direct callers:
  - drivers/usb/core/endpoint.c:interval_show
  - drivers/usb/core/devices.c:usb_dump_config
```
**Symbols:**

```
ffffffff822013af-ffffffff822013ef: usb_decode_interval.cold (STB_LOCAL)
ffffffff81d2bf10-ffffffff81d2bfe4: usb_decode_interval (STB_GLOBAL)
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
