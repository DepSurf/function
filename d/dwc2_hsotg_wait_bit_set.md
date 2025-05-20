# Function: <code>dwc2_hsotg_wait_bit_set</code>

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
int dwc2_hsotg_wait_bit_set(struct dwc2_hsotg *hsotg, u32 offset, u32 mask, u32 timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81770745)
Location: drivers/usb/dwc2/core.c:985
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffff817708c0-ffffffff81770934: dwc2_hsotg_wait_bit_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dwc2_hsotg_wait_bit_set(struct dwc2_hsotg *hsotg, u32 offset, u32 mask, u32 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81794e20)
Location: drivers/usb/dwc2/core.c:986
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffff81794e20-ffffffff81794e96: dwc2_hsotg_wait_bit_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dwc2_hsotg_wait_bit_set(struct dwc2_hsotg *hsotg, u32 offset, u32 mask, u32 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff817d3690)
Location: drivers/usb/dwc2/core.c:986
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffff817d3690-ffffffff817d3706: dwc2_hsotg_wait_bit_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dwc2_hsotg_wait_bit_set(struct dwc2_hsotg *hsotg, u32 offset, u32 mask, u32 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81804560)
Location: drivers/usb/dwc2/core.c:986
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffff81804560-ffffffff818045d6: dwc2_hsotg_wait_bit_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int dwc2_hsotg_wait_bit_set(struct dwc2_hsotg *hsotg, u32 offset, u32 mask, u32 timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff818d5435)
Location: drivers/usb/dwc2/core.c:1001
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffff818d5660-ffffffff818d56d6: dwc2_hsotg_wait_bit_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int dwc2_hsotg_wait_bit_set(struct dwc2_hsotg *hsotg, u32 offset, u32 mask, u32 timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff818df765)
Location: drivers/usb/dwc2/core.c:1001
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffff818df980-ffffffff818df9f6: dwc2_hsotg_wait_bit_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int dwc2_hsotg_wait_bit_set(struct dwc2_hsotg *hsotg, u32 offset, u32 mask, u32 timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff818c28e5)
Location: drivers/usb/dwc2/core.c:945
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffff818c2b10-ffffffff818c2b86: dwc2_hsotg_wait_bit_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dwc2_hsotg_wait_bit_set(struct dwc2_hsotg *hsotg, u32 offset, u32 mask, u32 timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81959879)
Location: drivers/usb/dwc2/core.c:945
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffff81d187a8-ffffffff81d187bd: dwc2_hsotg_wait_bit_set.cold (STB_LOCAL)
ffffffff81959bf0-ffffffff81959c82: dwc2_hsotg_wait_bit_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dwc2_hsotg_wait_bit_set(struct dwc2_hsotg *hsotg, u32 offset, u32 mask, u32 timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81ab36f9)
Location: drivers/usb/dwc2/core.c:945
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffff81ee3791-ffffffff81ee37a6: dwc2_hsotg_wait_bit_set.cold (STB_LOCAL)
ffffffff81ab3aa0-ffffffff81ab3b4a: dwc2_hsotg_wait_bit_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dwc2_hsotg_wait_bit_set(struct dwc2_hsotg *hsotg, u32 offset, u32 mask, u32 timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81c3bec9)
Location: drivers/usb/dwc2/core.c:915
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffff8209f8f1-ffffffff8209f906: dwc2_hsotg_wait_bit_set.cold (STB_LOCAL)
ffffffff81c3c2f0-ffffffff81c3c39a: dwc2_hsotg_wait_bit_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dwc2_hsotg_wait_bit_set(struct dwc2_hsotg *hsotg, u32 offset, u32 mask, u32 timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81ca32c9)
Location: drivers/usb/dwc2/core.c:915
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffff82120ea7-ffffffff82120ebc: dwc2_hsotg_wait_bit_set.cold (STB_LOCAL)
ffffffff81ca36f0-ffffffff81ca379a: dwc2_hsotg_wait_bit_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dwc2_hsotg_wait_bit_set(struct dwc2_hsotg *hsotg, u32 offset, u32 mask, u32 timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81d57f19)
Location: drivers/usb/dwc2/core.c:915
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffff8220267e-ffffffff82202693: dwc2_hsotg_wait_bit_set.cold (STB_LOCAL)
ffffffff81d58340-ffffffff81d583ea: dwc2_hsotg_wait_bit_set (STB_GLOBAL)
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
int dwc2_hsotg_wait_bit_set(struct dwc2_hsotg *hsotg, u32 offset, u32 mask, u32 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffff800010a3b3e8)
Location: drivers/usb/dwc2/core.c:986
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffff800010a3b3e8-ffff800010a3b498: dwc2_hsotg_wait_bit_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int dwc2_hsotg_wait_bit_set(struct dwc2_hsotg *hsotg, u32 offset, u32 mask, u32 timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (c0b0ea7c)
Location: drivers/usb/dwc2/core.c:986
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
c0b0ed78-c0b0ee04: dwc2_hsotg_wait_bit_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dwc2_hsotg_wait_bit_set(struct dwc2_hsotg *hsotg, u32 offset, u32 mask, u32 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (c000000000af9570)
Location: drivers/usb/dwc2/core.c:986
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
c000000000af9570-c000000000af96d0: dwc2_hsotg_wait_bit_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dwc2_hsotg_wait_bit_set(struct dwc2_hsotg *hsotg, u32 offset, u32 mask, u32 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffe000656894)
Location: drivers/usb/dwc2/core.c:986
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffe000656894-ffffffe00065693e: dwc2_hsotg_wait_bit_set (STB_GLOBAL)
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
int dwc2_hsotg_wait_bit_set(struct dwc2_hsotg *hsotg, u32 offset, u32 mask, u32 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff817bc940)
Location: drivers/usb/dwc2/core.c:986
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffff817bc940-ffffffff817bc9b6: dwc2_hsotg_wait_bit_set (STB_GLOBAL)
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
int dwc2_hsotg_wait_bit_set(struct dwc2_hsotg *hsotg, u32 offset, u32 mask, u32 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff817f93e0)
Location: drivers/usb/dwc2/core.c:986
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffff817f93e0-ffffffff817f9456: dwc2_hsotg_wait_bit_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dwc2_hsotg_wait_bit_set(struct dwc2_hsotg *hsotg, u32 offset, u32 mask, u32 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81813620)
Location: drivers/usb/dwc2/core.c:986
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffff81813620-ffffffff81813696: dwc2_hsotg_wait_bit_set (STB_GLOBAL)
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
