# Function: <code>detach_page_private</code>

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
In mm/migrate.c (ffffffff812e4eb6)
Location: include/linux/pagemap.h:235
Inline: True
```
```
In fs/buffer.c (ffffffff8135bab8)
Location: include/linux/pagemap.h:235
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
```
```
In fs/iomap/buffered-io.c (ffffffff813abf45)
Location: include/linux/pagemap.h:235
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In drivers/md/md-bitmap.c (ffffffff819723d1)
Location: include/linux/pagemap.h:235
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
In mm/migrate.c (ffffffff812ef891)
Location: include/linux/pagemap.h:271
Inline: True
```
```
In fs/buffer.c (ffffffff8136a068)
Location: include/linux/pagemap.h:271
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
```
```
In fs/iomap/buffered-io.c (ffffffff813bdd95)
Location: include/linux/pagemap.h:271
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In drivers/md/md-bitmap.c (ffffffff819772e1)
Location: include/linux/pagemap.h:271
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
In mm/migrate.c (ffffffff812f657a)
Location: include/linux/pagemap.h:286
Inline: True
```
```
In fs/buffer.c (ffffffff81370c78)
Location: include/linux/pagemap.h:286
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff813c4f55)
Location: include/linux/pagemap.h:286
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In drivers/md/md-bitmap.c (ffffffff8195b9f1)
Location: include/linux/pagemap.h:286
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
In mm/migrate.c (ffffffff81340bbe)
Location: include/linux/pagemap.h:286
Inline: True
```
```
In fs/buffer.c (ffffffff813bf8c8)
Location: include/linux/pagemap.h:286
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff81414985)
Location: include/linux/pagemap.h:286
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In drivers/md/md-bitmap.c (ffffffff81a011f1)
Location: include/linux/pagemap.h:286
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
In mm/migrate.c (ffffffff813b2a39)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_page
```
```
In drivers/md/md-bitmap.c (ffffffff81b68cb9)
Location: include/linux/pagemap.h:466
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81d047d9)
Location: include/linux/pagemap.h:464
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
In drivers/md/md-bitmap.c (ffffffff81d6d899)
Location: include/linux/pagemap.h:468
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
In drivers/md/md-bitmap.c (ffffffff81e24cd9)
Location: include/linux/pagemap.h:526
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
