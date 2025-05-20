# Function: <code>__fswab32</code>

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
In init/do_mounts_rd.c (ffffffff81f5ab7d)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - init/do_mounts_rd.c:rd_load_image
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff81059236)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip1_apic_icr_write
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff81067707)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calgary_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calgary_dump_error_regs
  - arch/x86/kernel/pci-calgary_64.c:calgary_watchdog
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
```
```
In kernel/module_signing.c (ffffffff8110ac7e)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - kernel/module_signing.c:mod_verify_sig
```
```
In kernel/debug/gdbstub.c (ffffffff81131714)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
```
```
In kernel/trace/blktrace.c (ffffffff8115b318)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_log_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
```
```
In kernel/bpf/core.c (ffffffff81172543)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - kernel/bpf/core.c:__bpf_prog_run
  - kernel/bpf/core.c:__bpf_prog_run
```
```
In mm/swapfile.c (ffffffff811d6722)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
```
```
In fs/ext4/super.c (ffffffff81322c0f)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
```
```
In fs/jbd2/commit.c (ffffffff812e9b02)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff812eb8d5)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jbd2_journal_recover
```
```
In fs/jbd2/revoke.c (ffffffff812ed691)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff812ef02a)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_clear_features
  - fs/jbd2/journal.c:jbd2_journal_clear_features
  - fs/jbd2/journal.c:jbd2_journal_clear_features
  - fs/jbd2/journal.c:jbd2_superblock_csum
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
```
```
In fs/ecryptfs/crypto.c (ffffffff8130505c)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_validate_marker
  - fs/ecryptfs/crypto.c:ecryptfs_write_crypt_stat_flags
  - fs/ecryptfs/crypto.c:ecryptfs_write_header_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In fs/ecryptfs/miscdev.c (ffffffff8130bf0e)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
