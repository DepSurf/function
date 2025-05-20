# Function: <code>xa_load</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *xa_load(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a17a00)
Location: lib/xarray.c:1266
Inline: False
Direct callers:
  - kernel/memremap.c:get_dev_pagemap
  - mm/readahead.c:__do_page_cache_readahead
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
```
**Symbols:**

```
ffffffff81a17a00-ffffffff81a17a79: xa_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *xa_load(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a876b0)
Location: lib/xarray.c:1285
Inline: False
Direct callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/memremap.c:get_dev_pagemap
```
**Symbols:**

```
ffffffff81a876b0-ffffffff81a8772b: xa_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *xa_load(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81abe950)
Location: lib/xarray.c:1296
Inline: False
Direct callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/shmem.c:shmem_confirm_swap
  - mm/memremap.c:get_dev_pagemap
```
**Symbols:**

```
ffffffff81abe950-ffffffff81abe9cb: xa_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *xa_load(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff815fb090)
Location: lib/xarray.c:1298
Inline: False
Direct callers:
  - mm/readahead.c:page_cache_readahead_unbounded
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/memremap.c:get_dev_pagemap
  - fs/mpage.c:mpage_readahead
  - fs/iomap/buffered-io.c:iomap_readahead_actor
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - drivers/iommu/ioasid.c:ioasid_find
  - drivers/iommu/ioasid.c:ioasid_free
  - drivers/iommu/ioasid.c:ioasid_set_data
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:init_memory_block
  - drivers/base/memory.c:find_memory_block
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:__devlink_snapshot_id_decrement
  - net/core/devlink.c:__devlink_snapshot_id_increment
```
**Symbols:**

```
ffffffff815fb090-ffffffff815fb10b: xa_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *xa_load(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8161fb80)
Location: lib/xarray.c:1448
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_load_page
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/readahead.c:page_cache_ra_unbounded
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/vmalloc.c:vb_free
  - mm/memremap.c:get_dev_pagemap
  - fs/mpage.c:mpage_readahead
  - fs/io_uring.c:io_uring_flush
  - fs/io_uring.c:io_uring_flush
  - fs/io_uring.c:io_uring_flush
  - fs/io_uring.c:io_uring_add_task_file
  - fs/iomap/buffered-io.c:iomap_readahead_actor
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - drivers/iommu/ioasid.c:ioasid_find
  - drivers/iommu/ioasid.c:ioasid_put
  - drivers/iommu/ioasid.c:ioasid_get
  - drivers/iommu/ioasid.c:ioasid_set_data
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:init_memory_block
  - drivers/base/memory.c:find_memory_block
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:__devlink_snapshot_id_decrement
  - net/core/devlink.c:__devlink_snapshot_id_increment
```
**Symbols:**

```
ffffffff8161fb80-ffffffff8161fc0d: xa_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *xa_load(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81603300)
Location: lib/xarray.c:1449
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_load_page
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_unbounded
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/vmalloc.c:vb_free
  - mm/swap_state.c:get_shadow_from_swap_cache
  - mm/memremap.c:get_dev_pagemap
  - fs/mpage.c:mpage_readahead
  - fs/io_uring.c:__io_uring_add_task_file
  - fs/io_uring.c:io_init_req
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_provide_buffers
  - fs/iomap/buffered-io.c:iomap_readahead_actor
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/bio.c:bioset_init
  - block/bio.c:bioset_exit
  - block/genhd.c:blk_lookup_devt
  - block/partitions/core.c:add_partition
  - drivers/iommu/ioasid.c:ioasid_find
  - drivers/iommu/ioasid.c:ioasid_put
  - drivers/iommu/ioasid.c:ioasid_get
  - drivers/iommu/ioasid.c:ioasid_set_data
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:init_memory_block
  - drivers/base/memory.c:find_memory_block
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:__devlink_region_snapshot_create
  - net/core/devlink.c:__devlink_snapshot_id_decrement
