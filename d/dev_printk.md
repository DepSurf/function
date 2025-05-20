# Function: <code>dev_printk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dev_printk(const char *level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81547750)
Location: drivers/base/core.c:2199
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - drivers/pci/access.c:pci_vpd_pci22_wait
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/pci/probe.c:pci_bus_release_busn_res
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/setup-bus.c:res_to_dev_res
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/pcie/portdrv_core.c:pcie_port_remove_service
  - drivers/pci/pcie/portdrv_core.c:pcie_port_probe_service
  - drivers/pci/pcie/aer/aerdrv_core.c:broadcast_error_message
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/pci/pcie/aer/aerdrv_core.c:report_error_detected
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_isr
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_init
  - drivers/pci/pcie/aer/aerdrv.c:aer_root_reset
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_on
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_off
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_blink
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_off_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/pnp/core.c:pnp_add_device
  - drivers/pnp/resource.c:pnp_add_irq_resource
  - drivers/pnp/resource.c:pnp_add_dma_resource
  - drivers/pnp/resource.c:pnp_add_io_resource
  - drivers/pnp/resource.c:pnp_add_mem_resource
  - drivers/pnp/resource.c:pnp_add_bus_resource
  - drivers/scsi/hosts.c:scsi_host_set_state
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_logging.c:sdev_prefix_printk
  - drivers/scsi/scsi_logging.c:scmd_printk
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
  - drivers/scsi/scsi_logging.c:scsi_print_result
  - drivers/ata/libata-core.c:ata_print_version
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_do_submiturb
  - arch/x86/pci/i386.c:pcibios_resource_survey_bus
  - arch/x86/pci/fixup.c:pci_fixup_video
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
```
**Symbols:**

```
ffffffff81547750-ffffffff815477c4: dev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dev_printk(const char *level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815994b0)
Location: drivers/base/core.c:2199
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/probe.c:pci_bus_release_busn_res
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:res_to_dev_res
  - drivers/pci/pcie/portdrv_core.c:pcie_port_remove_service
  - drivers/pci/pcie/portdrv_core.c:pcie_port_probe_service
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_init
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_isr
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/pci/pcie/aer/aerdrv_core.c:broadcast_error_message
  - drivers/pci/pcie/aer/aerdrv_core.c:report_error_detected
  - drivers/pci/pcie/aer/aerdrv.c:aer_root_reset
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_off_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_blink
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_off
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_on
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/pnp/core.c:pnp_add_device
  - drivers/pnp/resource.c:pnp_add_bus_resource
  - drivers/pnp/resource.c:pnp_add_mem_resource
  - drivers/pnp/resource.c:pnp_add_io_resource
  - drivers/pnp/resource.c:pnp_add_dma_resource
  - drivers/pnp/resource.c:pnp_add_irq_resource
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_host_set_state
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_logging.c:scsi_print_result
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scmd_printk
  - drivers/scsi/scsi_logging.c:sdev_prefix_printk
  - drivers/ata/libata-core.c:ata_print_version
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
  - arch/x86/pci/i386.c:pcibios_resource_survey_bus
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
```
**Symbols:**

```
ffffffff815994b0-ffffffff81599524: dev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dev_printk(const char *level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815c6df0)
Location: drivers/base/core.c:2790
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/probe.c:pci_bus_release_busn_res
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:res_to_dev_res
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/pci/pcie/aer/aerdrv_core.c:broadcast_error_message
  - drivers/pci/pcie/aer/aerdrv_core.c:report_error_detected
  - drivers/pci/pcie/aer/aerdrv.c:aer_root_reset
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_off_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_blink
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_off
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_on
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/pnp/core.c:pnp_add_device
  - drivers/pnp/resource.c:pnp_add_bus_resource
  - drivers/pnp/resource.c:pnp_add_mem_resource
  - drivers/pnp/resource.c:pnp_add_io_resource
  - drivers/pnp/resource.c:pnp_add_dma_resource
  - drivers/pnp/resource.c:pnp_add_irq_resource
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_host_set_state
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_logging.c:scsi_print_result
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scmd_printk
  - drivers/scsi/scsi_logging.c:sdev_prefix_printk
  - drivers/ata/libata-core.c:ata_print_version
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
  - arch/x86/pci/i386.c:pcibios_resource_survey_bus
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
```
**Symbols:**

```
ffffffff815c6df0-ffffffff815c6e64: dev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dev_printk(const char *level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815dbb80)
Location: drivers/base/core.c:2792
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/probe.c:pci_bus_release_busn_res
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/pci/pcie/aer/aerdrv_core.c:broadcast_error_message
  - drivers/pci/pcie/aer/aerdrv_core.c:report_error_detected
  - drivers/pci/pcie/aer/aerdrv.c:aer_root_reset
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_off_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_blink
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_off
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_on
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/pnp/core.c:pnp_add_device
  - drivers/pnp/resource.c:pnp_add_bus_resource
  - drivers/pnp/resource.c:pnp_add_mem_resource
  - drivers/pnp/resource.c:pnp_add_io_resource
  - drivers/pnp/resource.c:pnp_add_dma_resource
  - drivers/pnp/resource.c:pnp_add_irq_resource
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_host_set_state
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_logging.c:scsi_print_result
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scmd_printk
  - drivers/scsi/scsi_logging.c:sdev_prefix_printk
  - drivers/ata/libata-core.c:ata_print_version
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
  - arch/x86/pci/i386.c:pcibios_resource_survey_bus
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
```
**Symbols:**

```
ffffffff815dbb80-ffffffff815dbbf2: dev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dev_printk(const char *level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81642bb0)
Location: drivers/base/core.c:2928
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/probe.c:pci_bus_release_busn_res
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/pci/pcie/aer/aerdrv_core.c:broadcast_error_message
  - drivers/pci/pcie/aer/aerdrv_core.c:report_error_detected
  - drivers/pci/pcie/aer/aerdrv.c:aer_root_reset
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_off_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_blink
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_off
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_on
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/pnp/core.c:pnp_add_device
  - drivers/pnp/resource.c:pnp_add_bus_resource
  - drivers/pnp/resource.c:pnp_add_mem_resource
  - drivers/pnp/resource.c:pnp_add_io_resource
  - drivers/pnp/resource.c:pnp_add_dma_resource
  - drivers/pnp/resource.c:pnp_add_irq_resource
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_host_set_state
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_logging.c:scsi_print_result
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scmd_printk
  - drivers/scsi/scsi_logging.c:sdev_prefix_printk
  - drivers/ata/libata-core.c:ata_print_version
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
  - arch/x86/pci/i386.c:pcibios_resource_survey_bus
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
```
**Symbols:**

```
ffffffff81642bb0-ffffffff81642c22: dev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dev_printk(const char *level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8167dd00)
Location: drivers/base/core.c:2983
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/probe.c:pci_bus_release_busn_res
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/pcie/err.c:pcie_do_fatal_recovery
  - drivers/pci/pcie/err.c:pcie_do_fatal_recovery
  - drivers/pci/pcie/err.c:pcie_do_fatal_recovery
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_off_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_blink
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_off
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_on
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
  - drivers/pci/hotplug/shpchp_core.c:get_adapter_status
  - drivers/pci/hotplug/shpchp_core.c:get_latch_status
  - drivers/pci/hotplug/shpchp_core.c:get_attention_status
  - drivers/pci/hotplug/shpchp_core.c:get_power_status
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
  - drivers/pci/hotplug/shpchp_core.c:set_attention_status
  - drivers/pci/hotplug/shpchp_core.c:release_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_mode1_ECC_cap
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log_header
  - drivers/video/hdmi.c:hdmi_infoframe_log_header
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/pnp/core.c:pnp_add_device
  - drivers/pnp/resource.c:pnp_add_bus_resource
  - drivers/pnp/resource.c:pnp_add_mem_resource
  - drivers/pnp/resource.c:pnp_add_io_resource
  - drivers/pnp/resource.c:pnp_add_dma_resource
  - drivers/pnp/resource.c:pnp_add_irq_resource
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_host_set_state
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_logging.c:scsi_print_result
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scmd_printk
  - drivers/scsi/scsi_logging.c:sdev_prefix_printk
  - drivers/ata/libata-core.c:ata_print_version
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
  - arch/x86/pci/i386.c:pcibios_resource_survey_bus
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
```
**Symbols:**

```
ffffffff8167dd00-ffffffff8167dd74: dev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dev_printk(const char *level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169d700)
Location: drivers/base/core.c:3058
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/probe.c:pci_bus_release_busn_res
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/pci.c:pci_set_cacheline_size
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_blink
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_on
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/shpchp_core.c:get_adapter_status
  - drivers/pci/hotplug/shpchp_core.c:get_latch_status
  - drivers/pci/hotplug/shpchp_core.c:get_attention_status
  - drivers/pci/hotplug/shpchp_core.c:get_power_status
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
  - drivers/pci/hotplug/shpchp_core.c:set_attention_status
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_mode1_ECC_cap
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log_header
  - drivers/video/hdmi.c:hdmi_infoframe_log_header
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/pnp/core.c:pnp_add_device
  - drivers/pnp/resource.c:pnp_add_bus_resource
  - drivers/pnp/resource.c:pnp_add_mem_resource
  - drivers/pnp/resource.c:pnp_add_io_resource
  - drivers/pnp/resource.c:pnp_add_dma_resource
  - drivers/pnp/resource.c:pnp_add_irq_resource
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_host_set_state
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_logging.c:scsi_print_result
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scmd_printk
  - drivers/scsi/scsi_logging.c:sdev_prefix_printk
  - drivers/ata/libata-core.c:ata_print_version
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
  - arch/x86/pci/i386.c:pcibios_resource_survey_bus
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
```
**Symbols:**

```
ffffffff8169d700-ffffffff8169d774: dev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dev_printk(const char *level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816d8d08)
Location: drivers/base/core.c:3312
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/hotplug/shpchp_core.c:get_adapter_status
  - drivers/pci/hotplug/shpchp_core.c:get_latch_status
  - drivers/pci/hotplug/shpchp_core.c:get_attention_status
  - drivers/pci/hotplug/shpchp_core.c:get_power_status
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
  - drivers/pci/hotplug/shpchp_core.c:set_attention_status
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_mode1_ECC_cap
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log_header
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/pnp/core.c:pnp_add_device
  - drivers/pnp/resource.c:pnp_add_bus_resource
  - drivers/pnp/resource.c:pnp_add_mem_resource
  - drivers/pnp/resource.c:pnp_add_io_resource
  - drivers/pnp/resource.c:pnp_add_dma_resource
  - drivers/pnp/resource.c:pnp_add_irq_resource
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_host_set_state
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_logging.c:scsi_print_result
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scmd_printk
  - drivers/scsi/scsi_logging.c:sdev_prefix_printk
  - drivers/ata/libata-core.c:ata_print_version
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
  - arch/x86/pci/i386.c:pcibios_resource_survey_bus
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
```
**Symbols:**

```
ffffffff816d8d08-ffffffff816d8d7c: dev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dev_printk(const char *level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816fcd8e)
Location: drivers/base/core.c:3464
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/hotplug/shpchp_core.c:get_adapter_status
  - drivers/pci/hotplug/shpchp_core.c:get_latch_status
  - drivers/pci/hotplug/shpchp_core.c:get_attention_status
  - drivers/pci/hotplug/shpchp_core.c:get_power_status
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
  - drivers/pci/hotplug/shpchp_core.c:set_attention_status
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_mode1_ECC_cap
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log_header
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/pnp/core.c:pnp_add_device
  - drivers/pnp/resource.c:pnp_add_bus_resource
  - drivers/pnp/resource.c:pnp_add_mem_resource
  - drivers/pnp/resource.c:pnp_add_io_resource
  - drivers/pnp/resource.c:pnp_add_dma_resource
  - drivers/pnp/resource.c:pnp_add_irq_resource
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_host_set_state
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_logging.c:scsi_print_result
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scmd_printk
  - drivers/scsi/scsi_logging.c:sdev_prefix_printk
  - drivers/ata/libata-core.c:ata_print_version
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
  - arch/x86/pci/i386.c:pcibios_resource_survey_bus
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
```
**Symbols:**

```
ffffffff816fcd8e-ffffffff816fce02: dev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dev_printk(const char *level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b66e1)
Location: drivers/base/core.c:3932
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_ixp4x0_rev
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
  - drivers/pci/hotplug/shpchp_core.c:get_adapter_status
  - drivers/pci/hotplug/shpchp_core.c:get_latch_status
  - drivers/pci/hotplug/shpchp_core.c:get_attention_status
  - drivers/pci/hotplug/shpchp_core.c:get_power_status
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
  - drivers/pci/hotplug/shpchp_core.c:set_attention_status
  - drivers/pci/hotplug/shpchp_core.c:init_slots
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
  - drivers/pci/hotplug/shpchp_ctrl.c:remove_board
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button
  - drivers/pci/hotplug/shpchp_ctrl.c:amd_pogo_errata_restore_misc_reg
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_mode1_ECC_cap
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/video/hdmi.c:hdmi_vendor_any_infoframe_log
  - drivers/video/hdmi.c:hdmi_vendor_any_infoframe_log
  - drivers/video/hdmi.c:hdmi_vendor_any_infoframe_log
  - drivers/video/hdmi.c:hdmi_vendor_any_infoframe_log
  - drivers/video/hdmi.c:hdmi_vendor_any_infoframe_log
  - drivers/video/hdmi.c:hdmi_drm_infoframe_log
  - drivers/video/hdmi.c:hdmi_drm_infoframe_log
  - drivers/video/hdmi.c:hdmi_drm_infoframe_log
  - drivers/video/hdmi.c:hdmi_drm_infoframe_log
  - drivers/video/hdmi.c:hdmi_drm_infoframe_log
  - drivers/video/hdmi.c:hdmi_drm_infoframe_log
  - drivers/video/hdmi.c:hdmi_drm_infoframe_log
  - drivers/video/hdmi.c:hdmi_drm_infoframe_log
  - drivers/video/hdmi.c:hdmi_drm_infoframe_log
  - drivers/video/hdmi.c:hdmi_drm_infoframe_log
  - drivers/video/hdmi.c:hdmi_drm_infoframe_log
  - drivers/video/hdmi.c:hdmi_audio_infoframe_log
  - drivers/video/hdmi.c:hdmi_audio_infoframe_log
  - drivers/video/hdmi.c:hdmi_audio_infoframe_log
  - drivers/video/hdmi.c:hdmi_audio_infoframe_log
  - drivers/video/hdmi.c:hdmi_audio_infoframe_log
  - drivers/video/hdmi.c:hdmi_audio_infoframe_log
  - drivers/video/hdmi.c:hdmi_audio_infoframe_log
  - drivers/video/hdmi.c:hdmi_audio_infoframe_log
  - drivers/video/hdmi.c:hdmi_audio_infoframe_log
  - drivers/video/hdmi.c:hdmi_spd_infoframe_log
  - drivers/video/hdmi.c:hdmi_spd_infoframe_log
  - drivers/video/hdmi.c:hdmi_spd_infoframe_log
  - drivers/video/hdmi.c:hdmi_avi_infoframe_log
  - drivers/video/hdmi.c:hdmi_avi_infoframe_log
  - drivers/video/hdmi.c:hdmi_avi_infoframe_log
  - drivers/video/hdmi.c:hdmi_avi_infoframe_log
  - drivers/video/hdmi.c:hdmi_avi_infoframe_log
  - drivers/video/hdmi.c:hdmi_avi_infoframe_log
  - drivers/video/hdmi.c:hdmi_avi_infoframe_log
  - drivers/video/hdmi.c:hdmi_avi_infoframe_log
  - drivers/video/hdmi.c:hdmi_avi_infoframe_log
  - drivers/video/hdmi.c:hdmi_avi_infoframe_log
  - drivers/video/hdmi.c:hdmi_avi_infoframe_log
  - drivers/video/hdmi.c:hdmi_avi_infoframe_log
  - drivers/video/hdmi.c:hdmi_avi_infoframe_log
  - drivers/video/hdmi.c:hdmi_avi_infoframe_log
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/pnp/core.c:pnp_add_device
  - drivers/pnp/resource.c:pnp_add_bus_resource
  - drivers/pnp/resource.c:pnp_add_mem_resource
  - drivers/pnp/resource.c:pnp_add_io_resource
  - drivers/pnp/resource.c:pnp_add_dma_resource
  - drivers/pnp/resource.c:pnp_add_irq_resource
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_host_set_state
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_unjam_host
  - drivers/scsi/scsi_error.c:scsi_unjam_host
  - drivers/scsi/scsi_error.c:scsi_restart_operations
  - drivers/scsi/scsi_error.c:scsi_eh_host_reset
  - drivers/scsi/scsi_error.c:scsi_eh_host_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_logging.c:scsi_print_result
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scmd_printk
  - drivers/scsi/scsi_logging.c:sdev_prefix_printk
  - drivers/ata/libata-core.c:ata_print_version
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - arch/x86/pci/i386.c:pcibios_resource_survey_bus
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
```
**Symbols:**

```
ffffffff817b66e1-ffffffff817b6755: dev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dev_printk(const char *level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81c0de2f)
Location: drivers/base/core.c:4330
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_ixp4x0_rev
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - drivers/pci/pcie/aer.c:aer_print_error
  - drivers/pci/pcie/aer.c:aer_print_error
  - drivers/pci/pcie/aer.c:__aer_print_error
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
  - drivers/pci/hotplug/shpchp_core.c:get_adapter_status
  - drivers/pci/hotplug/shpchp_core.c:get_latch_status
  - drivers/pci/hotplug/shpchp_core.c:get_attention_status
  - drivers/pci/hotplug/shpchp_core.c:get_power_status
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
  - drivers/pci/hotplug/shpchp_core.c:set_attention_status
  - drivers/pci/hotplug/shpchp_core.c:init_slots
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
  - drivers/pci/hotplug/shpchp_ctrl.c:remove_board
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button
  - drivers/pci/hotplug/shpchp_ctrl.c:amd_pogo_errata_restore_misc_reg
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_mode1_ECC_cap
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/video/hdmi.c:hdmi_vendor_any_infoframe_log
  - drivers/video/hdmi.c:hdmi_vendor_any_infoframe_log
  - drivers/video/hdmi.c:hdmi_vendor_any_infoframe_log
  - drivers/video/hdmi.c:hdmi_vendor_any_infoframe_log
  - drivers/video/hdmi.c:hdmi_vendor_any_infoframe_log
  - drivers/video/hdmi.c:hdmi_drm_infoframe_log
  - drivers/video/hdmi.c:hdmi_drm_infoframe_log
  - drivers/video/hdmi.c:hdmi_drm_infoframe_log
  - drivers/video/hdmi.c:hdmi_drm_infoframe_log
  - drivers/video/hdmi.c:hdmi_drm_infoframe_log
  - drivers/video/hdmi.c:hdmi_drm_infoframe_log
  - drivers/video/hdmi.c:hdmi_drm_infoframe_log
  - drivers/video/hdmi.c:hdmi_drm_infoframe_log
  - drivers/video/hdmi.c:hdmi_drm_infoframe_log
  - drivers/video/hdmi.c:hdmi_drm_infoframe_log
  - drivers/video/hdmi.c:hdmi_drm_infoframe_log
  - drivers/video/hdmi.c:hdmi_audio_infoframe_log
  - drivers/video/hdmi.c:hdmi_audio_infoframe_log
  - drivers/video/hdmi.c:hdmi_audio_infoframe_log
  - drivers/video/hdmi.c:hdmi_audio_infoframe_log
  - drivers/video/hdmi.c:hdmi_audio_infoframe_log
  - drivers/video/hdmi.c:hdmi_audio_infoframe_log
  - drivers/video/hdmi.c:hdmi_audio_infoframe_log
  - drivers/video/hdmi.c:hdmi_audio_infoframe_log
  - drivers/video/hdmi.c:hdmi_audio_infoframe_log
  - drivers/video/hdmi.c:hdmi_spd_infoframe_log
  - drivers/video/hdmi.c:hdmi_spd_infoframe_log
  - drivers/video/hdmi.c:hdmi_spd_infoframe_log
  - drivers/video/hdmi.c:hdmi_avi_infoframe_log
  - drivers/video/hdmi.c:hdmi_avi_infoframe_log
  - drivers/video/hdmi.c:hdmi_avi_infoframe_log
  - drivers/video/hdmi.c:hdmi_avi_infoframe_log
  - drivers/video/hdmi.c:hdmi_avi_infoframe_log
  - drivers/video/hdmi.c:hdmi_avi_infoframe_log
  - drivers/video/hdmi.c:hdmi_avi_infoframe_log
  - drivers/video/hdmi.c:hdmi_avi_infoframe_log
  - drivers/video/hdmi.c:hdmi_avi_infoframe_log
  - drivers/video/hdmi.c:hdmi_avi_infoframe_log
  - drivers/video/hdmi.c:hdmi_avi_infoframe_log
  - drivers/video/hdmi.c:hdmi_avi_infoframe_log
  - drivers/video/hdmi.c:hdmi_avi_infoframe_log
  - drivers/video/hdmi.c:hdmi_avi_infoframe_log
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/pnp/core.c:pnp_add_device
  - drivers/pnp/resource.c:pnp_add_bus_resource
  - drivers/pnp/resource.c:pnp_add_mem_resource
  - drivers/pnp/resource.c:pnp_add_io_resource
  - drivers/pnp/resource.c:pnp_add_dma_resource
  - drivers/pnp/resource.c:pnp_add_irq_resource
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_host_set_state
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_unjam_host
  - drivers/scsi/scsi_error.c:scsi_unjam_host
  - drivers/scsi/scsi_error.c:scsi_restart_operations
  - drivers/scsi/scsi_error.c:scsi_eh_host_reset
  - drivers/scsi/scsi_error.c:scsi_eh_host_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_prep_async_scan
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_logging.c:scsi_print_result
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scmd_printk
  - drivers/scsi/scsi_logging.c:sdev_prefix_printk
  - drivers/ata/libata-core.c:ata_print_version
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - arch/x86/pci/i386.c:pcibios_resource_survey_bus
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
```
**Symbols:**

```
ffffffff81c0de2f-ffffffff81c0dea3: dev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dev_printk(const char *level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81c001cd)
Location: drivers/base/core.c:4557
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - drivers/pci/pcie/aer.c:aer_print_error
  - drivers/pci/pcie/aer.c:aer_print_error
  - drivers/pci/pcie/aer.c:__aer_print_error
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
  - drivers/pci/hotplug/shpchp_core.c:get_adapter_status
  - drivers/pci/hotplug/shpchp_core.c:get_latch_status
  - drivers/pci/hotplug/shpchp_core.c:get_attention_status
  - drivers/pci/hotplug/shpchp_core.c:get_power_status
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
  - drivers/pci/hotplug/shpchp_core.c:set_attention_status
  - drivers/pci/hotplug/shpchp_core.c:init_slots
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button
  - drivers/pci/hotplug/shpchp_ctrl.c:amd_pogo_errata_restore_misc_reg
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_mode1_ECC_cap
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_audio_infoframe_log
  - drivers/video/hdmi.c:hdmi_audio_infoframe_log
  - drivers/video/hdmi.c:hdmi_audio_infoframe_log
  - drivers/video/hdmi.c:hdmi_audio_infoframe_log
  - drivers/video/hdmi.c:hdmi_audio_infoframe_log
  - drivers/video/hdmi.c:hdmi_audio_infoframe_log
  - drivers/video/hdmi.c:hdmi_audio_infoframe_log
  - drivers/video/hdmi.c:hdmi_audio_infoframe_log
  - drivers/video/hdmi.c:hdmi_audio_infoframe_log
  - drivers/video/hdmi.c:hdmi_avi_infoframe_log
  - drivers/video/hdmi.c:hdmi_avi_infoframe_log
  - drivers/video/hdmi.c:hdmi_avi_infoframe_log
  - drivers/video/hdmi.c:hdmi_avi_infoframe_log
  - drivers/video/hdmi.c:hdmi_avi_infoframe_log
  - drivers/video/hdmi.c:hdmi_avi_infoframe_log
  - drivers/video/hdmi.c:hdmi_avi_infoframe_log
  - drivers/video/hdmi.c:hdmi_avi_infoframe_log
  - drivers/video/hdmi.c:hdmi_avi_infoframe_log
  - drivers/video/hdmi.c:hdmi_avi_infoframe_log
  - drivers/video/hdmi.c:hdmi_avi_infoframe_log
  - drivers/video/hdmi.c:hdmi_avi_infoframe_log
  - drivers/video/hdmi.c:hdmi_avi_infoframe_log
  - drivers/video/hdmi.c:hdmi_avi_infoframe_log
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/pnp/core.c:pnp_add_device
  - drivers/pnp/resource.c:pnp_add_bus_resource
  - drivers/pnp/resource.c:pnp_add_mem_resource
  - drivers/pnp/resource.c:pnp_add_io_resource
  - drivers/pnp/resource.c:pnp_add_dma_resource
  - drivers/pnp/resource.c:pnp_add_irq_resource
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_host_set_state
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_unjam_host
  - drivers/scsi/scsi_error.c:scsi_unjam_host
  - drivers/scsi/scsi_error.c:scsi_eh_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_logging.c:scsi_print_result
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scmd_printk
  - drivers/scsi/scsi_logging.c:sdev_prefix_printk
  - drivers/ata/libata-core.c:ata_print_version
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
  - arch/x86/pci/i386.c:pcibios_resource_survey_bus
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
```
**Symbols:**

```
ffffffff81c001cd-ffffffff81c00241: dev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void dev_printk(const char *level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffff8000108e79cc)
Location: drivers/base/core.c:3464
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/hotplug/shpchp_core.c:get_adapter_status
  - drivers/pci/hotplug/shpchp_core.c:get_latch_status
  - drivers/pci/hotplug/shpchp_core.c:get_attention_status
  - drivers/pci/hotplug/shpchp_core.c:get_power_status
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
  - drivers/pci/hotplug/shpchp_core.c:set_attention_status
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_mode1_ECC_cap
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log_header
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/pnp/core.c:pnp_add_device
  - drivers/pnp/resource.c:pnp_add_bus_resource
  - drivers/pnp/resource.c:pnp_add_mem_resource
  - drivers/pnp/resource.c:pnp_add_io_resource
  - drivers/pnp/resource.c:pnp_add_dma_resource
  - drivers/pnp/resource.c:pnp_add_irq_resource
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_host_set_state
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_logging.c:scsi_print_result
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scmd_printk
  - drivers/scsi/scsi_logging.c:sdev_prefix_printk
  - drivers/ata/libata-core.c:ata_print_version
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
```
**Symbols:**

```
ffff8000108e79cc-ffff8000108e7a60: dev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dev_printk(const char *level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c09d5e1c)
Location: drivers/base/core.c:3464
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log_header
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_host_set_state
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_logging.c:scsi_print_result
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scmd_printk
  - drivers/scsi/scsi_logging.c:sdev_prefix_printk
  - drivers/ata/libata-core.c:ata_print_version
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/musb/musb_core.c:musb_stage0_irq
  - drivers/usb/musb/musb_core.c:musb_stage0_irq
  - drivers/usb/musb/musb_core.c:musb_stage0_irq
  - drivers/usb/musb/musb_core.c:musb_stage0_irq
