# Function: <code>isolate_huge_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool isolate_huge_page(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811dfa80)
Location: mm/hugetlb.c:4416
Inline: False
Direct callers:
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/migrate.c:SyS_move_pages
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff811dfa80-ffffffff811dfb2a: isolate_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool isolate_huge_page(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811fe120)
Location: mm/hugetlb.c:4437
Inline: False
Direct callers:
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/migrate.c:SyS_move_pages
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff811fe120-ffffffff811fe1ca: isolate_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool isolate_huge_page(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8120ebf0)
Location: mm/hugetlb.c:4550
Inline: False
Direct callers:
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/migrate.c:SYSC_move_pages
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff8120ebf0-ffffffff8120ec9a: isolate_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool isolate_huge_page(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8121a4a0)
Location: mm/hugetlb.c:4703
Inline: False
Direct callers:
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/migrate.c:SYSC_move_pages
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff8121a4a0-ffffffff8121a53e: isolate_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool isolate_huge_page(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81235610)
Location: mm/hugetlb.c:4783
Inline: False
Direct callers:
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/memory_hotplug.c:__offline_pages
  - mm/migrate.c:SYSC_move_pages
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff81235610-ffffffff812356ae: isolate_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool isolate_huge_page(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81258550)
Location: mm/hugetlb.c:4812
Inline: False
Direct callers:
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/memory_hotplug.c:__offline_pages
  - mm/migrate.c:kernel_move_pages
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff81258550-ffffffff812585ee: isolate_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool isolate_huge_page(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8126cc20)
Location: mm/hugetlb.c:4901
Inline: False
Direct callers:
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/memory_hotplug.c:__offline_pages
  - mm/migrate.c:kernel_move_pages
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff8126cc20-ffffffff8126ccc0: isolate_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool isolate_huge_page(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81288050)
Location: mm/hugetlb.c:5006
Inline: False
Direct callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/memory_hotplug.c:do_migrate_range
  - mm/migrate.c:do_pages_move
```
**Symbols:**

```
ffffffff81288050-ffffffff812880e1: isolate_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool isolate_huge_page(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81297c50)
Location: mm/hugetlb.c:5123
Inline: False
Direct callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/memory_hotplug.c:do_migrate_range
  - mm/migrate.c:do_pages_move
```
**Symbols:**

```
ffffffff81297c50-ffffffff81297ce1: isolate_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool isolate_huge_page(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812cb310)
Location: mm/hugetlb.c:5622
Inline: False
Direct callers:
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/migrate.c:add_page_for_migration
```
**Symbols:**

```
ffffffff812cb310-ffffffff812cb3a1: isolate_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool isolate_huge_page(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d6f20)
Location: mm/hugetlb.c:5634
Inline: False
Direct callers:
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/migrate.c:add_page_for_migration
  - mm/memory-failure.c:isolate_page
```
**Symbols:**

```
ffffffff812d6f20-ffffffff812d6fc1: isolate_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool isolate_huge_page(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812de130)
Location: mm/hugetlb.c:5914
Inline: False
Direct callers:
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/migrate.c:add_page_for_migration
  - mm/memory-failure.c:__soft_offline_page
```
**Symbols:**

```
ffffffff812de130-ffffffff812de1cd: isolate_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool isolate_huge_page(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81325360)
Location: mm/hugetlb.c:6251
Inline: False
Direct callers:
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/migrate.c:add_page_for_migration
  - mm/memory-failure.c:__soft_offline_page
```
**Symbols:**

```
ffffffff81325360-ffffffff813253fd: isolate_huge_page (STB_GLOBAL)
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
bool isolate_huge_page(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffff800010335f70)
Location: mm/hugetlb.c:5123
Inline: False
Direct callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/migrate.c:do_pages_move
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffff800010335f70-ffff8000103360d4: isolate_huge_page (STB_GLOBAL)
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
In mm/gup.c (0)
Location: include/linux/hugetlb.h:190
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool isolate_huge_page(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c000000000410730)
Location: mm/hugetlb.c:5123
Inline: False
Direct callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/memory_hotplug.c:do_migrate_range
  - mm/migrate.c:do_pages_move
```
**Symbols:**

```
c000000000410730-c0000000004108a8: isolate_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool isolate_huge_page(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffe0002320a0)
Location: mm/hugetlb.c:5123
Inline: False
Direct callers:
  - mm/gup.c:__gup_longterm_locked
```
**Symbols:**

```
ffffffe0002320a0-ffffffe00023217e: isolate_huge_page (STB_GLOBAL)
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
bool isolate_huge_page(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81290230)
Location: mm/hugetlb.c:5123
Inline: False
Direct callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/memory_hotplug.c:do_migrate_range
  - mm/migrate.c:do_pages_move
```
**Symbols:**

```
ffffffff81290230-ffffffff812902c1: isolate_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool isolate_huge_page(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81281ec0)
Location: mm/hugetlb.c:5123
Inline: False
Direct callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/memory_hotplug.c:do_migrate_range
  - mm/migrate.c:do_pages_move
```
**Symbols:**

```
ffffffff81281ec0-ffffffff81281f51: isolate_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool isolate_huge_page(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128e040)
Location: mm/hugetlb.c:5123
Inline: False
Direct callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/memory_hotplug.c:do_migrate_range
  - mm/migrate.c:do_pages_move
```
**Symbols:**

```
ffffffff8128e040-ffffffff8128e0d1: isolate_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool isolate_huge_page(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8129dde0)
Location: mm/hugetlb.c:5123
Inline: False
Direct callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/memory_hotplug.c:do_migrate_range
  - mm/migrate.c:do_pages_move
```
**Symbols:**

```
ffffffff8129dde0-ffffffff8129de73: isolate_huge_page (STB_GLOBAL)
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