```
**Symbols:**

```
ffffffff81603300-ffffffff8160338d: xa_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *xa_load(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff816718a0)
Location: lib/xarray.c:1449
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_load_page
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_unbounded
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/vmalloc.c:vb_free
  - mm/swap_state.c:get_shadow_from_swap_cache
  - mm/memremap.c:get_dev_pagemap
  - fs/mpage.c:mpage_readahead
  - fs/io_uring.c:__io_uring_add_tctx_node
  - fs/io_uring.c:io_init_req
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_provide_buffers
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/bio.c:bioset_init
  - block/bio.c:bioset_exit
  - block/genhd.c:blk_lookup_devt
  - block/partitions/core.c:bdev_resize_partition
  - block/partitions/core.c:bdev_del_partition
  - block/partitions/core.c:add_partition
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:intel_svm_bind_mm
  - drivers/iommu/intel/svm.c:pasid_to_svm_sdev
  - drivers/iommu/ioasid.c:ioasid_find
  - drivers/iommu/ioasid.c:ioasid_put
  - drivers/iommu/ioasid.c:ioasid_get
  - drivers/iommu/ioasid.c:ioasid_set_data
  - drivers/base/memory.c:memory_group_find_by_id
  - drivers/base/memory.c:memory_group_unregister
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:init_memory_block
  - drivers/base/memory.c:find_memory_block
  - drivers/vfio/vfio.c:vfio_assign_device_set
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:__devlink_region_snapshot_create
  - net/core/devlink.c:__devlink_snapshot_id_decrement
```
**Symbols:**

```
ffffffff816718a0-ffffffff8167192d: xa_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *xa_load(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8178c860)
Location: lib/xarray.c:1456
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_load_page
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/main.c:arch_memory_failure
  - arch/x86/kernel/cpu/sgx/main.c:arch_is_platform_page
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
  - kernel/irq/msi.c:msi_domain_populate_irqs
  - kernel/irq/msi.c:msi_get_virq
  - mm/filemap.c:__filemap_add_folio
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_unbounded
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_reparent_list_lrus
  - mm/list_lru.c:memcg_reparent_list_lrus
  - mm/list_lru.c:__list_lru_walk_one
  - mm/list_lru.c:list_lru_count_one
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
  - mm/vmalloc.c:vb_free
  - mm/swap_state.c:get_shadow_from_swap_cache
  - mm/memremap.c:get_dev_pagemap
  - fs/mpage.c:mpage_readahead
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - security/apparmor/secid.c:apparmor_secid_to_secctx
  - block/bio.c:bioset_init
  - block/bio.c:bioset_exit
  - block/blk-mq.c:blk_mq_poll
  - block/blk-mq.c:blk_mq_poll_hybrid
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/genhd.c:blk_lookup_devt
  - block/partitions/core.c:bdev_resize_partition
  - block/partitions/core.c:bdev_del_partition
  - block/partitions/core.c:add_partition
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:io_register_pbuf_ring
  - io_uring/io_uring.c:__io_uring_add_tctx_node
  - io_uring/io_uring.c:io_init_req
  - io_uring/io_uring.c:io_provide_buffers
  - io_uring/io_uring.c:io_remove_buffers
  - io_uring/io_uring.c:io_buffer_select
  - io_uring/io_uring.c:io_kbuf_recycle
  - drivers/xen/grant-dma-ops.c:xen_grant_setup_dma_ops
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:intel_svm_bind_mm
  - drivers/iommu/intel/svm.c:pasid_to_svm_sdev
  - drivers/iommu/ioasid.c:ioasid_find
  - drivers/iommu/ioasid.c:ioasid_free
  - drivers/iommu/ioasid.c:ioasid_set_data
  - drivers/base/memory.c:memory_group_find_by_id
  - drivers/base/memory.c:memory_group_unregister
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:add_memory_block
  - drivers/base/memory.c:find_memory_block
  - drivers/dax/super.c:fs_dax_get_by_bdev
  - drivers/vfio/vfio.c:vfio_assign_device_set
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:__devlink_region_snapshot_create
  - net/core/devlink.c:__devlink_snapshot_id_decrement
