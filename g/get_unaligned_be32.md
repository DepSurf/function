# Function: <code>get_unaligned_be32</code>

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
In kernel/bpf/core.c (ffffffff81172543)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
  - kernel/bpf/core.c:__bpf_prog_run
```
```
In fs/ecryptfs/crypto.c (ffffffff8130505c)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
```
```
In crypto/sha256_generic.c (ffffffff813a5e58)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_transform
```
```
In block/partitions/ldm.c (ffffffff813d0258)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
```
```
In lib/decompress_unlzo.c (ffffffff81f9dc1f)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:parse_header
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
```
```
In lib/sha1.c (ffffffff813f057b)
Location: include/linux/unaligned/access_ok.h:27
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
```
In lib/xz/xz_dec_bcj.c (ffffffff81411098)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsi_scan.c (ffffffff815b2f1f)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/sd.c (ffffffff815bcda1)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/firmware/dmi_scan.c (ffffffff81fb572e)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff8176c8e5)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
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
In net/ipv4/cipso_ipv4.c (ffffffff817ae110)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
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
In kernel/bpf/core.c (ffffffff81180335)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
  - kernel/bpf/core.c:__bpf_prog_run
```
```
In fs/ecryptfs/crypto.c (ffffffff8133904c)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
```
```
In crypto/sha256_generic.c (ffffffff813e34c8)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_transform
```
```
In block/partitions/ldm.c (ffffffff814172c8)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
```
```
In lib/decompress_unlzo.c (ffffffff81fc9282)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:parse_header
```
```
In lib/sha1.c (ffffffff81436f35)
Location: include/linux/unaligned/access_ok.h:27
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
```
In lib/xz/xz_dec_bcj.c (ffffffff81458e0b)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsi_scan.c (ffffffff8160b3b1)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_trace.c (ffffffff81610365)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff8161780f)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:read_capacity_16
```
```
In drivers/firmware/dmi_scan.c (ffffffff81fe27fd)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff817d9e6d)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
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
In net/ipv4/cipso_ipv4.c (ffffffff8181b0f3)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In net/ipv6/calipso.c (ffffffff818708c2)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
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
In kernel/bpf/core.c (ffffffff8118c1a5)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
  - kernel/bpf/core.c:__bpf_prog_run
```
```
In fs/ecryptfs/crypto.c (ffffffff8134edec)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
```
```
In crypto/sha256_generic.c (ffffffff813fc4e8)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_transform
```
```
In block/partitions/ldm.c (ffffffff814327f8)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
```
```
In lib/decompress_unlzo.c (ffffffff820061db)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:parse_header
```
```
In lib/sha1.c (ffffffff81453f25)
Location: include/linux/unaligned/access_ok.h:27
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
```
In lib/xz/xz_dec_bcj.c (ffffffff814777cb)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsi_scan.c (ffffffff8163ac65)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_trace.c (ffffffff8163fbf5)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff816472d9)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:read_capacity_16
```
```
In drivers/scsi/sd_zbc.c (ffffffff81648d3e)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8170029e)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
```
In drivers/firmware/dmi_scan.c (ffffffff820205da)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81808473)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
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
In net/ipv4/cipso_ipv4.c (ffffffff8184c9b3)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In net/ipv6/calipso.c (ffffffff818a3832)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
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
In kernel/bpf/core.c (ffffffff8118ff3b)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
  - kernel/bpf/core.c:___bpf_prog_run
