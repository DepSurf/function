# Function: <code>intel_pasid_get_dev_max_id</code>

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
int intel_pasid_get_dev_max_id(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff81694295)
Location: drivers/iommu/intel-pasid.c:228
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_get_entry
```
**Symbols:**

```
ffffffff81694230-ffffffff81694257: intel_pasid_get_dev_max_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int intel_pasid_get_dev_max_id(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff816ccbb7)
Location: drivers/iommu/intel-pasid.c:213
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_get_entry
```
**Symbols:**

```
ffffffff816ccb50-ffffffff816ccb77: intel_pasid_get_dev_max_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int intel_pasid_get_dev_max_id(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff816f03f7)
Location: drivers/iommu/intel-pasid.c:213
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_get_entry
```
**Symbols:**

```
ffffffff816f0390-ffffffff816f03b7: intel_pasid_get_dev_max_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int intel_pasid_get_dev_max_id(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff817a7ada)
Location: drivers/iommu/intel/pasid.c:234
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_get_entry
```
**Symbols:**

```
ffffffff817a7a70-ffffffff817a7a95: intel_pasid_get_dev_max_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int intel_pasid_get_dev_max_id(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff817b3981)
Location: drivers/iommu/intel/pasid.c:234
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_get_entry
```
**Symbols:**

```
ffffffff817b3920-ffffffff817b3945: intel_pasid_get_dev_max_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff817963e1)
Location: drivers/iommu/intel/pasid.c:233
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_get_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff8181e371)
Location: drivers/iommu/intel/pasid.c:233
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_get_entry
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
In drivers/iommu/intel/pasid.c (ffffffff8195e787)
Location: drivers/iommu/intel/pasid.c:170
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff81ac6158)
Location: drivers/iommu/intel/pasid.c:175
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff81b12d28)
Location: drivers/iommu/intel/pasid.c:175
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff81b67b68)
Location: drivers/iommu/intel/pasid.c:118
Inline: True
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
int intel_pasid_get_dev_max_id(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff816b5be7)
Location: drivers/iommu/intel-pasid.c:213
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_get_entry
```
**Symbols:**

```
ffffffff816b5b80-ffffffff816b5ba7: intel_pasid_get_dev_max_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int intel_pasid_get_dev_max_id(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff81693827)
Location: drivers/iommu/intel-pasid.c:213
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_get_entry
```
**Symbols:**

```
ffffffff816937c0-ffffffff816937e7: intel_pasid_get_dev_max_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int intel_pasid_get_dev_max_id(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff816e40b7)
Location: drivers/iommu/intel-pasid.c:213
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_get_entry
```
**Symbols:**

```
ffffffff816e4050-ffffffff816e4077: intel_pasid_get_dev_max_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int intel_pasid_get_dev_max_id(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff816fe788)
Location: drivers/iommu/intel-pasid.c:213
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_get_entry
```
**Symbols:**

```
ffffffff816fe720-ffffffff816fe747: intel_pasid_get_dev_max_id (STB_GLOBAL)
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
