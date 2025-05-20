# Function: <code>gen_pool_alloc_algo_owner</code>

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
long unsigned int gen_pool_alloc_algo_owner(struct gen_pool *pool, size_t size, genpool_algo_t algo, void *data, void **owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff81516950)
Location: lib/genalloc.c:275
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - lib/genalloc.c:gen_pool_dma_alloc_algo
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
```
**Symbols:**

```
ffffffff81516950-ffffffff81516b64: gen_pool_alloc_algo_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int gen_pool_alloc_algo_owner(struct gen_pool *pool, size_t size, genpool_algo_t algo, void *data, void **owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff81537390)
Location: lib/genalloc.c:275
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - lib/genalloc.c:gen_pool_dma_alloc_algo
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
```
**Symbols:**

```
ffffffff81537390-ffffffff815375a4: gen_pool_alloc_algo_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int gen_pool_alloc_algo_owner(struct gen_pool *pool, size_t size, genpool_algo_t algo, void *data, void **owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8159bd00)
Location: lib/genalloc.c:275
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - kernel/dma/pool.c:__dma_alloc_from_pool
  - lib/genalloc.c:gen_pool_dma_alloc_algo
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
```
**Symbols:**

```
ffffffff8159bd00-ffffffff8159bf1c: gen_pool_alloc_algo_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int gen_pool_alloc_algo_owner(struct gen_pool *pool, size_t size, genpool_algo_t algo, void *data, void **owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff815b7740)
Location: lib/genalloc.c:276
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - kernel/dma/pool.c:__dma_alloc_from_pool
  - lib/genalloc.c:gen_pool_dma_alloc_algo
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
  - drivers/acpi/apei/ghes.c:ghes_defer_non_standard_event
