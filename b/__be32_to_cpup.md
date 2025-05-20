# Function: <code>__be32_to_cpup</code>

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
Location: include/uapi/linux/byteorder/little_endian.h:79
Inline: True
Inline callers:
  - kernel/bpf/core.c:__bpf_prog_run
```
```
In fs/ecryptfs/crypto.c (ffffffff8130505c)
Location: include/uapi/linux/byteorder/little_endian.h:79
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
```
```
In crypto/sha256_generic.c (ffffffff813a5e58)
Location: include/uapi/linux/byteorder/little_endian.h:79
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_transform
```
```
In block/partitions/ldm.c (ffffffff813d0258)
Location: include/uapi/linux/byteorder/little_endian.h:79
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
Location: include/uapi/linux/byteorder/little_endian.h:79
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:parse_header
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
```
```
In lib/sha1.c (ffffffff813f057b)
Location: include/uapi/linux/byteorder/little_endian.h:79
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
Location: include/uapi/linux/byteorder/little_endian.h:79
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff815269bc)
Location: include/uapi/linux/byteorder/little_endian.h:79
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
```
```
In drivers/scsi/scsi_scan.c (ffffffff815b2f1f)
Location: include/uapi/linux/byteorder/little_endian.h:79
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/sd.c (ffffffff815bcda1)
Location: include/uapi/linux/byteorder/little_endian.h:79
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
Location: include/uapi/linux/byteorder/little_endian.h:79
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff8176c8e5)
Location: include/uapi/linux/byteorder/little_endian.h:79
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
Location: include/uapi/linux/byteorder/little_endian.h:79
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
Location: include/uapi/linux/byteorder/little_endian.h:79
Inline: True
Inline callers:
  - kernel/bpf/core.c:__bpf_prog_run
```
```
In fs/ecryptfs/crypto.c (ffffffff8133904c)
Location: include/uapi/linux/byteorder/little_endian.h:79
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
```
```
In crypto/sha256_generic.c (ffffffff813e34c8)
Location: include/uapi/linux/byteorder/little_endian.h:79
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_transform
```
```
In block/partitions/ldm.c (ffffffff814172c8)
Location: include/uapi/linux/byteorder/little_endian.h:79
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
Location: include/uapi/linux/byteorder/little_endian.h:79
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:parse_header
```
```
In lib/sha1.c (ffffffff81436f35)
Location: include/uapi/linux/byteorder/little_endian.h:79
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
Location: include/uapi/linux/byteorder/little_endian.h:79
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81579eb9)
Location: include/uapi/linux/byteorder/little_endian.h:79
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
```
```
In drivers/scsi/scsi_scan.c (ffffffff8160b3b1)
Location: include/uapi/linux/byteorder/little_endian.h:79
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_trace.c (ffffffff81610365)
Location: include/uapi/linux/byteorder/little_endian.h:79
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff8161780f)
Location: include/uapi/linux/byteorder/little_endian.h:79
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
Location: include/uapi/linux/byteorder/little_endian.h:79
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff817d9e6d)
Location: include/uapi/linux/byteorder/little_endian.h:79
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
Location: include/uapi/linux/byteorder/little_endian.h:79
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In net/ipv6/calipso.c (ffffffff818708c2)
Location: include/uapi/linux/byteorder/little_endian.h:79
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
Location: include/uapi/linux/byteorder/little_endian.h:79
Inline: True
Inline callers:
  - kernel/bpf/core.c:__bpf_prog_run
