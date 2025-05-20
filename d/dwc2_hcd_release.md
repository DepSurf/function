# Function: <code>dwc2_hcd_release</code>

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
In drivers/usb/dwc2/hcd.c (ffffffff8162a5e9)
Location: drivers/usb/dwc2/hcd.c:2976
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
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
In drivers/usb/dwc2/hcd.c (ffffffff8168aa0b)
Location: drivers/usb/dwc2/hcd.c:4956
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
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
In drivers/usb/dwc2/hcd.c (ffffffff816b8b2e)
Location: drivers/usb/dwc2/hcd.c:4956
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
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
In drivers/usb/dwc2/hcd.c (ffffffff816cce6e)
Location: drivers/usb/dwc2/hcd.c:5038
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
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
In drivers/usb/dwc2/hcd.c (ffffffff81739461)
Location: drivers/usb/dwc2/hcd.c:5053
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
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
In drivers/usb/dwc2/hcd.c (ffffffff8177951d)
Location: drivers/usb/dwc2/hcd.c:5119
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dwc2_hcd_release(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff8179e910)
Location: drivers/usb/dwc2/hcd.c:5138
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
**Symbols:**

```
ffffffff8179e910-ffffffff8179eb96: dwc2_hcd_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dwc2_hcd_release(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff817dd510)
Location: drivers/usb/dwc2/hcd.c:4995
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
**Symbols:**

```
ffffffff817dd510-ffffffff817dd799: dwc2_hcd_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dwc2_hcd_release(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff8180e440)
Location: drivers/usb/dwc2/hcd.c:4995
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
**Symbols:**

```
ffffffff8180e440-ffffffff8180e6c9: dwc2_hcd_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818dfa84)
Location: drivers/usb/dwc2/hcd.c:4995
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818e98e4)
Location: drivers/usb/dwc2/hcd.c:4997
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
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
In drivers/usb/dwc2/hcd.c (ffffffff818cb3b4)
Location: drivers/usb/dwc2/hcd.c:5114
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
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
In drivers/usb/dwc2/hcd.c (ffffffff819646a9)
Location: drivers/usb/dwc2/hcd.c:5115
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
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
In drivers/usb/dwc2/hcd.c (ffffffff81abebb5)
Location: drivers/usb/dwc2/hcd.c:5111
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
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
In drivers/usb/dwc2/hcd.c (ffffffff81c48425)
Location: drivers/usb/dwc2/hcd.c:5082
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
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
In drivers/usb/dwc2/hcd.c (ffffffff81caf9f5)
Location: drivers/usb/dwc2/hcd.c:5082
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
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
In drivers/usb/dwc2/hcd.c (ffffffff81d64705)
Location: drivers/usb/dwc2/hcd.c:5082
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
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
In drivers/usb/dwc2/hcd.c (ffff800010a4785c)
Location: drivers/usb/dwc2/hcd.c:4995
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
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
In drivers/usb/dwc2/hcd.c (c0b1a020)
Location: drivers/usb/dwc2/hcd.c:4995
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
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
In drivers/usb/dwc2/hcd.c (c000000000b0c4a8)
Location: drivers/usb/dwc2/hcd.c:4995
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
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
In drivers/usb/dwc2/hcd.c (ffffffe000664312)
Location: drivers/usb/dwc2/hcd.c:4995
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
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
void dwc2_hcd_release(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff817c6820)
Location: drivers/usb/dwc2/hcd.c:4995
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
**Symbols:**

```
ffffffff817c6820-ffffffff817c6aa9: dwc2_hcd_release (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dwc2_hcd_release(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818032c0)
Location: drivers/usb/dwc2/hcd.c:4995
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
**Symbols:**

```
ffffffff818032c0-ffffffff81803549: dwc2_hcd_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dwc2_hcd_release(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff8181d3d0)
Location: drivers/usb/dwc2/hcd.c:4995
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
**Symbols:**

```
ffffffff8181d3d0-ffffffff8181d659: dwc2_hcd_release (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
