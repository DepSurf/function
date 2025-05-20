# Function: <code>ata_port_printk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ata_port_printk(const struct ata_port *ap, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff815c92c0)
Location: drivers/ata/libata-core.c:6812
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_force_cbl
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-sff.c:ata_sff_drain_fifo
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_flush_pio_task
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
```
**Symbols:**

```
ffffffff815c92c0-ffffffff815c933e: ata_port_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ata_port_printk(const struct ata_port *ap, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81621a50)
Location: drivers/ata/libata-core.c:7016
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
  - drivers/ata/libata-core.c:ata_force_cbl
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-sff.c:ata_sff_drain_fifo
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_flush_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
```
**Symbols:**

```
ffffffff81621a50-ffffffff81621ace: ata_port_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ata_port_printk(const struct ata_port *ap, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816525d0)
Location: drivers/ata/libata-core.c:7058
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
  - drivers/ata/libata-core.c:ata_force_cbl
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-sff.c:ata_sff_drain_fifo
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_flush_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
```
**Symbols:**

```
ffffffff816525d0-ffffffff8165264e: ata_port_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ata_port_printk(const struct ata_port *ap, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81666bf0)
Location: drivers/ata/libata-core.c:7144
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
  - drivers/ata/libata-core.c:ata_force_cbl
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_flush_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
```
**Symbols:**

```
ffffffff81666bf0-ffffffff81666c6c: ata_port_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ata_port_printk(const struct ata_port *ap, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816d0250)
Location: drivers/ata/libata-core.c:7174
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
  - drivers/ata/libata-core.c:ata_force_cbl
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_flush_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
```
**Symbols:**

```
ffffffff816d0250-ffffffff816d02cc: ata_port_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ata_port_printk(const struct ata_port *ap, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81712e22)
Location: drivers/ata/libata-core.c:7221
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
  - drivers/ata/libata-core.c:ata_force_cbl
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_flush_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
```
**Symbols:**

```
ffffffff81712e22-ffffffff81712ea0: ata_port_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ata_port_printk(const struct ata_port *ap, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff817352d2)
Location: drivers/ata/libata-core.c:7225
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
  - drivers/ata/libata-core.c:ata_force_cbl
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_flush_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
```
**Symbols:**

```
ffffffff817352d2-ffffffff81735350: ata_port_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ata_port_printk(const struct ata_port *ap, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81770cc1)
Location: drivers/ata/libata-core.c:7210
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
  - drivers/ata/libata-core.c:ata_force_cbl
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_flush_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
```
**Symbols:**

```
ffffffff81770cc1-ffffffff81770d3f: ata_port_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ata_port_printk(const struct ata_port *ap, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81794cbf)
Location: drivers/ata/libata-core.c:7257
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
  - drivers/ata/libata-core.c:ata_force_cbl
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_flush_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
```
**Symbols:**

```
ffffffff81794cbf-ffffffff81794d3d: ata_port_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ata_port_printk(const struct ata_port *ap, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81858f37)
Location: drivers/ata/libata-core.c:6434
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_force_cbl
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-sata.c:ata_qc_complete_multiple
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_flush_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
```
**Symbols:**

```
ffffffff81858f37-ffffffff81858fb5: ata_port_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ata_port_printk(const struct ata_port *ap, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81c16f4a)
Location: drivers/ata/libata-core.c:6434
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_force_cbl
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-sata.c:ata_qc_complete_multiple
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_flush_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
```
**Symbols:**

```
ffffffff81c16f4a-ffffffff81c16fc8: ata_port_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ata_port_printk(const struct ata_port *ap, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81c08c92)
Location: drivers/ata/libata-core.c:6434
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_force_cbl
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-sata.c:ata_qc_complete_multiple
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_flush_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
```
**Symbols:**

```
ffffffff81c08c92-ffffffff81c08d10: ata_port_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ata_port_printk(const struct ata_port *ap, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81d0d53b)
Location: drivers/ata/libata-core.c:6496
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_force_cbl
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-sata.c:ata_qc_complete_multiple
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_flush_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
```
**Symbols:**

```
ffffffff81d0d53b-ffffffff81d0d5b9: ata_port_printk (STB_GLOBAL)
```
</details>
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
void ata_port_printk(const struct ata_port *ap, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffff80001099f6d0)
Location: drivers/ata/libata-core.c:7257
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
  - drivers/ata/libata-core.c:ata_force_cbl
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_flush_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libahci.c:ahci_port_stop
  - drivers/ata/libahci.c:ahci_port_suspend
  - drivers/ata/libahci.c:ahci_read_em_buffer
```
**Symbols:**

```
ffff80001099f6d0-ffff80001099f76c: ata_port_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ata_port_printk(const struct ata_port *ap, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c0a6fbf0)
Location: drivers/ata/libata-core.c:7257
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
  - drivers/ata/libata-core.c:ata_force_cbl
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_flush_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libahci.c:ahci_port_stop
  - drivers/ata/libahci.c:ahci_port_suspend
  - drivers/ata/libahci.c:ahci_read_em_buffer
```
**Symbols:**

```
c0a6fbf0-c0a6fc70: ata_port_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ata_port_printk(const struct ata_port *ap, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c000000000a63cd8)
Location: drivers/ata/libata-core.c:7257
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
  - drivers/ata/libata-core.c:ata_force_cbl
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_flush_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
c000000000a63cd8-c000000000a63d70: ata_port_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ata_port_printk(const struct ata_port *ap, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffe0005ff384)
Location: drivers/ata/libata-core.c:7257
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
  - drivers/ata/libata-core.c:ata_force_cbl
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_flush_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffe0005ff384-ffffffe0005ff3ec: ata_port_printk (STB_GLOBAL)
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
void ata_port_printk(const struct ata_port *ap, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81759dcf)
Location: drivers/ata/libata-core.c:7257
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
  - drivers/ata/libata-core.c:ata_force_cbl
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_flush_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
```
**Symbols:**

```
ffffffff81759dcf-ffffffff81759e4d: ata_port_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ata_port_printk(const struct ata_port *ap, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81739c6f)
Location: drivers/ata/libata-core.c:7257
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
  - drivers/ata/libata-core.c:ata_force_cbl
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_flush_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
```
**Symbols:**

```
ffffffff81739c6f-ffffffff81739ced: ata_port_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ata_port_printk(const struct ata_port *ap, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81789b3f)
Location: drivers/ata/libata-core.c:7257
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
  - drivers/ata/libata-core.c:ata_force_cbl
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_flush_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
```
**Symbols:**

```
ffffffff81789b3f-ffffffff81789bbd: ata_port_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ata_port_printk(const struct ata_port *ap, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff817a398f)
Location: drivers/ata/libata-core.c:7257
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
  - drivers/ata/libata-core.c:ata_force_cbl
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_flush_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
```
**Symbols:**

```
ffffffff817a398f-ffffffff817a3a0d: ata_port_printk (STB_GLOBAL)
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
