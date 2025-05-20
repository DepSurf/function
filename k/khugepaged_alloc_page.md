# Function: <code>khugepaged_alloc_page</code>

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
In mm/huge_memory.c (ffffffff811f4d6f)
Location: mm/huge_memory.c:2414
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct page *khugepaged_alloc_page(struct page **hpage, gfp_t gfp, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812194e0)
Location: mm/khugepaged.c:744
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff812194e0-ffffffff8121954d: khugepaged_alloc_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct page *khugepaged_alloc_page(struct page **hpage, gfp_t gfp, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8122ba60)
Location: mm/khugepaged.c:746
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
```
**Symbols:**

```
ffffffff8122ba60-ffffffff8122bacd: khugepaged_alloc_page (STB_LOCAL)
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
In mm/khugepaged.c (ffffffff81238be4)
Location: mm/khugepaged.c:744
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
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
In mm/khugepaged.c (ffffffff81258a92)
Location: mm/khugepaged.c:750
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct page *khugepaged_alloc_page(struct page **hpage, gfp_t gfp, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8127a8a0)
Location: mm/khugepaged.c:750
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff8127a8a0-ffffffff8127a8ea: khugepaged_alloc_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page *khugepaged_alloc_page(struct page **hpage, gfp_t gfp, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8128eea0)
Location: mm/khugepaged.c:769
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff8128eea0-ffffffff8128eeea: khugepaged_alloc_page (STB_LOCAL)
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
In mm/khugepaged.c (ffffffff812aa941)
Location: mm/khugepaged.c:769
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
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
In mm/khugepaged.c (ffffffff812bbedf)
Location: mm/khugepaged.c:781
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
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
In mm/khugepaged.c (ffffffff812f13d6)
Location: mm/khugepaged.c:863
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
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
In mm/khugepaged.c (ffffffff812fd954)
Location: mm/khugepaged.c:878
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
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
In mm/khugepaged.c (ffffffff813046a6)
Location: mm/khugepaged.c:876
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
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
In mm/khugepaged.c (ffffffff8134e3dc)
Location: mm/khugepaged.c:880
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
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
In mm/khugepaged.c (ffffffff813c4af2)
Location: mm/khugepaged.c:855
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct page *khugepaged_alloc_page(struct page **hpage, gfp_t gfp, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffff80001035c738)
Location: mm/khugepaged.c:781
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffff80001035c738-ffff80001035c7fc: khugepaged_alloc_page (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page *khugepaged_alloc_page(struct page **hpage, gfp_t gfp, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (c000000000445ca0)
Location: mm/khugepaged.c:781
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
c000000000445ca0-c000000000445da4: khugepaged_alloc_page (STB_LOCAL)
```
</details>
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
In mm/khugepaged.c (ffffffff812b44bf)
Location: mm/khugepaged.c:781
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
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
In mm/khugepaged.c (ffffffff812a553f)
Location: mm/khugepaged.c:781
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
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
In mm/khugepaged.c (ffffffff812b22cf)
Location: mm/khugepaged.c:781
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
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
In mm/khugepaged.c (ffffffff812c26cf)
Location: mm/khugepaged.c:781
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
