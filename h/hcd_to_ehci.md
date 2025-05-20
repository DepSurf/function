# Function: <code>hcd_to_ehci</code>

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
In drivers/usb/host/ehci-hcd.c (ffffffff81633272)
Location: drivers/usb/host/ehci.h:271
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
```
In drivers/usb/host/ehci-pci.c (ffffffff8163ca77)
Location: drivers/usb/host/ehci.h:271
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_resume
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: drivers/usb/host/ehci.h:271
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
In drivers/usb/host/ehci-hcd.c (ffffffff81698dce)
Location: drivers/usb/host/ehci.h:274
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
```
In drivers/usb/host/ehci-pci.c (ffffffff8169d687)
Location: drivers/usb/host/ehci.h:274
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_resume
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: drivers/usb/host/ehci.h:274
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
In drivers/usb/host/ehci-hcd.c (ffffffff816c72fe)
Location: drivers/usb/host/ehci.h:275
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
```
In drivers/usb/host/ehci-pci.c (ffffffff816cb7a7)
Location: drivers/usb/host/ehci.h:275
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_resume
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: drivers/usb/host/ehci.h:275
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
In drivers/usb/host/ehci-hcd.c (ffffffff816dbab0)
Location: drivers/usb/host/ehci.h:275
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
```
In drivers/usb/host/ehci-pci.c (ffffffff816dfee7)
Location: drivers/usb/host/ehci.h:275
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_resume
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: drivers/usb/host/ehci.h:275
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
In drivers/usb/host/ehci-hcd.c (ffffffff817481e0)
Location: drivers/usb/host/ehci.h:262
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
```
In drivers/usb/host/ehci-pci.c (ffffffff8174c6c7)
Location: drivers/usb/host/ehci.h:262
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_resume
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: drivers/usb/host/ehci.h:262
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
In drivers/usb/host/ehci-hcd.c (ffffffff81788995)
Location: drivers/usb/host/ehci.h:262
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
```
In drivers/usb/host/ehci-pci.c (ffffffff8178cfb5)
Location: drivers/usb/host/ehci.h:262
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_resume
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: drivers/usb/host/ehci.h:262
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
In drivers/usb/host/ehci-hcd.c (ffffffff817b10c5)
Location: drivers/usb/host/ehci.h:262
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
```
In drivers/usb/host/ehci-pci.c (ffffffff817b37b5)
Location: drivers/usb/host/ehci.h:262
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_resume
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: drivers/usb/host/ehci.h:262
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
In drivers/usb/host/ehci-hcd.c (ffffffff817eefb5)
Location: drivers/usb/host/ehci.h:262
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
```
In drivers/usb/host/ehci-pci.c (ffffffff817f2dd5)
Location: drivers/usb/host/ehci.h:262
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_resume
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: drivers/usb/host/ehci.h:262
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
In drivers/usb/host/ehci-hcd.c (ffffffff8181fe95)
Location: drivers/usb/host/ehci.h:262
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
```
In drivers/usb/host/ehci-pci.c (ffffffff81823bf5)
Location: drivers/usb/host/ehci.h:262
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_resume
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: drivers/usb/host/ehci.h:262
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
In drivers/usb/host/ehci-hcd.c (ffffffff818f1be5)
Location: drivers/usb/host/ehci.h:262
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_init
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:fill_async_buffer
```
```
In drivers/usb/host/ehci-pci.c (ffffffff818f5715)
Location: drivers/usb/host/ehci.h:262
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_resume
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: drivers/usb/host/ehci.h:262
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
In drivers/usb/host/ehci-hcd.c (ffffffff818fab05)
Location: drivers/usb/host/ehci.h:262
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_init
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:fill_async_buffer
```
```
In drivers/usb/host/ehci-pci.c (ffffffff818fe3f5)
Location: drivers/usb/host/ehci.h:262
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_resume
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: drivers/usb/host/ehci.h:262
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
In drivers/usb/host/ehci-hcd.c (ffffffff818df3f5)
Location: drivers/usb/host/ehci.h:263
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_init
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:fill_async_buffer
```
```
In drivers/usb/host/ehci-pci.c (ffffffff818e1b45)
Location: drivers/usb/host/ehci.h:263
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_resume
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: drivers/usb/host/ehci.h:263
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
In drivers/usb/host/ehci-hcd.c (ffffffff8197adc5)
Location: drivers/usb/host/ehci.h:264
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_init
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:fill_async_buffer
```
```
In drivers/usb/host/ehci-pci.c (ffffffff8197db15)
Location: drivers/usb/host/ehci.h:264
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_resume
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: drivers/usb/host/ehci.h:264
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
In drivers/usb/host/ehci-hcd.c (ffffffff81ad1b05)
Location: drivers/usb/host/ehci.h:265
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_init
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:fill_async_buffer
```
```
In drivers/usb/host/ehci-pci.c (ffffffff81ad9155)
Location: drivers/usb/host/ehci.h:265
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_resume
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: drivers/usb/host/ehci.h:265
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
In drivers/usb/host/ehci-hcd.c (ffffffff81c5c735)
Location: drivers/usb/host/ehci.h:265
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_init
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:fill_async_buffer
```
```
In drivers/usb/host/ehci-pci.c (ffffffff81c640c5)
Location: drivers/usb/host/ehci.h:265
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_resume
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: drivers/usb/host/ehci.h:265
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
In drivers/usb/host/ehci-hcd.c (ffffffff81cc3db5)
Location: drivers/usb/host/ehci.h:265
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_init
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:fill_async_buffer
```
```
In drivers/usb/host/ehci-pci.c (ffffffff81ccb4b5)
Location: drivers/usb/host/ehci.h:265
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_resume
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: drivers/usb/host/ehci.h:265
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
In drivers/usb/host/ehci-hcd.c (ffffffff81d78cc5)
Location: drivers/usb/host/ehci.h:266
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_init
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:fill_async_buffer
```
```
In drivers/usb/host/ehci-pci.c (ffffffff81d803a5)
Location: drivers/usb/host/ehci.h:266
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_resume
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: drivers/usb/host/ehci.h:266
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
In drivers/usb/host/ehci-hcd.c (ffff800010a5d460)
Location: drivers/usb/host/ehci.h:262
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
```
In drivers/usb/host/ehci-pci.c (ffff800010a5e41c)
Location: drivers/usb/host/ehci.h:262
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_resume
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ehci-orion.c (0)
Location: drivers/usb/host/ehci.h:262
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
In drivers/usb/host/ehci-hcd.c (c0b29d0c)
Location: drivers/usb/host/ehci.h:262
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:fill_async_buffer
```
```
In drivers/usb/host/ehci-pci.c (c0b2f7d8)
Location: drivers/usb/host/ehci.h:262
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_resume
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ehci-orion.c (0)
Location: drivers/usb/host/ehci.h:262
Inline: True
```
```
In drivers/usb/host/ehci-exynos.c (0)
Location: drivers/usb/host/ehci.h:262
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
In drivers/usb/host/ehci-hcd.c (c000000000b2435c)
Location: drivers/usb/host/ehci.h:262
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:fill_async_buffer
```
```
In drivers/usb/host/ehci-pci.c (c000000000b2c464)
Location: drivers/usb/host/ehci.h:262
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_resume
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
In drivers/usb/host/ehci-hcd.c (ffffffe0006771e0)
Location: drivers/usb/host/ehci.h:262
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:fill_async_buffer
```
```
In drivers/usb/host/ehci-pci.c (ffffffe00067939e)
Location: drivers/usb/host/ehci.h:262
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_resume
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
In drivers/usb/host/ehci-hcd.c (ffffffff817d8275)
Location: drivers/usb/host/ehci.h:262
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
```
In drivers/usb/host/ehci-pci.c (ffffffff817dbfd5)
Location: drivers/usb/host/ehci.h:262
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_resume
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: drivers/usb/host/ehci.h:262
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
In drivers/usb/host/ehci-hcd.c (ffffffff81814d15)
Location: drivers/usb/host/ehci.h:262
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
```
In drivers/usb/host/ehci-pci.c (ffffffff81818a75)
Location: drivers/usb/host/ehci.h:262
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_resume
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: drivers/usb/host/ehci.h:262
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
In drivers/usb/host/ehci-hcd.c (ffffffff8182e115)
Location: drivers/usb/host/ehci.h:262
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
```
In drivers/usb/host/ehci-pci.c (ffffffff81832a65)
Location: drivers/usb/host/ehci.h:262
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_resume
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: drivers/usb/host/ehci.h:262
Inline: True
```
</details>
</li>
</ul>

## Differences
