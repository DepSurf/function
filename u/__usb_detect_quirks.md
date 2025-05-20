# Function: <code>__usb_detect_quirks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u32 __usb_detect_quirks(struct usb_device *udev, const struct usb_device_id *id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/quirks.c (ffffffff8161dd70)
Location: drivers/usb/core/quirks.c:275
Inline: False
Direct callers:
  - drivers/usb/core/quirks.c:usb_detect_quirks
  - drivers/usb/core/quirks.c:usb_detect_quirks
  - drivers/usb/core/quirks.c:usb_detect_interface_quirks
```
**Symbols:**

```
ffffffff8161dd70-ffffffff8161de79: __usb_detect_quirks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u32 __usb_detect_quirks(struct usb_device *udev, const struct usb_device_id *id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/quirks.c (ffffffff8167e5c0)
Location: drivers/usb/core/quirks.c:281
Inline: False
Direct callers:
  - drivers/usb/core/quirks.c:usb_detect_interface_quirks
  - drivers/usb/core/quirks.c:usb_detect_quirks
  - drivers/usb/core/quirks.c:usb_detect_quirks
```
**Symbols:**

```
ffffffff8167e5c0-ffffffff8167e6c9: __usb_detect_quirks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u32 __usb_detect_quirks(struct usb_device *udev, const struct usb_device_id *id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/quirks.c (ffffffff816ac340)
Location: drivers/usb/core/quirks.c:293
Inline: False
Direct callers:
  - drivers/usb/core/quirks.c:usb_detect_interface_quirks
  - drivers/usb/core/quirks.c:usb_detect_quirks
  - drivers/usb/core/quirks.c:usb_detect_quirks
```
**Symbols:**

```
ffffffff816ac340-ffffffff816ac449: __usb_detect_quirks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u32 __usb_detect_quirks(struct usb_device *udev, const struct usb_device_id *id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/quirks.c (ffffffff816c15b0)
Location: drivers/usb/core/quirks.c:305
Inline: False
Direct callers:
  - drivers/usb/core/quirks.c:usb_detect_interface_quirks
  - drivers/usb/core/quirks.c:usb_detect_quirks
  - drivers/usb/core/quirks.c:usb_detect_quirks
```
**Symbols:**

```
ffffffff816c15b0-ffffffff816c16a8: __usb_detect_quirks (STB_LOCAL)
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
</ul>
