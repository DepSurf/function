# Function: <code>__swab64p</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81306755)
Location: include/uapi/linux/swab.h:180
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_i_size_init
```
```
In crypto/sha512_generic.c (ffffffff813a86d6)
Location: include/uapi/linux/swab.h:180
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
```
```
In block/partitions/ldm.c (ffffffff813d0601)
Location: include/uapi/linux/swab.h:180
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
```
```
In lib/digsig.c (ffffffff81419749)
Location: include/uapi/linux/swab.h:180
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/scsi/sd.c (ffffffff815bd751)
Location: include/uapi/linux/swab.h:180
Inline: True
Inline callers:
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:sd_revalidate_disk
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8133ac88)
Location: include/uapi/linux/swab.h:186
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In crypto/sha512_generic.c (ffffffff813e5bb8)
Location: include/uapi/linux/swab.h:186
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
```
```
In block/partitions/ldm.c (ffffffff81416978)
Location: include/uapi/linux/swab.h:186
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
```
```
In lib/digsig.c (ffffffff814614b5)
Location: include/uapi/linux/swab.h:186
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/scsi/scsi_trace.c (ffffffff816100fe)
Location: include/uapi/linux/swab.h:186
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff81617839)
Location: include/uapi/linux/swab.h:186
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:read_capacity_16
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81350a18)
Location: include/uapi/linux/swab.h:186
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In crypto/sha512_generic.c (ffffffff813febd8)
Location: include/uapi/linux/swab.h:186
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
```
```
In block/partitions/ldm.c (ffffffff81431ea8)
Location: include/uapi/linux/swab.h:186
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
```
```
In lib/digsig.c (ffffffff8147ffd5)
Location: include/uapi/linux/swab.h:186
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/scsi/scsi_trace.c (ffffffff8163f98e)
Location: include/uapi/linux/swab.h:186
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff81647303)
Location: include/uapi/linux/swab.h:186
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:read_capacity_16
```
```
In drivers/scsi/sd_zbc.c (ffffffff81648a84)
Location: include/uapi/linux/swab.h:186
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
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
In fs/ecryptfs/crypto.c (ffffffff81365528)
Location: include/uapi/linux/swab.h:186
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In crypto/sha512_generic.c (ffffffff8140bef1)
Location: include/uapi/linux/swab.h:186
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
```
```
In block/partitions/ldm.c (ffffffff8143ee4b)
Location: include/uapi/linux/swab.h:186
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
```
```
In lib/digsig.c (ffffffff81489274)
Location: include/uapi/linux/swab.h:186
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/scsi/scsi_error.c (ffffffff81647af4)
Location: include/uapi/linux/swab.h:186
Inline: True
```
```
In drivers/scsi/scsi_trace.c (ffffffff81654484)
Location: include/uapi/linux/swab.h:186
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff8165bf13)
Location: include/uapi/linux/swab.h:186
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/scsi/sd_zbc.c (ffffffff8165d3d4)
Location: include/uapi/linux/swab.h:186
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
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
In fs/ecryptfs/crypto.c (ffffffff8138a1f8)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In crypto/sha512_generic.c (ffffffff81434911)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
```
```
In block/partitions/ldm.c (ffffffff8146b240)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
```
```
In lib/digsig.c (ffffffff814c53b4)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/scsi/scsi_error.c (ffffffff816b0b64)
Location: include/uapi/linux/swab.h:187
Inline: True
```
```
In drivers/scsi/scsi_trace.c (ffffffff816bd9ca)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff816c5590)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/scsi/sd_zbc.c (ffffffff816c6cf2)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
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
In fs/ecryptfs/crypto.c (ffffffff813b8fcb)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In crypto/sha512_generic.c (ffffffff81467499)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
```
```
In block/partitions/ldm.c (ffffffff8149ec32)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
```
```
In lib/digsig.c (ffffffff814f62a0)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/scsi/scsi_error.c (ffffffff816eceaa)
Location: include/uapi/linux/swab.h:187
Inline: True
```
```
In drivers/scsi/scsi_trace.c (ffffffff816f9eec)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff81701c18)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/scsi/sd_zbc.c (ffffffff817030b9)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
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
In fs/ecryptfs/crypto.c (ffffffff813d253b)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In crypto/sha512_generic.c (ffffffff81485109)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
```
```
In block/partitions/ldm.c (ffffffff814b8fda)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
```
```
In lib/digsig.c (ffffffff8150a6a0)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/scsi/scsi_error.c (ffffffff817109ea)
Location: include/uapi/linux/swab.h:187
Inline: True
```
```
In drivers/scsi/scsi_trace.c (ffffffff8171c72f)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff81724bcf)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/scsi/sd_zbc.c (ffffffff817258a3)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
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
In fs/ecryptfs/crypto.c (ffffffff813fcfd9)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In crypto/sha512_generic.c (ffffffff814b3319)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
```
```
In block/partitions/ldm.c (ffffffff814e6de6)
Location: include/uapi/linux/swab.h:187
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
In lib/digsig.c (ffffffff815391f2)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/scsi/scsi_error.c (ffffffff8174c0e4)
Location: include/uapi/linux/swab.h:187
Inline: True
```
```
In drivers/scsi/scsi_trace.c (ffffffff8175802d)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff8175f87b)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/scsi/sd_zbc.c (ffffffff81760f55)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
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
In fs/ecryptfs/crypto.c (ffffffff81416eb9)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In crypto/sha512_generic.c (ffffffff814cc089)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
```
```
In block/partitions/ldm.c (ffffffff815001b6)
Location: include/uapi/linux/swab.h:187
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
In lib/digsig.c (ffffffff8155a012)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/scsi/scsi_error.c (ffffffff81770264)
Location: include/uapi/linux/swab.h:187
Inline: True
```
```
In drivers/scsi/scsi_trace.c (ffffffff8177c04f)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff817837ac)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/scsi/sd_zbc.c (ffffffff81784f15)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
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
In fs/ecryptfs/crypto.c (ffffffff8146540f)
Location: include/uapi/linux/swab.h:197
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In crypto/sha512_generic.c (ffffffff8152b528)
Location: include/uapi/linux/swab.h:197
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
```
```
In block/partitions/ldm.c (ffffffff81560487)
Location: include/uapi/linux/swab.h:197
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_tocblock
  - block/partitions/ldm.c:ldm_parse_tocblock
  - block/partitions/ldm.c:ldm_parse_tocblock
  - block/partitions/ldm.c:ldm_parse_tocblock
  - block/partitions/ldm.c:ldm_parse_tocblock
  - block/partitions/ldm.c:ldm_parse_privhead
  - block/partitions/ldm.c:ldm_parse_privhead
  - block/partitions/ldm.c:ldm_parse_privhead
  - block/partitions/ldm.c:ldm_parse_privhead
  - block/partitions/ldm.c:ldm_parse_privhead
