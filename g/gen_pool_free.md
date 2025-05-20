# Function: <code>gen_pool_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void gen_pool_free(struct gen_pool *pool, long unsigned int addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff814071e0)
Location: lib/genalloc.c:354
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_process
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
```
**Symbols:**

```
ffffffff814071e0-ffffffff81407263: gen_pool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void gen_pool_free(struct gen_pool *pool, long unsigned int addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8144ef90)
Location: lib/genalloc.c:373
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_process
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
```
**Symbols:**

```
ffffffff8144ef90-ffffffff8144f013: gen_pool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void gen_pool_free(struct gen_pool *pool, long unsigned int addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8146d950)
Location: lib/genalloc.c:374
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_process
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
```
**Symbols:**

```
ffffffff8146d950-ffffffff8146d9d3: gen_pool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void gen_pool_free(struct gen_pool *pool, long unsigned int addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff81473030)
Location: lib/genalloc.c:374
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_process
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
```
**Symbols:**

```
ffffffff81473030-ffffffff814730b3: gen_pool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void gen_pool_free(struct gen_pool *pool, long unsigned int addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff814a03c0)
Location: lib/genalloc.c:374
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_process
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
```
**Symbols:**

```
ffffffff814a03c0-ffffffff814a0446: gen_pool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void gen_pool_free(struct gen_pool *pool, long unsigned int addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff814d5560)
Location: lib/genalloc.c:374
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_process
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
```
**Symbols:**

```
ffffffff814d5560-ffffffff814d55e6: gen_pool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void gen_pool_free(struct gen_pool *pool, long unsigned int addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff814e9fc0)
Location: lib/genalloc.c:375
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
```
**Symbols:**

```
ffffffff814e9fc0-ffffffff814ea046: gen_pool_free (STB_GLOBAL)
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8104f220)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
```
```
In drivers/acpi/apei/ghes.c (ffffffff816232c6)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
```
```
In drivers/usb/core/buffer.c (ffffffff817c7d5d)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff817f642b)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:td_free
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8104fba0)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
```
```
In drivers/acpi/apei/ghes.c (ffffffff81644d96)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
```
```
In drivers/usb/core/buffer.c (ffffffff817f8894)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff8182728b)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:td_free
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff810540a0)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
```
```
In kernel/dma/pool.c (ffffffff8113faed)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - kernel/dma/pool.c:dma_free_from_pool
  - kernel/dma/pool.c:__dma_alloc_from_pool
```
```
In drivers/acpi/apei/ghes.c (ffffffff816f1fad)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free
  - drivers/acpi/apei/ghes.c:ghes_kick_task_work
```
```
In drivers/usb/core/buffer.c (ffffffff818c89f9)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff818f9f9b)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_free
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff81053000)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
```
```
In kernel/dma/pool.c (ffffffff8113b0dd)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - kernel/dma/pool.c:dma_free_from_pool
  - kernel/dma/pool.c:__dma_alloc_from_pool
```
```
In drivers/acpi/apei/ghes.c (ffffffff8170f36d)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free
  - drivers/acpi/apei/ghes.c:ghes_vendor_record_work_func
  - drivers/acpi/apei/ghes.c:ghes_kick_task_work
```
```
In drivers/usb/core/buffer.c (ffffffff818d3b49)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81902adb)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_free
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff810548f0)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
```
```
In kernel/dma/pool.c (ffffffff8113c3c4)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - kernel/dma/pool.c:dma_free_from_pool
  - kernel/dma/pool.c:dma_alloc_from_pool
```
```
In drivers/acpi/apei/ghes.c (ffffffff816f0c4d)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free
  - drivers/acpi/apei/ghes.c:ghes_vendor_record_work_func
  - drivers/acpi/apei/ghes.c:ghes_kick_task_work
```
```
In drivers/usb/core/buffer.c (ffffffff818b70a9)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff818e5c1e)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_free
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8105d240)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
```
```
In kernel/dma/pool.c (ffffffff8115f4e4)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - kernel/dma/pool.c:dma_free_from_pool
  - kernel/dma/pool.c:dma_alloc_from_pool
```
```
In drivers/acpi/apei/ghes.c (ffffffff8176ad5d)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free
  - drivers/acpi/apei/ghes.c:ghes_vendor_record_work_func
  - drivers/acpi/apei/ghes.c:ghes_kick_task_work
```
```
In drivers/usb/core/buffer.c (ffffffff8194cb89)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81981fbe)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_free
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff81069760)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
```
```
In kernel/dma/pool.c (ffffffff81189746)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - kernel/dma/pool.c:dma_free_from_pool
  - kernel/dma/pool.c:dma_alloc_from_pool
