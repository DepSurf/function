# Function: <code>usb_generic_driver_probe</code>

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
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int usb_generic_driver_probe(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/generic.c (0)
Location: drivers/usb/core/generic.c:230
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_probe_device
```
**Symbols:**

```
ffffffff818d0120-ffffffff818d0156: usb_generic_driver_probe.cold (STB_LOCAL)
ffffffff818d0060-ffffffff818d00d0: usb_generic_driver_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int usb_generic_driver_probe(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/generic.c (0)
Location: drivers/usb/core/generic.c:226
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_probe_device
```
**Symbols:**

```
ffffffff81c1ea25-ffffffff81c1ea5b: usb_generic_driver_probe.cold (STB_LOCAL)
ffffffff818da570-ffffffff818da5e0: usb_generic_driver_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int usb_generic_driver_probe(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/generic.c (0)
Location: drivers/usb/core/generic.c:226
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_probe_device
```
**Symbols:**

```
ffffffff81c108b6-ffffffff81c108ec: usb_generic_driver_probe.cold (STB_LOCAL)
ffffffff818bd9d0-ffffffff818bda40: usb_generic_driver_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int usb_generic_driver_probe(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/generic.c (0)
Location: drivers/usb/core/generic.c:226
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_probe_device
```
**Symbols:**

```
ffffffff81d17bd3-ffffffff81d17c09: usb_generic_driver_probe.cold (STB_LOCAL)
ffffffff81953d10-ffffffff81953d80: usb_generic_driver_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int usb_generic_driver_probe(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/generic.c (0)
Location: drivers/usb/core/generic.c:226
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_probe_device
```
**Symbols:**

```
ffffffff81ee2a6e-ffffffff81ee2aa3: usb_generic_driver_probe.cold (STB_LOCAL)
ffffffff81aad5d0-ffffffff81aad655: usb_generic_driver_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int usb_generic_driver_probe(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/generic.c (ffffffff81c34f60)
Location: drivers/usb/core/generic.c:226
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_probe_device
```
**Symbols:**

```
ffffffff81c34f60-ffffffff81c35000: usb_generic_driver_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int usb_generic_driver_probe(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/generic.c (ffffffff81c9c280)
Location: drivers/usb/core/generic.c:226
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_probe_device
```
**Symbols:**

```
ffffffff81c9c280-ffffffff81c9c320: usb_generic_driver_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int usb_generic_driver_probe(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/generic.c (ffffffff81d50c50)
Location: drivers/usb/core/generic.c:242
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_probe_device
```
**Symbols:**

```
ffffffff81d50c50-ffffffff81d50ccf: usb_generic_driver_probe (STB_GLOBAL)
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
