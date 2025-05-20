# Function: <code>musb_dbg</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void musb_dbg(struct musb *musb, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/musb/musb_trace.c (c0b6909c)
Location: drivers/usb/musb/musb_trace.c:13
Inline: False
Direct callers:
  - drivers/usb/musb/musb_core.c:musb_irq_work
  - drivers/usb/musb/musb_core.c:musb_irq_work
  - drivers/usb/musb/musb_core.c:musb_irq_work
  - drivers/usb/musb/musb_core.c:musb_irq_work
  - drivers/usb/musb/musb_core.c:musb_irq_work
  - drivers/usb/musb/musb_core.c:musb_core_init
  - drivers/usb/musb/musb_core.c:musb_core_init
  - drivers/usb/musb/musb_core.c:musb_core_init
  - drivers/usb/musb/musb_core.c:ep_config_from_hw
  - drivers/usb/musb/musb_core.c:musb_start
  - drivers/usb/musb/musb_core.c:musb_stage0_irq
  - drivers/usb/musb/musb_core.c:musb_stage0_irq
  - drivers/usb/musb/musb_core.c:musb_stage0_irq
  - drivers/usb/musb/musb_core.c:musb_stage0_irq
  - drivers/usb/musb/musb_core.c:musb_stage0_irq
  - drivers/usb/musb/musb_core.c:musb_stage0_irq
  - drivers/usb/musb/musb_core.c:musb_stage0_irq
  - drivers/usb/musb/musb_core.c:musb_stage0_irq
  - drivers/usb/musb/musb_core.c:musb_stage0_irq
  - drivers/usb/musb/musb_core.c:musb_stage0_irq
  - drivers/usb/musb/musb_core.c:musb_stage0_irq
  - drivers/usb/musb/musb_core.c:musb_stage0_irq
  - drivers/usb/musb/musb_core.c:musb_stage0_irq
  - drivers/usb/musb/musb_core.c:musb_stage0_irq
  - drivers/usb/musb/musb_core.c:musb_stage0_irq
  - drivers/usb/musb/musb_core.c:musb_stage0_irq
  - drivers/usb/musb/musb_core.c:musb_hnp_stop
  - drivers/usb/musb/musb_core.c:musb_hnp_stop
  - drivers/usb/musb/musb_core.c:musb_hnp_stop
  - drivers/usb/musb/musb_core.c:musb_hnp_stop
  - drivers/usb/musb/musb_core.c:musb_otg_timer_func
  - drivers/usb/musb/musb_core.c:musb_otg_timer_func
  - drivers/usb/musb/musb_core.c:musb_otg_timer_func
  - drivers/usb/musb/musb_virthub.c:musb_hub_control
  - drivers/usb/musb/musb_virthub.c:musb_hub_control
  - drivers/usb/musb/musb_virthub.c:musb_hub_control
  - drivers/usb/musb/musb_virthub.c:musb_hub_control
  - drivers/usb/musb/musb_virthub.c:musb_root_disconnect
  - drivers/usb/musb/musb_virthub.c:musb_port_reset
  - drivers/usb/musb/musb_virthub.c:musb_port_reset
  - drivers/usb/musb/musb_virthub.c:musb_port_reset
  - drivers/usb/musb/musb_virthub.c:musb_port_suspend
  - drivers/usb/musb/musb_virthub.c:musb_port_suspend
  - drivers/usb/musb/musb_virthub.c:musb_port_suspend
  - drivers/usb/musb/musb_virthub.c:musb_host_finish_resume
  - drivers/usb/musb/musb_host.c:musb_urb_enqueue
  - drivers/usb/musb/musb_host.c:musb_host_rx
  - drivers/usb/musb/musb_host.c:musb_host_rx
  - drivers/usb/musb/musb_host.c:musb_host_rx
  - drivers/usb/musb/musb_host.c:musb_host_rx
  - drivers/usb/musb/musb_host.c:musb_host_rx
  - drivers/usb/musb/musb_host.c:musb_host_rx
  - drivers/usb/musb/musb_host.c:musb_host_rx
  - drivers/usb/musb/musb_host.c:musb_host_rx
  - drivers/usb/musb/musb_host.c:musb_host_rx
  - drivers/usb/musb/musb_host.c:musb_host_tx
  - drivers/usb/musb/musb_host.c:musb_host_tx
  - drivers/usb/musb/musb_host.c:musb_host_tx
  - drivers/usb/musb/musb_host.c:musb_host_tx
  - drivers/usb/musb/musb_host.c:musb_host_tx
  - drivers/usb/musb/musb_host.c:musb_host_tx
  - drivers/usb/musb/musb_host.c:musb_h_ep0_irq
  - drivers/usb/musb/musb_host.c:musb_h_ep0_irq
  - drivers/usb/musb/musb_host.c:musb_h_ep0_irq
  - drivers/usb/musb/musb_host.c:musb_h_ep0_irq
  - drivers/usb/musb/musb_host.c:musb_h_ep0_irq
  - drivers/usb/musb/musb_host.c:musb_h_ep0_irq
  - drivers/usb/musb/musb_host.c:musb_h_ep0_irq
  - drivers/usb/musb/musb_host.c:musb_h_ep0_irq
  - drivers/usb/musb/musb_host.c:musb_h_ep0_irq
  - drivers/usb/musb/musb_host.c:musb_h_ep0_irq
  - drivers/usb/musb/musb_host.c:musb_host_packet_rx
  - drivers/usb/musb/musb_host.c:musb_host_packet_rx
  - drivers/usb/musb/musb_host.c:musb_host_packet_rx
  - drivers/usb/musb/musb_host.c:musb_advance_schedule
  - drivers/usb/musb/musb_host.c:musb_start_urb
  - drivers/usb/musb/musb_host.c:musb_start_urb
  - drivers/usb/musb/musb_gadget_ep0.c:musb_g_ep0_halt
  - drivers/usb/musb/musb_gadget_ep0.c:musb_g_ep0_queue
  - drivers/usb/musb/musb_gadget_ep0.c:musb_g_ep0_queue
  - drivers/usb/musb/musb_gadget_ep0.c:musb_g_ep0_irq
  - drivers/usb/musb/musb_gadget_ep0.c:musb_g_ep0_irq
  - drivers/usb/musb/musb_gadget_ep0.c:musb_g_ep0_irq
  - drivers/usb/musb/musb_gadget_ep0.c:musb_g_ep0_irq
  - drivers/usb/musb/musb_gadget_ep0.c:musb_g_ep0_irq
  - drivers/usb/musb/musb_gadget_ep0.c:musb_g_ep0_irq
  - drivers/usb/musb/musb_gadget_ep0.c:musb_g_ep0_irq
  - drivers/usb/musb/musb_gadget_ep0.c:musb_g_ep0_irq
  - drivers/usb/musb/musb_gadget_ep0.c:musb_g_ep0_irq
  - drivers/usb/musb/musb_gadget_ep0.c:ep0_txstate
  - drivers/usb/musb/musb_gadget_ep0.c:service_zero_data_request
  - drivers/usb/musb/musb_gadget_ep0.c:service_zero_data_request
  - drivers/usb/musb/musb_gadget.c:musb_g_reset
  - drivers/usb/musb/musb_gadget.c:musb_g_disconnect
  - drivers/usb/musb/musb_gadget.c:musb_g_disconnect
  - drivers/usb/musb/musb_gadget.c:musb_g_suspend
  - drivers/usb/musb/musb_gadget.c:musb_gadget_work
  - drivers/usb/musb/musb_gadget.c:musb_gadget_wakeup
  - drivers/usb/musb/musb_gadget.c:musb_gadget_wakeup
  - drivers/usb/musb/musb_gadget.c:musb_gadget_wakeup
  - drivers/usb/musb/musb_gadget.c:musb_gadget_set_halt
  - drivers/usb/musb/musb_gadget.c:musb_gadget_set_halt
  - drivers/usb/musb/musb_gadget.c:musb_gadget_set_halt
  - drivers/usb/musb/musb_gadget.c:musb_gadget_set_halt
  - drivers/usb/musb/musb_gadget.c:musb_gadget_set_halt
  - drivers/usb/musb/musb_gadget.c:musb_gadget_set_halt
  - drivers/usb/musb/musb_gadget.c:musb_gadget_set_halt
  - drivers/usb/musb/musb_gadget.c:musb_gadget_queue
  - drivers/usb/musb/musb_gadget.c:musb_gadget_disable
  - drivers/usb/musb/musb_gadget.c:musb_gadget_enable
  - drivers/usb/musb/musb_gadget.c:musb_gadget_enable
  - drivers/usb/musb/musb_gadget.c:musb_g_rx
  - drivers/usb/musb/musb_gadget.c:musb_g_rx
  - drivers/usb/musb/musb_gadget.c:musb_g_rx
  - drivers/usb/musb/musb_gadget.c:rxstate
  - drivers/usb/musb/musb_gadget.c:rxstate
  - drivers/usb/musb/musb_gadget.c:musb_g_tx
  - drivers/usb/musb/musb_gadget.c:musb_g_tx
  - drivers/usb/musb/musb_gadget.c:txstate
  - drivers/usb/musb/musb_gadget.c:txstate
  - drivers/usb/musb/musb_gadget.c:txstate
  - drivers/usb/musb/musb_gadget.c:txstate
  - drivers/usb/musb/musb_gadget.c:txstate
```
**Symbols:**

```
c0b6909c-c0b6918c: musb_dbg (STB_GLOBAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
