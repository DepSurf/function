# Function: <code>memory_read_from_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t memory_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81234290)
Location: fs/libfs.c:655
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/sfi/sfi_acpi.c:sfi_acpi_table_show
  - drivers/sfi/sfi_core.c:sfi_table_show
  - drivers/sfi/sfi_core.c:sfi_table_show
  - drivers/scsi/scsi_sysfs.c:show_inquiry
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg80
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg83
```
**Symbols:**

```
ffffffff81234290-ffffffff812342e3: memory_read_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t memory_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8125c830)
Location: fs/libfs.c:683
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/sfi/sfi_acpi.c:sfi_acpi_table_show
  - drivers/sfi/sfi_core.c:sfi_table_show
  - drivers/sfi/sfi_core.c:sfi_table_show
  - drivers/scsi/scsi_sysfs.c:show_inquiry
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg80
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg83
```
**Symbols:**

```
ffffffff8125c830-ffffffff8125c883: memory_read_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t memory_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8126fd80)
Location: fs/libfs.c:691
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/sfi/sfi_acpi.c:sfi_acpi_table_show
  - drivers/sfi/sfi_core.c:sfi_table_show
  - drivers/sfi/sfi_core.c:sfi_table_show
  - drivers/scsi/scsi_sysfs.c:show_inquiry
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg80
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg83
```
**Symbols:**

```
ffffffff8126fd80-ffffffff8126fdd3: memory_read_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t memory_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8127d560)
Location: fs/libfs.c:692
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/sfi/sfi_acpi.c:sfi_acpi_table_show
  - drivers/sfi/sfi_core.c:sfi_table_show
  - drivers/sfi/sfi_core.c:sfi_table_show
  - drivers/scsi/scsi_sysfs.c:show_inquiry
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg80
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg83
```
**Symbols:**

```
ffffffff8127d560-ffffffff8127d5b3: memory_read_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t memory_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812a0000)
Location: fs/libfs.c:692
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_data_show
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/sfi/sfi_acpi.c:sfi_acpi_table_show
  - drivers/sfi/sfi_core.c:sfi_table_show
  - drivers/sfi/sfi_core.c:sfi_table_show
  - drivers/scsi/scsi_sysfs.c:show_inquiry
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg80
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg83
```
**Symbols:**

```
ffffffff812a0000-ffffffff812a0053: memory_read_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t memory_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812c67b0)
Location: fs/libfs.c:692
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_data_show
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/sfi/sfi_acpi.c:sfi_acpi_table_show
  - drivers/sfi/sfi_core.c:sfi_table_show
  - drivers/sfi/sfi_core.c:sfi_table_show
  - drivers/scsi/scsi_sysfs.c:show_inquiry
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg80
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg83
```
**Symbols:**

```
ffffffff812c67b0-ffffffff812c6803: memory_read_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t memory_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812db9b0)
Location: fs/libfs.c:692
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_data_show
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/sfi/sfi_acpi.c:sfi_acpi_table_show
  - drivers/sfi/sfi_core.c:sfi_table_show
  - drivers/sfi/sfi_core.c:sfi_table_show
  - drivers/scsi/scsi_sysfs.c:show_inquiry
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg80
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg83
```
**Symbols:**

```
ffffffff812db9b0-ffffffff812dba03: memory_read_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t memory_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812fa040)
Location: fs/libfs.c:711
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_data_show
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/sfi/sfi_acpi.c:sfi_acpi_table_show
  - drivers/sfi/sfi_core.c:sfi_table_show
  - drivers/sfi/sfi_core.c:sfi_table_show
  - drivers/scsi/scsi_sysfs.c:show_inquiry
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg80
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg83
```
**Symbols:**

```
ffffffff812fa040-ffffffff812fa093: memory_read_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t memory_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8130bd00)
Location: fs/libfs.c:716
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/sfi/sfi_acpi.c:sfi_acpi_table_show
  - drivers/sfi/sfi_core.c:sfi_table_show
  - drivers/sfi/sfi_core.c:sfi_table_show
  - drivers/base/devcoredump.c:devcd_readv
  - drivers/scsi/scsi_sysfs.c:show_inquiry
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg80
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg83
```
**Symbols:**

```
ffffffff8130bd00-ffffffff8130bd53: memory_read_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t memory_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff813453c0)
Location: fs/libfs.c:785
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_data_show
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/sfi/sfi_acpi.c:sfi_acpi_table_show
  - drivers/sfi/sfi_core.c:sfi_table_show
  - drivers/sfi/sfi_core.c:sfi_table_show
  - drivers/base/devcoredump.c:devcd_readv
  - drivers/scsi/scsi_sysfs.c:show_inquiry
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg0
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg89
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg80
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg83
  - drivers/leds/led-triggers.c:led_trigger_read
