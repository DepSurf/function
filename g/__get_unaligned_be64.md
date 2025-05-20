# Function: <code>__get_unaligned_be64</code>

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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: include/linux/unaligned/be_byteshift.h:17
Inline: True
```
```
In crypto/sha512_generic.c (0)
Location: include/linux/unaligned/be_byteshift.h:17
Inline: True
```
```
In block/partitions/ldm.c (0)
Location: include/linux/unaligned/be_byteshift.h:17
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/unaligned/be_byteshift.h:17
Inline: True
```
```
In drivers/scsi/scsi_trace.c (0)
Location: include/linux/unaligned/be_byteshift.h:17
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/unaligned/be_byteshift.h:17
Inline: True
```
```
In drivers/scsi/sd_zbc.c (0)
Location: include/linux/unaligned/be_byteshift.h:17
Inline: True
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffe000366e70)
Location: include/linux/unaligned/be_byteshift.h:17
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_i_size_init
```
```
In crypto/sha512_generic.c (ffffffe00040bf7e)
Location: include/linux/unaligned/be_byteshift.h:17
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
```
```
In block/partitions/ldm.c (ffffffe00043dd6a)
Location: include/linux/unaligned/be_byteshift.h:17
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In drivers/scsi/scsi_error.c (ffffffe0005dc426)
Location: include/linux/unaligned/be_byteshift.h:17
Inline: True
```
```
In drivers/scsi/scsi_trace.c (ffffffe0005e7ad8)
Location: include/linux/unaligned/be_byteshift.h:17
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffe0005ee374)
Location: include/linux/unaligned/be_byteshift.h:17
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/scsi/sd_zbc.c (ffffffe0005ef786)
Location: include/linux/unaligned/be_byteshift.h:17
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
</details>
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
