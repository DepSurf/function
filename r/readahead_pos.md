# Function: <code>readahead_pos</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813ac867)
Location: include/linux/pagemap.h:793
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readahead
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813be053)
Location: include/linux/pagemap.h:950
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readahead
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
In mm/readahead.c (ffffffff8126b9de)
Location: include/linux/pagemap.h:992
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
```
```
In fs/iomap/buffered-io.c (ffffffff813c479d)
Location: include/linux/pagemap.h:992
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readahead
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
In mm/readahead.c (ffffffff812a86ae)
Location: include/linux/pagemap.h:995
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
```
```
In fs/iomap/buffered-io.c (ffffffff81414c70)
Location: include/linux/pagemap.h:995
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readahead
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
In mm/readahead.c (ffffffff813019ba)
Location: include/linux/pagemap.h:1360
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
```
```
In fs/iomap/buffered-io.c (ffffffff8148c380)
Location: include/linux/pagemap.h:1360
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readahead
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
In mm/readahead.c (ffffffff8136c067)
Location: include/linux/pagemap.h:1336
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
```
```
In fs/iomap/buffered-io.c (ffffffff8151eb10)
Location: include/linux/pagemap.h:1336
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readahead
```
```
In fs/squashfs/file.c (ffffffff815eece5)
Location: include/linux/pagemap.h:1336
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_readahead
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
In mm/readahead.c (ffffffff8139e322)
Location: include/linux/pagemap.h:1339
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
```
```
In fs/iomap/buffered-io.c (ffffffff81556c70)
Location: include/linux/pagemap.h:1339
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readahead
```
```
In fs/squashfs/file.c (ffffffff81626cd7)
Location: include/linux/pagemap.h:1339
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_readahead
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
In mm/readahead.c (ffffffff813c7fc3)
Location: include/linux/pagemap.h:1426
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
```
```
In fs/iomap/buffered-io.c (ffffffff8158d130)
Location: include/linux/pagemap.h:1426
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readahead
```
```
In fs/squashfs/file.c (ffffffff8165fe3b)
Location: include/linux/pagemap.h:1426
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_readahead
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
