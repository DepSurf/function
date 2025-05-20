# Function: <code>init_sync_kiocb</code>

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
In mm/page_io.c (ffffffff811d22d1)
Location: include/linux/fs.h:338
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff8120be5d)
Location: include/linux/fs.h:338
Inline: True
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
In mm/page_io.c (ffffffff811efea5)
Location: include/linux/fs.h:339
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff81231949)
Location: include/linux/fs.h:339
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
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
In mm/page_io.c (ffffffff812007e1)
Location: include/linux/fs.h:289
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff81243ef9)
Location: include/linux/fs.h:289
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffffffff81279027)
Location: include/linux/fs.h:289
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
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
In mm/page_io.c (ffffffff8120b41b)
Location: include/linux/fs.h:1902
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff8124f891)
Location: include/linux/fs.h:1902
Inline: True
```
```
In fs/splice.c (ffffffff81286587)
Location: include/linux/fs.h:1902
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
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
In mm/page_io.c (ffffffff812248db)
Location: include/linux/fs.h:1932
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff812717d1)
Location: include/linux/fs.h:1932
Inline: True
```
```
In fs/splice.c (ffffffff812a9087)
Location: include/linux/fs.h:1932
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/fuse/file.c (0)
Location: include/linux/fs.h:1932
Inline: True
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
In mm/page_io.c (ffffffff81246f65)
Location: include/linux/fs.h:1961
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff81297634)
Location: include/linux/fs.h:1961
Inline: True
```
```
In fs/splice.c (ffffffff812cfbc0)
Location: include/linux/fs.h:1961
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/fuse/file.c (ffffffff813cae97)
Location: include/linux/fs.h:1961
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_readpage
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
In mm/page_io.c (ffffffff8125b39c)
Location: include/linux/fs.h:2043
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff812ac2e4)
Location: include/linux/fs.h:2043
Inline: True
```
```
In fs/splice.c (ffffffff812e4fad)
Location: include/linux/fs.h:2043
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/fuse/file.c (ffffffff813e291a)
Location: include/linux/fs.h:2043
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_readpage
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
In mm/page_io.c (ffffffff812764eb)
Location: include/linux/fs.h:2050
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff812c89e3)
Location: include/linux/fs.h:2050
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffffffff8130379d)
Location: include/linux/fs.h:2050
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/fuse/file.c (ffffffff8140e5e1)
Location: include/linux/fs.h:2050
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_readpage
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
In mm/page_io.c (ffffffff81285fdb)
Location: include/linux/fs.h:2085
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff812da3f3)
Location: include/linux/fs.h:2085
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffffffff8131681d)
Location: include/linux/fs.h:2085
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
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
In mm/page_io.c (ffffffff812b8305)
Location: include/linux/fs.h:2099
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff81310853)
Location: include/linux/fs.h:2099
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:new_sync_write
  - fs/read_write.c:new_sync_read
```
```
In fs/splice.c (ffffffff8135048b)
Location: include/linux/fs.h:2099
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
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
In mm/page_io.c (ffffffff812c39cf)
Location: include/linux/fs.h:2069
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff8131d263)
Location: include/linux/fs.h:2069
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:new_sync_write
  - fs/read_write.c:__kernel_read
  - fs/read_write.c:new_sync_read
```
```
In fs/seq_file.c (ffffffff8134df57)
Location: include/linux/fs.h:2069
Inline: True
Inline callers:
  - fs/seq_file.c:seq_read
```
```
In fs/splice.c (ffffffff8135d32b)
Location: include/linux/fs.h:2069
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
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
In mm/page_io.c (ffffffff812ca79a)
Location: include/linux/fs.h:2277
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff813233d3)
Location: include/linux/fs.h:2277
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:new_sync_write
  - fs/read_write.c:__kernel_read
  - fs/read_write.c:new_sync_read
```
```
In fs/seq_file.c (ffffffff81355287)
Location: include/linux/fs.h:2277
Inline: True
Inline callers:
  - fs/seq_file.c:seq_read
```
```
In fs/splice.c (ffffffff81363d8b)
Location: include/linux/fs.h:2277
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
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
In mm/page_io.c (ffffffff8130f797)
Location: include/linux/fs.h:2331
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff813708c3)
Location: include/linux/fs.h:2331
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:new_sync_write
  - fs/read_write.c:__kernel_read
  - fs/read_write.c:new_sync_read
```
```
In fs/seq_file.c (ffffffff813a3697)
Location: include/linux/fs.h:2331
Inline: True
Inline callers:
  - fs/seq_file.c:seq_read
```
```
In fs/splice.c (ffffffff813b25bb)
Location: include/linux/fs.h:2331
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
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
In mm/page_io.c (ffffffff8137a124)
Location: include/linux/fs.h:2204
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff813ef469)
Location: include/linux/fs.h:2204
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:new_sync_write
  - fs/read_write.c:__kernel_read
  - fs/read_write.c:new_sync_read
