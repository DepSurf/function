# Function: <code>hcd_to_xhci</code>

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
In drivers/usb/host/xhci.c (ffffffff8164a6f2)
Location: drivers/usb/host/xhci.h:1680
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_find_raw_port_number
  - drivers/usb/host/xhci.c:xhci_update_device
  - drivers/usb/host/xhci.c:xhci_get_frame
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_update_hub_device
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8165c5ec)
Location: drivers/usb/host/xhci.h:1680
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
```
In drivers/usb/host/xhci-hub.c (ffffffff8165d102)
Location: drivers/usb/host/xhci.h:1680
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_ports
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
```
```
In drivers/usb/host/xhci-pci.c (ffffffff81661d06)
Location: drivers/usb/host/xhci.h:1680
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pme_quirk
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
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
In drivers/usb/host/xhci.c (ffffffff816ae98d)
Location: drivers/usb/host/xhci.h:1697
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_get_frame
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_update_device
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_find_raw_port_number
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816bcdec)
Location: drivers/usb/host/xhci.h:1697
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
```
In drivers/usb/host/xhci-hub.c (ffffffff816bfb0b)
Location: drivers/usb/host/xhci.h:1697
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_ports
```
```
In drivers/usb/host/xhci-pci.c (ffffffff816c1fd6)
Location: drivers/usb/host/xhci.h:1697
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
  - drivers/usb/host/xhci-pci.c:xhci_pme_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
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
In drivers/usb/host/xhci.c (ffffffff816dcb2d)
Location: drivers/usb/host/xhci.h:1694
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_get_frame
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_update_device
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_find_raw_port_number
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816eacfc)
Location: drivers/usb/host/xhci.h:1694
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
```
In drivers/usb/host/xhci-hub.c (ffffffff816ed9db)
Location: drivers/usb/host/xhci.h:1694
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_ports
```
```
In drivers/usb/host/xhci-pci.c (ffffffff816eff36)
Location: drivers/usb/host/xhci.h:1694
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
  - drivers/usb/host/xhci-pci.c:xhci_pme_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
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
In drivers/usb/host/xhci.c (ffffffff816f0f1e)
Location: drivers/usb/host/xhci.h:1867
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_get_frame
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_update_device
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_find_raw_port_number
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816ff12c)
Location: drivers/usb/host/xhci.h:1867
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
```
In drivers/usb/host/xhci-hub.c (ffffffff817023bb)
Location: drivers/usb/host/xhci.h:1867
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_ports
```
```
In drivers/usb/host/xhci-pci.c (ffffffff81705716)
Location: drivers/usb/host/xhci.h:1867
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
  - drivers/usb/host/xhci-pci.c:xhci_pme_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
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
In drivers/usb/host/xhci.c (ffffffff8175d0fe)
Location: drivers/usb/host/xhci.h:1876
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_get_frame
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_update_device
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_find_raw_port_number
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8176bd1c)
Location: drivers/usb/host/xhci.h:1876
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
```
In drivers/usb/host/xhci-hub.c (ffffffff8176f12b)
Location: drivers/usb/host/xhci.h:1876
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_ports
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8177335b)
Location: drivers/usb/host/xhci.h:1876
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_show
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8177535c)
Location: drivers/usb/host/xhci.h:1876
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
```
```
In drivers/usb/host/xhci-pci.c (ffffffff81776906)
Location: drivers/usb/host/xhci.h:1876
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
  - drivers/usb/host/xhci-pci.c:xhci_pme_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
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
In drivers/usb/host/xhci.c (ffffffff8179db2e)
Location: drivers/usb/host/xhci.h:1890
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_get_frame
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_update_device
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_check_args
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817ad0e5)
Location: drivers/usb/host/xhci.h:1890
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
```
In drivers/usb/host/xhci-hub.c (ffffffff817b0095)
Location: drivers/usb/host/xhci.h:1890
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817b396b)
Location: drivers/usb/host/xhci.h:1890
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_show
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff817b69af)
Location: drivers/usb/host/xhci.h:1890
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
```
```
In drivers/usb/host/xhci-pci.c (ffffffff817b7565)
Location: drivers/usb/host/xhci.h:1890
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
  - drivers/usb/host/xhci-pci.c:xhci_pme_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
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
In drivers/usb/host/xhci.c (ffffffff817c3f1e)
Location: drivers/usb/host/xhci.h:1896
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_get_frame
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_update_device
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_check_args
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817d33b5)
Location: drivers/usb/host/xhci.h:1896
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
```
In drivers/usb/host/xhci-hub.c (ffffffff817d6a35)
Location: drivers/usb/host/xhci.h:1896
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817d9e8b)
Location: drivers/usb/host/xhci.h:1896
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_show
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff817dd0bf)
Location: drivers/usb/host/xhci.h:1896
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
```
```
In drivers/usb/host/xhci-pci.c (ffffffff817ddb75)
Location: drivers/usb/host/xhci.h:1896
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
  - drivers/usb/host/xhci-pci.c:xhci_pme_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
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
In drivers/usb/host/xhci.c (ffffffff818016d5)
Location: drivers/usb/host/xhci.h:1909
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_get_frame
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_update_device
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_check_args
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81812975)
Location: drivers/usb/host/xhci.h:1909
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81816eb5)
Location: drivers/usb/host/xhci.h:1909
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8181a825)
Location: drivers/usb/host/xhci.h:1909
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_show
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8181d26e)
Location: drivers/usb/host/xhci.h:1909
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
```
```
In drivers/usb/host/xhci-pci.c (ffffffff8181e625)
Location: drivers/usb/host/xhci.h:1909
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
  - drivers/usb/host/xhci-pci.c:xhci_pme_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
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
In drivers/usb/host/xhci.c (ffffffff81832785)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_get_frame
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_update_device
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_check_args
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81843bd5)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
```
In drivers/usb/host/xhci-hub.c (ffffffff818481e5)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8184bba5)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_show
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8184e62e)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
```
```
In drivers/usb/host/xhci-pci.c (ffffffff8184f9f5)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_shutdown
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
  - drivers/usb/host/xhci-pci.c:xhci_pme_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
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
In drivers/usb/host/xhci.c (ffffffff81905895)
Location: drivers/usb/host/xhci.h:1920
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_get_frame
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_update_device
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_check_args
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81916815)
Location: drivers/usb/host/xhci.h:1920
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
```
In drivers/usb/host/xhci-hub.c (ffffffff8191a8f5)
Location: drivers/usb/host/xhci.h:1920
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8191e715)
Location: drivers/usb/host/xhci.h:1920
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_show
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81921a1c)
Location: drivers/usb/host/xhci.h:1920
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
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
In drivers/usb/host/xhci.c (ffffffff8190e095)
Location: drivers/usb/host/xhci.h:1931
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_get_frame
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_update_device
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_check_args
  - drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8191ddae)
Location: drivers/usb/host/xhci.h:1931
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
```
In drivers/usb/host/xhci-hub.c (ffffffff8192126d)
Location: drivers/usb/host/xhci.h:1931
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81925eb5)
Location: drivers/usb/host/xhci.h:1931
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_show
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8192906c)
Location: drivers/usb/host/xhci.h:1931
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
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
In drivers/usb/host/xhci.c (ffffffff818f1595)
Location: drivers/usb/host/xhci.h:1944
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_get_frame
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_update_device
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_check_args
  - drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8190071e)
