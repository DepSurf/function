# Function: <code>__free_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __free_pages(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81194dc0)
Location: mm/page_alloc.c:3283
Inline: True
Direct callers:
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
  - arch/x86/mm/pageattr.c:__change_page_attr
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:profile_cpu_callback
  - kernel/profile.c:profile_cpu_callback
  - kernel/profile.c:profile_cpu_callback
  - kernel/kexec_core.c:kimage_free_pages
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/relay.c:relay_destroy_buf
  - kernel/trace/trace.c:tracing_spd_release_pipe
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/events/ring_buffer.c:perf_mmap_free_page
  - kernel/events/ring_buffer.c:rb_irq_work
  - kernel/events/uprobes.c:__create_xol_area
  - mm/mempool.c:mempool_free_pages
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:alloc_kmem_pages
  - mm/page_alloc.c:__free_kmem_pages
  - mm/page_alloc.c:__free_kmem_pages
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:alloc_kmem_pages_node
  - mm/page_alloc.c:free_contig_range
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/compaction.c:release_freepages
  - mm/memory.c:__pte_alloc
  - mm/vmalloc.c:__vunmap
  - mm/swapfile.c:SyS_swapoff
  - mm/swapfile.c:add_swap_count_continuation
  - mm/hugetlb.c:update_and_free_page
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
  - mm/memory_hotplug.c:generic_online_page
  - mm/memory_hotplug.c:put_page_bootmem
  - mm/huge_memory.c:get_huge_zero_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/zbud.c:free_zbud_page
  - mm/zsmalloc.c:free_zspage
  - mm/zsmalloc.c:free_zspage
  - mm/zsmalloc.c:free_zspage
  - fs/pipe.c:free_pipe_info
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:default_file_splice_read
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepages_fill
  - block/bio.c:bio_alloc_pages
  - block/bio.c:bio_uncopy_user
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio
  - drivers/xen/grant-table.c:gnttab_handle_deferred
  - drivers/xen/balloon.c:balloon_process
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
  - drivers/char/agp/intel-gtt.c:intel_gtt_cleanup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/iommu/amd_iommu.c:free_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
  - drivers/base/firmware_class.c:__fw_free_buf
  - drivers/base/firmware_class.c:firmware_loading_store
  - drivers/block/brd.c:brd_free_pages
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/scsi/sd.c:sd_uninit_command
  - drivers/scsi/sd.c:sd_setup_discard_cmnd
  - drivers/md/dm-kcopyd.c:kcopyd_put_pages
  - drivers/md/dm-kcopyd.c:drop_pages
```
**Symbols:**

```
ffffffff81194dc0-ffffffff81194de4: __free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __free_pages(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811a8f20)
Location: mm/page_alloc.c:3751
Inline: True
Direct callers:
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
  - arch/x86/mm/pageattr.c:__change_page_attr
  - kernel/fork.c:free_task
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/profile.c:profile_dead_cpu
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
  - kernel/relay.c:relay_destroy_buf
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_spd_release_pipe
  - kernel/events/ring_buffer.c:perf_mmap_free_page
  - kernel/events/uprobes.c:__create_xol_area
  - mm/mempool.c:mempool_free_pages
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/compaction.c:release_freepages
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:__pte_alloc
  - mm/vmalloc.c:__vunmap
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:SyS_swapoff
  - mm/hugetlb.c:update_and_free_page
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free_bulk
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
  - mm/memory_hotplug.c:generic_online_page
  - mm/memory_hotplug.c:put_page_bootmem
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:get_huge_zero_page
  - mm/khugepaged.c:collapse_shmem
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/zbud.c:free_zbud_page
  - mm/zsmalloc.c:zs_malloc
  - fs/pipe.c:free_pipe_info
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:default_file_splice_read
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
  - block/bio.c:bio_alloc_pages
  - drivers/xen/grant-table.c:gnttab_handle_deferred
  - drivers/xen/balloon.c:balloon_process
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/iommu/amd_iommu.c:free_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
  - drivers/base/firmware_class.c:firmware_loading_store
  - drivers/base/firmware_class.c:__fw_free_buf
  - drivers/base/devcoredump.c:devcd_free_sgtable
  - drivers/block/brd.c:brd_free_pages
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/scsi/sd.c:sd_uninit_command
  - drivers/net/virtio_net.c:remove_vq_common
  - drivers/md/dm-kcopyd.c:drop_pages
  - drivers/md/dm-kcopyd.c:kcopyd_put_pages
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
**Symbols:**

