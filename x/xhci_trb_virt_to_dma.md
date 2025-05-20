# Function: <code>xhci_trb_virt_to_dma</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment *seg, union xhci_trb *trb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816577e0)
Location: drivers/usb/host/xhci-ring.c:76
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:td_to_noop
  - drivers/usb/host/xhci-ring.c:td_to_noop
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:xhci_irq
Direct callers:
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-ring.c:td_to_noop
  - drivers/usb/host/xhci-ring.c:td_to_noop
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-dbg.c:xhci_dbg_ring_ptrs
  - drivers/usb/host/xhci-dbg.c:xhci_dbg_ring_ptrs
```
**Symbols:**

```
ffffffff816577e0-ffffffff81657808: xhci_trb_virt_to_dma.part.33 (STB_LOCAL)
ffffffff81657b30-ffffffff81657b4d: xhci_trb_virt_to_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment *seg, union xhci_trb *trb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816ba7a0)
Location: drivers/usb/host/xhci-ring.c:78
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
Direct callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-dbg.c:xhci_dbg_ring_ptrs
  - drivers/usb/host/xhci-dbg.c:xhci_dbg_ring_ptrs
```
**Symbols:**

```
ffffffff816b7f70-ffffffff816b7f98: xhci_trb_virt_to_dma.part.41 (STB_LOCAL)
ffffffff816b8290-ffffffff816b82ad: xhci_trb_virt_to_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment *seg, union xhci_trb *trb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816e8a10)
Location: drivers/usb/host/xhci-ring.c:78
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
Direct callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-dbg.c:xhci_dbg_ring_ptrs
  - drivers/usb/host/xhci-dbg.c:xhci_dbg_ring_ptrs
