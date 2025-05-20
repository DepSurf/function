# Function: <code>folio_wait_locked</code>

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
In mm/filemap.c (ffffffff812f40d7)
Location: include/linux/pagemap.h:1025
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:__folio_lock_or_retry
  - mm/filemap.c:__folio_lock_or_retry
```
```
In mm/hugetlb.c (ffffffff81392cab)
Location: include/linux/pagemap.h:1025
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/zsmalloc.c (ffffffff813e28c9)
Location: include/linux/pagemap.h:1025
Inline: True
Inline callers:
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
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
In mm/filemap.c (ffffffff8135fcaf)
Location: include/linux/pagemap.h:1018
Inline: True
Inline callers:
  - mm/filemap.c:__folio_lock_or_retry
```
```
In mm/hugetlb.c (ffffffff814116f6)
Location: include/linux/pagemap.h:1018
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/zsmalloc.c (ffffffff81469e29)
Location: include/linux/pagemap.h:1018
Inline: True
Inline callers:
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
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
In mm/filemap.c (ffffffff81390c75)
Location: include/linux/pagemap.h:1029
Inline: True
Inline callers:
  - mm/filemap.c:__folio_lock_or_retry
```
```
In mm/hugetlb.c (ffffffff814449b2)
Location: include/linux/pagemap.h:1029
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/zsmalloc.c (ffffffff8149f029)
Location: include/linux/pagemap.h:1029
Inline: True
Inline callers:
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
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
In mm/filemap.c (ffffffff813ba934)
Location: include/linux/pagemap.h:1120
Inline: True
Inline callers:
  - mm/filemap.c:__folio_lock_or_retry
```
```
In mm/hugetlb.c (ffffffff8147ebcc)
Location: include/linux/pagemap.h:1120
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/zsmalloc.c (ffffffff814ce789)
Location: include/linux/pagemap.h:1120
Inline: True
Inline callers:
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
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