```
In security/keys/trusted.c (ffffffff813369fc)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - security/keys/trusted.c:oiap
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
```
```
In security/smack/smackfs.c (0)
Location: include/uapi/linux/swab.h:57
Inline: True
```
```
In security/apparmor/match.c (ffffffff8137916d)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/integrity/digsig_asymmetric.c (ffffffff813967ec)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In crypto/algapi.c (ffffffff8139d872)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_inc
  - crypto/algapi.c:crypto_inc
```
```
In crypto/sha1_generic.c (ffffffff813a5925)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
```
```
In crypto/sha256_generic.c (ffffffff813a5e58)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:crypto_sha256_finup
```
```
In block/partitions/amiga.c (ffffffff813ce5c2)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff813ceafd)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff813cf3d3)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff813cfc04)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff813d0258)
Location: include/uapi/linux/swab.h:57
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
In block/partitions/sgi.c (ffffffff813d33b3)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff813d3623)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/sysv68.c (ffffffff813d4cbc)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In block/t10-pi.c (ffffffff813e88b7)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_verify
  - block/t10-pi.c:t10_pi_generate
```
```
In lib/decompress_unlzo.c (ffffffff81f9dc1f)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - lib/decompress_unlzo.c:parse_header
  - lib/decompress_unlzo.c:unlzo
  - lib/decompress_unlzo.c:unlzo
```
```
In lib/sha1.c (ffffffff813f057b)
Location: include/uapi/linux/swab.h:57
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
In lib/vsprintf.c (ffffffff813f4c38)
Location: include/uapi/linux/swab.h:57
Inline: True
```
```
In lib/iomap.c (ffffffff81402896)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - lib/iomap.c:ioread32be
  - lib/iomap.c:ioread32be
```
```
In lib/crc32.c (ffffffff81406b01)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - lib/crc32.c:crc32_be
  - lib/crc32.c:crc32_be
```
```
In lib/xz/xz_dec_bcj.c (ffffffff81411098)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
  - lib/xz/xz_dec_bcj.c:bcj_apply
```
```
In drivers/pnp/support.c (ffffffff814b9fb5)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - drivers/pnp/support.c:pnp_eisa_id_to_string
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/uapi/linux/swab.h:57
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/uapi/linux/swab.h:57
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/uapi/linux/swab.h:57
Inline: True
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff815239ac)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
  - drivers/char/tpm/tpm-interface.c:tpm_do_selftest
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read_dev
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff81525191)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-sysfs.c:caps_show
  - drivers/char/tpm/tpm-sysfs.c:pcrs_show
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81525ea5)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff81528bfa)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_recv
```
```
In drivers/lightnvm/sysblk.c (ffffffff81544828)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - drivers/lightnvm/sysblk.c:nvm_scan_block
  - drivers/lightnvm/sysblk.c:nvm_scan_block
  - drivers/lightnvm/sysblk.c:nvm_sysblk_to_cpu
  - drivers/lightnvm/sysblk.c:nvm_sysblk_to_cpu
  - drivers/lightnvm/sysblk.c:nvm_cpu_to_sysblk
  - drivers/lightnvm/sysblk.c:nvm_cpu_to_sysblk
  - drivers/lightnvm/sysblk.c:nvm_update_sysblock
```
```
In drivers/base/regmap/regmap.c (ffffffff81562605)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_32_be_inplace
  - drivers/base/regmap/regmap.c:regmap_parse_32_be
  - drivers/base/regmap/regmap.c:regmap_format_32_be
```
```
In drivers/block/virtio_blk.c (0)
Location: include/uapi/linux/swab.h:57
Inline: True
```
```
In drivers/misc/bmp085.c (ffffffff81579226)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - drivers/misc/bmp085.c:show_pressure
```
```
In drivers/scsi/scsi.c (ffffffff815a65f1)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_report_opcode
```
```
In drivers/scsi/scsi_scan.c (ffffffff815b2e5d)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
```
```
In drivers/scsi/sd.c (ffffffff815bcda1)
Location: include/uapi/linux/swab.h:57
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
  - drivers/scsi/sd.c:sd_setup_write_same_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same_cmnd
  - drivers/scsi/sd.c:sd_setup_discard_cmnd
  - drivers/scsi/sd.c:sd_setup_discard_cmnd
  - drivers/scsi/sd.c:sd_setup_discard_cmnd
```
```
In drivers/scsi/sd_dif.c (ffffffff815bf8cf)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_prepare
  - drivers/scsi/sd_dif.c:sd_dif_prepare
  - drivers/scsi/sd_dif.c:sd_dif_complete
  - drivers/scsi/sd_dif.c:sd_dif_complete
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/uapi/linux/swab.h:57
Inline: True
```
```
In drivers/net/virtio_net.c (0)
Location: include/uapi/linux/swab.h:57
Inline: True
```
```
In drivers/net/slip/slhc.c (ffffffff815f93ca)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - drivers/net/slip/slhc.c:slhc_compress
  - drivers/net/slip/slhc.c:slhc_compress
  - drivers/net/slip/slhc.c:slhc_compress
  - drivers/net/slip/slhc.c:slhc_compress
```
```
In drivers/cdrom/cdrom.c (ffffffff81600149)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_get_last_written
  - drivers/cdrom/cdrom.c:cdrom_get_last_written
  - drivers/cdrom/cdrom.c:cdrom_get_last_written
  - drivers/cdrom/cdrom.c:cdrom_get_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff816c5fb0)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_send_csd
  - drivers/mmc/core/mmc_ops.c:mmc_send_cid
```
```
In drivers/mmc/core/sd.c (ffffffff816c7284)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_setup_card
```
```
In drivers/mmc/core/sd_ops.c (ffffffff816c8623)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
```
```
In drivers/firmware/dmi_scan.c (ffffffff81fb572e)
Location: include/uapi/linux/swab.h:57
Inline: True
```
```
In net/core/flow_dissector.c (ffffffff8171212c)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/utils.c (ffffffff8172fcaf)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - net/core/utils.c:in_aton
```
```
In net/core/filter.c (ffffffff81731b49)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_key
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/tso.c (ffffffff81734138)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_start
```
```
In net/ipv4/ip_forward.c (ffffffff8175a8d8)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff8175ac1e)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_build
```
```
In net/ipv4/ip_output.c (ffffffff8175cfa1)
Location: include/uapi/linux/swab.h:57
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff8175fe55)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp.c (ffffffff8176787c)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/tcp_input.c (ffffffff8176bd1d)
Location: include/uapi/linux/swab.h:57
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
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_output.c (ffffffff8177479b)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_options_write
  - net/ipv4/tcp_output.c:tcp_options_write
  - net/ipv4/tcp_output.c:tcp_options_write
  - net/ipv4/tcp_output.c:tcp_options_write
  - net/ipv4/tcp_output.c:tcp_options_write
  - net/ipv4/tcp_output.c:tcp_options_write
  - net/ipv4/tcp_output.c:tcp_options_write
  - net/ipv4/tcp_output.c:tcp_options_write
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177aec2)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/uapi/linux/swab.h:57
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff8178333c)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8178af9d)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffff8178d436)
Location: include/uapi/linux/swab.h:57
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff8178ec3f)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_unreach
```
```
In net/ipv4/devinet.c (ffffffff8178fec6)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/af_inet.c (ffffffff81793c38)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffffffff817957e6)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_show
  - net/ipv4/igmp.c:igmp_mcf_seq_show
```
```
In net/ipv4/fib_frontend.c (ffffffff8179b575)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
```
In net/ipv4/fib_trie.c (ffffffff8179ebdd)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_trie_seq_show
  - net/ipv4/fib_trie.c:fib_trie_seq_show
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_dump
```
```
In net/ipv4/fib_rules.c (ffffffff817a6d04)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/syncookies.c (ffffffff817aaf87)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/inet_lro.c (ffffffff817aba44)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - net/ipv4/inet_lro.c:lro_tcp_ip_check
  - net/ipv4/inet_lro.c:lro_tcp_ip_check
```
```
In net/ipv4/cipso_ipv4.c (ffffffff817ad4f6)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
```
```
In net/ipv4/xfrm4_policy.c (ffffffff817af965)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:_decode_session4
```
```
In net/ipv4/xfrm4_state.c (ffffffff817afcff)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - net/ipv4/xfrm4_state.c:__xfrm4_init_tempsel
  - net/ipv4/xfrm4_state.c:__xfrm4_init_tempsel
```
```
In net/ipv4/xfrm4_output.c (ffffffff817b0286)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b1e0b)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
```
```
In net/xfrm/xfrm_state.c (ffffffff817b7bb8)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_helper_sainfo
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_state_walk
  - net/xfrm/xfrm_state.c:xfrm_state_walk
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/xfrm/xfrm_input.c (ffffffff817bb90e)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_replay.c (ffffffff817bd1ed)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_seqhi
  - net/xfrm/xfrm_replay.c:xfrm_replay_recheck_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
