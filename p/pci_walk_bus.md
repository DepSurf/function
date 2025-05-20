# Function: <code>pci_walk_bus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pci_walk_bus(struct pci_bus *top, int (*cb)(struct pci_dev *, void *), void *userdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8142f1b0)
Location: drivers/pci/bus.c:340
Inline: False
Direct callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/pci.c:__pci_complete_power_transition
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_pme_wakeup_bus
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/pcie/aer/aerdrv_core.c:broadcast_error_message
  - drivers/pci/pcie/aer/aerdrv_core.c:broadcast_error_message
  - drivers/pci/pcie/aer/aerdrv_core.c:broadcast_error_message
  - drivers/pci/pcie/aer/aerdrv.c:set_downstream_devices_error_reporting
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
**Symbols:**

```
ffffffff8142f1b0-ffffffff8142f23c: pci_walk_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pci_walk_bus(struct pci_bus *top, int (*cb)(struct pci_dev *, void *), void *userdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8147a820)
Location: drivers/pci/bus.c:380
Inline: False
Direct callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_pme_wakeup_bus
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:__pci_complete_power_transition
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/pcie/aer/aerdrv_core.c:broadcast_error_message
  - drivers/pci/pcie/aer/aerdrv_core.c:broadcast_error_message
  - drivers/pci/pcie/aer/aerdrv_core.c:broadcast_error_message
  - drivers/pci/pcie/aer/aerdrv.c:set_downstream_devices_error_reporting
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
**Symbols:**

```
ffffffff8147a820-ffffffff8147a8ac: pci_walk_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pci_walk_bus(struct pci_bus *top, int (*cb)(struct pci_dev *, void *), void *userdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8149bca0)
Location: drivers/pci/bus.c:380
Inline: False
Direct callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_pme_wakeup_bus
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:__pci_complete_power_transition
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/pcie/aer/aerdrv_core.c:broadcast_error_message
  - drivers/pci/pcie/aer/aerdrv_core.c:broadcast_error_message
  - drivers/pci/pcie/aer/aerdrv_core.c:broadcast_error_message
  - drivers/pci/pcie/aer/aerdrv.c:set_downstream_devices_error_reporting
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
**Symbols:**

```
ffffffff8149bca0-ffffffff8149bd2c: pci_walk_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pci_walk_bus(struct pci_bus *top, int (*cb)(struct pci_dev *, void *), void *userdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff814a5a80)
Location: drivers/pci/bus.c:380
Inline: False
Direct callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_pme_wakeup_bus
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:__pci_complete_power_transition
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/pcie/aer/aerdrv_core.c:broadcast_error_message
  - drivers/pci/pcie/aer/aerdrv_core.c:broadcast_error_message
  - drivers/pci/pcie/aer/aerdrv_core.c:broadcast_error_message
  - drivers/pci/pcie/aer/aerdrv.c:set_downstream_devices_error_reporting
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
```
**Symbols:**

```
ffffffff814a5a80-ffffffff814a5b0c: pci_walk_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_walk_bus(struct pci_bus *top, int (*cb)(struct pci_dev *, void *), void *userdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff814e48c0)
Location: drivers/pci/bus.c:380
Inline: False
Direct callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_pme_wakeup_bus
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:__pci_complete_power_transition
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/quirks.c:quirk_no_ext_tags
  - drivers/pci/pcie/aer/aerdrv_core.c:broadcast_error_message
  - drivers/pci/pcie/aer/aerdrv_core.c:broadcast_error_message
  - drivers/pci/pcie/aer/aerdrv_core.c:broadcast_error_message
  - drivers/pci/pcie/aer/aerdrv.c:set_downstream_devices_error_reporting
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
```
**Symbols:**

```
ffffffff814e48c0-ffffffff814e4950: pci_walk_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_walk_bus(struct pci_bus *top, int (*cb)(struct pci_dev *, void *), void *userdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff81513da0)
Location: drivers/pci/bus.c:379
Inline: False
Direct callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_pme_wakeup_bus
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:__pci_complete_power_transition
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/quirks.c:quirk_no_ext_tags
  - drivers/pci/pcie/err.c:pcie_do_fatal_recovery
  - drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
**Symbols:**

```
ffffffff81513da0-ffffffff81513e30: pci_walk_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_walk_bus(struct pci_bus *top, int (*cb)(struct pci_dev *, void *), void *userdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff81529500)
Location: drivers/pci/bus.c:379
Inline: False
Direct callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_pme_wakeup_bus
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:__pci_complete_power_transition
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/quirks.c:quirk_no_ext_tags
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
**Symbols:**

