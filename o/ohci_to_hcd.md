# Function: <code>ohci_to_hcd</code>

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
In drivers/usb/host/ohci-hcd.c (0)
Location: drivers/usb/host/ohci.h:482
Inline: True
```
```
In drivers/usb/host/ohci-pci.c (0)
Location: drivers/usb/host/ohci.h:482
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
In drivers/usb/host/ohci-hcd.c (ffffffff816a1b7b)
Location: drivers/usb/host/ohci.h:482
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_init
```
```
In drivers/usb/host/ohci-pci.c (0)
Location: drivers/usb/host/ohci.h:482
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
In drivers/usb/host/ohci-hcd.c (ffffffff816d07fb)
Location: drivers/usb/host/ohci.h:482
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_init
```
```
In drivers/usb/host/ohci-pci.c (0)
Location: drivers/usb/host/ohci.h:482
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
In drivers/usb/host/ohci-hcd.c (ffffffff816e4e8d)
Location: drivers/usb/host/ohci.h:483
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_init
```
```
In drivers/usb/host/ohci-pci.c (0)
Location: drivers/usb/host/ohci.h:483
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
In drivers/usb/host/ohci-hcd.c (ffffffff81751698)
Location: drivers/usb/host/ohci.h:484
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_init
```
```
In drivers/usb/host/ohci-pci.c (0)
Location: drivers/usb/host/ohci.h:484
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
In drivers/usb/host/ohci-hcd.c (ffffffff8179392f)
Location: drivers/usb/host/ohci.h:481
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:ohci_dump
  - drivers/usb/host/ohci-hcd.c:ohci_dump
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_intr_mask
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
```
```
In drivers/usb/host/ohci-pci.c (ffffffff81793e3f)
Location: drivers/usb/host/ohci.h:481
Inline: True
Inline callers:
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd700
  - drivers/usb/host/ohci-pci.c:ohci_quirk_nec_worker
  - drivers/usb/host/ohci-pci.c:ohci_quirk_toshiba_scc
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd756
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
In drivers/usb/host/ohci-hcd.c (ffffffff817b9eff)
Location: drivers/usb/host/ohci.h:481
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:ohci_dump
  - drivers/usb/host/ohci-hcd.c:ohci_dump
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_intr_mask
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
```
```
In drivers/usb/host/ohci-pci.c (ffffffff817ba40f)
Location: drivers/usb/host/ohci.h:481
Inline: True
Inline callers:
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd700
  - drivers/usb/host/ohci-pci.c:ohci_quirk_nec_worker
  - drivers/usb/host/ohci-pci.c:ohci_quirk_toshiba_scc
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd756
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
In drivers/usb/host/ohci-hcd.c (ffffffff817f89f3)
Location: drivers/usb/host/ohci.h:483
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/ohci-hcd.c:td_alloc
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:ohci_dump
  - drivers/usb/host/ohci-hcd.c:ohci_dump
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_intr_mask
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
```
```
In drivers/usb/host/ohci-pci.c (ffffffff817f9d2f)
Location: drivers/usb/host/ohci.h:483
Inline: True
Inline callers:
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd700
  - drivers/usb/host/ohci-pci.c:ohci_quirk_nec_worker
  - drivers/usb/host/ohci-pci.c:ohci_quirk_toshiba_scc
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd756
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
In drivers/usb/host/ohci-hcd.c (ffffffff81829853)
Location: drivers/usb/host/ohci.h:483
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/ohci-hcd.c:td_alloc
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:ohci_dump
  - drivers/usb/host/ohci-hcd.c:ohci_dump
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_intr_mask
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
```
```
In drivers/usb/host/ohci-pci.c (ffffffff8182ab6f)
Location: drivers/usb/host/ohci.h:483
Inline: True
Inline callers:
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd700
  - drivers/usb/host/ohci-pci.c:ohci_quirk_nec_worker
  - drivers/usb/host/ohci-pci.c:ohci_quirk_toshiba_scc
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd756
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
In drivers/usb/host/ohci-hcd.c (ffffffff818fc363)
Location: drivers/usb/host/ohci.h:483
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:ed_halted
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:periodic_unlink
  - drivers/usb/host/ohci-hcd.c:periodic_unlink
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:periodic_link
  - drivers/usb/host/ohci-hcd.c:periodic_link
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/ohci-hcd.c:td_alloc
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:ohci_dump
  - drivers/usb/host/ohci-hcd.c:ohci_dump
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_intr_mask
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_root_hub_state_changes
  - drivers/usb/host/ohci-hcd.c:ohci_root_hub_state_changes
  - drivers/usb/host/ohci-hcd.c:ohci_root_hub_state_changes
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
```
```
In drivers/usb/host/ohci-pci.c (ffffffff818fc9f2)
Location: drivers/usb/host/ohci.h:483
Inline: True
Inline callers:
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd700
  - drivers/usb/host/ohci-pci.c:ohci_quirk_nec_worker
  - drivers/usb/host/ohci-pci.c:ohci_quirk_toshiba_scc
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd756
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
In drivers/usb/host/ohci-hcd.c (ffffffff81904ef3)
Location: drivers/usb/host/ohci.h:483
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:ed_halted
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:periodic_unlink
  - drivers/usb/host/ohci-hcd.c:periodic_unlink
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:periodic_link
  - drivers/usb/host/ohci-hcd.c:periodic_link
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/ohci-hcd.c:td_alloc
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:ohci_dump
  - drivers/usb/host/ohci-hcd.c:ohci_dump
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_intr_mask
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_root_hub_state_changes
  - drivers/usb/host/ohci-hcd.c:ohci_root_hub_state_changes
  - drivers/usb/host/ohci-hcd.c:ohci_root_hub_state_changes
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
```
```
In drivers/usb/host/ohci-pci.c (ffffffff81905362)
Location: drivers/usb/host/ohci.h:483
Inline: True
Inline callers:
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd700
  - drivers/usb/host/ohci-pci.c:ohci_quirk_nec_worker
  - drivers/usb/host/ohci-pci.c:ohci_quirk_toshiba_scc
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd756
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
In drivers/usb/host/ohci-hcd.c (ffffffff818e86ac)
Location: drivers/usb/host/ohci.h:483
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:ed_halted
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/ohci-hcd.c:td_alloc
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:ohci_dump
  - drivers/usb/host/ohci-hcd.c:ohci_dump
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_intr_mask
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_root_hub_state_changes
  - drivers/usb/host/ohci-hcd.c:ohci_root_hub_state_changes
  - drivers/usb/host/ohci-hcd.c:ohci_root_hub_state_changes
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
```
```
In drivers/usb/host/ohci-pci.c (ffffffff818e8b52)
Location: drivers/usb/host/ohci.h:483
Inline: True
Inline callers:
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd700
  - drivers/usb/host/ohci-pci.c:ohci_quirk_nec_worker
  - drivers/usb/host/ohci-pci.c:ohci_quirk_toshiba_scc
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd756
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
In drivers/usb/host/ohci-hcd.c (ffffffff81984afc)
Location: drivers/usb/host/ohci.h:483
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:ed_halted
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/ohci-hcd.c:td_alloc
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:ohci_dump
  - drivers/usb/host/ohci-hcd.c:ohci_dump
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_intr_mask
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_root_hub_state_changes
  - drivers/usb/host/ohci-hcd.c:ohci_root_hub_state_changes
  - drivers/usb/host/ohci-hcd.c:ohci_root_hub_state_changes
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
```
```
In drivers/usb/host/ohci-pci.c (ffffffff81984f5f)
Location: drivers/usb/host/ohci.h:483
Inline: True
Inline callers:
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd700
  - drivers/usb/host/ohci-pci.c:ohci_quirk_nec_worker
  - drivers/usb/host/ohci-pci.c:ohci_quirk_toshiba_scc
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd756
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
In drivers/usb/host/ohci-hcd.c (ffffffff81eeab11)
Location: drivers/usb/host/ohci.h:483
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:ohci_root_hub_state_changes
```
```
In drivers/usb/host/ohci-pci.c (0)
Location: drivers/usb/host/ohci.h:483
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
In drivers/usb/host/ohci-hcd.c (ffffffff81c69da2)
Location: drivers/usb/host/ohci.h:483
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:ohci_root_hub_state_changes
```
```
In drivers/usb/host/ohci-pci.c (0)
Location: drivers/usb/host/ohci.h:483
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
In drivers/usb/host/ohci-hcd.c (ffffffff81cd1146)
Location: drivers/usb/host/ohci.h:483
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:ohci_root_hub_state_changes
```
```
In drivers/usb/host/ohci-pci.c (0)
Location: drivers/usb/host/ohci.h:483
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
In drivers/usb/host/ohci-hcd.c (ffffffff81d86109)
Location: drivers/usb/host/ohci.h:483
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:ohci_root_hub_state_changes
```
```
In drivers/usb/host/ohci-pci.c (0)
Location: drivers/usb/host/ohci.h:483
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
In drivers/usb/host/ohci-hcd.c (ffff800010a65d40)
Location: drivers/usb/host/ohci.h:483
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/ohci-hcd.c:td_alloc
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:ohci_dump
  - drivers/usb/host/ohci-hcd.c:ohci_dump
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_intr_mask
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
```
```
In drivers/usb/host/ohci-pci.c (ffff800010a66780)
Location: drivers/usb/host/ohci.h:483
Inline: True
Inline callers:
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd700
  - drivers/usb/host/ohci-pci.c:ohci_quirk_nec_worker
  - drivers/usb/host/ohci-pci.c:ohci_quirk_toshiba_scc
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd756
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
In drivers/usb/host/ohci-hcd.c (c0b36c08)
Location: drivers/usb/host/ohci.h:483
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/ohci-hcd.c:td_alloc
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:ohci_dump
  - drivers/usb/host/ohci-hcd.c:ohci_dump
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_intr_mask
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
```
```
In drivers/usb/host/ohci-pci.c (c0b37fe4)
Location: drivers/usb/host/ohci.h:483
Inline: True
Inline callers:
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd700
  - drivers/usb/host/ohci-pci.c:ohci_quirk_nec_worker
  - drivers/usb/host/ohci-pci.c:ohci_quirk_toshiba_scc
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd756
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
In drivers/usb/host/ohci-hcd.c (c000000000b358d0)
Location: drivers/usb/host/ohci.h:483
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/ohci-hcd.c:td_alloc
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:ohci_dump
  - drivers/usb/host/ohci-hcd.c:ohci_dump
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_intr_mask
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
```
```
In drivers/usb/host/ohci-pci.c (c000000000b37070)
Location: drivers/usb/host/ohci.h:483
Inline: True
Inline callers:
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd700
  - drivers/usb/host/ohci-pci.c:ohci_quirk_nec_worker
  - drivers/usb/host/ohci-pci.c:ohci_quirk_toshiba_scc
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd756
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
In drivers/usb/host/ohci-hcd.c (ffffffe00068006a)
Location: drivers/usb/host/ohci.h:483
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/ohci-hcd.c:td_alloc
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:ohci_dump
  - drivers/usb/host/ohci-hcd.c:ohci_dump
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_intr_mask
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
```
```
In drivers/usb/host/ohci-pci.c (ffffffe000680782)
Location: drivers/usb/host/ohci.h:483
Inline: True
Inline callers:
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd700
  - drivers/usb/host/ohci-pci.c:ohci_quirk_nec_worker
  - drivers/usb/host/ohci-pci.c:ohci_quirk_toshiba_scc
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd756
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
In drivers/usb/host/ohci-hcd.c (ffffffff817e1c33)
Location: drivers/usb/host/ohci.h:483
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/ohci-hcd.c:td_alloc
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:ohci_dump
  - drivers/usb/host/ohci-hcd.c:ohci_dump
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_intr_mask
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
```
```
In drivers/usb/host/ohci-pci.c (ffffffff817e2f4f)
Location: drivers/usb/host/ohci.h:483
Inline: True
Inline callers:
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd700
  - drivers/usb/host/ohci-pci.c:ohci_quirk_nec_worker
  - drivers/usb/host/ohci-pci.c:ohci_quirk_toshiba_scc
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd756
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
In drivers/usb/host/ohci-hcd.c (ffffffff8181e6d3)
Location: drivers/usb/host/ohci.h:483
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/ohci-hcd.c:td_alloc
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:ohci_dump
  - drivers/usb/host/ohci-hcd.c:ohci_dump
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_intr_mask
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
```
```
In drivers/usb/host/ohci-pci.c (ffffffff8181f9ef)
Location: drivers/usb/host/ohci.h:483
Inline: True
Inline callers:
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd700
  - drivers/usb/host/ohci-pci.c:ohci_quirk_nec_worker
  - drivers/usb/host/ohci-pci.c:ohci_quirk_toshiba_scc
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd756
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
In drivers/usb/host/ohci-hcd.c (ffffffff818383ba)
Location: drivers/usb/host/ohci.h:483
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/ohci-hcd.c:td_alloc
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:ohci_dump
  - drivers/usb/host/ohci-hcd.c:ohci_dump
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_intr_mask
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
```
```
In drivers/usb/host/ohci-pci.c (ffffffff8183995f)
Location: drivers/usb/host/ohci.h:483
Inline: True
Inline callers:
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd700
  - drivers/usb/host/ohci-pci.c:ohci_quirk_nec_worker
  - drivers/usb/host/ohci-pci.c:ohci_quirk_toshiba_scc
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd756
```
</details>
</li>
</ul>

## Differences
