# Function: <code>ata_link_next</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct ata_link *ata_link_next(struct ata_link *link, struct ata_port *ap, enum ata_link_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff815c7ef0)
Location: drivers/ata/libata-core.c:194
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
Direct callers:
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
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
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff815c7ef0-ffffffff815c7f9b: ata_link_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct ata_link *ata_link_next(struct ata_link *link, struct ata_port *ap, enum ata_link_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816272fa)
Location: drivers/ata/libata-core.c:197
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff81620b10-ffffffff81620bbf: ata_link_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct ata_link *ata_link_next(struct ata_link *link, struct ata_port *ap, enum ata_link_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81657f64)
Location: drivers/ata/libata-core.c:197
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff81651680-ffffffff8165172f: ata_link_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct ata_link *ata_link_next(struct ata_link *link, struct ata_port *ap, enum ata_link_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81665d80)
Location: drivers/ata/libata-core.c:197
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff81665d80-ffffffff81665e24: ata_link_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct ata_link *ata_link_next(struct ata_link *link, struct ata_port *ap, enum ata_link_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816cf3c0)
Location: drivers/ata/libata-core.c:197
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff816cf3c0-ffffffff816cf460: ata_link_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct ata_link *ata_link_next(struct ata_link *link, struct ata_port *ap, enum ata_link_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8170bde0)
Location: drivers/ata/libata-core.c:197
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff8170bde0-ffffffff8170be7d: ata_link_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct ata_link *ata_link_next(struct ata_link *link, struct ata_port *ap, enum ata_link_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8172e260)
Location: drivers/ata/libata-core.c:197
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff8172e260-ffffffff8172e2fd: ata_link_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct ata_link *ata_link_next(struct ata_link *link, struct ata_port *ap, enum ata_link_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff817699e0)
Location: drivers/ata/libata-core.c:181
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff817699e0-ffffffff81769a9c: ata_link_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct ata_link *ata_link_next(struct ata_link *link, struct ata_port *ap, enum ata_link_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8178dab0)
Location: drivers/ata/libata-core.c:181
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff8178dab0-ffffffff8178db6c: ata_link_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct ata_link *ata_link_next(struct ata_link *link, struct ata_port *ap, enum ata_link_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8185400c)
Location: drivers/ata/libata-core.c:180
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_dev_xfermask
Direct callers:
  - drivers/ata/libata-core.c:ata_port_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_dev_xfermask
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-eh.c:ata_eh_handle_port_resume
  - drivers/ata/libata-eh.c:ata_eh_handle_port_resume
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
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_eh_unload
  - drivers/ata/libata-eh.c:ata_eh_unload
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
  - drivers/ata/libata-pmp.c:sata_pmp_eh_handle_disabled_links
  - drivers/ata/libata-pmp.c:sata_pmp_eh_handle_disabled_links
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff81852310-ffffffff818523cc: ata_link_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct ata_link *ata_link_next(struct ata_link *link, struct ata_port *ap, enum ata_link_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff818642dc)
Location: drivers/ata/libata-core.c:180
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_dev_xfermask
Direct callers:
  - drivers/ata/libata-core.c:ata_port_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_dev_xfermask
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-eh.c:ata_eh_handle_port_resume
  - drivers/ata/libata-eh.c:ata_eh_handle_port_resume
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
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_eh_unload
  - drivers/ata/libata-eh.c:ata_eh_unload
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
  - drivers/ata/libata-pmp.c:sata_pmp_eh_handle_disabled_links
  - drivers/ata/libata-pmp.c:sata_pmp_eh_handle_disabled_links
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff81862670-ffffffff8186272c: ata_link_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct ata_link *ata_link_next(struct ata_link *link, struct ata_port *ap, enum ata_link_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff818461c6)
Location: drivers/ata/libata-core.c:180
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_dev_xfermask
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_dev_xfermask
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-eh.c:ata_eh_handle_port_resume
  - drivers/ata/libata-eh.c:ata_eh_handle_port_resume
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
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff81845470-ffffffff81845529: ata_link_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct ata_link *ata_link_next(struct ata_link *link, struct ata_port *ap, enum ata_link_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff818d2be8)
Location: drivers/ata/libata-core.c:186
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_dev_xfermask
  - drivers/ata/libata-core.c:ata_dev_xfermask
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-eh.c:ata_eh_handle_port_resume
  - drivers/ata/libata-eh.c:ata_eh_handle_port_resume
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
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff818d1ef0-ffffffff818d1fa9: ata_link_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct ata_link *ata_link_next(struct ata_link *link, struct ata_port *ap, enum ata_link_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81a23318)
Location: drivers/ata/libata-core.c:187
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_dev_xfermask
  - drivers/ata/libata-core.c:ata_dev_xfermask
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-eh.c:ata_eh_handle_port_resume
  - drivers/ata/libata-eh.c:ata_eh_handle_port_resume
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
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-sata.c:sata_async_notification
  - drivers/ata/libata-sata.c:sata_async_notification
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff81a22280-ffffffff81a22387: ata_link_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct ata_link *ata_link_next(struct ata_link *link, struct ata_port *ap, enum ata_link_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81ba50f8)
Location: drivers/ata/libata-core.c:187
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_dev_xfermask
  - drivers/ata/libata-core.c:ata_dev_xfermask
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-eh.c:ata_eh_handle_port_resume
  - drivers/ata/libata-eh.c:ata_eh_handle_port_resume
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
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-sata.c:sata_async_notification
  - drivers/ata/libata-sata.c:sata_async_notification
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff81ba3840-ffffffff81ba3947: ata_link_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct ata_link *ata_link_next(struct ata_link *link, struct ata_port *ap, enum ata_link_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81bfbf55)
Location: drivers/ata/libata-core.c:187
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_dev_xfermask
  - drivers/ata/libata-core.c:ata_dev_xfermask
  - drivers/ata/libata-core.c:ata_dev_xfermask
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-eh.c:ata_eh_handle_port_resume
  - drivers/ata/libata-eh.c:ata_eh_handle_port_resume
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
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-sata.c:sata_async_notification
  - drivers/ata/libata-sata.c:sata_async_notification
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff81bfc2a0-ffffffff81bfc39d: ata_link_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct ata_link *ata_link_next(struct ata_link *link, struct ata_port *ap, enum ata_link_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81c51b85)
Location: drivers/ata/libata-core.c:187
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_detach
  - drivers/ata/libata-core.c:ata_port_detach
  - drivers/ata/libata-core.c:ata_port_detach
  - drivers/ata/libata-core.c:ata_port_detach
  - drivers/ata/libata-core.c:ata_port_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_dev_xfermask
  - drivers/ata/libata-core.c:ata_dev_xfermask
  - drivers/ata/libata-core.c:ata_dev_xfermask
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
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
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_eh_unload
  - drivers/ata/libata-eh.c:ata_eh_unload
  - drivers/ata/libata-eh.c:ata_eh_unload
  - drivers/ata/libata-eh.c:ata_eh_unload
  - drivers/ata/libata-sata.c:sata_async_notification
  - drivers/ata/libata-sata.c:sata_async_notification
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-pmp.c:sata_pmp_quirks
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff81c52210-ffffffff81c52312: ata_link_next (STB_GLOBAL)
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
struct ata_link *ata_link_next(struct ata_link *link, struct ata_port *ap, enum ata_link_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffff800010996700)
Location: drivers/ata/libata-core.c:181
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libahci.c:ahci_port_resume
  - drivers/ata/libahci.c:ahci_port_resume
  - drivers/ata/libahci.c:ahci_port_resume
  - drivers/ata/libahci.c:ahci_port_resume
  - drivers/ata/libahci.c:ahci_error_intr
  - drivers/ata/libahci.c:ahci_error_intr
  - drivers/ata/libahci.c:ahci_led_show
  - drivers/ata/libahci.c:ahci_led_show
