# Function: <code>usb_hcd_request_irqs</code>

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
In drivers/usb/core/hcd.c (ffffffff8160e3f0)
Location: drivers/usb/core/hcd.c:2650
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffffffff8166dfab)
Location: drivers/usb/core/hcd.c:2654
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffffffff8169bc8b)
Location: drivers/usb/core/hcd.c:2653
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffffffff816b0f87)
Location: drivers/usb/core/hcd.c:2679
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffffffff8171c5ab)
Location: drivers/usb/core/hcd.c:2666
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffffffff8175b1ba)
Location: drivers/usb/core/hcd.c:2682
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffffffff8177f6d6)
Location: drivers/usb/core/hcd.c:2666
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffffffff817bf4bf)
Location: drivers/usb/core/hcd.c:2577
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffffffff817efe27)
Location: drivers/usb/core/hcd.c:2576
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int usb_hcd_request_irqs(struct usb_hcd *hcd, unsigned int irqnum, long unsigned int irqflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff818bed61)
Location: drivers/usb/core/hcd.c:2573
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff818bed61-ffffffff818bee6c: usb_hcd_request_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int usb_hcd_request_irqs(struct usb_hcd *hcd, unsigned int irqnum, long unsigned int irqflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81c1c38e)
Location: drivers/usb/core/hcd.c:2585
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff81c1c38e-ffffffff81c1c499: usb_hcd_request_irqs (STB_LOCAL)
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
In drivers/usb/core/hcd.c (ffffffff81c0eb75)
Location: drivers/usb/core/hcd.c:2585
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffffffff81d15d0e)
Location: drivers/usb/core/hcd.c:2736
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffffffff81ee0811)
Location: drivers/usb/core/hcd.c:2739
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffffffff81c1fb2f)
Location: drivers/usb/core/hcd.c:2733
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffffffff81c86ad8)
Location: drivers/usb/core/hcd.c:2737
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffffffff81d3b546)
Location: drivers/usb/core/hcd.c:2712
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffff800010a1ddd8)
Location: drivers/usb/core/hcd.c:2576
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (c0af5318)
Location: drivers/usb/core/hcd.c:2576
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (c000000000ad6c68)
Location: drivers/usb/core/hcd.c:2576
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffffffe000640f58)
Location: drivers/usb/core/hcd.c:2576
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffffffff817a8207)
Location: drivers/usb/core/hcd.c:2576
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffffffff81799c20)
Location: drivers/usb/core/hcd.c:2576
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffffffff817e4ca7)
Location: drivers/usb/core/hcd.c:2576
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffffffff817fef13)
Location: drivers/usb/core/hcd.c:2576
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
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
