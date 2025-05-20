# Function: <code>folio_attach_private</code>

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
In mm/migrate.c (ffffffff813b2a8a)
Location: include/linux/pagemap.h:413
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_page
```
```
In fs/buffer.c (ffffffff81445456)
Location: include/linux/pagemap.h:413
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:grow_dev_page
```
```
In fs/iomap/buffered-io.c (ffffffff814883fe)
Location: include/linux/pagemap.h:413
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_migrate_page
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In drivers/md/md-bitmap.c (ffffffff81b68751)
Location: include/linux/pagemap.h:413
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
In mm/migrate.c (ffffffff814343a0)
Location: include/linux/pagemap.h:411
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_folio
```
```
In fs/buffer.c (ffffffff814d4cde)
Location: include/linux/pagemap.h:411
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:grow_dev_page
```
```
In fs/iomap/buffered-io.c (ffffffff8151cda5)
Location: include/linux/pagemap.h:411
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In drivers/md/md-bitmap.c (ffffffff81d041f1)
Location: include/linux/pagemap.h:411
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
In mm/migrate.c (ffffffff81469cf6)
Location: include/linux/pagemap.h:415
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_folio
```
```
In fs/buffer.c (ffffffff81509f47)
Location: include/linux/pagemap.h:415
Inline: True
Inline callers:
  - fs/buffer.c:folio_create_empty_buffers
  - fs/buffer.c:__getblk_slow
```
```
In fs/iomap/buffered-io.c (ffffffff81554f57)
Location: include/linux/pagemap.h:415
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In drivers/md/md-bitmap.c (ffffffff81d6cf81)
Location: include/linux/pagemap.h:415
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
In mm/migrate.c (ffffffff81498c86)
Location: include/linux/pagemap.h:473
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_folio
```
```
In fs/buffer.c (ffffffff8153ed76)
Location: include/linux/pagemap.h:473
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_slow
```
```
In fs/iomap/buffered-io.c (ffffffff8158b61e)
Location: include/linux/pagemap.h:473
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:ifs_alloc
```
```
In drivers/md/md-bitmap.c (ffffffff81e241a8)
Location: include/linux/pagemap.h:473
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
