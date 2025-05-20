# Function: <code>dwc2_hc_halt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dwc2_hc_halt(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81622bf0)
Location: drivers/usb/dwc2/core.c:1410
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff81622bf0-ffffffff81622da7: dwc2_hc_halt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void dwc2_hc_halt(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff816878a0)
Location: drivers/usb/dwc2/hcd.c:928
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff816878a0-ffffffff81687a48: dwc2_hc_halt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void dwc2_hc_halt(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff816b5ad0)
Location: drivers/usb/dwc2/hcd.c:958
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff816b5ad0-ffffffff816b5c80: dwc2_hc_halt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void dwc2_hc_halt(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff816c9de0)
Location: drivers/usb/dwc2/hcd.c:975
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff816c9de0-ffffffff816c9fae: dwc2_hc_halt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void dwc2_hc_halt(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81736300)
Location: drivers/usb/dwc2/hcd.c:981
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff81736300-ffffffff817364da: dwc2_hc_halt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dwc2_hc_halt(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81775cc0)
Location: drivers/usb/dwc2/hcd.c:998
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff81775cc0-ffffffff81775f25: dwc2_hc_halt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dwc2_hc_halt(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff8179b300)
Location: drivers/usb/dwc2/hcd.c:991
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff8179b300-ffffffff8179b645: dwc2_hc_halt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_halt(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:801
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff817deaa0-ffffffff817dead1: dwc2_hc_halt.cold (STB_LOCAL)
ffffffff817da430-ffffffff817da748: dwc2_hc_halt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_halt(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:801
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff8180f9cb-ffffffff8180f9fc: dwc2_hc_halt.cold (STB_LOCAL)
ffffffff8180b350-ffffffff8180b668: dwc2_hc_halt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_halt(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:801
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff818e06d0-ffffffff818e0701: dwc2_hc_halt.cold (STB_LOCAL)
ffffffff818dc0c0-ffffffff818dc3c8: dwc2_hc_halt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_halt(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:801
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff81c1f747-ffffffff81c1f778: dwc2_hc_halt.cold (STB_LOCAL)
ffffffff818e5f80-ffffffff818e625d: dwc2_hc_halt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_halt(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:799
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff81c114d9-ffffffff81c1150a: dwc2_hc_halt.cold (STB_LOCAL)
ffffffff818c8360-ffffffff818c8642: dwc2_hc_halt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_halt(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:799
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff81d1b11f-ffffffff81d1b26d: dwc2_hc_halt.cold (STB_LOCAL)
ffffffff81960aa0-ffffffff81960e01: dwc2_hc_halt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_halt(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:795
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff81ee63ae-ffffffff81ee64fc: dwc2_hc_halt.cold (STB_LOCAL)
ffffffff81abae80-ffffffff81abb227: dwc2_hc_halt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_halt(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:766
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff820a1c71-ffffffff820a1d8e: dwc2_hc_halt.cold (STB_LOCAL)
ffffffff81c44360-ffffffff81c44717: dwc2_hc_halt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_halt(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:766
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff82123244-ffffffff82123361: dwc2_hc_halt.cold (STB_LOCAL)
ffffffff81cab950-ffffffff81cabd05: dwc2_hc_halt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_halt(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:766
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff82204a1b-ffffffff82204b38: dwc2_hc_halt.cold (STB_LOCAL)
ffffffff81d60600-ffffffff81d609b5: dwc2_hc_halt (STB_GLOBAL)
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
void dwc2_hc_halt(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffff800010a43768)
Location: drivers/usb/dwc2/hcd.c:801
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffff800010a43768-ffff800010a43a4c: dwc2_hc_halt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dwc2_hc_halt(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (c0b16034)
Location: drivers/usb/dwc2/hcd.c:801
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
c0b16034-c0b16388: dwc2_hc_halt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dwc2_hc_halt(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (c000000000b05e40)
Location: drivers/usb/dwc2/hcd.c:801
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
c000000000b05e40-c000000000b064fc: dwc2_hc_halt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dwc2_hc_halt(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffe00065fe18)
Location: drivers/usb/dwc2/hcd.c:801
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffe00065fe18-ffffffe00066020e: dwc2_hc_halt (STB_GLOBAL)
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
void dwc2_hc_halt(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:801
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff817c7dab-ffffffff817c7ddc: dwc2_hc_halt.cold (STB_LOCAL)
ffffffff817c3730-ffffffff817c3a48: dwc2_hc_halt (STB_GLOBAL)
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
void dwc2_hc_halt(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:801
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff8180484b-ffffffff8180487c: dwc2_hc_halt.cold (STB_LOCAL)
ffffffff818001d0-ffffffff818004e8: dwc2_hc_halt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_halt(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:801
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff8181e95b-ffffffff8181e98c: dwc2_hc_halt.cold (STB_LOCAL)
ffffffff8181a2e0-ffffffff8181a5f8: dwc2_hc_halt (STB_GLOBAL)
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
