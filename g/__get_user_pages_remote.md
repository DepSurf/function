# Function: <code>__get_user_pages_remote</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __get_user_pages_remote(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8128a540)
Location: mm/gup.c:1832
Inline: False
Direct callers:
  - mm/gup.c:pin_user_pages_remote
  - mm/gup.c:get_user_pages_remote
```
**Symbols:**

```
ffffffff8128a540-ffffffff8128a7f2: __get_user_pages_remote (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __get_user_pages_remote(struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81294130)
Location: mm/gup.c:1699
Inline: False
Direct callers:
  - mm/gup.c:pin_user_pages_remote
  - mm/gup.c:get_user_pages_remote
```
**Symbols:**

```
ffffffff81294130-ffffffff81294470: __get_user_pages_remote (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __get_user_pages_remote(struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81299bb0)
Location: mm/gup.c:1765
Inline: False
Direct callers:
  - mm/gup.c:pin_user_pages_remote
  - mm/gup.c:get_user_pages_remote
```
**Symbols:**

```
ffffffff81299bb0-ffffffff81299eb7: __get_user_pages_remote (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __get_user_pages_remote(struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812da540)
Location: mm/gup.c:1853
Inline: False
Direct callers:
  - mm/gup.c:pin_user_pages_remote
  - mm/gup.c:get_user_pages_remote
```
**Symbols:**

```
ffffffff812da540-ffffffff812da85b: __get_user_pages_remote (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __get_user_pages_remote(struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81339fd0)
Location: mm/gup.c:2042
Inline: False
Direct callers:
  - mm/gup.c:pin_user_pages_remote
  - mm/gup.c:get_user_pages_remote
```
**Symbols:**

```
ffffffff81339fd0-ffffffff8133a30c: __get_user_pages_remote (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
