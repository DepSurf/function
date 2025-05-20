# Function: <code>pasid_to_svm_sdev</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pasid_to_svm_sdev(struct device *dev, unsigned int pasid, struct intel_svm **rsvm, struct intel_svm_dev **rsdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff817b5150)
Location: drivers/iommu/intel/svm.c:250
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:intel_svm_page_response
  - drivers/iommu/intel/svm.c:intel_svm_unbind_gpasid
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
```
**Symbols:**

```
ffffffff817b5150-ffffffff817b5212: pasid_to_svm_sdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pasid_to_svm_sdev(struct device *dev, unsigned int pasid, struct intel_svm **rsvm, struct intel_svm_dev **rsdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff81798570)
Location: drivers/iommu/intel/svm.c:213
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:intel_svm_page_response
  - drivers/iommu/intel/svm.c:intel_svm_unbind_gpasid
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
```
**Symbols:**

```
ffffffff81798570-ffffffff81798632: pasid_to_svm_sdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pasid_to_svm_sdev(struct device *dev, unsigned int pasid, struct intel_svm **rsvm, struct intel_svm_dev **rsdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff81821970)
Location: drivers/iommu/intel/svm.c:285
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:intel_svm_page_response
  - drivers/iommu/intel/svm.c:intel_svm_unbind_gpasid
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
```
**Symbols:**

```
ffffffff81821970-ffffffff81821a32: pasid_to_svm_sdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pasid_to_svm_sdev(struct device *dev, unsigned int pasid, struct intel_svm **rsvm, struct intel_svm_dev **rsdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff81961b40)
Location: drivers/iommu/intel/svm.c:280
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:intel_svm_page_response
```
**Symbols:**

```
ffffffff81961b40-ffffffff81961c12: pasid_to_svm_sdev (STB_LOCAL)
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
In drivers/iommu/intel/svm.c (ffffffff81aca963)
Location: drivers/iommu/intel/svm.c:266
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
In drivers/iommu/intel/svm.c (ffffffff81b16ec7)
Location: drivers/iommu/intel/svm.c:264
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
In drivers/iommu/intel/svm.c (ffffffff81b6cfe5)
Location: drivers/iommu/intel/svm.c:286
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_remove_dev_pasid
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
