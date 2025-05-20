# Function: <code>uhci_writew</code>

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
In drivers/usb/host/uhci-hcd.c (ffffffff8164468e)
Location: drivers/usb/host/uhci-hcd.h:516
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
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
In drivers/usb/host/uhci-hcd.c (ffffffff816aa4e5)
Location: drivers/usb/host/uhci-hcd.h:516
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
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
In drivers/usb/host/uhci-hcd.c (ffffffff816d8625)
Location: drivers/usb/host/uhci-hcd.h:516
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
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
In drivers/usb/host/uhci-hcd.c (ffffffff816ecb15)
Location: drivers/usb/host/uhci-hcd.h:525
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
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
In drivers/usb/host/uhci-hcd.c (ffffffff8175930b)
Location: drivers/usb/host/uhci-hcd.h:526
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
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
In drivers/usb/host/uhci-hcd.c (ffffffff817993d4)
Location: drivers/usb/host/uhci-hcd.h:529
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
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
In drivers/usb/host/uhci-hcd.c (ffffffff817bfd44)
Location: drivers/usb/host/uhci-hcd.h:529
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
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
In drivers/usb/host/uhci-hcd.c (ffffffff817ff5f8)
Location: drivers/usb/host/uhci-hcd.h:529
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
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
In drivers/usb/host/uhci-hcd.c (ffffffff81830458)
Location: drivers/usb/host/uhci-hcd.h:529
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
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
In drivers/usb/host/uhci-hcd.c (ffffffff81901338)
Location: drivers/usb/host/uhci-hcd.h:529
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
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
In drivers/usb/host/uhci-hcd.c (ffffffff81909c08)
Location: drivers/usb/host/uhci-hcd.h:529
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
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
In drivers/usb/host/uhci-hcd.c (ffffffff818ee328)
Location: drivers/usb/host/uhci-hcd.h:525
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
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
In drivers/usb/host/uhci-hcd.c (ffffffff8198aaf8)
Location: drivers/usb/host/uhci-hcd.h:525
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
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
In drivers/usb/host/uhci-hcd.c (ffffffff81ae4994)
Location: drivers/usb/host/uhci-hcd.h:525
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
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
In drivers/usb/host/uhci-hcd.c (ffffffff81c70554)
Location: drivers/usb/host/uhci-hcd.h:525
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
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
In drivers/usb/host/uhci-hcd.c (ffffffff81cd7b45)
Location: drivers/usb/host/uhci-hcd.h:533
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
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
In drivers/usb/host/uhci-hcd.c (ffffffff81d8cb55)
Location: drivers/usb/host/uhci-hcd.h:533
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
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
In drivers/usb/host/uhci-hcd.c (ffff800010a6acb0)
Location: drivers/usb/host/uhci-hcd.h:529
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:start_rh
  - drivers/usb/host/uhci-hcd.c:start_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:configure_hc
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
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
In drivers/usb/host/uhci-hcd.c (c0b3f43c)
Location: drivers/usb/host/uhci-hcd.h:633
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:start_rh
  - drivers/usb/host/uhci-hcd.c:start_rh
  - drivers/usb/host/uhci-hcd.c:start_rh
  - drivers/usb/host/uhci-hcd.c:start_rh
  - drivers/usb/host/uhci-hcd.c:start_rh
  - drivers/usb/host/uhci-hcd.c:start_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:configure_hc
  - drivers/usb/host/uhci-hcd.c:configure_hc
  - drivers/usb/host/uhci-hcd.c:uhci_generic_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_generic_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_generic_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_generic_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_generic_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_generic_reset_hc
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
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
In drivers/usb/host/uhci-hcd.c (c000000000b3e504)
Location: drivers/usb/host/uhci-hcd.h:529
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:start_rh
  - drivers/usb/host/uhci-hcd.c:start_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:configure_hc
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
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
In drivers/usb/host/uhci-hcd.c (ffffffe00068481c)
Location: drivers/usb/host/uhci-hcd.h:529
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:configure_hc
  - drivers/usb/host/uhci-hcd.c:uhci_hc_died
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
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
In drivers/usb/host/uhci-hcd.c (ffffffff817e8838)
Location: drivers/usb/host/uhci-hcd.h:529
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
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
In drivers/usb/host/uhci-hcd.c (ffffffff818252d8)
Location: drivers/usb/host/uhci-hcd.h:529
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
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
In drivers/usb/host/uhci-hcd.c (ffffffff8183ad18)
Location: drivers/usb/host/uhci-hcd.h:529
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
```
</details>
</li>
</ul>

## Differences
