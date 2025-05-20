# Function: <code>sd_is_zoned</code>

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
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff816432f3)
Location: drivers/scsi/sd.h:259
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:provisioning_mode_store
```
```
In drivers/scsi/sd_zbc.c (ffffffff81648fe5)
Location: drivers/scsi/sd.h:259
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_report_cmnd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81659738)
Location: drivers/scsi/sd.h:275
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:provisioning_mode_store
```
```
In drivers/scsi/sd_zbc.c (ffffffff8165d935)
Location: drivers/scsi/sd.h:275
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_report_cmnd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff816c4108)
Location: drivers/scsi/sd.h:276
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:provisioning_mode_store
```
```
In drivers/scsi/sd_zbc.c (ffffffff816c6f15)
Location: drivers/scsi/sd.h:276
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_report_cmnd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81700668)
Location: drivers/scsi/sd.h:275
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:provisioning_mode_store
```
```
In drivers/scsi/sd_zbc.c (ffffffff817037a5)
Location: drivers/scsi/sd.h:275
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_report_cmnd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff8172348a)
Location: drivers/scsi/sd.h:265
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:provisioning_mode_store
  - drivers/scsi/sd.c:provisioning_mode_store
```
```
In drivers/scsi/sd_zbc.c (ffffffff81725d15)
Location: drivers/scsi/sd.h:265
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff8175ea6b)
Location: drivers/scsi/sd.h:203
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:provisioning_mode_store
  - drivers/scsi/sd.c:provisioning_mode_store
```
```
In drivers/scsi/sd_zbc.c (ffffffff81761455)
Location: drivers/scsi/sd.h:203
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81782a01)
Location: drivers/scsi/sd.h:203
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:provisioning_mode_store
  - drivers/scsi/sd.c:provisioning_mode_store
```
```
In drivers/scsi/sd_zbc.c (ffffffff81785445)
Location: drivers/scsi/sd.h:203
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81846041)
Location: drivers/scsi/sd.h:209
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:provisioning_mode_store
  - drivers/scsi/sd.c:provisioning_mode_store
```
```
In drivers/scsi/sd_zbc.c (ffffffff818496ea)
Location: drivers/scsi/sd.h:209
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_cmnd_checks
  - drivers/scsi/sd_zbc.c:sd_zbc_cmnd_checks
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff818560ca)
Location: drivers/scsi/sd.h:212
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:provisioning_mode_store
  - drivers/scsi/sd.c:provisioning_mode_store
```
```
In drivers/scsi/sd_zbc.c (ffffffff81859c37)
Location: drivers/scsi/sd.h:212
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_cmnd_checks
  - drivers/scsi/sd_zbc.c:sd_zbc_cmnd_checks
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81838e76)
Location: drivers/scsi/sd.h:212
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:provisioning_mode_store
  - drivers/scsi/sd.c:provisioning_mode_store
```
```
In drivers/scsi/sd_zbc.c (ffffffff8183c946)
Location: drivers/scsi/sd.h:212
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_release_disk
  - drivers/scsi/sd_zbc.c:sd_zbc_release_disk
  - drivers/scsi/sd_zbc.c:sd_zbc_cmnd_checks
  - drivers/scsi/sd_zbc.c:sd_zbc_cmnd_checks
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff818c54d5)
Location: drivers/scsi/sd.h:212
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:provisioning_mode_store
  - drivers/scsi/sd.c:provisioning_mode_store
```
```
In drivers/scsi/sd_zbc.c (ffffffff818c92b6)
Location: drivers/scsi/sd.h:212
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_release_disk
  - drivers/scsi/sd_zbc.c:sd_zbc_release_disk
  - drivers/scsi/sd_zbc.c:sd_zbc_cmnd_checks
  - drivers/scsi/sd_zbc.c:sd_zbc_cmnd_checks
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81a11efd)
Location: drivers/scsi/sd.h:237
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:provisioning_mode_store
```
```
In drivers/scsi/sd_zbc.c (ffffffff81a1685c)
Location: drivers/scsi/sd.h:237
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_cmnd_checks
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81b921ed)
Location: drivers/scsi/sd.h:237
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:provisioning_mode_store
```
```
In drivers/scsi/sd_zbc.c (ffffffff81b97685)
Location: drivers/scsi/sd.h:237
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_cmnd_checks
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81be86fe)
Location: drivers/scsi/sd.h:237
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:provisioning_mode_store
```
```
In drivers/scsi/sd_zbc.c (ffffffff81bedc35)
Location: drivers/scsi/sd.h:237
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_cmnd_checks
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81c3dc5c)
Location: drivers/scsi/sd.h:238
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:provisioning_mode_store
```
```
In drivers/scsi/sd_zbc.c (ffffffff81c43365)
Location: drivers/scsi/sd.h:238
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_cmnd_checks
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffff800010989650)
Location: drivers/scsi/sd.h:203
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:provisioning_mode_store
  - drivers/scsi/sd.c:provisioning_mode_store
```
```
In drivers/scsi/sd_zbc.c (ffff80001098bcd8)
Location: drivers/scsi/sd.h:203
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (c0a5b7c4)
Location: drivers/scsi/sd.h:203
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:provisioning_mode_store
  - drivers/scsi/sd.c:provisioning_mode_store
```
```
In drivers/scsi/sd_zbc.c (c0a5e078)
Location: drivers/scsi/sd.h:203
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (c000000000a49840)
Location: drivers/scsi/sd.h:203
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:provisioning_mode_store
  - drivers/scsi/sd.c:provisioning_mode_store
```
```
In drivers/scsi/sd_zbc.c (c000000000a4caa0)
Location: drivers/scsi/sd.h:203
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffe0005ed910)
Location: drivers/scsi/sd.h:203
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:provisioning_mode_store
  - drivers/scsi/sd.c:provisioning_mode_store
```
```
In drivers/scsi/sd_zbc.c (ffffffe0005f03b8)
Location: drivers/scsi/sd.h:203
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff817370f1)
Location: drivers/scsi/sd.h:203
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:provisioning_mode_store
  - drivers/scsi/sd.c:provisioning_mode_store
```
```
In drivers/scsi/sd_zbc.c (ffffffff81739b35)
Location: drivers/scsi/sd.h:203
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81718d91)
Location: drivers/scsi/sd.h:203
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:provisioning_mode_store
  - drivers/scsi/sd.c:provisioning_mode_store
```
```
In drivers/scsi/sd_zbc.c (ffffffff8171b7d5)
Location: drivers/scsi/sd.h:203
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81777881)
Location: drivers/scsi/sd.h:203
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:provisioning_mode_store
  - drivers/scsi/sd.c:provisioning_mode_store
```
```
In drivers/scsi/sd_zbc.c (ffffffff8177a2c5)
Location: drivers/scsi/sd.h:203
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff817916a1)
Location: drivers/scsi/sd.h:203
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:provisioning_mode_store
  - drivers/scsi/sd.c:provisioning_mode_store
```
```
In drivers/scsi/sd_zbc.c (ffffffff817940f5)
Location: drivers/scsi/sd.h:203
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
</details>
</li>
</ul>

## Differences