Location: drivers/usb/host/xhci.h:1944
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
```
In drivers/usb/host/xhci-hub.c (ffffffff8190497d)
Location: drivers/usb/host/xhci.h:1944
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff819095aa)
Location: drivers/usb/host/xhci.h:1944
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_show
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8190c6fc)
Location: drivers/usb/host/xhci.h:1944
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
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
In drivers/usb/host/xhci.c (ffffffff8198e4d5)
Location: drivers/usb/host/xhci.h:1951
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_get_frame
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_update_device
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_check_args
  - drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8199fe95)
Location: drivers/usb/host/xhci.h:1951
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
```
In drivers/usb/host/xhci-hub.c (ffffffff819a517d)
Location: drivers/usb/host/xhci.h:1951
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff819a9e2a)
Location: drivers/usb/host/xhci.h:1951
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_show
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff819ac6ec)
Location: drivers/usb/host/xhci.h:1951
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
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
In drivers/usb/host/xhci.c (ffffffff81aea935)
Location: drivers/usb/host/xhci.h:1952
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_get_frame
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_update_device
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_check_args
  - drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81afd555)
Location: drivers/usb/host/xhci.h:1952
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81b02b5d)
Location: drivers/usb/host/xhci.h:1952
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81b07db8)
Location: drivers/usb/host/xhci.h:1952
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_show
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81b0ac7c)
Location: drivers/usb/host/xhci.h:1952
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
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
In drivers/usb/host/xhci.c (ffffffff81c76d85)
Location: drivers/usb/host/xhci.h:1954
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_get_frame
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_update_device
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_check_args
  - drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81c8c1e4)
