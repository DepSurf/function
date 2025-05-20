# Function: <code>intel_pasid_setup_nested</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int intel_pasid_setup_nested(struct intel_iommu *iommu, struct device *dev, pgd_t *gpgd, int pasid, struct iommu_gpasid_bind_data_vtd *pasid_data, struct dmar_domain *domain, int addr_width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/pasid.c (0)
Location: drivers/iommu/intel/pasid.c:753
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
```
**Symbols:**

```
ffffffff817a86f8-ffffffff817a87ee: intel_pasid_setup_nested.cold (STB_LOCAL)
ffffffff817a8210-ffffffff817a85b3: intel_pasid_setup_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int intel_pasid_setup_nested(struct intel_iommu *iommu, struct device *dev, pgd_t *gpgd, u32 pasid, struct iommu_gpasid_bind_data_vtd *pasid_data, struct dmar_domain *domain, int addr_width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/pasid.c (0)
Location: drivers/iommu/intel/pasid.c:761
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
```
**Symbols:**

```
ffffffff81c0cdd1-ffffffff81c0cec7: intel_pasid_setup_nested.cold (STB_LOCAL)
ffffffff817b40c0-ffffffff817b4463: intel_pasid_setup_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int intel_pasid_setup_nested(struct intel_iommu *iommu, struct device *dev, pgd_t *gpgd, u32 pasid, struct iommu_gpasid_bind_data_vtd *pasid_data, struct dmar_domain *domain, int addr_width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/pasid.c (0)
Location: drivers/iommu/intel/pasid.c:809
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
```
**Symbols:**

```
ffffffff81bfe531-ffffffff81bfe627: intel_pasid_setup_nested.cold (STB_LOCAL)
ffffffff81797180-ffffffff81797529: intel_pasid_setup_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int intel_pasid_setup_nested(struct intel_iommu *iommu, struct device *dev, pgd_t *gpgd, u32 pasid, struct iommu_gpasid_bind_data_vtd *pasid_data, struct dmar_domain *domain, int addr_width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/pasid.c (0)
Location: drivers/iommu/intel/pasid.c:825
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
```
**Symbols:**

```
ffffffff81d003cd-ffffffff81d004c3: intel_pasid_setup_nested.cold (STB_LOCAL)
ffffffff8181f180-ffffffff8181f58c: intel_pasid_setup_nested (STB_GLOBAL)
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
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int intel_pasid_setup_nested(struct intel_iommu *iommu, struct device *dev, u32 pasid, struct dmar_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff81b68c50)
Location: drivers/iommu/intel/pasid.c:586
Inline: False
Direct callers:
  - drivers/iommu/intel/nested.c:intel_nested_attach_dev
```
**Symbols:**

```
ffffffff81b68c50-ffffffff81b68fdd: intel_pasid_setup_nested (STB_GLOBAL)
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
</ul>