```
ffffffff811a8f20-ffffffff811a8f43: __free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __free_pages(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811b94c0)
Location: mm/page_alloc.c:3892
Inline: True
Direct callers:
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
  - arch/x86/mm/pageattr.c:__change_page_attr
  - kernel/fork.c:put_task_stack
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/profile.c:profile_dead_cpu
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
  - kernel/relay.c:relay_destroy_buf
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_spd_release_pipe
  - kernel/events/ring_buffer.c:perf_mmap_free_page
  - kernel/events/uprobes.c:__create_xol_area
  - mm/mempool.c:mempool_free_pages
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/compaction.c:release_freepages
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:__pte_alloc
  - mm/vmalloc.c:__vunmap
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:SyS_swapoff
  - mm/hugetlb.c:update_and_free_page
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free_bulk
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
  - mm/memory_hotplug.c:generic_online_page
  - mm/memory_hotplug.c:put_page_bootmem
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_shmem
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/zbud.c:free_zbud_page
  - mm/zsmalloc.c:zs_malloc
  - fs/pipe.c:free_pipe_info
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - crypto/scompress.c:crypto_scomp_sg_free
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
  - block/bio.c:bio_alloc_pages
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:blkdev_report_zones
  - drivers/xen/grant-table.c:gnttab_handle_deferred
  - drivers/xen/balloon.c:balloon_process
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/iommu/amd_iommu.c:free_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
  - drivers/base/firmware_class.c:firmware_loading_store
  - drivers/base/firmware_class.c:__fw_free_buf
  - drivers/base/devcoredump.c:devcd_free_sgtable
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/scsi/sd.c:sd_uninit_command
  - drivers/md/dm-kcopyd.c:drop_pages
  - drivers/md/dm-kcopyd.c:kcopyd_put_pages
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
**Symbols:**

```
ffffffff811b94c0-ffffffff811b94e3: __free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __free_pages(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811c1530)
Location: mm/page_alloc.c:4179
Inline: True
Direct callers:
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
  - arch/x86/mm/pageattr.c:__change_page_attr
  - kernel/fork.c:put_task_stack
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/profile.c:profile_dead_cpu
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
  - kernel/relay.c:relay_destroy_buf
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_spd_release_pipe
  - kernel/events/ring_buffer.c:perf_mmap_free_page
  - kernel/events/uprobes.c:__create_xol_area
  - mm/mempool.c:mempool_free_pages
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/compaction.c:release_freepages
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__pte_alloc
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:SyS_swapoff
  - mm/hugetlb.c:update_and_free_page
  - mm/slub.c:kfree
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
  - mm/memory_hotplug.c:generic_online_page
  - mm/memory_hotplug.c:put_page_bootmem
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_shmem
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/zbud.c:free_zbud_page
  - mm/zsmalloc.c:zs_malloc
  - fs/pipe.c:free_pipe_info
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
  - block/bio.c:bio_alloc_pages
  - block/blk-mq.c:blk_mq_free_rqs
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:blkdev_report_zones
  - drivers/xen/grant-table.c:gnttab_handle_deferred
  - drivers/xen/balloon.c:balloon_process
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
  - drivers/char/tpm/tpm-interface.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm-interface.c:tpm_getcap
  - drivers/char/tpm/tpm-interface.c:tpm_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context_cmd
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/iommu/amd_iommu.c:free_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
  - drivers/base/firmware_class.c:firmware_loading_store
  - drivers/base/firmware_class.c:fw_free_buf
  - drivers/base/devcoredump.c:devcd_free_sgtable
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/scsi/sd.c:sd_uninit_command
  - drivers/md/dm-kcopyd.c:drop_pages
  - drivers/md/dm-kcopyd.c:kcopyd_put_pages
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
**Symbols:**

```
ffffffff811c1530-ffffffff811c1553: __free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __free_pages(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d5950)
Location: mm/page_alloc.c:4298
Inline: True
Direct callers:
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/mem_encrypt.c:sev_alloc
  - kernel/fork.c:put_task_stack
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/profile.c:profile_dead_cpu
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
  - kernel/relay.c:relay_destroy_buf
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_spd_release_pipe
  - kernel/events/ring_buffer.c:perf_mmap_free_page
  - kernel/events/uprobes.c:__create_xol_area
  - mm/mempool.c:mempool_free_pages
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/compaction.c:release_freepages
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:__pte_alloc
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:SYSC_swapoff
  - mm/hugetlb.c:update_and_free_page
  - mm/slub.c:kfree
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
  - mm/memory_hotplug.c:generic_online_page
  - mm/memory_hotplug.c:put_page_bootmem
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_shmem
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/zbud.c:free_zbud_page
  - mm/zsmalloc.c:zs_malloc
  - fs/pipe.c:free_pipe_info
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
  - block/bio.c:bio_alloc_pages
  - block/blk-mq.c:blk_mq_free_rqs
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:blkdev_report_zones
  - drivers/xen/grant-table.c:gnttab_handle_deferred
  - drivers/xen/balloon.c:balloon_process
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
  - drivers/char/tpm/tpm-interface.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm-interface.c:tpm_getcap
  - drivers/char/tpm/tpm-interface.c:tpm_startup
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context_cmd
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/iommu/amd_iommu.c:free_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
  - drivers/base/firmware_class.c:firmware_loading_store
  - drivers/base/firmware_class.c:__fw_free_buf
  - drivers/base/devcoredump.c:devcd_free_sgtable
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/scsi/sd.c:sd_uninit_command
  - drivers/md/dm-kcopyd.c:drop_pages
  - drivers/md/dm-kcopyd.c:kcopyd_put_pages
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
**Symbols:**

```
ffffffff811d5950-ffffffff811d5971: __free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __free_pages(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f6d60)
Location: mm/page_alloc.c:4430
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/pageattr.c:__change_page_attr
  - kernel/fork.c:put_task_stack
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/profile.c:profile_dead_cpu
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
  - kernel/relay.c:relay_destroy_buf
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_spd_release_pipe
  - kernel/events/ring_buffer.c:perf_mmap_free_page
  - kernel/events/uprobes.c:__create_xol_area
  - mm/mempool.c:mempool_free_pages
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/compaction.c:release_freepages
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:__pte_alloc
  - mm/vmalloc.c:__vunmap
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapoff
  - mm/hugetlb.c:update_and_free_page
  - mm/slub.c:kfree
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
  - mm/memory_hotplug.c:generic_online_page
  - mm/memory_hotplug.c:put_page_bootmem
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_shmem
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/zbud.c:free_zbud_page
  - mm/zsmalloc.c:zs_malloc
  - fs/pipe.c:free_pipe_info
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - security/keys/big_key.c:big_key_free_buffer
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
  - block/blk-mq.c:blk_mq_free_rqs
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:blkdev_report_zones
  - lib/scatterlist.c:sgl_free_n_order
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/xen/balloon.c:balloon_process
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
  - drivers/char/tpm/tpm-interface.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm-interface.c:tpm_getcap
  - drivers/char/tpm/tpm-interface.c:tpm_startup
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context_cmd
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/iommu/amd_iommu.c:free_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/devcoredump.c:devcd_free_sgtable
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/scsi/sd.c:sd_uninit_command
  - drivers/md/dm-kcopyd.c:drop_pages
  - drivers/md/dm-kcopyd.c:kcopyd_put_pages
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
**Symbols:**

