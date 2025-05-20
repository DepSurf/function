# Function: <code>__gup_longterm_locked</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __gup_longterm_locked(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, struct page **pages, struct vm_area_struct **vmas, unsigned int gup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8124d5b0)
Location: mm/gup.c:1543
Inline: False
Direct callers:
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:get_user_pages
```
**Symbols:**

```
ffffffff8124d5b0-ffffffff8124dab1: __gup_longterm_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __gup_longterm_locked(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, struct page **pages, struct vm_area_struct **vmas, unsigned int gup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8125bae0)
Location: mm/gup.c:1546
Inline: False
Direct callers:
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:get_user_pages
```
**Symbols:**

```
ffffffff8125bae0-ffffffff8125bfe8: __gup_longterm_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __gup_longterm_locked(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, struct page **pages, struct vm_area_struct **vmas, unsigned int gup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8128a290)
Location: mm/gup.c:1767
Inline: False
Direct callers:
  - mm/gup.c:pin_user_pages
  - mm/gup.c:internal_get_user_pages_fast
  - mm/gup.c:get_user_pages
  - mm/gup.c:__get_user_pages_remote
```
**Symbols:**

```
ffffffff8128a290-ffffffff8128a49b: __gup_longterm_locked (STB_LOCAL)
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
In mm/gup.c (ffffffff812940fa)
Location: mm/gup.c:1654
Inline: True
Inline callers:
  - mm/gup.c:pin_user_pages
  - mm/gup.c:internal_get_user_pages_fast
  - mm/gup.c:get_user_pages
  - mm/gup.c:__get_user_pages_remote
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __gup_longterm_locked(struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, struct page **pages, struct vm_area_struct **vmas, unsigned int gup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812999d0)
Location: mm/gup.c:1719
Inline: False
Direct callers:
  - mm/gup.c:pin_user_pages
  - mm/gup.c:internal_get_user_pages_fast
  - mm/gup.c:get_user_pages
  - mm/gup.c:__get_user_pages_remote
```
**Symbols:**

```
ffffffff812999d0-ffffffff81299ae7: __gup_longterm_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __gup_longterm_locked(struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, struct page **pages, struct vm_area_struct **vmas, unsigned int gup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812da350)
Location: mm/gup.c:1807
Inline: False
Direct callers:
  - mm/gup.c:pin_user_pages
  - mm/gup.c:internal_get_user_pages_fast
  - mm/gup.c:get_user_pages
  - mm/gup.c:__get_user_pages_remote
```
**Symbols:**

```
ffffffff812da350-ffffffff812da488: __gup_longterm_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __gup_longterm_locked(struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, struct page **pages, struct vm_area_struct **vmas, unsigned int gup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81339d60)
Location: mm/gup.c:1996
Inline: False
Direct callers:
  - mm/gup.c:pin_user_pages
  - mm/gup.c:internal_get_user_pages_fast
  - mm/gup.c:get_user_pages
  - mm/gup.c:__get_user_pages_remote
```
**Symbols:**

```
ffffffff81339d60-ffffffff81339eab: __gup_longterm_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __gup_longterm_locked(struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, struct page **pages, struct vm_area_struct **vmas, int *locked, unsigned int gup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813b1330)
Location: mm/gup.c:2042
Inline: False
Direct callers:
  - mm/gup.c:pin_user_pages
  - mm/gup.c:pin_user_pages_remote
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages
  - mm/gup.c:get_user_pages_remote
```
**Symbols:**

```
ffffffff813b1330-ffffffff813b1a87: __gup_longterm_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __gup_longterm_locked(struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, struct page **pages, int *locked, unsigned int gup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813e6140)
Location: mm/gup.c:2174
Inline: False
Direct callers:
  - mm/gup.c:pin_user_pages_unlocked
  - mm/gup.c:pin_user_pages
  - mm/gup.c:pin_user_pages_remote
  - mm/gup.c:internal_get_user_pages_fast
```
**Symbols:**

```
ffffffff813e6140-ffffffff813e697c: __gup_longterm_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __gup_longterm_locked(struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, struct page **pages, int *locked, unsigned int gup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81410ca0)
Location: mm/gup.c:2200
Inline: False
Direct callers:
  - mm/gup.c:pin_user_pages_unlocked
  - mm/gup.c:pin_user_pages
  - mm/gup.c:pin_user_pages_remote
  - mm/gup.c:internal_get_user_pages_fast
```
**Symbols:**

```
ffffffff81410ca0-ffffffff81411615: __gup_longterm_locked (STB_LOCAL)
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
long int __gup_longterm_locked(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, struct page **pages, struct vm_area_struct **vmas, unsigned int gup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffff8000102f2ee8)
Location: mm/gup.c:1546
Inline: False
Direct callers:
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:get_user_pages
```
**Symbols:**

```
ffff8000102f2ee8-ffff8000102f33bc: __gup_longterm_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __gup_longterm_locked(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, struct page **pages, struct vm_area_struct **vmas, unsigned int gup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (c0515314)
Location: mm/gup.c:1546
Inline: False
Direct callers:
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:get_user_pages
```
**Symbols:**

```
c0515314-c0515720: __gup_longterm_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __gup_longterm_locked(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, struct page **pages, struct vm_area_struct **vmas, unsigned int gup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (c0000000003b9840)
Location: mm/gup.c:1546
Inline: False
Direct callers:
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:get_user_pages
```
**Symbols:**

```
c0000000003b9840-c0000000003b9f2c: __gup_longterm_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __gup_longterm_locked(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, struct page **pages, struct vm_area_struct **vmas, unsigned int gup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffe0002052ca)
Location: mm/gup.c:1546
Inline: False
Direct callers:
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:get_user_pages
```
**Symbols:**

```
ffffffe0002052ca-ffffffe000205658: __gup_longterm_locked (STB_LOCAL)
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
long int __gup_longterm_locked(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, struct page **pages, struct vm_area_struct **vmas, unsigned int gup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81254130)
Location: mm/gup.c:1546
Inline: False
Direct callers:
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:get_user_pages
```
**Symbols:**

```
ffffffff81254130-ffffffff81254638: __gup_longterm_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __gup_longterm_locked(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, struct page **pages, struct vm_area_struct **vmas, unsigned int gup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81246d80)
Location: mm/gup.c:1546
Inline: False
Direct callers:
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:get_user_pages
```
**Symbols:**

```
ffffffff81246d80-ffffffff81247288: __gup_longterm_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __gup_longterm_locked(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, struct page **pages, struct vm_area_struct **vmas, unsigned int gup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81251ed0)
Location: mm/gup.c:1546
Inline: False
Direct callers:
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:get_user_pages
```
**Symbols:**

```
ffffffff81251ed0-ffffffff812523d8: __gup_longterm_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __gup_longterm_locked(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, struct page **pages, struct vm_area_struct **vmas, unsigned int gup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81261880)
Location: mm/gup.c:1546
Inline: False
Direct callers:
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:get_user_pages
```
**Symbols:**

```
ffffffff81261880-ffffffff81261d88: __gup_longterm_locked (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int *locked</code>
</li>
<li>
<b>Param reordered. </b>
<code>mm, start, nr_pages, pages, vmas, gup_flags</code> ➡️ <code>mm, start, nr_pages, pages, vmas, locked, gup_flags</code>
</li>
</ul>
</details>
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
<code>mm, start, nr_pages, pages, vmas, locked, gup_flags</code> ➡️ <code>mm, start, nr_pages, pages, locked, gup_flags</code>
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
