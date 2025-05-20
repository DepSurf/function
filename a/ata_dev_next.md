# Function: <code>ata_dev_next</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct ata_device *ata_dev_next(struct ata_device *dev, struct ata_link *link, enum ata_dev_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff815c7fa0)
Location: drivers/ata/libata-core.c:253
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_do_reset
  - drivers/ata/libata-eh.c:ata_do_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_link_nr_enabled
  - drivers/ata/libata-eh.c:ata_link_nr_enabled
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_cbl_80wire
  - drivers/ata/libata-acpi.c:ata_acpi_cbl_80wire
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/ata/ata_generic.c:generic_set_mode
```
**Symbols:**

```
ffffffff815c7fa0-ffffffff815c808e: ata_dev_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct ata_device *ata_dev_next(struct ata_device *dev, struct ata_link *link, enum ata_dev_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81620bc0)
Location: drivers/ata/libata-core.c:256
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_link_nr_enabled
  - drivers/ata/libata-eh.c:ata_link_nr_enabled
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_do_reset
  - drivers/ata/libata-eh.c:ata_do_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_cbl_80wire
  - drivers/ata/libata-acpi.c:ata_acpi_cbl_80wire
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/ata/ata_generic.c:generic_set_mode
```
**Symbols:**

```
ffffffff81620bc0-ffffffff81620cac: ata_dev_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct ata_device *ata_dev_next(struct ata_device *dev, struct ata_link *link, enum ata_dev_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81651730)
Location: drivers/ata/libata-core.c:256
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_link_nr_enabled
  - drivers/ata/libata-eh.c:ata_link_nr_enabled
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_do_reset
  - drivers/ata/libata-eh.c:ata_do_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_cbl_80wire
  - drivers/ata/libata-acpi.c:ata_acpi_cbl_80wire
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/ata/ata_generic.c:generic_set_mode
```
**Symbols:**

```
ffffffff81651730-ffffffff81651821: ata_dev_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct ata_device *ata_dev_next(struct ata_device *dev, struct ata_link *link, enum ata_dev_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81665e30)
Location: drivers/ata/libata-core.c:256
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_link_nr_enabled
  - drivers/ata/libata-eh.c:ata_link_nr_enabled
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_do_reset
  - drivers/ata/libata-eh.c:ata_do_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_cbl_80wire
  - drivers/ata/libata-acpi.c:ata_acpi_cbl_80wire
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/ata/ata_generic.c:generic_set_mode
```
**Symbols:**

```
ffffffff81665e30-ffffffff81665f17: ata_dev_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct ata_device *ata_dev_next(struct ata_device *dev, struct ata_link *link, enum ata_dev_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816cf460)
Location: drivers/ata/libata-core.c:256
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_link_nr_enabled
  - drivers/ata/libata-eh.c:ata_link_nr_enabled
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_do_reset
  - drivers/ata/libata-eh.c:ata_do_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_cbl_80wire
  - drivers/ata/libata-acpi.c:ata_acpi_cbl_80wire
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/ata/ata_generic.c:generic_set_mode
```
**Symbols:**

```
ffffffff816cf460-ffffffff816cf548: ata_dev_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct ata_device *ata_dev_next(struct ata_device *dev, struct ata_link *link, enum ata_dev_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8170be80)
Location: drivers/ata/libata-core.c:256
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_link_nr_enabled
  - drivers/ata/libata-eh.c:ata_link_nr_enabled
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_do_reset
  - drivers/ata/libata-eh.c:ata_do_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_cbl_80wire
  - drivers/ata/libata-acpi.c:ata_acpi_cbl_80wire
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/ata/ata_generic.c:generic_set_mode
```
**Symbols:**

```
ffffffff8170be80-ffffffff8170bf75: ata_dev_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct ata_device *ata_dev_next(struct ata_device *dev, struct ata_link *link, enum ata_dev_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8172e300)
Location: drivers/ata/libata-core.c:256
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_link_nr_enabled
  - drivers/ata/libata-eh.c:ata_link_nr_enabled
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_do_reset
  - drivers/ata/libata-eh.c:ata_do_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_cbl_80wire
  - drivers/ata/libata-acpi.c:ata_acpi_cbl_80wire
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/ata/ata_generic.c:generic_set_mode
```
**Symbols:**

```
ffffffff8172e300-ffffffff8172e3f5: ata_dev_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct ata_device *ata_dev_next(struct ata_device *dev, struct ata_link *link, enum ata_dev_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81769aa0)
Location: drivers/ata/libata-core.c:240
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_link_nr_enabled
  - drivers/ata/libata-eh.c:ata_link_nr_enabled
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_do_reset
  - drivers/ata/libata-eh.c:ata_do_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_cbl_80wire
  - drivers/ata/libata-acpi.c:ata_acpi_cbl_80wire
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/ata/ata_generic.c:generic_set_mode
```
**Symbols:**

```
ffffffff81769aa0-ffffffff81769b79: ata_dev_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct ata_device *ata_dev_next(struct ata_device *dev, struct ata_link *link, enum ata_dev_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8178db70)
Location: drivers/ata/libata-core.c:240
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_link_nr_enabled
  - drivers/ata/libata-eh.c:ata_link_nr_enabled
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_do_reset
  - drivers/ata/libata-eh.c:ata_do_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_cbl_80wire
  - drivers/ata/libata-acpi.c:ata_acpi_cbl_80wire
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/ata/ata_generic.c:generic_set_mode
```
**Symbols:**

```
ffffffff8178db70-ffffffff8178dc49: ata_dev_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct ata_device *ata_dev_next(struct ata_device *dev, struct ata_link *link, enum ata_dev_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81854018)
Location: drivers/ata/libata-core.c:240
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_detach
  - drivers/ata/libata-core.c:ata_port_detach
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
Direct callers:
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_dev_xfermask
  - drivers/ata/libata-core.c:ata_dev_xfermask
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-eh.c:ata_eh_handle_port_resume
  - drivers/ata/libata-eh.c:ata_eh_handle_port_resume
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_do_reset
  - drivers/ata/libata-eh.c:ata_do_reset
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_eh_unload
  - drivers/ata/libata-eh.c:ata_eh_unload
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_cbl_80wire
  - drivers/ata/libata-acpi.c:ata_acpi_cbl_80wire
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/ata/ata_generic.c:generic_set_mode
```
**Symbols:**

```
ffffffff81853770-ffffffff8185383b: ata_dev_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct ata_device *ata_dev_next(struct ata_device *dev, struct ata_link *link, enum ata_dev_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff818642e8)
Location: drivers/ata/libata-core.c:240
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_detach
  - drivers/ata/libata-core.c:ata_port_detach
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
Direct callers:
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_dev_xfermask
  - drivers/ata/libata-core.c:ata_dev_xfermask
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-eh.c:ata_eh_handle_port_resume
  - drivers/ata/libata-eh.c:ata_eh_handle_port_resume
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_do_reset
  - drivers/ata/libata-eh.c:ata_do_reset
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_eh_unload
  - drivers/ata/libata-eh.c:ata_eh_unload
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_cbl_80wire
  - drivers/ata/libata-acpi.c:ata_acpi_cbl_80wire
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/ata/ata_generic.c:generic_set_mode
```
**Symbols:**

```
ffffffff81863a40-ffffffff81863b0b: ata_dev_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct ata_device *ata_dev_next(struct ata_device *dev, struct ata_link *link, enum ata_dev_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff818461d2)
Location: drivers/ata/libata-core.c:240
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
Direct callers:
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_dev_xfermask
  - drivers/ata/libata-core.c:ata_dev_xfermask
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-eh.c:ata_eh_handle_port_resume
  - drivers/ata/libata-eh.c:ata_eh_handle_port_resume
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_do_reset
  - drivers/ata/libata-eh.c:ata_do_reset
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_cbl_80wire
  - drivers/ata/libata-acpi.c:ata_acpi_cbl_80wire
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/ata/ata_generic.c:generic_set_mode
```
**Symbols:**

```
ffffffff81845f90-ffffffff8184606a: ata_dev_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct ata_device *ata_dev_next(struct ata_device *dev, struct ata_link *link, enum ata_dev_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff818d2bfe)
Location: drivers/ata/libata-core.c:246
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
Direct callers:
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_dev_xfermask
  - drivers/ata/libata-core.c:ata_dev_xfermask
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-eh.c:ata_eh_handle_port_resume
  - drivers/ata/libata-eh.c:ata_eh_handle_port_resume
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_do_reset
  - drivers/ata/libata-eh.c:ata_do_reset
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_cbl_80wire
  - drivers/ata/libata-acpi.c:ata_acpi_cbl_80wire
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/ata/ata_generic.c:generic_set_mode
```
**Symbols:**

```
ffffffff818d2da0-ffffffff818d2e7a: ata_dev_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct ata_device *ata_dev_next(struct ata_device *dev, struct ata_link *link, enum ata_dev_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81a2332e)
Location: drivers/ata/libata-core.c:247
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
Direct callers:
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_dev_xfermask
  - drivers/ata/libata-core.c:ata_dev_xfermask
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-eh.c:ata_eh_handle_port_resume
  - drivers/ata/libata-eh.c:ata_eh_handle_port_resume
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_do_reset
  - drivers/ata/libata-eh.c:ata_do_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_cbl_80wire
  - drivers/ata/libata-acpi.c:ata_acpi_cbl_80wire
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/ata/ata_generic.c:generic_set_mode
```
**Symbols:**

```
ffffffff81a23df0-ffffffff81a23ef0: ata_dev_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct ata_device *ata_dev_next(struct ata_device *dev, struct ata_link *link, enum ata_dev_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81ba510e)
Location: drivers/ata/libata-core.c:247
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
Direct callers:
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_dev_xfermask
  - drivers/ata/libata-core.c:ata_dev_xfermask
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-eh.c:ata_eh_handle_port_resume
  - drivers/ata/libata-eh.c:ata_eh_handle_port_resume
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_do_reset
  - drivers/ata/libata-eh.c:ata_do_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_cbl_80wire
  - drivers/ata/libata-acpi.c:ata_acpi_cbl_80wire
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/ata/ata_generic.c:generic_set_mode
```
**Symbols:**

```
ffffffff81ba5d80-ffffffff81ba5e80: ata_dev_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct ata_device *ata_dev_next(struct ata_device *dev, struct ata_link *link, enum ata_dev_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81bfbf6b)
Location: drivers/ata/libata-core.c:247
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
Direct callers:
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_dev_xfermask
  - drivers/ata/libata-core.c:ata_dev_xfermask
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-eh.c:ata_eh_handle_port_resume
  - drivers/ata/libata-eh.c:ata_eh_handle_port_resume
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_do_reset
  - drivers/ata/libata-eh.c:ata_do_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_cbl_80wire
  - drivers/ata/libata-acpi.c:ata_acpi_cbl_80wire
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/ata/ata_generic.c:generic_set_mode
```
**Symbols:**

```
ffffffff81bfc8c0-ffffffff81bfc9e3: ata_dev_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct ata_device *ata_dev_next(struct ata_device *dev, struct ata_link *link, enum ata_dev_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81c51b95)
Location: drivers/ata/libata-core.c:247
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_detach
  - drivers/ata/libata-core.c:ata_port_detach
  - drivers/ata/libata-core.c:ata_port_detach
  - drivers/ata/libata-core.c:ata_port_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
