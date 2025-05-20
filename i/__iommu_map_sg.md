# Function: <code>__iommu_map_sg</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t __iommu_map_sg(struct iommu_domain *domain, long unsigned int iova, struct scatterlist *sg, unsigned int nents, int prot, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff817902a0)
Location: drivers/iommu/iommu.c:2322
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_map_sg_atomic
  - drivers/iommu/iommu.c:iommu_map_sg
```
**Symbols:**

```
ffffffff817902a0-ffffffff8179038a: __iommu_map_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t __iommu_map_sg(struct iommu_domain *domain, long unsigned int iova, struct scatterlist *sg, unsigned int nents, int prot, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff817bb770)
Location: drivers/iommu/iommu.c:2542
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_map_sg_atomic
  - drivers/iommu/iommu.c:iommu_map_sg
```
**Symbols:**

```
ffffffff817bb770-ffffffff817bb878: __iommu_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
size_t __iommu_map_sg(struct iommu_domain *domain, long unsigned int iova, struct scatterlist *sg, unsigned int nents, int prot, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8179de70)
Location: drivers/iommu/iommu.c:2573
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_map_sg_atomic
  - drivers/iommu/iommu.c:iommu_map_sg
```
**Symbols:**

```
ffffffff8179de70-ffffffff8179df80: __iommu_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t __iommu_map_sg(struct iommu_domain *domain, long unsigned int iova, struct scatterlist *sg, unsigned int nents, int prot, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81826fb0)
Location: drivers/iommu/iommu.c:2659
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_map_sg_atomic
  - drivers/iommu/iommu.c:iommu_map_sg
```
**Symbols:**

```
ffffffff81826fb0-ffffffff818270cc: __iommu_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t __iommu_map_sg(struct iommu_domain *domain, long unsigned int iova, struct scatterlist *sg, unsigned int nents, int prot, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81966b50)
Location: drivers/iommu/iommu.c:2436
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_map_sg_atomic
  - drivers/iommu/iommu.c:iommu_map_sg
```
**Symbols:**

```
ffffffff81966b50-ffffffff81966caf: __iommu_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t __iommu_map_sg(struct iommu_domain *domain, long unsigned int iova, struct scatterlist *sg, unsigned int nents, int prot, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81ad02d0)
Location: drivers/iommu/iommu.c:2500
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_map_sg_atomic
  - drivers/iommu/iommu.c:iommu_map_sg
```
**Symbols:**

```
ffffffff81ad02d0-ffffffff81ad0440: __iommu_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __iommu_map_sg(struct device *dev, struct scatterlist *sg, int nents, enum dma_data_direction dir, long unsigned int attrs, bool is_coherent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/mm/dma-mapping.c (c031d344)
Location: arch/arm/mm/dma-mapping.c:1658
Inline: False
Direct callers:
  - arch/arm/mm/dma-mapping.c:arm_iommu_map_sg
  - arch/arm/mm/dma-mapping.c:arm_coherent_iommu_map_sg
```
**Symbols:**

```
c031d344-c031d5ac: __iommu_map_sg (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>size_t</code> ➡️ <code>ssize_t</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