```
ffffffff811f6d60-ffffffff811f6d81: __free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __free_pages(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81209100)
Location: mm/page_alloc.c:4612
Inline: True
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvm_setup_vsyscall_timeinfo
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/pageattr.c:__change_page_attr
  - kernel/fork.c:put_task_stack
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/dma/direct.c:__dma_direct_free_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/profile.c:profile_dead_cpu
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
  - kernel/relay.c:relay_destroy_buf
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_spd_release_pipe
  - kernel/events/ring_buffer.c:perf_mmap_free_page
  - kernel/events/uprobes.c:__create_xol_area
  - mm/mempool.c:mempool_free_pages
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:memblock_free_pages
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/compaction.c:release_freepages
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__pte_alloc
  - mm/vmalloc.c:__vunmap
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapoff
  - mm/hugetlb.c:update_and_free_page
  - mm/slub.c:kfree
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
  - mm/memory_hotplug.c:generic_online_page
  - mm/memory_hotplug.c:put_page_bootmem
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_shmem
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/zbud.c:free_zbud_page
  - mm/zsmalloc.c:zs_malloc
  - fs/pipe.c:free_pipe_info
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/readdir.c:fuse_readdir
  - security/keys/big_key.c:big_key_free_buffer
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_kern_endio
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
  - block/blk-mq.c:blk_mq_free_rqs
  - lib/scatterlist.c:sgl_free_n_order
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/xen/balloon.c:balloon_process
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context_cmd
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/iommu/amd_iommu.c:free_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/devcoredump.c:devcd_free_sgtable
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/md/dm-kcopyd.c:drop_pages
  - drivers/md/dm-kcopyd.c:kcopyd_put_pages
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
**Symbols:**

```
ffffffff81209100-ffffffff81209121: __free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __free_pages(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81270480)
Location: mm/page_alloc.c:4779
Inline: True
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/pageattr.c:__change_page_attr
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/profile.c:profile_dead_cpu
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
  - kernel/relay.c:relay_destroy_buf
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_spd_release_pipe
  - kernel/events/ring_buffer.c:perf_mmap_free_page
  - kernel/events/uprobes.c:__create_xol_area
  - mm/mempool.c:mempool_free_pages
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/compaction.c:release_freepages
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
  - mm/vmalloc.c:__vunmap
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapoff
  - mm/hugetlb.c:update_and_free_page
  - mm/slub.c:kfree
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/memory_hotplug.c:__online_page_free
  - mm/memory_hotplug.c:put_page_bootmem
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:shrink_huge_zero_page_scan
  - mm/khugepaged.c:collapse_shmem
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/zbud.c:free_zbud_page
  - mm/zsmalloc.c:zs_malloc
  - fs/pipe.c:free_pipe_info
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - security/keys/big_key.c:big_key_free_buffer
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_free_pages
  - block/blk-mq.c:blk_mq_free_rqs
  - lib/scatterlist.c:sgl_free_n_order
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/xen/balloon.c:balloon_process
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
  - drivers/char/tpm/tpm-interface.c:tpm_send
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/iommu/amd_iommu.c:free_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/base/devcoredump.c:devcd_free_sgtable
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/md/dm-kcopyd.c:drop_pages
  - drivers/md/dm-kcopyd.c:kcopyd_put_pages
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
**Symbols:**

```
ffffffff81270480-ffffffff812704a2: __free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __free_pages(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127f2c0)
Location: mm/page_alloc.c:4797
Inline: True
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/pageattr.c:__change_page_attr
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/profile.c:profile_dead_cpu
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
  - kernel/relay.c:relay_destroy_buf
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_spd_release_pipe
  - kernel/events/ring_buffer.c:perf_mmap_free_page
  - kernel/events/uprobes.c:__create_xol_area
  - mm/mempool.c:mempool_free_pages
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/compaction.c:release_freepages
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
  - mm/vmalloc.c:__vunmap
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapoff
  - mm/hugetlb.c:update_and_free_page
  - mm/slub.c:kfree
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/memory_hotplug.c:__online_page_free
  - mm/memory_hotplug.c:put_page_bootmem
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:shrink_huge_zero_page_scan
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/zbud.c:free_zbud_page
  - mm/zsmalloc.c:zs_malloc
  - fs/pipe.c:free_pipe_info
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_free
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - security/keys/big_key.c:big_key_free_buffer
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_free_pages
  - block/blk-mq.c:blk_mq_free_rqs
  - lib/scatterlist.c:sgl_free_n_order
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/xen/balloon.c:balloon_process
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/iommu/amd_iommu.c:free_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/base/devcoredump.c:devcd_free_sgtable
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/md/dm-kcopyd.c:drop_pages
  - drivers/md/dm-kcopyd.c:kcopyd_put_pages
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
**Symbols:**

```
ffffffff8127f2c0-ffffffff8127f2e2: __free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __free_pages(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812b171b)
Location: mm/page_alloc.c:4900
Inline: True
Inline callers:
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - kernel/power/snapshot.c:free_unnecessary_pages
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/pool.c:atomic_pool_expand
  - kernel/profile.c:profile_dead_cpu
  - kernel/time/namespace.c:free_time_ns
  - kernel/time/namespace.c:clone_time_ns
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
  - kernel/relay.c:relay_destroy_buf
  - kernel/relay.c:relay_alloc_buf
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_spd_release_pipe
  - kernel/bpf/ringbuf.c:ringbuf_map_free
  - kernel/bpf/ringbuf.c:bpf_ringbuf_area_alloc
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:__rb_free_aux
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/watch_queue.c:__put_watch_queue
  - kernel/watch_queue.c:watch_queue_set_size
  - mm/mempool.c:mempool_free_pages
  - mm/compaction.c:release_freepages
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
  - mm/vmalloc.c:__vunmap
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__free_pages_core
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapoff
  - mm/hugetlb.c:update_and_free_page
  - mm/slub.c:kfree
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/memory_hotplug.c:put_page_bootmem
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:shrink_huge_zero_page_scan
  - mm/huge_memory.c:get_huge_zero_page
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/zbud.c:zbud_reclaim_page
  - mm/zbud.c:zbud_free
  - mm/zsmalloc.c:alloc_zspage
  - fs/pipe.c:free_pipe_info
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_free
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - block/bio.c:bio_free_pages
  - block/blk-map.c:bio_copy_user_iov
  - block/blk-mq.c:blk_mq_free_rqs
  - lib/scatterlist.c:sgl_alloc_order
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/xen/balloon.c:increase_reservation
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/char/agp/intel-gtt.c:intel_gtt_setup_scratch_page
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
  - drivers/iommu/intel/iommu.c:intel_free_coherent
  - drivers/iommu/intel/iommu.c:intel_alloc_coherent
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/base/devcoredump.c:devcd_free_sgtable
  - drivers/block/loop.c:lo_read_transfer
  - drivers/block/loop.c:lo_write_transfer
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:fill_grant_buffer
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_free
  - drivers/scsi/sg.c:sg_remove_scat
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/vfio/vfio_iommu_type1.c:vfio_test_domain_fgsp
  - drivers/md/dm-kcopyd.c:run_complete_job
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
**Symbols:**

