# Function: <code>lowmem_page_address</code>

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
In init/do_mounts.c (ffffffff81f5a387)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/events/intel/bts.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff810142e5)
Location: include/linux/mm.h:906
Inline: True
```
```
In arch/x86/xen/mmu.c (ffffffff810202c8)
Location: include/linux/mm.h:906
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81034609)
Location: include/linux/mm.h:906
Inline: True
```
```
In arch/x86/kernel/pci-dma.c (ffffffff81034ef9)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105b7e6)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff81066f12)
Location: include/linux/mm.h:906
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In arch/x86/mm/pageattr.c (ffffffff8106d4b2)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81f7aed7)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In kernel/fork.c (ffffffff8107e7bb)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/power/snapshot.c (ffffffff810d1625)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
```
```
In kernel/profile.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In kernel/kexec_core.c (ffffffff8110c961)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_add_entry
  - kernel/kexec_core.c:kimage_load_segment
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffff81146922)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_alloc_read_page
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/trace/trace.c (ffffffff81151489)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff811851ab)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
```
```
In kernel/events/uprobes.c (ffffffff81187686)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/page_alloc.c (ffffffff81191b53)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - mm/page_alloc.c:get_zeroed_page
  - mm/page_alloc.c:alloc_pages_exact
```
```
In mm/truncate.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In mm/shmem.c (ffffffff811a8b8a)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_follow_link
```
```
In mm/percpu.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In mm/slab_common.c (ffffffff811b276d)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
```
```
In mm/memory.c (ffffffff811bba49)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__pmd_alloc
```
```
In mm/vmalloc.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In mm/swapfile.c (ffffffff811d6425)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
```
```
In mm/zswap.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff8181f102)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffff811e6030)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/slub.c (ffffffff811e7365)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - mm/slub.c:get_map
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:print_trailer
  - mm/slub.c:check_object
  - mm/slub.c:on_freelist
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:validate_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:process_slab
  - mm/slub.c:new_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_create
```
```
In mm/migrate.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In mm/swap_cgroup.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In mm/zbud.c (ffffffff81204936)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (ffffffff8120550f)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
```
```
In mm/userfaultfd.c (ffffffff81207c57)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (ffffffff81213031)
Location: include/linux/mm.h:906
Inline: True
```
```
In fs/namei.c (ffffffff81217ea0)
Location: include/linux/mm.h:906
Inline: True
```
```
In fs/libfs.c (ffffffff81234e6c)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_begin
```
```
In fs/splice.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In fs/buffer.c (ffffffff812437b6)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin
  - fs/buffer.c:nobh_write_begin
```
```
In fs/direct-io.c (ffffffff8124a562)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In fs/aio.c (ffffffff8125bb24)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_complete
  - fs/aio.c:SyS_io_setup
```
```
In fs/dax.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812976a1)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/page-io.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In fs/ext4/symlink.c (ffffffff812be6c9)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_encrypted_follow_link
```
```
In fs/ext4/mballoc.c (ffffffff812ceefc)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff812d6b69)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/inline.c (ffffffff812e04e0)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/readpage.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff812ea737)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff812f2c8b)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ecryptfs/mmap.c (ffffffff81303e6c)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff81304ac7)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/ecryptfs/crypto.c (ffffffff8130651c)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In fs/fuse/dev.c (ffffffff8130e704)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/dir.c (ffffffff8131363a)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
```
```
In fs/fuse/file.c (ffffffff81315908)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In security/selinux/ss/status.c (ffffffff8135caff)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - security/selinux/ss/status.c:selinux_kernel_status_page
  - security/selinux/ss/status.c:selinux_status_update_setenforce
  - security/selinux/ss/status.c:selinux_status_update_policyload
```
```
In security/tomoyo/domain.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In crypto/scatterwalk.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In crypto/eseqiv.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In crypto/ahash.c (ffffffff813a29f5)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
  - crypto/ahash.c:hash_walk_next
```
```
In crypto/shash.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In block/blk-mq.c (ffffffff813c3c67)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_rq_map
```
```
In block/partition-generic.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In block/bio-integrity.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In lib/scatterlist.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In lib/iov_iter.c (ffffffff813fcc2e)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_from_iter_iovec
  - lib/iov_iter.c:copy_page_to_iter_iovec
```
```
In lib/swiotlb.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In lib/mpi/mpicoder.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff8181ad84)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/xen/balloon.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff8152656f)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
```
```
In drivers/iommu/amd_iommu.c (ffffffff81531341)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
```
```
In drivers/iommu/dmar.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In drivers/iommu/intel-iommu.c (ffffffff8153566f)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dma_pte_list_pagetables
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
```
```
In drivers/iommu/intel-svm.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In drivers/base/firmware_class.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In drivers/block/brd.c (ffffffff8156d06f)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - drivers/block/brd.c:brd_direct_access
  - drivers/block/brd.c:brd_do_bvec
```
```
In drivers/block/loop.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff815ae379)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/scsi_lib_dma.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff815bf444)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_discard_cmnd
```
```
In drivers/scsi/sd_dif.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In drivers/scsi/sg.c (ffffffff815c274c)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read_oxfer
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In drivers/ata/libata-scsi.c (ffffffff815d1f15)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff815f2a63)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:try_fill_recv
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In drivers/usb/core/hcd.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In drivers/md/md.c (ffffffff8168b7e5)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_90_sync
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_rdev_size_change
```
```
In drivers/md/bitmap.c (ffffffff8169c669)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_file_clear_bit
  - drivers/md/bitmap.c:bitmap_file_set_bit
  - drivers/md/bitmap.c:bitmap_init_from_disk
  - drivers/md/bitmap.c:bitmap_print_sb
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_copy_from_slot
```
```
In net/core/sock.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In net/core/skbuff.c (ffffffff817083fb)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_seq_read
```
```
In net/core/datagram.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In net/core/tso.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff8175ec65)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/mm.h:906
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/mm.h:906
Inline: True
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
In init/do_mounts.c (ffffffff81f82332)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/events/intel/bts.c (ffffffff8100cced)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:__bts_event_start
```
```
In arch/x86/events/intel/pt.c (ffffffff81013d2f)
Location: include/linux/mm.h:1003
Inline: True
```
```
In arch/x86/xen/mmu.c (ffffffff81022187)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_mm_unpin_all
  - arch/x86/xen/mmu.c:xen_mm_pin_all
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810337d3)
Location: include/linux/mm.h:1003
Inline: True
```
```
In arch/x86/kernel/pci-dma.c (ffffffff810340dc)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105be93)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff81066cb5)
Location: include/linux/mm.h:1003
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff81067a25)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
```
```
In arch/x86/mm/init_64.c (ffffffff81896441)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:sync_global_pgds
```
```
In arch/x86/mm/pageattr.c (ffffffff8106f229)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:set_pages_rw
  - arch/x86/mm/pageattr.c:set_pages_ro
  - arch/x86/mm/pageattr.c:set_pages_nx
  - arch/x86/mm/pageattr.c:set_pages_x
  - arch/x86/mm/pageattr.c:set_pages_wb
  - arch/x86/mm/pageattr.c:set_pages_uc
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81fa3961)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In kernel/fork.c (ffffffff8108043f)
Location: include/linux/mm.h:1003
Inline: True
```
```
In kernel/power/snapshot.c (ffffffff810d6c04)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_free
```
```
In kernel/profile.c (ffffffff810f143a)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/kexec_core.c (ffffffff81114a93)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_add_entry
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8113fec4)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/trace/ring_buffer.c (ffffffff8114f172)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_alloc_read_page
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff81158590)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff8117cdca)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff8119700c)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff81199c61)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In mm/page_alloc.c (ffffffff811a90d2)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:__alloc_page_frag
  - mm/page_alloc.c:get_zeroed_page
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/truncate.c (ffffffff811b5135)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff811c315b)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/percpu.c (ffffffff81fb31e6)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_page_first_chunk
```
```
In mm/slab_common.c (ffffffff811cc247)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
```
```
In mm/memory.c (ffffffff811ddde4)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/vmalloc.c (ffffffff811ecd42)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
```
```
In mm/swapfile.c (ffffffff811f15be)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff811f6911)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/sparse-vmemmap.c (ffffffff8189961d)
Location: include/linux/mm.h:1003
Inline: True
```
```
In mm/ksm.c (ffffffff81205db0)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:memcmp_pages
  - mm/ksm.c:memcmp_pages
```
```
In mm/slub.c (ffffffff81207b27)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__check_heap_object
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:check_object
  - mm/slub.c:print_trailer
  - mm/slub.c:get_map
```
```
In mm/migrate.c (ffffffff812108a5)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff81216bb9)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff8121b020)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/swap_cgroup.c (ffffffff8122534e)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/zbud.c (ffffffff812298b3)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (ffffffff8122bfda)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/userfaultfd.c (ffffffff8122d5b1)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (ffffffff81239cff)
Location: include/linux/mm.h:1003
Inline: True
```
```
In fs/namei.c (ffffffff8123da6f)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - fs/namei.c:__page_symlink
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff8125d0a6)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/splice.c (ffffffff81265be7)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - fs/splice.c:write_pipe_buf
  - fs/splice.c:default_file_splice_read
```
```
In fs/buffer.c (ffffffff8126cef4)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - fs/buffer.c:guard_bio_eod
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/direct-io.c (ffffffff81272f3d)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff812763c5)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff812864f8)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
  - fs/aio.c:SyS_io_setup
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_complete
  - fs/aio.c:aio_complete
  - fs/aio.c:aio_setup_ring
```
```
In fs/dax.c (ffffffff81287bca)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - fs/dax.c:dax_fault
  - fs/dax.c:dax_fault
  - fs/dax.c:read_dax_sector
```
```
In fs/binfmt_elf.c (ffffffff81295951)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff812985de)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap.c (ffffffff8129c7ef)
Location: include/linux/mm.h:1003
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812c676a)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff812ce9e2)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/symlink.c (ffffffff812ee00d)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_encrypted_get_link
```
```
In fs/ext4/mballoc.c (ffffffff812ff380)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff81306865)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/inline.c (ffffffff81310f70)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/readpage.c (ffffffff81313616)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/jbd2/transaction.c (ffffffff81316381)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81317db3)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff813207fc)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff8132273a)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/symlink.c (ffffffff8132489c)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff81324f93)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff81325454)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_next_page
  - fs/squashfs/page_actor.c:direct_first_page
```
```
In fs/ecryptfs/mmap.c (ffffffff81338958)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff81338ef7)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffffffff8133a8dc)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/dev.c (ffffffff81342a77)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/dir.c (ffffffff81347afe)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
```
```
In fs/fuse/file.c (ffffffff8134a773)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_short_read
```
```
In security/selinux/selinuxfs.c (ffffffff81381a9a)
Location: include/linux/mm.h:1003
Inline: True
```
```
In security/selinux/ss/status.c (ffffffff81392bb7)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - security/selinux/ss/status.c:selinux_status_update_policyload
  - security/selinux/ss/status.c:selinux_status_update_setenforce
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
```
In security/tomoyo/domain.c (ffffffff813a41d0)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff813db724)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff813dd61c)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/ahash.c (ffffffff813deb88)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
  - crypto/ahash.c:hash_walk_next
```
```
In crypto/shash.c (ffffffff813dff8c)
Location: include/linux/mm.h:1003
Inline: True
```
```
In block/bio.c (ffffffff813f62e1)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_copy_data
  - block/bio.c:bio_copy_data
  - block/bio.c:zero_fill_bio
```
```
In block/blk-merge.c (ffffffff81403ac3)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - block/blk-merge.c:bio_data
```
```
In block/blk-mq.c (ffffffff81407fdf)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_rq_map
```
```
In block/partition-generic.c (ffffffff81411415)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/bounce.c (ffffffff8141adf0)
Location: include/linux/mm.h:1003
Inline: True
```
```
In block/bio-integrity.c (ffffffff8142d861)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_free
```
```
In lib/scatterlist.c (ffffffff81441527)
Location: include/linux/mm.h:1003
Inline: True
```
```
In lib/iov_iter.c (ffffffff8144424e)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_to_iter
  - lib/iov_iter.c:memcpy_from_page
  - lib/iov_iter.c:copy_page_from_iter_iovec
  - lib/iov_iter.c:copy_page_to_iter_iovec
```
```
In lib/swiotlb.c (0)
Location: include/linux/mm.h:1003
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff81894eef)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/mm.h:1003
Inline: True
```
```
In drivers/xen/balloon.c (ffffffff81516c26)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff8156a2b8)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/mm.h:1003
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81579dc8)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
```
```
In drivers/iommu/amd_iommu.c (ffffffff81584e42)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
```
```
In drivers/iommu/dmar.c (ffffffff815899a2)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff8158fae8)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:dma_free_pagelist
  - drivers/iommu/intel-iommu.c:dma_pte_list_pagetables
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel-svm.c (ffffffff81591136)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables
  - drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815928c3)
Location: include/linux/mm.h:1003
Inline: True
```
```
In drivers/base/firmware_class.c (ffffffff815b2863)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:firmware_rw
```
```
In drivers/block/brd.c (ffffffff815c289f)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - drivers/block/brd.c:brd_direct_access
  - drivers/block/brd.c:brd_make_request
  - drivers/block/brd.c:brd_do_bvec
  - drivers/block/brd.c:brd_do_bvec
  - drivers/block/brd.c:brd_do_bvec
  - drivers/block/brd.c:brd_do_bvec
  - drivers/block/brd.c:brd_do_bvec
```
```
In drivers/block/loop.c (ffffffff815c5dbe)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff815cb149)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/scsi/scsi_lib.c (ffffffff8160624f)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/scsi_lib_dma.c (0)
Location: include/linux/mm.h:1003
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81614f7e)
Location: include/linux/mm.h:1003
Inline: True
```
```
In drivers/scsi/sd_dif.c (ffffffff8161829a)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_complete
  - drivers/scsi/sd_dif.c:sd_dif_prepare
```
```
In drivers/scsi/sg.c (ffffffff8161b143)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_read_oxfer
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/mm.h:1003
Inline: True
```
```
In drivers/ata/libata-scsi.c (ffffffff8162b831)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
```
```
In drivers/ata/libata-sff.c (ffffffff81638603)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/spi/spi.c (0)
Location: include/linux/mm.h:1003
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff81653142)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:try_fill_recv
```
```
In drivers/net/xen-netfront.c (ffffffff8165c0ee)
Location: include/linux/mm.h:1003
Inline: True
```
```
In drivers/usb/core/hcd.c (0)
Location: include/linux/mm.h:1003
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff8167121f)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff8167ccf2)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/md/md.c (ffffffff816f5fd6)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_90_sync
  - drivers/md/md.c:super_90_validate
```
```
In drivers/md/bitmap.c (ffffffff816ff3dd)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_copy_from_slot
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_daemon_work
  - drivers/md/bitmap.c:bitmap_init_from_disk
  - drivers/md/bitmap.c:bitmap_init_from_disk
  - drivers/md/bitmap.c:bitmap_file_clear_bit
  - drivers/md/bitmap.c:bitmap_file_set_bit
  - drivers/md/bitmap.c:bitmap_print_sb
```
```
In drivers/firmware/efi/capsule.c (ffffffff817353d0)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/sock.c (ffffffff817677c4)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - net/core/sock.c:sock_no_sendpage
```
```
In net/core/skbuff.c (ffffffff817733c0)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_append_datato_frags
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/datagram.c (ffffffff81774fa0)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram
```
```
In net/core/dev.c (ffffffff8177b4c8)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - net/core/dev.c:skb_gro_reset_offset
```
```
In net/core/tso.c (ffffffff8179fdda)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/ipv4/ip_output.c (ffffffff817caf1e)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff817d6277)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv6/ip6_output.c (ffffffff81832c50)
Location: include/linux/mm.h:1003
Inline: True
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
In init/do_mounts.c (ffffffff81fbe3f4)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/events/intel/bts.c (ffffffff8100cdbd)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:__bts_event_start
```
```
In arch/x86/events/intel/pt.c (ffffffff81013eaf)
Location: include/linux/mm.h:992
Inline: True
```
```
In arch/x86/xen/mmu.c (ffffffff810228d4)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_mm_unpin_all
  - arch/x86/xen/mmu.c:xen_mm_pin_all
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81033403)
Location: include/linux/mm.h:992
Inline: True
```
```
In arch/x86/kernel/pci-dma.c (ffffffff81033d0b)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105ee13)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff8106a8e8)
Location: include/linux/mm.h:992
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8106b675)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
```
```
In arch/x86/mm/init_64.c (ffffffff818cab58)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:sync_global_pgds
```
```
In arch/x86/mm/pageattr.c (ffffffff81072e8a)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:set_pages_rw
  - arch/x86/mm/pageattr.c:set_pages_ro
  - arch/x86/mm/pageattr.c:set_pages_nx
  - arch/x86/mm/pageattr.c:set_pages_x
  - arch/x86/mm/pageattr.c:set_pages_wb
  - arch/x86/mm/pageattr.c:set_pages_uc
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81fdf26a)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In kernel/power/snapshot.c (ffffffff810dd774)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_free
```
```
In kernel/profile.c (ffffffff810f8427)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/kexec_core.c (ffffffff8111c183)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_add_entry
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81149caa)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/trace/ring_buffer.c (ffffffff81159312)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_alloc_read_page
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff81164d46)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811889de)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff811a6a1c)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff811a9331)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In mm/page_alloc.c (ffffffff811bba0b)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:__get_free_pages
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/truncate.c (ffffffff811c5750)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff811d31eb)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/percpu.c (ffffffff81fefd45)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_page_first_chunk
```
```
In mm/slab_common.c (ffffffff811dc2ed)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/memory.c (ffffffff811edbf6)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/vmalloc.c (ffffffff811fdfd5)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
```
```
In mm/swapfile.c (ffffffff81201fcd)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff812072c1)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/sparse-vmemmap.c (ffffffff818cdcd5)
Location: include/linux/mm.h:992
Inline: True
```
```
In mm/ksm.c (ffffffff81217dc0)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:memcmp_pages
  - mm/ksm.c:memcmp_pages
  - mm/ksm.c:calc_checksum
```
```
In mm/slub.c (ffffffff81219b57)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__check_heap_object
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:check_object
  - mm/slub.c:print_trailer
  - mm/slub.c:get_map
```
```
In mm/migrate.c (ffffffff81222a47)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812291ce)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff8122e859)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/swap_cgroup.c (ffffffff8123793e)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/zbud.c (ffffffff8123be53)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (ffffffff8123e51a)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/userfaultfd.c (ffffffff8123fae6)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff812446e0)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range_compare
  - fs/read_write.c:vfs_dedupe_file_range_compare
```
```
In fs/exec.c (ffffffff8124ca40)
Location: include/linux/mm.h:992
Inline: True
```
```
In fs/namei.c (ffffffff8125085f)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - fs/namei.c:__page_symlink
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff812705fc)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/splice.c (ffffffff812792a7)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - fs/splice.c:write_pipe_buf
  - fs/splice.c:default_file_splice_read
```
```
In fs/buffer.c (ffffffff81280184)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - fs/buffer.c:guard_bio_eod
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/direct-io.c (ffffffff81287927)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff8128a105)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff8129997a)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_complete
  - fs/aio.c:aio_complete
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:aio_setup_ring
```
```
In fs/dax.c (ffffffff8129c396)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:read_dax_sector
```
```
In fs/binfmt_elf.c (ffffffff812aa5b4)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff812ad072)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap.c (ffffffff812b150f)
Location: include/linux/mm.h:992
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812dc033)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff812e47dd)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/symlink.c (ffffffff81303fac)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_encrypted_get_link
```
```
In fs/ext4/mballoc.c (ffffffff81315406)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff8131cebe)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/inline.c (ffffffff81326e47)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/readpage.c (ffffffff813295b4)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/jbd2/transaction.c (ffffffff8132c371)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff8132dda1)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff8133669a)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff813385ca)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/symlink.c (ffffffff8133a7aa)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff8133aded)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff8133b2a4)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_next_page
  - fs/squashfs/page_actor.c:direct_first_page
```
```
In fs/ecryptfs/mmap.c (ffffffff8134e6f8)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff8134ec97)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffffffff8135067c)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/dev.c (ffffffff81358947)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/dir.c (ffffffff8135d448)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
```
```
In fs/fuse/file.c (ffffffff8135ffe3)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_short_read
```
```
In security/selinux/selinuxfs.c (ffffffff81398511)
Location: include/linux/mm.h:992
Inline: True
```
```
In security/selinux/ss/status.c (ffffffff813a97d7)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - security/selinux/ss/status.c:selinux_status_update_policyload
  - security/selinux/ss/status.c:selinux_status_update_setenforce
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
```
In security/tomoyo/domain.c (ffffffff813bad51)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff813f3062)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff813f4eec)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff813f6454)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff813f7128)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
  - crypto/ahash.c:hash_walk_next
```
```
In crypto/shash.c (ffffffff813f851c)
Location: include/linux/mm.h:992
Inline: True
```
```
In block/bio.c (ffffffff8140fcce)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_copy_data
  - block/bio.c:bio_copy_data
  - block/bio.c:zero_fill_bio
```
```
In block/blk-merge.c (ffffffff8141d833)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - block/blk-merge.c:bio_data
```
```
In block/blk-mq.c (ffffffff81422c9b)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_rq_map
```
```
In block/partition-generic.c (ffffffff8142c7b9)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/bounce.c (ffffffff81436331)
Location: include/linux/mm.h:992
Inline: True
```
```
In block/bio-integrity.c (ffffffff814476bb)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/blk-zoned.c (ffffffff81448dbe)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_report_zones
```
```
In lib/scatterlist.c (ffffffff8145e741)
Location: include/linux/mm.h:992
Inline: True
```
```
In lib/iov_iter.c (ffffffff81462439)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
  - lib/iov_iter.c:copy_page_from_iter_iovec
  - lib/iov_iter.c:copy_page_to_iter_iovec
```
```
In lib/swiotlb.c (0)
Location: include/linux/mm.h:992
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff818c9642)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/mm.h:992
Inline: True
```
```
In drivers/xen/balloon.c (ffffffff815430e3)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff815969ee)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/mm.h:992
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff815a6308)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
```
```
In drivers/iommu/amd_iommu.c (ffffffff815b1f1c)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
```
```
In drivers/iommu/dmar.c (ffffffff815b705e)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff815bd329)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:dma_free_pagelist
  - drivers/iommu/intel-iommu.c:dma_pte_list_pagetables
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel-svm.c (ffffffff815bea06)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables
  - drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815c0183)
Location: include/linux/mm.h:992
Inline: True
```
```
In drivers/base/firmware_class.c (ffffffff815e1c83)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:firmware_rw
```
```
In drivers/block/loop.c (ffffffff815f431d)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff815f7d8a)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/scsi/scsi_lib.c (ffffffff8163576c)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/scsi_lib_dma.c (0)
Location: include/linux/mm.h:992
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff8164486a)
Location: include/linux/mm.h:992
Inline: True
```
```
In drivers/scsi/sd_dif.c (ffffffff81647e3a)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_complete
  - drivers/scsi/sd_dif.c:sd_dif_prepare
```
```
In drivers/scsi/sg.c (ffffffff8164bdbf)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_read_oxfer
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/mm.h:992
Inline: True
```
```
In drivers/ata/libata-scsi.c (ffffffff8165c9d5)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
```
```
In drivers/ata/libata-sff.c (ffffffff8166969d)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/spi/spi.c (0)
Location: include/linux/mm.h:992
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff8168a003)
Location: include/linux/mm.h:992
Inline: True
```
```
In drivers/usb/core/hcd.c (0)
Location: include/linux/mm.h:992
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff8169eed6)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff816aaa8e)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/md/md.c (ffffffff81727805)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_90_sync
  - drivers/md/md.c:super_90_validate
```
```
In drivers/md/bitmap.c (ffffffff81731008)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_copy_from_slot
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_daemon_work
  - drivers/md/bitmap.c:bitmap_init_from_disk
  - drivers/md/bitmap.c:bitmap_init_from_disk
  - drivers/md/bitmap.c:bitmap_file_clear_bit
  - drivers/md/bitmap.c:bitmap_file_set_bit
  - drivers/md/bitmap.c:bitmap_print_sb
```
```
In drivers/firmware/efi/capsule.c (ffffffff81768584)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/sock.c (ffffffff817947d4)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - net/core/sock.c:sock_no_sendpage
```
```
In net/core/skbuff.c (ffffffff817a05dc)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_append_datato_frags
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/datagram.c (ffffffff817a22f6)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram
```
```
In net/core/dev.c (ffffffff817a8b2e)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - net/core/dev.c:skb_gro_reset_offset
```
```
In net/core/tso.c (ffffffff817ce7aa)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/ipv4/ip_output.c (ffffffff817fac3b)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff81806276)
Location: include/linux/mm.h:992
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv6/ip6_output.c (ffffffff818648a0)
Location: include/linux/mm.h:992
Inline: True
```
```
In lib/dma-noop.c (ffffffff818c55dd)
Location: include/linux/mm.h:992
Inline: True
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
In init/do_mounts.c (ffffffff8209e532)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/events/intel/bts.c (ffffffff8100cbd0)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:__bts_event_start
```
```
In arch/x86/events/intel/pt.c (ffffffff810124ed)
Location: include/linux/mm.h:1034
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810248b1)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_mm_unpin_all
  - arch/x86/xen/mmu_pv.c:xen_mm_pin_all
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810315c5)
Location: include/linux/mm.h:1034
Inline: True
```
```
In arch/x86/kernel/pci-dma.c (ffffffff81031dc2)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105e4b3)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff81069bc8)
Location: include/linux/mm.h:1034
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8106aa05)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
```
```
In arch/x86/mm/init_64.c (ffffffff81902068)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:sync_global_pgds
```
```
In arch/x86/mm/pageattr.c (ffffffff810723fa)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:set_pages_rw
  - arch/x86/mm/pageattr.c:set_pages_ro
  - arch/x86/mm/pageattr.c:set_pages_nx
  - arch/x86/mm/pageattr.c:set_pages_x
  - arch/x86/mm/pageattr.c:set_pages_wb
  - arch/x86/mm/pageattr.c:set_pages_uc
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff820c01bc)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In kernel/power/snapshot.c (ffffffff810dc954)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_free
```
```
In kernel/profile.c (ffffffff810fa44f)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/kexec_core.c (ffffffff8111e01f)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_add_entry
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8114baad)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/trace/ring_buffer.c (ffffffff8115e90f)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff81168080)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff8118b663)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff811ae1fb)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff811b08af)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In mm/page_alloc.c (ffffffff811c3cbf)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:__get_free_pages
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/truncate.c (ffffffff811cd971)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff811da868)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mcopy_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/percpu.c (ffffffff820d213e)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_page_first_chunk
```
```
In mm/slab_common.c (ffffffff811e620d)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/memory.c (ffffffff811f8d4b)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/vmalloc.c (ffffffff81208bfc)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
```
```
In mm/swapfile.c (ffffffff8120c85f)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff81212440)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/sparse-vmemmap.c (ffffffff81905186)
Location: include/linux/mm.h:1034
Inline: True
```
```
In mm/ksm.c (ffffffff812239c4)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:memcmp_pages
  - mm/ksm.c:memcmp_pages
  - mm/ksm.c:calc_checksum
```
```
In mm/slub.c (ffffffff81225887)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__check_heap_object
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
  - mm/slub.c:print_trailer
  - mm/slub.c:get_map
```
```
In mm/migrate.c (ffffffff8122e475)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff8123558f)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff81238fb6)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/swap_cgroup.c (ffffffff8124357e)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/zbud.c (ffffffff81247ab6)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (ffffffff81249f13)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/userfaultfd.c (ffffffff8124b618)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff81250129)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range_compare
  - fs/read_write.c:vfs_dedupe_file_range_compare
```
```
In fs/exec.c (ffffffff81258af3)
Location: include/linux/mm.h:1034
Inline: True
```
```
In fs/namei.c (ffffffff8125c9dd)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - fs/namei.c:__page_symlink
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff8127dcd2)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/splice.c (ffffffff81286817)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - fs/splice.c:write_pipe_buf
  - fs/splice.c:default_file_splice_read
```
```
In fs/buffer.c (ffffffff8128da53)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - fs/buffer.c:guard_bio_eod
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/direct-io.c (ffffffff812944e8)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff81296c6f)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff812a7348)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_complete
  - fs/aio.c:aio_complete
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:aio_setup_ring
```
```
In fs/dax.c (ffffffff812ab4b5)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
```
```
In fs/binfmt_elf.c (ffffffff812b6dbf)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff812b9e9e)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap.c (ffffffff812be958)
Location: include/linux/mm.h:1034
Inline: True
```
```
In fs/ext4/inline.c (ffffffff812fad3f)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff813005b2)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff8130c7cb)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff813155aa)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff8131e4ac)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff8131eb5c)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff8133914f)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_encrypted_get_link
```
```
In fs/jbd2/transaction.c (ffffffff81341617)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81342f0c)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff8134b39d)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff8134d54f)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/symlink.c (ffffffff8134f486)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff8134fa08)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff8134fdd6)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_next_page
  - fs/squashfs/page_actor.c:direct_first_page
