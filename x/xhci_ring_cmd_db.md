# Function: <code>xhci_ring_cmd_db</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_ring_cmd_db(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816579b0)
Location: drivers/usb/host/xhci-ring.c:272
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:finish_td
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:finish_td
```
**Symbols:**

```
ffffffff816579b0-ffffffff816579f2: xhci_ring_cmd_db.part.34 (STB_LOCAL)
ffffffff81657b50-ffffffff81657b6a: xhci_ring_cmd_db (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_ring_cmd_db(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816bb0bf)
Location: drivers/usb/host/xhci-ring.c:252
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
**Symbols:**

```
ffffffff816b7fa0-ffffffff816b7fde: xhci_ring_cmd_db.part.42 (STB_LOCAL)
ffffffff816b82b0-ffffffff816b82ca: xhci_ring_cmd_db (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_ring_cmd_db(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816e939e)
Location: drivers/usb/host/xhci-ring.c:271
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
**Symbols:**

```
ffffffff816e6240-ffffffff816e627e: xhci_ring_cmd_db.part.49 (STB_LOCAL)
ffffffff816e6640-ffffffff816e665a: xhci_ring_cmd_db (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_ring_cmd_db(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816fd6c7)
Location: drivers/usb/host/xhci-ring.c:288
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
**Symbols:**

```
ffffffff816f9fc0-ffffffff816f9ffe: xhci_ring_cmd_db.part.53 (STB_LOCAL)
ffffffff816fa7a0-ffffffff816fa7bb: xhci_ring_cmd_db (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_ring_cmd_db(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff8176a237)
Location: drivers/usb/host/xhci-ring.c:277
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
**Symbols:**

```
ffffffff81766a00-ffffffff81766a3e: xhci_ring_cmd_db.part.48 (STB_LOCAL)
ffffffff817672e0-ffffffff817672fb: xhci_ring_cmd_db (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_ring_cmd_db(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817ab923)
Location: drivers/usb/host/xhci-ring.c:277
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
**Symbols:**

```
ffffffff817a7620-ffffffff817a765e: xhci_ring_cmd_db.part.48 (STB_LOCAL)
ffffffff817a85b0-ffffffff817a85ca: xhci_ring_cmd_db (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_ring_cmd_db(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817d1987)
Location: drivers/usb/host/xhci-ring.c:277
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
**Symbols:**

```
ffffffff817cd4d0-ffffffff817cd50e: xhci_ring_cmd_db.part.50 (STB_LOCAL)
ffffffff817ce520-ffffffff817ce53a: xhci_ring_cmd_db (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_ring_cmd_db(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81811542)
Location: drivers/usb/host/xhci-ring.c:277
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
**Symbols:**

```
ffffffff8180d270-ffffffff8180d2ae: xhci_ring_cmd_db.part.0 (STB_LOCAL)
ffffffff8180ebf0-ffffffff8180ec0a: xhci_ring_cmd_db (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_ring_cmd_db(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81842733)
Location: drivers/usb/host/xhci-ring.c:277
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
**Symbols:**

```
ffffffff8183e360-ffffffff8183e39e: xhci_ring_cmd_db.part.0 (STB_LOCAL)
ffffffff8183fd00-ffffffff8183fd1a: xhci_ring_cmd_db (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_ring_cmd_db(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81911a0d)
Location: drivers/usb/host/xhci-ring.c:277
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_cleanup_halted_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_handle_cmd_reset_ep
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-ring.c:xhci_cleanup_halted_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_handle_cmd_reset_ep
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
**Symbols:**

```
ffffffff81911120-ffffffff819111a6: xhci_ring_cmd_db.part.0 (STB_LOCAL)
ffffffff81912dc0-ffffffff81912dda: xhci_ring_cmd_db (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_ring_cmd_db(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff8191941d)
Location: drivers/usb/host/xhci-ring.c:277
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_cleanup_halted_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_handle_cmd_reset_ep
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-ring.c:xhci_cleanup_halted_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_handle_cmd_reset_ep
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
**Symbols:**

```
ffffffff819188a0-ffffffff81918914: xhci_ring_cmd_db.part.0 (STB_LOCAL)
ffffffff8191a430-ffffffff8191a44a: xhci_ring_cmd_db (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void xhci_ring_cmd_db(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff818fcd50)
Location: drivers/usb/host/xhci-ring.c:301
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
**Symbols:**

```
ffffffff818fcd50-ffffffff818fcdce: xhci_ring_cmd_db (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void xhci_ring_cmd_db(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff8199be60)
Location: drivers/usb/host/xhci-ring.c:301
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
**Symbols:**

```
ffffffff8199be60-ffffffff8199bed8: xhci_ring_cmd_db (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_ring_cmd_db(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81afb79d)
Location: drivers/usb/host/xhci-ring.c:301
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_run_finished
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
**Symbols:**

```
ffffffff81af7c80-ffffffff81af7d0f: xhci_ring_cmd_db.part.0 (STB_LOCAL)
ffffffff81af9e40-ffffffff81af9e66: xhci_ring_cmd_db (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_ring_cmd_db(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81c86777)
Location: drivers/usb/host/xhci-ring.c:301
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_halted_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_run_finished
  - drivers/usb/host/xhci-ring.c:xhci_handle_halted_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
**Symbols:**

```
ffffffff81c859d0-ffffffff81c85a5f: xhci_ring_cmd_db.part.0 (STB_LOCAL)
ffffffff81c88110-ffffffff81c88136: xhci_ring_cmd_db (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_ring_cmd_db(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81ced5a7)
Location: drivers/usb/host/xhci-ring.c:355
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_halted_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_run_finished
  - drivers/usb/host/xhci-ring.c:xhci_handle_halted_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
**Symbols:**

```
ffffffff81cec820-ffffffff81cec8af: xhci_ring_cmd_db.part.0 (STB_LOCAL)
ffffffff81cef2f0-ffffffff81cef316: xhci_ring_cmd_db (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_ring_cmd_db(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81da3367)
Location: drivers/usb/host/xhci-ring.c:361
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_halted_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_run_finished
  - drivers/usb/host/xhci-ring.c:xhci_handle_halted_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
**Symbols:**

```
ffffffff81da1e60-ffffffff81da1eef: xhci_ring_cmd_db.part.0 (STB_LOCAL)
ffffffff81da4b10-ffffffff81da4b36: xhci_ring_cmd_db (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_ring_cmd_db(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffff800010a8166c)
Location: drivers/usb/host/xhci-ring.c:277
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
**Symbols:**

```
ffff800010a7c558-ffff800010a7c5c4: xhci_ring_cmd_db.part.0 (STB_LOCAL)
ffff800010a7e6a8-ffff800010a7e6dc: xhci_ring_cmd_db (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_ring_cmd_db(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c0b54a3c)
Location: drivers/usb/host/xhci-ring.c:277
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
**Symbols:**

```
c0b50164-c0b501cc: xhci_ring_cmd_db.part.0 (STB_LOCAL)
c0b51bc4-c0b51bec: xhci_ring_cmd_db (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_ring_cmd_db(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c000000000b5a9a8)
Location: drivers/usb/host/xhci-ring.c:277
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
**Symbols:**

```
c000000000b552c0-c000000000b553c4: xhci_ring_cmd_db.part.0 (STB_LOCAL)
c000000000b56fd0-c000000000b56ff0: xhci_ring_cmd_db (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_ring_cmd_db(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffe000697c6e)
Location: drivers/usb/host/xhci-ring.c:277
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
**Symbols:**

```
ffffffe000693700-ffffffe000693786: xhci_ring_cmd_db.part.0 (STB_LOCAL)
ffffffe00069542e-ffffffe000695460: xhci_ring_cmd_db (STB_GLOBAL)
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
void xhci_ring_cmd_db(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817faae3)
Location: drivers/usb/host/xhci-ring.c:277
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
**Symbols:**

```
ffffffff817f6710-ffffffff817f674e: xhci_ring_cmd_db.part.0 (STB_LOCAL)
ffffffff817f80b0-ffffffff817f80ca: xhci_ring_cmd_db (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_ring_cmd_db(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817bfc83)
Location: drivers/usb/host/xhci-ring.c:277
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
**Symbols:**

```
ffffffff817bb8b0-ffffffff817bb8ee: xhci_ring_cmd_db.part.0 (STB_LOCAL)
ffffffff817bd250-ffffffff817bd26a: xhci_ring_cmd_db (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_ring_cmd_db(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff818375b3)
Location: drivers/usb/host/xhci-ring.c:277
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
**Symbols:**

```
ffffffff818331e0-ffffffff8183321e: xhci_ring_cmd_db.part.0 (STB_LOCAL)
ffffffff81834b80-ffffffff81834b9a: xhci_ring_cmd_db (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_ring_cmd_db(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff818519d4)
Location: drivers/usb/host/xhci-ring.c:277
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
**Symbols:**

```
ffffffff8184d570-ffffffff8184d5ae: xhci_ring_cmd_db.part.0 (STB_LOCAL)
ffffffff8184eea0-ffffffff8184eeba: xhci_ring_cmd_db (STB_GLOBAL)
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