```
ffffffff81529500-ffffffff81529590: pci_walk_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pci_walk_bus(struct pci_bus *top, int (*cb)(struct pci_dev *, void *), void *userdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff81558780)
Location: drivers/pci/bus.c:378
Inline: False
Direct callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_pme_wakeup_bus
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:__pci_complete_power_transition
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/quirks.c:quirk_no_ext_tags
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
**Symbols:**

```
ffffffff81558780-ffffffff81558810: pci_walk_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pci_walk_bus(struct pci_bus *top, int (*cb)(struct pci_dev *, void *), void *userdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff81579d60)
Location: drivers/pci/bus.c:378
Inline: False
Direct callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_pme_wakeup_bus
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:__pci_complete_power_transition
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/quirks.c:quirk_no_ext_tags
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff81579d60-ffffffff81579df0: pci_walk_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pci_walk_bus(struct pci_bus *top, int (*cb)(struct pci_dev *, void *), void *userdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8161edb0)
Location: drivers/pci/bus.c:374
Inline: False
Direct callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_pme_wakeup_bus
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/aer.c:aer_remove
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/quirks.c:quirk_no_ext_tags
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_try_bus_reset
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_try_bus_reset
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_attach
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
**Symbols:**

```
ffffffff8161edb0-ffffffff8161ee40: pci_walk_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pci_walk_bus(struct pci_bus *top, int (*cb)(struct pci_dev *, void *), void *userdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff816455a0)
Location: drivers/pci/bus.c:374
Inline: False
Direct callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_pme_wakeup_bus
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/rcec.c:walk_rcec
  - drivers/pci/pcie/rcec.c:walk_rcec
  - drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/quirks.c:quirk_no_ext_tags
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_try_bus_reset
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_try_bus_reset
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_attach
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
**Symbols:**

```
ffffffff816455a0-ffffffff81645630: pci_walk_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pci_walk_bus(struct pci_bus *top, int (*cb)(struct pci_dev *, void *), void *userdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff816282e0)
Location: drivers/pci/bus.c:374
Inline: False
Direct callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_pme_wakeup_bus
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/rcec.c:walk_rcec
  - drivers/pci/pcie/rcec.c:walk_rcec
  - drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/quirks.c:quirk_no_ext_tags
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_try_bus_reset
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_try_bus_reset
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
**Symbols:**

```
ffffffff816282e0-ffffffff81628370: pci_walk_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pci_walk_bus(struct pci_bus *top, int (*cb)(struct pci_dev *, void *), void *userdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff81697be0)
Location: drivers/pci/bus.c:374
Inline: False
Direct callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_pme_wakeup_bus
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/rcec.c:walk_rcec
  - drivers/pci/pcie/rcec.c:walk_rcec
  - drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/quirks.c:quirk_no_ext_tags
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_dev_set_resettable
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
```
**Symbols:**

```
ffffffff81697be0-ffffffff81697c70: pci_walk_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pci_walk_bus(struct pci_bus *top, int (*cb)(struct pci_dev *, void *), void *userdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff817b8db0)
Location: drivers/pci/bus.c:374
Inline: False
Direct callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_pme_wakeup_bus
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_resume_bus
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/pcie/rcec.c:walk_rcec
  - drivers/pci/pcie/rcec.c:walk_rcec
  - drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting
  - drivers/pci/pcie/aer.c:find_source_device
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/quirks.c:quirk_no_ext_tags
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_dev_set_resettable
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
```
**Symbols:**

```
ffffffff817b8db0-ffffffff817b8e4e: pci_walk_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_walk_bus(struct pci_bus *top, int (*cb)(struct pci_dev *, void *), void *userdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff818d3870)
Location: drivers/pci/bus.c:378
Inline: False
Direct callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_pme_wakeup_bus
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_resume_bus
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/pcie/rcec.c:walk_rcec
  - drivers/pci/pcie/rcec.c:walk_rcec
  - drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting
  - drivers/pci/pcie/aer.c:find_source_device
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/quirks.c:quirk_no_ext_tags
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
**Symbols:**

```
ffffffff818d3870-ffffffff818d390e: pci_walk_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_walk_bus(struct pci_bus *top, int (*cb)(struct pci_dev *, void *), void *userdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff819169a0)
Location: drivers/pci/bus.c:400
Inline: False
Direct callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_pme_wakeup_bus
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_resume_bus
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/pcie/rcec.c:walk_rcec
  - drivers/pci/pcie/rcec.c:walk_rcec
  - drivers/pci/pcie/aer.c:find_source_device
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/quirks.c:quirk_no_ext_tags
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
**Symbols:**