```
```
In fs/ecryptfs/crypto.c (ffffffff813638aa)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
```
```
In crypto/sha256_generic.c (ffffffff814097d8)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_transform
```
```
In block/partitions/ldm.c (ffffffff8143f606)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
```
```
In lib/xz/xz_dec_bcj.c (ffffffff81480aa2)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsi_error.c (ffffffff81647ae4)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
```
```
In drivers/scsi/scsi_scan.c (ffffffff8164fbbc)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
```
```
In drivers/scsi/scsi_trace.c (ffffffff816545ac)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff8165bef0)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
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
In drivers/scsi/sd_zbc.c (ffffffff8165d6f2)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
```
```
In drivers/ata/libata-scsi.c (ffffffff8166faa4)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81715b50)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
```
In drivers/firmware/dmi_scan.c (ffffffff82103520)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81828856)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
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
In net/ipv4/cipso_ipv4.c (ffffffff81870403)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In net/ipv6/calipso.c (ffffffff818c9de0)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
```
```
In lib/decompress_unlzo.c (ffffffff821112b6)
Location: include/linux/unaligned/access_ok.h:27
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:parse_header
```
```
In lib/sha1.c (ffffffff818f4055)
Location: include/linux/unaligned/access_ok.h:27
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
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8138861a)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
```
```
In crypto/sha256_generic.c (ffffffff814321f8)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_transform
```
```
In block/partitions/ldm.c (ffffffff8146ba93)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
```
```
In lib/xz/xz_dec_bcj.c (ffffffff814bc8d8)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsi_error.c (ffffffff816b0b54)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
```
```
In drivers/scsi/scsi_scan.c (ffffffff816b91c1)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
```
```
In drivers/scsi/scsi_trace.c (ffffffff816bdafe)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff816c556d)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
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
In drivers/scsi/sd_zbc.c (ffffffff816c6a3c)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
```
```
In drivers/ata/libata-scsi.c (ffffffff816d9084)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81786d50)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
```
In drivers/firmware/dmi_scan.c (ffffffff8270cc01)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff818a7c88)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
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
In net/ipv4/cipso_ipv4.c (ffffffff818f0e03)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In net/ipv6/calipso.c (ffffffff8194d4cb)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
```
```
In lib/decompress_unlzo.c (ffffffff8271b6bc)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:parse_header
```
```
In lib/sha1.c (ffffffff8197aa55)
Location: include/linux/unaligned/access_ok.h:28
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
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff813b7475)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
```
```
In crypto/sha256_generic.c (ffffffff81464d68)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_transform
```
```
In block/partitions/ldm.c (ffffffff8149f223)
Location: include/linux/unaligned/access_ok.h:28
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
```
```
In lib/xz/xz_dec_bcj.c (ffffffff814ef0c8)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsi_error.c (ffffffff816ece9a)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
```
```
In drivers/scsi/scsi_scan.c (ffffffff816f54f0)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
```
```
In drivers/scsi/scsi_trace.c (ffffffff816f9f47)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff81701710)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
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
In drivers/scsi/sd_zbc.c (ffffffff81702e63)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
```
```
In drivers/ata/libata-scsi.c (ffffffff8171552e)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817c7e35)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
```
In drivers/firmware/dmi_scan.c (ffffffff82736ec3)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
```
```
In net/core/filter.c (ffffffff818b1583)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_32
```
```
In net/ipv4/tcp_input.c (ffffffff818fcd7c)
Location: include/linux/unaligned/access_ok.h:28
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
In net/ipv4/cipso_ipv4.c (ffffffff8194773b)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In net/ipv6/calipso.c (ffffffff819a5c70)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
```
```
In lib/decompress_unlzo.c (ffffffff82745ee3)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:parse_header
```
```
In lib/sha1.c (ffffffff819d6fd9)
Location: include/linux/unaligned/access_ok.h:28
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
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff813d0a45)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
```
```
In crypto/sha256_generic.c (ffffffff814829d8)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_transform
```
```
In block/partitions/ldm.c (ffffffff814b95c5)
Location: include/linux/unaligned/access_ok.h:28
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
```
```
In lib/xz/xz_dec_bcj.c (ffffffff81502f59)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsi_error.c (ffffffff817109da)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
```
```
In drivers/scsi/scsi_scan.c (ffffffff81717e18)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
```
```
In drivers/scsi/scsi_trace.c (ffffffff8171c925)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff81724658)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
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
In drivers/scsi/sd_zbc.c (ffffffff81725829)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/ata/libata-scsi.c (ffffffff81737afe)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817ef4d5)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
```
In drivers/firmware/dmi_scan.c (ffffffff828f0def)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
```
```
In net/core/filter.c (ffffffff818d60cd)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_32
```
```
In net/ipv4/tcp_input.c (ffffffff8192aeec)
Location: include/linux/unaligned/access_ok.h:28
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
In net/ipv4/cipso_ipv4.c (ffffffff8197930b)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In net/ipv6/calipso.c (ffffffff819dce3a)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
```
```
In lib/decompress_unlzo.c (ffffffff8290021b)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:parse_header
```
```
In lib/sha1.c (ffffffff81a0f219)
Location: include/linux/unaligned/access_ok.h:28
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
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff813fb585)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
```
```
In crypto/sha256_generic.c (ffffffff814b0c08)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_transform
```
```
In block/partitions/ldm.c (ffffffff814e7cad)
Location: include/linux/unaligned/access_ok.h:28
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
  - block/partitions/ldm.c:ldm_parse_vol5