```
```
In fs/ecryptfs/mmap.c (ffffffff813631fe)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff81363756)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffffffff8136518c)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/dev.c (ffffffff8136d1a1)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_do
```
```
In fs/fuse/dir.c (ffffffff81371e62)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
```
```
In fs/fuse/file.c (ffffffff81374b59)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_short_read
```
```
In security/selinux/selinuxfs.c (ffffffff813ae741)
Location: include/linux/mm.h:1034
Inline: True
```
```
In security/selinux/ss/status.c (ffffffff813c0197)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - security/selinux/ss/status.c:selinux_status_update_policyload
  - security/selinux/ss/status.c:selinux_status_update_setenforce
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
```
In security/tomoyo/domain.c (ffffffff813d15f6)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff813ff3c9)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff8140121d)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff81402878)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff814034f8)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
  - crypto/ahash.c:hash_walk_next
```
```
In crypto/shash.c (ffffffff81404a38)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff8141d66f)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_copy_data
  - block/bio.c:bio_copy_data
  - block/bio.c:zero_fill_bio
```
```
In block/blk-mq.c (ffffffff81432800)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In block/partition-generic.c (ffffffff81439b11)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/bounce.c (ffffffff81442e3d)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
  - block/bounce.c:blk_queue_bounce
```
```
In block/bio-integrity.c (ffffffff81455ab7)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/blk-zoned.c (ffffffff8145732a)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_report_zones
```
```
In lib/scatterlist.c (ffffffff8146394e)
Location: include/linux/mm.h:1034
Inline: True
```
```
In lib/iov_iter.c (ffffffff8146814a)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
```
```
In lib/swiotlb.c (0)
Location: include/linux/mm.h:1034
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff81900baa)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/mm.h:1034
Inline: True
```
```
In drivers/xen/balloon.c (ffffffff81556f5c)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff815aa7e8)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/mm.h:1034
Inline: True
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff815b722c)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm-interface.c:tpm_getcap
  - drivers/char/tpm/tpm-interface.c:tpm_startup
  - drivers/char/tpm/tpm-interface.c:tpm_startup
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff815bac27)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context_cmd
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff815bc1b9)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/iommu/amd_iommu.c (ffffffff815c7ba9)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
```
```
In drivers/iommu/dmar.c (ffffffff815cce45)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff815d2f59)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:dma_free_pagelist
  - drivers/iommu/intel-iommu.c:dma_pte_list_pagetables
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel-svm.c (ffffffff815d4626)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables
  - drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815d5cd8)
Location: include/linux/mm.h:1034
Inline: True
```
```
In drivers/base/firmware_class.c (ffffffff815f6900)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:firmware_rw
```
```
In drivers/block/loop.c (ffffffff81605c5d)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff8160bb3a)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/scsi/scsi_lib.c (ffffffff8164a926)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/scsi_lib_dma.c (0)
Location: include/linux/mm.h:1034
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff8165a8db)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
```
```
In drivers/scsi/sd_dif.c (ffffffff8165c971)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_complete
  - drivers/scsi/sd_dif.c:sd_dif_prepare
```
```
In drivers/scsi/sg.c (ffffffff816607bc)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_read_oxfer
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/mm.h:1034
Inline: True
```
```
In drivers/ata/libata-scsi.c (ffffffff816712e0)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
```
```
In drivers/ata/libata-sff.c (ffffffff8167de13)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/spi/spi.c (0)
Location: include/linux/mm.h:1034
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff8169d915)
Location: include/linux/mm.h:1034
Inline: True
```
```
In drivers/usb/core/hcd.c (0)
Location: include/linux/mm.h:1034
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff816b4013)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff816bfa8e)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/md/md.c (ffffffff817400c7)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_90_sync
  - drivers/md/md.c:super_90_validate
```
```
In drivers/md/bitmap.c (ffffffff81749f77)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_copy_from_slot
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_daemon_work
  - drivers/md/bitmap.c:bitmap_init_from_disk
  - drivers/md/bitmap.c:bitmap_init_from_disk
  - drivers/md/bitmap.c:bitmap_file_clear_bit
  - drivers/md/bitmap.c:bitmap_file_set_bit
  - drivers/md/bitmap.c:bitmap_print_sb
```
```
In drivers/md/dm.c (ffffffff8174c211)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_remap_zone_report
```
```
In drivers/edac/edac_mc.c (ffffffff8175c5de)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/firmware/efi/capsule.c (ffffffff81786e5b)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/sock.c (ffffffff817b29f4)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - net/core/sock.c:sock_no_sendpage
```
```
In net/core/skbuff.c (ffffffff817badb4)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_append_datato_frags
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/datagram.c (ffffffff817bfb88)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram
```
```
In net/core/dev.c (ffffffff817c71d9)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - net/core/dev.c:skb_gro_reset_offset
```
```
In net/core/tso.c (ffffffff817edc5b)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/ipv4/ip_output.c (ffffffff8181b054)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff81826df1)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv6/ip6_output.c (ffffffff818880b2)
Location: include/linux/mm.h:1034
Inline: True
```
```
In lib/dma-virt.c (ffffffff818ebe50)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - lib/dma-virt.c:dma_virt_map_page
```
```
In arch/x86/lib/usercopy_64.c (ffffffff818fd8aa)
Location: include/linux/mm.h:1034
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
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
In init/do_mounts.c (ffffffff826a4500)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/events/intel/bts.c (ffffffff8100d170)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:__bts_event_start
```
```
In arch/x86/events/intel/ds.c (ffffffff8100dee8)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff810125bd)
Location: include/linux/mm.h:1085
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025451)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_mm_unpin_all
  - arch/x86/xen/mmu_pv.c:xen_mm_pin_all
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102a6f0)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81033809)
Location: include/linux/mm.h:1085
Inline: True
```
```
In arch/x86/kernel/pci-dma.c (ffffffff810340f6)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810621e3)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff8106e478)
Location: include/linux/mm.h:1085
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8106f305)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
```
```
In arch/x86/mm/init_64.c (ffffffff8198c069)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:sync_global_pgds
```
```
In arch/x86/mm/pageattr.c (ffffffff81077c6a)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:set_pages_rw
  - arch/x86/mm/pageattr.c:set_pages_ro
  - arch/x86/mm/pageattr.c:set_pages_nx
  - arch/x86/mm/pageattr.c:set_pages_x
  - arch/x86/mm/pageattr.c:set_pages_wb
  - arch/x86/mm/pageattr.c:set_pages_uc
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff8108047c)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:sev_alloc
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff826c8373)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In kernel/power/snapshot.c (ffffffff810e4b74)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_free
```
```
In kernel/profile.c (ffffffff81104dd3)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/kexec_core.c (ffffffff8112980f)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_add_entry
  - kernel/kexec_core.c:kimage_free_pages
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81158379)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/trace/ring_buffer.c (ffffffff8116b90f)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff81175023)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff81199116)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff811c1e6b)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff811c43bf)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In mm/page_alloc.c (ffffffff811d8a5f)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:__get_free_pages
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/truncate.c (ffffffff811e2c60)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff811f05fb)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/percpu.c (ffffffff826dac55)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_page_first_chunk
```
```
In mm/slab_common.c (ffffffff811fc44d)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/memory.c (ffffffff812110db)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/vmalloc.c (ffffffff81221d27)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
```
```
In mm/swapfile.c (ffffffff81226588)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:SYSC_swapon
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff8122d090)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/sparse-vmemmap.c (ffffffff8198f168)
Location: include/linux/mm.h:1085
Inline: True
```
```
In mm/ksm.c (ffffffff8123f004)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:memcmp_pages
  - mm/ksm.c:memcmp_pages
  - mm/ksm.c:calc_checksum
```
```
In mm/slub.c (ffffffff81240f17)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__check_heap_object
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
  - mm/slub.c:print_trailer
  - mm/slub.c:get_map
```
```
In mm/migrate.c (ffffffff8124a6c9)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff81253f3a)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff81259a31)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/swap_cgroup.c (ffffffff812633ce)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/zbud.c (ffffffff81267c66)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (ffffffff8126a135)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/userfaultfd.c (ffffffff8126b954)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff81272045)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range_compare
  - fs/read_write.c:vfs_dedupe_file_range_compare
```
```
In fs/exec.c (ffffffff8127ac6e)
Location: include/linux/mm.h:1085
Inline: True
```
```
In fs/namei.c (ffffffff8127ed2d)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - fs/namei.c:__page_symlink
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff812a07af)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/splice.c (ffffffff812a92d7)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - fs/splice.c:write_pipe_buf
  - fs/splice.c:default_file_splice_read
```
```
In fs/buffer.c (ffffffff812b0609)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - fs/buffer.c:guard_bio_eod
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/direct-io.c (ffffffff812b7482)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff812b9eda)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff812ca6dd)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_complete
  - fs/aio.c:aio_complete
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:aio_setup_ring
```
```
In fs/dax.c (ffffffff812cedfb)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
```
```
In fs/binfmt_elf.c (ffffffff812da778)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff812dd868)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap.c (ffffffff812e231e)
Location: include/linux/mm.h:1085
Inline: True
```
```
In fs/ext4/inline.c (ffffffff8131f42f)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff81324dd5)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff813313a3)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff81339df4)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff81342acc)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813431c3)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff8135d44f)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_encrypted_get_link
```
```
In fs/jbd2/transaction.c (ffffffff81365c49)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81367537)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff8136f9ca)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff81371bff)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/symlink.c (ffffffff81373b43)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff813740ba)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff81374556)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_next_page
  - fs/squashfs/page_actor.c:direct_first_page
```
```
In fs/ecryptfs/mmap.c (ffffffff81387ec2)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff813884a0)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffffffff81389e5c)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/dev.c (ffffffff81391d5b)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_do
```
```
In fs/fuse/dir.c (ffffffff81396b62)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
```
```
In fs/fuse/file.c (ffffffff8139980d)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_short_read
```
```
In security/selinux/selinuxfs.c (ffffffff813d47f5)
Location: include/linux/mm.h:1085
Inline: True
```
```
In security/selinux/ss/status.c (ffffffff813e6337)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - security/selinux/ss/status.c:selinux_status_update_policyload
  - security/selinux/ss/status.c:selinux_status_update_setenforce
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
```
In security/tomoyo/domain.c (ffffffff813f7ab6)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff8142797e)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff8142982d)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff8142aee8)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff8142bc28)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
  - crypto/ahash.c:hash_walk_next
```
```
In crypto/shash.c (ffffffff8142d34c)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff814484ff)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_copy_data
  - block/bio.c:bio_copy_data
  - block/bio.c:zero_fill_bio
```
```
In block/blk-mq.c (ffffffff8145e3d0)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In block/partition-generic.c (ffffffff81465b11)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/bounce.c (ffffffff8146f878)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
  - block/bounce.c:blk_queue_bounce
```
```
In block/bio-integrity.c (ffffffff8148171e)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/blk-zoned.c (ffffffff81483026)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_report_zones
```
```
In lib/scatterlist.c (ffffffff8148f8ee)
Location: include/linux/mm.h:1085
Inline: True
```
```
In lib/iov_iter.c (ffffffff814918af)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
```
```
In lib/swiotlb.c (0)
Location: include/linux/mm.h:1085
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff8198abaa)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/xen/balloon.c (ffffffff815baf6a)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff8161116e)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff8161de7e)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm-interface.c:tpm_getcap
  - drivers/char/tpm/tpm-interface.c:tpm_startup
  - drivers/char/tpm/tpm-interface.c:tpm_startup
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff8161f28b)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816212f0)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context_cmd
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff81622680)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/iommu/amd_iommu.c (ffffffff8162e879)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
```
```
In drivers/iommu/dmar.c (ffffffff81633c45)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff81639c59)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:dma_free_pagelist
  - drivers/iommu/intel-iommu.c:dma_pte_list_pagetables
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel-svm.c (ffffffff8163b3b6)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables
  - drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8163ca88)
Location: include/linux/mm.h:1085
Inline: True
```
```
In drivers/base/firmware_class.c (ffffffff8165e860)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:firmware_rw
```
```
In drivers/block/loop.c (ffffffff8166e05d)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff816743f8)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/scsi/scsi_lib.c (ffffffff816b3c96)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/sd.c (ffffffff816c3aa1)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
```
```
In drivers/scsi/sd_dif.c (ffffffff816c5fcb)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_complete
  - drivers/scsi/sd_dif.c:sd_dif_prepare
```
```
In drivers/scsi/sg.c (ffffffff816c9cdc)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_read_oxfer
```
```
In drivers/ata/libata-scsi.c (ffffffff816da8c0)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
```
```
In drivers/ata/libata-sff.c (ffffffff816e761a)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/net/tun.c (ffffffff816feeae)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff81708975)
Location: include/linux/mm.h:1085
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff8171f843)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff8172b43e)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/md/md.c (ffffffff817b277b)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_90_sync
  - drivers/md/md.c:super_90_validate
```
```
In drivers/md/md-bitmap.c (ffffffff817bc25d)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:bitmap_resize
  - drivers/md/md-bitmap.c:bitmap_resize
  - drivers/md/md-bitmap.c:bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_daemon_work
  - drivers/md/md-bitmap.c:bitmap_init_from_disk
  - drivers/md/md-bitmap.c:bitmap_init_from_disk
  - drivers/md/md-bitmap.c:bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:bitmap_file_set_bit
  - drivers/md/md-bitmap.c:bitmap_print_sb
```
```
In drivers/md/dm.c (ffffffff817be5d5)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_remap_zone_report
```
```
In drivers/edac/edac_mc.c (ffffffff817ce830)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/firmware/efi/capsule.c (ffffffff817fd2eb)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/sock.c (ffffffff8182acc4)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
```
```
In net/core/skbuff.c (ffffffff81832e8d)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_append_datato_frags
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/datagram.c (ffffffff81839738)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram
```
```
In net/core/dev.c (ffffffff81840db9)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - net/core/dev.c:skb_gro_reset_offset
```
```
In net/core/tso.c (ffffffff81869e9b)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/ipv4/ip_output.c (ffffffff81899ffd)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff818a4d22)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff8190a4f6)
Location: include/linux/mm.h:1085
Inline: True
```
```
In lib/dma-virt.c (ffffffff81971e40)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - lib/dma-virt.c:dma_virt_map_page
```
```
In arch/x86/lib/usercopy_64.c (ffffffff8198539a)
Location: include/linux/mm.h:1085
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
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
In init/do_mounts.c (ffffffff826cd620)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/events/intel/bts.c (ffffffff8100d8d6)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:__bts_event_start
```
```
In arch/x86/events/intel/ds.c (ffffffff8100e6a8)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff81012f8d)
Location: include/linux/mm.h:1164
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810261a1)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_mm_unpin_all
  - arch/x86/xen/mmu_pv.c:xen_mm_pin_all
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102ae1b)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81034b82)
Location: include/linux/mm.h:1164
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810652e3)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff81071ec5)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
```
```
In arch/x86/mm/init_64.c (ffffffff819e89ed)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
```
```
In arch/x86/mm/pageattr.c (ffffffff8107a750)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:set_pages_rw
  - arch/x86/mm/pageattr.c:set_pages_ro
  - arch/x86/mm/pageattr.c:set_pages_nx
  - arch/x86/mm/pageattr.c:set_pages_x
  - arch/x86/mm/pageattr.c:set_pages_wb
  - arch/x86/mm/pageattr.c:set_pages_uc
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff826f22b0)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In kernel/power/snapshot.c (ffffffff810ec860)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/dma/direct.c (ffffffff8110cea1)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_alloc
```
```
In kernel/dma/virt.c (ffffffff8110d195)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - kernel/dma/virt.c:dma_virt_map_page
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/mm.h:1164
Inline: True
```
```
In kernel/profile.c (ffffffff8110fb63)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/kexec_core.c (ffffffff811377a5)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_add_entry
  - kernel/kexec_core.c:kimage_free_pages
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81166f95)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/trace/ring_buffer.c (ffffffff8117ad7c)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff81183faf)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811ae821)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/sockmap.c (ffffffff811cfbac)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:bpf_tcp_sendmsg
  - kernel/bpf/sockmap.c:bpf_exec_tx_verdict
```
```
In kernel/bpf/stackmap.c (ffffffff811d0d1c)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/ring_buffer.c (ffffffff811e222b)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff811e48ce)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In mm/page_alloc.c (ffffffff811f6ff6)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:__get_free_pages
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/truncate.c (ffffffff8120420c)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff81211d6b)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/percpu.c (ffffffff8270517a)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_page_first_chunk
```
```
In mm/slab_common.c (ffffffff8121d5ad)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/memory.c (ffffffff81231adb)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:copy_subpage
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/vmalloc.c (ffffffff81243c2b)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
```
```
In mm/swapfile.c (ffffffff81249898)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff8124fd16)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/sparse-vmemmap.c (ffffffff819eb9e4)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffff812627b0)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:memcmp_pages
  - mm/ksm.c:memcmp_pages
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff81262b65)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
```
```
In mm/slub.c (ffffffff81263ea5)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__check_heap_object
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
  - mm/slub.c:print_trailer
  - mm/slub.c:get_map
```
```
In mm/migrate.c (ffffffff8126da03)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff8127392c)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff8127b81b)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/swap_cgroup.c (ffffffff81287685)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/zbud.c (ffffffff8128c5dc)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (ffffffff8128e8e1)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/userfaultfd.c (ffffffff8129037d)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff81298080)
Location: include/linux/mm.h:1164
Inline: True
```
```
In fs/exec.c (ffffffff812a1a1e)
Location: include/linux/mm.h:1164
Inline: True
```
```
In fs/namei.c (ffffffff812a56bd)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - fs/namei.c:__page_symlink
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff812c6d15)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/splice.c (ffffffff812cfe17)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - fs/splice.c:write_pipe_buf
  - fs/splice.c:default_file_splice_read
```
```
In fs/buffer.c (ffffffff812d83eb)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - fs/buffer.c:guard_bio_eod
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/direct-io.c (ffffffff812e003d)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff812e2c8c)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff812f4871)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_complete
  - fs/aio.c:aio_complete
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:aio_setup_ring
```
```
In fs/dax.c (ffffffff812f871e)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/binfmt_elf.c (ffffffff8130646f)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff81309e14)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap.c (ffffffff8130ec69)
Location: include/linux/mm.h:1164
Inline: True
```
```
In fs/ext4/inline.c (ffffffff8134d513)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff81353022)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff8135f95f)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff81368336)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff81370a1c)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff81370f1f)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff8138bdf6)
Location: include/linux/mm.h:1164
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff813943bb)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81395dd4)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff8139dee5)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff813a01bc)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff813a257a)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff813a2d92)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff813a2f66)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_next_page
  - fs/squashfs/page_actor.c:direct_first_page
```
```
In fs/ecryptfs/mmap.c (ffffffff813b6a3d)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff813b72a0)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffffffff813b8cbc)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/dev.c (ffffffff813c0d94)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_do
```
```
In fs/fuse/dir.c (ffffffff813c5d12)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
```
```
In fs/fuse/file.c (ffffffff813c83fb)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_short_read
```
```
In security/selinux/selinuxfs.c (ffffffff81404b5c)
Location: include/linux/mm.h:1164
Inline: True
```
```
In security/selinux/ss/status.c (ffffffff81417064)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - security/selinux/ss/status.c:selinux_status_update_policyload
  - security/selinux/ss/status.c:selinux_status_update_setenforce
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
```
In security/tomoyo/domain.c (ffffffff81428a86)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff8145a7de)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff8145c897)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff8145dc29)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff8145e939)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
  - crypto/ahash.c:hash_walk_next
```
```
In crypto/shash.c (ffffffff8145ffb8)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff8147b64a)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:zero_fill_bio_iter
```
```
In block/blk-mq.c (ffffffff81491d00)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In block/partition-generic.c (ffffffff814994e1)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/bounce.c (ffffffff814a3c48)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
  - block/bounce.c:blk_queue_bounce
  - block/bounce.c:copy_to_high_bio_irq
  - block/bounce.c:copy_to_high_bio_irq
```
```
In block/bio-integrity.c (ffffffff814b61e1)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/blk-zoned.c (ffffffff814b7c7e)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_report_zones
```
```
In lib/scatterlist.c (ffffffff814c45ce)
Location: include/linux/mm.h:1164
Inline: True
```
```
In lib/iov_iter.c (ffffffff814c6881)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:memcpy_mcsafe_to_page
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
```
```
In drivers/acpi/osl.c (ffffffff819e74da)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/xen/balloon.c (ffffffff815f361a)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff8164abee)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff81657b8e)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm-interface.c:tpm_getcap
  - drivers/char/tpm/tpm-interface.c:tpm_startup
  - drivers/char/tpm/tpm-interface.c:tpm_startup
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff81659020)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff8165b0ac)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context_cmd
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff8165c450)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/iommu/amd_iommu.c (ffffffff81669558)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
```
```
In drivers/iommu/dmar.c (ffffffff8166eddd)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff81674dc9)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:dma_free_pagelist
  - drivers/iommu/intel-iommu.c:dma_pte_list_pagetables
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel-svm.c (ffffffff816768d6)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables
  - drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81677ed4)
Location: include/linux/mm.h:1164
Inline: True
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff8169b230)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_rw
```
```
In drivers/block/loop.c (ffffffff816a9b3d)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff816b05a3)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/scsi/scsi_lib.c (ffffffff816efd3b)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/sd.c (ffffffff816ffbfa)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
```
```
In drivers/scsi/sd_dif.c (ffffffff81702555)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_complete
  - drivers/scsi/sd_dif.c:sd_dif_prepare
```
```
In drivers/scsi/sg.c (ffffffff81706660)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_read_oxfer
```
```
In drivers/ata/libata-scsi.c (ffffffff81716d80)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
```
```
In drivers/ata/libata-sff.c (ffffffff81723d5a)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/net/tun.c (ffffffff8173cf1f)
Location: include/linux/mm.h:1164
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff817476b5)
Location: include/linux/mm.h:1164
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff8175f4bb)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff8176a4ef)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/md/md.c (ffffffff817f5ceb)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_90_sync
  - drivers/md/md.c:super_90_validate
```
```
In drivers/md/md-bitmap.c (ffffffff818043de)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:bitmap_resize
  - drivers/md/md-bitmap.c:bitmap_resize
  - drivers/md/md-bitmap.c:bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_daemon_work
  - drivers/md/md-bitmap.c:bitmap_init_from_disk
  - drivers/md/md-bitmap.c:bitmap_init_from_disk
  - drivers/md/md-bitmap.c:bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:bitmap_file_set_bit
  - drivers/md/md-bitmap.c:bitmap_print_sb
```
```
In drivers/md/dm.c (ffffffff818068c9)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_remap_zone_report
```
```
In drivers/edac/edac_mc.c (ffffffff8181749c)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/firmware/efi/capsule.c (ffffffff81846b1f)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/sock.c (ffffffff81874db4)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
```
```
In net/core/skbuff.c (ffffffff8187d3aa)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_datato_frags
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/datagram.c (ffffffff81883e62)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram
```
```
In net/core/dev.c (ffffffff8188b429)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - net/core/dev.c:skb_gro_reset_offset
```
```
In net/core/filter.c (ffffffff818b3a10)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/tso.c (ffffffff818b9b6d)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/ipv4/ip_output.c (ffffffff818ee567)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff818fa861)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff8196189e)
Location: include/linux/mm.h:1164
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff819cd261)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In arch/x86/lib/usercopy_64.c (ffffffff819e18ea)
Location: include/linux/mm.h:1164
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
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
In init/do_mounts.c (ffffffff828835f7)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/events/intel/bts.c (ffffffff8100dda6)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:__bts_event_start
```
```
In arch/x86/events/intel/ds.c (ffffffff8100eb78)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff8101395d)
Location: include/linux/mm.h:1232
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025d51)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_mm_unpin_all
  - arch/x86/xen/mmu_pv.c:xen_mm_pin_all
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102b54b)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81035d62)
Location: include/linux/mm.h:1232
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106af53)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
```
```
In arch/x86/kernel/kvmclock.c (ffffffff828a074d)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_setup_vsyscall_timeinfo
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff81077f05)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
```
```
In arch/x86/mm/init_64.c (ffffffff81a24276)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
```
```
In arch/x86/mm/pageattr.c (ffffffff81080f00)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:set_pages_rw
  - arch/x86/mm/pageattr.c:set_pages_ro
  - arch/x86/mm/pageattr.c:set_pages_nx
  - arch/x86/mm/pageattr.c:set_pages_x
  - arch/x86/mm/pageattr.c:set_pages_wb
  - arch/x86/mm/pageattr.c:set_pages_uc
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828a92b9)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In kernel/power/snapshot.c (ffffffff810f7f00)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/dma/direct.c (ffffffff81118c11)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_alloc_pages
```
```
In kernel/dma/virt.c (ffffffff81118e65)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - kernel/dma/virt.c:dma_virt_map_page
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/mm.h:1232
Inline: True
```
```
In kernel/profile.c (ffffffff8111b253)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/kexec_core.c (ffffffff81142f45)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_add_entry
  - kernel/kexec_core.c:kimage_alloc_control_pages
  - kernel/kexec_core.c:kimage_free_pages
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81173cf5)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/trace/ring_buffer.c (ffffffff811877ec)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff8119191f)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811bceb5)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/stackmap.c (ffffffff811e0854)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/ring_buffer.c (ffffffff811f269b)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff811f5727)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In mm/page_alloc.c (ffffffff81209396)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:__get_free_pages
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/truncate.c (ffffffff81216bcc)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff81223c08)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/percpu.c (ffffffff828bc8c1)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_page_first_chunk
```
```
In mm/slab_common.c (ffffffff8123059d)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/memory.c (ffffffff812452ab)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:copy_subpage
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/vmalloc.c (ffffffff8125832b)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
```
```
In mm/swapfile.c (ffffffff8125dec5)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff81264286)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/sparse-vmemmap.c (ffffffff81a26c6a)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffff81277030)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:memcmp_pages
  - mm/ksm.c:memcmp_pages
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff812773e5)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
```
```
In mm/slub.c (ffffffff81278615)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__check_heap_object
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
  - mm/slub.c:print_trailer
  - mm/slub.c:get_map
```
```
In mm/migrate.c (ffffffff81282009)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff81287ecf)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff8128fbd4)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/swap_cgroup.c (ffffffff8129c5d5)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/zbud.c (ffffffff812a155c)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (ffffffff812a2a81)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/userfaultfd.c (ffffffff812a531c)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff812ad301)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (ffffffff812b67de)
Location: include/linux/mm.h:1232
Inline: True
```
```
In fs/namei.c (ffffffff812ba82d)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - fs/namei.c:__page_symlink
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff812dbee5)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/splice.c (ffffffff812e5227)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - fs/splice.c:write_pipe_buf
  - fs/splice.c:default_file_splice_read
```
```
In fs/buffer.c (ffffffff812ed8bb)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - fs/buffer.c:guard_bio_eod
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/direct-io.c (ffffffff812f4b69)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff812f78ee)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff8130971e)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_complete
  - fs/aio.c:aio_complete
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:aio_setup_ring
```
```
In fs/dax.c (ffffffff8130ed81)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/binfmt_elf.c (ffffffff8131bbff)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff8131f614)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap.c (ffffffff813243f1)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - fs/iomap.c:iomap_write_end
  - fs/iomap.c:iomap_read_page_sync
  - fs/iomap.c:iomap_readpage_actor
```
```
In fs/ext4/inline.c (ffffffff813656a3)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff8136b14f)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff81377e05)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff813807b9)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff81388eb1)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813893c1)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff813a4986)
Location: include/linux/mm.h:1232
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff813ad10b)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813aeb2a)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff813b6c55)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff813b8f3d)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff813bb35a)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff813bbb9f)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff813bbd66)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_next_page
  - fs/squashfs/page_actor.c:direct_first_page
```
```
In fs/ecryptfs/mmap.c (ffffffff813cff8d)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff813d07f0)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffffffff813d222c)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/dev.c (ffffffff813da0f4)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_do
```
```
In fs/fuse/dir.c (ffffffff813ddeb2)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readlink_page
```
```
In fs/fuse/file.c (ffffffff813e1621)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_short_read
```
```
In fs/fuse/readdir.c (ffffffff813ea71c)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/selinux/selinuxfs.c (ffffffff8141ffac)
Location: include/linux/mm.h:1232
Inline: True
```
```
In security/selinux/ss/status.c (ffffffff81433574)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - security/selinux/ss/status.c:selinux_status_update_policyload
  - security/selinux/ss/status.c:selinux_status_update_setenforce
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
```
In security/tomoyo/domain.c (ffffffff81445356)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff8147834e)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff81479f07)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff8147b4c9)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff8147c2a9)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
  - crypto/ahash.c:hash_walk_next
```
```
In crypto/shash.c (ffffffff8147da48)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff814997ba)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:zero_fill_bio_iter
```
```
In block/blk-mq.c (ffffffff814ab76d)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In block/partition-generic.c (ffffffff814b3741)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/bounce.c (ffffffff814be4d6)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
  - block/bounce.c:blk_queue_bounce
  - block/bounce.c:copy_to_high_bio_irq
  - block/bounce.c:copy_to_high_bio_irq
```
```
In block/bio-integrity.c (ffffffff814c9ae1)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/t10-pi.c (ffffffff814cb091)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_complete
  - block/t10-pi.c:t10_pi_prepare
