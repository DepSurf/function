# Function: <code>swsusp_unset_page_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void swsusp_unset_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810d0977)
Location: kernel/power/snapshot.c:901
Inline: True
Inline callers:
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
Direct callers:
  - mm/page_alloc.c:mark_free_pages
```
**Symbols:**

```
ffffffff810d1080-ffffffff810d10b1: swsusp_unset_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void swsusp_unset_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810d6fb6)
Location: kernel/power/snapshot.c:999
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
Direct callers:
  - mm/page_alloc.c:mark_free_pages
```
**Symbols:**

```
ffffffff810d5dc0-ffffffff810d5df1: swsusp_unset_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void swsusp_unset_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810ddb3a)
Location: kernel/power/snapshot.c:999
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
Direct callers:
  - mm/page_alloc.c:mark_free_pages
```
**Symbols:**

```
ffffffff810dc930-ffffffff810dc95b: swsusp_unset_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void swsusp_unset_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810dcca1)
Location: kernel/power/snapshot.c:1001
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
Direct callers:
  - mm/page_alloc.c:mark_free_pages
```
**Symbols:**

```
ffffffff810dba50-ffffffff810dba7f: swsusp_unset_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void swsusp_unset_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810e4ecc)
Location: kernel/power/snapshot.c:1003
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
Direct callers:
  - mm/page_alloc.c:mark_free_pages
```
**Symbols:**

```
ffffffff810e3c70-ffffffff810e3c9f: swsusp_unset_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void swsusp_unset_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810ecb41)
Location: kernel/power/snapshot.c:1003
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
Direct callers:
  - mm/page_alloc.c:mark_free_pages
```
**Symbols:**

```
ffffffff810ebf00-ffffffff810ebf2e: swsusp_unset_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void swsusp_unset_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810f81e1)
Location: kernel/power/snapshot.c:1004
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
Direct callers:
  - mm/page_alloc.c:mark_free_pages
```
**Symbols:**

```
ffffffff810f75a0-ffffffff810f75ce: swsusp_unset_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void swsusp_unset_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81100763)
Location: kernel/power/snapshot.c:1005
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
Direct callers:
  - mm/page_alloc.c:mark_free_pages
```
**Symbols:**

```
ffffffff810ffb00-ffffffff810ffb2e: swsusp_unset_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void swsusp_unset_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff8110cbc3)
Location: kernel/power/snapshot.c:1012
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
Direct callers:
  - mm/page_alloc.c:mark_free_pages
```
**Symbols:**

```
ffffffff8110bf60-ffffffff8110bf8e: swsusp_unset_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void swsusp_unset_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81116270)
Location: kernel/power/snapshot.c:1011
Inline: True
Inline callers:
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
Direct callers:
  - kernel/power/snapshot.c:free_unnecessary_pages
  - mm/page_alloc.c:mark_free_pages
```
**Symbols:**

```
ffffffff81116ea0-ffffffff81116ece: swsusp_unset_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void swsusp_unset_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff811126f0)
Location: kernel/power/snapshot.c:1045
Inline: True
Inline callers:
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
Direct callers:
  - kernel/power/snapshot.c:free_unnecessary_pages
  - mm/page_alloc.c:mark_free_pages
```
**Symbols:**

```
ffffffff81113320-ffffffff8111334e: swsusp_unset_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void swsusp_unset_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81113141)
Location: kernel/power/snapshot.c:1045
Inline: True
Inline callers:
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:create_zone_bm_rtree
  - kernel/power/snapshot.c:create_zone_bm_rtree
Direct callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - mm/page_alloc.c:mark_free_pages
```
**Symbols:**

```
ffffffff81113c20-ffffffff81113c4e: swsusp_unset_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void swsusp_unset_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff811332e1)
Location: kernel/power/snapshot.c:1038
Inline: True
Inline callers:
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
Direct callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - mm/page_alloc.c:mark_free_pages
```
**Symbols:**

```
ffffffff81133de0-ffffffff81133e0e: swsusp_unset_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void swsusp_unset_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81155177)
Location: kernel/power/snapshot.c:1042
Inline: True
Inline callers:
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
Direct callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - mm/page_alloc.c:mark_free_pages
```
**Symbols:**

```
ffffffff81155c90-ffffffff81155cd2: swsusp_unset_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void swsusp_unset_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81187304)
Location: kernel/power/snapshot.c:1042
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
Direct callers:
  - mm/page_alloc.c:mark_free_pages
```
**Symbols:**

```
ffffffff811861e0-ffffffff81186222: swsusp_unset_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void swsusp_unset_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81198456)
Location: kernel/power/snapshot.c:1042
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
```
**Symbols:**

```
ffffffff81197360-ffffffff811973a2: swsusp_unset_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void swsusp_unset_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff811a72c6)
Location: kernel/power/snapshot.c:1052
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
```
**Symbols:**

```
ffffffff811a5eb0-ffffffff811a5ef2: swsusp_unset_page_free (STB_GLOBAL)
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
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void swsusp_unset_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (c03be044)
Location: kernel/power/snapshot.c:1012
Inline: False
Direct callers:
  - kernel/power/snapshot.c:restore_highmem
  - kernel/power/snapshot.c:snapshot_write_finalize
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - mm/page_alloc.c:mark_free_pages
```
**Symbols:**

```
c03be044-c03be0a4: swsusp_unset_page_free (STB_GLOBAL)
```
</details>
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void swsusp_unset_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81104de3)
Location: kernel/power/snapshot.c:1011
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
Direct callers:
  - mm/page_alloc.c:mark_free_pages
```
**Symbols:**

```
ffffffff81104180-ffffffff811041ae: swsusp_unset_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void swsusp_unset_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810f6083)
Location: kernel/power/snapshot.c:1012
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
Direct callers:
  - mm/page_alloc.c:mark_free_pages
```
**Symbols:**

```
ffffffff810f5420-ffffffff810f544e: swsusp_unset_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void swsusp_unset_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81103093)
Location: kernel/power/snapshot.c:1012
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
Direct callers:
  - mm/page_alloc.c:mark_free_pages
```
**Symbols:**

```
ffffffff81102430-ffffffff8110245e: swsusp_unset_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void swsusp_unset_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff8110e483)
Location: kernel/power/snapshot.c:1012
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
Direct callers:
  - mm/page_alloc.c:mark_free_pages
```
**Symbols:**

```
ffffffff8110d800-ffffffff8110d82e: swsusp_unset_page_free (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