```
```
In lib/xz/xz_dec_bcj.c (ffffffff81531119)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsi_error.c (ffffffff8174c0cb)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
```
```
In drivers/scsi/scsi_scan.c (ffffffff81753120)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_trace.c (ffffffff81757fdc)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff8175f850)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
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
In drivers/scsi/sd_zbc.c (ffffffff81760e89)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/ata/libata-scsi.c (ffffffff81773aee)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8182ff95)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
```
In drivers/firmware/dmi_scan.c (ffffffff8290c437)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
```
```
In net/core/filter.c (ffffffff819238bd)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_32
```
```
In net/ipv4/tcp_input.c (ffffffff8198e2e6)
Location: include/linux/unaligned/access_ok.h:28
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
In net/ipv4/cipso_ipv4.c (ffffffff819e2ddf)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In net/ipv6/calipso.c (ffffffff81a4baa7)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
```
```
In lib/decompress_unlzo.c (ffffffff8291ce00)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:parse_header
```
```
In lib/sha1.c (ffffffff81a7e791)
Location: include/linux/unaligned/access_ok.h:28
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
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81415465)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
```
```
In block/partitions/ldm.c (ffffffff8150107d)
Location: include/linux/unaligned/access_ok.h:28
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
  - block/partitions/ldm.c:ldm_parse_vol5
```
```
In lib/crypto/sha256.c (ffffffff8152f75a)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
```
```
In lib/xz/xz_dec_bcj.c (ffffffff81551fa9)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsi_error.c (ffffffff8177024b)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
```
```
In drivers/scsi/scsi_scan.c (ffffffff817773a0)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_trace.c (ffffffff8177c077)
Location: include/linux/unaligned/access_ok.h:28
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
```
```
In drivers/scsi/sd.c (ffffffff81783781)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
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
In drivers/scsi/sd_zbc.c (ffffffff81784e49)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/ata/libata-scsi.c (ffffffff81797a5e)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff818618c5)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
```
In drivers/firmware/dmi_scan.c (ffffffff82915e06)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
```
```
In net/core/filter.c (ffffffff81955aed)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_32
```
```
In net/ipv4/tcp_input.c (ffffffff819c4f16)
Location: include/linux/unaligned/access_ok.h:28
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
In net/ipv4/cipso_ipv4.c (ffffffff81a19dcf)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In net/ipv6/calipso.c (ffffffff81a82677)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
```
```
In lib/decompress_unlzo.c (ffffffff82926c82)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:parse_header
```
```
In lib/sha1.c (ffffffff81ab5991)
Location: include/linux/unaligned/access_ok.h:28
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
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81465598)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In block/partitions/ldm.c (ffffffff815617a7)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_dsk4
  - block/partitions/ldm.c:ldm_parse_dsk3
  - block/partitions/ldm.c:ldm_parse_dgr4
  - block/partitions/ldm.c:ldm_parse_dgr3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_vmdb
  - block/partitions/ldm.c:ldm_parse_vmdb
  - block/partitions/ldm.c:ldm_parse_vmdb
  - block/partitions/ldm.c:ldm_parse_vmdb
```
```
In lib/crypto/sha256.c (ffffffff81593a4d)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
```
```
In lib/xz/xz_dec_bcj.c (ffffffff815db683)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In lib/decompress_unlzo.c (ffffffff82d0ca6a)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:parse_header
```
```
In lib/sha1.c (ffffffff815f044b)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
```
```
In drivers/base/regmap/regmap.c (ffffffff817da445)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_32_be_inplace
  - drivers/base/regmap/regmap.c:regmap_parse_32_be
```
```
In drivers/scsi/scsi_error.c (ffffffff81830f2e)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
```
```
In drivers/scsi/scsi_scan.c (ffffffff8183a2b0)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_trace.c (ffffffff8183f2b8)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff81845ea6)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:read_capacity_10
```
```
In drivers/scsi/sd_zbc.c (ffffffff818488e8)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/scsi/sr.c (ffffffff8184a0f1)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/ata/libata-scsi.c (ffffffff8185d632)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff819353b4)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_query_fw_version
```
```
In drivers/firmware/dmi_scan.c (ffffffff82d27fce)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
```
```
In net/core/filter.c (ffffffff81a286db)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_32
```
```
In net/ipv4/tcp_input.c (ffffffff81ab0518)
Location: include/linux/unaligned/access_ok.h:28
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
In net/ipv4/cipso_ipv4.c (ffffffff81b0b497)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In net/ipv6/calipso.c (ffffffff81b7d594)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
```
```
In net/mptcp/options.c (ffffffff81bb0448)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
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
In fs/ecryptfs/crypto.c (ffffffff81480e38)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In block/partitions/ldm.c (ffffffff8157d297)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_dsk4
  - block/partitions/ldm.c:ldm_parse_dsk3
  - block/partitions/ldm.c:ldm_parse_dgr4
  - block/partitions/ldm.c:ldm_parse_dgr3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_vmdb
  - block/partitions/ldm.c:ldm_parse_vmdb
  - block/partitions/ldm.c:ldm_parse_vmdb
  - block/partitions/ldm.c:ldm_parse_vmdb
```
```
In lib/crypto/sha256.c (ffffffff815b064c)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
```
```
In lib/xz/xz_dec_bcj.c (ffffffff815f92d7)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In lib/decompress_unlzo.c (ffffffff82ffa030)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:parse_header
```
```
In lib/sha1.c (ffffffff81614bab)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
```
```
In drivers/base/regmap/regmap.c (ffffffff817ef1f5)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_32_be_inplace
  - drivers/base/regmap/regmap.c:regmap_parse_32_be
