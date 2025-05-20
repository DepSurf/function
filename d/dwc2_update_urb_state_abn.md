# Function: <code>dwc2_update_urb_state_abn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dwc2_update_urb_state_abn(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, struct dwc2_hcd_urb *urb, struct dwc2_qtd *qtd, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (ffffffff8162b610)
Location: drivers/usb/dwc2/hcd_intr.c:1157
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
**Symbols:**

```
ffffffff8162b610-ffffffff8162b719: dwc2_update_urb_state_abn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (ffffffff8168b630)
Location: drivers/usb/dwc2/hcd_intr.c:1140
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
```
**Symbols:**

```
ffffffff8168b630-ffffffff8168b6a2: dwc2_update_urb_state_abn.isra.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (ffffffff816b9730)
Location: drivers/usb/dwc2/hcd_intr.c:1145
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
```
**Symbols:**

```
ffffffff816b9730-ffffffff816b97a2: dwc2_update_urb_state_abn.isra.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (ffffffff816cda30)
Location: drivers/usb/dwc2/hcd_intr.c:1145
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
```
**Symbols:**

```
ffffffff816cda30-ffffffff816cdaa2: dwc2_update_urb_state_abn.isra.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (ffffffff8173a040)
Location: drivers/usb/dwc2/hcd_intr.c:1146
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
```
**Symbols:**

```
ffffffff8173a040-ffffffff8173a0b2: dwc2_update_urb_state_abn.isra.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (ffffffff8177a670)
Location: drivers/usb/dwc2/hcd_intr.c:1171
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
```
**Symbols:**

```
ffffffff8177a670-ffffffff8177a6e4: dwc2_update_urb_state_abn.isra.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (ffffffff817a02a0)
Location: drivers/usb/dwc2/hcd_intr.c:1171
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
```
**Symbols:**

```
ffffffff817a02a0-ffffffff817a030d: dwc2_update_urb_state_abn.isra.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd_intr.c:1171
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
```
**Symbols:**

```
ffffffff817df3e0-ffffffff817df434: dwc2_update_urb_state_abn.isra.0 (STB_LOCAL)
ffffffff817e1657-ffffffff817e1677: dwc2_update_urb_state_abn.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd_intr.c:1171
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
```
**Symbols:**

```
ffffffff818102d0-ffffffff81810324: dwc2_update_urb_state_abn.isra.0 (STB_LOCAL)
ffffffff81812547-ffffffff81812567: dwc2_update_urb_state_abn.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void dwc2_update_urb_state_abn(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, struct dwc2_hcd_urb *urb, struct dwc2_qtd *qtd, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd_intr.c:1171
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
```
**Symbols:**

```
ffffffff818e1570-ffffffff818e15db: dwc2_update_urb_state_abn (STB_LOCAL)
ffffffff818e35b6-ffffffff818e35dd: dwc2_update_urb_state_abn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void dwc2_update_urb_state_abn(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, struct dwc2_hcd_urb *urb, struct dwc2_qtd *qtd, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd_intr.c:1171
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
```
**Symbols:**

```
ffffffff818eacd0-ffffffff818ead3b: dwc2_update_urb_state_abn (STB_LOCAL)
ffffffff81c1faee-ffffffff81c1fb15: dwc2_update_urb_state_abn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void dwc2_update_urb_state_abn(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, struct dwc2_hcd_urb *urb, struct dwc2_qtd *qtd, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd_intr.c:1171
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
```
**Symbols:**

```
ffffffff818ce620-ffffffff818ce68b: dwc2_update_urb_state_abn (STB_LOCAL)
ffffffff81c11abd-ffffffff81c11ae4: dwc2_update_urb_state_abn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dwc2_update_urb_state_abn(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, struct dwc2_hcd_urb *urb, struct dwc2_qtd *qtd, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd_intr.c:1171
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
```
**Symbols:**

```
ffffffff81967e90-ffffffff81967f32: dwc2_update_urb_state_abn (STB_LOCAL)
ffffffff81d1d25b-ffffffff81d1d2b3: dwc2_update_urb_state_abn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dwc2_update_urb_state_abn(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, struct dwc2_hcd_urb *urb, struct dwc2_qtd *qtd, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd_intr.c:1171
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
```
**Symbols:**

```
ffffffff81ac2010-ffffffff81ac20c0: dwc2_update_urb_state_abn (STB_LOCAL)
ffffffff81ee8aad-ffffffff81ee8b05: dwc2_update_urb_state_abn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void dwc2_update_urb_state_abn(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, struct dwc2_hcd_urb *urb, struct dwc2_qtd *qtd, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd_intr.c:1141
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
```
**Symbols:**

```
ffffffff81c4bcf0-ffffffff81c4bdbc: dwc2_update_urb_state_abn (STB_LOCAL)
ffffffff820a3e9d-ffffffff820a3ecc: dwc2_update_urb_state_abn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void dwc2_update_urb_state_abn(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, struct dwc2_hcd_urb *urb, struct dwc2_qtd *qtd, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd_intr.c:1141
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
```
**Symbols:**

```
ffffffff81cb3360-ffffffff81cb342c: dwc2_update_urb_state_abn (STB_LOCAL)
ffffffff8212545a-ffffffff82125489: dwc2_update_urb_state_abn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dwc2_update_urb_state_abn(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, struct dwc2_hcd_urb *urb, struct dwc2_qtd *qtd, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd_intr.c:1141
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
```
**Symbols:**

```
ffffffff81d68090-ffffffff81d6815c: dwc2_update_urb_state_abn (STB_LOCAL)
ffffffff82206c2e-ffffffff82206c5d: dwc2_update_urb_state_abn.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (ffff800010a48bf8)
Location: drivers/usb/dwc2/hcd_intr.c:1171
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
```
**Symbols:**

```
ffff800010a48bf8-ffff800010a48cc4: dwc2_update_urb_state_abn.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dwc2_update_urb_state_abn(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, struct dwc2_hcd_urb *urb, struct dwc2_qtd *qtd, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (c0b1afc4)
Location: drivers/usb/dwc2/hcd_intr.c:1171
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
```
**Symbols:**

```
c0b1afc4-c0b1b054: dwc2_update_urb_state_abn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (c000000000b0e170)
Location: drivers/usb/dwc2/hcd_intr.c:1171
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
```
**Symbols:**

```
c000000000b0e170-c000000000b0e298: dwc2_update_urb_state_abn.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (ffffffe0006659d2)
Location: drivers/usb/dwc2/hcd_intr.c:1171
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
```
**Symbols:**

```
ffffffe0006659d2-ffffffe000665a78: dwc2_update_urb_state_abn.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd_intr.c:1171
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
```
**Symbols:**

```
ffffffff817c86b0-ffffffff817c8704: dwc2_update_urb_state_abn.isra.0 (STB_LOCAL)
ffffffff817ca927-ffffffff817ca947: dwc2_update_urb_state_abn.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd_intr.c:1171
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
```
**Symbols:**

```
ffffffff81805150-ffffffff818051a4: dwc2_update_urb_state_abn.isra.0 (STB_LOCAL)
ffffffff818073c7-ffffffff818073e7: dwc2_update_urb_state_abn.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd_intr.c:1171
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
```
**Symbols:**

```
ffffffff8181f260-ffffffff8181f2b4: dwc2_update_urb_state_abn.isra.0 (STB_LOCAL)
ffffffff818214d3-ffffffff818214f3: dwc2_update_urb_state_abn.isra.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
