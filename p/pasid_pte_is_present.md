# Function: <code>pasid_pte_is_present</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff817a826b)
Location: drivers/iommu/intel/intel-pasid.h:96
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
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
In drivers/iommu/intel/pasid.c (ffffffff817b411b)
Location: drivers/iommu/intel/pasid.h:96
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
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
In drivers/iommu/intel/pasid.c (ffffffff817971da)
Location: drivers/iommu/intel/pasid.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
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
In drivers/iommu/intel/pasid.c (ffffffff8181f1de)
Location: drivers/iommu/intel/pasid.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
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
In drivers/iommu/intel/pasid.c (ffffffff8195f52d)
Location: drivers/iommu/intel/pasid.h:96
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_page_snoop_control
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
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
In drivers/iommu/intel/pasid.c (ffffffff81ac714d)
Location: drivers/iommu/intel/pasid.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_page_snoop_control
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
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
In drivers/iommu/intel/pasid.c (ffffffff81b13cb0)
Location: drivers/iommu/intel/pasid.h:90
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_page_snoop_control
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
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
In drivers/iommu/intel/pasid.c (ffffffff81b68d49)
Location: drivers/iommu/intel/pasid.h:78
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_page_snoop_control
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
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
