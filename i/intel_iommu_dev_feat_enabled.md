# Function: <code>intel_iommu_dev_feat_enabled</code>

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
bool intel_iommu_dev_feat_enabled(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816c7620)
Location: drivers/iommu/intel-iommu.c:5642
Inline: False
```
**Symbols:**

```
ffffffff816c7620-ffffffff816c7690: intel_iommu_dev_feat_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool intel_iommu_dev_feat_enabled(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816ea580)
Location: drivers/iommu/intel-iommu.c:5943
Inline: False
```
**Symbols:**

```
ffffffff816ea580-ffffffff816ea5f0: intel_iommu_dev_feat_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool intel_iommu_dev_feat_enabled(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a1840)
Location: drivers/iommu/intel/iommu.c:5981
Inline: False
```
**Symbols:**

```
ffffffff817a1840-ffffffff817a18be: intel_iommu_dev_feat_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool intel_iommu_dev_feat_enabled(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817af000)
Location: drivers/iommu/intel/iommu.c:5387
Inline: False
```
**Symbols:**

```
ffffffff817af000-ffffffff817af095: intel_iommu_dev_feat_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool intel_iommu_dev_feat_enabled(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817917c0)
Location: drivers/iommu/intel/iommu.c:5439
Inline: False
```
**Symbols:**

```
ffffffff817917c0-ffffffff81791822: intel_iommu_dev_feat_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool intel_iommu_dev_feat_enabled(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81818de0)
Location: drivers/iommu/intel/iommu.c:5500
Inline: False
```
**Symbols:**

```
ffffffff81818de0-ffffffff81818e42: intel_iommu_dev_feat_enabled (STB_LOCAL)
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
bool intel_iommu_dev_feat_enabled(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816b0060)
Location: drivers/iommu/intel-iommu.c:5943
Inline: False
```
**Symbols:**

```
ffffffff816b0060-ffffffff816b00d0: intel_iommu_dev_feat_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool intel_iommu_dev_feat_enabled(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168d9b0)
Location: drivers/iommu/intel-iommu.c:5943
Inline: False
```
**Symbols:**

```
ffffffff8168d9b0-ffffffff8168da20: intel_iommu_dev_feat_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool intel_iommu_dev_feat_enabled(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816de240)
Location: drivers/iommu/intel-iommu.c:5943
Inline: False
```
**Symbols:**

```
ffffffff816de240-ffffffff816de2b0: intel_iommu_dev_feat_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool intel_iommu_dev_feat_enabled(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816f8840)
Location: drivers/iommu/intel-iommu.c:5943
Inline: False
```
**Symbols:**

```
ffffffff816f8840-ffffffff816f88b9: intel_iommu_dev_feat_enabled (STB_LOCAL)
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
