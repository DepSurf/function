# Function: <code>page_ref_sub_and_test</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811ab3ca)
Location: include/linux/page_ref.h:118
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_page_frag
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
In mm/page_alloc.c (ffffffff811bb9a4)
Location: include/linux/page_ref.h:118
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
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
In mm/page_alloc.c (ffffffff811c3c80)
Location: include/linux/page_ref.h:118
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
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
In mm/page_alloc.c (ffffffff811d8a20)
Location: include/linux/page_ref.h:119
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
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
In mm/page_alloc.c (ffffffff811f9c57)
Location: include/linux/page_ref.h:119
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
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
In mm/page_alloc.c (ffffffff8120c2fd)
Location: include/linux/page_ref.h:119
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
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
In mm/page_alloc.c (ffffffff81272564)
Location: include/linux/page_ref.h:119
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
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
In mm/page_alloc.c (ffffffff812813c4)
Location: include/linux/page_ref.h:119
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81287af8)
Location: include/linux/page_ref.h:128
Inline: True
Inline callers:
  - mm/gup.c:unpin_user_page
```
```
In mm/page_alloc.c (ffffffff812b389b)
Location: include/linux/page_ref.h:128
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
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
In mm/page_alloc.c (ffffffff812bf379)
Location: include/linux/page_ref.h:128
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
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
In mm/page_alloc.c (ffffffff812c441d)
Location: include/linux/page_ref.h:128
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
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
In mm/page_alloc.c (ffffffff813082dd)
Location: include/linux/page_ref.h:128
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812f2815)
Location: include/linux/page_ref.h:180
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:filemap_free_folio
```
```
In mm/gup.c (ffffffff8133706c)
Location: include/linux/page_ref.h:180
Inline: True
Inline callers:
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_get_folio
```
```
In mm/page_alloc.c (ffffffff813705e9)
Location: include/linux/page_ref.h:180
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8135acc8)
Location: include/linux/page_ref.h:180
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:filemap_free_folio
```
```
In mm/shmem.c (ffffffff8138ac63)
Location: include/linux/page_ref.h:180
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_folio
```
```
In mm/gup.c (ffffffff813ae52c)
Location: include/linux/page_ref.h:180
Inline: True
Inline callers:
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/page_alloc.c (ffffffff813ed57b)
Location: include/linux/page_ref.h:180
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8138c6ec)
Location: include/linux/page_ref.h:180
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:filemap_free_folio
```
```
In mm/shmem.c (ffffffff813bd189)
Location: include/linux/page_ref.h:180
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_folio
```
```
In mm/gup.c (ffffffff813e2d7e)
Location: include/linux/page_ref.h:180
Inline: True
Inline callers:
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/page_alloc.c (ffffffff81422513)
Location: include/linux/page_ref.h:180
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
```
```
In mm/khugepaged.c (ffffffff814804cb)
Location: include/linux/page_ref.h:180
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813b624f)
Location: include/linux/page_ref.h:180
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:filemap_free_folio
```
```
In mm/shmem.c (ffffffff813e7ff9)
Location: include/linux/page_ref.h:180
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_folio
```
```
In mm/gup.c (ffffffff8140d5bb)
Location: include/linux/page_ref.h:180
Inline: True
Inline callers:
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/page_alloc.c (ffffffff8144f25c)
Location: include/linux/page_ref.h:180
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
```
```
In mm/khugepaged.c (ffffffff814ae5db)
Location: include/linux/page_ref.h:180
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
</details>
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
In mm/page_alloc.c (ffff800010319060)
Location: include/linux/page_ref.h:119
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
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
In mm/page_alloc.c (c0533b54)
Location: include/linux/page_ref.h:119
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003ebac0)
Location: include/linux/page_ref.h:119
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
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
In mm/page_alloc.c (ffffffe00021ee14)
Location: include/linux/page_ref.h:119
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
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
In mm/page_alloc.c (ffffffff81279a14)
Location: include/linux/page_ref.h:119
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
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
In mm/page_alloc.c (ffffffff8126b904)
Location: include/linux/page_ref.h:119
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
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
In mm/page_alloc.c (ffffffff812777b4)
Location: include/linux/page_ref.h:119
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
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
In mm/page_alloc.c (ffffffff812873a4)
Location: include/linux/page_ref.h:119
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
</details>
</li>
</ul>

## Differences
