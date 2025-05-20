# Function: <code>dwc2_handle_wakeup_detected_intr</code>

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
In drivers/usb/dwc2/core_intr.c (ffffffff81625baa)
Location: drivers/usb/dwc2/core_intr.c:347
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
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
In drivers/usb/dwc2/core_intr.c (ffffffff8168427a)
Location: drivers/usb/dwc2/core_intr.c:345
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
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
In drivers/usb/dwc2/core_intr.c (ffffffff816b081b)
Location: drivers/usb/dwc2/core_intr.c:345
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
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
In drivers/usb/dwc2/core_intr.c (ffffffff816c57d2)
Location: drivers/usb/dwc2/core_intr.c:344
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
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
In drivers/usb/dwc2/core_intr.c (ffffffff81731ab2)
Location: drivers/usb/dwc2/core_intr.c:345
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
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
In drivers/usb/dwc2/core_intr.c (ffffffff81771128)
Location: drivers/usb/dwc2/core_intr.c:396
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
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
In drivers/usb/dwc2/core_intr.c (ffffffff81795d80)
Location: drivers/usb/dwc2/core_intr.c:396
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void dwc2_handle_wakeup_detected_intr(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (0)
Location: drivers/usb/dwc2/core_intr.c:396
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
ffffffff817d4890-ffffffff817d4b3c: dwc2_handle_wakeup_detected_intr (STB_LOCAL)
ffffffff817d59b6-ffffffff817d59de: dwc2_handle_wakeup_detected_intr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void dwc2_handle_wakeup_detected_intr(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (0)
Location: drivers/usb/dwc2/core_intr.c:396
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
ffffffff81805740-ffffffff818059ec: dwc2_handle_wakeup_detected_intr (STB_LOCAL)
ffffffff81806866-ffffffff8180688e: dwc2_handle_wakeup_detected_intr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void dwc2_handle_wakeup_detected_intr(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (0)
Location: drivers/usb/dwc2/core_intr.c:391
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
ffffffff818d64f0-ffffffff818d679e: dwc2_handle_wakeup_detected_intr (STB_LOCAL)
ffffffff818d70d7-ffffffff818d70ff: dwc2_handle_wakeup_detected_intr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void dwc2_handle_wakeup_detected_intr(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (0)
Location: drivers/usb/dwc2/core_intr.c:391
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
ffffffff818e06d0-ffffffff818e097e: dwc2_handle_wakeup_detected_intr (STB_LOCAL)
ffffffff81c1ed36-ffffffff81c1ed5e: dwc2_handle_wakeup_detected_intr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void dwc2_handle_wakeup_detected_intr(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (0)
Location: drivers/usb/dwc2/core_intr.c:407
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
ffffffff818c35b0-ffffffff818c387a: dwc2_handle_wakeup_detected_intr (STB_LOCAL)
ffffffff81c10b47-ffffffff81c10b83: dwc2_handle_wakeup_detected_intr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dwc2_handle_wakeup_detected_intr(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (0)
Location: drivers/usb/dwc2/core_intr.c:407
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
ffffffff8195ada0-ffffffff8195b13c: dwc2_handle_wakeup_detected_intr (STB_LOCAL)
ffffffff81d18d9b-ffffffff81d18ed9: dwc2_handle_wakeup_detected_intr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dwc2_handle_wakeup_detected_intr(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (0)
Location: drivers/usb/dwc2/core_intr.c:407
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
ffffffff81ab4c20-ffffffff81ab4fd5: dwc2_handle_wakeup_detected_intr (STB_LOCAL)
ffffffff81ee3f62-ffffffff81ee40c9: dwc2_handle_wakeup_detected_intr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void dwc2_handle_wakeup_detected_intr(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (0)
Location: drivers/usb/dwc2/core_intr.c:377
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
ffffffff81c3d490-ffffffff81c3d887: dwc2_handle_wakeup_detected_intr (STB_LOCAL)
ffffffff820a004c-ffffffff820a0176: dwc2_handle_wakeup_detected_intr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void dwc2_handle_wakeup_detected_intr(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (0)
Location: drivers/usb/dwc2/core_intr.c:377
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
ffffffff81ca4870-ffffffff81ca4c71: dwc2_handle_wakeup_detected_intr (STB_LOCAL)
ffffffff82121602-ffffffff8212172c: dwc2_handle_wakeup_detected_intr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dwc2_handle_wakeup_detected_intr(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (0)
Location: drivers/usb/dwc2/core_intr.c:377
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
ffffffff81d594c0-ffffffff81d598c1: dwc2_handle_wakeup_detected_intr (STB_LOCAL)
ffffffff82202dd9-ffffffff82202f03: dwc2_handle_wakeup_detected_intr.cold (STB_LOCAL)
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
void dwc2_handle_wakeup_detected_intr(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (ffff800010a3ca58)
Location: drivers/usb/dwc2/core_intr.c:396
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
ffff800010a3ca58-ffff800010a3ce08: dwc2_handle_wakeup_detected_intr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dwc2_handle_wakeup_detected_intr(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (c0b0f4e0)
Location: drivers/usb/dwc2/core_intr.c:396
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
c0b0f4e0-c0b0f848: dwc2_handle_wakeup_detected_intr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dwc2_handle_wakeup_detected_intr(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (c000000000afb920)
Location: drivers/usb/dwc2/core_intr.c:396
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
c000000000afb920-c000000000afbf88: dwc2_handle_wakeup_detected_intr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dwc2_handle_wakeup_detected_intr(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (ffffffe0006585be)
Location: drivers/usb/dwc2/core_intr.c:396
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
ffffffe0006585be-ffffffe000658a92: dwc2_handle_wakeup_detected_intr (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void dwc2_handle_wakeup_detected_intr(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (0)
Location: drivers/usb/dwc2/core_intr.c:396
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
ffffffff817bdb20-ffffffff817bddcc: dwc2_handle_wakeup_detected_intr (STB_LOCAL)
ffffffff817bec46-ffffffff817bec6e: dwc2_handle_wakeup_detected_intr.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void dwc2_handle_wakeup_detected_intr(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (0)
Location: drivers/usb/dwc2/core_intr.c:396
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
ffffffff817fa5c0-ffffffff817fa86c: dwc2_handle_wakeup_detected_intr (STB_LOCAL)
ffffffff817fb6e6-ffffffff817fb70e: dwc2_handle_wakeup_detected_intr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void dwc2_handle_wakeup_detected_intr(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (0)
Location: drivers/usb/dwc2/core_intr.c:396
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
ffffffff81814cc0-ffffffff81814f6c: dwc2_handle_wakeup_detected_intr (STB_LOCAL)
ffffffff81815812-ffffffff8181583a: dwc2_handle_wakeup_detected_intr.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
