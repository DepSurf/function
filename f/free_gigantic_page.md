# Function: <code>free_gigantic_page</code>

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
In mm/hugetlb.c (ffffffff811daa7a)
Location: mm/hugetlb.c:1022
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
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
In mm/hugetlb.c (ffffffff811f8c33)
Location: mm/hugetlb.c:1045
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
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
In mm/hugetlb.c (ffffffff81209642)
Location: mm/hugetlb.c:1045
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
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
In mm/hugetlb.c (ffffffff81214e94)
Location: mm/hugetlb.c:1063
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
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
In mm/hugetlb.c (ffffffff8122fbc2)
Location: mm/hugetlb.c:1064
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
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
In mm/hugetlb.c (ffffffff81252000)
Location: mm/hugetlb.c:1056
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
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
In mm/hugetlb.c (ffffffff812663fd)
Location: mm/hugetlb.c:1056
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
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
In mm/hugetlb.c (ffffffff8128155e)
Location: mm/hugetlb.c:1066
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
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
In mm/hugetlb.c (ffffffff8129105e)
Location: mm/hugetlb.c:1067
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
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
In mm/hugetlb.c (ffffffff812c4bd8)
Location: mm/hugetlb.c:1235
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
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
In mm/hugetlb.c (ffffffff812d0919)
Location: mm/hugetlb.c:1261
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
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
In mm/hugetlb.c (ffffffff812d61fe)
Location: mm/hugetlb.c:1270
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void free_gigantic_page(struct page *page, unsigned int order);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8131df59)
Location: mm/hugetlb.c:1284
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
Direct callers:
  - mm/hugetlb.c:gather_bootmem_prealloc
```
**Symbols:**

```
ffffffff81cbf15b-ffffffff81cbf1aa: free_gigantic_page (STB_LOCAL)
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
In mm/hugetlb.c (ffffffff83490c0e)
Location: mm/hugetlb.c:1349
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffff80001032e4e4)
Location: mm/hugetlb.c:1067
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c000000000407070)
Location: mm/hugetlb.c:1067
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffe00022c310)
Location: mm/hugetlb.c:1067
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
```
</details>
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
In mm/hugetlb.c (ffffffff8128963e)
Location: mm/hugetlb.c:1067
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
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
In mm/hugetlb.c (ffffffff8127b4de)
Location: mm/hugetlb.c:1067
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
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
In mm/hugetlb.c (ffffffff8128744e)
Location: mm/hugetlb.c:1067
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
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
In mm/hugetlb.c (ffffffff81297b8e)
Location: mm/hugetlb.c:1067
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
