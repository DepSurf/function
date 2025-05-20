# Function: <code>dwc2_hsotg_wait_bit_clear</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int dwc2_hsotg_wait_bit_clear(struct dwc2_hsotg *hsotg, u32 offset, u32 mask, u32 timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81770940)
Location: drivers/usb/dwc2/core.c:1008
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
```
**Symbols:**

```
ffffffff81770940-ffffffff817709b6: dwc2_hsotg_wait_bit_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dwc2_hsotg_wait_bit_clear(struct dwc2_hsotg *hsotg, u32 offset, u32 mask, u32 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff817952a0)
Location: drivers/usb/dwc2/core.c:1009
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff817952a0-ffffffff81795316: dwc2_hsotg_wait_bit_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dwc2_hsotg_wait_bit_clear(struct dwc2_hsotg *hsotg, u32 offset, u32 mask, u32 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff817d3b20)
Location: drivers/usb/dwc2/core.c:1009
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff817d3b20-ffffffff817d3b96: dwc2_hsotg_wait_bit_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dwc2_hsotg_wait_bit_clear(struct dwc2_hsotg *hsotg, u32 offset, u32 mask, u32 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff818049f0)
Location: drivers/usb/dwc2/core.c:1009
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff818049f0-ffffffff81804a66: dwc2_hsotg_wait_bit_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int dwc2_hsotg_wait_bit_clear(struct dwc2_hsotg *hsotg, u32 offset, u32 mask, u32 timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff818d54a3)
Location: drivers/usb/dwc2/core.c:1024
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff818d56e0-ffffffff818d5756: dwc2_hsotg_wait_bit_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int dwc2_hsotg_wait_bit_clear(struct dwc2_hsotg *hsotg, u32 offset, u32 mask, u32 timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff818df7c3)
Location: drivers/usb/dwc2/core.c:1024
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff818dfa00-ffffffff818dfa76: dwc2_hsotg_wait_bit_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int dwc2_hsotg_wait_bit_clear(struct dwc2_hsotg *hsotg, u32 offset, u32 mask, u32 timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff818c2946)
Location: drivers/usb/dwc2/core.c:968
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff818c2b90-ffffffff818c2c06: dwc2_hsotg_wait_bit_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dwc2_hsotg_wait_bit_clear(struct dwc2_hsotg *hsotg, u32 offset, u32 mask, u32 timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:968
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff81d187bd-ffffffff81d187d2: dwc2_hsotg_wait_bit_clear.cold (STB_LOCAL)
ffffffff81959c90-ffffffff81959d22: dwc2_hsotg_wait_bit_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dwc2_hsotg_wait_bit_clear(struct dwc2_hsotg *hsotg, u32 offset, u32 mask, u32 timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:968
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff81ee37a6-ffffffff81ee37bb: dwc2_hsotg_wait_bit_clear.cold (STB_LOCAL)
ffffffff81ab3b50-ffffffff81ab3bfa: dwc2_hsotg_wait_bit_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dwc2_hsotg_wait_bit_clear(struct dwc2_hsotg *hsotg, u32 offset, u32 mask, u32 timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:938
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff8209f906-ffffffff8209f91b: dwc2_hsotg_wait_bit_clear.cold (STB_LOCAL)
ffffffff81c3c3b0-ffffffff81c3c45a: dwc2_hsotg_wait_bit_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dwc2_hsotg_wait_bit_clear(struct dwc2_hsotg *hsotg, u32 offset, u32 mask, u32 timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:938
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff82120ebc-ffffffff82120ed1: dwc2_hsotg_wait_bit_clear.cold (STB_LOCAL)
ffffffff81ca37b0-ffffffff81ca385a: dwc2_hsotg_wait_bit_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dwc2_hsotg_wait_bit_clear(struct dwc2_hsotg *hsotg, u32 offset, u32 mask, u32 timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:938
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff82202693-ffffffff822026a8: dwc2_hsotg_wait_bit_clear.cold (STB_LOCAL)
ffffffff81d58400-ffffffff81d584aa: dwc2_hsotg_wait_bit_clear (STB_GLOBAL)
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
int dwc2_hsotg_wait_bit_clear(struct dwc2_hsotg *hsotg, u32 offset, u32 mask, u32 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffff800010a3bae8)
Location: drivers/usb/dwc2/core.c:1009
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffff800010a3bae8-ffff800010a3bb98: dwc2_hsotg_wait_bit_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int dwc2_hsotg_wait_bit_clear(struct dwc2_hsotg *hsotg, u32 offset, u32 mask, u32 timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (c0b0ee04)
Location: drivers/usb/dwc2/core.c:1009
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
c0b0ee04-c0b0ee90: dwc2_hsotg_wait_bit_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dwc2_hsotg_wait_bit_clear(struct dwc2_hsotg *hsotg, u32 offset, u32 mask, u32 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (c000000000af9fe0)
Location: drivers/usb/dwc2/core.c:1009
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
c000000000af9fe0-c000000000afa140: dwc2_hsotg_wait_bit_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dwc2_hsotg_wait_bit_clear(struct dwc2_hsotg *hsotg, u32 offset, u32 mask, u32 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffe0006571c6)
Location: drivers/usb/dwc2/core.c:1009
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffe0006571c6-ffffffe000657270: dwc2_hsotg_wait_bit_clear (STB_GLOBAL)
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
int dwc2_hsotg_wait_bit_clear(struct dwc2_hsotg *hsotg, u32 offset, u32 mask, u32 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff817bcdd0)
Location: drivers/usb/dwc2/core.c:1009
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff817bcdd0-ffffffff817bce46: dwc2_hsotg_wait_bit_clear (STB_GLOBAL)
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
int dwc2_hsotg_wait_bit_clear(struct dwc2_hsotg *hsotg, u32 offset, u32 mask, u32 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff817f9870)
Location: drivers/usb/dwc2/core.c:1009
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff817f9870-ffffffff817f98e6: dwc2_hsotg_wait_bit_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dwc2_hsotg_wait_bit_clear(struct dwc2_hsotg *hsotg, u32 offset, u32 mask, u32 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81813ab0)
Location: drivers/usb/dwc2/core.c:1009
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff81813ab0-ffffffff81813b26: dwc2_hsotg_wait_bit_clear (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