```
```
In drivers/acpi/apei/ghes.c (ffffffff8189f90d)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free
  - drivers/acpi/apei/ghes.c:ghes_vendor_record_work_func
  - drivers/acpi/apei/ghes.c:ghes_kick_task_work
```
```
In drivers/usb/core/buffer.c (ffffffff81aa5781)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81adea9e)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_free
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff81079420)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
```
```
In kernel/dma/pool.c (ffffffff811c5b76)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - kernel/dma/pool.c:dma_free_from_pool
  - kernel/dma/pool.c:dma_alloc_from_pool
```
```
In drivers/pci/p2pdma.c (ffffffff8191c6e3)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_alloc_p2pmem
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/acpi/apei/ghes.c (ffffffff819e8cda)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free
  - drivers/acpi/apei/ghes.c:ghes_vendor_record_work_func
  - drivers/acpi/apei/ghes.c:ghes_kick_task_work
```
```
In drivers/usb/core/buffer.c (ffffffff81c2c1f1)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81c69fae)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_free
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8107b6d0)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
```
```
In kernel/dma/pool.c (ffffffff811d8746)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - kernel/dma/pool.c:dma_free_from_pool
  - kernel/dma/pool.c:__dma_alloc_from_pool
```
```
In drivers/pci/p2pdma.c (ffffffff8195fca3)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_alloc_p2pmem
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a30cba)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free
  - drivers/acpi/apei/ghes.c:ghes_vendor_record_work_func
  - drivers/acpi/apei/ghes.c:ghes_kick_task_work
```
```
In drivers/usb/core/buffer.c (ffffffff81c93372)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free_pages
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81cd13be)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_free
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff81082b90)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
```
```
In kernel/dma/pool.c (ffffffff811ee256)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - kernel/dma/pool.c:dma_free_from_pool
  - kernel/dma/pool.c:__dma_alloc_from_pool
```
```
In drivers/pci/p2pdma.c (ffffffff819a9363)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_alloc_p2pmem
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a7c12e)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free
  - drivers/acpi/apei/ghes.c:ghes_vendor_record_work_func
  - drivers/acpi/apei/ghes.c:ghes_kick_task_work
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_region_free
```
```
In drivers/usb/core/buffer.c (ffffffff81d47e22)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free_pages
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81d8637e)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_free
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
In kernel/dma/remap.c (ffff800010197588)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - kernel/dma/remap.c:dma_free_from_pool
```
```
In drivers/acpi/apei/ghes.c (ffff8000107afd30)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_in_nmi_queue_one_entry
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
```
```
In drivers/soc/fsl/qbman/bman.c (ffff80001081267c)
Location: include/linux/genalloc.h:169
Inline: True
```
```
In drivers/soc/fsl/qbman/qman.c (ffff800010816d90)
Location: include/linux/genalloc.h:169
Inline: True
```
```
In drivers/net/ethernet/freescale/fman/fman_muram.c (ffff8000109edeec)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/fman_muram.c:fman_muram_free_mem
```
```
In drivers/usb/core/buffer.c (ffff800010a29658)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/host/ohci-hcd.c (ffff800010a621e0)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:td_free
```
```
In drivers/edac/altera_edac.c (ffff800010b158e4)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/edac/altera_edac.c:ocram_free_mem
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
In arch/arm/mm/dma-mapping.c (c031b0d0)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - arch/arm/mm/dma-mapping.c:__free_from_pool
```
```
In drivers/net/ethernet/ti/davinci_cpdma.c (c0ad6e78)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/davinci_cpdma.c:__cpdma_chan_free
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_submit_si
```
```
In drivers/usb/core/buffer.c (c0aff5ac)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/host/ohci-hcd.c (c0b35390)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:td_free
```
```
In sound/core/memalloc.c (c0c9bf50)
Location: include/linux/genalloc.h:169
Inline: True
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
In drivers/usb/core/buffer.c (c000000000ae5bb0)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/host/ohci-hcd.c (c000000000b31b20)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:td_free
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
In drivers/usb/core/buffer.c (ffffffe00064b062)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/host/ohci-hcd.c (ffffffe00067d432)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:td_free
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8104fca0)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
```
```
In drivers/usb/core/buffer.c (ffffffff817b0c74)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff817df66b)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:td_free
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8103f200)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
```
```
In drivers/usb/core/buffer.c (ffffffff817a26a4)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8104fb50)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
```
```
In drivers/acpi/apei/ghes.c (ffffffff81638bd6)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
```
```
In drivers/usb/core/buffer.c (ffffffff817ed714)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff8181c10b)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:td_free
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff81050f90)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process
```
```
In drivers/acpi/apei/ghes.c (ffffffff81652f26)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
```
```
In drivers/usb/core/buffer.c (ffffffff81807954)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81836feb)
Location: include/linux/genalloc.h:169
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:td_free
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
