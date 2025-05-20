# Function: <code>bio_add_folio_nofail</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bio_add_folio_nofail(struct bio *bio, struct folio *folio, size_t len, size_t off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8176bac0)
Location: block/bio.c:1117
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_read_folio_sync
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
**Symbols:**

```
ffffffff8176bac0-ffffffff8176bb44: bio_add_folio_nofail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bio_add_folio_nofail(struct bio *bio, struct folio *folio, size_t len, size_t off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff817adf60)
Location: block/bio.c:1118
Inline: False
Direct callers:
  - mm/page_io.c:swap_read_folio
  - mm/page_io.c:swap_read_folio_bdev_sync
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage_bdev_sync
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_read_folio_sync
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
**Symbols:**

```
ffffffff817adf60-ffffffff817adfe4: bio_add_folio_nofail (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
