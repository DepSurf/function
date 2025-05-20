# Function: <code>folio_detach_private</code>

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
In mm/migrate.c (ffffffff813b2a4f)
Location: include/linux/pagemap.h:448
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_page
```
```
In fs/buffer.c (ffffffff8144384b)
Location: include/linux/pagemap.h:448
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff814883d4)
Location: include/linux/pagemap.h:448
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_migrate_page
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In drivers/md/md-bitmap.c (ffffffff81b68ccd)
Location: include/linux/pagemap.h:448
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
In mm/migrate.c (ffffffff8143437a)
Location: include/linux/pagemap.h:446
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_folio
```
```
In fs/buffer.c (ffffffff814d209b)
Location: include/linux/pagemap.h:446
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff8151c9a5)
Location: include/linux/pagemap.h:446
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In drivers/md/md-bitmap.c (ffffffff81d047ed)
Location: include/linux/pagemap.h:446
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
In mm/migrate.c (ffffffff81469ccd)
Location: include/linux/pagemap.h:450
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_folio
```
```
In fs/buffer.c (ffffffff81509aab)
Location: include/linux/pagemap.h:450
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff81554b95)
Location: include/linux/pagemap.h:450
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In drivers/md/md-bitmap.c (ffffffff81d6d8ad)
Location: include/linux/pagemap.h:450
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
In mm/migrate.c (ffffffff81498c5d)
Location: include/linux/pagemap.h:508
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_folio
```
```
In fs/buffer.c (ffffffff8153e8db)
Location: include/linux/pagemap.h:508
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff8158af55)
Location: include/linux/pagemap.h:508
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:ifs_free
```
```
In drivers/md/md-bitmap.c (ffffffff81e24ced)
Location: include/linux/pagemap.h:508
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
