# Function: <code>intel_iommu_aux_get_pasid</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int intel_iommu_aux_get_pasid(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816c5510)
Location: drivers/iommu/intel-iommu.c:5653
Inline: False
```
**Symbols:**

```
ffffffff816c5510-ffffffff816c5529: intel_iommu_aux_get_pasid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int intel_iommu_aux_get_pasid(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816e8450)
Location: drivers/iommu/intel-iommu.c:5954
Inline: False
```
**Symbols:**

```
ffffffff816e8450-ffffffff816e8469: intel_iommu_aux_get_pasid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int intel_iommu_aux_get_pasid(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8179eff0)
Location: drivers/iommu/intel/iommu.c:5992
Inline: False
```
**Symbols:**

```
ffffffff8179eff0-ffffffff8179f009: intel_iommu_aux_get_pasid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int intel_iommu_aux_get_pasid(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817ac890)
Location: drivers/iommu/intel/iommu.c:5398
Inline: False
```
**Symbols:**

```
ffffffff817ac890-ffffffff817ac8a8: intel_iommu_aux_get_pasid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int intel_iommu_aux_get_pasid(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8178f760)
Location: drivers/iommu/intel/iommu.c:5450
Inline: False
```
**Symbols:**

```
ffffffff8178f760-ffffffff8178f778: intel_iommu_aux_get_pasid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int intel_iommu_aux_get_pasid(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81817070)
Location: drivers/iommu/intel/iommu.c:5511
Inline: False
```
**Symbols:**

```
ffffffff81817070-ffffffff81817088: intel_iommu_aux_get_pasid (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int intel_iommu_aux_get_pasid(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816adf30)
Location: drivers/iommu/intel-iommu.c:5954
Inline: False
```
**Symbols:**

```
ffffffff816adf30-ffffffff816adf49: intel_iommu_aux_get_pasid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int intel_iommu_aux_get_pasid(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168b890)
Location: drivers/iommu/intel-iommu.c:5954
Inline: False
```
**Symbols:**

```
ffffffff8168b890-ffffffff8168b8a9: intel_iommu_aux_get_pasid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int intel_iommu_aux_get_pasid(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816dc110)
Location: drivers/iommu/intel-iommu.c:5954
Inline: False
```
**Symbols:**

```
ffffffff816dc110-ffffffff816dc129: intel_iommu_aux_get_pasid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int intel_iommu_aux_get_pasid(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816f66e0)
Location: drivers/iommu/intel-iommu.c:5954
Inline: False
```
**Symbols:**

```
ffffffff816f66e0-ffffffff816f66f9: intel_iommu_aux_get_pasid (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
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
