# Function: <code>__free_iova</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __free_iova(struct iova_domain *iovad, struct iova *iova);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff8152d340)
Location: drivers/iommu/iova.c:342
Inline: False
Direct callers:
  - drivers/iommu/iova.c:free_iova
  - drivers/iommu/intel-iommu.c:flush_unmaps
  - drivers/iommu/intel-iommu.c:intel_map_sg
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff8152d340-ffffffff8152d3c4: __free_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __free_iova(struct iova_domain *iovad, struct iova *iova);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81580750)
Location: drivers/iommu/iova.c:365
Inline: False
Direct callers:
  - drivers/iommu/iova.c:free_iova
```
**Symbols:**

```
ffffffff81580750-ffffffff81580789: __free_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __free_iova(struct iova_domain *iovad, struct iova *iova);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff815ad2f0)
Location: drivers/iommu/iova.c:365
Inline: False
Direct callers:
  - drivers/iommu/iova.c:free_iova
```
**Symbols:**

```
ffffffff815ad2f0-ffffffff815ad329: __free_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __free_iova(struct iova_domain *iovad, struct iova *iova);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff815c2f00)
Location: drivers/iommu/iova.c:341
Inline: False
Direct callers:
  - drivers/iommu/iova.c:free_iova
```
**Symbols:**

```
ffffffff815c2f00-ffffffff815c2f39: __free_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __free_iova(struct iova_domain *iovad, struct iova *iova);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816299b0)
Location: drivers/iommu/iova.c:365
Inline: False
Direct callers:
  - drivers/iommu/iova.c:free_iova
```
**Symbols:**

```
ffffffff816299b0-ffffffff816299e9: __free_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __free_iova(struct iova_domain *iovad, struct iova *iova);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816646c0)
Location: drivers/iommu/iova.c:365
Inline: False
Direct callers:
  - drivers/iommu/iova.c:free_iova
```
**Symbols:**

```
ffffffff816646c0-ffffffff816646f9: __free_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __free_iova(struct iova_domain *iovad, struct iova *iova);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81682cc0)
Location: drivers/iommu/iova.c:374
Inline: False
Direct callers:
  - drivers/iommu/iova.c:free_iova
```
**Symbols:**

```
ffffffff81682cc0-ffffffff81682cf9: __free_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __free_iova(struct iova_domain *iovad, struct iova *iova);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816ba3d0)
Location: drivers/iommu/iova.c:373
Inline: False
Direct callers:
  - drivers/iommu/iova.c:free_iova
```
**Symbols:**

```
ffffffff816ba3d0-ffffffff816ba40b: __free_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __free_iova(struct iova_domain *iovad, struct iova *iova);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816dd200)
Location: drivers/iommu/iova.c:373
Inline: False
Direct callers:
  - drivers/iommu/iova.c:free_iova
```
**Symbols:**

```
ffffffff816dd200-ffffffff816dd23b: __free_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __free_iova(struct iova_domain *iovad, struct iova *iova);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff817943b0)
Location: drivers/iommu/iova.c:373
Inline: True
Inline callers:
  - drivers/iommu/iova.c:fq_ring_free