```
```
In drivers/scsi/scsi_error.c (ffffffff81841b6e)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
```
```
In drivers/scsi/scsi_scan.c (ffffffff8184ac70)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_trace.c (ffffffff8184f918)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff81855f23)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:read_capacity_10
```
```
In drivers/scsi/sd_zbc.c (ffffffff81858e98)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/scsi/sr.c (ffffffff8185a7a1)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/ata/libata-scsi.c (ffffffff8186c6f2)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8193c424)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_query_fw_version
```
```
In drivers/firmware/dmi_scan.c (ffffffff830166e6)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
```
```
In net/core/filter.c (ffffffff81a28ffb)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_32
```
```
In net/ipv4/tcp_input.c (ffffffff81abb604)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_check_dsack
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b1980b)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In net/ipv6/calipso.c (ffffffff81b8c6ba)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
```
```
In net/mptcp/options.c (ffffffff81bc3e4a)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
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
In fs/ecryptfs/crypto.c (ffffffff81486728)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff814c6e95)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
```
```
In block/partitions/ldm.c (ffffffff81584dca)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
```
```
In lib/crypto/sha256.c (ffffffff815bb487)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
```
```
In lib/xz/xz_dec_bcj.c (ffffffff815dbb9a)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In lib/decompress_unlzo.c (ffffffff83204c3c)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:parse_header
```
```
In lib/sha1.c (ffffffff815f823e)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
```
```
In drivers/base/regmap/regmap.c (ffffffff817d3a95)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_32_be_inplace
  - drivers/base/regmap/regmap.c:regmap_parse_32_be
```
```
In drivers/scsi/scsi_error.c (ffffffff81824b6e)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
```
```
In drivers/scsi/scsi_scan.c (ffffffff8182dfd1)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_trace.c (ffffffff81832d0b)
Location: include/linux/unaligned/access_ok.h:28
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
```
```
In drivers/scsi/sd.c (ffffffff81838cd3)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:read_capacity_10
```
```
In drivers/scsi/sd_zbc.c (ffffffff8183ca40)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/scsi/sr.c (ffffffff8183daa1)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/ata/libata-scsi.c (ffffffff8184f34d)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8191f9bf)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
```
In drivers/firmware/dmi_scan.c (ffffffff8322168f)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
```
```
In net/core/filter.c (ffffffff81a102f4)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_32
```
```
In net/ipv4/tcp_input.c (ffffffff81aa65b5)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_check_dsack
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b0727b)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In net/ipv6/calipso.c (ffffffff81b7b7fa)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
```
```
In net/mptcp/options.c (ffffffff81bb4593)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
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
In fs/ecryptfs/crypto.c (ffffffff814ddeb8)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_read_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff8151f975)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
```
```
In block/partitions/ldm.c (ffffffff815ea73a)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
```
```
In lib/crypto/sha256.c (ffffffff81622067)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
```
```
In lib/xz/xz_dec_bcj.c (ffffffff8164763a)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In lib/decompress_unlzo.c (ffffffff832ec916)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:parse_header
```
```
In lib/sha1.c (ffffffff81665ade)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
  - lib/sha1.c:sha1_transform
```
```
In drivers/base/regmap/regmap.c (ffffffff8185ee05)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_32_be_inplace
  - drivers/base/regmap/regmap.c:regmap_parse_32_be
```
```
In drivers/scsi/scsi_error.c (ffffffff818b03ee)
Location: include/asm-generic/unaligned.h:60
Inline: True
```
```
In drivers/scsi/scsi_scan.c (ffffffff818b9da1)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_trace.c (ffffffff818bed5b)
Location: include/asm-generic/unaligned.h:60
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
```
```
In drivers/scsi/sd.c (ffffffff818c5333)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:read_capacity_10
```
```
In drivers/scsi/sd_zbc.c (ffffffff818c93b0)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/scsi/sr.c (ffffffff818ca561)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/ata/libata-scsi.c (ffffffff818dc9bd)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff819c276f)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
```
In drivers/firmware/dmi_scan.c (ffffffff8330b0dd)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
```
```
In net/core/filter.c (ffffffff81ac5fa7)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_32
```
```
In net/ipv4/tcp_input.c (ffffffff81b629a5)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_check_dsack
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81bca0f7)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In net/ipv6/calipso.c (ffffffff81c4615a)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
```
```
In net/mptcp/options.c (ffffffff81c82d77)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
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
In fs/ecryptfs/crypto.c (ffffffff8156bdf6)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_read_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_read_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_read_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff815b304d)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
```
```
In block/partitions/ldm.c (ffffffff8169a1c7)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
```
```
In lib/crypto/sha256.c (ffffffff816f1bef)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
```
```
In lib/xz/xz_dec_bcj.c (ffffffff8175d8d7)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In lib/decompress_unlzo.c (ffffffff834a450b)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:parse_header
```
```
In lib/sha1.c (ffffffff8178015e)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - lib/sha1.c:sha1_transform
```
```
In drivers/base/regmap/regmap.c (ffffffff819a67b5)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_32_be
```
```
In drivers/scsi/scsi_error.c (ffffffff819fb4c1)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_get_sense_info_fld
```
```
In drivers/scsi/scsi_scan.c (ffffffff81a05748)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_trace.c (ffffffff81a0b175)
Location: include/asm-generic/unaligned.h:60
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
```
```
In drivers/scsi/sd.c (ffffffff81a11d62)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:read_capacity_16
```
```
In drivers/scsi/sd_zbc.c (ffffffff81a15448)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/scsi/sr.c (ffffffff81a17a62)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/ata/libata-scsi.c (ffffffff81a2d4ec)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81b22b53)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
```
In drivers/firmware/dmi_scan.c (ffffffff834c4a29)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
```
```
In net/core/filter.c (ffffffff81c4165d)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_32
```
```
In net/ipv4/tcp_input.c (ffffffff81cf104a)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_check_dsack
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81d5f88c)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In net/ipv6/calipso.c (ffffffff81de5574)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
```
```
In net/mptcp/options.c (ffffffff81e28c12)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
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
In fs/ecryptfs/crypto.c (ffffffff8160ff16)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_read_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_read_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_read_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff8165dccd)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
```
```
In block/partitions/ldm.c (ffffffff8175988d)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
```
```
In lib/crypto/sha1.c (ffffffff817e3783)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - lib/crypto/sha1.c:sha1_transform
```
```
In lib/crypto/sha256.c (ffffffff817e39cf)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
```
```
In lib/xz/xz_dec_bcj.c (ffffffff8188ae07)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/base/regmap/regmap.c (ffffffff81b198f5)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_32_be_inplace
  - drivers/base/regmap/regmap.c:regmap_parse_32_be
```
```
In drivers/scsi/scsi_error.c (ffffffff81b79201)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_get_sense_info_fld
```
```
In drivers/scsi/scsi_scan.c (ffffffff81b8445c)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_trace.c (ffffffff81b8aba5)
Location: include/asm-generic/unaligned.h:60
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
```
```
In drivers/scsi/sd.c (ffffffff81b92042)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:read_capacity_16
```
```
In drivers/scsi/sd_zbc.c (ffffffff81b96378)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/scsi/sr.c (ffffffff81b98972)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/ata/libata-scsi.c (ffffffff81bb0e2c)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81cb546a)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
```
In net/core/filter.c (ffffffff81df6fcd)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_32
```
```
In net/ipv4/tcp_input.c (ffffffff81eb5cca)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_check_dsack
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f29f9c)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In net/ipv6/calipso.c (ffffffff81fb7d64)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
```
```
In net/mptcp/options.c (ffffffff82000de5)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_parse_option
  - net/mptcp/options.c:mptcp_parse_option
  - net/mptcp/options.c:mptcp_parse_option
  - net/mptcp/options.c:mptcp_parse_option
  - net/mptcp/options.c:mptcp_parse_option
  - net/mptcp/options.c:mptcp_parse_option
