# Function: <code>prepare_transfer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int prepare_transfer(struct xhci_hcd *xhci, struct xhci_virt_device *xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb *urb, unsigned int td_index, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81657100)
Location: drivers/usb/host/xhci-ring.c:2889
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
```
**Symbols:**

```
ffffffff81657100-ffffffff81657228: prepare_transfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int prepare_transfer(struct xhci_hcd *xhci, struct xhci_virt_device *xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb *urb, unsigned int td_index, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816b7860)
Location: drivers/usb/host/xhci-ring.c:2912
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff816b7860-ffffffff816b798e: prepare_transfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int prepare_transfer(struct xhci_hcd *xhci, struct xhci_virt_device *xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb *urb, unsigned int td_index, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816e5b10)
Location: drivers/usb/host/xhci-ring.c:2814
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff816e5b10-ffffffff816e5c3e: prepare_transfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int prepare_transfer(struct xhci_hcd *xhci, struct xhci_virt_device *xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb *urb, unsigned int td_index, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816f99b0)
Location: drivers/usb/host/xhci-ring.c:2916
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff816f99b0-ffffffff816f9af6: prepare_transfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int prepare_transfer(struct xhci_hcd *xhci, struct xhci_virt_device *xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb *urb, unsigned int td_index, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81766510)
Location: drivers/usb/host/xhci-ring.c:2920
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff81766510-ffffffff81766656: prepare_transfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int prepare_transfer(struct xhci_hcd *xhci, struct xhci_virt_device *xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb *urb, unsigned int td_index, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817a7260)
Location: drivers/usb/host/xhci-ring.c:2839
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff817a7260-ffffffff817a739e: prepare_transfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int prepare_transfer(struct xhci_hcd *xhci, struct xhci_virt_device *xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb *urb, unsigned int td_index, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817cd110)
Location: drivers/usb/host/xhci-ring.c:2903
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff817cd110-ffffffff817cd24e: prepare_transfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int prepare_transfer(struct xhci_hcd *xhci, struct xhci_virt_device *xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb *urb, unsigned int td_index, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff8180cef0)
Location: drivers/usb/host/xhci-ring.c:2949
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff8180cef0-ffffffff8180d036: prepare_transfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int prepare_transfer(struct xhci_hcd *xhci, struct xhci_virt_device *xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb *urb, unsigned int td_index, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff8183dfe0)
Location: drivers/usb/host/xhci-ring.c:2976
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff8183dfe0-ffffffff8183e126: prepare_transfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int prepare_transfer(struct xhci_hcd *xhci, struct xhci_virt_device *xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb *urb, unsigned int td_index, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81910ac0)
Location: drivers/usb/host/xhci-ring.c:3022
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff81910ac0-ffffffff81910c06: prepare_transfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int prepare_transfer(struct xhci_hcd *xhci, struct xhci_virt_device *xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb *urb, unsigned int td_index, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81918340)
Location: drivers/usb/host/xhci-ring.c:3032
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff81918340-ffffffff81918486: prepare_transfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int prepare_transfer(struct xhci_hcd *xhci, struct xhci_virt_device *xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb *urb, unsigned int td_index, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff818fdaa0)
Location: drivers/usb/host/xhci-ring.c:3220
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff818fdaa0-ffffffff818fdbe8: prepare_transfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int prepare_transfer(struct xhci_hcd *xhci, struct xhci_virt_device *xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb *urb, unsigned int td_index, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff8199cdd0)
Location: drivers/usb/host/xhci-ring.c:3290
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff8199cdd0-ffffffff8199cf15: prepare_transfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int prepare_transfer(struct xhci_hcd *xhci, struct xhci_virt_device *xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb *urb, unsigned int td_index, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81af7d10)
Location: drivers/usb/host/xhci-ring.c:3225
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff81af7d10-ffffffff81af7e92: prepare_transfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int prepare_transfer(struct xhci_hcd *xhci, struct xhci_virt_device *xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb *urb, unsigned int td_index, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81c85a70)
Location: drivers/usb/host/xhci-ring.c:3232
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff81c85a70-ffffffff81c85bf2: prepare_transfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int prepare_transfer(struct xhci_hcd *xhci, struct xhci_virt_device *xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb *urb, unsigned int td_index, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81cec8c0)
Location: drivers/usb/host/xhci-ring.c:3252
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff81cec8c0-ffffffff81ceca42: prepare_transfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int prepare_transfer(struct xhci_hcd *xhci, struct xhci_virt_device *xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb *urb, unsigned int td_index, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81da1f00)
Location: drivers/usb/host/xhci-ring.c:3295
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff81da1f00-ffffffff81da2082: prepare_transfer (STB_LOCAL)
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
int prepare_transfer(struct xhci_hcd *xhci, struct xhci_virt_device *xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb *urb, unsigned int td_index, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffff800010a7bf88)
Location: drivers/usb/host/xhci-ring.c:2976
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffff800010a7bf88-ffff800010a7c0fc: prepare_transfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int prepare_transfer(struct xhci_hcd *xhci, struct xhci_virt_device *xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb *urb, unsigned int td_index, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c0b4fde4)
Location: drivers/usb/host/xhci-ring.c:2976
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
c0b4fde4-c0b4ff34: prepare_transfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int prepare_transfer(struct xhci_hcd *xhci, struct xhci_virt_device *xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb *urb, unsigned int td_index, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c000000000b54050)
Location: drivers/usb/host/xhci-ring.c:2976
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
c000000000b54050-c000000000b541fc: prepare_transfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int prepare_transfer(struct xhci_hcd *xhci, struct xhci_virt_device *xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb *urb, unsigned int td_index, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffe00069324c)
Location: drivers/usb/host/xhci-ring.c:2976
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffe00069324c-ffffffe000693384: prepare_transfer (STB_LOCAL)
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
int prepare_transfer(struct xhci_hcd *xhci, struct xhci_virt_device *xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb *urb, unsigned int td_index, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817f6390)
Location: drivers/usb/host/xhci-ring.c:2976
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff817f6390-ffffffff817f64d6: prepare_transfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int prepare_transfer(struct xhci_hcd *xhci, struct xhci_virt_device *xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb *urb, unsigned int td_index, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817bb530)
Location: drivers/usb/host/xhci-ring.c:2976
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff817bb530-ffffffff817bb676: prepare_transfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int prepare_transfer(struct xhci_hcd *xhci, struct xhci_virt_device *xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb *urb, unsigned int td_index, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81832e60)
Location: drivers/usb/host/xhci-ring.c:2976
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff81832e60-ffffffff81832fa6: prepare_transfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int prepare_transfer(struct xhci_hcd *xhci, struct xhci_virt_device *xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb *urb, unsigned int td_index, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff8184d060)
Location: drivers/usb/host/xhci-ring.c:2976
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff8184d060-ffffffff8184d1a6: prepare_transfer (STB_LOCAL)
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
