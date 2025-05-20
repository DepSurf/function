# Function: <code>sg_alloc_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int sg_alloc_table(struct sg_table *table, unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff813fa660)
Location: lib/scatterlist.c:359
Inline: True
Direct callers:
  - lib/scatterlist.c:sg_alloc_table_from_pages
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/base/dma-mapping.c:dma_common_get_sgtable
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff813fa660-ffffffff813fa6ec: sg_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int sg_alloc_table(struct sg_table *table, unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814416e0)
Location: lib/scatterlist.c:359
Inline: True
Direct callers:
  - lib/scatterlist.c:sg_alloc_table_from_pages
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/base/dma-mapping.c:dma_common_get_sgtable
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff814416e0-ffffffff8144176c: sg_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int sg_alloc_table(struct sg_table *table, unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8145e900)
Location: lib/scatterlist.c:359
Inline: True
Direct callers:
  - lib/scatterlist.c:sg_alloc_table_from_pages
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff8145e900-ffffffff8145e98c: sg_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int sg_alloc_table(struct sg_table *table, unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81463bb0)
Location: lib/scatterlist.c:359
Inline: True
Direct callers:
  - lib/scatterlist.c:sg_alloc_table_from_pages
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff81463bb0-ffffffff81463c46: sg_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int sg_alloc_table(struct sg_table *table, unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8148fb50)
Location: lib/scatterlist.c:359
Inline: True
Direct callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/base/dma-mapping.c:dma_common_get_sgtable
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff8148fb50-ffffffff8148fbe6: sg_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int sg_alloc_table(struct sg_table *table, unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814c4430)
Location: lib/scatterlist.c:347
Inline: True
Direct callers:
  - kernel/dma/mapping.c:dma_common_get_sgtable
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/spi/spi.c:spi_map_buf
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff814c4430-ffffffff814c447b: sg_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int sg_alloc_table(struct sg_table *table, unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814d8b20)
Location: lib/scatterlist.c:347
Inline: True
Direct callers:
  - kernel/dma/mapping.c:dma_common_get_sgtable
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/spi/spi.c:spi_map_buf
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff814d8b20-ffffffff814d8b6b: sg_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int sg_alloc_table(struct sg_table *table, unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815049c0)
Location: lib/scatterlist.c:355
Inline: True
Direct callers:
  - kernel/dma/mapping.c:dma_common_get_sgtable
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/spi/spi.c:spi_map_buf
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff815049c0-ffffffff81504a11: sg_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int sg_alloc_table(struct sg_table *table, unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81522900)
Location: lib/scatterlist.c:355
Inline: True
Direct callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/spi/spi.c:spi_map_buf
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff81522900-ffffffff81522951: sg_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int sg_alloc_table(struct sg_table *table, unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81586375)
Location: lib/scatterlist.c:355
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_alloc_table_from_pages
  - lib/scatterlist.c:__sg_alloc_table_from_pages
