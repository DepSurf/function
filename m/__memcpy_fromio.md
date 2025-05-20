# Function: <code>__memcpy_fromio</code>

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
void __memcpy_fromio(void *to, const volatile void *from, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/io.c (ffff800010095d00)
Location: arch/arm64/kernel/io.c:15
Inline: False
Direct callers:
  - fs/libfs.c:memory_read_from_io_buffer
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/video/fbdev/core/fbmem.c:fb_read
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/misc/sram.c:sram_read
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/ti_sci.c:ti_sci_debug_show
  - drivers/firmware/arm_scmi/driver.c:scmi_fetch_response
  - drivers/mailbox/zynqmp-ipi-mailbox.c:zynqmp_ipi_interrupt
```
**Symbols:**

```
ffff800010095d00-ffff800010095db4: __memcpy_fromio (STB_GLOBAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
