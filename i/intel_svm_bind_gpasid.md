# Function: <code>intel_svm_bind_gpasid</code>

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
int intel_svm_bind_gpasid(struct iommu_domain *domain, struct device *dev, struct iommu_gpasid_bind_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/svm.c (0)
Location: drivers/iommu/intel/svm.c:231
Inline: False
```
**Symbols:**

```
ffffffff817aa8ee-ffffffff817aa94b: intel_svm_bind_gpasid.cold (STB_LOCAL)
ffffffff817aa1b0-ffffffff817aa513: intel_svm_bind_gpasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int intel_svm_bind_gpasid(struct iommu_domain *domain, struct device *dev, struct iommu_gpasid_bind_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/svm.c (0)
Location: drivers/iommu/intel/svm.c:294
Inline: False
```
**Symbols:**

```
ffffffff81c0d019-ffffffff81c0d069: intel_svm_bind_gpasid.cold (STB_LOCAL)
ffffffff817b6650-ffffffff817b69cf: intel_svm_bind_gpasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int intel_svm_bind_gpasid(struct iommu_domain *domain, struct device *dev, struct iommu_gpasid_bind_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/svm.c (0)
Location: drivers/iommu/intel/svm.c:257
Inline: False
```
**Symbols:**

```
ffffffff81bff3b1-ffffffff81bff40e: intel_svm_bind_gpasid.cold (STB_LOCAL)
ffffffff817998f0-ffffffff81799c8c: intel_svm_bind_gpasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int intel_svm_bind_gpasid(struct iommu_domain *domain, struct device *dev, struct iommu_gpasid_bind_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/svm.c (0)
Location: drivers/iommu/intel/svm.c:321
Inline: False
```
**Symbols:**

```
ffffffff81d0136b-ffffffff81d013c8: intel_svm_bind_gpasid.cold (STB_LOCAL)
ffffffff81821e50-ffffffff818221f1: intel_svm_bind_gpasid (STB_GLOBAL)
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
