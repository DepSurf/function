# Function: <code>read_cache_folio</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
struct folio *read_cache_folio(struct address_space *mapping, long unsigned int index, filler_t *filler, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812f43b0)
Location: mm/filemap.c:3589
Inline: False
Direct callers:
  - fs/verity/enable.c:read_file_data_page
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
**Symbols:**

```
ffffffff812f43b0-ffffffff812f43d3: read_cache_folio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct folio *read_cache_folio(struct address_space *mapping, long unsigned int index, filler_t *filler, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8135e4c0)
Location: mm/filemap.c:3583
Inline: False
Direct callers:
  - fs/verity/enable.c:build_merkle_tree_level
  - block/partitions/core.c:read_part_sector
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
**Symbols:**

```
ffffffff8135e4c0-ffffffff8135e4e3: read_cache_folio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct folio *read_cache_folio(struct address_space *mapping, long unsigned int index, filler_t *filler, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81391220)
Location: mm/filemap.c:3727
Inline: False
Direct callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
  - block/partitions/core.c:read_part_sector
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
**Symbols:**

```
ffffffff81391220-ffffffff81391243: read_cache_folio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct folio *read_cache_folio(struct address_space *mapping, long unsigned int index, filler_t *filler, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813bafc0)
Location: mm/filemap.c:3734
Inline: False
Direct callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
  - block/partitions/core.c:read_part_sector
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
**Symbols:**

```
ffffffff813bafc0-ffffffff813bafe3: read_cache_folio (STB_GLOBAL)
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
