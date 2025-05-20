# Function: <code>__iommu_release_dma_ownership</code>

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
<summary>In <code>6.2</code>: ✅</summary>

```c
void __iommu_release_dma_ownership(struct iommu_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81ad0b00)
Location: drivers/iommu/iommu.c:3237
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_device_release_dma_owner
  - drivers/iommu/iommu.c:iommu_group_release_dma_owner
```
**Symbols:**

```
ffffffff81ad0b00-ffffffff81ad0b7c: __iommu_release_dma_ownership (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __iommu_release_dma_ownership(struct iommu_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b1e5e0)
Location: drivers/iommu/iommu.c:3193
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_device_release_dma_owner
  - drivers/iommu/iommu.c:iommu_group_release_dma_owner
```
**Symbols:**

```
ffffffff81b1e5e0-ffffffff81b1e65b: __iommu_release_dma_ownership (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __iommu_release_dma_ownership(struct iommu_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b768d0)
Location: drivers/iommu/iommu.c:3435
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_device_release_dma_owner
  - drivers/iommu/iommu.c:iommu_group_release_dma_owner
```
**Symbols:**

```
ffffffff81b768d0-ffffffff81b76a23: __iommu_release_dma_ownership (STB_LOCAL)
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
