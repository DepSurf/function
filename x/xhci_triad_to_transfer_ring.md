# Function: <code>xhci_triad_to_transfer_ring</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct xhci_ring *xhci_triad_to_transfer_ring(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816575e0)
Location: drivers/usb/host/xhci-ring.c:375
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_urb_to_transfer_ring
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
```
**Symbols:**

```
ffffffff816575e0-ffffffff81657660: xhci_triad_to_transfer_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct xhci_ring *xhci_triad_to_transfer_ring(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816b8320)
Location: drivers/usb/host/xhci-ring.c:368
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
```
**Symbols:**

```
ffffffff816b8320-ffffffff816b83a8: xhci_triad_to_transfer_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct xhci_ring *xhci_triad_to_transfer_ring(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816e66b0)
Location: drivers/usb/host/xhci-ring.c:452
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
```
**Symbols:**

```
ffffffff816e66b0-ffffffff816e6738: xhci_triad_to_transfer_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct xhci_ring *xhci_triad_to_transfer_ring(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816fa800)
Location: drivers/usb/host/xhci-ring.c:451
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
```
**Symbols:**

```
ffffffff816fa800-ffffffff816fa884: xhci_triad_to_transfer_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct xhci_ring *xhci_triad_to_transfer_ring(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81767340)
Location: drivers/usb/host/xhci-ring.c:440
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
```
**Symbols:**

```
ffffffff81767340-ffffffff817673c4: xhci_triad_to_transfer_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct xhci_ring *xhci_triad_to_transfer_ring(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817a8610)
Location: drivers/usb/host/xhci-ring.c:440
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
```
**Symbols:**

```
ffffffff817a8610-ffffffff817a8692: xhci_triad_to_transfer_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct xhci_ring *xhci_triad_to_transfer_ring(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817ce580)
Location: drivers/usb/host/xhci-ring.c:440
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
```
**Symbols:**

```
ffffffff817ce580-ffffffff817ce602: xhci_triad_to_transfer_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct xhci_ring *xhci_triad_to_transfer_ring(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff8181316e)
Location: drivers/usb/host/xhci-ring.c:447
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
```
**Symbols:**

```
ffffffff8181316e-ffffffff818131af: xhci_triad_to_transfer_ring.cold (STB_LOCAL)
ffffffff8180ec70-ffffffff8180ecc1: xhci_triad_to_transfer_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct xhci_ring *xhci_triad_to_transfer_ring(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81844398)
Location: drivers/usb/host/xhci-ring.c:447
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
```
**Symbols:**

```
ffffffff81844398-ffffffff818443d9: xhci_triad_to_transfer_ring.cold (STB_LOCAL)
ffffffff8183fd80-ffffffff8183fdd1: xhci_triad_to_transfer_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct xhci_ring *xhci_triad_to_transfer_ring(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:453
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
```
**Symbols:**

```
ffffffff819170b2-ffffffff819170f3: xhci_triad_to_transfer_ring.cold (STB_LOCAL)
ffffffff81913a30-ffffffff81913a81: xhci_triad_to_transfer_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct xhci_ring *xhci_triad_to_transfer_ring(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:453
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
```
**Symbols:**

```
ffffffff81c21fda-ffffffff81c2201b: xhci_triad_to_transfer_ring.cold (STB_LOCAL)
ffffffff8191b050-ffffffff8191b0a1: xhci_triad_to_transfer_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct xhci_ring *xhci_triad_to_transfer_ring(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff818fbe25)
Location: drivers/usb/host/xhci-ring.c:516
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:prepare_transfer
```
**Symbols:**

```
ffffffff81c13f28-ffffffff81c13f8c: xhci_triad_to_transfer_ring.cold (STB_LOCAL)
ffffffff818fda10-ffffffff818fda95: xhci_triad_to_transfer_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct xhci_ring *xhci_triad_to_transfer_ring(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff8199acaa)
Location: drivers/usb/host/xhci-ring.c:529
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:prepare_transfer
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
```
**Symbols:**

```
ffffffff81d20e6b-ffffffff81d20ed3: xhci_triad_to_transfer_ring.cold (STB_LOCAL)
ffffffff8199cca0-ffffffff8199cdcd: xhci_triad_to_transfer_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct xhci_ring *xhci_triad_to_transfer_ring(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81afdf47)
Location: drivers/usb/host/xhci-ring.c:529
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:prepare_transfer
  - drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffffffff81eecb56-ffffffff81eecb9f: xhci_triad_to_transfer_ring.cold (STB_LOCAL)
ffffffff81afacb0-ffffffff81afade9: xhci_triad_to_transfer_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct xhci_ring *xhci_triad_to_transfer_ring(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81c8cce7)
Location: drivers/usb/host/xhci-ring.c:529
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:prepare_transfer
  - drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffffffff81c89130-ffffffff81c89297: xhci_triad_to_transfer_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct xhci_ring *xhci_triad_to_transfer_ring(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81cf3867)
Location: drivers/usb/host/xhci-ring.c:583
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:prepare_transfer
  - drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffffffff81cf0330-ffffffff81cf0497: xhci_triad_to_transfer_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct xhci_ring *xhci_triad_to_transfer_ring(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81da91a7)
Location: drivers/usb/host/xhci-ring.c:591
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:prepare_transfer
  - drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
**Symbols:**

```
ffffffff81da5b50-ffffffff81da5cb7: xhci_triad_to_transfer_ring (STB_GLOBAL)
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
struct xhci_ring *xhci_triad_to_transfer_ring(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffff800010a7e7a8)
Location: drivers/usb/host/xhci-ring.c:447
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
```
**Symbols:**

```
ffff800010a7e7a8-ffff800010a7e880: xhci_triad_to_transfer_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct xhci_ring *xhci_triad_to_transfer_ring(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c0b51c6c)
Location: drivers/usb/host/xhci-ring.c:447
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
```
**Symbols:**

```
c0b51c6c-c0b51d24: xhci_triad_to_transfer_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct xhci_ring *xhci_triad_to_transfer_ring(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c000000000b57070)
Location: drivers/usb/host/xhci-ring.c:447
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
```
**Symbols:**

```
c000000000b57070-c000000000b5715c: xhci_triad_to_transfer_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct xhci_ring *xhci_triad_to_transfer_ring(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffe000695536)
Location: drivers/usb/host/xhci-ring.c:447
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
```
**Symbols:**

```
ffffffe000695536-ffffffe0006955f4: xhci_triad_to_transfer_ring (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct xhci_ring *xhci_triad_to_transfer_ring(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817fc748)
Location: drivers/usb/host/xhci-ring.c:447
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
```
**Symbols:**

```
ffffffff817fc748-ffffffff817fc789: xhci_triad_to_transfer_ring.cold (STB_LOCAL)
ffffffff817f8130-ffffffff817f8181: xhci_triad_to_transfer_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct xhci_ring *xhci_triad_to_transfer_ring(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817c18e8)
Location: drivers/usb/host/xhci-ring.c:447
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
```
**Symbols:**

```
ffffffff817c18e8-ffffffff817c1929: xhci_triad_to_transfer_ring.cold (STB_LOCAL)
ffffffff817bd2d0-ffffffff817bd321: xhci_triad_to_transfer_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct xhci_ring *xhci_triad_to_transfer_ring(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81839218)
Location: drivers/usb/host/xhci-ring.c:447
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
```
**Symbols:**

```
ffffffff81839218-ffffffff81839259: xhci_triad_to_transfer_ring.cold (STB_LOCAL)
ffffffff81834c00-ffffffff81834c51: xhci_triad_to_transfer_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct xhci_ring *xhci_triad_to_transfer_ring(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff8185366b)
Location: drivers/usb/host/xhci-ring.c:447
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
```
**Symbols:**

```
ffffffff8185366b-ffffffff818536ac: xhci_triad_to_transfer_ring.cold (STB_LOCAL)
ffffffff8184ef20-ffffffff8184ef71: xhci_triad_to_transfer_ring (STB_GLOBAL)
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
