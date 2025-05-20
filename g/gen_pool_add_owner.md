# Function: <code>gen_pool_add_owner</code>

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
int gen_pool_add_owner(struct gen_pool *pool, long unsigned int virt, phys_addr_t phys, size_t size, int nid, void *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff81516d00)
Location: lib/genalloc.c:182
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
```
**Symbols:**

```
ffffffff81516d00-ffffffff81516dbc: gen_pool_add_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int gen_pool_add_owner(struct gen_pool *pool, long unsigned int virt, phys_addr_t phys, size_t size, int nid, void *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff81537740)
Location: lib/genalloc.c:182
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
```
**Symbols:**

```
ffffffff81537740-ffffffff815377fc: gen_pool_add_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int gen_pool_add_owner(struct gen_pool *pool, long unsigned int virt, phys_addr_t phys, size_t size, int nid, void *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8159b840)
Location: lib/genalloc.c:182
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
  - kernel/dma/pool.c:atomic_pool_expand
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/misc/sram.c:sram_add_partition
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
```
**Symbols:**

```
ffffffff8159b840-ffffffff8159b8fc: gen_pool_add_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int gen_pool_add_owner(struct gen_pool *pool, long unsigned int virt, phys_addr_t phys, size_t size, int nid, void *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff815b70e0)
Location: lib/genalloc.c:183
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
  - kernel/dma/pool.c:atomic_pool_expand
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/misc/sram.c:sram_add_partition
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
```
**Symbols:**

```
ffffffff815b70e0-ffffffff815b7198: gen_pool_add_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int gen_pool_add_owner(struct gen_pool *pool, long unsigned int virt, phys_addr_t phys, size_t size, int nid, void *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff815c1f50)
Location: lib/genalloc.c:184
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
  - kernel/dma/pool.c:atomic_pool_expand
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
```
**Symbols:**

```
ffffffff815c1f50-ffffffff815c2008: gen_pool_add_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int gen_pool_add_owner(struct gen_pool *pool, long unsigned int virt, phys_addr_t phys, size_t size, int nid, void *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/genalloc.c (0)
Location: lib/genalloc.c:184
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
  - kernel/dma/pool.c:atomic_pool_expand
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/misc/sram.c:sram_add_partition
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
```
**Symbols:**

```
ffffffff81cdb530-ffffffff81cdb555: gen_pool_add_owner.cold (STB_LOCAL)
ffffffff81629dc0-ffffffff81629e81: gen_pool_add_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int gen_pool_add_owner(struct gen_pool *pool, long unsigned int virt, phys_addr_t phys, size_t size, int nid, void *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/genalloc.c (0)
Location: lib/genalloc.c:184
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
  - kernel/dma/pool.c:atomic_pool_expand
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/misc/sram.c:sram_add_partition
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
```
**Symbols:**

```
ffffffff81e93d59-ffffffff81e93d7e: gen_pool_add_owner.cold (STB_LOCAL)
ffffffff816fb090-ffffffff816fb173: gen_pool_add_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int gen_pool_add_owner(struct gen_pool *pool, long unsigned int virt, phys_addr_t phys, size_t size, int nid, void *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/genalloc.c (0)
Location: lib/genalloc.c:184
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
  - kernel/dma/pool.c:atomic_pool_expand
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/misc/sram.c:sram_add_partition
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
```
**Symbols:**

```
ffffffff82078dd8-ffffffff82078dfd: gen_pool_add_owner.cold (STB_LOCAL)
ffffffff817edc10-ffffffff817edcf3: gen_pool_add_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int gen_pool_add_owner(struct gen_pool *pool, long unsigned int virt, phys_addr_t phys, size_t size, int nid, void *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/genalloc.c (0)
Location: lib/genalloc.c:182
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
  - kernel/dma/pool.c:atomic_pool_expand
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/misc/sram.c:sram_add_partition
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
```
**Symbols:**

```
ffffffff820f9522-ffffffff820f9547: gen_pool_add_owner.cold (STB_LOCAL)
ffffffff8182e020-ffffffff8182e103: gen_pool_add_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int gen_pool_add_owner(struct gen_pool *pool, long unsigned int virt, phys_addr_t phys, size_t size, int nid, void *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/genalloc.c (0)
Location: lib/genalloc.c:184
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
  - kernel/dma/pool.c:atomic_pool_expand
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/misc/sram.c:sram_add_partition
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
```
**Symbols:**

```
ffffffff821d768f-ffffffff821d76b4: gen_pool_add_owner.cold (STB_LOCAL)
ffffffff8187fbe0-ffffffff8187fcc3: gen_pool_add_owner (STB_GLOBAL)
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
int gen_pool_add_owner(struct gen_pool *pool, long unsigned int virt, phys_addr_t phys, size_t size, int nid, void *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffff800010644868)
Location: lib/genalloc.c:182
Inline: False
Direct callers:
  - kernel/dma/remap.c:dma_atomic_pool_init
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
  - drivers/soc/fsl/qbman/bman_ccsr.c:fsl_bman_probe
  - drivers/soc/fsl/qbman/qman_ccsr.c:fsl_qman_probe
  - drivers/soc/fsl/qbman/qman_ccsr.c:fsl_qman_probe
  - drivers/soc/fsl/qbman/qman_ccsr.c:fsl_qman_probe
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/net/ethernet/freescale/fman/fman_muram.c:fman_muram_init
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
```
**Symbols:**

```
ffff800010644868-ffff800010644964: gen_pool_add_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int gen_pool_add_owner(struct gen_pool *pool, long unsigned int virt, phys_addr_t phys, size_t size, int nid, void *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (c07ea4a8)
Location: lib/genalloc.c:182
Inline: False
Direct callers:
  - arch/arm/mm/dma-mapping.c:atomic_pool_init
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/misc/sram.c:sram_add_pool
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_ctlr_create
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
```
**Symbols:**

```
c07ea4a8-c07ea554: gen_pool_add_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int gen_pool_add_owner(struct gen_pool *pool, long unsigned int virt, phys_addr_t phys, size_t size, int nid, void *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (c0000000007efd80)
Location: lib/genalloc.c:182
Inline: False
Direct callers:
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
```
**Symbols:**

```
c0000000007efd80-c0000000007efed0: gen_pool_add_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int gen_pool_add_owner(struct gen_pool *pool, long unsigned int virt, phys_addr_t phys, size_t size, int nid, void *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffe0004707f8)
Location: lib/genalloc.c:182
Inline: False
Direct callers:
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
```
**Symbols:**

```
ffffffe0004707f8-ffffffe0004708ce: gen_pool_add_owner (STB_GLOBAL)
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
int gen_pool_add_owner(struct gen_pool *pool, long unsigned int virt, phys_addr_t phys, size_t size, int nid, void *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8152fd20)
Location: lib/genalloc.c:182
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
```
**Symbols:**

```
ffffffff8152fd20-ffffffff8152fddc: gen_pool_add_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int gen_pool_add_owner(struct gen_pool *pool, long unsigned int virt, phys_addr_t phys, size_t size, int nid, void *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff81520000)
Location: lib/genalloc.c:182
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
```
**Symbols:**

```
ffffffff81520000-ffffffff815200bc: gen_pool_add_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int gen_pool_add_owner(struct gen_pool *pool, long unsigned int virt, phys_addr_t phys, size_t size, int nid, void *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8152ba60)
Location: lib/genalloc.c:182
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
```
**Symbols:**

```
ffffffff8152ba60-ffffffff8152bb1c: gen_pool_add_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int gen_pool_add_owner(struct gen_pool *pool, long unsigned int virt, phys_addr_t phys, size_t size, int nid, void *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff81545300)
Location: lib/genalloc.c:182
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
```
**Symbols:**

```
ffffffff81545300-ffffffff815453ba: gen_pool_add_owner (STB_GLOBAL)
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
