# Function: <code>__get_user_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int __get_user_pages(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *nonblocking);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811baad0)
Location: mm/gup.c:453
Inline: False
Direct callers:
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages
  - mm/gup.c:populate_vma_page_range
  - mm/gup.c:get_dump_page
```
**Symbols:**

```
ffffffff811baad0-ffffffff811bb0ea: __get_user_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int __get_user_pages(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *nonblocking);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811d5340)
Location: mm/gup.c:519
Inline: False
Direct callers:
  - mm/gup.c:get_dump_page
  - mm/gup.c:populate_vma_page_range
  - mm/gup.c:get_user_pages
  - mm/gup.c:get_user_pages_remote
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:get_user_pages_locked
```
**Symbols:**

```
ffffffff811d5340-ffffffff811d59dd: __get_user_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int __get_user_pages(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *nonblocking);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811e5360)
Location: mm/gup.c:530
Inline: False
Direct callers:
  - mm/gup.c:get_dump_page
  - mm/gup.c:populate_vma_page_range
  - mm/gup.c:get_user_pages
  - mm/gup.c:get_user_pages_remote
  - mm/gup.c:get_user_pages_remote
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:get_user_pages_locked
```
**Symbols:**

```
ffffffff811e5360-ffffffff811e59d7: __get_user_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int __get_user_pages(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *nonblocking);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811efa20)
Location: mm/gup.c:613
Inline: False
Direct callers:
  - mm/gup.c:get_dump_page
  - mm/gup.c:populate_vma_page_range
  - mm/gup.c:get_user_pages
  - mm/gup.c:get_user_pages_remote
  - mm/gup.c:get_user_pages_remote
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:get_user_pages_locked
```
**Symbols:**

```
ffffffff811efa20-ffffffff811f0061: __get_user_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int __get_user_pages(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *nonblocking);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81206dd0)
Location: mm/gup.c:638
Inline: False
Direct callers:
  - mm/gup.c:get_dump_page
  - mm/gup.c:populate_vma_page_range
  - mm/gup.c:get_user_pages
  - mm/gup.c:get_user_pages_remote
  - mm/gup.c:get_user_pages_remote
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:get_user_pages_locked
```
**Symbols:**

```
ffffffff81206dd0-ffffffff812074af: __get_user_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int __get_user_pages(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *nonblocking);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81227b40)
Location: mm/gup.c:657
Inline: False
Direct callers:
  - mm/gup.c:get_dump_page
  - mm/gup.c:populate_vma_page_range
  - mm/gup.c:get_user_pages
  - mm/gup.c:get_user_pages_remote
  - mm/gup.c:get_user_pages_remote
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:get_user_pages_locked
```
**Symbols:**

```
ffffffff81227b40-ffffffff8122820b: __get_user_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __get_user_pages(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *nonblocking);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8123b320)
Location: mm/gup.c:674
Inline: False
Direct callers:
  - mm/gup.c:get_dump_page
  - mm/gup.c:populate_vma_page_range
  - mm/gup.c:get_user_pages
  - mm/gup.c:get_user_pages_remote
  - mm/gup.c:get_user_pages_remote
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:get_user_pages_locked
```
**Symbols:**

```
ffffffff8123b320-ffffffff8123ba2f: __get_user_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __get_user_pages(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *nonblocking);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8124c800)
Location: mm/gup.c:790
Inline: False
Direct callers:
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:get_dump_page
  - mm/gup.c:populate_vma_page_range
  - mm/gup.c:get_user_pages_remote
  - mm/gup.c:get_user_pages_remote
```
**Symbols:**

```
ffffffff8124c800-ffffffff8124cf70: __get_user_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __get_user_pages(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *nonblocking);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8125ad30)
Location: mm/gup.c:789
Inline: False
Direct callers:
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:get_dump_page
  - mm/gup.c:populate_vma_page_range
  - mm/gup.c:get_user_pages_remote
  - mm/gup.c:get_user_pages_remote
