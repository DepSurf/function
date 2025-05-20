# Function: <code>intel_svm_free_pasid_tables</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int intel_svm_free_pasid_tables(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff8153c510)
Location: drivers/iommu/intel-svm.c:69
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
```
**Symbols:**

```
ffffffff8153c510-ffffffff8153c588: intel_svm_free_pasid_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int intel_svm_free_pasid_tables(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff81591090)
Location: drivers/iommu/intel-svm.c:69
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
```
**Symbols:**

```
ffffffff81591090-ffffffff81591108: intel_svm_free_pasid_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int intel_svm_free_pasid_tables(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff815be960)
Location: drivers/iommu/intel-svm.c:79
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
```
**Symbols:**

```
ffffffff815be960-ffffffff815be9df: intel_svm_free_pasid_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int intel_svm_free_pasid_tables(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff815d4580)
Location: drivers/iommu/intel-svm.c:80
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
```
**Symbols:**

```
ffffffff815d4580-ffffffff815d45ff: intel_svm_free_pasid_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int intel_svm_free_pasid_tables(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff8163b310)
Location: drivers/iommu/intel-svm.c:81
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
```
**Symbols:**

```
ffffffff8163b310-ffffffff8163b38f: intel_svm_free_pasid_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int intel_svm_free_pasid_tables(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff81676830)
Location: drivers/iommu/intel-svm.c:93
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
```
**Symbols:**

```
ffffffff81676830-ffffffff816768af: intel_svm_free_pasid_tables (STB_GLOBAL)
```
</details>
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
</ul>