```
**Symbols:**

```
ffffffff81793f50-ffffffff81793f8b: __free_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __free_iova(struct iova_domain *iovad, struct iova *iova);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff817c0790)
Location: drivers/iommu/iova.c:383
Inline: False
```
**Symbols:**

```
ffffffff817c0790-ffffffff817c07cb: __free_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __free_iova(struct iova_domain *iovad, struct iova *iova);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff817a3a20)
Location: drivers/iommu/iova.c:450
Inline: False
```
**Symbols:**

```
ffffffff817a3a20-ffffffff817a3a5b: __free_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __free_iova(struct iova_domain *iovad, struct iova *iova);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff8182cb30)
Location: drivers/iommu/iova.c:446
Inline: False
```
**Symbols:**

```
ffffffff8182cb30-ffffffff8182cb81: __free_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __free_iova(struct iova_domain *iovad, struct iova *iova);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff8196ddd0)
Location: drivers/iommu/iova.c:387
Inline: False
```
**Symbols:**

```
ffffffff8196ddd0-ffffffff8196de2a: __free_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __free_iova(struct iova_domain *iovad, struct iova *iova);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81ad8700)
Location: drivers/iommu/iova.c:392
Inline: False
```
**Symbols:**

```
ffffffff81ad8700-ffffffff81ad875a: __free_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __free_iova(struct iova_domain *iovad, struct iova *iova);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81b26820)
Location: drivers/iommu/iova.c:392
Inline: False
```
**Symbols:**

```
ffffffff81b26820-ffffffff81b2687a: __free_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __free_iova(struct iova_domain *iovad, struct iova *iova);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81b7d460)
Location: drivers/iommu/iova.c:393
Inline: False
```
**Symbols:**

```
ffffffff81b7d460-ffffffff81b7d4ba: __free_iova (STB_GLOBAL)
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
void __free_iova(struct iova_domain *iovad, struct iova *iova);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffff8000108cd140)
Location: drivers/iommu/iova.c:373
Inline: False
Direct callers:
  - drivers/iommu/iova.c:free_iova
```
**Symbols:**

```
ffff8000108cd140-ffff8000108cd1e8: __free_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/arm/mm/dma-mapping.c (c031cc5c)
Location: arch/arm/mm/dma-mapping.c:1198
Inline: True
Inline callers:
  - arch/arm/mm/dma-mapping.c:arm_iommu_unmap_resource
  - arch/arm/mm/dma-mapping.c:arm_iommu_map_resource
  - arch/arm/mm/dma-mapping.c:arm_iommu_unmap_page
  - arch/arm/mm/dma-mapping.c:arm_coherent_iommu_unmap_page
  - arch/arm/mm/dma-mapping.c:arm_coherent_iommu_map_page
  - arch/arm/mm/dma-mapping.c:__map_sg_chunk
  - arch/arm/mm/dma-mapping.c:__iommu_remove_mapping
  - arch/arm/mm/dma-mapping.c:__iommu_create_mapping
Direct callers:
  - arch/arm/mm/dma-mapping.c:arm_iommu_unmap_resource
  - arch/arm/mm/dma-mapping.c:arm_iommu_map_resource
  - arch/arm/mm/dma-mapping.c:arm_iommu_unmap_page
  - arch/arm/mm/dma-mapping.c:arm_coherent_iommu_unmap_page
  - arch/arm/mm/dma-mapping.c:arm_coherent_iommu_map_page
  - arch/arm/mm/dma-mapping.c:__map_sg_chunk
  - arch/arm/mm/dma-mapping.c:__iommu_remove_mapping
  - arch/arm/mm/dma-mapping.c:__iommu_create_mapping
```
**Symbols:**

```
c031bc74-c031bc84: __free_iova.part.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void __free_iova(struct iova_domain *iovad, struct iova *iova);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816a2c50)
Location: drivers/iommu/iova.c:373
Inline: False
Direct callers:
  - drivers/iommu/iova.c:free_iova
```
**Symbols:**

```
ffffffff816a2c50-ffffffff816a2c8b: __free_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __free_iova(struct iova_domain *iovad, struct iova *iova);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81680640)
Location: drivers/iommu/iova.c:373
Inline: False
Direct callers:
  - drivers/iommu/iova.c:free_iova
```
**Symbols:**

```
ffffffff81680640-ffffffff8168067b: __free_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __free_iova(struct iova_domain *iovad, struct iova *iova);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816d0ec0)
Location: drivers/iommu/iova.c:373
Inline: False
Direct callers:
  - drivers/iommu/iova.c:free_iova
```
**Symbols:**

```
ffffffff816d0ec0-ffffffff816d0efb: __free_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __free_iova(struct iova_domain *iovad, struct iova *iova);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816eb620)
Location: drivers/iommu/iova.c:373
Inline: False
Direct callers:
  - drivers/iommu/iova.c:free_iova
```
**Symbols:**

```
ffffffff816eb620-ffffffff816eb65b: __free_iova (STB_GLOBAL)
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
