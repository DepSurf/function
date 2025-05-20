# Function: <code>__get_unaligned_be32</code>

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
Location: include/linux/unaligned/be_byteshift.h:12
Inline: True
```
```
In crypto/sha512_generic.c (0)
Location: include/linux/unaligned/be_byteshift.h:12
Inline: True
```
```
In block/partitions/ldm.c (0)
Location: include/linux/unaligned/be_byteshift.h:12
Inline: True
```
```
In lib/crypto/sha256.c (0)
Location: include/linux/unaligned/be_byteshift.h:12
Inline: True
```
```
In lib/xz/xz_dec_bcj.c (0)
Location: include/linux/unaligned/be_byteshift.h:12
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/unaligned/be_byteshift.h:12
Inline: True
```
```
In drivers/scsi/scsi_scan.c (0)
Location: include/linux/unaligned/be_byteshift.h:12
Inline: True
```
```
In drivers/scsi/scsi_trace.c (0)
Location: include/linux/unaligned/be_byteshift.h:12
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/unaligned/be_byteshift.h:12
Inline: True
```
```
In drivers/scsi/sd_zbc.c (0)
Location: include/linux/unaligned/be_byteshift.h:12
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/unaligned/be_byteshift.h:12
Inline: True
```
```
In drivers/firmware/dmi_scan.c (0)
Location: include/linux/unaligned/be_byteshift.h:12
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/unaligned/be_byteshift.h:12
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/unaligned/be_byteshift.h:12
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (0)
Location: include/linux/unaligned/be_byteshift.h:12
Inline: True
```
```
In net/ipv6/calipso.c (0)
Location: include/linux/unaligned/be_byteshift.h:12
Inline: True
```
```
In lib/decompress_unlzo.c (0)
Location: include/linux/unaligned/be_byteshift.h:12
Inline: True
```
```
In lib/sha1.c (0)
Location: include/linux/unaligned/be_byteshift.h:12
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
Location: include/linux/unaligned/be_byteshift.h:12
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_i_size_init
  - fs/ecryptfs/crypto.c:ecryptfs_i_size_init
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
```
```
In crypto/sha512_generic.c (ffffffe00040bf7e)
Location: include/linux/unaligned/be_byteshift.h:12
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
```
```
In block/partitions/ldm.c (ffffffe00043e7b4)
Location: include/linux/unaligned/be_byteshift.h:12
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
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
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In lib/crypto/sha256.c (ffffffe000468908)
Location: include/linux/unaligned/be_byteshift.h:12
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
```
```
In lib/xz/xz_dec_bcj.c (ffffffe00048b8ce)
Location: include/linux/unaligned/be_byteshift.h:12
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsi_error.c (ffffffe0005dc3f8)
Location: include/linux/unaligned/be_byteshift.h:12
Inline: True
```
```
In drivers/scsi/scsi_scan.c (ffffffe0005e275a)
Location: include/linux/unaligned/be_byteshift.h:12
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_trace.c (ffffffe0005e7ad8)
Location: include/linux/unaligned/be_byteshift.h:12
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffe0005ee31c)
Location: include/linux/unaligned/be_byteshift.h:12
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:read_capacity_10
```
```
In drivers/scsi/sd_zbc.c (ffffffe0005f00f0)
Location: include/linux/unaligned/be_byteshift.h:12
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/ata/libata-scsi.c (ffffffe000600a4c)
Location: include/linux/unaligned/be_byteshift.h:12
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
```
In drivers/mmc/host/mmc_spi.c (ffffffe00071ab54)
Location: include/linux/unaligned/be_byteshift.h:12
Inline: True
```
```
In net/core/filter.c (ffffffe000778c24)
Location: include/linux/unaligned/be_byteshift.h:12
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_32
```
```
In net/ipv4/tcp_input.c (ffffffe0007dae4e)
Location: include/linux/unaligned/be_byteshift.h:12
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
```
In net/ipv4/cipso_ipv4.c (ffffffe0008268b2)
Location: include/linux/unaligned/be_byteshift.h:12
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In net/ipv6/calipso.c (ffffffe0008870b0)
Location: include/linux/unaligned/be_byteshift.h:12
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
```
```
In lib/decompress_unlzo.c (ffffffe0000469b8)
Location: include/linux/unaligned/be_byteshift.h:12
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:parse_header
```
```
In lib/sha1.c (ffffffe0008b83fa)
Location: include/linux/unaligned/be_byteshift.h:12
Inline: True
Inline callers:
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
  - lib/sha1.c:sha_transform
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
