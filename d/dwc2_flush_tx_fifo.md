# Function: <code>dwc2_flush_tx_fifo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dwc2_flush_tx_fifo(struct dwc2_hsotg *hsotg, const int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81623580)
Location: drivers/usb/dwc2/core.c:2332
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff81623580-ffffffff81623604: dwc2_flush_tx_fifo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dwc2_flush_tx_fifo(struct dwc2_hsotg *hsotg, const int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81682130)
Location: drivers/usb/dwc2/core.c:581
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
```
**Symbols:**

```
ffffffff81682130-ffffffff816821ab: dwc2_flush_tx_fifo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dwc2_flush_tx_fifo(struct dwc2_hsotg *hsotg, const int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff816affe0)
Location: drivers/usb/dwc2/core.c:682
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
```
**Symbols:**

```
ffffffff816affe0-ffffffff816b005b: dwc2_flush_tx_fifo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dwc2_flush_tx_fifo(struct dwc2_hsotg *hsotg, const int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff816c51c0)
Location: drivers/usb/dwc2/core.c:682
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
```
**Symbols:**

```
ffffffff816c51c0-ffffffff816c523b: dwc2_flush_tx_fifo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dwc2_flush_tx_fifo(struct dwc2_hsotg *hsotg, const int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff817314a0)
Location: drivers/usb/dwc2/core.c:683
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
```
**Symbols:**

```
ffffffff817314a0-ffffffff8173151b: dwc2_flush_tx_fifo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dwc2_flush_tx_fifo(struct dwc2_hsotg *hsotg, const int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81770690)
Location: drivers/usb/dwc2/core.c:852
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
```
**Symbols:**

```
ffffffff81770690-ffffffff8177073b: dwc2_flush_tx_fifo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dwc2_flush_tx_fifo(struct dwc2_hsotg *hsotg, const int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81795450)
Location: drivers/usb/dwc2/core.c:853
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff81795450-ffffffff8179550b: dwc2_flush_tx_fifo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void dwc2_flush_tx_fifo(struct dwc2_hsotg *hsotg, const int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:853
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff817d4366-ffffffff817d439e: dwc2_flush_tx_fifo.cold (STB_LOCAL)
ffffffff817d3cb0-ffffffff817d3d31: dwc2_flush_tx_fifo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void dwc2_flush_tx_fifo(struct dwc2_hsotg *hsotg, const int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:853
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff81805210-ffffffff81805248: dwc2_flush_tx_fifo.cold (STB_LOCAL)
ffffffff81804b80-ffffffff81804c01: dwc2_flush_tx_fifo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dwc2_flush_tx_fifo(struct dwc2_hsotg *hsotg, const int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff818d5350)
Location: drivers/usb/dwc2/core.c:868
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff818d5350-ffffffff818d5429: dwc2_flush_tx_fifo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dwc2_flush_tx_fifo(struct dwc2_hsotg *hsotg, const int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff818df670)
Location: drivers/usb/dwc2/core.c:868
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff818df670-ffffffff818df749: dwc2_flush_tx_fifo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dwc2_flush_tx_fifo(struct dwc2_hsotg *hsotg, const int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff818c27f0)
Location: drivers/usb/dwc2/core.c:812
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff818c27f0-ffffffff818c28ce: dwc2_flush_tx_fifo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dwc2_flush_tx_fifo(struct dwc2_hsotg *hsotg, const int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:812
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff81d18620-ffffffff81d1865f: dwc2_flush_tx_fifo.cold (STB_LOCAL)
ffffffff81959740-ffffffff81959855: dwc2_flush_tx_fifo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dwc2_flush_tx_fifo(struct dwc2_hsotg *hsotg, const int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:812
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff81ee35df-ffffffff81ee361e: dwc2_flush_tx_fifo.cold (STB_LOCAL)
ffffffff81ab35b0-ffffffff81ab36e0: dwc2_flush_tx_fifo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void dwc2_flush_tx_fifo(struct dwc2_hsotg *hsotg, const int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:782
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff8209f73f-ffffffff8209f77e: dwc2_flush_tx_fifo.cold (STB_LOCAL)
ffffffff81c3bd70-ffffffff81c3bea0: dwc2_flush_tx_fifo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void dwc2_flush_tx_fifo(struct dwc2_hsotg *hsotg, const int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:782
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff82120cf5-ffffffff82120d34: dwc2_flush_tx_fifo.cold (STB_LOCAL)
ffffffff81ca3170-ffffffff81ca32a0: dwc2_flush_tx_fifo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dwc2_flush_tx_fifo(struct dwc2_hsotg *hsotg, const int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:782
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff822024cc-ffffffff8220250b: dwc2_flush_tx_fifo.cold (STB_LOCAL)
ffffffff81d57dc0-ffffffff81d57ef0: dwc2_flush_tx_fifo (STB_GLOBAL)
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
void dwc2_flush_tx_fifo(struct dwc2_hsotg *hsotg, const int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffff800010a3bd38)
Location: drivers/usb/dwc2/core.c:853
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffff800010a3bd38-ffff800010a3be18: dwc2_flush_tx_fifo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dwc2_flush_tx_fifo(struct dwc2_hsotg *hsotg, const int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (c0b0e940)
Location: drivers/usb/dwc2/core.c:853
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
c0b0e940-c0b0ea68: dwc2_flush_tx_fifo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dwc2_flush_tx_fifo(struct dwc2_hsotg *hsotg, const int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (c000000000afa450)
Location: drivers/usb/dwc2/core.c:853
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
c000000000afa450-c000000000afa564: dwc2_flush_tx_fifo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dwc2_flush_tx_fifo(struct dwc2_hsotg *hsotg, const int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffe00065744e)
Location: drivers/usb/dwc2/core.c:853
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffe00065744e-ffffffe00065754c: dwc2_flush_tx_fifo (STB_GLOBAL)
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
void dwc2_flush_tx_fifo(struct dwc2_hsotg *hsotg, const int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:853
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff817bd5f0-ffffffff817bd628: dwc2_flush_tx_fifo.cold (STB_LOCAL)
ffffffff817bcf60-ffffffff817bcfe1: dwc2_flush_tx_fifo (STB_GLOBAL)
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
void dwc2_flush_tx_fifo(struct dwc2_hsotg *hsotg, const int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:853
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff817fa090-ffffffff817fa0c8: dwc2_flush_tx_fifo.cold (STB_LOCAL)
ffffffff817f9a00-ffffffff817f9a81: dwc2_flush_tx_fifo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void dwc2_flush_tx_fifo(struct dwc2_hsotg *hsotg, const int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:853
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff818142d0-ffffffff81814308: dwc2_flush_tx_fifo.cold (STB_LOCAL)
ffffffff81813c40-ffffffff81813cc1: dwc2_flush_tx_fifo (STB_GLOBAL)
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
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
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
