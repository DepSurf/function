# Function: <code>intel_iommu_dev_disable_feat</code>

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
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int intel_iommu_dev_disable_feat(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:5633
Inline: False
```
**Symbols:**

```
ffffffff816c6c70-ffffffff816c6cc3: intel_iommu_dev_disable_feat (STB_LOCAL)
ffffffff816cbdb1-ffffffff816cbdcc: intel_iommu_dev_disable_feat.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int intel_iommu_dev_disable_feat(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816e9990)
Location: drivers/iommu/intel-iommu.c:5934
Inline: False
```
**Symbols:**

```
ffffffff816e9990-ffffffff816e99db: intel_iommu_dev_disable_feat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int intel_iommu_dev_disable_feat(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8179f110)
Location: drivers/iommu/intel/iommu.c:5972
Inline: False
```
**Symbols:**

```
ffffffff8179f110-ffffffff8179f16d: intel_iommu_dev_disable_feat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int intel_iommu_dev_disable_feat(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817ac8e0)
Location: drivers/iommu/intel/iommu.c:5378
Inline: False
```
**Symbols:**

```
ffffffff817ac8e0-ffffffff817ac942: intel_iommu_dev_disable_feat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int intel_iommu_dev_disable_feat(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8178f7b0)
Location: drivers/iommu/intel/iommu.c:5430
Inline: False
```
**Symbols:**

```
ffffffff8178f7b0-ffffffff8178f812: intel_iommu_dev_disable_feat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int intel_iommu_dev_disable_feat(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff818175c0)
Location: drivers/iommu/intel/iommu.c:5482
Inline: False
```
**Symbols:**

```
ffffffff818175c0-ffffffff8181767c: intel_iommu_dev_disable_feat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int intel_iommu_dev_disable_feat(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff819586a0)
Location: drivers/iommu/intel/iommu.c:4844
Inline: False
```
**Symbols:**

```
ffffffff819586a0-ffffffff81958719: intel_iommu_dev_disable_feat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int intel_iommu_dev_disable_feat(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81abf750)
Location: drivers/iommu/intel/iommu.c:4719
Inline: False
```
**Symbols:**

```
ffffffff81abf750-ffffffff81abf7e2: intel_iommu_dev_disable_feat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int intel_iommu_dev_disable_feat(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b0bfb0)
Location: drivers/iommu/intel/iommu.c:4677
Inline: False
```
**Symbols:**

```
ffffffff81b0bfb0-ffffffff81b0c049: intel_iommu_dev_disable_feat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int intel_iommu_dev_disable_feat(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b60170)
Location: drivers/iommu/intel/iommu.c:4576
Inline: False
```
**Symbols:**

```
ffffffff81b60170-ffffffff81b60209: intel_iommu_dev_disable_feat (STB_LOCAL)
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
int intel_iommu_dev_disable_feat(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816af470)
Location: drivers/iommu/intel-iommu.c:5934
Inline: False
```
**Symbols:**

```
ffffffff816af470-ffffffff816af4bb: intel_iommu_dev_disable_feat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int intel_iommu_dev_disable_feat(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168cdc0)
Location: drivers/iommu/intel-iommu.c:5934
Inline: False
```
**Symbols:**

```
ffffffff8168cdc0-ffffffff8168ce0b: intel_iommu_dev_disable_feat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int intel_iommu_dev_disable_feat(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816dd650)
Location: drivers/iommu/intel-iommu.c:5934
Inline: False
```
**Symbols:**

```
ffffffff816dd650-ffffffff816dd69b: intel_iommu_dev_disable_feat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int intel_iommu_dev_disable_feat(struct device *dev, enum iommu_dev_features feat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816f79f0)
Location: drivers/iommu/intel-iommu.c:5934
Inline: False
```
**Symbols:**

```
ffffffff816f79f0-ffffffff816f7a3b: intel_iommu_dev_disable_feat (STB_LOCAL)
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
