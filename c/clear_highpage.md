# Function: <code>clear_highpage</code>

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
In mm/page_alloc.c (ffffffff81196085)
Location: include/linux/highmem.h:186
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/shmem.c (ffffffff811a8626)
Location: include/linux/highmem.h:186
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_getpage_gfp
```
```
In fs/libfs.c (ffffffff81234cbf)
Location: include/linux/highmem.h:186
Inline: True
Inline callers:
  - fs/libfs.c:simple_readpage
```
```
In fs/fuse/dev.c (ffffffff8130e959)
Location: include/linux/highmem.h:186
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In drivers/xen/balloon.c (ffffffff814c64ec)
Location: include/linux/highmem.h:186
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/block/brd.c (0)
Location: include/linux/highmem.h:186
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
In mm/page_alloc.c (ffffffff811aa0af)
Location: include/linux/highmem.h:186
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/shmem.c (ffffffff811c006b)
Location: include/linux/highmem.h:186
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/libfs.c (ffffffff8125d3af)
Location: include/linux/highmem.h:186
Inline: True
Inline callers:
  - fs/libfs.c:simple_readpage
```
```
In fs/fuse/dev.c (ffffffff81342cd1)
Location: include/linux/highmem.h:186
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In drivers/xen/balloon.c (ffffffff81516c1d)
Location: include/linux/highmem.h:186
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/block/brd.c (ffffffff815c3273)
Location: include/linux/highmem.h:186
Inline: True
Inline callers:
  - drivers/block/brd.c:brd_make_request
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
In mm/page_alloc.c (ffffffff811ba5e9)
Location: include/linux/highmem.h:186
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/shmem.c (ffffffff811d023b)
Location: include/linux/highmem.h:186
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/libfs.c (ffffffff812708df)
Location: include/linux/highmem.h:186
Inline: True
Inline callers:
  - fs/libfs.c:simple_readpage
```
```
In fs/fuse/dev.c (ffffffff81358afa)
Location: include/linux/highmem.h:186
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In drivers/xen/balloon.c (ffffffff81543089)
Location: include/linux/highmem.h:186
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
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
In mm/page_alloc.c (ffffffff811c25bb)
Location: include/linux/highmem.h:186
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/shmem.c (ffffffff811d8cdf)
Location: include/linux/highmem.h:186
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/libfs.c (ffffffff8127d219)
Location: include/linux/highmem.h:186
Inline: True
Inline callers:
  - fs/libfs.c:simple_readpage
```
```
In fs/fuse/dev.c (ffffffff8136d4f9)
Location: include/linux/highmem.h:186
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In drivers/xen/balloon.c (ffffffff81556f39)
Location: include/linux/highmem.h:186
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
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
In kernel/kexec_core.c (0)
Location: include/linux/highmem.h:187
Inline: True
```
```
In mm/page_alloc.c (ffffffff811d7038)
Location: include/linux/highmem.h:187
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/shmem.c (ffffffff811edf2d)
Location: include/linux/highmem.h:187
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/libfs.c (ffffffff8129fcb9)
Location: include/linux/highmem.h:187
Inline: True
Inline callers:
  - fs/libfs.c:simple_readpage
```
```
In fs/fuse/dev.c (ffffffff81391c6e)
Location: include/linux/highmem.h:187
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In drivers/xen/balloon.c (ffffffff815baf5a)
Location: include/linux/highmem.h:187
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
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
In kernel/power/snapshot.c (ffffffff810ec2a5)
Location: include/linux/highmem.h:187
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/kexec_core.c (0)
Location: include/linux/highmem.h:187
Inline: True
```
```
In mm/page_alloc.c (ffffffff811f84d0)
Location: include/linux/highmem.h:187
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/shmem.c (ffffffff8120f3c8)
Location: include/linux/highmem.h:187
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/libfs.c (ffffffff812c6595)
Location: include/linux/highmem.h:187
Inline: True
Inline callers:
  - fs/libfs.c:simple_readpage
