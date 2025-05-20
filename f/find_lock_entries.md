# Function: <code>find_lock_entries</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int find_lock_entries(struct address_space *mapping, long unsigned int start, long unsigned int end, struct pagevec *pvec, long unsigned int *indices);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81262c90)
Location: mm/filemap.c:2030
Inline: False
Direct callers:
  - mm/truncate.c:__invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff81262c90-ffffffff81262f92: find_lock_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
unsigned int find_lock_entries(struct address_space *mapping, long unsigned int start, long unsigned int end, struct pagevec *pvec, long unsigned int *indices);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:2085
Inline: False
Direct callers:
  - mm/truncate.c:__invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff81cb9fb5-ffffffff81cb9fe3: find_lock_entries.cold (STB_LOCAL)
ffffffff8129f340-ffffffff8129f686: find_lock_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
unsigned int find_lock_entries(struct address_space *mapping, long unsigned int start, long unsigned int end, struct folio_batch *fbatch, long unsigned int *indices);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:2115
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_mapping_pagevec
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff81e6b628-ffffffff81e6b664: find_lock_entries.cold (STB_LOCAL)
ffffffff812f62e0-ffffffff812f6594: find_lock_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
unsigned int find_lock_entries(struct address_space *mapping, long unsigned int *start, long unsigned int end, struct folio_batch *fbatch, long unsigned int *indices);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:2098
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_mapping_pagevec
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff8206229d-ffffffff820622d9: find_lock_entries.cold (STB_LOCAL)
ffffffff8135ff50-ffffffff8136021a: find_lock_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
unsigned int find_lock_entries(struct address_space *mapping, long unsigned int *start, long unsigned int end, struct folio_batch *fbatch, long unsigned int *indices);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:2069
Inline: False
Direct callers:
  - mm/truncate.c:mapping_try_invalidate
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff820e1a3c-ffffffff820e1a78: find_lock_entries.cold (STB_LOCAL)
ffffffff81391dd0-ffffffff813920e3: find_lock_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
unsigned int find_lock_entries(struct address_space *mapping, long unsigned int *start, long unsigned int end, struct folio_batch *fbatch, long unsigned int *indices);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:2055
Inline: False
Direct callers:
  - mm/truncate.c:mapping_try_invalidate
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff821be474-ffffffff821be4b0: find_lock_entries.cold (STB_LOCAL)
ffffffff813bbc70-ffffffff813bbf61: find_lock_entries (STB_GLOBAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio_batch *fbatch</code>
</li>
<li>
<b>Param removed. </b>
<code>struct pagevec *pvec</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long unsigned int start</code> ➡️ <code>long unsigned int *start</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
