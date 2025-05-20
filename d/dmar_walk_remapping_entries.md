# Function: <code>dmar_walk_remapping_entries</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dmar_walk_remapping_entries(struct acpi_dmar_header *start, size_t len, struct dmar_res_callback *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff815332b0)
Location: drivers/iommu/dmar.c:544
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:detect_intel_iommu
  - drivers/iommu/dmar.c:dmar_table_init
```
**Symbols:**

```
ffffffff815332b0-ffffffff8153343e: dmar_walk_remapping_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dmar_walk_remapping_entries(struct acpi_dmar_header *start, size_t len, struct dmar_res_callback *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff81587840)
Location: drivers/iommu/dmar.c:556
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:detect_intel_iommu
  - drivers/iommu/dmar.c:dmar_table_init
```
**Symbols:**

```
ffffffff81587840-ffffffff815879c2: dmar_walk_remapping_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dmar_walk_remapping_entries(struct acpi_dmar_header *start, size_t len, struct dmar_res_callback *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff815b4f00)
Location: drivers/iommu/dmar.c:555
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:detect_intel_iommu
  - drivers/iommu/dmar.c:dmar_table_init
```
**Symbols:**

```
ffffffff815b4f00-ffffffff815b5082: dmar_walk_remapping_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dmar_walk_remapping_entries(struct acpi_dmar_header *start, size_t len, struct dmar_res_callback *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff815cad90)
Location: drivers/iommu/dmar.c:557
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:detect_intel_iommu
  - drivers/iommu/dmar.c:dmar_table_init
```
**Symbols:**

```
ffffffff815cad90-ffffffff815caf4a: dmar_walk_remapping_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dmar_walk_remapping_entries(struct acpi_dmar_header *start, size_t len, struct dmar_res_callback *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff81631b50)
Location: drivers/iommu/dmar.c:557
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:detect_intel_iommu
  - drivers/iommu/dmar.c:dmar_table_init