```
```
In block/blk-zoned.c (ffffffff814cbd86)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In lib/scatterlist.c (ffffffff814d8cc1)
Location: include/linux/mm.h:1232
Inline: True
```
```
In lib/iov_iter.c (ffffffff814db012)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:memcpy_mcsafe_to_page
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
```
```
In drivers/acpi/osl.c (ffffffff81a2294a)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8160b9c9)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:return_free_pages_to_mm
```
```
In drivers/xen/grant-table.c (ffffffff8160cd25)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff8160e699)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff81668eae)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81677928)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81679060)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context_cmd
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff816797c0)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff8167a700)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
```
In drivers/iommu/amd_iommu.c (ffffffff81687db9)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:free_page_list
```
```
In drivers/iommu/dmar.c (ffffffff8168d336)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff816933f5)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
  - drivers/iommu/intel-iommu.c:dma_free_pagelist
  - drivers/iommu/intel-iommu.c:dma_pte_list_pagetables
  - drivers/iommu/intel-iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel-pasid.c (ffffffff8169409f)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel-svm.c (ffffffff81695a46)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81696fb4)
Location: include/linux/mm.h:1232
Inline: True
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff816bbab0)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_rw
```
```
In drivers/block/loop.c (ffffffff816ca77d)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff816d0770)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81702b8e)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8170ae5b)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:kmap_udmabuf
```
```
In drivers/scsi/scsi_lib.c (ffffffff8171359b)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/sd.c (ffffffff817231af)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sg.c (ffffffff81728a50)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_read_oxfer
```
```
In drivers/ata/libata-scsi.c (ffffffff817393c0)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
```
```
In drivers/ata/libata-sff.c (ffffffff8174667a)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/net/tun.c (ffffffff81762717)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff8176b7af)
Location: include/linux/mm.h:1232
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff81783a9b)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff8178ea7f)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/md/md.c (ffffffff81821c6b)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_90_sync
  - drivers/md/md.c:super_90_validate
```
```
In drivers/md/md-bitmap.c (ffffffff818305de)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (ffffffff81842d3c)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/firmware/efi/capsule.c (ffffffff81872d7f)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/sock.c (ffffffff81895674)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
```
```
In net/core/skbuff.c (ffffffff8189df88)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/datagram.c (ffffffff818a4e70)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/dev.c (ffffffff818ac5a9)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - net/core/dev.c:skb_gro_reset_offset
```
```
In net/core/filter.c (ffffffff818d9610)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/tso.c (ffffffff818e0927)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/skmsg.c (ffffffff818e5ccd)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff8191bd2b)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff81928722)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff819961f5)
Location: include/linux/mm.h:1232
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff81a06425)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81a1c8aa)
Location: include/linux/mm.h:1232
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
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
In init/do_mounts.c (ffffffff8289a614)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/events/intel/bts.c (ffffffff8100e676)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:__bts_event_start
```
```
In arch/x86/events/intel/ds.c (ffffffff81010a3a)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff81014dd1)
Location: include/linux/mm.h:1300
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81027a68)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_mm_unpin_all
  - arch/x86/xen/mmu_pv.c:xen_mm_pin_all
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102d2c1)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81037ec2)
Location: include/linux/mm.h:1300
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ea23)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/kernel/kvmclock.c (ffffffff828b88e9)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8107ba95)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
```
```
In arch/x86/mm/init_64.c (ffffffff81a94929)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
```
```
In arch/x86/mm/pageattr.c (ffffffff81084ad6)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:kernel_page_present
  - arch/x86/mm/pageattr.c:__set_pages_np
  - arch/x86/mm/pageattr.c:__set_pages_p
  - arch/x86/mm/pageattr.c:set_pages_rw
  - arch/x86/mm/pageattr.c:set_pages_ro
  - arch/x86/mm/pageattr.c:set_pages_nx
  - arch/x86/mm/pageattr.c:set_pages_x
  - arch/x86/mm/pageattr.c:set_pages_wb
  - arch/x86/mm/pageattr.c:set_pages_uc
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c1aa2)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In kernel/power/snapshot.c (ffffffff811004f6)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/power/swap.c (0)
Location: include/linux/mm.h:1300
Inline: True
```
```
In kernel/dma/direct.c (ffffffff8112309a)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_alloc_pages
```
```
In kernel/dma/virt.c (ffffffff81123895)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - kernel/dma/virt.c:dma_virt_map_page
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/mm.h:1300
Inline: True
```
```
In kernel/profile.c (ffffffff81125915)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/kexec_core.c (ffffffff8114e296)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_add_entry
  - kernel/kexec_core.c:kimage_alloc_control_pages
  - kernel/kexec_core.c:kimage_free_pages
  - kernel/kexec_core.c:kimage_alloc_pages
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81180af0)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/trace/ring_buffer.c (ffffffff81194d1c)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff8119f322)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cc55e)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/stackmap.c (ffffffff811f6459)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/ring_buffer.c (ffffffff8120a36b)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff8120d49c)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In mm/truncate.c (ffffffff81226582)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff81235435)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/percpu.c (ffffffff828d3e06)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_page_first_chunk
```
```
In mm/slab_common.c (ffffffff812405bd)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/memory.c (ffffffff812572eb)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:copy_subpage
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/vmalloc.c (ffffffff81268ca4)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
```
```
In mm/page_alloc.c (ffffffff812728af)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:__get_free_pages
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/swapfile.c (ffffffff8127905e)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff8127f1dd)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/sparse-vmemmap.c (ffffffff81a9750c)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffff8129288e)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:memcmp_pages
  - mm/ksm.c:memcmp_pages
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff81292d21)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
```
```
In mm/slub.c (ffffffff81294715)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__check_heap_object
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
  - mm/slub.c:print_trailer
  - mm/slub.c:get_map
```
```
In mm/migrate.c (ffffffff8129e12a)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812a2aea)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812aac6d)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/swap_cgroup.c (ffffffff812b7785)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/zbud.c (ffffffff812bc8dc)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (ffffffff812bdf77)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/userfaultfd.c (ffffffff812c0ac6)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff812c9c81)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (ffffffff812d36ca)
Location: include/linux/mm.h:1300
Inline: True
```
```
In fs/namei.c (ffffffff812d7425)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - fs/namei.c:__page_symlink
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff812fa58c)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/splice.c (ffffffff81303a27)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - fs/splice.c:write_pipe_buf
  - fs/splice.c:default_file_splice_read
```
```
In fs/buffer.c (ffffffff8130f079)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - fs/buffer.c:guard_bio_eod
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/direct-io.c (ffffffff81315f1c)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff81317f39)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff8132b8bb)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_read_events
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:aio_setup_ring
```
```
In fs/dax.c (ffffffff81334a74)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/binfmt_elf.c (ffffffff813434f1)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff81346e49)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap/buffered-io.c (ffffffff8134c530)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inline.c (ffffffff8138e9e6)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff8139468f)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff813a1293)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff813a95e8)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813b2fb5)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813b3592)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff813ceb64)
Location: include/linux/mm.h:1300
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff813d73c3)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813d900c)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff813e1338)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff813e3d53)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff813e5c07)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff813e6434)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff813e6606)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_next_page
  - fs/squashfs/page_actor.c:direct_first_page
```
```
In fs/ecryptfs/mmap.c (ffffffff813fab7c)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff813fb410)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffffffff813fcc8f)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/dev.c (ffffffff81406229)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_do
```
```
In fs/fuse/dir.c (ffffffff81409ea3)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readlink_page
```
```
In fs/fuse/file.c (ffffffff8140d2ee)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_short_read
```
```
In fs/fuse/readdir.c (ffffffff81416b1e)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/selinux/selinuxfs.c (ffffffff8144dbed)
Location: include/linux/mm.h:1300
Inline: True
```
```
In security/selinux/ss/status.c (ffffffff81460f94)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - security/selinux/ss/status.c:selinux_status_update_policyload
  - security/selinux/ss/status.c:selinux_status_update_setenforce
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
```
In security/tomoyo/domain.c (ffffffff81472fd3)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff814a6189)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff814a7dbe)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff814a973c)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff814aa599)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
  - crypto/ahash.c:hash_walk_next
```
```
In crypto/shash.c (ffffffff814abce2)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff814c791d)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:zero_fill_bio_iter
```
```
In block/blk-mq.c (ffffffff814d995d)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In block/partition-generic.c (ffffffff814e1ccb)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/bounce.c (ffffffff814ecc97)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:copy_to_high_bio_irq
  - block/bounce.c:copy_to_high_bio_irq
```
```
In block/bio-integrity.c (ffffffff814f81b1)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/t10-pi.c (ffffffff814f99dd)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_complete
  - block/t10-pi.c:t10_pi_prepare
```
```
In lib/scatterlist.c (ffffffff81504b74)
Location: include/linux/mm.h:1300
Inline: True
```
```
In lib/iov_iter.c (ffffffff81506936)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:memcpy_mcsafe_to_page
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
```
```
In drivers/acpi/osl.c (ffffffff81a929ee)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8163f697)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:return_free_pages_to_mm
```
```
In drivers/xen/grant-table.c (ffffffff816419c8)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff8164241e)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff8169e81d)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff816ac7e2)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_send
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff816ad5a7)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816af7f6)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff816afde9)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff816b10bb)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
```
In drivers/iommu/amd_iommu.c (ffffffff816c0b79)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:free_page_list
```
```
In drivers/iommu/dmar.c (ffffffff816c4d40)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff816c5900)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dma_free_pagelist
  - drivers/iommu/intel-iommu.c:dma_pte_list_pagetables
  - drivers/iommu/intel-iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel-pasid.c (ffffffff816cc9af)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel-svm.c (ffffffff816ce346)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816cf925)
Location: include/linux/mm.h:1300
Inline: True
```
```
In drivers/base/firmware_loader/main.c (ffffffff816f56c9)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff816f6261)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_rw
```
```
In drivers/block/loop.c (ffffffff81705d3d)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff8170a469)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8173ca3b)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
```
```
In drivers/dma-buf/udmabuf.c (ffffffff817465be)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:kmap_udmabuf
```
```
In drivers/scsi/scsi_lib.c (ffffffff8174ee81)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/sd.c (ffffffff817605fe)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/mm.h:1300
Inline: True
```
```
In drivers/ata/libata-scsi.c (ffffffff817753f5)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
```
```
In drivers/ata/libata-sff.c (ffffffff8178234b)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/net/tun.c (ffffffff817a0469)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff817a95b4)
Location: include/linux/mm.h:1300
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff817c1dae)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff817cb74e)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/md/md.c (ffffffff818647de)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_90_sync
  - drivers/md/md.c:super_90_validate
```
```
In drivers/md/md-bitmap.c (ffffffff81872c50)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (ffffffff81885b34)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/firmware/efi/capsule.c (ffffffff818b6f5f)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/sock.c (ffffffff818dfb94)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
```
```
In net/core/skbuff.c (ffffffff818e8757)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_dump
```
```
In net/core/datagram.c (ffffffff818ef5cd)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/dev.c (ffffffff818f7e34)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - net/core/dev.c:skb_gro_reset_offset
```
```
In net/core/filter.c (ffffffff8192b7ec)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/tso.c (ffffffff8192efba)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/skmsg.c (ffffffff819355e7)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/ipv4/ip_output.c (ffffffff8197e020)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff8198b699)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81a02661)
Location: include/linux/mm.h:1300
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff81a75d4b)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81a8c4e0)
Location: include/linux/mm.h:1300
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
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
In init/do_mounts.c (ffffffff8289d5f9)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/events/intel/bts.c (ffffffff8100f1e7)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:__bts_event_start
```
```
In arch/x86/events/intel/ds.c (ffffffff8101111a)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff8101571d)
Location: include/linux/mm.h:1314
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81028048)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_mm_unpin_all
  - arch/x86/xen/mmu_pv.c:xen_mm_pin_all
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102dbd1)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81038692)
Location: include/linux/mm.h:1314
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ffd3)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/kernel/kvmclock.c (ffffffff828bedd7)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8107cb85)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
```
```
In arch/x86/mm/init_64.c (ffffffff81acc209)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
```
```
In arch/x86/mm/pageattr.c (ffffffff810857d6)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:kernel_page_present
  - arch/x86/mm/pageattr.c:__set_pages_np
  - arch/x86/mm/pageattr.c:__set_pages_p
  - arch/x86/mm/pageattr.c:set_pages_rw
  - arch/x86/mm/pageattr.c:set_pages_ro
  - arch/x86/mm/pageattr.c:set_pages_wb
  - arch/x86/mm/pageattr.c:set_pages_uc
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In kernel/power/snapshot.c (ffffffff8110c956)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/power/swap.c (0)
Location: include/linux/mm.h:1314
Inline: True
```
```
In kernel/dma/direct.c (ffffffff8112f4da)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_alloc_pages
```
```
In kernel/dma/virt.c (ffffffff8112f825)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/dma/virt.c:dma_virt_map_page
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/mm.h:1314
Inline: True
```
```
In kernel/profile.c (ffffffff811318e5)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/kexec_core.c (ffffffff81159fa6)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_add_entry
  - kernel/kexec_core.c:kimage_alloc_control_pages
  - kernel/kexec_core.c:kimage_free_pages
  - kernel/kexec_core.c:kimage_alloc_pages
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8118c960)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/trace/ring_buffer.c (ffffffff811a07dc)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811aace2)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d8b26)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/stackmap.c (ffffffff81203417)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/ring_buffer.c (ffffffff8121764b)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff8121a929)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In mm/truncate.c (ffffffff812343ee)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff81243675)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/util.c (ffffffff81245c2a)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
```
```
In mm/percpu.c (ffffffff828dc27d)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_page_first_chunk
```
```
In mm/slab_common.c (ffffffff8124eb34)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/memory.c (ffffffff8126587b)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:copy_subpage
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/vmalloc.c (ffffffff812775dc)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
```
```
In mm/page_alloc.c (ffffffff8128170f)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:__get_free_pages
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/swapfile.c (ffffffff81288b3e)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff8128ec3d)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/sparse-vmemmap.c (ffffffff81acedee)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffff812a2611)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff812a2aa1)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
```
```
In mm/slub.c (ffffffff812a44e5)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__check_heap_object
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
  - mm/slub.c:print_trailer
  - mm/slub.c:get_map
```
```
In mm/migrate.c (ffffffff812ad9da)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812b3fdd)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812bc23e)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/swap_cgroup.c (ffffffff812c9665)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/zbud.c (ffffffff812ce7cc)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (ffffffff812cfe67)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/userfaultfd.c (ffffffff812d2876)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff812db75f)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (ffffffff812e525a)
Location: include/linux/mm.h:1314
Inline: True
```
```
In fs/namei.c (ffffffff812e8f85)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/namei.c:__page_symlink
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff8130c30c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/splice.c (ffffffff81316aa7)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/splice.c:write_pipe_buf
  - fs/splice.c:default_file_splice_read
```
```
In fs/buffer.c (ffffffff81323c03)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/direct-io.c (ffffffff81328d9c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff8132adaf)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff8133e70b)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_read_events
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:aio_setup_ring
```
```
In fs/io_uring.c (ffffffff81340b50)
Location: include/linux/mm.h:1314
Inline: True
```
```
In fs/dax.c (ffffffff8134864c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/verity/verify.c (ffffffff813510dc)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/verity/verify.c:extract_hash
```
```
In fs/binfmt_elf.c (ffffffff8135b92f)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff8135f157)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap/buffered-io.c (ffffffff81364800)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inline.c (ffffffff813a7446)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff813ad00f)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff813ba119)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff813c2508)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813cc037)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813cc788)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff813e8234)
Location: include/linux/mm.h:1314
Inline: True
```
```
In fs/ext4/verity.c (ffffffff813eeddf)
Location: include/linux/mm.h:1314
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff813f13f3)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813f3005)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff813fb388)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff813fdd95)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff813ffc57)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff814004aa)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff81400686)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_next_page
  - fs/squashfs/page_actor.c:direct_first_page
```
```
In fs/ecryptfs/mmap.c (ffffffff81414a4c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff814152e0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffffffff81416b6f)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/dev.c (ffffffff81420d89)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_do
```
```
In fs/fuse/dir.c (ffffffff814234e3)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readlink_page
```
```
In fs/fuse/file.c (ffffffff814286f5)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (ffffffff81430a5a)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/selinux/selinuxfs.c (ffffffff81467a0d)
Location: include/linux/mm.h:1314
Inline: True
```
```
In security/selinux/ss/status.c (ffffffff8147ad44)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - security/selinux/ss/status.c:selinux_status_update_policyload
  - security/selinux/ss/status.c:selinux_status_update_setenforce
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
```
In security/tomoyo/domain.c (ffffffff8148cd73)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff814c0e19)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff814c2a1e)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff814c442c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff814c5259)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
  - crypto/ahash.c:hash_walk_next
```
```
In crypto/shash.c (ffffffff814c69c2)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff814e0a10)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_truncate
  - block/bio.c:zero_fill_bio_iter
```
```
In block/blk-mq.c (ffffffff814f2d1d)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In block/partition-generic.c (ffffffff814fb08a)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/bounce.c (ffffffff815060e4)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:copy_to_high_bio_irq
  - block/bounce.c:copy_to_high_bio_irq
