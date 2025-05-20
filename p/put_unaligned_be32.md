# Function: <code>put_unaligned_be32</code>

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
In kernel/debug/gdbstub.c (ffffffff81131714)
Location: include/linux/unaligned/access_ok.h:57
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
```
```
In fs/ecryptfs/crypto.c (ffffffff81306354)
Location: include/linux/unaligned/access_ok.h:57
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_crypt_stat_flags
  - fs/ecryptfs/crypto.c:ecryptfs_write_header_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In crypto/sha1_generic.c (ffffffff813a5925)
Location: include/linux/unaligned/access_ok.h:57
Inline: True
Inline callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
```
```
In crypto/sha256_generic.c (ffffffff813a7a98)
Location: include/linux/unaligned/access_ok.h:57
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
```
In lib/xz/xz_dec_bcj.c (ffffffff814110d0)
Location: include/linux/unaligned/access_ok.h:57
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsi.c (ffffffff815a65f1)
Location: include/linux/unaligned/access_ok.h:57
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
```
```
In drivers/scsi/scsi_scan.c (ffffffff815b2e5d)
Location: include/linux/unaligned/access_ok.h:57
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/sd.c (ffffffff815bf020)
Location: include/linux/unaligned/access_ok.h:57
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_setup_write_same_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same_cmnd
  - drivers/scsi/sd.c:sd_setup_discard_cmnd
  - drivers/scsi/sd.c:sd_setup_discard_cmnd
  - drivers/scsi/sd.c:sd_setup_discard_cmnd
```
```
In drivers/ata/libata-scsi.c (ffffffff815d132f)
Location: include/linux/unaligned/access_ok.h:57
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In net/core/tso.c (ffffffff81734138)
Location: include/linux/unaligned/access_ok.h:57
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
```
```
In net/ipv4/ip_options.c (ffffffff8175ac1e)
Location: include/linux/unaligned/access_ok.h:57
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_compile
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
In kernel/debug/gdbstub.c (ffffffff81139eb8)
Location: include/linux/unaligned/access_ok.h:57
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
```
```
In fs/ecryptfs/crypto.c (ffffffff8133a918)
Location: include/linux/unaligned/access_ok.h:57
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In crypto/sha1_generic.c (ffffffff813e3090)
Location: include/linux/unaligned/access_ok.h:57
Inline: True
Inline callers:
  - crypto/sha1_generic.c:sha1_final
```
```
In crypto/sha256_generic.c (ffffffff813e509e)
Location: include/linux/unaligned/access_ok.h:57
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_final
```
```
In lib/xz/xz_dec_bcj.c (ffffffff81458e45)
Location: include/linux/unaligned/access_ok.h:57
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsi.c (ffffffff815fe881)
Location: include/linux/unaligned/access_ok.h:57
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
```
```
In drivers/scsi/scsi_common.c (ffffffff816097b9)
Location: include/linux/unaligned/access_ok.h:57
Inline: True
```
```
In drivers/scsi/scsi_scan.c (ffffffff8160b2c7)
Location: include/linux/unaligned/access_ok.h:57
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/sd.c (ffffffff81613d40)
Location: include/linux/unaligned/access_ok.h:57
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_pr_command
```
```
In drivers/ata/libata-scsi.c (ffffffff8162c125)
Location: include/linux/unaligned/access_ok.h:57
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In net/core/tso.c (ffffffff8179fc08)
Location: include/linux/unaligned/access_ok.h:57
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
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
In kernel/debug/gdbstub.c (ffffffff81143c4a)
Location: include/linux/unaligned/access_ok.h:57
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
```
```
In fs/ecryptfs/crypto.c (ffffffff813506b5)
Location: include/linux/unaligned/access_ok.h:57
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In crypto/sha1_generic.c (ffffffff813fc0b0)
Location: include/linux/unaligned/access_ok.h:57
Inline: True
Inline callers:
  - crypto/sha1_generic.c:sha1_final
```
```
In crypto/sha256_generic.c (ffffffff813fe0be)
Location: include/linux/unaligned/access_ok.h:57
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_final
```
```
In lib/xz/xz_dec_bcj.c (ffffffff81477805)
Location: include/linux/unaligned/access_ok.h:57
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsi.c (ffffffff8162dec1)
Location: include/linux/unaligned/access_ok.h:57
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
```
```
In drivers/scsi/scsi_common.c (ffffffff81639099)
Location: include/linux/unaligned/access_ok.h:57
Inline: True
```
```
In drivers/scsi/scsi_scan.c (ffffffff8163ab81)
Location: include/linux/unaligned/access_ok.h:57
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/sd.c (ffffffff816436a8)
Location: include/linux/unaligned/access_ok.h:57
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_pr_command
```
```
In drivers/scsi/sd_zbc.c (ffffffff816486ad)
Location: include/linux/unaligned/access_ok.h:57
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_report_cmnd
```
```
In drivers/ata/libata-scsi.c (ffffffff8165d275)
Location: include/linux/unaligned/access_ok.h:57
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In net/core/tso.c (ffffffff817ce5d8)
Location: include/linux/unaligned/access_ok.h:57
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
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
In kernel/debug/gdbstub.c (ffffffff81145771)
Location: include/linux/unaligned/access_ok.h:57
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
```
```
In fs/ecryptfs/crypto.c (ffffffff813651c7)
Location: include/linux/unaligned/access_ok.h:57
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In crypto/sha1_generic.c (ffffffff81409394)
Location: include/linux/unaligned/access_ok.h:57
Inline: True
Inline callers:
  - crypto/sha1_generic.c:sha1_final
```
```
In crypto/sha256_generic.c (ffffffff8140b3b2)
Location: include/linux/unaligned/access_ok.h:57
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_final
```
```
In lib/xz/xz_dec_bcj.c (ffffffff81480add)
Location: include/linux/unaligned/access_ok.h:57
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsi.c (ffffffff816432ed)
Location: include/linux/unaligned/access_ok.h:57
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
```
```
In drivers/scsi/scsi_common.c (ffffffff8164dcba)
Location: include/linux/unaligned/access_ok.h:57
Inline: True
```
```
In drivers/scsi/scsi_scan.c (ffffffff8164fadc)
Location: include/linux/unaligned/access_ok.h:57
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
```
```
In drivers/scsi/sd.c (ffffffff81657db8)
Location: include/linux/unaligned/access_ok.h:57
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/scsi/sd_zbc.c (ffffffff8165d007)
Location: include/linux/unaligned/access_ok.h:57
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_report_cmnd
```
```
In drivers/ata/libata-scsi.c (ffffffff81671ec1)
Location: include/linux/unaligned/access_ok.h:57
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In net/core/tso.c (ffffffff817eda88)
Location: include/linux/unaligned/access_ok.h:57
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
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
In kernel/debug/gdbstub.c (ffffffff811521a2)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
```
```
In fs/ecryptfs/crypto.c (ffffffff81389e97)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In crypto/sha1_generic.c (ffffffff81431db4)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - crypto/sha1_generic.c:sha1_final
```
```
In crypto/sha256_generic.c (ffffffff81433dd2)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_final
```
```
In lib/xz/xz_dec_bcj.c (ffffffff814bc913)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsi.c (ffffffff816ac3fd)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
```
```
In drivers/scsi/scsi_common.c (ffffffff816b6f8a)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
```
```
In drivers/scsi/scsi_scan.c (ffffffff816b90d4)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
```
```
In drivers/scsi/sd.c (ffffffff816c1278)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/scsi/sd_zbc.c (ffffffff816c6667)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_report_cmnd
```
```
In drivers/ata/libata-scsi.c (ffffffff816db501)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In net/core/tso.c (ffffffff81869cc8)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
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
In kernel/debug/gdbstub.c (ffffffff81160d07)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
```
```
In fs/ecryptfs/crypto.c (ffffffff813b8cec)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In crypto/sha1_generic.c (ffffffff81464914)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - crypto/sha1_generic.c:sha1_final
```
```
In crypto/sha256_generic.c (ffffffff81466946)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_final
```
```
In lib/xz/xz_dec_bcj.c (ffffffff814ef111)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsi.c (ffffffff816e894e)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
```
```
In drivers/scsi/scsi_common.c (ffffffff816f32c3)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
```
```
In drivers/scsi/scsi_scan.c (ffffffff816f5424)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
```
```
In drivers/scsi/sd.c (ffffffff816fd8c8)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/scsi/sd_zbc.c (ffffffff81702c3b)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_report_cmnd
```
```
In drivers/ata/libata-scsi.c (ffffffff81717849)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In net/core/tso.c (ffffffff818b99b1)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
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
In kernel/debug/gdbstub.c (ffffffff8116dad3)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
```
```
In fs/ecryptfs/crypto.c (ffffffff813d225c)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In crypto/sha1_generic.c (ffffffff81482584)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - crypto/sha1_generic.c:sha1_final
```
```
In crypto/sha256_generic.c (ffffffff814845b6)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_final
```
```
In lib/xz/xz_dec_bcj.c (ffffffff81502f99)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsi.c (ffffffff8170c44e)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
```
```
In drivers/scsi/scsi_scan.c (ffffffff81717d73)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
```
```
In drivers/scsi/scsi_common.c (ffffffff8171ec23)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81720498)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/scsi/sd_zbc.c (ffffffff817252ec)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/ata/libata-scsi.c (ffffffff81739e99)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In net/core/tso.c (ffffffff818e0771)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
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
In kernel/debug/gdbstub.c (ffffffff8117aab6)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:gdb_cmd_query
```
```
In fs/ecryptfs/crypto.c (ffffffff813fccbf)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In crypto/sha1_generic.c (ffffffff814b07c4)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - crypto/sha1_generic.c:sha1_final
```
```
In crypto/sha256_generic.c (ffffffff814b27e6)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_final
```
```
In lib/xz/xz_dec_bcj.c (ffffffff81531101)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsi.c (ffffffff81747b6e)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
```
```
In drivers/scsi/scsi_scan.c (ffffffff81753083)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_common.c (ffffffff8175a313)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff8175bb14)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/scsi/sd_zbc.c (ffffffff81760957)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/ata/libata-scsi.c (ffffffff81775eae)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In net/core/tso.c (ffffffff8192ee02)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
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
In kernel/debug/gdbstub.c (ffffffff81186946)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:gdb_cmd_query
```
```
In fs/ecryptfs/crypto.c (ffffffff81416b9f)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In crypto/sha1_generic.c (ffffffff814cb434)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - crypto/sha1_generic.c:sha1_final
```
```
In lib/crypto/sha256.c (ffffffff815313d2)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - lib/crypto/sha256.c:__sha256_final
```
```
In lib/xz/xz_dec_bcj.c (ffffffff81551f91)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsi.c (ffffffff8176bcbe)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
```
```
In drivers/scsi/scsi_scan.c (ffffffff81777303)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_common.c (ffffffff8177e223)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff8177fa24)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/scsi/sd_zbc.c (ffffffff817848f7)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/ata/libata-scsi.c (ffffffff81799e19)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In net/core/tso.c (ffffffff81961072)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
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
In kernel/debug/gdbstub.c (ffffffff8119ae79)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:gdb_cmd_query
```
```
In fs/ecryptfs/crypto.c (ffffffff81463e55)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_write_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_write_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_write_headers_virt
```
```
In crypto/sha1_generic.c (ffffffff8152a768)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - crypto/sha1_generic.c:sha1_final
```
```
In lib/crypto/sha256.c (ffffffff815955c7)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - lib/crypto/sha256.c:__sha256_final
```
```
In lib/xz/xz_dec_bcj.c (ffffffff815db66b)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/base/regmap/regmap.c (ffffffff817da415)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_format_32_be
```
```
In drivers/scsi/scsi.c (ffffffff8182df2e)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
```
```
In drivers/scsi/scsi_scan.c (ffffffff8183a213)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_common.c (ffffffff818418b3)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81843f6e)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_unmap_cmnd
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/scsi/sd_zbc.c (ffffffff818485d9)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/scsi/sr.c (ffffffff81849b16)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff8185c359)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In net/core/tso.c (ffffffff81a345ef)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
```
```
In net/mptcp/subflow.c (ffffffff81baf08f)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
```
```
In net/mptcp/options.c (ffffffff81bb172c)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
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
In kernel/debug/gdbstub.c (ffffffff81197fe9)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:gdb_cmd_query
```
```
In fs/ecryptfs/crypto.c (ffffffff8147f615)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_write_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_write_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_write_headers_virt
```
```
In crypto/sha1_generic.c (ffffffff81547718)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - crypto/sha1_generic.c:sha1_final
```
```
In lib/crypto/sha256.c (ffffffff815b108b)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256
```
```
In lib/xz/xz_dec_bcj.c (ffffffff815f92bf)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/base/regmap/regmap.c (ffffffff817ef1c5)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_format_32_be
```
```
In drivers/scsi/scsi.c (ffffffff8183ef6e)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
```
```
In drivers/scsi/scsi_scan.c (ffffffff8184abd3)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_common.c (ffffffff81851dd3)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81854219)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_unmap_cmnd
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/scsi/sd_zbc.c (ffffffff81858ac9)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/scsi/sr.c (ffffffff8185a06e)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff8186b449)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In net/core/tso.c (ffffffff81a368ea)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
```
```
In net/mptcp/subflow.c (ffffffff81bc1c5f)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
```
```
In net/mptcp/options.c (ffffffff81bc566c)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
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
In kernel/debug/gdbstub.c (ffffffff81198e31)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:gdb_cmd_query
```
```
In fs/ecryptfs/crypto.c (ffffffff8148627d)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In crypto/sha1_generic.c (ffffffff8154fdd8)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - crypto/sha1_generic.c:sha1_final
```
```
In lib/crypto/sha256.c (ffffffff815bbe9b)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256
```
```
In lib/xz/xz_dec_bcj.c (ffffffff815dbb82)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/base/regmap/regmap.c (ffffffff817d3a65)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_format_32_be
```
```
In drivers/scsi/scsi.c (ffffffff8182217e)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
```
```
In drivers/scsi/scsi_scan.c (ffffffff8182df34)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_common.c (ffffffff81834e4b)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81837c6c)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_unmap_cmnd
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/scsi/sd_zbc.c (ffffffff8183ba4b)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/scsi/sr.c (ffffffff8183d078)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff8184dd59)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In net/core/tso.c (ffffffff81a1da6b)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b0667d)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
```
```
In net/mptcp/subflow.c (ffffffff81bb256a)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
```
```
In net/mptcp/options.c (ffffffff81bb60e7)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
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
In kernel/debug/gdbstub.c (ffffffff811c2bf7)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:gdb_cmd_query
```
```
In fs/ecryptfs/crypto.c (ffffffff814dda0d)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In crypto/sha1_generic.c (ffffffff815b0737)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - crypto/sha1_generic.c:sha1_final
```
```
In lib/crypto/sha256.c (ffffffff81622cdc)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256
```
```
In lib/xz/xz_dec_bcj.c (ffffffff81647672)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/base/regmap/regmap.c (ffffffff8185ee50)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_format_32_be
```
```
In drivers/scsi/scsi.c (ffffffff818acabe)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
```
```
In drivers/scsi/scsi_scan.c (ffffffff818b9d04)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_common.c (ffffffff818c11db)
Location: include/asm-generic/unaligned.h:75
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff818c503e)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/scsi/sd_zbc.c (ffffffff818c811b)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/scsi/sr.c (ffffffff818c9a0f)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff818de697)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In net/core/tso.c (ffffffff81ad14fb)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81bc93bd)
Location: include/asm-generic/unaligned.h:75
Inline: True
```
```
In net/mptcp/subflow.c (ffffffff81c80820)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
```
```
In net/mptcp/options.c (ffffffff81c84ea3)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
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
In kernel/debug/gdbstub.c (ffffffff811f63cf)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:gdb_cmd_query
```
```
In fs/ecryptfs/crypto.c (ffffffff8156bad9)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In crypto/sha1_generic.c (ffffffff816590a6)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - crypto/sha1_generic.c:sha1_final
```
```
In lib/crypto/sha256.c (ffffffff816f2898)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256
  - lib/crypto/sha256.c:sha224_final
```
```
In lib/xz/xz_dec_bcj.c (ffffffff8175d90f)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/base/regmap/regmap.c (ffffffff819a67f0)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_format_32_be
```
```
In drivers/scsi/scsi.c (ffffffff819f786f)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
```
```
In drivers/scsi/scsi_scan.c (ffffffff81a056a7)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_common.c (ffffffff81a0d831)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - drivers/scsi/scsi_common.c:scsi_set_sense_information
```
```
In drivers/scsi/sd.c (ffffffff81a11cb9)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/scsi/sd_zbc.c (ffffffff81a14f82)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/scsi/sr.c (ffffffff81a16d6a)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff81a2fa30)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In net/core/tso.c (ffffffff81c4edd8)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81d5ea4c)
Location: include/asm-generic/unaligned.h:75
Inline: True
```
```
In net/mptcp/subflow.c (ffffffff81e26490)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
```
```
In net/mptcp/options.c (ffffffff81e2af0a)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
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
In kernel/debug/gdbstub.c (ffffffff8123d590)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:gdb_cmd_query
```
```
In fs/ecryptfs/crypto.c (ffffffff8160fb09)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In crypto/sha1_generic.c (ffffffff81713526)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - crypto/sha1_generic.c:sha1_final
```
```
In lib/crypto/sha256.c (ffffffff817e46a8)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256
  - lib/crypto/sha256.c:sha224_final
```
```
In lib/xz/xz_dec_bcj.c (ffffffff8188ae3f)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/base/regmap/regmap.c (ffffffff81b190a0)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_format_32_be
```
```
In drivers/scsi/scsi.c (ffffffff81b750cf)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
```
```
In drivers/scsi/scsi_scan.c (ffffffff81b843b4)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_common.c (ffffffff81b8d711)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - drivers/scsi/scsi_common.c:scsi_set_sense_information
```
```
In drivers/scsi/sd.c (ffffffff81b91f84)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/scsi/sd_zbc.c (ffffffff81b95bd2)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/scsi/sr.c (ffffffff81b97bca)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff81bb2f74)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In net/core/tso.c (ffffffff81e03e59)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f29118)
Location: include/asm-generic/unaligned.h:75
Inline: True
```
```
In net/mptcp/subflow.c (ffffffff81fff5b2)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
```
```
In net/mptcp/options.c (ffffffff820030ba)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
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
In kernel/debug/gdbstub.c (ffffffff812545c8)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:gdb_cmd_query
```
```
In fs/ecryptfs/crypto.c (ffffffff81647999)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In crypto/sha1_generic.c (ffffffff8174e673)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
```
```
In lib/crypto/sha256.c (ffffffff818247d4)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256
  - lib/crypto/sha256.c:sha224_final
```
```
In lib/xz/xz_dec_bcj.c (ffffffff818cd2cc)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/base/regmap/regmap.c (ffffffff81b67d90)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_format_32_be
```
```
In drivers/scsi/scsi.c (ffffffff81bc8988)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
```
```
In drivers/scsi/scsi_scan.c (ffffffff81bd812f)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_common.c (ffffffff81be1861)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - drivers/scsi/scsi_common.c:scsi_set_sense_information
```
```
In drivers/scsi/sd.c (ffffffff81be845e)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/scsi/sd_zbc.c (ffffffff81bec19e)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/scsi/sr.c (ffffffff81bee149)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff81c0a58d)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In net/core/tso.c (ffffffff81e76649)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f88dac)
Location: include/asm-generic/unaligned.h:75
Inline: True
```
```
In net/mptcp/subflow.c (ffffffff8207b6c1)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
```
```
In net/mptcp/options.c (ffffffff8207f24a)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
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
In kernel/debug/gdbstub.c (ffffffff8126e438)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:gdb_cmd_query
```
```
In fs/ecryptfs/crypto.c (ffffffff81680e49)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In crypto/sha1_generic.c (ffffffff817902c3)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
```
```
In lib/crypto/sha256.c (ffffffff8186a814)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256
  - lib/crypto/sha256.c:sha224_final
```
```
In lib/xz/xz_dec_bcj.c (ffffffff8191ee6e)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/base/regmap/regmap.c (ffffffff81bbbae0)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_format_32_be
```
```
In drivers/scsi/scsi.c (ffffffff81c1d878)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
```
```
In drivers/scsi/scsi_scan.c (ffffffff81c2cdff)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_common.c (ffffffff81c36891)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - drivers/scsi/scsi_common.c:scsi_set_sense_information
```
```
In drivers/scsi/sd.c (ffffffff81c3d9cb)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/scsi/sd_zbc.c (ffffffff81c4185b)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/scsi/sr.c (ffffffff81c43856)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff81c5f642)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In net/core/tso.c (ffffffff81f36609)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8205039c)
Location: include/asm-generic/unaligned.h:75
Inline: True
```
```
In net/mptcp/subflow.c (ffffffff82150c92)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
```
```
In net/mptcp/options.c (ffffffff8215473a)
Location: include/asm-generic/unaligned.h:75
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
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
In kernel/debug/gdbstub.c (ffff8000101fb188)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:int_to_threadref
```
```
In fs/ecryptfs/crypto.c (ffff8000104f82ac)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_header_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_crypt_stat_flags
```
```
In crypto/sha1_generic.c (ffff8000105c73d8)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
```
```
In lib/crypto/sha256.c (ffff80001063d490)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - lib/crypto/sha256.c:__sha256_final
```
```
In lib/xz/xz_dec_bcj.c (ffff80001065dcf0)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsi.c (ffff80001096dca4)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
```
```
In drivers/scsi/scsi_scan.c (ffff80001097b670)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_common.c (ffff8000109848b8)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
```
```
In drivers/scsi/sd.c (ffff80001098ab68)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/scsi/sd_zbc.c (ffff80001098b0f4)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
```
```
In drivers/ata/libata-scsi.c (ffff8000109a4334)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In net/core/tso.c (ffff800010c048f4)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
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
In kernel/debug/gdbstub.c (c043c99c)
Location: include/linux/unaligned/be_byteshift.h:61
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:gdb_cmd_query
```
```
In fs/ecryptfs/crypto.c (c06b5ae8)
Location: include/linux/unaligned/be_byteshift.h:61
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In crypto/sha1_generic.c (c0773f94)
Location: include/linux/unaligned/be_byteshift.h:61
Inline: True
Inline callers:
  - crypto/sha1_generic.c:sha1_final
```
```
In lib/crypto/sha256.c (c07e38cc)
Location: include/linux/unaligned/be_byteshift.h:61
Inline: True
Inline callers:
  - lib/crypto/sha256.c:__sha256_final
```
```
In lib/xz/xz_dec_bcj.c (c0807610)
Location: include/linux/unaligned/be_byteshift.h:61
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsi.c (c0a436f8)
Location: include/linux/unaligned/be_byteshift.h:61
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
```
```
In drivers/scsi/scsi_scan.c (c0a4f45c)
Location: include/linux/unaligned/be_byteshift.h:61
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_common.c (c0a56e5c)
Location: include/linux/unaligned/be_byteshift.h:61
Inline: True
```
```
In drivers/scsi/sd.c (c0a588fc)
Location: include/linux/unaligned/be_byteshift.h:61
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/scsi/sd_zbc.c (c0a5d418)
Location: include/linux/unaligned/be_byteshift.h:61
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/ata/libata-scsi.c (c0a72d6c)
Location: include/linux/unaligned/be_byteshift.h:61
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
```
```
In net/core/tso.c (c0d1dd94)
Location: include/linux/unaligned/be_byteshift.h:61
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
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
In kernel/debug/gdbstub.c (c000000000274e08)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:gdb_cmd_query
```
```
In fs/ecryptfs/crypto.c (c00000000063a098)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In crypto/sha1_generic.c (c000000000750f80)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - crypto/sha1_generic.c:sha1_final
```
```
In lib/crypto/sha256.c (c0000000007e4e74)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - lib/crypto/sha256.c:__sha256_final
```
```
In lib/xz/xz_dec_bcj.c (c00000000080ff00)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsi.c (c000000000a270ac)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
```
```
In drivers/scsi/scsi_scan.c (c000000000a36910)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_common.c (c000000000a41700)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
```
```
In drivers/scsi/sd.c (c000000000a45aac)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/scsi/sd_zbc.c (c000000000a4bc5c)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/ata/libata-scsi.c (c000000000a697bc)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In net/core/tso.c (c000000000cee874)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
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
In fs/ecryptfs/crypto.c (ffffffe000366ba2)
Location: include/linux/unaligned/be_byteshift.h:61
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In crypto/sha1_generic.c (ffffffe00040b444)
Location: include/linux/unaligned/be_byteshift.h:61
Inline: True
Inline callers:
  - crypto/sha1_generic.c:sha1_final
```
```
In lib/crypto/sha256.c (ffffffe00046b1be)
Location: include/linux/unaligned/be_byteshift.h:61
Inline: True
Inline callers:
  - lib/crypto/sha256.c:__sha256_final
```
```
In lib/xz/xz_dec_bcj.c (ffffffe00048b910)
Location: include/linux/unaligned/be_byteshift.h:61
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsi.c (ffffffe0005d8510)
Location: include/linux/unaligned/be_byteshift.h:61
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
```
```
In drivers/scsi/scsi_scan.c (ffffffe0005e2680)
Location: include/linux/unaligned/be_byteshift.h:61
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_common.c (ffffffe0005e9502)
Location: include/linux/unaligned/be_byteshift.h:61
Inline: True
```
```
In drivers/scsi/sd.c (ffffffe0005eabfc)
Location: include/linux/unaligned/be_byteshift.h:61
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/scsi/sd_zbc.c (ffffffe0005ef48e)
Location: include/linux/unaligned/be_byteshift.h:61
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/ata/libata-scsi.c (ffffffe000602d52)
Location: include/linux/unaligned/be_byteshift.h:61
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
```
```
In drivers/mmc/host/mmc_spi.c (ffffffe00071b2ae)
Location: include/linux/unaligned/be_byteshift.h:61
Inline: True
Inline callers:
  - drivers/mmc/host/mmc_spi.c:mmc_spi_command_send
```
```
In net/core/tso.c (ffffffe0007834e6)
Location: include/linux/unaligned/be_byteshift.h:61
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
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
In kernel/debug/gdbstub.c (ffffffff8117ef66)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:gdb_cmd_query
```
```
In fs/ecryptfs/crypto.c (ffffffff8140f17f)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In crypto/sha1_generic.c (ffffffff814c3a14)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - crypto/sha1_generic.c:sha1_final
```
```
In lib/crypto/sha256.c (ffffffff815299b2)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - lib/crypto/sha256.c:__sha256_final
```
```
In lib/xz/xz_dec_bcj.c (ffffffff8154a571)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsi.c (ffffffff817203ae)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
```
```
In drivers/scsi/scsi_scan.c (ffffffff8172b9f3)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_common.c (ffffffff81732913)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81734114)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/scsi/sd_zbc.c (ffffffff81738fe7)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/ata/libata-scsi.c (ffffffff8175ef09)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In net/core/tso.c (ffffffff81901042)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
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
In kernel/debug/gdbstub.c (ffffffff811720b6)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:gdb_cmd_query
```
```
In fs/ecryptfs/crypto.c (ffffffff813ffbff)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In crypto/sha1_generic.c (ffffffff814b4434)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - crypto/sha1_generic.c:sha1_final
```
```
In lib/crypto/sha256.c (ffffffff81519c92)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - lib/crypto/sha256.c:__sha256_final
```
```
In lib/xz/xz_dec_bcj.c (ffffffff8153a851)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsi.c (ffffffff816f97de)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
```
```
In drivers/scsi/scsi_scan.c (ffffffff81704e13)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_common.c (ffffffff8170bd33)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81715db4)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/scsi/sd_zbc.c (ffffffff8171ac87)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/ata/libata-scsi.c (ffffffff8173ed9d)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In net/core/tso.c (ffffffff818bae72)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
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
In kernel/debug/gdbstub.c (ffffffff8117cd36)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:gdb_cmd_query
```
```
In fs/ecryptfs/crypto.c (ffffffff8140c4ff)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In crypto/sha1_generic.c (ffffffff814bfaa4)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - crypto/sha1_generic.c:sha1_final
```
```
In lib/crypto/sha256.c (ffffffff81525a42)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - lib/crypto/sha256.c:__sha256_final
```
```
In lib/xz/xz_dec_bcj.c (ffffffff815462b1)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsi.c (ffffffff8175f17e)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
```
```
In drivers/scsi/scsi_scan.c (ffffffff8176a7c3)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_common.c (ffffffff817716e3)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff817748a4)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/scsi/sd_zbc.c (ffffffff81779777)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/ata/libata-scsi.c (ffffffff8178ec99)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In net/core/tso.c (ffffffff81952072)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
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
In kernel/debug/gdbstub.c (ffffffff8118a656)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:gdb_cmd_query
```
```
In fs/ecryptfs/crypto.c (ffffffff8142217f)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In crypto/sha1_generic.c (ffffffff814d8574)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - crypto/sha1_generic.c:sha1_final
```
```
In lib/crypto/sha256.c (ffffffff8153f3c2)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - lib/crypto/sha256.c:__sha256_final
```
```
In lib/xz/xz_dec_bcj.c (ffffffff815600e1)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsi.c (ffffffff8177a7de)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
```
```
In drivers/scsi/scsi_scan.c (ffffffff81785f13)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_common.c (ffffffff8178ce83)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff8178e684)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/scsi/sd_zbc.c (ffffffff817935a7)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/ata/libata-scsi.c (ffffffff817a8dc9)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In net/core/tso.c (ffffffff81973ab2)
Location: include/linux/unaligned/access_ok.h:58
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
```
</details>
</li>
</ul>

## Differences
