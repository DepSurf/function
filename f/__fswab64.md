# Function: <code>__fswab64</code>

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
In arch/x86/kernel/pci-calgary_64.c (ffffffff81f767f4)
Location: include/uapi/linux/swab.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
```
```
In arch/x86/kernel/tce_64.c (ffffffff81068171)
Location: include/uapi/linux/swab.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_build
```
```
In kernel/trace/blktrace.c (ffffffff8115acf0)
Location: include/uapi/linux/swab.h:68
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:get_pdu_int
  - kernel/trace/blktrace.c:blk_log_remap
  - kernel/trace/blktrace.c:blk_add_trace_unplug
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
```
```
In kernel/bpf/core.c (ffffffff811728a6)
Location: include/uapi/linux/swab.h:68
Inline: True
Inline callers:
  - kernel/bpf/core.c:__bpf_prog_run
```
```
In mm/memtest.c (ffffffff81f8d15e)
Location: include/uapi/linux/swab.h:68
Inline: True
Inline callers:
  - mm/memtest.c:reserve_bad_mem
  - mm/memtest.c:early_memtest
```
```
In fs/jbd2/commit.c (ffffffff812e9afd)
Location: include/uapi/linux/swab.h:68
Inline: True
```
```
In fs/jbd2/recovery.c (ffffffff812ec05e)
Location: include/uapi/linux/swab.h:68
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff812edd0e)
Location: include/uapi/linux/swab.h:68
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/ecryptfs/mmap.c (ffffffff81304509)
Location: include/uapi/linux/swab.h:68
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffff81306755)
Location: include/uapi/linux/swab.h:68
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_i_size_init
```
```
In crypto/eseqiv.c (ffffffff813a27b9)
Location: include/uapi/linux/swab.h:68
Inline: True
Inline callers:
  - crypto/eseqiv.c:eseqiv_givencrypt
