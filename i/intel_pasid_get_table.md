# Function: <code>intel_pasid_get_table</code>

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
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct pasid_table *intel_pasid_get_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff81694265)
Location: drivers/iommu/intel-pasid.c:217
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_get_entry
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff81694210-ffffffff8169422b: intel_pasid_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct pasid_table *intel_pasid_get_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff816ccb85)
Location: drivers/iommu/intel-pasid.c:202
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_get_entry
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff816ccb30-ffffffff816ccb4b: intel_pasid_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct pasid_table *intel_pasid_get_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff816f03c5)
Location: drivers/iommu/intel-pasid.c:202
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_get_entry
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff816f0370-ffffffff816f038b: intel_pasid_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct pasid_table *intel_pasid_get_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff817a7aa5)
Location: drivers/iommu/intel/pasid.c:223
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_get_entry
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff817a7a50-ffffffff817a7a69: intel_pasid_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct pasid_table *intel_pasid_get_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff817b3965)
Location: drivers/iommu/intel/pasid.c:223
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_get_entry
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff817b3900-ffffffff817b3919: intel_pasid_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct pasid_table *intel_pasid_get_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff817963c5)
Location: drivers/iommu/intel/pasid.c:222
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_get_entry
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff81796a30-ffffffff81796a49: intel_pasid_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct pasid_table *intel_pasid_get_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff8181e355)
Location: drivers/iommu/intel/pasid.c:222
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_get_entry
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff8181e9d0-ffffffff8181e9e9: intel_pasid_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct pasid_table *intel_pasid_get_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff8195e755)
Location: drivers/iommu/intel/pasid.c:159
Inline: True
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_add_dev_info
```
**Symbols:**

```
ffffffff8195ed20-ffffffff8195ed4a: intel_pasid_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct pasid_table *intel_pasid_get_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff81ac6125)
Location: drivers/iommu/intel/pasid.c:164
Inline: True
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
```
**Symbols:**

```
ffffffff81ac6800-ffffffff81ac682a: intel_pasid_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct pasid_table *intel_pasid_get_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff81b12cf5)
Location: drivers/iommu/intel/pasid.c:164
Inline: True
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
```
**Symbols:**

```
ffffffff81b13400-ffffffff81b1342a: intel_pasid_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct pasid_table *intel_pasid_get_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff81b67b35)
Location: drivers/iommu/intel/pasid.c:107
Inline: True
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
```
**Symbols:**

```
ffffffff81b68030-ffffffff81b6805a: intel_pasid_get_table (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct pasid_table *intel_pasid_get_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff816b5bb5)
Location: drivers/iommu/intel-pasid.c:202
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_get_entry
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff816b5b60-ffffffff816b5b7b: intel_pasid_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct pasid_table *intel_pasid_get_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff816937f5)
Location: drivers/iommu/intel-pasid.c:202
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_get_entry
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff816937a0-ffffffff816937bb: intel_pasid_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct pasid_table *intel_pasid_get_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff816e4085)
Location: drivers/iommu/intel-pasid.c:202
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_get_entry
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff816e4030-ffffffff816e404b: intel_pasid_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct pasid_table *intel_pasid_get_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff816fe755)
Location: drivers/iommu/intel-pasid.c:202
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_get_entry
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff816fe700-ffffffff816fe71b: intel_pasid_get_table (STB_GLOBAL)
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