```
**Symbols:**

```
ffffffff816e6210-ffffffff816e6238: xhci_trb_virt_to_dma.part.48 (STB_LOCAL)
ffffffff816e6620-ffffffff816e663d: xhci_trb_virt_to_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment *seg, union xhci_trb *trb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816fcc70)
Location: drivers/usb/host/xhci-ring.c:78
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
Direct callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring
```
**Symbols:**

```
ffffffff816f9f90-ffffffff816f9fb8: xhci_trb_virt_to_dma.part.52 (STB_LOCAL)
ffffffff816fa780-ffffffff816fa79d: xhci_trb_virt_to_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment *seg, union xhci_trb *trb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817697f0)
Location: drivers/usb/host/xhci-ring.c:66
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
Direct callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_dequeue_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_enqueue_show
```
**Symbols:**

```
ffffffff817669d0-ffffffff817669f8: xhci_trb_virt_to_dma.part.45 (STB_LOCAL)
ffffffff817671c0-ffffffff817671dd: xhci_trb_virt_to_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment *seg, union xhci_trb *trb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817aaab0)
Location: drivers/usb/host/xhci-ring.c:66
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
Direct callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_dequeue_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_enqueue_show
```
**Symbols:**

```
ffffffff817a7eb0-ffffffff817a7ee6: xhci_trb_virt_to_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment *seg, union xhci_trb *trb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817d0a60)
Location: drivers/usb/host/xhci-ring.c:66
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
Direct callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_dequeue_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_enqueue_show
```
**Symbols:**

```
ffffffff817cdd80-ffffffff817cddb6: xhci_trb_virt_to_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment *seg, union xhci_trb *trb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff818107fe)
Location: drivers/usb/host/xhci-ring.c:66
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
Direct callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_dequeue_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_enqueue_show
```
**Symbols:**

```
ffffffff8180e440-ffffffff8180e476: xhci_trb_virt_to_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment *seg, union xhci_trb *trb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff818419ee)
Location: drivers/usb/host/xhci-ring.c:66
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
Direct callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_dequeue_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_enqueue_show
```
**Symbols:**

```
ffffffff8183f530-ffffffff8183f566: xhci_trb_virt_to_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment *seg, union xhci_trb *trb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81915c02)
Location: drivers/usb/host/xhci-ring.c:66
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_input_ctx_for_quirk
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_dequeue_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_enqueue_show
```
**Symbols:**

```
ffffffff81911e90-ffffffff81911ec6: xhci_trb_virt_to_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment *seg, union xhci_trb *trb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff8191d1f2)
Location: drivers/usb/host/xhci-ring.c:66
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_input_ctx_for_quirk
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_dequeue_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_enqueue_show
```
**Symbols:**

```
ffffffff81919500-ffffffff81919536: xhci_trb_virt_to_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment *seg, union xhci_trb *trb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff818fc4f6)
Location: drivers/usb/host/xhci-ring.c:69
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_dequeue_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_enqueue_show
```
**Symbols:**

```
ffffffff818fc560-ffffffff818fc596: xhci_trb_virt_to_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment *seg, union xhci_trb *trb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff8199b406)
Location: drivers/usb/host/xhci-ring.c:69
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_dequeue_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_enqueue_show
```
**Symbols:**

```
ffffffff8199b470-ffffffff8199b4a6: xhci_trb_virt_to_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment *seg, union xhci_trb *trb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81af8be6)
Location: drivers/usb/host/xhci-ring.c:69
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_dequeue_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_enqueue_show
```
**Symbols:**

```
ffffffff81af8c60-ffffffff81af8caa: xhci_trb_virt_to_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment *seg, union xhci_trb *trb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81c86bd6)
Location: drivers/usb/host/xhci-ring.c:69
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_dequeue_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_enqueue_show
```
**Symbols:**

```
ffffffff81c86c60-ffffffff81c86caa: xhci_trb_virt_to_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment *seg, union xhci_trb *trb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81ceda06)
Location: drivers/usb/host/xhci-ring.c:69
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_dequeue_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_enqueue_show
```
**Symbols:**

```
ffffffff81cedf90-ffffffff81cedfda: xhci_trb_virt_to_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment *seg, union xhci_trb *trb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81da37c7)
Location: drivers/usb/host/xhci-ring.c:69
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci-mem.c:xhci_add_interrupter
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_dequeue_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_enqueue_show
```
**Symbols:**

```
ffffffff81da3d80-ffffffff81da3dca: xhci_trb_virt_to_dma (STB_GLOBAL)
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
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment *seg, union xhci_trb *trb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffff800010a80880)
Location: drivers/usb/host/xhci-ring.c:66
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
Direct callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_dequeue_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_enqueue_show
```
**Symbols:**

```
ffff800010a7dd50-ffff800010a7ddac: xhci_trb_virt_to_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment *seg, union xhci_trb *trb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c0b53b88)
Location: drivers/usb/host/xhci-ring.c:66
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_cmd_set_deq
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
Direct callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_dequeue_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_enqueue_show
```
**Symbols:**

```
c0b512c0-c0b51318: xhci_trb_virt_to_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment *seg, union xhci_trb *trb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c000000000b596ac)
Location: drivers/usb/host/xhci-ring.c:66
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
Direct callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_dequeue_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_enqueue_show
```
**Symbols:**

```
c000000000b56430-c000000000b56478: xhci_trb_virt_to_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment *seg, union xhci_trb *trb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffe000697108)
Location: drivers/usb/host/xhci-ring.c:66
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
Direct callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_dequeue_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_enqueue_show
```
**Symbols:**

```
ffffffe000694bcc-ffffffe000694c24: xhci_trb_virt_to_dma (STB_GLOBAL)
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
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment *seg, union xhci_trb *trb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817f9d9e)
Location: drivers/usb/host/xhci-ring.c:66
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
Direct callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_dequeue_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_enqueue_show
```
**Symbols:**

```
ffffffff817f78e0-ffffffff817f7916: xhci_trb_virt_to_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment *seg, union xhci_trb *trb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817bef3e)
Location: drivers/usb/host/xhci-ring.c:66
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
Direct callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_dequeue_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_enqueue_show
```
**Symbols:**

```
ffffffff817bca80-ffffffff817bcab6: xhci_trb_virt_to_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment *seg, union xhci_trb *trb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff8183686e)
Location: drivers/usb/host/xhci-ring.c:66
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
Direct callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_dequeue_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_enqueue_show
```
**Symbols:**

```
ffffffff818343b0-ffffffff818343e6: xhci_trb_virt_to_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment *seg, union xhci_trb *trb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81850bee)
Location: drivers/usb/host/xhci-ring.c:66
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:trb_in_td
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
Direct callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td
  - drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_dequeue_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_enqueue_show
```
**Symbols:**

```
ffffffff8184e6b0-ffffffff8184e6e6: xhci_trb_virt_to_dma (STB_GLOBAL)
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
