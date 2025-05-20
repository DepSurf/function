# Function: <code>_dev_printk</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void _dev_printk(const char *level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81d0273e)
Location: drivers/base/core.c:4622
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
  - drivers/pci/hotplug/shpchp_ctrl.c:change_bus_speed
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
  - drivers/pnp/resource.c:pnp_add_bus_resource
  - drivers/pnp/resource.c:pnp_add_mem_resource
  - drivers/pnp/resource.c:pnp_add_io_resource
  - drivers/pnp/resource.c:pnp_add_dma_resource
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
  - arch/x86/pci/i386.c:pcibios_resource_survey_bus
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
```
**Symbols:**

```
ffffffff81d0273e-ffffffff81d027b2: _dev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void _dev_printk(const char *level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ecad44)
Location: drivers/base/core.c:4656
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:nvidia_force_enable_hpet
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
  - drivers/pci/hotplug/shpchp_ctrl.c:change_bus_speed
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
  - drivers/pnp/resource.c:pnp_add_bus_resource
  - drivers/pnp/resource.c:pnp_add_mem_resource
  - drivers/pnp/resource.c:pnp_add_io_resource
  - drivers/pnp/resource.c:pnp_add_dma_resource
  - drivers/scsi/hosts.c:scsi_flush_work
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
  - arch/x86/pci/i386.c:pcibios_resource_survey_bus
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
```
**Symbols:**

```
ffffffff81ecad44-ffffffff81ecade5: _dev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void _dev_printk(const char *level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae2c00)
Location: drivers/base/core.c:4875
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:nvidia_force_enable_hpet
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
  - drivers/pci/hotplug/shpchp_ctrl.c:change_bus_speed
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
  - drivers/video/hdmi.c:hdmi_audio_infoframe_log
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
  - drivers/video/hdmi.c:hdmi_avi_infoframe_log
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/pnp/resource.c:pnp_add_bus_resource
  - drivers/pnp/resource.c:pnp_add_mem_resource
  - drivers/pnp/resource.c:pnp_add_io_resource
  - drivers/pnp/resource.c:pnp_add_dma_resource
  - drivers/scsi/hosts.c:scsi_flush_work
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
  - drivers/scsi/scsi_proc.c:scsi_proc_host_add
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
ffffffff81ae2c00-ffffffff81ae2c91: _dev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void _dev_printk(const char *level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b30b20)
Location: drivers/base/core.c:4880
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:nvidia_force_enable_hpet
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
  - drivers/pci/hotplug/shpchp_ctrl.c:change_bus_speed
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
  - drivers/video/hdmi.c:hdmi_audio_infoframe_log
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
  - drivers/video/hdmi.c:hdmi_avi_infoframe_log
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/pnp/resource.c:pnp_add_bus_resource
  - drivers/pnp/resource.c:pnp_add_mem_resource
  - drivers/pnp/resource.c:pnp_add_io_resource
  - drivers/pnp/resource.c:pnp_add_dma_resource
  - drivers/scsi/hosts.c:scsi_flush_work
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
  - drivers/scsi/scsi_proc.c:scsi_proc_host_add
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
ffffffff81b30b20-ffffffff81b30bb1: _dev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void _dev_printk(const char *level, const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b88120)
Location: drivers/base/core.c:4893
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:nvidia_force_enable_hpet
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
  - drivers/pci/hotplug/shpchp_ctrl.c:change_bus_speed
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
  - drivers/video/hdmi.c:hdmi_audio_infoframe_log
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
  - drivers/video/hdmi.c:hdmi_avi_infoframe_log
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/pnp/resource.c:pnp_add_bus_resource
  - drivers/pnp/resource.c:pnp_add_mem_resource
  - drivers/pnp/resource.c:pnp_add_io_resource
  - drivers/pnp/resource.c:pnp_add_dma_resource
  - drivers/scsi/hosts.c:scsi_flush_work
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
  - drivers/scsi/scsi_proc.c:scsi_proc_host_add
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
  - drivers/gpu/drm/drm_print.c:__drm_dev_dbg
  - drivers/gpu/drm/drm_print.c:drm_dev_printk
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - arch/x86/pci/i386.c:pcibios_resource_survey_bus
  - arch/x86/pci/acpi.c:pci_acpi_root_prepare_resources
```
**Symbols:**

```
ffffffff81b88120-ffffffff81b881b1: _dev_printk (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