```
**Symbols:**

```
ffffffff81631b50-ffffffff81631d19: dmar_walk_remapping_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int dmar_walk_remapping_entries(struct acpi_dmar_header *start, size_t len, struct dmar_res_callback *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:557
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:detect_intel_iommu
  - drivers/iommu/dmar.c:dmar_table_init
```
**Symbols:**

```
ffffffff8166cf60-ffffffff8166d0a8: dmar_walk_remapping_entries (STB_LOCAL)
ffffffff8166f162-ffffffff8166f1fc: dmar_walk_remapping_entries.cold.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int dmar_walk_remapping_entries(struct acpi_dmar_header *start, size_t len, struct dmar_res_callback *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:557
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:detect_intel_iommu
  - drivers/iommu/dmar.c:dmar_table_init
```
**Symbols:**

```
ffffffff8168b2f0-ffffffff8168b438: dmar_walk_remapping_entries (STB_LOCAL)
ffffffff8168d6c2-ffffffff8168d75c: dmar_walk_remapping_entries.cold.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dmar_walk_remapping_entries(struct acpi_dmar_header *start, size_t len, struct dmar_res_callback *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:546
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:detect_intel_iommu
  - drivers/iommu/dmar.c:dmar_table_init
```
**Symbols:**

```
ffffffff816c2d40-ffffffff816c2e69: dmar_walk_remapping_entries (STB_LOCAL)
ffffffff816c50c2-ffffffff816c514b: dmar_walk_remapping_entries.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int dmar_walk_remapping_entries(struct acpi_dmar_header *start, size_t len, struct dmar_res_callback *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:556
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:detect_intel_iommu
  - drivers/iommu/dmar.c:dmar_table_init
```
**Symbols:**

```
ffffffff816e5c30-ffffffff816e5d59: dmar_walk_remapping_entries (STB_LOCAL)
ffffffff816e7ff2-ffffffff816e807b: dmar_walk_remapping_entries.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dmar_walk_remapping_entries(struct acpi_dmar_header *start, size_t len, struct dmar_res_callback *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:556
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_walk_dmar_table
```
**Symbols:**

```
ffffffff8179c510-ffffffff8179c637: dmar_walk_remapping_entries (STB_LOCAL)
ffffffff8179ebb7-ffffffff8179ec40: dmar_walk_remapping_entries.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dmar_walk_remapping_entries(struct acpi_dmar_header *start, size_t len, struct dmar_res_callback *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:578
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_walk_dmar_table
```
**Symbols:**

```
ffffffff817aa1e0-ffffffff817aa307: dmar_walk_remapping_entries (STB_LOCAL)
ffffffff81c0bfe2-ffffffff81c0c06b: dmar_walk_remapping_entries.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dmar_walk_remapping_entries(struct acpi_dmar_header *start, size_t len, struct dmar_res_callback *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:584
Inline: False
```
**Symbols:**

```
ffffffff8178cf70-ffffffff8178d0a3: dmar_walk_remapping_entries (STB_LOCAL)
ffffffff81bfd7fb-ffffffff81bfd8c0: dmar_walk_remapping_entries.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dmar_walk_remapping_entries(struct acpi_dmar_header *start, size_t len, struct dmar_res_callback *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:583
Inline: False
```
**Symbols:**

```
ffffffff81814800-ffffffff818149d0: dmar_walk_remapping_entries (STB_LOCAL)
ffffffff81cfed31-ffffffff81cfee1d: dmar_walk_remapping_entries.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dmar_walk_remapping_entries(struct acpi_dmar_header *start, size_t len, struct dmar_res_callback *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:580
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_walk_dsm_resource
```
**Symbols:**

```
ffffffff81955690-ffffffff81955864: dmar_walk_remapping_entries (STB_LOCAL)
ffffffff81ec753e-ffffffff81ec7604: dmar_walk_remapping_entries.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int dmar_walk_remapping_entries(struct acpi_dmar_header *start, size_t len, struct dmar_res_callback *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:580
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_walk_dsm_resource
  - drivers/iommu/intel/dmar.c:detect_intel_iommu
  - drivers/iommu/intel/dmar.c:parse_dmar_table
```
**Symbols:**

```
ffffffff81abc0c0-ffffffff81abc32b: dmar_walk_remapping_entries (STB_LOCAL)
ffffffff82097334-ffffffff8209735e: dmar_walk_remapping_entries.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int dmar_walk_remapping_entries(struct acpi_dmar_header *start, size_t len, struct dmar_res_callback *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:582
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_walk_dsm_resource
  - drivers/iommu/intel/dmar.c:detect_intel_iommu
  - drivers/iommu/intel/dmar.c:parse_dmar_table
```
**Symbols:**

```
ffffffff81b089b0-ffffffff81b08c1e: dmar_walk_remapping_entries (STB_LOCAL)
ffffffff82118376-ffffffff821183a0: dmar_walk_remapping_entries.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int dmar_walk_remapping_entries(struct acpi_dmar_header *start, size_t len, struct dmar_res_callback *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:582
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_walk_dsm_resource
  - drivers/iommu/intel/dmar.c:detect_intel_iommu
  - drivers/iommu/intel/dmar.c:parse_dmar_table
```
**Symbols:**

```
ffffffff81b5c9d0-ffffffff81b5cc3e: dmar_walk_remapping_entries (STB_LOCAL)
ffffffff821f608a-ffffffff821f60b4: dmar_walk_remapping_entries.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int dmar_walk_remapping_entries(struct acpi_dmar_header *start, size_t len, struct dmar_res_callback *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:556
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:detect_intel_iommu
  - drivers/iommu/dmar.c:dmar_table_init
```
**Symbols:**

```
ffffffff816ab710-ffffffff816ab839: dmar_walk_remapping_entries (STB_LOCAL)
ffffffff816adad2-ffffffff816adb5b: dmar_walk_remapping_entries.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int dmar_walk_remapping_entries(struct acpi_dmar_header *start, size_t len, struct dmar_res_callback *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:556
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:detect_intel_iommu
  - drivers/iommu/dmar.c:dmar_table_init
```
**Symbols:**

```
ffffffff81689070-ffffffff81689199: dmar_walk_remapping_entries (STB_LOCAL)
ffffffff8168b432-ffffffff8168b4bb: dmar_walk_remapping_entries.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int dmar_walk_remapping_entries(struct acpi_dmar_header *start, size_t len, struct dmar_res_callback *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:556
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:detect_intel_iommu
  - drivers/iommu/dmar.c:dmar_table_init
```
**Symbols:**

```
ffffffff816d98f0-ffffffff816d9a19: dmar_walk_remapping_entries (STB_LOCAL)
ffffffff816dbcb2-ffffffff816dbd3b: dmar_walk_remapping_entries.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int dmar_walk_remapping_entries(struct acpi_dmar_header *start, size_t len, struct dmar_res_callback *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:556
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:detect_intel_iommu
  - drivers/iommu/dmar.c:dmar_table_init
```
**Symbols:**

```
ffffffff816f3ea0-ffffffff816f3fc9: dmar_walk_remapping_entries (STB_LOCAL)
ffffffff816f6282-ffffffff816f630b: dmar_walk_remapping_entries.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