```
```
In net/ipv6/ip6_output.c (ffffffff817c4d8d)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/addrconf.c (ffffffff817d0907)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/route.c (ffffffff817d6f4a)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/uapi/linux/swab.h:57
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff817dc2fa)
Location: include/uapi/linux/swab.h:57
Inline: True
```
```
In net/ipv6/ndisc.c (ffffffff817df5e1)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/udp.c (0)
Location: include/uapi/linux/swab.h:57
Inline: True
```
```
In net/ipv6/raw.c (ffffffff817e6a4a)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
```
```
In net/ipv6/icmp.c (ffffffff817e7b83)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (0)
Location: include/uapi/linux/swab.h:57
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817eec96)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_pseudoheader
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff817f2e0f)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff817f6171)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
  - net/ipv6/ip6_flowlabel.c:fl_lookup
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
```
```
In net/ipv6/xfrm6_state.c (ffffffff817fca23)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:__xfrm6_init_tempsel
  - net/ipv6/xfrm6_state.c:__xfrm6_init_tempsel
```
```
In net/ipv6/fib6_rules.c (ffffffff817fe6c2)
Location: include/uapi/linux/swab.h:57
Inline: True
```
```
In net/ipv6/syncookies.c (ffffffff817ff0c7)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/output_core.c (ffffffff818008a2)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
  - net/ipv6/output_core.c:ipv6_select_ident
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff8180d019)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_audit_addr
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_audit_addr
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81817b15)
Location: include/uapi/linux/swab.h:57
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_ipv6_magic
```
</details>
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/smp.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In virt/kvm/arm/mmio.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In arch/arm64/kvm/hyp/vgic-v2-cpuif-proxy.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/firmware/efi/libstub/fdt.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In lib/fdt.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In lib/fdt_rw.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In lib/fdt_sw.c (ffff80001144048c)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - lib/fdt_sw.c:fdt_create_with_flags
```
```
In kernel/irq/generic-chip.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In kernel/module_signing.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In kernel/module_signature.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In kernel/debug/gdbstub.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In kernel/bpf/lpm_trie.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In fs/jbd2/commit.c (ffff8000104ce494)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In fs/jbd2/revoke.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In fs/jbd2/journal.c (ffff8000104d6318)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In fs/ecryptfs/crypto.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In security/keys/dh.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In security/keys/trusted.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In security/apparmor/match.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In security/integrity/digsig_asymmetric.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In security/integrity/ima/ima_modsig.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In crypto/algapi.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In crypto/sha1_generic.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In crypto/drbg.c (ffff8000105d206c)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_ctr_df
```
```
In block/partitions/amiga.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In block/partitions/atari.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In block/partitions/aix.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In block/partitions/mac.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In block/partitions/ldm.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In block/partitions/sgi.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In block/partitions/sun.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In block/partitions/sysv68.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In block/t10-pi.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In block/sed-opal.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In lib/crypto/sha256.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In lib/crc32.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In lib/xz/xz_dec_bcj.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/irqchip/irq-ls-scfg-msi.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/bus/brcmstb_gisb.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/bus/fsl-mc/fsl-mc-bus.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/pinctrl/devicetree.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/pinctrl/pinctrl-rockchip.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/pinctrl/pinctrl-single.c (ffff80001069d1a0)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
```
```
In drivers/pinctrl/freescale/pinctrl-imx.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/pinctrl/freescale/pinctrl-scu.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/gpio/gpio-mmio.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/pci/of.c (ffff8000106f9ab8)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/pci/of.c:of_irq_parse_and_map_pci
```
```
In drivers/pci/quirks.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/pnp/support.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/clk/clk-divider.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/clk/clk-gate.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/clk/clk-multiplier.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/clk/clk-mux.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/clk/clk-fractional-divider.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/clk/clk-qoriq.c (ffff8000107c8718)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/clk/clk-qoriq.c:mux_set_parent
```
```
In drivers/soc/fsl/qbman/bman_ccsr.c (ffff80001080f96c)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/bman_ccsr.c:fsl_bman_probe
```
```
In drivers/soc/fsl/qbman/qman_ccsr.c (ffff8000108100e8)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman_ccsr.c:qm_set_memory
```
```
In drivers/soc/fsl/qbman/bman.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/soc/fsl/qbman/qman.c (ffff800010816ef0)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman.c:qman_shutdown_fq
  - drivers/soc/fsl/qbman/qman.c:_qm_dqrr_consume_and_match
  - drivers/soc/fsl/qbman/qman.c:_qm_mr_consume_and_match_verb
  - drivers/soc/fsl/qbman/qman.c:qman_enqueue
  - drivers/soc/fsl/qbman/qman.c:qman_query_fq_np
  - drivers/soc/fsl/qbman/qman.c:qman_query_fq
  - drivers/soc/fsl/qbman/qman.c:qman_oos_fq
  - drivers/soc/fsl/qbman/qman.c:qman_retire_fq
  - drivers/soc/fsl/qbman/qman.c:qman_retire_fq
  - drivers/soc/fsl/qbman/qman.c:qman_schedule_fq
  - drivers/soc/fsl/qbman/qman.c:qman_init_fq
  - drivers/soc/fsl/qbman/qman.c:qman_p_poll_dqrr
  - drivers/soc/fsl/qbman/qman.c:qm_mr_process_task
  - drivers/soc/fsl/qbman/qman.c:qman_create_portal
  - drivers/soc/fsl/qbman/qman.c:qman_create_portal
  - drivers/soc/fsl/qbman/qman.c:drain_mr_fqrni
  - drivers/soc/fsl/qbman/qman.c:portal_isr
  - drivers/soc/fsl/qbman/qman.c:portal_isr
  - drivers/soc/fsl/qbman/qman.c:qman_portal_set_iperiod
  - drivers/soc/fsl/qbman/qman.c:qman_dqrr_set_ithresh
```
```
In drivers/soc/fsl/qbman/dpaa_sys.c (ffff800010817b10)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/dpaa_sys.c:qbman_init_private_mem
  - drivers/soc/fsl/qbman/dpaa_sys.c:qbman_init_private_mem
```
```
In drivers/soc/fsl/guts.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/soc/sunxi/sunxi_sram.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/tty/serial/earlycon.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/tty/serial/8250/8250_dwlib.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/tty/serial/8250/8250_early.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/tty/serial/8250/8250_dw.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/char/tpm/tpm-dev-common.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/char/tpm/tpm-interface.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/char/tpm/tpm1-cmd.c (ffff8000108ba750)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In drivers/char/tpm/tpm2-cmd.c (ffff8000108bcfe4)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (ffff8000108bd718)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm-sysfs.c (ffff8000108bea00)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
```
In drivers/char/tpm/eventlog/of.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/char/tpm/tpm_crb.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/iommu/of_iommu.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/iommu/arm-smmu.c (ffff8000108cef8c)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu.c:__arm_smmu_get_pci_sid
```
```
In drivers/iommu/virtio-iommu.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/misc/vexpress-syscfg.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/scsi/scsi.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/scsi/scsi_scan.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/scsi/scsi_trace.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/scsi/scsi_common.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/scsi/sd_zbc.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/spi/spi-fsl-spi.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/net/ethernet/freescale/fec_main.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/net/ethernet/freescale/xgmac_mdio.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/net/ethernet/freescale/fman/fman.c (ffff8000109f05f4)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/fman.c:fman_probe
  - drivers/net/ethernet/freescale/fman/fman.c:fman_probe
  - drivers/net/ethernet/freescale/fman/fman.c:fman_probe
  - drivers/net/ethernet/freescale/fman/fman.c:fman_probe
  - drivers/net/ethernet/freescale/fman/fman.c:fman_probe
  - drivers/net/ethernet/freescale/fman/fman.c:fman_reset_mac
  - drivers/net/ethernet/freescale/fman/fman.c:fman_set_port_params
  - drivers/net/ethernet/freescale/fman/fman.c:dma_init
  - drivers/net/ethernet/freescale/fman/fman.c:dma_init