```
```
In fs/ecryptfs/crypto.c (ffffffff8134edec)
Location: include/uapi/linux/byteorder/little_endian.h:79
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
```
```
In crypto/sha256_generic.c (ffffffff813fc4e8)
Location: include/uapi/linux/byteorder/little_endian.h:79
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_transform
```
```
In block/partitions/ldm.c (ffffffff814327f8)
Location: include/uapi/linux/byteorder/little_endian.h:79
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
Location: include/uapi/linux/byteorder/little_endian.h:79
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:parse_header
```
```
In lib/sha1.c (ffffffff81453f25)
Location: include/uapi/linux/byteorder/little_endian.h:79
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
Location: include/uapi/linux/byteorder/little_endian.h:79
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff815a63f8)
Location: include/uapi/linux/byteorder/little_endian.h:79
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
```
```
In drivers/scsi/scsi_scan.c (ffffffff8163ac65)
Location: include/uapi/linux/byteorder/little_endian.h:79
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_trace.c (ffffffff8163fbf5)
Location: include/uapi/linux/byteorder/little_endian.h:79
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff816472d9)
Location: include/uapi/linux/byteorder/little_endian.h:79
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
Location: include/uapi/linux/byteorder/little_endian.h:79
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8170029e)
Location: include/uapi/linux/byteorder/little_endian.h:79
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
```
In drivers/firmware/dmi_scan.c (ffffffff820205da)
Location: include/uapi/linux/byteorder/little_endian.h:79
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81808473)
Location: include/uapi/linux/byteorder/little_endian.h:79
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
Location: include/uapi/linux/byteorder/little_endian.h:79
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In net/ipv6/calipso.c (ffffffff818a3832)
Location: include/uapi/linux/byteorder/little_endian.h:79
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
Location: include/uapi/linux/byteorder/little_endian.h:79
Inline: True
Inline callers:
  - kernel/bpf/core.c:___bpf_prog_run
```
```
In fs/ecryptfs/crypto.c (ffffffff813638aa)
Location: include/uapi/linux/byteorder/little_endian.h:79
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
```
```
In crypto/sha256_generic.c (ffffffff814097d8)
Location: include/uapi/linux/byteorder/little_endian.h:79
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_transform
```
```
In block/partitions/ldm.c (ffffffff8143f606)
Location: include/uapi/linux/byteorder/little_endian.h:79
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
Location: include/uapi/linux/byteorder/little_endian.h:79
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff815bad12)
Location: include/uapi/linux/byteorder/little_endian.h:79
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff815bc8a8)
Location: include/uapi/linux/byteorder/little_endian.h:79
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/scsi/scsi_error.c (ffffffff81647ae4)
Location: include/uapi/linux/byteorder/little_endian.h:79
Inline: True
```
```
In drivers/scsi/scsi_scan.c (ffffffff8164fbbc)
Location: include/uapi/linux/byteorder/little_endian.h:79
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
```
```
In drivers/scsi/scsi_trace.c (ffffffff816545ac)
Location: include/uapi/linux/byteorder/little_endian.h:79
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff8165bef0)
Location: include/uapi/linux/byteorder/little_endian.h:79
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
Location: include/uapi/linux/byteorder/little_endian.h:79
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
```
```
In drivers/ata/libata-scsi.c (ffffffff8166faa4)
Location: include/uapi/linux/byteorder/little_endian.h:79
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81715b50)
Location: include/uapi/linux/byteorder/little_endian.h:79
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
```
In drivers/firmware/dmi_scan.c (ffffffff82103520)
Location: include/uapi/linux/byteorder/little_endian.h:79
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81828856)
Location: include/uapi/linux/byteorder/little_endian.h:79
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
Location: include/uapi/linux/byteorder/little_endian.h:79
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In net/ipv6/calipso.c (ffffffff818c9de0)
Location: include/uapi/linux/byteorder/little_endian.h:79
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
```
```
In lib/decompress_unlzo.c (ffffffff821112b6)
Location: include/uapi/linux/byteorder/little_endian.h:79
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:parse_header
```
```
In lib/sha1.c (ffffffff818f4055)
Location: include/uapi/linux/byteorder/little_endian.h:79
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
```
```
In crypto/sha256_generic.c (ffffffff814321f8)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_transform
```
```
In block/partitions/ldm.c (ffffffff8146ba93)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81621365)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff81622d48)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/scsi/scsi_error.c (ffffffff816b0b54)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In drivers/scsi/scsi_scan.c (ffffffff816b91c1)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
```
```
In drivers/scsi/scsi_trace.c (ffffffff816bdafe)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff816c556d)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81786d50)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
```
In drivers/firmware/dmi_scan.c (ffffffff8270cc01)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff818a7c88)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In net/ipv6/calipso.c (ffffffff8194d4cb)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
```
```
In lib/decompress_unlzo.c (ffffffff8271b6bc)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:parse_header
```
```
In lib/sha1.c (ffffffff8197aa55)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
```
```
In crypto/sha256_generic.c (ffffffff81464d68)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_transform
```
```
In block/partitions/ldm.c (ffffffff8149f223)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff8165b121)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff8165cb2d)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff816604e8)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_recv
```
```
In drivers/scsi/scsi_error.c (ffffffff816ece9a)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In drivers/scsi/scsi_scan.c (ffffffff816f54f0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
```
```
In drivers/scsi/scsi_trace.c (ffffffff816f9f47)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff81701710)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817c7e35)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
```
In drivers/firmware/dmi_scan.c (ffffffff82736ec3)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
```
```
In net/core/filter.c (ffffffff818b1583)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_32
```
```
In net/ipv4/tcp_input.c (ffffffff818fcd7c)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In net/ipv6/calipso.c (ffffffff819a5c70)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
```
```
In lib/decompress_unlzo.c (ffffffff82745ee3)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:parse_header
```
```
In lib/sha1.c (ffffffff819d6fd9)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
```
```
In crypto/sha256_generic.c (ffffffff814829d8)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_transform
```
```
In block/partitions/ldm.c (ffffffff814b95c5)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816790d8)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff81679e9d)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8167e075)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_recv
```
```
In drivers/scsi/scsi_error.c (ffffffff817109da)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In drivers/scsi/scsi_scan.c (ffffffff81717e18)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
```
```
In drivers/scsi/scsi_trace.c (ffffffff8171c925)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff81724658)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817ef4d5)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
```
In drivers/firmware/dmi_scan.c (ffffffff828f0def)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
```
```
In drivers/nvmem/core.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In net/core/filter.c (ffffffff818d60cd)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_32
```
```
In net/ipv4/tcp_input.c (ffffffff8192aeec)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In net/ipv6/calipso.c (ffffffff819dce3a)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
```
```
In lib/decompress_unlzo.c (ffffffff8290021b)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:parse_header
```
```
In lib/sha1.c (ffffffff81a0f219)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
```
```
In crypto/sha256_generic.c (ffffffff814b0c08)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_transform
```
```
In block/partitions/ldm.c (ffffffff814e7cad)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816af8d8)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff816b05c4)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff816b4dd2)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_recv
```
```
In drivers/scsi/scsi_error.c (ffffffff8174c0cb)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In drivers/scsi/scsi_scan.c (ffffffff81753120)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_trace.c (ffffffff81757fdc)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
  - drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb
```
```
In drivers/scsi/sd.c (ffffffff8175f850)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8182ff95)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
```
In drivers/firmware/dmi_scan.c (ffffffff8290c437)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
```
```
In drivers/nvmem/core.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In net/core/filter.c (ffffffff819238bd)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_32
```
```
In net/ipv4/tcp_input.c (ffffffff8198e2e6)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In net/ipv6/calipso.c (ffffffff81a4baa7)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
```
```
In lib/decompress_unlzo.c (ffffffff8291ce00)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:parse_header
```
```
In lib/sha1.c (ffffffff81a7e791)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
```
```
In block/partitions/ldm.c (ffffffff8150107d)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
```
```
In lib/xz/xz_dec_bcj.c (ffffffff81551fa9)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816d25d1)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff816d32c4)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff816d7ab2)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_recv
```
```
In drivers/scsi/scsi_error.c (ffffffff8177024b)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In drivers/scsi/scsi_scan.c (ffffffff817773a0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_trace.c (ffffffff8177c077)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff818618c5)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
```
In drivers/firmware/dmi_scan.c (ffffffff82915e06)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
```
```
In drivers/nvmem/core.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In net/core/filter.c (ffffffff81955aed)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_32
```
```
In net/ipv4/tcp_input.c (ffffffff819c4f16)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In net/ipv6/calipso.c (ffffffff81a82677)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
```
```
In lib/decompress_unlzo.c (ffffffff82926c82)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:parse_header
```
```
In lib/sha1.c (ffffffff81ab5991)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
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
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff814a3608)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
```
```
In block/partitions/ldm.c (ffffffff815617a7)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
```
```
In lib/xz/xz_dec_bcj.c (ffffffff815db683)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In lib/decompress_unlzo.c (ffffffff82d0ca6a)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:parse_header
```
```
In lib/sha1.c (ffffffff815f044b)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff81785b52)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff8178765b)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8178bf82)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_recv
```
```
In drivers/base/regmap/regmap.c (ffffffff817da445)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_32_be_inplace
  - drivers/base/regmap/regmap.c:regmap_parse_32_be
```
```
In drivers/scsi/scsi_error.c (ffffffff81830f2e)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In drivers/scsi/scsi_scan.c (ffffffff8183a2b0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_trace.c (ffffffff8183f2b8)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/ata/libata-scsi.c (ffffffff8185d632)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff819353b4)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_query_fw_version
```
```
In drivers/firmware/dmi_scan.c (ffffffff82d27fce)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
```
```
In drivers/nvmem/core.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In net/core/filter.c (ffffffff81a286db)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_32
```
```
In net/ipv4/tcp_input.c (ffffffff81ab0518)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In net/ipv6/calipso.c (ffffffff81b7d594)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
```
```
In net/mptcp/options.c (ffffffff81bb0448)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
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
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff814c0dad)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
```
```
In block/partitions/ldm.c (ffffffff8157d297)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In lib/decompress_unlzo.c (ffffffff82ffa030)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:parse_header
```
```
In lib/sha1.c (ffffffff81614bab)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff8179cd52)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff8179e76b)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff817a2512)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_recv
```
```
In drivers/base/regmap/regmap.c (ffffffff817ef1f5)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_32_be_inplace
  - drivers/base/regmap/regmap.c:regmap_parse_32_be
```
```
In drivers/scsi/scsi_error.c (ffffffff81841b6e)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In drivers/scsi/scsi_scan.c (ffffffff8184ac70)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_trace.c (ffffffff8184f918)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/ata/libata-scsi.c (ffffffff8186c6f2)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8193c424)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_query_fw_version
```
```
In drivers/firmware/dmi_scan.c (ffffffff830166e6)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
```
```
In drivers/nvmem/core.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In net/core/filter.c (ffffffff81a28ffb)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_32
```
```
In net/ipv4/tcp_input.c (ffffffff81abb604)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In net/ipv6/calipso.c (ffffffff81b8c6ba)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
```
```
In net/mptcp/options.c (ffffffff81bc3e4a)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
```
```
In block/partitions/ldm.c (ffffffff81584dca)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In lib/decompress_unlzo.c (ffffffff83204c3c)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:parse_header
```
```
In lib/sha1.c (ffffffff815f823e)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff8177f827)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff81781088)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff81785212)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_recv
```
```
In drivers/base/regmap/regmap.c (ffffffff817d3a95)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_32_be_inplace
  - drivers/base/regmap/regmap.c:regmap_parse_32_be
```
```
In drivers/scsi/scsi_error.c (ffffffff81824b6e)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In drivers/scsi/scsi_scan.c (ffffffff8182dfd1)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_trace.c (ffffffff81832d0b)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/ata/libata-scsi.c (ffffffff8184f34d)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8191f9bf)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
```
In drivers/firmware/dmi_scan.c (ffffffff8322168f)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
```
```
In drivers/nvmem/core.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In net/core/filter.c (ffffffff81a102f4)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_32
```
```
In net/ipv4/tcp_input.c (ffffffff81aa65b5)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In net/ipv6/calipso.c (ffffffff81b7b7fa)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
```
```
In net/mptcp/options.c (ffffffff81bb4593)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff8151fa7d)
Location: include/uapi/linux/byteorder/little_endian.h:81
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81805bb7)
Location: include/uapi/linux/byteorder/little_endian.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff8180767f)
Location: include/uapi/linux/byteorder/little_endian.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8180bd42)
Location: include/uapi/linux/byteorder/little_endian.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_recv
```
```
In drivers/nvmem/core.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:81
Inline: True
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
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff815b31db)
Location: include/uapi/linux/byteorder/little_endian.h:81
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff8194566d)
Location: include/uapi/linux/byteorder/little_endian.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff819472a8)
Location: include/uapi/linux/byteorder/little_endian.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8194c2d2)
Location: include/uapi/linux/byteorder/little_endian.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_recv
```
```
In drivers/nvmem/core.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:81
Inline: True
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
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff8165de5b)
Location: include/uapi/linux/byteorder/little_endian.h:81
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81aa869d)
Location: include/uapi/linux/byteorder/little_endian.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff81aaa5ec)
Location: include/uapi/linux/byteorder/little_endian.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff81ab0452)
Location: include/uapi/linux/byteorder/little_endian.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_recv
```
```
In drivers/nvmem/core.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:81
Inline: True
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
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff816967a3)
Location: include/uapi/linux/byteorder/little_endian.h:81
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81af3ecd)
Location: include/uapi/linux/byteorder/little_endian.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff81af5e0c)
Location: include/uapi/linux/byteorder/little_endian.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff81afc2a2)
Location: include/uapi/linux/byteorder/little_endian.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_recv
```
```
In drivers/nvmem/core.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:81
Inline: True
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
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff816d2e23)
Location: include/uapi/linux/byteorder/little_endian.h:81
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81b4748d)
Location: include/uapi/linux/byteorder/little_endian.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff81b493fc)
Location: include/uapi/linux/byteorder/little_endian.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff81b4f8b2)
Location: include/uapi/linux/byteorder/little_endian.h:81
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_recv
```
```
In drivers/nvmem/core.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:81
Inline: True
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In block/partitions/ldm.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In lib/crypto/sha256.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In lib/xz/xz_dec_bcj.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In drivers/bus/fsl-mc/fsl-mc-bus.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In drivers/pinctrl/devicetree.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In drivers/pinctrl/pinctrl-rockchip.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In drivers/char/tpm/tpm2-space.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In drivers/char/tpm/eventlog/of.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In drivers/char/tpm/tpm_crb.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In drivers/iommu/of_iommu.c (ffff8000108cea7c)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/iommu/of_iommu.c:of_get_dma_window
  - drivers/iommu/of_iommu.c:of_get_dma_window
