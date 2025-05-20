# Function: <code>intel_iommu_sva_invalidate</code>

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
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int intel_iommu_sva_invalidate(struct iommu_domain *domain, struct device *dev, struct iommu_cache_invalidate_info *inv_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:5387
Inline: False
```
**Symbols:**

```
ffffffff817a3180-ffffffff817a3555: intel_iommu_sva_invalidate (STB_LOCAL)
ffffffff817a6e61-ffffffff817a6eda: intel_iommu_sva_invalidate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int intel_iommu_sva_invalidate(struct iommu_domain *domain, struct device *dev, struct iommu_cache_invalidate_info *inv_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:4808
Inline: False
```
**Symbols:**

```
ffffffff817b1260-ffffffff817b16ba: intel_iommu_sva_invalidate (STB_LOCAL)
ffffffff81c0cafc-ffffffff81c0cb7d: intel_iommu_sva_invalidate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int intel_iommu_sva_invalidate(struct iommu_domain *domain, struct device *dev, struct iommu_cache_invalidate_info *inv_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:4908
Inline: False
```
**Symbols:**

```
ffffffff81793de0-ffffffff81794244: intel_iommu_sva_invalidate (STB_LOCAL)
ffffffff81bfe27e-ffffffff81bfe2f7: intel_iommu_sva_invalidate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int intel_iommu_sva_invalidate(struct iommu_domain *domain, struct device *dev, struct iommu_cache_invalidate_info *inv_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:4899
Inline: False
```
**Symbols:**

```
ffffffff8181bc90-ffffffff8181c14a: intel_iommu_sva_invalidate (STB_LOCAL)
ffffffff81cffff8-ffffffff81d000e9: intel_iommu_sva_invalidate.cold (STB_LOCAL)
```
</details>
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
