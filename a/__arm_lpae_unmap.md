# Function: <code>__arm_lpae_unmap</code>

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
In <code>6.2</code>: Absent ⚠️
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
size_t __arm_lpae_unmap(struct arm_lpae_io_pgtable *data, struct iommu_iotlb_gather *gather, long unsigned int iova, size_t size, int lvl, arm_lpae_iopte *ptep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/io-pgtable-arm.c (ffff8000108cc040)
Location: drivers/iommu/io-pgtable-arm.c:598
Inline: False
Direct callers:
  - drivers/iommu/io-pgtable-arm.c:arm_lpae_unmap
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_unmap
  - drivers/iommu/io-pgtable-arm.c:arm_lpae_split_blk_unmap
  - drivers/iommu/io-pgtable-arm.c:arm_lpae_init_pte
```
**Symbols:**

```
ffff8000108cc040-ffff8000108cc310: __arm_lpae_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
size_t __arm_lpae_unmap(struct arm_lpae_io_pgtable *data, struct iommu_iotlb_gather *gather, long unsigned int iova, size_t size, int lvl, arm_lpae_iopte *ptep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/io-pgtable-arm.c (c09c07a8)
Location: drivers/iommu/io-pgtable-arm.c:598
Inline: False
Direct callers:
  - drivers/iommu/io-pgtable-arm.c:arm_lpae_unmap
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_unmap
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_unmap
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_map
```
**Symbols:**

```
c09c07a8-c09c0ca0: __arm_lpae_unmap (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