```
```
In lib/decompress_unlzo.c (ffffffff83f1b356)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
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
In fs/ecryptfs/crypto.c (ffffffff81647da6)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_read_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_read_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_read_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff8169660d)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
```
```
In block/partitions/ldm.c (ffffffff81796d7d)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
```
```
In lib/crypto/sha1.c (ffffffff818236d3)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - lib/crypto/sha1.c:sha1_transform
```
```
In lib/crypto/sha256.c (ffffffff8182391f)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
```
```
In lib/xz/xz_dec_bcj.c (ffffffff818cd295)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/base/regmap/regmap.c (ffffffff81b68385)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_32_be_inplace
  - drivers/base/regmap/regmap.c:regmap_parse_32_be
```
```
In drivers/scsi/scsi_error.c (ffffffff81bcce91)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_get_sense_info_fld
```
```
In drivers/scsi/scsi_scan.c (ffffffff81bd81c8)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_trace.c (ffffffff81bde9fe)
Location: include/asm-generic/unaligned.h:60
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
```
```
In drivers/scsi/sd.c (ffffffff81be8552)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:sd_pr_read_reservation
  - drivers/scsi/sd.c:sd_pr_read_reservation
  - drivers/scsi/sd.c:sd_pr_read_keys
  - drivers/scsi/sd.c:sd_pr_read_keys
