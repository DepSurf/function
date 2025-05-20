# Function: <code>gen_pool_free_owner</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void gen_pool_free_owner(struct gen_pool *pool, long unsigned int addr, size_t size, void **owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff81516c50)
Location: lib/genalloc.c:485
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:td_free
```
**Symbols:**

```
ffffffff81516c50-ffffffff81516cf7: gen_pool_free_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void gen_pool_free_owner(struct gen_pool *pool, long unsigned int addr, size_t size, void **owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff81537690)
Location: lib/genalloc.c:485
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:td_free
```
**Symbols:**

```
ffffffff81537690-ffffffff81537737: gen_pool_free_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void gen_pool_free_owner(struct gen_pool *pool, long unsigned int addr, size_t size, void **owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8159bf20)
Location: lib/genalloc.c:485
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
  - kernel/dma/pool.c:dma_free_from_pool
  - kernel/dma/pool.c:__dma_alloc_from_pool
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free
  - drivers/acpi/apei/ghes.c:ghes_kick_task_work
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_free
```
**Symbols:**

```
ffffffff8159bf20-ffffffff8159bfca: gen_pool_free_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void gen_pool_free_owner(struct gen_pool *pool, long unsigned int addr, size_t size, void **owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff815b7950)
Location: lib/genalloc.c:486
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
  - kernel/dma/pool.c:dma_free_from_pool
  - kernel/dma/pool.c:__dma_alloc_from_pool
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free
  - drivers/acpi/apei/ghes.c:ghes_vendor_record_work_func
  - drivers/acpi/apei/ghes.c:ghes_kick_task_work
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_free
```
**Symbols:**

```
ffffffff815b7950-ffffffff815b7a02: gen_pool_free_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void gen_pool_free_owner(struct gen_pool *pool, long unsigned int addr, size_t size, void **owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff815c27c0)
Location: lib/genalloc.c:487
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
  - kernel/dma/pool.c:dma_free_from_pool
  - kernel/dma/pool.c:dma_alloc_from_pool
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free
  - drivers/acpi/apei/ghes.c:ghes_vendor_record_work_func
  - drivers/acpi/apei/ghes.c:ghes_kick_task_work
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_free
```
**Symbols:**

```
ffffffff815c27c0-ffffffff815c2875: gen_pool_free_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void gen_pool_free_owner(struct gen_pool *pool, long unsigned int addr, size_t size, void **owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/genalloc.c (0)
Location: lib/genalloc.c:487
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
  - kernel/dma/pool.c:dma_free_from_pool
  - kernel/dma/pool.c:dma_alloc_from_pool
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free
  - drivers/acpi/apei/ghes.c:ghes_vendor_record_work_func
  - drivers/acpi/apei/ghes.c:ghes_kick_task_work
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_free
```
**Symbols:**

```
ffffffff81cdb6d0-ffffffff81cdb768: gen_pool_free_owner.cold (STB_LOCAL)
ffffffff8162a710-ffffffff8162a7ea: gen_pool_free_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void gen_pool_free_owner(struct gen_pool *pool, long unsigned int addr, size_t size, void **owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/genalloc.c (0)
Location: lib/genalloc.c:487
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
  - kernel/dma/pool.c:dma_free_from_pool
  - kernel/dma/pool.c:dma_alloc_from_pool
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free
  - drivers/acpi/apei/ghes.c:ghes_vendor_record_work_func
  - drivers/acpi/apei/ghes.c:ghes_kick_task_work
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_free
```
**Symbols:**

```
ffffffff81e93f17-ffffffff81e93faf: gen_pool_free_owner.cold (STB_LOCAL)
ffffffff816fbb60-ffffffff816fbc65: gen_pool_free_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void gen_pool_free_owner(struct gen_pool *pool, long unsigned int addr, size_t size, void **owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/genalloc.c (0)
Location: lib/genalloc.c:487
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
  - kernel/dma/pool.c:dma_free_from_pool
  - kernel/dma/pool.c:dma_alloc_from_pool
  - drivers/pci/p2pdma.c:pci_p2pmem_free_sgl
  - drivers/pci/p2pdma.c:pci_alloc_p2pmem
  - drivers/pci/p2pdma.c:p2pdma_page_free
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free
  - drivers/acpi/apei/ghes.c:ghes_vendor_record_work_func
  - drivers/acpi/apei/ghes.c:ghes_kick_task_work
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_free
```
**Symbols:**

```
ffffffff82078f96-ffffffff8207902e: gen_pool_free_owner.cold (STB_LOCAL)
ffffffff817ee800-ffffffff817ee905: gen_pool_free_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void gen_pool_free_owner(struct gen_pool *pool, long unsigned int addr, size_t size, void **owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/genalloc.c (0)
Location: lib/genalloc.c:485
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
  - kernel/dma/pool.c:dma_free_from_pool
  - kernel/dma/pool.c:__dma_alloc_from_pool
  - drivers/pci/p2pdma.c:pci_p2pmem_free_sgl
  - drivers/pci/p2pdma.c:pci_alloc_p2pmem
  - drivers/pci/p2pdma.c:p2pdma_page_free
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free
  - drivers/acpi/apei/ghes.c:ghes_vendor_record_work_func
  - drivers/acpi/apei/ghes.c:ghes_kick_task_work
  - drivers/usb/core/buffer.c:hcd_buffer_free_pages
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_free
```
**Symbols:**

```
ffffffff820f96cf-ffffffff820f9752: gen_pool_free_owner.cold (STB_LOCAL)
ffffffff8182ebc0-ffffffff8182ecbf: gen_pool_free_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void gen_pool_free_owner(struct gen_pool *pool, long unsigned int addr, size_t size, void **owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/genalloc.c (0)
Location: lib/genalloc.c:487
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
  - kernel/dma/pool.c:dma_free_from_pool
  - kernel/dma/pool.c:__dma_alloc_from_pool
  - drivers/pci/p2pdma.c:pci_p2pmem_free_sgl
  - drivers/pci/p2pdma.c:pci_alloc_p2pmem
  - drivers/pci/p2pdma.c:p2pdma_page_free
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free
  - drivers/acpi/apei/ghes.c:ghes_vendor_record_work_func
  - drivers/acpi/apei/ghes.c:ghes_kick_task_work
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_region_free
  - drivers/usb/core/buffer.c:hcd_buffer_free_pages
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_free
```
**Symbols:**

```
ffffffff821d783c-ffffffff821d78bf: gen_pool_free_owner.cold (STB_LOCAL)
ffffffff81880780-ffffffff8188087f: gen_pool_free_owner (STB_GLOBAL)
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
void gen_pool_free_owner(struct gen_pool *pool, long unsigned int addr, size_t size, void **owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffff800010644968)
Location: lib/genalloc.c:485
Inline: False
Direct callers:
  - kernel/dma/remap.c:dma_free_from_pool
  - drivers/acpi/apei/ghes.c:ghes_in_nmi_queue_one_entry
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
  - drivers/net/ethernet/freescale/fman/fman_muram.c:fman_muram_free_mem
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/edac/altera_edac.c:ocram_free_mem
```
**Symbols:**

```
ffff800010644968-ffff800010644a34: gen_pool_free_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void gen_pool_free_owner(struct gen_pool *pool, long unsigned int addr, size_t size, void **owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (c07eab94)
Location: lib/genalloc.c:485
Inline: False
Direct callers:
  - arch/arm/mm/dma-mapping.c:__free_from_pool
  - drivers/net/ethernet/ti/davinci_cpdma.c:__cpdma_chan_free
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_submit_si
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:td_free
```
**Symbols:**

```
c07eab94-c07eac7c: gen_pool_free_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void gen_pool_free_owner(struct gen_pool *pool, long unsigned int addr, size_t size, void **owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (c0000000007efc60)
Location: lib/genalloc.c:485
Inline: False
Direct callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:td_free
```
**Symbols:**

```
c0000000007efc60-c0000000007efd7c: gen_pool_free_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void gen_pool_free_owner(struct gen_pool *pool, long unsigned int addr, size_t size, void **owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffe000470b78)
Location: lib/genalloc.c:485
Inline: False
Direct callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:td_free
```
**Symbols:**

```
ffffffe000470b78-ffffffe000470c20: gen_pool_free_owner (STB_GLOBAL)
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
void gen_pool_free_owner(struct gen_pool *pool, long unsigned int addr, size_t size, void **owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8152fc70)
Location: lib/genalloc.c:485
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:td_free
```
**Symbols:**

```
ffffffff8152fc70-ffffffff8152fd17: gen_pool_free_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void gen_pool_free_owner(struct gen_pool *pool, long unsigned int addr, size_t size, void **owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8151ff50)
Location: lib/genalloc.c:485
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
**Symbols:**

```
ffffffff8151ff50-ffffffff8151fff7: gen_pool_free_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void gen_pool_free_owner(struct gen_pool *pool, long unsigned int addr, size_t size, void **owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8152b9b0)
Location: lib/genalloc.c:485
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:td_free
```
**Symbols:**

```
ffffffff8152b9b0-ffffffff8152ba57: gen_pool_free_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void gen_pool_free_owner(struct gen_pool *pool, long unsigned int addr, size_t size, void **owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff81545720)
Location: lib/genalloc.c:485
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:td_free
```
**Symbols:**

```
ffffffff81545720-ffffffff815457f7: gen_pool_free_owner (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
