# Function: <code>domain_attach_iommu</code>

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
In drivers/iommu/intel-iommu.c (ffffffff81539ca0)
Location: drivers/iommu/intel-iommu.c:1743
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
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
In drivers/iommu/intel-iommu.c (ffffffff8158e750)
Location: drivers/iommu/intel-iommu.c:1783
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
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
In drivers/iommu/intel-iommu.c (ffffffff815bc270)
Location: drivers/iommu/intel-iommu.c:1807
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
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
In drivers/iommu/intel-iommu.c (ffffffff815d1e5d)
Location: drivers/iommu/intel-iommu.c:1812
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
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
In drivers/iommu/intel-iommu.c (ffffffff81638c3d)
Location: drivers/iommu/intel-iommu.c:1814
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
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
In drivers/iommu/intel-iommu.c (ffffffff81673f1c)
Location: drivers/iommu/intel-iommu.c:1842
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
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
In drivers/iommu/intel-iommu.c (ffffffff816924b4)
Location: drivers/iommu/intel-iommu.c:1728
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int domain_attach_iommu(struct dmar_domain *domain, struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:1719
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff816c7c60-ffffffff816c7d34: domain_attach_iommu (STB_LOCAL)
ffffffff816cbe41-ffffffff816cbe6f: domain_attach_iommu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int domain_attach_iommu(struct dmar_domain *domain, struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816eac6d)
Location: drivers/iommu/intel-iommu.c:1730
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff816eac10-ffffffff816eace4: domain_attach_iommu (STB_LOCAL)
ffffffff816ef729-ffffffff816ef757: domain_attach_iommu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int domain_attach_iommu(struct dmar_domain *domain, struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1807
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:aux_domain_add_dev
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff817a1e60-ffffffff817a1f34: domain_attach_iommu (STB_LOCAL)
ffffffff817a6dad-ffffffff817a6ddb: domain_attach_iommu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int domain_attach_iommu(struct dmar_domain *domain, struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1906
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:aux_domain_add_dev
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff817b0020-ffffffff817b00f4: domain_attach_iommu (STB_LOCAL)
ffffffff81c0c639-ffffffff81c0c667: domain_attach_iommu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int domain_attach_iommu(struct dmar_domain *domain, struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1912
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:aux_domain_add_dev
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff81791e20-ffffffff81791ef4: domain_attach_iommu (STB_LOCAL)
ffffffff81bfdd3d-ffffffff81bfdd6b: domain_attach_iommu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int domain_attach_iommu(struct dmar_domain *domain, struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81819c3c)
Location: drivers/iommu/intel/iommu.c:1913
Inline: True
Direct callers:
  - drivers/iommu/intel/iommu.c:aux_domain_add_dev
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff81819bd0-ffffffff81819cf0: domain_attach_iommu (STB_LOCAL)
ffffffff81cff635-ffffffff81cff678: domain_attach_iommu.cold (STB_LOCAL)
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
In drivers/iommu/intel/iommu.c (ffffffff8195d39f)
Location: drivers/iommu/intel/iommu.c:1811
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:domain_add_dev_info
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int domain_attach_iommu(struct dmar_domain *domain, struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81ac1e40)
Location: drivers/iommu/intel/iommu.c:1776
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
```
**Symbols:**

```
ffffffff81ac1e40-ffffffff81ac1fe2: domain_attach_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int domain_attach_iommu(struct dmar_domain *domain, struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b0ead0)
Location: drivers/iommu/intel/iommu.c:1744
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
```
**Symbols:**

```
ffffffff81b0ead0-ffffffff81b0ec7e: domain_attach_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int domain_attach_iommu(struct dmar_domain *domain, struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b66450)
Location: drivers/iommu/intel/iommu.c:1695
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_set_dev_pasid
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
  - drivers/iommu/intel/nested.c:intel_nested_attach_dev
```
**Symbols:**

```
ffffffff81b66450-ffffffff81b6662b: domain_attach_iommu (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int domain_attach_iommu(struct dmar_domain *domain, struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816b074d)
Location: drivers/iommu/intel-iommu.c:1730
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff816b06f0-ffffffff816b07c4: domain_attach_iommu (STB_LOCAL)
ffffffff816b4f19-ffffffff816b4f47: domain_attach_iommu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int domain_attach_iommu(struct dmar_domain *domain, struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168e09d)
Location: drivers/iommu/intel-iommu.c:1730
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff8168e040-ffffffff8168e114: domain_attach_iommu (STB_LOCAL)
ffffffff81692b59-ffffffff81692b87: domain_attach_iommu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int domain_attach_iommu(struct dmar_domain *domain, struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816de92d)
Location: drivers/iommu/intel-iommu.c:1730
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff816de8d0-ffffffff816de9a4: domain_attach_iommu (STB_LOCAL)
ffffffff816e33e9-ffffffff816e3417: domain_attach_iommu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int domain_attach_iommu(struct dmar_domain *domain, struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816f904d)
Location: drivers/iommu/intel-iommu.c:1730
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff816f8ff0-ffffffff816f90c4: domain_attach_iommu (STB_LOCAL)
ffffffff816fda79-ffffffff816fdaa7: domain_attach_iommu.cold (STB_LOCAL)
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
