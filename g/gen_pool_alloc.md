# Function: <code>gen_pool_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int gen_pool_alloc(struct gen_pool *pool, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff81406f80)
Location: lib/genalloc.c:271
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_add
  - lib/genalloc.c:gen_pool_dma_alloc
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
```
**Symbols:**

```
ffffffff81406f80-ffffffff8140715f: gen_pool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int gen_pool_alloc(struct gen_pool *pool, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8144ef1f)
Location: lib/genalloc.c:271
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_dma_alloc
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_add
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
```
**Symbols:**

```
ffffffff8144eef0-ffffffff8144ef03: gen_pool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long unsigned int gen_pool_alloc(struct gen_pool *pool, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8146d8df)
Location: lib/genalloc.c:271
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_dma_alloc
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_add
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
```
**Symbols:**

```
ffffffff8146d8b0-ffffffff8146d8c3: gen_pool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int gen_pool_alloc(struct gen_pool *pool, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff81472fbf)
Location: lib/genalloc.c:271
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_dma_alloc
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
```
**Symbols:**

```
ffffffff81472f90-ffffffff81472fa3: gen_pool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int gen_pool_alloc(struct gen_pool *pool, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff814a034f)
Location: lib/genalloc.c:271
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_dma_alloc
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
```
**Symbols:**

```
ffffffff814a0320-ffffffff814a0333: gen_pool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long unsigned int gen_pool_alloc(struct gen_pool *pool, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff814d54f6)
Location: lib/genalloc.c:271
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_dma_alloc
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_add
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
```
**Symbols:**

```
ffffffff814d54c0-ffffffff814d54d3: gen_pool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long unsigned int gen_pool_alloc(struct gen_pool *pool, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff814e9f56)
Location: lib/genalloc.c:272
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_dma_alloc
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
```
**Symbols:**

```
ffffffff814e9f20-ffffffff814e9f33: gen_pool_alloc (STB_GLOBAL)
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8104f29a)
Location: include/linux/genalloc.h:151
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
```
```
In drivers/acpi/apei/ghes.c (ffffffff81621f57)
Location: include/linux/genalloc.h:151
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8104fc1a)
Location: include/linux/genalloc.h:151
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
```
```
In drivers/acpi/apei/ghes.c (ffffffff81643a37)
Location: include/linux/genalloc.h:151
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8105411a)
Location: include/linux/genalloc.h:151
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
```
```
In kernel/dma/pool.c (ffffffff8113f7e5)
Location: include/linux/genalloc.h:151
Inline: True
Inline callers:
  - kernel/dma/pool.c:__dma_alloc_from_pool
```
```
In drivers/acpi/apei/ghes.c (ffffffff816f1396)
Location: include/linux/genalloc.h:151
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8105307a)
Location: include/linux/genalloc.h:151
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
```
```
In kernel/dma/pool.c (ffffffff8113adea)
Location: include/linux/genalloc.h:151
Inline: True
Inline callers:
  - kernel/dma/pool.c:__dma_alloc_from_pool
```
```
In drivers/acpi/apei/ghes.c (ffffffff8170e736)
Location: include/linux/genalloc.h:151
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
  - drivers/acpi/apei/ghes.c:ghes_defer_non_standard_event
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8105496a)
Location: include/linux/genalloc.h:151
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
```
```
In kernel/dma/pool.c (ffffffff8113c26b)
Location: include/linux/genalloc.h:151
Inline: True
Inline callers:
  - kernel/dma/pool.c:dma_alloc_from_pool
```
```
In drivers/acpi/apei/ghes.c (ffffffff816efd87)
Location: include/linux/genalloc.h:151
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8105d2ba)
Location: include/linux/genalloc.h:151
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
```
```
In kernel/dma/pool.c (ffffffff8115f38e)
Location: include/linux/genalloc.h:151
Inline: True
Inline callers:
  - kernel/dma/pool.c:dma_alloc_from_pool
```
```
In drivers/acpi/apei/ghes.c (ffffffff81769e2d)
Location: include/linux/genalloc.h:151
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff810697ea)
Location: include/linux/genalloc.h:151
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
```
```
In kernel/dma/pool.c (ffffffff811895ae)
Location: include/linux/genalloc.h:151
Inline: True
Inline callers:
  - kernel/dma/pool.c:dma_alloc_from_pool