```
**Symbols:**

```
ffffffff813453c0-ffffffff81345413: memory_read_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t memory_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81351710)
Location: fs/libfs.c:787
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_data_show
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/sfi/sfi_acpi.c:sfi_acpi_table_show
  - drivers/sfi/sfi_core.c:sfi_table_show
  - drivers/sfi/sfi_core.c:sfi_table_show
  - drivers/base/devcoredump.c:devcd_readv
  - drivers/scsi/scsi_sysfs.c:show_inquiry
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg0
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg89
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg80
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg83
  - drivers/leds/led-triggers.c:led_trigger_read
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_read
```
**Symbols:**

```
ffffffff81351710-ffffffff81351763: memory_read_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t memory_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81358430)
Location: fs/libfs.c:790
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_data_show
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/base/devcoredump.c:devcd_readv
  - drivers/scsi/scsi_sysfs.c:show_inquiry
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg0
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg89
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg80
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg83
  - drivers/leds/led-triggers.c:led_trigger_read
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_read
```
**Symbols:**

```
ffffffff81358430-ffffffff81358483: memory_read_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t memory_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff813a6940)
Location: fs/libfs.c:799
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_print_to_buf
  - drivers/acpi/sysfs.c:acpi_data_show
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/base/devcoredump.c:devcd_readv
  - drivers/scsi/scsi_sysfs.c:show_inquiry
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg0
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg89
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg80
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg83
  - drivers/leds/led-triggers.c:led_trigger_read
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_read
```
**Symbols:**

```
ffffffff813a6940-ffffffff813a6993: memory_read_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t memory_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8142b320)
Location: fs/libfs.c:826
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_print_to_buf
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/base/devcoredump.c:devcd_readv
  - drivers/scsi/scsi_sysfs.c:show_inquiry
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg0
  - drivers/scsi/scsi_sysfs.c:show_vpd_pgb2
  - drivers/scsi/scsi_sysfs.c:show_vpd_pgb1
  - drivers/scsi/scsi_sysfs.c:show_vpd_pgb0
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg89
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg80
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg83
  - drivers/leds/led-triggers.c:led_trigger_read
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_read
```
**Symbols:**

```
ffffffff8142b320-ffffffff8142b382: memory_read_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t memory_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff814b8d80)
Location: fs/libfs.c:827
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_print_to_buf
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/base/devcoredump.c:devcd_readv
  - drivers/scsi/scsi_sysfs.c:show_inquiry
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg0
  - drivers/scsi/scsi_sysfs.c:show_vpd_pgb2
  - drivers/scsi/scsi_sysfs.c:show_vpd_pgb1
  - drivers/scsi/scsi_sysfs.c:show_vpd_pgb0
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg89
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg80
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg83
  - drivers/leds/led-triggers.c:led_trigger_read
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_read
```
**Symbols:**

```
ffffffff814b8d80-ffffffff814b8de2: memory_read_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t memory_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff814ee060)
Location: fs/libfs.c:822
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_print_to_buf
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/base/devcoredump.c:devcd_readv
  - drivers/scsi/scsi_sysfs.c:show_inquiry
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg0
  - drivers/scsi/scsi_sysfs.c:show_vpd_pgb2
  - drivers/scsi/scsi_sysfs.c:show_vpd_pgb1
  - drivers/scsi/scsi_sysfs.c:show_vpd_pgb0
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg89
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg80
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg83
  - drivers/leds/led-triggers.c:led_trigger_read
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_read
```
**Symbols:**

```
ffffffff814ee060-ffffffff814ee0c2: memory_read_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t memory_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81521d10)
Location: fs/libfs.c:1092
Inline: False
Direct callers:
  - lib/bitmap-str.c:bitmap_print_to_buf
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/base/devcoredump.c:devcd_readv
  - drivers/scsi/scsi_sysfs.c:show_inquiry
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg0
  - drivers/scsi/scsi_sysfs.c:show_vpd_pgb2
  - drivers/scsi/scsi_sysfs.c:show_vpd_pgb1
  - drivers/scsi/scsi_sysfs.c:show_vpd_pgb0
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg89
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg80
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg83
  - drivers/leds/led-triggers.c:led_trigger_read
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_read
```
**Symbols:**

```
ffffffff81521d10-ffffffff81521d72: memory_read_from_buffer (STB_GLOBAL)
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
ssize_t memory_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffff8000103c02e8)
Location: fs/libfs.c:716
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/base/devcoredump.c:devcd_readv
  - drivers/scsi/scsi_sysfs.c:show_inquiry
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg80
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg83
  - drivers/of/kobj.c:of_node_property_read
