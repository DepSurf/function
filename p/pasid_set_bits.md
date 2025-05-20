# Function: <code>pasid_set_bits</code>

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
In drivers/iommu/intel-pasid.c (ffffffff81694a1c)
Location: drivers/iommu/intel-pasid.c:300
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
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
In drivers/iommu/intel-pasid.c (ffffffff816cd31f)
Location: drivers/iommu/intel-pasid.c:285
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
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
In drivers/iommu/intel-pasid.c (ffffffff816f0b7f)
Location: drivers/iommu/intel-pasid.c:285
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
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
In drivers/iommu/intel/pasid.c (ffffffff817a8300)
Location: drivers/iommu/intel/pasid.c:322
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
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
In drivers/iommu/intel/pasid.c (ffffffff817b41b0)
Location: drivers/iommu/intel/pasid.c:321
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
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
In drivers/iommu/intel/pasid.c (ffffffff8179726f)
Location: drivers/iommu/intel/pasid.c:326
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
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
In drivers/iommu/intel/pasid.c (ffffffff8181f27b)
Location: drivers/iommu/intel/pasid.c:326
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
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
In drivers/iommu/intel/pasid.c (ffffffff8195f538)
Location: drivers/iommu/intel/pasid.c:263
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_page_snoop_control
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
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
In drivers/iommu/intel/pasid.c (ffffffff81ac7158)
Location: drivers/iommu/intel/pasid.c:272
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_page_snoop_control
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
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
In drivers/iommu/intel/pasid.c (ffffffff81b13cbb)
Location: drivers/iommu/intel/pasid.c:272
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_page_snoop_control
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
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
In drivers/iommu/intel/pasid.c (ffffffff81b68d9f)
Location: drivers/iommu/intel/pasid.h:113
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_page_snoop_control
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_dirty_tracking
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_dirty_tracking
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff816b636f)
Location: drivers/iommu/intel-pasid.c:285
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
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
In drivers/iommu/intel-pasid.c (ffffffff81693faf)
Location: drivers/iommu/intel-pasid.c:285
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
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
In drivers/iommu/intel-pasid.c (ffffffff816e483f)
Location: drivers/iommu/intel-pasid.c:285
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
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
In drivers/iommu/intel-pasid.c (ffffffff816feeff)
Location: drivers/iommu/intel-pasid.c:285
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
```
</details>
</li>
</ul>

## Differences
