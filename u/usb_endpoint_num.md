# Function: <code>usb_endpoint_num</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: include/uapi/linux/usb/ch9.h:427
Inline: True
```
```
In drivers/usb/core/urb.c (0)
Location: include/uapi/linux/usb/ch9.h:427
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff816126e4)
Location: include/uapi/linux/usb/ch9.h:427
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_endpoint
```
```
In drivers/usb/core/devio.c (0)
Location: include/uapi/linux/usb/ch9.h:427
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/uapi/linux/usb/ch9.h:427
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/uapi/linux/usb/ch9.h:427
Inline: True
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
In drivers/usb/core/hcd.c (ffffffff8166f47a)
Location: include/uapi/linux/usb/ch9.h:450
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
```
```
In drivers/usb/core/urb.c (ffffffff81670049)
Location: include/uapi/linux/usb/ch9.h:450
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff81672684)
Location: include/uapi/linux/usb/ch9.h:450
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_endpoint
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/devio.c (0)
Location: include/uapi/linux/usb/ch9.h:450
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8169b5d3)
Location: include/uapi/linux/usb/ch9.h:450
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
```
```
In drivers/usb/host/xhci.c (ffffffff816b16da)
Location: include/uapi/linux/usb/ch9.h:450
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_get_endpoint_flag
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
In drivers/usb/core/hcd.c (ffffffff8169d15a)
Location: include/uapi/linux/usb/ch9.h:456
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
```
```
In drivers/usb/core/urb.c (ffffffff8169dd27)
Location: include/uapi/linux/usb/ch9.h:456
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff816a0334)
Location: include/uapi/linux/usb/ch9.h:456
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_endpoint
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/devio.c (0)
Location: include/uapi/linux/usb/ch9.h:456
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816c96b3)
Location: include/uapi/linux/usb/ch9.h:456
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
```
```
In drivers/usb/host/xhci.c (ffffffff816df88a)
Location: include/uapi/linux/usb/ch9.h:456
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_get_endpoint_flag
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
In drivers/usb/core/hcd.c (ffffffff816b2529)
Location: include/uapi/linux/usb/ch9.h:457
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
```
```
In drivers/usb/core/urb.c (ffffffff816b3136)
Location: include/uapi/linux/usb/ch9.h:457
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff816b5504)
Location: include/uapi/linux/usb/ch9.h:457
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_endpoint
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/devio.c (0)
Location: include/uapi/linux/usb/ch9.h:457
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816de046)
Location: include/uapi/linux/usb/ch9.h:457
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
```
```
In drivers/usb/host/xhci.c (ffffffff816f351a)
Location: include/uapi/linux/usb/ch9.h:457
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_get_endpoint_flag
```
```
In drivers/usb/host/xhci-trace.c (ffffffff817039ba)
Location: include/uapi/linux/usb/ch9.h:457
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_urb
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
In drivers/usb/core/hcd.c (ffffffff8171dbac)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
```
```
In drivers/usb/core/urb.c (ffffffff8171e8db)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff81720d94)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_endpoint
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/devio.c (0)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8174a783)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
```
```
In drivers/usb/host/xhci.c (ffffffff8175f7e2)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_get_endpoint_flag
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81770715)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_urb
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
In drivers/usb/core/hcd.c (ffffffff8175c80c)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
```
```
In drivers/usb/core/urb.c (ffffffff8175d534)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (ffffffff8175fba1)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_endpoint
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/devio.c (0)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8178a64d)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
```
In drivers/usb/host/xhci.c (ffffffff817a01c7)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_get_endpoint_flag
```
```
In drivers/usb/host/xhci-trace.c (ffffffff817b0b2b)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_urb
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
In drivers/usb/core/hcd.c (ffffffff81780dcc)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
```
```
In drivers/usb/core/urb.c (ffffffff81781b6e)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (ffffffff81784161)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_endpoint
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/devio.c (0)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817ac2ed)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
```
In drivers/usb/host/xhci.c (ffffffff817c6487)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_get_endpoint_flag
```
```
In drivers/usb/host/xhci-trace.c (ffffffff817d70ab)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_urb
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
In drivers/usb/core/hcd.c (ffffffff817be7dc)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
```
```
In drivers/usb/core/urb.c (ffffffff817c00bb)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (ffffffff817c24a1)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_endpoint
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/devio.c (0)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817eb507)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
```
In drivers/usb/host/xhci.c (ffffffff81801714)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_get_endpoint_flag
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81817619)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_urb
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
In drivers/usb/core/hcd.c (ffffffff817ef13c)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
```
```
In drivers/usb/core/urb.c (ffffffff817f0a3b)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (ffffffff817f2e21)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_endpoint
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/config.c (0)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8181c3d7)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
```
In drivers/usb/host/xhci.c (ffffffff818327da)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_get_endpoint_flag
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81848959)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_urb
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
In drivers/usb/core/hcd.c (ffffffff818be75a)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:unlink1
```
```
In drivers/usb/core/urb.c (ffffffff818bff51)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (ffffffff818c296d)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_interface
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/config.c (0)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff818ccf75)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818f2cf7)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
```
In drivers/usb/host/xhci.c (ffffffff819058e4)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_calculate_streams_and_bitmask
  - drivers/usb/host/xhci.c:xhci_calculate_streams_and_bitmask
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-trace.c (ffffffff8191b060)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_urb
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
In drivers/usb/core/hcd.c (ffffffff818cb35a)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:unlink1
```
```
In drivers/usb/core/urb.c (ffffffff818ccb44)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (ffffffff818cec8d)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_interface
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/config.c (0)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff818d816d)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818fbc17)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
```
In drivers/usb/host/xhci.c (ffffffff8190e0e4)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_calculate_streams_and_bitmask
  - drivers/usb/host/xhci.c:xhci_calculate_streams_and_bitmask
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-trace.c (ffffffff819226d0)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_urb
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
In drivers/usb/core/hcd.c (ffffffff818ae97a)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:unlink1
```
```
In drivers/usb/core/urb.c (ffffffff818b015f)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (ffffffff818b22be)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_interface
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/config.c (0)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff818bb05b)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818de8c7)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
```
In drivers/usb/host/xhci.c (ffffffff818f15e4)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81905de0)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_urb
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
In drivers/usb/core/hcd.c (ffffffff81943ada)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:unlink1
```
```
In drivers/usb/core/urb.c (ffffffff8194538a)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (ffffffff819475ae)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_interface
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/config.c (0)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff81951801)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8197a537)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
```
In drivers/usb/host/xhci.c (ffffffff8198e535)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-trace.c (ffffffff819a65e0)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_urb
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
In drivers/usb/core/hcd.c (ffffffff81a9bf6b)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:unlink1
```
```
In drivers/usb/core/urb.c (ffffffff81a9d9fe)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (ffffffff81a9feee)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_interface
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/config.c (0)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff81aaa8ac)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81ad7d07)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
```
In drivers/usb/host/xhci.c (ffffffff81aea98a)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81b042ff)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_urb
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
In drivers/usb/core/hcd.c (ffffffff81c20e0b)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:unlink1
```
```
In drivers/usb/core/urb.c (ffffffff81c22aac)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (ffffffff81c2532e)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_interface
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/config.c (0)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff81c31cb4)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81c62cf7)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
```
In drivers/usb/host/xhci.c (ffffffff81c76dda)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81c9385c)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_urb
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
In drivers/usb/core/hcd.c (ffffffff81c87d8b)
Location: include/uapi/linux/usb/ch9.h:472
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:unlink1
```
```
In drivers/usb/core/urb.c (ffffffff81c89a2c)
Location: include/uapi/linux/usb/ch9.h:472
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (ffffffff81c8c2bb)
Location: include/uapi/linux/usb/ch9.h:472
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_interface
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/config.c (0)
Location: include/uapi/linux/usb/ch9.h:472
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff81c98f34)
Location: include/uapi/linux/usb/ch9.h:472
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81cca0f7)
Location: include/uapi/linux/usb/ch9.h:472
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
```
In drivers/usb/host/xhci.c (ffffffff81cddeba)
Location: include/uapi/linux/usb/ch9.h:472
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81cf9fcc)
Location: include/uapi/linux/usb/ch9.h:472
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_urb
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
In drivers/usb/core/hcd.c (ffffffff81d3c7db)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:unlink1
```
```
In drivers/usb/core/urb.c (ffffffff81d3e41a)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (ffffffff81d40d9b)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_interface
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/config.c (0)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff81d4daa4)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81d7efd7)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
```
In drivers/usb/host/xhci.c (ffffffff81d92eca)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81daf91c)
Location: include/uapi/linux/usb/ch9.h:469
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_urb
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
In drivers/usb/core/hcd.c (ffff800010a1eed4)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
```
```
In drivers/usb/core/urb.c (ffff800010a20594)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (ffff800010a23830)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_endpoint
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/config.c (0)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffff800010a59a60)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
```
In drivers/usb/host/xhci.c (ffff800010a6fbf0)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_get_endpoint_flag
```
```
In drivers/usb/host/xhci-trace.c (ffff800010a8a410)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_urb
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
In drivers/usb/core/hcd.c (c0af65c4)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:unlink1
```
```
In drivers/usb/core/urb.c (c0af7668)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (c0af9e10)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_endpoint
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/config.c (0)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
```
```
In drivers/usb/core/devio.c (c0b04e2c)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/usb/host/ehci-hcd.c (c0b28ab8)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
```
In drivers/usb/host/xhci.c (c0b43030)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_get_endpoint_flag
```
```
In drivers/usb/host/xhci-trace.c (c0b5a830)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_urb
```
```
In drivers/usb/musb/musb_host.c (c0b6b958)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/musb/musb_host.c:musb_urb_enqueue
```
```
In drivers/usb/musb/musb_gadget.c (c0b6f00c)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/musb/musb_gadget.c:musb_gadget_enable
```
```
In drivers/staging/emxx_udc/emxx_udc.c (c0c5d50c)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_ep_enable
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
In drivers/usb/core/hcd.c (c000000000ad9134)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
```
```
In drivers/usb/core/urb.c (c000000000ada9ec)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (c000000000ade338)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_endpoint
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/config.c (0)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (c000000000b229a0)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
```
In drivers/usb/host/xhci.c (c000000000b431a8)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_get_endpoint_flag
```
```
In drivers/usb/host/xhci-trace.c (c000000000b61f5c)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_urb
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
In drivers/usb/core/hcd.c (ffffffe0006427c4)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
```
```
In drivers/usb/core/urb.c (ffffffe000643876)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (ffffffe000645f1c)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_endpoint
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/config.c (0)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffe0006752ec)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
```
In drivers/usb/host/xhci.c (ffffffe000687f0c)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_get_endpoint_flag
```
```
In drivers/usb/host/xhci-trace.c (ffffffe00069cf52)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_urb
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
In drivers/usb/core/hcd.c (ffffffff817a751c)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
```
```
In drivers/usb/core/urb.c (ffffffff817a8e1b)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (ffffffff817ab201)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_endpoint
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/config.c (0)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817d47b7)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
```
In drivers/usb/host/xhci.c (ffffffff817eabba)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_get_endpoint_flag
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81800d09)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_urb
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
In drivers/usb/core/hcd.c (ffffffff81798f6c)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
```
```
In drivers/usb/core/urb.c (ffffffff8179a82b)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (ffffffff8179cc01)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_endpoint
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/config.c (0)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff817afcca)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_get_endpoint_flag
```
```
In drivers/usb/host/xhci-trace.c (ffffffff817c5ea9)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_urb
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
In drivers/usb/core/hcd.c (ffffffff817e3fbc)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
```
```
In drivers/usb/core/urb.c (ffffffff817e58bb)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (ffffffff817e7ca1)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_endpoint
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/config.c (0)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81811257)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
```
In drivers/usb/host/xhci.c (ffffffff8182765a)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_get_endpoint_flag
```
```
In drivers/usb/host/xhci-trace.c (ffffffff8183d7d9)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_urb
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
In drivers/usb/core/hcd.c (ffffffff817fe25c)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
```
```
In drivers/usb/core/urb.c (ffffffff817ffb1b)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (ffffffff81801ef1)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_endpoint
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/config.c (0)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8182bd27)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
```
In drivers/usb/host/xhci.c (ffffffff818415fa)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_get_endpoint_flag
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81857ca9)
Location: include/uapi/linux/usb/ch9.h:462
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_urb
```
</details>
</li>
</ul>

## Differences