```
```
In drivers/scsi/sd_zbc.c (ffffffff81bec666)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/scsi/sr.c (ffffffff81beef08)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/ata/libata-scsi.c (ffffffff81c08bbc)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81d1cada)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
```
In net/core/filter.c (ffffffff81e68ead)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_32
```
```
In net/ipv4/tcp_input.c (ffffffff81f140e6)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_check_dsack
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f89b4b)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In net/ipv6/calipso.c (ffffffff820184f4)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
```
```
In net/mptcp/options.c (ffffffff8207d064)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_parse_option
  - net/mptcp/options.c:mptcp_parse_option
  - net/mptcp/options.c:mptcp_parse_option
  - net/mptcp/options.c:mptcp_parse_option
  - net/mptcp/options.c:mptcp_parse_option
  - net/mptcp/options.c:mptcp_parse_option
```
```
In lib/decompress_unlzo.c (ffffffff83741be6)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
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
In fs/ecryptfs/crypto.c (ffffffff81681259)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_read_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_read_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_read_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff816d2c8d)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
```
```
In block/partitions/ldm.c (ffffffff817da77d)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
```
```
In lib/crypto/sha1.c (ffffffff81869713)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - lib/crypto/sha1.c:sha1_transform
```
```
In lib/crypto/sha256.c (ffffffff8186995f)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
```
```
In lib/xz/xz_dec_bcj.c (ffffffff8191ee30)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/base/regmap/regmap.c (ffffffff81bbc045)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_32_be_inplace
  - drivers/base/regmap/regmap.c:regmap_parse_32_be
```
```
In drivers/scsi/scsi_error.c (ffffffff81c21ac1)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_get_sense_info_fld
```
```
In drivers/scsi/scsi_scan.c (ffffffff81c2ce98)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_trace.c (ffffffff81c338ee)
Location: include/asm-generic/unaligned.h:60
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
```
```
In drivers/scsi/sd.c (ffffffff81c3dab2)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:sd_pr_read_reservation
  - drivers/scsi/sd.c:sd_pr_read_reservation
  - drivers/scsi/sd.c:sd_pr_read_keys
  - drivers/scsi/sd.c:sd_pr_read_keys
```
```
In drivers/scsi/sd_zbc.c (ffffffff81c41d26)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/scsi/sr.c (ffffffff81c44678)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/ata/libata-scsi.c (ffffffff81c5dc9c)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81dd282a)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
```
In net/core/filter.c (ffffffff81f2848d)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_32
```
```
In net/ipv4/tcp_input.c (ffffffff81fd85c6)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_check_dsack
```
```
In net/ipv4/cipso_ipv4.c (ffffffff820512ab)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In net/ipv6/calipso.c (ffffffff820e74c4)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
```
```
In net/mptcp/options.c (ffffffff8215256d)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_parse_option
  - net/mptcp/options.c:mptcp_parse_option
  - net/mptcp/options.c:mptcp_parse_option
  - net/mptcp/options.c:mptcp_parse_option
  - net/mptcp/options.c:mptcp_parse_option
  - net/mptcp/options.c:mptcp_parse_option
```
```
In lib/decompress_unlzo.c (ffffffff83976696)
Location: include/asm-generic/unaligned.h:60
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
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
Location: include/linux/unaligned/access_ok.h:28
Inline: True
```
```
In block/partitions/ldm.c (0)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
```
```
In lib/crypto/sha256.c (0)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
```
```
In lib/xz/xz_dec_bcj.c (0)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
```
```
In drivers/scsi/scsi_scan.c (0)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
```
```
In drivers/scsi/scsi_trace.c (0)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
```
```
In drivers/scsi/sd_zbc.c (0)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
```
```
In drivers/firmware/dmi_scan.c (0)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (0)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
```
```
In net/ipv6/calipso.c (0)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
```
```
In lib/decompress_unlzo.c (0)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
```
```
In lib/sha1.c (0)
Location: include/linux/unaligned/access_ok.h:28
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
In fs/ecryptfs/crypto.c (0)
Location: include/linux/unaligned/be_byteshift.h:46
Inline: True
```
```
In block/partitions/ldm.c (0)
Location: include/linux/unaligned/be_byteshift.h:46
Inline: True
```
```
In lib/crypto/sha256.c (0)
Location: include/linux/unaligned/be_byteshift.h:46
Inline: True
```
```
In lib/xz/xz_dec_bcj.c (0)
Location: include/linux/unaligned/be_byteshift.h:46
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/unaligned/be_byteshift.h:46
Inline: True
```
```
In drivers/scsi/scsi_scan.c (0)
Location: include/linux/unaligned/be_byteshift.h:46
Inline: True
```
```
In drivers/scsi/scsi_trace.c (0)
Location: include/linux/unaligned/be_byteshift.h:46
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/linux/unaligned/be_byteshift.h:46
Inline: True
```
```
In drivers/scsi/sd_zbc.c (0)
Location: include/linux/unaligned/be_byteshift.h:46
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/unaligned/be_byteshift.h:46
Inline: True
```
```
In drivers/firmware/dmi_scan.c (0)
Location: include/linux/unaligned/be_byteshift.h:46
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/unaligned/be_byteshift.h:46
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/unaligned/be_byteshift.h:46
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (0)
Location: include/linux/unaligned/be_byteshift.h:46
Inline: True
```
```
In net/ipv6/calipso.c (0)
Location: include/linux/unaligned/be_byteshift.h:46
Inline: True
```
```
In lib/decompress_unlzo.c (0)
Location: include/linux/unaligned/be_byteshift.h:46
Inline: True
```
```
In lib/sha1.c (0)
Location: include/linux/unaligned/be_byteshift.h:46
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
In fs/ecryptfs/crypto.c (c000000000637b30)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
```
```
In block/partitions/ldm.c (c00000000079ea7c)
Location: include/linux/unaligned/access_ok.h:28
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
  - block/partitions/ldm.c:ldm_parse_vol5