Location: drivers/usb/host/xhci.h:1954
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81c91bfd)
Location: drivers/usb/host/xhci.h:1954
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81c97708)
Location: drivers/usb/host/xhci.h:1954
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_show
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81c9abbc)
Location: drivers/usb/host/xhci.h:1954
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
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
In drivers/usb/host/xhci.c (ffffffff81cdde65)
Location: drivers/usb/host/xhci.h:1963
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_get_frame
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_update_device
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_check_args
  - drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81cf2d64)
Location: drivers/usb/host/xhci.h:1963
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81cf82ed)
Location: drivers/usb/host/xhci.h:1963
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status
  - drivers/usb/host/xhci-hub.c:xhci_handle_usb2_port_link_resume
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81cfdb56)
Location: drivers/usb/host/xhci.h:1963
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_bInterfaceProtocol_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_bInterfaceProtocol_show
  - drivers/usb/host/xhci-dbgcap.c:dbc_bcdDevice_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_bcdDevice_show
  - drivers/usb/host/xhci-dbgcap.c:dbc_idProduct_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_idProduct_show
  - drivers/usb/host/xhci-dbgcap.c:dbc_idVendor_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_idVendor_show
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_show
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81d01f6c)
Location: drivers/usb/host/xhci.h:1963
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
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
In drivers/usb/host/xhci.c (ffffffff81d92e75)
Location: drivers/usb/host/xhci.h:1939
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_get_frame
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_update_device
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_check_args
  - drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81d9d37e)
Location: drivers/usb/host/xhci.h:1939
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_create_secondary_interrupter
  - drivers/usb/host/xhci-mem.c:xhci_remove_secondary_interrupter
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81da86a4)
Location: drivers/usb/host/xhci.h:1939
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81dadc1d)
Location: drivers/usb/host/xhci.h:1939
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status
  - drivers/usb/host/xhci-hub.c:xhci_handle_usb2_port_link_resume
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81db34b6)
Location: drivers/usb/host/xhci.h:1939
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_bInterfaceProtocol_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_bInterfaceProtocol_show
  - drivers/usb/host/xhci-dbgcap.c:dbc_bcdDevice_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_bcdDevice_show
  - drivers/usb/host/xhci-dbgcap.c:dbc_idProduct_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_idProduct_show
  - drivers/usb/host/xhci-dbgcap.c:dbc_idVendor_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_idVendor_show
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81db7a9c)
Location: drivers/usb/host/xhci.h:1939
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
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
In drivers/usb/host/xhci.c (ffff800010a6fb94)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_get_frame
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_update_device
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_check_args
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
```
In drivers/usb/host/xhci-ring.c (ffff800010a82cd4)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
```
In drivers/usb/host/xhci-hub.c (ffff800010a87270)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
```
```
In drivers/usb/host/xhci-dbgcap.c (ffff800010a8afa0)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_show
```
```
In drivers/usb/host/xhci-mtk-sch.c (ffff800010a8e220)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_drop_ep_quirk
  - drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_add_ep_quirk
  - drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_sch_init