```
**Symbols:**

```
ffffffff8178c860-ffffffff8178c945: xa_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *xa_load(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff82049f20)
Location: lib/xarray.c:1456
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_access
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_load_page
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/main.c:arch_memory_failure
  - arch/x86/kernel/cpu/sgx/main.c:arch_is_platform_page
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
  - kernel/irq/msi.c:msi_domain_populate_irqs
  - kernel/irq/msi.c:msi_domain_get_virq
  - mm/filemap.c:__filemap_add_folio
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_unbounded
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_reparent_list_lrus
  - mm/list_lru.c:memcg_reparent_list_lrus
  - mm/list_lru.c:__list_lru_walk_one
  - mm/list_lru.c:list_lru_count_one
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
  - mm/vmalloc.c:vb_free
  - mm/swap_state.c:get_shadow_from_swap_cache
  - mm/memremap.c:get_dev_pagemap
  - fs/mpage.c:mpage_readahead
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - security/apparmor/secid.c:apparmor_secid_to_secctx
  - block/bio.c:bioset_init
  - block/bio.c:bioset_exit
  - block/blk-mq.c:blk_mq_poll_classic
  - block/blk-mq.c:blk_mq_poll_hybrid
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/genhd.c:blk_lookup_devt
  - block/partitions/core.c:bdev_resize_partition
  - block/partitions/core.c:bdev_del_partition
  - block/partitions/core.c:add_partition
  - io_uring/io_uring.c:io_init_req
  - io_uring/tctx.c:__io_uring_add_tctx_node
  - io_uring/kbuf.c:io_unregister_pbuf_ring
  - io_uring/kbuf.c:io_register_pbuf_ring
  - io_uring/kbuf.c:io_provide_buffers
  - io_uring/kbuf.c:io_remove_buffers
  - io_uring/kbuf.c:io_buffer_select
  - io_uring/kbuf.c:io_kbuf_recycle_legacy
  - drivers/pci/p2pdma.c:pci_p2pdma_map_segment
  - drivers/xen/grant-dma-ops.c:xen_virtio_restricted_mem_acc
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_unmap_page
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_map_page
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_free
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
  - drivers/iommu/intel/iommu.c:domain_context_clear_one
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:domain_detach_iommu
  - drivers/iommu/intel/iommu.c:domain_attach_iommu
  - drivers/iommu/intel/iommu.c:intel_flush_iotlb_all
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/svm.c:intel_svm_drain_prq
  - drivers/iommu/intel/svm.c:intel_svm_bind_mm
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev_pasid
  - drivers/iommu/ioasid.c:ioasid_find
  - drivers/iommu/ioasid.c:ioasid_free
  - drivers/iommu/ioasid.c:ioasid_set_data
  - drivers/base/memory.c:memblk_nr_poison_sub
  - drivers/base/memory.c:memblk_nr_poison_inc
  - drivers/base/memory.c:memory_group_find_by_id
  - drivers/base/memory.c:memory_group_unregister
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:add_memory_block
  - drivers/base/memory.c:find_memory_block
  - drivers/dax/super.c:fs_dax_get_by_bdev
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_nl_cmd_region_del
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:__devlink_region_snapshot_create
  - net/core/devlink.c:__devlink_snapshot_id_decrement
  - net/core/devlink.c:devlink_nl_cmd_port_new_doit
  - net/core/devlink.c:devlink_nl_pre_doit
  - net/core/devlink.c:devlink_nl_pre_doit
  - net/core/devlink.c:devlink_nl_pre_doit
```
**Symbols:**

```
ffffffff82049f20-ffffffff8204a005: xa_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *xa_load(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff820c87c0)
Location: lib/xarray.c:1454
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_access
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_load_page
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/main.c:arch_memory_failure
  - arch/x86/kernel/cpu/sgx/main.c:arch_is_platform_page
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
  - kernel/irq/msi.c:msi_domain_populate_irqs
  - kernel/irq/msi.c:msi_domain_get_virq
  - mm/filemap.c:__filemap_add_folio
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_unbounded
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_reparent_list_lrus
  - mm/list_lru.c:memcg_reparent_list_lrus
  - mm/list_lru.c:__list_lru_walk_one
  - mm/list_lru.c:list_lru_count_one
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
  - mm/vmalloc.c:vmap_ram_vread_iter
  - mm/vmalloc.c:vb_free
  - mm/swap_state.c:get_shadow_from_swap_cache
  - mm/memremap.c:get_dev_pagemap
  - fs/mpage.c:mpage_readahead
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - security/apparmor/secid.c:apparmor_secid_to_secctx
  - block/bio.c:bioset_init
  - block/bio.c:bioset_exit
  - block/blk-mq.c:blk_mq_poll
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/genhd.c:part_devt
  - block/partitions/core.c:bdev_resize_partition
  - block/partitions/core.c:bdev_del_partition
  - block/partitions/core.c:add_partition
  - io_uring/io_uring.c:io_init_req
  - io_uring/tctx.c:__io_uring_add_tctx_node
  - io_uring/kbuf.c:io_pbuf_get_address
  - io_uring/kbuf.c:io_unregister_pbuf_ring
  - io_uring/kbuf.c:io_register_pbuf_ring
  - io_uring/kbuf.c:io_provide_buffers
  - io_uring/kbuf.c:io_remove_buffers
  - io_uring/kbuf.c:io_buffer_select
  - io_uring/kbuf.c:io_kbuf_recycle_legacy
  - drivers/pci/p2pdma.c:pci_p2pdma_map_segment
  - drivers/xen/grant-dma-ops.c:xen_virtio_restricted_mem_acc
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_unmap_page
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_map_page
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_free
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
  - drivers/iommu/intel/iommu.c:domain_context_clear_one
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:domain_detach_iommu
  - drivers/iommu/intel/iommu.c:domain_attach_iommu
  - drivers/iommu/intel/iommu.c:intel_flush_iotlb_all
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/svm.c:intel_svm_drain_prq
  - drivers/iommu/intel/svm.c:intel_svm_bind_mm
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev_pasid
  - drivers/base/memory.c:memblk_nr_poison_sub
  - drivers/base/memory.c:memblk_nr_poison_inc
  - drivers/base/memory.c:memory_group_find_by_id
  - drivers/base/memory.c:memory_group_unregister
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:add_memory_block
  - drivers/base/memory.c:find_memory_block
  - drivers/dax/super.c:fs_dax_get_by_bdev
  - net/sched/cls_api.c:tcf_classify
  - net/devlink/leftover.c:devl_param_value_changed
  - net/devlink/leftover.c:devl_param_driverinit_value_set
  - net/devlink/leftover.c:devl_param_driverinit_value_get
  - net/devlink/leftover.c:devlink_param_unregister
  - net/devlink/leftover.c:devlink_nl_cmd_region_read_dumpit
  - net/devlink/leftover.c:devlink_nl_cmd_region_new
  - net/devlink/leftover.c:devlink_nl_cmd_region_new
  - net/devlink/leftover.c:devlink_nl_cmd_region_del
  - net/devlink/leftover.c:devlink_nl_cmd_region_get_doit
  - net/devlink/leftover.c:__devlink_region_snapshot_create
  - net/devlink/leftover.c:__devlink_snapshot_id_decrement
  - net/devlink/leftover.c:devlink_rate_get_from_info
  - net/devlink/leftover.c:devlink_port_get_from_info
