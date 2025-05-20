# Function: <code>usb_hcd_is_primary_hcd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_is_primary_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8160c2a0)
Location: drivers/usb/core/hcd.c:2634
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:hcd_release
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
Direct callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
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
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-hub.c:xhci_get_ports
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pme_quirk
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff8160c2a0-ffffffff8160c2c7: usb_hcd_is_primary_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_is_primary_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8166d589)
Location: drivers/usb/core/hcd.c:2638
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
Direct callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/host/xhci.c:xhci_gen_setup
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
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_ports
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
  - drivers/usb/host/xhci-pci.c:xhci_pme_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
**Symbols:**

```
ffffffff8166be70-ffffffff8166be9a: usb_hcd_is_primary_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_is_primary_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8169b289)
Location: drivers/usb/core/hcd.c:2637
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
Direct callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/host/xhci.c:xhci_gen_setup
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
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_ports
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
  - drivers/usb/host/xhci-pci.c:xhci_pme_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
**Symbols:**

```
ffffffff81699b70-ffffffff81699b9a: usb_hcd_is_primary_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_is_primary_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff816b05e9)
Location: drivers/usb/core/hcd.c:2663
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
Direct callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/host/xhci.c:xhci_gen_setup
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
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_ports
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
  - drivers/usb/host/xhci-pci.c:xhci_pme_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
**Symbols:**

```
ffffffff816aeec0-ffffffff816aeee4: usb_hcd_is_primary_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_is_primary_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8171bbff)
Location: drivers/usb/core/hcd.c:2650
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
Direct callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/host/xhci.c:xhci_gen_setup
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
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_ports
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_show
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
  - drivers/usb/host/xhci-pci.c:xhci_pme_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
**Symbols:**

```
ffffffff8171a4e0-ffffffff8171a504: usb_hcd_is_primary_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_is_primary_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8175a8af)
Location: drivers/usb/core/hcd.c:2666
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
Direct callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/host/xhci.c:xhci_gen_setup
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
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci-ring.c:xhci_irq
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
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_show
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
  - drivers/usb/host/xhci-pci.c:xhci_pme_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
**Symbols:**

```
ffffffff817592f0-ffffffff81759317: usb_hcd_is_primary_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_is_primary_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8177eedf)
Location: drivers/usb/core/hcd.c:2650
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
Direct callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/host/xhci.c:xhci_gen_setup
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
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci-ring.c:xhci_irq
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
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_show
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
  - drivers/usb/host/xhci-pci.c:xhci_pme_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
**Symbols:**

```
ffffffff8177d860-ffffffff8177d887: usb_hcd_is_primary_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_is_primary_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817bf025)
Location: drivers/usb/core/hcd.c:2561
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
Direct callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_gen_setup
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
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci-ring.c:xhci_irq
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
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_show
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
  - drivers/usb/host/xhci-pci.c:xhci_pme_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
**Symbols:**

```
ffffffff817bbc00-ffffffff817bbc27: usb_hcd_is_primary_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_is_primary_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817ef9a5)
Location: drivers/usb/core/hcd.c:2560
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
Direct callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_gen_setup
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
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci-ring.c:xhci_irq
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
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_show
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
  - drivers/usb/host/xhci-pci.c:xhci_pci_shutdown
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
  - drivers/usb/host/xhci-pci.c:xhci_pme_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
**Symbols:**

```
ffffffff817ec430-ffffffff817ec457: usb_hcd_is_primary_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_is_primary_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff818bf028)
Location: drivers/usb/core/hcd.c:2557
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
Direct callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
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
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci-ring.c:xhci_irq
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
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_show
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
```
**Symbols:**

```
ffffffff818bba30-ffffffff818bba57: usb_hcd_is_primary_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_is_primary_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81c1c655)
Location: drivers/usb/core/hcd.c:2569
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
Direct callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
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
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci-ring.c:xhci_irq
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
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_show
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
```
**Symbols:**

```
ffffffff818c8810-ffffffff818c8837: usb_hcd_is_primary_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_is_primary_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81c0e431)
Location: drivers/usb/core/hcd.c:2569
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
Direct callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
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
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci-ring.c:xhci_irq
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
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_show
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
```
**Symbols:**

```
ffffffff818abe50-ffffffff818abe77: usb_hcd_is_primary_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_is_primary_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81d15566)
Location: drivers/usb/core/hcd.c:2720
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
Direct callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
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
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci-ring.c:xhci_irq
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
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_show
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
```
**Symbols:**

```
ffffffff81940e40-ffffffff81940e67: usb_hcd_is_primary_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_is_primary_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81ee0098)
Location: drivers/usb/core/hcd.c:2723
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
Direct callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_gen_setup
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
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci-ring.c:xhci_irq
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
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_show
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
```
**Symbols:**

```
ffffffff81a99160-ffffffff81a99193: usb_hcd_is_primary_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_is_primary_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81c1eaf9)
Location: drivers/usb/core/hcd.c:2717
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
Direct callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_gen_setup
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
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci-ring.c:xhci_irq
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
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_show
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
```
**Symbols:**

```
ffffffff81c1d0e0-ffffffff81c1d113: usb_hcd_is_primary_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_is_primary_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81c859f9)
Location: drivers/usb/core/hcd.c:2721
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
Direct callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_gen_setup
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
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci-ring.c:xhci_irq
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
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
```
**Symbols:**

```
ffffffff81c83ff0-ffffffff81c84023: usb_hcd_is_primary_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_is_primary_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81d3a0b9)
Location: drivers/usb/core/hcd.c:2696
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
Direct callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_gen_setup
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
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci-mem.c:xhci_create_secondary_interrupter
  - drivers/usb/host/xhci-mem.c:xhci_remove_secondary_interrupter
  - drivers/usb/host/xhci-ring.c:xhci_irq
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
  - drivers/usb/host/xhci-dbgcap.c:dbc_bInterfaceProtocol_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_bInterfaceProtocol_show
  - drivers/usb/host/xhci-dbgcap.c:dbc_bcdDevice_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_bcdDevice_show
  - drivers/usb/host/xhci-dbgcap.c:dbc_idProduct_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_idProduct_show
  - drivers/usb/host/xhci-dbgcap.c:dbc_idVendor_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_idVendor_show
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
```
**Symbols:**

```
ffffffff81d389f0-ffffffff81d38a23: usb_hcd_is_primary_hcd (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_is_primary_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffff800010a1fc2c)
Location: drivers/usb/core/hcd.c:2560
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
Direct callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_gen_setup
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
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci-ring.c:xhci_irq
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
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_show
  - drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_drop_ep_quirk
  - drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_add_ep_quirk
  - drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_sch_init
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
  - drivers/usb/host/xhci-pci.c:xhci_pci_shutdown
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
  - drivers/usb/host/xhci-pci.c:xhci_pme_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
