# Function: <code>usb_generic_driver_disconnect</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
void usb_generic_driver_disconnect(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/generic.c (ffffffff818cfc60)
Location: drivers/usb/core/generic.c:257
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_unbind_device
```
**Symbols:**

```
ffffffff818cfc60-ffffffff818cfc91: usb_generic_driver_disconnect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void usb_generic_driver_disconnect(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/generic.c (ffffffff818da1a0)
Location: drivers/usb/core/generic.c:253
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_unbind_device
```
**Symbols:**

```
ffffffff818da1a0-ffffffff818da1d1: usb_generic_driver_disconnect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void usb_generic_driver_disconnect(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/generic.c (ffffffff818bd600)
Location: drivers/usb/core/generic.c:253
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_unbind_device
```
**Symbols:**

```
ffffffff818bd600-ffffffff818bd631: usb_generic_driver_disconnect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void usb_generic_driver_disconnect(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/generic.c (ffffffff81953940)
Location: drivers/usb/core/generic.c:253
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_unbind_device
```
**Symbols:**

```
ffffffff81953940-ffffffff81953971: usb_generic_driver_disconnect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void usb_generic_driver_disconnect(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/generic.c (ffffffff81aad540)
Location: drivers/usb/core/generic.c:253
Inline: True
Direct callers:
  - drivers/usb/core/driver.c:usb_unbind_device
```
**Symbols:**

```
ffffffff81aad540-ffffffff81aad579: usb_generic_driver_disconnect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void usb_generic_driver_disconnect(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/generic.c (ffffffff81c34eb0)
Location: drivers/usb/core/generic.c:253
Inline: True
Direct callers:
  - drivers/usb/core/driver.c:usb_unbind_device
```
**Symbols:**

```
ffffffff81c34eb0-ffffffff81c34ee9: usb_generic_driver_disconnect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void usb_generic_driver_disconnect(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/generic.c (ffffffff81c9c1d0)
Location: drivers/usb/core/generic.c:253
Inline: True
Direct callers:
  - drivers/usb/core/driver.c:usb_unbind_device
```
**Symbols:**

```
ffffffff81c9c1d0-ffffffff81c9c209: usb_generic_driver_disconnect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void usb_generic_driver_disconnect(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/generic.c (ffffffff81d50e20)
Location: drivers/usb/core/generic.c:269
Inline: True
Direct callers:
  - drivers/usb/core/driver.c:usb_unbind_device
```
**Symbols:**

```
ffffffff81d50e20-ffffffff81d50e59: usb_generic_driver_disconnect (STB_GLOBAL)
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
