# Function: <code>intel_pasid_free_id</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void intel_pasid_free_id(int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff81693f00)
Location: drivers/iommu/intel-pasid.c:48
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff81693f00-ffffffff81693f38: intel_pasid_free_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void intel_pasid_free_id(int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff816cc810)
Location: drivers/iommu/intel-pasid.c:48
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff816cc810-ffffffff816cc848: intel_pasid_free_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void intel_pasid_free_id(int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff816f0050)
Location: drivers/iommu/intel-pasid.c:48
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff816f0050-ffffffff816f0088: intel_pasid_free_id (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void intel_pasid_free_id(int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff816b5840)
Location: drivers/iommu/intel-pasid.c:48
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff816b5840-ffffffff816b5878: intel_pasid_free_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void intel_pasid_free_id(int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff81693480)
Location: drivers/iommu/intel-pasid.c:48
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff81693480-ffffffff816934b8: intel_pasid_free_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void intel_pasid_free_id(int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff816e3d10)
Location: drivers/iommu/intel-pasid.c:48
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff816e3d10-ffffffff816e3d48: intel_pasid_free_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void intel_pasid_free_id(int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff816fe3e0)
Location: drivers/iommu/intel-pasid.c:48
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff816fe3e0-ffffffff816fe416: intel_pasid_free_id (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