```
```
In crypto/sha1_generic.c (ffffffff813a5917)
Location: include/uapi/linux/swab.h:68
Inline: True
Inline callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
```
```
In crypto/sha256_generic.c (ffffffff813a7a7a)
Location: include/uapi/linux/swab.h:68
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
```
In crypto/sha512_generic.c (ffffffff813a86d6)
Location: include/uapi/linux/swab.h:68
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:crypto_sha512_finup
  - crypto/sha512_generic.c:crypto_sha512_finup
  - crypto/sha512_generic.c:crypto_sha512_finup
```
```
In block/partitions/ldm.c (ffffffff813d0601)
Location: include/uapi/linux/swab.h:68
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
Location: include/uapi/linux/swab.h:68
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/uapi/linux/swab.h:68
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/uapi/linux/swab.h:68
Inline: True
```
```
In drivers/lightnvm/sysblk.c (ffffffff81544a48)
Location: include/uapi/linux/swab.h:68
Inline: True
Inline callers:
  - drivers/lightnvm/sysblk.c:nvm_sysblk_to_cpu
  - drivers/lightnvm/sysblk.c:nvm_cpu_to_sysblk
```
```
In drivers/block/virtio_blk.c (0)
Location: include/uapi/linux/swab.h:68
Inline: True
```
```
In drivers/scsi/scsi_common.c (ffffffff815b15f0)
Location: include/uapi/linux/swab.h:68
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff815bd751)
Location: include/uapi/linux/swab.h:68
Inline: True
Inline callers:
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_setup_write_same_cmnd
  - drivers/scsi/sd.c:sd_setup_discard_cmnd
  - drivers/scsi/sd.c:sd_setup_discard_cmnd
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/uapi/linux/swab.h:68
Inline: True
```
```
In net/core/filter.c (ffffffff81731b41)
Location: include/uapi/linux/swab.h:68
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_key
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/ipv6/addrconf.c (ffffffff817cb2f8)
Location: include/uapi/linux/swab.h:68
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
```
```
In net/ipv6/addrlabel.c (ffffffff817d27a0)
Location: include/uapi/linux/swab.h:68
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ipv6_addr_label
  - net/ipv6/addrlabel.c:__ipv6_addr_label
```
```
In net/ipv6/ip6_fib.c (ffffffff817da909)
Location: include/uapi/linux/swab.h:68
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_1
  - net/ipv6/ip6_fib.c:fib6_add_1
  - net/ipv6/ip6_fib.c:fib6_add_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_lookup_1
  - net/ipv6/ip6_fib.c:fib6_lookup_1
```
```
In net/ipv6/fib6_rules.c (ffffffff817fe563)
Location: include/uapi/linux/swab.h:68
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
__u64 __fswab64(__u64 val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/kaslr.c (0)
Location: include/uapi/linux/swab.h:65
Inline: True
```
```
In arch/arm64/kernel/machine_kexec_file.c (0)
Location: include/uapi/linux/swab.h:65
Inline: True
```
```
In virt/kvm/arm/mmio.c (0)
Location: include/uapi/linux/swab.h:65
Inline: True
```
```
In drivers/firmware/efi/libstub/fdt.c (0)
Location: include/uapi/linux/swab.h:65
Inline: True
```
```
In lib/fdt_rw.c (0)
Location: include/uapi/linux/swab.h:65
Inline: True
```
```
In lib/fdt_sw.c (0)
Location: include/uapi/linux/swab.h:65
Inline: True
```
```
In kernel/trace/blktrace.c (ffff8000102379fc)
Location: include/uapi/linux/swab.h:65
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_unplug
```
```
In kernel/bpf/core.c (0)
Location: include/uapi/linux/swab.h:65
Inline: True
```
```
In kernel/bpf/lpm_trie.c (0)
Location: include/uapi/linux/swab.h:65
Inline: True
```
```
In mm/memtest.c (ffff80001034e678)
Location: include/uapi/linux/swab.h:65
Inline: False
Direct callers:
  - mm/memtest.c:early_memtest
  - mm/memtest.c:reserve_bad_mem
```
```
In fs/jbd2/commit.c (0)
Location: include/uapi/linux/swab.h:65
Inline: True
```
```
In fs/jbd2/recovery.c (0)
Location: include/uapi/linux/swab.h:65
Inline: True
```
```
In fs/jbd2/revoke.c (0)
Location: include/uapi/linux/swab.h:65
Inline: True
```
```
In fs/ecryptfs/mmap.c (0)
Location: include/uapi/linux/swab.h:65
Inline: True
```
```
In fs/ecryptfs/crypto.c (0)
Location: include/uapi/linux/swab.h:65
Inline: True
```
```
In security/selinux/ss/policydb.c (0)
Location: include/uapi/linux/swab.h:65
Inline: True
```
```
In crypto/sha1_generic.c (ffff8000105c7364)
Location: include/uapi/linux/swab.h:65
Inline: True
Inline callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
```
```
In crypto/sha512_generic.c (0)
Location: include/uapi/linux/swab.h:65
Inline: True
Inline callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
```
```
In crypto/gf128mul.c (0)
Location: include/uapi/linux/swab.h:65
Inline: True
```
```
In crypto/gcm.c (ffff8000105cc8ac)
Location: include/uapi/linux/swab.h:65
Inline: True
```
```
In crypto/drbg.c (0)
Location: include/uapi/linux/swab.h:65
Inline: True
```
```
In block/partitions/ldm.c (0)
Location: include/uapi/linux/swab.h:65
Inline: True
```
```
In block/sed-opal.c (0)
Location: include/uapi/linux/swab.h:65
Inline: True
```
```
In lib/crypto/sha256.c (ffff80001063d400)
Location: include/uapi/linux/swab.h:65
Inline: True
Inline callers:
  - lib/crypto/sha256.c:__sha256_final
```
```
In lib/mpi/mpicoder.c (0)
Location: include/uapi/linux/swab.h:65
Inline: True
```
```
In lib/digsig.c (0)
Location: include/uapi/linux/swab.h:65
Inline: True
```
```
In drivers/soc/fsl/qbman/bman.c (0)
Location: include/uapi/linux/swab.h:65
Inline: True
```
```
In drivers/soc/fsl/qbman/qman.c (0)
Location: include/uapi/linux/swab.h:65
Inline: True
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/uapi/linux/swab.h:65
Inline: False
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/uapi/linux/swab.h:65
Inline: False
```
```
In drivers/char/tpm/eventlog/of.c (0)
Location: include/uapi/linux/swab.h:65
Inline: True
```
```
In drivers/iommu/virtio-iommu.c (0)
Location: include/uapi/linux/swab.h:65
Inline: False
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/uapi/linux/swab.h:65
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/uapi/linux/swab.h:65
Inline: True
```
```
In drivers/scsi/scsi_trace.c (0)
Location: include/uapi/linux/swab.h:65
Inline: True
```
```
In drivers/scsi/scsi_common.c (0)
Location: include/uapi/linux/swab.h:65
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/uapi/linux/swab.h:65
Inline: True
```
```
In drivers/scsi/sd_zbc.c (0)
Location: include/uapi/linux/swab.h:65
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/uapi/linux/swab.h:65
Inline: True
```
```
In drivers/net/ethernet/freescale/fman/fman_port.c (0)
Location: include/uapi/linux/swab.h:65
Inline: True
```
```
In drivers/of/property.c (0)
Location: include/uapi/linux/swab.h:65
Inline: True
```
```
In net/core/filter.c (ffff800010c011f4)
Location: include/uapi/linux/swab.h:65
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/uapi/linux/swab.h:65
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/uapi/linux/swab.h:65
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/uapi/linux/swab.h:65
Inline: True
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/uapi/linux/swab.h:65
Inline: True
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/uapi/linux/swab.h:65
Inline: True
```
**Symbols:**

