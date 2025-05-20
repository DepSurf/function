# Function: <code>xhci_ring_ep_doorbell</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void xhci_ring_ep_doorbell(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81656d7f)
Location: drivers/usb/host/xhci-ring.c:325
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
```
**Symbols:**

```
ffffffff81657b70-ffffffff81657ba9: xhci_ring_ep_doorbell (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void xhci_ring_ep_doorbell(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816ba3c8)
Location: drivers/usb/host/xhci-ring.c:314
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
```
**Symbols:**

```
ffffffff816b82d0-ffffffff816b8312: xhci_ring_ep_doorbell (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void xhci_ring_ep_doorbell(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816e8638)
Location: drivers/usb/host/xhci-ring.c:398
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
```
**Symbols:**

```
ffffffff816e6660-ffffffff816e66a2: xhci_ring_ep_doorbell (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void xhci_ring_ep_doorbell(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816fc90a)
Location: drivers/usb/host/xhci-ring.c:397
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
```
**Symbols:**

```
ffffffff816fa7c0-ffffffff816fa7fe: xhci_ring_ep_doorbell (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void xhci_ring_ep_doorbell(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81769491)
Location: drivers/usb/host/xhci-ring.c:386
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
```
**Symbols:**

```
ffffffff81767300-ffffffff81767340: xhci_ring_ep_doorbell (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void xhci_ring_ep_doorbell(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817aa739)
Location: drivers/usb/host/xhci-ring.c:386
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
```
**Symbols:**

```
ffffffff817a85d0-ffffffff817a860f: xhci_ring_ep_doorbell (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void xhci_ring_ep_doorbell(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817d06e9)
Location: drivers/usb/host/xhci-ring.c:386
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
```
**Symbols:**

```
ffffffff817ce540-ffffffff817ce57f: xhci_ring_ep_doorbell (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void xhci_ring_ep_doorbell(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff8180e0f7)
Location: drivers/usb/host/xhci-ring.c:386
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
```
**Symbols:**

```
ffffffff8180ec10-ffffffff8180ec51: xhci_ring_ep_doorbell (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void xhci_ring_ep_doorbell(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff8183f1e7)
Location: drivers/usb/host/xhci-ring.c:386
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
```
**Symbols:**

```
ffffffff8183fd20-ffffffff8183fd61: xhci_ring_ep_doorbell (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xhci_ring_ep_doorbell(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81912de0)
Location: drivers/usb/host/xhci-ring.c:389
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
```
**Symbols:**

```
ffffffff81912de0-ffffffff81912e85: xhci_ring_ep_doorbell (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xhci_ring_ep_doorbell(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff8191a450)
Location: drivers/usb/host/xhci-ring.c:389
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
```
**Symbols:**

```
ffffffff8191a450-ffffffff8191a4d5: xhci_ring_ep_doorbell (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xhci_ring_ep_doorbell(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff818fd7a0)
Location: drivers/usb/host/xhci-ring.c:413
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
```
**Symbols:**

```
ffffffff818fd7a0-ffffffff818fd822: xhci_ring_ep_doorbell (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xhci_ring_ep_doorbell(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff8199c900)
Location: drivers/usb/host/xhci-ring.c:426
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
```
**Symbols:**

```
ffffffff8199c900-ffffffff8199c9f7: xhci_ring_ep_doorbell (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xhci_ring_ep_doorbell(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81af9e70)
Location: drivers/usb/host/xhci-ring.c:426
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
```
**Symbols:**

```
ffffffff81af9e70-ffffffff81af9f99: xhci_ring_ep_doorbell (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xhci_ring_ep_doorbell(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81c88150)
Location: drivers/usb/host/xhci-ring.c:426
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
```
**Symbols:**

```
ffffffff81c88150-ffffffff81c88279: xhci_ring_ep_doorbell (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xhci_ring_ep_doorbell(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81cef330)
Location: drivers/usb/host/xhci-ring.c:480
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
```
**Symbols:**

```
ffffffff81cef330-ffffffff81cef486: xhci_ring_ep_doorbell (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xhci_ring_ep_doorbell(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81da4b50)
Location: drivers/usb/host/xhci-ring.c:488
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
```
**Symbols:**

```
ffffffff81da4b50-ffffffff81da4ca6: xhci_ring_ep_doorbell (STB_GLOBAL)
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
void xhci_ring_ep_doorbell(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffff800010a7db58)
Location: drivers/usb/host/xhci-ring.c:386
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
```
**Symbols:**

```
ffff800010a7e6e0-ffff800010a7e75c: xhci_ring_ep_doorbell (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void xhci_ring_ep_doorbell(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c0b4f4ec)
Location: drivers/usb/host/xhci-ring.c:386
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:giveback_first_trb
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
```
**Symbols:**

```
c0b51bec-c0b51c50: xhci_ring_ep_doorbell (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void xhci_ring_ep_doorbell(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c000000000b56144)
Location: drivers/usb/host/xhci-ring.c:386
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
```
**Symbols:**

```
c000000000b56ff0-c000000000b5704c: xhci_ring_ep_doorbell (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void xhci_ring_ep_doorbell(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffe000692e7a)
Location: drivers/usb/host/xhci-ring.c:386
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
```
**Symbols:**

```
ffffffe000695460-ffffffe0006954fc: xhci_ring_ep_doorbell (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void xhci_ring_ep_doorbell(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817f7597)
Location: drivers/usb/host/xhci-ring.c:386
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
```
**Symbols:**

```
ffffffff817f80d0-ffffffff817f8111: xhci_ring_ep_doorbell (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void xhci_ring_ep_doorbell(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817bc737)
Location: drivers/usb/host/xhci-ring.c:386
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
```
**Symbols:**

```
ffffffff817bd270-ffffffff817bd2b1: xhci_ring_ep_doorbell (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void xhci_ring_ep_doorbell(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81834067)
Location: drivers/usb/host/xhci-ring.c:386
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
```
**Symbols:**

```
ffffffff81834ba0-ffffffff81834be1: xhci_ring_ep_doorbell (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void xhci_ring_ep_doorbell(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff8184e36a)
Location: drivers/usb/host/xhci-ring.c:386
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
  - drivers/usb/host/xhci-hub.c:xhci_ring_device
```
**Symbols:**

```
ffffffff8184eec0-ffffffff8184ef01: xhci_ring_ep_doorbell (STB_GLOBAL)
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