```
ffffffff812b15b0-ffffffff812b15d2: __free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __free_pages(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bcf80)
Location: mm/page_alloc.c:5071
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:put_task_stack
  - kernel/power/snapshot.c:free_unnecessary_pages
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/ops_helpers.c:dma_common_free_pages
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
  - kernel/dma/pool.c:atomic_pool_expand
  - kernel/profile.c:profile_dead_cpu
  - kernel/time/namespace.c:free_time_ns
  - kernel/time/namespace.c:clone_time_ns
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
  - kernel/relay.c:relay_destroy_buf
  - kernel/relay.c:relay_alloc_buf
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_spd_release_pipe
  - kernel/bpf/ringbuf.c:ringbuf_map_free
  - kernel/bpf/ringbuf.c:bpf_ringbuf_area_alloc
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:__rb_free_aux
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/watch_queue.c:__put_watch_queue
  - kernel/watch_queue.c:watch_queue_set_size
  - mm/mempool.c:mempool_free_pages
  - mm/compaction.c:release_freepages
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
  - mm/vmalloc.c:__vunmap
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapoff
  - mm/hugetlb.c:update_and_free_page
  - mm/slub.c:kfree
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:__free_slab
  - mm/memory_hotplug.c:put_page_bootmem
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:shrink_huge_zero_page_scan
  - mm/huge_memory.c:get_huge_zero_page
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/zbud.c:zbud_reclaim_page
  - mm/zbud.c:zbud_free
  - mm/zsmalloc.c:alloc_zspage
  - fs/pipe.c:free_pipe_info
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_free
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - block/bio.c:bio_free_pages
  - block/blk-map.c:bio_copy_user_iov
  - block/blk-mq.c:blk_mq_free_rqs
  - lib/scatterlist.c:sgl_free
  - lib/scatterlist.c:sgl_alloc_order
  - drivers/xen/balloon.c:increase_reservation
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/char/agp/intel-gtt.c:intel_gtt_setup_scratch_page
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/base/devcoredump.c:devcd_free_sgtable
  - drivers/block/loop.c:lo_read_transfer
  - drivers/block/loop.c:lo_write_transfer
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:fill_grant_buffer
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_release
  - drivers/scsi/sg.c:sg_remove_scat
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/vfio/vfio_iommu_type1.c:vfio_test_domain_fgsp
  - drivers/md/dm-kcopyd.c:run_complete_job
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
**Symbols:**

```
ffffffff812bcf80-ffffffff812bcffe: __free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __free_pages(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812c1e30)
Location: mm/page_alloc.c:5272
Inline: True
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:put_task_stack
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:create_zone_bm_rtree
  - kernel/power/snapshot.c:create_zone_bm_rtree
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/ops_helpers.c:dma_common_free_pages
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
  - kernel/dma/pool.c:atomic_pool_expand
  - kernel/profile.c:profile_dead_cpu
  - kernel/time/namespace.c:free_time_ns
  - kernel/time/namespace.c:copy_time_ns
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
  - kernel/relay.c:relay_destroy_buf
  - kernel/relay.c:relay_create_buf
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_spd_release_pipe
  - kernel/bpf/ringbuf.c:ringbuf_map_free
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:__rb_free_aux
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/watch_queue.c:__put_watch_queue
  - kernel/watch_queue.c:watch_queue_set_size
  - mm/mempool.c:mempool_free_pages
  - mm/compaction.c:release_freepages
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
  - mm/memory.c:__pte_alloc
  - mm/vmalloc.c:__vunmap
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:__alloc_pages
  - mm/memory_hotplug.c:put_page_bootmem
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapoff
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:update_and_free_page
  - mm/slub.c:kfree
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:__free_slab
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:shrink_huge_zero_page_scan
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/zbud.c:zbud_reclaim_page
  - mm/zbud.c:zbud_free
  - mm/zsmalloc.c:alloc_zspage
  - fs/pipe.c:free_pipe_info
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_free
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - block/bio.c:bio_free_pages
  - block/blk-map.c:bio_copy_user_iov
  - block/blk-mq.c:blk_mq_free_rqs
  - lib/scatterlist.c:sgl_free
  - lib/scatterlist.c:sgl_alloc_order
  - drivers/xen/balloon.c:balloon_process
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/base/devcoredump.c:devcd_free_sgtable
  - drivers/block/loop.c:lo_read_transfer
  - drivers/block/loop.c:lo_write_transfer
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_release
  - drivers/scsi/sg.c:sg_remove_scat
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/md/dm-kcopyd.c:run_complete_job
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
**Symbols:**

