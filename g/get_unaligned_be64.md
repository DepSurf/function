# Function: <code>get_unaligned_be64</code>

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
Location: include/linux/unaligned/access_ok.h:32
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_i_size_init
```
```
In crypto/sha512_generic.c (ffffffff813a86d6)
Location: include/linux/unaligned/access_ok.h:32
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
```
```
In block/partitions/ldm.c (ffffffff813d0601)
Location: include/linux/unaligned/access_ok.h:32
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
In drivers/scsi/sd.c (ffffffff815bd751)
Location: include/linux/unaligned/access_ok.h:32
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
Location: include/linux/unaligned/access_ok.h:32
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In crypto/sha512_generic.c (ffffffff813e5bb8)
Location: include/linux/unaligned/access_ok.h:32
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
```
```
In block/partitions/ldm.c (ffffffff81416978)
Location: include/linux/unaligned/access_ok.h:32
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
In drivers/scsi/scsi_trace.c (ffffffff816100fe)
Location: include/linux/unaligned/access_ok.h:32
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff81617839)
Location: include/linux/unaligned/access_ok.h:32
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
Location: include/linux/unaligned/access_ok.h:32
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In crypto/sha512_generic.c (ffffffff813febd8)
Location: include/linux/unaligned/access_ok.h:32
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
```
```
In block/partitions/ldm.c (ffffffff81431ea8)
Location: include/linux/unaligned/access_ok.h:32
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
In drivers/scsi/scsi_trace.c (ffffffff8163f98e)
Location: include/linux/unaligned/access_ok.h:32
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff81647303)
Location: include/linux/unaligned/access_ok.h:32
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:read_capacity_16
```
```
In drivers/scsi/sd_zbc.c (ffffffff81648a84)
Location: include/linux/unaligned/access_ok.h:32
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
Location: include/linux/unaligned/access_ok.h:32
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In crypto/sha512_generic.c (ffffffff8140bef1)
Location: include/linux/unaligned/access_ok.h:32
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
```
```
In block/partitions/ldm.c (ffffffff8143ee4b)
Location: include/linux/unaligned/access_ok.h:32
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
In drivers/scsi/scsi_error.c (ffffffff81647af4)
Location: include/linux/unaligned/access_ok.h:32
Inline: True
```
```
In drivers/scsi/scsi_trace.c (ffffffff81654484)
Location: include/linux/unaligned/access_ok.h:32
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff8165bf13)
Location: include/linux/unaligned/access_ok.h:32
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/scsi/sd_zbc.c (ffffffff8165d3d4)
Location: include/linux/unaligned/access_ok.h:32
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
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In crypto/sha512_generic.c (ffffffff81434911)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
```
```
In block/partitions/ldm.c (ffffffff8146b240)
Location: include/linux/unaligned/access_ok.h:33
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
In drivers/scsi/scsi_error.c (ffffffff816b0b64)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
```
```
In drivers/scsi/scsi_trace.c (ffffffff816bd9ca)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff816c5590)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/scsi/sd_zbc.c (ffffffff816c6cf2)
Location: include/linux/unaligned/access_ok.h:33
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
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In crypto/sha512_generic.c (ffffffff81467499)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
```
```
In block/partitions/ldm.c (ffffffff8149ec32)
Location: include/linux/unaligned/access_ok.h:33
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
In drivers/scsi/scsi_error.c (ffffffff816eceaa)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
```
```
In drivers/scsi/scsi_trace.c (ffffffff816f9eec)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff81701c18)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/scsi/sd_zbc.c (ffffffff817030b9)
Location: include/linux/unaligned/access_ok.h:33
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
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In crypto/sha512_generic.c (ffffffff81485109)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
```
```
In block/partitions/ldm.c (ffffffff814b8fda)
Location: include/linux/unaligned/access_ok.h:33
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
In drivers/scsi/scsi_error.c (ffffffff817109ea)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
```
```
In drivers/scsi/scsi_trace.c (ffffffff8171c72f)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff81724bcf)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/scsi/sd_zbc.c (ffffffff817258a3)
Location: include/linux/unaligned/access_ok.h:33
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
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In crypto/sha512_generic.c (ffffffff814b3319)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
```
```
In block/partitions/ldm.c (ffffffff814e6de6)
Location: include/linux/unaligned/access_ok.h:33
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
In drivers/scsi/scsi_error.c (ffffffff8174c0e4)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
```
```
In drivers/scsi/scsi_trace.c (ffffffff8175802d)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff8175f87b)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/scsi/sd_zbc.c (ffffffff81760f55)
Location: include/linux/unaligned/access_ok.h:33
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
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In crypto/sha512_generic.c (ffffffff814cc089)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
```
```
In block/partitions/ldm.c (ffffffff815001b6)
Location: include/linux/unaligned/access_ok.h:33
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
In drivers/scsi/scsi_error.c (ffffffff81770264)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
```
```
In drivers/scsi/scsi_trace.c (ffffffff8177c04f)
Location: include/linux/unaligned/access_ok.h:33
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
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/scsi/sd_zbc.c (ffffffff81784f15)
Location: include/linux/unaligned/access_ok.h:33
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
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In crypto/sha512_generic.c (ffffffff8152b528)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
```
```
In block/partitions/ldm.c (ffffffff81560487)
Location: include/linux/unaligned/access_ok.h:33
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
In drivers/base/regmap/regmap.c (ffffffff817da3f5)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_64_be_inplace
  - drivers/base/regmap/regmap.c:regmap_parse_64_be
