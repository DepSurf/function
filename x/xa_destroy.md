# Function: <code>xa_destroy</code>

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
void xa_destroy(struct xarray *xa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a17f80)
Location: lib/xarray.c:1935
Inline: False
```
**Symbols:**

```
ffffffff81a17f80-ffffffff81a18037: xa_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xa_destroy(struct xarray *xa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a87b30)
Location: lib/xarray.c:1962
Inline: False
```
**Symbols:**

```
ffffffff81a87b30-ffffffff81a87c03: xa_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xa_destroy(struct xarray *xa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81abedd0)
Location: lib/xarray.c:1983
Inline: False
```
**Symbols:**

```
ffffffff81abedd0-ffffffff81abeea3: xa_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xa_destroy(struct xarray *xa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff815fb6b0)
Location: lib/xarray.c:1986
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_free
```
**Symbols:**

```
ffffffff815fb6b0-ffffffff815fb7ba: xa_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xa_destroy(struct xarray *xa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81620220)
Location: lib/xarray.c:2199
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - net/core/devlink.c:devlink_free
```
**Symbols:**

```
ffffffff81620220-ffffffff8162032a: xa_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xa_destroy(struct xarray *xa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81603860)
Location: lib/xarray.c:2200
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
  - net/core/devlink.c:devlink_free
```
**Symbols:**

```
ffffffff81603860-ffffffff81603969: xa_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xa_destroy(struct xarray *xa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81671f90)
Location: lib/xarray.c:2200
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
  - drivers/vfio/vfio.c:vfio_cleanup
  - net/core/devlink.c:devlink_free
```
**Symbols:**

```
ffffffff81671f90-ffffffff816720a1: xa_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xa_destroy(struct xarray *xa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8178c740)
Location: lib/xarray.c:2207
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
  - kernel/irq/msi.c:msi_device_data_release
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_release
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_ring_ctx_alloc
  - drivers/vfio/vfio.c:vfio_cleanup
  - net/core/devlink.c:devlink_free
```
**Symbols:**

```
ffffffff8178c740-ffffffff8178c85e: xa_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xa_destroy(struct xarray *xa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff82049df0)
Location: lib/xarray.c:2207
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
  - kernel/irq/msi.c:msi_device_data_release
  - kernel/irq/msi.c:msi_device_data_release
  - block/blk-mq.c:blk_mq_release
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_ring_ctx_alloc
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
  - drivers/pci/doe.c:pci_doe_xa_destroy
  - net/core/devlink.c:devlink_free
  - net/core/devlink.c:devlink_free
```
**Symbols:**

```
ffffffff82049df0-ffffffff82049f0e: xa_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xa_destroy(struct xarray *xa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff820c8690)
Location: lib/xarray.c:2205
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
  - kernel/irq/msi.c:msi_device_data_release
  - kernel/irq/msi.c:msi_device_data_release
  - block/blk-mq.c:blk_mq_release
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_ring_ctx_alloc
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
  - drivers/pci/doe.c:pci_doe_destroy
  - drivers/pci/doe.c:pci_doe_destroy
  - drivers/pci/doe.c:pci_doe_init
  - drivers/pci/doe.c:pci_doe_create_mb
  - net/devlink/core.c:devlink_free
  - net/devlink/core.c:devlink_free
  - net/devlink/core.c:devlink_free
```
**Symbols:**

```
ffffffff820c8690-ffffffff820c87a8: xa_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xa_destroy(struct xarray *xa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff821a3010)
Location: lib/xarray.c:2211
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
  - kernel/irq/msi.c:msi_device_data_release
  - kernel/irq/msi.c:msi_device_data_release
  - fs/libfs.c:simple_offset_destroy
  - block/blk-mq.c:blk_mq_release
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_ring_ctx_alloc
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
  - drivers/pci/doe.c:pci_doe_destroy
  - drivers/pci/doe.c:pci_doe_destroy
  - drivers/pci/doe.c:pci_doe_init
  - drivers/pci/doe.c:pci_doe_create_mb
  - drivers/dpll/dpll_core.c:dpll_pin_put
  - drivers/dpll/dpll_core.c:dpll_pin_put
  - drivers/dpll/dpll_core.c:dpll_pin_get
  - drivers/dpll/dpll_core.c:dpll_pin_get
  - drivers/dpll/dpll_core.c:dpll_device_put
  - net/core/dev.c:netdev_exit
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_chain_put
  - net/devlink/core.c:devlink_free
  - net/devlink/core.c:devlink_free
  - net/devlink/core.c:devlink_free
  - net/devlink/core.c:devlink_free
```
**Symbols:**

```
ffffffff821a3010-ffffffff821a3128: xa_destroy (STB_GLOBAL)
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
void xa_destroy(struct xarray *xa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffff800010d9ac28)
Location: lib/xarray.c:1983
Inline: False
```
**Symbols:**

```
ffff800010d9ac28-ffff800010d9ad40: xa_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void xa_destroy(struct xarray *xa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c0e96d60)
Location: lib/xarray.c:1983
Inline: False
```
**Symbols:**

```
c0e96d60-c0e96e38: xa_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void xa_destroy(struct xarray *xa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c000000000ee02c0)
Location: lib/xarray.c:1983
Inline: False
```
**Symbols:**

```
c000000000ee02c0-c000000000ee03c4: xa_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void xa_destroy(struct xarray *xa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffe0008c2bc4)
Location: lib/xarray.c:1983
Inline: False
```
**Symbols:**

```
ffffffe0008c2bc4-ffffffe0008c2c64: xa_destroy (STB_GLOBAL)
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
void xa_destroy(struct xarray *xa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a5dc20)
Location: lib/xarray.c:1983
Inline: False
```
**Symbols:**

```
ffffffff81a5dc20-ffffffff81a5dcf3: xa_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void xa_destroy(struct xarray *xa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a1acf0)
Location: lib/xarray.c:1983
Inline: False
```
**Symbols:**

```
ffffffff81a1acf0-ffffffff81a1adc3: xa_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void xa_destroy(struct xarray *xa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81aca010)
Location: lib/xarray.c:1983
Inline: False
```
**Symbols:**

```
ffffffff81aca010-ffffffff81aca0e3: xa_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xa_destroy(struct xarray *xa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ad65a0)
Location: lib/xarray.c:1983
Inline: False
```
**Symbols:**

```
ffffffff81ad65a0-ffffffff81ad6673: xa_destroy (STB_GLOBAL)
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