```
```
In fs/fuse/dev.c (ffffffff813c0ca0)
Location: include/linux/highmem.h:187
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In drivers/xen/balloon.c (ffffffff815f360a)
Location: include/linux/highmem.h:187
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
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
In kernel/power/snapshot.c (ffffffff810f7945)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/kexec_core.c (0)
Location: include/linux/highmem.h:211
Inline: True
```
```
In mm/page_alloc.c (ffffffff8120a8c7)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/shmem.c (ffffffff81221bfa)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/khugepaged.c (ffffffff8128fbc4)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/libfs.c (ffffffff812db795)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/libfs.c:simple_readpage
```
```
In fs/fuse/dev.c (ffffffff813da000)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In drivers/xen/grant-table.c (ffffffff8160cd15)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff8160e689)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/scsi/sd.c (ffffffff8172319f)
Location: include/linux/highmem.h:211
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
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810ffef6)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/kexec_core.c (ffffffff8114d519)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In mm/shmem.c (ffffffff8123146c)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/page_alloc.c (ffffffff8126d4d3)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/khugepaged.c (ffffffff812aac65)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/libfs.c (ffffffff812f9e25)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/libfs.c:simple_readpage
```
```
In fs/fuse/dev.c (ffffffff814062af)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In drivers/xen/grant-table.c (ffffffff816419c0)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81642416)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/scsi/sd.c (ffffffff817605ee)
Location: include/linux/highmem.h:211
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
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff8110c356)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/kexec_core.c (ffffffff81159204)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In mm/shmem.c (ffffffff8123f52c)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/page_alloc.c (ffffffff8127c013)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/khugepaged.c (ffffffff812bc236)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/libfs.c (ffffffff8130ba55)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/libfs.c:simple_readpage
```
```
In fs/fuse/dev.c (ffffffff81420e0f)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In drivers/xen/grant-table.c (ffffffff81662fd0)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff816649df)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/scsi/sd.c (ffffffff8178457f)
Location: include/linux/highmem.h:211
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
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81117185)
Location: include/linux/highmem.h:280
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/kexec_core.c (0)
Location: include/linux/highmem.h:280
Inline: True
```
```
In mm/shmem.c (ffffffff8126cd6f)
Location: include/linux/highmem.h:280
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
```
```
In mm/page_alloc.c (ffffffff812ae33d)
Location: include/linux/highmem.h:280
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/khugepaged.c (ffffffff812f176e)
Location: include/linux/highmem.h:280
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/libfs.c (ffffffff81345985)
Location: include/linux/highmem.h:280
Inline: True
Inline callers:
  - fs/libfs.c:simple_readpage
```
```
In fs/fuse/dev.c (ffffffff8146fea1)
Location: include/linux/highmem.h:280
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In drivers/xen/grant-table.c (ffffffff81713504)
Location: include/linux/highmem.h:280
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff8171455f)
Location: include/linux/highmem.h:280
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/scsi/sd.c (ffffffff8184436f)
Location: include/linux/highmem.h:280
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_unmap_cmnd
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
In kernel/power/snapshot.c (ffffffff81112221)
Location: include/linux/highmem.h:200
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_or_poison_free_page
```
```
In kernel/kexec_core.c (0)
Location: include/linux/highmem.h:200
Inline: True
```
```
In mm/shmem.c (ffffffff81277814)
Location: include/linux/highmem.h:200
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
```
```
In mm/page_alloc.c (ffffffff812b9f56)
Location: include/linux/highmem.h:200
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/khugepaged.c (ffffffff812fdcc3)
Location: include/linux/highmem.h:200
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/libfs.c (ffffffff81351fd5)
Location: include/linux/highmem.h:200
Inline: True
Inline callers:
  - fs/libfs.c:simple_readpage
```
```
In fs/fuse/dev.c (ffffffff8148a73e)
Location: include/linux/highmem.h:200
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In drivers/xen/grant-table.c (ffffffff817303f4)
Location: include/linux/highmem.h:200
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81730c3f)
Location: include/linux/highmem.h:200
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/scsi/sd.c (ffffffff81854688)
Location: include/linux/highmem.h:200
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_unmap_cmnd
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
In kernel/power/snapshot.c (ffffffff81113fcd)
Location: include/linux/highmem.h:200
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
```
In kernel/kexec_core.c (0)
Location: include/linux/highmem.h:200
Inline: True
```
```
In mm/shmem.c (ffffffff8127c674)
Location: include/linux/highmem.h:200
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
```
```
In mm/page_alloc.c (ffffffff812bf3f9)
Location: include/linux/highmem.h:200
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/khugepaged.c (ffffffff81304e39)
Location: include/linux/highmem.h:200
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/libfs.c (ffffffff81358ce5)
Location: include/linux/highmem.h:200
Inline: True
Inline callers:
  - fs/libfs.c:simple_readpage
```
```
In fs/fuse/dev.c (ffffffff8149020d)
Location: include/linux/highmem.h:200
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In drivers/xen/grant-table.c (ffffffff81713f94)
Location: include/linux/highmem.h:200
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff817147cb)
Location: include/linux/highmem.h:200
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/scsi/sd.c (ffffffff81838228)
Location: include/linux/highmem.h:200
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_unmap_cmnd
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
In kernel/power/snapshot.c (ffffffff811340d1)
Location: include/linux/highmem.h:178
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
```
In kernel/kexec_core.c (0)
Location: include/linux/highmem.h:178
Inline: True
```
```
In mm/shmem.c (ffffffff812ba884)
Location: include/linux/highmem.h:178
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
```
```
In mm/page_alloc.c (ffffffff81301575)
Location: include/linux/highmem.h:178
Inline: True
```
```
In mm/khugepaged.c (ffffffff8134ebcc)
Location: include/linux/highmem.h:178
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/secretmem.c (ffffffff81366382)
Location: include/linux/highmem.h:178
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_freepage
```
```
In fs/libfs.c (ffffffff813a7345)
Location: include/linux/highmem.h:178
Inline: True
Inline callers:
  - fs/libfs.c:simple_readpage
