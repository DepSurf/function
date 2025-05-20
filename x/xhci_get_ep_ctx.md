# Function: <code>xhci_get_ep_ctx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct xhci_ep_ctx *xhci_get_ep_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81653d80)
Location: drivers/usb/host/xhci-mem.c:557
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_zero
  - drivers/usb/host/xhci-mem.c:xhci_update_bw_info
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci-ring.c:prepare_transfer
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:finish_td
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-dbg.c:xhci_dbg_ctx
```
**Symbols:**

```
ffffffff81653d80-ffffffff81653daf: xhci_get_ep_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct xhci_ep_ctx *xhci_get_ep_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816b5676)
Location: drivers/usb/host/xhci-mem.c:569
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_update_bw_info
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_zero
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
  - drivers/usb/host/xhci-ring.c:prepare_transfer
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-dbg.c:xhci_dbg_ctx
```
**Symbols:**

```
ffffffff816b4810-ffffffff816b483f: xhci_get_ep_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct xhci_ep_ctx *xhci_get_ep_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816e3826)
Location: drivers/usb/host/xhci-mem.c:569
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_update_bw_info
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_zero
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
  - drivers/usb/host/xhci-ring.c:prepare_transfer
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-dbg.c:xhci_dbg_ctx
```
**Symbols:**

```
ffffffff816e29c0-ffffffff816e29ef: xhci_get_ep_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct xhci_ep_ctx *xhci_get_ep_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816f7866)
Location: drivers/usb/host/xhci-mem.c:523
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_update_bw_info
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_zero
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
  - drivers/usb/host/xhci-ring.c:prepare_transfer
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
```
**Symbols:**

```
ffffffff816f6ac0-ffffffff816f6aef: xhci_get_ep_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct xhci_ep_ctx *xhci_get_ep_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817645a6)
Location: drivers/usb/host/xhci-mem.c:510
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_update_bw_info
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_zero
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
  - drivers/usb/host/xhci-ring.c:prepare_transfer
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
```
**Symbols:**

```
ffffffff81763530-ffffffff8176355f: xhci_get_ep_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct xhci_ep_ctx *xhci_get_ep_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817a4815)
Location: drivers/usb/host/xhci-mem.c:514
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_update_bw_info
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_zero
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
  - drivers/usb/host/xhci-ring.c:prepare_transfer
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
```
**Symbols:**

```
ffffffff817a3780-ffffffff817a37af: xhci_get_ep_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct xhci_ep_ctx *xhci_get_ep_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817caba5)
Location: drivers/usb/host/xhci-mem.c:514
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_update_bw_info
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_zero
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
  - drivers/usb/host/xhci-ring.c:prepare_transfer
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
```
**Symbols:**

```
ffffffff817c9aa0-ffffffff817c9acf: xhci_get_ep_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct xhci_ep_ctx *xhci_get_ep_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8180af95)
Location: drivers/usb/host/xhci-mem.c:514
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_update_bw_info
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_zero
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
  - drivers/usb/host/xhci-ring.c:prepare_transfer
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
```
**Symbols:**

```
ffffffff81809ec0-ffffffff81809eef: xhci_get_ep_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct xhci_ep_ctx *xhci_get_ep_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8183bf55)
Location: drivers/usb/host/xhci-mem.c:514
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_update_bw_info
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_zero
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
  - drivers/usb/host/xhci-ring.c:prepare_transfer
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
```
**Symbols:**

```
ffffffff8183ae40-ffffffff8183ae6f: xhci_get_ep_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct xhci_ep_ctx *xhci_get_ep_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8190ed25)
Location: drivers/usb/host/xhci-mem.c:514
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_update_bw_info
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_zero
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_setup_input_ctx_for_quirk
  - drivers/usb/host/xhci.c:xhci_zero_in_ctx
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
  - drivers/usb/host/xhci-ring.c:prepare_transfer
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:xhci_handle_cmd_reset_ep
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
```
**Symbols:**

```
ffffffff8190d890-ffffffff8190d8bf: xhci_get_ep_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct xhci_ep_ctx *xhci_get_ep_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81916893)
Location: drivers/usb/host/xhci-mem.c:523
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_update_bw_info
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_zero
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_setup_input_ctx_for_quirk
  - drivers/usb/host/xhci.c:xhci_zero_in_ctx
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
  - drivers/usb/host/xhci-ring.c:prepare_transfer
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:xhci_handle_cmd_reset_ep
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
```
**Symbols:**

```
ffffffff81915430-ffffffff8191545f: xhci_get_ep_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct xhci_ep_ctx *xhci_get_ep_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff818f9d13)
Location: drivers/usb/host/xhci-mem.c:523
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_update_bw_info
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_zero
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_zero_in_ctx
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
  - drivers/usb/host/xhci-ring.c:prepare_transfer
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:xhci_handle_cmd_reset_ep
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
```
**Symbols:**

```
ffffffff818f6b90-ffffffff818f6bbf: xhci_get_ep_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct xhci_ep_ctx *xhci_get_ep_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff819989a3)
Location: drivers/usb/host/xhci-mem.c:523
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_update_bw_info
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_zero
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_zero_in_ctx
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
  - drivers/usb/host/xhci-ring.c:prepare_transfer
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:xhci_handle_cmd_reset_ep
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
```
**Symbols:**

```
ffffffff81994fb0-ffffffff81994fdf: xhci_get_ep_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct xhci_ep_ctx *xhci_get_ep_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81af596f)
Location: drivers/usb/host/xhci-mem.c:522
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_update_bw_info
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_zero
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_zero_in_ctx
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
  - drivers/usb/host/xhci-ring.c:prepare_transfer
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
```
**Symbols:**

```
ffffffff81af1c50-ffffffff81af1c88: xhci_get_ep_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct xhci_ep_ctx *xhci_get_ep_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81c8321f)
Location: drivers/usb/host/xhci-mem.c:522
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_update_bw_info
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_zero
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_zero_in_ctx
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
  - drivers/usb/host/xhci-ring.c:prepare_transfer
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
```
**Symbols:**

```
ffffffff81c7ee30-ffffffff81c7ee68: xhci_get_ep_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct xhci_ep_ctx *xhci_get_ep_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81ce9f5f)
Location: drivers/usb/host/xhci-mem.c:514
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_update_bw_info
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_zero
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_zero_in_ctx
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
  - drivers/usb/host/xhci-ring.c:prepare_transfer
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
```
**Symbols:**

```
ffffffff81ce60b0-ffffffff81ce60e8: xhci_get_ep_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct xhci_ep_ctx *xhci_get_ep_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81d9f78f)
Location: drivers/usb/host/xhci-mem.c:525
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_update_bw_info
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_zero
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_zero_in_ctx
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
  - drivers/usb/host/xhci-ring.c:prepare_transfer
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
```
**Symbols:**

```
ffffffff81d9b1b0-ffffffff81d9b1e8: xhci_get_ep_ctx (STB_GLOBAL)
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
struct xhci_ep_ctx *xhci_get_ep_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffff800010a79cd0)
Location: drivers/usb/host/xhci-mem.c:514
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_update_bw_info
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_zero
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
  - drivers/usb/host/xhci-ring.c:prepare_transfer
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_add_ep_quirk
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
```
**Symbols:**

```
ffff800010a789c8-ffff800010a78a28: xhci_get_ep_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct xhci_ep_ctx *xhci_get_ep_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c0b4d6cc)
Location: drivers/usb/host/xhci-mem.c:514
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_update_bw_info
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_zero
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
  - drivers/usb/host/xhci-ring.c:prepare_transfer
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_cmd_set_deq
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_add_ep_quirk
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
```
**Symbols:**

```
c0b4c590-c0b4c5d0: xhci_get_ep_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct xhci_ep_ctx *xhci_get_ep_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c000000000b51408)
Location: drivers/usb/host/xhci-mem.c:514
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_update_bw_info
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_zero
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
  - drivers/usb/host/xhci-ring.c:prepare_transfer
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
```
**Symbols:**

```
c000000000b4fe30-c000000000b4fe8c: xhci_get_ep_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct xhci_ep_ctx *xhci_get_ep_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffe0006914a4)
Location: drivers/usb/host/xhci-mem.c:514
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_update_bw_info
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_zero
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
  - drivers/usb/host/xhci-ring.c:prepare_transfer
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
```
**Symbols:**

```
ffffffe000690440-ffffffe00069049a: xhci_get_ep_ctx (STB_GLOBAL)
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
struct xhci_ep_ctx *xhci_get_ep_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817f4305)
Location: drivers/usb/host/xhci-mem.c:514
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_update_bw_info
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_zero
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
  - drivers/usb/host/xhci-ring.c:prepare_transfer
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
```
**Symbols:**

```
ffffffff817f31f0-ffffffff817f321f: xhci_get_ep_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct xhci_ep_ctx *xhci_get_ep_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817b94a5)
Location: drivers/usb/host/xhci-mem.c:514
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_update_bw_info
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_zero
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
  - drivers/usb/host/xhci-ring.c:prepare_transfer
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
```
**Symbols:**

```
ffffffff817b8390-ffffffff817b83bf: xhci_get_ep_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct xhci_ep_ctx *xhci_get_ep_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81830dd5)
Location: drivers/usb/host/xhci-mem.c:514
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_update_bw_info
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_zero
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
  - drivers/usb/host/xhci-ring.c:prepare_transfer
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
```
**Symbols:**

```
ffffffff8182fcc0-ffffffff8182fcef: xhci_get_ep_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct xhci_ep_ctx *xhci_get_ep_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8184afa5)
Location: drivers/usb/host/xhci-mem.c:514
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_copy
  - drivers/usb/host/xhci-mem.c:xhci_update_bw_info
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_zero
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
  - drivers/usb/host/xhci-ring.c:prepare_transfer
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
```
**Symbols:**

```
ffffffff81849e60-ffffffff81849e8f: xhci_get_ep_ctx (STB_GLOBAL)
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