```
```
In drivers/scsi/scsi_error.c (ffffffff81830f47)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
```
```
In drivers/scsi/scsi_trace.c (ffffffff8183f669)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff81845e8d)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_block_limits
```
```
In drivers/scsi/sd_zbc.c (ffffffff81848782)
Location: include/linux/unaligned/access_ok.h:33
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
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_finish_connect
```
```
In net/mptcp/options.c (ffffffff81bb1654)
Location: include/linux/unaligned/access_ok.h:33
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
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In crypto/sha512_generic.c (ffffffff815484f8)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
```
```
In block/partitions/ldm.c (ffffffff8157bf77)
Location: include/linux/unaligned/access_ok.h:33
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
In drivers/base/regmap/regmap.c (ffffffff817ef1a5)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_64_be_inplace
  - drivers/base/regmap/regmap.c:regmap_parse_64_be
```
```
In drivers/scsi/scsi_error.c (ffffffff81841b87)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
```
```
In drivers/scsi/scsi_trace.c (ffffffff8184fcc9)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff81855f0a)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_block_limits
```
```
In drivers/scsi/sd_zbc.c (ffffffff81858c69)
Location: include/linux/unaligned/access_ok.h:33
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
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_finish_connect
```
```
In net/mptcp/options.c (ffffffff81bc5598)
Location: include/linux/unaligned/access_ok.h:33
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
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In crypto/sha512_generic.c (ffffffff81550bbd)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
```
```
In block/partitions/ldm.c (ffffffff81583a59)
Location: include/linux/unaligned/access_ok.h:33
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
In drivers/base/regmap/regmap.c (ffffffff817d3a45)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_64_be_inplace
  - drivers/base/regmap/regmap.c:regmap_parse_64_be
```
```
In drivers/scsi/scsi_error.c (ffffffff81824b83)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
```
```
In drivers/scsi/scsi_trace.c (ffffffff81832ce3)
Location: include/linux/unaligned/access_ok.h:33
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
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_block_limits
```
```
In drivers/scsi/sd_zbc.c (ffffffff8183ca95)
Location: include/linux/unaligned/access_ok.h:33
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
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_check_req
```
```
In net/mptcp/options.c (ffffffff81bb49cb)
Location: include/linux/unaligned/access_ok.h:33
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
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff814ddd2f)
Location: include/asm-generic/unaligned.h:65
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In crypto/sha512_generic.c (ffffffff815b15e7)
Location: include/asm-generic/unaligned.h:65
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
```
```
In block/partitions/ldm.c (ffffffff815e90a9)
Location: include/asm-generic/unaligned.h:65
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
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
In drivers/base/regmap/regmap.c (ffffffff8185ed95)
Location: include/asm-generic/unaligned.h:65
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_64_be_inplace
  - drivers/base/regmap/regmap.c:regmap_parse_64_be
