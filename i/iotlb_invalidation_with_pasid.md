# Function: <code>iotlb_invalidation_with_pasid</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff81694b05)
Location: drivers/iommu/intel-pasid.c:428
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff816cd3e4)
Location: drivers/iommu/intel-pasid.c:413
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff816f0c44)
Location: drivers/iommu/intel-pasid.c:413
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff817a7cd5)
Location: drivers/iommu/intel/pasid.c:461
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff817b3b72)
Location: drivers/iommu/intel/pasid.c:460
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
In <code>6.8</code>: Absent ⚠️
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff816b6434)
Location: drivers/iommu/intel-pasid.c:413
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff81694074)
Location: drivers/iommu/intel-pasid.c:413
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff816e4904)
Location: drivers/iommu/intel-pasid.c:413
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff816fefc4)
Location: drivers/iommu/intel-pasid.c:413
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
```
</details>
</li>
</ul>

## Differences
