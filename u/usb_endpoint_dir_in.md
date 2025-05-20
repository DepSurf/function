# Function: <code>usb_endpoint_dir_in</code>

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
In drivers/usb/core/hub.c (0)
Location: include/uapi/linux/usb/ch9.h:450
Inline: True
```
```
In drivers/usb/core/endpoint.c (0)
Location: include/uapi/linux/usb/ch9.h:450
Inline: True
```
```
In drivers/usb/core/devices.c (0)
Location: include/uapi/linux/usb/ch9.h:450
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/uapi/linux/usb/ch9.h:450
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/uapi/linux/usb/ch9.h:450
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/uapi/linux/usb/ch9.h:450
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81654524)
Location: include/uapi/linux/usb/ch9.h:450
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
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
In drivers/usb/core/hub.c (0)
Location: include/uapi/linux/usb/ch9.h:473
Inline: True
```
```
In drivers/usb/core/endpoint.c (0)
Location: include/uapi/linux/usb/ch9.h:473
Inline: True
```
```
In drivers/usb/core/devices.c (0)
Location: include/uapi/linux/usb/ch9.h:473
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/uapi/linux/usb/ch9.h:473
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816a92a9)
Location: include/uapi/linux/usb/ch9.h:473
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
```
In drivers/usb/host/xhci.c (0)
Location: include/uapi/linux/usb/ch9.h:473
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/uapi/linux/usb/ch9.h:473
Inline: True
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
In drivers/usb/core/hub.c (0)
Location: include/uapi/linux/usb/ch9.h:479
Inline: True
```
```
In drivers/usb/core/endpoint.c (0)
Location: include/uapi/linux/usb/ch9.h:479
Inline: True
```
```
In drivers/usb/core/devices.c (0)
Location: include/uapi/linux/usb/ch9.h:479
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/uapi/linux/usb/ch9.h:479
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816d73d3)
Location: include/uapi/linux/usb/ch9.h:479
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
```
In drivers/usb/host/xhci.c (0)
Location: include/uapi/linux/usb/ch9.h:479
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/uapi/linux/usb/ch9.h:479
Inline: True
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
In drivers/usb/core/usb.c (0)
Location: include/uapi/linux/usb/ch9.h:480
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: include/uapi/linux/usb/ch9.h:480
Inline: True
```
```
In drivers/usb/core/endpoint.c (0)
Location: include/uapi/linux/usb/ch9.h:480
Inline: True
```
```
In drivers/usb/core/devices.c (0)
Location: include/uapi/linux/usb/ch9.h:480
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/uapi/linux/usb/ch9.h:480
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816eb80f)
Location: include/uapi/linux/usb/ch9.h:480
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
```
In drivers/usb/host/xhci.c (0)
Location: include/uapi/linux/usb/ch9.h:480
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/uapi/linux/usb/ch9.h:480
Inline: True
```
```
In drivers/usb/host/xhci-trace.c (ffffffff817039c8)
Location: include/uapi/linux/usb/ch9.h:480
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
In drivers/usb/core/usb.c (0)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
```
```
In drivers/usb/core/endpoint.c (0)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
```
```
In drivers/usb/core/devices.c (0)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81757fff)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
```
In drivers/usb/host/xhci.c (0)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (0)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81770724)
Location: include/uapi/linux/usb/ch9.h:485
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
In drivers/usb/core/usb.c (ffffffff8174fe38)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:match_endpoint
  - drivers/usb/core/usb.c:match_endpoint
```
```
In drivers/usb/core/hub.c (ffffffff81758d14)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/endpoint.c (ffffffff81766d0d)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:direction_show
```
```
In drivers/usb/core/devices.c (ffffffff8176cae6)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817821ff)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817974f9)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
```
In drivers/usb/host/xhci.c (ffffffff8179b9d9)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817a420d)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-trace.c (ffffffff817b0b39)
Location: include/uapi/linux/usb/ch9.h:485
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
In drivers/usb/core/usb.c (ffffffff81774268)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:match_endpoint
  - drivers/usb/core/usb.c:match_endpoint
```
```
In drivers/usb/core/hub.c (ffffffff8177d284)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/endpoint.c (ffffffff8178b28d)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:direction_show
```
```
In drivers/usb/core/devices.c (ffffffff81791136)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817a8a20)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817bda39)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
```
In drivers/usb/host/xhci.c (ffffffff817c1d99)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817ca593)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-trace.c (ffffffff817d70b9)
Location: include/uapi/linux/usb/ch9.h:485
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
In drivers/usb/core/usb.c (ffffffff817b2398)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:match_endpoint
  - drivers/usb/core/usb.c:match_endpoint
