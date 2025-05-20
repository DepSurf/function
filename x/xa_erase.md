# Function: <code>xa_erase</code>

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
void *xa_erase(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a193d0)
Location: lib/xarray.c:1324
Inline: False
```
**Symbols:**

```
ffffffff81a193d0-ffffffff81a19402: xa_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *xa_erase(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a89120)
Location: lib/xarray.c:1342
Inline: False
```
**Symbols:**

```
ffffffff81a89120-ffffffff81a89154: xa_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *xa_erase(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ac03c0)
Location: lib/xarray.c:1353
Inline: False
```
**Symbols:**

```
ffffffff81ac03c0-ffffffff81ac03f4: xa_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *xa_erase(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff815fc680)
Location: lib/xarray.c:1355
Inline: False
Direct callers:
  - drivers/iommu/ioasid.c:ioasid_free
  - drivers/iommu/ioasid.c:default_free
  - drivers/base/memory.c:unregister_memory
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - net/core/devlink.c:__devlink_snapshot_id_decrement
```
**Symbols:**

```
ffffffff815fc680-ffffffff815fc738: xa_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *xa_erase(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff816212a0)
Location: lib/xarray.c:1505
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - fs/io_uring.c:io_uring_flush
  - fs/io_uring.c:io_uring_remove_task_files
  - drivers/iommu/ioasid.c:ioasid_put
  - drivers/iommu/ioasid.c:default_free
  - drivers/base/memory.c:unregister_memory
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - net/core/devlink.c:__devlink_snapshot_id_decrement
```
**Symbols:**

```
ffffffff816212a0-ffffffff81621358: xa_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *xa_erase(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81604480)
Location: lib/xarray.c:1506
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_uring_del_task_file
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_provide_buffers
  - block/bio.c:bioset_exit
  - block/partitions/core.c:delete_partition
  - drivers/iommu/ioasid.c:ioasid_put
  - drivers/iommu/ioasid.c:default_free
  - drivers/base/memory.c:unregister_memory
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - net/core/devlink.c:__devlink_snapshot_id_decrement
```
**Symbols:**

```
ffffffff81604480-ffffffff81604538: xa_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *xa_erase(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81672d70)
Location: lib/xarray.c:1506
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
  - mm/vmalloc.c:free_vmap_block
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_uring_del_tctx_node
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_provide_buffers
  - block/bio.c:bioset_exit
  - block/partitions/core.c:delete_partition
  - drivers/iommu/intel/svm.c:intel_svm_bind_mm
  - drivers/iommu/intel/svm.c:intel_svm_unbind_gpasid
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
  - drivers/iommu/ioasid.c:ioasid_put
  - drivers/iommu/ioasid.c:default_free
  - drivers/base/memory.c:memory_group_unregister
  - drivers/base/memory.c:unregister_memory
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - net/core/devlink.c:devlink_free
  - net/core/devlink.c:__devlink_snapshot_id_decrement
```
**Symbols:**

```
ffffffff81672d70-ffffffff81672e28: xa_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *xa_erase(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8178d180)
Location: lib/xarray.c:1513
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
  - kernel/irq/msi.c:msi_free_msi_descs_range
  - block/bio.c:bioset_exit
  - block/blk-mq.c:blk_mq_exit_hctx
  - block/genhd.c:__alloc_disk_node
  - block/partitions/core.c:delete_partition
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:io_uring_del_tctx_node
  - io_uring/io_uring.c:io_ring_ctx_wait_and_kill
  - io_uring/io_uring.c:io_ring_ctx_free
  - drivers/iommu/intel/svm.c:intel_svm_bind_mm
  - drivers/iommu/ioasid.c:ioasid_free
  - drivers/iommu/ioasid.c:default_free
  - drivers/base/memory.c:memory_group_unregister
  - drivers/base/memory.c:remove_memory_block
  - drivers/dax/super.c:dax_remove_host
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - net/core/devlink.c:devlink_free
  - net/core/devlink.c:__devlink_snapshot_id_decrement
```
**Symbols:**

```
ffffffff8178d180-ffffffff8178d1b8: xa_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *xa_erase(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8204a7b0)
Location: lib/xarray.c:1513
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_remove_pages
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
  - kernel/irq/msi.c:msi_domain_free_descs
  - block/bio.c:bioset_exit
  - block/blk-mq.c:blk_mq_exit_hctx
  - block/genhd.c:__alloc_disk_node
  - block/partitions/core.c:delete_partition
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:io_ring_ctx_wait_and_kill
  - io_uring/tctx.c:io_uring_del_tctx_node
  - io_uring/kbuf.c:io_unregister_pbuf_ring
  - io_uring/kbuf.c:io_destroy_buffers
  - drivers/iommu/intel/iommu.c:domain_detach_iommu
  - drivers/iommu/intel/svm.c:intel_svm_bind_mm
  - drivers/iommu/iommu.c:iommu_detach_device_pasid
  - drivers/iommu/iommu.c:iommu_attach_device_pasid
  - drivers/iommu/ioasid.c:ioasid_free
  - drivers/iommu/ioasid.c:default_free
  - drivers/base/memory.c:memory_group_unregister
  - drivers/base/memory.c:remove_memory_block
  - drivers/dax/super.c:dax_remove_host
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - drivers/opp/core.c:devm_pm_opp_set_config
  - net/core/devlink.c:devl_port_unregister
  - net/core/devlink.c:devlink_free
  - net/core/devlink.c:devlink_alloc_ns