```
**Symbols:**

```
ffffffff8125ad30-ffffffff8125b4a0: __get_user_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __get_user_pages(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81289500)
Location: mm/gup.c:1031
Inline: False
Direct callers:
  - mm/gup.c:pin_user_pages_locked
  - mm/gup.c:pin_user_pages_locked
  - mm/gup.c:pin_user_pages_locked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:__get_user_pages_remote
  - mm/gup.c:__get_user_pages_remote
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:get_dump_page
  - mm/gup.c:populate_vma_page_range
```
**Symbols:**

```
ffffffff81289500-ffffffff81289a8c: __get_user_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __get_user_pages(struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812931e0)
Location: mm/gup.c:990
Inline: False
Direct callers:
  - mm/gup.c:pin_user_pages_locked
  - mm/gup.c:pin_user_pages_locked
  - mm/gup.c:pin_user_pages
  - mm/gup.c:internal_get_user_pages_fast
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:get_user_pages
  - mm/gup.c:__get_user_pages_remote
  - mm/gup.c:__get_user_pages_remote
  - mm/gup.c:__get_user_pages_remote
  - mm/gup.c:get_dump_page
  - mm/gup.c:get_dump_page
  - mm/gup.c:populate_vma_page_range
```
**Symbols:**

```
ffffffff812931e0-ffffffff81293727: __get_user_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __get_user_pages(struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81298b70)
Location: mm/gup.c:1075
Inline: False
Direct callers:
  - mm/gup.c:pin_user_pages_locked
  - mm/gup.c:pin_user_pages_locked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:__get_user_pages_remote
  - mm/gup.c:__get_user_pages_remote
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:get_dump_page
  - mm/gup.c:get_dump_page
  - mm/gup.c:populate_vma_page_range
```
**Symbols:**

```
ffffffff81298b70-ffffffff812990ce: __get_user_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __get_user_pages(struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812d95f0)
Location: mm/gup.c:1104
Inline: False
Direct callers:
  - mm/gup.c:pin_user_pages_locked
  - mm/gup.c:pin_user_pages_locked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:__get_user_pages_remote
  - mm/gup.c:__get_user_pages_remote
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:get_dump_page
  - mm/gup.c:get_dump_page
  - mm/gup.c:faultin_vma_page_range
  - mm/gup.c:populate_vma_page_range
```
**Symbols:**

```
ffffffff812d95f0-ffffffff812d9a0d: __get_user_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __get_user_pages(struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813395f0)
Location: mm/gup.c:1122
Inline: False
Direct callers:
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:__get_user_pages_remote
  - mm/gup.c:__get_user_pages_remote
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:get_dump_page
  - mm/gup.c:get_dump_page
  - mm/gup.c:faultin_vma_page_range
  - mm/gup.c:populate_vma_page_range
```
**Symbols:**

```
ffffffff813395f0-ffffffff813399f1: __get_user_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __get_user_pages(struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813b0f00)
Location: mm/gup.c:1082
Inline: False
Direct callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:get_dump_page
  - mm/gup.c:get_dump_page
  - mm/gup.c:faultin_vma_page_range
  - mm/gup.c:populate_vma_page_range
```
**Symbols:**

```
ffffffff813b0f00-ffffffff813b131a: __get_user_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __get_user_pages(struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, int *locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813e5300)
Location: mm/gup.c:1191
Inline: False
Direct callers:
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages
  - mm/gup.c:get_user_pages
  - mm/gup.c:get_user_pages_remote
  - mm/gup.c:get_user_pages_remote
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:get_dump_page
  - mm/gup.c:faultin_vma_page_range
  - mm/gup.c:populate_vma_page_range
```
**Symbols:**

```
ffffffff813e5300-ffffffff813e56cc: __get_user_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __get_user_pages(struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, int *locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8140fb90)
Location: mm/gup.c:1186
Inline: False
Direct callers:
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages
  - mm/gup.c:get_user_pages
  - mm/gup.c:get_user_pages_remote
  - mm/gup.c:get_user_pages_remote
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:get_dump_page
  - mm/gup.c:faultin_vma_page_range
  - mm/gup.c:populate_vma_page_range