```
```
In drivers/net/ethernet/freescale/fman/fman_keygen.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/net/ethernet/freescale/fman/fman_port.c (ffff8000109f2734)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/fman_port.c:init_low_level_driver
  - drivers/net/ethernet/freescale/fman/fman_port.c:init_low_level_driver
  - drivers/net/ethernet/freescale/fman/fman_port.c:init_low_level_driver
  - drivers/net/ethernet/freescale/fman/fman_port.c:init_low_level_driver
  - drivers/net/ethernet/freescale/fman/fman_port.c:init_low_level_driver
  - drivers/net/ethernet/freescale/fman/fman_port.c:init_low_level_driver
```
```
In drivers/net/ethernet/freescale/fman/fman_dtsec.c (ffff8000109f54ac)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_modify_mac_address
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:init
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:init
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:init
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:init
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:init
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:init
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:init
```
```
In drivers/net/ethernet/freescale/fman/fman_memac.c (ffff8000109f7404)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_init
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_init
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_init
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_del_hash_mac_address
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_set_allmulti
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_add_hash_mac_address
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_exception
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_err_exception
```
```
In drivers/net/ethernet/freescale/fman/fman_tgec.c (ffff8000109f88f8)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_init
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_init
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_init
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_init
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_del_hash_mac_address
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_set_allmulti
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_set_allmulti
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_add_hash_mac_address
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_set_tx_pause_frames
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:set_mac_address
```
```
In drivers/net/slip/slhc.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/usb/dwc2/core.c (ffff800010a3bd80)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
```
```
In drivers/usb/dwc2/core_intr.c (ffff800010a3c5b8)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
```
```
In drivers/usb/dwc2/platform.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/usb/dwc2/params.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (ffff800010a414d0)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-common.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/edac/altera_edac.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/opp/of.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/mmc/core/host.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/mmc/core/mmc_ops.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/mmc/core/sd.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/mmc/core/sd_ops.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/mmc/core/block.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/firmware/dmi_scan.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/firmware/efi/efi.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/of/base.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/of/platform.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/of/property.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/of/dynamic.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/of/fdt.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/of/fdt_address.c (ffff8000114abac4)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/of/fdt_address.c:fdt_bus_default_translate
```
```
In drivers/of/address.c (ffff800010b72e04)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/of/address.c:of_bus_default_translate
```
```
In drivers/of/irq.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/of/of_reserved_mem.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/of/resolver.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/of/overlay.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/of/of_numa.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/memory/brcmstb_dpfe.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/memory/fsl_ifc.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/nvmem/core.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/core/flow_dissector.c (ffff800010bc4150)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/utils.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/core/filter.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/core/tso.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/ipv4/ip_options.c (ffff800010c60fac)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:__ip_options_compile
```
```
In net/ipv4/ip_output.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/ipv4/tcp_output.c (ffff800010c81d58)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_options_write
  - net/ipv4/tcp_output.c:tcp_options_write
  - net/ipv4/tcp_output.c:tcp_options_write
  - net/ipv4/tcp_output.c:tcp_options_write
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (ffff800010c902b4)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/ipv4/gre_offload.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/ipv4/fib_rules.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdba50)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffff800010ce9d2c)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/xfrm/xfrm_replay.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/ipv6/ip6_output.c (ffff800010cfc588)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/addrconf.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/ipv6/route.c (ffff800010d11438)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
  - net/ipv6/route.c:trace_event_raw_event_fib6_table_lookup
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (ffff800010d1d410)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/ipv6/udp.c (ffff800010d258cc)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffff800010d2a1a8)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/icmp.c (ffff800010d2c030)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d39180)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
```
In net/ipv6/ping.c (ffff800010d3a4d0)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/ipv6/datagram.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/ipv6/ip6_flowlabel.c (ffff800010d4032c)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
```
```
In net/ipv6/fib6_rules.c (ffff800010d4b470)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/ipv6/calipso.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffff800010d4f518)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/ipv6/ip6_checksum.c (ffff800010d5364c)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:csum_ipv6_magic
```
```
In net/ipv6/output_core.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/netlabel/netlabel_addrlist.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/ncsi/ncsi-cmd.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/ncsi/ncsi-rsp.c (ffff800010d757ec)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
```
```
In net/ncsi/ncsi-aen.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In lib/decompress_unlzo.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In lib/sha1.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In lib/vsprintf.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
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
In kernel/irq/generic-chip.c (ffffffe000118cc2)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_writel_be
  - kernel/irq/generic-chip.c:irq_readl_be
```
```
In kernel/module_signing.c (ffffffe000146ad4)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - kernel/module_signing.c:mod_verify_sig
```
```
In kernel/module_signature.c (ffffffe000146b7a)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - kernel/module_signature.c:mod_check_sig
```
```
In kernel/trace/blktrace.c (ffffffe00018e9ce)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_log_remap
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
```
```
In kernel/bpf/core.c (ffffffe00019c220)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_calc_tag
```
```
In kernel/bpf/lpm_trie.c (ffffffe0001b48e6)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - kernel/bpf/lpm_trie.c:longest_prefix_match
```
```
In mm/swapfile.c (ffffffe0002277cc)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/binfmt_flat.c (ffffffe0002c346c)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
```
```
In fs/ext4/super.c (ffffffe000337c90)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
```
```
In fs/jbd2/commit.c (ffffffe000346340)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffe000347cd0)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jbd2_journal_recover
```
```
In fs/jbd2/revoke.c (ffffffe000349834)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffe000349db2)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_clear_features
  - fs/jbd2/journal.c:jbd2_journal_clear_features
  - fs/jbd2/journal.c:jbd2_journal_clear_features
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_superblock_csum
```
```
In fs/ecryptfs/miscdev.c (ffffffe00036c4cc)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
```
In security/keys/dh.c (ffffffe000397152)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - security/keys/dh.c:keyctl_dh_compute_kdf
  - security/keys/dh.c:keyctl_dh_compute_kdf
