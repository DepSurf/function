# Function: <code>iommu_map_sg_atomic</code>

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
size_t iommu_map_sg_atomic(struct iommu_domain *domain, long unsigned int iova, struct scatterlist *sg, unsigned int nents, int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff817903e0)
Location: drivers/iommu/iommu.c:2374
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
```
**Symbols:**

```
ffffffff817903e0-ffffffff817903f6: iommu_map_sg_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t iommu_map_sg_atomic(struct iommu_domain *domain, long unsigned int iova, struct scatterlist *sg, unsigned int nents, int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff817bb8d0)
Location: drivers/iommu/iommu.c:2597
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
```
**Symbols:**

```
ffffffff817bb8d0-ffffffff817bb8e6: iommu_map_sg_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
size_t iommu_map_sg_atomic(struct iommu_domain *domain, long unsigned int iova, struct scatterlist *sg, unsigned int nents, int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8179f8d0)
Location: drivers/iommu/iommu.c:2628
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
```
**Symbols:**

```
ffffffff8179f8d0-ffffffff8179f8e6: iommu_map_sg_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t iommu_map_sg_atomic(struct iommu_domain *domain, long unsigned int iova, struct scatterlist *sg, unsigned int nents, int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff818288c0)
Location: drivers/iommu/iommu.c:2713
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
```
**Symbols:**

```
ffffffff818288c0-ffffffff818288d6: iommu_map_sg_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t iommu_map_sg_atomic(struct iommu_domain *domain, long unsigned int iova, struct scatterlist *sg, unsigned int nents, int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81968850)
Location: drivers/iommu/iommu.c:2490
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
```
**Symbols:**

```
ffffffff81968850-ffffffff81968878: iommu_map_sg_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t iommu_map_sg_atomic(struct iommu_domain *domain, long unsigned int iova, struct scatterlist *sg, unsigned int nents, int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81ad25e0)
Location: drivers/iommu/iommu.c:2558
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
```
**Symbols:**

```
ffffffff81ad25e0-ffffffff81ad2608: iommu_map_sg_atomic (STB_GLOBAL)
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
In <code>armhf</code>: Absent ⚠️
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
