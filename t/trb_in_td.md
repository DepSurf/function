# Function: <code>trb_in_td</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct xhci_segment *trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *start_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t suspect_dma, bool debug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816583d0)
Location: drivers/usb/host/xhci-ring.c:1673
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff816583d0-ffffffff81658556: trb_in_td (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct xhci_segment *trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *start_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t suspect_dma, bool debug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816b8de0)
Location: drivers/usb/host/xhci-ring.c:1698
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff816b8de0-ffffffff816b8f74: trb_in_td (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct xhci_segment *trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *start_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t suspect_dma, bool debug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816e7060)
Location: drivers/usb/host/xhci-ring.c:1714
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff816e7060-ffffffff816e71f4: trb_in_td (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct xhci_segment *trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *start_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t suspect_dma, bool debug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816fb120)
Location: drivers/usb/host/xhci-ring.c:1761
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff816fb120-ffffffff816fb2b0: trb_in_td (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct xhci_segment *trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *start_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t suspect_dma, bool debug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81767c60)
Location: drivers/usb/host/xhci-ring.c:1755
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff81767c60-ffffffff81767df0: trb_in_td (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct xhci_segment *trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *start_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t suspect_dma, bool debug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817a8f20)
Location: drivers/usb/host/xhci-ring.c:1680
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff817a8f20-ffffffff817a90ce: trb_in_td (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct xhci_segment *trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *start_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t suspect_dma, bool debug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817cee90)
Location: drivers/usb/host/xhci-ring.c:1728
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff817cee90-ffffffff817cf03e: trb_in_td (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct xhci_segment *trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *start_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t suspect_dma, bool debug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:1748
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff81813488-ffffffff818134cf: trb_in_td.cold (STB_LOCAL)
ffffffff8180f290-ffffffff8180f3f1: trb_in_td (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct xhci_segment *trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *start_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t suspect_dma, bool debug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:1748
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff818446b2-ffffffff818446f9: trb_in_td.cold (STB_LOCAL)
ffffffff818403a0-ffffffff81840501: trb_in_td (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct xhci_segment *trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *start_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t suspect_dma, bool debug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:1774
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff81917213-ffffffff8191725a: trb_in_td.cold (STB_LOCAL)
ffffffff81914130-ffffffff8191428d: trb_in_td (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct xhci_segment *trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *start_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t suspect_dma, bool debug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:1779
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff81c2213b-ffffffff81c22182: trb_in_td.cold (STB_LOCAL)
ffffffff8191b750-ffffffff8191b8ad: trb_in_td (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct xhci_segment *trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *start_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t suspect_dma, bool debug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2019
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff81c14358-ffffffff81c1439f: trb_in_td.cold (STB_LOCAL)
ffffffff818fed10-ffffffff818fee6c: trb_in_td (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct xhci_segment *trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *start_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t suspect_dma, bool debug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2084
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
```
**Symbols:**

```
ffffffff81d212a1-ffffffff81d212e8: trb_in_td.cold (STB_LOCAL)
ffffffff8199dee0-ffffffff8199e03c: trb_in_td (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct xhci_segment *trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *start_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t suspect_dma, bool debug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2018
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
```
**Symbols:**

```
ffffffff81eece7c-ffffffff81eecec4: trb_in_td.cold (STB_LOCAL)
ffffffff81afb2a0-ffffffff81afb3f9: trb_in_td (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct xhci_segment *trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *start_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t suspect_dma, bool debug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81c89a90)
Location: drivers/usb/host/xhci-ring.c:2020
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
```
**Symbols:**

```
ffffffff81c89a90-ffffffff81c89c45: trb_in_td (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct xhci_segment *trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *start_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t suspect_dma, bool debug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81cf0ca0)
Location: drivers/usb/host/xhci-ring.c:2042
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff81cf0ca0-ffffffff81cf0e55: trb_in_td (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct xhci_segment *trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *start_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t suspect_dma, bool debug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81da64f0)
Location: drivers/usb/host/xhci-ring.c:2047
Inline: False
```
**Symbols:**

```
ffffffff81da64f0-ffffffff81da66a5: trb_in_td (STB_GLOBAL)
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
struct xhci_segment *trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *start_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t suspect_dma, bool debug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffff800010a7f0d0)
Location: drivers/usb/host/xhci-ring.c:1748
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffff800010a7f0d0-ffff800010a7f28c: trb_in_td (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct xhci_segment *trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *start_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t suspect_dma, bool debug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c0b52440)
Location: drivers/usb/host/xhci-ring.c:1748
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
c0b52440-c0b52614: trb_in_td (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct xhci_segment *trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *start_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t suspect_dma, bool debug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c000000000b57bc0)
Location: drivers/usb/host/xhci-ring.c:1748
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
c000000000b57bc0-c000000000b57e44: trb_in_td (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct xhci_segment *trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *start_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t suspect_dma, bool debug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffe000695cd4)
Location: drivers/usb/host/xhci-ring.c:1748
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffe000695cd4-ffffffe000695e08: trb_in_td (STB_GLOBAL)
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
struct xhci_segment *trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *start_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t suspect_dma, bool debug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:1748
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff817fca62-ffffffff817fcaa9: trb_in_td.cold (STB_LOCAL)
ffffffff817f8750-ffffffff817f88b1: trb_in_td (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct xhci_segment *trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *start_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t suspect_dma, bool debug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:1748
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff817c1c02-ffffffff817c1c49: trb_in_td.cold (STB_LOCAL)
ffffffff817bd8f0-ffffffff817bda51: trb_in_td (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct xhci_segment *trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *start_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t suspect_dma, bool debug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:1748
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff81839532-ffffffff81839579: trb_in_td.cold (STB_LOCAL)
ffffffff81835220-ffffffff81835381: trb_in_td (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct xhci_segment *trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *start_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t suspect_dma, bool debug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:1748
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff81853985-ffffffff818539cc: trb_in_td.cold (STB_LOCAL)
ffffffff8184f540-ffffffff8184f6a1: trb_in_td (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