```
**Symbols:**

```
ffffffff8140fb90-ffffffff8141007a: __get_user_pages (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
long int __get_user_pages(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *nonblocking);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffff8000102f24b8)
Location: mm/gup.c:789
Inline: False
Direct callers:
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:get_dump_page
  - mm/gup.c:populate_vma_page_range
  - mm/gup.c:get_user_pages_remote
  - mm/gup.c:get_user_pages_remote
```
**Symbols:**

```
ffff8000102f24b8-ffff8000102f2884: __get_user_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __get_user_pages(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *nonblocking);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (c05146b8)
Location: mm/gup.c:789
Inline: False
Direct callers:
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:get_dump_page
  - mm/gup.c:populate_vma_page_range
  - mm/gup.c:get_user_pages_remote
  - mm/gup.c:get_user_pages_remote
```
**Symbols:**

```
c05146b8-c0514bc0: __get_user_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __get_user_pages(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *nonblocking);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (c0000000003b89f0)
Location: mm/gup.c:789
Inline: False
Direct callers:
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:get_dump_page
  - mm/gup.c:populate_vma_page_range
  - mm/gup.c:get_user_pages_remote
  - mm/gup.c:get_user_pages_remote
```
**Symbols:**

```
c0000000003b89f0-c0000000003b8f90: __get_user_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __get_user_pages(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *nonblocking);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffe000204ab4)
Location: mm/gup.c:789
Inline: False
Direct callers:
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:get_dump_page
  - mm/gup.c:populate_vma_page_range
  - mm/gup.c:get_user_pages_remote
  - mm/gup.c:get_user_pages_remote
```
**Symbols:**

```
ffffffe000204ab4-ffffffe000204e36: __get_user_pages (STB_LOCAL)
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
long int __get_user_pages(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *nonblocking);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81253380)
Location: mm/gup.c:789
Inline: False
Direct callers:
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:get_dump_page
  - mm/gup.c:populate_vma_page_range
  - mm/gup.c:get_user_pages_remote
  - mm/gup.c:get_user_pages_remote
```
**Symbols:**

```
ffffffff81253380-ffffffff81253af0: __get_user_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __get_user_pages(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *nonblocking);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81246060)
Location: mm/gup.c:789
Inline: False
Direct callers:
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:get_dump_page
  - mm/gup.c:populate_vma_page_range
  - mm/gup.c:get_user_pages_remote
  - mm/gup.c:get_user_pages_remote
```
**Symbols:**

```
ffffffff81246060-ffffffff8124673b: __get_user_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __get_user_pages(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *nonblocking);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81251120)
Location: mm/gup.c:789
Inline: False
Direct callers:
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:get_dump_page
  - mm/gup.c:populate_vma_page_range
  - mm/gup.c:get_user_pages_remote
  - mm/gup.c:get_user_pages_remote
```
**Symbols:**

```
ffffffff81251120-ffffffff81251890: __get_user_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __get_user_pages(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *nonblocking);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81260aa0)
Location: mm/gup.c:789
Inline: False
Direct callers:
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:get_dump_page
  - mm/gup.c:populate_vma_page_range
  - mm/gup.c:get_user_pages_remote
  - mm/gup.c:get_user_pages_remote
```
**Symbols:**

```
ffffffff81260aa0-ffffffff81261239: __get_user_pages (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int *locked</code>
</li>
<li>
<b>Param removed. </b>
<code>int *nonblocking</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct task_struct *tsk</code>
</li>
<li>
<b>Param reordered. </b>
<code>tsk, mm, start, nr_pages, gup_flags, pages, vmas, locked</code> ➡️ <code>mm, start, nr_pages, gup_flags, pages, vmas, locked</code>
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
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct **vmas</code>
</li>
<li>
<b>Param reordered. </b>
<code>mm, start, nr_pages, gup_flags, pages, vmas, locked</code> ➡️ <code>mm, start, nr_pages, gup_flags, pages, locked</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