```
```
In drivers/scsi/scsi_error.c (ffffffff818b0403)
Location: include/asm-generic/unaligned.h:65
Inline: True
```
```
In drivers/scsi/scsi_trace.c (ffffffff818bed33)
Location: include/asm-generic/unaligned.h:65
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff818c531a)
Location: include/asm-generic/unaligned.h:65
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_block_limits
```
```
In drivers/scsi/sd_zbc.c (ffffffff818c9405)
Location: include/asm-generic/unaligned.h:65
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
```
```
In net/mptcp/subflow.c (ffffffff81c819a9)
Location: include/asm-generic/unaligned.h:65
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_check_req
```
```
In net/mptcp/options.c (ffffffff81c832ef)
Location: include/asm-generic/unaligned.h:65
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
  - net/mptcp/options.c:mptcp_parse_option
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
In fs/ecryptfs/crypto.c (ffffffff8156be3e)
Location: include/asm-generic/unaligned.h:65
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In crypto/sha512_generic.c (ffffffff8165a058)
Location: include/asm-generic/unaligned.h:65
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
```
```
In block/partitions/ldm.c (ffffffff816989ce)
Location: include/asm-generic/unaligned.h:65
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
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
In drivers/base/regmap/regmap.c (ffffffff819a6755)
Location: include/asm-generic/unaligned.h:65
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_64_be
```
```
In drivers/scsi/scsi_error.c (ffffffff819fb4df)
Location: include/asm-generic/unaligned.h:65
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_get_sense_info_fld
```
```
In drivers/scsi/scsi_trace.c (ffffffff81a0b14c)
Location: include/asm-generic/unaligned.h:65
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff81a10d10)
Location: include/asm-generic/unaligned.h:65
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:read_capacity_16
```
```
In drivers/scsi/sd_zbc.c (ffffffff81a154d2)
Location: include/asm-generic/unaligned.h:65
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
```
```
In drivers/ata/libata-scsi.c (ffffffff81a2c170)
Location: include/asm-generic/unaligned.h:65
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
```
```
In net/mptcp/subflow.c (ffffffff81e274b3)
Location: include/asm-generic/unaligned.h:65
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_check_req
```
```
In net/mptcp/options.c (ffffffff81e2924a)
Location: include/asm-generic/unaligned.h:65
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
  - net/mptcp/options.c:mptcp_parse_option
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
In fs/ecryptfs/crypto.c (ffffffff8160ff5e)
Location: include/asm-generic/unaligned.h:65
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In crypto/sha512_generic.c (ffffffff817143a8)
Location: include/asm-generic/unaligned.h:65
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
```
```
In block/partitions/ldm.c (ffffffff81757a01)
Location: include/asm-generic/unaligned.h:65
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
In drivers/base/regmap/regmap.c (ffffffff81b198c5)
Location: include/asm-generic/unaligned.h:65
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_64_be_inplace
  - drivers/base/regmap/regmap.c:regmap_parse_64_be
```
```
In drivers/scsi/scsi_error.c (ffffffff81b7921f)
Location: include/asm-generic/unaligned.h:65
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_get_sense_info_fld
```
```
In drivers/scsi/scsi_trace.c (ffffffff81b8ab7c)
Location: include/asm-generic/unaligned.h:65
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff81b90f6b)
Location: include/asm-generic/unaligned.h:65
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:read_capacity_16
```
```
In drivers/scsi/sd_zbc.c (ffffffff81b96402)
Location: include/asm-generic/unaligned.h:65
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
```
```
In drivers/ata/libata-scsi.c (ffffffff81baf760)
Location: include/asm-generic/unaligned.h:65
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
```
```
In net/mptcp/subflow.c (ffffffff81ffec11)
Location: include/asm-generic/unaligned.h:65
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_check_req
```
```
In net/mptcp/options.c (ffffffff82000a2a)
Location: include/asm-generic/unaligned.h:65
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
  - net/mptcp/options.c:mptcp_parse_option
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
In fs/ecryptfs/crypto.c (ffffffff81647dee)
Location: include/asm-generic/unaligned.h:65
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In crypto/sha512_generic.c (ffffffff8174f19f)
Location: include/asm-generic/unaligned.h:65
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
```
```
In block/partitions/ldm.c (ffffffff81794da1)
Location: include/asm-generic/unaligned.h:65
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
In drivers/base/regmap/regmap.c (ffffffff81b68355)
Location: include/asm-generic/unaligned.h:65
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_64_be_inplace
  - drivers/base/regmap/regmap.c:regmap_parse_64_be
