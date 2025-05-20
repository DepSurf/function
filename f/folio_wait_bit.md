# Function: <code>folio_wait_bit</code>

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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void folio_wait_bit(struct folio *folio, int bit_nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812f4154)
Location: mm/filemap.c:1471
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:__folio_lock_or_retry
  - mm/filemap.c:folio_wait_private_2
Direct callers:
  - mm/page-writeback.c:folio_wait_writeback
  - mm/hugetlb.c:hugetlb_fault
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
```
**Symbols:**

```
ffffffff812f1a20-ffffffff812f1a48: folio_wait_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void folio_wait_bit(struct folio *folio, int bit_nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8135fcb3)
Location: mm/filemap.c:1439
Inline: True
Inline callers:
  - mm/filemap.c:__folio_lock_or_retry
  - mm/filemap.c:folio_wait_private_2
Direct callers:
  - mm/page-writeback.c:folio_wait_writeback
  - mm/hugetlb.c:hugetlb_fault
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
```
**Symbols:**

```
ffffffff8135c640-ffffffff8135c668: folio_wait_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void folio_wait_bit(struct folio *folio, int bit_nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81390c79)
Location: mm/filemap.c:1443
Inline: True
Inline callers:
  - mm/filemap.c:__folio_lock_or_retry
  - mm/filemap.c:folio_wait_private_2
Direct callers:
  - mm/page-writeback.c:folio_wait_writeback
  - mm/hugetlb.c:hugetlb_fault
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
```
**Symbols:**

```
ffffffff8138e670-ffffffff8138e698: folio_wait_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void folio_wait_bit(struct folio *folio, int bit_nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813ba93c)
Location: mm/filemap.c:1413
Inline: True
Inline callers:
  - mm/filemap.c:__folio_lock_or_retry
  - mm/filemap.c:folio_wait_private_2
Direct callers:
  - mm/page-writeback.c:folio_wait_writeback
  - mm/hugetlb.c:hugetlb_fault
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
```
**Symbols:**

```
ffffffff813b7d30-ffffffff813b7d58: folio_wait_bit (STB_GLOBAL)
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
<b>Regular</b>
<ul>
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
