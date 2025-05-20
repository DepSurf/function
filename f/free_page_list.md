# Function: <code>free_page_list</code>

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
void free_page_list(struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816846c0)
Location: drivers/iommu/amd_iommu.c:1329
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
**Symbols:**

```
ffffffff816846c0-ffffffff816846ff: free_page_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_page_list(struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816bbc10)
Location: drivers/iommu/amd_iommu.c:1338
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
**Symbols:**

```
ffffffff816bbc10-ffffffff816bbc4f: free_page_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_page_list(struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816deaa0)
Location: drivers/iommu/amd_iommu.c:1364
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
**Symbols:**

```
ffffffff816deaa0-ffffffff816deadf: free_page_list (STB_LOCAL)
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
In drivers/iommu/amd/iommu.c (ffffffff81799ae3)
Location: drivers/iommu/amd/iommu.c:1302
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:iommu_map_page
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
In drivers/iommu/amd/iommu.c (ffffffff817a8213)
Location: drivers/iommu/amd/iommu.c:1392
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:iommu_map_page
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
In drivers/iommu/amd/io_pgtable.c (ffffffff8178ca3c)
Location: drivers/iommu/amd/io_pgtable.c:77
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_page
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
In drivers/iommu/amd/io_pgtable.c (ffffffff81813f08)
Location: drivers/iommu/amd/io_pgtable.c:77
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:v1_free_pgtable
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_page
```
</details>
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
<summary>In <code>aws</code>: ✅</summary>

```c
void free_page_list(struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a44f0)
Location: drivers/iommu/amd_iommu.c:1364
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
**Symbols:**

```
ffffffff816a44f0-ffffffff816a452f: free_page_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_page_list(struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81681ee0)
Location: drivers/iommu/amd_iommu.c:1364
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
**Symbols:**

```
ffffffff81681ee0-ffffffff81681f1f: free_page_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_page_list(struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d2760)
Location: drivers/iommu/amd_iommu.c:1364
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
**Symbols:**

```
ffffffff816d2760-ffffffff816d279f: free_page_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_page_list(struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816ecda0)
Location: drivers/iommu/amd_iommu.c:1364
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
**Symbols:**

```
ffffffff816ecda0-ffffffff816ecddf: free_page_list (STB_LOCAL)
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
