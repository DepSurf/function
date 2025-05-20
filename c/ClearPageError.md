# Function: <code>ClearPageError</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118eda0)
Location: include/linux/page-flags.h:210
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:filemap_fault
```
```
In fs/ext4/page-io.c (ffffffff8129fe68)
Location: include/linux/page-flags.h:210
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811a364d)
Location: include/linux/page-flags.h:256
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
```
```
In fs/ext4/page-io.c (ffffffff812ce768)
Location: include/linux/page-flags.h:256
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b3871)
Location: include/linux/page-flags.h:266
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
```
```
In fs/ext4/page-io.c (ffffffff812e4548)
Location: include/linux/page-flags.h:266
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ba6a1)
Location: include/linux/page-flags.h:266
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In fs/ext4/page-io.c (ffffffff8131e228)
Location: include/linux/page-flags.h:266
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811cdf0d)
Location: include/linux/page-flags.h:267
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In fs/ext4/page-io.c (ffffffff81342848)
Location: include/linux/page-flags.h:267
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811efad9)
Location: include/linux/page-flags.h:274
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In fs/ext4/page-io.c (ffffffff813706c8)
Location: include/linux/page-flags.h:274
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81201d32)
Location: include/linux/page-flags.h:283
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In fs/ext4/page-io.c (ffffffff81388b58)
Location: include/linux/page-flags.h:283
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812177d2)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In fs/ext4/page-io.c (ffffffff813b2c46)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8122510d)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In fs/ext4/page-io.c (ffffffff813cbca6)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813cc2aa)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81252fa5)
Location: include/linux/page-flags.h:322
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In fs/ext4/page-io.c (ffffffff81417e06)
Location: include/linux/page-flags.h:322
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff8141835b)
Location: include/linux/page-flags.h:322
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
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
In mm/filemap.c (ffffffff8125db69)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read_readpage
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In fs/iomap/buffered-io.c (ffffffff813bd02d)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:__iomap_write_begin
```
```
In fs/ext4/page-io.c (ffffffff8142b90b)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff8142bebb)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
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
In mm/filemap.c (ffffffff81260910)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In fs/iomap/buffered-io.c (ffffffff813c4162)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:__iomap_write_begin
```
```
In fs/ext4/page-io.c (ffffffff8143252b)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff81432b7b)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
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
In mm/filemap.c (ffffffff8129d2fc)
Location: include/linux/page-flags.h:344
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In fs/iomap/buffered-io.c (ffffffff8141377e)
Location: include/linux/page-flags.h:344
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:__iomap_write_begin
```
```
In fs/ext4/page-io.c (ffffffff81485deb)
Location: include/linux/page-flags.h:344
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff8148634b)
Location: include/linux/page-flags.h:344
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
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
In mm/filemap.c (ffffffff812efced)
Location: include/linux/page-flags.h:494
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In fs/ext4/page-io.c (ffffffff815093b7)
Location: include/linux/page-flags.h:494
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff81509c4f)
Location: include/linux/page-flags.h:494
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
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
In mm/filemap.c (ffffffff8135ae88)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In fs/ext4/page-io.c (ffffffff815a3f5f)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102b24cc)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In fs/ext4/page-io.c (ffff8000104a3e30)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffff8000104a46d4)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04df3c0)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In fs/ext4/page-io.c (c0665cdc)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (c06662bc)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c00000000036899c)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In fs/ext4/page-io.c (c0000000005d0f20)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (c0000000005d16d0)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d7d28)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In fs/ext4/page-io.c (ffffffe000325388)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffe00032584a)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121d75d)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In fs/ext4/page-io.c (ffffffff813c4286)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813c488a)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121092d)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In fs/ext4/page-io.c (ffffffff813b4d06)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813b530a)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121b4fd)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In fs/ext4/page-io.c (ffffffff813c1716)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813c1d1a)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8122a55a)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In fs/ext4/page-io.c (ffffffff813d6876)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813d6e9a)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
</details>
</li>
</ul>

## Differences
