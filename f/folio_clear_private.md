# Function: <code>folio_clear_private</code>

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
In mm/migrate.c (ffffffff813b2a5e)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:folio_migrate_flags
```
```
In fs/buffer.c (ffffffff81443853)
Location: include/linux/page-flags.h:530
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff814883e3)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_migrate_page
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In drivers/md/md-bitmap.c (ffffffff81b68cd5)
Location: include/linux/page-flags.h:530
Inline: True
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
In mm/migrate.c (ffffffff81434389)
Location: include/linux/page-flags.h:509
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:folio_migrate_flags
```
```
In fs/buffer.c (ffffffff814d20a3)
Location: include/linux/page-flags.h:509
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff8151c9c4)
Location: include/linux/page-flags.h:509
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In drivers/md/md-bitmap.c (ffffffff81d047f5)
Location: include/linux/page-flags.h:509
Inline: True
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
In mm/migrate.c (ffffffff81469cdd)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:folio_migrate_flags
```
```
In fs/buffer.c (ffffffff81509ab3)
Location: include/linux/page-flags.h:502
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff81554bb2)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In drivers/md/md-bitmap.c (ffffffff81d6d8b5)
Location: include/linux/page-flags.h:502
Inline: True
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
In mm/migrate.c (ffffffff81498c6d)
Location: include/linux/page-flags.h:504
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:folio_migrate_flags
```
```
In fs/buffer.c (ffffffff8153e8e3)
Location: include/linux/page-flags.h:504
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff8158af73)
Location: include/linux/page-flags.h:504
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:ifs_free
```
```
In drivers/md/md-bitmap.c (ffffffff81e24cf5)
Location: include/linux/page-flags.h:504
Inline: True
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