```
```
In lib/crypto/sha256.c (c0000000007e3110)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
```
```
In lib/xz/xz_dec_bcj.c (c00000000080fec8)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsi_error.c (c000000000a2cf80)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
```
```
In drivers/scsi/scsi_scan.c (c000000000a36a30)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_trace.c (c000000000a3e7b0)
Location: include/linux/unaligned/access_ok.h:28
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
```
```
In drivers/scsi/sd.c (c000000000a4a540)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
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
In drivers/scsi/sd_zbc.c (c000000000a4c7c8)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/ata/libata-scsi.c (c000000000a66c08)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
```
In net/core/filter.c (c000000000cdd734)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_32
```
```
In net/ipv4/tcp_input.c (c000000000d7fd9c)
Location: include/linux/unaligned/access_ok.h:28
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
In net/ipv4/cipso_ipv4.c (c000000000df558c)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In net/ipv6/calipso.c (c000000000e8523c)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
```
```
In lib/decompress_unlzo.c (c0000000013cabac)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:parse_header
```
```
In lib/sha1.c (c000000000ed3550)
Location: include/linux/unaligned/access_ok.h:28
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
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffe0003655de)
Location: include/linux/unaligned/be_byteshift.h:46
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
```
```
In block/partitions/ldm.c (ffffffe00043e7b4)
Location: include/linux/unaligned/be_byteshift.h:46
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
  - block/partitions/ldm.c:ldm_parse_vol5
```
```
In lib/crypto/sha256.c (ffffffe000468908)
Location: include/linux/unaligned/be_byteshift.h:46
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
```
```
In lib/xz/xz_dec_bcj.c (ffffffe00048b8ce)
Location: include/linux/unaligned/be_byteshift.h:46
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsi_error.c (ffffffe0005dc3f8)
Location: include/linux/unaligned/be_byteshift.h:46
Inline: True
```
```
In drivers/scsi/scsi_scan.c (ffffffe0005e275a)
Location: include/linux/unaligned/be_byteshift.h:46
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_trace.c (ffffffe0005e7ad8)
Location: include/linux/unaligned/be_byteshift.h:46
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
```
```
In drivers/scsi/sd.c (ffffffe0005ee31c)
Location: include/linux/unaligned/be_byteshift.h:46
Inline: True
Inline callers:
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
Location: include/linux/unaligned/be_byteshift.h:46
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/ata/libata-scsi.c (ffffffe000600a4c)
Location: include/linux/unaligned/be_byteshift.h:46
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
```
In drivers/mmc/host/mmc_spi.c (ffffffe00071ab54)
Location: include/linux/unaligned/be_byteshift.h:46
Inline: True
```
```
In net/core/filter.c (ffffffe000778c24)
Location: include/linux/unaligned/be_byteshift.h:46
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_32
```
```
In net/ipv4/tcp_input.c (ffffffe0007dae4e)
Location: include/linux/unaligned/be_byteshift.h:46
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
Location: include/linux/unaligned/be_byteshift.h:46
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In net/ipv6/calipso.c (ffffffe0008870b0)
Location: include/linux/unaligned/be_byteshift.h:46
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
```
```
In lib/decompress_unlzo.c (ffffffe0000469b8)
Location: include/linux/unaligned/be_byteshift.h:46
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:parse_header
```
```
In lib/sha1.c (ffffffe0008b83fa)
Location: include/linux/unaligned/be_byteshift.h:46
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8140da45)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
```
```
In block/partitions/ldm.c (ffffffff814f965d)
Location: include/linux/unaligned/access_ok.h:28
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
  - block/partitions/ldm.c:ldm_parse_vol5
