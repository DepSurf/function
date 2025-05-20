# Function: <code>folio_clear_error</code>

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
In mm/filemap.c (ffffffff812f431d)
Location: include/linux/page-flags.h:494
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_folio
```
```
In fs/iomap/buffered-io.c (ffffffff8148af2c)
Location: include/linux/page-flags.h:494
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:__iomap_write_begin
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
In mm/filemap.c (ffffffff8135c7c3)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/filemap.c:filemap_read_folio
```
```
In fs/iomap/buffered-io.c (ffffffff8151ef17)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:__iomap_write_begin
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
In mm/filemap.c (ffffffff8138e7f3)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/filemap.c:filemap_read_folio
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In fs/iomap/buffered-io.c (ffffffff8155705f)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:__iomap_write_begin
```
```
In fs/ext4/page-io.c (ffffffff815da9ca)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
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
In mm/filemap.c (ffffffff813b7eb3)
Location: include/linux/page-flags.h:469
Inline: True
Inline callers:
  - mm/filemap.c:filemap_read_folio
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In fs/iomap/buffered-io.c (ffffffff8158d596)
Location: include/linux/page-flags.h:469
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:__iomap_write_begin
```
```
In fs/ext4/page-io.c (ffffffff81613187)
Location: include/linux/page-flags.h:469
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
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
