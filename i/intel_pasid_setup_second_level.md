# Function: <code>intel_pasid_setup_second_level</code>

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
int intel_pasid_setup_second_level(struct intel_iommu *iommu, struct dmar_domain *domain, struct device *dev, int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-pasid.c (0)
Location: drivers/iommu/intel-pasid.c:545
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff81694b9b-ffffffff81694bb5: intel_pasid_setup_second_level.cold.11 (STB_LOCAL)
ffffffff81694720-ffffffff8169499c: intel_pasid_setup_second_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int intel_pasid_setup_second_level(struct intel_iommu *iommu, struct dmar_domain *domain, struct device *dev, int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-pasid.c (0)
Location: drivers/iommu/intel-pasid.c:530
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff816cd4fb-ffffffff816cd54a: intel_pasid_setup_second_level.cold (STB_LOCAL)
ffffffff816cd040-ffffffff816cd298: intel_pasid_setup_second_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int intel_pasid_setup_second_level(struct intel_iommu *iommu, struct dmar_domain *domain, struct device *dev, int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-pasid.c (0)
Location: drivers/iommu/intel-pasid.c:538
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff816f0cdc-ffffffff816f0d2b: intel_pasid_setup_second_level.cold (STB_LOCAL)
ffffffff816f08a0-ffffffff816f0af8: intel_pasid_setup_second_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int intel_pasid_setup_second_level(struct intel_iommu *iommu, struct dmar_domain *domain, struct device *dev, int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/pasid.c (0)
Location: drivers/iommu/intel/pasid.c:608
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:aux_domain_add_dev
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff817a868d-ffffffff817a86dc: intel_pasid_setup_second_level.cold (STB_LOCAL)
ffffffff817a7f60-ffffffff817a8110: intel_pasid_setup_second_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int intel_pasid_setup_second_level(struct intel_iommu *iommu, struct dmar_domain *domain, struct device *dev, u32 pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/pasid.c (0)
Location: drivers/iommu/intel/pasid.c:616
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:aux_domain_add_dev
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff81c0cd66-ffffffff81c0cdb5: intel_pasid_setup_second_level.cold (STB_LOCAL)
ffffffff817b3e10-ffffffff817b3fc0: intel_pasid_setup_second_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int intel_pasid_setup_second_level(struct intel_iommu *iommu, struct dmar_domain *domain, struct device *dev, u32 pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/pasid.c (0)
Location: drivers/iommu/intel/pasid.c:657
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:aux_domain_add_dev
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff81bfe4c6-ffffffff81bfe515: intel_pasid_setup_second_level.cold (STB_LOCAL)
ffffffff81796ea0-ffffffff81797074: intel_pasid_setup_second_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int intel_pasid_setup_second_level(struct intel_iommu *iommu, struct dmar_domain *domain, struct device *dev, u32 pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/pasid.c (0)
Location: drivers/iommu/intel/pasid.c:665
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:aux_domain_add_dev
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff81d00362-ffffffff81d003b1: intel_pasid_setup_second_level.cold (STB_LOCAL)
ffffffff8181ee60-ffffffff8181f070: intel_pasid_setup_second_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int intel_pasid_setup_second_level(struct intel_iommu *iommu, struct dmar_domain *domain, struct device *dev, u32 pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/pasid.c (0)
Location: drivers/iommu/intel/pasid.c:602
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_add_dev_info
```
**Symbols:**

```
ffffffff81ec8948-ffffffff81ec898f: intel_pasid_setup_second_level.cold (STB_LOCAL)
ffffffff8195f1b0-ffffffff8195f3b0: intel_pasid_setup_second_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int intel_pasid_setup_second_level(struct intel_iommu *iommu, struct dmar_domain *domain, struct device *dev, u32 pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff81ac6d20)
Location: drivers/iommu/intel/pasid.c:611
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
```
**Symbols:**

```
ffffffff81ac6d20-ffffffff81ac6f62: intel_pasid_setup_second_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int intel_pasid_setup_second_level(struct intel_iommu *iommu, struct dmar_domain *domain, struct device *dev, u32 pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff81b138b0)
Location: drivers/iommu/intel/pasid.c:581
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
```
**Symbols:**

```
ffffffff81b138b0-ffffffff81b13add: intel_pasid_setup_second_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int intel_pasid_setup_second_level(struct intel_iommu *iommu, struct dmar_domain *domain, struct device *dev, u32 pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff81b684e0)
Location: drivers/iommu/intel/pasid.c:367
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_set_dev_pasid
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
```
**Symbols:**

```
ffffffff81b684e0-ffffffff81b68720: intel_pasid_setup_second_level (STB_GLOBAL)
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
int intel_pasid_setup_second_level(struct intel_iommu *iommu, struct dmar_domain *domain, struct device *dev, int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-pasid.c (0)
Location: drivers/iommu/intel-pasid.c:538
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff816b64cc-ffffffff816b651b: intel_pasid_setup_second_level.cold (STB_LOCAL)
ffffffff816b6090-ffffffff816b62e8: intel_pasid_setup_second_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int intel_pasid_setup_second_level(struct intel_iommu *iommu, struct dmar_domain *domain, struct device *dev, int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-pasid.c (0)
Location: drivers/iommu/intel-pasid.c:538
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff8169410c-ffffffff8169415b: intel_pasid_setup_second_level.cold (STB_LOCAL)
ffffffff81693cd0-ffffffff81693f28: intel_pasid_setup_second_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int intel_pasid_setup_second_level(struct intel_iommu *iommu, struct dmar_domain *domain, struct device *dev, int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-pasid.c (0)
Location: drivers/iommu/intel-pasid.c:538
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff816e499c-ffffffff816e49eb: intel_pasid_setup_second_level.cold (STB_LOCAL)
ffffffff816e4560-ffffffff816e47b8: intel_pasid_setup_second_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int intel_pasid_setup_second_level(struct intel_iommu *iommu, struct dmar_domain *domain, struct device *dev, int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-pasid.c (0)
Location: drivers/iommu/intel-pasid.c:538
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff816ff05c-ffffffff816ff0ab: intel_pasid_setup_second_level.cold (STB_LOCAL)
ffffffff816fec20-ffffffff816fee78: intel_pasid_setup_second_level (STB_GLOBAL)
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
