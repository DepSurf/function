# Function: <code>folio_wait_stable</code>

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
void folio_wait_stable(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812fcbd0)
Location: mm/page-writeback.c:3053
Inline: False
Direct callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:__filemap_get_folio
  - mm/folio-compat.c:wait_for_stable_page
  - mm/folio-compat.c:wait_for_stable_page
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
**Symbols:**

```
ffffffff812fcbd0-ffffffff812fcc02: folio_wait_stable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void folio_wait_stable(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81366f50)
Location: mm/page-writeback.c:3191
Inline: False
Direct callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:__filemap_get_folio
  - mm/folio-compat.c:wait_for_stable_page
  - mm/folio-compat.c:wait_for_stable_page
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
**Symbols:**

```
ffffffff81366f50-ffffffff81366f82: folio_wait_stable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void folio_wait_stable(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff813995d0)
Location: mm/page-writeback.c:3132
Inline: False
Direct callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:__filemap_get_folio
  - mm/folio-compat.c:wait_for_stable_page
  - mm/folio-compat.c:wait_for_stable_page
  - mm/folio-compat.c:wait_for_stable_page
  - fs/buffer.c:block_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
ffffffff813995d0-ffffffff81399602: folio_wait_stable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void folio_wait_stable(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff813c33d0)
Location: mm/page-writeback.c:3104
Inline: False
Direct callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:__filemap_get_folio
  - mm/folio-compat.c:wait_for_stable_page
  - mm/folio-compat.c:wait_for_stable_page
  - mm/folio-compat.c:wait_for_stable_page
  - fs/buffer.c:block_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
ffffffff813c33d0-ffffffff813c340f: folio_wait_stable (STB_GLOBAL)
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