```
```
In block/bio-integrity.c (ffffffff81515f91)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/t10-pi.c (ffffffff81517768)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/scatterlist.c (ffffffff81522cb4)
Location: include/linux/mm.h:1314
Inline: True
```
```
In lib/iov_iter.c (ffffffff81524a46)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:memcpy_mcsafe_to_page
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
```
```
In drivers/acpi/osl.c (ffffffff81aca1ae)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81661ab7)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:return_free_pages_to_mm
```
```
In drivers/xen/grant-table.c (ffffffff81662fd8)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff816649e7)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff816c18cd)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff816d0287)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816d24ef)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff816d2ae9)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff816d3dbb)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
```
In drivers/iommu/amd_iommu.c (ffffffff816e3ba9)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:free_page_list
```
```
In drivers/iommu/dmar.c (ffffffff816e7c70)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff816e8930)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dma_free_pagelist
  - drivers/iommu/intel-iommu.c:dma_pte_list_pagetables
  - drivers/iommu/intel-iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel-pasid.c (ffffffff816f01ec)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel-svm.c (ffffffff816f2186)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816f3765)
Location: include/linux/mm.h:1314
Inline: True
```
```
In drivers/base/firmware_loader/main.c (ffffffff81719ac9)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff8171a661)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_rw
```
```
In drivers/block/loop.c (ffffffff81729f8d)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff8172e769)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff817607de)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8176a70e)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:kmap_udmabuf
```
```
In drivers/scsi/scsi_lib.c (ffffffff8177305d)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/sd.c (ffffffff8178458f)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/mm.h:1314
Inline: True
```
```
In drivers/ata/libata-scsi.c (ffffffff81799365)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
```
```
In drivers/ata/libata-sff.c (ffffffff817a5ffb)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/net/tun.c (ffffffff817c5416)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff817cd024)
Location: include/linux/mm.h:1314
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff817f272e)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff817fc3ae)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/md/md.c (ffffffff8189651e)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_90_sync
  - drivers/md/md.c:super_90_validate
```
```
In drivers/md/md-bitmap.c (ffffffff818a4a50)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (ffffffff818b7ad4)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/firmware/efi/capsule.c (ffffffff818e98bf)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/sock.c (ffffffff81911d44)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
```
```
In net/core/skbuff.c (ffffffff8191a997)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_dump
```
```
In net/core/datagram.c (ffffffff81921569)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/dev.c (ffffffff81929be4)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/dev.c:skb_gro_reset_offset
```
```
In net/core/filter.c (ffffffff8195db0b)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/tso.c (ffffffff8196122b)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/skmsg.c (ffffffff819683a7)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/ipv4/ip_output.c (ffffffff819b4a35)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff819c1edf)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81a39239)
Location: include/linux/mm.h:1314
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff81aacd1d)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81ac37a0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
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
In init/do_mounts.c (ffffffff82cc3c8d)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/events/intel/bts.c (ffffffff81010309)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:__bts_event_start
```
```
In arch/x86/events/intel/ds.c (ffffffff81010ddb)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff81016c1d)
Location: include/linux/mm.h:1488
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81029f58)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_mm_unpin_all
  - arch/x86/xen/mmu_pv.c:xen_mm_pin_all
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102feb9)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103b0e0)
Location: include/linux/mm.h:1488
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810773f3)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/kernel/kvmclock.c (ffffffff82ce30c7)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
```
```
In arch/x86/mm/init_64.c (ffffffff81bc41e7)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pte_table
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108f599)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:kernel_page_present
  - arch/x86/mm/pat/set_memory.c:set_direct_map_default_noflush
  - arch/x86/mm/pat/set_memory.c:set_direct_map_invalid_noflush
  - arch/x86/mm/pat/set_memory.c:set_pages_rw
  - arch/x86/mm/pat/set_memory.c:set_pages_ro
  - arch/x86/mm/pat/set_memory.c:set_pages_wb
  - arch/x86/mm/pat/set_memory.c:set_pages_uc
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb
```
```
In kernel/power/snapshot.c (ffffffff81117bc7)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:safe_copy_page
  - kernel/power/snapshot.c:safe_copy_page
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/power/swap.c (0)
Location: include/linux/mm.h:1488
Inline: True
```
```
In kernel/dma/direct.c (ffffffff8113e0aa)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_alloc_pages
```
```
In kernel/dma/virt.c (ffffffff8113e62a)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - kernel/dma/virt.c:dma_virt_map_sg
  - kernel/dma/virt.c:dma_virt_map_page
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/mm.h:1488
Inline: True
```
```
In kernel/profile.c (ffffffff81140c55)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/time/namespace.c (ffffffff81159d12)
Location: include/linux/mm.h:1488
Inline: True
```
```
In kernel/kexec_core.c (ffffffff8116a0c7)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_normal_segment
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_add_entry
  - kernel/kexec_core.c:kimage_alloc_crash_control_pages
  - kernel/kexec_core.c:kimage_free_pages
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811a131e)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/trace/ring_buffer.c (ffffffff811b6dbc)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811c2fb0)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f4fc0)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
```
```
In kernel/bpf/stackmap.c (ffffffff8122b198)
Location: include/linux/mm.h:1488
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff81242efb)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff81247320)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In kernel/watch_queue.c (ffffffff8124ca86)
Location: include/linux/mm.h:1488
Inline: True
```
```
In mm/truncate.c (ffffffff812619bb)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff8126f835)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/util.c (ffffffff812739aa)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
```
```
In mm/percpu.c (ffffffff82cfa38b)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_page_first_chunk
```
```
In mm/slab_common.c (ffffffff8127cdf4)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/memory.c (ffffffff81295bd3)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:copy_subpage
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:do_cow_fault
  - mm/memory.c:do_cow_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/vmalloc.c (ffffffff812abe1f)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
```
```
In mm/page_alloc.c (ffffffff812b3bf5)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:get_zeroed_page
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/swapfile.c (ffffffff812bb7de)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff812c19c5)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/sparse-vmemmap.c (ffffffff81bc77b0)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffff812d6d37)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff812d71ee)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - mm/page_poison.c:poison_pages
```
```
In mm/slub.c (ffffffff812d9005)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__check_heap_object
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:deactivate_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:print_trailer
  - mm/slub.c:get_map
```
```
In mm/migrate.c (ffffffff812e2eb8)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:copy_huge_page
  - mm/migrate.c:copy_huge_page
  - mm/migrate.c:__copy_gigantic_page
  - mm/migrate.c:__copy_gigantic_page
```
```
In mm/khugepaged.c (ffffffff812f1776)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_copy
  - mm/khugepaged.c:__collapse_huge_page_copy
  - mm/khugepaged.c:__collapse_huge_page_copy
```
```
In mm/swap_cgroup.c (ffffffff812fecd5)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/zbud.c (ffffffff81304aa0)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (ffffffff81306fcf)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:find_alloced_obj
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:obj_free
  - mm/zsmalloc.c:obj_malloc
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:init_zspage
```
```
In mm/userfaultfd.c (ffffffff8130879e)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/read_write.c (ffffffff8131170b)
Location: include/linux/mm.h:1488
Inline: True
```
```
In fs/exec.c (ffffffff8131c47f)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - fs/exec.c:copy_string_kernel
```
```
In fs/namei.c (ffffffff81321645)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - fs/namei.c:__page_symlink
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff813457f2)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/splice.c (ffffffff813501f5)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - fs/splice.c:write_pipe_buf
```
```
In fs/buffer.c (ffffffff8135ca73)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - fs/buffer.c:block_write_full_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_expand_zero
  - fs/buffer.c:cont_expand_zero
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:page_zero_new_buffers
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/direct-io.c (ffffffff81362e47)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff8136481b)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff813783b7)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_complete
  - fs/aio.c:aio_complete
  - fs/aio.c:ioctx_add_table
  - fs/aio.c:aio_setup_ring
```
```
In fs/io_uring.c (ffffffff8137c0a6)
Location: include/linux/mm.h:1488
Inline: True
```
```
In fs/dax.c (ffffffff8138e8af)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_writeback_one
```
```
In fs/verity/verify.c (ffffffff81397b4c)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - fs/verity/verify.c:extract_hash
```
```
In fs/binfmt_elf.c (ffffffff813a0471)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff813a3727)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap/buffered-io.c (ffffffff813aca8f)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_write_end_inline
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inline.c (ffffffff813f35e6)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff813f933d)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff81405d1a)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_get_buddy_page_lock
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff8140ec1d)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff81418160)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff81418af1)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff81434d91)
Location: include/linux/mm.h:1488
Inline: True
```
```
In fs/ext4/verity.c (ffffffff8143c3c2)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/transaction.c (ffffffff8143c92d)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_freeze_jh_data
```
```
In fs/jbd2/commit.c (ffffffff814408e1)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_block_tag_csum_set
```
```
In fs/jbd2/journal.c (ffffffff81448afb)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/block.c (ffffffff814498f9)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:copy_bio_to_actor
```
```
In fs/squashfs/file.c (ffffffff8144b7f3)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff8144d615)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff8144debc)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff8144e038)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_next_page
  - fs/squashfs/page_actor.c:direct_first_page
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff8144eb8c)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff8144ef53)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff8144f276)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff8144f5c4)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff8144f8b8)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In fs/ecryptfs/mmap.c (ffffffff81462cd2)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff814635a0)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffffffff8146515b)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/dev.c (ffffffff8146fe11)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/dir.c (ffffffff81472a53)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readlink_page
```
```
In fs/fuse/file.c (ffffffff814763cc)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (ffffffff814805cc)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In security/selinux/selinuxfs.c (ffffffff814bb56d)
Location: include/linux/mm.h:1488
Inline: True
```
```
In security/selinux/status.c (ffffffff814be58b)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - security/selinux/status.c:selinux_status_update_policyload
  - security/selinux/status.c:selinux_status_update_setenforce
  - security/selinux/status.c:selinux_kernel_status_page
```
```
In security/tomoyo/domain.c (ffffffff814e3fff)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff815216c3)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (ffffffff8152338a)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_next_copy
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff8152417e)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
  - crypto/ahash.c:hash_walk_next
```
```
In crypto/shash.c (ffffffff81525c8b)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff8153e584)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:zero_fill_bio_iter
```
```
In block/blk-map.c (ffffffff8154a051)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:bio_copy_kern_endio_read
```
```
In block/blk-mq.c (ffffffff815532ec)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In block/partitions/core.c (ffffffff8155ddca)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
```
```
In block/bounce.c (ffffffff81566c8a)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:copy_to_high_bio_irq
  - block/bounce.c:copy_to_high_bio_irq
```
```
In block/bio-integrity.c (ffffffff8157692a)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/t10-pi.c (ffffffff81577f29)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/scatterlist.c (ffffffff81585c8e)
Location: include/linux/mm.h:1488
Inline: True
```
```
In lib/iov_iter.c (ffffffff81589259)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:memcpy_mcsafe_to_page
  - lib/iov_iter.c:csum_and_copy_to_pipe_iter
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
  - lib/iov_iter.c:copy_page_from_iter_iovec
  - lib/iov_iter.c:copy_page_to_iter_iovec
```
```
In arch/x86/lib/usercopy_64.c (ffffffff815ffca0)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
```
```
In drivers/acpi/osl.c (ffffffff81bc27fe)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8170fa28)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:get_free_page_and_send
  - drivers/virtio/virtio_balloon.c:return_free_pages_to_mm
```
```
In drivers/xen/grant-table.c (ffffffff8171350c)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81714567)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff81774e4c)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/iommu/dma-iommu.c (ffffffff817921b2)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
```
```
In drivers/iommu/amd/iommu.c (ffffffff81799ae8)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:iommu_map_page
```
```
In drivers/iommu/intel/dmar.c (ffffffff8179e7b0)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff817a2912)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_unmap
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
  - drivers/iommu/intel/iommu.c:intel_alloc_coherent
  - drivers/iommu/intel/iommu.c:intel_alloc_coherent
  - drivers/iommu/intel/iommu.c:intel_unmap
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:domain_exit
  - drivers/iommu/intel/iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel/iommu.c:iova_entry_free
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff817a78cf)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/svm.c (ffffffff817a9fd6)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817ab9f8)
Location: include/linux/mm.h:1488
Inline: True
```
```
In drivers/base/firmware_loader/main.c (ffffffff817d5af1)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz_pages
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff817d6681)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_rw
```
```
In drivers/block/loop.c (ffffffff817e8015)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff817eec77)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff818205ed)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_clear_memmap_errors
```
```
In drivers/scsi/scsicam.c (ffffffff818302ad)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/scsi/scsi_lib.c (ffffffff81834cee)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/sd.c (ffffffff8184437f)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_unmap_cmnd
  - drivers/scsi/sd.c:sd_setup_unmap_cmnd
```
```
In drivers/scsi/sg.c (ffffffff8184e889)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read_oxfer
```
```
In drivers/ata/libata-sff.c (ffffffff8186a2d4)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/net/tun.c (ffffffff8188cd54)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/xen-netfront.c (ffffffff81896dd3)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_release_rx_bufs
  - drivers/net/xen-netfront.c:xennet_release_tx_bufs
```
```
In drivers/usb/core/message.c (ffffffff818c20ab)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff818cde1e)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/md/md.c (ffffffff81963e91)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:does_sb_need_changing
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_90_sync
  - drivers/md/md.c:super_90_validate
```
```
In drivers/md/md-bitmap.c (ffffffff81974413)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (ffffffff81987d4e)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/firmware/efi/capsule.c (ffffffff819bcfc9)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In drivers/firmware/efi/memmap.c (ffffffff82d2a4fe)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:__efi_memmap_free
```
```
In net/core/sock.c (ffffffff819e3c97)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
```
```
In net/core/skbuff.c (ffffffff819ecfa2)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:linear_to_page
  - net/core/skbuff.c:linear_to_page
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/datagram.c (ffffffff819f5703)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/dev.c (ffffffff819fdc1b)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - net/core/dev.c:skb_gro_reset_offset
```
```
In net/core/filter.c (ffffffff81a2cc50)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/tso.c (ffffffff81a3475e)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/skmsg.c (ffffffff81a3bdeb)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/ipv4/ip_output.c (ffffffff81a9eb8a)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81aad70b)
Location: include/linux/mm.h:1488
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81b2e968)
Location: include/linux/mm.h:1488
Inline: True
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
In init/do_mounts.c (ffffffff82fafdbb)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/events/intel/bts.c (ffffffff8100f869)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:__bts_event_start
```
```
In arch/x86/events/intel/ds.c (ffffffff8101043a)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff810170bd)
Location: include/linux/mm.h:1529
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102a938)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_mm_unpin_all
  - arch/x86/xen/mmu_pv.c:xen_mm_pin_all
```
```
In arch/x86/hyperv/hv_init.c (ffffffff81030ae9)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103b8f0)
Location: include/linux/mm.h:1529
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81066196)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81067236)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_init
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81067f6a)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077a23)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/kernel/kvmclock.c (ffffffff82fd03c3)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
```
```
In arch/x86/mm/init_64.c (ffffffff81c3d0e9)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pte_table
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108f359)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:kernel_page_present
  - arch/x86/mm/pat/set_memory.c:set_direct_map_default_noflush
  - arch/x86/mm/pat/set_memory.c:set_direct_map_invalid_noflush
  - arch/x86/mm/pat/set_memory.c:set_pages_rw
  - arch/x86/mm/pat/set_memory.c:set_pages_ro
  - arch/x86/mm/pat/set_memory.c:set_pages_wb
  - arch/x86/mm/pat/set_memory.c:set_pages_uc
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb
```
```
In kernel/power/snapshot.c (ffffffff81114007)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:safe_copy_page
  - kernel/power/snapshot.c:safe_copy_page
  - kernel/power/snapshot.c:safe_copy_page
  - kernel/power/snapshot.c:clear_or_poison_free_page
```
```
In kernel/power/swap.c (0)
Location: include/linux/mm.h:1529
Inline: True
```
```
In kernel/dma/mapping.c (ffffffff81137aa9)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_alloc_noncoherent
```
```
In kernel/dma/direct.c (ffffffff81138fc9)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc
```
```
In kernel/dma/ops_helpers.c (ffffffff81139c30)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/mm.h:1529
Inline: True
```
```
In kernel/profile.c (ffffffff8113cf85)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/time/namespace.c (ffffffff811561ee)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - kernel/time/namespace.c:timens_commit
```
```
In kernel/kexec_core.c (ffffffff81166807)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_normal_segment
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_add_entry
  - kernel/kexec_core.c:kimage_alloc_crash_control_pages
  - kernel/kexec_core.c:kimage_free_pages
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8119e46e)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/trace/ring_buffer.c (ffffffff811b4973)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811c0bc0)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f3950)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
```
```
In kernel/bpf/stackmap.c (ffffffff812330cc)
Location: include/linux/mm.h:1529
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff8124d59b)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff8125199c)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In kernel/watch_queue.c (ffffffff81256ec6)
Location: include/linux/mm.h:1529
Inline: True
```
```
In mm/truncate.c (ffffffff8126ad98)
Location: include/linux/mm.h:1529
Inline: True
```
```
In mm/shmem.c (ffffffff8127aba5)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
```
```
In mm/util.c (ffffffff8127e23a)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
```
```
In mm/percpu.c (ffffffff82fe70ec)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_page_first_chunk
```
```
In mm/slab_common.c (ffffffff81288c95)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/memory.c (ffffffff812a0b7e)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:do_cow_fault
  - mm/memory.c:do_cow_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/vmalloc.c (ffffffff812b733f)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
```
```
In mm/page_alloc.c (ffffffff812bf6b0)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:get_zeroed_page
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/swapfile.c (ffffffff812c727e)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff812cd639)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/sparse-vmemmap.c (ffffffff81c404e4)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffff812e28c7)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff812e2d82)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - mm/page_poison.c:__kernel_unpoison_pages
  - mm/page_poison.c:__kernel_poison_pages
```
```
In mm/slub.c (ffffffff812e4611)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:kfree
  - mm/slub.c:__check_heap_object
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:deactivate_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:print_trailer
  - mm/slub.c:get_map
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/migrate.c (ffffffff812ee2f8)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:copy_huge_page
  - mm/migrate.c:copy_huge_page
  - mm/migrate.c:__copy_gigantic_page
  - mm/migrate.c:__copy_gigantic_page
```
```
In mm/khugepaged.c (ffffffff812fdccb)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff81308b3c)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
```
```
In mm/swap_cgroup.c (ffffffff8130b015)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/zbud.c (ffffffff813107f5)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (ffffffff81312d0f)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:find_alloced_obj
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:obj_free
  - mm/zsmalloc.c:obj_malloc
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:init_zspage
```
```
In mm/userfaultfd.c (ffffffff81314574)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/exec.c (ffffffff8132795f)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - fs/exec.c:copy_string_kernel
```
```
In fs/namei.c (ffffffff8132cbe5)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - fs/namei.c:__page_symlink
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff81351fe9)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - fs/libfs.c:simple_readpage
```
```
In fs/remap_range.c (ffffffff81366a8b)
Location: include/linux/mm.h:1529
Inline: True
```
```
In fs/buffer.c (ffffffff81367a91)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/direct-io.c (ffffffff8136f3b8)
Location: include/linux/mm.h:1529
Inline: True
```
```
In fs/mpage.c (ffffffff813712b3)
Location: include/linux/mm.h:1529
Inline: True
```
```
In fs/aio.c (ffffffff813860be)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_complete
  - fs/aio.c:aio_complete
  - fs/aio.c:ioctx_add_table
  - fs/aio.c:aio_setup_ring
```
```
In fs/dax.c (ffffffff813a000d)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_writeback_one
```
```
In fs/verity/verify.c (ffffffff813a93cc)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - fs/verity/verify.c:extract_hash
```
```
In fs/coredump.c (ffffffff813b95cc)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
```
```
In fs/iomap/buffered-io.c (ffffffff813bca47)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end_inline
```
```
In fs/ext4/inline.c (ffffffff81405d76)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff81408404)
Location: include/linux/mm.h:1529
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff81418fbc)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_get_buddy_page_lock
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff81421d28)
Location: include/linux/mm.h:1529
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff8142aed3)
Location: include/linux/mm.h:1529
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff8142c688)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff8144d871)
Location: include/linux/mm.h:1529
Inline: True
```
```
In fs/ext4/verity.c (ffffffff81458712)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/transaction.c (ffffffff81458cad)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_freeze_jh_data
```
```
In fs/jbd2/commit.c (ffffffff8145cb0e)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_block_tag_csum_set
```
```
In fs/jbd2/journal.c (ffffffff814656f1)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/block.c (ffffffff81466073)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:copy_bio_to_actor
```
```
In fs/squashfs/file.c (ffffffff81467ed3)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff81469c55)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff8146a473)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff8146a5d8)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_next_page
  - fs/squashfs/page_actor.c:direct_first_page
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff8146b17c)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff8146b513)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff8146b816)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff8146bb44)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff8146be18)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In fs/ecryptfs/mmap.c (ffffffff8147e554)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff8147ede0)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffffffff81480a04)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/dev.c (ffffffff8148a6ae)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/dir.c (ffffffff8148d3e9)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readlink_page
```
```
In fs/fuse/file.c (ffffffff81490e37)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (ffffffff8149bcaf)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In security/selinux/selinuxfs.c (ffffffff814d8f4d)
Location: include/linux/mm.h:1529
Inline: True
```
```
In security/selinux/status.c (ffffffff814dbfab)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - security/selinux/status.c:selinux_status_update_policyload
  - security/selinux/status.c:selinux_status_update_setenforce
  - security/selinux/status.c:selinux_kernel_status_page
```
```
In security/tomoyo/domain.c (ffffffff81501428)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff8153e533)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (ffffffff815402da)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_next_copy
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff81541025)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
```
```
In crypto/shash.c (ffffffff81542bbb)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff8155af7d)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:zero_fill_bio_iter
```
```
In block/blk-map.c (ffffffff81565e01)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:bio_copy_kern_endio_read
```
```
In block/blk-mq.c (ffffffff8156f97c)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In block/partitions/core.c (ffffffff81579bd9)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
```
```
In block/bounce.c (ffffffff81581af0)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:copy_to_high_bio_irq
  - block/bounce.c:copy_to_high_bio_irq
```
```
In block/bio-integrity.c (ffffffff815932f8)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/t10-pi.c (ffffffff81594ba9)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/scatterlist.c (ffffffff815a2d6e)
Location: include/linux/mm.h:1529
Inline: True
```
```
In lib/iov_iter.c (ffffffff815a58ee)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:copy_mc_pipe_to_iter
  - lib/iov_iter.c:csum_and_copy_to_pipe_iter
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
  - lib/iov_iter.c:copy_page_from_iter_iovec
  - lib/iov_iter.c:copy_page_to_iter_iovec
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81624b90)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
```
```
In drivers/acpi/osl.c (ffffffff81c3b84c)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8172c828)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:get_free_page_and_send
  - drivers/virtio/virtio_balloon.c:return_free_pages_to_mm
```
```
In drivers/xen/grant-table.c (ffffffff817303fc)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81730c47)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff8178fb9c)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/iommu/amd/iommu.c (ffffffff817a8218)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:iommu_map_page
```
```
In drivers/iommu/intel/dmar.c (ffffffff817ac500)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff817af1d3)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_tlb_sync
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:domain_exit
  - drivers/iommu/intel/iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff817b376f)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/svm.c (ffffffff817b6476)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817b7dd8)
Location: include/linux/mm.h:1529
Inline: True
```
```
In drivers/iommu/dma-iommu.c (ffffffff817be987)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
  - drivers/iommu/dma-iommu.c:iommu_dma_entry_dtor
```
```
In drivers/base/firmware_loader/main.c (ffffffff817ea501)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz_pages
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff817eb0b1)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_rw
```
```
In drivers/block/loop.c (ffffffff817fcf75)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff81803577)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8182f4dd)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_clear_memmap_errors
```
```
In drivers/scsi/scsicam.c (ffffffff81840f24)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/scsi/scsi_lib.c (ffffffff81845dbe)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/sd.c (ffffffff81854698)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_unmap_cmnd
  - drivers/scsi/sd.c:sd_setup_unmap_cmnd
```
```
In drivers/scsi/sg.c (ffffffff8185ec79)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read_oxfer
```
```
In drivers/ata/libata-sff.c (ffffffff818790e4)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/net/tun.c (ffffffff8189afbc)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/xen-netfront.c (ffffffff818a6bc3)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_release_rx_bufs
  - drivers/net/xen-netfront.c:xennet_release_tx_bufs
```
```
In drivers/usb/core/message.c (ffffffff818ce39b)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff818d8e16)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/md/md.c (ffffffff8196a781)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:does_sb_need_changing
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_90_sync
  - drivers/md/md.c:super_90_validate
```
```
In drivers/md/md-bitmap.c (ffffffff81979313)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (ffffffff8198bc7e)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/firmware/efi/memmap.c (ffffffff83018c1d)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:__efi_memmap_free
```
```
In drivers/firmware/efi/capsule.c (ffffffff819bed83)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/sock.c (ffffffff819e3627)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
```
```
In net/core/skbuff.c (ffffffff819ecc62)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:linear_to_page
  - net/core/skbuff.c:linear_to_page
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/datagram.c (ffffffff819f51c3)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/dev.c (ffffffff819fd76b)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - net/core/dev.c:skb_gro_reset_offset
```
```
In net/core/filter.c (ffffffff81a2e209)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/tso.c (ffffffff81a36ab6)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/skmsg.c (ffffffff81a3fecf)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/ipv4/ip_output.c (ffffffff81aa8acd)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81ab4a82)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81b3d3b8)
Location: include/linux/mm.h:1529
Inline: True
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
In init/do_mounts.c (ffffffff831b9e1e)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/events/intel/bts.c (ffffffff810108b9)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:__bts_event_start
```
```
In arch/x86/events/intel/ds.c (ffffffff810113ca)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff810181ad)
Location: include/linux/mm.h:1599
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102b528)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_mm_unpin_all
  - arch/x86/xen/mmu_pv.c:xen_mm_pin_all
```
```
In arch/x86/hyperv/hv_init.c (ffffffff81031610)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff81034074)
Location: include/linux/mm.h:1599
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103d28e)
Location: include/linux/mm.h:1599
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810665f6)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8106739f)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810684dd)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810784b3)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/kernel/kvmclock.c (ffffffff831db053)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
```
```
In arch/x86/mm/init_64.c (ffffffff81c2ee8f)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108fee9)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:kernel_page_present
  - arch/x86/mm/pat/set_memory.c:set_direct_map_default_noflush
  - arch/x86/mm/pat/set_memory.c:set_direct_map_invalid_noflush
  - arch/x86/mm/pat/set_memory.c:set_pages_rw
  - arch/x86/mm/pat/set_memory.c:set_pages_ro
  - arch/x86/mm/pat/set_memory.c:set_pages_wb
  - arch/x86/mm/pat/set_memory.c:set_pages_uc
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb
```
```
In kernel/power/snapshot.c (ffffffff81114906)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
```
In kernel/power/swap.c (0)
Location: include/linux/mm.h:1599
Inline: True
```
```
In kernel/dma/mapping.c (ffffffff81138b38)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_vmap_noncontiguous
```
```
In kernel/dma/direct.c (ffffffff8113a0a9)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc
```
```
In kernel/dma/ops_helpers.c (ffffffff8113ad50)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/mm.h:1599
Inline: True
```
```
In kernel/profile.c (ffffffff8113e1c5)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/time/namespace.c (ffffffff811575ee)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - kernel/time/namespace.c:timens_commit
```
```
In kernel/kexec_core.c (ffffffff811675a7)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_normal_segment
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_add_entry
  - kernel/kexec_core.c:kimage_alloc_crash_control_pages
  - kernel/kexec_core.c:kimage_free_pages
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8119f18c)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/trace/ring_buffer.c (ffffffff811b3d33)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811c1b42)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f4e36)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff81251edb)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff812557ce)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In kernel/watch_queue.c (ffffffff8125b356)
Location: include/linux/mm.h:1599
Inline: True
```
```
In mm/truncate.c (ffffffff8126ff4a)
Location: include/linux/mm.h:1599
Inline: True
```
```
In mm/shmem.c (ffffffff8127fd29)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
```
```
In mm/util.c (ffffffff812833aa)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
```
```
In mm/percpu.c (ffffffff831f180d)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_page_first_chunk
```
```
In mm/slab_common.c (ffffffff8128e345)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/memory.c (ffffffff812a64be)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/vmalloc.c (ffffffff812bd894)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
```
```
In mm/page_alloc.c (ffffffff812c4d30)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:get_zeroed_page
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/swapfile.c (ffffffff812cdb9e)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff812d40b8)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/sparse-vmemmap.c (ffffffff81c3258c)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffff812ea057)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff812ea4aa)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - mm/page_poison.c:__kernel_unpoison_pages
  - mm/page_poison.c:__kernel_poison_pages
```
```
In mm/slub.c (ffffffff812ebe71)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:kfree
  - mm/slub.c:__check_heap_object
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:kmem_obj_info
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:deactivate_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:print_trailer
  - mm/slub.c:get_map
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/migrate.c (ffffffff812f4419)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/khugepaged.c (ffffffff81304e41)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff8130f27f)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
```
```
In mm/swap_cgroup.c (ffffffff81311675)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/zbud.c (ffffffff813168c2)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (ffffffff81318013)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:obj_free
  - mm/zsmalloc.c:obj_malloc
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:alloc_zspage
```
```
In mm/userfaultfd.c (ffffffff8131a721)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/exec.c (ffffffff8132d70f)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - fs/exec.c:copy_string_kernel
```
```
In fs/namei.c (ffffffff813327a5)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - fs/namei.c:__page_symlink
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff81358cf9)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - fs/libfs.c:simple_readpage
```
```
In fs/remap_range.c (ffffffff8136d33b)
Location: include/linux/mm.h:1599
Inline: True
```
```
In fs/buffer.c (ffffffff8136e697)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/direct-io.c (ffffffff81375c6a)
Location: include/linux/mm.h:1599
Inline: True
```
```
In fs/mpage.c (ffffffff81377c65)
Location: include/linux/mm.h:1599
Inline: True
```
```
In fs/aio.c (ffffffff8138d20e)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_complete
  - fs/aio.c:aio_complete
  - fs/aio.c:ioctx_add_table
  - fs/aio.c:aio_setup_ring
```
```
In fs/dax.c (ffffffff813a75a3)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_writeback_one
```
```
In fs/verity/read_metadata.c (ffffffff813b0614)
Location: include/linux/mm.h:1599
Inline: True
```
```
In fs/verity/verify.c (ffffffff813b0903)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - fs/verity/verify.c:extract_hash
```
```
In fs/coredump.c (ffffffff813c0737)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
```
```
In fs/iomap/buffered-io.c (ffffffff813c4ab3)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/ext4/inline.c (ffffffff8140c0b6)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff8140e716)
Location: include/linux/mm.h:1599
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff8141f862)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff8142852a)
Location: include/linux/mm.h:1599
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff81431a45)
Location: include/linux/mm.h:1599
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff81433357)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff81453374)
Location: include/linux/mm.h:1599
Inline: True
```
```
In fs/ext4/verity.c (ffffffff8145e08e)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/transaction.c (ffffffff814603d3)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff814621a5)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff8146ae90)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/block.c (ffffffff8146b812)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:copy_bio_to_actor
```
```
In fs/squashfs/file.c (ffffffff8146d4d6)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff8146f351)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff8146fb46)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff8146fc98)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_next_page
  - fs/squashfs/page_actor.c:direct_first_page
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff8147083a)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff81470bd3)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff81470ec6)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff814711d3)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff814714a8)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In fs/ecryptfs/mmap.c (ffffffff81484028)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff81484970)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffffffff8148624d)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/dev.c (ffffffff8149017d)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/dir.c (ffffffff81492ae6)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readlink_page
```
```
In fs/fuse/file.c (ffffffff8149bc32)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (ffffffff814a0dcf)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In fs/fuse/ioctl.c (ffffffff814a1abc)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_do_ioctl
```
```
In security/selinux/selinuxfs.c (ffffffff814df8d2)
Location: include/linux/mm.h:1599
Inline: True
```
```
In security/selinux/status.c (ffffffff814e290b)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - security/selinux/status.c:selinux_status_update_policyload
  - security/selinux/status.c:selinux_status_update_setenforce
  - security/selinux/status.c:selinux_kernel_status_page
```
```
In security/tomoyo/domain.c (ffffffff81507f08)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff81546c03)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (ffffffff815487d0)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff81549689)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
```
```
In crypto/shash.c (ffffffff8154b25c)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff815637af)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:zero_fill_bio
```
```
In block/blk-map.c (ffffffff8156e35e)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:bio_copy_kern_endio_read
```
```
In block/blk-mq.c (ffffffff8157782c)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq.c:blk_mq_free_rqs
```
```
In block/partitions/core.c (ffffffff8158190c)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
```
```
In block/bio-integrity.c (ffffffff8159a0fa)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/t10-pi.c (ffffffff8159b96f)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/scatterlist.c (ffffffff815a9c9e)
Location: include/linux/mm.h:1599
Inline: True
```
```
In lib/iov_iter.c (ffffffff815ac9e9)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In lib/buildid.c (ffffffff815efed5)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81608540)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
```
```
In drivers/acpi/osl.c (ffffffff81c2e00c)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81711a05)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:return_free_pages_to_mm
```
```
In drivers/xen/grant-table.c (ffffffff81713f9c)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff817147d3)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff8177270c)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff8178ca41)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_page
```
```
In drivers/iommu/intel/dmar.c (ffffffff8178f3d0)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff81791bb3)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_tlb_sync
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:domain_exit
  - drivers/iommu/intel/iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff8179689f)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/svm.c (ffffffff81799706)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff8179af44)
Location: include/linux/mm.h:1599
Inline: True
```
```
In drivers/iommu/dma-iommu.c (ffffffff817a1827)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
  - drivers/iommu/dma-iommu.c:iommu_dma_entry_dtor
```
```
In drivers/base/firmware_loader/main.c (ffffffff817cec96)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff817cf833)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_rw
```
```
In drivers/block/loop.c (ffffffff817e1a03)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff817e7d3d)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81812615)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_clear_memmap_errors
```
```
In drivers/scsi/scsicam.c (ffffffff81824114)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/scsi/scsi_lib.c (ffffffff8182905e)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/sd.c (ffffffff81838238)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_unmap_cmnd
  - drivers/scsi/sd.c:sd_setup_unmap_cmnd
```
```
In drivers/scsi/sg.c (ffffffff81842c49)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read_oxfer
```
```
In drivers/ata/libata-sff.c (ffffffff8185b924)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-sff.c:ata_pio_xfer
```
```
In drivers/net/tun.c (ffffffff8187d833)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/xen-netfront.c (ffffffff8188a340)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
```
In drivers/usb/core/message.c (ffffffff818b166e)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff818bbfa5)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/md/md.c (ffffffff8194e591)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_90_sync
  - drivers/md/md.c:super_90_validate
```
```
In drivers/md/md-bitmap.c (ffffffff8195d8d0)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (ffffffff81970aa2)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_ce_error
```
```
In drivers/firmware/efi/memmap.c (ffffffff83223c15)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:__efi_memmap_free
```
```
In drivers/firmware/efi/capsule.c (ffffffff819a3484)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/sock.c (ffffffff819c96a7)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
```
```
In net/core/skbuff.c (ffffffff819d313a)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/datagram.c (ffffffff819db34b)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/dev.c (ffffffff819f2623)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
```
```
In net/core/filter.c (ffffffff81a14e89)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/tso.c (ffffffff81a1dc31)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/skmsg.c (ffffffff81a4e772)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/ipv4/ip_output.c (ffffffff81a93bea)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81a9fc19)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81b2a838)
Location: include/linux/mm.h:1599
Inline: True
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
In init/do_mounts.c (ffffffff8329a24d)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:do_mount_root
```
```
In arch/x86/events/intel/bts.c (ffffffff8101155f)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:__bts_event_start
```
```
In arch/x86/events/intel/ds.c (ffffffff810121cc)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff81019a91)
Location: include/linux/mm.h:1610
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102fc88)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_mm_unpin_all
  - arch/x86/xen/mmu_pv.c:xen_mm_pin_all
```
```
In arch/x86/hyperv/hv_init.c (ffffffff832a5c92)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff81039314)
Location: include/linux/mm.h:1610
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81042dcb)
Location: include/linux/mm.h:1610
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81070740)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8107171b)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81072992)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81085d13)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/kernel/kvmclock.c (ffffffff832be397)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
```
```
In arch/x86/mm/init_64.c (ffffffff81d4d590)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109f9ca)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:kernel_page_present
  - arch/x86/mm/pat/set_memory.c:set_direct_map_default_noflush
  - arch/x86/mm/pat/set_memory.c:set_direct_map_invalid_noflush
  - arch/x86/mm/pat/set_memory.c:set_pages_rw
  - arch/x86/mm/pat/set_memory.c:set_pages_ro
  - arch/x86/mm/pat/set_memory.c:set_pages_wb
  - arch/x86/mm/pat/set_memory.c:set_pages_uc
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb
```
```
In kernel/power/snapshot.c (ffffffff81134a46)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
```
In kernel/power/swap.c (0)
Location: include/linux/mm.h:1610
Inline: True
```
```
In kernel/dma/mapping.c (ffffffff8115ba48)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_vmap_noncontiguous
```
```
In kernel/dma/direct.c (ffffffff8115d110)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc
```
```
In kernel/dma/ops_helpers.c (ffffffff8115dc80)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/mm.h:1610
Inline: True
```
```
In kernel/profile.c (ffffffff8116154f)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/time/namespace.c (ffffffff8117c44a)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - kernel/time/namespace.c:timens_commit
```
```
In kernel/kexec_core.c (ffffffff8118cd57)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_normal_segment
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_add_entry
  - kernel/kexec_core.c:kimage_alloc_crash_control_pages
  - kernel/kexec_core.c:kimage_free_pages
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811c900c)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/trace/ring_buffer.c (ffffffff811ddd07)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811ec6e2)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff81227031)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff8128d768)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff8129147e)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In kernel/watch_queue.c (ffffffff8129715c)
Location: include/linux/mm.h:1610
Inline: True
```
```
In mm/truncate.c (ffffffff812ad34a)
Location: include/linux/mm.h:1610
Inline: True
```
```
In mm/shmem.c (ffffffff812be039)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
```
```
In mm/util.c (ffffffff812c156a)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
  - mm/util.c:copy_huge_page
  - mm/util.c:copy_huge_page
```
```
In mm/percpu.c (ffffffff832d717e)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_page_first_chunk
```
```
In mm/slab_common.c (ffffffff812ce267)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/memory.c (ffffffff812e797e)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/vmalloc.c (ffffffff81300083)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
```
```
In mm/page_alloc.c (ffffffff813091e0)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:get_zeroed_page
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/swapfile.c (ffffffff8131301e)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff81319d82)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/sparse-vmemmap.c (ffffffff81d510cf)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffff81331f79)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff813323ca)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - mm/page_poison.c:__kernel_unpoison_pages
  - mm/page_poison.c:__kernel_poison_pages
```
```
In mm/slub.c (ffffffff81333eda)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__check_heap_object
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:kmem_obj_info
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:deactivate_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:print_trailer
  - mm/slub.c:__fill_map
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/migrate.c (ffffffff8133e788)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/khugepaged.c (ffffffff8134ebd4)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff8135a123)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
```
```
In mm/swap_cgroup.c (ffffffff8135c9ec)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/zbud.c (ffffffff81362aec)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (ffffffff81364519)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:obj_free
  - mm/zsmalloc.c:obj_malloc
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:alloc_zspage
```
```
In mm/secretmem.c (ffffffff81366392)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_freepage
  - mm/secretmem.c:secretmem_fault
```
```
In mm/userfaultfd.c (ffffffff81367f4f)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/exec.c (ffffffff8137af3f)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - fs/exec.c:copy_string_kernel
```
```
In fs/namei.c (ffffffff8137ff35)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - fs/namei.c:__page_symlink
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff813a7359)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - fs/libfs.c:simple_readpage
```
```
In fs/remap_range.c (ffffffff813bc01b)
Location: include/linux/mm.h:1610
Inline: True
```
```
In fs/buffer.c (ffffffff813bd928)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/direct-io.c (ffffffff813c209d)
Location: include/linux/mm.h:1610
Inline: True
```
```
In fs/mpage.c (ffffffff813c42f5)
Location: include/linux/mm.h:1610
Inline: True
```
```
In fs/aio.c (ffffffff813da96e)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_complete
  - fs/aio.c:aio_complete
  - fs/aio.c:ioctx_add_table
  - fs/aio.c:aio_setup_ring
```
```
In fs/dax.c (ffffffff813f4d81)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
  - fs/dax.c:dax_fault_cow_page
  - fs/dax.c:dax_writeback_one
```
```
In fs/verity/read_metadata.c (ffffffff81400204)
Location: include/linux/mm.h:1610
Inline: True
```
```
In fs/verity/verify.c (ffffffff814004e3)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - fs/verity/verify.c:extract_hash
```
```
In fs/coredump.c (ffffffff814105a3)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
```
```
In fs/iomap/buffered-io.c (ffffffff81414247)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_inline_data
```
```
In fs/ext4/inline.c (ffffffff8145efb6)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff814615f0)
Location: include/linux/mm.h:1610
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff81472f64)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff8147c22d)
Location: include/linux/mm.h:1610
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff81485265)
Location: include/linux/mm.h:1610
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff814864f5)
Location: include/linux/mm.h:1610
Inline: True
```
```
In fs/ext4/symlink.c (ffffffff814a7354)
Location: include/linux/mm.h:1610
Inline: True
```
```
In fs/ext4/verity.c (ffffffff814b35ae)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/transaction.c (ffffffff814b5856)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff814b769b)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff814c16a0)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/block.c (ffffffff814c2060)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:copy_bio_to_actor
```
```
In fs/squashfs/file.c (ffffffff814c3d6e)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff814c5d41)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff814c659c)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff814c6708)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_next_page
  - fs/squashfs/page_actor.c:direct_first_page
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff814c72aa)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff814c7643)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff814c7936)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff814c7c63)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff814c7f38)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In fs/ecryptfs/mmap.c (ffffffff814db2fe)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff814dbff0)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffffffff814dd9dd)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/dev.c (ffffffff814e7bab)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/dir.c (ffffffff814ea4c6)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readlink_page
```
```
In fs/fuse/file.c (ffffffff814f362a)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (ffffffff814f8cdb)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In fs/fuse/ioctl.c (ffffffff814f9b8f)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_do_ioctl
```
```
In security/selinux/selinuxfs.c (ffffffff81537412)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_read_handle_status
```
```
In security/selinux/status.c (ffffffff8153bacb)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - security/selinux/status.c:selinux_status_update_policyload
  - security/selinux/status.c:selinux_status_update_setenforce
  - security/selinux/status.c:selinux_kernel_status_page
```
```
In security/tomoyo/domain.c (ffffffff81565146)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff815a73e3)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (ffffffff815a8fb0)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff815a9e69)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
```
```
In crypto/shash.c (ffffffff815aba3c)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff815c70e4)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:zero_fill_bio
```
```
In block/blk-map.c (ffffffff815d281e)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:bio_copy_kern_endio_read
```
```
In block/blk-mq.c (ffffffff815dc54c)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq.c:blk_mq_free_rqs
```
```
In block/partitions/core.c (ffffffff815e6d11)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
```
```
In block/bio-integrity.c (ffffffff81602363)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/t10-pi.c (ffffffff8160390b)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/scatterlist.c (ffffffff81612de3)
Location: include/linux/mm.h:1610
Inline: True
```
```
In lib/iov_iter.c (ffffffff81619976)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In lib/buildid.c (ffffffff8165d175)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81677180)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
```
```
In drivers/acpi/osl.c (ffffffff81d4c92b)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8178e475)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:return_free_pages_to_mm
```
```
In drivers/xen/grant-table.c (ffffffff817909d7)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81791613)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff817f7f3c)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81813f0d)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:v1_free_pgtable
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_page
```
```
In drivers/iommu/intel/dmar.c (ffffffff81816cf0)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff818195a6)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_tlb_sync
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
  - drivers/iommu/intel/iommu.c:domain_exit
  - drivers/iommu/intel/iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff8181e833)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/svm.c (ffffffff81821c19)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81823a74)