Direct callers:
  - kernel/dma/mapping.c:dma_common_get_sgtable
  - kernel/dma/direct.c:dma_direct_get_sgtable
  - drivers/char/agp/intel-gtt.c:intel_gtt_map_memory
  - drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable
  - drivers/spi/spi.c:spi_map_buf
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff81586190-ffffffff81586221: sg_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int sg_alloc_table(struct sg_table *table, unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815a3270)
Location: lib/scatterlist.c:355
Inline: True
Direct callers:
  - kernel/dma/direct.c:dma_direct_get_sgtable
  - kernel/dma/ops_helpers.c:dma_common_get_sgtable
  - drivers/char/agp/intel-gtt.c:intel_gtt_map_memory
  - drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:dup_sg_table
  - drivers/spi/spi.c:spi_map_buf
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff815a3270-ffffffff815a3301: sg_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int sg_alloc_table(struct sg_table *table, unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815aa630)
Location: lib/scatterlist.c:355
Inline: True
Direct callers:
  - kernel/dma/mapping.c:dma_alloc_noncontiguous
  - kernel/dma/direct.c:dma_direct_get_sgtable
  - kernel/dma/ops_helpers.c:dma_common_get_sgtable
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_attach
  - drivers/spi/spi.c:spi_map_buf
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff815aa630-ffffffff815aa6c1: sg_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sg_alloc_table(struct sg_table *table, unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff816138c0)
Location: lib/scatterlist.c:371
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_alloc_noncontiguous
  - kernel/dma/direct.c:dma_direct_get_sgtable
  - kernel/dma/ops_helpers.c:dma_common_get_sgtable
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_attach
  - drivers/spi/spi.c:spi_map_buf
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff816138c0-ffffffff81613952: sg_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sg_alloc_table(struct sg_table *table, unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff816e0190)
Location: lib/scatterlist.c:371
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_alloc_noncontiguous
  - kernel/dma/direct.c:dma_direct_get_sgtable
  - kernel/dma/ops_helpers.c:dma_common_get_sgtable
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_attach
  - drivers/spi/spi.c:spi_map_buf
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff816e0190-ffffffff816e024e: sg_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sg_alloc_table(struct sg_table *table, unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff817d0480)
Location: lib/scatterlist.c:371
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_alloc_noncontiguous
  - kernel/dma/direct.c:dma_direct_get_sgtable
  - kernel/dma/ops_helpers.c:dma_common_get_sgtable
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_attach
  - drivers/spi/spi.c:spi_map_buf_attrs
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff817d0480-ffffffff817d053e: sg_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sg_alloc_table(struct sg_table *table, unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8180f0d0)
Location: lib/scatterlist.c:373
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_alloc_noncontiguous
  - kernel/dma/direct.c:dma_direct_get_sgtable
  - kernel/dma/ops_helpers.c:dma_common_get_sgtable
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_attach
  - drivers/spi/spi.c:spi_map_buf_attrs
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff8180f0d0-ffffffff8180f18e: sg_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sg_alloc_table(struct sg_table *table, unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81854d50)
Location: lib/scatterlist.c:374
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_alloc_noncontiguous
  - kernel/dma/direct.c:dma_direct_get_sgtable
  - kernel/dma/ops_helpers.c:dma_common_get_sgtable
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_attach
  - drivers/spi/spi.c:spi_map_buf_attrs
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff81854d50-ffffffff81854e0e: sg_alloc_table (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int sg_alloc_table(struct sg_table *table, unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffff80001062c688)
Location: lib/scatterlist.c:355
Inline: True
Direct callers:
  - kernel/dma/mapping.c:dma_common_get_sgtable
  - kernel/dma/mapping.c:dma_common_get_sgtable
  - drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable
  - drivers/spi/spi.c:spi_map_buf
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffff80001062c688-ffff80001062c6f4: sg_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int sg_alloc_table(struct sg_table *table, unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (c07d3170)
Location: lib/scatterlist.c:355
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_map_buf
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
c07d3170-c07d31e0: sg_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int sg_alloc_table(struct sg_table *table, unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (c0000000007cf240)
Location: lib/scatterlist.c:355
Inline: True
Direct callers:
  - kernel/dma/mapping.c:dma_common_get_sgtable
  - drivers/spi/spi.c:spi_map_buf
  - drivers/spi/spi.c:spi_map_buf
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
c0000000007cf240-c0000000007cf2d4: sg_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int sg_alloc_table(struct sg_table *table, unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffe00045c89c)
Location: lib/scatterlist.c:355
Inline: True
Direct callers:
  - kernel/dma/mapping.c:dma_common_get_sgtable
  - drivers/spi/spi.c:spi_map_buf
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffe00045c89c-ffffffe00045c8fc: sg_alloc_table (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int sg_alloc_table(struct sg_table *table, unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8151aee0)
Location: lib/scatterlist.c:355
Inline: True
Direct callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/spi/spi.c:spi_map_buf
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff8151aee0-ffffffff8151af31: sg_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int sg_alloc_table(struct sg_table *table, unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8150b1d0)
Location: lib/scatterlist.c:355
Inline: True
Direct callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/spi/spi.c:spi_map_buf
```
**Symbols:**

```
ffffffff8150b1d0-ffffffff8150b221: sg_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int sg_alloc_table(struct sg_table *table, unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81516f70)
Location: lib/scatterlist.c:355
Inline: True
Direct callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/spi/spi.c:spi_map_buf
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff81516f70-ffffffff81516fc1: sg_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int sg_alloc_table(struct sg_table *table, unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81530700)
Location: lib/scatterlist.c:355
Inline: True
Direct callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/spi/spi.c:spi_map_buf
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff81530700-ffffffff81530751: sg_alloc_table (STB_GLOBAL)
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