```
ffff80001034e678-ffff80001034e680: __fswab64 (STB_LOCAL)
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
<summary>In <code>riscv64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
__u64 __fswab64(__u64 val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffe00018e9ce)
Location: include/uapi/linux/swab.h:65
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_log_remap
  - kernel/trace/blktrace.c:get_pdu_int
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_unplug
```
```
In kernel/bpf/core.c (0)
Location: include/uapi/linux/swab.h:65
Inline: True
```
```
In mm/memtest.c (ffffffe00023df3c)
Location: include/uapi/linux/swab.h:65
Inline: False
Direct callers:
  - mm/memtest.c:early_memtest
  - mm/memtest.c:reserve_bad_mem
```
```
In fs/jbd2/commit.c (ffffffe0003456a4)
Location: include/uapi/linux/swab.h:65
Inline: True
```
```
In fs/jbd2/recovery.c (ffffffe000347614)
Location: include/uapi/linux/swab.h:65
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffe000349912)
Location: include/uapi/linux/swab.h:65
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In security/selinux/ss/policydb.c (ffffffe0003b603c)
Location: include/uapi/linux/swab.h:65
Inline: True
```
```
In crypto/sha1_generic.c (ffffffe00040b3d2)
Location: include/uapi/linux/swab.h:65
Inline: True
Inline callers:
  - crypto/sha1_generic.c:sha1_final
```
```
In crypto/sha512_generic.c (ffffffe00040c146)
Location: include/uapi/linux/swab.h:65
Inline: True
Inline callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
  - crypto/sha512_generic.c:crypto_sha512_finup
```
```
In crypto/gf128mul.c (ffffffe00040c9da)
Location: include/uapi/linux/swab.h:65
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
```
```
In crypto/gcm.c (ffffffe000410758)
Location: include/uapi/linux/swab.h:65
Inline: True
```
```
In crypto/drbg.c (ffffffe0004177b2)
Location: include/uapi/linux/swab.h:65
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_generate
```
```
In block/sed-opal.c (ffffffe000459990)
Location: include/uapi/linux/swab.h:65
Inline: True
Inline callers:
  - block/sed-opal.c:opal_discovery0_end
  - block/sed-opal.c:opal_discovery0_end
```
```
In lib/crypto/sha256.c (ffffffe00046b106)
Location: include/uapi/linux/swab.h:65
Inline: True
Inline callers:
  - lib/crypto/sha256.c:__sha256_final
```
```
In lib/mpi/mpicoder.c (ffffffe00048f8f4)
Location: include/uapi/linux/swab.h:65
Inline: True
Inline callers:
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_read_buffer
```
```
In lib/digsig.c (ffffffe0004928a6)
Location: include/uapi/linux/swab.h:65
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/uapi/linux/swab.h:65
Inline: False
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/uapi/linux/swab.h:65
Inline: False
```
```
In drivers/char/tpm/eventlog/of.c (ffffffe000571f58)
Location: include/uapi/linux/swab.h:65
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/of.c:tpm_read_log_of
```
```
In drivers/base/regmap/regmap.c (ffffffe000594c6a)
Location: include/uapi/linux/swab.h:65
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_parse_64_be_inplace
  - drivers/base/regmap/regmap.c:regmap_parse_64_be
  - drivers/base/regmap/regmap.c:regmap_format_64_be
```
```
In drivers/of/property.c (ffffffe000722e56)
Location: include/uapi/linux/swab.h:65
Inline: True
Inline callers:
  - drivers/of/property.c:of_property_read_u64_index
```
```
In net/core/filter.c (ffffffe00077f28a)
Location: include/uapi/linux/swab.h:65
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In lib/fdt_rw.c (ffffffe0008b15dc)
Location: include/uapi/linux/swab.h:65
Inline: True
Inline callers:
  - lib/fdt_rw.c:fdt_add_mem_rsv
  - lib/fdt_rw.c:fdt_add_mem_rsv
```
**Symbols:**

```
ffffffe00023df3c-ffffffe00023df9c: __fswab64 (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
