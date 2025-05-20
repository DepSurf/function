# Function: <code>first_pte_l7</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816e12fc)
Location: drivers/iommu/amd_iommu.c:490
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
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
In drivers/iommu/amd/iommu.c (ffffffff81795df0)
Location: drivers/iommu/amd/iommu.c:434
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:fetch_pte
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
In drivers/iommu/amd/iommu.c (ffffffff817a4510)
Location: drivers/iommu/amd/iommu.c:443
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:fetch_pte
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
In drivers/iommu/amd/io_pgtable.c (ffffffff8178c15b)
Location: drivers/iommu/amd/io_pgtable.c:50
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:fetch_pte
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u64 *first_pte_l7(u64 *pte, long unsigned int *page_size, long unsigned int *count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/io_pgtable.c (0)
Location: drivers/iommu/amd/io_pgtable.c:50
Inline: False
Direct callers:
  - drivers/iommu/amd/io_pgtable.c:fetch_pte
```
**Symbols:**

```
ffffffff818132d0-ffffffff8181336e: first_pte_l7 (STB_LOCAL)
ffffffff81cfe9b3-ffffffff81cfe9d4: first_pte_l7.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u64 *first_pte_l7(u64 *pte, long unsigned int *page_size, long unsigned int *count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/io_pgtable.c (0)
Location: drivers/iommu/amd/io_pgtable.c:50
Inline: False
Direct callers:
  - drivers/iommu/amd/io_pgtable.c:fetch_pte
```
**Symbols:**

```
ffffffff819542b0-ffffffff81954357: first_pte_l7 (STB_LOCAL)
ffffffff81ec720f-ffffffff81ec7230: first_pte_l7.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u64 *first_pte_l7(u64 *pte, long unsigned int *page_size, long unsigned int *count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/io_pgtable.c (0)
Location: drivers/iommu/amd/io_pgtable.c:50
Inline: False
Direct callers:
  - drivers/iommu/amd/io_pgtable.c:fetch_pte
```
**Symbols:**

```
ffffffff81aba0a0-ffffffff81aba147: first_pte_l7 (STB_LOCAL)
ffffffff82097162-ffffffff82097183: first_pte_l7.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u64 *first_pte_l7(u64 *pte, long unsigned int *page_size, long unsigned int *count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/io_pgtable.c (0)
Location: drivers/iommu/amd/io_pgtable.c:50
Inline: False
Direct callers:
  - drivers/iommu/amd/io_pgtable.c:fetch_pte
```
**Symbols:**

```
ffffffff81b06640-ffffffff81b066e7: first_pte_l7 (STB_LOCAL)
ffffffff821180ab-ffffffff821180cc: first_pte_l7.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u64 *first_pte_l7(u64 *pte, long unsigned int *page_size, long unsigned int *count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/io_pgtable.c (0)
Location: drivers/iommu/amd/io_pgtable.c:50
Inline: False
Direct callers:
  - drivers/iommu/amd/io_pgtable.c:fetch_pte
```
**Symbols:**

```
ffffffff81b5a460-ffffffff81b5a507: first_pte_l7 (STB_LOCAL)
ffffffff821f5d78-ffffffff821f5d99: first_pte_l7.cold (STB_LOCAL)
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
In drivers/iommu/amd_iommu.c (ffffffff816a6d4c)
Location: drivers/iommu/amd_iommu.c:490
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
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
In drivers/iommu/amd_iommu.c (ffffffff8168473c)
Location: drivers/iommu/amd_iommu.c:490
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
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
In drivers/iommu/amd_iommu.c (ffffffff816d4fbc)
Location: drivers/iommu/amd_iommu.c:490
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
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
In drivers/iommu/amd_iommu.c (ffffffff816ef6bc)
Location: drivers/iommu/amd_iommu.c:490
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
