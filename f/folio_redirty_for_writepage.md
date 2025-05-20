# Function: <code>folio_redirty_for_writepage</code>

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
bool folio_redirty_for_writepage(struct writeback_control *wbc, struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81300560)
Location: mm/page-writeback.c:2678
Inline: False
Direct callers:
  - mm/folio-compat.c:redirty_page_for_writepage
  - mm/folio-compat.c:redirty_page_for_writepage
  - fs/iomap/buffered-io.c:iomap_do_writepage
```
**Symbols:**

```
ffffffff81300560-ffffffff813005dc: folio_redirty_for_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool folio_redirty_for_writepage(struct writeback_control *wbc, struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8136aeb0)
Location: mm/page-writeback.c:2816
Inline: False
Direct callers:
  - mm/folio-compat.c:redirty_page_for_writepage
  - mm/folio-compat.c:redirty_page_for_writepage
  - fs/iomap/buffered-io.c:iomap_do_writepage
```
**Symbols:**

```
ffffffff8136aeb0-ffffffff8136aeff: folio_redirty_for_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool folio_redirty_for_writepage(struct writeback_control *wbc, struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8139d040)
Location: mm/page-writeback.c:2757
Inline: False
Direct callers:
  - mm/folio-compat.c:redirty_page_for_writepage
  - mm/folio-compat.c:redirty_page_for_writepage
  - mm/folio-compat.c:redirty_page_for_writepage
  - fs/buffer.c:__block_write_full_folio
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/ext4/super.c:ext4_journalled_writepage_callback
```
**Symbols:**

```
ffffffff8139d040-ffffffff8139d08f: folio_redirty_for_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool folio_redirty_for_writepage(struct writeback_control *wbc, struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff813c6d30)
Location: mm/page-writeback.c:2726
Inline: False
Direct callers:
  - mm/folio-compat.c:redirty_page_for_writepage
  - mm/folio-compat.c:redirty_page_for_writepage
  - mm/folio-compat.c:redirty_page_for_writepage
  - fs/buffer.c:__block_write_full_folio
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/ext4/super.c:ext4_journalled_writepage_callback
```
**Symbols:**

```
ffffffff813c6d30-ffffffff813c6e58: folio_redirty_for_writepage (STB_GLOBAL)
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
