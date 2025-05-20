# Function: <code>dmar_free_seq_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff81533690)
Location: drivers/iommu/dmar.c:992
Inline: True
Direct callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_free_drhd
```
**Symbols:**

```
ffffffff81533690-ffffffff815336b1: dmar_free_seq_id.isra.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff81587c50)
Location: drivers/iommu/dmar.c:1004
Inline: True
Direct callers:
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
**Symbols:**

```
ffffffff81587c50-ffffffff81587c71: dmar_free_seq_id.isra.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff815b5310)
Location: drivers/iommu/dmar.c:1005
Inline: True
Direct callers:
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
**Symbols:**

```
ffffffff815b5310-ffffffff815b5331: dmar_free_seq_id.isra.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff815cb1b0)
Location: drivers/iommu/dmar.c:1008
Inline: True
Direct callers:
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
**Symbols:**

```
ffffffff815cb1b0-ffffffff815cb1d1: dmar_free_seq_id.isra.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff81631f80)
Location: drivers/iommu/dmar.c:1011
Inline: True
Direct callers:
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
**Symbols:**

```
ffffffff81631f80-ffffffff81631fa3: dmar_free_seq_id.isra.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff8166d340)
Location: drivers/iommu/dmar.c:1011
Inline: True
Direct callers:
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
**Symbols:**

```
ffffffff8166d340-ffffffff8166d362: dmar_free_seq_id.isra.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff8168b750)
Location: drivers/iommu/dmar.c:1011
Inline: True
Direct callers:
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
**Symbols:**

```
ffffffff8168b750-ffffffff8168b772: dmar_free_seq_id.isra.8 (STB_LOCAL)
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
In drivers/iommu/dmar.c (ffffffff816c3a0f)
Location: drivers/iommu/dmar.c:1000
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
In drivers/iommu/dmar.c (ffffffff816e695f)
Location: drivers/iommu/dmar.c:1010
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_free_drhd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dmar_free_seq_id(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff8179ccf0)
Location: drivers/iommu/intel/dmar.c:1015
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:free_iommu
  - drivers/iommu/intel/dmar.c:alloc_iommu
```
**Symbols:**

```
ffffffff8179ccf0-ffffffff8179cd15: dmar_free_seq_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dmar_free_seq_id(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff817aa9c0)
Location: drivers/iommu/intel/dmar.c:1038
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:free_iommu
  - drivers/iommu/intel/dmar.c:alloc_iommu
```
**Symbols:**

```
ffffffff817aa9c0-ffffffff817aa9e5: dmar_free_seq_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dmar_free_seq_id(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff8178d3b0)
Location: drivers/iommu/intel/dmar.c:1045
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
```
**Symbols:**

```
ffffffff8178d3b0-ffffffff8178d3d5: dmar_free_seq_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dmar_free_seq_id(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81814ba0)
Location: drivers/iommu/intel/dmar.c:1044
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
```
**Symbols:**

```
ffffffff81814ba0-ffffffff81814bc5: dmar_free_seq_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dmar_free_seq_id(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81955030)
Location: drivers/iommu/intel/dmar.c:1040
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
```
**Symbols:**

```
ffffffff81955030-ffffffff8195505b: dmar_free_seq_id (STB_LOCAL)
```
</details>
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
In drivers/iommu/dmar.c (ffffffff816ac43f)
Location: drivers/iommu/dmar.c:1010
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
In drivers/iommu/dmar.c (ffffffff81689d9f)
Location: drivers/iommu/dmar.c:1010
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
In drivers/iommu/dmar.c (ffffffff816da61f)
Location: drivers/iommu/dmar.c:1010
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
In drivers/iommu/dmar.c (ffffffff816f4bcf)
Location: drivers/iommu/dmar.c:1010
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
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