```
**Symbols:**

```
ffffffff820c87c0-ffffffff820c88a5: xa_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *xa_load(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff821a3140)
Location: lib/xarray.c:1454
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_access
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_load_page
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/main.c:arch_memory_failure
  - arch/x86/kernel/cpu/sgx/main.c:arch_is_platform_page
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
  - kernel/irq/msi.c:msi_domain_populate_irqs
  - kernel/irq/msi.c:msi_domain_get_virq
  - mm/filemap.c:__filemap_add_folio
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_unbounded
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_reparent_list_lrus
  - mm/list_lru.c:memcg_reparent_list_lrus
  - mm/list_lru.c:__list_lru_walk_one
  - mm/list_lru.c:list_lru_count_one
  - mm/list_lru.c:list_lru_putback
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
  - mm/vmalloc.c:vmap_ram_vread_iter
  - mm/vmalloc.c:vb_free
  - mm/swap_state.c:get_shadow_from_swap_cache
  - mm/memremap.c:get_dev_pagemap
  - fs/mpage.c:mpage_readahead
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - security/apparmor/secid.c:apparmor_secid_to_secctx
  - block/bio.c:bioset_init
  - block/bio.c:bioset_exit
  - block/blk-mq.c:blk_mq_poll
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/genhd.c:part_devt
  - block/partitions/core.c:bdev_resize_partition
  - block/partitions/core.c:bdev_del_partition
  - block/partitions/core.c:add_partition
  - io_uring/io_uring.c:io_init_req
  - io_uring/tctx.c:__io_uring_add_tctx_node
  - io_uring/kbuf.c:io_pbuf_get_address
  - io_uring/kbuf.c:io_register_pbuf_status
  - io_uring/kbuf.c:io_unregister_pbuf_ring
  - io_uring/kbuf.c:io_register_pbuf_ring
  - io_uring/kbuf.c:io_provide_buffers
  - io_uring/kbuf.c:io_remove_buffers
  - io_uring/kbuf.c:io_buffer_select
  - io_uring/kbuf.c:io_kbuf_recycle_legacy
  - drivers/pci/p2pdma.c:pci_p2pdma_map_segment
  - drivers/xen/grant-dma-ops.c:xen_virtio_restricted_mem_acc
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_unmap_page
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_map_page
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_free
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc
  - drivers/iommu/intel/iommu.c:domain_setup_first_level
  - drivers/iommu/intel/iommu.c:domain_context_clear_one
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:domain_detach_iommu
  - drivers/iommu/intel/iommu.c:domain_attach_iommu
  - drivers/iommu/intel/iommu.c:intel_flush_iotlb_all
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
  - drivers/iommu/intel/iommu.c:domain_flush_pasid_iotlb
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/nested.c:intel_nested_cache_invalidate_user
  - drivers/iommu/intel/svm.c:intel_drain_pasid_prq
  - drivers/iommu/intel/svm.c:intel_svm_remove_dev_pasid
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev_pasid
  - drivers/base/memory.c:memblk_nr_poison_sub
  - drivers/base/memory.c:memblk_nr_poison_inc
  - drivers/base/memory.c:memory_group_find_by_id
  - drivers/base/memory.c:memory_group_unregister
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:add_memory_block
  - drivers/base/memory.c:find_memory_block
  - drivers/dax/super.c:fs_dax_get_by_bdev
  - drivers/dpll/dpll_core.c:dpll_pin_on_pin_priv
  - drivers/dpll/dpll_core.c:dpll_pin_on_dpll_priv
  - drivers/dpll/dpll_core.c:dpll_device_get_by_id
  - drivers/dpll/dpll_netlink.c:dpll_pin_pre_doit
  - drivers/dpll/dpll_netlink.c:dpll_pin_parent_pin_set
  - drivers/dpll/dpll_netlink.c:dpll_pin_parent_pin_set
  - drivers/dpll/dpll_netlink.c:dpll_pin_parent_device_set
  - drivers/dpll/dpll_netlink.c:dpll_pin_parent_device_set
  - drivers/dpll/dpll_netlink.c:dpll_pin_parent_device_set
  - drivers/dpll/dpll_netlink.c:dpll_pin_parent_device_set
  - drivers/dpll/dpll_netlink.c:dpll_pin_parent_device_set
  - drivers/dpll/dpll_netlink.c:dpll_pin_parent_device_set
  - drivers/dpll/dpll_netlink.c:dpll_pin_parent_device_set
  - drivers/dpll/dpll_netlink.c:dpll_pin_parent_device_set
  - drivers/dpll/dpll_netlink.c:dpll_pin_parent_device_set
  - net/core/page_pool_user.c:netdev_nl_page_pool_get_do
  - net/sched/cls_api.c:tcf_classify
  - net/netlink/genetlink.c:genl_sk_priv_get
  - net/devlink/port.c:devlink_port_rel_cleanup_cb
  - net/devlink/port.c:devlink_port_rel_notify_cb
  - net/devlink/port.c:devlink_port_get_from_info
  - net/devlink/param.c:devl_param_value_changed
  - net/devlink/param.c:devl_param_driverinit_value_set
  - net/devlink/param.c:devl_param_driverinit_value_get
  - net/devlink/param.c:devlink_param_unregister
  - net/devlink/region.c:devlink_nl_region_new_doit
  - net/devlink/region.c:__devlink_region_snapshot_create
  - net/devlink/region.c:__devlink_snapshot_id_decrement
