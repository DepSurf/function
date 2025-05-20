# Function: <code>intel_svm_bind_mm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int intel_svm_bind_mm(struct device *dev, int *pasid, int flags, struct svm_dev_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff8153bf70)
Location: drivers/iommu/intel-svm.c:287
Inline: False
```
**Symbols:**

```
ffffffff8153bf70-ffffffff8153c41d: intel_svm_bind_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int intel_svm_bind_mm(struct device *dev, int *pasid, int flags, struct svm_dev_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff81590ac0)
Location: drivers/iommu/intel-svm.c:287
Inline: False
```
**Symbols:**

```
ffffffff81590ac0-ffffffff81590f9f: intel_svm_bind_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int intel_svm_bind_mm(struct device *dev, int *pasid, int flags, struct svm_dev_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff815be350)
Location: drivers/iommu/intel-svm.c:293
Inline: False
```
**Symbols:**

```
ffffffff815be350-ffffffff815be827: intel_svm_bind_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int intel_svm_bind_mm(struct device *dev, int *pasid, int flags, struct svm_dev_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff815d3f60)
Location: drivers/iommu/intel-svm.c:285
Inline: False
```
**Symbols:**

```
ffffffff815d3f60-ffffffff815d4450: intel_svm_bind_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int intel_svm_bind_mm(struct device *dev, int *pasid, int flags, struct svm_dev_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff8163acb0)
Location: drivers/iommu/intel-svm.c:289
Inline: False
```
**Symbols:**

```
ffffffff8163acb0-ffffffff8163b1d8: intel_svm_bind_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int intel_svm_bind_mm(struct device *dev, int *pasid, int flags, struct svm_dev_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff816762a0)
Location: drivers/iommu/intel-svm.c:302
Inline: False
```
**Symbols:**

```
ffffffff816762a0-ffffffff81676794: intel_svm_bind_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int intel_svm_bind_mm(struct device *dev, int *pasid, int flags, struct svm_dev_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff81695020)
Location: drivers/iommu/intel-svm.c:237
Inline: False
```
**Symbols:**

```
ffffffff81695020-ffffffff81695525: intel_svm_bind_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int intel_svm_bind_mm(struct device *dev, int *pasid, int flags, struct svm_dev_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-svm.c (0)
Location: drivers/iommu/intel-svm.c:214
Inline: False
```
**Symbols:**

```
ffffffff816ce4ee-ffffffff816ce508: intel_svm_bind_mm.cold (STB_LOCAL)
ffffffff816cdd20-ffffffff816ce2e1: intel_svm_bind_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int intel_svm_bind_mm(struct device *dev, int *pasid, int flags, struct svm_dev_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-svm.c (0)
Location: drivers/iommu/intel-svm.c:210
Inline: False
```
**Symbols:**

```
ffffffff816f231b-ffffffff816f2335: intel_svm_bind_mm.cold (STB_LOCAL)
ffffffff816f1b70-ffffffff816f2130: intel_svm_bind_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/svm.c (0)
Location: drivers/iommu/intel/svm.c:426
Inline: True
Direct callers:
  - drivers/iommu/intel/svm.c:intel_svm_bind
```
**Symbols:**

```
ffffffff817a9b30-ffffffff817a9fa9: intel_svm_bind_mm.constprop.0 (STB_LOCAL)
ffffffff817aa821-ffffffff817aa854: intel_svm_bind_mm.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/svm.c (0)
Location: drivers/iommu/intel/svm.c:501
Inline: True
Direct callers:
  - drivers/iommu/intel/svm.c:intel_svm_bind
```
**Symbols:**

```
ffffffff817b5d40-ffffffff817b6272: intel_svm_bind_mm.constprop.0 (STB_LOCAL)
ffffffff81c0cf4c-ffffffff81c0cf7f: intel_svm_bind_mm.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/svm.c (0)
Location: drivers/iommu/intel/svm.c:464
Inline: True
Direct callers:
  - drivers/iommu/intel/svm.c:intel_svm_bind
```
**Symbols:**

```
ffffffff81799030-ffffffff8179950d: intel_svm_bind_mm.constprop.0 (STB_LOCAL)
ffffffff81bff2e4-ffffffff81bff317: intel_svm_bind_mm.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct iommu_sva *intel_svm_bind_mm(struct intel_iommu *iommu, struct device *dev, struct mm_struct *mm, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff81821660)
Location: drivers/iommu/intel/svm.c:537
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:intel_svm_bind
```
**Symbols:**

```
ffffffff81821660-ffffffff81821962: intel_svm_bind_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct iommu_sva *intel_svm_bind_mm(struct intel_iommu *iommu, struct device *dev, struct mm_struct *mm, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff81961810)
Location: drivers/iommu/intel/svm.c:325
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:intel_svm_bind
```
**Symbols:**

```
ffffffff81961810-ffffffff81961b3e: intel_svm_bind_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct iommu_sva *intel_svm_bind_mm(struct intel_iommu *iommu, struct device *dev, struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff81aca320)
Location: drivers/iommu/intel/svm.c:302
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:intel_svm_set_dev_pasid
```
**Symbols:**

```
ffffffff81aca320-ffffffff81aca5f7: intel_svm_bind_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int intel_svm_bind_mm(struct intel_iommu *iommu, struct device *dev, struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff81b17080)
Location: drivers/iommu/intel/svm.c:300
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:intel_svm_set_dev_pasid
```
**Symbols:**

```
ffffffff81b17080-ffffffff81b1730b: intel_svm_bind_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff81b6c570)
Location: drivers/iommu/intel/svm.c:318
Inline: True
Direct callers:
  - drivers/iommu/intel/svm.c:intel_svm_set_dev_pasid
```
**Symbols:**

```
ffffffff81b6c570-ffffffff81b6c873: intel_svm_bind_mm.isra.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int intel_svm_bind_mm(struct device *dev, int *pasid, int flags, struct svm_dev_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-svm.c (0)
Location: drivers/iommu/intel-svm.c:210
Inline: False
```
**Symbols:**

```
ffffffff816b7b0b-ffffffff816b7b25: intel_svm_bind_mm.cold (STB_LOCAL)
ffffffff816b7360-ffffffff816b7920: intel_svm_bind_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int intel_svm_bind_mm(struct device *dev, int *pasid, int flags, struct svm_dev_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-svm.c (0)
Location: drivers/iommu/intel-svm.c:210
Inline: False
```
**Symbols:**

```
ffffffff8169574b-ffffffff81695765: intel_svm_bind_mm.cold (STB_LOCAL)
ffffffff81694fa0-ffffffff81695560: intel_svm_bind_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int intel_svm_bind_mm(struct device *dev, int *pasid, int flags, struct svm_dev_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-svm.c (0)
Location: drivers/iommu/intel-svm.c:210
Inline: False
```
**Symbols:**

```
ffffffff816e5fdb-ffffffff816e5ff5: intel_svm_bind_mm.cold (STB_LOCAL)
ffffffff816e5830-ffffffff816e5df0: intel_svm_bind_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int intel_svm_bind_mm(struct device *dev, int *pasid, int flags, struct svm_dev_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-svm.c (0)
Location: drivers/iommu/intel-svm.c:210
Inline: False
```
**Symbols:**

```
ffffffff817006db-ffffffff817006f5: intel_svm_bind_mm.cold (STB_LOCAL)
ffffffff816ffaf0-ffffffff817000c0: intel_svm_bind_mm (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int flags</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>struct iommu_sva *</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
