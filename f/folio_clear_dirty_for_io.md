# Function: <code>folio_clear_dirty_for_io</code>

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
bool folio_clear_dirty_for_io(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812fd900)
Location: mm/page-writeback.c:2801
Inline: False
Direct callers:
  - mm/page-writeback.c:folio_write_one
  - mm/folio-compat.c:clear_page_dirty_for_io
  - mm/folio-compat.c:clear_page_dirty_for_io
  - mm/vmscan.c:pageout
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/fuse/file.c:fuse_launder_folio
```
**Symbols:**

```
ffffffff812fd900-ffffffff812fdb27: folio_clear_dirty_for_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool folio_clear_dirty_for_io(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81368120)
Location: mm/page-writeback.c:2939
Inline: False
Direct callers:
  - mm/page-writeback.c:folio_write_one
  - mm/folio-compat.c:clear_page_dirty_for_io
  - mm/folio-compat.c:clear_page_dirty_for_io
  - mm/vmscan.c:pageout
  - mm/migrate.c:writeout
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/fuse/file.c:fuse_launder_folio
```
**Symbols:**

```
ffffffff81368120-ffffffff813682f3: folio_clear_dirty_for_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool folio_clear_dirty_for_io(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81399fa0)
Location: mm/page-writeback.c:2880
Inline: False
Direct callers:
  - mm/page-writeback.c:write_cache_pages
  - mm/folio-compat.c:clear_page_dirty_for_io
  - mm/folio-compat.c:clear_page_dirty_for_io
  - mm/folio-compat.c:clear_page_dirty_for_io
  - mm/vmscan.c:pageout
  - mm/migrate.c:writeout
  - fs/ext4/inode.c:mpage_submit_folio
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/fuse/file.c:fuse_launder_folio
```
**Symbols:**

```
ffffffff81399fa0-ffffffff8139a173: folio_clear_dirty_for_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool folio_clear_dirty_for_io(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff813c3c60)
Location: mm/page-writeback.c:2859
Inline: False
Direct callers:
  - mm/page-writeback.c:write_cache_pages
  - mm/folio-compat.c:clear_page_dirty_for_io
  - mm/folio-compat.c:clear_page_dirty_for_io
  - mm/folio-compat.c:clear_page_dirty_for_io
  - mm/vmscan.c:pageout
  - mm/migrate.c:writeout
  - fs/ext4/inode.c:mpage_submit_folio
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/fuse/file.c:fuse_launder_folio
```
**Symbols:**

```
ffffffff813c3c60-ffffffff813c3e30: folio_clear_dirty_for_io (STB_GLOBAL)
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