Location: include/linux/mm.h:1610
Inline: True
```
```
In drivers/iommu/dma-iommu.c (ffffffff8182ae97)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
  - drivers/iommu/dma-iommu.c:iommu_dma_entry_dtor
```
```
In drivers/base/firmware_loader/main.c (ffffffff818593a6)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff81859f93)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_rw
```
```
In drivers/block/loop.c (ffffffff8186d6f3)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff81873c60)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8189cca5)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_clear_memmap_errors
```
```
In drivers/scsi/scsicam.c (ffffffff818af954)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b4a2c)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/sd.c (ffffffff818c5172)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sg.c (ffffffff818cda42)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read_oxfer
```
```
In drivers/ata/libata-sff.c (ffffffff818eb38b)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:atapi_pio_bytes
  - drivers/ata/libata-sff.c:ata_pio_xfer
```
```
In drivers/net/tun.c (ffffffff8190eea3)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/xen-netfront.c (ffffffff8191cd62)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
```
In drivers/usb/core/message.c (ffffffff819468be)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff81950775)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/md/md.c (ffffffff819f3997)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_90_sync
  - drivers/md/md.c:super_90_validate
```
```
In drivers/md/md-bitmap.c (ffffffff81a0319a)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (ffffffff81a193c2)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_ce_error
```
```
In drivers/firmware/efi/memmap.c (ffffffff8330da1b)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:__efi_memmap_free
```
```
In drivers/firmware/efi/capsule.c (ffffffff81a50704)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/sock.c (ffffffff81a78a27)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
```
```
In net/core/skbuff.c (ffffffff81a82e29)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/datagram.c (ffffffff81a8a9cb)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/dev.c (ffffffff81aa44f3)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
```
```
In net/core/filter.c (ffffffff81ac86e2)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/tso.c (ffffffff81ad16d1)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/skmsg.c (ffffffff81b05120)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/ipv4/ip_output.c (ffffffff81b4f033)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81b5b9d2)
Location: include/linux/mm.h:1610
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81bf0939)
Location: include/linux/mm.h:1610
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
In init/do_mounts.c (ffffffff8344857d)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:do_mount_root
```
```
In arch/x86/events/intel/bts.c (ffffffff81012e5a)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_reset
  - arch/x86/events/intel/bts.c:__bts_event_start
```
```
In arch/x86/events/intel/ds.c (ffffffff81013b58)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff8101bfa1)
Location: include/linux/mm.h:1731
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81035268)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_mm_unpin_all
  - arch/x86/xen/mmu_pv.c:xen_mm_pin_all
```
```
In arch/x86/hyperv/hv_init.c (ffffffff83454d81)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff81040193)
Location: include/linux/mm.h:1731
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8104aedd)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107dd17)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8107f77f)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81080cf0)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810960e0)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/kernel/kvmclock.c (ffffffff83470065)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
```
```
In arch/x86/kernel/sev.c (ffffffff810a4eaf)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
```
```
In arch/x86/mm/init_64.c (ffffffff81f1d29a)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810b37fa)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:kernel_page_present
  - arch/x86/mm/pat/set_memory.c:set_direct_map_default_noflush
  - arch/x86/mm/pat/set_memory.c:set_direct_map_invalid_noflush
  - arch/x86/mm/pat/set_memory.c:set_pages_rw
  - arch/x86/mm/pat/set_memory.c:set_pages_ro
  - arch/x86/mm/pat/set_memory.c:set_pages_wb
  - arch/x86/mm/pat/set_memory.c:set_pages_uc
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb
```
```
In kernel/power/snapshot.c (ffffffff81156c1a)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
```
In kernel/power/swap.c (0)
Location: include/linux/mm.h:1731
Inline: True
```
```
In kernel/dma/mapping.c (ffffffff81185578)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_vmap_noncontiguous
```
```
In kernel/dma/direct.c (ffffffff81186f25)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc
```
```
In kernel/dma/ops_helpers.c (ffffffff81187c3d)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/mm.h:1731
Inline: True
```
```
In kernel/profile.c (ffffffff811943c8)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/time/namespace.c (ffffffff811b1c23)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - kernel/time/namespace.c:timens_commit
```
```
In kernel/kexec_core.c (ffffffff811bc388)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_normal_segment
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_add_entry
  - kernel/kexec_core.c:kimage_alloc_crash_control_pages
  - kernel/kexec_core.c:kimage_free_pages
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811fcb00)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/trace/ring_buffer.c (ffffffff81214e54)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff81224946)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff81266b7a)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff812e2508)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff812e6a5c)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In kernel/watch_queue.c (ffffffff812ecfd1)
Location: include/linux/mm.h:1731
Inline: True
```
```
In mm/truncate.c (ffffffff81307c70)
Location: include/linux/mm.h:1731
Inline: True
```
```
In mm/shmem.c (ffffffff8131a8d5)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
```
```
In mm/util.c (ffffffff8131e571)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
  - mm/util.c:folio_copy
  - mm/util.c:folio_copy
```
```
In mm/percpu.c (ffffffff8348bd84)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_page_first_chunk
```
```
In mm/slab_common.c (ffffffff8132c324)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/memory.c (ffffffff81348b3d)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
```
```
In mm/vmalloc.c (ffffffff81366407)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
```
```
In mm/page_alloc.c (ffffffff813716d6)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:get_zeroed_page
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/swapfile.c (ffffffff8137e2d4)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff8138567a)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/sparse-vmemmap.c (ffffffff81f212f8)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffff813a32f1)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff813a37f0)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - mm/page_poison.c:__kernel_unpoison_pages
  - mm/page_poison.c:__kernel_poison_pages
```
```
In mm/slub.c (ffffffff813a5377)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__check_heap_object
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:__kmem_obj_info
  - mm/slub.c:free_partial
  - mm/slub.c:deactivate_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
  - mm/slub.c:slab_pad_check
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:print_trailer
  - mm/slub.c:__fill_map
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/khugepaged.c (ffffffff813c5836)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff813d34e0)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
```
```
In mm/swap_cgroup.c (ffffffff813d669c)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/zbud.c (ffffffff813df499)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (ffffffff813e24a5)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:obj_free
  - mm/zsmalloc.c:obj_malloc
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:alloc_zspage
```
```
In mm/secretmem.c (ffffffff813e3a78)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
```
```
In mm/userfaultfd.c (ffffffff813e5697)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/usercopy.c (ffffffff813e6ca4)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - mm/usercopy.c:check_heap_object
```
```
In fs/exec.c (ffffffff813fb21c)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - fs/exec.c:remove_arg_zero
  - fs/exec.c:copy_string_kernel
```
```
In fs/namei.c (ffffffff81400103)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff8142c4f0)
Location: include/linux/mm.h:1731
Inline: True
```
```
In fs/remap_range.c (ffffffff81442001)
Location: include/linux/mm.h:1731
Inline: True
```
```
In fs/buffer.c (ffffffff81444529)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/direct-io.c (ffffffff81448f50)
Location: include/linux/mm.h:1731
Inline: True
```
```
In fs/mpage.c (ffffffff8144af80)
Location: include/linux/mm.h:1731
Inline: True
```
```
In fs/aio.c (ffffffff81465376)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_complete
  - fs/aio.c:aio_complete
  - fs/aio.c:ioctx_add_table
  - fs/aio.c:aio_setup_ring
```
```
In fs/dax.c (ffffffff81467888)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
  - fs/dax.c:dax_fault_cow_page
  - fs/dax.c:dax_writeback_one
```
```
In fs/verity/read_metadata.c (ffffffff8147401f)
Location: include/linux/mm.h:1731
Inline: True
```
```
In fs/verity/verify.c (ffffffff8147441a)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - fs/verity/verify.c:extract_hash
```
```
In fs/coredump.c (ffffffff81486093)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
```
```
In fs/iomap/buffered-io.c (ffffffff8148a3cb)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_inline_data
```
```
In fs/ext4/inline.c (ffffffff814dd7c9)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff814e0720)
Location: include/linux/mm.h:1731
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff814f4197)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff814fe8a0)
Location: include/linux/mm.h:1731
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff815085a0)
Location: include/linux/mm.h:1731
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff81509970)
Location: include/linux/mm.h:1731
Inline: True
```
```
In fs/ext4/verity.c (ffffffff8153c180)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/transaction.c (ffffffff8153d474)
Location: include/linux/mm.h:1731
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff81540e67)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff8154c032)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/block.c (ffffffff8154cab8)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:copy_bio_to_actor
```
```
In fs/squashfs/file.c (ffffffff8154eae0)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_read_folio
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff81550ca8)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
```
In fs/squashfs/file_direct.c (ffffffff815516c5)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff81551868)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_next_page
  - fs/squashfs/page_actor.c:direct_first_page
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff81552673)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff81552a3d)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff81552d71)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff815530be)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff81553401)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In fs/hugetlbfs/inode.c (ffffffff81554840)
Location: include/linux/mm.h:1731
Inline: True
```
```
In fs/ecryptfs/mmap.c (ffffffff81568b85)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff81569cf0)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffffffff8156ba9a)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/dev.c (ffffffff8157615f)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/dir.c (ffffffff815790a5)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readlink_page
```
```
In fs/fuse/file.c (ffffffff815830b4)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (ffffffff81589320)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In fs/fuse/ioctl.c (ffffffff81589ede)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_do_ioctl
```
```
In security/selinux/selinuxfs.c (ffffffff815ce7c2)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_read_handle_status
```
```
In security/selinux/status.c (ffffffff815d332b)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - security/selinux/status.c:selinux_status_update_policyload
  - security/selinux/status.c:selinux_status_update_setenforce
  - security/selinux/status.c:selinux_kernel_status_page
```
```
In security/tomoyo/domain.c (ffffffff81600949)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff8164e73c)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (ffffffff81650598)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_next_copy
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff8165137d)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
```
```
In crypto/shash.c (ffffffff81653354)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff81672038)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:zero_fill_bio
```
```
In block/blk-map.c (ffffffff8167e5ab)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:bio_copy_kern_endio_read
```
```
In block/blk-mq.c (ffffffff81689eb9)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq.c:blk_mq_free_rqs
```
```
In block/partitions/core.c (ffffffff81695e9f)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
```
```
In block/bio-integrity.c (ffffffff816b4f67)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/t10-pi.c (ffffffff816b6b37)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - block/t10-pi.c:ext_pi_type1_complete
  - block/t10-pi.c:ext_pi_type1_prepare
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In io_uring/io_uring.c (ffffffff816ce24a)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_register_pbuf_ring
  - io_uring/io_uring.c:io_add_buffers
  - io_uring/io_uring.c:io_buffer_select
```
```
In lib/scatterlist.c (ffffffff816df43a)
Location: include/linux/mm.h:1731
Inline: True
```
```
In lib/iov_iter.c (ffffffff816e6d88)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:copy_mc_pipe_to_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:copy_pipe_to_iter
```
```
In lib/stackdepot.c (ffffffff8176f9ce)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - lib/stackdepot.c:__stack_depot_save
```
```
In lib/buildid.c (ffffffff817765cc)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
```
In arch/x86/lib/usercopy_64.c (ffffffff817921b7)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
```
```
In drivers/acpi/osl.c (ffffffff81f1c471)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/virtio/virtio_balloon.c (ffffffff818c66b8)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
```
```
In drivers/xen/grant-table.c (ffffffff818c9814)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff818ca0c9)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff8193654a)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/iommu/intel/dmar.c (ffffffff81957cf6)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff8195bd8c)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_domain_alloc
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff8195ebaa)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/svm.c (ffffffff81961dc9)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81962ee4)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
```
In drivers/iommu/dma-iommu.c (ffffffff8196c2b3)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
```
```
In drivers/base/firmware_loader/main.c (ffffffff8199ff7c)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
```
```
In drivers/base/firmware_loader/sysfs.c (ffffffff819a12a3)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - drivers/base/firmware_loader/sysfs.c:firmware_rw
```
```
In drivers/block/xen-blkfront.c (ffffffff819bb69f)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff819e6573)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_clear_memmap_errors
```
```
In drivers/scsi/scsicam.c (ffffffff819fa8e4)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/scsi/scsi_lib.c (ffffffff819ff9d6)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/sd.c (ffffffff81a11c3e)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sg.c (ffffffff81a1b76b)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read_oxfer
```
```
In drivers/ata/libata-sff.c (ffffffff81a3bcfa)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
```
```
In drivers/net/tun.c (ffffffff81a62ad2)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/xen-netfront.c (ffffffff81a73c42)
Location: include/linux/mm.h:1731
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff81a9f38a)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff81aa8f73)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/md/md.c (ffffffff81b5d628)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_90_sync
  - drivers/md/md.c:super_90_validate
```
```
In drivers/md/md-bitmap.c (ffffffff81b6ae78)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (ffffffff81b8200a)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/firmware/efi/memmap.c (ffffffff834c778b)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:__efi_memmap_free
```
```
In drivers/firmware/efi/capsule.c (ffffffff81bbf5cb)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/sock.c (ffffffff81bec48a)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
```
```
In net/core/skbuff.c (ffffffff81bf7bda)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/datagram.c (ffffffff81bfffe5)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/filter.c (ffffffff81c3f642)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_adjust_tail
  - net/core/filter.c:bpf_xdp_adjust_tail
  - net/core/filter.c:bpf_xdp_pointer
  - net/core/filter.c:bpf_xdp_copy_buf
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/tso.c (ffffffff81c4f047)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/xdp.c (ffffffff81c51413)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
  - net/core/xdp.c:xdp_return_buff
  - net/core/xdp.c:xdp_return_frame_rx_napi
  - net/core/xdp.c:xdp_return_frame
```
```
In net/core/gro.c (ffffffff81c544c3)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_receive
  - net/core/gro.c:skb_gro_receive
```
```
In net/core/skmsg.c (ffffffff81c8d406)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/bpf/test_run.c (ffffffff81cb5ac8)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
```
```
In net/ipv4/ip_output.c (ffffffff81cdc993)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81cea970)
Location: include/linux/mm.h:1731
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81d89011)
Location: include/linux/mm.h:1731
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
In init/do_mounts.c (ffffffff83e622b1)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:do_mount_root
```
```
In arch/x86/events/intel/bts.c (ffffffff81016e8a)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_reset
  - arch/x86/events/intel/bts.c:__bts_event_start
```
```
In arch/x86/events/intel/ds.c (ffffffff81018228)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff810202f1)
Location: include/linux/mm.h:1864
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103ce98)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_mm_unpin_all
  - arch/x86/xen/mmu_pv.c:xen_mm_pin_all
```
```
In arch/x86/hyperv/hv_init.c (ffffffff81044ce0)
Location: include/linux/mm.h:1864
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff810493f3)
Location: include/linux/mm.h:1864
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81056952)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8108f278)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81091897)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81093518)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810abd70)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/kernel/kvmclock.c (ffffffff83e96a59)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
```
```
In arch/x86/kernel/sev.c (ffffffff810bd5b9)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
```
```
In arch/x86/mm/init_64.c (ffffffff820c5439)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810ce3fa)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:kernel_page_present
  - arch/x86/mm/pat/set_memory.c:set_direct_map_default_noflush
  - arch/x86/mm/pat/set_memory.c:set_direct_map_invalid_noflush
  - arch/x86/mm/pat/set_memory.c:set_pages_rw
  - arch/x86/mm/pat/set_memory.c:set_pages_ro
  - arch/x86/mm/pat/set_memory.c:set_pages_wb
  - arch/x86/mm/pat/set_memory.c:set_pages_uc
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb
```
```
In arch/x86/platform/efi/memmap.c (ffffffff83ea18be)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - arch/x86/platform/efi/memmap.c:__efi_memmap_free
```
```
In kernel/power/snapshot.c (ffffffff81187856)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
```
In kernel/power/swap.c (0)
Location: include/linux/mm.h:1864
Inline: True
```
```
In kernel/dma/mapping.c (ffffffff811c0dd8)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_vmap_noncontiguous
```
```
In kernel/dma/direct.c (ffffffff811c29f5)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc
```
```
In kernel/dma/ops_helpers.c (ffffffff811c38d8)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/mm.h:1864
Inline: True
```
```
In kernel/profile.c (ffffffff811d1b28)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/time/namespace.c (ffffffff811f2a23)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - kernel/time/namespace.c:timens_commit
```
```
In kernel/kexec_core.c (ffffffff811fe208)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_normal_segment
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_add_entry
  - kernel/kexec_core.c:kimage_alloc_crash_control_pages
  - kernel/kexec_core.c:kimage_free_pages
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81244228)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/trace/ring_buffer.c (ffffffff8125e514)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff8126fa98)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff812b88c3)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
```
```
In kernel/events/ring_buffer.c (ffffffff8134ac78)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff81350549)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In kernel/watch_queue.c (ffffffff81357351)
Location: include/linux/mm.h:1864
Inline: True
```
```
In mm/truncate.c (ffffffff81371380)
Location: include/linux/mm.h:1864
Inline: True
```
```
In mm/shmem.c (ffffffff8138d9f5)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_folio_gfp
```
```
In mm/util.c (ffffffff81392051)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
  - mm/util.c:folio_copy
  - mm/util.c:folio_copy
```
```
In mm/percpu.c (ffffffff83ebcbfb)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_page_first_chunk
```
```
In mm/slab_common.c (ffffffff813a1327)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - mm/slab_common.c:__kmalloc_large_node
  - mm/slab_common.c:__ksize
```
```
In mm/memory.c (ffffffff813c0faa)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
```
```
In mm/vmalloc.c (ffffffff813e2017)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
```
```
In mm/page_alloc.c (ffffffff813eee06)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:get_zeroed_page
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/swapfile.c (ffffffff813fbee4)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff814033e3)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/sparse-vmemmap.c (ffffffff820cb18e)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffff81422f81)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff81423580)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - mm/page_poison.c:__kernel_unpoison_pages
  - mm/page_poison.c:__kernel_poison_pages
```
```
In mm/slub.c (ffffffff814264b5)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__check_heap_object
  - mm/slub.c:__kmem_obj_info
  - mm/slub.c:free_partial
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__kmem_cache_free
  - mm/slub.c:free_debug_processing
  - mm/slub.c:deactivate_slab
  - mm/slub.c:free_slab
  - mm/slub.c:free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:shuffle_freelist
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
  - mm/slub.c:slab_pad_check
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:print_trailer
  - mm/slub.c:__fill_map
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/migrate_device.c (ffffffff8143a582)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/migrate_device.c:migrate_device_coherent_page
```
```
In mm/khugepaged.c (ffffffff8144a191)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff81458ec3)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_slab_obj
  - mm/memcontrol.c:mem_cgroup_from_obj
```
```
In mm/swap_cgroup.c (ffffffff8145c14c)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/zbud.c (ffffffff81466279)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (ffffffff8146825b)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - mm/zsmalloc.c:restore_freelist
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:find_tagged_obj
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:obj_free
  - mm/zsmalloc.c:obj_malloc
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:alloc_zspage
```
```
In mm/secretmem.c (ffffffff8146b455)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
```
```
In mm/userfaultfd.c (ffffffff8146d17c)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/usercopy.c (ffffffff8146e87b)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - mm/usercopy.c:check_heap_object
```
```
In fs/exec.c (ffffffff814852f2)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - fs/exec.c:remove_arg_zero
  - fs/exec.c:copy_string_kernel
```
```
In fs/namei.c (ffffffff8148a153)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff814b9b20)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - fs/libfs.c:zero_user_segments
```
```
In fs/remap_range.c (ffffffff814d0ae7)
Location: include/linux/mm.h:1864
Inline: True
```
```
In fs/buffer.c (ffffffff814d3799)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:zero_user_segments
```
```
In fs/direct-io.c (ffffffff814d7240)
Location: include/linux/mm.h:1864
Inline: True
```
```
In fs/mpage.c (ffffffff814d97b0)
Location: include/linux/mm.h:1864
Inline: True
```
```
In fs/aio.c (ffffffff814f53b6)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_complete
  - fs/aio.c:aio_complete
  - fs/aio.c:ioctx_add_table
  - fs/aio.c:aio_setup_ring
```
```
In fs/dax.c (ffffffff814f7f48)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
  - fs/dax.c:dax_fault_cow_page
  - fs/dax.c:dax_writeback_one
```
```
In fs/verity/read_metadata.c (ffffffff8150626c)
Location: include/linux/mm.h:1864
Inline: True
```
```
In fs/verity/verify.c (ffffffff81506d17)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/iomap/buffered-io.c (ffffffff8151ddb8)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_inline_data
  - fs/iomap/buffered-io.c:zero_user_segments
```
```
In fs/ext4/inline.c (ffffffff815767f9)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff81579980)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - fs/ext4/inode.c:zero_user_segments
```
```
In fs/ext4/mballoc.c (ffffffff8158e6bb)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff815990e0)
Location: include/linux/mm.h:1864
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff815a3090)
Location: include/linux/mm.h:1864
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff815a45e0)
Location: include/linux/mm.h:1864
Inline: True
```
```
In fs/ext4/verity.c (ffffffff815da840)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/transaction.c (ffffffff815dbca3)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_freeze_jh_data
```
```
In fs/jbd2/commit.c (ffffffff815dffba)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff815ebe02)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/block.c (ffffffff815ec958)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:copy_bio_to_actor
```
```
In fs/squashfs/file.c (ffffffff815ef0e9)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_read_folio
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff815f1980)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
```
In fs/squashfs/page_actor.c (ffffffff815f1f74)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:handle_next_page
```
```
In fs/squashfs/file_direct.c (ffffffff815f26de)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff815f3bde)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff815f4030)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff815f439d)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff815f4766)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff815f4b39)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In fs/hugetlbfs/inode.c (ffffffff815f6310)
Location: include/linux/mm.h:1864
Inline: True
```
```
In fs/ecryptfs/mmap.c (ffffffff8160c4b5)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff8160d9a0)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffffffff8160faca)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/dev.c (ffffffff8161b237)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/dir.c (ffffffff8161e6c5)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readlink_page
```
```
In fs/fuse/file.c (ffffffff81629044)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (ffffffff8162f9a9)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In fs/fuse/ioctl.c (ffffffff81630555)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_do_ioctl
```
```
In security/selinux/selinuxfs.c (ffffffff8167c272)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_read_handle_status
```
```
In security/selinux/status.c (ffffffff8168135b)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - security/selinux/status.c:selinux_status_update_policyload
  - security/selinux/status.c:selinux_status_update_setenforce
  - security/selinux/status.c:selinux_kernel_status_page
```
```
In security/tomoyo/domain.c (ffffffff816b1899)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff81707b9c)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (ffffffff81709d38)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_next_copy
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff8170ac0d)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
```
```
In crypto/shash.c (ffffffff8170d074)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff8172d76c)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:zero_fill_bio
```
```
In block/blk-map.c (ffffffff8173b28b)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:bio_copy_kern_endio_read
```
```
In block/blk-mq.c (ffffffff8174843c)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq.c:blk_mq_free_rqs
```
```
In block/partitions/core.c (ffffffff81755229)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
```
```
In block/bio-integrity.c (ffffffff81774a3f)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/t10-pi.c (ffffffff81776af7)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - block/t10-pi.c:ext_pi_type1_complete
  - block/t10-pi.c:ext_pi_type1_prepare
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In io_uring/kbuf.c (ffffffff8179fcd6)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_register_pbuf_ring
  - io_uring/kbuf.c:io_add_buffers
  - io_uring/kbuf.c:io_buffer_select
```
```
In lib/scatterlist.c (ffffffff817cf66a)
Location: include/linux/mm.h:1864
Inline: True
```
```
In lib/iov_iter.c (ffffffff817d663a)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:copy_pipe_to_iter
```
```
In lib/stackdepot.c (ffffffff8189f4f4)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - lib/stackdepot.c:__stack_depot_save
```
```
In drivers/pci/p2pdma.c (ffffffff8191ce36)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pmem_free_sgl
```
```
In drivers/acpi/osl.c (ffffffff820c44a1)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a17008)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
```
```
In drivers/xen/grant-table.c (ffffffff81a1a5ef)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81a1ac89)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff81a9638a)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/iommu/intel/dmar.c (ffffffff81abecb6)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff81ac35a8)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_domain_alloc
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/iommu.c:iommu_context_addr
```
```
In drivers/iommu/intel/pasid.c (ffffffff81ac6645)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/svm.c (ffffffff81acab19)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81acbf63)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
```
In drivers/iommu/dma-iommu.c (ffffffff81ad486b)
Location: include/linux/mm.h:1864
Inline: True
```
```
In drivers/base/firmware_loader/main.c (ffffffff81b11a99)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
```
```
In drivers/base/firmware_loader/sysfs.c (ffffffff81b13026)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - drivers/base/firmware_loader/sysfs.c:firmware_rw
```
```
In drivers/block/xen-blkfront.c (ffffffff81b30bef)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81b625f5)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_clear_memmap_errors
```
```
In drivers/scsi/scsicam.c (ffffffff81b788e4)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b7e02b)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/sd.c (ffffffff81b91f09)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sg.c (ffffffff81b9c8db)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read_oxfer
```
```
In drivers/ata/libata-sff.c (ffffffff81bc114a)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
```
```
In drivers/net/tun.c (ffffffff81beef9b)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/xen-netfront.c (ffffffff81c07d72)
Location: include/linux/mm.h:1864
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff81c2480a)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff81c30223)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/md/md.c (ffffffff81cf757c)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:does_sb_need_changing
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_90_sync
  - drivers/md/md.c:super_90_validate
```
```
In drivers/md/md-bitmap.c (ffffffff81d06d99)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (ffffffff81d2082d)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/firmware/efi/capsule.c (ffffffff81d63deb)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/sock.c (ffffffff81d98f0d)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
```
```
In net/core/skbuff.c (ffffffff81da693a)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:__napi_alloc_skb
```
```
In net/core/datagram.c (ffffffff81daf3d5)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/filter.c (ffffffff81df3b52)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_adjust_tail
  - net/core/filter.c:bpf_xdp_adjust_tail
  - net/core/filter.c:bpf_xdp_pointer
  - net/core/filter.c:bpf_xdp_copy_buf
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/tso.c (ffffffff81e040f7)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/xdp.c (ffffffff81e06ba6)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
  - net/core/xdp.c:xdp_return_buff
  - net/core/xdp.c:xdp_return_frame_rx_napi
  - net/core/xdp.c:xdp_return_frame
```
```
In net/core/gro.c (ffffffff81e09c13)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_receive
  - net/core/gro.c:skb_gro_receive
```
```
In net/core/skmsg.c (ffffffff81e45a46)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/bpf/test_run.c (ffffffff81e73f98)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
```
```
In net/ipv4/ip_output.c (ffffffff81e9d3f3)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81eaeb25)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81f56e40)
Location: include/linux/mm.h:1864
Inline: True
```
```
In lib/buildid.c (ffffffff8201f019)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
```
In arch/x86/lib/usercopy_64.c (ffffffff8204ff87)
Location: include/linux/mm.h:1864
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
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
In init/do_mounts.c (ffffffff836826d5)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - init/do_mounts.c:mount_root_generic
  - init/do_mounts.c:do_mount_root
```
```
In arch/x86/events/intel/bts.c (ffffffff81016829)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_reset
  - arch/x86/events/intel/bts.c:__bts_event_start
```
```
In arch/x86/events/intel/ds.c (ffffffff81017b08)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff81020041)
Location: include/linux/mm.h:2135
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103cd78)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_mm_unpin_all
  - arch/x86/xen/mmu_pv.c:xen_mm_pin_all
```
```
In arch/x86/hyperv/hv_init.c (ffffffff81044e20)
Location: include/linux/mm.h:2135
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff81049653)
Location: include/linux/mm.h:2135
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81057922)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81092178)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff810947d4)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81096478)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810af930)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/kernel/kvmclock.c (ffffffff836ba609)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
```
```
In arch/x86/kernel/sev.c (ffffffff810c0c29)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
```
```
In arch/x86/mm/init_64.c (ffffffff82149499)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d19ba)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:kernel_page_present
  - arch/x86/mm/pat/set_memory.c:set_direct_map_default_noflush
  - arch/x86/mm/pat/set_memory.c:set_direct_map_invalid_noflush
  - arch/x86/mm/pat/set_memory.c:set_pages_rw
  - arch/x86/mm/pat/set_memory.c:set_pages_ro
  - arch/x86/mm/pat/set_memory.c:set_pages_wb
  - arch/x86/mm/pat/set_memory.c:set_pages_uc
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb
```
```
In arch/x86/platform/efi/memmap.c (ffffffff836c5b1e)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - arch/x86/platform/efi/memmap.c:__efi_memmap_free
```
```
In kernel/power/snapshot.c (ffffffff811989e6)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
```
In kernel/power/swap.c (0)
Location: include/linux/mm.h:2135
Inline: True
```
```
In kernel/dma/mapping.c (ffffffff811d38c8)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_vmap_noncontiguous
```
```
In kernel/dma/direct.c (ffffffff811d5535)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc
```
```
In kernel/dma/ops_helpers.c (ffffffff811d6425)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/mm.h:2135
Inline: True
```
```
In kernel/module/decompress.c (ffffffff811e1b68)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - kernel/module/decompress.c:module_zstd_decompress
```
```
In kernel/profile.c (ffffffff811e5e18)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/time/namespace.c (ffffffff812071a3)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - kernel/time/namespace.c:timens_commit
```
```
In kernel/kexec_core.c (ffffffff812134c8)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_normal_segment
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_add_entry
  - kernel/kexec_core.c:kimage_alloc_crash_control_pages
  - kernel/kexec_core.c:kimage_free_pages
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8125b308)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/trace/ring_buffer.c (ffffffff812756f4)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff81286cf2)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_events_user.c (ffffffff812c57a3)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_enabler_write
```
```
In kernel/trace/trace_uprobe.c (ffffffff812dbf03)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
```
```
In kernel/events/ring_buffer.c (ffffffff8137bca8)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff8138177a)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In kernel/watch_queue.c (ffffffff81388bcc)
Location: include/linux/mm.h:2135
Inline: True
```
```
In mm/truncate.c (ffffffff813a3550)
Location: include/linux/mm.h:2135
Inline: True
```
```
In mm/shmem.c (ffffffff813c1b85)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_folio_gfp
```
```
In mm/util.c (ffffffff813c4a51)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
  - mm/util.c:folio_copy
  - mm/util.c:folio_copy
