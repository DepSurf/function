# Function: <code>alloc_pages</code>

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
In init/do_mounts.c (ffffffff81f5a385)
Location: include/linux/gfp.h:456
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff81066e6a)
Location: include/linux/gfp.h:456
Inline: True
```
```
In arch/x86/mm/pageattr.c (ffffffff8106d556)
Location: include/linux/gfp.h:456
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/pgtable.c (ffffffff81070be6)
Location: include/linux/gfp.h:456
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81f7aeb3)
Location: include/linux/gfp.h:456
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In kernel/power/snapshot.c (ffffffff810d0366)
Location: include/linux/gfp.h:456
Inline: True
Inline callers:
  - kernel/power/snapshot.c:alloc_image_page
```
```
In kernel/kexec_core.c (ffffffff8110c47c)
Location: include/linux/gfp.h:456
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/relay.c (ffffffff8113d539)
Location: include/linux/gfp.h:456
Inline: True
```
```
In kernel/trace/trace.c (ffffffff81151580)
Location: include/linux/gfp.h:456
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
```
In kernel/events/uprobes.c (ffffffff81187173)
Location: include/linux/gfp.h:456
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In mm/filemap.c (ffffffff8118d674)
Location: include/linux/gfp.h:456
Inline: True
```
```
In mm/mempool.c (ffffffff8118fe59)
Location: include/linux/gfp.h:456
Inline: True
Inline callers:
  - mm/mempool.c:mempool_alloc_pages
```
```
In mm/page_alloc.c (ffffffff81191b49)
Location: include/linux/gfp.h:456
Inline: True
Inline callers:
  - mm/page_alloc.c:get_zeroed_page
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:alloc_kmem_pages
```
```
In mm/memory.c (ffffffff811beab5)
Location: include/linux/gfp.h:456
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/vmalloc.c (ffffffff811cf1ae)
Location: include/linux/gfp.h:456
Inline: True
```
```
In mm/swapfile.c (ffffffff811d71e5)
Location: include/linux/gfp.h:456
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
```
```
In mm/sparse-vmemmap.c (ffffffff8181f0eb)
Location: include/linux/gfp.h:456
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffffffff811e9a17)
Location: include/linux/gfp.h:456
Inline: True
Inline callers:
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
```
```
In mm/huge_memory.c (ffffffff811f5a2f)
Location: include/linux/gfp.h:456
Inline: True
Inline callers:
  - mm/huge_memory.c:get_huge_zero_page
```
```
In mm/swap_cgroup.c (ffffffff81200ca3)
Location: include/linux/gfp.h:456
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_swapon
```
```
In mm/page_isolation.c (ffffffff81204159)
Location: include/linux/gfp.h:456
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In mm/zbud.c (ffffffff81204919)
Location: include/linux/gfp.h:456
Inline: True
Inline callers:
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (ffffffff81205b27)
Location: include/linux/gfp.h:456
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (ffffffff81207466)
Location: include/linux/gfp.h:456
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_enqueue
```
```
In fs/pipe.c (ffffffff81215010)
Location: include/linux/gfp.h:456
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/splice.c (ffffffff8123f087)
Location: include/linux/gfp.h:456
Inline: True
Inline callers:
  - fs/splice.c:default_file_splice_read
```
```
In fs/ecryptfs/crypto.c (ffffffff81305c2a)
Location: include/linux/gfp.h:456
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In fs/fuse/dev.c (ffffffff8130dfbf)
Location: include/linux/gfp.h:456
Inline: True
```
```
In fs/fuse/dir.c (ffffffff813134a4)
Location: include/linux/gfp.h:456
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readdir
```
```
In fs/fuse/file.c (ffffffff81315b8f)
Location: include/linux/gfp.h:456
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepages_fill
```
```
In security/selinux/ss/status.c (ffffffff8135cae4)
Location: include/linux/gfp.h:456
Inline: True
Inline callers:
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
```
In block/bio.c (ffffffff813b0568)
Location: include/linux/gfp.h:456
Inline: True
Inline callers:
  - block/bio.c:bio_alloc_pages
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_copy_kern
```
```
In drivers/xen/balloon.c (ffffffff814c6527)
Location: include/linux/gfp.h:456
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff815175ae)
Location: include/linux/gfp.h:456
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff8151d7b6)
Location: include/linux/gfp.h:456
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81521cc5)
Location: include/linux/gfp.h:456
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81526547)
Location: include/linux/gfp.h:456
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
```
```
In drivers/iommu/amd_iommu.c (ffffffff81531280)
Location: include/linux/gfp.h:456
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
```
```
In drivers/iommu/intel-iommu.c (ffffffff8153b002)
Location: include/linux/gfp.h:456
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
```
```
In drivers/iommu/intel-svm.c (ffffffff8153c43e)
Location: include/linux/gfp.h:456
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables
  - drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/base/firmware_class.c (ffffffff8155e910)
Location: include/linux/gfp.h:456
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:firmware_data_write
```
```
In drivers/block/brd.c (ffffffff8156cfaf)
Location: include/linux/gfp.h:456
Inline: True
```
```
In drivers/block/loop.c (ffffffff81570721)
Location: include/linux/gfp.h:456
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/block/xen-blkfront.c (ffffffff81576cd3)
Location: include/linux/gfp.h:456
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
```
```
In drivers/scsi/sd.c (ffffffff815bf2f6)
Location: include/linux/gfp.h:456
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_discard_cmnd
```
```
In drivers/scsi/sg.c (ffffffff815c49cf)
Location: include/linux/gfp.h:456
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff815f2b2a)
Location: include/linux/gfp.h:456
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:try_fill_recv
```
```
In drivers/net/xen-netfront.c (ffffffff815fb122)
Location: include/linux/gfp.h:456
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In drivers/md/md.c (ffffffff81691f76)
Location: include/linux/gfp.h:456
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_load
```
```
In drivers/md/bitmap.c (ffffffff8169e06f)
Location: include/linux/gfp.h:456
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
```
```
In drivers/md/dm-kcopyd.c (ffffffff816abb80)
Location: include/linux/gfp.h:456
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:alloc_pl
```
```
In net/core/sock.c (ffffffff8170170e)
Location: include/linux/gfp.h:456
Inline: True
```
```
In net/core/skbuff.c (ffffffff8170666d)
Location: include/linux/gfp.h:456
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
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
In init/do_mounts.c (ffffffff81f82330)
Location: include/linux/gfp.h:467
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff81066c38)
Location: include/linux/gfp.h:467
Inline: True
```
```
In arch/x86/mm/pageattr.c (ffffffff8106d357)
Location: include/linux/gfp.h:467
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/pgtable.c (ffffffff810709e6)
Location: include/linux/gfp.h:467
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81fa3944)
Location: include/linux/gfp.h:467
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In kernel/power/snapshot.c (ffffffff810d4ef6)
Location: include/linux/gfp.h:467
Inline: True
Inline callers:
  - kernel/power/snapshot.c:alloc_image_page
```
```
In kernel/kexec_core.c (ffffffff81113cfc)
Location: include/linux/gfp.h:467
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/relay.c (ffffffff81145d16)
Location: include/linux/gfp.h:467
Inline: True
```
```
In kernel/trace/trace.c (ffffffff8115a600)
Location: include/linux/gfp.h:467
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
```
In kernel/events/uprobes.c (ffffffff81199693)
Location: include/linux/gfp.h:467
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In mm/filemap.c (ffffffff811a026d)
Location: include/linux/gfp.h:467
Inline: True
```
```
In mm/mempool.c (ffffffff811a4009)
Location: include/linux/gfp.h:467
Inline: True
Inline callers:
  - mm/mempool.c:mempool_alloc_pages
```
```
In mm/page_alloc.c (ffffffff811a90c6)
Location: include/linux/gfp.h:467
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:get_zeroed_page
```
```
In mm/slab_common.c (ffffffff811cc230)
Location: include/linux/gfp.h:467
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
```
```
In mm/memory.c (ffffffff811da90c)
Location: include/linux/gfp.h:467
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/vmalloc.c (ffffffff811ec33a)
Location: include/linux/gfp.h:467
Inline: True
```
```
In mm/swapfile.c (ffffffff811f5367)
Location: include/linux/gfp.h:467
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
```
```
In mm/sparse-vmemmap.c (ffffffff81899645)
Location: include/linux/gfp.h:467
Inline: True
```
```
In mm/slub.c (ffffffff8120854d)
Location: include/linux/gfp.h:467
Inline: True
Inline callers:
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
```
```
In mm/huge_memory.c (ffffffff81214060)
Location: include/linux/gfp.h:467
Inline: True
Inline callers:
  - mm/huge_memory.c:get_huge_zero_page
```
```
In mm/swap_cgroup.c (ffffffff81225410)
Location: include/linux/gfp.h:467
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_swapon
```
```
In mm/page_isolation.c (ffffffff812290f4)
Location: include/linux/gfp.h:467
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In mm/zbud.c (ffffffff81229895)
Location: include/linux/gfp.h:467
Inline: True
Inline callers:
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (ffffffff8122af90)
Location: include/linux/gfp.h:467
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (ffffffff8122cde6)
Location: include/linux/gfp.h:467
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_enqueue
```
```
In fs/pipe.c (ffffffff8123be73)
Location: include/linux/gfp.h:467
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/splice.c (ffffffff812673a3)
Location: include/linux/gfp.h:467
Inline: True
Inline callers:
  - fs/splice.c:default_file_splice_read
```
```
In fs/dax.c (ffffffff81287644)
Location: include/linux/gfp.h:467
Inline: True
Inline callers:
  - fs/dax.c:read_dax_sector
```
```
In fs/ecryptfs/crypto.c (ffffffff8133a8b6)
Location: include/linux/gfp.h:467
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/dev.c (ffffffff8134258f)
Location: include/linux/gfp.h:467
Inline: True
```
```
In fs/fuse/dir.c (ffffffff81347a21)
Location: include/linux/gfp.h:467
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readdir
```
```
In fs/fuse/file.c (ffffffff8134a4ee)
Location: include/linux/gfp.h:467
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In security/selinux/ss/status.c (ffffffff81392ab4)
Location: include/linux/gfp.h:467
Inline: True
Inline callers:
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
```
In block/bio.c (ffffffff813f62c7)
Location: include/linux/gfp.h:467
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81516c5b)
Location: include/linux/gfp.h:467
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff8156a25a)
Location: include/linux/gfp.h:467
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff81570576)
Location: include/linux/gfp.h:467
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/char/agp/intel-gtt.c (ffffffff815754e5)
Location: include/linux/gfp.h:467
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81579d9d)
Location: include/linux/gfp.h:467
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
```
```
In drivers/iommu/amd_iommu.c (ffffffff81584dec)
Location: include/linux/gfp.h:467
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
```
```
In drivers/iommu/intel-iommu.c (ffffffff8158fad2)
Location: include/linux/gfp.h:467
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
```
```
In drivers/iommu/intel-svm.c (ffffffff81591116)
Location: include/linux/gfp.h:467
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables
  - drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables
```
```
In drivers/base/firmware_class.c (ffffffff815b2f19)
Location: include/linux/gfp.h:467
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:firmware_data_write
```
```
In drivers/block/brd.c (ffffffff815c27cf)
Location: include/linux/gfp.h:467
Inline: True
```
```
In drivers/block/loop.c (ffffffff815c6328)
Location: include/linux/gfp.h:467
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/block/xen-blkfront.c (ffffffff815cd4d1)
Location: include/linux/gfp.h:467
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
```
```
In drivers/scsi/sd.c (ffffffff81614f09)
Location: include/linux/gfp.h:467
Inline: True
```
```
In drivers/scsi/sg.c (ffffffff8161d1e8)
Location: include/linux/gfp.h:467
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff81652796)
Location: include/linux/gfp.h:467
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:try_fill_recv
```
```
In drivers/net/xen-netfront.c (ffffffff8165b06f)
Location: include/linux/gfp.h:467
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In drivers/md/md.c (ffffffff816f4a76)
Location: include/linux/gfp.h:467
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_load
```
```
In drivers/md/bitmap.c (ffffffff816ff2ec)
Location: include/linux/gfp.h:467
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
```
```
In drivers/md/dm-kcopyd.c (ffffffff8170c090)
Location: include/linux/gfp.h:467
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:alloc_pl
```
```
In drivers/firmware/efi/capsule.c (ffffffff8173536a)
Location: include/linux/gfp.h:467
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/sock.c (ffffffff81768977)
Location: include/linux/gfp.h:467
Inline: True
```
```
In net/core/skbuff.c (ffffffff8176e23c)
Location: include/linux/gfp.h:467
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_copy_ubufs
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
In init/do_mounts.c (ffffffff81fbe3d1)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff8106a87f)
Location: include/linux/gfp.h:460
Inline: True
```
```
In arch/x86/mm/pageattr.c (ffffffff81070f94)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/pgtable.c (ffffffff81074676)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81fdf24d)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In kernel/power/snapshot.c (ffffffff810dbaa6)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - kernel/power/snapshot.c:alloc_image_page
```
```
In kernel/kexec_core.c (ffffffff8111b40c)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/relay.c (ffffffff8114fa3c)
Location: include/linux/gfp.h:460
Inline: True
```
```
In kernel/trace/trace.c (ffffffff81164e1d)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
```
In kernel/events/uprobes.c (ffffffff811aa6c3)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In mm/filemap.c (ffffffff811af6ad)
Location: include/linux/gfp.h:460
Inline: True
```
```
In mm/mempool.c (ffffffff811b4369)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - mm/mempool.c:mempool_alloc_pages
```
```
In mm/page_alloc.c (ffffffff811b6a99)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - mm/page_alloc.c:__get_free_pages
```
```
In mm/slab_common.c (ffffffff811dc2d8)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/memory.c (ffffffff811ea47c)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/vmalloc.c (ffffffff811fd5da)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_node_range
```
```
In mm/swapfile.c (ffffffff81205e9a)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
```
```
In mm/sparse-vmemmap.c (ffffffff818cdcf7)
Location: include/linux/gfp.h:460
Inline: True
```
```
In mm/slub.c (ffffffff8121a5b9)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
```
```
In mm/huge_memory.c (ffffffff812264a2)
Location: include/linux/gfp.h:460
Inline: True
```
```
In mm/swap_cgroup.c (ffffffff812379f0)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_swapon
```
```
In mm/page_isolation.c (ffffffff8123b694)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In mm/zbud.c (ffffffff8123be35)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (ffffffff8123d4f4)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (ffffffff8123f306)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_enqueue
```
```
In fs/pipe.c (ffffffff8124ebf4)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/dax.c (ffffffff8129b204)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - fs/dax.c:read_dax_sector
```
```
In fs/ecryptfs/crypto.c (ffffffff81350656)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/dev.c (ffffffff813583bf)
Location: include/linux/gfp.h:460
Inline: True
```
```
In fs/fuse/dir.c (ffffffff8135d36e)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readdir
```
```
In fs/fuse/file.c (ffffffff8135fcff)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In security/selinux/ss/status.c (ffffffff813a96e4)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
```
In crypto/scompress.c (ffffffff813fabe7)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - crypto/scompress.c:scomp_acomp_comp_decomp
```
```
In block/bio.c (ffffffff8140fcb7)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_alloc_pages
```
```
In block/blk-zoned.c (ffffffff81448cb4)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_report_zones
```
```
In lib/iov_iter.c (ffffffff8145f887)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - lib/iov_iter.c:push_pipe
```
```
In drivers/xen/balloon.c (ffffffff815430b9)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff8159699a)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff8159cc36)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/char/agp/intel-gtt.c (ffffffff815a1b75)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff815a62e0)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
```
```
In drivers/iommu/amd_iommu.c (ffffffff815b1ece)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
```
```
In drivers/iommu/intel-iommu.c (ffffffff815bd313)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
```
```
In drivers/iommu/intel-svm.c (ffffffff815be9e6)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables
  - drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables
```
```
In drivers/base/firmware_class.c (ffffffff815e231a)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:firmware_data_write
```
```
In drivers/block/loop.c (ffffffff815f48bc)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/block/xen-blkfront.c (ffffffff815fa091)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
```
```
In drivers/scsi/sd.c (ffffffff816447f7)
Location: include/linux/gfp.h:460
Inline: True
```
```
In drivers/scsi/sg.c (ffffffff8164dde8)
Location: include/linux/gfp.h:460
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff81688ec7)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In drivers/md/md.c (ffffffff817277a2)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:super_1_load
```
```
In drivers/md/bitmap.c (ffffffff81730f2e)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
```
```
In drivers/md/dm-kcopyd.c (ffffffff8173e0c0)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:alloc_pl
```
```
In drivers/firmware/efi/capsule.c (ffffffff817684ea)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In drivers/firmware/efi/memmap.c (ffffffff820224fa)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
```
In net/core/sock.c (ffffffff81795887)
Location: include/linux/gfp.h:460
Inline: True
```
```
In net/core/skbuff.c (ffffffff8179b67c)
Location: include/linux/gfp.h:460
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_copy_ubufs
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
In init/do_mounts.c (ffffffff8209e50f)
Location: include/linux/gfp.h:505
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff81069b5f)
Location: include/linux/gfp.h:505
Inline: True
```
```
In arch/x86/mm/pageattr.c (ffffffff810706da)
Location: include/linux/gfp.h:505
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/pgtable.c (ffffffff81073bc6)
Location: include/linux/gfp.h:505
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff820c019f)
Location: include/linux/gfp.h:505
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In kernel/power/snapshot.c (ffffffff810db006)
Location: include/linux/gfp.h:505
Inline: True
Inline callers:
  - kernel/power/snapshot.c:alloc_image_page
```
```
In kernel/kexec_core.c (ffffffff8111d2cc)
Location: include/linux/gfp.h:505
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/relay.c (ffffffff81152192)
Location: include/linux/gfp.h:505
Inline: True
```
```
In kernel/trace/trace.c (ffffffff81168171)
Location: include/linux/gfp.h:505
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
```
In kernel/events/uprobes.c (ffffffff811b1c13)
Location: include/linux/gfp.h:505
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In mm/filemap.c (ffffffff811b656f)
Location: include/linux/gfp.h:505
Inline: True
```
```
In mm/mempool.c (ffffffff811baf59)
Location: include/linux/gfp.h:505
Inline: True
Inline callers:
  - mm/mempool.c:mempool_alloc_pages
```
```
In mm/page_alloc.c (ffffffff811be939)
Location: include/linux/gfp.h:505
Inline: True
Inline callers:
  - mm/page_alloc.c:__get_free_pages
