# Function: <code>might_alloc</code>

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
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812e3bd6)
Location: include/linux/sched/mm.h:192
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
In mm/backing-dev.c (ffffffff81287bb5)
Location: include/linux/sched/mm.h:196
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/dmapool.c (ffffffff812d5675)
Location: include/linux/sched/mm.h:196
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In mm/slub.c (ffffffff812eb4a6)
Location: include/linux/sched/mm.h:196
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
In mm/backing-dev.c (ffffffff812c7355)
Location: include/linux/sched/mm.h:196
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/dmapool.c (ffffffff8131b495)
Location: include/linux/sched/mm.h:196
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In mm/slub.c (ffffffff81338bf0)
Location: include/linux/sched/mm.h:196
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
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
In mm/backing-dev.c (ffffffff81323ff5)
Location: include/linux/sched/mm.h:269
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/dmapool.c (ffffffff81386c95)
Location: include/linux/sched/mm.h:269
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In mm/slub.c (ffffffff813aa7c2)
Location: include/linux/sched/mm.h:269
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81090bb8)
Location: include/linux/sched/mm.h:269
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81092961)
Location: include/linux/sched/mm.h:269
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In kernel/irq/msi.c (ffffffff811a4181)
Location: include/linux/sched/mm.h:269
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_insert_desc
  - kernel/irq/msi.c:msi_insert_desc
```
```
In mm/mempool.c (ffffffff81360fc5)
Location: include/linux/sched/mm.h:269
Inline: True
Inline callers:
  - mm/mempool.c:mempool_alloc
```
```
In mm/shmem.c (0)
Location: include/linux/sched/mm.h:269
Inline: True
```
```
In mm/backing-dev.c (ffffffff813988c5)
Location: include/linux/sched/mm.h:269
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/vmalloc.c (ffffffff813e0194)
Location: include/linux/sched/mm.h:269
Inline: True
```
```
In mm/page_alloc.c (ffffffff813ec8ca)
Location: include/linux/sched/mm.h:269
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
```
```
In mm/dmapool.c (ffffffff81404b65)
Location: include/linux/sched/mm.h:269
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In mm/slub.c (ffffffff8142cc19)
Location: include/linux/sched/mm.h:269
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:__kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc
```
```
In block/blk-mq.c (ffffffff81740d18)
Location: include/linux/sched/mm.h:269
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_hctx
```
```
In block/genhd.c (ffffffff817528a5)
Location: include/linux/sched/mm.h:269
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/partitions/core.c (ffffffff817547e8)
Location: include/linux/sched/mm.h:269
Inline: True
Inline callers:
  - block/partitions/core.c:add_partition
```
```
In io_uring/io_uring.c (ffffffff8178c3cf)
Location: include/linux/sched/mm.h:269
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_register
```
```
In drivers/pci/doe.c (ffffffff819205b8)
Location: include/linux/sched/mm.h:269
Inline: True
Inline callers:
  - drivers/pci/doe.c:pcim_doe_create_mb
```
```
In drivers/iommu/intel/iommu.c (0)
Location: include/linux/sched/mm.h:269
Inline: True
```
```
In drivers/iommu/intel/svm.c (0)
Location: include/linux/sched/mm.h:269
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff81acf34d)
Location: include/linux/sched/mm.h:269
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_attach_device_pasid
```
```
In drivers/iommu/ioasid.c (0)
Location: include/linux/sched/mm.h:269
Inline: True
```
```
In drivers/base/memory.c (ffffffff81b1602d)
Location: include/linux/sched/mm.h:269
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_group_register
```
```
In drivers/dax/super.c (ffffffff81b65a82)
Location: include/linux/sched/mm.h:269
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_add_host
```
```
In drivers/dma-buf/dma-heap.c (ffffffff81b6f954)
Location: include/linux/sched/mm.h:269
Inline: True
Inline callers:
  - drivers/dma-buf/dma-heap.c:dma_heap_add
```
```
In drivers/opp/core.c (ffffffff81d29bb6)
Location: include/linux/sched/mm.h:269
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_set_config
```
```
In net/core/devlink.c (ffffffff81e2f486)
Location: include/linux/sched/mm.h:269
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_region_snapshot_id_get
  - net/core/devlink.c:devl_port_register
  - net/core/devlink.c:devlink_alloc_ns
  - net/core/devlink.c:devlink_nl_cmd_region_new
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81093ae8)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81095894)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In kernel/irq/msi.c (ffffffff811b63f7)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_insert_desc
  - kernel/irq/msi.c:msi_insert_desc
```
```
In mm/mempool.c (ffffffff81393385)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - mm/mempool.c:mempool_alloc
```
```
In mm/shmem.c (0)
Location: include/linux/sched/mm.h:301
Inline: True
```
```
In mm/backing-dev.c (ffffffff813cb825)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/vmalloc.c (ffffffff81414f48)
Location: include/linux/sched/mm.h:301
Inline: True
```
```
In mm/page_alloc.c (ffffffff8142183c)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
```
```
In mm/dmapool.c (ffffffff814380e5)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In mm/slub.c (ffffffff81462229)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:__kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc
```
```
In block/blk-mq.c (ffffffff8177cfd8)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_hctx
```
```
In block/genhd.c (ffffffff8178ea65)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/partitions/core.c (ffffffff817908ea)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - block/partitions/core.c:add_partition
```
```
In io_uring/io_uring.c (ffffffff817cd5e3)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_register
```
```
In drivers/pci/doe.c (ffffffff81963e3e)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - drivers/pci/doe.c:pci_doe_init
  - drivers/pci/doe.c:pci_doe_create_mb
