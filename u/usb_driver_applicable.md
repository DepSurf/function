# Function: <code>usb_driver_applicable</code>

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
bool usb_driver_applicable(struct usb_device *udev, struct usb_device_driver *udrv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff818d1580)
Location: drivers/usb/core/driver.c:842
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_device_match
```
**Symbols:**

```
ffffffff818d1580-ffffffff818d1629: usb_driver_applicable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool usb_driver_applicable(struct usb_device *udev, struct usb_device_driver *udrv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff818b4ba0)
Location: drivers/usb/core/driver.c:838
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_device_match
```
**Symbols:**

```
ffffffff818b4ba0-ffffffff818b4c4c: usb_driver_applicable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool usb_driver_applicable(struct usb_device *udev, struct usb_device_driver *udrv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff8194a0d0)
Location: drivers/usb/core/driver.c:838
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_device_match
```
**Symbols:**

```
ffffffff8194a0d0-ffffffff8194a17c: usb_driver_applicable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool usb_driver_applicable(struct usb_device *udev, struct usb_device_driver *udrv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81aa2d00)
Location: drivers/usb/core/driver.c:839
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_device_match
```
**Symbols:**

```
ffffffff81aa2d00-ffffffff81aa2dbd: usb_driver_applicable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool usb_driver_applicable(struct usb_device *udev, struct usb_device_driver *udrv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81c287a0)
Location: drivers/usb/core/driver.c:839
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_device_match
```
**Symbols:**

```
ffffffff81c287a0-ffffffff81c2885d: usb_driver_applicable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool usb_driver_applicable(struct usb_device *udev, struct usb_device_driver *udrv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81c8f770)
Location: drivers/usb/core/driver.c:839
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_device_match
```
**Symbols:**

```
ffffffff81c8f770-ffffffff81c8f82d: usb_driver_applicable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool usb_driver_applicable(struct usb_device *udev, struct usb_device_driver *udrv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81d442f0)
Location: drivers/usb/core/driver.c:842
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_device_match
```
**Symbols:**

```
ffffffff81d442f0-ffffffff81d443ad: usb_driver_applicable (STB_GLOBAL)
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