```
```
In mm/slab_common.c (ffffffff811e61f8)
Location: include/linux/gfp.h:505
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/memory.c (ffffffff811f54fc)
Location: include/linux/gfp.h:505
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/vmalloc.c (ffffffff812082b2)
Location: include/linux/gfp.h:505
Inline: True
```
```
In mm/swapfile.c (ffffffff8121160a)
Location: include/linux/gfp.h:505
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
```
```
In mm/sparse-vmemmap.c (ffffffff81905173)
Location: include/linux/gfp.h:505
Inline: True
```
```
In mm/slub.c (ffffffff8122605a)
Location: include/linux/gfp.h:505
Inline: True
Inline callers:
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
```
```
In mm/huge_memory.c (ffffffff81232351)
Location: include/linux/gfp.h:505
Inline: True
```
```
In mm/swap_cgroup.c (ffffffff8124362b)
Location: include/linux/gfp.h:505
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_swapon
```
```
In mm/zbud.c (ffffffff81247a98)
Location: include/linux/gfp.h:505
Inline: True
Inline callers:
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (ffffffff81248e83)
Location: include/linux/gfp.h:505
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (ffffffff8124ac56)
Location: include/linux/gfp.h:505
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_enqueue
```
```
In fs/pipe.c (ffffffff8125aaee)
Location: include/linux/gfp.h:505
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/ecryptfs/crypto.c (ffffffff81365166)
Location: include/linux/gfp.h:505
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/dev.c (ffffffff8136cfb1)
Location: include/linux/gfp.h:505
Inline: True
```
```
In fs/fuse/dir.c (ffffffff81371d4d)
Location: include/linux/gfp.h:505
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readdir
```
```
In fs/fuse/file.c (ffffffff813748ec)
Location: include/linux/gfp.h:505
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In security/selinux/ss/status.c (ffffffff813c00a4)
Location: include/linux/gfp.h:505
Inline: True
Inline callers:
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
```
In crypto/scompress.c (ffffffff81407601)
Location: include/linux/gfp.h:505
Inline: True
Inline callers:
  - crypto/scompress.c:scomp_acomp_comp_decomp
```
```
In block/bio.c (ffffffff8141d658)
Location: include/linux/gfp.h:505
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_alloc_pages
```
```
In block/blk-zoned.c (ffffffff81457234)
Location: include/linux/gfp.h:505
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_report_zones
```
```
In lib/iov_iter.c (ffffffff81464b77)
Location: include/linux/gfp.h:505
Inline: True
Inline callers:
  - lib/iov_iter.c:push_pipe
```
```
In drivers/xen/balloon.c (ffffffff81556fa8)
Location: include/linux/gfp.h:505
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff815aa793)
Location: include/linux/gfp.h:505
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff815b0d06)
Location: include/linux/gfp.h:505
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/char/agp/intel-gtt.c (ffffffff815b575c)
Location: include/linux/gfp.h:505
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff815b71e8)
Location: include/linux/gfp.h:505
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm-interface.c:tpm_getcap
  - drivers/char/tpm/tpm-interface.c:tpm_startup
  - drivers/char/tpm/tpm-interface.c:tpm_startup
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff815babff)
Location: include/linux/gfp.h:505
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
In drivers/char/tpm/tpm2-space.c (ffffffff815bc178)
Location: include/linux/gfp.h:505
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/iommu/amd_iommu.c (ffffffff815c7b5b)
Location: include/linux/gfp.h:505
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
```
```
In drivers/iommu/intel-iommu.c (ffffffff815d2f43)
Location: include/linux/gfp.h:505
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
```
```
In drivers/iommu/intel-svm.c (ffffffff815d4606)
Location: include/linux/gfp.h:505
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables
  - drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables
```
```
In drivers/base/firmware_class.c (ffffffff815f7023)
Location: include/linux/gfp.h:505
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:firmware_data_write
```
```
In drivers/block/loop.c (ffffffff81608b2e)
Location: include/linux/gfp.h:505
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/block/xen-blkfront.c (ffffffff8160e1c6)
Location: include/linux/gfp.h:505
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
```
```
In drivers/scsi/sd.c (ffffffff8165a84f)
Location: include/linux/gfp.h:505
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sg.c (ffffffff816626f5)
Location: include/linux/gfp.h:505
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff8169e5cf)
Location: include/linux/gfp.h:505
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In drivers/md/md.c (ffffffff81740062)
Location: include/linux/gfp.h:505
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:super_1_load
```
```
In drivers/md/bitmap.c (ffffffff81749e7c)
Location: include/linux/gfp.h:505
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
```
```
In drivers/md/dm-kcopyd.c (ffffffff81757bca)
Location: include/linux/gfp.h:505
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:alloc_pl
```
```
In drivers/firmware/efi/capsule.c (ffffffff81786dbd)
Location: include/linux/gfp.h:505
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In drivers/firmware/efi/memmap.c (ffffffff8210522e)
Location: include/linux/gfp.h:505
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
```
In net/core/sock.c (ffffffff817b3542)
Location: include/linux/gfp.h:505
Inline: True
```
```
In net/core/skbuff.c (ffffffff817bd1d5)
Location: include/linux/gfp.h:505
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_copy_ubufs
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
In init/do_mounts.c (ffffffff826a44dd)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102a6e4)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff8106e40f)
Location: include/linux/gfp.h:490
Inline: True
```
```
In arch/x86/mm/pageattr.c (ffffffff81075d9a)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/pgtable.c (ffffffff810795e6)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff826c8356)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In kernel/power/snapshot.c (ffffffff810e3076)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - kernel/power/snapshot.c:alloc_image_page
```
```
In kernel/kexec_core.c (ffffffff811289f4)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/relay.c (ffffffff8115e842)
Location: include/linux/gfp.h:490
Inline: True
```
```
In kernel/trace/trace.c (ffffffff81175114)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
```
In kernel/events/uprobes.c (ffffffff811c5823)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In mm/filemap.c (ffffffff811ca8da)
Location: include/linux/gfp.h:490
Inline: True
```
```
In mm/mempool.c (ffffffff811cfb49)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - mm/mempool.c:mempool_alloc_pages
```
```
In mm/page_alloc.c (ffffffff811d36a9)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - mm/page_alloc.c:__get_free_pages
```
```
In mm/slab_common.c (ffffffff811fc438)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/memory.c (ffffffff8120e3cc)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/vmalloc.c (ffffffff81221371)
Location: include/linux/gfp.h:490
Inline: True
```
```
In mm/swapfile.c (ffffffff8122bf57)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
```
```
In mm/slub.c (ffffffff812431e1)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
```
```
In mm/huge_memory.c (ffffffff8124fa11)
Location: include/linux/gfp.h:490
Inline: True
```
```
In mm/swap_cgroup.c (ffffffff8126347b)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_swapon
```
```
In mm/zbud.c (ffffffff81267c48)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (ffffffff812690b3)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (ffffffff8126aec6)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_alloc
```
```
In fs/pipe.c (ffffffff8127ce8e)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/ecryptfs/crypto.c (ffffffff81389e36)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/dev.c (ffffffff81391b07)
Location: include/linux/gfp.h:490
Inline: True
```
```
In fs/fuse/dir.c (ffffffff81396a4d)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readdir
```
```
In fs/fuse/file.c (ffffffff8139959e)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In security/selinux/ss/status.c (ffffffff813e6244)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
```
In crypto/scompress.c (ffffffff8142ff1b)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - crypto/scompress.c:scomp_acomp_comp_decomp
```
```
In block/bio.c (ffffffff814484e8)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_alloc_pages
```
```
In block/blk-zoned.c (ffffffff81482f39)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_report_zones
```
```
In lib/iov_iter.c (ffffffff81490af7)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - lib/iov_iter.c:push_pipe
```
```
In drivers/xen/balloon.c (ffffffff815bafb4)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff81611119)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff816178a6)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8161c7a9)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff8161de58)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm-interface.c:tpm_getcap
  - drivers/char/tpm/tpm-interface.c:tpm_startup
  - drivers/char/tpm/tpm-interface.c:tpm_startup
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff8161f236)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816212d3)
Location: include/linux/gfp.h:490
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
In drivers/char/tpm/tpm2-space.c (ffffffff81622658)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/iommu/amd_iommu.c (ffffffff8162e82b)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
```
```
In drivers/iommu/intel-iommu.c (ffffffff81639c43)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
```
```
In drivers/iommu/intel-svm.c (ffffffff8163b396)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables
  - drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables
```
```
In drivers/base/firmware_class.c (ffffffff8165ef53)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:firmware_data_write
```
```
In drivers/block/loop.c (ffffffff816713d7)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/block/xen-blkfront.c (ffffffff81676a46)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
```
```
In drivers/scsi/sd.c (ffffffff816c3a15)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sg.c (ffffffff816cbd45)
Location: include/linux/gfp.h:490
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff8170976f)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In drivers/md/md.c (ffffffff817b2712)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:super_1_load
```
```
In drivers/md/md-bitmap.c (ffffffff817bc15c)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:bitmap_resize
  - drivers/md/md-bitmap.c:bitmap_resize
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_create
```
```
In drivers/md/dm-kcopyd.c (ffffffff817c9e3a)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:alloc_pl
```
```
In drivers/firmware/efi/capsule.c (ffffffff817fd24d)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In drivers/firmware/efi/memmap.c (ffffffff8270e8f7)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
```
In net/core/sock.c (ffffffff8182b90f)
Location: include/linux/gfp.h:490
Inline: True
```
```
In net/core/skbuff.c (ffffffff81833bb5)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_copy_ubufs
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
In init/do_mounts.c (ffffffff826cd607)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102ae0f)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
```
```
In arch/x86/mm/pageattr.c (ffffffff810788e0)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/pgtable.c (ffffffff8107c1a5)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff826f2293)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In kernel/power/snapshot.c (ffffffff810ed21e)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - kernel/power/snapshot.c:alloc_image_page
```
```
In kernel/kexec_core.c (ffffffff81136a65)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/relay.c (ffffffff8116d727)
Location: include/linux/gfp.h:490
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811840a2)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
```
In kernel/events/uprobes.c (ffffffff811e5d7f)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In mm/filemap.c (ffffffff811eb913)
Location: include/linux/gfp.h:490
Inline: True
```
```
In mm/mempool.c (ffffffff811f0dc5)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - mm/mempool.c:mempool_alloc_pages
```
```
In mm/page_alloc.c (ffffffff811f4965)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - mm/page_alloc.c:__get_free_pages
```
```
In mm/slab_common.c (ffffffff8121d595)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/memory.c (ffffffff8122edc8)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/vmalloc.c (ffffffff8124322f)
Location: include/linux/gfp.h:490
Inline: True
```
```
In mm/swapfile.c (ffffffff8124e415)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
```
```
In mm/slub.c (ffffffff81264a42)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
```
```
In mm/huge_memory.c (ffffffff81273f6b)
Location: include/linux/gfp.h:490
Inline: True
```
```
In mm/swap_cgroup.c (ffffffff8128775a)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_swapon
```
```
In mm/zbud.c (ffffffff8128c5a8)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (ffffffff8128e081)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (ffffffff8128f8b5)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_alloc
```
```
In fs/pipe.c (ffffffff812a3e20)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/ecryptfs/crypto.c (ffffffff813b8cab)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/dev.c (ffffffff813c05a0)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_fill
```
```
In fs/fuse/dir.c (ffffffff813c5c22)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readdir
```
```
In fs/fuse/file.c (ffffffff813c817e)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In security/keys/big_key.c (ffffffff813ecf0c)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_alloc_buffer
```
```
In security/selinux/ss/status.c (ffffffff81416f47)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
```
In block/bio.c (ffffffff8147b62c)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_user_iov
```
```
In block/blk-zoned.c (ffffffff814b7bbc)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_report_zones
```
```
In lib/scatterlist.c (ffffffff814c4af9)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_alloc_order
```
```
In lib/iov_iter.c (ffffffff814c58d6)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - lib/iov_iter.c:push_pipe
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff81549517)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/xen/balloon.c (ffffffff815f3664)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff8164ab99)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff816513a5)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81656402)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff81657b55)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm-interface.c:tpm_getcap
  - drivers/char/tpm/tpm-interface.c:tpm_startup
  - drivers/char/tpm/tpm-interface.c:tpm_startup
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff8165900a)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff8165b08f)
Location: include/linux/gfp.h:490
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
In drivers/char/tpm/tpm2-space.c (ffffffff8165c415)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/iommu/amd_iommu.c (ffffffff8166950b)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
```
```
In drivers/iommu/intel-iommu.c (ffffffff81674db3)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
```
```
In drivers/iommu/intel-svm.c (ffffffff816768b5)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables
  - drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff8169b5f9)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
```
```
In drivers/block/loop.c (ffffffff816ad0f9)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/block/xen-blkfront.c (ffffffff816b22a3)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
```
```
In drivers/scsi/sd.c (ffffffff816ffba9)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sg.c (ffffffff81708691)
Location: include/linux/gfp.h:490
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff81748255)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In drivers/md/md.c (ffffffff817f5c87)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:super_1_load
```
```
In drivers/md/md-bitmap.c (ffffffff81804224)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:bitmap_resize
  - drivers/md/md-bitmap.c:bitmap_resize
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_create
```
```
In drivers/md/dm-kcopyd.c (ffffffff81812b1a)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:alloc_pl
```
```
In drivers/firmware/efi/capsule.c (ffffffff81846a7c)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In drivers/firmware/efi/memmap.c (ffffffff82738bc3)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
```
In net/core/sock.c (ffffffff81877230)
Location: include/linux/gfp.h:490
Inline: True
```
```
In net/core/skbuff.c (ffffffff8187e030)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/filter.c (ffffffff818b39f8)
Location: include/linux/gfp.h:490
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pull_data
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
In init/do_mounts.c (ffffffff828835de)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102b53f)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff828a0720)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_setup_vsyscall_timeinfo
```
```
In arch/x86/mm/pageattr.c (ffffffff8107f0cc)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/pgtable.c (ffffffff81082b35)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828a929c)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In kernel/power/snapshot.c (ffffffff810f8880)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - kernel/power/snapshot.c:alloc_image_page
```
```
In kernel/kexec_core.c (ffffffff811420c5)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/relay.c (ffffffff8117b16d)
Location: include/linux/gfp.h:507
Inline: True
```
```
In kernel/trace/trace.c (ffffffff81191a12)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
```
In kernel/events/uprobes.c (ffffffff811f68cf)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In mm/filemap.c (ffffffff811fc493)
Location: include/linux/gfp.h:507
Inline: True
```
```
In mm/mempool.c (ffffffff81202c25)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - mm/mempool.c:mempool_alloc_pages
```
```
In mm/page_alloc.c (ffffffff81206da5)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - mm/page_alloc.c:__get_free_pages
```
```
In mm/slab_common.c (ffffffff81230585)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/memory.c (ffffffff81241858)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/vmalloc.c (ffffffff81257932)
Location: include/linux/gfp.h:507
Inline: True
```
```
In mm/swapfile.c (ffffffff812627d5)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
```
```
In mm/slub.c (ffffffff812791d8)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
```
```
In mm/huge_memory.c (ffffffff81288f8b)
Location: include/linux/gfp.h:507
Inline: True
```
```
In mm/swap_cgroup.c (ffffffff8129c6aa)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_swapon
```
```
In mm/zbud.c (ffffffff812a1528)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (ffffffff812a39b1)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (ffffffff812a47d5)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_alloc
```
```
In fs/pipe.c (ffffffff812b8f6e)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/ecryptfs/crypto.c (ffffffff813d221b)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/dev.c (ffffffff813d9d90)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_fill
```
```
In fs/fuse/dir.c (ffffffff813dde72)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
```
```
In fs/fuse/file.c (ffffffff813e13b6)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (ffffffff813ea0d0)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In security/keys/big_key.c (ffffffff814080ec)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_alloc_buffer
```
```
In security/selinux/ss/status.c (ffffffff81433457)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
```
In block/bio.c (ffffffff8149979c)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_user_iov
```
```
In lib/scatterlist.c (ffffffff814d91e9)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_alloc_order
```
```
In lib/iov_iter.c (ffffffff814da076)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - lib/iov_iter.c:push_pipe
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8155fc19)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8160b9ae)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:report_free_page_func
```
```
In drivers/xen/balloon.c (ffffffff8160e65e)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff81668e59)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff8166f575)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81674285)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81677907)
Location: include/linux/gfp.h:507
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff81679043)
Location: include/linux/gfp.h:507
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
In drivers/char/tpm/tpm2-space.c (ffffffff81679785)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff8167a6ea)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
```
In drivers/iommu/amd_iommu.c (ffffffff81687d6b)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
```
```
In drivers/iommu/intel-iommu.c (ffffffff816933e3)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
```
```
In drivers/iommu/intel-svm.c (ffffffff81695a25)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/lightnvm/core.c (ffffffff81698cb2)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff816bbe79)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
```
```
In drivers/block/loop.c (ffffffff816cd425)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/block/xen-blkfront.c (ffffffff816d2da3)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
```
```
In drivers/scsi/sg.c (ffffffff8172ab9d)
Location: include/linux/gfp.h:507
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff8176c315)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In drivers/md/md.c (ffffffff81821c07)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:super_1_load
```
```
In drivers/md/md-bitmap.c (ffffffff81830424)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In drivers/md/dm-kcopyd.c (ffffffff8183ea9a)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:alloc_pl
```
```
In drivers/firmware/efi/capsule.c (ffffffff81872cdc)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In drivers/firmware/efi/memmap.c (ffffffff828f2b6f)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
```
In net/core/sock.c (ffffffff81896760)
Location: include/linux/gfp.h:507
Inline: True
```
```
In net/core/skbuff.c (ffffffff8189ebef)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/filter.c (ffffffff818d95b6)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
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
In init/do_mounts.c (ffffffff8289a5fb)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102d2ac)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff828b88ba)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
```
```
In arch/x86/mm/pageattr.c (ffffffff81082f61)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/pgtable.c (ffffffff81086755)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c1a85)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In kernel/power/snapshot.c (ffffffff81100ed3)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - kernel/power/snapshot.c:alloc_image_page
```
```
In kernel/kexec_core.c (ffffffff8114d475)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/relay.c (ffffffff81188110)
Location: include/linux/gfp.h:507
Inline: True
```
```
In kernel/trace/trace.c (ffffffff8119f424)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
```
In kernel/events/uprobes.c (ffffffff8120e685)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In mm/filemap.c (ffffffff81213b5b)
Location: include/linux/gfp.h:507
Inline: True
```
```
In mm/mempool.c (ffffffff8121a035)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - mm/mempool.c:mempool_alloc_pages
```
```
In mm/slab_common.c (ffffffff812405a5)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/memory.c (ffffffff812541d8)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/vmalloc.c (ffffffff8126a68e)
Location: include/linux/gfp.h:507
Inline: True
```
```
In mm/page_alloc.c (ffffffff8126cdd5)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - mm/page_alloc.c:__get_free_pages
```
```
In mm/swapfile.c (ffffffff8127d6d5)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
```
```
In mm/slub.c (ffffffff81293f61)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/huge_memory.c (ffffffff812a3c40)
Location: include/linux/gfp.h:507
Inline: True
```
```
In mm/swap_cgroup.c (ffffffff812b7857)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_swapon
```
```
In mm/zbud.c (ffffffff812bc8a5)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (ffffffff812bedbd)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (ffffffff812bfd55)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_alloc
```
```
In fs/pipe.c (ffffffff812d5b72)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/ecryptfs/crypto.c (ffffffff813fcc7e)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/dev.c (ffffffff81405920)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_fill
```
```
In fs/fuse/dir.c (ffffffff81409e60)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
```
```
In fs/fuse/file.c (ffffffff8140d084)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (ffffffff814163c7)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In security/keys/big_key.c (ffffffff8143512c)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_alloc_buffer
```
```
In security/selinux/ss/status.c (ffffffff81460e78)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
```
In block/bio.c (ffffffff814c78fc)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_user_iov
```
```
In lib/scatterlist.c (ffffffff81505085)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_alloc_order
```
```
In lib/iov_iter.c (ffffffff81505885)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - lib/iov_iter.c:push_pipe
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8158fed7)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8163f67c)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
```
```
In drivers/xen/balloon.c (ffffffff816423e0)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff8169e7c9)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff816a50b5)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816aa22f)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff816ac7c1)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_send
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff816ad575)
Location: include/linux/gfp.h:507
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff816af7d5)
Location: include/linux/gfp.h:507
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
In drivers/char/tpm/tpm2-space.c (ffffffff816afdc8)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff816b1093)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
```
In drivers/iommu/amd_iommu.c (ffffffff816c0b2a)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
```
```
In drivers/iommu/intel-iommu.c (ffffffff816cb803)
Location: include/linux/gfp.h:507
Inline: True
```
```
In drivers/iommu/intel-svm.c (ffffffff816ce325)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/lightnvm/core.c (ffffffff816d1702)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
```
```
In drivers/base/firmware_loader/main.c (ffffffff816f54fc)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/block/loop.c (ffffffff8170967c)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/block/xen-blkfront.c (ffffffff8170b24b)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
```
```
In drivers/scsi/sg.c (ffffffff817662ce)
Location: include/linux/gfp.h:507
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff817aa135)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In drivers/md/md.c (ffffffff81864777)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:super_1_load
```
```
In drivers/md/md-bitmap.c (ffffffff81872b71)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
```
In drivers/md/dm-kcopyd.c (ffffffff818817ef)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:alloc_pl
```
```
In drivers/firmware/efi/capsule.c (ffffffff818b6ebc)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In drivers/firmware/efi/memmap.c (ffffffff8290e34a)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:__efi_memmap_alloc_late
```
```
In net/core/sock.c (ffffffff818e0b27)
Location: include/linux/gfp.h:507
Inline: True
```
```
In net/core/skbuff.c (ffffffff818e9431)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/filter.c (ffffffff8192b77a)
Location: include/linux/gfp.h:507
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
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
In init/do_mounts.c (ffffffff8289d5e0)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102dbbc)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff828beda8)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
```
```
In arch/x86/mm/pageattr.c (ffffffff81084031)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/pgtable.c (ffffffff81087445)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c7efe)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In kernel/power/snapshot.c (ffffffff8110d333)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - kernel/power/snapshot.c:alloc_image_page
```
```
In kernel/kexec_core.c (ffffffff8115916b)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/relay.c (ffffffff81194050)
Location: include/linux/gfp.h:536
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811aade4)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
```
In kernel/events/uprobes.c (ffffffff8121bcc5)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In mm/filemap.c (ffffffff8122132b)
Location: include/linux/gfp.h:536
Inline: True
```
```
In mm/mempool.c (ffffffff812279a5)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/mempool.c:mempool_alloc_pages
```
```
In mm/slab_common.c (ffffffff8124eb15)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/memory.c (ffffffff81262738)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/vmalloc.c (ffffffff812795a0)
Location: include/linux/gfp.h:536
Inline: True
```
```
In mm/page_alloc.c (ffffffff8127bbe5)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/page_alloc.c:__get_free_pages
```
```
In mm/swapfile.c (ffffffff8128d175)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
```
```
In mm/slub.c (ffffffff812a3cd1)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/huge_memory.c (ffffffff812b5140)
Location: include/linux/gfp.h:536
Inline: True
```
```
In mm/swap_cgroup.c (ffffffff812c9737)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_swapon
```
```
In mm/zbud.c (ffffffff812ce795)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (ffffffff812d0d1d)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (ffffffff812d1ca5)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_alloc
```
```
In fs/pipe.c (ffffffff812e76e2)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/ecryptfs/crypto.c (ffffffff81416b5e)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/dev.c (ffffffff8141f8e0)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_fill
```
```
In fs/fuse/dir.c (ffffffff814234a0)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
```
```
In fs/fuse/file.c (ffffffff8142850b)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (ffffffff814302cb)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In security/keys/big_key.c (ffffffff8144eeac)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_alloc_buffer
```
```
In security/selinux/ss/status.c (ffffffff8147ac28)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
```
In block/bio.c (ffffffff814e09f2)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_user_iov
```
```
In lib/scatterlist.c (ffffffff81522a95)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_alloc_order
```
```
In lib/iov_iter.c (ffffffff81523835)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - lib/iov_iter.c:push_pipe
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815b1ef7)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81661a9c)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
```
```
In drivers/xen/balloon.c (ffffffff816649b0)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff816c1879)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff816c7de5)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816ccf6f)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff816d0255)
Location: include/linux/gfp.h:536
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff816d24c7)
Location: include/linux/gfp.h:536
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
In drivers/char/tpm/tpm2-space.c (ffffffff816d2ac8)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff816d3d93)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
```
In drivers/iommu/amd_iommu.c (ffffffff816e3b5a)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
```
```
In drivers/iommu/intel-iommu.c (ffffffff816eeba3)
Location: include/linux/gfp.h:536
Inline: True
```
```
In drivers/iommu/intel-svm.c (ffffffff816f2165)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/lightnvm/core.c (ffffffff816f56b2)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
```
```
In drivers/base/firmware_loader/main.c (ffffffff817198fc)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/block/loop.c (ffffffff8172da24)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/block/xen-blkfront.c (ffffffff8172f54b)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
```
```
In drivers/scsi/sg.c (ffffffff8178a2be)
Location: include/linux/gfp.h:536
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff817cdb95)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d511e)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
```
In drivers/md/md.c (ffffffff818964b7)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:super_1_load
```
```
In drivers/md/md-bitmap.c (ffffffff818a4971)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
```
In drivers/md/dm-kcopyd.c (ffffffff818b368f)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:alloc_pl
```
```
In drivers/firmware/efi/capsule.c (ffffffff818e981c)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In drivers/firmware/efi/memmap.c (ffffffff82917d63)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:__efi_memmap_alloc_late
```
```
In net/core/sock.c (ffffffff81912cf7)
Location: include/linux/gfp.h:536
Inline: True
```
```
In net/core/skbuff.c (ffffffff8191b591)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/filter.c (ffffffff8195daad)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
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
In init/do_mounts.c (ffffffff82cc3c75)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102feab)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff82ce309b)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
```
```
In arch/x86/mm/pgtable.c (ffffffff810898f5)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108e0cd)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff82cead34)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In kernel/power/snapshot.c (ffffffff811182e9)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - kernel/power/snapshot.c:alloc_image_page
```
```
In kernel/dma/pool.c (ffffffff8113f6b0)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - kernel/dma/pool.c:atomic_pool_expand
```
```
In kernel/time/namespace.c (ffffffff81159c10)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - kernel/time/namespace.c:clone_time_ns
```
```
In kernel/kexec_core.c (ffffffff81169fa6)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/relay.c (ffffffff811a80bb)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - kernel/relay.c:relay_alloc_buf
```
```
In kernel/trace/trace.c (ffffffff811c30c3)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
```
In kernel/events/uprobes.c (ffffffff812483a1)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In kernel/watch_queue.c (ffffffff8124d024)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_size
```
```
In mm/filemap.c (ffffffff81252e25)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
```
```
In mm/mempool.c (ffffffff81254325)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - mm/mempool.c:mempool_alloc_pages
```
```
In mm/slab_common.c (ffffffff8127cdd5)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/memory.c (ffffffff81292638)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/vmalloc.c (ffffffff812ac3f0)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff812b1c13)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:get_zeroed_page
```
```
In mm/swapfile.c (ffffffff812bfc15)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
```
```
In mm/slub.c (ffffffff812d9819)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/huge_memory.c (ffffffff812e8717)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - mm/huge_memory.c:get_huge_zero_page
```
```
In mm/swap_cgroup.c (ffffffff812fed9c)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_swapon
```
```
In mm/zbud.c (ffffffff81304a69)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (ffffffff8130594d)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - mm/zsmalloc.c:alloc_zspage
```
```
In mm/balloon_compaction.c (ffffffff813078e5)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_alloc
```
```
In fs/pipe.c (ffffffff8131f6e6)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/squashfs/block.c (ffffffff814493e9)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_bio_read
```
```
In fs/ecryptfs/crypto.c (ffffffff8146514d)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/dev.c (ffffffff8146e970)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_fill
```
```
In fs/fuse/dir.c (ffffffff81472a10)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
```
```
In fs/fuse/file.c (ffffffff814761b7)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (ffffffff814807df)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In security/selinux/status.c (ffffffff814be498)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - security/selinux/status.c:selinux_kernel_status_page
```
```
In block/blk-map.c (ffffffff8154a034)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:bio_copy_user_iov
```
```
In lib/scatterlist.c (ffffffff815865ea)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_alloc_order
```
```
In lib/iov_iter.c (ffffffff81586f22)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - lib/iov_iter.c:push_pipe
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8165b4d7)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8170fa0d)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:get_free_page_and_send
```
```
In drivers/xen/balloon.c (ffffffff81714530)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff81774df5)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff8177c585)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81781f4f)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_setup_scratch_page
```
```
In drivers/iommu/intel/iommu.c (ffffffff817a61ea)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_alloc_coherent
```
```
In drivers/iommu/intel/svm.c (ffffffff817a9fb5)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
```
```
In drivers/lightnvm/core.c (ffffffff817adf12)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
```
```
In drivers/base/firmware_loader/main.c (ffffffff817d5a3c)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/block/loop.c (ffffffff817e8ea0)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_read_transfer
  - drivers/block/loop.c:lo_write_transfer