```
```
In lib/digsig.c (ffffffff815e3942)
Location: include/uapi/linux/swab.h:197
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/base/regmap/regmap.c (ffffffff817da3f5)
Location: include/uapi/linux/swab.h:197
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_64_be_inplace
  - drivers/base/regmap/regmap.c:regmap_parse_64_be
```
```
In drivers/scsi/scsi_error.c (ffffffff81830f47)
Location: include/uapi/linux/swab.h:197
Inline: True
```
```
In drivers/scsi/scsi_trace.c (ffffffff8183f669)
Location: include/uapi/linux/swab.h:197
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff81845e8d)
Location: include/uapi/linux/swab.h:197
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_block_limits
```
```
In drivers/scsi/sd_zbc.c (ffffffff81848782)
Location: include/uapi/linux/swab.h:197
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_check_capacity
  - drivers/scsi/sd_zbc.c:sd_zbc_check_capacity
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
```
```
In net/mptcp/subflow.c (ffffffff81bae4b0)
Location: include/uapi/linux/swab.h:197
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_finish_connect
```
```
In net/mptcp/options.c (ffffffff81bb1654)
Location: include/uapi/linux/swab.h:197
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_established_options_addr
  - net/mptcp/options.c:mptcp_parse_option
  - net/mptcp/options.c:mptcp_parse_option
  - net/mptcp/options.c:mptcp_parse_option
  - net/mptcp/options.c:mptcp_parse_option
  - net/mptcp/options.c:mptcp_parse_option
  - net/mptcp/options.c:mptcp_parse_option
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
In fs/ecryptfs/crypto.c (ffffffff81480caf)
Location: include/uapi/linux/swab.h:197
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In crypto/sha512_generic.c (ffffffff815484f8)
Location: include/uapi/linux/swab.h:197
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
```
```
In block/partitions/ldm.c (ffffffff8157bf77)
Location: include/uapi/linux/swab.h:197
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_tocblock
  - block/partitions/ldm.c:ldm_parse_tocblock
  - block/partitions/ldm.c:ldm_parse_tocblock
  - block/partitions/ldm.c:ldm_parse_tocblock
  - block/partitions/ldm.c:ldm_parse_tocblock
  - block/partitions/ldm.c:ldm_parse_privhead
  - block/partitions/ldm.c:ldm_parse_privhead
  - block/partitions/ldm.c:ldm_parse_privhead
  - block/partitions/ldm.c:ldm_parse_privhead
  - block/partitions/ldm.c:ldm_parse_privhead
