# Function: <code>domain_detach_iommu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81538f4c)
Location: drivers/iommu/intel-iommu.c:1777
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8158da07)
Location: drivers/iommu/intel-iommu.c:1817
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815bb1a7)
Location: drivers/iommu/intel-iommu.c:1841
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815d0e26)
Location: drivers/iommu/intel-iommu.c:1846
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81637c26)
Location: drivers/iommu/intel-iommu.c:1848
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81672f8f)
Location: drivers/iommu/intel-iommu.c:1876
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168fc44)
Location: drivers/iommu/intel-iommu.c:1762
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int domain_detach_iommu(struct dmar_domain *domain, struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816c7700)
Location: drivers/iommu/intel-iommu.c:1753
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff816c7700-ffffffff816c779d: domain_detach_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int domain_detach_iommu(struct dmar_domain *domain, struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816ea670)
Location: drivers/iommu/intel-iommu.c:1764
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff816ea670-ffffffff816ea70d: domain_detach_iommu (STB_LOCAL)
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
In drivers/iommu/intel/iommu.c (ffffffff817a1f40)
Location: drivers/iommu/intel/iommu.c:1841
Inline: True
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_aux_detach_device
  - drivers/iommu/intel/iommu.c:aux_domain_add_dev
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff817a1f40-ffffffff817a1fc3: domain_detach_iommu.isra.0 (STB_LOCAL)
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
In drivers/iommu/intel/iommu.c (ffffffff817b0100)
Location: drivers/iommu/intel/iommu.c:1940
Inline: True
Direct callers:
  - drivers/iommu/intel/iommu.c:aux_domain_remove_dev
  - drivers/iommu/intel/iommu.c:aux_domain_add_dev
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff817b0100-ffffffff817b0183: domain_detach_iommu.isra.0 (STB_LOCAL)
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
In drivers/iommu/intel/iommu.c (ffffffff81791f00)
Location: drivers/iommu/intel/iommu.c:1946
Inline: True
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_aux_detach_device
  - drivers/iommu/intel/iommu.c:aux_domain_add_dev
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff81791f00-ffffffff81791f83: domain_detach_iommu.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void domain_detach_iommu(struct dmar_domain *domain, struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81819750)
Location: drivers/iommu/intel/iommu.c:1945
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_aux_detach_device
  - drivers/iommu/intel/iommu.c:aux_domain_add_dev
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff81819750-ffffffff8181984d: domain_detach_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8195b94f)
Location: drivers/iommu/intel/iommu.c:1840
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void domain_detach_iommu(struct dmar_domain *domain, struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81ac1d90)
Location: drivers/iommu/intel/iommu.c:1826
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_release_device
  - drivers/iommu/intel/iommu.c:device_block_translation
```
**Symbols:**

```
ffffffff81ac1d90-ffffffff81ac1e25: domain_detach_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void domain_detach_iommu(struct dmar_domain *domain, struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b0ea20)
Location: drivers/iommu/intel/iommu.c:1794
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_release_device
  - drivers/iommu/intel/iommu.c:device_block_translation
```
**Symbols:**

```
ffffffff81b0ea20-ffffffff81b0eabb: domain_detach_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void domain_detach_iommu(struct dmar_domain *domain, struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b66640)
Location: drivers/iommu/intel/iommu.c:1744
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_set_dev_pasid
  - drivers/iommu/intel/iommu.c:intel_iommu_remove_dev_pasid
  - drivers/iommu/intel/iommu.c:intel_iommu_release_device
  - drivers/iommu/intel/iommu.c:device_block_translation
  - drivers/iommu/intel/nested.c:intel_nested_attach_dev
```
**Symbols:**

```
ffffffff81b66640-ffffffff81b666db: domain_detach_iommu (STB_GLOBAL)
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
int domain_detach_iommu(struct dmar_domain *domain, struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816b0150)
Location: drivers/iommu/intel-iommu.c:1764
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff816b0150-ffffffff816b01ed: domain_detach_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int domain_detach_iommu(struct dmar_domain *domain, struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168daa0)
Location: drivers/iommu/intel-iommu.c:1764
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff8168daa0-ffffffff8168db3d: domain_detach_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int domain_detach_iommu(struct dmar_domain *domain, struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816de330)
Location: drivers/iommu/intel-iommu.c:1764
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff816de330-ffffffff816de3cd: domain_detach_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int domain_detach_iommu(struct dmar_domain *domain, struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816f8940)
Location: drivers/iommu/intel-iommu.c:1764
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff816f8940-ffffffff816f89dd: domain_detach_iommu (STB_LOCAL)
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
