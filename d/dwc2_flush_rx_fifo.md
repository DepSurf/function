# Function: <code>dwc2_flush_rx_fifo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dwc2_flush_rx_fifo(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81623610)
Location: drivers/usb/dwc2/core.c:2364
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff81623610-ffffffff81623682: dwc2_flush_rx_fifo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dwc2_flush_rx_fifo(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff816821b0)
Location: drivers/usb/dwc2/core.c:613
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
```
**Symbols:**

```
ffffffff816821b0-ffffffff8168221c: dwc2_flush_rx_fifo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dwc2_flush_rx_fifo(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff816b0060)
Location: drivers/usb/dwc2/core.c:714
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
```
**Symbols:**

```
ffffffff816b0060-ffffffff816b00cc: dwc2_flush_rx_fifo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dwc2_flush_rx_fifo(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff816c5240)
Location: drivers/usb/dwc2/core.c:714
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
```
**Symbols:**

```
ffffffff816c5240-ffffffff816c52ac: dwc2_flush_rx_fifo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dwc2_flush_rx_fifo(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81731520)
Location: drivers/usb/dwc2/core.c:715
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
```
**Symbols:**

```
ffffffff81731520-ffffffff8173158c: dwc2_flush_rx_fifo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dwc2_flush_rx_fifo(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81770740)
Location: drivers/usb/dwc2/core.c:880
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
```
**Symbols:**

```
ffffffff81770740-ffffffff817707d9: dwc2_flush_rx_fifo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dwc2_flush_rx_fifo(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81795510)
Location: drivers/usb/dwc2/core.c:881
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff81795510-ffffffff817955ba: dwc2_flush_rx_fifo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void dwc2_flush_rx_fifo(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:881
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff817d439e-ffffffff817d43d4: dwc2_flush_rx_fifo.cold (STB_LOCAL)
ffffffff817d3d40-ffffffff817d3db4: dwc2_flush_rx_fifo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void dwc2_flush_rx_fifo(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:881
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff81805248-ffffffff8180527e: dwc2_flush_rx_fifo.cold (STB_LOCAL)
ffffffff81804c10-ffffffff81804c84: dwc2_flush_rx_fifo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dwc2_flush_rx_fifo(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff818d5430)
Location: drivers/usb/dwc2/core.c:896
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff818d5430-ffffffff818d54f8: dwc2_flush_rx_fifo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dwc2_flush_rx_fifo(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff818df750)
Location: drivers/usb/dwc2/core.c:896
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff818df750-ffffffff818df818: dwc2_flush_rx_fifo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dwc2_flush_rx_fifo(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff818c28d0)
Location: drivers/usb/dwc2/core.c:840
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff818c28d0-ffffffff818c299d: dwc2_flush_rx_fifo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dwc2_flush_rx_fifo(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:840
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff81d1865f-ffffffff81d1869e: dwc2_flush_rx_fifo.cold (STB_LOCAL)
ffffffff81959860-ffffffff81959964: dwc2_flush_rx_fifo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dwc2_flush_rx_fifo(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:840
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff81ee361e-ffffffff81ee365d: dwc2_flush_rx_fifo.cold (STB_LOCAL)
ffffffff81ab36e0-ffffffff81ab37ff: dwc2_flush_rx_fifo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void dwc2_flush_rx_fifo(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:810
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff8209f77e-ffffffff8209f7bd: dwc2_flush_rx_fifo.cold (STB_LOCAL)
ffffffff81c3beb0-ffffffff81c3bfcf: dwc2_flush_rx_fifo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void dwc2_flush_rx_fifo(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:810
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff82120d34-ffffffff82120d73: dwc2_flush_rx_fifo.cold (STB_LOCAL)
ffffffff81ca32b0-ffffffff81ca33cf: dwc2_flush_rx_fifo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dwc2_flush_rx_fifo(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:810
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff8220250b-ffffffff8220254a: dwc2_flush_rx_fifo.cold (STB_LOCAL)
ffffffff81d57f00-ffffffff81d5801f: dwc2_flush_rx_fifo (STB_GLOBAL)
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
void dwc2_flush_rx_fifo(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffff800010a3be18)
Location: drivers/usb/dwc2/core.c:881
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffff800010a3be18-ffff800010a3bee8: dwc2_flush_rx_fifo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dwc2_flush_rx_fifo(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (c0b0ea68)
Location: drivers/usb/dwc2/core.c:881
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
c0b0ea68-c0b0eb84: dwc2_flush_rx_fifo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dwc2_flush_rx_fifo(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (c000000000afa570)
Location: drivers/usb/dwc2/core.c:881
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
c000000000afa570-c000000000afa668: dwc2_flush_rx_fifo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dwc2_flush_rx_fifo(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffe00065754c)
Location: drivers/usb/dwc2/core.c:881
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffe00065754c-ffffffe000657622: dwc2_flush_rx_fifo (STB_GLOBAL)
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
void dwc2_flush_rx_fifo(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:881
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff817bd628-ffffffff817bd65e: dwc2_flush_rx_fifo.cold (STB_LOCAL)
ffffffff817bcff0-ffffffff817bd064: dwc2_flush_rx_fifo (STB_GLOBAL)
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
void dwc2_flush_rx_fifo(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:881
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff817fa0c8-ffffffff817fa0fe: dwc2_flush_rx_fifo.cold (STB_LOCAL)
ffffffff817f9a90-ffffffff817f9b04: dwc2_flush_rx_fifo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void dwc2_flush_rx_fifo(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:881
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff81814308-ffffffff8181433e: dwc2_flush_rx_fifo.cold (STB_LOCAL)
ffffffff81813cd0-ffffffff81813d44: dwc2_flush_rx_fifo (STB_GLOBAL)
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
