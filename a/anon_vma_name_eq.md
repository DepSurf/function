# Function: <code>anon_vma_name_eq</code>

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
In <code>5.8</code>: Absent ⚠️
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
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8134ee7e)
Location: include/linux/mm_inline.h:202
Inline: True
Inline callers:
  - mm/mmap.c:vma_merge
  - mm/mmap.c:can_vma_merge_before
```
```
In mm/madvise.c (ffffffff81377fc0)
Location: include/linux/mm_inline.h:202
Inline: True
Inline callers:
  - mm/madvise.c:madvise_update_vma
  - mm/madvise.c:madvise_update_vma
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
In mm/mmap.c (ffffffff813c67bf)
Location: include/linux/mm_inline.h:419
Inline: True
Inline callers:
  - mm/mmap.c:can_vma_merge_after
  - mm/mmap.c:can_vma_merge_before
```
```
In mm/madvise.c (ffffffff813f58c7)
Location: include/linux/mm_inline.h:419
Inline: True
Inline callers:
  - mm/madvise.c:madvise_update_vma
  - mm/madvise.c:madvise_update_vma
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
In mm/mmap.c (ffffffff813faa1f)
Location: include/linux/mm_inline.h:407
Inline: True
Inline callers:
  - mm/mmap.c:can_vma_merge_after
  - mm/mmap.c:can_vma_merge_before
```
```
In mm/madvise.c (ffffffff8142864a)
Location: include/linux/mm_inline.h:407
Inline: True
Inline callers:
  - mm/madvise.c:madvise_update_vma
  - mm/madvise.c:madvise_update_vma
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
In mm/mmap.c (ffffffff814267df)
Location: include/linux/mm_inline.h:404
Inline: True
Inline callers:
  - mm/mmap.c:can_vma_merge_after
  - mm/mmap.c:can_vma_merge_before
```
```
In mm/madvise.c (ffffffff81461ef7)
Location: include/linux/mm_inline.h:404
Inline: True
Inline callers:
  - mm/madvise.c:madvise_update_vma
  - mm/madvise.c:madvise_update_vma
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
