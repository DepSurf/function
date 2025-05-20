# Function: <code>intel_pasid_alloc_table</code>

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
int intel_pasid_alloc_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff81693f80)
Location: drivers/iommu/intel-pasid.c:122
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff81693f80-ffffffff81694120: intel_pasid_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int intel_pasid_alloc_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-pasid.c (0)
Location: drivers/iommu/intel-pasid.c:122
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff816cd45b-ffffffff816cd473: intel_pasid_alloc_table.cold (STB_LOCAL)
ffffffff816cc890-ffffffff816cca3f: intel_pasid_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int intel_pasid_alloc_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff816f00d0)
Location: drivers/iommu/intel-pasid.c:122
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff816f00d0-ffffffff816f027c: intel_pasid_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int intel_pasid_alloc_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff817a77b0)
Location: drivers/iommu/intel/pasid.c:143
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff817a77b0-ffffffff817a7955: intel_pasid_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int intel_pasid_alloc_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff817b3650)
Location: drivers/iommu/intel/pasid.c:143
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff817b3650-ffffffff817b3803: intel_pasid_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int intel_pasid_alloc_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff81796780)
Location: drivers/iommu/intel/pasid.c:142
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff81796780-ffffffff81796931: intel_pasid_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int intel_pasid_alloc_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/pasid.c (0)
Location: drivers/iommu/intel/pasid.c:142
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff81d00298-ffffffff81d002bb: intel_pasid_alloc_table.cold (STB_LOCAL)
ffffffff8181e710-ffffffff8181e8d2: intel_pasid_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int intel_pasid_alloc_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/pasid.c (0)
Location: drivers/iommu/intel/pasid.c:94
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_add_dev_info
```
**Symbols:**

```
ffffffff81ec88bb-ffffffff81ec88da: intel_pasid_alloc_table.cold (STB_LOCAL)
ffffffff8195eaf0-ffffffff8195ec4d: intel_pasid_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int intel_pasid_alloc_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/pasid.c (0)
Location: drivers/iommu/intel/pasid.c:94
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_device
```
**Symbols:**

```
ffffffff82097ac3-ffffffff82097ae2: intel_pasid_alloc_table.cold (STB_LOCAL)
ffffffff81ac6580-ffffffff81ac670d: intel_pasid_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int intel_pasid_alloc_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/pasid.c (0)
Location: drivers/iommu/intel/pasid.c:94
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_device
```
**Symbols:**

```
ffffffff82118a2a-ffffffff82118a62: intel_pasid_alloc_table.cold (STB_LOCAL)
ffffffff81b13170-ffffffff81b1330d: intel_pasid_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int intel_pasid_alloc_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/pasid.c (0)
Location: drivers/iommu/intel/pasid.c:37
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_device
```
**Symbols:**

```
ffffffff821f6788-ffffffff821f67c0: intel_pasid_alloc_table.cold (STB_LOCAL)
ffffffff81b67d70-ffffffff81b67f3c: intel_pasid_alloc_table (STB_GLOBAL)
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
int intel_pasid_alloc_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff816b58c0)
Location: drivers/iommu/intel-pasid.c:122
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff816b58c0-ffffffff816b5a6c: intel_pasid_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int intel_pasid_alloc_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff81693500)
Location: drivers/iommu/intel-pasid.c:122
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff81693500-ffffffff816936ac: intel_pasid_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int intel_pasid_alloc_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff816e3d90)
Location: drivers/iommu/intel-pasid.c:122
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff816e3d90-ffffffff816e3f3c: intel_pasid_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int intel_pasid_alloc_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff816fe460)
Location: drivers/iommu/intel-pasid.c:122
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff816fe460-ffffffff816fe607: intel_pasid_alloc_table (STB_GLOBAL)
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
