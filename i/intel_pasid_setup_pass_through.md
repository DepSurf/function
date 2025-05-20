# Function: <code>intel_pasid_setup_pass_through</code>

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
int intel_pasid_setup_pass_through(struct intel_iommu *iommu, struct dmar_domain *domain, struct device *dev, int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff816949a0)
Location: drivers/iommu/intel-pasid.c:618
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff816949a0-ffffffff81694b67: intel_pasid_setup_pass_through (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int intel_pasid_setup_pass_through(struct intel_iommu *iommu, struct dmar_domain *domain, struct device *dev, int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-pasid.c (0)
Location: drivers/iommu/intel-pasid.c:603
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff816cd54a-ffffffff816cd566: intel_pasid_setup_pass_through.cold (STB_LOCAL)
ffffffff816cd2a0-ffffffff816cd448: intel_pasid_setup_pass_through (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int intel_pasid_setup_pass_through(struct intel_iommu *iommu, struct dmar_domain *domain, struct device *dev, int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-pasid.c (0)
Location: drivers/iommu/intel-pasid.c:611
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff816f0d2b-ffffffff816f0d47: intel_pasid_setup_pass_through.cold (STB_LOCAL)
ffffffff816f0b00-ffffffff816f0ca8: intel_pasid_setup_pass_through (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int intel_pasid_setup_pass_through(struct intel_iommu *iommu, struct dmar_domain *domain, struct device *dev, int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/pasid.c (0)
Location: drivers/iommu/intel/pasid.c:666
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff817a86dc-ffffffff817a86f8: intel_pasid_setup_pass_through.cold (STB_LOCAL)
ffffffff817a8110-ffffffff817a8210: intel_pasid_setup_pass_through (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int intel_pasid_setup_pass_through(struct intel_iommu *iommu, struct dmar_domain *domain, struct device *dev, u32 pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/pasid.c (0)
Location: drivers/iommu/intel/pasid.c:674
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff81c0cdb5-ffffffff81c0cdd1: intel_pasid_setup_pass_through.cold (STB_LOCAL)
ffffffff817b3fc0-ffffffff817b40c0: intel_pasid_setup_pass_through (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int intel_pasid_setup_pass_through(struct intel_iommu *iommu, struct dmar_domain *domain, struct device *dev, u32 pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/pasid.c (0)
Location: drivers/iommu/intel/pasid.c:719
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff81bfe515-ffffffff81bfe531: intel_pasid_setup_pass_through.cold (STB_LOCAL)
ffffffff81797080-ffffffff8179717c: intel_pasid_setup_pass_through (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int intel_pasid_setup_pass_through(struct intel_iommu *iommu, struct dmar_domain *domain, struct device *dev, u32 pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/pasid.c (0)
Location: drivers/iommu/intel/pasid.c:731
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff81d003b1-ffffffff81d003cd: intel_pasid_setup_pass_through.cold (STB_LOCAL)
ffffffff8181f070-ffffffff8181f17e: intel_pasid_setup_pass_through (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int intel_pasid_setup_pass_through(struct intel_iommu *iommu, struct dmar_domain *domain, struct device *dev, u32 pasid);
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
  - drivers/iommu/intel/iommu.c:domain_add_dev_info
```
**Symbols:**

```
ffffffff81ec898f-ffffffff81ec89ab: intel_pasid_setup_pass_through.cold (STB_LOCAL)
ffffffff8195f3b0-ffffffff8195f4c9: intel_pasid_setup_pass_through (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int intel_pasid_setup_pass_through(struct intel_iommu *iommu, struct dmar_domain *domain, struct device *dev, u32 pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff81ac6f80)
Location: drivers/iommu/intel/pasid.c:678
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
```
**Symbols:**

```
ffffffff81ac6f80-ffffffff81ac70d9: intel_pasid_setup_pass_through (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int intel_pasid_setup_pass_through(struct intel_iommu *iommu, struct dmar_domain *domain, struct device *dev, u32 pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff81b13af0)
Location: drivers/iommu/intel/pasid.c:642
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
```
**Symbols:**

```
ffffffff81b13af0-ffffffff81b13c34: intel_pasid_setup_pass_through (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int intel_pasid_setup_pass_through(struct intel_iommu *iommu, struct device *dev, u32 pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff81b68970)
Location: drivers/iommu/intel/pasid.c:501
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_set_dev_pasid
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
```
**Symbols:**

```
ffffffff81b68970-ffffffff81b68ab4: intel_pasid_setup_pass_through (STB_GLOBAL)
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
int intel_pasid_setup_pass_through(struct intel_iommu *iommu, struct dmar_domain *domain, struct device *dev, int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-pasid.c (0)
Location: drivers/iommu/intel-pasid.c:611
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff816b651b-ffffffff816b6537: intel_pasid_setup_pass_through.cold (STB_LOCAL)
ffffffff816b62f0-ffffffff816b6498: intel_pasid_setup_pass_through (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int intel_pasid_setup_pass_through(struct intel_iommu *iommu, struct dmar_domain *domain, struct device *dev, int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-pasid.c (0)
Location: drivers/iommu/intel-pasid.c:611
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff8169415b-ffffffff81694177: intel_pasid_setup_pass_through.cold (STB_LOCAL)
ffffffff81693f30-ffffffff816940d8: intel_pasid_setup_pass_through (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int intel_pasid_setup_pass_through(struct intel_iommu *iommu, struct dmar_domain *domain, struct device *dev, int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-pasid.c (0)
Location: drivers/iommu/intel-pasid.c:611
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff816e49eb-ffffffff816e4a07: intel_pasid_setup_pass_through.cold (STB_LOCAL)
ffffffff816e47c0-ffffffff816e4968: intel_pasid_setup_pass_through (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int intel_pasid_setup_pass_through(struct intel_iommu *iommu, struct dmar_domain *domain, struct device *dev, int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-pasid.c (0)
Location: drivers/iommu/intel-pasid.c:611
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff816ff0ab-ffffffff816ff0c7: intel_pasid_setup_pass_through.cold (STB_LOCAL)
ffffffff816fee80-ffffffff816ff028: intel_pasid_setup_pass_through (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct dmar_domain *domain</code>
</li>
<li>
<b>Param reordered. </b>
<code>iommu, domain, dev, pasid</code> ➡️ <code>iommu, dev, pasid</code>
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