```
```
In drivers/usb/core/hub.c (ffffffff817bb7e4)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/endpoint.c (ffffffff817c9890)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:direction_show
```
```
In drivers/usb/core/devices.c (ffffffff817cf739)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_desc
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817e7c8a)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817fcbcb)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
```
In drivers/usb/host/xhci.c (ffffffff8180167a)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8180a998)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81817627)
Location: include/uapi/linux/usb/ch9.h:485
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
In drivers/usb/core/usb.c (ffffffff817e2ac8)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:match_endpoint
  - drivers/usb/core/usb.c:match_endpoint
```
```
In drivers/usb/core/hub.c (ffffffff817ebff2)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/endpoint.c (ffffffff817fa3d0)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:direction_show
```
```
In drivers/usb/core/devices.c (ffffffff818005a9)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_desc
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81818b4a)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8182da1b)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
```
In drivers/usb/host/xhci.c (ffffffff8183272a)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8183b918)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81848967)
Location: include/uapi/linux/usb/ch9.h:485
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
In drivers/usb/core/usb.c (ffffffff818b1618)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:match_endpoint
  - drivers/usb/core/usb.c:match_endpoint
```
```
In drivers/usb/core/hub.c (ffffffff818bb609)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/endpoint.c (ffffffff818ca5f0)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:direction_show
```
```
In drivers/usb/core/devices.c (ffffffff818d0a84)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_config
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818e9c90)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81902a6d)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
```
In drivers/usb/host/xhci.c (ffffffff81905932)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
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
In drivers/usb/host/xhci-mem.c (ffffffff8190e68d)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-trace.c (ffffffff8191b06e)
Location: include/uapi/linux/usb/ch9.h:485
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
In drivers/usb/core/usb.c (ffffffff818bffc8)
Location: include/uapi/linux/usb/ch9.h:492
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:match_endpoint
  - drivers/usb/core/usb.c:match_endpoint
```
```
In drivers/usb/core/hub.c (ffffffff81c1c132)
Location: include/uapi/linux/usb/ch9.h:492
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/endpoint.c (ffffffff818d5700)
Location: include/uapi/linux/usb/ch9.h:492
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:direction_show
```
```
In drivers/usb/core/devices.c (ffffffff818daeec)
Location: include/uapi/linux/usb/ch9.h:492
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_config
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818f2b80)
Location: include/uapi/linux/usb/ch9.h:492
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8190b33d)
Location: include/uapi/linux/usb/ch9.h:492
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
```
In drivers/usb/host/xhci.c (ffffffff8190e132)
Location: include/uapi/linux/usb/ch9.h:492
Inline: True
Inline callers:
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
In drivers/usb/host/xhci-mem.c (ffffffff819161df)
Location: include/uapi/linux/usb/ch9.h:492
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-trace.c (ffffffff819226de)
Location: include/uapi/linux/usb/ch9.h:492
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
In drivers/usb/core/usb.c (ffffffff818a319f)
Location: include/uapi/linux/usb/ch9.h:492
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:match_endpoint
  - drivers/usb/core/usb.c:match_endpoint
