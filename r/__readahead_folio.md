# Function: <code>__readahead_folio</code>

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
In mm/readahead.c (ffffffff813014e3)
Location: include/linux/pagemap.h:1260
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
```
```
In fs/mpage.c (ffffffff8144bc06)
Location: include/linux/pagemap.h:1260
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/iomap/buffered-io.c (ffffffff8148c48e)
Location: include/linux/pagemap.h:1260
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readahead
```
```
In fs/ext4/readpage.c (ffffffff8150a09f)
Location: include/linux/pagemap.h:1260
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In mm/readahead.c (ffffffff8136bb98)
Location: include/linux/pagemap.h:1236
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
```
```
In fs/mpage.c (ffffffff814da22a)
Location: include/linux/pagemap.h:1236
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/iomap/buffered-io.c (ffffffff8151ebfc)
Location: include/linux/pagemap.h:1236
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readahead
```
```
In fs/ext4/readpage.c (ffffffff815a4ccc)
Location: include/linux/pagemap.h:1236
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In mm/readahead.c (ffffffff8139de25)
Location: include/linux/pagemap.h:1239
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
```
```
In fs/mpage.c (ffffffff8150e16a)
Location: include/linux/pagemap.h:1239
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/iomap/buffered-io.c (ffffffff81556d5b)
Location: include/linux/pagemap.h:1239
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readahead
```
```
In fs/ext4/readpage.c (ffffffff815db638)
Location: include/linux/pagemap.h:1239
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In mm/readahead.c (ffffffff813c7ad5)
Location: include/linux/pagemap.h:1326
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
```
```
In fs/mpage.c (ffffffff81542c4a)
Location: include/linux/pagemap.h:1326
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/iomap/buffered-io.c (ffffffff8158d222)
Location: include/linux/pagemap.h:1326
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readahead
```
```
In fs/ext4/readpage.c (ffffffff81613f08)
Location: include/linux/pagemap.h:1326
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
