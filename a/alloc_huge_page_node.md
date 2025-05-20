# Function: <code>alloc_huge_page_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct page *alloc_huge_page_node(struct hstate *h, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811dc800)
Location: mm/hugetlb.c:1623
Inline: False
Direct callers:
  - mm/migrate.c:new_page_node
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
```
**Symbols:**

```
ffffffff811dc800-ffffffff811dc872: alloc_huge_page_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct page *alloc_huge_page_node(struct hstate *h, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811faa70)
Location: mm/hugetlb.c:1651
Inline: False
Direct callers:
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:new_page_node
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
```
**Symbols:**

```
ffffffff811faa70-ffffffff811faae2: alloc_huge_page_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct page *alloc_huge_page_node(struct hstate *h, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8120b570)
Location: mm/hugetlb.c:1674
Inline: False
Direct callers:
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:new_page_node
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
```
**Symbols:**

```
ffffffff8120b570-ffffffff8120b5e2: alloc_huge_page_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct page *alloc_huge_page_node(struct hstate *h, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81216b20)
Location: mm/hugetlb.c:1625
Inline: False
Direct callers:
  - mm/migrate.c:new_page_node
```
**Symbols:**

```
ffffffff81216b20-ffffffff81216bcf: alloc_huge_page_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct page *alloc_huge_page_node(struct hstate *h, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812317d0)
Location: mm/hugetlb.c:1631
Inline: False
Direct callers:
  - mm/migrate.c:new_page_node
```
**Symbols:**

```
ffffffff812317d0-ffffffff8123187f: alloc_huge_page_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct page *alloc_huge_page_node(struct hstate *h, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812546e0)
Location: mm/hugetlb.c:1631
Inline: False
```
**Symbols:**

```
ffffffff812546e0-ffffffff8125479b: alloc_huge_page_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page *alloc_huge_page_node(struct hstate *h, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81268ac0)
Location: mm/hugetlb.c:1631
Inline: False
```
**Symbols:**

```
ffffffff81268ac0-ffffffff81268b7b: alloc_huge_page_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *alloc_huge_page_node(struct hstate *h, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81283b70)
Location: mm/hugetlb.c:1674
Inline: False
```
**Symbols:**

```
ffffffff81283b70-ffffffff81283c46: alloc_huge_page_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *alloc_huge_page_node(struct hstate *h, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81293710)
Location: mm/hugetlb.c:1754
Inline: False
```
**Symbols:**

```
ffffffff81293710-ffffffff812937e6: alloc_huge_page_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *alloc_huge_page_node(struct hstate *h, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812c6b50)
Location: mm/hugetlb.c:1999
Inline: False
```
**Symbols:**

```
ffffffff812c6b50-ffffffff812c6c2a: alloc_huge_page_node (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct page *alloc_huge_page_node(struct hstate *h, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffff8000103318b0)
Location: mm/hugetlb.c:1754
Inline: False
```
**Symbols:**

```
ffff8000103318b0-ffff800010331a08: alloc_huge_page_node (STB_GLOBAL)
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
struct page *alloc_huge_page_node(struct hstate *h, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c00000000040a7a0)
Location: mm/hugetlb.c:1754
Inline: False
```
**Symbols:**

```
c00000000040a7a0-c00000000040a980: alloc_huge_page_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct page *alloc_huge_page_node(struct hstate *h, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffe00022e87e)
Location: mm/hugetlb.c:1754
Inline: False
```
**Symbols:**

```
ffffffe00022e87e-ffffffe00022e95e: alloc_huge_page_node (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct page *alloc_huge_page_node(struct hstate *h, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128bcf0)
Location: mm/hugetlb.c:1754
Inline: False
```
**Symbols:**

```
ffffffff8128bcf0-ffffffff8128bdc6: alloc_huge_page_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *alloc_huge_page_node(struct hstate *h, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8127db20)
Location: mm/hugetlb.c:1754
Inline: False
```
**Symbols:**

```
ffffffff8127db20-ffffffff8127dbf6: alloc_huge_page_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *alloc_huge_page_node(struct hstate *h, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81289b00)
Location: mm/hugetlb.c:1754
Inline: False
```
**Symbols:**

```
ffffffff81289b00-ffffffff81289bd6: alloc_huge_page_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *alloc_huge_page_node(struct hstate *h, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812998f0)
Location: mm/hugetlb.c:1754
Inline: False
```
**Symbols:**

```
ffffffff812998f0-ffffffff812999dc: alloc_huge_page_node (STB_GLOBAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