```
```
In drivers/usb/core/hub.c (ffffffff81c0e018)
Location: include/uapi/linux/usb/ch9.h:492
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/endpoint.c (ffffffff818b8cc0)
Location: include/uapi/linux/usb/ch9.h:492
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:direction_show
```
```
In drivers/usb/core/devices.c (ffffffff818be432)
Location: include/uapi/linux/usb/ch9.h:492
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_config
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818d633e)
Location: include/uapi/linux/usb/ch9.h:492
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff818ed637)
Location: include/uapi/linux/usb/ch9.h:492
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
```
In drivers/usb/host/xhci.c (ffffffff818f162d)
Location: include/uapi/linux/usb/ch9.h:492
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
```
```
In drivers/usb/host/xhci-mem.c (ffffffff818f9693)
Location: include/uapi/linux/usb/ch9.h:492
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81905dee)
Location: include/uapi/linux/usb/ch9.h:492
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
In drivers/usb/core/usb.c (ffffffff81937d1f)
Location: include/uapi/linux/usb/ch9.h:492
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:match_endpoint
  - drivers/usb/core/usb.c:match_endpoint
```
```
In drivers/usb/core/hub.c (ffffffff81d150f2)
Location: include/uapi/linux/usb/ch9.h:492
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/endpoint.c (ffffffff8194e780)
Location: include/uapi/linux/usb/ch9.h:492
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:direction_show
```
```
In drivers/usb/core/devices.c (ffffffff819547f2)
Location: include/uapi/linux/usb/ch9.h:492
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_config
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81970fe1)
Location: include/uapi/linux/usb/ch9.h:492
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81989d1f)
Location: include/uapi/linux/usb/ch9.h:492
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
```
In drivers/usb/host/xhci.c (ffffffff8198e5c0)
Location: include/uapi/linux/usb/ch9.h:492
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_free_streams
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
In drivers/usb/host/xhci-mem.c (ffffffff819981f7)
Location: include/uapi/linux/usb/ch9.h:492
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-trace.c (ffffffff819a65ee)
Location: include/uapi/linux/usb/ch9.h:492
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
In drivers/usb/core/usb.c (ffffffff81a8f413)
Location: include/uapi/linux/usb/ch9.h:492
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:match_endpoint
  - drivers/usb/core/usb.c:match_endpoint
```
```
In drivers/usb/core/hub.c (ffffffff81edfc91)
Location: include/uapi/linux/usb/ch9.h:492
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/endpoint.c (ffffffff81aa7770)
Location: include/uapi/linux/usb/ch9.h:492
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:direction_show
```
```
In drivers/usb/core/devices.c (ffffffff81aae0c6)
Location: include/uapi/linux/usb/ch9.h:492
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_config
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81acbe50)
Location: include/uapi/linux/usb/ch9.h:492
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81ae7939)
Location: include/uapi/linux/usb/ch9.h:492
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
```
In drivers/usb/host/xhci.c (ffffffff81aeaa2a)
Location: include/uapi/linux/usb/ch9.h:492
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_free_streams
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
In drivers/usb/host/xhci-mem.c (ffffffff81af518c)
Location: include/uapi/linux/usb/ch9.h:492
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81b0430d)
Location: include/uapi/linux/usb/ch9.h:492
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
In drivers/usb/core/usb.c (ffffffff81c110a3)
Location: include/uapi/linux/usb/ch9.h:492
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:match_endpoint
  - drivers/usb/core/usb.c:match_endpoint
```
```
In drivers/usb/core/hub.c (ffffffff81c1caa5)
Location: include/uapi/linux/usb/ch9.h:492
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/endpoint.c (ffffffff81c2e640)
Location: include/uapi/linux/usb/ch9.h:492
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:direction_show
```
```
In drivers/usb/core/devices.c (ffffffff81c35af6)
Location: include/uapi/linux/usb/ch9.h:492
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_config
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81c565c2)
Location: include/uapi/linux/usb/ch9.h:492
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81c73859)
Location: include/uapi/linux/usb/ch9.h:492
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
```
In drivers/usb/host/xhci.c (ffffffff81c76e7a)
Location: include/uapi/linux/usb/ch9.h:492
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_free_streams
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
In drivers/usb/host/xhci-mem.c (ffffffff81c829fc)
Location: include/uapi/linux/usb/ch9.h:492
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81c9386a)
Location: include/uapi/linux/usb/ch9.h:492
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
In drivers/usb/core/usb.c (ffffffff81c77d14)
Location: include/uapi/linux/usb/ch9.h:495
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:match_endpoint
  - drivers/usb/core/usb.c:match_endpoint
