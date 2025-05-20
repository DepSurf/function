# Function: <code>dwc2_disable_host_interrupts</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dwc2_disable_host_interrupts(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81622930)
Location: drivers/usb/dwc2/core.c:875
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
```
**Symbols:**

```
ffffffff81622930-ffffffff81622954: dwc2_disable_host_interrupts (STB_GLOBAL)
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
Location: drivers/usb/dwc2/hcd.c:374
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
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
Location: drivers/usb/dwc2/hcd.c:375
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
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
Location: drivers/usb/dwc2/hcd.c:391
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
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
Location: drivers/usb/dwc2/hcd.c:397
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
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
Location: drivers/usb/dwc2/hcd.c:410
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
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
In drivers/usb/dwc2/hcd.c (ffffffff8179e915)
Location: drivers/usb/dwc2/hcd.c:404
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
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
In drivers/usb/dwc2/hcd.c (ffffffff817dd515)
Location: drivers/usb/dwc2/hcd.c:214
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
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
In drivers/usb/dwc2/hcd.c (ffffffff8180e445)
Location: drivers/usb/dwc2/hcd.c:214
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
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
Location: drivers/usb/dwc2/hcd.c:214
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
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
Location: drivers/usb/dwc2/hcd.c:214
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
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
Location: drivers/usb/dwc2/hcd.c:212
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dwc2_disable_host_interrupts(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff819646a9)
Location: drivers/usb/dwc2/hcd.c:212
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
```
**Symbols:**

```
ffffffff8195f0f0-ffffffff8195f17c: dwc2_disable_host_interrupts (STB_LOCAL)
ffffffff81d1a8ad-ffffffff81d1a900: dwc2_disable_host_interrupts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dwc2_disable_host_interrupts(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81abebb5)
Location: drivers/usb/dwc2/hcd.c:208
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
```
**Symbols:**

```
ffffffff81ab9570-ffffffff81ab95f7: dwc2_disable_host_interrupts (STB_LOCAL)
ffffffff81ee59ea-ffffffff81ee5a54: dwc2_disable_host_interrupts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dwc2_disable_host_interrupts(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81c48425)
Location: drivers/usb/dwc2/hcd.c:179
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
```
**Symbols:**

```
ffffffff81c42900-ffffffff81c42987: dwc2_disable_host_interrupts (STB_LOCAL)
ffffffff820a1348-ffffffff820a13b2: dwc2_disable_host_interrupts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dwc2_disable_host_interrupts(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81caf9f5)
Location: drivers/usb/dwc2/hcd.c:179
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
```
**Symbols:**

```
ffffffff81ca9ed0-ffffffff81ca9f57: dwc2_disable_host_interrupts (STB_LOCAL)
ffffffff8212291b-ffffffff82122985: dwc2_disable_host_interrupts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dwc2_disable_host_interrupts(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81d64705)
Location: drivers/usb/dwc2/hcd.c:179
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
```
**Symbols:**

```
ffffffff81d5eb80-ffffffff81d5ec07: dwc2_disable_host_interrupts (STB_LOCAL)
ffffffff822040f2-ffffffff8220415c: dwc2_disable_host_interrupts.cold (STB_LOCAL)
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
void dwc2_disable_host_interrupts(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffff800010a40a50)
Location: drivers/usb/dwc2/hcd.c:214
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
```
**Symbols:**

```
ffff800010a40a50-ffff800010a40adc: dwc2_disable_host_interrupts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dwc2_disable_host_interrupts(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (c0b13388)
Location: drivers/usb/dwc2/hcd.c:214
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
```
**Symbols:**

```
c0b13388-c0b133f0: dwc2_disable_host_interrupts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dwc2_disable_host_interrupts(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (c000000000b01590)
Location: drivers/usb/dwc2/hcd.c:214
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
```
**Symbols:**

```
c000000000b01590-c000000000b0167c: dwc2_disable_host_interrupts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dwc2_disable_host_interrupts(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffe00065c7d8)
Location: drivers/usb/dwc2/hcd.c:214
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
```
**Symbols:**

```
ffffffe00065c7d8-ffffffe00065c89e: dwc2_disable_host_interrupts (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (ffffffff817c6825)
Location: drivers/usb/dwc2/hcd.c:214
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
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
In drivers/usb/dwc2/hcd.c (ffffffff818032c5)
Location: drivers/usb/dwc2/hcd.c:214
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
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
In drivers/usb/dwc2/hcd.c (ffffffff8181d3d5)
Location: drivers/usb/dwc2/hcd.c:214
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
