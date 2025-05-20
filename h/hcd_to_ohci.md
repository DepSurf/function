# Function: <code>hcd_to_ohci</code>

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
In drivers/usb/host/ohci-hcd.c (ffffffff8163fa11)
Location: drivers/usb/host/ohci.h:478
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_irq
```
```
In drivers/usb/host/ohci-pci.c (0)
Location: drivers/usb/host/ohci.h:478
Inline: True
```
```
In drivers/usb/host/ohci-platform.c (0)
Location: drivers/usb/host/ohci.h:478
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
In drivers/usb/host/ohci-hcd.c (ffffffff816a414c)
Location: drivers/usb/host/ohci.h:478
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
```
```
In drivers/usb/host/ohci-pci.c (0)
Location: drivers/usb/host/ohci.h:478
Inline: True
```
```
In drivers/usb/host/ohci-platform.c (0)
Location: drivers/usb/host/ohci.h:478
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
In drivers/usb/host/ohci-hcd.c (ffffffff816d224c)
Location: drivers/usb/host/ohci.h:478
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
```
```
In drivers/usb/host/ohci-pci.c (0)
Location: drivers/usb/host/ohci.h:478
Inline: True
```
```
In drivers/usb/host/ohci-platform.c (0)
Location: drivers/usb/host/ohci.h:478
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
In drivers/usb/host/ohci-hcd.c (ffffffff816e696c)
Location: drivers/usb/host/ohci.h:479
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
```
```
In drivers/usb/host/ohci-pci.c (0)
Location: drivers/usb/host/ohci.h:479
Inline: True
```
```
In drivers/usb/host/ohci-platform.c (0)
Location: drivers/usb/host/ohci.h:479
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
In drivers/usb/host/ohci-hcd.c (ffffffff8175319c)
Location: drivers/usb/host/ohci.h:480
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
```
```
In drivers/usb/host/ohci-pci.c (0)
Location: drivers/usb/host/ohci.h:480
Inline: True
```
```
In drivers/usb/host/ohci-platform.c (0)
Location: drivers/usb/host/ohci.h:480
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
In drivers/usb/host/ohci-hcd.c (ffffffff81793825)
Location: drivers/usb/host/ohci.h:477
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
```
```
In drivers/usb/host/ohci-pci.c (0)
Location: drivers/usb/host/ohci.h:477
Inline: True
```
```
In drivers/usb/host/ohci-platform.c (0)
Location: drivers/usb/host/ohci.h:477
Inline: True
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
In drivers/usb/host/ohci-hcd.c (ffffffff817b9df5)
Location: drivers/usb/host/ohci.h:477
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
```
```
In drivers/usb/host/ohci-pci.c (0)
Location: drivers/usb/host/ohci.h:477
Inline: True
```
```
In drivers/usb/host/ohci-platform.c (0)
Location: drivers/usb/host/ohci.h:477
Inline: True
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
In drivers/usb/host/ohci-hcd.c (ffffffff817f88e5)
Location: drivers/usb/host/ohci.h:479
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
```
```
In drivers/usb/host/ohci-pci.c (0)
Location: drivers/usb/host/ohci.h:479
Inline: True
```
```
In drivers/usb/host/ohci-platform.c (0)
Location: drivers/usb/host/ohci.h:479
Inline: True
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
In drivers/usb/host/ohci-hcd.c (ffffffff81829745)
Location: drivers/usb/host/ohci.h:479
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
```
```
In drivers/usb/host/ohci-pci.c (0)
Location: drivers/usb/host/ohci.h:479
Inline: True
```
```
In drivers/usb/host/ohci-platform.c (0)
Location: drivers/usb/host/ohci.h:479
Inline: True
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
In drivers/usb/host/ohci-hcd.c (ffffffff818fc255)
Location: drivers/usb/host/ohci.h:479
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
```
```
In drivers/usb/host/ohci-pci.c (0)
Location: drivers/usb/host/ohci.h:479
Inline: True
```
```
In drivers/usb/host/ohci-platform.c (0)
Location: drivers/usb/host/ohci.h:479
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
In drivers/usb/host/ohci-hcd.c (ffffffff81904de5)
Location: drivers/usb/host/ohci.h:479
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
```
```
In drivers/usb/host/ohci-pci.c (0)
Location: drivers/usb/host/ohci.h:479
Inline: True
```
```
In drivers/usb/host/ohci-platform.c (0)
Location: drivers/usb/host/ohci.h:479
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
In drivers/usb/host/ohci-hcd.c (ffffffff818e8595)
Location: drivers/usb/host/ohci.h:479
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
```
```
In drivers/usb/host/ohci-pci.c (0)
Location: drivers/usb/host/ohci.h:479
Inline: True
```
```
In drivers/usb/host/ohci-platform.c (0)
Location: drivers/usb/host/ohci.h:479
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
In drivers/usb/host/ohci-hcd.c (ffffffff819849e5)
Location: drivers/usb/host/ohci.h:479
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
```
```
In drivers/usb/host/ohci-pci.c (0)
Location: drivers/usb/host/ohci.h:479
Inline: True
```
```
In drivers/usb/host/ohci-platform.c (0)
Location: drivers/usb/host/ohci.h:479
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
In drivers/usb/host/ohci-hcd.c (ffffffff81adff45)
Location: drivers/usb/host/ohci.h:479
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
```
```
In drivers/usb/host/ohci-pci.c (0)
Location: drivers/usb/host/ohci.h:479
Inline: True
```
```
In drivers/usb/host/ohci-platform.c (0)
Location: drivers/usb/host/ohci.h:479
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
In drivers/usb/host/ohci-hcd.c (ffffffff81c6b575)
Location: drivers/usb/host/ohci.h:479
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
```
```
In drivers/usb/host/ohci-pci.c (0)
Location: drivers/usb/host/ohci.h:479
Inline: True
```
```
In drivers/usb/host/ohci-platform.c (0)
Location: drivers/usb/host/ohci.h:479
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
In drivers/usb/host/ohci-hcd.c (ffffffff81cd2a15)
Location: drivers/usb/host/ohci.h:479
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
```
```
In drivers/usb/host/ohci-pci.c (0)
Location: drivers/usb/host/ohci.h:479
Inline: True
```
```
In drivers/usb/host/ohci-platform.c (0)
Location: drivers/usb/host/ohci.h:479
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
In drivers/usb/host/ohci-hcd.c (ffffffff81d879d5)
Location: drivers/usb/host/ohci.h:479
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
```
```
In drivers/usb/host/ohci-pci.c (0)
Location: drivers/usb/host/ohci.h:479
Inline: True
```
```
In drivers/usb/host/ohci-platform.c (0)
Location: drivers/usb/host/ohci.h:479
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
In drivers/usb/host/ohci-hcd.c (ffff800010a65bb8)
Location: drivers/usb/host/ohci.h:479
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
```
```
In drivers/usb/host/ohci-pci.c (0)
Location: drivers/usb/host/ohci.h:479
Inline: True
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
In drivers/usb/host/ohci-hcd.c (c0b372ac)
Location: drivers/usb/host/ohci.h:479
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_tmio_start
  - drivers/usb/host/ohci-hcd.c:ohci_sm501_start
  - drivers/usb/host/ohci-hcd.c:ohci_sm501_init
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
```
```
In drivers/usb/host/ohci-pci.c (0)
Location: drivers/usb/host/ohci.h:479
Inline: True
```
```
In drivers/usb/host/ohci-exynos.c (0)
Location: drivers/usb/host/ohci.h:479
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
In drivers/usb/host/ohci-hcd.c (c000000000b357a4)
Location: drivers/usb/host/ohci.h:479
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
```
```
In drivers/usb/host/ohci-pci.c (0)
Location: drivers/usb/host/ohci.h:479
Inline: True
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
In drivers/usb/host/ohci-hcd.c (ffffffe00067fee4)
Location: drivers/usb/host/ohci.h:479
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
```
```
In drivers/usb/host/ohci-pci.c (0)
Location: drivers/usb/host/ohci.h:479
Inline: True
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
In drivers/usb/host/ohci-hcd.c (ffffffff817e1b25)
Location: drivers/usb/host/ohci.h:479
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
```
```
In drivers/usb/host/ohci-pci.c (0)
Location: drivers/usb/host/ohci.h:479
Inline: True
```
```
In drivers/usb/host/ohci-platform.c (0)
Location: drivers/usb/host/ohci.h:479
Inline: True
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
In drivers/usb/host/ohci-hcd.c (ffffffff8181e5c5)
Location: drivers/usb/host/ohci.h:479
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
```
```
In drivers/usb/host/ohci-pci.c (0)
Location: drivers/usb/host/ohci.h:479
Inline: True
```
```
In drivers/usb/host/ohci-platform.c (0)
Location: drivers/usb/host/ohci.h:479
Inline: True
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
In drivers/usb/host/ohci-hcd.c (ffffffff818382b5)
Location: drivers/usb/host/ohci.h:479
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
```
```
In drivers/usb/host/ohci-pci.c (0)
Location: drivers/usb/host/ohci.h:479
Inline: True
```
```
In drivers/usb/host/ohci-platform.c (0)
Location: drivers/usb/host/ohci.h:479
Inline: True
```
</details>
</li>
</ul>

## Differences