```
**Symbols:**

```
c09d5e1c-c09d5e90: dev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dev_printk(const char *level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c00000000097dc2c)
Location: drivers/base/core.c:3464
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log_header
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_host_set_state
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_logging.c:scsi_print_result
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scmd_printk
  - drivers/scsi/scsi_logging.c:sdev_prefix_printk
  - drivers/scsi/scsi_transport_srp.c:srp_reconnect_work
  - drivers/ata/libata-core.c:ata_print_version
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
```
**Symbols:**

```
c00000000097dc2c-c00000000097dcb4: dev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dev_printk(const char *level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffe00057bf3c)
Location: drivers/base/core.c:3464
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/hotplug/shpchp_core.c:get_adapter_status
  - drivers/pci/hotplug/shpchp_core.c:get_latch_status
  - drivers/pci/hotplug/shpchp_core.c:get_attention_status
  - drivers/pci/hotplug/shpchp_core.c:get_power_status
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
  - drivers/pci/hotplug/shpchp_core.c:set_attention_status
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_mode1_ECC_cap
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log_header
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_host_set_state
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_logging.c:scsi_print_result
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scmd_printk
  - drivers/scsi/scsi_logging.c:sdev_prefix_printk
  - drivers/ata/libata-core.c:ata_print_version
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
```
**Symbols:**

```
ffffffe00057bf3c-ffffffe00057bf9a: dev_printk (STB_GLOBAL)
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
void dev_printk(const char *level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816c257e)
Location: drivers/base/core.c:3464
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/hotplug/shpchp_core.c:get_adapter_status
  - drivers/pci/hotplug/shpchp_core.c:get_latch_status
  - drivers/pci/hotplug/shpchp_core.c:get_attention_status
  - drivers/pci/hotplug/shpchp_core.c:get_power_status
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
  - drivers/pci/hotplug/shpchp_core.c:set_attention_status
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_mode1_ECC_cap
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log_header
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/pnp/core.c:pnp_add_device
  - drivers/pnp/resource.c:pnp_add_bus_resource
  - drivers/pnp/resource.c:pnp_add_mem_resource
  - drivers/pnp/resource.c:pnp_add_io_resource
  - drivers/pnp/resource.c:pnp_add_dma_resource
  - drivers/pnp/resource.c:pnp_add_irq_resource
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_host_set_state
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_logging.c:scsi_print_result
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scmd_printk
  - drivers/scsi/scsi_logging.c:sdev_prefix_printk
  - drivers/ata/libata-core.c:ata_print_version
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
  - arch/x86/pci/i386.c:pcibios_resource_survey_bus
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
```
**Symbols:**

```
ffffffff816c257e-ffffffff816c25f2: dev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dev_printk(const char *level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169d82e)
Location: drivers/base/core.c:3464
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/hotplug/shpchp_core.c:get_adapter_status
  - drivers/pci/hotplug/shpchp_core.c:get_latch_status
  - drivers/pci/hotplug/shpchp_core.c:get_attention_status
  - drivers/pci/hotplug/shpchp_core.c:get_power_status
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
  - drivers/pci/hotplug/shpchp_core.c:set_attention_status
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_mode1_ECC_cap
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log_header
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/pnp/core.c:pnp_add_device
  - drivers/pnp/resource.c:pnp_add_bus_resource
  - drivers/pnp/resource.c:pnp_add_mem_resource
  - drivers/pnp/resource.c:pnp_add_io_resource
  - drivers/pnp/resource.c:pnp_add_dma_resource
  - drivers/pnp/resource.c:pnp_add_irq_resource
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_host_set_state
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_logging.c:scsi_print_result
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scmd_printk
  - drivers/scsi/scsi_logging.c:sdev_prefix_printk
  - drivers/scsi/scsi_transport_fc.c:fc_vport_sched_delete
  - drivers/scsi/scsi_transport_fc.c:fc_vport_setup
  - drivers/scsi/scsi_transport_fc.c:fc_timeout_deleted_rport
  - drivers/scsi/scsi_transport_fc.c:fc_timeout_deleted_rport
  - drivers/scsi/scsi_transport_fc.c:fc_timeout_deleted_rport
  - drivers/scsi/scsi_transport_fc.c:fc_timeout_deleted_rport
  - drivers/ata/libata-core.c:ata_print_version
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
  - arch/x86/pci/i386.c:pcibios_resource_survey_bus
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
```
**Symbols:**

```
ffffffff8169d82e-ffffffff8169d8a2: dev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dev_printk(const char *level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816f0a4e)
Location: drivers/base/core.c:3464
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/hotplug/shpchp_core.c:get_adapter_status
  - drivers/pci/hotplug/shpchp_core.c:get_latch_status
  - drivers/pci/hotplug/shpchp_core.c:get_attention_status
  - drivers/pci/hotplug/shpchp_core.c:get_power_status
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
  - drivers/pci/hotplug/shpchp_core.c:set_attention_status
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_mode1_ECC_cap
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log_header
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/pnp/core.c:pnp_add_device
  - drivers/pnp/resource.c:pnp_add_bus_resource
  - drivers/pnp/resource.c:pnp_add_mem_resource
  - drivers/pnp/resource.c:pnp_add_io_resource
  - drivers/pnp/resource.c:pnp_add_dma_resource
  - drivers/pnp/resource.c:pnp_add_irq_resource
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_host_set_state
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_logging.c:scsi_print_result
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scmd_printk
  - drivers/scsi/scsi_logging.c:sdev_prefix_printk
  - drivers/ata/libata-core.c:ata_print_version
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
  - arch/x86/pci/i386.c:pcibios_resource_survey_bus
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
```
**Symbols:**

```
ffffffff816f0a4e-ffffffff816f0ac2: dev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dev_printk(const char *level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8170b28e)
Location: drivers/base/core.c:3464
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:ati_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:vt8237_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/hotplug/shpchp_core.c:get_adapter_status
  - drivers/pci/hotplug/shpchp_core.c:get_latch_status
  - drivers/pci/hotplug/shpchp_core.c:get_attention_status
  - drivers/pci/hotplug/shpchp_core.c:get_power_status
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
  - drivers/pci/hotplug/shpchp_core.c:set_attention_status
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_mode1_ECC_cap
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log
  - drivers/video/hdmi.c:hdmi_infoframe_log_header
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/pnp/core.c:pnp_add_device
  - drivers/pnp/resource.c:pnp_add_bus_resource
  - drivers/pnp/resource.c:pnp_add_mem_resource
  - drivers/pnp/resource.c:pnp_add_io_resource
  - drivers/pnp/resource.c:pnp_add_dma_resource
  - drivers/pnp/resource.c:pnp_add_irq_resource
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_host_set_state
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_logging.c:scsi_print_result
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scmd_printk
  - drivers/scsi/scsi_logging.c:sdev_prefix_printk
  - drivers/ata/libata-core.c:ata_print_version
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
  - arch/x86/pci/i386.c:pcibios_resource_survey_bus
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
```
**Symbols:**

```
ffffffff8170b28e-ffffffff8170b302: dev_printk (STB_GLOBAL)
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
