# Function: <code>xhci_get_virt_ep</code>

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
struct xhci_virt_ep *xhci_get_virt_ep(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff818fda15)
Location: drivers/usb/host/xhci-ring.c:472
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:xhci_handle_cmd_reset_ep
  - drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds
```
**Symbols:**

```
ffffffff818fb1e0-ffffffff818fb227: xhci_get_virt_ep (STB_LOCAL)
ffffffff81c139b0-ffffffff81c13a05: xhci_get_virt_ep.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct xhci_virt_ep *xhci_get_virt_ep(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff8199cca5)
Location: drivers/usb/host/xhci-ring.c:485
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:xhci_handle_cmd_reset_ep
  - drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds
```
**Symbols:**

```
ffffffff8199a050-ffffffff8199a111: xhci_get_virt_ep (STB_LOCAL)
ffffffff81d2082a-ffffffff81d20880: xhci_get_virt_ep.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct xhci_virt_ep *xhci_get_virt_ep(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81afacb5)
Location: drivers/usb/host/xhci-ring.c:485
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:prepare_transfer
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
```
**Symbols:**

```
ffffffff81af70b0-ffffffff81af716f: xhci_get_virt_ep (STB_LOCAL)
ffffffff81eec3dd-ffffffff81eec423: xhci_get_virt_ep.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct xhci_virt_ep *xhci_get_virt_ep(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81c84b60)
Location: drivers/usb/host/xhci-ring.c:485
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:prepare_transfer
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
```
**Symbols:**

```
ffffffff81c84b60-ffffffff81c84c6b: xhci_get_virt_ep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct xhci_virt_ep *xhci_get_virt_ep(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81ceb820)
Location: drivers/usb/host/xhci-ring.c:539
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:prepare_transfer
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
```
**Symbols:**

```
ffffffff81ceb820-ffffffff81ceb92b: xhci_get_virt_ep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct xhci_virt_ep *xhci_get_virt_ep(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81da0e40)
Location: drivers/usb/host/xhci-ring.c:547
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:prepare_transfer
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
```
**Symbols:**

```
ffffffff81da0e40-ffffffff81da0f4b: xhci_get_virt_ep (STB_LOCAL)
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
