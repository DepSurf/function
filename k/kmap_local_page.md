# Function: <code>kmap_local_page</code>

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
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff813c0737)
Location: include/linux/highmem-internal.h:158
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
```
```
In fs/ext4/verity.c (ffffffff8145e08e)
Location: include/linux/highmem-internal.h:158
Inline: True
Inline callers:
  - fs/ext4/verity.c:pagecache_read
```
```
In lib/iov_iter.c (ffffffff815adb14)
Location: include/linux/highmem-internal.h:158
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
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
In fs/coredump.c (ffffffff814105a3)
Location: include/linux/highmem-internal.h:169
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
```
```
In fs/iomap/buffered-io.c (ffffffff81414247)
Location: include/linux/highmem-internal.h:169
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_inline_data
```
```
In fs/ext4/verity.c (ffffffff814b35ae)
Location: include/linux/highmem-internal.h:169
Inline: True
Inline callers:
  - fs/ext4/verity.c:pagecache_read
```
```
In block/bio.c (ffffffff815c70e4)
Location: include/linux/highmem-internal.h:169
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:zero_fill_bio
```
```
In block/blk-map.c (ffffffff815d2a33)
Location: include/linux/highmem-internal.h:169
Inline: True
Inline callers:
  - block/blk-map.c:bio_copy_kern_endio_read