```
```
In drivers/usb/core/hub.c (ffffffff81c839a2)
Location: include/uapi/linux/usb/ch9.h:495
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/endpoint.c (ffffffff81c958a0)
Location: include/uapi/linux/usb/ch9.h:495
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:direction_show
```
```
In drivers/usb/core/devices.c (ffffffff81c9ce2f)
Location: include/uapi/linux/usb/ch9.h:495
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_config
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81cbdc0d)
Location: include/uapi/linux/usb/ch9.h:495
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81cdadff)
Location: include/uapi/linux/usb/ch9.h:495
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
```
In drivers/usb/host/xhci.c (ffffffff81cddf5a)
Location: include/uapi/linux/usb/ch9.h:495
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_free_streams
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
In drivers/usb/host/xhci-mem.c (ffffffff81ce96c9)
Location: include/uapi/linux/usb/ch9.h:495
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81cf9fda)
Location: include/uapi/linux/usb/ch9.h:495
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
In drivers/usb/core/usb.c (ffffffff81d2c714)
Location: include/uapi/linux/usb/ch9.h:492
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:match_endpoint
  - drivers/usb/core/usb.c:match_endpoint
```
```
In drivers/usb/core/hub.c (ffffffff81d38352)
Location: include/uapi/linux/usb/ch9.h:492
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/endpoint.c (ffffffff81d4a360)
Location: include/uapi/linux/usb/ch9.h:492
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:direction_show
```
```
In drivers/usb/core/devices.c (ffffffff81d519df)
Location: include/uapi/linux/usb/ch9.h:492
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_config
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81d7297d)
Location: include/uapi/linux/usb/ch9.h:492
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81d8fe2f)
Location: include/uapi/linux/usb/ch9.h:492
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
```
In drivers/usb/host/xhci.c (ffffffff81d92f6a)
Location: include/uapi/linux/usb/ch9.h:492
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_free_streams
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
In drivers/usb/host/xhci-mem.c (ffffffff81d9eefe)
Location: include/uapi/linux/usb/ch9.h:492
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81daf92a)
Location: include/uapi/linux/usb/ch9.h:492
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
In drivers/usb/core/usb.c (ffff800010a10dc8)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:match_endpoint
  - drivers/usb/core/usb.c:match_endpoint
```
```
In drivers/usb/core/hub.c (ffff800010a1a1b0)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/endpoint.c (ffff800010a2b92c)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:direction_show
```
```
In drivers/usb/core/devices.c (ffff800010a3441c)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_desc
```
```
In drivers/usb/host/ehci-hcd.c (ffff800010a51e9c)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
```
In drivers/usb/host/uhci-hcd.c (ffff800010a690c8)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
```
In drivers/usb/host/xhci.c (ffff800010a6ec0c)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (ffff800010a796f4)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-trace.c (ffff800010a8a420)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_urb
```
```
In drivers/usb/host/xhci-mtk-sch.c (ffff800010a8e390)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_drop_ep_quirk
  - drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_add_ep_quirk
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
In drivers/usb/core/usb.c (c0ae94c0)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:match_endpoint
  - drivers/usb/core/usb.c:match_endpoint
```
```
In drivers/usb/core/hub.c (c0af23e0)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/endpoint.c (c0b012fc)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:direction_show
```
```
In drivers/usb/core/devices.c (c0b07d20)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_desc
```
```
In drivers/usb/host/ehci-hcd.c (c0b259cc)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
```
In drivers/usb/host/uhci-hcd.c (c0b395b0)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
```
In drivers/usb/host/xhci.c (c0b42f88)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (c0b4d0fc)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-trace.c (c0b5a840)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_urb
```
```
In drivers/usb/host/xhci-mtk-sch.c (c0b5ffa8)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_drop_ep_quirk
  - drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_add_ep_quirk
```
```
In drivers/usb/musb/musb_gadget.c (c0b6f08c)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/musb/musb_gadget.c:musb_gadget_enable
  - drivers/usb/musb/musb_gadget.c:musb_gadget_enable
