# Function: <code>descriptors_changed</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int descriptors_changed(struct usb_device *udev, struct usb_device_descriptor *old_device_descriptor, struct usb_host_bos *old_bos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81604640)
Location: drivers/usb/core/hub.c:5280
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
```
**Symbols:**

```
ffffffff81604640-ffffffff81604904: descriptors_changed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int descriptors_changed(struct usb_device *udev, struct usb_device_descriptor *old_device_descriptor, struct usb_host_bos *old_bos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81664340)
Location: drivers/usb/core/hub.c:5298
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
```
**Symbols:**

```
ffffffff81664340-ffffffff81664614: descriptors_changed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8169457b)
Location: drivers/usb/core/hub.c:5275
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int descriptors_changed(struct usb_device *udev, struct usb_device_descriptor *old_device_descriptor, struct usb_host_bos *old_bos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816a75e0)
Location: drivers/usb/core/hub.c:5296
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
```
**Symbols:**

```
ffffffff816a75e0-ffffffff816a78aa: descriptors_changed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int descriptors_changed(struct usb_device *udev, struct usb_device_descriptor *old_device_descriptor, struct usb_host_bos *old_bos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817129c0)
Location: drivers/usb/core/hub.c:5334
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
```
**Symbols:**

```
ffffffff817129c0-ffffffff81712c8a: descriptors_changed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int descriptors_changed(struct usb_device *udev, struct usb_device_descriptor *old_device_descriptor, struct usb_host_bos *old_bos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81751670)
Location: drivers/usb/core/hub.c:5406
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
```
**Symbols:**

```
ffffffff81751670-ffffffff81751935: descriptors_changed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int descriptors_changed(struct usb_device *udev, struct usb_device_descriptor *old_device_descriptor, struct usb_host_bos *old_bos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81775ad0)
Location: drivers/usb/core/hub.c:5506
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
```
**Symbols:**

```
ffffffff81775ad0-ffffffff81775d95: descriptors_changed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int descriptors_changed(struct usb_device *udev, struct usb_device_descriptor *old_device_descriptor, struct usb_host_bos *old_bos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817b4990)
Location: drivers/usb/core/hub.c:5553
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
```
**Symbols:**

```
ffffffff817b4990-ffffffff817b4c58: descriptors_changed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int descriptors_changed(struct usb_device *udev, struct usb_device_descriptor *old_device_descriptor, struct usb_host_bos *old_bos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817e50c0)
Location: drivers/usb/core/hub.c:5602
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
```
**Symbols:**

```
ffffffff817e50c0-ffffffff817e5388: descriptors_changed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int descriptors_changed(struct usb_device *udev, struct usb_device_descriptor *old_device_descriptor, struct usb_host_bos *old_bos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818b2ff0)
Location: drivers/usb/core/hub.c:4996
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect_change
```
**Symbols:**

```
ffffffff818b2ff0-ffffffff818b3280: descriptors_changed.part.0 (STB_LOCAL)
ffffffff818b3280-ffffffff818b32bf: descriptors_changed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int descriptors_changed(struct usb_device *udev, struct usb_device_descriptor *old_device_descriptor, struct usb_host_bos *old_bos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818c1960)
Location: drivers/usb/core/hub.c:5011
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect_change
```
**Symbols:**

```
ffffffff818c1960-ffffffff818c1bf0: descriptors_changed.part.0 (STB_LOCAL)
ffffffff818c1bf0-ffffffff818c1c2f: descriptors_changed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int descriptors_changed(struct usb_device *udev, struct usb_device_descriptor *old_device_descriptor, struct usb_host_bos *old_bos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818a4a70)
Location: drivers/usb/core/hub.c:5135
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect_change
```
**Symbols:**

```
ffffffff818a4a70-ffffffff818a4cf5: descriptors_changed.part.0 (STB_LOCAL)
ffffffff818a4d00-ffffffff818a4d42: descriptors_changed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int descriptors_changed(struct usb_device *udev, struct usb_device_descriptor *old_device_descriptor, struct usb_host_bos *old_bos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81939720)
Location: drivers/usb/core/hub.c:5136
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect_change
```
**Symbols:**

```
ffffffff81939720-ffffffff8193999c: descriptors_changed.part.0 (STB_LOCAL)
ffffffff819399a0-ffffffff819399e2: descriptors_changed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int descriptors_changed(struct usb_device *udev, struct usb_device_descriptor *old_device_descriptor, struct usb_host_bos *old_bos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81a91070)
Location: drivers/usb/core/hub.c:5143
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect_change
```
**Symbols:**

```
ffffffff81a91070-ffffffff81a91313: descriptors_changed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int descriptors_changed(struct usb_device *udev, struct usb_device_descriptor *old_device_descriptor, struct usb_host_bos *old_bos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c12e70)
Location: drivers/usb/core/hub.c:5145
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect_change
```
**Symbols:**

```
ffffffff81c12e70-ffffffff81c13113: descriptors_changed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int descriptors_changed(struct usb_device *udev, struct usb_device_descriptor *new_device_descriptor, struct usb_host_bos *old_bos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c79e10)
Location: drivers/usb/core/hub.c:5220
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect_change
```
**Symbols:**

```
ffffffff81c79e10-ffffffff81c7a0de: descriptors_changed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int descriptors_changed(struct usb_device *udev, struct usb_device_descriptor *new_device_descriptor, struct usb_host_bos *old_bos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81d2e810)
Location: drivers/usb/core/hub.c:5222
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect_change
```
**Symbols:**

```
ffffffff81d2e810-ffffffff81d2eade: descriptors_changed (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int descriptors_changed(struct usb_device *udev, struct usb_device_descriptor *old_device_descriptor, struct usb_host_bos *old_bos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffff800010a12ba8)
Location: drivers/usb/core/hub.c:5602
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
```
**Symbols:**

```
ffff800010a12ba8-ffff800010a12e68: descriptors_changed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int descriptors_changed(struct usb_device *udev, struct usb_device_descriptor *old_device_descriptor, struct usb_host_bos *old_bos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c0aebf30)
Location: drivers/usb/core/hub.c:5602
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
```
**Symbols:**

```
c0aebf30-c0aec1d0: descriptors_changed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int descriptors_changed(struct usb_device *udev, struct usb_device_descriptor *old_device_descriptor, struct usb_host_bos *old_bos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c000000000acba20)
Location: drivers/usb/core/hub.c:5602
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
```
**Symbols:**

```
c000000000acba20-c000000000acbe08: descriptors_changed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffe00063a80a)
Location: drivers/usb/core/hub.c:5602
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
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
int descriptors_changed(struct usb_device *udev, struct usb_device_descriptor *old_device_descriptor, struct usb_host_bos *old_bos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8179d4a0)
Location: drivers/usb/core/hub.c:5602
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
```
**Symbols:**

```
ffffffff8179d4a0-ffffffff8179d768: descriptors_changed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int descriptors_changed(struct usb_device *udev, struct usb_device_descriptor *old_device_descriptor, struct usb_host_bos *old_bos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8178f120)
Location: drivers/usb/core/hub.c:5602
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
```
**Symbols:**

```
ffffffff8178f120-ffffffff8178f3e8: descriptors_changed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int descriptors_changed(struct usb_device *udev, struct usb_device_descriptor *old_device_descriptor, struct usb_host_bos *old_bos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817d9f40)
Location: drivers/usb/core/hub.c:5602
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
```
**Symbols:**

```
ffffffff817d9f40-ffffffff817da208: descriptors_changed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int descriptors_changed(struct usb_device *udev, struct usb_device_descriptor *old_device_descriptor, struct usb_host_bos *old_bos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817f41d0)
Location: drivers/usb/core/hub.c:5602
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
```
**Symbols:**

```
ffffffff817f41d0-ffffffff817f4498: descriptors_changed (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct usb_device_descriptor *new_device_descriptor</code>
</li>
<li>
<b>Param removed. </b>
<code>struct usb_device_descriptor *old_device_descriptor</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