```
```
In drivers/usb/host/xhci-debugfs.c (ffff800010a8fcd8)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
```
```
In drivers/usb/host/xhci-pci.c (ffff800010a905f0)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_shutdown
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
  - drivers/usb/host/xhci-pci.c:xhci_pme_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
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
In drivers/usb/host/xhci.c (c0b42ff4)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_get_frame
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_update_device
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
```
In drivers/usb/host/xhci-ring.c (c0b5655c)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
```
In drivers/usb/host/xhci-hub.c (c0b5a1d8)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
```
```
In drivers/usb/host/xhci-dbgcap.c (c0b5dc44)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_show
```
```
In drivers/usb/host/xhci-mtk-sch.c (c0b5fe0c)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_drop_ep_quirk
  - drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_add_ep_quirk
  - drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_sch_init
```
```
In drivers/usb/host/xhci-debugfs.c (c0b61ed0)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
```
```
In drivers/usb/host/xhci-pci.c (c0b6281c)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_shutdown
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
  - drivers/usb/host/xhci-pci.c:xhci_pme_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
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
In drivers/usb/host/xhci.c (c000000000b43160)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_get_frame
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_update_device
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_check_args
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
```
In drivers/usb/host/xhci-ring.c (c000000000b5c5f4)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
```
In drivers/usb/host/xhci-hub.c (c000000000b616b0)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
```
```
In drivers/usb/host/xhci-dbgcap.c (c000000000b669c0)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_show
```
```
In drivers/usb/host/xhci-debugfs.c (c000000000b6a4e4)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
```
```
In drivers/usb/host/xhci-pci.c (c000000000b6c884)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_shutdown
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
  - drivers/usb/host/xhci-pci.c:xhci_pme_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
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
In drivers/usb/host/xhci.c (ffffffe000687ed8)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_get_frame
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_update_device
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
```
In drivers/usb/host/xhci-ring.c (ffffffe000699140)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
```
In drivers/usb/host/xhci-hub.c (ffffffe00069cae4)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffe0006a04ca)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_show
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffe0006a27b6)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
```
```
In drivers/usb/host/xhci-pci.c (ffffffe0006a3ab8)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_shutdown
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
  - drivers/usb/host/xhci-pci.c:xhci_pme_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
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
In drivers/usb/host/xhci.c (ffffffff817eab65)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_get_frame
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_update_device
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_check_args
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817fbf85)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81800595)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff818043fe)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
```
```
In drivers/usb/host/xhci-pci.c (ffffffff818057c5)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_shutdown
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
  - drivers/usb/host/xhci-pci.c:xhci_pme_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
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
In drivers/usb/host/xhci.c (ffffffff817afc75)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_get_frame
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_update_device
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_check_args
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817c1125)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
```
In drivers/usb/host/xhci-hub.c (ffffffff817c5735)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817c90f5)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_show
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff817cbb7e)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
```
```
In drivers/usb/host/xhci-pci.c (ffffffff817ccf45)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_shutdown
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
  - drivers/usb/host/xhci-pci.c:xhci_pme_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
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
In drivers/usb/host/xhci.c (ffffffff81827605)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_get_frame
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_update_device
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_check_args
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81838a55)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
```
In drivers/usb/host/xhci-hub.c (ffffffff8183d065)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81840a25)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_show
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff818434ae)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
```
```
In drivers/usb/host/xhci-pci.c (ffffffff81844875)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_shutdown
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
  - drivers/usb/host/xhci-pci.c:xhci_pme_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
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
In drivers/usb/host/xhci.c (ffffffff818415a5)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_get_frame
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_update_device
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_check_args
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81852ea5)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81857535)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8185aef5)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_show
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8185da0e)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
```
```
In drivers/usb/host/xhci-pci.c (ffffffff8185edd5)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_shutdown
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
  - drivers/usb/host/xhci-pci.c:xhci_pme_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
</details>
</li>
</ul>

## Differences
