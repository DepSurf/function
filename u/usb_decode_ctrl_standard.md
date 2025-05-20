# Function: <code>usb_decode_ctrl_standard</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void usb_decode_ctrl_standard(char *str, size_t size, __u8 bRequestType, __u8 bRequest, __u16 wValue, __u16 wIndex, __u16 wLength);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/common/debug.c (ffffffff81c10a60)
Location: drivers/usb/common/debug.c:230
Inline: False
Direct callers:
  - drivers/usb/common/debug.c:usb_decode_ctrl
```
**Symbols:**

```
ffffffff81c10a60-ffffffff81c10f7c: usb_decode_ctrl_standard (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void usb_decode_ctrl_standard(char *str, size_t size, __u8 bRequestType, __u8 bRequest, __u16 wValue, __u16 wIndex, __u16 wLength);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/common/debug.c (ffffffff81c776f0)
Location: drivers/usb/common/debug.c:230
Inline: False
Direct callers:
  - drivers/usb/common/debug.c:usb_decode_ctrl
```
**Symbols:**

```
ffffffff81c776f0-ffffffff81c77bdf: usb_decode_ctrl_standard (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void usb_decode_ctrl_standard(char *str, size_t size, __u8 bRequestType, __u8 bRequest, __u16 wValue, __u16 wIndex, __u16 wLength);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/common/debug.c (ffffffff81d2c0f0)
Location: drivers/usb/common/debug.c:230
Inline: False
Direct callers:
  - drivers/usb/common/debug.c:usb_decode_ctrl
```
**Symbols:**

```
ffffffff81d2c0f0-ffffffff81d2c5df: usb_decode_ctrl_standard (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
