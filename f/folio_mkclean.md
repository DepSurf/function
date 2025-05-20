# Function: <code>folio_mkclean</code>

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
int folio_mkclean(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8135be50)
Location: mm/rmap.c:1035
Inline: False
Direct callers:
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/truncate.c:pagecache_isize_extended
  - mm/memory-failure.c:hwpoison_user_mappings
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
```
**Symbols:**

```
ffffffff8135be50-ffffffff8135bf28: folio_mkclean (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int folio_mkclean(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff813d6ad0)
Location: mm/rmap.c:1031
Inline: False
Direct callers:
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/truncate.c:pagecache_isize_extended
  - mm/memory-failure.c:hwpoison_user_mappings
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
```
**Symbols:**

```
ffffffff813d6ad0-ffffffff813d6bc0: folio_mkclean (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int folio_mkclean(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8140b8b0)
Location: mm/rmap.c:1028
Inline: False
Direct callers:
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/truncate.c:pagecache_isize_extended
  - mm/memory-failure.c:hwpoison_user_mappings
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
```
**Symbols:**

```
ffffffff8140b8b0-ffffffff8140b99f: folio_mkclean (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int folio_mkclean(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81438170)
Location: mm/rmap.c:1080
Inline: False
Direct callers:
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/truncate.c:pagecache_isize_extended
  - mm/memory-failure.c:hwpoison_user_mappings
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
```
**Symbols:**

```
ffffffff81438170-ffffffff8143825c: folio_mkclean (STB_GLOBAL)
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
