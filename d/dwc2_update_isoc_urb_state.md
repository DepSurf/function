# Function: <code>dwc2_update_isoc_urb_state</code>

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
In drivers/usb/dwc2/hcd_intr.c (ffffffff8162b41f)
Location: drivers/usb/dwc2/hcd_intr.c:543
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
enum dwc2_halt_status dwc2_update_isoc_urb_state(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, struct dwc2_qtd *qtd, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (ffffffff8168b6b0)
Location: drivers/usb/dwc2/hcd_intr.c:566
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
**Symbols:**

```
ffffffff8168b6b0-ffffffff8168b862: dwc2_update_isoc_urb_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
enum dwc2_halt_status dwc2_update_isoc_urb_state(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, struct dwc2_qtd *qtd, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (ffffffff816b97b0)
Location: drivers/usb/dwc2/hcd_intr.c:566
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
**Symbols:**

```
ffffffff816b97b0-ffffffff816b9961: dwc2_update_isoc_urb_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
enum dwc2_halt_status dwc2_update_isoc_urb_state(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, struct dwc2_qtd *qtd, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (ffffffff816cdab0)
Location: drivers/usb/dwc2/hcd_intr.c:565
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
**Symbols:**

```
ffffffff816cdab0-ffffffff816cdc4c: dwc2_update_isoc_urb_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
enum dwc2_halt_status dwc2_update_isoc_urb_state(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, struct dwc2_qtd *qtd, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (ffffffff8173a0c0)
Location: drivers/usb/dwc2/hcd_intr.c:566
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
**Symbols:**

```
ffffffff8173a0c0-ffffffff8173a25f: dwc2_update_isoc_urb_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
enum dwc2_halt_status dwc2_update_isoc_urb_state(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, struct dwc2_qtd *qtd, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (ffffffff8177a6f0)
Location: drivers/usb/dwc2/hcd_intr.c:584
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
**Symbols:**

```
ffffffff8177a6f0-ffffffff8177a88f: dwc2_update_isoc_urb_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
enum dwc2_halt_status dwc2_update_isoc_urb_state(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, struct dwc2_qtd *qtd, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (ffffffff817a0100)
Location: drivers/usb/dwc2/hcd_intr.c:584
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
**Symbols:**

```
ffffffff817a0100-ffffffff817a0293: dwc2_update_isoc_urb_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
enum dwc2_halt_status dwc2_update_isoc_urb_state(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, struct dwc2_qtd *qtd, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd_intr.c:584
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
**Symbols:**

```
ffffffff817df240-ffffffff817df3e0: dwc2_update_isoc_urb_state (STB_LOCAL)
ffffffff817e163f-ffffffff817e1657: dwc2_update_isoc_urb_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
enum dwc2_halt_status dwc2_update_isoc_urb_state(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, struct dwc2_qtd *qtd, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd_intr.c:584
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
**Symbols:**

```
ffffffff81810130-ffffffff818102d0: dwc2_update_isoc_urb_state (STB_LOCAL)
ffffffff8181252f-ffffffff81812547: dwc2_update_isoc_urb_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
enum dwc2_halt_status dwc2_update_isoc_urb_state(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, struct dwc2_qtd *qtd, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (ffffffff818e1be4)
Location: drivers/usb/dwc2/hcd_intr.c:584
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
**Symbols:**

```
ffffffff818e0f10-ffffffff818e10a0: dwc2_update_isoc_urb_state (STB_LOCAL)
ffffffff818e3573-ffffffff818e358a: dwc2_update_isoc_urb_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
enum dwc2_halt_status dwc2_update_isoc_urb_state(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, struct dwc2_qtd *qtd, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (ffffffff818eb444)
Location: drivers/usb/dwc2/hcd_intr.c:584
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
**Symbols:**

```
ffffffff818ea760-ffffffff818ea8f0: dwc2_update_isoc_urb_state (STB_LOCAL)
ffffffff81c1fad7-ffffffff81c1faee: dwc2_update_isoc_urb_state.cold (STB_LOCAL)
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
In drivers/usb/dwc2/hcd_intr.c (ffffffff818cedf2)
Location: drivers/usb/dwc2/hcd_intr.c:584
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81968bd8)
Location: drivers/usb/dwc2/hcd_intr.c:584
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81ac2dc0)
Location: drivers/usb/dwc2/hcd_intr.c:584
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81c4ccb0)
Location: drivers/usb/dwc2/hcd_intr.c:554
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81cb4325)
Location: drivers/usb/dwc2/hcd_intr.c:554
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81d69055)
Location: drivers/usb/dwc2/hcd_intr.c:554
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
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
enum dwc2_halt_status dwc2_update_isoc_urb_state(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, struct dwc2_qtd *qtd, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (ffff800010a48a28)
Location: drivers/usb/dwc2/hcd_intr.c:584
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
**Symbols:**

```
ffff800010a48a28-ffff800010a48bf8: dwc2_update_isoc_urb_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
enum dwc2_halt_status dwc2_update_isoc_urb_state(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, struct dwc2_qtd *qtd, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (c0b1b054)
Location: drivers/usb/dwc2/hcd_intr.c:584
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
**Symbols:**

```
c0b1b054-c0b1b200: dwc2_update_isoc_urb_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
enum dwc2_halt_status dwc2_update_isoc_urb_state(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, struct dwc2_qtd *qtd, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (c000000000b0def0)
Location: drivers/usb/dwc2/hcd_intr.c:584
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
**Symbols:**

```
c000000000b0def0-c000000000b0e168: dwc2_update_isoc_urb_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
enum dwc2_halt_status dwc2_update_isoc_urb_state(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, struct dwc2_qtd *qtd, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (ffffffe000665852)
Location: drivers/usb/dwc2/hcd_intr.c:584
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
**Symbols:**

```
ffffffe000665852-ffffffe0006659d2: dwc2_update_isoc_urb_state (STB_LOCAL)
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
enum dwc2_halt_status dwc2_update_isoc_urb_state(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, struct dwc2_qtd *qtd, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd_intr.c:584
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
**Symbols:**

```
ffffffff817c8510-ffffffff817c86b0: dwc2_update_isoc_urb_state (STB_LOCAL)
ffffffff817ca90f-ffffffff817ca927: dwc2_update_isoc_urb_state.cold (STB_LOCAL)
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
enum dwc2_halt_status dwc2_update_isoc_urb_state(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, struct dwc2_qtd *qtd, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd_intr.c:584
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
**Symbols:**

```
ffffffff81804fb0-ffffffff81805150: dwc2_update_isoc_urb_state (STB_LOCAL)
ffffffff818073af-ffffffff818073c7: dwc2_update_isoc_urb_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
enum dwc2_halt_status dwc2_update_isoc_urb_state(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, int chnum, struct dwc2_qtd *qtd, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd_intr.c:584
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
**Symbols:**

```
ffffffff8181f0c0-ffffffff8181f260: dwc2_update_isoc_urb_state (STB_LOCAL)
ffffffff818214bb-ffffffff818214d3: dwc2_update_isoc_urb_state.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
