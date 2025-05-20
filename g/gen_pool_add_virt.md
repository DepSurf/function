# Function: <code>gen_pool_add_virt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int gen_pool_add_virt(struct gen_pool *pool, long unsigned int virt, phys_addr_t phys, size_t size, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff814075b0)
Location: lib/genalloc.c:182
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_init
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_expand
  - drivers/misc/sram.c:sram_probe
  - drivers/misc/sram.c:sram_probe
```
**Symbols:**

```
ffffffff814075b0-ffffffff8140764c: gen_pool_add_virt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int gen_pool_add_virt(struct gen_pool *pool, long unsigned int virt, phys_addr_t phys, size_t size, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8144f410)
Location: lib/genalloc.c:182
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_init
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_expand
  - drivers/misc/sram.c:sram_probe
  - drivers/misc/sram.c:sram_probe
```
**Symbols:**

```
ffffffff8144f410-ffffffff8144f4ae: gen_pool_add_virt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int gen_pool_add_virt(struct gen_pool *pool, long unsigned int virt, phys_addr_t phys, size_t size, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8146ddd0)
Location: lib/genalloc.c:182
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_init
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_expand
  - drivers/misc/sram.c:sram_probe
  - drivers/misc/sram.c:sram_probe
```
**Symbols:**

```
ffffffff8146ddd0-ffffffff8146de6e: gen_pool_add_virt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int gen_pool_add_virt(struct gen_pool *pool, long unsigned int virt, phys_addr_t phys, size_t size, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff814734a0)
Location: lib/genalloc.c:182
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_init
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_expand
  - drivers/misc/sram.c:sram_probe
  - drivers/misc/sram.c:sram_probe
```
**Symbols:**

```
ffffffff814734a0-ffffffff8147353e: gen_pool_add_virt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int gen_pool_add_virt(struct gen_pool *pool, long unsigned int virt, phys_addr_t phys, size_t size, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff814a0830)
Location: lib/genalloc.c:182
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_init
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_expand
  - drivers/misc/sram.c:sram_probe
  - drivers/misc/sram.c:sram_probe
```
**Symbols:**

```
ffffffff814a0830-ffffffff814a08ce: gen_pool_add_virt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int gen_pool_add_virt(struct gen_pool *pool, long unsigned int virt, phys_addr_t phys, size_t size, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff814d59c0)
Location: lib/genalloc.c:182
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_init
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_expand
  - drivers/misc/sram.c:sram_probe
  - drivers/misc/sram.c:sram_probe
```
**Symbols:**

```
ffffffff814d59c0-ffffffff814d5a5e: gen_pool_add_virt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int gen_pool_add_virt(struct gen_pool *pool, long unsigned int virt, phys_addr_t phys, size_t size, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff814ea050)
Location: lib/genalloc.c:183
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
  - drivers/misc/sram.c:sram_probe
  - drivers/misc/sram.c:sram_probe
