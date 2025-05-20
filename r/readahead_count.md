# Function: <code>readahead_count</code>

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
In mm/readahead.c (ffffffff8125cb9e)
Location: include/linux/pagemap.h:820
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
```
```
In fs/mpage.c (ffffffff8136558d)
Location: include/linux/pagemap.h:820
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/pagemap.h:820
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff81418627)
Location: include/linux/pagemap.h:820
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/fuse/file.c (ffffffff81477e6b)
Location: include/linux/pagemap.h:820
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
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
In mm/readahead.c (ffffffff81266f1e)
Location: include/linux/pagemap.h:977
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
```
```
In fs/mpage.c (ffffffff8137245d)
Location: include/linux/pagemap.h:977
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/pagemap.h:977
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff8142c187)
Location: include/linux/pagemap.h:977
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/fuse/file.c (ffffffff81492b39)
Location: include/linux/pagemap.h:977
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
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
In mm/readahead.c (ffffffff8126bb69)
Location: include/linux/pagemap.h:1019
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
```
```
In fs/mpage.c (ffffffff8137853d)
Location: include/linux/pagemap.h:1019
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/pagemap.h:1019
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff81432e52)
Location: include/linux/pagemap.h:1019
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/fuse/file.c (ffffffff8149759c)
Location: include/linux/pagemap.h:1019
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
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
In mm/readahead.c (ffffffff812a883c)
Location: include/linux/pagemap.h:1022
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
```
```
In fs/mpage.c (ffffffff813c4e1d)
Location: include/linux/pagemap.h:1022
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/pagemap.h:1022
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff81486788)
Location: include/linux/pagemap.h:1022
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/fuse/file.c (ffffffff814eef26)
Location: include/linux/pagemap.h:1022
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
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
In mm/readahead.c (ffffffff81301493)
Location: include/linux/pagemap.h:1387
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
```
```
In fs/mpage.c (ffffffff8144bc6e)
Location: include/linux/pagemap.h:1387
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/pagemap.h:1387
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff8150a025)
Location: include/linux/pagemap.h:1387
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/fuse/file.c (ffffffff8157ec81)
Location: include/linux/pagemap.h:1387
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
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
In mm/readahead.c (ffffffff8136bb55)
Location: include/linux/pagemap.h:1363
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
```
```
In fs/mpage.c (ffffffff814da28c)
Location: include/linux/pagemap.h:1363
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/pagemap.h:1363
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff815a4bc5)
Location: include/linux/pagemap.h:1363
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/fuse/file.c (ffffffff81624941)
Location: include/linux/pagemap.h:1363
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
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
In mm/readahead.c (ffffffff8139dde2)
Location: include/linux/pagemap.h:1366
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
```
```
In fs/mpage.c (ffffffff8150e1cc)
Location: include/linux/pagemap.h:1366
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/pagemap.h:1366
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff815db595)
Location: include/linux/pagemap.h:1366
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/fuse/file.c (ffffffff8165cd18)
Location: include/linux/pagemap.h:1366
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
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
In mm/readahead.c (ffffffff813c7a92)
Location: include/linux/pagemap.h:1453
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
```
```
In fs/mpage.c (ffffffff81542ca9)
Location: include/linux/pagemap.h:1453
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/pagemap.h:1453
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff81613e65)
Location: include/linux/pagemap.h:1453
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/fuse/file.c (ffffffff81696a78)
Location: include/linux/pagemap.h:1453
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
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