```
```
In drivers/block/xen-blkfront.c (ffffffff817ed633)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:fill_grant_buffer
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff8182a8ce)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
```
```
In drivers/scsi/sg.c (ffffffff8184ea35)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_build_indirect
```
```
In drivers/net/xen-netfront.c (ffffffff818980aa)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189dee5)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_test_domain_fgsp
```
```
In drivers/md/md.c (ffffffff81963e27)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:super_1_load
```
```
In drivers/md/md-bitmap.c (ffffffff81972a05)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_storage_alloc
  - drivers/md/md-bitmap.c:md_bitmap_storage_alloc
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
```
```
In drivers/md/dm-kcopyd.c (ffffffff81983d3b)
Location: include/linux/gfp.h:543
Inline: True
```
```
In drivers/firmware/efi/capsule.c (ffffffff819bcf42)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In drivers/firmware/efi/memmap.c (ffffffff82d2a27a)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
```
In net/core/sock.c (ffffffff819e489c)
Location: include/linux/gfp.h:543
Inline: True
```
```
In net/core/skbuff.c (ffffffff819ee3fb)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/filter.c (ffffffff81a2cbdf)
Location: include/linux/gfp.h:543
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
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
In init/do_mounts.c (ffffffff82fafda3)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/hyperv/hv_init.c (ffffffff81030adb)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81067219)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff82fd0394)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
```
```
In arch/x86/mm/pgtable.c (ffffffff81089ae5)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108df9d)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff82fd85d2)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In kernel/power/snapshot.c (ffffffff81bdf780)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - kernel/power/snapshot.c:alloc_image_page
```
```
In kernel/dma/pool.c (ffffffff8113ac9e)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - kernel/dma/pool.c:atomic_pool_expand
```
```
In kernel/time/namespace.c (ffffffff81155c21)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - kernel/time/namespace.c:clone_time_ns
```
```
In kernel/kexec_core.c (ffffffff811666e6)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/relay.c (ffffffff811a563b)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - kernel/relay.c:relay_alloc_buf
```
```
In kernel/trace/trace.c (ffffffff811c0cd3)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
```
In kernel/events/uprobes.c (ffffffff81252ab1)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In kernel/watch_queue.c (ffffffff81257484)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_size
```
```
In mm/filemap.c (ffffffff8125d9f2)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read_get_pages
  - mm/filemap.c:pagecache_get_page
```
```
In mm/mempool.c (ffffffff8125ecf5)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - mm/mempool.c:mempool_alloc_pages
```
```
In mm/slab_common.c (ffffffff81288c7f)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/memory.c (ffffffff8129ceeb)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/vmalloc.c (ffffffff812b797a)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff812bd58d)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:get_zeroed_page
```
```
In mm/swapfile.c (ffffffff812cb7c5)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
```
```
In mm/slub.c (ffffffff812e4fe6)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
```
In mm/huge_memory.c (ffffffff812f3a27)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - mm/huge_memory.c:get_huge_zero_page
```
```
In mm/swap_cgroup.c (ffffffff8130b0dc)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_swapon
```
```
In mm/zbud.c (ffffffff813107c5)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (ffffffff813116ad)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - mm/zsmalloc.c:alloc_zspage
```
```
In mm/balloon_compaction.c (ffffffff81313615)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_alloc
```
```
In fs/pipe.c (ffffffff8132abf6)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/squashfs/block.c (ffffffff81465b5c)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_bio_read
```
```
In fs/ecryptfs/crypto.c (ffffffff814809f3)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/dev.c (ffffffff814890f0)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_fill
```
```
In fs/fuse/dir.c (ffffffff8148d3a7)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
```
```
In fs/fuse/file.c (ffffffff81490c1c)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (ffffffff8149bebf)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In security/selinux/status.c (ffffffff814dbeb8)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - security/selinux/status.c:selinux_kernel_status_page
```
```
In block/blk-map.c (ffffffff81565de4)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:bio_copy_user_iov
```
```
In lib/scatterlist.c (ffffffff815a38d1)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_alloc_order
```
```
In lib/iov_iter.c (ffffffff815a4702)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - lib/iov_iter.c:push_pipe
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8172c80d)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:get_free_page_and_send
```
```
In drivers/xen/balloon.c (ffffffff81730c10)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff8178fb45)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff817956d5)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81c09edf)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_setup_scratch_page
```
```
In drivers/iommu/intel/svm.c (ffffffff817b6455)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
```
```
In drivers/lightnvm/core.c (ffffffff817c2a92)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
```
```
In drivers/base/firmware_loader/main.c (ffffffff817ea44c)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/block/loop.c (ffffffff817fc4dd)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_read_transfer
  - drivers/block/loop.c:lo_write_transfer
```
```
In drivers/block/xen-blkfront.c (ffffffff81801f63)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:fill_grant_buffer
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff8183b27f)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
```
```
In drivers/scsi/sg.c (ffffffff8185f3b4)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_build_indirect
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818acc75)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_test_domain_fgsp
```
```
In drivers/md/md.c (ffffffff8196a717)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:super_1_load
```
```
In drivers/md/md-bitmap.c (ffffffff81977be5)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_storage_alloc
  - drivers/md/md-bitmap.c:md_bitmap_storage_alloc
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
```
```
In drivers/md/dm-kcopyd.c (ffffffff81987e4b)
Location: include/linux/gfp.h:545
Inline: True
```
```
In drivers/firmware/efi/memmap.c (ffffffff8301898a)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
```
In drivers/firmware/efi/capsule.c (ffffffff819becfe)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/sock.c (ffffffff819e40d7)
Location: include/linux/gfp.h:545
Inline: True
```
```
In net/core/skbuff.c (ffffffff819ee09b)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/filter.c (ffffffff81a2e197)
Location: include/linux/gfp.h:545
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *alloc_pages(gfp_t gfp, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812e2640)
Location: mm/mempolicy.c:2257
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/mm/pgtable.c:pte_alloc_one
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - kernel/power/snapshot.c:alloc_image_page
  - kernel/dma/pool.c:atomic_pool_expand
  - kernel/time/namespace.c:copy_time_ns
  - kernel/kexec_core.c:kimage_alloc_pages
  - kernel/relay.c:relay_create_buf
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/watch_queue.c:watch_queue_set_size
  - mm/mempool.c:mempool_alloc_pages
  - mm/slab_common.c:kmalloc_order
  - mm/memory.c:__pmd_alloc
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:get_zeroed_page
  - mm/swapfile.c:add_swap_count_continuation
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/zbud.c:zbud_alloc
  - mm/zsmalloc.c:alloc_zspage
  - mm/balloon_compaction.c:balloon_page_alloc
  - fs/pipe.c:pipe_write
  - fs/squashfs/block.c:squashfs_bio_read
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/fuse/dev.c:fuse_copy_fill
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - security/selinux/status.c:selinux_kernel_status_page
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:bio_copy_user_iov
  - lib/scatterlist.c:sgl_alloc_order
  - lib/iov_iter.c:push_pipe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/block/loop.c:lo_read_transfer
  - drivers/block/loop.c:lo_write_transfer
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:super_1_load
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
  - drivers/md/dm-kcopyd.c:alloc_pl
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
**Symbols:**

