# Function: <code>free_sub_pt</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page *free_sub_pt(long unsigned int root, int mode, struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81684090)
Location: drivers/iommu/amd_iommu.c:1379
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
**Symbols:**

```
ffffffff81684090-ffffffff8168422d: free_sub_pt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *free_sub_pt(long unsigned int root, int mode, struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816bb630)
Location: drivers/iommu/amd_iommu.c:1388
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
**Symbols:**

```
ffffffff816bb630-ffffffff816bb7a7: free_sub_pt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *free_sub_pt(long unsigned int root, int mode, struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816de490)
Location: drivers/iommu/amd_iommu.c:1414
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
**Symbols:**

```
ffffffff816de490-ffffffff816de607: free_sub_pt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *free_sub_pt(long unsigned int root, int mode, struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817997b0)
Location: drivers/iommu/amd/iommu.c:1352
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:iommu_map_page
```
**Symbols:**

```
ffffffff817997b0-ffffffff8179992c: free_sub_pt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *free_sub_pt(long unsigned int root, int mode, struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a7ee0)
Location: drivers/iommu/amd/iommu.c:1442
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:iommu_map_page
```
**Symbols:**

```
ffffffff817a7ee0-ffffffff817a805c: free_sub_pt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *free_sub_pt(long unsigned int root, int mode, struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/io_pgtable.c (ffffffff8178c670)
Location: drivers/iommu/amd/io_pgtable.c:128
Inline: False
Direct callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_page
```
**Symbols:**

```
ffffffff8178c670-ffffffff8178c7ee: free_sub_pt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct page *free_sub_pt(long unsigned int root, int mode, struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/io_pgtable.c (ffffffff81813d20)
Location: drivers/iommu/amd/io_pgtable.c:128
Inline: False
Direct callers:
  - drivers/iommu/amd/io_pgtable.c:v1_free_pgtable
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_page
```
**Symbols:**

```
ffffffff81813d20-ffffffff81813e9e: free_sub_pt (STB_LOCAL)
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
In drivers/iommu/amd/io_pgtable.c (ffffffff81954c08)
Location: drivers/iommu/amd/io_pgtable.c:113
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:v1_free_pgtable
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_page
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
In drivers/iommu/amd/io_pgtable.c (ffffffff81abaa78)
Location: drivers/iommu/amd/io_pgtable.c:113
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:v1_free_pgtable
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_pages
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
In drivers/iommu/amd/io_pgtable.c (ffffffff81b07148)
Location: drivers/iommu/amd/io_pgtable.c:113
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:v1_free_pgtable
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_pages
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
In drivers/iommu/amd/io_pgtable.c (ffffffff81b5b118)
Location: drivers/iommu/amd/io_pgtable.c:113
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:v1_free_pgtable
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_pages
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
<summary>In <code>aws</code>: ✅</summary>

```c
struct page *free_sub_pt(long unsigned int root, int mode, struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a3ee0)
Location: drivers/iommu/amd_iommu.c:1414
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
**Symbols:**

```
ffffffff816a3ee0-ffffffff816a4057: free_sub_pt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *free_sub_pt(long unsigned int root, int mode, struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816818d0)
Location: drivers/iommu/amd_iommu.c:1414
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
**Symbols:**

```
ffffffff816818d0-ffffffff81681a47: free_sub_pt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *free_sub_pt(long unsigned int root, int mode, struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d2150)
Location: drivers/iommu/amd_iommu.c:1414
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
**Symbols:**

```
ffffffff816d2150-ffffffff816d22c7: free_sub_pt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *free_sub_pt(long unsigned int root, int mode, struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816ec750)
Location: drivers/iommu/amd_iommu.c:1414
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
**Symbols:**

```
ffffffff816ec750-ffffffff816ec8c7: free_sub_pt (STB_LOCAL)
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