```
**Symbols:**

```
ffffffff8204a7b0-ffffffff8204a7e8: xa_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *xa_erase(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff820c90b0)
Location: lib/xarray.c:1511
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_remove_pages
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
  - kernel/irq/msi.c:msi_domain_free_descs
  - mm/vmalloc.c:free_vmap_block
  - block/bio.c:bioset_exit
  - block/blk-mq.c:blk_mq_exit_hctx
  - block/genhd.c:__alloc_disk_node
  - block/partitions/core.c:bdev_disk_changed
  - block/partitions/core.c:bdev_del_partition
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:io_ring_ctx_wait_and_kill
  - io_uring/tctx.c:io_uring_del_tctx_node
  - io_uring/kbuf.c:io_unregister_pbuf_ring
  - io_uring/kbuf.c:io_destroy_buffers
  - drivers/iommu/intel/iommu.c:domain_detach_iommu
  - drivers/iommu/intel/svm.c:intel_svm_bind_mm
  - drivers/iommu/iommu.c:iommu_detach_device_pasid
  - drivers/iommu/iommu.c:iommu_attach_device_pasid
  - drivers/base/memory.c:memory_group_unregister
  - drivers/base/memory.c:remove_memory_block
  - drivers/dax/super.c:dax_remove_host
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - drivers/opp/core.c:devm_pm_opp_set_config
  - net/sched/cls_api.c:tcf_exts_destroy
  - net/devlink/leftover.c:devlink_param_unregister
  - net/devlink/leftover.c:devl_port_unregister
  - net/devlink/core.c:devlink_free
```
**Symbols:**

```
ffffffff820c90b0-ffffffff820c90e8: xa_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *xa_erase(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff821a3a30)
Location: lib/xarray.c:1511
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_remove_pages
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
  - kernel/irq/msi.c:msi_domain_free_descs
  - mm/vmalloc.c:free_vmap_block
  - fs/libfs.c:simple_offset_rename_exchange
  - fs/libfs.c:simple_offset_rename_exchange
  - fs/libfs.c:simple_offset_rename_exchange
  - fs/libfs.c:simple_offset_rename_exchange
  - fs/libfs.c:simple_offset_rename_exchange
  - block/bio.c:bioset_exit
  - block/blk-mq.c:blk_mq_exit_hctx
  - block/genhd.c:__alloc_disk_node
  - block/partitions/core.c:bdev_disk_changed
  - block/partitions/core.c:bdev_del_partition
  - io_uring/tctx.c:io_uring_del_tctx_node
  - io_uring/kbuf.c:io_unregister_pbuf_ring
  - io_uring/kbuf.c:io_destroy_buffers
  - io_uring/register.c:io_unregister_personality
  - drivers/iommu/intel/iommu.c:domain_detach_iommu
  - drivers/iommu/intel/svm.c:intel_svm_remove_dev_pasid
  - drivers/iommu/iommu.c:iommu_detach_device_pasid
  - drivers/iommu/iommu.c:iommu_attach_device_pasid
  - drivers/base/memory.c:memory_group_unregister
  - drivers/base/memory.c:remove_memory_block
  - drivers/dax/super.c:dax_remove_host
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - drivers/opp/core.c:devm_pm_opp_set_config
  - drivers/dpll/dpll_core.c:dpll_pin_put
  - drivers/dpll/dpll_core.c:dpll_device_put
  - drivers/dpll/dpll_core.c:dpll_xa_ref_dpll_add
  - drivers/dpll/dpll_core.c:dpll_xa_ref_pin_add
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:unlist_netdevice
  - net/core/page_pool_user.c:page_pool_unlist
  - net/sched/cls_api.c:tcf_exts_destroy
  - net/sched/cls_api.c:tcf_block_put_ext
  - net/netlink/genetlink.c:genl_release
  - net/devlink/core.c:devlink_free
  - net/devlink/core.c:__devlink_rel_put
  - net/devlink/dev.c:devlink_rel_cleanup_cb
  - net/devlink/port.c:devl_port_unregister
  - net/devlink/param.c:devlink_param_unregister
```
**Symbols:**

```
ffffffff821a3a30-ffffffff821a3a68: xa_erase (STB_GLOBAL)
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
void *xa_erase(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffff800010d9b190)
Location: lib/xarray.c:1353
Inline: False
```
**Symbols:**

```
ffff800010d9b190-ffff800010d9b220: xa_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *xa_erase(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c0e97a3c)
Location: lib/xarray.c:1353
Inline: False
```
**Symbols:**

```
c0e97a3c-c0e97a7c: xa_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *xa_erase(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c000000000ee1530)
Location: lib/xarray.c:1353
Inline: False
```
**Symbols:**

```
c000000000ee1530-c000000000ee15d8: xa_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *xa_erase(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffe0008c3486)
Location: lib/xarray.c:1353
Inline: False
```
**Symbols:**

```
ffffffe0008c3486-ffffffe0008c34f6: xa_erase (STB_GLOBAL)
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
void *xa_erase(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a5f210)
Location: lib/xarray.c:1353
Inline: False
```
**Symbols:**

```
ffffffff81a5f210-ffffffff81a5f244: xa_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *xa_erase(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a1c2e0)
Location: lib/xarray.c:1353
Inline: False
```
**Symbols:**

```
ffffffff81a1c2e0-ffffffff81a1c314: xa_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *xa_erase(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81acb600)
Location: lib/xarray.c:1353
Inline: False
```
**Symbols:**

```
ffffffff81acb600-ffffffff81acb634: xa_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *xa_erase(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ad72e0)
Location: lib/xarray.c:1353
Inline: False
```
**Symbols:**

```
ffffffff81ad72e0-ffffffff81ad7312: xa_erase (STB_GLOBAL)
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
