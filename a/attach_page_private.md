# Function: <code>attach_page_private</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812e4ef6)
Location: include/linux/pagemap.h:219
Inline: True
```
```
In fs/buffer.c (ffffffff8135ac2d)
Location: include/linux/pagemap.h:219
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:grow_dev_page
```
```
In fs/iomap/buffered-io.c (ffffffff813aa6da)
Location: include/linux/pagemap.h:219
Inline: True
```
```
In drivers/md/md-bitmap.c (ffffffff81972dc7)
Location: include/linux/pagemap.h:219
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812ef8d1)
Location: include/linux/pagemap.h:255
Inline: True
```
```
In fs/buffer.c (ffffffff81368a6d)
Location: include/linux/pagemap.h:255
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:grow_dev_page
```
```
In fs/iomap/buffered-io.c (ffffffff813bcc44)
Location: include/linux/pagemap.h:255
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In drivers/md/md-bitmap.c (ffffffff81977cef)
Location: include/linux/pagemap.h:255
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812f65ba)
Location: include/linux/pagemap.h:270
Inline: True
```
```
In fs/buffer.c (ffffffff8136ff2a)
Location: include/linux/pagemap.h:270
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:grow_dev_page
```
```
In fs/iomap/buffered-io.c (ffffffff813c3d59)
Location: include/linux/pagemap.h:270
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In drivers/md/md-bitmap.c (ffffffff8195b7fb)
Location: include/linux/pagemap.h:270
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81340bfb)
Location: include/linux/pagemap.h:270
Inline: True
```
```
In fs/buffer.c (ffffffff813bea8d)
Location: include/linux/pagemap.h:270
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:grow_dev_page
```
```
In fs/iomap/buffered-io.c (ffffffff81412ff9)
Location: include/linux/pagemap.h:270
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In drivers/md/md-bitmap.c (ffffffff81a00ff4)
Location: include/linux/pagemap.h:270
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff813b2a75)
Location: include/linux/pagemap.h:461
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_page
```
```
In fs/buffer.c (ffffffff81445442)
Location: include/linux/pagemap.h:461
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:grow_dev_page
```
```
In drivers/md/md-bitmap.c (ffffffff81b6873c)
Location: include/linux/pagemap.h:461
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
In fs/buffer.c (ffffffff814d4cca)
Location: include/linux/pagemap.h:459
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:grow_dev_page
```
```
In drivers/md/md-bitmap.c (ffffffff81d041dc)
Location: include/linux/pagemap.h:459
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81d6cf6c)
Location: include/linux/pagemap.h:463
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81e24197)
Location: include/linux/pagemap.h:521
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
