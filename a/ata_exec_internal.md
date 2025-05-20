# Function: <code>ata_exec_internal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
unsigned int ata_exec_internal(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, void *buf, unsigned int buflen, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff815cbc90)
Location: drivers/ata/libata-core.c:1736
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_do_set_mode
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:atapi_eh_tur
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-zpodd.c:zpodd_post_poweron
  - drivers/ata/libata-zpodd.c:zpodd_init
```
**Symbols:**

```
ffffffff815cbc90-ffffffff815cbd45: ata_exec_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int ata_exec_internal(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, void *buf, unsigned int buflen, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816245c6)
Location: drivers/ata/libata-core.c:1739
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/ata/libata-zpodd.c:zpodd_post_poweron
```
**Symbols:**

```
ffffffff81624460-ffffffff81624515: ata_exec_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
unsigned int ata_exec_internal(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, void *buf, unsigned int buflen, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81655166)
Location: drivers/ata/libata-core.c:1748
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/ata/libata-zpodd.c:zpodd_post_poweron
```
**Symbols:**

```
ffffffff81655000-ffffffff816550b5: ata_exec_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
unsigned int ata_exec_internal(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, void *buf, unsigned int buflen, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81669c22)
Location: drivers/ata/libata-core.c:1748
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/ata/libata-zpodd.c:zpodd_post_poweron
```
**Symbols:**

```
ffffffff816695c0-ffffffff8166964f: ata_exec_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int ata_exec_internal(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, void *buf, unsigned int buflen, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816d3272)
Location: drivers/ata/libata-core.c:1748
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/ata/libata-zpodd.c:zpodd_post_poweron
```
**Symbols:**

```
ffffffff816d2c10-ffffffff816d2c9f: ata_exec_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
unsigned int ata_exec_internal(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, void *buf, unsigned int buflen, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8170f686)
Location: drivers/ata/libata-core.c:1739
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/ata/libata-zpodd.c:zpodd_post_poweron
```
**Symbols:**

```
ffffffff8170f260-ffffffff8170f2f1: ata_exec_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
unsigned int ata_exec_internal(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, void *buf, unsigned int buflen, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81731b36)
Location: drivers/ata/libata-core.c:1739
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/ata/libata-zpodd.c:zpodd_post_poweron
```
**Symbols:**

```
ffffffff81731710-ffffffff817317a1: ata_exec_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int ata_exec_internal(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, void *buf, unsigned int buflen, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8176d65a)
Location: drivers/ata/libata-core.c:1723
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/ata/libata-zpodd.c:zpodd_post_poweron
```
**Symbols:**

```
ffffffff817710fa-ffffffff8177111d: ata_exec_internal.cold (STB_LOCAL)
ffffffff8176ced0-ffffffff8176cf65: ata_exec_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
unsigned int ata_exec_internal(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, void *buf, unsigned int buflen, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff817916ca)
Location: drivers/ata/libata-core.c:1723
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/ata/libata-zpodd.c:zpodd_post_poweron
```
**Symbols:**

```
ffffffff81790f40-ffffffff81790fd5: ata_exec_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int ata_exec_internal(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, void *buf, unsigned int buflen, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81855ed6)
Location: drivers/ata/libata-core.c:1667
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
  - drivers/ata/libata-pmp.c:sata_pmp_write
  - drivers/ata/libata-pmp.c:sata_pmp_read
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-zpodd.c:zpodd_post_poweron
  - drivers/ata/libata-zpodd.c:zpodd_get_mech_type
```
**Symbols:**

```
ffffffff81855a70-ffffffff81855b05: ata_exec_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
unsigned int ata_exec_internal(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, void *buf, unsigned int buflen, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81866156)
Location: drivers/ata/libata-core.c:1667
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
  - drivers/ata/libata-pmp.c:sata_pmp_write
  - drivers/ata/libata-pmp.c:sata_pmp_read
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-zpodd.c:zpodd_post_poweron
  - drivers/ata/libata-zpodd.c:zpodd_get_mech_type
