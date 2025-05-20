# Function: <code>truncate_inode_folio</code>

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
int truncate_inode_folio(struct address_space *mapping, struct folio *folio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81308833)
Location: mm/truncate.c:190
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:generic_error_remove_page
  - mm/truncate.c:truncate_inode_partial_folio
Direct callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff81308120-ffffffff81308161: truncate_inode_folio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int truncate_inode_folio(struct address_space *mapping, struct folio *folio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81372715)
Location: mm/truncate.c:190
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:generic_error_remove_page
  - mm/truncate.c:truncate_inode_partial_folio
Direct callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff813720e0-ffffffff81372121: truncate_inode_folio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int truncate_inode_folio(struct address_space *mapping, struct folio *folio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff813a4846)
Location: mm/truncate.c:190
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:generic_error_remove_page
  - mm/truncate.c:truncate_inode_partial_folio
Direct callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff813a4290-ffffffff813a42d1: truncate_inode_folio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int truncate_inode_folio(struct address_space *mapping, struct folio *folio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff813ce3a1)
Location: mm/truncate.c:189
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:generic_error_remove_folio
  - mm/truncate.c:truncate_inode_partial_folio
Direct callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff813cddd0-ffffffff813cde11: truncate_inode_folio (STB_GLOBAL)
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
