# Function: <code>__xa_insert</code>

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
int __xa_insert(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a18d90)
Location: lib/xarray.c:1458
Inline: False
```
**Symbols:**

```
ffffffff81a18d90-ffffffff81a18ea3: __xa_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __xa_insert(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a88aa0)
Location: lib/xarray.c:1472
Inline: False
```
**Symbols:**

```
ffffffff81a88aa0-ffffffff81a88bac: __xa_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __xa_insert(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81abfd40)
Location: lib/xarray.c:1483
Inline: False
```
**Symbols:**

```
ffffffff81abfd40-ffffffff81abfe4c: __xa_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __xa_insert(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff815fc340)
Location: lib/xarray.c:1485
Inline: False
```
**Symbols:**

```
ffffffff815fc340-ffffffff815fc448: __xa_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __xa_insert(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81620f60)
Location: lib/xarray.c:1635
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
**Symbols:**

```
ffffffff81620f60-ffffffff81621068: __xa_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __xa_insert(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81604940)
Location: lib/xarray.c:1636
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - fs/io_uring.c:io_provide_buffers
  - block/genhd.c:__alloc_disk_node
  - block/partitions/core.c:add_partition
```
**Symbols:**

```
ffffffff81604940-ffffffff81604a48: __xa_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __xa_insert(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81673230)
Location: lib/xarray.c:1636
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - fs/io_uring.c:io_provide_buffers
  - block/genhd.c:__alloc_disk_node
  - block/partitions/core.c:add_partition
```
**Symbols:**

```
ffffffff81673230-ffffffff8167333c: __xa_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __xa_insert(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8178d840)
Location: lib/xarray.c:1643
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - kernel/irq/msi.c:msi_add_simple_msi_descs
  - kernel/irq/msi.c:msi_add_msi_desc
  - block/blk-mq.c:blk_mq_init_hctx
  - block/genhd.c:__alloc_disk_node
  - block/partitions/core.c:add_partition
  - drivers/dax/super.c:dax_add_host
```
**Symbols:**

```
ffffffff8178d840-ffffffff8178d965: __xa_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __xa_insert(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8204aed0)
Location: lib/xarray.c:1643
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - kernel/irq/msi.c:msi_insert_desc
  - block/blk-mq.c:blk_mq_init_hctx
  - block/genhd.c:__alloc_disk_node
  - block/partitions/core.c:add_partition
  - drivers/pci/doe.c:pcim_doe_create_mb
  - drivers/dax/super.c:dax_add_host
  - net/core/devlink.c:devl_port_register
```
**Symbols:**

```
ffffffff8204aed0-ffffffff8204aff5: __xa_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __xa_insert(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff820c97d0)
Location: lib/xarray.c:1641
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - kernel/irq/msi.c:msi_insert_desc
  - block/blk-mq.c:blk_mq_init_hctx
  - block/genhd.c:__alloc_disk_node
  - block/partitions/core.c:add_partition
  - drivers/pci/doe.c:pci_doe_init
  - drivers/pci/doe.c:pci_doe_create_mb
  - drivers/dax/super.c:dax_add_host
  - net/devlink/leftover.c:devl_params_register
  - net/devlink/leftover.c:devl_port_register_with_ops
```
**Symbols:**

```
ffffffff820c97d0-ffffffff820c98f5: __xa_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __xa_insert(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff821a4150)
Location: lib/xarray.c:1641
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - kernel/irq/msi.c:msi_insert_desc
  - block/blk-mq.c:blk_mq_init_hctx
  - block/genhd.c:__alloc_disk_node
  - block/partitions/core.c:add_partition
  - drivers/pci/doe.c:pci_doe_init
  - drivers/pci/doe.c:pci_doe_create_mb
  - drivers/dax/super.c:dax_add_host
  - drivers/dpll/dpll_core.c:dpll_xa_ref_dpll_add
  - drivers/dpll/dpll_core.c:dpll_xa_ref_pin_add
  - net/core/dev.c:__dev_change_net_namespace
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/devlink/dev.c:devl_nested_devlink_set
  - net/devlink/port.c:devl_port_register_with_ops
  - net/devlink/param.c:devl_params_register
```
**Symbols:**

```
ffffffff821a4150-ffffffff821a4275: __xa_insert (STB_GLOBAL)
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
int __xa_insert(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffff800010d9b6c8)
Location: lib/xarray.c:1483
Inline: False
```
**Symbols:**

```
ffff800010d9b6c8-ffff800010d9b7ec: __xa_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __xa_insert(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c0e97dc0)
Location: lib/xarray.c:1483
Inline: False
```
**Symbols:**

```
c0e97dc0-c0e97f14: __xa_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __xa_insert(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c000000000ee1a10)
Location: lib/xarray.c:1483
Inline: False
```
**Symbols:**

```
c000000000ee1a10-c000000000ee1ba8: __xa_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __xa_insert(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffe0008c3942)
Location: lib/xarray.c:1483
Inline: False
```
**Symbols:**

```
ffffffe0008c3942-ffffffe0008c3a3a: __xa_insert (STB_GLOBAL)
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
int __xa_insert(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a5eb90)
Location: lib/xarray.c:1483
Inline: False
```
**Symbols:**

```
ffffffff81a5eb90-ffffffff81a5ec9c: __xa_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __xa_insert(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a1bc60)
Location: lib/xarray.c:1483
Inline: False
```
**Symbols:**

```
ffffffff81a1bc60-ffffffff81a1bd6c: __xa_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __xa_insert(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81acaf80)
Location: lib/xarray.c:1483
Inline: False
```
**Symbols:**

```
ffffffff81acaf80-ffffffff81acb08c: __xa_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __xa_insert(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ad75e0)
Location: lib/xarray.c:1483
Inline: False
```
**Symbols:**

```
ffffffff81ad75e0-ffffffff81ad76ec: __xa_insert (STB_GLOBAL)
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
