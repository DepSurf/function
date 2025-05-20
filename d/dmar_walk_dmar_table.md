# Function: <code>dmar_walk_dmar_table</code>

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
In drivers/iommu/dmar.c (ffffffff81faa796)
Location: drivers/iommu/dmar.c:583
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:detect_intel_iommu
  - drivers/iommu/dmar.c:dmar_table_init
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
In drivers/iommu/dmar.c (ffffffff81fd7289)
Location: drivers/iommu/dmar.c:595
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:detect_intel_iommu
  - drivers/iommu/dmar.c:dmar_table_init
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
In drivers/iommu/dmar.c (ffffffff82014eb3)
Location: drivers/iommu/dmar.c:594
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:detect_intel_iommu
  - drivers/iommu/dmar.c:dmar_table_init
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
In drivers/iommu/dmar.c (ffffffff820f6a63)
Location: drivers/iommu/dmar.c:598
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:detect_intel_iommu
  - drivers/iommu/dmar.c:dmar_table_init
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
In drivers/iommu/dmar.c (ffffffff82700293)
Location: drivers/iommu/dmar.c:598
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:detect_intel_iommu
  - drivers/iommu/dmar.c:dmar_table_init
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
In drivers/iommu/dmar.c (ffffffff82729fa9)
Location: drivers/iommu/dmar.c:598
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:detect_intel_iommu
  - drivers/iommu/dmar.c:dmar_table_init
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
In drivers/iommu/dmar.c (ffffffff828e2867)
Location: drivers/iommu/dmar.c:598
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:detect_intel_iommu
  - drivers/iommu/dmar.c:dmar_table_init
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
In drivers/iommu/dmar.c (ffffffff828fd322)
Location: drivers/iommu/dmar.c:587
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:detect_intel_iommu
  - drivers/iommu/dmar.c:dmar_table_init
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
In drivers/iommu/dmar.c (ffffffff82906356)
Location: drivers/iommu/dmar.c:597
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:detect_intel_iommu
  - drivers/iommu/dmar.c:dmar_table_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dmar_walk_dmar_table(struct acpi_table_dmar *dmar, struct dmar_res_callback *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff8179ec40)
Location: drivers/iommu/intel/dmar.c:597
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:detect_intel_iommu
  - drivers/iommu/intel/dmar.c:parse_dmar_table
```
**Symbols:**

```
ffffffff8179ec40-ffffffff8179ec59: dmar_walk_dmar_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dmar_walk_dmar_table(struct acpi_table_dmar *dmar, struct dmar_res_callback *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81c0c06b)
Location: drivers/iommu/intel/dmar.c:619
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:detect_intel_iommu
  - drivers/iommu/intel/dmar.c:parse_dmar_table
```
**Symbols:**

```
ffffffff81c0c06b-ffffffff81c0c084: dmar_walk_dmar_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81bfd8f4)
Location: drivers/iommu/intel/dmar.c:625
Inline: True
Direct callers:
  - drivers/iommu/intel/dmar.c:detect_intel_iommu
  - drivers/iommu/intel/dmar.c:parse_dmar_table
```
**Symbols:**

```
ffffffff81bfd8f4-ffffffff81bfd90d: dmar_walk_dmar_table.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81cfee45)
Location: drivers/iommu/intel/dmar.c:624
Inline: True
Direct callers:
  - drivers/iommu/intel/dmar.c:detect_intel_iommu
  - drivers/iommu/intel/dmar.c:parse_dmar_table
```
**Symbols:**

```
ffffffff81cfee45-ffffffff81cfee5e: dmar_walk_dmar_table.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81ec762b)
Location: drivers/iommu/intel/dmar.c:621
Inline: True
Direct callers:
  - drivers/iommu/intel/dmar.c:detect_intel_iommu
  - drivers/iommu/intel/dmar.c:parse_dmar_table
```
**Symbols:**

```
ffffffff81ec762b-ffffffff81ec764e: dmar_walk_dmar_table.constprop.0 (STB_LOCAL)
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
In drivers/iommu/intel/dmar.c (ffffffff83ef4b8a)
Location: drivers/iommu/intel/dmar.c:621
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:detect_intel_iommu
  - drivers/iommu/intel/dmar.c:parse_dmar_table
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
In drivers/iommu/intel/dmar.c (ffffffff8371a74a)
Location: drivers/iommu/intel/dmar.c:623
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:detect_intel_iommu
  - drivers/iommu/intel/dmar.c:parse_dmar_table
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
In drivers/iommu/intel/dmar.c (ffffffff8394e22a)
Location: drivers/iommu/intel/dmar.c:623
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:detect_intel_iommu
  - drivers/iommu/intel/dmar.c:parse_dmar_table
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
In drivers/iommu/dmar.c (ffffffff828edb3d)
Location: drivers/iommu/dmar.c:597
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:detect_intel_iommu
  - drivers/iommu/dmar.c:dmar_table_init
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
In drivers/iommu/dmar.c (ffffffff828e4fca)
Location: drivers/iommu/dmar.c:597
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:detect_intel_iommu
  - drivers/iommu/dmar.c:dmar_table_init
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
In drivers/iommu/dmar.c (ffffffff82901679)
Location: drivers/iommu/dmar.c:597
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:detect_intel_iommu
  - drivers/iommu/dmar.c:dmar_table_init
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
In drivers/iommu/dmar.c (ffffffff829073b8)
Location: drivers/iommu/dmar.c:597
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:detect_intel_iommu
  - drivers/iommu/dmar.c:dmar_table_init
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
</ul>