**Symbols:**

```
ffff800010a1b4c0-ffff800010a1b504: usb_hcd_is_primary_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_is_primary_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (c0af6e78)
Location: drivers/usb/core/hcd.c:2560
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
Direct callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_gen_setup
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
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci-ring.c:xhci_irq
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
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_show
  - drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_drop_ep_quirk
  - drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_add_ep_quirk
  - drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_sch_init
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
  - drivers/usb/host/xhci-pci.c:xhci_pci_shutdown
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
  - drivers/usb/host/xhci-pci.c:xhci_pme_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
**Symbols:**

```
c0af3444-c0af3474: usb_hcd_is_primary_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_is_primary_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (c000000000ad9da4)
Location: drivers/usb/core/hcd.c:2560
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
Direct callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_gen_setup
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
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci-ring.c:xhci_irq
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
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_show
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
  - drivers/usb/host/xhci-pci.c:xhci_pci_shutdown
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
  - drivers/usb/host/xhci-pci.c:xhci_pme_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
**Symbols:**

```
c000000000ad4b80-c000000000ad4bb8: usb_hcd_is_primary_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_is_primary_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffe000643046)
Location: drivers/usb/core/hcd.c:2560
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
Direct callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_gen_setup
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
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci-ring.c:xhci_irq
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
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_show
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
  - drivers/usb/host/xhci-pci.c:xhci_pci_shutdown
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
  - drivers/usb/host/xhci-pci.c:xhci_pme_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
**Symbols:**

```
ffffffe00063fa6c-ffffffe00063faa6: usb_hcd_is_primary_hcd (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_is_primary_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817a7d85)
Location: drivers/usb/core/hcd.c:2560
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
Direct callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_gen_setup
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
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci-ring.c:xhci_irq
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
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
  - drivers/usb/host/xhci-pci.c:xhci_pci_shutdown
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
  - drivers/usb/host/xhci-pci.c:xhci_pme_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
**Symbols:**

```
ffffffff817a4810-ffffffff817a4837: usb_hcd_is_primary_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_is_primary_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8179979e)
Location: drivers/usb/core/hcd.c:2560
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
Direct callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_gen_setup
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
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci-ring.c:xhci_irq
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
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_show
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
  - drivers/usb/host/xhci-pci.c:xhci_pci_shutdown
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
  - drivers/usb/host/xhci-pci.c:xhci_pme_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
**Symbols:**

```
ffffffff81796380-ffffffff817963a7: usb_hcd_is_primary_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_is_primary_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817e4825)
Location: drivers/usb/core/hcd.c:2560
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
Direct callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_gen_setup
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
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci-ring.c:xhci_irq
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
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_show
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
  - drivers/usb/host/xhci-pci.c:xhci_pci_shutdown
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
  - drivers/usb/host/xhci-pci.c:xhci_pme_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
**Symbols:**

```
ffffffff817e12b0-ffffffff817e12d7: usb_hcd_is_primary_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int usb_hcd_is_primary_hcd(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817fea91)
Location: drivers/usb/core/hcd.c:2560
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
Direct callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_gen_setup
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
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci-ring.c:xhci_irq
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
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_show
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
  - drivers/usb/host/xhci-pci.c:xhci_pci_shutdown
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
  - drivers/usb/host/xhci-pci.c:xhci_pme_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
**Symbols:**

```
ffffffff817fb5f0-ffffffff817fb617: usb_hcd_is_primary_hcd (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
