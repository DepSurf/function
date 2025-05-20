# Function: <code>rh_queue_status</code>

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
In drivers/usb/core/hcd.c (ffffffff8160e93a)
Location: drivers/usb/core/hcd.c:807
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
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
In drivers/usb/core/hcd.c (ffffffff8166e674)
Location: drivers/usb/core/hcd.c:806
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
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
In drivers/usb/core/hcd.c (ffffffff8169c354)
Location: drivers/usb/core/hcd.c:807
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
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
In drivers/usb/core/hcd.c (ffffffff816b16ba)
Location: drivers/usb/core/hcd.c:811
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
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
In drivers/usb/core/hcd.c (ffffffff8171ccec)
Location: drivers/usb/core/hcd.c:800
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
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
In drivers/usb/core/hcd.c (ffffffff8175badb)
Location: drivers/usb/core/hcd.c:802
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
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
In drivers/usb/core/hcd.c (ffffffff8178000b)
Location: drivers/usb/core/hcd.c:802
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
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
In drivers/usb/core/hcd.c (ffffffff817be02c)
Location: drivers/usb/core/hcd.c:805
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
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
In drivers/usb/core/hcd.c (ffffffff817ee98c)
Location: drivers/usb/core/hcd.c:805
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rh_queue_status(struct usb_hcd *hcd, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff818bc840)
Location: drivers/usb/core/hcd.c:806
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
**Symbols:**

```
ffffffff818bc840-ffffffff818bc963: rh_queue_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rh_queue_status(struct usb_hcd *hcd, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff818c9550)
Location: drivers/usb/core/hcd.c:805
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
**Symbols:**

```
ffffffff818c9550-ffffffff818c9673: rh_queue_status (STB_LOCAL)
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
In drivers/usb/core/hcd.c (ffffffff818ae1d0)
Location: drivers/usb/core/hcd.c:805
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
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
In drivers/usb/core/hcd.c (ffffffff819432a0)
Location: drivers/usb/core/hcd.c:812
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
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
In drivers/usb/core/hcd.c (ffffffff81a9b6d7)
Location: drivers/usb/core/hcd.c:812
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
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
In drivers/usb/core/hcd.c (ffffffff81c2053a)
Location: drivers/usb/core/hcd.c:812
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
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
In drivers/usb/core/hcd.c (ffffffff81c874ba)
Location: drivers/usb/core/hcd.c:812
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
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
In drivers/usb/core/hcd.c (ffffffff81d3bf1a)
Location: drivers/usb/core/hcd.c:787
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
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
In drivers/usb/core/hcd.c (ffff800010a1e574)
Location: drivers/usb/core/hcd.c:805
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
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
In drivers/usb/core/hcd.c (c0af5df4)
Location: drivers/usb/core/hcd.c:805
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
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
In drivers/usb/core/hcd.c (c000000000ad8580)
Location: drivers/usb/core/hcd.c:805
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
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
In drivers/usb/core/hcd.c (ffffffe000642080)
Location: drivers/usb/core/hcd.c:805
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
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
In drivers/usb/core/hcd.c (ffffffff817a6d6c)
Location: drivers/usb/core/hcd.c:805
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
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
In drivers/usb/core/hcd.c (ffffffff817987c5)
Location: drivers/usb/core/hcd.c:805
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
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
In drivers/usb/core/hcd.c (ffffffff817e380c)
Location: drivers/usb/core/hcd.c:805
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
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
In drivers/usb/core/hcd.c (ffffffff817fdacc)
Location: drivers/usb/core/hcd.c:805
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
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