```
```
In block/bio-integrity.c (ffffffff81602363)
Location: include/linux/highmem-internal.h:169
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/t10-pi.c (ffffffff8160390b)
Location: include/linux/highmem-internal.h:169
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/iov_iter.c (ffffffff81619976)
Location: include/linux/highmem-internal.h:169
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_page_from_iter
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
In kernel/power/snapshot.c (ffffffff811561ca)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
```
In kernel/kexec_core.c (ffffffff811bc7f8)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/events/uprobes.c (ffffffff812e6a5c)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/truncate.c (ffffffff81307c70)
Location: include/linux/highmem-internal.h:180
Inline: True
```
```
In mm/shmem.c (ffffffff81317f22)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
```
```
In mm/util.c (ffffffff8131e016)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - mm/util.c:folio_copy
  - mm/util.c:folio_copy
```
```
In mm/memory.c (ffffffff8134882e)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
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
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
```
```
In mm/page_alloc.c (ffffffff813709f8)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/ksm.c (ffffffff813a32f1)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/khugepaged.c (ffffffff813c5836)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/secretmem.c (ffffffff813e36c0)
Location: include/linux/highmem-internal.h:180
Inline: True
```
```
In fs/libfs.c (ffffffff8142c4f0)
Location: include/linux/highmem-internal.h:180
Inline: True
```
```
In fs/buffer.c (ffffffff814431f0)
Location: include/linux/highmem-internal.h:180
Inline: True
```
```
In fs/direct-io.c (ffffffff81448f50)
Location: include/linux/highmem-internal.h:180
Inline: True
```
```
In fs/mpage.c (ffffffff8144af80)
Location: include/linux/highmem-internal.h:180
Inline: True
```
```
In fs/dax.c (ffffffff81467888)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
```
```
In fs/coredump.c (ffffffff81486093)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
```
```
In fs/iomap/buffered-io.c (ffffffff81488100)
Location: include/linux/highmem-internal.h:180
Inline: True
```
```
In fs/ext4/inline.c (ffffffff814dbd90)
Location: include/linux/highmem-internal.h:180
Inline: True
```
```
In fs/ext4/inode.c (ffffffff814e0720)
Location: include/linux/highmem-internal.h:180
Inline: True
```
```
In fs/ext4/move_extent.c (ffffffff814fe8a0)
Location: include/linux/highmem-internal.h:180
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff815085a0)
Location: include/linux/highmem-internal.h:180
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff81509970)
Location: include/linux/highmem-internal.h:180
Inline: True
```
```
In fs/ext4/verity.c (ffffffff8153c180)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/hugetlbfs/inode.c (ffffffff81554840)
Location: include/linux/highmem-internal.h:180
Inline: True
```
```
In fs/ecryptfs/mmap.c (ffffffff81568d30)
Location: include/linux/highmem-internal.h:180
Inline: True
```
```
In fs/fuse/dev.c (ffffffff8157615f)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffff815830b4)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (ffffffff81588908)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In fs/fuse/ioctl.c (ffffffff81589ede)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_do_ioctl
```
```
In block/bio.c (ffffffff81672038)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:zero_fill_bio
```
```
In block/blk-map.c (ffffffff8167f514)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - block/blk-map.c:bio_copy_kern_endio_read
```
```
In block/bio-integrity.c (ffffffff816b4f67)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/t10-pi.c (ffffffff816b6b37)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - block/t10-pi.c:ext_pi_type1_complete
  - block/t10-pi.c:ext_pi_type1_prepare
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/iov_iter.c (ffffffff816e6d88)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:copy_mc_pipe_to_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:copy_pipe_to_iter
```
```
In drivers/xen/grant-table.c (ffffffff818c9814)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff818ca0c9)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/scsi/sd.c (ffffffff81a11c3e)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
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
In arch/x86/hyperv/hv_init.c (ffffffff81044ce0)
Location: include/linux/highmem-internal.h:180
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8108f278)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81091897)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81093518)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
```
```
In kernel/power/snapshot.c (ffffffff81186769)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/highmem-internal.h:180
Inline: True
```
```
In kernel/kexec_core.c (ffffffff811fe298)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_normal_segment
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/events/uprobes.c (ffffffff81350549)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/truncate.c (ffffffff81371380)
Location: include/linux/highmem-internal.h:180
Inline: True
```
```
In mm/shmem.c (ffffffff8138ccf2)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_get_folio_gfp
```
```
In mm/util.c (ffffffff81391a74)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - mm/util.c:folio_copy
  - mm/util.c:folio_copy
```
```
In mm/memory.c (ffffffff813c0d1a)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
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
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
```
```
In mm/page_alloc.c (ffffffff813ece7a)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/ksm.c (ffffffff81422f81)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate_device.c (ffffffff8143a582)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/migrate_device.c:migrate_device_coherent_page
```
```
In mm/khugepaged.c (ffffffff8144a191)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/secretmem.c (ffffffff8146b090)
Location: include/linux/highmem-internal.h:180
Inline: True
```
```
In mm/userfaultfd.c (ffffffff8146d17c)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (ffffffff814852f2)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - fs/exec.c:remove_arg_zero
  - fs/exec.c:copy_string_kernel
```
```
In fs/libfs.c (ffffffff814b9b20)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - fs/libfs.c:zero_user_segments
```
```
In fs/buffer.c (ffffffff814d2530)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - fs/buffer.c:zero_user_segments
```
```
In fs/direct-io.c (ffffffff814d7240)
Location: include/linux/highmem-internal.h:180
Inline: True
```
```
In fs/mpage.c (ffffffff814d97b0)
Location: include/linux/highmem-internal.h:180
Inline: True
```
```
In fs/dax.c (ffffffff814f7f48)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
```
```
In fs/verity/read_metadata.c (ffffffff8150626c)
Location: include/linux/highmem-internal.h:180
Inline: True
```
```
In fs/verity/verify.c (ffffffff81506d17)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/iomap/buffered-io.c (ffffffff8151bd80)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:zero_user_segments
```
```
In fs/ext4/inline.c (ffffffff81574d10)
Location: include/linux/highmem-internal.h:180
Inline: True
```
```
In fs/ext4/inode.c (ffffffff81579980)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - fs/ext4/inode.c:zero_user_segments
```
```
In fs/ext4/move_extent.c (ffffffff815990e0)
Location: include/linux/highmem-internal.h:180
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff815a3090)
Location: include/linux/highmem-internal.h:180
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff815a45e0)
Location: include/linux/highmem-internal.h:180
Inline: True
```
```
In fs/ext4/verity.c (ffffffff815da840)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/squashfs/file.c (ffffffff815ef0e9)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readahead
```
```
In fs/squashfs/page_actor.c (ffffffff815f1f74)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:handle_next_page
```
```
In fs/squashfs/file_direct.c (ffffffff815f26de)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff815f6310)
Location: include/linux/highmem-internal.h:180
Inline: True
```
```
In fs/ecryptfs/mmap.c (ffffffff8160c6a0)
Location: include/linux/highmem-internal.h:180
Inline: True
```
```
In fs/fuse/dev.c (ffffffff8161b237)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffff81629044)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (ffffffff8162f9a9)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In fs/fuse/ioctl.c (ffffffff81630555)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_do_ioctl
```
```
In block/bio.c (ffffffff8172d76c)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:zero_fill_bio
```
```
In block/blk-map.c (ffffffff8173b9e4)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - block/blk-map.c:bio_copy_kern_endio_read
```
```
In block/bio-integrity.c (ffffffff81774a3f)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/t10-pi.c (ffffffff81776af7)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - block/t10-pi.c:ext_pi_type1_complete
  - block/t10-pi.c:ext_pi_type1_prepare
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/iov_iter.c (ffffffff817d663a)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:copy_pipe_to_iter
```
```
In drivers/xen/grant-table.c (ffffffff81a1a5ef)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81a1ac89)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/base/firmware_loader/main.c (ffffffff81b11a99)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
```
```
In drivers/base/firmware_loader/sysfs.c (ffffffff81b13026)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - drivers/base/firmware_loader/sysfs.c:firmware_rw
```
```
In drivers/scsi/sd.c (ffffffff81b91f09)
Location: include/linux/highmem-internal.h:180
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
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
In arch/x86/hyperv/hv_init.c (ffffffff81044e20)
Location: include/linux/highmem-internal.h:183
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81092178)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff810947d4)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81096478)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
```
```
In kernel/power/snapshot.c (ffffffff811978ea)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/highmem-internal.h:183
Inline: True
```
```
In kernel/module/decompress.c (ffffffff811e1b68)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - kernel/module/decompress.c:module_zstd_decompress
```
```
In kernel/kexec_core.c (ffffffff81213558)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_normal_segment
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/trace/trace_events_user.c (ffffffff812c57a3)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_enabler_write
```
```
In kernel/events/uprobes.c (ffffffff8138177a)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/truncate.c (ffffffff813a3550)
Location: include/linux/highmem-internal.h:183
Inline: True
```
```
In mm/shmem.c (ffffffff813c3031)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_folio_gfp
```
```
In mm/util.c (ffffffff813c447c)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - mm/util.c:folio_copy
  - mm/util.c:folio_copy
```
```
In mm/memory.c (ffffffff813f5d29)
Location: include/linux/highmem-internal.h:183
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
  - mm/memory.c:do_cow_fault
  - mm/memory.c:do_cow_fault
  - mm/memory.c:__wp_page_copy_user
  - mm/memory.c:__wp_page_copy_user
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
```
```
In mm/page_alloc.c (ffffffff81421db8)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/ksm.c (ffffffff81457fd8)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate_device.c (ffffffff8146fec6)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/migrate_device.c:migrate_device_coherent_page
```
```
In mm/khugepaged.c (ffffffff8147fc16)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/secretmem.c (ffffffff8149ff50)
Location: include/linux/highmem-internal.h:183
Inline: True
```
```
In fs/exec.c (ffffffff814ba360)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - fs/exec.c:remove_arg_zero
  - fs/exec.c:copy_string_kernel
```
```
In fs/libfs.c (ffffffff814eeac0)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - fs/libfs.c:zero_user_segments
```
```
In fs/buffer.c (ffffffff81508ce0)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - fs/buffer.c:zero_user_segments
```
```
In fs/mpage.c (ffffffff8150d810)
Location: include/linux/highmem-internal.h:183
Inline: True
```
```
In fs/direct-io.c (ffffffff815102f0)
Location: include/linux/highmem-internal.h:183
Inline: True
```
```
In fs/dax.c (ffffffff8152f148)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
```
```
In fs/verity/read_metadata.c (ffffffff8153d59d)
Location: include/linux/highmem-internal.h:183
Inline: True
```
```
In fs/verity/verify.c (ffffffff8153dbcb)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_data_block
```
```
In fs/iomap/buffered-io.c (ffffffff81554090)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:zero_user_segments
```
```
In fs/ext4/inline.c (ffffffff815acbe0)
Location: include/linux/highmem-internal.h:183
Inline: True
```
```
In fs/ext4/inode.c (ffffffff815b0910)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - fs/ext4/inode.c:zero_user_segments
```
```
In fs/ext4/move_extent.c (ffffffff815cfbc0)
Location: include/linux/highmem-internal.h:183
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff815d9a70)
Location: include/linux/highmem-internal.h:183
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff815daf20)
Location: include/linux/highmem-internal.h:183
Inline: True
```
```
In fs/ext4/verity.c (ffffffff816120ed)
Location: include/linux/highmem-internal.h:183
Inline: True
```
```
In fs/squashfs/file.c (ffffffff816270c6)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readahead
```
```
In fs/squashfs/page_actor.c (ffffffff8162a064)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:handle_next_page
```
```
In fs/squashfs/file_direct.c (ffffffff8162a7d0)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff8162e490)
Location: include/linux/highmem-internal.h:183
Inline: True
```
```
In fs/ecryptfs/mmap.c (ffffffff81644590)
Location: include/linux/highmem-internal.h:183
Inline: True
```
```
In fs/fuse/dev.c (ffffffff816533a7)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffff81661266)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (ffffffff81667be9)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In fs/fuse/ioctl.c (ffffffff81668622)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_do_ioctl
```
```
In crypto/scatterwalk.c (ffffffff817412dd)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (ffffffff81743948)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_next_copy
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff81745489)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_new_entry
```
```
In crypto/shash.c (ffffffff817469ad)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff81769b23)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:zero_fill_bio
```
```
In block/blk-map.c (ffffffff81778124)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - block/blk-map.c:bio_copy_kern_endio_read
```
```
In block/bio-integrity.c (ffffffff817b4765)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/t10-pi.c (ffffffff817b66cb)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - block/t10-pi.c:ext_pi_type1_complete
  - block/t10-pi.c:ext_pi_type1_prepare
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/iov_iter.c (ffffffff81813ced)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_page_to_iter_nofault
  - lib/iov_iter.c:copy_page_to_iter_nofault
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In drivers/xen/grant-table.c (ffffffff81a6346f)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81a63e39)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/base/firmware_loader/main.c (ffffffff81b5fd89)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
```
```
In drivers/base/firmware_loader/sysfs.c (ffffffff81b61336)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - drivers/base/firmware_loader/sysfs.c:firmware_rw
```
```
In drivers/scsi/sd.c (ffffffff81be4eea)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_set_special_bvec
```
```
In net/core/skbuff.c (ffffffff81e14cbd)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_splice_from_iter
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
In arch/x86/hyperv/hv_init.c (ffffffff8104b350)
Location: include/linux/highmem-internal.h:183
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81099598)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109bcb4)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109d9e8)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
```
```
In arch/x86/kernel/crash.c (ffffffff810b81d5)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:arch_crash_handle_hotplug_event
```
```
In kernel/power/snapshot.c (ffffffff811a6553)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/highmem-internal.h:183
Inline: True
```
```
In kernel/module/decompress.c (ffffffff811f78d2)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - kernel/module/decompress.c:module_zstd_decompress
```
```
In kernel/crash_core.c (ffffffff8122a34a)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - kernel/crash_core.c:crash_handle_hotplug_event
```
```
In kernel/kexec_core.c (ffffffff8122b488)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_normal_segment
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/trace/trace_events_user.c (ffffffff812e1fe9)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_enabler_write
```
```
In kernel/events/uprobes.c (ffffffff813aab0c)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/truncate.c (ffffffff813cd100)
Location: include/linux/highmem-internal.h:183
Inline: True
```
```
In mm/shmem.c (ffffffff813edb4a)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_folio_gfp
```
```
In mm/util.c (ffffffff813ef4b5)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
  - mm/util.c:folio_copy
  - mm/util.c:folio_copy
```
```
In mm/memory.c (ffffffff81421a06)
Location: include/linux/highmem-internal.h:183
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
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:__wp_page_copy_user
  - mm/memory.c:__wp_page_copy_user
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
```
```
In mm/page_alloc.c (ffffffff8144ebea)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/swapfile.c (ffffffff81466dce)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff814713c7)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - mm/zswap.c:zswap_load
  - mm/zswap.c:zswap_store
```
```
In mm/ksm.c (ffffffff8391dd08)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:cmp_and_merge_page
```
```
In mm/page_poison.c (ffffffff81492f26)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - mm/page_poison.c:__kernel_unpoison_pages
  - mm/page_poison.c:__kernel_poison_pages
```
```
In mm/migrate_device.c (ffffffff8149f140)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/migrate_device.c:migrate_device_coherent_page
```
```
In mm/khugepaged.c (ffffffff814add20)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/secretmem.c (ffffffff814cf6a0)
Location: include/linux/highmem-internal.h:183
Inline: True
```
```
In fs/exec.c (ffffffff814ec8e0)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - fs/exec.c:remove_arg_zero
  - fs/exec.c:copy_string_kernel
```
```
In fs/libfs.c (ffffffff81522aa0)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - fs/libfs.c:zero_user_segments
```
```
In fs/buffer.c (ffffffff8153dfa0)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - fs/buffer.c:zero_user_segments
```
```
In fs/mpage.c (ffffffff81542530)
Location: include/linux/highmem-internal.h:183
Inline: True
```
```
In fs/direct-io.c (ffffffff815447a0)
Location: include/linux/highmem-internal.h:183
Inline: True
```
```
In fs/dax.c (ffffffff81564028)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
```
```
In fs/verity/read_metadata.c (ffffffff815729fd)
Location: include/linux/highmem-internal.h:183
Inline: True
```
```
In fs/verity/verify.c (ffffffff8157316b)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_data_block
```
```
In fs/coredump.c (ffffffff81586fd7)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
```
```
In fs/iomap/buffered-io.c (ffffffff8158a070)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:zero_user_segments
```
```
In fs/ext4/inline.c (ffffffff815e5b10)
Location: include/linux/highmem-internal.h:183
Inline: True
```
```
In fs/ext4/inode.c (ffffffff815e9840)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - fs/ext4/inode.c:zero_user_segments
```
```
In fs/ext4/move_extent.c (ffffffff81608450)
Location: include/linux/highmem-internal.h:183
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff816127a0)
Location: include/linux/highmem-internal.h:183
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff81613750)
Location: include/linux/highmem-internal.h:183
Inline: True
```
```
In fs/ext4/verity.c (ffffffff8164ae8d)
Location: include/linux/highmem-internal.h:183
Inline: True
```
```
In fs/squashfs/file.c (ffffffff81660200)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readahead
```
```
In fs/squashfs/page_actor.c (ffffffff816632e4)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:handle_next_page
```
```
In fs/squashfs/file_direct.c (ffffffff81663aeb)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff81667950)
Location: include/linux/highmem-internal.h:183
Inline: True
```
```
In fs/ecryptfs/mmap.c (ffffffff8167d92a)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff8167ed20)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffffffff816802a8)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/dev.c (ffffffff8168c9b7)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffff8169b126)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (ffffffff816a1f16)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In fs/fuse/ioctl.c (ffffffff816a2922)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_do_ioctl
```
```
In crypto/scatterwalk.c (ffffffff8178217d)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (ffffffff81785c78)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_next_copy
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff81787777)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_new_entry
  - crypto/ahash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff817abcd3)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:zero_fill_bio_iter
```
```
In block/blk-map.c (ffffffff817ba504)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - block/blk-map.c:bio_copy_kern_endio_read
```
```
In block/bio-integrity.c (ffffffff817f85a5)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/t10-pi.c (ffffffff817fb0db)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - block/t10-pi.c:ext_pi_type1_complete
  - block/t10-pi.c:ext_pi_type1_prepare
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/iov_iter.c (ffffffff8185861a)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_page_to_iter_nofault
  - lib/iov_iter.c:copy_page_to_iter_nofault
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In drivers/xen/grant-table.c (ffffffff81ab5c8f)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81ab6679)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/iommu/iommufd/iova_bitmap.c (ffffffff81b71ba8)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - drivers/iommu/iommufd/iova_bitmap.c:iova_bitmap_set
```
```
In drivers/base/firmware_loader/main.c (ffffffff81bb3799)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
```
```
In drivers/base/firmware_loader/sysfs.c (ffffffff81bb4dc6)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - drivers/base/firmware_loader/sysfs.c:firmware_rw
```
```
In drivers/scsi/sd.c (ffffffff81c3a04a)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_set_special_bvec
```
```
In net/core/skbuff.c (ffffffff81ece48f)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - net/core/skbuff.c:csum_and_copy_from_iter_full
  - net/core/skbuff.c:skb_splice_from_iter
```
```
In net/core/datagram.c (ffffffff81edd82d)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - net/core/datagram.c:csum_and_copy_to_iter
```
```
In net/xdp/xsk.c (ffffffff8213eb41)
Location: include/linux/highmem-internal.h:183
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_build_skb
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
