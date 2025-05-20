# Function: <code>__put_unaligned_be32</code>

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
In kernel/debug/gdbstub.c (c043c99c)
Location: include/linux/unaligned/be_byteshift.h:29
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:gdb_cmd_query
```
```
In fs/ecryptfs/mmap.c (c06b38bc)
Location: include/linux/unaligned/be_byteshift.h:29
Inline: True
```
```
In fs/ecryptfs/crypto.c (c06b5ae8)
Location: include/linux/unaligned/be_byteshift.h:29
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In crypto/sha1_generic.c (c0773f94)
Location: include/linux/unaligned/be_byteshift.h:29
Inline: True
Inline callers:
  - crypto/sha1_generic.c:sha1_final
```
```
In crypto/sha512_generic.c (c07757ec)
Location: include/linux/unaligned/be_byteshift.h:29
Inline: True
Inline callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
  - crypto/sha512_generic.c:crypto_sha512_finup
```
```
In lib/crypto/sha256.c (c07e38cc)
Location: include/linux/unaligned/be_byteshift.h:29
Inline: True
Inline callers:
  - lib/crypto/sha256.c:__sha256_final
```
```
In lib/xz/xz_dec_bcj.c (c0807610)
Location: include/linux/unaligned/be_byteshift.h:29
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsi.c (c0a436f8)
Location: include/linux/unaligned/be_byteshift.h:29
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
```
```
In drivers/scsi/scsi_scan.c (c0a4f45c)
Location: include/linux/unaligned/be_byteshift.h:29
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_common.c (c0a56e5c)
Location: include/linux/unaligned/be_byteshift.h:29
Inline: True
```
```
In drivers/scsi/sd.c (c0a588fc)
Location: include/linux/unaligned/be_byteshift.h:29
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/scsi/sd_zbc.c (c0a5dcd0)
Location: include/linux/unaligned/be_byteshift.h:29
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/ata/libata-scsi.c (c0a72d6c)
Location: include/linux/unaligned/be_byteshift.h:29
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
```
```
In net/core/tso.c (c0d1dd94)
Location: include/linux/unaligned/be_byteshift.h:29
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
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
In fs/ecryptfs/mmap.c (ffffffe000364df0)
Location: include/linux/unaligned/be_byteshift.h:29
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffe000366ba2)
Location: include/linux/unaligned/be_byteshift.h:29
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In crypto/sha1_generic.c (ffffffe00040b444)
Location: include/linux/unaligned/be_byteshift.h:29
Inline: True
Inline callers:
  - crypto/sha1_generic.c:sha1_final
```
```
In crypto/sha512_generic.c (ffffffe00040c238)
Location: include/linux/unaligned/be_byteshift.h:29
Inline: True
Inline callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
  - crypto/sha512_generic.c:crypto_sha512_finup
```
```
In lib/crypto/sha256.c (ffffffe00046b1be)
Location: include/linux/unaligned/be_byteshift.h:29
Inline: True
Inline callers:
  - lib/crypto/sha256.c:__sha256_final
```
```
In lib/xz/xz_dec_bcj.c (ffffffe00048b910)
Location: include/linux/unaligned/be_byteshift.h:29
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/scsi/scsi.c (ffffffe0005d8510)
Location: include/linux/unaligned/be_byteshift.h:29
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
```
```
In drivers/scsi/scsi_scan.c (ffffffe0005e2680)
Location: include/linux/unaligned/be_byteshift.h:29
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/scsi_common.c (ffffffe0005e9502)
Location: include/linux/unaligned/be_byteshift.h:29
Inline: True
```
```
In drivers/scsi/sd.c (ffffffe0005eab6e)
Location: include/linux/unaligned/be_byteshift.h:29
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_sec_submit
```
```
In drivers/scsi/sd_zbc.c (ffffffe0005effc6)
Location: include/linux/unaligned/be_byteshift.h:29
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
```
```
In drivers/ata/libata-scsi.c (ffffffe000602c9a)
Location: include/linux/unaligned/be_byteshift.h:29
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b6
```
```
In drivers/mmc/host/mmc_spi.c (ffffffe00071b2ae)
Location: include/linux/unaligned/be_byteshift.h:29
Inline: True
Inline callers:
  - drivers/mmc/host/mmc_spi.c:mmc_spi_command_send
```
```
In net/core/tso.c (ffffffe0007834e6)
Location: include/linux/unaligned/be_byteshift.h:29
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
