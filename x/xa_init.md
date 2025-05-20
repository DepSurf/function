# Function: <code>xa_init</code>

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
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff810656df)
Location: include/linux/xarray.h:389
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
```
```
In fs/io_uring.c (ffffffff8138a857)
Location: include/linux/xarray.h:389
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_alloc_task_context
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
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff81065daf)
Location: include/linux/xarray.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81069854)
Location: include/linux/xarray.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_open
```
```
In fs/io_uring.c (ffffffff81392489)
Location: include/linux/xarray.h:391
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_alloc_task_context
```
```
In block/genhd.c (ffffffff8157e8ef)
Location: include/linux/xarray.h:391
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
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
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff8106fecf)
Location: include/linux/xarray.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81073f34)
Location: include/linux/xarray.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_open
```
```
In fs/io_uring.c (ffffffff813e04b6)
Location: include/linux/xarray.h:391
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_alloc_task_context
```
```
In block/genhd.c (ffffffff815e3e30)
Location: include/linux/xarray.h:391
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
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
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff8107d7e1)
Location: include/linux/xarray.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81082464)
Location: include/linux/xarray.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_open
```
```
In kernel/irq/msi.c (ffffffff8116f08c)
Location: include/linux/xarray.h:392
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_setup_device_data
```
```
In block/blk-mq.c (ffffffff8168a995)
Location: include/linux/xarray.h:392
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/genhd.c (ffffffff816930fd)
Location: include/linux/xarray.h:392
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In io_uring/io_uring.c (ffffffff81e8ec79)
Location: include/linux/xarray.h:392
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_alloc_task_context
  - io_uring/io_uring.c:io_ring_ctx_alloc
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
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff8108ed41)
Location: include/linux/xarray.h:393
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81094ed4)
Location: include/linux/xarray.h:393
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_open
```
```
In block/blk-mq.c (ffffffff81749b78)
Location: include/linux/xarray.h:393
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/genhd.c (ffffffff81752891)
Location: include/linux/xarray.h:393
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In io_uring/io_uring.c (ffffffff81789fb9)
Location: include/linux/xarray.h:393
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_ctx_alloc
```
```
In io_uring/tctx.c (ffffffff8179bb44)
Location: include/linux/xarray.h:393
Inline: True
Inline callers:
  - io_uring/tctx.c:io_uring_alloc_task_context
```
```
In drivers/pci/p2pdma.c (ffffffff8191c40d)
Location: include/linux/xarray.h:393
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
```
```
In drivers/pci/doe.c (ffffffff8192043f)
Location: include/linux/xarray.h:393
Inline: True
Inline callers:
  - drivers/pci/doe.c:pcim_doe_create_mb
```
```
In drivers/iommu/intel/iommu.c (ffffffff81ac0e46)
Location: include/linux/xarray.h:393
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:alloc_domain
```
```
In drivers/iommu/iommu.c (ffffffff81acdeec)
Location: include/linux/xarray.h:393
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_alloc
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
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff81091c31)
Location: include/linux/xarray.h:393
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81097e54)
Location: include/linux/xarray.h:393
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_open
```
```
In mm/vmalloc.c (ffffffff836e6191)
Location: include/linux/xarray.h:393
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_init
```
```
In block/blk-mq.c (ffffffff8178627c)
Location: include/linux/xarray.h:393
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/genhd.c (ffffffff8178ea51)
Location: include/linux/xarray.h:393
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In io_uring/io_uring.c (ffffffff817ca8c9)
Location: include/linux/xarray.h:393
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_ctx_alloc
```
```
In io_uring/tctx.c (ffffffff817dcc74)
Location: include/linux/xarray.h:393
Inline: True
Inline callers:
  - io_uring/tctx.c:io_uring_alloc_task_context
```
```
In drivers/pci/p2pdma.c (ffffffff8195fa0f)
Location: include/linux/xarray.h:393
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
```
```
In drivers/pci/doe.c (ffffffff81963dd5)
Location: include/linux/xarray.h:393
Inline: True
Inline callers:
  - drivers/pci/doe.c:pci_doe_init
  - drivers/pci/doe.c:pci_doe_create_mb
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b0d6b6)
Location: include/linux/xarray.h:393
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:alloc_domain
```
```
In drivers/iommu/iommu.c (ffffffff81b1ca7c)
Location: include/linux/xarray.h:393
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_alloc
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
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff81099010)
Location: include/linux/xarray.h:393
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff8109f3f3)
Location: include/linux/xarray.h:393
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_open
```
```
In mm/vmalloc.c (ffffffff839189f1)
Location: include/linux/xarray.h:393
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_init
```
```
In block/blk-mq.c (ffffffff817c8958)
Location: include/linux/xarray.h:393
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/genhd.c (ffffffff817d1340)
Location: include/linux/xarray.h:393
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In io_uring/io_uring.c (ffffffff8180e1d8)
Location: include/linux/xarray.h:393
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_ctx_alloc
```
```
In io_uring/tctx.c (ffffffff81820f56)
Location: include/linux/xarray.h:393
Inline: True
Inline callers:
  - io_uring/tctx.c:io_uring_alloc_task_context
```
```
In drivers/pci/p2pdma.c (ffffffff819a9096)
Location: include/linux/xarray.h:393
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
```
```
In drivers/pci/doe.c (ffffffff819ad485)
Location: include/linux/xarray.h:393
Inline: True
Inline callers:
  - drivers/pci/doe.c:pci_doe_init
  - drivers/pci/doe.c:pci_doe_create_mb
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b62d91)
Location: include/linux/xarray.h:393
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:alloc_domain
```
```
In drivers/iommu/intel/nested.c (ffffffff81b6968e)
Location: include/linux/xarray.h:393
Inline: True
Inline callers:
  - drivers/iommu/intel/nested.c:intel_nested_domain_alloc
```
```
In drivers/iommu/iommu.c (ffffffff81b72f9b)
Location: include/linux/xarray.h:393
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_alloc
```
```
In net/sched/cls_api.c (ffffffff81f7cc54)
Location: include/linux/xarray.h:393
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/netlink/genetlink.c (ffffffff81f8fc06)
Location: include/linux/xarray.h:393
Inline: True
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