```
ffffffff812c1e30-ffffffff812c1eae: __free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __free_pages(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:5453
Inline: True
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:put_task_stack
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/ops_helpers.c:dma_common_free_pages
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
  - kernel/dma/pool.c:atomic_pool_expand
  - kernel/profile.c:profile_dead_cpu
  - kernel/time/namespace.c:free_time_ns
  - kernel/time/namespace.c:copy_time_ns
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
  - kernel/relay.c:relay_destroy_buf
  - kernel/relay.c:relay_create_buf
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_spd_release_pipe
  - kernel/bpf/ringbuf.c:ringbuf_map_free
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/watch_queue.c:__put_watch_queue
  - kernel/watch_queue.c:watch_queue_set_size
  - mm/mempool.c:mempool_free_pages
  - mm/compaction.c:release_freepages
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
  - mm/memory.c:__pte_alloc
  - mm/vmalloc.c:__vunmap
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:__alloc_pages
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapoff
  - mm/sparse-vmemmap.c:vmemmap_remap_alloc
  - mm/sparse-vmemmap.c:vmemmap_remap_free
  - mm/slub.c:kfree
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:__free_slab
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/zbud.c:zbud_zpool_free
  - mm/zsmalloc.c:alloc_zspage
  - mm/bootmem_info.c:put_page_bootmem
  - fs/pipe.c:free_pipe_info
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_free
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - block/bio.c:bio_free_pages
  - block/blk-map.c:bio_copy_user_iov
  - block/blk-mq.c:blk_mq_free_rqs
  - lib/scatterlist.c:sgl_free
  - lib/scatterlist.c:sgl_alloc_order
  - drivers/xen/balloon.c:balloon_thread
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
  - drivers/base/devcoredump.c:devcd_free_sgtable
  - drivers/block/loop.c:lo_read_transfer
  - drivers/block/loop.c:lo_write_transfer
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_release
  - drivers/scsi/sg.c:sg_remove_scat
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/md/dm-kcopyd.c:run_complete_job
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
**Symbols:**

```
ffffffff81cbd78f-ffffffff81cbd7a8: __free_pages.cold (STB_LOCAL)
ffffffff81305760-ffffffff8130580e: __free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __free_pages(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff8136db4f)
Location: mm/page_alloc.c:5508
Inline: True
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/ops_helpers.c:dma_common_free_pages
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
  - kernel/dma/pool.c:atomic_pool_expand
  - kernel/profile.c:profile_dead_cpu
  - kernel/time/namespace.c:free_time_ns
  - kernel/time/namespace.c:copy_time_ns
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
  - kernel/relay.c:relay_destroy_buf
  - kernel/relay.c:relay_alloc_buf
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_spd_release_pipe
  - kernel/bpf/ringbuf.c:ringbuf_map_free
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/watch_queue.c:__put_watch_queue
  - kernel/watch_queue.c:watch_queue_set_size
  - mm/mempool.c:mempool_free_pages
  - mm/compaction.c:release_freepages
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
  - mm/vmalloc.c:__vunmap
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:__alloc_pages
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapoff
  - mm/sparse-vmemmap.c:vmemmap_remap_alloc
  - mm/sparse-vmemmap.c:vmemmap_remap_free
  - mm/slub.c:kfree
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:__free_slab
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_and_free_pmd
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/zbud.c:zbud_zpool_free
  - mm/zsmalloc.c:alloc_zspage
  - mm/bootmem_info.c:put_page_bootmem
  - fs/pipe.c:free_pipe_info
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_free
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - block/bio.c:bio_free_pages
  - block/blk-map.c:bio_copy_user_iov
  - block/blk-mq.c:blk_mq_free_rqs
  - io_uring/io_uring.c:io_ring_ctx_free
  - lib/scatterlist.c:sgl_free
  - lib/scatterlist.c:sgl_alloc_order
  - drivers/xen/balloon.c:balloon_thread
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_alloc_by_type
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
  - drivers/iommu/dma-iommu.c:iommu_dma_free_noncontiguous
  - drivers/base/devcoredump.c:devcd_free_sgtable
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_release
  - drivers/scsi/sg.c:sg_remove_scat
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/md/dm-kcopyd.c:run_complete_job
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
```
**Symbols:**

```
ffffffff81e6f6ef-ffffffff81e6f719: __free_pages.cold (STB_LOCAL)
ffffffff8136db30-ffffffff8136dc63: __free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __free_pages(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:5632
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/ops_helpers.c:dma_common_free_pages
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
  - kernel/dma/pool.c:atomic_pool_expand
  - kernel/profile.c:profile_dead_cpu
  - kernel/time/namespace.c:free_time_ns
  - kernel/time/namespace.c:copy_time_ns
  - kernel/kexec_core.c:crash_shrink_memory
  - kernel/kexec_core.c:kimage_free_pages
  - kernel/relay.c:relay_destroy_buf
  - kernel/relay.c:relay_alloc_buf
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_spd_release_pipe
  - kernel/bpf/ringbuf.c:ringbuf_map_free
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/watch_queue.c:__put_watch_queue
  - kernel/watch_queue.c:watch_queue_set_size
  - mm/mempool.c:mempool_free_pages
  - mm/slab_common.c:free_large_kmalloc
  - mm/compaction.c:release_freepages
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
  - mm/vmalloc.c:__vunmap
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:__alloc_pages
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapoff
  - mm/hugetlb.c:__update_and_free_page
  - mm/hugetlb_vmemmap.c:vmemmap_remap_free
  - mm/slub.c:__free_slab
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:mm_get_huge_zero_page
  - mm/khugepaged.c:collapse_and_free_pmd
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/zbud.c:zbud_zpool_free
  - mm/zsmalloc.c:alloc_zspage
  - mm/bootmem_info.c:put_page_bootmem
  - fs/pipe.c:free_pipe_info
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_free
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - block/bio.c:bio_free_pages
  - block/blk-map.c:bio_copy_user_iov
  - block/blk-mq.c:blk_mq_free_rqs
  - io_uring/kbuf.c:io_destroy_buffers
  - lib/scatterlist.c:sgl_free
  - lib/scatterlist.c:sgl_alloc_order
  - drivers/xen/balloon.c:balloon_thread
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_alloc_by_type
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
  - drivers/iommu/dma-iommu.c:iommu_dma_free_noncontiguous
  - drivers/base/devcoredump.c:devcd_free_sgtable
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_release
  - drivers/scsi/sg.c:sg_remove_scat
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/md/dm-kcopyd.c:run_complete_job
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
```
**Symbols:**

```
ffffffff820654b7-ffffffff820654e1: __free_pages.cold (STB_LOCAL)
ffffffff813e9fd0-ffffffff813ea10f: __free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __free_pages(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:4560
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/ops_helpers.c:dma_common_free_pages
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
  - kernel/dma/pool.c:atomic_pool_expand
  - kernel/module/decompress.c:module_decompress_cleanup
  - kernel/profile.c:profile_dead_cpu
  - kernel/time/namespace.c:free_time_ns
  - kernel/time/namespace.c:copy_time_ns
  - kernel/kexec_core.c:__crash_shrink_memory
  - kernel/kexec_core.c:kimage_free_pages
  - kernel/relay.c:relay_destroy_buf
  - kernel/relay.c:relay_alloc_buf
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_spd_release_pipe
  - kernel/bpf/ringbuf.c:ringbuf_map_free
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/watch_queue.c:__put_watch_queue
  - kernel/watch_queue.c:watch_queue_set_size
  - mm/mempool.c:mempool_free_pages
  - mm/slab_common.c:free_large_kmalloc
  - mm/compaction.c:release_freepages
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
  - mm/vmalloc.c:vfree
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:__alloc_pages
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapoff
  - mm/hugetlb.c:__update_and_free_hugetlb_folio
  - mm/hugetlb_vmemmap.c:vmemmap_remap_alloc
  - mm/hugetlb_vmemmap.c:vmemmap_remap_free
  - mm/slub.c:__free_slab
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:mm_get_huge_zero_page
  - mm/khugepaged.c:collapse_and_free_pmd
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/zbud.c:zbud_zpool_free
  - mm/zsmalloc.c:alloc_zspage
  - mm/bootmem_info.c:put_page_bootmem
  - fs/pipe.c:free_pipe_info
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_free
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - block/bio.c:bio_free_pages
  - block/blk-map.c:bio_copy_user_iov
  - block/blk-mq.c:blk_mq_free_rqs
  - io_uring/kbuf.c:io_destroy_buffers
  - lib/scatterlist.c:sgl_free
  - lib/scatterlist.c:sgl_alloc_order
  - drivers/xen/balloon.c:balloon_thread
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_alloc_by_type
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
  - drivers/iommu/dma-iommu.c:iommu_dma_free_noncontiguous
  - drivers/base/devcoredump.c:devcd_free_sgtable
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_release
  - drivers/scsi/sg.c:sg_remove_scat
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/net/virtio_net.c:remove_vq_common
  - drivers/net/virtio_net.c:xdp_linearize_page
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/md/dm-kcopyd.c:run_complete_job
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
```
**Symbols:**

```
ffffffff820e4cab-ffffffff820e4ccc: __free_pages.cold (STB_LOCAL)
ffffffff8141efa0-ffffffff8141f0e4: __free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __free_pages(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:4649
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/ops_helpers.c:dma_common_free_pages
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
  - kernel/dma/swiotlb.c:swiotlb_alloc_pool
  - kernel/dma/swiotlb.c:swiotlb_alloc_pool
  - kernel/module/decompress.c:module_decompress_cleanup
  - kernel/profile.c:profile_dead_cpu
  - kernel/time/namespace.c:free_time_ns
  - kernel/time/namespace.c:copy_time_ns
  - kernel/kexec_core.c:__crash_shrink_memory
  - kernel/kexec_core.c:kimage_free_pages
  - kernel/relay.c:relay_destroy_buf
  - kernel/relay.c:relay_alloc_buf
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_spd_release_pipe
  - kernel/bpf/ringbuf.c:ringbuf_map_free
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/watch_queue.c:__put_watch_queue
  - kernel/watch_queue.c:watch_queue_set_size
  - mm/mempool.c:mempool_free_pages
  - mm/compaction.c:release_freepages
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/pgtable-generic.c:pte_free_now
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:__alloc_pages
  - mm/slub.c:__free_slab
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapoff
  - mm/hugetlb.c:__update_and_free_hugetlb_folio
  - mm/hugetlb_vmemmap.c:__hugetlb_vmemmap_restore_folio
  - mm/hugetlb_vmemmap.c:free_vmemmap_page_list
  - mm/hugetlb_vmemmap.c:vmemmap_split_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:mm_get_huge_zero_page
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/zbud.c:zbud_zpool_free
  - mm/zsmalloc.c:alloc_zspage
  - mm/bootmem_info.c:put_page_bootmem
  - fs/pipe.c:free_pipe_info
  - fs/coredump.c:dump_user_range
  - fs/coredump.c:dump_user_range
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_free
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - block/bio.c:bio_free_pages
  - block/blk-map.c:bio_copy_user_iov
  - block/blk-mq.c:blk_mq_free_rqs
  - lib/scatterlist.c:sgl_free
  - lib/scatterlist.c:sgl_alloc_order
  - drivers/xen/balloon.c:balloon_thread
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_alloc_by_type
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
  - drivers/iommu/dma-iommu.c:iommu_dma_free_noncontiguous
  - drivers/base/devcoredump.c:devcd_free_sgtable
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_release
  - drivers/scsi/sg.c:sg_remove_scat
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/net/virtio_net.c:remove_vq_common
  - drivers/net/virtio_net.c:xdp_linearize_page
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/md/dm-kcopyd.c:run_complete_job
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
```
**Symbols:**

```
ffffffff821c197f-ffffffff821c19a0: __free_pages.cold (STB_LOCAL)
ffffffff8144bc70-ffffffff8144bdae: __free_pages (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __free_pages(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010316db0)
Location: mm/page_alloc.c:4797
Inline: True
Direct callers:
  - kernel/dma/contiguous.c:dma_free_contiguous
  - kernel/dma/remap.c:dma_atomic_pool_init
  - kernel/profile.c:profile_dead_cpu
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
  - kernel/relay.c:relay_destroy_buf
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_spd_release_pipe
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/uprobes.c:__create_xol_area
  - mm/mempool.c:mempool_free_pages
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/compaction.c:release_freepages
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
  - mm/vmalloc.c:__vunmap
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapoff
  - mm/hugetlb.c:update_and_free_page
  - mm/slub.c:kfree
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/memory_hotplug.c:__online_page_free
  - mm/memory_hotplug.c:__online_page_free
  - mm/memory_hotplug.c:put_page_bootmem
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:shrink_huge_zero_page_scan
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/zbud.c:zbud_reclaim_page
  - mm/zbud.c:zbud_free
  - mm/zsmalloc.c:zs_malloc
  - fs/pipe.c:free_pipe_info
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_free
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - security/keys/big_key.c:big_key_free_buffer
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_free_pages
  - block/blk-mq.c:blk_mq_free_rqs
  - lib/scatterlist.c:sgl_free_n_order
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/xen/balloon.c:balloon_process
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_remap
  - drivers/iommu/dma-iommu.c:__iommu_dma_free_pages
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/base/devcoredump.c:devcd_free_sgtable
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/md/dm-kcopyd.c:drop_pages
  - drivers/md/dm-kcopyd.c:kcopyd_put_pages
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
**Symbols:**

```
ffff800010316db0-ffff800010316e2c: __free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __free_pages(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c053162c)
Location: mm/page_alloc.c:4797
Inline: True
Direct callers:
  - arch/arm/mm/dma-mapping.c:arm_iommu_alloc_attrs
  - arch/arm/mm/dma-mapping.c:__iommu_free_atomic
  - arch/arm/mm/dma-mapping.c:__iommu_free_buffer
  - arch/arm/mm/dma-mapping.c:remap_allocator_free
  - arch/arm/mm/dma-mapping.c:simple_allocator_free
  - arch/arm/mm/dma-mapping.c:__alloc_remap_buffer
  - arch/arm/mm/pgd.c:pgd_free
  - kernel/fork.c:copy_process
  - kernel/fork.c:free_task
  - kernel/power/snapshot.c:restore_highmem
  - kernel/power/snapshot.c:snapshot_write_finalize
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/dma/contiguous.c:dma_free_contiguous
  - kernel/profile.c:profile_dead_cpu
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
  - kernel/relay.c:relay_destroy_buf
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_spd_release_pipe
  - kernel/events/uprobes.c:__create_xol_area
  - mm/mempool.c:mempool_free_pages
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/compaction.c:release_freepages
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
  - mm/vmalloc.c:__vunmap
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:free_highmem_page
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapoff
  - mm/slub.c:kfree
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/zbud.c:zbud_reclaim_page
  - mm/zbud.c:zbud_free
  - mm/zsmalloc.c:zs_malloc
  - fs/pipe.c:free_pipe_info
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_free
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - security/keys/big_key.c:big_key_free_buffer
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_free_pages
  - block/blk-mq.c:blk_mq_free_rqs
  - lib/scatterlist.c:sgl_free_n_order
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/dma/mv_xor.c:mv_chan_xor_self_test
  - drivers/dma/mv_xor.c:mv_chan_xor_self_test
  - drivers/dma/mv_xor.c:mv_chan_xor_self_test
  - drivers/dma/mv_xor.c:mv_chan_xor_self_test
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_alloc_pages
  - drivers/iommu/tegra-smmu.c:tegra_smmu_unmap
  - drivers/iommu/tegra-smmu.c:tegra_smmu_map
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/base/devcoredump.c:devcd_free_sgtable
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/scsi/sg.c:sg_remove_scat
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/md/dm-kcopyd.c:drop_pages
  - drivers/md/dm-kcopyd.c:kcopyd_put_pages
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
**Symbols:**

```
c053162c-c0531684: __free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __free_pages(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003e9140)
Location: mm/page_alloc.c:4797
Inline: True
Direct callers:
  - arch/powerpc/kernel/crash_dump.c:crash_free_reserved_phys_range
  - arch/powerpc/kernel/fadump.c:fadump_release_reserved_area
  - arch/powerpc/mm/init_64.c:vmemmap_free
  - arch/powerpc/mm/pgtable-frag.c:pte_fragment_free
  - arch/powerpc/mm/pgtable-frag.c:pte_fragment_free
  - arch/powerpc/mm/pgtable-frag.c:pte_frag_destroy
  - arch/powerpc/mm/book3s64/mmu_context.c:arch_exit_mmap
  - arch/powerpc/mm/book3s64/pgtable.c:pmd_fragment_free
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda1_setup_dma_pe
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/profile.c:profile_dead_cpu
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
  - kernel/relay.c:relay_destroy_buf
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_spd_release_pipe
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/uprobes.c:__create_xol_area
  - mm/mempool.c:mempool_free_pages
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/compaction.c:release_freepages
  - mm/vmalloc.c:__vunmap
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapoff
  - mm/slub.c:kfree
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/memory_hotplug.c:__online_page_free
  - mm/memory_hotplug.c:put_page_bootmem
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/zbud.c:zbud_reclaim_page
  - mm/zbud.c:zbud_free
  - mm/zsmalloc.c:zs_malloc
  - fs/pipe.c:free_pipe_info
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_free
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - security/keys/big_key.c:big_key_free_buffer
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_free_pages
  - block/blk-mq.c:blk_mq_free_rqs
  - lib/scatterlist.c:sgl_free_n_order
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/base/devcoredump.c:devcd_free_sgtable
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/scsi/sg.c:sg_remove_scat
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/md/dm-kcopyd.c:drop_pages
  - drivers/md/dm-kcopyd.c:kcopyd_put_pages
```
**Symbols:**

```
c0000000003e9140-c0000000003e9194: __free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __free_pages(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffe00021fd52)
Location: mm/page_alloc.c:4797
Inline: True
Inline callers:
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:release_task_stack
  - kernel/dma/contiguous.c:dma_free_contiguous
  - kernel/profile.c:profile_dead_cpu
  - kernel/relay.c:relay_destroy_buf
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_spd_release_pipe
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_free
  - mm/mempool.c:mempool_free_pages
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/compaction.c:release_freepages
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
  - mm/vmalloc.c:__vunmap
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__free_pages_core
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapoff
  - mm/hugetlb.c:update_and_free_page
  - mm/slub.c:kfree
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/zbud.c:zbud_reclaim_page
  - mm/zbud.c:zbud_free
  - mm/zsmalloc.c:zs_malloc
  - fs/pipe.c:free_pipe_info
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_free
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - security/keys/big_key.c:big_key_free_buffer
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_free_pages
  - block/blk-mq.c:blk_mq_free_rqs
  - lib/scatterlist.c:sgl_free_n_order
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/base/devcoredump.c:devcd_free_sgtable
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/scsi/sg.c:sg_remove_scat
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/md/dm-kcopyd.c:drop_pages
  - drivers/md/dm-kcopyd.c:kcopyd_put_pages
```
**Symbols:**

```
ffffffe00021d13c-ffffffe00021d186: __free_pages.part.0 (STB_LOCAL)
ffffffe00021d186-ffffffe00021d1ca: __free_pages (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void __free_pages(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81277910)
Location: mm/page_alloc.c:4797
Inline: True
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/pageattr.c:__change_page_attr
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/dma/contiguous.c:dma_free_contiguous
  - kernel/profile.c:profile_dead_cpu
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
  - kernel/relay.c:relay_destroy_buf
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_spd_release_pipe
  - kernel/events/ring_buffer.c:perf_mmap_free_page
  - kernel/events/uprobes.c:__create_xol_area
  - mm/mempool.c:mempool_free_pages
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/compaction.c:release_freepages
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
  - mm/vmalloc.c:__vunmap
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapoff
  - mm/hugetlb.c:update_and_free_page
  - mm/slub.c:kfree
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/memory_hotplug.c:__online_page_free
  - mm/memory_hotplug.c:put_page_bootmem
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:shrink_huge_zero_page_scan
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/zbud.c:free_zbud_page
  - mm/zsmalloc.c:zs_malloc
  - fs/pipe.c:free_pipe_info
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_free
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - security/keys/big_key.c:big_key_free_buffer
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_free_pages
  - block/blk-mq.c:blk_mq_free_rqs
  - lib/scatterlist.c:sgl_free_n_order
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/xen/balloon.c:balloon_process
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/iommu/amd_iommu.c:free_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/base/devcoredump.c:devcd_free_sgtable
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/nvme/host/core.c:nvme_init_ctrl
  - drivers/nvme/host/core.c:nvme_free_ctrl
  - drivers/nvme/host/core.c:nvme_free_ctrl
  - drivers/md/dm-kcopyd.c:drop_pages
  - drivers/md/dm-kcopyd.c:kcopyd_put_pages
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
**Symbols:**

```
ffffffff81277910-ffffffff81277932: __free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __free_pages(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81269820)
Location: mm/page_alloc.c:4797
Inline: True
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/profile.c:profile_dead_cpu
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
  - kernel/relay.c:relay_destroy_buf
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_spd_release_pipe
  - kernel/events/ring_buffer.c:perf_mmap_free_page
  - kernel/events/uprobes.c:__create_xol_area
  - mm/mempool.c:mempool_free_pages
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/compaction.c:release_freepages
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
  - mm/vmalloc.c:__vunmap
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapoff
  - mm/hugetlb.c:update_and_free_page
  - mm/slub.c:kfree
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/memory_hotplug.c:__online_page_free
  - mm/memory_hotplug.c:put_page_bootmem
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:shrink_huge_zero_page_scan
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/zbud.c:free_zbud_page
  - mm/zsmalloc.c:zs_malloc
  - fs/pipe.c:free_pipe_info
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_free
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - security/keys/big_key.c:big_key_free_buffer
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_free_pages
  - block/blk-mq.c:blk_mq_free_rqs
  - lib/scatterlist.c:sgl_free_n_order
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/iommu/amd_iommu.c:free_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/nvme/host/core.c:nvme_init_ctrl
  - drivers/nvme/host/core.c:nvme_free_ctrl
  - drivers/nvme/host/core.c:nvme_free_ctrl
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/md/dm-kcopyd.c:drop_pages
  - drivers/md/dm-kcopyd.c:kcopyd_put_pages
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - drivers/hv/channel.c:vmbus_free_ring
```
**Symbols:**

```
ffffffff81269820-ffffffff81269842: __free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __free_pages(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812756b0)
Location: mm/page_alloc.c:4797
Inline: True
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/pageattr.c:__change_page_attr
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/profile.c:profile_dead_cpu
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
  - kernel/relay.c:relay_destroy_buf
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_spd_release_pipe
  - kernel/events/ring_buffer.c:perf_mmap_free_page
  - kernel/events/uprobes.c:__create_xol_area
  - mm/mempool.c:mempool_free_pages
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/compaction.c:release_freepages
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
  - mm/vmalloc.c:__vunmap
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapoff
  - mm/hugetlb.c:update_and_free_page
  - mm/slub.c:kfree
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/memory_hotplug.c:__online_page_free
  - mm/memory_hotplug.c:put_page_bootmem
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:shrink_huge_zero_page_scan
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/zbud.c:free_zbud_page
  - mm/zsmalloc.c:zs_malloc
  - fs/pipe.c:free_pipe_info
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_free
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - security/keys/big_key.c:big_key_free_buffer
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_free_pages
  - block/blk-mq.c:blk_mq_free_rqs
  - lib/scatterlist.c:sgl_free_n_order
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/xen/balloon.c:balloon_process
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/iommu/amd_iommu.c:free_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/base/devcoredump.c:devcd_free_sgtable
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/md/dm-kcopyd.c:drop_pages
  - drivers/md/dm-kcopyd.c:kcopyd_put_pages
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
**Symbols:**

```
ffffffff812756b0-ffffffff812756d2: __free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __free_pages(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81285270)
Location: mm/page_alloc.c:4797
Inline: True
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/pageattr.c:__change_page_attr
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/profile.c:profile_dead_cpu
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
  - kernel/relay.c:relay_destroy_buf
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_spd_release_pipe
  - kernel/events/ring_buffer.c:perf_mmap_free_page
  - kernel/events/uprobes.c:__create_xol_area
  - mm/mempool.c:mempool_free_pages
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/compaction.c:release_freepages
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
  - mm/vmalloc.c:__vunmap
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapoff
  - mm/hugetlb.c:update_and_free_page
  - mm/slub.c:kfree
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/memory_hotplug.c:__online_page_free
  - mm/memory_hotplug.c:put_page_bootmem
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:shrink_huge_zero_page_scan
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/zbud.c:free_zbud_page
  - mm/zsmalloc.c:zs_malloc
  - fs/pipe.c:free_pipe_info
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_free
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - security/keys/big_key.c:big_key_free_buffer
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_free_pages
  - block/blk-mq.c:blk_mq_free_rqs
  - lib/scatterlist.c:sgl_free_n_order
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/xen/balloon.c:balloon_process
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/iommu/amd_iommu.c:free_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/base/devcoredump.c:devcd_free_sgtable
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/md/dm-kcopyd.c:drop_pages
  - drivers/md/dm-kcopyd.c:kcopyd_put_pages
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
**Symbols:**

```
ffffffff81285270-ffffffff81285292: __free_pages (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
