# Function: <code>__tag_set</code>

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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In arch/arm64/kernel/probes/uprobes.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In arch/arm64/mm/dma-mapping.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In arch/arm64/mm/flush.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In arch/arm64/mm/pageattr.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In virt/kvm/kvm_main.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In virt/kvm/coalesced_mmio.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In virt/kvm/arm/mmu.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In kernel/dma/direct.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In kernel/dma/virt.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In kernel/profile.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In mm/truncate.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In mm/shmem.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In mm/util.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In mm/slab_common.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In mm/memory.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In mm/page_alloc.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In mm/swapfile.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In mm/zswap.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In mm/sparse-vmemmap.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In mm/ksm.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In mm/page_poison.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In mm/slub.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In mm/migrate.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In mm/huge_memory.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In mm/khugepaged.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In mm/swap_cgroup.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In mm/zbud.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In fs/read_write.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In fs/exec.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In fs/namei.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In fs/libfs.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In fs/splice.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In fs/buffer.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In fs/direct-io.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In fs/mpage.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In fs/aio.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In fs/io_uring.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In fs/dax.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In fs/verity/verify.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In fs/ext4/inline.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In fs/ext4/move_extent.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In fs/ext4/page-io.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In fs/ext4/readpage.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In fs/ext4/symlink.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In fs/ext4/verity.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In fs/squashfs/file.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In fs/squashfs/symlink.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In fs/squashfs/file_direct.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In fs/squashfs/page_actor.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In fs/ecryptfs/mmap.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In fs/ecryptfs/crypto.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In fs/fuse/dir.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In fs/fuse/file.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In fs/fuse/readdir.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In security/selinux/ss/status.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In security/tomoyo/domain.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In crypto/scatterwalk.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In crypto/blkcipher.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In crypto/skcipher.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In crypto/ahash.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In crypto/shash.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In block/bio.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In block/blk-mq.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In block/partition-generic.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In block/bio-integrity.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In block/t10-pi.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In lib/scatterlist.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In lib/iov_iter.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In drivers/irqchip/irq-gic-v3-its.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In drivers/dma/mv_xor.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In drivers/xen/balloon.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In drivers/char/tpm/tpm2-space.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In drivers/char/tpm/tpm-sysfs.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In drivers/iommu/io-pgtable-arm.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In drivers/base/firmware_loader/fallback.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In drivers/block/loop.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In drivers/ata/libata-sff.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In drivers/net/tun.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In drivers/net/ethernet/freescale/fec_main.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In drivers/md/md.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In drivers/md/md-bitmap.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In drivers/firmware/efi/capsule.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In net/core/sock.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In net/core/skbuff.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In net/core/datagram.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In net/core/dev.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In net/core/filter.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In net/core/tso.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In net/core/xdp.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In net/core/skmsg.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In net/xdp/xdp_umem.c (0)
Location: arch/arm64/include/asm/memory.h:237
Inline: True
```
```
In arch/arm64/lib/uaccess_flushcache.c (0)
Location: arch/arm64/include/asm/memory.h:237
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
In <code>riscv64</code>: Absent ⚠️
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