```
```
In mm/percpu.c (ffffffff836e527b)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_page_first_chunk
```
```
In mm/slab_common.c (ffffffff813d45a3)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - mm/slab_common.c:__kmalloc_large_node
  - mm/slab_common.c:__ksize
```
```
In mm/memory.c (ffffffff813f5d29)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - mm/memory.c:copy_folio_from_user
  - mm/memory.c:copy_user_large_folio
  - mm/memory.c:copy_user_large_folio
  - mm/memory.c:copy_subpage
  - mm/memory.c:copy_subpage
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:do_cow_fault
  - mm/memory.c:do_cow_fault
  - mm/memory.c:__wp_page_copy_user
  - mm/memory.c:__wp_page_copy_user
  - mm/memory.c:__wp_page_copy_user
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
```
```
In mm/vmalloc.c (ffffffff814170c1)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - mm/vmalloc.c:vfree
  - mm/vmalloc.c:vfree
  - mm/vmalloc.c:vfree
```
```
In mm/page_alloc.c (ffffffff81422bd6)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:__page_frag_cache_refill
  - mm/page_alloc.c:get_zeroed_page
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/swapfile.c (ffffffff8142eff4)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff814368aa)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/sparse-vmemmap.c (ffffffff8214f41e)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffff81457fd8)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff81458820)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - mm/page_poison.c:__kernel_unpoison_pages
  - mm/page_poison.c:__kernel_poison_pages
```
```
In mm/slub.c (ffffffff8145b525)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__check_heap_object
  - mm/slub.c:__kmem_obj_info
  - mm/slub.c:free_partial
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__kmem_cache_free
  - mm/slub.c:free_debug_processing
  - mm/slub.c:deactivate_slab
  - mm/slub.c:free_slab
  - mm/slub.c:free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:shuffle_freelist
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
  - mm/slub.c:slab_pad_check
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:print_trailer
  - mm/slub.c:__fill_map
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/migrate_device.c (ffffffff8146fec6)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/migrate_device.c:migrate_device_coherent_page
```
```
In mm/khugepaged.c (ffffffff8147fc16)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff8148eb53)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_slab_obj
  - mm/memcontrol.c:mem_cgroup_from_obj
```
```
In mm/swap_cgroup.c (ffffffff81491dec)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/zbud.c (ffffffff8149bc16)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (ffffffff8149e13f)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:obj_free
  - mm/zsmalloc.c:obj_malloc
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:alloc_zspage
```
```
In mm/secretmem.c (ffffffff814a0237)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
```
```
In mm/userfaultfd.c (ffffffff814a1c62)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In mm/usercopy.c (ffffffff814a3013)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - mm/usercopy.c:check_heap_object
```
```
In fs/exec.c (ffffffff814ba360)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - fs/exec.c:remove_arg_zero
  - fs/exec.c:copy_string_kernel
```
```
In fs/namei.c (ffffffff814bf030)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff814eeac0)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - fs/libfs.c:zero_user_segments
```
```
In fs/remap_range.c (ffffffff815071e7)
Location: include/linux/mm.h:2135
Inline: True
```
```
In fs/buffer.c (ffffffff81508026)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - fs/buffer.c:set_bh_page
  - fs/buffer.c:folio_alloc_buffers
  - fs/buffer.c:zero_user_segments
```
```
In fs/mpage.c (ffffffff8150d810)
Location: include/linux/mm.h:2135
Inline: True
```
```
In fs/direct-io.c (ffffffff815102f0)
Location: include/linux/mm.h:2135
Inline: True
```
```
In fs/aio.c (ffffffff8152c167)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_complete
  - fs/aio.c:aio_complete
  - fs/aio.c:ioctx_add_table
  - fs/aio.c:aio_setup_ring
```
```
In fs/dax.c (ffffffff8152f148)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
  - fs/dax.c:dax_fault_cow_page
  - fs/dax.c:dax_writeback_one
```
```
In fs/verity/read_metadata.c (ffffffff8153d59d)
Location: include/linux/mm.h:2135
Inline: True
```
```
In fs/verity/verify.c (ffffffff8153e559)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_data_blocks
  - fs/verity/verify.c:verify_data_block
```
```
In fs/iomap/buffered-io.c (ffffffff81555f54)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_inline_data
  - fs/iomap/buffered-io.c:zero_user_segments
```
```
In fs/ext4/inline.c (ffffffff815adbaa)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_read_inline_folio
```
```
In fs/ext4/inode.c (ffffffff815b0910)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - fs/ext4/inode.c:zero_user_segments
```
```
In fs/ext4/mballoc.c (ffffffff815c50a8)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff815cfbc0)
Location: include/linux/mm.h:2135
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff815d9a70)
Location: include/linux/mm.h:2135
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff815daf20)
Location: include/linux/mm.h:2135
Inline: True
```
```
In fs/ext4/verity.c (ffffffff81612292)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - fs/ext4/verity.c:memcpy_from_file_folio
```
```
In fs/jbd2/transaction.c (ffffffff81613763)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_freeze_jh_data
```
```
In fs/jbd2/commit.c (ffffffff816172d6)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff816238e2)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/block.c (ffffffff816248d1)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:copy_bio_to_actor
```
```
In fs/squashfs/file.c (ffffffff816270c6)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_read_folio
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff81629a70)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
```
In fs/squashfs/page_actor.c (ffffffff8162a064)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:handle_next_page
```
```
In fs/squashfs/file_direct.c (ffffffff8162a7d0)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff8162bcce)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff8162c120)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff8162c492)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff8162c836)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff8162cbcf)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In fs/hugetlbfs/inode.c (ffffffff8162e490)
Location: include/linux/mm.h:2135
Inline: True
```
```
In fs/ecryptfs/mmap.c (ffffffff816443a5)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff81645850)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffffffff8164795a)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/dev.c (ffffffff816533a7)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/dir.c (ffffffff81656af5)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readlink_page
```
```
In fs/fuse/file.c (ffffffff81661266)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (ffffffff81667be9)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In fs/fuse/ioctl.c (ffffffff81668622)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_do_ioctl
```
```
In security/selinux/selinuxfs.c (ffffffff816b43e2)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_read_handle_status
```
```
In security/selinux/status.c (ffffffff816b93f7)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - security/selinux/status.c:selinux_status_update_policyload
  - security/selinux/status.c:selinux_status_update_setenforce
  - security/selinux/status.c:selinux_kernel_status_page
```
```
In security/tomoyo/domain.c (ffffffff816ea29c)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff817412dd)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (ffffffff81743948)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_next_copy
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff81745489)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_new_entry
```
```
In crypto/shash.c (ffffffff817469ad)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff81769b23)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:zero_fill_bio
```
```
In block/blk-map.c (ffffffff81777770)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - block/blk-map.c:bio_copy_kern
  - block/blk-map.c:bio_copy_kern_endio_read
```
```
In block/blk-mq.c (ffffffff81784b49)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq.c:blk_mq_free_rqs
```
```
In block/partitions/core.c (ffffffff81791507)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
```
```
In block/bio-integrity.c (ffffffff817b4765)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/t10-pi.c (ffffffff817b66cb)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - block/t10-pi.c:ext_pi_type1_complete
  - block/t10-pi.c:ext_pi_type1_prepare
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In io_uring/kbuf.c (ffffffff817e0df6)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_register_pbuf_ring
  - io_uring/kbuf.c:io_add_buffers
  - io_uring/kbuf.c:io_buffer_select
```
```
In lib/scatterlist.c (ffffffff8180db1a)
Location: include/linux/mm.h:2135
Inline: True
```
```
In lib/iov_iter.c (ffffffff81813ced)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_page_to_iter_nofault
  - lib/iov_iter.c:copy_page_to_iter_nofault
  - lib/iov_iter.c:copy_page_to_iter_nofault
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In lib/stackdepot.c (ffffffff818e1ac2)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - lib/stackdepot.c:__stack_depot_save
```
```
In drivers/pci/p2pdma.c (ffffffff819603f6)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pmem_free_sgl
```
```
In drivers/acpi/osl.c (ffffffff82148281)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a60098)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
```
```
In drivers/xen/grant-table.c (ffffffff81a6346f)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81a63e39)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff81ae1b9a)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81b06b25)
Location: include/linux/mm.h:2135
Inline: True
```
```
In drivers/iommu/amd/io_pgtable_v2.c (ffffffff81b07afb)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pgtable
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b0b656)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b0f0ed)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel/pasid.c (ffffffff81b1323a)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/svm.c (ffffffff81b17669)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b18ae6)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b23038)
Location: include/linux/mm.h:2135
Inline: True
```
```
In drivers/base/firmware_loader/main.c (ffffffff81b5fd89)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
```
```
In drivers/base/firmware_loader/sysfs.c (ffffffff81b61336)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - drivers/base/firmware_loader/sysfs.c:firmware_rw
```
```
In drivers/block/virtio_blk.c (ffffffff81b802d6)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_poll
  - drivers/block/virtio_blk.c:virtblk_complete_batch
  - drivers/block/virtio_blk.c:virtio_queue_rqs
  - drivers/block/virtio_blk.c:virtio_queue_rq
```
```
In drivers/block/xen-blkfront.c (ffffffff81b842af)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81bb5bf5)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_clear_memmap_errors
```
```
In drivers/scsi/scsicam.c (ffffffff81bcc571)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd1e0b)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/sd.c (ffffffff81be4eea)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_set_special_bvec
  - drivers/scsi/sd.c:sd_set_special_bvec
```
```
In drivers/scsi/sg.c (ffffffff81bf2ebc)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read_oxfer
```
```
In drivers/ata/libata-sff.c (ffffffff81c18c2a)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
```
```
In drivers/net/tun.c (ffffffff81c47024)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/virtio_net.c (ffffffff81c525f1)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:add_recvbuf_big
  - drivers/net/virtio_net.c:add_recvbuf_big
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable_xdp
  - drivers/net/virtio_net.c:receive_small_xdp
  - drivers/net/virtio_net.c:receive_small_xdp
  - drivers/net/virtio_net.c:xdp_linearize_page
  - drivers/net/virtio_net.c:xdp_linearize_page
  - drivers/net/virtio_net.c:xdp_linearize_page
  - drivers/net/virtio_net.c:xdp_linearize_page
  - drivers/net/virtio_net.c:page_to_skb
```
```
In drivers/net/xen-netfront.c (ffffffff81c6d492)
Location: include/linux/mm.h:2135
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff81c8b962)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff81c9746e)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/md/md.c (ffffffff81d5ee78)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:does_sb_need_changing
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_90_sync
  - drivers/md/md.c:super_90_validate
```
```
In drivers/md/md-bitmap.c (ffffffff81d7000b)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (ffffffff81d89a0d)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/firmware/efi/capsule.c (ffffffff81dcef3b)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/skbuff.c (ffffffff81e14cbd)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_splice_from_iter
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:__napi_alloc_skb
```
```
In net/core/datagram.c (ffffffff81e1f5d8)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/filter.c (ffffffff81e63544)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_adjust_tail
  - net/core/filter.c:bpf_xdp_adjust_tail
  - net/core/filter.c:bpf_xdp_pointer
  - net/core/filter.c:bpf_xdp_copy_buf
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/tso.c (ffffffff81e767f4)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/xdp.c (ffffffff81e79a73)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_return_buff
  - net/core/xdp.c:xdp_return_frame_rx_napi
  - net/core/xdp.c:xdp_return_frame
```
```
In net/core/gro.c (ffffffff81e7c3d9)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_receive
  - net/core/gro.c:skb_gro_receive
```
```
In net/core/skmsg.c (ffffffff81ea1056)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/bpf/test_run.c (ffffffff81ecfd25)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
```
```
In net/ipv4/ip_output.c (ffffffff81efa1a9)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81f0cbce)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81fb68a2)
Location: include/linux/mm.h:2135
Inline: True
```
```
In lib/buildid.c (ffffffff8209f02c)
Location: include/linux/mm.h:2135
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
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
In init/do_mounts.c (ffffffff838b1775)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - init/do_mounts.c:mount_root_generic
  - init/do_mounts.c:do_mount_root
```
```
In arch/x86/events/intel/bts.c (ffffffff8101c369)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_reset
  - arch/x86/events/intel/bts.c:__bts_event_start
```
```
In arch/x86/events/intel/ds.c (ffffffff8101d648)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff81026131)
Location: include/linux/mm.h:2190
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81043248)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_mm_unpin_all
  - arch/x86/xen/mmu_pv.c:xen_mm_pin_all
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8104b350)
Location: include/linux/mm.h:2190
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff81050a14)
Location: include/linux/mm.h:2190
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8105ebc2)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81099598)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109bcb4)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109d9e8)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b64c0)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/kernel/crash.c (ffffffff810b81d5)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:arch_crash_handle_hotplug_event
```
```
In arch/x86/kernel/kvmclock.c (ffffffff838eb009)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
```
```
In arch/x86/kernel/sev.c (ffffffff810c8089)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
```
```
In arch/x86/mm/init_64.c (ffffffff8222bf59)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810da0ea)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:kernel_page_present
  - arch/x86/mm/pat/set_memory.c:set_direct_map_default_noflush
  - arch/x86/mm/pat/set_memory.c:set_direct_map_invalid_noflush
  - arch/x86/mm/pat/set_memory.c:set_pages_rw
  - arch/x86/mm/pat/set_memory.c:set_pages_ro
  - arch/x86/mm/pat/set_memory.c:set_pages_wb
  - arch/x86/mm/pat/set_memory.c:set_pages_uc
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb
```
```
In arch/x86/platform/efi/memmap.c (ffffffff838f671e)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - arch/x86/platform/efi/memmap.c:__efi_memmap_free
```
```
In kernel/power/snapshot.c (ffffffff811a78a2)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
```
In kernel/power/swap.c (0)
Location: include/linux/mm.h:2190
Inline: True
```
```
In kernel/dma/mapping.c (ffffffff811e8568)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_vmap_noncontiguous
```
```
In kernel/dma/direct.c (ffffffff811ea425)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc
```
```
In kernel/dma/ops_helpers.c (ffffffff811eb455)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In kernel/dma/swiotlb.c (ffffffff811ebe58)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_alloc_pool
```
```
In kernel/module/decompress.c (ffffffff811f78d2)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - kernel/module/decompress.c:module_zstd_decompress
```
```
In kernel/profile.c (ffffffff811fbb68)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/time/namespace.c (ffffffff8121e3b3)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - kernel/time/namespace.c:timens_commit
```
```
In kernel/crash_core.c (ffffffff8122a34a)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - kernel/crash_core.c:crash_handle_hotplug_event
```
```
In kernel/kexec_core.c (ffffffff8122b3f8)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_normal_segment
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_add_entry
  - kernel/kexec_core.c:kimage_alloc_crash_control_pages
  - kernel/kexec_core.c:kimage_free_pages
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8127520c)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/trace/ring_buffer.c (ffffffff8128fdae)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff812a1dc2)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace.c:allocate_cmdlines_buffer
```
```
In kernel/trace/trace_events_user.c (ffffffff812e1fe9)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_enabler_write
```
```
In kernel/trace/trace_uprobe.c (ffffffff812f9fe3)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
```
```
In kernel/events/ring_buffer.c (ffffffff813a4ee8)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff813aab0c)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In kernel/watch_queue.c (ffffffff813b262c)
Location: include/linux/mm.h:2190
Inline: True
```
```
In mm/truncate.c (ffffffff813cd100)
Location: include/linux/mm.h:2190
Inline: True
```
```
In mm/shmem.c (ffffffff813ec902)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_folio_gfp
```
```
In mm/util.c (ffffffff813ef4b5)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
  - mm/util.c:folio_copy
  - mm/util.c:folio_copy
```
```
In mm/percpu.c (ffffffff83917a6b)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_page_first_chunk
```
```
In mm/slab_common.c (ffffffff813ff64c)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - mm/slab_common.c:__ksize
```
```
In mm/memory.c (ffffffff81421a06)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - mm/memory.c:copy_folio_from_user
  - mm/memory.c:copy_user_large_folio
  - mm/memory.c:copy_user_large_folio
  - mm/memory.c:copy_subpage
  - mm/memory.c:copy_subpage
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:__wp_page_copy_user
  - mm/memory.c:__wp_page_copy_user
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
  - mm/memory.c:__pte_alloc_kernel
```
```
In mm/vmalloc.c (ffffffff81443a1d)
Location: include/linux/mm.h:2190
Inline: True
```
```
In mm/page_alloc.c (ffffffff8144fab6)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:get_zeroed_page
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/slub.c (ffffffff81456705)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__check_heap_object
  - mm/slub.c:__kmem_obj_info
  - mm/slub.c:free_partial
  - mm/slub.c:__kmalloc_large_node
  - mm/slub.c:free_debug_processing
  - mm/slub.c:deactivate_slab
  - mm/slub.c:free_slab
  - mm/slub.c:free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:shuffle_freelist
  - mm/slub.c:__memcg_slab_free_hook
  - mm/slub.c:__memcg_slab_post_alloc_hook
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
  - mm/slub.c:slab_pad_check
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:print_trailer
  - mm/slub.c:__fill_map
```
```
In mm/swapfile.c (ffffffff81466dce)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff814713c7)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - mm/zswap.c:zswap_load
  - mm/zswap.c:zswap_store
```
```
In mm/hugetlb_vmemmap.c (ffffffff81480aa4)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_split_pmd
```
```
In mm/sparse-vmemmap.c (ffffffff822322ee)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffff8391dd08)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:cmp_and_merge_page
```
```
In mm/page_poison.c (ffffffff81492f26)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - mm/page_poison.c:__kernel_unpoison_pages
  - mm/page_poison.c:__kernel_poison_pages
```
```
In mm/migrate_device.c (ffffffff8149f140)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/migrate_device.c:migrate_device_coherent_page
```
```
In mm/khugepaged.c (ffffffff814add20)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff814be503)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_slab_obj
  - mm/memcontrol.c:mem_cgroup_from_obj
```
```
In mm/swap_cgroup.c (ffffffff814c17fc)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/zbud.c (ffffffff814cb316)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (ffffffff814cd288)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:migrate_zspage
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:obj_free
  - mm/zsmalloc.c:obj_malloc
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:alloc_zspage
```
```
In mm/secretmem.c (ffffffff814cf8be)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
```
```
In mm/userfaultfd.c (ffffffff814d1458)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In mm/usercopy.c (ffffffff814d3ea4)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - mm/usercopy.c:check_heap_object
```
```
In fs/exec.c (ffffffff814ec8e0)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - fs/exec.c:remove_arg_zero
  - fs/exec.c:copy_string_kernel
```
```
In fs/namei.c (ffffffff814f16d0)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff81522aa0)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - fs/libfs.c:zero_user_segments
```
```
In fs/remap_range.c (ffffffff8153c550)
Location: include/linux/mm.h:2190
Inline: True
```
```
In fs/buffer.c (ffffffff8153ec07)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - fs/buffer.c:folio_alloc_buffers
  - fs/buffer.c:zero_user_segments
```
```
In fs/mpage.c (ffffffff81542530)
Location: include/linux/mm.h:2190
Inline: True
```
```
In fs/direct-io.c (ffffffff815447a0)
Location: include/linux/mm.h:2190
Inline: True
```
```
In fs/aio.c (ffffffff81561047)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_complete
  - fs/aio.c:aio_complete
  - fs/aio.c:ioctx_add_table
  - fs/aio.c:aio_setup_ring
```
```
In fs/dax.c (ffffffff81564028)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
  - fs/dax.c:dax_fault_cow_page
  - fs/dax.c:dax_writeback_one
```
```
In fs/verity/read_metadata.c (ffffffff815729fd)
Location: include/linux/mm.h:2190
Inline: True
```
```
In fs/verity/verify.c (ffffffff81573af9)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_data_blocks
  - fs/verity/verify.c:verify_data_block
```
```
In fs/coredump.c (ffffffff81586fd7)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
  - fs/coredump.c:dump_user_range
```
```
In fs/iomap/buffered-io.c (ffffffff8158c448)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_inline_data
  - fs/iomap/buffered-io.c:zero_user_segments
```
```
In fs/ext4/inline.c (ffffffff815e696a)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_read_inline_folio
```
```
In fs/ext4/inode.c (ffffffff815e9840)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - fs/ext4/inode.c:zero_user_segments
```
```
In fs/ext4/mballoc.c (ffffffff815fd328)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff81608450)
Location: include/linux/mm.h:2190
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff816127a0)
Location: include/linux/mm.h:2190
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff81613750)
Location: include/linux/mm.h:2190
Inline: True
```
```
In fs/ext4/verity.c (ffffffff8164b27c)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - fs/ext4/verity.c:memcpy_from_file_folio
```
```
In fs/jbd2/transaction.c (ffffffff8164c578)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_freeze_jh_data
```
```
In fs/jbd2/commit.c (ffffffff81650110)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff8165c979)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/block.c (ffffffff8165d961)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:copy_bio_to_actor
```
```
In fs/squashfs/file.c (ffffffff81660200)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_read_folio
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff81662cc0)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
```
In fs/squashfs/page_actor.c (ffffffff816632e4)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:handle_next_page
```
```
In fs/squashfs/file_direct.c (ffffffff81663aeb)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff8166509e)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff81665520)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff816658c2)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff81665cc6)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff8166608f)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In fs/hugetlbfs/inode.c (ffffffff81667950)
Location: include/linux/mm.h:2190
Inline: True
```
```
In fs/ecryptfs/mmap.c (ffffffff8167d92a)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff8167ed20)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffffffff81680e0a)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/dev.c (ffffffff8168c9b7)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/dir.c (ffffffff81690375)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readlink_page
```
```
In fs/fuse/file.c (ffffffff8169b126)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (ffffffff816a1f16)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In fs/fuse/ioctl.c (ffffffff816a2922)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_do_ioctl
```
```
In security/selinux/selinuxfs.c (ffffffff816f0f42)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_read_handle_status
```
```
In security/selinux/status.c (ffffffff816f5eb7)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - security/selinux/status.c:selinux_status_update_policyload
  - security/selinux/status.c:selinux_status_update_setenforce
  - security/selinux/status.c:selinux_kernel_status_page
```
```
In security/tomoyo/domain.c (ffffffff81726fac)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff8178217d)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (ffffffff81785c78)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_next_copy
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff81787777)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_new_entry
  - crypto/ahash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff817abcd3)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:zero_fill_bio_iter
```
```
In block/blk-map.c (ffffffff817b9990)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - block/blk-map.c:bio_copy_kern
  - block/blk-map.c:bio_copy_kern_endio_read
```
```
In block/blk-mq.c (ffffffff817c7059)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq.c:blk_mq_free_rqs
```
```
In block/partitions/core.c (ffffffff817d4e09)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
```
```
In block/bio-integrity.c (ffffffff817f85a5)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_free
  - block/bio-integrity.c:bio_integrity_free
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/t10-pi.c (ffffffff817fb0db)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - block/t10-pi.c:ext_pi_type1_complete
  - block/t10-pi.c:ext_pi_type1_prepare
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In io_uring/io_uring.c (ffffffff81810a23)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uaddr_map
  - io_uring/io_uring.c:__io_uaddr_map
```
```
In io_uring/kbuf.c (ffffffff818253e5)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_register_pbuf_ring
  - io_uring/kbuf.c:io_buffer_select
```
```
In lib/scatterlist.c (ffffffff818537ca)
Location: include/linux/mm.h:2190
Inline: True
```
```
In lib/iov_iter.c (ffffffff81858315)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_page_to_iter_nofault
  - lib/iov_iter.c:copy_page_to_iter_nofault
  - lib/iov_iter.c:copy_page_to_iter_nofault
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In lib/stackdepot.c (ffffffff81928c3a)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - lib/stackdepot.c:stack_depot_save_flags
```
```
In drivers/pci/p2pdma.c (ffffffff819a9ae6)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pmem_free_sgl
```
```
In drivers/acpi/osl.c (ffffffff8222ac10)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81ab28d8)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
```
```
In drivers/xen/grant-table.c (ffffffff81ab5c8f)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81ab6679)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff81b34f8a)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/iommu/amd/iommu.c (ffffffff81b5756d)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:protection_domain_alloc
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81b5ab05)
Location: include/linux/mm.h:2190
Inline: True
```
```
In drivers/iommu/amd/io_pgtable_v2.c (ffffffff81b5bb2b)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pgtable
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b5f6fd)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b639dd)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel/pasid.c (ffffffff81b67e69)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/svm.c (ffffffff81b6cc59)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b6e455)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
```
In drivers/iommu/iommufd/iova_bitmap.c (ffffffff81b71ba8)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - drivers/iommu/iommufd/iova_bitmap.c:iova_bitmap_set
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b799a8)
Location: include/linux/mm.h:2190
Inline: True
```
```
In drivers/base/firmware_loader/main.c (ffffffff81bb3799)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
```
```
In drivers/base/firmware_loader/sysfs.c (ffffffff81bb4dc6)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - drivers/base/firmware_loader/sysfs.c:firmware_rw
```
```
In drivers/block/virtio_blk.c (ffffffff81bd4116)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_poll
  - drivers/block/virtio_blk.c:virtblk_complete_batch
  - drivers/block/virtio_blk.c:virtio_queue_rqs
  - drivers/block/virtio_blk.c:virtio_queue_rq
```
```
In drivers/block/xen-blkfront.c (ffffffff81bd81df)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81c0a1d5)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_clear_memmap_errors
```
```
In drivers/scsi/scsicam.c (ffffffff81c211a1)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c26a7b)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/sd.c (ffffffff81c3a04a)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_set_special_bvec
  - drivers/scsi/sd.c:sd_set_special_bvec
```
```
In drivers/scsi/sg.c (ffffffff81c487ac)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read_oxfer
```
```
In drivers/ata/libata-sff.c (ffffffff81c6d97a)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
```
```
In drivers/gpu/drm/drm_cache.c (ffffffff81c81288)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_cache.c:drm_clflush_page
```
```
In drivers/net/tun.c (ffffffff81cfca03)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/virtio_net.c (ffffffff81d05f06)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:add_recvbuf_big
  - drivers/net/virtio_net.c:add_recvbuf_big
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable_xdp
  - drivers/net/virtio_net.c:receive_small_xdp
  - drivers/net/virtio_net.c:receive_small_xdp
  - drivers/net/virtio_net.c:xdp_linearize_page
  - drivers/net/virtio_net.c:xdp_linearize_page
  - drivers/net/virtio_net.c:xdp_linearize_page
  - drivers/net/virtio_net.c:xdp_linearize_page
  - drivers/net/virtio_net.c:virtnet_rq_alloc
  - drivers/net/virtio_net.c:virtnet_rq_unmap
  - drivers/net/virtio_net.c:page_to_skb
```
```
In drivers/net/xen-netfront.c (ffffffff81d21de2)
Location: include/linux/mm.h:2190
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff81d40412)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff81d4bf4e)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/md/md.c (ffffffff81e160e8)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:does_sb_need_changing
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_90_sync
  - drivers/md/md.c:super_90_validate
```
```
In drivers/md/md-bitmap.c (ffffffff81e270bf)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (ffffffff81e411a5)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/firmware/efi/capsule.c (ffffffff81e87c6b)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/skbuff.c (ffffffff81ece48f)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - net/core/skbuff.c:csum_and_copy_from_iter_full
  - net/core/skbuff.c:csum_and_copy_from_iter_full
  - net/core/skbuff.c:skb_splice_from_iter
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:__napi_alloc_skb
```
```
In net/core/datagram.c (ffffffff81edd82d)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - net/core/datagram.c:csum_and_copy_to_iter
  - net/core/datagram.c:csum_and_copy_to_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/filter.c (ffffffff81f27c74)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_adjust_tail
  - net/core/filter.c:bpf_xdp_frags_shrink_tail
  - net/core/filter.c:bpf_xdp_pointer
  - net/core/filter.c:bpf_xdp_copy_buf
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/tso.c (ffffffff81f367b7)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/xdp.c (ffffffff81f39b93)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_return_buff
  - net/core/xdp.c:xdp_return_frame_rx_napi
  - net/core/xdp.c:xdp_return_frame
```
```
In net/core/gro.c (ffffffff81f3c729)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_receive
  - net/core/gro.c:skb_gro_receive
```
```
In net/core/skmsg.c (ffffffff81f63736)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/bpf/test_run.c (ffffffff81f93678)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
```
```
In net/ipv4/ip_output.c (ffffffff81fbe0d7)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81fd0cbe)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff8208418f)
Location: include/linux/mm.h:2190
Inline: True
```
```
In net/xdp/xsk.c (ffffffff8213eb41)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_build_skb
  - net/xdp/xsk.c:xsk_copy_xdp
