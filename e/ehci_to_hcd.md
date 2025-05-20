# Function: <code>ehci_to_hcd</code>

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
In drivers/usb/host/ehci-hcd.c (ffffffff8163104b)
Location: drivers/usb/host/ehci.h:275
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_port_power
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
```
```
In drivers/usb/host/ehci-pci.c (0)
Location: drivers/usb/host/ehci.h:275
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
In drivers/usb/host/ehci-hcd.c (ffffffff816921bc)
Location: drivers/usb/host/ehci.h:278
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_port_power
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
```
```
In drivers/usb/host/ehci-pci.c (0)
Location: drivers/usb/host/ehci.h:278
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
In drivers/usb/host/ehci-hcd.c (ffffffff816c029c)
Location: drivers/usb/host/ehci.h:279
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_port_power
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
```
```
In drivers/usb/host/ehci-pci.c (0)
Location: drivers/usb/host/ehci.h:279
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
In drivers/usb/host/ehci-hcd.c (ffffffff816d4c73)
Location: drivers/usb/host/ehci.h:279
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_port_power
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
```
```
In drivers/usb/host/ehci-pci.c (0)
Location: drivers/usb/host/ehci.h:279
Inline: True
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
In drivers/usb/host/ehci-hcd.c (ffffffff81741363)
Location: drivers/usb/host/ehci.h:266
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_port_power
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
```
```
In drivers/usb/host/ehci-pci.c (0)
Location: drivers/usb/host/ehci.h:266
Inline: True
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
In drivers/usb/host/ehci-hcd.c (ffffffff81788a87)
Location: drivers/usb/host/ehci.h:266
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:qh_schedule
  - drivers/usb/host/ehci-hcd.c:qh_link_periodic
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer
  - drivers/usb/host/ehci-hcd.c:qh_refresh
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:ehci_port_power
  - drivers/usb/host/ehci-hcd.c:ehci_port_handed_over
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_controller_death
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
```
```
In drivers/usb/host/ehci-pci.c (ffffffff8178d265)
Location: drivers/usb/host/ehci.h:266
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
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
In drivers/usb/host/ehci-hcd.c (ffffffff817b11b7)
Location: drivers/usb/host/ehci.h:266
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:qh_schedule
  - drivers/usb/host/ehci-hcd.c:qh_link_periodic
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer
  - drivers/usb/host/ehci-hcd.c:qh_refresh
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:ehci_port_power
  - drivers/usb/host/ehci-hcd.c:ehci_port_handed_over
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_controller_death
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
```
```
In drivers/usb/host/ehci-pci.c (ffffffff817b3a65)
Location: drivers/usb/host/ehci.h:266
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
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
In drivers/usb/host/ehci-hcd.c (ffffffff817ef0a7)
Location: drivers/usb/host/ehci.h:266
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:qh_schedule
  - drivers/usb/host/ehci-hcd.c:qh_link_periodic
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer
  - drivers/usb/host/ehci-hcd.c:qh_refresh
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:ehci_port_power
  - drivers/usb/host/ehci-hcd.c:ehci_port_handed_over
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
```
```
In drivers/usb/host/ehci-pci.c (ffffffff817f3273)
Location: drivers/usb/host/ehci.h:266
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
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
In drivers/usb/host/ehci-hcd.c (ffffffff8181ff87)
Location: drivers/usb/host/ehci.h:266
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:qh_schedule
  - drivers/usb/host/ehci-hcd.c:qh_link_periodic
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer
  - drivers/usb/host/ehci-hcd.c:qh_refresh
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:ehci_port_power
  - drivers/usb/host/ehci-hcd.c:ehci_port_handed_over
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
```
```
In drivers/usb/host/ehci-pci.c (ffffffff81824093)
Location: drivers/usb/host/ehci.h:266
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
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
In drivers/usb/host/ehci-hcd.c (ffffffff818f1ce6)
Location: drivers/usb/host/ehci.h:266
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_init
  - drivers/usb/host/ehci-hcd.c:ehci_init
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:sitd_link_urb
  - drivers/usb/host/ehci-hcd.c:sitd_link_urb
  - drivers/usb/host/ehci-hcd.c:sitd_link_urb
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:itd_link_urb
  - drivers/usb/host/ehci-hcd.c:itd_link_urb
  - drivers/usb/host/ehci-hcd.c:itd_link_urb
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:iso_stream_init
  - drivers/usb/host/ehci-hcd.c:iso_stream_init
  - drivers/usb/host/ehci-hcd.c:qh_schedule
  - drivers/usb/host/ehci-hcd.c:end_unlink_intr
  - drivers/usb/host/ehci-hcd.c:qh_unlink_periodic
  - drivers/usb/host/ehci-hcd.c:qh_link_periodic
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer
  - drivers/usb/host/ehci-hcd.c:qh_refresh
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:qh_destroy
  - drivers/usb/host/ehci-hcd.c:ehci_port_handed_over
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_handover_companion_ports
  - drivers/usb/host/ehci-hcd.c:ehci_handover_companion_ports
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
```
```
In drivers/usb/host/ehci-pci.c (ffffffff818f5c9c)
Location: drivers/usb/host/ehci.h:266
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_reinit
```
```
In drivers/usb/host/ehci-platform.c (ffffffff818f6433)
Location: drivers/usb/host/ehci.h:266
Inline: True
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
In drivers/usb/host/ehci-hcd.c (ffffffff818fac06)
Location: drivers/usb/host/ehci.h:266
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_init
  - drivers/usb/host/ehci-hcd.c:ehci_init
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:sitd_link_urb
  - drivers/usb/host/ehci-hcd.c:sitd_link_urb
  - drivers/usb/host/ehci-hcd.c:sitd_link_urb
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:itd_link_urb
  - drivers/usb/host/ehci-hcd.c:itd_link_urb
  - drivers/usb/host/ehci-hcd.c:itd_link_urb
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:iso_stream_init
  - drivers/usb/host/ehci-hcd.c:iso_stream_init
  - drivers/usb/host/ehci-hcd.c:qh_schedule
  - drivers/usb/host/ehci-hcd.c:end_unlink_intr
  - drivers/usb/host/ehci-hcd.c:qh_unlink_periodic
  - drivers/usb/host/ehci-hcd.c:qh_link_periodic
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer
  - drivers/usb/host/ehci-hcd.c:qh_refresh
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:qh_destroy
  - drivers/usb/host/ehci-hcd.c:ehci_port_handed_over
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_handover_companion_ports
  - drivers/usb/host/ehci-hcd.c:ehci_handover_companion_ports
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
```
```
In drivers/usb/host/ehci-pci.c (ffffffff81c2040a)
Location: drivers/usb/host/ehci.h:266
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_reinit
```
```
In drivers/usb/host/ehci-platform.c (ffffffff818fefe3)
Location: drivers/usb/host/ehci.h:266
Inline: True
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
In drivers/usb/host/ehci-hcd.c (ffffffff818df4fc)
Location: drivers/usb/host/ehci.h:267
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_init
  - drivers/usb/host/ehci-hcd.c:ehci_init
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:sitd_link_urb
  - drivers/usb/host/ehci-hcd.c:sitd_link_urb
  - drivers/usb/host/ehci-hcd.c:sitd_link_urb
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:itd_link_urb
  - drivers/usb/host/ehci-hcd.c:itd_link_urb
  - drivers/usb/host/ehci-hcd.c:itd_link_urb
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:iso_stream_init
  - drivers/usb/host/ehci-hcd.c:iso_stream_init
  - drivers/usb/host/ehci-hcd.c:qh_schedule
  - drivers/usb/host/ehci-hcd.c:qh_unlink_periodic
  - drivers/usb/host/ehci-hcd.c:qh_link_periodic
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer
  - drivers/usb/host/ehci-hcd.c:qh_refresh
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:qh_destroy
  - drivers/usb/host/ehci-hcd.c:ehci_port_handed_over
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_handover_companion_ports
  - drivers/usb/host/ehci-hcd.c:ehci_handover_companion_ports
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
```
```
In drivers/usb/host/ehci-pci.c (ffffffff81c12470)
Location: drivers/usb/host/ehci.h:267
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_reinit
```
```
In drivers/usb/host/ehci-platform.c (ffffffff818e2749)
Location: drivers/usb/host/ehci.h:267
Inline: True
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
In drivers/usb/host/ehci-hcd.c (ffffffff8197aecc)
Location: drivers/usb/host/ehci.h:268
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_init
  - drivers/usb/host/ehci-hcd.c:ehci_init
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:sitd_link_urb
  - drivers/usb/host/ehci-hcd.c:sitd_link_urb
  - drivers/usb/host/ehci-hcd.c:sitd_link_urb
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:itd_link_urb
  - drivers/usb/host/ehci-hcd.c:itd_link_urb
  - drivers/usb/host/ehci-hcd.c:itd_link_urb
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:iso_stream_init
  - drivers/usb/host/ehci-hcd.c:iso_stream_init
  - drivers/usb/host/ehci-hcd.c:qh_schedule
  - drivers/usb/host/ehci-hcd.c:qh_unlink_periodic
  - drivers/usb/host/ehci-hcd.c:qh_link_periodic
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer
  - drivers/usb/host/ehci-hcd.c:qh_refresh
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:qh_destroy
  - drivers/usb/host/ehci-hcd.c:ehci_port_handed_over
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_handover_companion_ports
  - drivers/usb/host/ehci-hcd.c:ehci_handover_companion_ports
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
```
```
In drivers/usb/host/ehci-pci.c (ffffffff81d1ee57)
Location: drivers/usb/host/ehci.h:268
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_reinit
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8197e856)
Location: drivers/usb/host/ehci.h:268
Inline: True
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
In drivers/usb/host/ehci-hcd.c (ffffffff81ad5841)
Location: drivers/usb/host/ehci.h:269
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_handover_companion_ports
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
```
```
In drivers/usb/host/ehci-pci.c (0)
Location: drivers/usb/host/ehci.h:269
Inline: True
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: drivers/usb/host/ehci.h:269
Inline: True
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
In drivers/usb/host/ehci-hcd.c (ffffffff81c60841)
Location: drivers/usb/host/ehci.h:269
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_handover_companion_ports
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
```
```
In drivers/usb/host/ehci-pci.c (0)
Location: drivers/usb/host/ehci.h:269
Inline: True
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: drivers/usb/host/ehci.h:269
Inline: True
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
In drivers/usb/host/ehci-hcd.c (ffffffff81cc7c01)
Location: drivers/usb/host/ehci.h:269
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_handover_companion_ports
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
```
```
In drivers/usb/host/ehci-pci.c (0)
Location: drivers/usb/host/ehci.h:269
Inline: True
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: drivers/usb/host/ehci.h:269
Inline: True
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
In drivers/usb/host/ehci-hcd.c (ffffffff81d7d141)
Location: drivers/usb/host/ehci.h:270
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_handover_companion_ports
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
```
```
In drivers/usb/host/ehci-pci.c (0)
Location: drivers/usb/host/ehci.h:270
Inline: True
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: drivers/usb/host/ehci.h:270
Inline: True
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
In drivers/usb/host/ehci-hcd.c (ffff800010a5d598)
Location: drivers/usb/host/ehci.h:266
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:qh_schedule
  - drivers/usb/host/ehci-hcd.c:qh_link_periodic
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer
  - drivers/usb/host/ehci-hcd.c:qh_refresh
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:ehci_port_power
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
```
```
In drivers/usb/host/ehci-pci.c (ffff800010a5e65c)
Location: drivers/usb/host/ehci.h:266
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
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
In drivers/usb/host/ehci-hcd.c (c0b29ddc)
Location: drivers/usb/host/ehci.h:266
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:qh_schedule
  - drivers/usb/host/ehci-hcd.c:qh_link_periodic
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:qh_refresh
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:ehci_port_power
  - drivers/usb/host/ehci-hcd.c:ehci_port_handed_over
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
```
```
In drivers/usb/host/ehci-pci.c (c0b2fa10)
Location: drivers/usb/host/ehci.h:266
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
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
In drivers/usb/host/ehci-hcd.c (c000000000b1c3e0)
Location: drivers/usb/host/ehci.h:266
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_ppc_of_probe
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:qh_schedule
  - drivers/usb/host/ehci-hcd.c:qh_link_periodic
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer
  - drivers/usb/host/ehci-hcd.c:qh_refresh
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:ehci_port_power
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
```
```
In drivers/usb/host/ehci-pci.c (c000000000b2c6fc)
Location: drivers/usb/host/ehci.h:266
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
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
In drivers/usb/host/ehci-hcd.c (ffffffe000677332)
Location: drivers/usb/host/ehci.h:266
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:qh_schedule
  - drivers/usb/host/ehci-hcd.c:qh_link_periodic
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:qh_refresh
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:ehci_port_power
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
```
```
In drivers/usb/host/ehci-pci.c (ffffffe000679564)
Location: drivers/usb/host/ehci.h:266
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
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
In drivers/usb/host/ehci-hcd.c (ffffffff817d8367)
Location: drivers/usb/host/ehci.h:266
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:qh_schedule
  - drivers/usb/host/ehci-hcd.c:qh_link_periodic
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer
  - drivers/usb/host/ehci-hcd.c:qh_refresh
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:ehci_port_power
  - drivers/usb/host/ehci-hcd.c:ehci_port_handed_over
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
```
```
In drivers/usb/host/ehci-pci.c (ffffffff817dc473)
Location: drivers/usb/host/ehci.h:266
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81814e07)
Location: drivers/usb/host/ehci.h:266
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:qh_schedule
  - drivers/usb/host/ehci-hcd.c:qh_link_periodic
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer
  - drivers/usb/host/ehci-hcd.c:qh_refresh
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:ehci_port_power
  - drivers/usb/host/ehci-hcd.c:ehci_port_handed_over
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
```
```
In drivers/usb/host/ehci-pci.c (ffffffff81818f13)
Location: drivers/usb/host/ehci.h:266
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
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
In drivers/usb/host/ehci-hcd.c (ffffffff8182e1fe)
Location: drivers/usb/host/ehci.h:266
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:qh_schedule
  - drivers/usb/host/ehci-hcd.c:qh_link_periodic
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_urb_done
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer
  - drivers/usb/host/ehci-hcd.c:qh_refresh
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:ehci_port_power
  - drivers/usb/host/ehci-hcd.c:ehci_port_handed_over
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
```
```
In drivers/usb/host/ehci-pci.c (ffffffff81832f03)
Location: drivers/usb/host/ehci.h:266
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
</details>
</li>
</ul>

## Differences
