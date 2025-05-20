# Function: <code>alloc_huge_page_nodemask</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct page *alloc_huge_page_nodemask(struct hstate *h, int preferred_nid, nodemask_t *nmask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81216bd0)
Location: mm/hugetlb.c:1645
Inline: False
Direct callers:
  - mm/memory_hotplug.c:new_node_page
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
```
**Symbols:**

```
ffffffff81216bd0-ffffffff81216c9b: alloc_huge_page_nodemask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct page *alloc_huge_page_nodemask(struct hstate *h, int preferred_nid, nodemask_t *nmask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81231880)
Location: mm/hugetlb.c:1651
Inline: False
Direct callers:
  - mm/memory_hotplug.c:new_node_page
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
```
**Symbols:**

```
ffffffff81231880-ffffffff8123194b: alloc_huge_page_nodemask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct page *alloc_huge_page_nodemask(struct hstate *h, int preferred_nid, nodemask_t *nmask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812547a0)
Location: mm/hugetlb.c:1651
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/memory_hotplug.c:new_node_page
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
```
**Symbols:**

```
ffffffff812547a0-ffffffff81254874: alloc_huge_page_nodemask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page *alloc_huge_page_nodemask(struct hstate *h, int preferred_nid, nodemask_t *nmask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81268b80)
Location: mm/hugetlb.c:1651
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/memory_hotplug.c:new_node_page
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
```
**Symbols:**

```
ffffffff81268b80-ffffffff81268c54: alloc_huge_page_nodemask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *alloc_huge_page_nodemask(struct hstate *h, int preferred_nid, nodemask_t *nmask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81283c50)
Location: mm/hugetlb.c:1694
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/memory_hotplug.c:new_node_page
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
```
**Symbols:**

```
ffffffff81283c50-ffffffff81283d3f: alloc_huge_page_nodemask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *alloc_huge_page_nodemask(struct hstate *h, int preferred_nid, nodemask_t *nmask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812937f0)
Location: mm/hugetlb.c:1774
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/memory_hotplug.c:new_node_page
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
```
**Symbols:**

```
ffffffff812937f0-ffffffff812938df: alloc_huge_page_nodemask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *alloc_huge_page_nodemask(struct hstate *h, int preferred_nid, nodemask_t *nmask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812c6c30)
Location: mm/hugetlb.c:2019
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/memory_hotplug.c:new_node_page
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
```
**Symbols:**

```
ffffffff812c6c30-ffffffff812c6d1c: alloc_huge_page_nodemask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *alloc_huge_page_nodemask(struct hstate *h, int preferred_nid, nodemask_t *nmask, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d27c0)
Location: mm/hugetlb.c:1968
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/migrate.c:alloc_migration_target
```
**Symbols:**

```
ffffffff812d27c0-ffffffff812d2873: alloc_huge_page_nodemask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *alloc_huge_page_nodemask(struct hstate *h, int preferred_nid, nodemask_t *nmask, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d9210)
Location: mm/hugetlb.c:1915
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/migrate.c:alloc_migration_target
```
**Symbols:**

```
ffffffff812d9210-ffffffff812d92ca: alloc_huge_page_nodemask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct page *alloc_huge_page_nodemask(struct hstate *h, int preferred_nid, nodemask_t *nmask, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8131fcf0)
Location: mm/hugetlb.c:2179
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/migrate.c:alloc_migration_target
```
**Symbols:**

```
ffffffff8131fcf0-ffffffff8131fdaa: alloc_huge_page_nodemask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct page *alloc_huge_page_nodemask(struct hstate *h, int preferred_nid, nodemask_t *nmask, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8138ca30)
Location: mm/hugetlb.c:2291
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/migrate.c:alloc_migration_target
```
**Symbols:**

```
ffffffff8138ca30-ffffffff8138cafc: alloc_huge_page_nodemask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct page *alloc_huge_page_nodemask(struct hstate *h, int preferred_nid, nodemask_t *nmask, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8140b430)
Location: mm/hugetlb.c:2477
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/migrate.c:alloc_migration_target
```
**Symbols:**

```
ffffffff8140b430-ffffffff8140b503: alloc_huge_page_nodemask (STB_GLOBAL)
```
</details>
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
struct page *alloc_huge_page_nodemask(struct hstate *h, int preferred_nid, nodemask_t *nmask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffff800010331a08)
Location: mm/hugetlb.c:1774
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
```
**Symbols:**

```
ffff800010331a08-ffff800010331b64: alloc_huge_page_nodemask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (0)
Location: include/linux/hugetlb.h:607
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page *alloc_huge_page_nodemask(struct hstate *h, int preferred_nid, nodemask_t *nmask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c00000000040a980)
Location: mm/hugetlb.c:1774
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/memory_hotplug.c:new_node_page
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
```
**Symbols:**

```
c00000000040a980-c00000000040abb0: alloc_huge_page_nodemask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct page *alloc_huge_page_nodemask(struct hstate *h, int preferred_nid, nodemask_t *nmask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffe00022e95e)
Location: mm/hugetlb.c:1774
Inline: True
Direct callers:
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/page_isolation.c:alloc_migrate_target
```
**Symbols:**

```
ffffffe00022e95e-ffffffe00022ea78: alloc_huge_page_nodemask (STB_GLOBAL)
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
struct page *alloc_huge_page_nodemask(struct hstate *h, int preferred_nid, nodemask_t *nmask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128bdd0)
Location: mm/hugetlb.c:1774
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/memory_hotplug.c:new_node_page
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
```
**Symbols:**

```
ffffffff8128bdd0-ffffffff8128bebf: alloc_huge_page_nodemask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *alloc_huge_page_nodemask(struct hstate *h, int preferred_nid, nodemask_t *nmask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8127dc00)
Location: mm/hugetlb.c:1774
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/memory_hotplug.c:new_node_page
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
```
**Symbols:**

```
ffffffff8127dc00-ffffffff8127dcef: alloc_huge_page_nodemask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *alloc_huge_page_nodemask(struct hstate *h, int preferred_nid, nodemask_t *nmask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81289be0)
Location: mm/hugetlb.c:1774
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/memory_hotplug.c:new_node_page
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
```
**Symbols:**

```
ffffffff81289be0-ffffffff81289ccf: alloc_huge_page_nodemask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *alloc_huge_page_nodemask(struct hstate *h, int preferred_nid, nodemask_t *nmask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812999e0)
Location: mm/hugetlb.c:1774
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/memory_hotplug.c:new_node_page
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
```
**Symbols:**

```
ffffffff812999e0-ffffffff81299ad3: alloc_huge_page_nodemask (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp_mask</code>
</li>
</ul>
</details>
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