```
**Symbols:**

```
ffff8000103c02e8-ffff8000103c0370: memory_read_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t memory_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (c059d70c)
Location: fs/libfs.c:716
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:devcd_readv
  - drivers/scsi/scsi_sysfs.c:show_inquiry
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg80
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg83
  - drivers/of/kobj.c:of_node_property_read
```
**Symbols:**

```
c059d70c-c059d7a4: memory_read_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t memory_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (c0000000004bf880)
Location: fs/libfs.c:716
Inline: False
Direct callers:
  - arch/powerpc/kernel/secvar-sysfs.c:data_read
  - arch/powerpc/platforms/powernv/opal.c:export_attr_read
  - arch/powerpc/platforms/powernv/opal.c:symbol_map_read
  - arch/powerpc/platforms/powernv/opal-msglog.c:memcons_copy
  - arch/powerpc/platforms/powernv/opal-msglog.c:memcons_copy
  - drivers/base/devcoredump.c:devcd_readv
  - drivers/scsi/scsi_sysfs.c:show_inquiry
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg80
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg83
  - drivers/of/kobj.c:of_node_property_read
```
**Symbols:**

```
c0000000004bf880-c0000000004bf920: memory_read_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t memory_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffe000280b0c)
Location: fs/libfs.c:716
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:devcd_readv
  - drivers/scsi/scsi_sysfs.c:show_inquiry
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg80
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg83
  - drivers/of/kobj.c:of_node_property_read
```
**Symbols:**

```
ffffffe000280b0c-ffffffe000280b7e: memory_read_from_buffer (STB_GLOBAL)
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
ssize_t memory_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff813042e0)
Location: fs/libfs.c:716
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/sfi/sfi_acpi.c:sfi_acpi_table_show
  - drivers/sfi/sfi_core.c:sfi_table_show
  - drivers/sfi/sfi_core.c:sfi_table_show
  - drivers/base/devcoredump.c:devcd_readv
  - drivers/scsi/scsi_sysfs.c:show_inquiry
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg80
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg83
```
**Symbols:**

```
ffffffff813042e0-ffffffff81304333: memory_read_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t memory_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812f4f00)
Location: fs/libfs.c:716
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/sfi/sfi_acpi.c:sfi_acpi_table_show
  - drivers/sfi/sfi_core.c:sfi_table_show
  - drivers/sfi/sfi_core.c:sfi_table_show
  - drivers/scsi/scsi_sysfs.c:show_inquiry
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg80
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg83
```
**Symbols:**

```
ffffffff812f4f00-ffffffff812f4f53: memory_read_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t memory_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff813020d0)
Location: fs/libfs.c:716
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/sfi/sfi_acpi.c:sfi_acpi_table_show
  - drivers/sfi/sfi_core.c:sfi_table_show
  - drivers/sfi/sfi_core.c:sfi_table_show
  - drivers/base/devcoredump.c:devcd_readv
  - drivers/scsi/scsi_sysfs.c:show_inquiry
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg80
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg83
```
**Symbols:**

```
ffffffff813020d0-ffffffff81302123: memory_read_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t memory_read_from_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff813136f0)
Location: fs/libfs.c:716
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_table_show
  - drivers/sfi/sfi_acpi.c:sfi_acpi_table_show
  - drivers/sfi/sfi_core.c:sfi_table_show
  - drivers/sfi/sfi_core.c:sfi_table_show
  - drivers/base/devcoredump.c:devcd_readv
  - drivers/scsi/scsi_sysfs.c:show_inquiry
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg80
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg83
```
**Symbols:**

```
ffffffff813136f0-ffffffff81313743: memory_read_from_buffer (STB_GLOBAL)
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
