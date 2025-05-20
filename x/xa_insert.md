# Function: <code>xa_insert</code>

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
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8106781a)
Location: include/linux/xarray.h:765
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In mm/vmalloc.c (ffffffff812b5a0c)
Location: include/linux/xarray.h:765
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
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff810678fc)
Location: include/linux/xarray.h:767
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In mm/vmalloc.c (ffffffff812bb0fc)
Location: include/linux/xarray.h:767
Inline: True
```
```
In fs/io_uring.c (ffffffff8139c05b)
Location: include/linux/xarray.h:767
Inline: True
Inline callers:
  - fs/io_uring.c:io_provide_buffers
```
```
In block/genhd.c (ffffffff8157e904)
Location: include/linux/xarray.h:767
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/partitions/core.c (ffffffff815813a3)
Location: include/linux/xarray.h:767
Inline: True
Inline callers:
  - block/partitions/core.c:add_partition
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
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81071cdc)
Location: include/linux/xarray.h:767
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In mm/vmalloc.c (ffffffff812fd706)
Location: include/linux/xarray.h:767
Inline: True
```
```
In fs/io_uring.c (ffffffff813eacb6)
Location: include/linux/xarray.h:767
Inline: True
Inline callers:
  - fs/io_uring.c:io_provide_buffers
```
```
In block/genhd.c (ffffffff815e3e4a)
Location: include/linux/xarray.h:767
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/partitions/core.c (ffffffff815e6702)
Location: include/linux/xarray.h:767
Inline: True
Inline callers:
  - block/partitions/core.c:add_partition
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
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81080052)
Location: include/linux/xarray.h:768
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In kernel/irq/msi.c (ffffffff8116ef6e)
Location: include/linux/xarray.h:768
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_add_simple_msi_descs
  - kernel/irq/msi.c:msi_add_msi_desc
```
```
In mm/vmalloc.c (ffffffff8136464f)
Location: include/linux/xarray.h:768
Inline: True
```
```
In block/blk-mq.c (ffffffff81683688)
Location: include/linux/xarray.h:768
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_hctx
```
```
In block/genhd.c (ffffffff81693114)
Location: include/linux/xarray.h:768
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/partitions/core.c (ffffffff81695628)
Location: include/linux/xarray.h:768
Inline: True
Inline callers:
  - block/partitions/core.c:add_partition
```
```
In drivers/dax/super.c (ffffffff819e9399)
Location: include/linux/xarray.h:768
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_add_host
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
Location: include/linux/xarray.h:774
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81092961)
Location: include/linux/xarray.h:774
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In kernel/irq/msi.c (ffffffff811a4143)
Location: include/linux/xarray.h:774
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_insert_desc
```
```
In mm/vmalloc.c (ffffffff813e0194)
Location: include/linux/xarray.h:774
Inline: True
```
```
In block/blk-mq.c (ffffffff81740d18)
Location: include/linux/xarray.h:774
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_hctx
```
```
In block/genhd.c (ffffffff817528a5)
Location: include/linux/xarray.h:774
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/partitions/core.c (ffffffff817547e8)
Location: include/linux/xarray.h:774
Inline: True
Inline callers:
  - block/partitions/core.c:add_partition
```
```
In drivers/pci/doe.c (ffffffff819205b8)
Location: include/linux/xarray.h:774
Inline: True
Inline callers:
  - drivers/pci/doe.c:pcim_doe_create_mb
```
```
In drivers/dax/super.c (ffffffff81b65a82)
Location: include/linux/xarray.h:774
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_add_host
```
```
In net/core/devlink.c (ffffffff81e3dee6)
Location: include/linux/xarray.h:774
Inline: True
Inline callers:
  - net/core/devlink.c:devl_port_register
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
Location: include/linux/xarray.h:774
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81095894)
Location: include/linux/xarray.h:774
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In kernel/irq/msi.c (ffffffff811b63b9)
Location: include/linux/xarray.h:774
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_insert_desc
```
```
In mm/vmalloc.c (ffffffff81414f48)
Location: include/linux/xarray.h:774
Inline: True
```
```
In block/blk-mq.c (ffffffff8177cfd8)
Location: include/linux/xarray.h:774
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_hctx
```
```
In block/genhd.c (ffffffff8178ea65)
Location: include/linux/xarray.h:774
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/partitions/core.c (ffffffff817908ea)
Location: include/linux/xarray.h:774
Inline: True
Inline callers:
  - block/partitions/core.c:add_partition
```
```
In drivers/pci/doe.c (ffffffff81963e3e)
Location: include/linux/xarray.h:774
Inline: True
Inline callers:
  - drivers/pci/doe.c:pci_doe_init
  - drivers/pci/doe.c:pci_doe_create_mb
```
```
In drivers/dax/super.c (ffffffff81bb90a2)
Location: include/linux/xarray.h:774
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_add_host
```
```
In net/devlink/leftover.c (ffffffff8203b814)
Location: include/linux/xarray.h:774
Inline: True
Inline callers:
  - net/devlink/leftover.c:devl_params_register
  - net/devlink/leftover.c:devl_port_register_with_ops
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
Location: include/linux/xarray.h:774
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109cdd4)
Location: include/linux/xarray.h:774
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In kernel/irq/msi.c (ffffffff811c6269)
Location: include/linux/xarray.h:774
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_insert_desc
```
```
In mm/vmalloc.c (ffffffff81441a17)
Location: include/linux/xarray.h:774
Inline: True
```
```
In block/blk-mq.c (ffffffff817bf368)
Location: include/linux/xarray.h:774
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_hctx
```
```
In block/genhd.c (ffffffff817d1354)
Location: include/linux/xarray.h:774
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/partitions/core.c (ffffffff817d4154)
Location: include/linux/xarray.h:774
Inline: True
Inline callers:
  - block/partitions/core.c:add_partition
```
```
In drivers/pci/doe.c (ffffffff819ad4ee)
Location: include/linux/xarray.h:774
Inline: True
Inline callers:
  - drivers/pci/doe.c:pci_doe_init
  - drivers/pci/doe.c:pci_doe_create_mb
```
```
In drivers/dax/super.c (ffffffff81c0d702)
Location: include/linux/xarray.h:774
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_add_host
```
```
In drivers/dpll/dpll_core.c (ffffffff81eb7752)
Location: include/linux/xarray.h:774
Inline: True
Inline callers:
  - drivers/dpll/dpll_core.c:dpll_xa_ref_dpll_add
  - drivers/dpll/dpll_core.c:dpll_xa_ref_pin_add
```
```
In net/core/dev.c (ffffffff81ef6ec1)
Location: include/linux/xarray.h:774
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
```
```
In net/sched/cls_api.c (ffffffff81f7cdbc)
Location: include/linux/xarray.h:774
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/devlink/dev.c (ffffffff821021a7)
Location: include/linux/xarray.h:774
Inline: True
Inline callers:
  - net/devlink/dev.c:devl_nested_devlink_set
```
```
In net/devlink/port.c (ffffffff82107238)
Location: include/linux/xarray.h:774
Inline: True
Inline callers:
  - net/devlink/port.c:devl_port_register_with_ops
```
```
In net/devlink/param.c (ffffffff8210eb63)
Location: include/linux/xarray.h:774
Inline: True
Inline callers:
  - net/devlink/param.c:devl_params_register
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
