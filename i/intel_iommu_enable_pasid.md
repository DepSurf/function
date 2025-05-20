# Function: <code>intel_iommu_enable_pasid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int intel_iommu_enable_pasid(struct intel_iommu *iommu, struct intel_svm_dev *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8153b210)
Location: drivers/iommu/intel-iommu.c:4992
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff8153b210-ffffffff8153b4be: intel_iommu_enable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int intel_iommu_enable_pasid(struct intel_iommu *iommu, struct intel_svm_dev *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8158fce0)
Location: drivers/iommu/intel-iommu.c:5130
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff8158fce0-ffffffff8158ffca: intel_iommu_enable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int intel_iommu_enable_pasid(struct intel_iommu *iommu, struct intel_svm_dev *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815bd540)
Location: drivers/iommu/intel-iommu.c:5281
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff815bd540-ffffffff815bd85d: intel_iommu_enable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int intel_iommu_enable_pasid(struct intel_iommu *iommu, struct intel_svm_dev *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815d3150)
Location: drivers/iommu/intel-iommu.c:5315
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff815d3150-ffffffff815d3452: intel_iommu_enable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int intel_iommu_enable_pasid(struct intel_iommu *iommu, struct intel_svm_dev *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81639e50)
Location: drivers/iommu/intel-iommu.c:5229
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff81639e50-ffffffff8163a15f: intel_iommu_enable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int intel_iommu_enable_pasid(struct intel_iommu *iommu, struct intel_svm_dev *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81674fe0)
Location: drivers/iommu/intel-iommu.c:5267
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff81674fe0-ffffffff816752d2: intel_iommu_enable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int intel_iommu_enable_pasid(struct intel_iommu *iommu, struct intel_svm_dev *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816935f0)
Location: drivers/iommu/intel-iommu.c:5303
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff816935f0-ffffffff8169377c: intel_iommu_enable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int intel_iommu_enable_pasid(struct intel_iommu *iommu, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:5448
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_dev_enable_feat
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff816cc696-ffffffff816cc6a9: intel_iommu_enable_pasid.cold (STB_LOCAL)
ffffffff816cba10-ffffffff816cbb2b: intel_iommu_enable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int intel_iommu_enable_pasid(struct intel_iommu *iommu, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816ef2f0)
Location: drivers/iommu/intel-iommu.c:5742
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_dev_enable_feat
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff816ef2f0-ffffffff816ef40e: intel_iommu_enable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int intel_iommu_enable_pasid(struct intel_iommu *iommu, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a66d0)
Location: drivers/iommu/intel/iommu.c:5762
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_enable_feat
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
```
**Symbols:**

```
ffffffff817a66d0-ffffffff817a682f: intel_iommu_enable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int intel_iommu_enable_pasid(struct intel_iommu *iommu, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817b30b0)
Location: drivers/iommu/intel/iommu.c:5204
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_enable_feat
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
```
**Symbols:**

```
ffffffff817b30b0-ffffffff817b320e: intel_iommu_enable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int intel_iommu_enable_pasid(struct intel_iommu *iommu, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817960c0)
Location: drivers/iommu/intel/iommu.c:5248
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
```
**Symbols:**

```
ffffffff817960c0-ffffffff8179621e: intel_iommu_enable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int intel_iommu_enable_pasid(struct intel_iommu *iommu, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8181df90)
Location: drivers/iommu/intel/iommu.c:5265
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
```
**Symbols:**

```
ffffffff8181df90-ffffffff8181e113: intel_iommu_enable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int intel_iommu_enable_pasid(struct intel_iommu *iommu, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8195e440)
Location: drivers/iommu/intel/iommu.c:4719
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_enable_feat
```
**Symbols:**

```
ffffffff8195e440-ffffffff8195e58d: intel_iommu_enable_pasid (STB_GLOBAL)
```
</details>
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
int intel_iommu_enable_pasid(struct intel_iommu *iommu, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816b4ae0)
Location: drivers/iommu/intel-iommu.c:5742
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_dev_enable_feat
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff816b4ae0-ffffffff816b4bfe: intel_iommu_enable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int intel_iommu_enable_pasid(struct intel_iommu *iommu, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81692720)
Location: drivers/iommu/intel-iommu.c:5742
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_dev_enable_feat
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff81692720-ffffffff8169283e: intel_iommu_enable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int intel_iommu_enable_pasid(struct intel_iommu *iommu, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816e2fb0)
Location: drivers/iommu/intel-iommu.c:5742
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_dev_enable_feat
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff816e2fb0-ffffffff816e30ce: intel_iommu_enable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int intel_iommu_enable_pasid(struct intel_iommu *iommu, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816fd630)
Location: drivers/iommu/intel-iommu.c:5742
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_dev_enable_feat
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff816fd630-ffffffff816fd751: intel_iommu_enable_pasid (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device *dev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct intel_svm_dev *sdev</code>
</li>
</ul>
</details>
</li>
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