```
ffffffff812e2640-ffffffff812e274a: alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct page *alloc_pages(gfp_t gfp, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81329870)
Location: mm/mempolicy.c:2172
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:do_mount_root
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/mm/pgtable.c:pte_alloc_one
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - kernel/power/snapshot.c:alloc_image_page
  - kernel/dma/pool.c:atomic_pool_expand
  - kernel/dma/pool.c:atomic_pool_expand
  - kernel/time/namespace.c:copy_time_ns
  - kernel/kexec_core.c:kimage_alloc_pages
  - kernel/relay.c:relay_create_buf
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/watch_queue.c:watch_queue_set_size
  - mm/mempool.c:mempool_alloc_pages
  - mm/slab_common.c:kmalloc_order
  - mm/memory.c:__pmd_alloc
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:get_zeroed_page
  - mm/swapfile.c:add_swap_count_continuation
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/zbud.c:zbud_alloc
  - mm/zsmalloc.c:alloc_zspage
  - mm/balloon_compaction.c:balloon_page_alloc
  - mm/secretmem.c:secretmem_fault
  - fs/pipe.c:pipe_write
  - fs/squashfs/block.c:squashfs_bio_read
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/fuse/dev.c:fuse_copy_fill
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - security/selinux/status.c:selinux_kernel_status_page
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:bio_copy_user_iov
  - lib/scatterlist.c:sgl_alloc_order
  - lib/iov_iter.c:push_pipe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/block/loop.c:lo_read_transfer
  - drivers/block/loop.c:lo_write_transfer
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:super_1_load
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
  - drivers/md/dm-kcopyd.c:alloc_pl
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
**Symbols:**

```
ffffffff81329870-ffffffff81329a3f: alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct page *alloc_pages(gfp_t gfp, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81398c60)
Location: mm/mempolicy.c:2254
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:do_mount_root
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/mm/pgtable.c:pte_alloc_one
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - kernel/power/snapshot.c:alloc_image_page
  - kernel/dma/pool.c:atomic_pool_expand
  - kernel/dma/pool.c:atomic_pool_expand
  - kernel/time/namespace.c:copy_time_ns
  - kernel/kexec_core.c:kimage_alloc_pages
  - kernel/relay.c:relay_alloc_buf
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/watch_queue.c:watch_queue_set_size
  - mm/mempool.c:mempool_alloc_pages
  - mm/slab_common.c:kmalloc_order
  - mm/memory.c:__pmd_alloc
  - mm/vmalloc.c:vm_area_alloc_pages
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:get_zeroed_page
  - mm/swapfile.c:add_swap_count_continuation
  - mm/mempolicy.c:folio_alloc
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/zbud.c:zbud_alloc
  - mm/zsmalloc.c:alloc_zspage
  - mm/balloon_compaction.c:balloon_page_alloc
  - mm/secretmem.c:secretmem_fault
  - fs/pipe.c:pipe_write
  - fs/squashfs/block.c:squashfs_bio_read
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/fuse/dev.c:fuse_copy_fill
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - security/selinux/status.c:selinux_kernel_status_page
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:bio_copy_user_iov
  - io_uring/io_uring.c:io_add_buffers
  - lib/scatterlist.c:sgl_alloc_order
  - lib/iov_iter.c:push_pipe
  - lib/stackdepot.c:__stack_depot_save
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_alloc_by_type
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:super_1_load
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
  - drivers/md/dm-kcopyd.c:alloc_pl
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - net/core/sock.c:skb_page_frag_refill
  - net/core/sock.c:skb_page_frag_refill
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
```
**Symbols:**

```
ffffffff81398c60-ffffffff81398e13: alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct page *alloc_pages(gfp_t gfp, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81418ad0)
Location: mm/mempolicy.c:2269
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:do_mount_root
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/mm/pgtable.c:pte_alloc_one
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/platform/efi/memmap.c:efi_memmap_alloc
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:preallocate_image_memory
  - kernel/dma/pool.c:atomic_pool_expand
  - kernel/dma/pool.c:atomic_pool_expand
  - kernel/time/namespace.c:copy_time_ns
  - kernel/kexec_core.c:kimage_alloc_pages
  - kernel/relay.c:relay_alloc_buf
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/watch_queue.c:watch_queue_set_size
  - mm/mempool.c:mempool_alloc_pages
  - mm/memory.c:__pmd_alloc
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:get_zeroed_page
  - mm/swapfile.c:add_swap_count_continuation
  - mm/mempolicy.c:folio_alloc
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/huge_memory.c:mm_get_huge_zero_page
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/zbud.c:zbud_alloc
  - mm/zsmalloc.c:alloc_zspage
  - mm/balloon_compaction.c:balloon_page_alloc
  - mm/secretmem.c:secretmem_fault
  - fs/pipe.c:pipe_write
  - fs/squashfs/block.c:squashfs_bio_read
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/fuse/dev.c:fuse_copy_fill
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - security/selinux/status.c:selinux_kernel_status_page
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:bio_copy_user_iov
  - io_uring/kbuf.c:io_add_buffers
  - lib/scatterlist.c:sgl_alloc_order
  - lib/iov_iter.c:append_pipe
  - lib/stackdepot.c:__stack_depot_save
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_alloc_by_type
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:super_1_load
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - net/core/sock.c:skb_page_frag_refill
  - net/core/sock.c:skb_page_frag_refill
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
```
**Symbols:**

```
ffffffff81418ad0-ffffffff81418c62: alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct page *alloc_pages(gfp_t gfp, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8144bfa0)
Location: mm/mempolicy.c:2280
Inline: False
Direct callers:
  - init/do_mounts.c:mount_root_generic
  - init/do_mounts.c:do_mount_root
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/mm/pgtable.c:pte_alloc_one
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/platform/efi/memmap.c:efi_memmap_alloc
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:preallocate_image_memory
  - kernel/dma/pool.c:atomic_pool_expand
  - kernel/dma/pool.c:atomic_pool_expand
  - kernel/module/decompress.c:module_zstd_decompress
  - kernel/time/namespace.c:copy_time_ns
  - kernel/kexec_core.c:kimage_alloc_pages
  - kernel/relay.c:relay_alloc_buf
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/watch_queue.c:watch_queue_set_size
  - mm/mempool.c:mempool_alloc_pages
  - mm/memory.c:__pmd_alloc
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:get_zeroed_page
  - mm/swapfile.c:add_swap_count_continuation
  - mm/mempolicy.c:folio_alloc
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/huge_memory.c:mm_get_huge_zero_page
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/zbud.c:zbud_alloc
  - mm/zsmalloc.c:alloc_zspage
  - mm/balloon_compaction.c:balloon_page_alloc
  - mm/secretmem.c:secretmem_fault
  - fs/pipe.c:pipe_write
  - fs/squashfs/block.c:squashfs_bio_read
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/fuse/dev.c:fuse_copy_fill
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - security/selinux/status.c:selinux_kernel_status_page
  - block/blk-map.c:bio_copy_kern
  - block/blk-map.c:bio_copy_user_iov
  - io_uring/kbuf.c:io_add_buffers
  - lib/scatterlist.c:sgl_alloc_order
  - lib/stackdepot.c:__stack_depot_save
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_alloc_by_type
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/net/virtio_net.c:add_recvbuf_big
  - drivers/net/virtio_net.c:add_recvbuf_big
  - drivers/net/virtio_net.c:xdp_linearize_page
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:super_1_load
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - net/core/sock.c:skb_page_frag_refill
  - net/core/sock.c:skb_page_frag_refill
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
```
**Symbols:**

```
ffffffff8144bfa0-ffffffff8144c132: alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct page *alloc_pages(gfp_t gfp, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81485ece)
Location: mm/mempolicy.c:2193
Inline: True
Inline callers:
  - mm/mempolicy.c:folio_alloc