```
```
In drivers/scsi/scsi_error.c (ffffffff81bccea2)
Location: include/asm-generic/unaligned.h:65
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_get_sense_info_fld
```
```
In drivers/scsi/scsi_trace.c (ffffffff81bde9e9)
Location: include/asm-generic/unaligned.h:65
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff81be69e4)
Location: include/asm-generic/unaligned.h:65
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:sd_pr_read_reservation
  - drivers/scsi/sd.c:sd_pr_read_keys
```
```
In drivers/scsi/sd_zbc.c (ffffffff81bec6ef)
Location: include/asm-generic/unaligned.h:65
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
```
```
In drivers/ata/libata-scsi.c (ffffffff81c06db2)
Location: include/asm-generic/unaligned.h:65
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
```
```
In net/mptcp/subflow.c (ffffffff8207acf1)
Location: include/asm-generic/unaligned.h:65
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_check_req
```
```
In net/mptcp/options.c (ffffffff8207cbda)
Location: include/asm-generic/unaligned.h:65
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
  - net/mptcp/options.c:mptcp_parse_option
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
In fs/ecryptfs/crypto.c (ffffffff816812a1)
Location: include/asm-generic/unaligned.h:65
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In crypto/sha512_generic.c (ffffffff81790def)
Location: include/asm-generic/unaligned.h:65
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
```
```
In block/partitions/ldm.c (ffffffff817d8701)
Location: include/asm-generic/unaligned.h:65
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
In drivers/scsi/scsi_error.c (ffffffff81c21ad2)
Location: include/asm-generic/unaligned.h:65
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_get_sense_info_fld
```
```
In drivers/scsi/scsi_trace.c (ffffffff81c338d9)
Location: include/asm-generic/unaligned.h:65
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff81c3c9f4)
Location: include/asm-generic/unaligned.h:65
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:sd_pr_read_reservation
  - drivers/scsi/sd.c:sd_pr_read_keys