```
```
In fs/fuse/dev.c (ffffffff814e7cc1)
Location: include/linux/highmem.h:178
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In drivers/xen/grant-table.c (ffffffff817909cf)
Location: include/linux/highmem.h:178
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff8179160b)
Location: include/linux/highmem.h:178
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/scsi/sd.c (ffffffff818c5162)
Location: include/linux/highmem.h:178
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
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff811561ca)
Location: include/linux/highmem.h:239
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
```
In kernel/kexec_core.c (0)
Location: include/linux/highmem.h:239
Inline: True
```
```
In mm/shmem.c (ffffffff81317f22)
Location: include/linux/highmem.h:239
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
```
```
In mm/page_alloc.c (ffffffff813709f8)
Location: include/linux/highmem.h:239
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/khugepaged.c (ffffffff813c5836)
Location: include/linux/highmem.h:239
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/fuse/dev.c (ffffffff815760d3)
Location: include/linux/highmem.h:239
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In drivers/xen/grant-table.c (ffffffff818c9814)
Location: include/linux/highmem.h:239
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff818ca0c9)
Location: include/linux/highmem.h:239
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/scsi/sd.c (ffffffff81a11c3e)
Location: include/linux/highmem.h:239
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
In kernel/power/snapshot.c (ffffffff81186769)
Location: include/linux/highmem.h:239
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
```
In kernel/kexec_core.c (0)
Location: include/linux/highmem.h:239
Inline: True
```
```
In mm/shmem.c (ffffffff8138ccf2)
Location: include/linux/highmem.h:239
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_get_folio_gfp
```
```
In mm/page_alloc.c (ffffffff813ece7a)
Location: include/linux/highmem.h:239
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/khugepaged.c (ffffffff8144a191)
Location: include/linux/highmem.h:239
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/fuse/dev.c (ffffffff8161b1d1)
Location: include/linux/highmem.h:239
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In drivers/xen/grant-table.c (ffffffff81a1a5ef)
Location: include/linux/highmem.h:239
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81a1ac89)
Location: include/linux/highmem.h:239
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/scsi/sd.c (ffffffff81b91f09)
Location: include/linux/highmem.h:239
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
In kernel/power/snapshot.c (ffffffff811978ea)
Location: include/linux/highmem.h:237
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
```
In kernel/kexec_core.c (0)
Location: include/linux/highmem.h:237
Inline: True
```
```
In mm/shmem.c (ffffffff813bfc4e)
Location: include/linux/highmem.h:237
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_folio_gfp
```
```
In mm/khugepaged.c (ffffffff8147fc16)
Location: include/linux/highmem.h:237
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/fuse/dev.c (ffffffff81653341)
Location: include/linux/highmem.h:237
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In drivers/xen/grant-table.c (ffffffff81a6346f)
Location: include/linux/highmem.h:237
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81a63e39)
Location: include/linux/highmem.h:237
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/scsi/sd.c (ffffffff81be4eea)
Location: include/linux/highmem.h:237
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_set_special_bvec
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
In kernel/power/snapshot.c (ffffffff811a6553)
Location: include/linux/highmem.h:237
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
```
In kernel/kexec_core.c (0)
Location: include/linux/highmem.h:237
Inline: True
```
```
In mm/shmem.c (ffffffff813eab8e)
Location: include/linux/highmem.h:237
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_folio_gfp
```
```
In mm/khugepaged.c (ffffffff814add20)
Location: include/linux/highmem.h:237
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/fuse/dev.c (ffffffff8168c951)
Location: include/linux/highmem.h:237
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In drivers/xen/grant-table.c (ffffffff81ab5c8f)
Location: include/linux/highmem.h:237
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81ab6679)
Location: include/linux/highmem.h:237
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/scsi/sd.c (ffffffff81c3a04a)
Location: include/linux/highmem.h:237
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_set_special_bvec
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
In kernel/kexec_core.c (0)
Location: include/linux/highmem.h:211
Inline: True
```
```
In mm/shmem.c (ffff8000102d0d38)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/page_alloc.c (ffff8000103135b8)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/khugepaged.c (ffff80001035d3c8)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/libfs.c (ffff8000103c0948)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/libfs.c:simple_readpage
```
```
In fs/fuse/dev.c (ffff800010503b08)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In drivers/xen/grant-table.c (ffff80001082cd18)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffff80001082e774)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/scsi/sd.c (ffff80001098ad4c)
Location: include/linux/highmem.h:211
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
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (c03beb00)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/kexec_core.c (0)
Location: include/linux/highmem.h:211
Inline: True
```
```
In mm/shmem.c (c04fb48c)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
```
```
In mm/page_alloc.c (c052e348)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In fs/libfs.c (c059d384)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/libfs.c:simple_readpage
```
```
In fs/fuse/dev.c (c06c0038)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In drivers/scsi/sd.c (c0a5d000)
Location: include/linux/highmem.h:211
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
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (c000000000230f00)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In mm/shmem.c (c000000000390f50)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/page_alloc.c (c0000000003e5260)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/khugepaged.c (c000000000448e5c)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/libfs.c (c0000000004bf024)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/libfs.c:simple_readpage
```
```
In fs/fuse/dev.c (c000000000648788)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In drivers/scsi/sd.c (c000000000a4b770)
Location: include/linux/highmem.h:211
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
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffe0001ee612)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
```
```
In mm/page_alloc.c (ffffffe00021a842)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In fs/libfs.c (ffffffe0002808d8)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/libfs.c:simple_readpage
```
```
In fs/fuse/dev.c (ffffffe0003707ae)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In drivers/scsi/sd.c (ffffffe0005ef150)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
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
In kernel/power/snapshot.c (ffffffff81104576)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/kexec_core.c (ffffffff81151824)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In mm/shmem.c (ffffffff81237b7c)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/page_alloc.c (ffffffff81274663)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/khugepaged.c (ffffffff812b4816)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/libfs.c (ffffffff81304035)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/libfs.c:simple_readpage
```
```
In fs/fuse/dev.c (ffffffff814193ef)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In drivers/xen/grant-table.c (ffffffff81628e40)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff8162a84f)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/scsi/sd.c (ffffffff81738c6f)
Location: include/linux/highmem.h:211
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
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810f5816)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/kexec_core.c (ffffffff81144b04)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In mm/shmem.c (ffffffff8122abbc)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/page_alloc.c (ffffffff812665d3)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/khugepaged.c (ffffffff812a587d)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/libfs.c (ffffffff812f4c55)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/libfs.c:simple_readpage
```
```
In fs/fuse/dev.c (ffffffff81409e6f)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In drivers/scsi/sd.c (ffffffff8171a90f)
Location: include/linux/highmem.h:211
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
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81102826)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/kexec_core.c (ffffffff8114f6d4)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In mm/shmem.c (ffffffff8123591c)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/page_alloc.c (ffffffff81272403)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/khugepaged.c (ffffffff812b2626)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/libfs.c (ffffffff81301e25)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/libfs.c:simple_readpage
```
```
In fs/fuse/dev.c (ffffffff8141558f)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In drivers/xen/grant-table.c (ffffffff81656e10)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff8165881f)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/scsi/sd.c (ffffffff817793ff)
Location: include/linux/highmem.h:211
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
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff8110dc06)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/kexec_core.c (ffffffff8115c4f4)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In mm/shmem.c (ffffffff81245bdb)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/page_alloc.c (ffffffff81282242)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/khugepaged.c (ffffffff812c2ccc)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/libfs.c (ffffffff81313335)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/libfs.c:simple_readpage
```
```
In fs/fuse/dev.c (ffffffff8142c318)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In drivers/xen/grant-table.c (ffffffff816713f0)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81672e1f)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/scsi/sd.c (ffffffff8179321f)
Location: include/linux/highmem.h:211
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
</details>
</li>
</ul>

## Differences