```
```
In net/mptcp/protocol.c (ffffffff8214cb2f)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
```
```
In lib/buildid.c (ffffffff8217702c)
Location: include/linux/mm.h:2190
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
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
In init/do_mounts.c (ffff800011431730)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/arm64/kernel/probes/uprobes.c (ffff8000100ac74c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/arm64/kernel/probes/uprobes.c:arch_uprobe_copy_ixol
```
```
In arch/arm64/mm/dma-mapping.c (ffff8000100acb44)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/arm64/mm/dma-mapping.c:arch_dma_prep_coherent
```
```
In arch/arm64/mm/flush.c (ffff8000100add00)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/arm64/mm/flush.c:__sync_icache_dcache
```
```
In arch/arm64/mm/pageattr.c (ffff8000100b0698)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/arm64/mm/pageattr.c:kernel_page_present
  - arch/arm64/mm/pageattr.c:__kernel_map_pages
  - arch/arm64/mm/pageattr.c:set_direct_map_default_noflush
  - arch/arm64/mm/pageattr.c:set_direct_map_invalid_noflush
  - arch/arm64/mm/pageattr.c:change_memory_common
```
```
In virt/kvm/kvm_main.c (ffff8000100b5930)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:kvm_vcpu_init
```
```
In virt/kvm/coalesced_mmio.c (ffff8000100c0048)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - virt/kvm/coalesced_mmio.c:kvm_coalesced_mmio_init
```
```
In virt/kvm/arm/mmu.c (ffff8000100cc748)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:kvm_set_spte_hva
  - virt/kvm/arm/mmu.c:user_mem_abort
  - virt/kvm/arm/mmu.c:user_mem_abort
  - virt/kvm/arm/mmu.c:__create_hyp_mappings
  - virt/kvm/arm/mmu.c:unmap_stage2_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
```
```
In kernel/dma/direct.c (ffff800010194f5c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_alloc_pages
```
```
In kernel/dma/virt.c (ffff800010195f2c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/dma/virt.c:dma_virt_map_page
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/mm.h:1314
Inline: True
```
```
In kernel/profile.c (ffff800010198a3c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/kexec_core.c (ffff8000101c963c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_add_entry
```
```
In kernel/debug/kdb/kdb_support.c (ffff800010203c7c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/trace/ring_buffer.c (ffff800010219fc0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffff800010227ae8)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffff800010259c0c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/stackmap.c (ffff80001028bb94)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/ring_buffer.c (ffff8000102a2080)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffff8000102a5cf8)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In mm/truncate.c (ffff8000102c4a10)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffff8000102d5958)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/util.c (ffff8000102d9330)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
```
```
In mm/slab_common.c (ffff8000102e4dfc)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/memory.c (ffff8000102fc080)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:copy_subpage
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/vmalloc.c (ffff80001030da98)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
```
```
In mm/page_alloc.c (ffff800010319bc4)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:get_zeroed_page
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/swapfile.c (ffff800010323afc)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffff80001032bfd0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/sparse-vmemmap.c (ffff800010da0a04)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffff800010342000)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffff800010342b7c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
```
```
In mm/slub.c (ffff800010344ab0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab_slab
  - mm/slub.c:__check_heap_object
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
  - mm/slub.c:print_trailer
  - mm/slub.c:get_map
```
```
In mm/migrate.c (ffff80001034f9e8)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffff800010355694)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffff80001035d3d4)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/swap_cgroup.c (ffff80001036cd28)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/zbud.c (ffff800010373158)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (ffff800010374884)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/userfaultfd.c (ffff80001037860c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/read_write.c (ffff80001038064c)
Location: include/linux/mm.h:1314
Inline: True
```
```
In fs/exec.c (ffff80001038c338)
Location: include/linux/mm.h:1314
Inline: True
```
```
In fs/namei.c (ffff8000103922bc)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/namei.c:__page_symlink
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffff8000103c0b18)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/splice.c (ffff8000103cd448)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/splice.c:write_pipe_buf
  - fs/splice.c:default_file_splice_read
```
```
In fs/buffer.c (ffff8000103dcf94)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/direct-io.c (ffff8000103e42b8)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffff8000103e642c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffff8000103fddc0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_complete
  - fs/aio.c:aio_complete
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:aio_setup_ring
```
```
In fs/io_uring.c (ffff800010400b44)
Location: include/linux/mm.h:1314
Inline: True
```
```
In fs/dax.c (ffff8000104095a4)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/verity/verify.c (ffff80001041313c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/verity/verify.c:extract_hash
```
```
In fs/binfmt_elf.c (ffff800010420f14)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffff8000104247c4)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap/buffered-io.c (ffff80001042b320)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inline.c (ffff80001047acc4)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffff8000104818c0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (ffff800010490944)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffff800010499f3c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffff8000104a40b0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffff8000104a4c14)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffff8000104c0f10)
Location: include/linux/mm.h:1314
Inline: True
```
```
In fs/ext4/verity.c (ffff8000104c810c)
Location: include/linux/mm.h:1314
Inline: True
```
```
In fs/jbd2/transaction.c (ffff8000104cb3b4)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffff8000104ce684)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffff8000104d8780)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffff8000104dbe48)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffff8000104ddc90)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffff8000104de4a0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffff8000104de718)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_next_page
  - fs/squashfs/page_actor.c:direct_first_page
```
```
In fs/ecryptfs/mmap.c (ffff8000104f61fc)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffff8000104f68d8)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffff8000104f8268)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/dev.c (ffff800010503a54)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_do
```
```
In fs/fuse/dir.c (ffff800010506950)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readlink_page
```
```
In fs/fuse/file.c (ffff80001050ab08)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (ffff800010515564)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/selinux/selinuxfs.c (ffff800010555de8)
Location: include/linux/mm.h:1314
Inline: True
```
```
In security/selinux/ss/status.c (ffff80001056b3a8)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - security/selinux/ss/status.c:selinux_status_update_policyload
  - security/selinux/ss/status.c:selinux_status_update_setenforce
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
```
In security/tomoyo/domain.c (ffff800010580250)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffff8000105bb0a8)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffff8000105bd1f4)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffff8000105bf0b4)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (0)
Location: include/linux/mm.h:1314
Inline: True
```
```
In crypto/shash.c (ffff8000105c1e28)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffff8000105dd51c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_truncate
  - block/bio.c:zero_fill_bio_iter
```
```
In block/blk-mq.c (ffff8000105f25a8)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In block/partition-generic.c (ffff8000105fd0cc)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/bio-integrity.c (ffff80001061d390)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/t10-pi.c (ffff80001061ec44)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/scatterlist.c (0)
Location: include/linux/mm.h:1314
Inline: True
```
```
In lib/iov_iter.c (ffff800010632b90)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff800011473d84)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_init
  - drivers/irqchip/irq-gic-v3-its.c:its_probe_one
  - drivers/irqchip/irq-gic-v3-its.c:its_probe_one
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_vcpu_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_vcpu_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_free_pending_table
  - drivers/irqchip/irq-gic-v3-its.c:its_allocate_pending_table
  - drivers/irqchip/irq-gic-v3-its.c:its_free_prop_table
  - drivers/irqchip/irq-gic-v3-its.c:its_allocate_prop_table
  - drivers/irqchip/irq-gic-v3-its.c:lpi_write_config
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmapp_cmd
```
```
In drivers/dma/mv_xor.c (ffff800010807bc8)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor.c:mv_xor_channel_add
```
```
In drivers/virtio/virtio_balloon.c (ffff80001082a394)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:return_free_pages_to_mm
```
```
In drivers/xen/grant-table.c (ffff80001082cd24)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffff80001082e780)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffff8000108b2b94)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/tpm/tpm1-cmd.c (ffff8000108baaf4)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In drivers/char/tpm/tpm2-cmd.c (ffff8000108bcf80)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (ffff8000108bd698)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm-sysfs.c (ffff8000108be988)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
```
In drivers/iommu/dma-iommu.c (ffff8000108ca4f0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
```
```
In drivers/iommu/io-pgtable-arm.c (ffff8000108cb3e0)
Location: include/linux/mm.h:1314
Inline: True
```
```
In drivers/base/firmware_loader/main.c (ffff80001090d1b0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
```
```
In drivers/base/firmware_loader/fallback.c (ffff80001090e1d8)
Location: include/linux/mm.h:1314
Inline: True
```
```
In drivers/block/loop.c (ffff800010920c24)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffff800010925678)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/dma-buf/udmabuf.c (ffff80001096c6cc)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:kmap_udmabuf
```
```
In drivers/scsi/scsi_lib.c (ffff80001097663c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/sd.c (ffff80001098ad60)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/mm.h:1314
Inline: True
```
```
In drivers/ata/libata-scsi.c (ffff8000109a2a78)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
```
```
In drivers/ata/libata-sff.c (ffff8000109b2334)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/net/tun.c (ffff8000109e0618)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e7f50)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
```
```
In drivers/net/xen-netfront.c (ffff800010a075d8)
Location: include/linux/mm.h:1314
Inline: True
```
```
In drivers/usb/core/message.c (ffff800010a22978)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffff800010a2f860)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/md/md.c (ffff800010ae9adc)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_90_sync
  - drivers/md/md.c:super_90_validate
```
```
In drivers/md/md-bitmap.c (ffff800010af90c0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/mm.h:1314
Inline: True
```
```
In drivers/firmware/efi/capsule.c (ffff800010b5cc64)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/sock.c (ffff800010ba9828)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
```
```
In net/core/skbuff.c (ffff800010bb4cd4)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_dump
```
```
In net/core/datagram.c (ffff800010bbbbf8)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/dev.c (ffff800010bc62a8)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/dev.c:skb_gro_reset_offset
```
```
In net/core/filter.c (ffff800010bfdba8)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/tso.c (ffff800010c04b08)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/skmsg.c (ffff800010c0e2b4)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/ipv4/ip_output.c (ffff800010c6518c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffff800010c74c40)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffff800010cf91fc)
Location: include/linux/mm.h:1314
Inline: True
```
```
In net/xdp/xdp_umem.c (ffff800010d81520)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In arch/arm64/lib/uaccess_flushcache.c (ffff800010d835b0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/arm64/lib/uaccess_flushcache.c:memcpy_page_flushcache
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/highmem.c (c0515d58)
Location: include/linux/mm.h:1314
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
In init/do_mounts.c (c000000001344aa4)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/powerpc/kernel/iommu.c (c000000000052f34)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/powerpc/kernel/iommu.c:iommu_alloc_coherent
  - arch/powerpc/kernel/iommu.c:iommu_map_page
  - arch/powerpc/kernel/iommu.c:iommu_init_table
  - arch/powerpc/kernel/iommu.c:ppc_iommu_map_sg
```
```
In arch/powerpc/kernel/machine_kexec_64.c (c000000000071884)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/powerpc/kernel/machine_kexec_64.c:default_machine_kexec
```
```
In arch/powerpc/mm/mem.c (c00000000008734c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/powerpc/mm/mem.c:flush_icache_user_range
```
```
In arch/powerpc/mm/pgtable-frag.c (c00000000008920c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/powerpc/mm/pgtable-frag.c:pte_fragment_alloc
```
```
In arch/powerpc/mm/book3s64/pgtable.c (c00000000009101c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/pgtable.c:pmd_fragment_alloc
```
```
In arch/powerpc/mm/hugetlbpage.c (c0000000000a6608)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/powerpc/mm/hugetlbpage.c:flush_dcache_icache_hugepage
```
```
In arch/powerpc/sysdev/xive/common.c (c0000000000bf0ec)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/common.c:xive_queue_page_alloc
```
```
In arch/powerpc/platforms/powernv/pci-ioda.c (c0000000000d6344)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda1_setup_dma_pe
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda_iommu_bypass_supported
```
```
In arch/powerpc/platforms/powernv/pci-ioda-tce.c (c0000000000dae04)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci-ioda-tce.c:pnv_alloc_tce_level
```
```
In arch/powerpc/platforms/pseries/lpar.c (c0000000000e9424)
Location: include/linux/mm.h:1314
Inline: True
```
```
In arch/powerpc/kvm/book3s_64_vio_hv.c (c000000000117cf8)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_64_vio_hv.c:kvmppc_h_get_tce
  - arch/powerpc/kvm/book3s_64_vio_hv.c:kvmppc_rm_tce_put
```
```
In arch/powerpc/perf/imc-pmu.c (c00000000012c25c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/powerpc/perf/imc-pmu.c:trace_imc_mem_alloc
  - arch/powerpc/perf/imc-pmu.c:thread_imc_mem_alloc
  - arch/powerpc/perf/imc-pmu.c:ppc_core_imc_cpu_online
```
```
In kernel/dma/direct.c (c0000000001f5238)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_alloc_pages
```
```
In kernel/dma/virt.c (c0000000001f6024)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/dma/virt.c:dma_virt_map_sg
  - kernel/dma/virt.c:dma_virt_map_page
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/mm.h:1314
Inline: True
```
```
In kernel/profile.c (c0000000001f9080)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/kexec_core.c (c000000000231f50)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_add_entry
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/debug/kdb/kdb_support.c (c00000000027e4cc)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/trace/ring_buffer.c (c00000000029c0b8)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (c0000000002ae080)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (c0000000002fd488)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/stackmap.c (c000000000337be0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/ring_buffer.c (c000000000353df4)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (c000000000358d44)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In mm/truncate.c (c00000000037f1b0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (c00000000039584c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/util.c (c000000000398f30)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
```
```
In mm/slab_common.c (c0000000003a69c4)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/memory.c (c0000000003c7a50)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:copy_subpage
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/vmalloc.c (c0000000003de670)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:__vunmap
```
```
In mm/page_alloc.c (c0000000003ecc54)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:__get_free_pages
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/swapfile.c (c0000000003f88c0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (c0000000004027b0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/sparse-vmemmap.c (c000000000eed7f8)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (c00000000041f848)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (c00000000041fffc)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
```
```
In mm/slub.c (c000000000422bc0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__check_heap_object
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
  - mm/slub.c:print_trailer
  - mm/slub.c:get_map
```
```
In mm/migrate.c (c0000000004323f4)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (c00000000043cca4)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (c000000000448e68)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/swap_cgroup.c (c00000000045cc30)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/zbud.c (c000000000464df4)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (c000000000467f68)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:obj_free
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:obj_malloc
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/userfaultfd.c (c00000000046b0d4)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (c000000000477208)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (c000000000484c8c)
Location: include/linux/mm.h:1314
Inline: True
```
```
In fs/namei.c (c00000000048ac90)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/namei.c:__page_symlink
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (c0000000004bf2c0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/splice.c (c0000000004cf2a0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/splice.c:write_pipe_buf
  - fs/splice.c:default_file_splice_read
```
```
In fs/buffer.c (c0000000004e2660)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:set_bh_page
```
```
In fs/direct-io.c (c0000000004ea398)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (c0000000004ec680)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (c000000000507338)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_read_events
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:aio_setup_ring
```
```
In fs/io_uring.c (c00000000050a568)
Location: include/linux/mm.h:1314
Inline: True
```
```
In fs/dax.c (c000000000514bf8)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/verity/verify.c (c000000000520ea8)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/verity/verify.c:extract_hash
```
```
In fs/binfmt_elf.c (c00000000052fc8c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (c0000000005338ac)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap/buffered-io.c (c00000000053bc40)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inline.c (c00000000059dd78)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (c0000000005a5ea8)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (c0000000005b8194)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (c0000000005c4258)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (c0000000005d12b0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (c0000000005d1db0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (c0000000005f782c)
Location: include/linux/mm.h:1314
Inline: True
```
```
In fs/ext4/verity.c (c0000000006008d4)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/transaction.c (c000000000604464)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (c0000000006070f0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (c000000000613934)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (c0000000006170fc)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (c000000000619818)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (c00000000061a3c0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (c00000000061a584)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_next_page
  - fs/squashfs/page_actor.c:direct_first_page
```
```
In fs/ecryptfs/mmap.c (c0000000006370bc)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (c000000000637968)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (c00000000063a068)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/dev.c (c000000000648710)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_do
```
```
In fs/fuse/dir.c (c00000000064bd9c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readlink_page
```
```
In fs/fuse/file.c (c000000000652ea4)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (c00000000065dd9c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/selinux/selinuxfs.c (c0000000006b1758)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_read_handle_status
```
```
In security/selinux/ss/status.c (c0000000006cf32c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - security/selinux/ss/status.c:selinux_status_update_policyload
  - security/selinux/ss/status.c:selinux_status_update_setenforce
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
```
In security/tomoyo/domain.c (c0000000006edb7c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (c000000000741794)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (c000000000744290)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (c0000000007468ac)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (c000000000747cd0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
  - crypto/ahash.c:hash_walk_next
```
```
In crypto/shash.c (c00000000074a474)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (c00000000076ecd8)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_truncate
  - block/bio.c:zero_fill_bio_iter
```
```
In block/blk-mq.c (c000000000789854)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In block/partition-generic.c (c000000000796704)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/bio-integrity.c (c0000000007bbe18)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/t10-pi.c (c0000000007be1c4)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/scatterlist.c (c0000000007cf408)
Location: include/linux/mm.h:1314
Inline: True
```
```
In lib/iov_iter.c (c0000000007d62d0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:memcpy_mcsafe_to_page
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
```
```
In drivers/virtio/virtio_balloon.c (c0000000008d71a0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:return_free_pages_to_mm
```
```
In drivers/char/virtio_console.c (c00000000094ce7c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/tpm/tpm1-cmd.c (c00000000095bf70)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In drivers/char/tpm/tpm2-cmd.c (c00000000095eca0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (c00000000095f570)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm-sysfs.c (c000000000960e74)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
```
In drivers/base/firmware_loader/main.c (c0000000009ad47c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
```
```
In drivers/base/firmware_loader/fallback.c (c0000000009ae75c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_rw
```
```
In drivers/block/loop.c (c0000000009c4afc)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/nvdimm/pfn_devs.c (c000000000a15c6c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
```
```
In drivers/dma-buf/udmabuf.c (c000000000a25108)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:kmap_udmabuf
```
```
In drivers/scsi/scsi_lib.c (c000000000a30ec4)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/sd.c (c000000000a4b788)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/mm.h:1314
Inline: True
```
```
In drivers/ata/libata-scsi.c (c000000000a686b4)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
```
```
In drivers/ata/libata-sff.c (c000000000a7aed8)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/net/tun.c (c000000000aa1a10)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/vfio/vfio_iommu_spapr_tce.c (c000000000ab4000)
Location: include/linux/mm.h:1314
Inline: True
```
```
In drivers/usb/core/message.c (c000000000add980)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (c000000000aebf7c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/md/md.c (c000000000bd7314)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_90_sync
  - drivers/md/md.c:super_90_validate
```
```
In drivers/md/md-bitmap.c (c000000000be7210)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (c000000000c033c0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In net/core/sock.c (c000000000c7ed60)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
```
```
In net/core/skbuff.c (c000000000c8ba38)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_dump
```
```
In net/core/datagram.c (c000000000c94b70)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/dev.c (c000000000ca0e94)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/dev.c:skb_gro_reset_offset
```
```
In net/core/filter.c (c000000000ce9824)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/tso.c (c000000000ceeabc)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/skmsg.c (c000000000cf9b88)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/ipv4/ip_output.c (c000000000d69558)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (c000000000d7c1b4)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (c000000000e20dd8)
Location: include/linux/mm.h:1314
Inline: True
```
```
In net/xdp/xdp_umem.c (c000000000ec1464)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In init/do_mounts.c (ffffffe0000013e8)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In kernel/fork.c (ffffffe0000bfd94)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/dma/direct.c (ffffffe000126db8)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_alloc_pages
```
```
In kernel/dma/virt.c (ffffffe00012799a)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/dma/virt.c:dma_virt_map_page
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/mm.h:1314
Inline: True
```
```
In kernel/profile.c (ffffffe0001299b2)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/trace/ring_buffer.c (ffffffe000177d30)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/trace/trace.c (ffffffe0001824d8)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/bpf/stackmap.c (ffffffe0001bf654)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/ring_buffer.c (ffffffe0001d167e)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/truncate.c (ffffffe0001e52b8)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffe0001f13a2)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/util.c (ffffffe0001f36c6)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
```
```
In mm/slab_common.c (ffffffe0001fb96c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/memory.c (ffffffe00020b7f6)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:copy_subpage
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:__pte_alloc
```
```
In mm/vmalloc.c (ffffffe00021666e)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:__vunmap
```
```
In mm/page_alloc.c (ffffffe00021f702)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:__get_free_pages
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/swapfile.c (ffffffe0002243a2)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffe00022a586)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/sparse-vmemmap.c (ffffffe000048da6)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffe0002362c6)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffe00023670a)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
```
```
In mm/slub.c (ffffffe000238998)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab_slab
  - mm/slub.c:__check_heap_object
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
  - mm/slub.c:print_trailer
  - mm/slub.c:get_map
```
```
In mm/migrate.c (ffffffe00023e840)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/swap_cgroup.c (ffffffe000249b84)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/zbud.c (ffffffe00024c05a)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (ffffffe00024d804)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:obj_free
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:obj_malloc
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/userfaultfd.c (ffffffe00024ffa0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffe000255b78)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (ffffffe00025dbee)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/exec.c:copy_strings
```
```
In fs/namei.c (ffffffe000261524)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/namei.c:__page_symlink
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffe0002810b8)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/splice.c (ffffffe00028a7d4)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/splice.c:write_pipe_buf
  - fs/splice.c:default_file_splice_read
```
```
In fs/buffer.c (ffffffe000295146)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/direct-io.c (ffffffe000299db8)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffe00029b73e)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffe0002abf24)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_complete
  - fs/aio.c:aio_complete
  - fs/aio.c:aio_setup_ring
```
```
In fs/io_uring.c (ffffffe0002ad0d0)
Location: include/linux/mm.h:1314
Inline: True
```
```
In fs/dax.c (ffffffe0002b4236)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/verity/verify.c (ffffffe0002bace8)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/verity/verify.c:extract_hash
```
```
In fs/binfmt_elf.c (ffffffe0002c190e)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/iomap/buffered-io.c (ffffffe0002c899e)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inline.c (ffffffe0003053b0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffe00030a48c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (ffffffe000315888)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffe00031d59e)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffe000325582)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffe000325d18)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffe00033c5da)
Location: include/linux/mm.h:1314
Inline: True
```
```
In fs/ext4/verity.c (ffffffe000341d9a)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/transaction.c (ffffffe0003441e8)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffe000345f24)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffe00034e4b8)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffe000350acc)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffe0003526ac)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffe000352e06)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffe000352f86)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_next_page
  - fs/squashfs/page_actor.c:direct_first_page
```
```
In fs/ecryptfs/mmap.c (ffffffe000365010)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffe000365558)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffffffe000366b6c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/dev.c (ffffffe000370728)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/dir.c (ffffffe000372b40)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readlink_page
```
```
In fs/fuse/file.c (ffffffe000377068)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (ffffffe00037ec36)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/selinux/selinuxfs.c (ffffffe0003ae826)
Location: include/linux/mm.h:1314
Inline: True
```
```
In security/selinux/ss/status.c (ffffffe0003c01b2)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - security/selinux/ss/status.c:selinux_status_update_policyload
  - security/selinux/ss/status.c:selinux_status_update_setenforce
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
```
In security/tomoyo/domain.c (ffffffe0003d0ecc)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffe000400b5e)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffe00040298a)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffe0004042e0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffe000404e84)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
  - crypto/ahash.c:hash_walk_next
```
```
In crypto/shash.c (ffffffe000406988)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffe000420606)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_truncate
  - block/bio.c:zero_fill_bio_iter
```
```
In block/blk-mq.c (ffffffe000430da0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In block/partition-generic.c (ffffffe000438cb2)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/bio-integrity.c (ffffffe000450202)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/t10-pi.c (ffffffe000451baa)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/scatterlist.c (ffffffe00045c96c)
Location: include/linux/mm.h:1314
Inline: True
```
```
In lib/iov_iter.c (ffffffe00045e37e)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
```
```
In drivers/virtio/virtio_balloon.c (ffffffe00052035e)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:return_free_pages_to_mm
```
```
In drivers/char/virtio_console.c (ffffffe000565840)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffe00056b540)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffe00056f07e)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (ffffffe00056faa0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffe000570f6a)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
```
In drivers/base/firmware_loader/main.c (ffffffe000591d86)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
```
```
In drivers/base/firmware_loader/fallback.c (ffffffe0005926fe)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_rw
```
```
In drivers/block/loop.c (ffffffe00059f520)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/dma-buf/udmabuf.c (ffffffe0005d71c6)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:kmap_udmabuf
```
```
In drivers/scsi/scsi_lib.c (ffffffe0005decec)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/sd.c (ffffffe0005ef15e)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/mm.h:1314
Inline: True
```
```
In drivers/ata/libata-scsi.c (ffffffe000603150)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
```
```
In drivers/ata/libata-sff.c (ffffffe00060eeac)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/net/tun.c (ffffffe00062a4d8)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/usb/core/message.c (ffffffe000645866)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffe00064fc36)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:processcompl
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/md/md.c (ffffffe0006de1d8)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_90_sync
  - drivers/md/md.c:super_90_validate
```
```
In drivers/md/md-bitmap.c (ffffffe0006eb29c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/mm.h:1314
Inline: True
```
```
In drivers/mmc/host/mmc_spi.c (ffffffe00071a7fc)
Location: include/linux/mm.h:1314
Inline: True
```
```
In net/core/sock.c (ffffffe00073cda2)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
```
```
In net/core/skbuff.c (ffffffe000744d1a)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_dump
```
```
In net/core/datagram.c (ffffffe00074aa0a)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/dev.c (ffffffe000752a92)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/dev.c:skb_gro_reset_offset
```
```
In net/core/filter.c (ffffffe00077d2aa)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/tso.c (ffffffe0007836e6)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/skmsg.c (ffffffe00078ad20)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/ipv4/ip_output.c (ffffffe0007cc880)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffe0007d8090)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffe000844e80)
Location: include/linux/mm.h:1314
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffe0008ad978)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In init/do_mounts.c (ffffffff8288b5f9)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/events/intel/bts.c (ffffffff8100f1e7)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:__bts_event_start
```
```
In arch/x86/events/intel/ds.c (ffffffff8101111a)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff8101571d)
Location: include/linux/mm.h:1314
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810281a8)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_mm_unpin_all
  - arch/x86/xen/mmu_pv.c:xen_mm_pin_all
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102dd31)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810387f2)
Location: include/linux/mm.h:1314
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ef73)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/kernel/kvmclock.c (ffffffff828a9dad)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8107bb85)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
```
```
In arch/x86/mm/init_64.c (ffffffff81a6b079)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
```
```
In arch/x86/mm/pageattr.c (ffffffff810847d6)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:kernel_page_present
  - arch/x86/mm/pageattr.c:__set_pages_np
  - arch/x86/mm/pageattr.c:__set_pages_p
  - arch/x86/mm/pageattr.c:set_pages_rw
  - arch/x86/mm/pageattr.c:set_pages_ro
  - arch/x86/mm/pageattr.c:set_pages_wb
  - arch/x86/mm/pageattr.c:set_pages_uc
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In kernel/power/snapshot.c (ffffffff81104b76)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/power/swap.c (0)
Location: include/linux/mm.h:1314
Inline: True
```
```
In kernel/dma/direct.c (ffffffff81127b1a)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_alloc_pages
```
```
In kernel/dma/virt.c (ffffffff81127fd5)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/dma/virt.c:dma_virt_map_page
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/mm.h:1314
Inline: True
```
```
In kernel/profile.c (ffffffff8112a095)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/kexec_core.c (ffffffff811525c6)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_add_entry
  - kernel/kexec_core.c:kimage_alloc_control_pages
  - kernel/kexec_core.c:kimage_free_pages
  - kernel/kexec_core.c:kimage_alloc_pages
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81184f80)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/trace/ring_buffer.c (ffffffff81198dfc)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811a3302)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d1146)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/stackmap.c (ffffffff811fba37)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/ring_buffer.c (ffffffff8120fc9b)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff81212f79)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In mm/truncate.c (ffffffff8122ca3e)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff8123bcc5)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/util.c (ffffffff8123e27a)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
```
```
In mm/percpu.c (ffffffff828c5131)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_page_first_chunk
```
```
In mm/slab_common.c (ffffffff81247184)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/memory.c (ffffffff8125decb)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:copy_subpage
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/vmalloc.c (ffffffff8126fc2c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
```
```
In mm/page_alloc.c (ffffffff81279d5f)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:__get_free_pages
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/swapfile.c (ffffffff8128111e)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff8128721d)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/sparse-vmemmap.c (ffffffff81a6dc5e)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffff8129abf1)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff8129b081)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
```
```
In mm/slub.c (ffffffff8129cac5)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__check_heap_object
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
  - mm/slub.c:print_trailer
  - mm/slub.c:get_map
```
```
In mm/migrate.c (ffffffff812a5fba)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812ac5bd)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812b481e)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/swap_cgroup.c (ffffffff812c1c45)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/zbud.c (ffffffff812c6dac)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (ffffffff812c8447)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/userfaultfd.c (ffffffff812cae56)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff812d3d3f)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (ffffffff812dd83a)
Location: include/linux/mm.h:1314
Inline: True
```
```
In fs/namei.c (ffffffff812e1565)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/namei.c:__page_symlink
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff813048ec)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/splice.c (ffffffff8130f087)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/splice.c:write_pipe_buf
  - fs/splice.c:default_file_splice_read
```
```
In fs/buffer.c (ffffffff8131c1e3)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/direct-io.c (ffffffff8132137c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff8132338f)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff81336ceb)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_read_events
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:aio_setup_ring
```
```
In fs/io_uring.c (ffffffff81339130)
Location: include/linux/mm.h:1314
Inline: True
```
```
In fs/dax.c (ffffffff81340c2c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/verity/verify.c (ffffffff813496bc)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/verity/verify.c:extract_hash
```
```
In fs/binfmt_elf.c (ffffffff81353f0f)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff81357737)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap/buffered-io.c (ffffffff8135cde0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inline.c (ffffffff8139fa26)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff813a55ef)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff813b26f9)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff813baae8)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813c4617)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813c4d68)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff813e0814)
Location: include/linux/mm.h:1314
Inline: True
```
```
In fs/ext4/verity.c (ffffffff813e73bf)
Location: include/linux/mm.h:1314
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff813e99d3)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813eb5e5)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff813f3968)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff813f6375)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff813f8237)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff813f8a8a)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff813f8c66)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_next_page
  - fs/squashfs/page_actor.c:direct_first_page
