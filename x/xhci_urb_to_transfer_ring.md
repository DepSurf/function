# Function: <code>xhci_urb_to_transfer_ring</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
struct xhci_ring *xhci_urb_to_transfer_ring(struct xhci_hcd *xhci, struct urb *urb);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8164be89)
Location: drivers/usb/host/xhci.c:1460
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81657660)
Location: drivers/usb/host/xhci-ring.c:411
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff81657660-ffffffff8165769f: xhci_urb_to_transfer_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816ac825)
Location: drivers/usb/host/xhci.h:1982
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816b9992)
Location: drivers/usb/host/xhci.h:1982
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816da94c)
Location: drivers/usb/host/xhci.h:1979
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816e7c02)
Location: drivers/usb/host/xhci.h:1979
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816eec1c)
Location: drivers/usb/host/xhci.h:2101
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816fbd3f)
Location: drivers/usb/host/xhci.h:2101
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8175b46c)
Location: drivers/usb/host/xhci.h:2124
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817688af)
Location: drivers/usb/host/xhci.h:2124
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8179bd6d)
Location: drivers/usb/host/xhci.h:2136
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817a9b25)
Location: drivers/usb/host/xhci.h:2136
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817c212d)
Location: drivers/usb/host/xhci.h:2144
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817cfad5)
Location: drivers/usb/host/xhci.h:2144
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81801adc)
Location: drivers/usb/host/xhci.h:2160
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8180ffbc)
Location: drivers/usb/host/xhci.h:2160
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81832d0c)
Location: drivers/usb/host/xhci.h:2170
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-ring.c (ffffffff818411ac)
Location: drivers/usb/host/xhci.h:2170
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81906342)
Location: drivers/usb/host/xhci.h:2173
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81915548)
Location: drivers/usb/host/xhci.h:2173
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8190eaeb)
Location: drivers/usb/host/xhci.h:2188
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8191cb38)
Location: drivers/usb/host/xhci.h:2188
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff818f2029)
Location: drivers/usb/host/xhci.h:2194
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81900f9c)
Location: drivers/usb/host/xhci.h:2194
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8198f21a)
Location: drivers/usb/host/xhci.h:2201
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-ring.c (ffffffff819a07bc)
Location: drivers/usb/host/xhci.h:2201
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81aeb6c2)
Location: drivers/usb/host/xhci.h:2228
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81afdf3d)
Location: drivers/usb/host/xhci.h:2228
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81c77c52)
Location: drivers/usb/host/xhci.h:2229
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81c8ccdd)
Location: drivers/usb/host/xhci.h:2229
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81cded32)
Location: drivers/usb/host/xhci.h:2239
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81cf385d)
Location: drivers/usb/host/xhci.h:2239
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81d93cb2)
Location: drivers/usb/host/xhci.h:2216
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81da919d)
Location: drivers/usb/host/xhci.h:2216
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffff800010a7019c)
Location: drivers/usb/host/xhci.h:2170
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-ring.c (ffff800010a7fef0)
Location: drivers/usb/host/xhci.h:2170
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c0b43570)
Location: drivers/usb/host/xhci.h:2170
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-ring.c (c0b532f8)
Location: drivers/usb/host/xhci.h:2170
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c000000000b446c0)
Location: drivers/usb/host/xhci.h:2170
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-ring.c (c000000000b58c4c)
Location: drivers/usb/host/xhci.h:2170
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffe000688458)
Location: drivers/usb/host/xhci.h:2170
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-ring.c (ffffffe0006968ce)
Location: drivers/usb/host/xhci.h:2170
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817eb0ec)
Location: drivers/usb/host/xhci.h:2170
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817f955c)
Location: drivers/usb/host/xhci.h:2170
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817b01fc)
Location: drivers/usb/host/xhci.h:2170
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817be6fc)
Location: drivers/usb/host/xhci.h:2170
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81827b8c)
Location: drivers/usb/host/xhci.h:2170
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8183602c)
Location: drivers/usb/host/xhci.h:2170
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81841b2c)
Location: drivers/usb/host/xhci.h:2170
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8185037c)
Location: drivers/usb/host/xhci.h:2170
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
