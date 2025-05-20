# Function: <code>dwc2_hcd_reinit</code>

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
In drivers/usb/dwc2/hcd.c (ffffffff81626b85)
Location: drivers/usb/dwc2/hcd.c:552
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
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
In drivers/usb/dwc2/hcd.c (ffffffff8168510d)
Location: drivers/usb/dwc2/hcd.c:2393
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
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
In drivers/usb/dwc2/hcd.c (ffffffff816b333d)
Location: drivers/usb/dwc2/hcd.c:2424
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
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
In drivers/usb/dwc2/hcd.c (ffffffff816c761d)
Location: drivers/usb/dwc2/hcd.c:2437
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
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
In drivers/usb/dwc2/hcd.c (ffffffff81733a8d)
Location: drivers/usb/dwc2/hcd.c:2443
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
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
In drivers/usb/dwc2/hcd.c (ffffffff81773e74)
Location: drivers/usb/dwc2/hcd.c:2497
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
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
In drivers/usb/dwc2/hcd.c (ffffffff8179ba93)
Location: drivers/usb/dwc2/hcd.c:2487
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
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
In drivers/usb/dwc2/hcd.c (ffffffff817dab83)
Location: drivers/usb/dwc2/hcd.c:2303
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
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
In drivers/usb/dwc2/hcd.c (ffffffff8180baa3)
Location: drivers/usb/dwc2/hcd.c:2303
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
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
In drivers/usb/dwc2/hcd.c (ffffffff818dca06)
Location: drivers/usb/dwc2/hcd.c:2303
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
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
In drivers/usb/dwc2/hcd.c (ffffffff818e6896)
Location: drivers/usb/dwc2/hcd.c:2304
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dwc2_hcd_reinit(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818c7f40)
Location: drivers/usb/dwc2/hcd.c:2302
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
```
**Symbols:**

```
ffffffff818c7f40-ffffffff818c8099: dwc2_hcd_reinit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dwc2_hcd_reinit(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:2302
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
```
**Symbols:**

```
ffffffff81961190-ffffffff819612af: dwc2_hcd_reinit (STB_LOCAL)
ffffffff81d1b2ab-ffffffff81d1b2bf: dwc2_hcd_reinit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dwc2_hcd_reinit(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:2298
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
```
**Symbols:**

```
ffffffff81abb5b0-ffffffff81abb6da: dwc2_hcd_reinit (STB_LOCAL)
ffffffff81ee653b-ffffffff81ee6550: dwc2_hcd_reinit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void dwc2_hcd_reinit(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:2269
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
```
**Symbols:**

```
ffffffff81c44ae0-ffffffff81c44c0a: dwc2_hcd_reinit (STB_LOCAL)
ffffffff820a1dcd-ffffffff820a1de2: dwc2_hcd_reinit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void dwc2_hcd_reinit(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:2269
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
```
**Symbols:**

```
ffffffff81cac0d0-ffffffff81cac1fa: dwc2_hcd_reinit (STB_LOCAL)
ffffffff821233a0-ffffffff821233b5: dwc2_hcd_reinit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dwc2_hcd_reinit(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:2269
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
```
**Symbols:**

```
ffffffff81d60d80-ffffffff81d60eaa: dwc2_hcd_reinit (STB_LOCAL)
ffffffff82204b77-ffffffff82204b8c: dwc2_hcd_reinit.cold (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (ffff800010a43fbc)
Location: drivers/usb/dwc2/hcd.c:2303
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
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
In drivers/usb/dwc2/hcd.c (c0b16864)
Location: drivers/usb/dwc2/hcd.c:2303
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
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
In drivers/usb/dwc2/hcd.c (c000000000b06c04)
Location: drivers/usb/dwc2/hcd.c:2303
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
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
In drivers/usb/dwc2/hcd.c (ffffffe000660684)
Location: drivers/usb/dwc2/hcd.c:2303
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
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
In drivers/usb/dwc2/hcd.c (ffffffff817c3e83)
Location: drivers/usb/dwc2/hcd.c:2303
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81800923)
Location: drivers/usb/dwc2/hcd.c:2303
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
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
In drivers/usb/dwc2/hcd.c (ffffffff8181aa33)
Location: drivers/usb/dwc2/hcd.c:2303
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
