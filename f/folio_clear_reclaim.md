# Function: <code>folio_clear_reclaim</code>

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
In mm/filemap.c (ffffffff812f022c)
Location: include/linux/page-flags.h:544
Inline: True
Inline callers:
  - mm/filemap.c:folio_end_writeback
```
```
In mm/page-writeback.c (ffffffff812fc697)
Location: include/linux/page-flags.h:544
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_mark_dirty
```
```
In mm/vmscan.c (ffffffff8130dde8)
Location: include/linux/page-flags.h:544
Inline: True
Inline callers:
  - mm/vmscan.c:pageout
  - mm/vmscan.c:pageout
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
In mm/filemap.c (ffffffff8135b5cc)
Location: include/linux/page-flags.h:523
Inline: True
Inline callers:
  - mm/filemap.c:folio_end_writeback
```
```
In mm/page-writeback.c (ffffffff813669b7)
Location: include/linux/page-flags.h:523
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_mark_dirty
```
```
In mm/vmscan.c (ffffffff81379c37)
Location: include/linux/page-flags.h:523
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_folio
  - mm/vmscan.c:pageout
  - mm/vmscan.c:pageout
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
In mm/filemap.c (ffffffff8138d42c)
Location: include/linux/page-flags.h:516
Inline: True
Inline callers:
  - mm/filemap.c:folio_end_writeback
```
```
In mm/page-writeback.c (ffffffff81399024)
Location: include/linux/page-flags.h:516
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_mark_dirty
```
```
In mm/vmscan.c (ffffffff813ad6f9)
Location: include/linux/page-flags.h:516
Inline: True
Inline callers:
  - mm/vmscan.c:pageout
  - mm/vmscan.c:pageout
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
In mm/filemap.c (ffffffff813b6fa8)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/filemap.c:folio_end_writeback
```
```
In mm/page-writeback.c (ffffffff813c2e24)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_mark_dirty
```
```
In mm/vmscan.c (ffffffff813d6b06)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/vmscan.c:pageout
  - mm/vmscan.c:pageout
```
```
In mm/page_io.c (ffffffff814637b5)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/page_io.c:__end_swap_bio_write
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