```
```
In lib/crypto/sha256.c (ffffffff81527d3a)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
```
```
In lib/xz/xz_dec_bcj.c (ffffffff8154a589)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsi_error.c (ffffffff8172493b)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
```
```
In drivers/scsi/scsi_scan.c (ffffffff8172ba90)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_trace.c (ffffffff81730767)
Location: include/linux/unaligned/access_ok.h:28
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
```
```
In drivers/scsi/sd.c (ffffffff81737e71)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
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
In drivers/scsi/sd_zbc.c (ffffffff81739539)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/ata/libata-scsi.c (ffffffff8175cb6e)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
```
In drivers/firmware/dmi_scan.c (ffffffff828fb35a)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
```
```
In net/core/filter.c (ffffffff818f5abd)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_32
```
```
In net/ipv4/tcp_input.c (ffffffff81964d86)
Location: include/linux/unaligned/access_ok.h:28
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
In net/ipv4/cipso_ipv4.c (ffffffff819b945f)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In net/ipv6/calipso.c (ffffffff81a21d07)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
```
```
In lib/decompress_unlzo.c (ffffffff8290b986)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:parse_header
```
```
In lib/sha1.c (ffffffff81a547e1)
Location: include/linux/unaligned/access_ok.h:28
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
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff813fe4c5)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
```
```
In block/partitions/ldm.c (ffffffff814e9b6d)
Location: include/linux/unaligned/access_ok.h:28
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
  - block/partitions/ldm.c:ldm_parse_vol5
```
```
In lib/crypto/sha256.c (ffffffff8151801a)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
```
```
In lib/xz/xz_dec_bcj.c (ffffffff8153a869)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsi_error.c (ffffffff816fdd6b)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
```
```
In drivers/scsi/scsi_scan.c (ffffffff81704eb0)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_trace.c (ffffffff81709b87)
Location: include/linux/unaligned/access_ok.h:28
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
```
```
In drivers/scsi/sd.c (ffffffff81719b11)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
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
In drivers/scsi/sd_zbc.c (ffffffff8171b1d9)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/ata/libata-scsi.c (ffffffff8173ca0e)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
```
In drivers/firmware/dmi_scan.c (ffffffff828f2bf6)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
```
```
In net/core/filter.c (ffffffff818af8ed)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_32
```
```
In net/ipv4/tcp_input.c (ffffffff8191e876)
Location: include/linux/unaligned/access_ok.h:28
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
In net/ipv4/cipso_ipv4.c (ffffffff8197624f)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In net/ipv6/calipso.c (ffffffff819deac7)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
```
```
In lib/decompress_unlzo.c (ffffffff82903cd4)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:parse_header
```
```
In lib/sha1.c (ffffffff81a118c1)
Location: include/linux/unaligned/access_ok.h:28
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
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8140adc5)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
```
```
In block/partitions/ldm.c (ffffffff814f56ed)
Location: include/linux/unaligned/access_ok.h:28
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
  - block/partitions/ldm.c:ldm_parse_vol5
```
```
In lib/crypto/sha256.c (ffffffff81523dca)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
```
```
In lib/xz/xz_dec_bcj.c (ffffffff815462c9)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsi_error.c (ffffffff8176370b)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
```
```
In drivers/scsi/scsi_scan.c (ffffffff8176a860)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_trace.c (ffffffff8176f537)
Location: include/linux/unaligned/access_ok.h:28
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
```
```
In drivers/scsi/sd.c (ffffffff81778601)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
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
In drivers/scsi/sd_zbc.c (ffffffff81779cc9)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/ata/libata-scsi.c (ffffffff8178c8de)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81855a55)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
```
In drivers/firmware/dmi_scan.c (ffffffff8291043b)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
```
```
In net/core/filter.c (ffffffff81946aed)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_32
```
```
In net/netfilter/nf_conntrack_proto_tcp.c (ffffffff819a6166)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_tcp.c:tcp_in_window
```
```
In net/ipv4/tcp_input.c (ffffffff819cf556)
Location: include/linux/unaligned/access_ok.h:28
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
In net/ipv4/cipso_ipv4.c (ffffffff81a23edf)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In net/ipv6/calipso.c (ffffffff81a8c787)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
```
```
In lib/decompress_unlzo.c (ffffffff829212d0)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:parse_header
```
```
In lib/sha1.c (ffffffff81ac0bd1)
Location: include/linux/unaligned/access_ok.h:28
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
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81420a65)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
```
```
In block/partitions/ldm.c (ffffffff8150e74d)
Location: include/linux/unaligned/access_ok.h:28
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
  - block/partitions/ldm.c:ldm_parse_vol5
```
```
In lib/crypto/sha256.c (ffffffff8153d74a)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
```
```
In lib/xz/xz_dec_bcj.c (ffffffff815600f9)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsi_error.c (ffffffff8177ed6b)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
```
```
In drivers/scsi/scsi_scan.c (ffffffff81785fb0)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_trace.c (ffffffff8178acd7)
Location: include/linux/unaligned/access_ok.h:28
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
```
```
In drivers/scsi/sd.c (ffffffff81792421)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
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
In drivers/scsi/sd_zbc.c (ffffffff81793af9)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/ata/libata-scsi.c (ffffffff817a672e)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81870b85)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
```
In drivers/firmware/dmi_scan.c (ffffffff82916e68)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
```
```
In net/core/filter.c (ffffffff819683fd)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_32
```
```
In net/ipv4/tcp_input.c (ffffffff819d90e6)
Location: include/linux/unaligned/access_ok.h:28
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
In net/ipv4/cipso_ipv4.c (ffffffff81a2f341)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In net/ipv6/calipso.c (ffffffff81a99511)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
```
```
In lib/decompress_unlzo.c (ffffffff82927cf4)
Location: include/linux/unaligned/access_ok.h:28
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:parse_header
```
```
In lib/sha1.c (ffffffff81acd0a1)
Location: include/linux/unaligned/access_ok.h:28
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

## Differences