```
```
In security/keys/trusted.c (ffffffe0003993de)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:TSS_checkhmac1
```
```
In security/smack/smackfs.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In security/apparmor/match.c (ffffffe0003ddf92)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/integrity/digsig_asymmetric.c (ffffffe0003f54e0)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In security/integrity/ima/ima_modsig.c (ffffffe0003fbf14)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - security/integrity/ima/ima_modsig.c:ima_read_modsig
```
```
In crypto/algapi.c (ffffffe0003ff0f4)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_inc
  - crypto/algapi.c:crypto_inc
```
```
In crypto/drbg.c (ffffffe0004168ac)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
```
In block/partitions/amiga.c (ffffffe00043ae18)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffe00043b17c)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffe00043bc38)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffe00043c5c2)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/sgi.c (ffffffe00043feb0)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffe0004401fe)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/sysv68.c (ffffffe000441cb6)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In block/t10-pi.c (ffffffe000451bae)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
  - block/t10-pi.c:t10_pi_type1_prepare
  - block/t10-pi.c:t10_pi_generate
```
```
In block/sed-opal.c (ffffffe000456872)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:opal_discovery0_end
  - block/sed-opal.c:opal_discovery0_end
```
```
In lib/crc32.c (ffffffe00046eee8)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - lib/crc32.c:crc32_be
  - lib/crc32.c:crc32_be
```
```
In drivers/pinctrl/devicetree.c (ffffffe00049c5d0)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/pinctrl/devicetree.c:pinctrl_parse_index_with_args
  - drivers/pinctrl/devicetree.c:pinctrl_dt_to_map
```
```
In drivers/pinctrl/pinctrl-single.c (ffffffe0004a1258)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
```
```
In drivers/gpio/gpio-mmio.c (ffffffe0004ad3e6)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_read32be
  - drivers/gpio/gpio-mmio.c:bgpio_write32be
```
```
In drivers/pci/of.c (ffffffe0004c9d8a)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/pci/of.c:of_irq_parse_and_map_pci
```
```
In drivers/pci/quirks.c (ffffffe0004cdc8c)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/clk/clk-divider.c (ffffffe0005118b2)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-divider.c:clk_divider_round_rate
  - drivers/clk/clk-divider.c:clk_divider_recalc_rate
```
```
In drivers/clk/clk-gate.c (ffffffe000512c6a)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/clk/clk-gate.c:clk_gate_is_enabled
  - drivers/clk/clk-gate.c:clk_gate_endisable
  - drivers/clk/clk-gate.c:clk_gate_endisable
```
```
In drivers/clk/clk-multiplier.c (ffffffe000512ec4)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-multiplier.c:clk_multiplier_recalc_rate
```
```
In drivers/clk/clk-mux.c (ffffffe000513286)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-mux.c:clk_mux_get_parent
```
```
In drivers/clk/clk-fractional-divider.c (ffffffe000513fd6)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/clk/clk-fractional-divider.c:clk_fd_recalc_rate
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/tty/serial/earlycon.c (ffffffe00002ee68)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/tty/serial/earlycon.c:of_setup_earlycon
  - drivers/tty/serial/earlycon.c:of_setup_earlycon
  - drivers/tty/serial/earlycon.c:of_setup_earlycon
  - drivers/tty/serial/earlycon.c:of_setup_earlycon
  - drivers/tty/serial/earlycon.c:of_setup_earlycon
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffe000550fb8)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_in
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_out
```
```
In drivers/tty/serial/8250/8250_dwlib.c (ffffffe000555af0)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffe000559954)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
```
```
In drivers/char/virtio_console.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffe00056935a)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
```
```
In drivers/char/tpm/tpm-interface.c (ffffffe000569e88)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffe00056b10c)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffe00056f0d4)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (ffffffe000570286)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffe000570fb6)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
```
In drivers/char/tpm/eventlog/of.c (ffffffe000571f60)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/of.c:tpm_read_log_of
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffe000572da6)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
```
```
In drivers/base/regmap/regmap.c (ffffffe0005936f2)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_32_be_inplace
  - drivers/base/regmap/regmap.c:regmap_parse_32_be
  - drivers/base/regmap/regmap.c:regmap_format_32_be
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffe00059bfb8)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read32be
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32be
```
```
In drivers/spi/spi-fsl-spi.c (ffffffe00061bf1e)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:fsl_spi_grlib_cs_control
  - drivers/spi/spi-fsl-spi.c:fsl_spi_grlib_cs_control
  - drivers/spi/spi-fsl-spi.c:fsl_spi_irq
  - drivers/spi/spi-fsl-spi.c:fsl_spi_irq
  - drivers/spi/spi-fsl-spi.c:fsl_spi_irq
  - drivers/spi/spi-fsl-spi.c:fsl_spi_irq
  - drivers/spi/spi-fsl-spi.c:fsl_spi_irq
  - drivers/spi/spi-fsl-spi.c:fsl_spi_setup
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_change_mode
  - drivers/spi/spi-fsl-spi.c:fsl_spi_change_mode
  - drivers/spi/spi-fsl-spi.c:fsl_spi_change_mode
