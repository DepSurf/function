# Function: <code>dwc2_hcd_complete_xfer_ddma</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dwc2_hcd_complete_xfer_ddma(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8162eed0)
Location: drivers/usb/dwc2/hcd_ddma.c:1154
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
**Symbols:**

```
ffffffff8162eed0-ffffffff8162f77f: dwc2_hcd_complete_xfer_ddma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dwc2_hcd_complete_xfer_ddma(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8168fbb0)
Location: drivers/usb/dwc2/hcd_ddma.c:1298
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
**Symbols:**

```
ffffffff8168fbb0-ffffffff8169062a: dwc2_hcd_complete_xfer_ddma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dwc2_hcd_complete_xfer_ddma(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff816bdc60)
Location: drivers/usb/dwc2/hcd_ddma.c:1298
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
**Symbols:**

```
ffffffff816bdc60-ffffffff816be6da: dwc2_hcd_complete_xfer_ddma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dwc2_hcd_complete_xfer_ddma(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff816d1cb0)
Location: drivers/usb/dwc2/hcd_ddma.c:1297
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
**Symbols:**

```
ffffffff816d1cb0-ffffffff816d26b7: dwc2_hcd_complete_xfer_ddma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dwc2_hcd_complete_xfer_ddma(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8173e330)
Location: drivers/usb/dwc2/hcd_ddma.c:1298
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
**Symbols:**

```
ffffffff8173e330-ffffffff8173ed3c: dwc2_hcd_complete_xfer_ddma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dwc2_hcd_complete_xfer_ddma(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8177ece0)
Location: drivers/usb/dwc2/hcd_ddma.c:1299
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
**Symbols:**

```
ffffffff8177ece0-ffffffff8177f707: dwc2_hcd_complete_xfer_ddma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dwc2_hcd_complete_xfer_ddma(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817a5480)
Location: drivers/usb/dwc2/hcd_ddma.c:1299
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
**Symbols:**

```
ffffffff817a5480-ffffffff817a5efb: dwc2_hcd_complete_xfer_ddma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void dwc2_hcd_complete_xfer_ddma(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (0)
Location: drivers/usb/dwc2/hcd_ddma.c:1299
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
**Symbols:**

```
ffffffff817e50d2-ffffffff817e5149: dwc2_hcd_complete_xfer_ddma.cold (STB_LOCAL)
ffffffff817e4690-ffffffff817e507a: dwc2_hcd_complete_xfer_ddma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void dwc2_hcd_complete_xfer_ddma(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (0)
Location: drivers/usb/dwc2/hcd_ddma.c:1299
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
**Symbols:**

```
ffffffff81815f92-ffffffff81816009: dwc2_hcd_complete_xfer_ddma.cold (STB_LOCAL)
ffffffff81815550-ffffffff81815f3a: dwc2_hcd_complete_xfer_ddma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dwc2_hcd_complete_xfer_ddma(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818e6dd0)
Location: drivers/usb/dwc2/hcd_ddma.c:1299
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
**Symbols:**

```
ffffffff818e6dd0-ffffffff818e6fc0: dwc2_hcd_complete_xfer_ddma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dwc2_hcd_complete_xfer_ddma(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818efe90)
Location: drivers/usb/dwc2/hcd_ddma.c:1299
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
**Symbols:**

```
ffffffff818efe90-ffffffff818f0080: dwc2_hcd_complete_xfer_ddma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dwc2_hcd_complete_xfer_ddma(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818d3640)
Location: drivers/usb/dwc2/hcd_ddma.c:1299
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
**Symbols:**

```
ffffffff818d3640-ffffffff818d382e: dwc2_hcd_complete_xfer_ddma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dwc2_hcd_complete_xfer_ddma(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8196e140)
Location: drivers/usb/dwc2/hcd_ddma.c:1299
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
**Symbols:**

```
ffffffff8196e140-ffffffff8196e32e: dwc2_hcd_complete_xfer_ddma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dwc2_hcd_complete_xfer_ddma(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81ac8770)
Location: drivers/usb/dwc2/hcd_ddma.c:1299
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
**Symbols:**

```
ffffffff81ac8770-ffffffff81ac898f: dwc2_hcd_complete_xfer_ddma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dwc2_hcd_complete_xfer_ddma(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81c52b20)
Location: drivers/usb/dwc2/hcd_ddma.c:1269
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
**Symbols:**

```
ffffffff81c52b20-ffffffff81c52d3f: dwc2_hcd_complete_xfer_ddma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dwc2_hcd_complete_xfer_ddma(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81cba0e0)
Location: drivers/usb/dwc2/hcd_ddma.c:1269
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
**Symbols:**

```
ffffffff81cba0e0-ffffffff81cba308: dwc2_hcd_complete_xfer_ddma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dwc2_hcd_complete_xfer_ddma(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81d6ee50)
Location: drivers/usb/dwc2/hcd_ddma.c:1269
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
**Symbols:**

```
ffffffff81d6ee50-ffffffff81d6f078: dwc2_hcd_complete_xfer_ddma (STB_GLOBAL)
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
void dwc2_hcd_complete_xfer_ddma(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffff800010a4e708)
Location: drivers/usb/dwc2/hcd_ddma.c:1299
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
**Symbols:**

```
ffff800010a4e708-ffff800010a4f040: dwc2_hcd_complete_xfer_ddma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dwc2_hcd_complete_xfer_ddma(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (c0b207bc)
Location: drivers/usb/dwc2/hcd_ddma.c:1299
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
**Symbols:**

```
c0b207bc-c0b2111c: dwc2_hcd_complete_xfer_ddma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dwc2_hcd_complete_xfer_ddma(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (c000000000b161e0)
Location: drivers/usb/dwc2/hcd_ddma.c:1299
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
**Symbols:**

```
c000000000b161e0-c000000000b16ea0: dwc2_hcd_complete_xfer_ddma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dwc2_hcd_complete_xfer_ddma(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffe00066b0b8)
Location: drivers/usb/dwc2/hcd_ddma.c:1299
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
**Symbols:**

```
ffffffe00066b0b8-ffffffe00066b8dc: dwc2_hcd_complete_xfer_ddma (STB_GLOBAL)
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
void dwc2_hcd_complete_xfer_ddma(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (0)
Location: drivers/usb/dwc2/hcd_ddma.c:1299
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
**Symbols:**

```
ffffffff817ce372-ffffffff817ce3e9: dwc2_hcd_complete_xfer_ddma.cold (STB_LOCAL)
ffffffff817cd930-ffffffff817ce31a: dwc2_hcd_complete_xfer_ddma (STB_GLOBAL)
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
void dwc2_hcd_complete_xfer_ddma(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (0)
Location: drivers/usb/dwc2/hcd_ddma.c:1299
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
**Symbols:**

```
ffffffff8180ae12-ffffffff8180ae89: dwc2_hcd_complete_xfer_ddma.cold (STB_LOCAL)
ffffffff8180a3d0-ffffffff8180adba: dwc2_hcd_complete_xfer_ddma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void dwc2_hcd_complete_xfer_ddma(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (0)
Location: drivers/usb/dwc2/hcd_ddma.c:1299
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
**Symbols:**

```
ffffffff81824f22-ffffffff81824f99: dwc2_hcd_complete_xfer_ddma.cold (STB_LOCAL)
ffffffff818244e0-ffffffff81824eca: dwc2_hcd_complete_xfer_ddma (STB_GLOBAL)
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
