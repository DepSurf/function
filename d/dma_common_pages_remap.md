# Function: <code>dma_common_pages_remap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *dma_common_pages_remap(struct page **pages, size_t size, long unsigned int vm_flags, pgprot_t prot, const void *caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dma-mapping.c (ffffffff8155dfa0)
Location: drivers/base/dma-mapping.c:278
Inline: False
Direct callers:
  - drivers/base/dma-mapping.c:dma_common_contiguous_remap
```
**Symbols:**

```
ffffffff8155dfa0-ffffffff8155dffc: dma_common_pages_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *dma_common_pages_remap(struct page **pages, size_t size, long unsigned int vm_flags, pgprot_t prot, const void *caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dma-mapping.c (ffffffff815b21e0)
Location: drivers/base/dma-mapping.c:277
Inline: False
Direct callers:
  - drivers/base/dma-mapping.c:dma_common_contiguous_remap
```
**Symbols:**

```
ffffffff815b21e0-ffffffff815b223c: dma_common_pages_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *dma_common_pages_remap(struct page **pages, size_t size, long unsigned int vm_flags, pgprot_t prot, const void *caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dma-mapping.c (ffffffff815e14d0)
Location: drivers/base/dma-mapping.c:280
Inline: False
Direct callers:
  - drivers/base/dma-mapping.c:dma_common_contiguous_remap
```
**Symbols:**

```
ffffffff815e14d0-ffffffff815e152c: dma_common_pages_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *dma_common_pages_remap(struct page **pages, size_t size, long unsigned int vm_flags, pgprot_t prot, const void *caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dma-mapping.c (ffffffff815f6150)
Location: drivers/base/dma-mapping.c:276
Inline: False
```
**Symbols:**

```
ffffffff815f6150-ffffffff815f61ac: dma_common_pages_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *dma_common_pages_remap(struct page **pages, size_t size, long unsigned int vm_flags, pgprot_t prot, const void *caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dma-mapping.c (ffffffff8165e070)
Location: drivers/base/dma-mapping.c:273
Inline: False
```
**Symbols:**

```
ffffffff8165e070-ffffffff8165e0cc: dma_common_pages_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *dma_common_pages_remap(struct page **pages, size_t size, long unsigned int vm_flags, pgprot_t prot, const void *caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8110cb20)
Location: kernel/dma/mapping.c:270
Inline: False
```
**Symbols:**

```
ffffffff8110cb20-ffffffff8110cb7d: dma_common_pages_remap (STB_GLOBAL)
```
</details>
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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *dma_common_pages_remap(struct page **pages, size_t size, pgprot_t prot, const void *caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/remap.c (ffffffff811897e0)
Location: kernel/dma/remap.c:22
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
```
**Symbols:**

```
ffffffff811897e0-ffffffff8118982f: dma_common_pages_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *dma_common_pages_remap(struct page **pages, size_t size, pgprot_t prot, const void *caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/remap.c (ffffffff811c5c30)
Location: kernel/dma/remap.c:22
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
```
**Symbols:**

```
ffffffff811c5c30-ffffffff811c5c7f: dma_common_pages_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *dma_common_pages_remap(struct page **pages, size_t size, pgprot_t prot, const void *caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/remap.c (ffffffff811d8800)
Location: kernel/dma/remap.c:22
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
```
**Symbols:**

```
ffffffff811d8800-ffffffff811d884f: dma_common_pages_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *dma_common_pages_remap(struct page **pages, size_t size, pgprot_t prot, const void *caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/remap.c (ffffffff811ee310)
Location: kernel/dma/remap.c:22
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
```
**Symbols:**

```
ffffffff811ee310-ffffffff811ee35f: dma_common_pages_remap (STB_GLOBAL)
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
void *dma_common_pages_remap(struct page **pages, size_t size, pgprot_t prot, const void *caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/remap.c (ffff800010197290)
Location: kernel/dma/remap.c:44
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_remap
```
**Symbols:**

```
ffff800010197290-ffff8000101972e8: dma_common_pages_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *dma_common_pages_remap(struct page **pages, size_t size, pgprot_t prot, const void *caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/remap.c (c03e2968)
Location: kernel/dma/remap.c:44
Inline: False
Direct callers:
  - arch/arm/mm/dma-mapping.c:arm_iommu_alloc_attrs
```
**Symbols:**

```
c03e2968-c03e2994: dma_common_pages_remap (STB_GLOBAL)
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
</ul>
