# Function: <code>iommu_dma_alloc_noncontiguous</code>

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
struct sg_table *iommu_dma_alloc_noncontiguous(struct device *dev, size_t size, enum dma_data_direction dir, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff8196c440)
Location: drivers/iommu/dma-iommu.c:871
Inline: False
```
**Symbols:**

```
ffffffff8196c440-ffffffff8196c532: iommu_dma_alloc_noncontiguous (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sg_table *iommu_dma_alloc_noncontiguous(struct device *dev, size_t size, enum dma_data_direction dir, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81ad6730)
Location: drivers/iommu/dma-iommu.c:879
Inline: False
```
**Symbols:**

```
ffffffff81ad6730-ffffffff81ad681f: iommu_dma_alloc_noncontiguous (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sg_table *iommu_dma_alloc_noncontiguous(struct device *dev, size_t size, enum dma_data_direction dir, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81b24f00)
Location: drivers/iommu/dma-iommu.c:920
Inline: False
```
**Symbols:**

```
ffffffff81b24f00-ffffffff81b24fef: iommu_dma_alloc_noncontiguous (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sg_table *iommu_dma_alloc_noncontiguous(struct device *dev, size_t size, enum dma_data_direction dir, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81b7bb70)
Location: drivers/iommu/dma-iommu.c:1039
Inline: False
```
**Symbols:**

```
ffffffff81b7bb70-ffffffff81b7bc7b: iommu_dma_alloc_noncontiguous (STB_LOCAL)
```
</details>
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
