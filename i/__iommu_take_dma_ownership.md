# Function: <code>__iommu_take_dma_ownership</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int __iommu_take_dma_ownership(struct iommu_group *group, void *owner);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81ad0620)
Location: drivers/iommu/iommu.c:3147
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:iommu_device_claim_dma_owner
  - drivers/iommu/iommu.c:iommu_group_claim_dma_owner
```
**Symbols:**

```
ffffffff81ad0620-ffffffff81ad06d8: __iommu_take_dma_ownership (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int __iommu_take_dma_ownership(struct iommu_group *group, void *owner);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b1e740)
Location: drivers/iommu/iommu.c:3103
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:iommu_device_claim_dma_owner
  - drivers/iommu/iommu.c:iommu_group_claim_dma_owner
```
**Symbols:**

```
ffffffff81b1e740-ffffffff81b1e800: __iommu_take_dma_ownership (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int __iommu_take_dma_ownership(struct iommu_group *group, void *owner);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b74f20)
Location: drivers/iommu/iommu.c:3347
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:iommu_device_claim_dma_owner
  - drivers/iommu/iommu.c:iommu_group_claim_dma_owner
```
**Symbols:**

```
ffffffff81b74f20-ffffffff81b74fec: __iommu_take_dma_ownership (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
