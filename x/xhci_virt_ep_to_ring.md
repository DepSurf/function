# Function: <code>xhci_virt_ep_to_ring</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct xhci_ring *xhci_virt_ep_to_ring(struct xhci_hcd *xhci, struct xhci_virt_ep *ep, unsigned int stream_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81c13a3f)
Location: drivers/usb/host/xhci-ring.c:492
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds
```
**Symbols:**

```
ffffffff81c13a3f-ffffffff81c13a67: xhci_virt_ep_to_ring.part.0 (STB_LOCAL)
ffffffff818fb560-ffffffff818fb595: xhci_virt_ep_to_ring (STB_LOCAL)
ffffffff81c13a67-ffffffff81c13a72: xhci_virt_ep_to_ring.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct xhci_ring *xhci_virt_ep_to_ring(struct xhci_hcd *xhci, struct xhci_virt_ep *ep, unsigned int stream_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81d208ba)
Location: drivers/usb/host/xhci-ring.c:505
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds
```
**Symbols:**

```
ffffffff81d208ba-ffffffff81d208e2: xhci_virt_ep_to_ring.part.0 (STB_LOCAL)
ffffffff8199a3f0-ffffffff8199a425: xhci_virt_ep_to_ring (STB_LOCAL)
ffffffff81d208e2-ffffffff81d208ed: xhci_virt_ep_to_ring.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81afdf5f)
Location: drivers/usb/host/xhci-ring.c:505
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:prepare_transfer
  - drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:prepare_transfer
  - drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
```
**Symbols:**

```
ffffffff81af7490-ffffffff81af74d1: xhci_virt_ep_to_ring.part.0 (STB_LOCAL)
ffffffff81eec45c-ffffffff81eec47e: xhci_virt_ep_to_ring.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81c8ccff)
Location: drivers/usb/host/xhci-ring.c:505
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:prepare_transfer
  - drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:prepare_transfer
  - drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
```
**Symbols:**

```
ffffffff81c85000-ffffffff81c85074: xhci_virt_ep_to_ring.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81cf387f)
Location: drivers/usb/host/xhci-ring.c:559
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:prepare_transfer
  - drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:prepare_transfer
  - drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
```
**Symbols:**

```
ffffffff81cebcc0-ffffffff81cebd34: xhci_virt_ep_to_ring.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81da91bf)
Location: drivers/usb/host/xhci-ring.c:567
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:prepare_transfer
  - drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:prepare_transfer
  - drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
```
**Symbols:**

```
ffffffff81da12e0-ffffffff81da1354: xhci_virt_ep_to_ring.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
