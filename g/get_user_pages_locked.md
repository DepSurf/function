# Function: <code>get_user_pages_locked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int get_user_pages_locked(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, int write, int force, struct page **pages, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811bb0f0)
Location: mm/gup.c:738
Inline: False
Direct callers:
  - mm/frame_vector.c:get_vaddr_frames
```
**Symbols:**

```
ffffffff811bb0f0-ffffffff811bb2b9: get_user_pages_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int get_user_pages_locked(long unsigned int start, long unsigned int nr_pages, int write, int force, struct page **pages, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811d59e0)
Location: mm/gup.c:845
Inline: False
Direct callers:
  - mm/frame_vector.c:get_vaddr_frames
```
**Symbols:**

```
ffffffff811d59e0-ffffffff811d5bb3: get_user_pages_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int get_user_pages_locked(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811e59e0)
Location: mm/gup.c:851
Inline: False
Direct callers:
  - mm/frame_vector.c:get_vaddr_frames
```
**Symbols:**

```
ffffffff811e59e0-ffffffff811e5b91: get_user_pages_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int get_user_pages_locked(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811f0070)
Location: mm/gup.c:932
Inline: False
Direct callers:
  - mm/frame_vector.c:get_vaddr_frames
```
**Symbols:**

```
ffffffff811f0070-ffffffff811f0212: get_user_pages_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int get_user_pages_locked(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812074b0)
Location: mm/gup.c:957
Inline: False
Direct callers:
  - mm/frame_vector.c:get_vaddr_frames
```
**Symbols:**

```
ffffffff812074b0-ffffffff81207652: get_user_pages_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int get_user_pages_locked(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81228210)
Location: mm/gup.c:979
Inline: False
Direct callers:
  - mm/frame_vector.c:get_vaddr_frames
```
**Symbols:**

```
ffffffff81228210-ffffffff812283b2: get_user_pages_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int get_user_pages_locked(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8123ba30)
Location: mm/gup.c:1004
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/frame_vector.c:get_vaddr_frames
```
**Symbols:**

```
ffffffff8123ba30-ffffffff8123bbd2: get_user_pages_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int get_user_pages_locked(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8124d1a0)
Location: mm/gup.c:1644
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/frame_vector.c:get_vaddr_frames
```
**Symbols:**

```
ffffffff8124d1a0-ffffffff8124d3b5: get_user_pages_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int get_user_pages_locked(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8125b6d0)
Location: mm/gup.c:1647
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/frame_vector.c:get_vaddr_frames
```
**Symbols:**

```
ffffffff8125b6d0-ffffffff8125b8e5: get_user_pages_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int get_user_pages_locked(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81289a90)
Location: mm/gup.c:2025
Inline: False
Direct callers:
  - mm/mempolicy.c:lookup_node
```
**Symbols:**

```
ffffffff81289a90-ffffffff81289d21: get_user_pages_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int get_user_pages_locked(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81293730)
Location: mm/gup.c:1881
Inline: False
Direct callers:
  - mm/mempolicy.c:lookup_node
```
**Symbols:**

```
ffffffff81293730-ffffffff81293a0e: get_user_pages_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int get_user_pages_locked(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812990d0)
Location: mm/gup.c:1947
Inline: False
Direct callers:
  - mm/mempolicy.c:do_get_mempolicy
```
**Symbols:**

```
ffffffff812990d0-ffffffff812993a8: get_user_pages_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int get_user_pages_locked(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812d9a10)
Location: mm/gup.c:2035
Inline: False
Direct callers:
  - mm/mempolicy.c:lookup_node
```
**Symbols:**

```
ffffffff812d9a10-ffffffff812d9ce8: get_user_pages_locked (STB_GLOBAL)
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
long int get_user_pages_locked(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffff8000102f2ad8)
Location: mm/gup.c:1647
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/frame_vector.c:get_vaddr_frames
```
**Symbols:**

```
ffff8000102f2ad8-ffff8000102f2cec: get_user_pages_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int get_user_pages_locked(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (c0514e60)
Location: mm/gup.c:1647
Inline: False
Direct callers:
  - mm/frame_vector.c:get_vaddr_frames
```
**Symbols:**

```
c0514e60-c05150d8: get_user_pages_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int get_user_pages_locked(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (c0000000003b9270)
Location: mm/gup.c:1647
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/frame_vector.c:get_vaddr_frames
```
**Symbols:**

```
c0000000003b9270-c0000000003b954c: get_user_pages_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int get_user_pages_locked(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffe000204fd6)
Location: mm/gup.c:1647
Inline: False
Direct callers:
  - mm/frame_vector.c:get_vaddr_frames
```
**Symbols:**

```
ffffffe000204fd6-ffffffe000205164: get_user_pages_locked (STB_GLOBAL)
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
long int get_user_pages_locked(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81253d20)
Location: mm/gup.c:1647
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/frame_vector.c:get_vaddr_frames
```
**Symbols:**

```
ffffffff81253d20-ffffffff81253f35: get_user_pages_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int get_user_pages_locked(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81246970)
Location: mm/gup.c:1647
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/frame_vector.c:get_vaddr_frames
```
**Symbols:**

```
ffffffff81246970-ffffffff81246b85: get_user_pages_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int get_user_pages_locked(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81251ac0)
Location: mm/gup.c:1647
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/frame_vector.c:get_vaddr_frames
```
**Symbols:**

```
ffffffff81251ac0-ffffffff81251cd5: get_user_pages_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int get_user_pages_locked(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81261470)
Location: mm/gup.c:1647
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/frame_vector.c:get_vaddr_frames
```
**Symbols:**

```
ffffffff81261470-ffffffff81261685: get_user_pages_locked (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct task_struct *tsk</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mm_struct *mm</code>
</li>
<li>
<b>Param reordered. </b>
<code>tsk, mm, start, nr_pages, write, force, pages, locked</code> ➡️ <code>start, nr_pages, write, force, pages, locked</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int gup_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int write</code>
</li>
<li>
<b>Param removed. </b>
<code>int force</code>
</li>
<li>
<b>Param reordered. </b>
<code>start, nr_pages, write, force, pages, locked</code> ➡️ <code>start, nr_pages, gup_flags, pages, locked</code>
</li>
</ul>
</details>
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
