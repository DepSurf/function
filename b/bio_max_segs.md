# Function: <code>bio_max_segs</code>

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
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81374007)
Location: include/linux/bio.h:25
Inline: True
```
```
In fs/direct-io.c (ffffffff81375e90)
Location: include/linux/bio.h:25
Inline: True
```
```
In fs/mpage.c (ffffffff81378286)
Location: include/linux/bio.h:25
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff813c3f6a)
Location: include/linux/bio.h:25
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/readpage.c (ffffffff814334af)
Location: include/linux/bio.h:25
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/blk-map.c (ffffffff8156e55a)
Location: include/linux/bio.h:25
Inline: True
Inline callers:
  - block/blk-map.c:bio_copy_user_iov
```
```
In drivers/md/dm-io.c (ffffffff8196b8c1)
Location: include/linux/bio.h:25
Inline: True
Inline callers:
  - drivers/md/dm-io.c:do_region
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
In fs/direct-io.c (ffffffff813c227b)
Location: include/linux/bio.h:24
Inline: True
```
```
In fs/mpage.c (ffffffff813c4a3c)
Location: include/linux/bio.h:24
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff8141340d)
Location: include/linux/bio.h:24
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/ext4/readpage.c (ffffffff81486ce4)
Location: include/linux/bio.h:24
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/fops.c (ffffffff815c61f8)
Location: include/linux/bio.h:24
Inline: True
```
```
In block/blk-map.c (ffffffff815d2b6a)
Location: include/linux/bio.h:24
Inline: True
Inline callers:
  - block/blk-map.c:bio_copy_user_iov
```
```
In drivers/md/dm-io.c (ffffffff81a13d81)
Location: include/linux/bio.h:24
Inline: True
Inline callers:
  - drivers/md/dm-io.c:do_region
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
In fs/direct-io.c (ffffffff81449265)
Location: include/linux/bio.h:15
Inline: True
```
```
In fs/mpage.c (ffffffff8144b5e5)
Location: include/linux/bio.h:15
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff8148bff6)
Location: include/linux/bio.h:15
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/ext4/readpage.c (ffffffff8150a726)
Location: include/linux/bio.h:15
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/fops.c (0)
Location: include/linux/bio.h:15
Inline: True
```
```
In block/blk-map.c (ffffffff8167e7a8)
Location: include/linux/bio.h:15
Inline: True
Inline callers:
  - block/blk-map.c:bio_copy_user_iov
```
```
In drivers/md/dm-io.c (ffffffff81b7c671)
Location: include/linux/bio.h:15
Inline: True
Inline callers:
  - drivers/md/dm-io.c:do_region
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
In fs/direct-io.c (ffffffff814d793a)
Location: include/linux/bio.h:15
Inline: True
```
```
In fs/mpage.c (ffffffff814d9dfd)
Location: include/linux/bio.h:15
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff8151e7bf)
Location: include/linux/bio.h:15
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/ext4/readpage.c (ffffffff815a51dc)
Location: include/linux/bio.h:15
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/fops.c (0)
Location: include/linux/bio.h:15
Inline: True
```
```
In block/blk-map.c (ffffffff8173b541)
Location: include/linux/bio.h:15
Inline: True
Inline callers:
  - block/blk-map.c:bio_copy_user_iov
```
```
In drivers/md/dm-io.c (ffffffff81d1a4ca)
Location: include/linux/bio.h:15
Inline: True
Inline callers:
  - drivers/md/dm-io.c:do_region
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
In fs/mpage.c (ffffffff8150de10)
Location: include/linux/bio.h:17
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/direct-io.c (ffffffff815109fb)
Location: include/linux/bio.h:17
Inline: True
Inline callers:
  - fs/direct-io.c:dio_send_cur_page
  - fs/direct-io.c:dio_send_cur_page
```
```
In fs/iomap/buffered-io.c (ffffffff8155692f)
Location: include/linux/bio.h:17
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/ext4/readpage.c (ffffffff815dbb7f)
Location: include/linux/bio.h:17
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/fops.c (0)
Location: include/linux/bio.h:17
Inline: True
```
```
In block/blk-map.c (ffffffff81777c81)
Location: include/linux/bio.h:17
Inline: True
Inline callers:
  - block/blk-map.c:bio_copy_user_iov
```
```
In drivers/md/dm-io.c (ffffffff81d83627)
Location: include/linux/bio.h:17
Inline: True
Inline callers:
  - drivers/md/dm-io.c:do_region
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
In fs/mpage.c (ffffffff81542a31)
Location: include/linux/bio.h:17
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/direct-io.c (ffffffff81544e9b)
Location: include/linux/bio.h:17
Inline: True
Inline callers:
  - fs/direct-io.c:dio_send_cur_page
  - fs/direct-io.c:dio_send_cur_page
```
```
In fs/iomap/buffered-io.c (ffffffff8158cde2)
Location: include/linux/bio.h:17
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/ext4/readpage.c (ffffffff81614446)
Location: include/linux/bio.h:17
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In block/fops.c (0)
Location: include/linux/bio.h:17
Inline: True
```
```
In block/blk-map.c (ffffffff817b9fbe)
Location: include/linux/bio.h:17
Inline: True
Inline callers:
  - block/blk-map.c:bio_copy_user_iov
```
```
In drivers/md/dm-io.c (ffffffff81e3ad07)
Location: include/linux/bio.h:17
Inline: True
Inline callers:
  - drivers/md/dm-io.c:do_region
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