```
```
In lib/digsig.c (ffffffff81607dd2)
Location: include/uapi/linux/swab.h:197
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/base/regmap/regmap.c (ffffffff817ef1a5)
Location: include/uapi/linux/swab.h:197
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_64_be_inplace
  - drivers/base/regmap/regmap.c:regmap_parse_64_be
```
```
In drivers/scsi/scsi_error.c (ffffffff81841b87)
Location: include/uapi/linux/swab.h:197
Inline: True
```
```
In drivers/scsi/scsi_trace.c (ffffffff8184fcc9)
Location: include/uapi/linux/swab.h:197
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff81855f0a)
Location: include/uapi/linux/swab.h:197
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_block_limits
```
```
In drivers/scsi/sd_zbc.c (ffffffff81858c69)
Location: include/uapi/linux/swab.h:197
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_check_capacity
  - drivers/scsi/sd_zbc.c:sd_zbc_check_capacity
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
```
```
In net/mptcp/subflow.c (ffffffff81bc2ddd)
Location: include/uapi/linux/swab.h:197
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_finish_connect
```
```
In net/mptcp/options.c (ffffffff81bc5598)
Location: include/uapi/linux/swab.h:197
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_established_options_add_addr
  - net/mptcp/options.c:mptcp_parse_option
  - net/mptcp/options.c:mptcp_parse_option
  - net/mptcp/options.c:mptcp_parse_option
  - net/mptcp/options.c:mptcp_parse_option
  - net/mptcp/options.c:mptcp_parse_option
  - net/mptcp/options.c:mptcp_parse_option
  - net/mptcp/options.c:mptcp_parse_option
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
In fs/ecryptfs/crypto.c (ffffffff8148659f)
Location: include/uapi/linux/swab.h:197
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In crypto/sha512_generic.c (ffffffff81550bbd)
Location: include/uapi/linux/swab.h:197
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
```
```
In block/partitions/ldm.c (ffffffff81583a59)
Location: include/uapi/linux/swab.h:197
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_parse_tocblock
  - block/partitions/ldm.c:ldm_parse_tocblock
  - block/partitions/ldm.c:ldm_parse_tocblock
  - block/partitions/ldm.c:ldm_parse_tocblock
  - block/partitions/ldm.c:ldm_parse_tocblock
```
```
In lib/digsig.c (ffffffff815eaae2)
Location: include/uapi/linux/swab.h:197
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/base/regmap/regmap.c (ffffffff817d3a45)
Location: include/uapi/linux/swab.h:197
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_64_be_inplace
  - drivers/base/regmap/regmap.c:regmap_parse_64_be
