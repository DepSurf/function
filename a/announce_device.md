# Function: <code>announce_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81608610)
Location: drivers/usb/core/hub.c:2234
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816682d8)
Location: drivers/usb/core/hub.c:2231
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
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
In drivers/usb/core/hub.c (ffffffff81695ff8)
Location: drivers/usb/core/hub.c:2150
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816ab407)
Location: drivers/usb/core/hub.c:2178
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81716867)
Location: drivers/usb/core/hub.c:2178
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817556ab)
Location: drivers/usb/core/hub.c:2202
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81779bdb)
Location: drivers/usb/core/hub.c:2213
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817b7a88)
Location: drivers/usb/core/hub.c:2253
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817e8258)
Location: drivers/usb/core/hub.c:2264
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void announce_device(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818b9cf7)
Location: drivers/usb/core/hub.c:2271
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_new_device
```
**Symbols:**

```
ffffffff818b9cf7-ffffffff818b9dca: announce_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void announce_device(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c1a81d)
Location: drivers/usb/core/hub.c:2272
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_new_device
```
**Symbols:**

```
ffffffff81c1a81d-ffffffff81c1a8f0: announce_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818a93b1)
Location: drivers/usb/core/hub.c:2279
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8193e2be)
Location: drivers/usb/core/hub.c:2282
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81a962d5)
Location: drivers/usb/core/hub.c:2282
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c18a02)
Location: drivers/usb/core/hub.c:2292
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c7f9c3)
Location: drivers/usb/core/hub.c:2307
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81d343ba)
Location: drivers/usb/core/hub.c:2323
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffff800010a17540)
Location: drivers/usb/core/hub.c:2264
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c0aef5c8)
Location: drivers/usb/core/hub.c:2264
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c000000000ad01ec)
Location: drivers/usb/core/hub.c:2264
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
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
In drivers/usb/core/hub.c (ffffffe00063c376)
Location: drivers/usb/core/hub.c:2264
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817a0638)
Location: drivers/usb/core/hub.c:2264
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:2283
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817dd0d8)
Location: drivers/usb/core/hub.c:2264
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817f73a8)
Location: drivers/usb/core/hub.c:2264
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