```
```
In drivers/net/slip/slhc.c (ffffffe00062fd28)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/net/slip/slhc.c:slhc_compress
  - drivers/net/slip/slhc.c:slhc_compress
  - drivers/net/slip/slhc.c:slhc_compress
  - drivers/net/slip/slhc.c:slhc_compress
```
```
In drivers/cdrom/cdrom.c (ffffffe000634038)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
  - drivers/cdrom/cdrom.c:cdrom_get_last_written
  - drivers/cdrom/cdrom.c:cdrom_get_last_written
  - drivers/cdrom/cdrom.c:cdrom_get_last_written
  - drivers/cdrom/cdrom.c:cdrom_get_last_written
```
```
In drivers/usb/dwc2/core.c (ffffffe0006579b8)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_clear
  - drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_set
  - drivers/usb/dwc2/core.c:dwc2_hw_is_device
  - drivers/usb/dwc2/core.c:dwc2_hw_is_host
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_is_controller_alive
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
```
```
In drivers/usb/dwc2/core_intr.c (ffffffe000659398)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
```
```
In drivers/usb/dwc2/params.c (ffffffe00065b520)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
```
In drivers/usb/dwc2/hcd.c (ffffffe000665046)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_set_even_odd_frame
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_read_packet
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_disable_host_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_disable_host_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffe000667e5e)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hcd_save_data_toggle
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffe0006695bc)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffe00066ab7a)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffe0006bda30)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:dw_readl
```
```
In drivers/power/supply/power_supply_core.c (ffffffe0006c8c44)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
```
```
In drivers/opp/of.c (ffffffe00070461a)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/opp/of.c:dev_pm_opp_of_add_table
  - drivers/opp/of.c:dev_pm_opp_of_add_table
```
```
In drivers/mmc/core/host.c (ffffffe000709fc0)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_of_parse_voltage
  - drivers/mmc/core/host.c:mmc_of_parse_voltage
```
```
In drivers/mmc/core/mmc_ops.c (ffffffe00070e096)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_send_cid
  - drivers/mmc/core/mmc_ops.c:mmc_send_csd
```
```
In drivers/mmc/core/sd.c (ffffffe00070fbf2)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/mmc/core/sd_ops.c (ffffffe0007108f8)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
```
```
In drivers/mmc/core/block.c (ffffffe000715e20)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_sd_num_wr_blocks
```
```
In drivers/of/base.c (ffffffe00071f52c)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/of/base.c:of_map_rid
  - drivers/of/base.c:of_map_rid
  - drivers/of/base.c:of_map_rid
  - drivers/of/base.c:of_map_rid
  - drivers/of/base.c:of_parse_phandle_with_args_map
  - drivers/of/base.c:of_parse_phandle_with_args_map
  - drivers/of/base.c:of_parse_phandle_with_args_map
  - drivers/of/base.c:of_parse_phandle_with_args_map
  - drivers/of/base.c:of_phandle_iterator_args
  - drivers/of/base.c:of_phandle_iterator_next
  - drivers/of/base.c:arch_find_n_match_cpu_physical_id
```
```
In drivers/of/property.c (ffffffe000722cf4)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/of/property.c:of_prop_next_u32
  - drivers/of/property.c:of_property_read_variable_u64_array
  - drivers/of/property.c:of_property_read_u64
  - drivers/of/property.c:of_property_read_variable_u32_array
  - drivers/of/property.c:of_property_read_u32_index
```
```
In drivers/of/dynamic.c (ffffffe000724800)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/of/dynamic.c:__of_attach_node
```
```
In drivers/of/fdt.c (ffffffe00003aca6)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/of/fdt.c:early_init_dt_scan_root
  - drivers/of/fdt.c:early_init_dt_scan_root
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/fdt.c:__fdt_scan_reserved_mem
  - drivers/of/fdt.c:__unflatten_device_tree
  - drivers/of/fdt.c:unflatten_dt_nodes
  - drivers/of/fdt.c:unflatten_dt_nodes
  - drivers/of/fdt.c:of_fdt_limit_memory
  - drivers/of/fdt.c:of_fdt_limit_memory
  - drivers/of/fdt.c:of_read_number
```
```
In drivers/of/fdt_address.c (ffffffe00003bdcc)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/of/fdt_address.c:fdt_bus_default_translate
  - drivers/of/fdt_address.c:fdt_bus_default_translate
  - drivers/of/fdt_address.c:fdt_bus_default_count_cells
  - drivers/of/fdt_address.c:fdt_bus_default_count_cells
  - drivers/of/fdt_address.c:of_read_number
```
```
In drivers/of/address.c (ffffffe000727c3c)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/of/address.c:of_dma_get_range
  - drivers/of/address.c:of_dma_get_range
  - drivers/of/address.c:of_get_address
  - drivers/of/address.c:__of_translate_address
  - drivers/of/address.c:__of_translate_address
  - drivers/of/address.c:__of_translate_address
  - drivers/of/address.c:of_bus_isa_get_flags
  - drivers/of/address.c:of_bus_isa_map
  - drivers/of/address.c:of_bus_isa_map
  - drivers/of/address.c:of_bus_isa_map
  - drivers/of/address.c:of_pci_range_parser_one
  - drivers/of/address.c:of_pci_range_parser_one
  - drivers/of/address.c:of_pci_range_parser_one
  - drivers/of/address.c:of_pci_range_parser_one
  - drivers/of/address.c:of_pci_range_parser_one
  - drivers/of/address.c:of_get_pci_address
  - drivers/of/address.c:of_get_pci_address
  - drivers/of/address.c:of_bus_pci_map
  - drivers/of/address.c:of_bus_pci_map
  - drivers/of/address.c:of_bus_pci_map
  - drivers/of/address.c:of_bus_pci_get_flags
  - drivers/of/address.c:of_bus_default_translate
  - drivers/of/address.c:of_bus_default_translate
  - drivers/of/address.c:of_bus_default_translate
  - drivers/of/address.c:of_bus_default_map
  - drivers/of/address.c:of_bus_default_map
  - drivers/of/address.c:of_bus_default_map
```
```
In drivers/of/irq.c (ffffffe0007281fc)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/of/irq.c:of_irq_parse_raw
  - drivers/of/irq.c:of_irq_parse_raw
  - drivers/of/irq.c:of_irq_parse_raw
  - drivers/of/irq.c:of_irq_parse_raw
```
```
In drivers/of/of_reserved_mem.c (ffffffe00003c62a)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/of/of_reserved_mem.c:fdt_init_reserved_mem
```
```
In drivers/of/resolver.c (ffffffe00072a0d8)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - drivers/of/resolver.c:of_resolve_phandles
  - drivers/of/resolver.c:adjust_local_phandle_references
  - drivers/of/resolver.c:adjust_local_phandle_references
  - drivers/of/resolver.c:adjust_local_phandle_references
  - drivers/of/resolver.c:adjust_overlay_phandles
  - drivers/of/resolver.c:adjust_overlay_phandles
```
```
In drivers/of/overlay.c (ffffffe00072ad00)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In drivers/nvmem/core.c (ffffffe000737fd0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/core/skbuff.c (ffffffe000748a00)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_dec_ttl
```
```
In net/core/flow_dissector.c (ffffffe000750246)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/utils.c (ffffffe0007743b6)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/core/utils.c:in_aton
```
```
In net/core/filter.c (ffffffe00077a110)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/core/filter.c:bpf_tcp_check_syncookie
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/filter.c:bpf_skb_get_tunnel_key
  - net/core/filter.c:bpf_skb_get_tunnel_key
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
```
```
In net/core/tso.c (ffffffe00078364e)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/ipv4/ip_forward.c (ffffffe0007c865a)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffe0007c9128)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:__ip_options_compile
```
```
In net/ipv4/ip_output.c (ffffffe0007ca95c)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffe0007cdabc)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/ipv4/tcp.c (ffffffe0007d6366)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/tcp_input.c (ffffffe0007e31e8)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffe0007e44e2)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_options_write
  - net/ipv4/tcp_output.c:tcp_options_write
  - net/ipv4/tcp_output.c:tcp_options_write
  - net/ipv4/tcp_output.c:tcp_options_write
  - net/ipv4/tcp_output.c:tcp_options_write
  - net/ipv4/tcp_output.c:tcp_options_write
  - net/ipv4/tcp_output.c:tcp_options_write
  - net/ipv4/tcp_output.c:tcp_options_write
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007eade8)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb
  - net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffe0007ef716)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_offload.c (ffffffe0007f4ad2)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffe0007fccca)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/arp.c (ffffffe0007fee3c)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/ipv4/icmp.c (ffffffe000800686)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_unreach
```
```
In net/ipv4/devinet.c (ffffffe0008034a0)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/af_inet.c (ffffffe0008053c6)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_current_timestamp
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffffffe000807c5a)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_show
  - net/ipv4/igmp.c:igmp_mcf_seq_show
```
```
In net/ipv4/fib_frontend.c (ffffffe00080c0a2)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
```
```
In net/ipv4/fib_trie.c (ffffffe000811594)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_route_seq_show
  - net/ipv4/fib_trie.c:fib_table_dump
  - net/ipv4/fib_trie.c:fib_info_notify_update
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
```
```
In net/ipv4/gre_offload.c (ffffffe000818090)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/fib_rules.c (ffffffe00081ccaa)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/syncookies.c (ffffffe0008233d8)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv4/cipso_ipv4.c (ffffffe000825afc)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/ipv4/xfrm4_output.c (ffffffe00082839c)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082d0e2)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:xfrm_policy_addr_delta
  - net/xfrm/xfrm_policy.c:xfrm_policy_addr_delta
  - net/xfrm/xfrm_policy.c:xfrm_policy_addr_delta
  - net/xfrm/xfrm_policy.c:xfrm_policy_addr_delta
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
  - net/xfrm/xfrm_policy.c:policy_hash_bysel
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
  - net/xfrm/xfrm_policy.c:xfrm_selector_match
```
```
In net/xfrm/xfrm_state.c (ffffffe000831d0c)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_helper_sainfo
  - net/xfrm/xfrm_state.c:xfrm_state_walk
  - net/xfrm/xfrm_state.c:xfrm_state_walk
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_input.c (ffffffe000838572)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_replay.c (ffffffe00083a686)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_recheck_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_check_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_check_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance
  - net/xfrm/xfrm_replay.c:xfrm_replay_check
  - net/xfrm/xfrm_replay.c:xfrm_replay_seqhi
```
```
In net/ipv6/ip6_output.c (ffffffe000846e18)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/addrconf.c (ffffffe000850cf4)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/addrlabel.c (ffffffe0008525c0)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ipv6_addr_label
```
```
In net/ipv6/route.c (ffffffe000856102)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
  - net/ipv6/route.c:trace_event_raw_event_fib6_table_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffe00085e718)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
```
```
In net/ipv6/ipv6_sockglue.c (ffffffe000860644)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/ipv6/ndisc.c (ffffffe000864250)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/udp.c (ffffffe000866342)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/raw.c (ffffffe00086a9f2)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_icmp_error
```
```
In net/ipv6/icmp.c (ffffffe00086c26a)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/mcast.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000876506)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffe000877140)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffe0008777b6)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
```
```
In net/ipv6/datagram.c (0)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/ipv6/ip6_flowlabel.c (ffffffe00087af24)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/fib6_rules.c (ffffffe000884144)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/ipv6/syncookies.c (ffffffe0008852f4)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
```
In net/ipv6/calipso.c (ffffffe000885ef6)
Location: include/uapi/linux/swab.h:56
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffe000887a82)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_hmac.c (ffffffe00088a910)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_push_hmac
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/ip6_checksum.c (ffffffe00088b318)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:csum_ipv6_magic
  - net/ipv6/ip6_checksum.c:csum_ipv6_magic