```
```
In drivers/scsi/sd_zbc.c (ffffffff81c41daf)
Location: include/asm-generic/unaligned.h:65
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
```
```
In drivers/ata/libata-scsi.c (ffffffff81c5be92)
Location: include/asm-generic/unaligned.h:65
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
```
```
In net/mptcp/subflow.c (ffffffff82150406)
Location: include/asm-generic/unaligned.h:65
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_check_req
```
```
In net/mptcp/options.c (ffffffff821520da)
Location: include/asm-generic/unaligned.h:65
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
  - net/mptcp/options.c:mptcp_parse_option
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
Location: include/linux/unaligned/access_ok.h:33
Inline: True
```
```
In crypto/sha512_generic.c (0)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
```
```
In block/partitions/ldm.c (0)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
```
```
In drivers/scsi/scsi_trace.c (0)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
```
```
In drivers/scsi/sd_zbc.c (ffff80001098b414)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
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
In fs/ecryptfs/crypto.c (0)
Location: include/linux/unaligned/be_byteshift.h:51
Inline: True
```
```
In crypto/sha512_generic.c (0)
Location: include/linux/unaligned/be_byteshift.h:51
Inline: True
```
```
In block/partitions/ldm.c (0)
Location: include/linux/unaligned/be_byteshift.h:51
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/unaligned/be_byteshift.h:51
Inline: True
```
```
In drivers/scsi/scsi_trace.c (0)
Location: include/linux/unaligned/be_byteshift.h:51
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/unaligned/be_byteshift.h:51
Inline: True
```
```
In drivers/scsi/sd_zbc.c (0)
Location: include/linux/unaligned/be_byteshift.h:51
Inline: True
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
In fs/ecryptfs/crypto.c (c00000000063a5b0)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In crypto/sha512_generic.c (c000000000751ce0)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
```
```
In block/partitions/ldm.c (c00000000079ce60)
Location: include/linux/unaligned/access_ok.h:33
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
In drivers/scsi/scsi_error.c (c000000000a2cfb0)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
```
```
In drivers/scsi/scsi_trace.c (c000000000a3e7b0)
Location: include/linux/unaligned/access_ok.h:33
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
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/scsi/sd_zbc.c (c000000000a4bf40)
Location: include/linux/unaligned/access_ok.h:33
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
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffe000366e70)
Location: include/linux/unaligned/be_byteshift.h:51
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_i_size_init
```
```
In crypto/sha512_generic.c (ffffffe00040bf7e)
Location: include/linux/unaligned/be_byteshift.h:51
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
```
```
In block/partitions/ldm.c (ffffffe00043dd6a)
Location: include/linux/unaligned/be_byteshift.h:51
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
Location: include/linux/unaligned/be_byteshift.h:51
Inline: True
```
```
In drivers/scsi/scsi_trace.c (ffffffe0005e7ad8)
Location: include/linux/unaligned/be_byteshift.h:51
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
Location: include/linux/unaligned/be_byteshift.h:51
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/scsi/sd_zbc.c (ffffffe0005ef786)
Location: include/linux/unaligned/be_byteshift.h:51
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8140f499)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In crypto/sha512_generic.c (ffffffff814c4669)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
```
```
In block/partitions/ldm.c (ffffffff814f8796)
Location: include/linux/unaligned/access_ok.h:33
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
In drivers/scsi/scsi_error.c (ffffffff81724954)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
```
```
In drivers/scsi/scsi_trace.c (ffffffff8173073f)
Location: include/linux/unaligned/access_ok.h:33
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
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/scsi/sd_zbc.c (ffffffff81739605)
Location: include/linux/unaligned/access_ok.h:33
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
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In crypto/sha512_generic.c (ffffffff814b5089)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
```
```
In block/partitions/ldm.c (ffffffff814e8ca6)
Location: include/linux/unaligned/access_ok.h:33
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
In drivers/scsi/scsi_error.c (ffffffff816fdd84)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
```
```
In drivers/scsi/scsi_trace.c (ffffffff81709b5f)
Location: include/linux/unaligned/access_ok.h:33
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
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - drivers/scsi/scsi_transport_fc.c:fc_parse_wwn
```
```
In drivers/scsi/storvsc_drv.c (ffffffff81713534)
Location: include/linux/unaligned/access_ok.h:33
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
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/scsi/sd_zbc.c (ffffffff8171b2a5)
Location: include/linux/unaligned/access_ok.h:33
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
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In crypto/sha512_generic.c (ffffffff814c06f9)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
```
```
In block/partitions/ldm.c (ffffffff814f4826)
Location: include/linux/unaligned/access_ok.h:33
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
In drivers/scsi/scsi_error.c (ffffffff81763724)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
```
```
In drivers/scsi/scsi_trace.c (ffffffff8176f50f)
Location: include/linux/unaligned/access_ok.h:33
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
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/scsi/sd_zbc.c (ffffffff81779d95)
Location: include/linux/unaligned/access_ok.h:33
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
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In crypto/sha512_generic.c (ffffffff814d91c9)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
```
```
In block/partitions/ldm.c (ffffffff8150d886)
Location: include/linux/unaligned/access_ok.h:33
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
In drivers/scsi/scsi_error.c (ffffffff8177ed84)
Location: include/linux/unaligned/access_ok.h:33
Inline: True
```
```
In drivers/scsi/scsi_trace.c (ffffffff8178acaf)
Location: include/linux/unaligned/access_ok.h:33
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
Location: include/linux/unaligned/access_ok.h:33
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/scsi/sd_zbc.c (ffffffff81793bc5)
Location: include/linux/unaligned/access_ok.h:33
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