```
**Symbols:**

```
ffffffff821a3140-ffffffff821a3225: xa_load (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void *xa_load(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffff800010d99be0)
Location: lib/xarray.c:1296
Inline: False
Direct callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/shmem.c:shmem_confirm_swap
```
**Symbols:**

```
ffff800010d99be0-ffff800010d99c58: xa_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *xa_load(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c0e96704)
Location: lib/xarray.c:1296
Inline: False
Direct callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
```
**Symbols:**

```
c0e96704-c0e967a0: xa_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *xa_load(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c000000000edfbe0)
Location: lib/xarray.c:1296
Inline: False
Direct callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/memremap.c:get_dev_pagemap
```
**Symbols:**

```
c000000000edfbe0-c000000000edfc90: xa_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *xa_load(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffe0008c2816)
Location: lib/xarray.c:1296
Inline: False
Direct callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/shmem.c:shmem_confirm_swap
```
**Symbols:**

```
ffffffe0008c2816-ffffffe0008c2880: xa_load (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void *xa_load(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a5d7a0)
Location: lib/xarray.c:1296
Inline: False
Direct callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/shmem.c:shmem_confirm_swap
  - mm/memremap.c:get_dev_pagemap
```
**Symbols:**

```
ffffffff81a5d7a0-ffffffff81a5d81b: xa_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *xa_load(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a1a870)
Location: lib/xarray.c:1296
Inline: False
Direct callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/shmem.c:shmem_confirm_swap
  - mm/memremap.c:get_dev_pagemap
```
**Symbols:**

```
ffffffff81a1a870-ffffffff81a1a8eb: xa_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *xa_load(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ac9b90)
Location: lib/xarray.c:1296
Inline: False
Direct callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/shmem.c:shmem_confirm_swap
  - mm/memremap.c:get_dev_pagemap
```
**Symbols:**

```
ffffffff81ac9b90-ffffffff81ac9c0b: xa_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *xa_load(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ad60e0)
Location: lib/xarray.c:1296
Inline: False
Direct callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/shmem.c:shmem_confirm_swap
  - mm/memremap.c:get_dev_pagemap
```
**Symbols:**

```
ffffffff81ad60e0-ffffffff81ad6174: xa_load (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