```
**Symbols:**

```
ffffffff81865ce0-ffffffff81865d75: ata_exec_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
unsigned int ata_exec_internal(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, void *buf, unsigned int buflen, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81848896)
Location: drivers/ata/libata-core.c:1667
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
  - drivers/ata/libata-pmp.c:sata_pmp_write
  - drivers/ata/libata-pmp.c:sata_pmp_read
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/ata/libata-zpodd.c:zpodd_post_poweron
```
**Symbols:**

```
ffffffff81848780-ffffffff81848815: ata_exec_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int ata_exec_internal(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, void *buf, unsigned int buflen, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff818d58e6)
Location: drivers/ata/libata-core.c:1670
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_hpa_resize
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
  - drivers/ata/libata-pmp.c:sata_pmp_write
  - drivers/ata/libata-pmp.c:sata_pmp_read
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/ata/libata-zpodd.c:zpodd_post_poweron
```
**Symbols:**

```
ffffffff818d57d0-ffffffff818d5865: ata_exec_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
unsigned int ata_exec_internal(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, void *buf, unsigned int buflen, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81a262ba)
Location: drivers/ata/libata-core.c:1645
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_read_log_page
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_set_max_sectors
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:ata_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
  - drivers/ata/libata-pmp.c:sata_pmp_write
  - drivers/ata/libata-pmp.c:sata_pmp_read
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/ata/libata-zpodd.c:zpodd_post_poweron
```
**Symbols:**

```
ffffffff81a25fc0-ffffffff81a26083: ata_exec_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
unsigned int ata_exec_internal(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, void *buf, unsigned int buflen, unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81ba84ca)
Location: drivers/ata/libata-core.c:1645
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_read_log_page
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_set_max_sectors
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:ata_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
  - drivers/ata/libata-pmp.c:sata_pmp_write
  - drivers/ata/libata-pmp.c:sata_pmp_read
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/ata/libata-zpodd.c:zpodd_post_poweron
```
**Symbols:**

```
ffffffff81ba8160-ffffffff81ba8224: ata_exec_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
unsigned int ata_exec_internal(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, void *buf, unsigned int buflen, unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81bff16a)
Location: drivers/ata/libata-core.c:1679
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_read_log_page
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_set_max_sectors
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:ata_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
  - drivers/ata/libata-pmp.c:sata_pmp_write
  - drivers/ata/libata-pmp.c:sata_pmp_read
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/ata/libata-zpodd.c:zpodd_post_poweron
```
**Symbols:**

```
ffffffff81bfee00-ffffffff81bfeec4: ata_exec_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int ata_exec_internal(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, void *buf, unsigned int buflen, unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81c551ba)
Location: drivers/ata/libata-core.c:1674
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_read_log_page
  - drivers/ata/libata-core.c:ata_dev_power_set_active
  - drivers/ata/libata-core.c:ata_dev_power_set_standby
  - drivers/ata/libata-core.c:ata_dev_power_is_active
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_hpa_resize
  - drivers/ata/libata-core.c:ata_set_max_sectors
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:ata_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
  - drivers/ata/libata-pmp.c:sata_pmp_write
  - drivers/ata/libata-pmp.c:sata_pmp_read
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/ata/libata-zpodd.c:zpodd_post_poweron
```
**Symbols:**

```
ffffffff81c54aa0-ffffffff81c54b64: ata_exec_internal (STB_GLOBAL)
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
unsigned int ata_exec_internal(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, void *buf, unsigned int buflen, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffff80001099b5a4)
Location: drivers/ata/libata-core.c:1723
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/ata/libata-zpodd.c:zpodd_post_poweron
```
**Symbols:**

```
ffff80001099ac00-ffff80001099accc: ata_exec_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
unsigned int ata_exec_internal(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, void *buf, unsigned int buflen, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c0a6b3a0)
Location: drivers/ata/libata-core.c:1723
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_read_id
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
  - drivers/ata/libata-pmp.c:sata_pmp_write
  - drivers/ata/libata-pmp.c:sata_pmp_read
```
**Symbols:**

```
c0a6ae3c-c0a6af14: ata_exec_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
unsigned int ata_exec_internal(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, void *buf, unsigned int buflen, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c000000000a5ed1c)
Location: drivers/ata/libata-core.c:1723
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
  - drivers/ata/libata-pmp.c:sata_pmp_write
  - drivers/ata/libata-pmp.c:sata_pmp_read
```
**Symbols:**

```
c000000000a5e1f0-c000000000a5e2c4: ata_exec_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
unsigned int ata_exec_internal(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, void *buf, unsigned int buflen, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffe0005fbb0a)
Location: drivers/ata/libata-core.c:1723
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
  - drivers/ata/libata-pmp.c:sata_pmp_write
  - drivers/ata/libata-pmp.c:sata_pmp_read
```
**Symbols:**

```
ffffffe0005fb3c6-ffffffe0005fb448: ata_exec_internal (STB_GLOBAL)
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
unsigned int ata_exec_internal(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, void *buf, unsigned int buflen, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8175680a)
Location: drivers/ata/libata-core.c:1723
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
```
**Symbols:**

```
ffffffff81756080-ffffffff81756115: ata_exec_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
unsigned int ata_exec_internal(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, void *buf, unsigned int buflen, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff817366aa)
Location: drivers/ata/libata-core.c:1723
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
```
**Symbols:**

```
ffffffff81735f20-ffffffff81735fb5: ata_exec_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
unsigned int ata_exec_internal(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, void *buf, unsigned int buflen, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8178654a)
Location: drivers/ata/libata-core.c:1723
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/ata/libata-zpodd.c:zpodd_post_poweron
```
**Symbols:**

```
ffffffff81785dc0-ffffffff81785e55: ata_exec_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
unsigned int ata_exec_internal(struct ata_device *dev, struct ata_taskfile *tf, const u8 *cdb, int dma_dir, void *buf, unsigned int buflen, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff817a039a)
Location: drivers/ata/libata-core.c:1723
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_set_feature
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_set_max_sectors
  - drivers/ata/libata-core.c:ata_read_native_max_address
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_park_issue_cmd
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:atapi_eh_request_sense
  - drivers/ata/libata-eh.c:atapi_eh_tur
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/ata/libata-zpodd.c:zpodd_post_poweron
```
**Symbols:**

```
ffffffff8179fc10-ffffffff8179fca5: ata_exec_internal (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long unsigned int timeout</code> ➡️ <code>unsigned int timeout</code>
</li>
</ul>
</details>
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