```
```
In drivers/iommu/intel/iommu.c (0)
Location: include/linux/sched/mm.h:301
Inline: True
```
```
In drivers/iommu/intel/svm.c (0)
Location: include/linux/sched/mm.h:301
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff81b1dfdd)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_attach_device_pasid
```
```
In drivers/base/memory.c (ffffffff81b64d9d)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_group_register
```
```
In drivers/dax/super.c (ffffffff81bb90a2)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_add_host
```
```
In drivers/dma-buf/dma-heap.c (ffffffff81bc3284)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - drivers/dma-buf/dma-heap.c:dma_heap_add
```
```
In drivers/opp/core.c (ffffffff81d92dcd)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_set_config
```
```
In net/sched/cls_api.c (ffffffff81eb66e0)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_init_ex
```
```
In net/devlink/leftover.c (ffffffff82032f76)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_region_snapshot_id_get
  - net/devlink/leftover.c:devl_params_register
  - net/devlink/leftover.c:devl_port_register_with_ops
  - net/devlink/leftover.c:devlink_nl_cmd_region_new
```
```
In net/devlink/core.c (ffffffff82041f6d)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - net/devlink/core.c:devlink_alloc_ns
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109afa0)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109cdd4)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In kernel/irq/msi.c (ffffffff811c62a7)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_insert_desc
  - kernel/irq/msi.c:msi_insert_desc
```
```
In mm/mempool.c (ffffffff813bd035)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - mm/mempool.c:mempool_alloc
```
```
In mm/shmem.c (0)
Location: include/linux/sched/mm.h:301
Inline: True
```
```
In mm/backing-dev.c (ffffffff813f6175)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/vmalloc.c (ffffffff81441a17)
Location: include/linux/sched/mm.h:301
Inline: True
```
```
In mm/page_alloc.c (ffffffff8144e66c)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
```
```
In mm/slub.c (ffffffff8145e747)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmalloc_node_trace
  - mm/slub.c:kmalloc_trace
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc
```
```
In mm/dmapool.c (ffffffff81471a45)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In fs/libfs.c (ffffffff8152369c)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - fs/libfs.c:simple_offset_add
```
```
In fs/buffer.c (ffffffff81541546)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - fs/buffer.c:__bread_gfp
```
```
In block/blk-mq.c (ffffffff817bf368)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_hctx
```
```
In block/genhd.c (ffffffff817d1354)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/partitions/core.c (ffffffff817d4154)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - block/partitions/core.c:add_partition
```
```
In io_uring/register.c (ffffffff8182bbb0)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - io_uring/register.c:__io_uring_register
```
```
In drivers/pci/doe.c (ffffffff819ad4ee)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - drivers/pci/doe.c:pci_doe_init
  - drivers/pci/doe.c:pci_doe_create_mb
```
```
In drivers/iommu/intel/iommu.c (0)
Location: include/linux/sched/mm.h:301
Inline: True
```
```
In drivers/iommu/intel/svm.c (0)
Location: include/linux/sched/mm.h:301
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff81b73f8a)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_attach_device_pasid
```
```
In drivers/base/memory.c (ffffffff81bb8afc)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_group_register
```
```
In drivers/dax/super.c (ffffffff81c0d702)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_add_host
```
```
In drivers/dma-buf/dma-heap.c (ffffffff81c17a23)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - drivers/dma-buf/dma-heap.c:dma_heap_add
```
```
In drivers/opp/core.c (ffffffff81e4a747)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_set_config
```
```
In drivers/dpll/dpll_core.c (ffffffff81eb6bd6)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - drivers/dpll/dpll_core.c:dpll_pin_get
  - drivers/dpll/dpll_core.c:dpll_device_get
  - drivers/dpll/dpll_core.c:dpll_xa_ref_dpll_add
  - drivers/dpll/dpll_core.c:dpll_xa_ref_pin_add
```
```
In net/core/dev.c (ffffffff81ef6ec1)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
```
```
In net/core/page_pool_user.c (ffffffff81f460cb)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - net/core/page_pool_user.c:page_pool_list
```
```
In net/sched/cls_api.c (ffffffff81f794fe)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_init_ex
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/netlink/genetlink.c (ffffffff81f8fdb0)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_sk_priv_get
```
```
In net/devlink/core.c (ffffffff820fea8d)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - net/devlink/core.c:devlink_alloc_ns
  - net/devlink/core.c:devlink_rel_nested_in_add
```
```
In net/devlink/dev.c (ffffffff821021a7)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - net/devlink/dev.c:devl_nested_devlink_set
```
```
In net/devlink/port.c (ffffffff82107238)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - net/devlink/port.c:devl_port_register_with_ops
```
```
In net/devlink/param.c (ffffffff8210eb63)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - net/devlink/param.c:devl_params_register
```
```
In net/devlink/region.c (ffffffff8210f566)
Location: include/linux/sched/mm.h:301
Inline: True
Inline callers:
  - net/devlink/region.c:devlink_region_snapshot_id_get
  - net/devlink/region.c:devlink_nl_region_new_doit
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
