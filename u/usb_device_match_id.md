# Function: <code>usb_device_match_id</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
const struct usb_device_id *usb_device_match_id(struct usb_device *udev, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff818c5193)
Location: drivers/usb/core/driver.c:828
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_device_match
  - drivers/usb/core/driver.c:usb_device_match
```
**Symbols:**

```
ffffffff818c5800-ffffffff818c5859: usb_device_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
const struct usb_device_id *usb_device_match_id(struct usb_device *udev, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff818d1520)
Location: drivers/usb/core/driver.c:828
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_applicable
  - drivers/usb/core/driver.c:usb_driver_applicable
  - drivers/usb/core/driver.c:usb_driver_applicable
  - drivers/usb/core/driver.c:usb_driver_applicable
```
**Symbols:**

```
ffffffff818d1520-ffffffff818d1579: usb_device_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
const struct usb_device_id *usb_device_match_id(struct usb_device *udev, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff818b4b40)
Location: drivers/usb/core/driver.c:824
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_applicable
  - drivers/usb/core/driver.c:usb_driver_applicable
  - drivers/usb/core/driver.c:usb_driver_applicable
  - drivers/usb/core/driver.c:usb_driver_applicable
```
**Symbols:**

```
ffffffff818b4b40-ffffffff818b4b99: usb_device_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
const struct usb_device_id *usb_device_match_id(struct usb_device *udev, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff8194a070)
Location: drivers/usb/core/driver.c:824
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_applicable
  - drivers/usb/core/driver.c:usb_driver_applicable
  - drivers/usb/core/driver.c:usb_driver_applicable
  - drivers/usb/core/driver.c:usb_driver_applicable
```
**Symbols:**

```
ffffffff8194a070-ffffffff8194a0c9: usb_device_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
const struct usb_device_id *usb_device_match_id(struct usb_device *udev, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81aa2d71)
Location: drivers/usb/core/driver.c:824
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_applicable
  - drivers/usb/core/driver.c:usb_driver_applicable
```
**Symbols:**

```
ffffffff81aa2760-ffffffff81aa27c9: usb_device_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
const struct usb_device_id *usb_device_match_id(struct usb_device *udev, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81c28811)
Location: drivers/usb/core/driver.c:824
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_applicable
  - drivers/usb/core/driver.c:usb_driver_applicable
```
**Symbols:**

```
ffffffff81c28170-ffffffff81c281d9: usb_device_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
const struct usb_device_id *usb_device_match_id(struct usb_device *udev, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81c8f7e1)
Location: drivers/usb/core/driver.c:824
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_applicable
  - drivers/usb/core/driver.c:usb_driver_applicable
```
**Symbols:**

```
ffffffff81c8f120-ffffffff81c8f189: usb_device_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
const struct usb_device_id *usb_device_match_id(struct usb_device *udev, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81d44361)
Location: drivers/usb/core/driver.c:827
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_applicable
  - drivers/usb/core/driver.c:usb_driver_applicable
```
**Symbols:**

```
ffffffff81d43ca0-ffffffff81d43d09: usb_device_match_id (STB_GLOBAL)
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
