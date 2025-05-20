# Function: <code>intel_pasid_setup_first_level</code>

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
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int intel_pasid_setup_first_level(struct intel_iommu *iommu, struct device *dev, pgd_t *pgd, int pasid, u16 did, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-pasid.c (0)
Location: drivers/iommu/intel-pasid.c:487
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff81694b67-ffffffff81694b9b: intel_pasid_setup_first_level.cold.10 (STB_LOCAL)
ffffffff81694500-ffffffff8169471e: intel_pasid_setup_first_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int intel_pasid_setup_first_level(struct intel_iommu *iommu, struct device *dev, pgd_t *pgd, int pasid, u16 did, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-pasid.c (0)
Location: drivers/iommu/intel-pasid.c:472
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff816cd4af-ffffffff816cd4fb: intel_pasid_setup_first_level.cold (STB_LOCAL)
ffffffff816cce20-ffffffff816cd033: intel_pasid_setup_first_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int intel_pasid_setup_first_level(struct intel_iommu *iommu, struct device *dev, pgd_t *pgd, int pasid, u16 did, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-pasid.c (0)
Location: drivers/iommu/intel-pasid.c:472
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff816f0ca8-ffffffff816f0cdc: intel_pasid_setup_first_level.cold (STB_LOCAL)
ffffffff816f0670-ffffffff816f0895: intel_pasid_setup_first_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int intel_pasid_setup_first_level(struct intel_iommu *iommu, struct device *dev, pgd_t *pgd, int pasid, u16 did, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/pasid.c (0)
Location: drivers/iommu/intel/pasid.c:535
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_setup_first_level
```
**Symbols:**

```
ffffffff817a85fb-ffffffff817a868d: intel_pasid_setup_first_level.cold (STB_LOCAL)
ffffffff817a7db0-ffffffff817a7f56: intel_pasid_setup_first_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int intel_pasid_setup_first_level(struct intel_iommu *iommu, struct device *dev, pgd_t *pgd, u32 pasid, u16 did, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/pasid.c (0)
Location: drivers/iommu/intel/pasid.c:543
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_setup_first_level
```
**Symbols:**

```
ffffffff81c0ccd4-ffffffff81c0cd66: intel_pasid_setup_first_level.cold (STB_LOCAL)
ffffffff817b3c60-ffffffff817b3e06: intel_pasid_setup_first_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int intel_pasid_setup_first_level(struct intel_iommu *iommu, struct device *dev, pgd_t *pgd, u32 pasid, u16 did, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/pasid.c (0)
Location: drivers/iommu/intel/pasid.c:578
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_setup_first_level
```
**Symbols:**

```
ffffffff81bfe41f-ffffffff81bfe4c6: intel_pasid_setup_first_level.cold (STB_LOCAL)
ffffffff81796c90-ffffffff81796e99: intel_pasid_setup_first_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int intel_pasid_setup_first_level(struct intel_iommu *iommu, struct device *dev, pgd_t *pgd, u32 pasid, u16 did, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/pasid.c (0)
Location: drivers/iommu/intel/pasid.c:582
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_setup_first_level
  - drivers/iommu/intel/svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff81d002bb-ffffffff81d00362: intel_pasid_setup_first_level.cold (STB_LOCAL)
ffffffff8181ec30-ffffffff8181ee53: intel_pasid_setup_first_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int intel_pasid_setup_first_level(struct intel_iommu *iommu, struct device *dev, pgd_t *pgd, u32 pasid, u16 did, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/pasid.c (0)
Location: drivers/iommu/intel/pasid.c:519
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_add_dev_info
  - drivers/iommu/intel/svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff81ec88da-ffffffff81ec8948: intel_pasid_setup_first_level.cold (STB_LOCAL)
ffffffff8195ef60-ffffffff8195f1a3: intel_pasid_setup_first_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int intel_pasid_setup_first_level(struct intel_iommu *iommu, struct device *dev, pgd_t *pgd, u32 pasid, u16 did, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff81ac6a70)
Location: drivers/iommu/intel/pasid.c:512
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
  - drivers/iommu/intel/svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff81ac6a70-ffffffff81ac6d0b: intel_pasid_setup_first_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int intel_pasid_setup_first_level(struct intel_iommu *iommu, struct device *dev, pgd_t *pgd, u32 pasid, u16 did, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff81b13670)
Location: drivers/iommu/intel/pasid.c:503
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
  - drivers/iommu/intel/svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff81b13670-ffffffff81b13898: intel_pasid_setup_first_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int intel_pasid_setup_first_level(struct intel_iommu *iommu, struct device *dev, pgd_t *pgd, u32 pasid, u16 did, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff81b682a0)
Location: drivers/iommu/intel/pasid.c:289
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_setup_first_level
```
**Symbols:**

```
ffffffff81b682a0-ffffffff81b684c8: intel_pasid_setup_first_level (STB_GLOBAL)
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
int intel_pasid_setup_first_level(struct intel_iommu *iommu, struct device *dev, pgd_t *pgd, int pasid, u16 did, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-pasid.c (0)
Location: drivers/iommu/intel-pasid.c:472
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff816b6498-ffffffff816b64cc: intel_pasid_setup_first_level.cold (STB_LOCAL)
ffffffff816b5e60-ffffffff816b6085: intel_pasid_setup_first_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int intel_pasid_setup_first_level(struct intel_iommu *iommu, struct device *dev, pgd_t *pgd, int pasid, u16 did, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-pasid.c (0)
Location: drivers/iommu/intel-pasid.c:472
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff816940d8-ffffffff8169410c: intel_pasid_setup_first_level.cold (STB_LOCAL)
ffffffff81693aa0-ffffffff81693cc5: intel_pasid_setup_first_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int intel_pasid_setup_first_level(struct intel_iommu *iommu, struct device *dev, pgd_t *pgd, int pasid, u16 did, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-pasid.c (0)
Location: drivers/iommu/intel-pasid.c:472
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff816e4968-ffffffff816e499c: intel_pasid_setup_first_level.cold (STB_LOCAL)
ffffffff816e4330-ffffffff816e4555: intel_pasid_setup_first_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int intel_pasid_setup_first_level(struct intel_iommu *iommu, struct device *dev, pgd_t *pgd, int pasid, u16 did, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-pasid.c (0)
Location: drivers/iommu/intel-pasid.c:472
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff816ff028-ffffffff816ff05c: intel_pasid_setup_first_level.cold (STB_LOCAL)
ffffffff816fe9f0-ffffffff816fec15: intel_pasid_setup_first_level (STB_GLOBAL)
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
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
