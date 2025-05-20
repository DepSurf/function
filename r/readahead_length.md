# Function: <code>readahead_length</code>

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
Location: include/linux/pagemap.h:802
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
Location: include/linux/pagemap.h:959
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readahead
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813c479d)
Location: include/linux/pagemap.h:1001
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readahead
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81414c95)
Location: include/linux/pagemap.h:1004
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readahead
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8148c3a5)
Location: include/linux/pagemap.h:1369
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
In fs/iomap/buffered-io.c (ffffffff8151eb35)
Location: include/linux/pagemap.h:1345
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readahead
```
```
In fs/squashfs/file.c (ffffffff815eebf6)
Location: include/linux/pagemap.h:1345
Inline: True
Inline callers:
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
In fs/iomap/buffered-io.c (ffffffff81556c95)
Location: include/linux/pagemap.h:1348
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readahead
```
```
In fs/squashfs/file.c (ffffffff81626be7)
Location: include/linux/pagemap.h:1348
Inline: True
Inline callers:
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
In fs/iomap/buffered-io.c (ffffffff8158d155)
Location: include/linux/pagemap.h:1435
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readahead
```
```
In fs/squashfs/file.c (ffffffff8165fd57)
Location: include/linux/pagemap.h:1435
Inline: True
Inline callers:
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
