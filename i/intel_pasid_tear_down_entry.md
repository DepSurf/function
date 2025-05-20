# Function: <code>intel_pasid_tear_down_entry</code>

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
void intel_pasid_tear_down_entry(struct intel_iommu *iommu, struct device *dev, int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff81694360)
Location: drivers/iommu/intel-pasid.c:459
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/iommu/intel-svm.c:intel_mm_release
```
**Symbols:**

```
ffffffff81694360-ffffffff816944fc: intel_pasid_tear_down_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void intel_pasid_tear_down_entry(struct intel_iommu *iommu, struct device *dev, int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-pasid.c (0)
Location: drivers/iommu/intel-pasid.c:444
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/iommu/intel-svm.c:intel_mm_release
```
**Symbols:**

```
ffffffff816cd489-ffffffff816cd4af: intel_pasid_tear_down_entry.cold (STB_LOCAL)
ffffffff816ccc80-ffffffff816cce1a: intel_pasid_tear_down_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void intel_pasid_tear_down_entry(struct intel_iommu *iommu, struct device *dev, int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff816f04d0)
Location: drivers/iommu/intel-pasid.c:444
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/iommu/intel-svm.c:intel_mm_release
```
**Symbols:**

```
ffffffff816f04d0-ffffffff816f0670: intel_pasid_tear_down_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void intel_pasid_tear_down_entry(struct intel_iommu *iommu, struct device *dev, int pasid, bool fault_ignore);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff817a7bd0)
Location: drivers/iommu/intel/pasid.c:492
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_aux_detach_device
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel/svm.c:intel_svm_unbind_gpasid
  - drivers/iommu/intel/svm.c:intel_mm_release
```
**Symbols:**

```
ffffffff817a7bd0-ffffffff817a7da4: intel_pasid_tear_down_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void intel_pasid_tear_down_entry(struct intel_iommu *iommu, struct device *dev, u32 pasid, bool fault_ignore);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff817b3a70)
Location: drivers/iommu/intel/pasid.c:500
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:aux_domain_remove_dev
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel/svm.c:intel_svm_unbind_gpasid
  - drivers/iommu/intel/svm.c:intel_mm_release
```
**Symbols:**

```
ffffffff817b3a70-ffffffff817b3c5f: intel_pasid_tear_down_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void intel_pasid_tear_down_entry(struct intel_iommu *iommu, struct device *dev, u32 pasid, bool fault_ignore);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff81796a50)
Location: drivers/iommu/intel/pasid.c:510
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_aux_detach_device
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel/svm.c:intel_svm_unbind_gpasid
  - drivers/iommu/intel/svm.c:intel_mm_release
```
**Symbols:**

```
ffffffff81796a50-ffffffff81796c8d: intel_pasid_tear_down_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void intel_pasid_tear_down_entry(struct intel_iommu *iommu, struct device *dev, u32 pasid, bool fault_ignore);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff8181e9f0)
Location: drivers/iommu/intel/pasid.c:510
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_aux_detach_device
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel/svm.c:intel_svm_unbind_gpasid
  - drivers/iommu/intel/svm.c:intel_mm_release
```
**Symbols:**

```
ffffffff8181e9f0-ffffffff8181ec2f: intel_pasid_tear_down_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void intel_pasid_tear_down_entry(struct intel_iommu *iommu, struct device *dev, u32 pasid, bool fault_ignore);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff8195ed50)
Location: drivers/iommu/intel/pasid.c:447
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel/svm.c:intel_mm_release
```
**Symbols:**

```
ffffffff8195ed50-ffffffff8195ef59: intel_pasid_tear_down_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void intel_pasid_tear_down_entry(struct intel_iommu *iommu, struct device *dev, u32 pasid, bool fault_ignore);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff81ac6840)
Location: drivers/iommu/intel/pasid.c:456
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_remove_dev_pasid
  - drivers/iommu/intel/iommu.c:intel_iommu_release_device
  - drivers/iommu/intel/iommu.c:device_block_translation
  - drivers/iommu/intel/svm.c:intel_mm_release
```
**Symbols:**

```
ffffffff81ac6840-ffffffff81ac6a5a: intel_pasid_tear_down_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void intel_pasid_tear_down_entry(struct intel_iommu *iommu, struct device *dev, u32 pasid, bool fault_ignore);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff81b13440)
Location: drivers/iommu/intel/pasid.c:447
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_remove_dev_pasid
  - drivers/iommu/intel/iommu.c:intel_iommu_release_device
  - drivers/iommu/intel/iommu.c:device_block_translation
  - drivers/iommu/intel/svm.c:intel_mm_release
```
**Symbols:**

```
ffffffff81b13440-ffffffff81b1365d: intel_pasid_tear_down_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void intel_pasid_tear_down_entry(struct intel_iommu *iommu, struct device *dev, u32 pasid, bool fault_ignore);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff81b68070)
Location: drivers/iommu/intel/pasid.c:233
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_remove_dev_pasid
  - drivers/iommu/intel/iommu.c:intel_iommu_release_device
  - drivers/iommu/intel/iommu.c:device_block_translation
  - drivers/iommu/intel/svm.c:intel_mm_release
```
**Symbols:**

```
ffffffff81b68070-ffffffff81b6828d: intel_pasid_tear_down_entry (STB_GLOBAL)
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
void intel_pasid_tear_down_entry(struct intel_iommu *iommu, struct device *dev, int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff816b5cc0)
Location: drivers/iommu/intel-pasid.c:444
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/iommu/intel-svm.c:intel_mm_release
```
**Symbols:**

```
ffffffff816b5cc0-ffffffff816b5e60: intel_pasid_tear_down_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void intel_pasid_tear_down_entry(struct intel_iommu *iommu, struct device *dev, int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff81693900)
Location: drivers/iommu/intel-pasid.c:444
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/iommu/intel-svm.c:intel_mm_release
```
**Symbols:**

```
ffffffff81693900-ffffffff81693aa0: intel_pasid_tear_down_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void intel_pasid_tear_down_entry(struct intel_iommu *iommu, struct device *dev, int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff816e4190)
Location: drivers/iommu/intel-pasid.c:444
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/iommu/intel-svm.c:intel_mm_release
```
**Symbols:**

```
ffffffff816e4190-ffffffff816e4330: intel_pasid_tear_down_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void intel_pasid_tear_down_entry(struct intel_iommu *iommu, struct device *dev, int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff816fe850)
Location: drivers/iommu/intel-pasid.c:444
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/iommu/intel-svm.c:intel_mm_release
```
**Symbols:**

```
ffffffff816fe850-ffffffff816fe9f0: intel_pasid_tear_down_entry (STB_GLOBAL)
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
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool fault_ignore</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int pasid</code> ➡️ <code>u32 pasid</code>
</li>
</ul>
</details>
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
