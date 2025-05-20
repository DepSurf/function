# Function: <code>intel_iommu_dev_has_feat</code>

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
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool intel_iommu_dev_has_feat(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816c6cd0)
Location: drivers/iommu/intel-iommu.c:5604
Inline: True
```
**Symbols:**

```
ffffffff816c6cd0-ffffffff816c6e64: intel_iommu_dev_has_feat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool intel_iommu_dev_has_feat(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816e9c30)
Location: drivers/iommu/intel-iommu.c:5905
Inline: True
```
**Symbols:**

```
ffffffff816e9c30-ffffffff816e9dc4: intel_iommu_dev_has_feat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool intel_iommu_dev_has_feat(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8179f450)
Location: drivers/iommu/intel/iommu.c:5925
Inline: False
```
**Symbols:**

```
ffffffff8179f450-ffffffff8179f641: intel_iommu_dev_has_feat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool intel_iommu_dev_has_feat(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817acf20)
Location: drivers/iommu/intel/iommu.c:5331
Inline: False
```
**Symbols:**

```
ffffffff817acf20-ffffffff817ad156: intel_iommu_dev_has_feat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool intel_iommu_dev_has_feat(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81791be0)
Location: drivers/iommu/intel/iommu.c:5375
Inline: True
```
**Symbols:**

```
ffffffff81791be0-ffffffff81791d93: intel_iommu_dev_has_feat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool intel_iommu_dev_has_feat(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81819310)
Location: drivers/iommu/intel/iommu.c:5434
Inline: True
```
**Symbols:**

```
ffffffff81819310-ffffffff818194c3: intel_iommu_dev_has_feat (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool intel_iommu_dev_has_feat(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816af710)
Location: drivers/iommu/intel-iommu.c:5905
Inline: True
```
**Symbols:**

```
ffffffff816af710-ffffffff816af8a4: intel_iommu_dev_has_feat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool intel_iommu_dev_has_feat(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168d060)
Location: drivers/iommu/intel-iommu.c:5905
Inline: True
```
**Symbols:**

```
ffffffff8168d060-ffffffff8168d1f4: intel_iommu_dev_has_feat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool intel_iommu_dev_has_feat(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816dd8f0)
Location: drivers/iommu/intel-iommu.c:5905
Inline: True
```
**Symbols:**

```
ffffffff816dd8f0-ffffffff816dda84: intel_iommu_dev_has_feat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool intel_iommu_dev_has_feat(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816f7f10)
Location: drivers/iommu/intel-iommu.c:5905
Inline: True
```
**Symbols:**

```
ffffffff816f7f10-ffffffff816f808e: intel_iommu_dev_has_feat (STB_LOCAL)
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
