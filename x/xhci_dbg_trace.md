# Function: <code>xhci_dbg_trace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void xhci_dbg_trace(struct xhci_hcd *xhci, void (*trace)(struct va_format *), const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbg.c (ffffffff8165f920)
Location: drivers/usb/host/xhci-dbg.c:601
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_host_resources
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_free_device_endpoint_resources
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-ring.c:prepare_ring
  - drivers/usb/host/xhci-ring.c:td_to_noop
  - drivers/usb/host/xhci-ring.c:td_to_noop
  - drivers/usb/host/xhci-ring.c:td_to_noop
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
```
**Symbols:**

```
ffffffff8165f920-ffffffff8165f9c1: xhci_dbg_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xhci_dbg_trace(struct xhci_hcd *xhci, void (*trace)(struct va_format *), const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbg.c (ffffffff816bff10)
Location: drivers/usb/host/xhci-dbg.c:601
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_device_endpoint_resources
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_free_host_resources
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:prepare_ring
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
```
**Symbols:**

```
ffffffff816bff10-ffffffff816bffb8: xhci_dbg_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xhci_dbg_trace(struct xhci_hcd *xhci, void (*trace)(struct va_format *), const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbg.c (ffffffff816ede80)
Location: drivers/usb/host/xhci-dbg.c:601
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_device_endpoint_resources
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_free_host_resources
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:xhci_setup_msix
  - drivers/usb/host/xhci.c:xhci_setup_msix
  - drivers/usb/host/xhci.c:xhci_halt
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:prepare_ring
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
```
**Symbols:**

```
ffffffff816ede80-ffffffff816edf28: xhci_dbg_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xhci_dbg_trace(struct xhci_hcd *xhci, void (*trace)(struct va_format *), const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbg.c (ffffffff817027f0)
Location: drivers/usb/host/xhci-dbg.c:295
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_device_endpoint_resources
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_free_host_resources
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:prepare_ring
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
```
**Symbols:**

```
ffffffff817027f0-ffffffff81702893: xhci_dbg_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xhci_dbg_trace(struct xhci_hcd *xhci, void (*trace)(struct va_format *), const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbg.c (ffffffff8176f550)
Location: drivers/usb/host/xhci-dbg.c:283
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_device_endpoint_resources
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_free_host_resources
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:prepare_ring
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
```
**Symbols:**

```
ffffffff8176f550-ffffffff8176f5f5: xhci_dbg_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xhci_dbg_trace(struct xhci_hcd *xhci, void (*trace)(struct va_format *), const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbg.c (ffffffff817b0500)
Location: drivers/usb/host/xhci-dbg.c:22
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_device_endpoint_resources
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_free_host_resources
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:prepare_ring
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
```
**Symbols:**

```
ffffffff817b0500-ffffffff817b05aa: xhci_dbg_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xhci_dbg_trace(struct xhci_hcd *xhci, void (*trace)(struct va_format *), const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbg.c (ffffffff817d6a80)
Location: drivers/usb/host/xhci-dbg.c:22
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_device_endpoint_resources
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_free_host_resources
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:prepare_ring
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
```
**Symbols:**

```
ffffffff817d6a80-ffffffff817d6b2a: xhci_dbg_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xhci_dbg_trace(struct xhci_hcd *xhci, void (*trace)(struct va_format *), const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbg.c (ffffffff81817030)
Location: drivers/usb/host/xhci-dbg.c:22
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_device_endpoint_resources
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_free_host_resources
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:prepare_ring
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
```
**Symbols:**

```
ffffffff81817030-ffffffff818170da: xhci_dbg_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xhci_dbg_trace(struct xhci_hcd *xhci, void (*trace)(struct va_format *), const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbg.c (ffffffff81848370)
Location: drivers/usb/host/xhci-dbg.c:22
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_device_endpoint_resources
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_free_host_resources
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:prepare_ring
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
```
**Symbols:**

```
ffffffff81848370-ffffffff8184841a: xhci_dbg_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xhci_dbg_trace(struct xhci_hcd *xhci, void (*trace)(struct va_format *), const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbg.c (ffffffff8191aa60)
Location: drivers/usb/host/xhci-dbg.c:22
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_check_bw_table
  - drivers/usb/host/xhci.c:xhci_check_bw_table
  - drivers/usb/host/xhci.c:xhci_check_bw_table
  - drivers/usb/host/xhci.c:xhci_check_bw_table
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_setup_msix
  - drivers/usb/host/xhci.c:xhci_setup_msix
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_add_in_port
  - drivers/usb/host/xhci-mem.c:xhci_add_in_port
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:prepare_ring
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_cmd_reset_ep
  - drivers/usb/host/xhci-ring.c:xhci_handle_cmd_reset_ep
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-ring.c:xhci_kill_endpoint_urbs
  - drivers/usb/host/xhci-ring.c:xhci_kill_endpoint_urbs
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status
```
**Symbols:**

```
ffffffff8191aa60-ffffffff8191ab0a: xhci_dbg_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xhci_dbg_trace(struct xhci_hcd *xhci, void (*trace)(struct va_format *), const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbg.c (ffffffff819212b0)
Location: drivers/usb/host/xhci-dbg.c:22
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_check_bw_table
  - drivers/usb/host/xhci.c:xhci_check_bw_table
  - drivers/usb/host/xhci.c:xhci_check_bw_table
  - drivers/usb/host/xhci.c:xhci_check_bw_table
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_setup_msix
  - drivers/usb/host/xhci.c:xhci_setup_msix
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_add_in_port
  - drivers/usb/host/xhci-mem.c:xhci_add_in_port
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:prepare_ring
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_cmd_reset_ep
  - drivers/usb/host/xhci-ring.c:xhci_handle_cmd_reset_ep
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-ring.c:xhci_kill_endpoint_urbs
  - drivers/usb/host/xhci-ring.c:xhci_kill_endpoint_urbs
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status
```
**Symbols:**

```
ffffffff819212b0-ffffffff8192135a: xhci_dbg_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xhci_dbg_trace(struct xhci_hcd *xhci, void (*trace)(struct va_format *), const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbg.c (ffffffff819049c0)
Location: drivers/usb/host/xhci-dbg.c:22
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_check_bw_table
  - drivers/usb/host/xhci.c:xhci_check_bw_table
  - drivers/usb/host/xhci.c:xhci_check_bw_table
  - drivers/usb/host/xhci.c:xhci_check_bw_table
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_add_in_port
  - drivers/usb/host/xhci-mem.c:xhci_add_in_port
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-ring.c:prepare_ring
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_cmd_reset_ep
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status
```
**Symbols:**

```
ffffffff819049c0-ffffffff81904a6a: xhci_dbg_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xhci_dbg_trace(struct xhci_hcd *xhci, void (*trace)(struct va_format *), const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbg.c (ffffffff819a51c0)
Location: drivers/usb/host/xhci-dbg.c:22
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_check_bw_table
  - drivers/usb/host/xhci.c:xhci_check_bw_table
  - drivers/usb/host/xhci.c:xhci_check_bw_table
  - drivers/usb/host/xhci.c:xhci_check_bw_table
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_add_in_port
  - drivers/usb/host/xhci-mem.c:xhci_add_in_port
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-ring.c:prepare_ring
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_cmd_reset_ep
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
  - drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status
```
**Symbols:**

```
ffffffff819a51c0-ffffffff819a5267: xhci_dbg_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xhci_dbg_trace(struct xhci_hcd *xhci, void (*trace)(struct va_format *), const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbg.c (ffffffff81b02ba0)
Location: drivers/usb/host/xhci-dbg.c:22
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_check_bw_table
  - drivers/usb/host/xhci.c:xhci_check_bw_table
  - drivers/usb/host/xhci.c:xhci_check_bw_table
  - drivers/usb/host/xhci.c:xhci_check_bw_table
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run_finished
  - drivers/usb/host/xhci.c:xhci_run_finished
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_add_in_port
  - drivers/usb/host/xhci-mem.c:xhci_add_in_port
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-ring.c:prepare_ring
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
  - drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status
```
**Symbols:**

```
ffffffff81b02ba0-ffffffff81b02c64: xhci_dbg_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xhci_dbg_trace(struct xhci_hcd *xhci, void (*trace)(struct va_format *), const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbg.c (ffffffff81c91c50)
Location: drivers/usb/host/xhci-dbg.c:22
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_check_bw_table
  - drivers/usb/host/xhci.c:xhci_check_bw_table
  - drivers/usb/host/xhci.c:xhci_check_bw_table
  - drivers/usb/host/xhci.c:xhci_check_bw_table
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run_finished
  - drivers/usb/host/xhci.c:xhci_run_finished
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_add_in_port
  - drivers/usb/host/xhci-mem.c:xhci_add_in_port
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-ring.c:prepare_ring
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
  - drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status
```
**Symbols:**

```
ffffffff81c91c50-ffffffff81c91d14: xhci_dbg_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xhci_dbg_trace(struct xhci_hcd *xhci, void (*trace)(struct va_format *), const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbg.c (ffffffff81cf8340)
Location: drivers/usb/host/xhci-dbg.c:22
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_check_bw_table
  - drivers/usb/host/xhci.c:xhci_check_bw_table
  - drivers/usb/host/xhci.c:xhci_check_bw_table
  - drivers/usb/host/xhci.c:xhci_check_bw_table
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run_finished
  - drivers/usb/host/xhci.c:xhci_run_finished
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_add_in_port
  - drivers/usb/host/xhci-mem.c:xhci_add_in_port
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-ring.c:prepare_ring
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
  - drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status
```
**Symbols:**

```
ffffffff81cf8340-ffffffff81cf8404: xhci_dbg_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xhci_dbg_trace(struct xhci_hcd *xhci, void (*trace)(struct va_format *), const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbg.c (ffffffff81dadc70)
Location: drivers/usb/host/xhci-dbg.c:22
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_check_bw_table
  - drivers/usb/host/xhci.c:xhci_check_bw_table
  - drivers/usb/host/xhci.c:xhci_check_bw_table
  - drivers/usb/host/xhci.c:xhci_check_bw_table
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run_finished
  - drivers/usb/host/xhci.c:xhci_run_finished
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_add_interrupter
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_add_in_port
  - drivers/usb/host/xhci-mem.c:xhci_add_in_port
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-ring.c:prepare_ring
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
  - drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status
```
**Symbols:**

```
ffffffff81dadc70-ffffffff81dadd34: xhci_dbg_trace (STB_GLOBAL)
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
void xhci_dbg_trace(struct xhci_hcd *xhci, void (*trace)(struct va_format *), const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbg.c (ffff800010a87540)
Location: drivers/usb/host/xhci-dbg.c:22
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_device_endpoint_resources
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_free_host_resources
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_add_in_port
  - drivers/usb/host/xhci-mem.c:xhci_add_in_port
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:prepare_ring
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
```
**Symbols:**

```
ffff800010a87540-ffff800010a87600: xhci_dbg_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void xhci_dbg_trace(struct xhci_hcd *xhci, void (*trace)(struct va_format *), const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbg.c (c0b5a20c)
Location: drivers/usb/host/xhci-dbg.c:22
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_device_endpoint_resources
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_free_host_resources
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:prepare_ring
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_cmd_set_deq
  - drivers/usb/host/xhci-ring.c:xhci_handle_cmd_set_deq
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
```
**Symbols:**

```
c0b5a20c-c0b5a2c0: xhci_dbg_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void xhci_dbg_trace(struct xhci_hcd *xhci, void (*trace)(struct va_format *), const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbg.c (c000000000b61700)
Location: drivers/usb/host/xhci-dbg.c:22
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_device_endpoint_resources
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_free_host_resources
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:prepare_ring
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
```
**Symbols:**

```
c000000000b61700-c000000000b617dc: xhci_dbg_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void xhci_dbg_trace(struct xhci_hcd *xhci, void (*trace)(struct va_format *), const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbg.c (ffffffe00069cb2e)
Location: drivers/usb/host/xhci-dbg.c:22
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_device_endpoint_resources
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_free_host_resources
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:prepare_ring
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
```
**Symbols:**

```
ffffffe00069cb2e-ffffffe00069cbb0: xhci_dbg_trace (STB_GLOBAL)
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
void xhci_dbg_trace(struct xhci_hcd *xhci, void (*trace)(struct va_format *), const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbg.c (ffffffff81800720)
Location: drivers/usb/host/xhci-dbg.c:22
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_device_endpoint_resources
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_free_host_resources
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:prepare_ring
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
```
**Symbols:**

```
ffffffff81800720-ffffffff818007ca: xhci_dbg_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void xhci_dbg_trace(struct xhci_hcd *xhci, void (*trace)(struct va_format *), const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbg.c (ffffffff817c58c0)
Location: drivers/usb/host/xhci-dbg.c:22
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_device_endpoint_resources
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_free_host_resources
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:prepare_ring
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
```
**Symbols:**

```
ffffffff817c58c0-ffffffff817c596a: xhci_dbg_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void xhci_dbg_trace(struct xhci_hcd *xhci, void (*trace)(struct va_format *), const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbg.c (ffffffff8183d1f0)
Location: drivers/usb/host/xhci-dbg.c:22
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_device_endpoint_resources
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_free_host_resources
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:prepare_ring
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
```
**Symbols:**

```
ffffffff8183d1f0-ffffffff8183d29a: xhci_dbg_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xhci_dbg_trace(struct xhci_hcd *xhci, void (*trace)(struct va_format *), const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbg.c (ffffffff818576c0)
Location: drivers/usb/host/xhci-dbg.c:22
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_device_endpoint_resources
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_free_host_resources
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:compliance_mode_recovery_timer_init
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_setup_streams_ep_input_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:prepare_ring
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
  - drivers/usb/host/xhci-pci.c:xhci_pci_quirks
```
**Symbols:**

```
ffffffff818576c0-ffffffff8185776a: xhci_dbg_trace (STB_GLOBAL)
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
