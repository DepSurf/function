# Function: <code>intel_iommu_dev_enable_feat</code>

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
int intel_iommu_dev_enable_feat(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816cbb30)
Location: drivers/iommu/intel-iommu.c:5624
Inline: False
```
**Symbols:**

```
ffffffff816cbb30-ffffffff816cbc02: intel_iommu_dev_enable_feat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int intel_iommu_dev_enable_feat(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816ef410)
Location: drivers/iommu/intel-iommu.c:5925
Inline: False
```
**Symbols:**

```
ffffffff816ef410-ffffffff816ef4e2: intel_iommu_dev_enable_feat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int intel_iommu_dev_enable_feat(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a6830)
Location: drivers/iommu/intel/iommu.c:5953
Inline: False
```
**Symbols:**

```
ffffffff817a6830-ffffffff817a6962: intel_iommu_dev_enable_feat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int intel_iommu_dev_enable_feat(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817b3210)
Location: drivers/iommu/intel/iommu.c:5359
Inline: False
```
**Symbols:**

```
ffffffff817b3210-ffffffff817b3314: intel_iommu_dev_enable_feat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int intel_iommu_dev_enable_feat(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81796220)
Location: drivers/iommu/intel/iommu.c:5405
Inline: True
```
**Symbols:**

```
ffffffff81796220-ffffffff81796363: intel_iommu_dev_enable_feat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int intel_iommu_dev_enable_feat(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8181e120)
Location: drivers/iommu/intel/iommu.c:5464
Inline: True
```
**Symbols:**

```
ffffffff8181e120-ffffffff8181e2f4: intel_iommu_dev_enable_feat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int intel_iommu_dev_enable_feat(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8195e590)
Location: drivers/iommu/intel/iommu.c:4829
Inline: False
```
**Symbols:**

```
ffffffff8195e590-ffffffff8195e695: intel_iommu_dev_enable_feat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int intel_iommu_dev_enable_feat(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81ac0850)
Location: drivers/iommu/intel/iommu.c:4704
Inline: False
```
**Symbols:**

```
ffffffff81ac0850-ffffffff81ac093c: intel_iommu_dev_enable_feat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int intel_iommu_dev_enable_feat(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b0d000)
Location: drivers/iommu/intel/iommu.c:4662
Inline: False
```
**Symbols:**

```
ffffffff81b0d000-ffffffff81b0d1a1: intel_iommu_dev_enable_feat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int intel_iommu_dev_enable_feat(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b61a10)
Location: drivers/iommu/intel/iommu.c:4561
Inline: False
```
**Symbols:**

```
ffffffff81b61a10-ffffffff81b61bb1: intel_iommu_dev_enable_feat (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int intel_iommu_dev_enable_feat(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816b4c00)
Location: drivers/iommu/intel-iommu.c:5925
Inline: False
```
**Symbols:**

```
ffffffff816b4c00-ffffffff816b4cd2: intel_iommu_dev_enable_feat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int intel_iommu_dev_enable_feat(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81692840)
Location: drivers/iommu/intel-iommu.c:5925
Inline: False
```
**Symbols:**

```
ffffffff81692840-ffffffff81692912: intel_iommu_dev_enable_feat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int intel_iommu_dev_enable_feat(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816e30d0)
Location: drivers/iommu/intel-iommu.c:5925
Inline: False
```
**Symbols:**

```
ffffffff816e30d0-ffffffff816e31a2: intel_iommu_dev_enable_feat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int intel_iommu_dev_enable_feat(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816fd760)
Location: drivers/iommu/intel-iommu.c:5925
Inline: False
```
**Symbols:**

```
ffffffff816fd760-ffffffff816fd832: intel_iommu_dev_enable_feat (STB_LOCAL)
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
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