```
ffffffff819169a0-ffffffff81916a3e: pci_walk_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_walk_bus(struct pci_bus *top, int (*cb)(struct pci_dev *, void *), void *userdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8195eab0)
Location: drivers/pci/bus.c:439
Inline: False
Direct callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_pme_wakeup_bus
  - drivers/pci/pci.c:__pci_set_power_state
  - drivers/pci/pci.c:pci_bus_set_current_state
  - drivers/pci/pci.c:pci_resume_bus
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/pcie/rcec.c:walk_rcec
  - drivers/pci/pcie/rcec.c:walk_rcec
  - drivers/pci/pcie/aer.c:find_source_device
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/quirks.c:quirk_no_ext_tags
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
**Symbols:**

```
ffffffff8195eab0-ffffffff8195eace: pci_walk_bus (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void pci_walk_bus(struct pci_bus *top, int (*cb)(struct pci_dev *, void *), void *userdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffff8000106dc528)
Location: drivers/pci/bus.c:378
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic-v3-its-pci-msi.c:its_pci_msi_prepare
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_pme_wakeup_bus
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:__pci_complete_power_transition
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/quirks.c:quirk_no_ext_tags
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
**Symbols:**

```
ffff8000106dc528-ffff8000106dc5e4: pci_walk_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_walk_bus(struct pci_bus *top, int (*cb)(struct pci_dev *, void *), void *userdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (c0878300)
Location: drivers/pci/bus.c:378
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic-v3-its-pci-msi.c:its_pci_msi_prepare
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_pme_wakeup_bus
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:__pci_complete_power_transition
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/quirks.c:quirk_no_ext_tags
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
**Symbols:**

```
c0878300-c0878390: pci_walk_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_walk_bus(struct pci_bus *top, int (*cb)(struct pci_dev *, void *), void *userdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (c0000000008544c0)
Location: drivers/pci/bus.c:378
Inline: False
Direct callers:
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda1_setup_dma_pe
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda_pe_dma_weight
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_pme_wakeup_bus
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:__pci_complete_power_transition
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/quirks.c:quirk_no_ext_tags
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
c0000000008544c0-c0000000008545d8: pci_walk_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_walk_bus(struct pci_bus *top, int (*cb)(struct pci_dev *, void *), void *userdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffe0004b4b12)
Location: drivers/pci/bus.c:378
Inline: False
Direct callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_pme_wakeup_bus
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:__pci_complete_power_transition
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/quirks.c:quirk_no_ext_tags
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
```
**Symbols:**

```
ffffffe0004b4b12-ffffffe0004b4ba4: pci_walk_bus (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void pci_walk_bus(struct pci_bus *top, int (*cb)(struct pci_dev *, void *), void *userdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8156e280)
Location: drivers/pci/bus.c:378
Inline: False
Direct callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_pme_wakeup_bus
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:__pci_complete_power_transition
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/quirks.c:quirk_no_ext_tags
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
**Symbols:**

```
ffffffff8156e280-ffffffff8156e310: pci_walk_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pci_walk_bus(struct pci_bus *top, int (*cb)(struct pci_dev *, void *), void *userdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8155c9e0)
Location: drivers/pci/bus.c:378
Inline: False
Direct callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_pme_wakeup_bus
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:__pci_complete_power_transition
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/quirks.c:quirk_no_ext_tags
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff8155c9e0-ffffffff8155ca70: pci_walk_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pci_walk_bus(struct pci_bus *top, int (*cb)(struct pci_dev *, void *), void *userdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8156dab0)
Location: drivers/pci/bus.c:378
Inline: False
Direct callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_pme_wakeup_bus
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:__pci_complete_power_transition
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/quirks.c:quirk_no_ext_tags
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff8156dab0-ffffffff8156db40: pci_walk_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pci_walk_bus(struct pci_bus *top, int (*cb)(struct pci_dev *, void *), void *userdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff81587f90)
Location: drivers/pci/bus.c:378
Inline: False
Direct callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_pme_wakeup_bus
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:__pci_complete_power_transition
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/quirks.c:quirk_no_ext_tags
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff81587f90-ffffffff81588020: pci_walk_bus (STB_GLOBAL)
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
