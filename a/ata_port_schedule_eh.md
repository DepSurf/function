# Function: <code>ata_port_schedule_eh</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void ata_port_schedule_eh(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff815d4eed)
Location: drivers/ata/libata-eh.c:1042
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
Direct callers:
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:__ata_port_probe
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff815d5aa0-ffffffff815d5ab5: ata_port_schedule_eh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void ata_port_schedule_eh(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8162f712)
Location: drivers/ata/libata-eh.c:1042
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:__ata_port_probe
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff8162f500-ffffffff8162f515: ata_port_schedule_eh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void ata_port_schedule_eh(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81660862)
Location: drivers/ata/libata-eh.c:1042
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:__ata_port_probe
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff81660650-ffffffff81660665: ata_port_schedule_eh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void ata_port_schedule_eh(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff816758c2)
Location: drivers/ata/libata-eh.c:1043
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:__ata_port_probe
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff81675680-ffffffff81675695: ata_port_schedule_eh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void ata_port_schedule_eh(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff816def32)
Location: drivers/ata/libata-eh.c:1041
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:__ata_port_probe
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff816dece0-ffffffff816decfb: ata_port_schedule_eh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void ata_port_schedule_eh(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8171b732)
Location: drivers/ata/libata-eh.c:992
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:__ata_port_probe
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff8171b4f0-ffffffff8171b50b: ata_port_schedule_eh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void ata_port_schedule_eh(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8173e002)
Location: drivers/ata/libata-eh.c:988
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:__ata_port_probe
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff8173ddc0-ffffffff8173dddb: ata_port_schedule_eh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void ata_port_schedule_eh(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81779b6d)
Location: drivers/ata/libata-eh.c:971
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:__ata_port_probe
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff81779920-ffffffff8177993b: ata_port_schedule_eh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void ata_port_schedule_eh(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8179d9cd)
Location: drivers/ata/libata-eh.c:971
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:__ata_port_probe
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff8179d780-ffffffff8179d79b: ata_port_schedule_eh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void ata_port_schedule_eh(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81861922)
Location: drivers/ata/libata-eh.c:970
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_do_link_abort
Direct callers:
  - drivers/ata/libata-core.c:ata_port_detach
  - drivers/ata/libata-core.c:__ata_port_probe
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff8185feb0-ffffffff8185fecb: ata_port_schedule_eh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void ata_port_schedule_eh(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81870746)
Location: drivers/ata/libata-eh.c:970
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_do_link_abort
Direct callers:
  - drivers/ata/libata-core.c:ata_port_detach
  - drivers/ata/libata-core.c:__ata_port_probe
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff8186ecd0-ffffffff8186eceb: ata_port_schedule_eh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void ata_port_schedule_eh(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81852f66)
Location: drivers/ata/libata-eh.c:970
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_do_link_abort
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:__ata_port_probe
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff818514d0-ffffffff818514eb: ata_port_schedule_eh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void ata_port_schedule_eh(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff818e0fd6)
Location: drivers/ata/libata-eh.c:978
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_do_link_abort
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:__ata_port_probe
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff818df080-ffffffff818df09b: ata_port_schedule_eh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void ata_port_schedule_eh(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81a320ec)
Location: drivers/ata/libata-eh.c:975
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_do_link_abort
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:__ata_port_probe
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-sata.c:sata_async_notification
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff81a306d0-ffffffff81a306f3: ata_port_schedule_eh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void ata_port_schedule_eh(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81bb65fc)
Location: drivers/ata/libata-eh.c:977
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_do_link_abort
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:__ata_port_probe
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-sata.c:sata_async_notification
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff81bb3d00-ffffffff81bb3d23: ata_port_schedule_eh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void ata_port_schedule_eh(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81c0d9ac)
Location: drivers/ata/libata-eh.c:980
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_do_link_abort
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:__ata_port_probe
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-sata.c:sata_async_notification
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff81c0b2a0-ffffffff81c0b2c3: ata_port_schedule_eh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void ata_port_schedule_eh(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81c62c04)
Location: drivers/ata/libata-eh.c:998
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_do_link_abort
Direct callers:
  - drivers/ata/libata-core.c:ata_port_detach
  - drivers/ata/libata-core.c:ata_port_probe
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-sata.c:sata_async_notification
  - drivers/ata/libata-sata.c:ata_scsi_lpm_store
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff81c60320-ffffffff81c60343: ata_port_schedule_eh (STB_GLOBAL)
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
void ata_port_schedule_eh(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffff8000109a8e40)
Location: drivers/ata/libata-eh.c:971
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:__ata_port_probe
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffff8000109a8b20-ffff8000109a8b54: ata_port_schedule_eh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void ata_port_schedule_eh(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (c0a78b50)
Location: drivers/ata/libata-eh.c:971
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:__ata_port_probe
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
```
**Symbols:**

```
c0a78894-c0a788b8: ata_port_schedule_eh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void ata_port_schedule_eh(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (c000000000a6f700)
Location: drivers/ata/libata-eh.c:971
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:__ata_port_probe
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
```
**Symbols:**

```
c000000000a6f3c0-c000000000a6f404: ata_port_schedule_eh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void ata_port_schedule_eh(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffe000606f60)
Location: drivers/ata/libata-eh.c:971
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:__ata_port_probe
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
```
**Symbols:**

```
ffffffe000606d12-ffffffe000606d3a: ata_port_schedule_eh (STB_GLOBAL)
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
void ata_port_schedule_eh(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81762abd)
Location: drivers/ata/libata-eh.c:971
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:__ata_port_probe
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff81762870-ffffffff8176288b: ata_port_schedule_eh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void ata_port_schedule_eh(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8174291d)
Location: drivers/ata/libata-eh.c:971
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:__ata_port_probe
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff817426d0-ffffffff817426eb: ata_port_schedule_eh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void ata_port_schedule_eh(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8179284d)
Location: drivers/ata/libata-eh.c:971
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:__ata_port_probe
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff81792600-ffffffff8179261b: ata_port_schedule_eh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void ata_port_schedule_eh(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff817ac68d)
Location: drivers/ata/libata-eh.c:971
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_do_link_abort
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
Direct callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:__ata_port_probe
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff817ac440-ffffffff817ac45b: ata_port_schedule_eh (STB_GLOBAL)
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
