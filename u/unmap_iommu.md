# Function: <code>unmap_iommu</code>

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
In drivers/iommu/dmar.c (ffffffff81534288)
Location: drivers/iommu/dmar.c:903
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_free_drhd
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
In drivers/iommu/dmar.c (ffffffff81588c79)
Location: drivers/iommu/dmar.c:915
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
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
In drivers/iommu/dmar.c (ffffffff815b6339)
Location: drivers/iommu/dmar.c:916
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
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
In drivers/iommu/dmar.c (ffffffff815cc1b3)
Location: drivers/iommu/dmar.c:919
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
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
In drivers/iommu/dmar.c (ffffffff81632f83)
Location: drivers/iommu/dmar.c:922
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
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
In drivers/iommu/dmar.c (ffffffff8166e1a3)
Location: drivers/iommu/dmar.c:922
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
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
In drivers/iommu/dmar.c (ffffffff8168c5d3)
Location: drivers/iommu/dmar.c:922
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
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
In drivers/iommu/dmar.c (ffffffff816c39f0)
Location: drivers/iommu/dmar.c:911
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_free_drhd
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
In drivers/iommu/dmar.c (ffffffff816e6940)
Location: drivers/iommu/dmar.c:921
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_free_drhd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void unmap_iommu(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff8179cf3f)
Location: drivers/iommu/intel/dmar.c:925
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:free_iommu
Direct callers:
  - drivers/iommu/intel/dmar.c:alloc_iommu
```
**Symbols:**

```
ffffffff8179c4e0-ffffffff8179c50f: unmap_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void unmap_iommu(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff817aac1c)
Location: drivers/iommu/intel/dmar.c:947
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:free_iommu
Direct callers:
  - drivers/iommu/intel/dmar.c:alloc_iommu
```
**Symbols:**

```
ffffffff817aa1b0-ffffffff817aa1df: unmap_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void unmap_iommu(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff8178e2ce)
Location: drivers/iommu/intel/dmar.c:954
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
Direct callers:
  - drivers/iommu/intel/dmar.c:alloc_iommu
```
**Symbols:**

```
ffffffff8178cf40-ffffffff8178cf6f: unmap_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void unmap_iommu(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81815b5e)
Location: drivers/iommu/intel/dmar.c:953
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
Direct callers:
  - drivers/iommu/intel/dmar.c:alloc_iommu
```
**Symbols:**

```
ffffffff818143e0-ffffffff8181440f: unmap_iommu (STB_LOCAL)
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
In drivers/iommu/intel/dmar.c (ffffffff81956301)
Location: drivers/iommu/intel/dmar.c:949
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
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
In drivers/iommu/intel/dmar.c (ffffffff81abd01b)
Location: drivers/iommu/intel/dmar.c:950
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
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
In drivers/iommu/intel/dmar.c (ffffffff81b0999c)
Location: drivers/iommu/intel/dmar.c:952
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
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
In drivers/iommu/intel/dmar.c (ffffffff81b5dadb)
Location: drivers/iommu/intel/dmar.c:952
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
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
In drivers/iommu/dmar.c (ffffffff816ac420)
Location: drivers/iommu/dmar.c:921
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_free_drhd
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
In drivers/iommu/dmar.c (ffffffff81689d80)
Location: drivers/iommu/dmar.c:921
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_free_drhd
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
In drivers/iommu/dmar.c (ffffffff816da600)
Location: drivers/iommu/dmar.c:921
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_free_drhd
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
In drivers/iommu/dmar.c (ffffffff816f4bb0)
Location: drivers/iommu/dmar.c:921
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_free_drhd
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