```
```
In fs/seq_file.c (ffffffff81427459)
Location: include/linux/fs.h:2204
Inline: True
Inline callers:
  - fs/seq_file.c:seq_read
```
```
In fs/splice.c (ffffffff814375f8)
Location: include/linux/fs.h:2204
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
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
In mm/page_io.c (ffffffff813f7c13)
Location: include/linux/fs.h:2336
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:swap_writepage_fs
```
```
In fs/read_write.c (ffffffff814775e8)
Location: include/linux/fs.h:2336
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:vfs_write
  - fs/read_write.c:__kernel_write_iter
  - fs/read_write.c:vfs_read
  - fs/read_write.c:__kernel_read
```
```
In fs/seq_file.c (ffffffff814b3f4e)
Location: include/linux/fs.h:2336
Inline: True
Inline callers:
  - fs/seq_file.c:seq_read
```
```
In fs/splice.c (ffffffff814c570f)
Location: include/linux/fs.h:2336
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
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
In mm/filemap.c (ffffffff8139250e)
Location: include/linux/fs.h:2025
Inline: True
Inline callers:
  - mm/filemap.c:filemap_splice_read
```
```
In mm/page_io.c (ffffffff8142add4)
Location: include/linux/fs.h:2025
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:swap_writepage_fs
```
```
In fs/read_write.c (ffffffff814abf68)
Location: include/linux/fs.h:2025
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:vfs_write
  - fs/read_write.c:__kernel_write_iter
  - fs/read_write.c:vfs_read
  - fs/read_write.c:__kernel_read
```
```
In fs/seq_file.c (ffffffff814e8fde)
Location: include/linux/fs.h:2025
Inline: True
Inline callers:
  - fs/seq_file.c:seq_read
```
```
In fs/splice.c (ffffffff814fa831)
Location: include/linux/fs.h:2025
Inline: True
Inline callers:
  - fs/splice.c:copy_splice_read
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
In mm/filemap.c (ffffffff813bc14e)
Location: include/linux/fs.h:2253
Inline: True
Inline callers:
  - mm/filemap.c:filemap_splice_read
```
```
In mm/page_io.c (ffffffff81464578)
Location: include/linux/fs.h:2253
Inline: True
Inline callers:
  - mm/page_io.c:swap_read_folio_fs
  - mm/page_io.c:swap_writepage_fs
```
```
In fs/read_write.c (ffffffff814dd30e)
Location: include/linux/fs.h:2253
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:vfs_write
  - fs/read_write.c:__kernel_write_iter
  - fs/read_write.c:vfs_read
  - fs/read_write.c:__kernel_read
```
```
In fs/seq_file.c (ffffffff8151ce65)
Location: include/linux/fs.h:2253
Inline: True
Inline callers:
  - fs/seq_file.c:seq_read
```
```
In fs/splice.c (ffffffff815307e9)
Location: include/linux/fs.h:2253
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:copy_splice_read
```
</details>
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
In mm/page_io.c (ffff800010320594)
Location: include/linux/fs.h:2085
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffff80001037f74c)
Location: include/linux/fs.h:2085
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffff8000103cd19c)
Location: include/linux/fs.h:2085
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
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
In mm/page_io.c (c0539024)
Location: include/linux/fs.h:2085
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (c0569da4)
Location: include/linux/fs.h:2085
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:new_sync_write
```
```
In fs/splice.c (c05a8d38)
Location: include/linux/fs.h:2085
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
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
In mm/page_io.c (c0000000003f5730)
Location: include/linux/fs.h:2085
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (c000000000475844)
Location: include/linux/fs.h:2085
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:new_sync_write
  - fs/read_write.c:new_sync_read
```
```
In fs/splice.c (c0000000004cef20)
Location: include/linux/fs.h:2085
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
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
In mm/page_io.c (ffffffe000221cb8)
Location: include/linux/fs.h:2085
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffe000255420)
Location: include/linux/fs.h:2085
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffffffe00028a5ac)
Location: include/linux/fs.h:2085
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
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
In mm/page_io.c (ffffffff8127e62b)
Location: include/linux/fs.h:2085
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff812d29d3)
Location: include/linux/fs.h:2085
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffffffff8130edfd)
Location: include/linux/fs.h:2085
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
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
In mm/page_io.c (ffffffff8127045b)
Location: include/linux/fs.h:2085
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff812c3653)
Location: include/linux/fs.h:2085
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffffffff812ffa0d)
Location: include/linux/fs.h:2085
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
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
In mm/page_io.c (ffffffff8127c3cb)
Location: include/linux/fs.h:2085
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff812d07e3)
Location: include/linux/fs.h:2085
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffffffff8130cbed)
Location: include/linux/fs.h:2085
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
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
In mm/page_io.c (ffffffff8128bf9b)
Location: include/linux/fs.h:2085
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In fs/read_write.c (ffffffff812e1613)
Location: include/linux/fs.h:2085
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffffffff8131e3fd)
Location: include/linux/fs.h:2085
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
</details>
</li>
</ul>

## Differences