```
**Symbols:**

```
ffffffff814ea050-ffffffff814ea0e9: gen_pool_add_virt (STB_GLOBAL)
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8104f3b3)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
```
```
In drivers/acpi/apei/ghes.c (ffffffff81623387)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
```
```
In drivers/misc/sram.c (ffffffff817101cc)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/usb/core/hcd.c (ffffffff817bc05e)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8104fd33)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
```
```
In drivers/acpi/apei/ghes.c (ffffffff81644e57)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
```
```
In drivers/misc/sram.c (ffffffff817344bc)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/usb/core/hcd.c (ffffffff817ec88e)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff81054243)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
```
```
In kernel/dma/pool.c (ffffffff8113f74f)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - kernel/dma/pool.c:atomic_pool_expand
```
```
In drivers/acpi/apei/ghes.c (ffffffff816f242b)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
```
```
In drivers/misc/sram.c (ffffffff817f1bec)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/misc/sram.c:sram_add_partition
```
```
In drivers/usb/core/hcd.c (ffffffff818bbf6e)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff810531a3)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
```
```
In kernel/dma/pool.c (ffffffff8113ad3d)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - kernel/dma/pool.c:atomic_pool_expand
```
```
In drivers/acpi/apei/ghes.c (ffffffff8170f7eb)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
```
```
In drivers/misc/sram.c (ffffffff8180621c)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/misc/sram.c:sram_add_partition
```
```
In drivers/usb/core/hcd.c (ffffffff818c8d2e)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff81054a93)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
```
```
In kernel/dma/pool.c (ffffffff8113c06c)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - kernel/dma/pool.c:atomic_pool_expand
```
```
In drivers/acpi/apei/ghes.c (ffffffff816f10bb)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
```
```
In drivers/misc/sram.c (ffffffff817ead2c)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/usb/core/hcd.c (ffffffff818ac2de)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8105d3e3)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
```
```
In kernel/dma/pool.c (ffffffff8115f17b)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - kernel/dma/pool.c:atomic_pool_expand
```
```
In drivers/acpi/apei/ghes.c (ffffffff8176b1cb)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
```
```
In drivers/misc/sram.c (ffffffff818777a8)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/misc/sram.c:sram_add_partition
```
```
In drivers/usb/core/hcd.c (ffffffff8194132e)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff81069924)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
```
```
In kernel/dma/pool.c (ffffffff8118939e)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - kernel/dma/pool.c:atomic_pool_expand
```
```
In drivers/acpi/apei/ghes.c (ffffffff8189fdc6)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
```
```
In drivers/misc/sram.c (ffffffff819bfa59)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/misc/sram.c:sram_add_partition
```
```
In drivers/usb/core/hcd.c (ffffffff81a99a5e)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff81079624)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
```
```
In kernel/dma/pool.c (ffffffff811c579e)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - kernel/dma/pool.c:atomic_pool_expand
```
```
In drivers/acpi/apei/ghes.c (ffffffff819e91d3)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
```
```
In drivers/misc/sram.c (ffffffff81b352ac)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/misc/sram.c:sram_add_partition
```
```
In drivers/usb/core/hcd.c (ffffffff81c1d883)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8107b8d4)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
```
```
In kernel/dma/pool.c (ffffffff811d8388)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - kernel/dma/pool.c:atomic_pool_expand
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a318e3)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
```
```
In drivers/misc/sram.c (ffffffff81b8876c)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/misc/sram.c:sram_add_partition
```
```
In drivers/usb/core/hcd.c (ffffffff81c84773)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff81082d94)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
```
```
In kernel/dma/pool.c (ffffffff811ede5d)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - kernel/dma/pool.c:atomic_pool_expand
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a7cd53)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
```
```
In drivers/misc/sram.c (ffffffff81bdc66b)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/misc/sram.c:sram_add_partition
```
```
In drivers/usb/core/hcd.c (ffffffff81d39173)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
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
In kernel/dma/remap.c (ffff80001144806c)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - kernel/dma/remap.c:dma_atomic_pool_init
```
```
In drivers/acpi/apei/ghes.c (ffff8000107b0ac8)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
```
```
In drivers/soc/fsl/qbman/bman_ccsr.c (ffff80001080fa6c)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/bman_ccsr.c:fsl_bman_probe
```
```
In drivers/soc/fsl/qbman/qman_ccsr.c (ffff800010810764)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman_ccsr.c:fsl_qman_probe
  - drivers/soc/fsl/qbman/qman_ccsr.c:fsl_qman_probe
  - drivers/soc/fsl/qbman/qman_ccsr.c:fsl_qman_probe
```
```
In drivers/misc/sram.c (ffff80001092b5a8)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/net/ethernet/freescale/fman/fman_muram.c (ffff8000109edd28)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/fman_muram.c:fman_muram_init
```
```
In drivers/usb/core/hcd.c (ffff800010a1b990)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
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
In arch/arm/mm/dma-mapping.c (c1507b44)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - arch/arm/mm/dma-mapping.c:atomic_pool_init
```
```
In drivers/misc/sram.c (c0a09c84)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/misc/sram.c:sram_add_pool
```
```
In drivers/net/ethernet/ti/davinci_cpdma.c (c0ad7858)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_ctlr_create
```
```
In drivers/usb/core/hcd.c (c0af38f0)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
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
In drivers/misc/sram.c (c0000000009ca814)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/usb/core/hcd.c (c000000000ad5408)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
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
In drivers/misc/sram.c (ffffffe0005a2eda)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/usb/core/hcd.c (ffffffe00063ff46)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8104fe33)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
```
```
In drivers/misc/sram.c (ffffffff816fa54c)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/usb/core/hcd.c (ffffffff817a4c6e)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8103f393)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
```
```
In drivers/misc/sram.c (ffffffff816ce35c)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/usb/core/hcd.c (ffffffff8179677e)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8104fce3)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
```
```
In drivers/acpi/apei/ghes.c (ffffffff81638c97)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
```
```
In drivers/misc/sram.c (ffffffff8172797c)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/usb/core/hcd.c (ffffffff817e170e)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff81051123)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init
```
```
In drivers/acpi/apei/ghes.c (ffffffff81652fe7)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
```
```
In drivers/misc/sram.c (ffffffff81742dbc)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/usb/core/hcd.c (ffffffff817fbafe)
Location: include/linux/genalloc.h:101
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
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
