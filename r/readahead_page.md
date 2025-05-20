# Function: <code>readahead_page</code>

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
In mm/readahead.c (ffffffff8125cbf9)
Location: include/linux/pagemap.h:718
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
```
```
In fs/mpage.c (ffffffff8136552a)
Location: include/linux/pagemap.h:718
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/iomap/buffered-io.c (ffffffff813ab525)
Location: include/linux/pagemap.h:718
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readahead_actor
```
```
In fs/ext4/readpage.c (ffffffff81418711)
Location: include/linux/pagemap.h:718
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In mm/readahead.c (ffffffff81266f79)
Location: include/linux/pagemap.h:873
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
```
```
In fs/mpage.c (ffffffff813723fa)
Location: include/linux/pagemap.h:873
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/iomap/buffered-io.c (ffffffff813bd655)
Location: include/linux/pagemap.h:873
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readahead_actor
```
```
In fs/ext4/readpage.c (ffffffff8142c265)
Location: include/linux/pagemap.h:873
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In mm/readahead.c (ffffffff8126bbbc)
Location: include/linux/pagemap.h:915
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
```
```
In fs/mpage.c (ffffffff813784da)
Location: include/linux/pagemap.h:915
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/iomap/buffered-io.c (ffffffff813c4645)
Location: include/linux/pagemap.h:915
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readahead_actor
```
```
In fs/ext4/readpage.c (ffffffff81432f4c)
Location: include/linux/pagemap.h:915
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In mm/readahead.c (ffffffff812a888f)
Location: include/linux/pagemap.h:918
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
```
```
In fs/mpage.c (ffffffff813c4dba)
Location: include/linux/pagemap.h:918
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/iomap/buffered-io.c (ffffffff81414d36)
Location: include/linux/pagemap.h:918
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readahead
```
```
In fs/ext4/readpage.c (ffffffff814868a1)
Location: include/linux/pagemap.h:918
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In fs/mpage.c (ffffffff8144bc06)
Location: include/linux/pagemap.h:1289
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/ext4/readpage.c (ffffffff8150a09f)
Location: include/linux/pagemap.h:1289
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In fs/ext4/readpage.c (ffffffff815a4ccc)
Location: include/linux/pagemap.h:1265
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
