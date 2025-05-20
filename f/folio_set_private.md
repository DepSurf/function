# Function: <code>folio_set_private</code>

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
In mm/migrate.c (ffffffff813b2a92)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_page
```
```
In fs/buffer.c (ffffffff8144545e)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:grow_dev_page
```
```
In fs/iomap/buffered-io.c (ffffffff81488409)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_migrate_page
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In drivers/md/md-bitmap.c (ffffffff81b68759)
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
In mm/migrate.c (ffffffff814343ab)
Location: include/linux/page-flags.h:509
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_folio
```
```
In fs/buffer.c (ffffffff814d4ce6)
Location: include/linux/page-flags.h:509
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:grow_dev_page
```
```
In fs/iomap/buffered-io.c (ffffffff8151cdb0)
Location: include/linux/page-flags.h:509
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In drivers/md/md-bitmap.c (ffffffff81d041f9)
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
In mm/migrate.c (ffffffff81469cff)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_folio
```
```
In fs/buffer.c (ffffffff81509f4f)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - fs/buffer.c:folio_create_empty_buffers
  - fs/buffer.c:__getblk_slow
```
```
In fs/iomap/buffered-io.c (ffffffff81554f62)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In drivers/md/md-bitmap.c (ffffffff81d6cf89)
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
In mm/migrate.c (ffffffff81498c8f)
Location: include/linux/page-flags.h:504
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_folio
```
```
In fs/buffer.c (ffffffff8153ed7e)
Location: include/linux/page-flags.h:504
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_slow
```
```
In fs/iomap/buffered-io.c (ffffffff8158b626)
Location: include/linux/page-flags.h:504
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:ifs_alloc
```
```
In drivers/md/md-bitmap.c (ffffffff81e241b1)
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
