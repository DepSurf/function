# Function: <code>folio_ref_sub_and_test</code>

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
In mm/filemap.c (ffffffff812f2815)
Location: include/linux/page_ref.h:189
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:filemap_free_folio
```
```
In mm/gup.c (ffffffff8133706c)
Location: include/linux/page_ref.h:189
Inline: True
Inline callers:
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_get_folio
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
Location: include/linux/page_ref.h:189
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:filemap_free_folio
```
```
In mm/shmem.c (ffffffff8138ac63)
Location: include/linux/page_ref.h:189
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_folio
```
```
In mm/gup.c (ffffffff813ae52c)
Location: include/linux/page_ref.h:189
Inline: True
Inline callers:
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
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
Location: include/linux/page_ref.h:189
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:filemap_free_folio
```
```
In mm/shmem.c (ffffffff813bd189)
Location: include/linux/page_ref.h:189
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_folio
```
```
In mm/gup.c (ffffffff813e2d7e)
Location: include/linux/page_ref.h:189
Inline: True
Inline callers:
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/khugepaged.c (ffffffff814804cb)
Location: include/linux/page_ref.h:189
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
Location: include/linux/page_ref.h:189
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:filemap_free_folio
```
```
In mm/shmem.c (ffffffff813e7ff9)
Location: include/linux/page_ref.h:189
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_folio
```
```
In mm/gup.c (ffffffff8140d5bb)
Location: include/linux/page_ref.h:189
Inline: True
Inline callers:
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/khugepaged.c (ffffffff814ae5db)
Location: include/linux/page_ref.h:189
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
