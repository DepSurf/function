# Function: <code>filemap_dirty_folio</code>

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
bool filemap_dirty_folio(struct address_space *mapping, struct folio *folio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff813004d0)
Location: mm/page-writeback.c:2616
Inline: True
Direct callers:
  - mm/page-writeback.c:folio_redirty_for_writepage
  - mm/folio-compat.c:__set_page_dirty_nobuffers
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/inode.c:ext4_journalled_dirty_folio
```
**Symbols:**

```
ffffffff813004d0-ffffffff81300555: filemap_dirty_folio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool filemap_dirty_folio(struct address_space *mapping, struct folio *folio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8136ae10)
Location: mm/page-writeback.c:2754
Inline: True
Direct callers:
  - mm/page-writeback.c:folio_redirty_for_writepage
  - mm/folio-compat.c:__set_page_dirty_nobuffers
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/inode.c:ext4_journalled_dirty_folio
```
**Symbols:**

```
ffffffff8136ae10-ffffffff8136ae95: filemap_dirty_folio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool filemap_dirty_folio(struct address_space *mapping, struct folio *folio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8139cfa0)
Location: mm/page-writeback.c:2695
Inline: True
Direct callers:
  - mm/page-writeback.c:folio_redirty_for_writepage
  - mm/folio-compat.c:__set_page_dirty_nobuffers
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/inode.c:ext4_journalled_dirty_folio
```
**Symbols:**

```
ffffffff8139cfa0-ffffffff8139d025: filemap_dirty_folio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool filemap_dirty_folio(struct address_space *mapping, struct folio *folio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff813c6c90)
Location: mm/page-writeback.c:2695
Inline: True
Direct callers:
  - mm/page-writeback.c:folio_redirty_for_writepage
  - mm/folio-compat.c:__set_page_dirty_nobuffers
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_dirty_folio
  - fs/ext4/inode.c:ext4_journalled_dirty_folio
```
**Symbols:**

```
ffffffff813c6c90-ffffffff813c6d15: filemap_dirty_folio (STB_GLOBAL)
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