```
```
In drivers/misc/vexpress-syscfg.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In drivers/scsi/scsi_scan.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In drivers/scsi/scsi_trace.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In drivers/scsi/sd_zbc.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In drivers/edac/altera_edac.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In drivers/opp/of.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In drivers/firmware/dmi_scan.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In drivers/of/base.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In drivers/of/property.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In drivers/of/dynamic.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In drivers/of/fdt.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In drivers/of/fdt_address.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In drivers/of/address.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In drivers/of/irq.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In drivers/of/resolver.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In drivers/of/overlay.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In drivers/nvmem/core.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In net/core/filter.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In net/ipv6/calipso.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In lib/decompress_unlzo.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In lib/sha1.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
In arch/arm/kernel/topology.c (c1506b1c)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - arch/arm/kernel/topology.c:init_cpu_topology
```
```
In arch/arm/mach-omap2/omap_hwmod.c (c03394cc)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap_hwmod.c:omap_hwmod_parse_module_range
```
```
In drivers/irqchip/irq-renesas-rza1.c (c08203a0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-rza1.c:rza1_irqc_probe
  - drivers/irqchip/irq-renesas-rza1.c:rza1_irqc_probe
  - drivers/irqchip/irq-renesas-rza1.c:rza1_irqc_probe
```
```
In drivers/bus/mvebu-mbus.c (c154f268)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/bus/mvebu-mbus.c:mvebu_mbus_dt_init
  - drivers/bus/mvebu-mbus.c:mvebu_mbus_dt_init
  - drivers/bus/mvebu-mbus.c:mvebu_mbus_dt_init
```
```
In drivers/bus/ti-sysc.c (c0828048)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/bus/ti-sysc.c:sysc_map_and_check_registers
```
```
In drivers/bus/uniphier-system-bus.c (c08298d8)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/bus/uniphier-system-bus.c:uniphier_system_bus_probe
  - drivers/bus/uniphier-system-bus.c:uniphier_system_bus_probe
  - drivers/bus/uniphier-system-bus.c:uniphier_system_bus_probe
```
```
In drivers/pinctrl/devicetree.c (c0832870)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/pinctrl/devicetree.c:pinctrl_parse_index_with_args
  - drivers/pinctrl/devicetree.c:pinctrl_dt_to_map
```
```
In drivers/pinctrl/pinctrl-rockchip.c (c083a69c)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_parse_dt
```
```
In drivers/char/tpm/tpm2-cmd.c (c09b6494)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm2-space.c (c09b7304)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/eventlog/of.c (c09b8e74)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/of.c:tpm_read_log_of
```
```
In drivers/iommu/of_iommu.c (c09c12fc)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/iommu/of_iommu.c:of_get_dma_window
  - drivers/iommu/of_iommu.c:of_get_dma_window
  - drivers/iommu/of_iommu.c:of_get_dma_window
```
```
In drivers/misc/vexpress-syscfg.c (c0a0a8e0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/misc/vexpress-syscfg.c:vexpress_syscfg_regmap_init
  - drivers/misc/vexpress-syscfg.c:vexpress_syscfg_regmap_init
  - drivers/misc/vexpress-syscfg.c:vexpress_syscfg_regmap_init
```
```
In drivers/net/ethernet/ti/cpsw.c (c0ad354c)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe_dt
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe_dt
```
```
In drivers/opp/of.c (c0bf6dd8)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/opp/of.c:dev_pm_opp_of_add_table
  - drivers/opp/of.c:dev_pm_opp_of_add_table
```
```
In drivers/opp/ti-opp-supply.c (c0bf7a1c)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In drivers/of/base.c (c0c4d3b0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/of/base.c:of_map_rid
  - drivers/of/base.c:of_map_rid
  - drivers/of/base.c:of_map_rid
  - drivers/of/base.c:of_map_rid
  - drivers/of/base.c:of_parse_phandle_with_args_map
  - drivers/of/base.c:of_phandle_iterator_args
  - drivers/of/base.c:of_phandle_iterator_next
```
```
In drivers/of/property.c (c0c51250)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/of/property.c:of_prop_next_u32
  - drivers/of/property.c:of_property_read_variable_u32_array
  - drivers/of/property.c:of_property_read_u32_index
```
```
In drivers/of/dynamic.c (c0c52edc)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/of/dynamic.c:__of_attach_node
```
```
In drivers/of/fdt.c (c15aee1c)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/of/fdt.c:early_init_dt_scan_root
  - drivers/of/fdt.c:early_init_dt_scan_root
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/fdt.c:__unflatten_device_tree
  - drivers/of/fdt.c:unflatten_dt_nodes
  - drivers/of/fdt.c:unflatten_dt_nodes
```
```
In drivers/of/fdt_address.c (c15b004c)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/of/fdt_address.c:fdt_bus_default_count_cells
  - drivers/of/fdt_address.c:fdt_bus_default_count_cells
```
```
In drivers/of/address.c (c0c54a6c)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/of/address.c:of_bus_isa_get_flags
  - drivers/of/address.c:of_pci_range_parser_one
  - drivers/of/address.c:of_pci_range_parser_one
  - drivers/of/address.c:of_pci_range_parser_one
  - drivers/of/address.c:of_bus_pci_map
  - drivers/of/address.c:of_bus_pci_map
```
```
In drivers/of/irq.c (c0c56f20)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/of/irq.c:of_irq_parse_raw
  - drivers/of/irq.c:of_irq_parse_raw
```
```
In drivers/of/resolver.c (c0c58bc4)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/of/resolver.c:adjust_overlay_phandles
```
```
In drivers/of/overlay.c (c0c5a348)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In drivers/nvmem/core.c (c0c819a0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In sound/soc/soc-core.c (c0ca16f8)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - sound/soc/soc-core.c:snd_soc_of_get_slot_mask
```
```
In sound/soc/fsl/fsl_ssi.c (c0cc0634)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_probe
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
In arch/powerpc/kernel/prom.c (c000000001349510)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - arch/powerpc/kernel/prom.c:early_init_dt_scan_cpus
  - arch/powerpc/kernel/prom.c:early_init_dt_scan_cpus
  - arch/powerpc/kernel/prom.c:early_init_dt_scan_cpus
```
```
In arch/powerpc/kernel/setup-common.c (c00000000134a430)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - arch/powerpc/kernel/setup-common.c:smp_setup_cpu_maps
```
```
In arch/powerpc/kernel/dt_cpu_ftrs.c (c00000000134ee04)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - arch/powerpc/kernel/dt_cpu_ftrs.c:dt_cpu_ftrs_scan_callback
  - arch/powerpc/kernel/dt_cpu_ftrs.c:scan_cpufeatures_subnodes
  - arch/powerpc/kernel/dt_cpu_ftrs.c:scan_cpufeatures_subnodes
  - arch/powerpc/kernel/dt_cpu_ftrs.c:scan_cpufeatures_subnodes
  - arch/powerpc/kernel/dt_cpu_ftrs.c:scan_cpufeatures_subnodes
  - arch/powerpc/kernel/dt_cpu_ftrs.c:scan_cpufeatures_subnodes
  - arch/powerpc/kernel/dt_cpu_ftrs.c:scan_cpufeatures_subnodes
  - arch/powerpc/kernel/dt_cpu_ftrs.c:scan_cpufeatures_subnodes
```
```
In arch/powerpc/kernel/crash_dump.c (c00000000004bd7c)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - arch/powerpc/kernel/crash_dump.c:crash_free_reserved_phys_range
  - arch/powerpc/kernel/crash_dump.c:crash_free_reserved_phys_range
```
```
In arch/powerpc/kernel/smp.c (c000000000054564)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - arch/powerpc/kernel/smp.c:cpu_to_core_id
```
```
In arch/powerpc/kernel/legacy_serial.c (c000000001351b80)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - arch/powerpc/kernel/legacy_serial.c:find_legacy_serial_ports
```
```
In arch/powerpc/kernel/isa-bridge.c (c0000000013522a8)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - arch/powerpc/kernel/isa-bridge.c:isa_bridge_init_non_pci
  - arch/powerpc/kernel/isa-bridge.c:isa_bridge_init_non_pci
```
```
In arch/powerpc/mm/book3s64/radix_pgtable.c (c0000000013563d4)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_pgtable.c:radix_dt_scan_page_sizes
```
```
In arch/powerpc/sysdev/xive/common.c (c0000000000beaf0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/common.c:xmon_xive_do_dump
  - arch/powerpc/sysdev/xive/common.c:xmon_xive_do_dump
  - arch/powerpc/sysdev/xive/common.c:xive_scan_interrupts
```
```
In arch/powerpc/platforms/powernv/opal-async.c (c00000000135ba8c)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-async.c:opal_async_comp_init
```
```
In arch/powerpc/platforms/powernv/opal-nvram.c (c00000000135c66c)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-nvram.c:opal_nvram_init
```
```
In arch/powerpc/platforms/powernv/pci-ioda.c (c000000001360024)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_init_ioda_phb
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_init_ioda_phb
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_init_ioda_phb
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_init_ioda_phb
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_init_ioda_phb
```
```
In arch/powerpc/platforms/pseries/nvram.c (c000000001361d30)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/nvram.c:pSeries_nvram_init
```
```
In arch/powerpc/platforms/pseries/msi.c (c0000000000f7624)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/msi.c:msi_quota_for_device
  - arch/powerpc/platforms/pseries/msi.c:count_spare_msis
  - arch/powerpc/platforms/pseries/msi.c:count_spare_msis
  - arch/powerpc/platforms/pseries/msi.c:count_non_bridge_devices
  - arch/powerpc/platforms/pseries/msi.c:check_req
```
```
In arch/powerpc/platforms/pseries/lparcfg.c (c0000000000fef60)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/lparcfg.c:lparcfg_data
```
```
In arch/powerpc/kvm/book3s_hv_rm_xive.c (c000000000124990)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_rm_xive.c:xive_rm_h_cppr
  - arch/powerpc/kvm/book3s_hv_rm_xive.c:xive_rm_scan_interrupts
```
```
In fs/ecryptfs/crypto.c (c000000000637b30)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
```
```
In block/partitions/ldm.c (c00000000079ea7c)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
```
```
In lib/xz/xz_dec_bcj.c (c00000000080fec8)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/pinctrl/devicetree.c (c00000000082c800)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/pinctrl/devicetree.c:pinctrl_parse_index_with_args
  - drivers/pinctrl/devicetree.c:pinctrl_dt_to_map
```
```
In drivers/video/fbdev/offb.c (c0000000013a450c)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/video/fbdev/offb.c:offb_init_nodriver
  - drivers/video/fbdev/offb.c:offb_init_nodriver
  - drivers/video/fbdev/offb.c:offb_init_nodriver
  - drivers/video/fbdev/offb.c:offb_init_nodriver
  - drivers/video/fbdev/offb.c:offb_init_nodriver
  - drivers/video/fbdev/offb.c:offb_init_nodriver
```
```
In drivers/tty/hvc/hvc_opal.c (c0000000013a65e4)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_opal.c:hvc_opal_init_early
  - drivers/tty/hvc/hvc_opal.c:hvc_opal_probe
```
```
In drivers/tty/hvc/hvsi.c (c0000000013a6b90)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/tty/hvc/hvsi.c:hvsi_console_init
  - drivers/tty/hvc/hvsi.c:hvsi_console_init
  - drivers/tty/hvc/hvsi.c:hvsi_console_init
```
```
In drivers/char/tpm/tpm2-cmd.c (c00000000095ef20)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm2-space.c (c00000000095ffc8)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/eventlog/of.c (c0000000009623c0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/of.c:tpm_read_log_of
```
```
In drivers/iommu/of_iommu.c (c000000000970398)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/iommu/of_iommu.c:of_get_dma_window
  - drivers/iommu/of_iommu.c:of_get_dma_window
  - drivers/iommu/of_iommu.c:of_get_dma_window
```
```
In drivers/scsi/scsi_error.c (c000000000a2cf80)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In drivers/scsi/scsi_scan.c (c000000000a36a30)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_trace.c (c000000000a3e7b0)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
```
In drivers/opp/of.c (c000000000c0eda0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/opp/of.c:dev_pm_opp_of_add_table
  - drivers/opp/of.c:dev_pm_opp_of_add_table
```
```
In drivers/of/base.c (c000000000c42cc0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/of/base.c:of_map_rid
  - drivers/of/base.c:of_map_rid
  - drivers/of/base.c:of_map_rid
  - drivers/of/base.c:of_map_rid
  - drivers/of/base.c:of_parse_phandle_with_args_map
  - drivers/of/base.c:of_phandle_iterator_args
  - drivers/of/base.c:of_phandle_iterator_next
```
```
In drivers/of/property.c (c000000000c48e40)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/of/property.c:of_prop_next_u32
  - drivers/of/property.c:of_property_read_variable_u32_array
  - drivers/of/property.c:of_property_read_u32_index
```
```
In drivers/of/dynamic.c (c000000000c4bf64)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/of/dynamic.c:__of_attach_node
```
```
In drivers/of/fdt.c (c0000000013ba7d0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/of/fdt.c:early_init_dt_scan_root
  - drivers/of/fdt.c:early_init_dt_scan_root
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/fdt.c:__unflatten_device_tree
  - drivers/of/fdt.c:unflatten_dt_nodes
  - drivers/of/fdt.c:unflatten_dt_nodes
```
```
In drivers/of/fdt_address.c (c0000000013bbb8c)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/of/fdt_address.c:fdt_bus_default_count_cells
  - drivers/of/fdt_address.c:fdt_bus_default_count_cells
```
```
In drivers/of/address.c (c000000000c4ea28)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/of/address.c:of_bus_isa_get_flags
  - drivers/of/address.c:of_pci_range_parser_one
  - drivers/of/address.c:of_pci_range_parser_one
  - drivers/of/address.c:of_pci_range_parser_one
  - drivers/of/address.c:of_bus_pci_map
  - drivers/of/address.c:of_bus_pci_map
```
```
In drivers/of/irq.c (c000000000c51d9c)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/of/irq.c:of_irq_parse_raw
  - drivers/of/irq.c:of_irq_parse_raw
```
```
In drivers/of/resolver.c (c000000000c54af8)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/of/resolver.c:adjust_overlay_phandles
```
```
In drivers/of/overlay.c (c000000000c57ab8)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In drivers/nvmem/core.c (c000000000c73810)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In net/core/filter.c (c000000000cdd734)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_32
```
```
In net/ipv4/tcp_input.c (c000000000d7fd9c)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In net/ipv6/calipso.c (c000000000e8523c)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
```
```
In lib/decompress_unlzo.c (c0000000013cabac)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:parse_header
```
```
In lib/sha1.c (c000000000ed3550)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
In drivers/pinctrl/devicetree.c (ffffffe00049c5d0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/pinctrl/devicetree.c:pinctrl_parse_index_with_args
  - drivers/pinctrl/devicetree.c:pinctrl_dt_to_map
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffe00056f4a8)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm2-space.c (ffffffe0005704c6)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/eventlog/of.c (ffffffe000571f54)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/of.c:tpm_read_log_of
```
```
In drivers/opp/of.c (ffffffe00070461a)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/opp/of.c:dev_pm_opp_of_add_table
  - drivers/opp/of.c:dev_pm_opp_of_add_table
```
```
In drivers/of/base.c (ffffffe00071f52c)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/of/base.c:of_map_rid
  - drivers/of/base.c:of_map_rid
  - drivers/of/base.c:of_map_rid
  - drivers/of/base.c:of_map_rid
  - drivers/of/base.c:of_parse_phandle_with_args_map
  - drivers/of/base.c:of_phandle_iterator_args
  - drivers/of/base.c:of_phandle_iterator_next
```
```
In drivers/of/property.c (ffffffe000722cf2)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/of/property.c:of_prop_next_u32
  - drivers/of/property.c:of_property_read_variable_u32_array
  - drivers/of/property.c:of_property_read_u32_index
```
```
In drivers/of/dynamic.c (ffffffe0007247fe)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/of/dynamic.c:__of_attach_node
```
```
In drivers/of/fdt.c (ffffffe00003aca4)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/of/fdt.c:early_init_dt_scan_root
  - drivers/of/fdt.c:early_init_dt_scan_root
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/fdt.c:__unflatten_device_tree
  - drivers/of/fdt.c:unflatten_dt_nodes
  - drivers/of/fdt.c:unflatten_dt_nodes
```
```
In drivers/of/fdt_address.c (ffffffe00003bc42)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/of/fdt_address.c:fdt_bus_default_count_cells
  - drivers/of/fdt_address.c:fdt_bus_default_count_cells
```
```
In drivers/of/address.c (ffffffe000726230)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/of/address.c:of_bus_isa_get_flags
  - drivers/of/address.c:of_pci_range_parser_one
  - drivers/of/address.c:of_bus_pci_get_flags
```
```
In drivers/of/irq.c (ffffffe000728248)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/of/irq.c:of_irq_parse_raw
  - drivers/of/irq.c:of_irq_parse_raw
```
```
In drivers/of/resolver.c (ffffffe000729bee)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/of/resolver.c:adjust_overlay_phandles
```
```
In drivers/of/overlay.c (ffffffe00072ad00)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In drivers/nvmem/core.c (ffffffe000737fd0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
```
```
In block/partitions/ldm.c (ffffffff814f965d)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
```
```
In lib/xz/xz_dec_bcj.c (ffffffff8154a589)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81698021)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff81698d14)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8169d502)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_recv
```
```
In drivers/scsi/scsi_error.c (ffffffff8172493b)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In drivers/scsi/scsi_scan.c (ffffffff8172ba90)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_trace.c (ffffffff81730767)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
```
In drivers/firmware/dmi_scan.c (ffffffff828fb35a)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
```
```
In drivers/nvmem/core.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In net/core/filter.c (ffffffff818f5abd)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_32
```
```
In net/ipv4/tcp_input.c (ffffffff81964d86)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In net/ipv6/calipso.c (ffffffff81a21d07)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
```
```
In lib/decompress_unlzo.c (ffffffff8290b986)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:parse_header
```
```
In lib/sha1.c (ffffffff81a547e1)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
```
```
In block/partitions/ldm.c (ffffffff814e9b6d)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
```
```
In lib/xz/xz_dec_bcj.c (ffffffff8153a869)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81675a11)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff81676704)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8167aef2)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_recv
```
```
In drivers/scsi/scsi_error.c (ffffffff816fdd6b)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In drivers/scsi/scsi_scan.c (ffffffff81704eb0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_trace.c (ffffffff81709b87)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
```
In drivers/firmware/dmi_scan.c (ffffffff828f2bf6)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
```
```
In drivers/nvmem/core.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In net/core/filter.c (ffffffff818af8ed)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_32
```
```
In net/ipv4/tcp_input.c (ffffffff8191e876)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In net/ipv6/calipso.c (ffffffff819deac7)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
```
```
In lib/decompress_unlzo.c (ffffffff82903cd4)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:parse_header
```
```
In lib/sha1.c (ffffffff81a118c1)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
```
```
In block/partitions/ldm.c (ffffffff814f56ed)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
```
```
In lib/xz/xz_dec_bcj.c (ffffffff815462c9)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816c6291)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff816c6f84)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff816cb772)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_recv
```
```
In drivers/scsi/scsi_error.c (ffffffff8176370b)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In drivers/scsi/scsi_scan.c (ffffffff8176a860)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_trace.c (ffffffff8176f537)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81855a55)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
```
In drivers/firmware/dmi_scan.c (ffffffff8291043b)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
```
```
In drivers/nvmem/core.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In net/core/filter.c (ffffffff81946aed)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_32
```
```
In net/netfilter/nf_conntrack_proto_tcp.c (ffffffff819a6166)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_tcp.c:tcp_in_window
```
```
In net/ipv4/tcp_input.c (ffffffff819cf556)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In net/ipv6/calipso.c (ffffffff81a8c787)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
```
```
In lib/decompress_unlzo.c (ffffffff829212d0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:parse_header
```
```
In lib/sha1.c (ffffffff81ac0bd1)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
```
```
In block/partitions/ldm.c (ffffffff8150e74d)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
```
```
In lib/xz/xz_dec_bcj.c (ffffffff815600f9)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816e0786)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff816e1474)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff816e5c42)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_recv
```
```
In drivers/scsi/scsi_error.c (ffffffff8177ed6b)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In drivers/scsi/scsi_scan.c (ffffffff81785fb0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_trace.c (ffffffff8178acd7)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81870b85)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
```
In drivers/firmware/dmi_scan.c (ffffffff82916e68)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
```
```
In drivers/nvmem/core.c (0)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
```
```
In net/core/filter.c (ffffffff819683fd)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_32
```
```
In net/ipv4/tcp_input.c (ffffffff819d90e6)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In net/ipv6/calipso.c (ffffffff81a99511)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_validate
```
```
In lib/decompress_unlzo.c (ffffffff82927cf4)
Location: include/uapi/linux/byteorder/little_endian.h:80
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:parse_header
```
```
In lib/sha1.c (ffffffff81acd0a1)
Location: include/uapi/linux/byteorder/little_endian.h:80
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