```
**Symbols:**

```
ffff800010996700-ffff8000109967fc: ata_link_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct ata_link *ata_link_next(struct ata_link *link, struct ata_port *ap, enum ata_link_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c0a66dc0)
Location: drivers/ata/libata-core.c:181
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libahci.c:ahci_port_resume
  - drivers/ata/libahci.c:ahci_port_resume
  - drivers/ata/libahci.c:ahci_port_resume
  - drivers/ata/libahci.c:ahci_port_resume
  - drivers/ata/libahci.c:ahci_error_intr
  - drivers/ata/libahci.c:ahci_error_intr
  - drivers/ata/libahci.c:ahci_led_show
  - drivers/ata/libahci.c:ahci_led_show
```
**Symbols:**

```
c0a66dc0-c0a66ea4: ata_link_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct ata_link *ata_link_next(struct ata_link *link, struct ata_port *ap, enum ata_link_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c000000000a59330)
Location: drivers/ata/libata-core.c:181
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
c000000000a59330-c000000000a5941c: ata_link_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct ata_link *ata_link_next(struct ata_link *link, struct ata_port *ap, enum ata_link_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffe0005f7e4e)
Location: drivers/ata/libata-core.c:181
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
ffffffe0005f7e4e-ffffffe0005f7f42: ata_link_next (STB_GLOBAL)
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
struct ata_link *ata_link_next(struct ata_link *link, struct ata_port *ap, enum ata_link_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81752c40)
Location: drivers/ata/libata-core.c:181
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff81752c40-ffffffff81752cfc: ata_link_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct ata_link *ata_link_next(struct ata_link *link, struct ata_port *ap, enum ata_link_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81732ae0)
Location: drivers/ata/libata-core.c:181
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff81732ae0-ffffffff81732b9c: ata_link_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct ata_link *ata_link_next(struct ata_link *link, struct ata_port *ap, enum ata_link_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81782930)
Location: drivers/ata/libata-core.c:181
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff81782930-ffffffff817829ec: ata_link_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct ata_link *ata_link_next(struct ata_link *link, struct ata_port *ap, enum ata_link_iter_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8179c7f0)
Location: drivers/ata/libata-core.c:181
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:ata_eh_autopsy
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff8179c7f0-ffffffff8179c8ac: ata_link_next (STB_GLOBAL)
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