```
```
In drivers/acpi/apei/ghes.c (ffffffff8189e956)
Location: include/linux/genalloc.h:151
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff810794ca)
Location: include/linux/genalloc.h:151
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
```
```
In kernel/dma/pool.c (ffffffff811c59ce)
Location: include/linux/genalloc.h:151
Inline: True
Inline callers:
  - kernel/dma/pool.c:dma_alloc_from_pool
```
```
In drivers/acpi/apei/ghes.c (ffffffff819e7c76)
Location: include/linux/genalloc.h:151
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
  - drivers/acpi/apei/ghes.c:ghes_defer_non_standard_event
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8107b77a)
Location: include/linux/genalloc.h:151
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
```
```
In kernel/dma/pool.c (ffffffff811d845b)
Location: include/linux/genalloc.h:151
Inline: True
Inline callers:
  - kernel/dma/pool.c:__dma_alloc_from_pool
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a30386)
Location: include/linux/genalloc.h:151
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
  - drivers/acpi/apei/ghes.c:ghes_defer_non_standard_event
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff81082c3a)
Location: include/linux/genalloc.h:151
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
```
```
In kernel/dma/pool.c (ffffffff811edf6b)
Location: include/linux/genalloc.h:151
Inline: True
Inline callers:
  - kernel/dma/pool.c:__dma_alloc_from_pool
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a7b896)
Location: include/linux/genalloc.h:151
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
  - drivers/acpi/apei/ghes.c:ghes_defer_non_standard_event
  - drivers/acpi/apei/ghes.c:ghes_handle_aer
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
In kernel/dma/remap.c (ffff8000101974b4)
Location: include/linux/genalloc.h:151
Inline: True
Inline callers:
  - kernel/dma/remap.c:dma_alloc_from_pool
```
```
In drivers/acpi/apei/ghes.c (ffff8000107afc44)
Location: include/linux/genalloc.h:151
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_in_nmi_queue_one_entry
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
```
```
In drivers/soc/fsl/qbman/bman.c (ffff8000108126cc)
Location: include/linux/genalloc.h:151
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/bman.c:bman_new_pool
```
```
In drivers/soc/fsl/qbman/qman.c (ffff800010812920)
Location: include/linux/genalloc.h:151
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman.c:qman_alloc_range
```
```
In drivers/net/ethernet/freescale/fman/fman_muram.c (ffff8000109ede7c)
Location: include/linux/genalloc.h:151
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/fman_muram.c:fman_muram_alloc
```
```
In drivers/edac/altera_edac.c (ffff800010b15964)
Location: include/linux/genalloc.h:151
Inline: True
Inline callers:
  - drivers/edac/altera_edac.c:ocram_alloc_mem
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
In arch/arm/mm/dma-mapping.c (c031bbd0)
Location: include/linux/genalloc.h:151
Inline: True
```
```
In arch/arm/mach-imx/pm-imx5.c (0)
Location: include/linux/genalloc.h:151
Inline: True
```
```
In arch/arm/mach-imx/pm-imx6.c (c151027c)
Location: include/linux/genalloc.h:151
Inline: True
Inline callers:
  - arch/arm/mach-imx/pm-imx6.c:imx6q_suspend_init
```
```
In arch/arm/mach-omap2/omap4-common.c (c1514c84)
Location: include/linux/genalloc.h:151
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap4-common.c:__omap4_sram_init
```
```
In drivers/net/ethernet/ti/davinci_cpdma.c (c0ad70c4)
Location: include/linux/genalloc.h:151
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_submit_si
```
</details>
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8104fd1a)
Location: include/linux/genalloc.h:151
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8103f27a)
Location: include/linux/genalloc.h:151
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8104fbca)
Location: include/linux/genalloc.h:151
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
```
```
In drivers/acpi/apei/ghes.c (ffffffff81637877)
Location: include/linux/genalloc.h:151
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8105100a)
Location: include/linux/genalloc.h:151
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
```
```
In drivers/acpi/apei/ghes.c (ffffffff81651bb7)
Location: include/linux/genalloc.h:151
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
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
