# Function: <code>iova_domain_init_rcaches</code>

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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int iova_domain_init_rcaches(struct iova_domain *iovad);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff8196e070)
Location: drivers/iommu/iova.c:711
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_init_domain
```
**Symbols:**

```
ffffffff8196e070-ffffffff8196e1ea: iova_domain_init_rcaches (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int iova_domain_init_rcaches(struct iova_domain *iovad);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81ad89d0)
Location: drivers/iommu/iova.c:714
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_init_domain
```
**Symbols:**

```
ffffffff81ad89d0-ffffffff81ad8b4f: iova_domain_init_rcaches (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int iova_domain_init_rcaches(struct iova_domain *iovad);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81b26640)
Location: drivers/iommu/iova.c:720
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_init_domain
```
**Symbols:**

```
ffffffff81b26640-ffffffff81b267b0: iova_domain_init_rcaches.part.0 (STB_LOCAL)
ffffffff81b267c0-ffffffff81b2680b: iova_domain_init_rcaches (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int iova_domain_init_rcaches(struct iova_domain *iovad);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81b7d940)
Location: drivers/iommu/iova.c:764
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_init_domain
```
**Symbols:**

```
ffffffff81b7d940-ffffffff81b7db48: iova_domain_init_rcaches.part.0 (STB_LOCAL)
ffffffff81b7db60-ffffffff81b7dbda: iova_domain_init_rcaches (STB_GLOBAL)
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
