# Function: <code>uhci_to_hcd</code>

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
In drivers/usb/host/uhci-hcd.c (ffffffff81645d3e)
Location: drivers/usb/host/uhci-hcd.h:462
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
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
In drivers/usb/host/uhci-hcd.c (ffffffff816a6871)
Location: drivers/usb/host/uhci-hcd.h:462
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
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
In drivers/usb/host/uhci-hcd.c (ffffffff816d4991)
Location: drivers/usb/host/uhci-hcd.h:462
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
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
In drivers/usb/host/uhci-hcd.c (ffffffff816e8e01)
Location: drivers/usb/host/uhci-hcd.h:465
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
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
In drivers/usb/host/uhci-hcd.c (ffffffff817555f1)
Location: drivers/usb/host/uhci-hcd.h:466
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
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
In drivers/usb/host/uhci-hcd.c (ffffffff81799445)
Location: drivers/usb/host/uhci-hcd.h:469
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_check_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_set_next_interrupt
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
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
In drivers/usb/host/uhci-hcd.c (ffffffff817bfdb5)
Location: drivers/usb/host/uhci-hcd.h:469
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_check_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_set_next_interrupt
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
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
In drivers/usb/host/uhci-hcd.c (ffffffff817ff673)
Location: drivers/usb/host/uhci-hcd.h:469
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_check_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_set_next_interrupt
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
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
In drivers/usb/host/uhci-hcd.c (ffffffff818304d3)
Location: drivers/usb/host/uhci-hcd.h:469
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_check_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_set_next_interrupt
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
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
In drivers/usb/host/uhci-hcd.c (ffffffff819013a9)
Location: drivers/usb/host/uhci-hcd.h:469
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:release_uhci
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_submit_isochronous
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_release_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_release_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_release_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_release_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_check_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
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
In drivers/usb/host/uhci-hcd.c (ffffffff81909c79)
Location: drivers/usb/host/uhci-hcd.h:469
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:release_uhci
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_submit_isochronous
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_release_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_release_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_release_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_release_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_check_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
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
In drivers/usb/host/uhci-hcd.c (ffffffff818ee399)
Location: drivers/usb/host/uhci-hcd.h:465
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_check_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
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
In drivers/usb/host/uhci-hcd.c (ffffffff8198ab69)
Location: drivers/usb/host/uhci-hcd.h:465
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_check_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
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
In drivers/usb/host/uhci-hcd.c (ffffffff81ae5270)
Location: drivers/usb/host/uhci-hcd.h:465
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
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
In drivers/usb/host/uhci-hcd.c (ffffffff81c70e90)
Location: drivers/usb/host/uhci-hcd.h:465
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
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
In drivers/usb/host/uhci-hcd.c (ffffffff81cd8470)
Location: drivers/usb/host/uhci-hcd.h:465
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
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
In drivers/usb/host/uhci-hcd.c (ffffffff81d8d480)
Location: drivers/usb/host/uhci-hcd.h:465
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
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
In drivers/usb/host/uhci-hcd.c (ffff800010a6aa50)
Location: drivers/usb/host/uhci-hcd.h:469
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:start_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_check_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_set_next_interrupt
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
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
In drivers/usb/host/uhci-hcd.c (c0b3d1ec)
Location: drivers/usb/host/uhci-hcd.h:469
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:start_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_generic_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_generic_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_generic_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_generic_reset_hc
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_check_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_set_next_interrupt
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
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
In drivers/usb/host/uhci-hcd.c (c000000000b3ca80)
Location: drivers/usb/host/uhci-hcd.h:469
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:start_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_check_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_set_next_interrupt
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
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
In drivers/usb/host/uhci-hcd.c (ffffffe00068490a)
Location: drivers/usb/host/uhci-hcd.h:469
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hc_died
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_check_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_set_next_interrupt
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
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
In drivers/usb/host/uhci-hcd.c (ffffffff817e88b3)
Location: drivers/usb/host/uhci-hcd.h:469
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_check_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_set_next_interrupt
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
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
In drivers/usb/host/uhci-hcd.c (ffffffff81825353)
Location: drivers/usb/host/uhci-hcd.h:469
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_check_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_set_next_interrupt
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
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
In drivers/usb/host/uhci-hcd.c (ffffffff8183ad8a)
Location: drivers/usb/host/uhci-hcd.h:469
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_configure_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_reserve_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_check_bandwidth
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_set_next_interrupt
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
</details>
</li>
</ul>

## Differences