```
```
In fs/ecryptfs/mmap.c (ffffffff8140d02c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff8140d8c0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffffffff8140f14f)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/dev.c (ffffffff81419369)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_do
```
```
In fs/fuse/dir.c (ffffffff8141bac3)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readlink_page
```
```
In fs/fuse/file.c (ffffffff81420cd5)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (ffffffff8142903a)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/selinux/selinuxfs.c (ffffffff8145ffed)
Location: include/linux/mm.h:1314
Inline: True
```
```
In security/selinux/ss/status.c (ffffffff81473324)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - security/selinux/ss/status.c:selinux_status_update_policyload
  - security/selinux/ss/status.c:selinux_status_update_setenforce
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
```
In security/tomoyo/domain.c (ffffffff81485353)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff814b93f9)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff814baffe)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff814bca0c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff814bd839)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
  - crypto/ahash.c:hash_walk_next
```
```
In crypto/shash.c (ffffffff814befa2)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff814d8ff0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_truncate
  - block/bio.c:zero_fill_bio_iter
```
```
In block/blk-mq.c (ffffffff814eb2fd)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In block/partition-generic.c (ffffffff814f366a)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/bounce.c (ffffffff814fe6c4)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:copy_to_high_bio_irq
  - block/bounce.c:copy_to_high_bio_irq
```
```
In block/bio-integrity.c (ffffffff8150e571)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/t10-pi.c (ffffffff8150fd48)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/scatterlist.c (ffffffff8151b294)
Location: include/linux/mm.h:1314
Inline: True
```
```
In lib/iov_iter.c (ffffffff8151d026)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:memcpy_mcsafe_to_page
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
```
```
In drivers/acpi/osl.c (ffffffff81a6901e)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81627927)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:return_free_pages_to_mm
```
```
In drivers/xen/grant-table.c (ffffffff81628e48)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff8162a857)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff8168731d)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81695cd7)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81697f3f)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff81698539)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff8169980b)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
```
In drivers/iommu/amd_iommu.c (ffffffff816a954c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:free_page_list
```
```
In drivers/iommu/dmar.c (ffffffff816ad750)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff816b436a)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
  - drivers/iommu/intel-iommu.c:dma_free_pagelist
  - drivers/iommu/intel-iommu.c:dma_pte_list_pagetables
  - drivers/iommu/intel-iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel-pasid.c (ffffffff816b59dc)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel-svm.c (ffffffff816b7976)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816b8f55)
Location: include/linux/mm.h:1314
Inline: True
```
```
In drivers/base/firmware_loader/main.c (ffffffff816dfdf9)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff816e0991)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_rw
```
```
In drivers/block/loop.c (ffffffff816efd6d)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff816f4759)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81714ece)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8171edfe)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:kmap_udmabuf
```
```
In drivers/scsi/scsi_lib.c (ffffffff8172774d)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/sd.c (ffffffff81738c7f)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/mm.h:1314
Inline: True
```
```
In drivers/nvme/host/core.c (ffffffff81744abe)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_setup_discard
```
```
In drivers/ata/libata-scsi.c (ffffffff8175e455)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
```
```
In drivers/ata/libata-sff.c (ffffffff8176b0bb)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/net/tun.c (ffffffff81789ef6)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff81791b34)
Location: include/linux/mm.h:1314
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff817aab0e)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff817b478e)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/md/md.c (ffffffff8183c39e)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_90_sync
  - drivers/md/md.c:super_90_validate
```
```
In drivers/md/md-bitmap.c (ffffffff8184a8d0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (ffffffff8185d954)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/firmware/efi/capsule.c (ffffffff8188c63f)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/sock.c (ffffffff818b1d44)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
```
```
In net/core/skbuff.c (ffffffff818ba997)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_dump
```
```
In net/core/datagram.c (ffffffff818c1569)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/dev.c (ffffffff818c9be4)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/dev.c:skb_gro_reset_offset
```
```
In net/core/filter.c (ffffffff818fdadb)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/tso.c (ffffffff819011fb)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/skmsg.c (ffffffff81908377)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/ipv4/ip_output.c (ffffffff819548a5)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff81961d4f)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff819d88c9)
Location: include/linux/mm.h:1314
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff81a4c0ad)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81a625f0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
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
In init/do_mounts.c (ffffffff82889576)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/events/intel/bts.c (ffffffff8100df47)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:__bts_event_start
```
```
In arch/x86/events/intel/ds.c (ffffffff8100feba)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff810149ed)
Location: include/linux/mm.h:1314
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8101d6b0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810281cb)
Location: include/linux/mm.h:1314
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105f350)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
```
```
In arch/x86/kernel/kvmclock.c (ffffffff828a208e)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8106b2b5)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
```
```
In arch/x86/mm/init_64.c (ffffffff81a275d1)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
```
```
In arch/x86/mm/pageattr.c (ffffffff810733d6)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:kernel_page_present
  - arch/x86/mm/pageattr.c:__set_pages_np
  - arch/x86/mm/pageattr.c:__set_pages_p
  - arch/x86/mm/pageattr.c:set_pages_rw
  - arch/x86/mm/pageattr.c:set_pages_ro
  - arch/x86/mm/pageattr.c:set_pages_wb
  - arch/x86/mm/pageattr.c:set_pages_uc
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
```
```
In kernel/power/snapshot.c (ffffffff810f5e16)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/power/swap.c (0)
Location: include/linux/mm.h:1314
Inline: True
```
```
In kernel/dma/direct.c (ffffffff8111a51a)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_alloc_pages
```
```
In kernel/dma/virt.c (ffffffff8111a865)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/dma/virt.c:dma_virt_map_page
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/mm.h:1314
Inline: True
```
```
In kernel/profile.c (ffffffff8111c925)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/kexec_core.c (ffffffff811458a6)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_add_entry
  - kernel/kexec_core.c:kimage_alloc_control_pages
  - kernel/kexec_core.c:kimage_free_pages
  - kernel/kexec_core.c:kimage_alloc_pages
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811780c0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/trace/ring_buffer.c (ffffffff8118c63c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811962d2)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811c3f16)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/stackmap.c (ffffffff811ee782)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/ring_buffer.c (ffffffff81202a2b)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff81205ce9)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In mm/truncate.c (ffffffff8121fb1e)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff8122ecc5)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/util.c (ffffffff8123127a)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
```
```
In mm/percpu.c (ffffffff828bd856)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_page_first_chunk
```
```
In mm/slab_common.c (ffffffff8123a134)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/memory.c (ffffffff8125031b)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:copy_subpage
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/vmalloc.c (ffffffff81261b9c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
```
```
In mm/page_alloc.c (ffffffff8126bc4f)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:__get_free_pages
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/swapfile.c (ffffffff81272f8e)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff8127907d)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/sparse-vmemmap.c (ffffffff81a2a1a5)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffff8128c7b1)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff8128cc41)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
```
```
In mm/slub.c (ffffffff8128e655)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__check_heap_object
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
  - mm/slub.c:print_trailer
  - mm/slub.c:get_map
```
```
In mm/migrate.c (ffffffff81297a6a)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff8129e66a)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812a5886)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/swap_cgroup.c (ffffffff812b2c95)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/zbud.c (ffffffff812b7dec)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (ffffffff812b9487)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/userfaultfd.c (ffffffff812bbdb9)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff812c49bf)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (ffffffff812ce4ba)
Location: include/linux/mm.h:1314
Inline: True
```
```
In fs/namei.c (ffffffff812d21a5)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/namei.c:__page_symlink
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff812f550c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/splice.c (ffffffff812ffc97)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/splice.c:write_pipe_buf
  - fs/splice.c:default_file_splice_read
```
```
In fs/buffer.c (ffffffff8130cd83)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/direct-io.c (ffffffff81311f1c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff81313f2f)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff81327661)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_read_events
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:aio_setup_ring
```
```
In fs/io_uring.c (ffffffff81329e60)
Location: include/linux/mm.h:1314
Inline: True
```
```
In fs/dax.c (ffffffff81331616)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/verity/verify.c (ffffffff8133a39c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/verity/verify.c:extract_hash
```
```
In fs/binfmt_elf.c (ffffffff81344bcf)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff813483e7)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap/buffered-io.c (ffffffff8134da80)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inline.c (ffffffff813904b6)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff8139607f)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff813a3189)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff813ab578)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813b5097)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813b57e8)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff813d1294)
Location: include/linux/mm.h:1314
Inline: True
```
```
In fs/ext4/verity.c (ffffffff813d7e3f)
Location: include/linux/mm.h:1314
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff813da453)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813dc065)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff813e43e8)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff813e6df5)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff813e8cb7)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff813e950a)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff813e96e6)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_next_page
  - fs/squashfs/page_actor.c:direct_first_page
```
```
In fs/ecryptfs/mmap.c (ffffffff813fdaac)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff813fe340)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffffffff813ffbcf)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/dev.c (ffffffff81409de9)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_do
```
```
In fs/fuse/dir.c (ffffffff8140c543)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readlink_page
```
```
In fs/fuse/file.c (ffffffff81411755)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (ffffffff81419aba)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/selinux/selinuxfs.c (ffffffff81450a1d)
Location: include/linux/mm.h:1314
Inline: True
```
```
In security/selinux/ss/status.c (ffffffff81463d44)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - security/selinux/ss/status.c:selinux_status_update_policyload
  - security/selinux/ss/status.c:selinux_status_update_setenforce
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
```
In security/tomoyo/domain.c (ffffffff81475d73)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff814a9e19)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff814aba1e)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff814ad42c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff814ae259)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
  - crypto/ahash.c:hash_walk_next
```
```
In crypto/shash.c (ffffffff814af9c2)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff814c99a0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_truncate
  - block/bio.c:zero_fill_bio_iter
```
```
In block/blk-mq.c (ffffffff814db84d)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In block/partition-generic.c (ffffffff814e3b7a)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/bounce.c (ffffffff814eebd4)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:copy_to_high_bio_irq
  - block/bounce.c:copy_to_high_bio_irq
```
```
In block/bio-integrity.c (ffffffff814fe9a1)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/t10-pi.c (ffffffff81500068)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/scatterlist.c (ffffffff8150b584)
Location: include/linux/mm.h:1314
Inline: True
```
```
In lib/iov_iter.c (ffffffff8150d316)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:memcpy_mcsafe_to_page
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
```
```
In drivers/acpi/osl.c (ffffffff81a25ade)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8161bfa7)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:return_free_pages_to_mm
```
```
In drivers/char/virtio_console.c (ffffffff81664f0d)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff816736c7)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff8167592f)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff81675f29)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff816771fb)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
```
In drivers/iommu/amd_iommu.c (ffffffff81686fe9)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:free_page_list
```
```
In drivers/iommu/dmar.c (ffffffff8168b0b0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff8168bd70)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dma_free_pagelist
  - drivers/iommu/intel-iommu.c:dma_pte_list_pagetables
  - drivers/iommu/intel-iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel-pasid.c (ffffffff8169361c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel-svm.c (ffffffff816955b6)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81696b95)
Location: include/linux/mm.h:1314
Inline: True
```
```
In drivers/base/firmware_loader/main.c (ffffffff816ba439)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff816bafd1)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_rw
```
```
In drivers/block/loop.c (ffffffff816c9e7d)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff816e894e)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
```
```
In drivers/nvdimm/pmem.c (ffffffff816eb70b)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/nvdimm/pmem.c:pmem_do_bvec
  - drivers/nvdimm/pmem.c:write_pmem
```
```
In drivers/nvdimm/btt.c (ffffffff816ed102)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/nvdimm/btt.c:btt_write_pg
  - drivers/nvdimm/btt.c:btt_read_pg
  - drivers/nvdimm/btt.c:btt_read_pg
  - drivers/nvdimm/btt.c:btt_rw_integrity
  - drivers/nvdimm/btt.c:arena_clear_freelist_error
```
```
In drivers/nvdimm/blk.c (ffffffff816ef245)
Location: include/linux/mm.h:1314
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff816f822e)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:kmap_udmabuf
```
```
In drivers/scsi/scsi_lib.c (ffffffff81700b78)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/sd.c (ffffffff8171a91f)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/mm.h:1314
Inline: True
```
```
In drivers/nvme/host/core.c (ffffffff8172674e)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_setup_discard
```
```
In drivers/ata/libata-scsi.c (ffffffff8173e2f5)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
```
```
In drivers/ata/libata-sff.c (ffffffff8174af1b)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/net/tun.c (ffffffff81769846)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/usb/core/message.c (ffffffff8179c50e)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff817a61be)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/md/md.c (ffffffff818039fe)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_90_sync
  - drivers/md/md.c:super_90_validate
```
```
In drivers/md/md-bitmap.c (ffffffff81811f00)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (ffffffff81824f24)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/firmware/efi/capsule.c (ffffffff81843fbf)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In drivers/hv/channel.c (ffffffff818515b3)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/hv/channel.c:__vmbus_open
```
```
In net/core/sock.c (ffffffff8186bc94)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
```
```
In net/core/skbuff.c (ffffffff818748e7)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_dump
```
```
In net/core/datagram.c (ffffffff8187b4a9)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/dev.c (ffffffff81883b24)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/dev.c:skb_gro_reset_offset
```
```
In net/core/filter.c (ffffffff818b790b)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/tso.c (ffffffff818bb02b)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/skmsg.c (ffffffff818c2187)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/ipv4/ip_output.c (ffffffff8190e395)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff8191b83f)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81995689)
Location: include/linux/mm.h:1314
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff81a08c9d)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81a1f660)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
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
In init/do_mounts.c (ffffffff8289e5f9)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/events/intel/bts.c (ffffffff8100f1a7)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:__bts_event_start
```
```
In arch/x86/events/intel/ds.c (ffffffff810110da)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff810156dd)
Location: include/linux/mm.h:1314
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81028008)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_mm_unpin_all
  - arch/x86/xen/mmu_pv.c:xen_mm_pin_all
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102db91)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81038652)
Location: include/linux/mm.h:1314
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106f423)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/kernel/kvmclock.c (ffffffff828bccac)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8107bb35)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
```
```
In arch/x86/mm/init_64.c (ffffffff81ad7489)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
```
```
In arch/x86/mm/pageattr.c (ffffffff81084786)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:kernel_page_present
  - arch/x86/mm/pageattr.c:__set_pages_np
  - arch/x86/mm/pageattr.c:__set_pages_p
  - arch/x86/mm/pageattr.c:set_pages_rw
  - arch/x86/mm/pageattr.c:set_pages_ro
  - arch/x86/mm/pageattr.c:set_pages_wb
  - arch/x86/mm/pageattr.c:set_pages_uc
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In kernel/power/snapshot.c (ffffffff81102e26)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/power/swap.c (0)
Location: include/linux/mm.h:1314
Inline: True
```
```
In kernel/dma/direct.c (ffffffff811259aa)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_alloc_pages
```
```
In kernel/dma/virt.c (ffffffff81125cf5)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/dma/virt.c:dma_virt_map_page
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/mm.h:1314
Inline: True
```
```
In kernel/profile.c (ffffffff81127db5)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/kexec_core.c (ffffffff81150476)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_add_entry
  - kernel/kexec_core.c:kimage_alloc_control_pages
  - kernel/kexec_core.c:kimage_free_pages
  - kernel/kexec_core.c:kimage_alloc_pages
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81182d50)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/trace/ring_buffer.c (ffffffff81196bcc)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811a10d2)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cef16)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/stackmap.c (ffffffff811f9807)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/ring_buffer.c (ffffffff8120da3b)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff81210d19)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In mm/truncate.c (ffffffff8122a7de)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff81239a65)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/util.c (ffffffff8123c01a)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
```
```
In mm/percpu.c (ffffffff828d7eb1)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_page_first_chunk
```
```
In mm/slab_common.c (ffffffff81244f24)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/memory.c (ffffffff8125bc6b)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:copy_subpage
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/vmalloc.c (ffffffff8126d9cc)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
```
```
In mm/page_alloc.c (ffffffff81277aff)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:__get_free_pages
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/swapfile.c (ffffffff8127ef2e)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff8128502d)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/sparse-vmemmap.c (ffffffff81ada06e)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffff81298a01)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff81298e91)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
```
```
In mm/slub.c (ffffffff8129a8d5)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__check_heap_object
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
  - mm/slub.c:print_trailer
  - mm/slub.c:get_map
```
```
In mm/migrate.c (ffffffff812a3dca)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812aa3cd)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812b262e)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/swap_cgroup.c (ffffffff812bfa55)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/zbud.c (ffffffff812c4bbc)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (ffffffff812c6257)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/userfaultfd.c (ffffffff812c8c66)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff812d1b4f)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (ffffffff812db64a)
Location: include/linux/mm.h:1314
Inline: True
```
```
In fs/namei.c (ffffffff812df375)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/namei.c:__page_symlink
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff813026dc)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/splice.c (ffffffff8130ce77)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/splice.c:write_pipe_buf
  - fs/splice.c:default_file_splice_read
```
```
In fs/buffer.c (ffffffff81319cb3)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/direct-io.c (ffffffff8131ee4c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff81320e5f)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff813347bb)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_read_events
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:aio_setup_ring
```
```
In fs/io_uring.c (ffffffff81336c00)
Location: include/linux/mm.h:1314
Inline: True
```
```
In fs/dax.c (ffffffff8133e6fc)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/verity/verify.c (ffffffff8134718c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/verity/verify.c:extract_hash
```
```
In fs/binfmt_elf.c (ffffffff813519df)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff81355207)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap/buffered-io.c (ffffffff8135a8b0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inline.c (ffffffff8139d286)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff813a2e4f)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff813aff59)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff813b8348)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813c1aa7)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813c21f8)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff813ddb94)
Location: include/linux/mm.h:1314
Inline: True
```
```
In fs/ext4/verity.c (ffffffff813e473f)
Location: include/linux/mm.h:1314
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff813e6d53)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813e8965)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff813f0ce8)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff813f36f5)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff813f55b7)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff813f5e0a)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff813f5fe6)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_next_page
  - fs/squashfs/page_actor.c:direct_first_page
```
```
In fs/ecryptfs/mmap.c (ffffffff8140a3ac)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff8140ac40)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffffffff8140c4cf)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/dev.c (ffffffff81415509)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_do
```
```
In fs/fuse/dir.c (ffffffff81417c63)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readlink_page
```
```
In fs/fuse/file.c (ffffffff8141ce75)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (ffffffff814251da)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/selinux/selinuxfs.c (ffffffff8145c08d)
Location: include/linux/mm.h:1314
Inline: True
```
```
In security/selinux/ss/status.c (ffffffff8146f3c4)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - security/selinux/ss/status.c:selinux_status_update_policyload
  - security/selinux/ss/status.c:selinux_status_update_setenforce
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
```
In security/tomoyo/domain.c (ffffffff814813f3)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff814b5489)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff814b708e)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff814b8a9c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff814b98c9)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
  - crypto/ahash.c:hash_walk_next
```
```
In crypto/shash.c (ffffffff814bb032)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff814d5080)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_truncate
  - block/bio.c:zero_fill_bio_iter
```
```
In block/blk-mq.c (ffffffff814e738d)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In block/partition-generic.c (ffffffff814ef6fa)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/bounce.c (ffffffff814fa754)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:copy_to_high_bio_irq
  - block/bounce.c:copy_to_high_bio_irq
```
```
In block/bio-integrity.c (ffffffff8150a601)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/t10-pi.c (ffffffff8150bdd8)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/scatterlist.c (ffffffff81517324)
Location: include/linux/mm.h:1314
Inline: True
```
```
In lib/iov_iter.c (ffffffff815190b6)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:memcpy_mcsafe_to_page
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
```
```
In drivers/acpi/osl.c (ffffffff81ad542e)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/virtio/virtio_balloon.c (ffffffff816558f7)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:return_free_pages_to_mm
```
```
In drivers/xen/grant-table.c (ffffffff81656e18)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81658827)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff816b565d)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff816c3f47)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816c61af)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff816c67a9)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff816c7a7b)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
```
In drivers/iommu/amd_iommu.c (ffffffff816d7869)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:free_page_list
```
```
In drivers/iommu/dmar.c (ffffffff816db930)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff816dc5f0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dma_free_pagelist
  - drivers/iommu/intel-iommu.c:dma_pte_list_pagetables
  - drivers/iommu/intel-iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel-pasid.c (ffffffff816e3eac)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel-svm.c (ffffffff816e5e46)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816e7425)
Location: include/linux/mm.h:1314
Inline: True
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff8170e061)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_rw
```
```
In drivers/block/loop.c (ffffffff8171d44d)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff81721c29)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81753c9e)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8175dbce)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:kmap_udmabuf
```
```
In drivers/scsi/scsi_lib.c (ffffffff8176651d)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/sd.c (ffffffff8177940f)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/mm.h:1314
Inline: True
```
```
In drivers/ata/libata-scsi.c (ffffffff8178e1e5)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
```
```
In drivers/ata/libata-sff.c (ffffffff8179ae7b)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/net/tun.c (ffffffff817ba296)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff817c1ea4)
Location: include/linux/mm.h:1314
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff817e75ae)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff817f122e)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/md/md.c (ffffffff8188b9ce)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_90_sync
  - drivers/md/md.c:super_90_validate
```
```
In drivers/md/md-bitmap.c (ffffffff81899f00)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (ffffffff818acf84)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/firmware/efi/capsule.c (ffffffff818de71f)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/sock.c (ffffffff81902d44)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
```
```
In net/core/skbuff.c (ffffffff8190b997)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_dump
```
```
In net/core/datagram.c (ffffffff81912569)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/dev.c (ffffffff8191abe4)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/dev.c:skb_gro_reset_offset
```
```
In net/core/filter.c (ffffffff8194eb0b)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/tso.c (ffffffff8195222b)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/skmsg.c (ffffffff819593a7)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/ipv4/ip_output.c (ffffffff819bf075)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff819cc51f)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81a43349)
Location: include/linux/mm.h:1314
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff81ab7f5d)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81ace9e0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
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
In init/do_mounts.c (ffffffff8289e5fe)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/events/intel/bts.c (ffffffff8100f377)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:__bts_event_start
```
```
In arch/x86/events/intel/ds.c (ffffffff810112ea)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff8101591d)
Location: include/linux/mm.h:1314
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81028c98)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_mm_unpin_all
  - arch/x86/xen/mmu_pv.c:xen_mm_pin_all
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102e981)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81039652)
Location: include/linux/mm.h:1314
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810716a3)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/kernel/kvmclock.c (ffffffff828bfe04)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8107dc35)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
```
```
In arch/x86/mm/init_64.c (ffffffff81ae3949)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
```
```
In arch/x86/mm/pageattr.c (ffffffff810868d6)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:kernel_page_present
  - arch/x86/mm/pageattr.c:__set_pages_np
  - arch/x86/mm/pageattr.c:__set_pages_p
  - arch/x86/mm/pageattr.c:set_pages_rw
  - arch/x86/mm/pageattr.c:set_pages_ro
  - arch/x86/mm/pageattr.c:set_pages_wb
  - arch/x86/mm/pageattr.c:set_pages_uc
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In kernel/power/snapshot.c (ffffffff8110e216)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/power/swap.c (0)
Location: include/linux/mm.h:1314
Inline: True
```
```
In kernel/dma/direct.c (ffffffff81131fea)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_alloc_pages
```
```
In kernel/dma/virt.c (ffffffff81132335)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/dma/virt.c:dma_virt_map_page
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/mm.h:1314
Inline: True
```
```
In kernel/profile.c (ffffffff81134435)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/kexec_core.c (ffffffff8115d2b0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_add_entry
  - kernel/kexec_core.c:kimage_alloc_control_pages
  - kernel/kexec_core.c:kimage_free_pages
  - kernel/kexec_core.c:kimage_alloc_pages
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8119067f)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/trace/ring_buffer.c (ffffffff811a47dc)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811aee62)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811dd1a6)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/stackmap.c (ffffffff812082ae)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/ring_buffer.c (ffffffff8121c8eb)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff8121fc34)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In mm/truncate.c (ffffffff81239bbd)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff81249155)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/util.c (ffffffff8124b741)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
```
```
In mm/percpu.c (ffffffff828dd2d2)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_page_first_chunk
```
```
In mm/slab_common.c (ffffffff81254914)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/memory.c (ffffffff8126b69f)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:copy_subpage
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/vmalloc.c (ffffffff8127d372)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
```
```
In mm/page_alloc.c (ffffffff812876ef)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:__get_free_pages
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/swapfile.c (ffffffff8128de09)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff812950b7)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/sparse-vmemmap.c (ffffffff81ae6524)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffff812a87b8)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff812a8c90)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
```
```
In mm/slub.c (ffffffff812aa7b5)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab_slab
  - mm/slub.c:__check_heap_object
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
  - mm/slub.c:print_trailer
  - mm/slub.c:get_map
```
```
In mm/migrate.c (ffffffff812b4664)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812ba731)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812c2cd4)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/swap_cgroup.c (ffffffff812d04b5)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/zbud.c (ffffffff812d5648)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (ffffffff812d7a08)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/userfaultfd.c (ffffffff812d9956)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff812e2968)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (ffffffff812ec5d1)
Location: include/linux/mm.h:1314
Inline: True
```
```
In fs/namei.c (ffffffff812f0765)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/namei.c:__page_symlink
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff81313d03)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/splice.c (ffffffff8131e690)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/splice.c:write_pipe_buf
  - fs/splice.c:default_file_splice_read
```
```
In fs/buffer.c (ffffffff8132b97a)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/direct-io.c (ffffffff81330b53)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff81332b86)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff813469c3)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_read_events
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:aio_setup_ring
```
```
In fs/io_uring.c (ffffffff81349cca)
Location: include/linux/mm.h:1314
Inline: True
```
```
In fs/dax.c (ffffffff81351593)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/verity/verify.c (ffffffff8135a473)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/verity/verify.c:extract_hash
```
```
In fs/binfmt_elf.c (ffffffff81364f7a)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff813687e2)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap/buffered-io.c (ffffffff8136e007)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inline.c (ffffffff813b17e5)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff813b7522)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff813c49b5)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff813cd04f)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813d6c0e)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813d7382)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff813f2fb4)
Location: include/linux/mm.h:1314
Inline: True
```
```
In fs/ext4/verity.c (ffffffff813f9b63)
Location: include/linux/mm.h:1314
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff813fc33a)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813fe1b3)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff814067c7)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff8140930c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff8140b1fb)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff8140b94e)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff8140bc96)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_next_page
  - fs/squashfs/page_actor.c:direct_first_page
```
```
In fs/ecryptfs/mmap.c (ffffffff814200a3)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff814208f4)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffffffff8142214f)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/dev.c (ffffffff8142c280)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_do
```
```
In fs/fuse/dir.c (ffffffff8142ea53)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readlink_page
```
```
In fs/fuse/file.c (ffffffff81433c5d)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (ffffffff8143c0aa)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/selinux/selinuxfs.c (ffffffff8147382d)
Location: include/linux/mm.h:1314
Inline: True
```
```
In security/selinux/ss/status.c (ffffffff81486c34)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - security/selinux/ss/status.c:selinux_status_update_policyload
  - security/selinux/ss/status.c:selinux_status_update_setenforce
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
```
In security/tomoyo/domain.c (ffffffff81498f6a)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff814cdf10)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff814cfb25)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff814d155c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff814d230c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
  - crypto/ahash.c:hash_walk_next
```
```
In crypto/shash.c (ffffffff814d3aed)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff814edc30)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_truncate
  - block/bio.c:zero_fill_bio_iter
```
```
In block/blk-mq.c (ffffffff8150032d)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In block/partition-generic.c (ffffffff8150878a)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/bounce.c (ffffffff815138fa)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:copy_to_high_bio_irq
  - block/bounce.c:copy_to_high_bio_irq
```
```
In block/bio-integrity.c (ffffffff81523c78)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/t10-pi.c (ffffffff8152547f)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/scatterlist.c (ffffffff81530ac3)
Location: include/linux/mm.h:1314
Inline: True
```
```
In lib/iov_iter.c (ffffffff8153288b)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:memcpy_mcsafe_to_page
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
```
```
In drivers/acpi/osl.c (ffffffff81ae18ee)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8166ef77)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:return_free_pages_to_mm
```
```
In drivers/xen/grant-table.c (ffffffff816713ff)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81672e2e)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff816d00f4)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff816de4f1)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816e06bd)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (ffffffff816e0ca7)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff816e1f79)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
```
In drivers/iommu/amd_iommu.c (ffffffff816f1e19)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:free_page_list
```
```
In drivers/iommu/dmar.c (ffffffff816f5f00)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff816f6c30)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dma_free_pagelist
  - drivers/iommu/intel-iommu.c:dma_pte_list_pagetables
  - drivers/iommu/intel-iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel-pasid.c (ffffffff816fe572)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel-svm.c (ffffffff81700546)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81701b25)
Location: include/linux/mm.h:1314
Inline: True
```
```
In drivers/base/firmware_loader/main.c (ffffffff81728125)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff81728ca2)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_rw
```
```
In drivers/block/loop.c (ffffffff817387b4)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff8173d000)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8176f10e)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
```
```
In drivers/dma-buf/udmabuf.c (ffffffff817791d5)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:kmap_udmabuf
```
```
In drivers/scsi/scsi_lib.c (ffffffff81781bd4)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/sd.c (ffffffff81793236)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/mm.h:1314
Inline: True
```
```
In drivers/ata/libata-scsi.c (ffffffff817a8035)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
```
```
In drivers/ata/libata-sff.c (ffffffff817b4d02)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/net/tun.c (ffffffff817d2796)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff817dc164)
Location: include/linux/mm.h:1314
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff818017fe)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff8180b46e)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/md/md.c (ffffffff818aac3e)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_90_sync
  - drivers/md/md.c:super_90_validate
```
```
In drivers/md/md-bitmap.c (ffffffff818b606e)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (ffffffff818c91db)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/firmware/efi/capsule.c (ffffffff818fb1df)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/sock.c (ffffffff81923cee)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
```
```
In net/core/skbuff.c (ffffffff8192cab7)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_dump
```
```
In net/core/datagram.c (ffffffff819336c4)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/dev.c (ffffffff8193bd74)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/dev.c:skb_gro_reset_offset
```
```
In net/core/filter.c (ffffffff819704db)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/tso.c (ffffffff81973c6b)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/skmsg.c (ffffffff8197b4c7)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/ipv4/ip_output.c (ffffffff819c8a0b)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp.c (ffffffff819d60af)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81a4efe9)
Location: include/linux/mm.h:1314
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff81ac437d)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81adaef7)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
```
</details>
</li>
</ul>

## Differences