```
```
In drivers/scsi/scsi_error.c (ffffffff81824b83)
Location: include/uapi/linux/swab.h:197
Inline: True
```
```
In drivers/scsi/scsi_trace.c (ffffffff81832ce3)
Location: include/uapi/linux/swab.h:197
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff81838cba)
Location: include/uapi/linux/swab.h:197
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_block_limits
```
```
In drivers/scsi/sd_zbc.c (ffffffff8183ca95)
Location: include/uapi/linux/swab.h:197
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
```
```
In net/mptcp/subflow.c (ffffffff81bb32ae)
Location: include/uapi/linux/swab.h:197
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_check_req
```
```
In net/mptcp/options.c (ffffffff81bb49cb)
Location: include/uapi/linux/swab.h:197
Inline: True
Inline callers:
  - net/mptcp/options.c:add_addr_generate_hmac
  - net/mptcp/options.c:mptcp_parse_option
  - net/mptcp/options.c:mptcp_parse_option
  - net/mptcp/options.c:mptcp_parse_option
  - net/mptcp/options.c:mptcp_parse_option
  - net/mptcp/options.c:mptcp_parse_option
  - net/mptcp/options.c:mptcp_parse_option
  - net/mptcp/options.c:mptcp_parse_option
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/digsig.c (ffffffff81656fe2)
Location: include/uapi/linux/swab.h:197
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/digsig.c (ffffffff8176e820)
Location: include/uapi/linux/swab.h:197
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
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
In lib/digsig.c (ffffffff8189e110)
Location: include/uapi/linux/swab.h:197
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81b256f3)
Location: include/uapi/linux/swab.h:197
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_noinc_read
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
In lib/digsig.c (ffffffff818e06d0)
Location: include/uapi/linux/swab.h:197
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81b757e6)
Location: include/uapi/linux/swab.h:197
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_noinc_read
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/digsig.c (ffffffff81927210)
Location: include/uapi/linux/swab.h:197
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
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
In fs/ecryptfs/crypto.c (0)
Location: include/uapi/linux/swab.h:187
Inline: True
```
```
In crypto/sha512_generic.c (0)
Location: include/uapi/linux/swab.h:187
Inline: True
```
```
In block/partitions/ldm.c (0)
Location: include/uapi/linux/swab.h:187
Inline: True
```
```
In lib/digsig.c (0)
Location: include/uapi/linux/swab.h:187
Inline: True
```
```
In drivers/char/tpm/eventlog/of.c (ffff8000108c05fc)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/of.c:tpm_read_log_of
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/uapi/linux/swab.h:187
Inline: True
```
```
In drivers/scsi/scsi_trace.c (0)
Location: include/uapi/linux/swab.h:187
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/uapi/linux/swab.h:187
Inline: True
```
```
In drivers/scsi/sd_zbc.c (ffff80001098b414)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
```
```
In drivers/of/property.c (0)
Location: include/uapi/linux/swab.h:187
Inline: True
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
In lib/digsig.c (c080f44c)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/char/tpm/eventlog/of.c (c09b8e78)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/of.c:tpm_read_log_of
```
```
In drivers/of/property.c (c0c5154c)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - drivers/of/property.c:of_property_read_u64_index
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
In arch/powerpc/mm/numa.c (c0000000000a2fac)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - arch/powerpc/mm/numa.c:memory_hotplug_max
```
```
In arch/powerpc/platforms/powernv/pci-ioda.c (c000000001360ae0)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_init_ioda_hub
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_init_ioda_phb
```
```
In arch/powerpc/platforms/pseries/hotplug-memory.c (c0000000000fac3c)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/hotplug-memory.c:pseries_memory_block_size
```
```
In fs/ecryptfs/crypto.c (c00000000063a5b0)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In crypto/sha512_generic.c (c000000000751ce0)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
```
```
In block/partitions/ldm.c (c00000000079ce60)
Location: include/uapi/linux/swab.h:187
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
In lib/digsig.c (c00000000081c36c)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/char/tpm/eventlog/of.c (c0000000009623c4)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/of.c:tpm_read_log_of
```
```
In drivers/scsi/scsi_error.c (c000000000a2cfb0)
Location: include/uapi/linux/swab.h:187
Inline: True
```
```
In drivers/scsi/scsi_trace.c (c000000000a3e7b0)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (c000000000a4a564)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/scsi/sd_zbc.c (c000000000a4bf40)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
```
In drivers/of/property.c (c000000000c49284)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - drivers/of/property.c:of_property_read_u64_index
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
In lib/digsig.c (ffffffe0004928a0)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/char/tpm/eventlog/of.c (ffffffe000571f54)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/of.c:tpm_read_log_of
```
```
In drivers/of/property.c (ffffffe000722e4a)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - drivers/of/property.c:of_property_read_u64_index
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
In fs/ecryptfs/crypto.c (ffffffff8140f499)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In crypto/sha512_generic.c (ffffffff814c4669)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
```
```
In block/partitions/ldm.c (ffffffff814f8796)
Location: include/uapi/linux/swab.h:187
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
In lib/digsig.c (ffffffff815525f2)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/scsi/scsi_error.c (ffffffff81724954)
Location: include/uapi/linux/swab.h:187
Inline: True
```
```
In drivers/scsi/scsi_trace.c (ffffffff8173073f)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff81737e9c)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/scsi/sd_zbc.c (ffffffff81739605)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
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
In fs/ecryptfs/crypto.c (ffffffff813fff19)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In crypto/sha512_generic.c (ffffffff814b5089)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
```
```
In block/partitions/ldm.c (ffffffff814e8ca6)
Location: include/uapi/linux/swab.h:187
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
In lib/digsig.c (ffffffff815428d2)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/scsi/scsi_error.c (ffffffff816fdd84)
Location: include/uapi/linux/swab.h:187
Inline: True
```
```
In drivers/scsi/scsi_trace.c (ffffffff81709b5f)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/scsi_transport_fc.c (ffffffff8170db2b)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - drivers/scsi/scsi_transport_fc.c:fc_parse_wwn
```
```
In drivers/scsi/storvsc_drv.c (ffffffff81713534)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - drivers/scsi/storvsc_drv.c:storvsc_on_channel_callback
  - drivers/scsi/storvsc_drv.c:storvsc_on_channel_callback
  - drivers/scsi/storvsc_drv.c:storvsc_on_channel_callback
  - drivers/scsi/storvsc_drv.c:storvsc_on_channel_callback
  - drivers/scsi/storvsc_drv.c:storvsc_channel_init
  - drivers/scsi/storvsc_drv.c:storvsc_channel_init
  - drivers/scsi/storvsc_drv.c:storvsc_channel_init
  - drivers/scsi/storvsc_drv.c:storvsc_channel_init
```
```
In drivers/scsi/sd.c (ffffffff81719b3c)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/scsi/sd_zbc.c (ffffffff8171b2a5)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
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
In fs/ecryptfs/crypto.c (ffffffff8140c819)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In crypto/sha512_generic.c (ffffffff814c06f9)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
```
```
In block/partitions/ldm.c (ffffffff814f4826)
Location: include/uapi/linux/swab.h:187
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
In lib/digsig.c (ffffffff8154e332)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/scsi/scsi_error.c (ffffffff81763724)
Location: include/uapi/linux/swab.h:187
Inline: True
```
```
In drivers/scsi/scsi_trace.c (ffffffff8176f50f)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff8177862c)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/scsi/sd_zbc.c (ffffffff81779d95)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
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
In fs/ecryptfs/crypto.c (ffffffff81422499)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In crypto/sha512_generic.c (ffffffff814d91c9)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
```
```
In block/partitions/ldm.c (ffffffff8150d886)
Location: include/uapi/linux/swab.h:187
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
In lib/digsig.c (ffffffff81568182)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/scsi/scsi_error.c (ffffffff8177ed84)
Location: include/uapi/linux/swab.h:187
Inline: True
```
```
In drivers/scsi/scsi_trace.c (ffffffff8178acaf)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff8179244c)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/scsi/sd_zbc.c (ffffffff81793bc5)
Location: include/uapi/linux/swab.h:187
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
</details>
</li>
</ul>

## Differences
