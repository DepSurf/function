# Function: <code>folio_test_readahead</code>

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
In mm/filemap.c (ffffffff812f14f2)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_read_batch
```
```
In mm/migrate.c (ffffffff813b098d)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
```
```
In fs/verity/enable.c (ffffffff81472088)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - fs/verity/enable.c:read_file_data_page
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
In mm/filemap.c (ffffffff8135be92)
Location: include/linux/page-flags.h:525
Inline: True
Inline callers:
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_read_batch
```
```
In mm/migrate.c (ffffffff81431516)
Location: include/linux/page-flags.h:525
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
```
```
In fs/verity/enable.c (ffffffff815040ca)
Location: include/linux/page-flags.h:525
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
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
In mm/filemap.c (ffffffff8138e172)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_read_batch
```
```
In mm/migrate.c (ffffffff81466e96)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
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
In mm/filemap.c (ffffffff813b90c8)
Location: include/linux/page-flags.h:520
Inline: True
Inline callers:
  - mm/filemap.c:next_uptodate_folio
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_read_batch
```
```
In mm/migrate.c (ffffffff814960f0)
Location: include/linux/page-flags.h:520
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
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
