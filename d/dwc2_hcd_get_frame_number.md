# Function: <code>dwc2_hcd_get_frame_number</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int dwc2_hcd_get_frame_number(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81626905)
Location: drivers/usb/dwc2/hcd.c:1879
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
```
**Symbols:**

```
ffffffff81629830-ffffffff8162984b: dwc2_hcd_get_frame_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int dwc2_hcd_get_frame_number(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81684e25)
Location: drivers/usb/dwc2/hcd.c:3736
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
```
**Symbols:**

```
ffffffff816884c0-ffffffff816884d8: dwc2_hcd_get_frame_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int dwc2_hcd_get_frame_number(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff816b3055)
Location: drivers/usb/dwc2/hcd.c:3767
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
```
**Symbols:**

```
ffffffff816b66e0-ffffffff816b66f8: dwc2_hcd_get_frame_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int dwc2_hcd_get_frame_number(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff816c7335)
Location: drivers/usb/dwc2/hcd.c:3795
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
```
**Symbols:**

```
ffffffff816caa40-ffffffff816caa58: dwc2_hcd_get_frame_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int dwc2_hcd_get_frame_number(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff817337a5)
Location: drivers/usb/dwc2/hcd.c:3804
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
```
**Symbols:**

```
ffffffff81736f90-ffffffff81736fa8: dwc2_hcd_get_frame_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int dwc2_hcd_get_frame_number(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff817734a5)
Location: drivers/usb/dwc2/hcd.c:3934
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
```
**Symbols:**

```
ffffffff81776f70-ffffffff81776f88: dwc2_hcd_get_frame_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int dwc2_hcd_get_frame_number(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff817987bd)
Location: drivers/usb/dwc2/hcd.c:3934
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
```
**Symbols:**

```
ffffffff8179cc00-ffffffff8179cc23: dwc2_hcd_get_frame_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int dwc2_hcd_get_frame_number(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff817d7a4d)
Location: drivers/usb/dwc2/hcd.c:3754
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
```
**Symbols:**

```
ffffffff817db7d0-ffffffff817db7f3: dwc2_hcd_get_frame_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int dwc2_hcd_get_frame_number(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818088dd)
Location: drivers/usb/dwc2/hcd.c:3754
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
```
**Symbols:**

```
ffffffff8180c6f0-ffffffff8180c713: dwc2_hcd_get_frame_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int dwc2_hcd_get_frame_number(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818d960d)
Location: drivers/usb/dwc2/hcd.c:3754
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_isoc_dma_desc
```
**Symbols:**

```
ffffffff818dd4b0-ffffffff818dd4d3: dwc2_hcd_get_frame_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int dwc2_hcd_get_frame_number(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818e355d)
Location: drivers/usb/dwc2/hcd.c:3755
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_isoc_dma_desc
```
**Symbols:**

```
ffffffff818e7300-ffffffff818e7323: dwc2_hcd_get_frame_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int dwc2_hcd_get_frame_number(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818c682d)
Location: drivers/usb/dwc2/hcd.c:3806
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_isoc_dma_desc
```
**Symbols:**

```
ffffffff818c91f0-ffffffff818c9215: dwc2_hcd_get_frame_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dwc2_hcd_get_frame_number(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff8195ef83)
Location: drivers/usb/dwc2/hcd.c:3806
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_isoc_dma_desc
```
**Symbols:**

```
ffffffff81d1b5f1-ffffffff81d1b605: dwc2_hcd_get_frame_number.cold (STB_LOCAL)
ffffffff81961df0-ffffffff81961e2b: dwc2_hcd_get_frame_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dwc2_hcd_get_frame_number(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81ab93e3)
Location: drivers/usb/dwc2/hcd.c:3802
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_isoc_dma_desc
```
**Symbols:**

```
ffffffff81ee6935-ffffffff81ee6949: dwc2_hcd_get_frame_number.cold (STB_LOCAL)
ffffffff81abc260-ffffffff81abc2a3: dwc2_hcd_get_frame_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dwc2_hcd_get_frame_number(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81c42753)
Location: drivers/usb/dwc2/hcd.c:3773
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_isoc_dma_desc
```
**Symbols:**

```
ffffffff820a2163-ffffffff820a2177: dwc2_hcd_get_frame_number.cold (STB_LOCAL)
ffffffff81c45880-ffffffff81c458c3: dwc2_hcd_get_frame_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dwc2_hcd_get_frame_number(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81ca9d23)
Location: drivers/usb/dwc2/hcd.c:3773
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_isoc_dma_desc
```
**Symbols:**

```
ffffffff82123729-ffffffff8212373d: dwc2_hcd_get_frame_number.cold (STB_LOCAL)
ffffffff81cace50-ffffffff81cace93: dwc2_hcd_get_frame_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dwc2_hcd_get_frame_number(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81d5e9d3)
Location: drivers/usb/dwc2/hcd.c:3773
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_isoc_dma_desc
```
**Symbols:**

```
ffffffff82204f00-ffffffff82204f14: dwc2_hcd_get_frame_number.cold (STB_LOCAL)
ffffffff81d61b00-ffffffff81d61b43: dwc2_hcd_get_frame_number (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int dwc2_hcd_get_frame_number(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffff800010a40a14)
Location: drivers/usb/dwc2/hcd.c:3754
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
```
**Symbols:**

```
ffff800010a44ef0-ffff800010a44f44: dwc2_hcd_get_frame_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int dwc2_hcd_get_frame_number(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (c0b12a98)
Location: drivers/usb/dwc2/hcd.c:3754
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_calc_starting_frame
```
**Symbols:**

```
c0b17704-c0b17738: dwc2_hcd_get_frame_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int dwc2_hcd_get_frame_number(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (c000000000b014f4)
Location: drivers/usb/dwc2/hcd.c:3754
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
```
**Symbols:**

```
c000000000b083b0-c000000000b0846c: dwc2_hcd_get_frame_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int dwc2_hcd_get_frame_number(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffe00065c78c)
Location: drivers/usb/dwc2/hcd.c:3754
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
```
**Symbols:**

```
ffffffe000661798-ffffffe0006617fa: dwc2_hcd_get_frame_number (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int dwc2_hcd_get_frame_number(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff817c0cbd)
Location: drivers/usb/dwc2/hcd.c:3754
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
```
**Symbols:**

```
ffffffff817c4ad0-ffffffff817c4af3: dwc2_hcd_get_frame_number (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int dwc2_hcd_get_frame_number(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff817fd75d)
Location: drivers/usb/dwc2/hcd.c:3754
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
```
**Symbols:**

```
ffffffff81801570-ffffffff81801593: dwc2_hcd_get_frame_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int dwc2_hcd_get_frame_number(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff8181786d)
Location: drivers/usb/dwc2/hcd.c:3754
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
```
**Symbols:**

```
ffffffff8181b680-ffffffff8181b6a3: dwc2_hcd_get_frame_number (STB_GLOBAL)
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