```
```
In net/ipv6/output_core.c (ffffffe00088bc46)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_select_ident
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/netlabel/netlabel_addrlist.c (ffffffe000899fbc)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_audit_addr
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_audit_addr
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_audit_addr
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af4list_add
```
```
In net/ncsi/ncsi-cmd.c (ffffffe0008a4920)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_build_header
```
```
In net/ncsi/ncsi-rsp.c (ffffffe0008a4f4a)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
```
```
In net/ncsi/ncsi-aen.c (ffffffe0008a754c)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In lib/fdt.c (ffffffe0008af40e)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - lib/fdt.c:fdt_next_tag
  - lib/fdt.c:fdt_next_tag
```
```
In lib/fdt_rw.c (ffffffe0008b1f7c)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - lib/fdt_rw.c:fdt_pack
  - lib/fdt_rw.c:fdt_open_into
  - lib/fdt_rw.c:fdt_open_into
  - lib/fdt_rw.c:fdt_open_into
  - lib/fdt_rw.c:fdt_open_into
  - lib/fdt_rw.c:fdt_packblocks_
  - lib/fdt_rw.c:fdt_packblocks_
  - lib/fdt_rw.c:fdt_packblocks_
  - lib/fdt_rw.c:fdt_packblocks_
  - lib/fdt_rw.c:fdt_appendprop
  - lib/fdt_rw.c:fdt_add_property_
  - lib/fdt_rw.c:fdt_add_property_
  - lib/fdt_rw.c:fdt_add_property_
  - lib/fdt_rw.c:fdt_add_property_
  - lib/fdt_rw.c:fdt_splice_struct_
  - lib/fdt_rw.c:fdt_splice_struct_
  - lib/fdt_rw.c:fdt_splice_mem_rsv_
  - lib/fdt_rw.c:fdt_splice_mem_rsv_
```
```
In lib/vsprintf.c (ffffffe0008beeda)
Location: include/uapi/linux/swab.h:56
Inline: True
Inline callers:
  - lib/vsprintf.c:ip6_addr_string_sa
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