Direct callers:
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_dev_xfermask
  - drivers/ata/libata-core.c:ata_dev_xfermask
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-eh.c:ata_eh_handle_port_resume
  - drivers/ata/libata-eh.c:ata_eh_handle_port_resume
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_do_reset
  - drivers/ata/libata-eh.c:ata_do_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_eh_unload
  - drivers/ata/libata-eh.c:ata_eh_unload
  - drivers/ata/libata-eh.c:ata_eh_unload
  - drivers/ata/libata-eh.c:ata_eh_unload
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_cbl_80wire
  - drivers/ata/libata-acpi.c:ata_acpi_cbl_80wire
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/ata/ata_generic.c:generic_set_mode
```
**Symbols:**

```
ffffffff81c52330-ffffffff81c52453: ata_dev_next (STB_GLOBAL)
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
struct ata_device *ata_dev_next(struct ata_device *dev, struct ata_link *link, enum ata_dev_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffff800010996800)
Location: drivers/ata/libata-core.c:240
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_link_nr_enabled
  - drivers/ata/libata-eh.c:ata_link_nr_enabled
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_cbl_80wire
  - drivers/ata/libata-acpi.c:ata_acpi_cbl_80wire
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/ahci_imx.c:ahci_imx_error_handler
```
**Symbols:**

```
ffff800010996800-ffff800010996934: ata_dev_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct ata_device *ata_dev_next(struct ata_device *dev, struct ata_link *link, enum ata_dev_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c0a66ea4)
Location: drivers/ata/libata-core.c:240
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_link_nr_enabled
  - drivers/ata/libata-eh.c:ata_link_nr_enabled
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/ahci_imx.c:ahci_imx_error_handler
```
**Symbols:**

```
c0a66ea4-c0a66fb8: ata_dev_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct ata_device *ata_dev_next(struct ata_device *dev, struct ata_link *link, enum ata_dev_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c000000000a59140)
Location: drivers/ata/libata-core.c:240
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_link_nr_enabled
  - drivers/ata/libata-eh.c:ata_link_nr_enabled
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
c000000000a59140-c000000000a592a4: ata_dev_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct ata_device *ata_dev_next(struct ata_device *dev, struct ata_link *link, enum ata_dev_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffe0005f7f42)
Location: drivers/ata/libata-core.c:240
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_link_nr_enabled
  - drivers/ata/libata-eh.c:ata_link_nr_enabled
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffe0005f7f42-ffffffe0005f8032: ata_dev_next (STB_GLOBAL)
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
struct ata_device *ata_dev_next(struct ata_device *dev, struct ata_link *link, enum ata_dev_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81752d00)
Location: drivers/ata/libata-core.c:240
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_link_nr_enabled
  - drivers/ata/libata-eh.c:ata_link_nr_enabled
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_do_reset
  - drivers/ata/libata-eh.c:ata_do_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_cbl_80wire
  - drivers/ata/libata-acpi.c:ata_acpi_cbl_80wire
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/ata/ata_generic.c:generic_set_mode
```
**Symbols:**

```
ffffffff81752d00-ffffffff81752dd9: ata_dev_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct ata_device *ata_dev_next(struct ata_device *dev, struct ata_link *link, enum ata_dev_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81732ba0)
Location: drivers/ata/libata-core.c:240
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_link_nr_enabled
  - drivers/ata/libata-eh.c:ata_link_nr_enabled
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_do_reset
  - drivers/ata/libata-eh.c:ata_do_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_cbl_80wire
  - drivers/ata/libata-acpi.c:ata_acpi_cbl_80wire
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/ata/ata_generic.c:generic_set_mode
```
**Symbols:**

```
ffffffff81732ba0-ffffffff81732c79: ata_dev_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct ata_device *ata_dev_next(struct ata_device *dev, struct ata_link *link, enum ata_dev_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff817829f0)
Location: drivers/ata/libata-core.c:240
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_link_nr_enabled
  - drivers/ata/libata-eh.c:ata_link_nr_enabled
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_do_reset
  - drivers/ata/libata-eh.c:ata_do_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_cbl_80wire
  - drivers/ata/libata-acpi.c:ata_acpi_cbl_80wire
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/ata/ata_generic.c:generic_set_mode
```
**Symbols:**

```
ffffffff817829f0-ffffffff81782ac9: ata_dev_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct ata_device *ata_dev_next(struct ata_device *dev, struct ata_link *link, enum ata_dev_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8179c8b0)
Location: drivers/ata/libata-core.c:240
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_link_nr_enabled
  - drivers/ata/libata-eh.c:ata_link_nr_enabled
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_set_mode
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_do_reset
  - drivers/ata/libata-eh.c:ata_do_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-eh.c:ata_eh_clear_action
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_cbl_80wire
  - drivers/ata/libata-acpi.c:ata_acpi_cbl_80wire
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/ata/ata_generic.c:generic_set_mode
```
**Symbols:**

```
ffffffff8179c8b0-ffffffff8179c989: ata_dev_next (STB_GLOBAL)
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