```
```
In drivers/usb/gadget/udc/core.c (c0b73864)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
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
In drivers/usb/core/usb.c (c000000000ac7c54)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:match_endpoint
  - drivers/usb/core/usb.c:match_endpoint
```
```
In drivers/usb/core/hub.c (c000000000ad38f8)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/endpoint.c (c000000000ae88e0)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:direction_show
```
```
In drivers/usb/core/devices.c (c000000000af1dfc)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_desc
```
```
In drivers/usb/host/ehci-hcd.c (c000000000b1b44c)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
```
In drivers/usb/host/uhci-hcd.c (c000000000b38970)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
```
In drivers/usb/host/xhci.c (c000000000b4309c)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (c000000000b50d48)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-trace.c (c000000000b61f6c)
Location: include/uapi/linux/usb/ch9.h:485
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
In drivers/usb/core/usb.c (ffffffe000636a82)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:match_endpoint
  - drivers/usb/core/usb.c:match_endpoint
```
```
In drivers/usb/core/hub.c (ffffffe00063ebfa)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/endpoint.c (ffffffe00064cd38)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:direction_show
```
```
In drivers/usb/core/devices.c (ffffffe000651fda)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_desc
```
```
In drivers/usb/host/ehci-hcd.c (ffffffe00066f314)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
```
In drivers/usb/host/uhci-hcd.c (ffffffe000681e9a)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
```
In drivers/usb/host/xhci.c (ffffffe000687e3e)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (ffffffe000690ef0)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-trace.c (ffffffe00069cf62)
Location: include/uapi/linux/usb/ch9.h:485
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
In drivers/usb/core/usb.c (ffffffff8179aea8)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:match_endpoint
  - drivers/usb/core/usb.c:match_endpoint
```
```
In drivers/usb/core/hub.c (ffffffff817a43d2)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/endpoint.c (ffffffff817b27b0)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:direction_show
```
```
In drivers/usb/core/devices.c (ffffffff817b8989)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_desc
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817d0f2a)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817e5dfb)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
```
In drivers/usb/host/xhci.c (ffffffff817eab0a)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817f3cc8)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81800d17)
Location: include/uapi/linux/usb/ch9.h:485
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
In drivers/usb/core/usb.c (ffffffff8178cb38)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:match_endpoint
  - drivers/usb/core/usb.c:match_endpoint
```
```
In drivers/usb/core/hub.c (ffffffff81795f43)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/endpoint.c (ffffffff817a41e0)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:direction_show
```
```
In drivers/usb/core/devices.c (ffffffff817aa3b9)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_desc
```
```
In drivers/usb/host/xhci.c (ffffffff817afc1a)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817b8e68)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-trace.c (ffffffff817c5eb7)
Location: include/uapi/linux/usb/ch9.h:485
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
In drivers/usb/core/usb.c (ffffffff817d7948)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:match_endpoint
  - drivers/usb/core/usb.c:match_endpoint
```
```
In drivers/usb/core/hub.c (ffffffff817e0e72)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/endpoint.c (ffffffff817ef250)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:direction_show
```
```
In drivers/usb/core/devices.c (ffffffff817f5429)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_desc
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8180d9ca)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8182289b)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
```
In drivers/usb/host/xhci.c (ffffffff818275aa)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81830798)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-trace.c (ffffffff8183d7e7)
Location: include/uapi/linux/usb/ch9.h:485
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
In drivers/usb/core/usb.c (ffffffff817f1be8)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:match_endpoint
  - drivers/usb/core/usb.c:match_endpoint
```
```
In drivers/usb/core/hub.c (ffffffff817fb162)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/endpoint.c (ffffffff81809490)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:direction_show
```
```
In drivers/usb/core/devices.c (ffffffff8180f669)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_desc
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8182805a)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8183dfbb)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
```
In drivers/usb/host/xhci.c (ffffffff8184154a)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8184a968)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81857cb7)
Location: include/uapi/linux/usb/ch9.h:485
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_urb
```
</details>
</li>
</ul>

## Differences