```
**Symbols:**

```
ffffffff815b7740-ffffffff815b7946: gen_pool_alloc_algo_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int gen_pool_alloc_algo_owner(struct gen_pool *pool, size_t size, genpool_algo_t algo, void *data, void **owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff815c25b0)
Location: lib/genalloc.c:277
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - kernel/dma/pool.c:dma_alloc_from_pool
  - lib/genalloc.c:gen_pool_dma_alloc_algo
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
```
**Symbols:**

```
ffffffff815c25b0-ffffffff815c27b3: gen_pool_alloc_algo_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long unsigned int gen_pool_alloc_algo_owner(struct gen_pool *pool, size_t size, genpool_algo_t algo, void *data, void **owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/genalloc.c (0)
Location: lib/genalloc.c:277
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - kernel/dma/pool.c:dma_alloc_from_pool
  - lib/genalloc.c:gen_pool_dma_alloc_algo
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
```
**Symbols:**

```
ffffffff81cdb653-ffffffff81cdb6d0: gen_pool_alloc_algo_owner.cold (STB_LOCAL)
ffffffff8162a4e0-ffffffff8162a70f: gen_pool_alloc_algo_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long unsigned int gen_pool_alloc_algo_owner(struct gen_pool *pool, size_t size, genpool_algo_t algo, void *data, void **owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/genalloc.c (0)
Location: lib/genalloc.c:277
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - kernel/dma/pool.c:dma_alloc_from_pool
  - lib/genalloc.c:gen_pool_dma_alloc_algo
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
```
**Symbols:**

```
ffffffff81e93e7c-ffffffff81e93f17: gen_pool_alloc_algo_owner.cold (STB_LOCAL)
ffffffff816fb8f0-ffffffff816fbb54: gen_pool_alloc_algo_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long unsigned int gen_pool_alloc_algo_owner(struct gen_pool *pool, size_t size, genpool_algo_t algo, void *data, void **owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/genalloc.c (0)
Location: lib/genalloc.c:277
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - kernel/dma/pool.c:dma_alloc_from_pool
  - lib/genalloc.c:gen_pool_dma_alloc_algo
  - drivers/pci/p2pdma.c:pci_alloc_p2pmem
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
  - drivers/acpi/apei/ghes.c:ghes_defer_non_standard_event
```
**Symbols:**

```
ffffffff82078efb-ffffffff82078f96: gen_pool_alloc_algo_owner.cold (STB_LOCAL)
ffffffff817ee580-ffffffff817ee7e4: gen_pool_alloc_algo_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long unsigned int gen_pool_alloc_algo_owner(struct gen_pool *pool, size_t size, genpool_algo_t algo, void *data, void **owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/genalloc.c (0)
Location: lib/genalloc.c:275
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - kernel/dma/pool.c:__dma_alloc_from_pool
  - lib/genalloc.c:gen_pool_dma_alloc_algo
  - drivers/pci/p2pdma.c:pci_alloc_p2pmem
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
  - drivers/acpi/apei/ghes.c:ghes_defer_non_standard_event
```
**Symbols:**

```
ffffffff820f9638-ffffffff820f96cf: gen_pool_alloc_algo_owner.cold (STB_LOCAL)
ffffffff8182e960-ffffffff8182eba9: gen_pool_alloc_algo_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long unsigned int gen_pool_alloc_algo_owner(struct gen_pool *pool, size_t size, genpool_algo_t algo, void *data, void **owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/genalloc.c (0)
Location: lib/genalloc.c:277
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - kernel/dma/pool.c:__dma_alloc_from_pool
  - lib/genalloc.c:gen_pool_dma_alloc_algo
  - drivers/pci/p2pdma.c:pci_alloc_p2pmem
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
  - drivers/acpi/apei/ghes.c:ghes_defer_non_standard_event
  - drivers/acpi/apei/ghes.c:ghes_handle_aer
```
**Symbols:**

```
ffffffff821d77a5-ffffffff821d783c: gen_pool_alloc_algo_owner.cold (STB_LOCAL)
ffffffff81880520-ffffffff81880769: gen_pool_alloc_algo_owner (STB_GLOBAL)
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
long unsigned int gen_pool_alloc_algo_owner(struct gen_pool *pool, size_t size, genpool_algo_t algo, void *data, void **owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffff800010644450)
Location: lib/genalloc.c:275
Inline: False
Direct callers:
  - kernel/dma/remap.c:dma_alloc_from_pool
  - lib/genalloc.c:gen_pool_dma_alloc_algo
  - drivers/acpi/apei/ghes.c:ghes_in_nmi_queue_one_entry
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/soc/fsl/qbman/bman.c:bman_new_pool
  - drivers/soc/fsl/qbman/qman.c:qman_alloc_range
  - drivers/net/ethernet/freescale/fman/fman_muram.c:fman_muram_alloc
  - drivers/edac/altera_edac.c:ocram_alloc_mem
```
**Symbols:**

```
ffff800010644450-ffff8000106446a8: gen_pool_alloc_algo_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int gen_pool_alloc_algo_owner(struct gen_pool *pool, size_t size, genpool_algo_t algo, void *data, void **owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (c07ead0c)
Location: lib/genalloc.c:275
Inline: False
Direct callers:
  - arch/arm/mach-imx/pm-imx6.c:imx6q_suspend_init
  - arch/arm/mach-omap2/omap4-common.c:__omap4_sram_init
  - lib/genalloc.c:gen_pool_dma_alloc_algo
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_submit_si
```
**Symbols:**

```
c07ead0c-c07eaf80: gen_pool_alloc_algo_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int gen_pool_alloc_algo_owner(struct gen_pool *pool, size_t size, genpool_algo_t algo, void *data, void **owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (c0000000007ef7c0)
Location: lib/genalloc.c:275
Inline: False
Direct callers:
  - lib/genalloc.c:gen_pool_dma_alloc_algo
```
**Symbols:**

```
c0000000007ef7c0-c0000000007efad0: gen_pool_alloc_algo_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int gen_pool_alloc_algo_owner(struct gen_pool *pool, size_t size, genpool_algo_t algo, void *data, void **owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffe0004708ce)
Location: lib/genalloc.c:275
Inline: False
Direct callers:
  - lib/genalloc.c:gen_pool_dma_alloc_algo
```
**Symbols:**

```
ffffffe0004708ce-ffffffe000470abe: gen_pool_alloc_algo_owner (STB_GLOBAL)
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
long unsigned int gen_pool_alloc_algo_owner(struct gen_pool *pool, size_t size, genpool_algo_t algo, void *data, void **owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8152f970)
Location: lib/genalloc.c:275
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - lib/genalloc.c:gen_pool_dma_alloc_algo
```
**Symbols:**

```
ffffffff8152f970-ffffffff8152fb84: gen_pool_alloc_algo_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int gen_pool_alloc_algo_owner(struct gen_pool *pool, size_t size, genpool_algo_t algo, void *data, void **owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8151fc50)
Location: lib/genalloc.c:275
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - lib/genalloc.c:gen_pool_dma_alloc_algo
```
**Symbols:**

```
ffffffff8151fc50-ffffffff8151fe64: gen_pool_alloc_algo_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int gen_pool_alloc_algo_owner(struct gen_pool *pool, size_t size, genpool_algo_t algo, void *data, void **owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8152b6b0)
Location: lib/genalloc.c:275
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - lib/genalloc.c:gen_pool_dma_alloc_algo
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
```
**Symbols:**

```
ffffffff8152b6b0-ffffffff8152b8c4: gen_pool_alloc_algo_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int gen_pool_alloc_algo_owner(struct gen_pool *pool, size_t size, genpool_algo_t algo, void *data, void **owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff81545430)
Location: lib/genalloc.c:275
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add
  - lib/genalloc.c:gen_pool_dma_alloc_algo
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
```
**Symbols:**

```
ffffffff81545430-ffffffff81545653: gen_pool_alloc_algo_owner (STB_GLOBAL)
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
