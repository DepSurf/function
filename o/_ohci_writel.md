# Function: <code>_ohci_writel</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff8163dd68)
Location: drivers/usb/host/ohci.h:572
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff816a417f)
Location: drivers/usb/host/ohci.h:572
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
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
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff816d227f)
Location: drivers/usb/host/ohci.h:572
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
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
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff816e68d8)
Location: drivers/usb/host/ohci.h:573
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
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
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81753108)
Location: drivers/usb/host/ohci.h:574
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
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
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81793858)
Location: drivers/usb/host/ohci.h:571
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
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
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff817b9e28)
Location: drivers/usb/host/ohci.h:571
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
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
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff817f8919)
Location: drivers/usb/host/ohci.h:573
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
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
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81829779)
Location: drivers/usb/host/ohci.h:573
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
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
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff818fc289)
Location: drivers/usb/host/ohci.h:573
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:takeback_td
  - drivers/usb/host/ohci-hcd.c:takeback_td
  - drivers/usb/host/ohci-hcd.c:takeback_td
  - drivers/usb/host/ohci-hcd.c:takeback_td
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
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
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81904e19)
Location: drivers/usb/host/ohci.h:573
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:takeback_td
  - drivers/usb/host/ohci-hcd.c:takeback_td
  - drivers/usb/host/ohci-hcd.c:takeback_td
  - drivers/usb/host/ohci-hcd.c:takeback_td
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
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
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff818e85cc)
Location: drivers/usb/host/ohci.h:573
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
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
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81984a1c)
Location: drivers/usb/host/ohci.h:573
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
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
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81adff7b)
Location: drivers/usb/host/ohci.h:573
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
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
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81c6b5ab)
Location: drivers/usb/host/ohci.h:573
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
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
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81cd2a51)
Location: drivers/usb/host/ohci.h:573
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
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
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81d87a11)
Location: drivers/usb/host/ohci.h:573
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
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
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffff800010a65c30)
Location: drivers/usb/host/ohci.h:573
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:_ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:_ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:_ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_usb_reset
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
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
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (c0b36b40)
Location: drivers/usb/host/ohci.h:573
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:_ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:_ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:_ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
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
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (c000000000b35910)
Location: drivers/usb/host/ohci.h:573
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:_ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:_ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:_ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_usb_reset
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
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
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffe00067ff38)
Location: drivers/usb/host/ohci.h:573
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:_ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:_ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:_ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
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
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff817e1b59)
Location: drivers/usb/host/ohci.h:573
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
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
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff8181e5f9)
Location: drivers/usb/host/ohci.h:573
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
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
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff818382e9)
Location: drivers/usb/host/ohci.h:573
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
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
</details>
</li>
</ul>

## Differences