Direct callers:
  - init/do_mounts.c:mount_root_generic
  - init/do_mounts.c:do_mount_root
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/mm/pgtable.c:pte_alloc_one
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/platform/efi/memmap.c:efi_memmap_alloc
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:preallocate_image_memory
  - kernel/dma/swiotlb.c:swiotlb_alloc_pool
  - kernel/dma/pool.c:atomic_pool_expand
  - kernel/dma/pool.c:atomic_pool_expand
  - kernel/module/decompress.c:module_zstd_decompress
  - kernel/time/namespace.c:copy_time_ns
  - kernel/kexec_core.c:kimage_alloc_pages
  - kernel/relay.c:relay_alloc_buf
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:allocate_cmdlines_buffer
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/watch_queue.c:watch_queue_set_size
  - mm/mempool.c:mempool_alloc_pages
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__pte_alloc_kernel
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:get_zeroed_page
  - mm/swapfile.c:add_swap_count_continuation
  - mm/hugetlb_vmemmap.c:vmemmap_split_pmd
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/huge_memory.c:mm_get_huge_zero_page
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/zbud.c:zbud_alloc
  - mm/zsmalloc.c:alloc_zspage
  - mm/balloon_compaction.c:balloon_page_alloc
  - fs/pipe.c:pipe_write
  - fs/coredump.c:dump_user_range
  - fs/squashfs/block.c:squashfs_bio_read
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/fuse/dev.c:fuse_copy_fill
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - security/selinux/status.c:selinux_kernel_status_page
  - block/blk-map.c:bio_copy_kern
  - block/blk-map.c:bio_copy_user_iov
  - lib/scatterlist.c:sgl_alloc_order
  - lib/stackdepot.c:stack_depot_save_flags
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_alloc_by_type
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/net/virtio_net.c:add_recvbuf_big
  - drivers/net/virtio_net.c:add_recvbuf_big
  - drivers/net/virtio_net.c:xdp_linearize_page
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:super_1_load
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
  - drivers/md/dm-kcopyd.c:alloc_pl
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - net/core/sock.c:skb_page_frag_refill
  - net/core/sock.c:skb_page_frag_refill
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/xdp/xsk.c:xsk_build_skb
```
**Symbols:**

```
ffffffff81485dd0-ffffffff81485e9a: alloc_pages (STB_GLOBAL)
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
In init/do_mounts.c (ffff800011431708)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In virt/kvm/kvm_main.c (ffff8000100b5920)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:kvm_vcpu_init
```
```
In virt/kvm/coalesced_mmio.c (ffff8000100c0038)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - virt/kvm/coalesced_mmio.c:kvm_coalesced_mmio_init
```
```
In virt/kvm/arm/mmu.c (ffff8000100c8f90)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:__create_hyp_mappings
```
```
In kernel/dma/remap.c (ffff800011447fd0)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - kernel/dma/remap.c:dma_atomic_pool_init
```
```
In kernel/kexec_core.c (ffff8000101c8788)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/relay.c (ffff80001020ba34)
Location: include/linux/gfp.h:536
Inline: True
```
```
In kernel/trace/trace.c (ffff800010227b94)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
```
In kernel/events/uprobes.c (ffff8000102a75ec)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In mm/filemap.c (ffff8000102ae000)
Location: include/linux/gfp.h:536
Inline: True
```
```
In mm/mempool.c (ffff8000102b5004)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/mempool.c:mempool_alloc_pages
```
```
In mm/slab_common.c (ffff8000102e4dec)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/memory.c (ffff8000102f99a8)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:do_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/vmalloc.c (ffff8000103100a4)
Location: include/linux/gfp.h:536
Inline: True
```
```
In mm/page_alloc.c (ffff8000103170d8)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:get_zeroed_page
```
```
In mm/swapfile.c (ffff800010328918)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
```
```
In mm/slub.c (ffff800010345998)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/huge_memory.c (ffff800010356d80)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/swap_cgroup.c (ffff80001036ce18)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_swapon
```
```
In mm/zbud.c (ffff8000103730f4)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (ffff8000103760bc)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (ffff8000103774a8)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_alloc
```
```
In fs/pipe.c (ffff8000103903f4)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/ecryptfs/crypto.c (ffff8000104f8258)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/dev.c (ffff800010501ef8)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_fill
```
```
In fs/fuse/dir.c (ffff800010506904)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
```
```
In fs/fuse/file.c (ffff80001050a97c)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (ffff800010514e94)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In security/keys/big_key.c (ffff800010539ad4)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_alloc_buffer
```
```
In security/selinux/ss/status.c (ffff80001056b280)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
```
In block/bio.c (ffff8000105dd580)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_user_iov
```
```
In lib/scatterlist.c (ffff80001062cdbc)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_alloc_order
```
```
In lib/iov_iter.c (ffff80001062d71c)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - lib/iov_iter.c:push_pipe
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff800010674004)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_allocate_pending_table
  - drivers/irqchip/irq-gic-v3-its.c:its_allocate_prop_table
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffff80001072e418)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/dma/mv_xor.c (ffff800010807b58)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor.c:mv_xor_channel_add
```
```
In drivers/virtio/virtio_balloon.c (ffff80001082a380)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
```
```
In drivers/xen/balloon.c (ffff80001082e750)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffff8000108b2b48)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/tpm/tpm1-cmd.c (ffff8000108baac4)
Location: include/linux/gfp.h:536
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
In drivers/char/tpm/tpm2-cmd.c (ffff8000108bcf5c)
Location: include/linux/gfp.h:536
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
In drivers/char/tpm/tpm2-space.c (ffff8000108bd674)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm-sysfs.c (ffff8000108be964)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
```
In drivers/lightnvm/core.c (ffff8000108decb8)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
```
```
In drivers/base/firmware_loader/main.c (ffff80001090cf1c)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/block/loop.c (ffff800010922f78)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/block/xen-blkfront.c (ffff80001092634c)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
```
```
In drivers/scsi/sg.c (ffff80001098f288)
Location: include/linux/gfp.h:536
Inline: True
```
```
In drivers/net/xen-netfront.c (ffff800010a06dbc)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In drivers/md/md.c (ffff800010ae9a6c)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:super_1_load
```
```
In drivers/md/md-bitmap.c (ffff800010af8ff0)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
```
In drivers/md/dm-kcopyd.c (ffff800010b0a97c)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:alloc_pl
```
```
In drivers/firmware/efi/capsule.c (ffff800010b5cb5c)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In drivers/firmware/efi/memmap.c (ffff8000114a6778)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
```
In net/core/sock.c (ffff800010bac708)
Location: include/linux/gfp.h:536
Inline: True
```
```
In net/core/skbuff.c (ffff800010bb5a78)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/filter.c (ffff800010bfdb58)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (c000000001344a8c)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/powerpc/mm/pgtable-frag.c (c0000000000891e8)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - arch/powerpc/mm/pgtable-frag.c:pte_fragment_alloc
  - arch/powerpc/mm/pgtable-frag.c:pte_fragment_alloc
```
```
In arch/powerpc/mm/book3s64/pgtable.c (c000000000090fec)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/pgtable.c:pmd_fragment_alloc
```
```
In kernel/kexec_core.c (c000000000230e34)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/relay.c (c000000000289a50)
Location: include/linux/gfp.h:536
Inline: True
```
```
In kernel/trace/trace.c (c0000000002ae148)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
```
In kernel/events/uprobes.c (c00000000035aae0)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In mm/filemap.c (c000000000363120)
Location: include/linux/gfp.h:536
Inline: True
```
```
In mm/mempool.c (c00000000036c5bc)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/mempool.c:mempool_alloc_pages
```
```
In mm/slab_common.c (c0000000003a69a4)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/vmalloc.c (c0000000003e1308)
Location: include/linux/gfp.h:536
Inline: True
```
```
In mm/page_alloc.c (c0000000003e46dc)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/page_alloc.c:__get_free_pages
```
```
In mm/swapfile.c (c0000000003ffc50)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
```
```
In mm/slub.c (c000000000421f50)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/huge_memory.c (c00000000043d7c8)
Location: include/linux/gfp.h:536
Inline: True
```
```
In mm/swap_cgroup.c (c00000000045cd50)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_swapon
```
```
In mm/zbud.c (c000000000464dac)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (c0000000004660a4)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (c000000000469f5c)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_alloc
```
```
In fs/pipe.c (c000000000487f40)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/ecryptfs/crypto.c (c00000000063a054)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/dev.c (c000000000647d44)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_fill
```
```
In fs/fuse/dir.c (c00000000064bd50)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
```
```
In fs/fuse/file.c (c000000000652c70)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (c00000000065d558)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In security/keys/big_key.c (c0000000006887e4)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_alloc_buffer
```
```
In security/selinux/ss/status.c (c0000000006cf1a0)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
```
In block/bio.c (c00000000076ed4c)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_user_iov
```
```
In lib/scatterlist.c (c0000000007cfb7c)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_alloc_order
```
```
In lib/iov_iter.c (c0000000007d0968)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - lib/iov_iter.c:push_pipe
```
```
In drivers/virtio/virtio_balloon.c (c0000000008d7188)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
```
```
In drivers/char/virtio_console.c (c00000000094ce20)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (c00000000095548c)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/char/tpm/tpm1-cmd.c (c00000000095bf1c)
Location: include/linux/gfp.h:536
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
In drivers/char/tpm/tpm2-cmd.c (c00000000095ec6c)
Location: include/linux/gfp.h:536
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
In drivers/char/tpm/tpm2-space.c (c00000000095f540)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm-sysfs.c (c000000000960e4c)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
```
In drivers/lightnvm/core.c (c000000000972af0)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
```
```
In drivers/base/firmware_loader/main.c (c0000000009ad194)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/block/loop.c (c0000000009c9630)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/scsi/sg.c (c000000000a53d58)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_build_indirect
```
```
In drivers/md/md.c (c000000000bd729c)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:super_1_load
```
```
In drivers/md/md-bitmap.c (c000000000be713c)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
```
In drivers/md/dm-kcopyd.c (c000000000bfcd68)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:alloc_pl
```
```
In net/core/sock.c (c000000000c82790)
Location: include/linux/gfp.h:536
Inline: True
```
```
In net/core/skbuff.c (c000000000c8ce2c)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/filter.c (c000000000ce97c8)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In init/do_mounts.c (ffffffff8288b5e0)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102dd1c)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff828a9d7e)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
```
```
In arch/x86/mm/pageattr.c (ffffffff81083031)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/pgtable.c (ffffffff81086445)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828b2e96)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In kernel/power/snapshot.c (ffffffff81105553)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - kernel/power/snapshot.c:alloc_image_page
```
```
In kernel/kexec_core.c (ffffffff8115178b)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/relay.c (ffffffff8118c670)
Location: include/linux/gfp.h:536
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811a3404)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
```
In kernel/events/uprobes.c (ffffffff81214315)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In mm/filemap.c (ffffffff8121997b)
Location: include/linux/gfp.h:536
Inline: True
```
```
In mm/mempool.c (ffffffff8121fff5)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/mempool.c:mempool_alloc_pages
```
```
In mm/slab_common.c (ffffffff81247165)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/memory.c (ffffffff8125ad88)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/vmalloc.c (ffffffff81271bf0)
Location: include/linux/gfp.h:536
Inline: True
```
```
In mm/page_alloc.c (ffffffff81274235)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/page_alloc.c:__get_free_pages
```
```
In mm/swapfile.c (ffffffff81285755)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
```
```
In mm/slub.c (ffffffff8129c2b1)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/huge_memory.c (ffffffff812ad720)
Location: include/linux/gfp.h:536
Inline: True
```
```
In mm/swap_cgroup.c (ffffffff812c1d17)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_swapon
```
```
In mm/zbud.c (ffffffff812c6d75)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (ffffffff812c92fd)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (ffffffff812ca285)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_alloc
```
```
In fs/pipe.c (ffffffff812dfcc2)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/ecryptfs/crypto.c (ffffffff8140f13e)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/dev.c (ffffffff81417ec0)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_fill
```
```
In fs/fuse/dir.c (ffffffff8141ba80)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
```
```
In fs/fuse/file.c (ffffffff81420aeb)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (ffffffff814288ab)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In security/keys/big_key.c (ffffffff8144748c)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_alloc_buffer
```
```
In security/selinux/ss/status.c (ffffffff81473208)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
```
In block/bio.c (ffffffff814d8fd2)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_user_iov
```
```
In lib/scatterlist.c (ffffffff8151b075)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_alloc_order
```
```
In lib/iov_iter.c (ffffffff8151be15)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - lib/iov_iter.c:push_pipe
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815a56b7)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8162790c)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
```
```
In drivers/xen/balloon.c (ffffffff8162a820)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff816872c9)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff8168d835)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816929bf)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81695ca5)
Location: include/linux/gfp.h:536
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff81697f17)
Location: include/linux/gfp.h:536
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
In drivers/char/tpm/tpm2-space.c (ffffffff81698518)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff816997e3)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
```
In drivers/iommu/amd_iommu.c (ffffffff816a94fb)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
```
```
In drivers/iommu/intel-iommu.c (ffffffff816b43e8)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
```
```
In drivers/iommu/intel-svm.c (ffffffff816b7955)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/lightnvm/core.c (ffffffff816baea2)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
```
```
In drivers/base/firmware_loader/main.c (ffffffff816dfc2c)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/block/loop.c (ffffffff816f3804)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/block/xen-blkfront.c (ffffffff816f54bb)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
```
```
In drivers/scsi/sg.c (ffffffff8173e9ae)
Location: include/linux/gfp.h:536
Inline: True
```
```
In drivers/nvme/host/core.c (ffffffff8174243c)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_init_ctrl
```
```
In drivers/net/xen-netfront.c (ffffffff817927b5)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In drivers/md/md.c (ffffffff8183c337)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:super_1_load
```
```
In drivers/md/md-bitmap.c (ffffffff8184a7f1)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
```
In drivers/md/dm-kcopyd.c (ffffffff8185950f)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:alloc_pl
```
```
In drivers/firmware/efi/capsule.c (ffffffff8188c59c)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In drivers/firmware/efi/memmap.c (ffffffff828fd169)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:__efi_memmap_alloc_late
```
```
In net/core/sock.c (ffffffff818b2cf7)
Location: include/linux/gfp.h:536
Inline: True
```
```
In net/core/skbuff.c (ffffffff818bb591)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/filter.c (ffffffff818fda7d)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
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
In init/do_mounts.c (ffffffff8288955d)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8101d69b)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff828a205f)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
```
```
In arch/x86/mm/pageattr.c (ffffffff8107181a)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
```
```
In arch/x86/mm/pgtable.c (ffffffff810751c5)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828ab017)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In kernel/power/snapshot.c (ffffffff810f67f3)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - kernel/power/snapshot.c:alloc_image_page
```
```
In kernel/kexec_core.c (ffffffff81144a6b)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/relay.c (ffffffff8117f750)
Location: include/linux/gfp.h:536
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811963d4)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
```
In kernel/events/uprobes.c (ffffffff81207085)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In mm/filemap.c (ffffffff8120cb8b)
Location: include/linux/gfp.h:536
Inline: True
```
```
In mm/mempool.c (ffffffff812131a5)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/mempool.c:mempool_alloc_pages
```
```
In mm/slab_common.c (ffffffff8123a115)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/memory.c (ffffffff8124d116)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/vmalloc.c (ffffffff81263b60)
Location: include/linux/gfp.h:536
Inline: True
```
```
In mm/page_alloc.c (ffffffff812661a5)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/page_alloc.c:__get_free_pages
```
```
In mm/swapfile.c (ffffffff812775c5)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
```
```
In mm/slub.c (ffffffff8128de62)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/huge_memory.c (ffffffff8129eda0)
Location: include/linux/gfp.h:536
Inline: True
```
```
In mm/swap_cgroup.c (ffffffff812b2d67)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_swapon
```
```
In mm/zbud.c (ffffffff812b7db5)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (ffffffff812ba33d)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (ffffffff812bb2c5)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_alloc
```
```
In fs/pipe.c (ffffffff812d0902)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/ecryptfs/crypto.c (ffffffff813ffbbe)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/dev.c (ffffffff81408940)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_fill
```
```
In fs/fuse/dir.c (ffffffff8140c500)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
```
```
In fs/fuse/file.c (ffffffff8141156b)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (ffffffff8141932b)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In security/keys/big_key.c (ffffffff81437edc)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_alloc_buffer
```
```
In security/selinux/ss/status.c (ffffffff81463c28)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
```
In block/bio.c (ffffffff814c9982)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_user_iov
```
```
In lib/scatterlist.c (ffffffff8150b365)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_alloc_order
```
```
In lib/iov_iter.c (ffffffff8150c105)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - lib/iov_iter.c:push_pipe
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff81594857)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8161bf8c)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
```
```
In drivers/char/virtio_console.c (ffffffff81664eb9)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff8166b225)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816703af)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81673695)
Location: include/linux/gfp.h:536
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff81675907)
Location: include/linux/gfp.h:536
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
In drivers/char/tpm/tpm2-space.c (ffffffff81675f08)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff816771d3)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
```
In drivers/iommu/amd_iommu.c (ffffffff81686f9a)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
```
```
In drivers/iommu/intel-iommu.c (ffffffff81691fd3)
Location: include/linux/gfp.h:536
Inline: True
```
```
In drivers/iommu/intel-svm.c (ffffffff81695595)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/base/firmware_loader/main.c (ffffffff816ba26c)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/block/loop.c (ffffffff816cd904)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/scsi/sg.c (ffffffff8172064e)
Location: include/linux/gfp.h:536
Inline: True
```
```
In drivers/nvme/host/core.c (ffffffff817240cc)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_init_ctrl
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177f1ce)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
```
In drivers/md/md.c (ffffffff81803997)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:super_1_load
```
```
In drivers/md/md-bitmap.c (ffffffff81811e21)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
```
In drivers/md/dm-kcopyd.c (ffffffff81820b1f)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:alloc_pl
```
```
In drivers/firmware/efi/capsule.c (ffffffff81843f1c)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In drivers/firmware/efi/memmap.c (ffffffff828f4a05)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:__efi_memmap_alloc_late
```
```
In drivers/hv/channel.c (ffffffff81850f23)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/hv/channel.c:vmbus_alloc_ring
```
```
In net/core/sock.c (ffffffff8186cc47)
Location: include/linux/gfp.h:536
Inline: True
```
```
In net/core/skbuff.c (ffffffff818754d1)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/filter.c (ffffffff818b78ad)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
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
In init/do_mounts.c (ffffffff8289e5e0)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102db7c)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff828bcc7d)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
```
```
In arch/x86/mm/pageattr.c (ffffffff81082fe1)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/pgtable.c (ffffffff810863f5)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c5d95)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In kernel/power/snapshot.c (ffffffff81103803)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - kernel/power/snapshot.c:alloc_image_page
```
```
In kernel/kexec_core.c (ffffffff8114f63b)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/relay.c (ffffffff8118a440)
Location: include/linux/gfp.h:536
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811a11d4)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
```
In kernel/events/uprobes.c (ffffffff812120b5)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In mm/filemap.c (ffffffff8121771b)
Location: include/linux/gfp.h:536
Inline: True
```
```
In mm/mempool.c (ffffffff8121dd95)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/mempool.c:mempool_alloc_pages
```
```
In mm/slab_common.c (ffffffff81244f05)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/memory.c (ffffffff81258b28)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/vmalloc.c (ffffffff8126f990)
Location: include/linux/gfp.h:536
Inline: True
```
```
In mm/page_alloc.c (ffffffff81271fd5)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/page_alloc.c:__get_free_pages
```
```
In mm/swapfile.c (ffffffff81283565)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
```
```
In mm/slub.c (ffffffff8129a0c1)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/huge_memory.c (ffffffff812ab530)
Location: include/linux/gfp.h:536
Inline: True
```
```
In mm/swap_cgroup.c (ffffffff812bfb27)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_swapon
```
```
In mm/zbud.c (ffffffff812c4b85)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (ffffffff812c710d)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (ffffffff812c8095)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_alloc
```
```
In fs/pipe.c (ffffffff812ddad2)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/ecryptfs/crypto.c (ffffffff8140c4be)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/dev.c (ffffffff81414060)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_fill
```
```
In fs/fuse/dir.c (ffffffff81417c20)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
```
```
In fs/fuse/file.c (ffffffff8141cc8b)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (ffffffff81424a4b)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In security/keys/big_key.c (ffffffff8144352c)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_alloc_buffer
```
```
In security/selinux/ss/status.c (ffffffff8146f2a8)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
```
In block/bio.c (ffffffff814d5062)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_user_iov
```
```
In lib/scatterlist.c (ffffffff81517105)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_alloc_order
```
```
In lib/iov_iter.c (ffffffff81517ea5)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - lib/iov_iter.c:push_pipe
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815a5c47)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/virtio/virtio_balloon.c (ffffffff816558dc)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
```
```
In drivers/xen/balloon.c (ffffffff816587f0)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff816b5609)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff816bbaa5)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816c0c2f)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff816c3f15)
Location: include/linux/gfp.h:536
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff816c6187)
Location: include/linux/gfp.h:536
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
In drivers/char/tpm/tpm2-space.c (ffffffff816c6788)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff816c7a53)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
```
In drivers/iommu/amd_iommu.c (ffffffff816d781a)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
```
```
In drivers/iommu/intel-iommu.c (ffffffff816e2863)
Location: include/linux/gfp.h:536
Inline: True
```
```
In drivers/iommu/intel-svm.c (ffffffff816e5e25)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/lightnvm/core.c (ffffffff816e9372)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
```
```
In drivers/base/firmware_loader/main.c (ffffffff8170d34c)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/block/loop.c (ffffffff81720ee4)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/block/xen-blkfront.c (ffffffff81722a0b)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
```
```
In drivers/scsi/sg.c (ffffffff8177f13e)
Location: include/linux/gfp.h:536
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff817c2a15)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817c9f9e)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
```
In drivers/md/md.c (ffffffff8188b967)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:super_1_load
```
```
In drivers/md/md-bitmap.c (ffffffff81899e21)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
```
In drivers/md/dm-kcopyd.c (ffffffff818a8b3f)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:alloc_pl
```
```
In drivers/firmware/efi/capsule.c (ffffffff818de67c)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In drivers/firmware/efi/memmap.c (ffffffff82912398)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:__efi_memmap_alloc_late
```
```
In net/core/sock.c (ffffffff81903cf7)
Location: include/linux/gfp.h:536
Inline: True
```
```
In net/core/skbuff.c (ffffffff8190c591)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/filter.c (ffffffff8194eaad)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
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
In init/do_mounts.c (ffffffff8289e5e5)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102e96c)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff828bfdd5)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
```
```
In arch/x86/mm/pageattr.c (ffffffff810850ed)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/pgtable.c (ffffffff81088535)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c8f3b)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In kernel/power/snapshot.c (ffffffff8110ebf3)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - kernel/power/snapshot.c:alloc_image_page
```
```
In kernel/kexec_core.c (ffffffff8115c45b)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/relay.c (ffffffff81197db0)
Location: include/linux/gfp.h:536
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811aef64)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
```
In kernel/events/uprobes.c (ffffffff81221035)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In mm/filemap.c (ffffffff812267cb)
Location: include/linux/gfp.h:536
Inline: True
```
```
In mm/mempool.c (ffffffff8122ce05)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/mempool.c:mempool_alloc_pages
```
```
In mm/slab_common.c (ffffffff812548f5)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/memory.c (ffffffff81268528)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/vmalloc.c (ffffffff8127f385)
Location: include/linux/gfp.h:536
Inline: True
```
```
In mm/page_alloc.c (ffffffff81281a35)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/page_alloc.c:__get_free_pages
```
```
In mm/swapfile.c (ffffffff81293245)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
```
```
In mm/slub.c (ffffffff812a9f2a)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/huge_memory.c (ffffffff812bb880)
Location: include/linux/gfp.h:536
Inline: True
```
```
In mm/swap_cgroup.c (ffffffff812d0594)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_swapon
```
```
In mm/zbud.c (ffffffff812d5611)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (ffffffff812d69bb)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (ffffffff812d8da5)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_alloc
```
```
In fs/pipe.c (ffffffff812eea52)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/ecryptfs/crypto.c (ffffffff8142213e)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/dev.c (ffffffff8142bc70)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_fill
```
```
In fs/fuse/dir.c (ffffffff8142ea10)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
```
```
In fs/fuse/file.c (ffffffff81433a6d)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (ffffffff8143b8db)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In security/keys/big_key.c (ffffffff8145a85c)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_alloc_buffer
```
```
In security/selinux/ss/status.c (ffffffff81486b18)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
```
In block/bio.c (ffffffff814edc12)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_user_iov
```
```
In lib/scatterlist.c (ffffffff81530895)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_alloc_order
```
```
In lib/iov_iter.c (ffffffff81531645)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - lib/iov_iter.c:push_pipe
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815c0047)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8166ef5c)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
```
```
In drivers/xen/balloon.c (ffffffff81672df0)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff816d0099)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff816d6075)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816db1ff)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff816de4c5)
Location: include/linux/gfp.h:536
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff816e0687)
Location: include/linux/gfp.h:536
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
In drivers/char/tpm/tpm2-space.c (ffffffff816e0c78)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff816e1f43)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
```
In drivers/iommu/amd_iommu.c (ffffffff816f1dca)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
```
```
In drivers/iommu/intel-iommu.c (ffffffff816fcec3)
Location: include/linux/gfp.h:536
Inline: True
```
```
In drivers/iommu/intel-svm.c (ffffffff81700525)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/lightnvm/core.c (ffffffff81703bb2)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
```
```
In drivers/base/firmware_loader/main.c (ffffffff81727f6c)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/block/loop.c (ffffffff8173c241)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/block/xen-blkfront.c (ffffffff8173de4b)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
```
```
In drivers/scsi/sg.c (ffffffff81798f3e)
Location: include/linux/gfp.h:536
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff817dccd5)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e423e)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
```
In drivers/md/md.c (ffffffff818aabd7)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:super_1_load
```
```
In drivers/md/md-bitmap.c (ffffffff818b5f91)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
```
In drivers/md/dm-kcopyd.c (ffffffff818c4f4f)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:alloc_pl
```
```
In drivers/firmware/efi/capsule.c (ffffffff818fb174)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In drivers/firmware/efi/memmap.c (ffffffff82918dc5)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:__efi_memmap_alloc_late
```
```
In net/core/sock.c (ffffffff81924cf7)
Location: include/linux/gfp.h:536
Inline: True
```
```
In net/core/skbuff.c (ffffffff8192d6c1)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/filter.c (ffffffff8197047d)
Location: include/linux/gfp.h:536
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
