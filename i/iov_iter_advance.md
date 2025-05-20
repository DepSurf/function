# Function: <code>iov_iter_advance</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void iov_iter_advance(struct iov_iter *i, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff813fb290)
Location: lib/iov_iter.c:509
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_direct_write
  - fs/read_write.c:do_loop_readv_writev
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/blk-map.c:blk_rq_map_user_iov
  - drivers/char/mem.c:write_iter_null
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:zerocopy_sg_from_iter
```
**Symbols:**

```
ffffffff813fb290-ffffffff813fb3f6: iov_iter_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void iov_iter_advance(struct iov_iter *i, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814432d0)
Location: lib/iov_iter.c:458
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - fs/read_write.c:do_loop_readv_writev
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap.c:iomap_write_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-map.c:blk_rq_map_user_iov
  - drivers/char/mem.c:write_iter_null
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:zerocopy_sg_from_iter
```
**Symbols:**

```
ffffffff814432d0-ffffffff81443532: iov_iter_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void iov_iter_advance(struct iov_iter *i, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81460ad0)
Location: lib/iov_iter.c:779
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - fs/read_write.c:do_loop_readv_writev
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:generic_file_splice_read
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap.c:iomap_dio_actor
  - fs/iomap.c:iomap_write_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_iov_iter_get_pages
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-map.c:blk_rq_map_user_iov
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:copy_from_iter_full_nocache
  - lib/iov_iter.c:copy_from_iter_full
  - drivers/char/mem.c:write_iter_null
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:zerocopy_sg_from_iter
```
**Symbols:**

```
ffffffff81460ad0-ffffffff81460e63: iov_iter_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void iov_iter_advance(struct iov_iter *i, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81465ec0)
Location: lib/iov_iter.c:841
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/read_write.c:do_iter_read
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:generic_file_splice_read
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap.c:iomap_dio_actor
  - fs/iomap.c:iomap_write_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_iov_iter_get_pages
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-map.c:blk_rq_map_user_iov
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - drivers/char/mem.c:write_iter_null
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff81465ec0-ffffffff814661dd: iov_iter_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void iov_iter_advance(struct iov_iter *i, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81491fc0)
Location: lib/iov_iter.c:843
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/read_write.c:do_iter_read
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:generic_file_splice_read
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap.c:iomap_dio_actor
  - fs/iomap.c:iomap_write_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_iov_iter_get_pages
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - drivers/char/mem.c:write_iter_null
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
**Symbols:**

```
ffffffff81491fc0-ffffffff814922e3: iov_iter_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void iov_iter_advance(struct iov_iter *i, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814c6c50)
Location: lib/iov_iter.c:973
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/read_write.c:do_iter_read
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:generic_file_splice_read
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap.c:iomap_dio_actor
  - fs/iomap.c:iomap_write_actor
  - fs/fuse/dev.c:fuse_copy_fill
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_iov_iter_get_pages
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - drivers/char/mem.c:write_iter_null
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
**Symbols:**

```
ffffffff814c6c50-ffffffff814c6f74: iov_iter_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void iov_iter_advance(struct iov_iter *i, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814db7a0)
Location: lib/iov_iter.c:1019
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/read_write.c:do_iter_read
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:generic_file_splice_read
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap.c:iomap_dio_bio_actor
  - fs/iomap.c:iomap_write_actor
  - fs/fuse/dev.c:fuse_copy_fill
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_iov_iter_get_pages
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - drivers/char/mem.c:write_iter_null
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
```
**Symbols:**

```
ffffffff814db7a0-ffffffff814dbb20: iov_iter_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void iov_iter_advance(struct iov_iter *i, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815070d0)
Location: lib/iov_iter.c:1033
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/read_write.c:do_iter_read
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:generic_file_splice_read
  - fs/direct-io.c:do_direct_IO
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/fuse/dev.c:fuse_copy_fill
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_iov_iter_get_pages
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - drivers/char/mem.c:write_iter_null
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
```
**Symbols:**

```
ffffffff815070d0-ffffffff81507488: iov_iter_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void iov_iter_advance(struct iov_iter *i, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815251e0)
Location: lib/iov_iter.c:1033
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/read_write.c:do_iter_read
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:generic_file_splice_read
  - fs/direct-io.c:do_direct_IO
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/fuse/dev.c:fuse_copy_fill
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_iov_iter_get_pages
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - drivers/char/mem.c:write_iter_null
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
```
**Symbols:**

```
ffffffff815251e0-ffffffff81525598: iov_iter_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void iov_iter_advance(struct iov_iter *i, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8158a840)
Location: lib/iov_iter.c:1065
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:generic_file_splice_read
  - fs/direct-io.c:do_direct_IO
  - fs/io_uring.c:io_import_fixed
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/fuse/dev.c:fuse_copy_fill
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fill_write_pages
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:__bio_iov_append_get_pages
  - block/bio.c:__bio_iov_iter_get_pages
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_copy_user_iov
  - block/blk-map.c:bio_copy_user_iov
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - drivers/char/mem.c:write_iter_null
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
```
**Symbols:**

```
ffffffff8158a840-ffffffff8158abc1: iov_iter_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void iov_iter_advance(struct iov_iter *i, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815a5cf0)
Location: lib/iov_iter.c:1072
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - mm/madvise.c:__do_sys_process_madvise
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:generic_file_splice_read
  - fs/direct-io.c:do_direct_IO
  - fs/io_uring.c:loop_rw_iter
  - fs/io_uring.c:io_import_fixed
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/fuse/dev.c:fuse_copy_fill
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fill_write_pages
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:__bio_iov_append_get_pages
  - block/bio.c:__bio_iov_iter_get_pages
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_copy_user_iov
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - drivers/char/mem.c:write_iter_null
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
```
**Symbols:**

```
ffffffff815a5cf0-ffffffff815a5fec: iov_iter_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void iov_iter_advance(struct iov_iter *i, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815b18d0)
Location: lib/iov_iter.c:1158
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - mm/madvise.c:__do_sys_process_madvise
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:generic_file_splice_read
  - fs/direct-io.c:do_direct_IO
  - fs/io_uring.c:loop_rw_iter
  - fs/io_uring.c:io_import_iovec
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/fuse/dev.c:fuse_copy_fill
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fill_write_pages
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_copy_user_iov
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - drivers/char/mem.c:write_iter_null
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
```
**Symbols:**

```
ffffffff815b18d0-ffffffff815b1ed1: iov_iter_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void iov_iter_advance(struct iov_iter *i, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:1019
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_process_madvise
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:generic_file_splice_read
  - fs/direct-io.c:do_direct_IO
  - fs/io_uring.c:io_read
  - fs/io_uring.c:loop_rw_iter
  - fs/io_uring.c:io_import_iovec
  - fs/fuse/dev.c:fuse_copy_fill
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - block/bio.c:__bio_iov_append_get_pages
  - block/bio.c:__bio_iov_iter_get_pages
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_copy_user_iov
  - drivers/char/mem.c:write_iter_null
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
```
**Symbols:**

```
ffffffff81cda8d4-ffffffff81cda8e9: iov_iter_advance.cold (STB_LOCAL)
ffffffff816157d0-ffffffff81615a2b: iov_iter_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void iov_iter_advance(struct iov_iter *i, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:1071
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_process_madvise
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:generic_file_splice_read
  - fs/direct-io.c:do_direct_IO
  - fs/fuse/dev.c:fuse_copy_fill
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_iov_iter_get_pages
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_copy_user_iov
  - io_uring/io_uring.c:io_read
  - io_uring/io_uring.c:loop_rw_iter
  - io_uring/io_uring.c:__io_import_iovec
  - drivers/char/mem.c:write_iter_null
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
```
**Symbols:**

```
ffffffff81e92f06-ffffffff81e92f1b: iov_iter_advance.cold (STB_LOCAL)
ffffffff816e2380-ffffffff816e2619: iov_iter_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void iov_iter_advance(struct iov_iter *i, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff817d21c0)
Location: lib/iov_iter.c:895
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_process_madvise
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - block/bio.c:bio_iov_iter_get_pages
  - block/blk-map.c:bio_copy_user_iov
  - io_uring/rsrc.c:io_import_fixed
  - io_uring/rw.c:io_read
  - io_uring/rw.c:loop_rw_iter
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - drivers/char/mem.c:write_iter_null
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff817d21c0-ffffffff817d244e: iov_iter_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void iov_iter_advance(struct iov_iter *i, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8180fa10)
Location: lib/iov_iter.c:629
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_process_madvise
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - block/bio.c:bio_iov_iter_get_pages
  - block/blk-map.c:bio_copy_user_iov
  - io_uring/rw.c:io_read
  - io_uring/rw.c:loop_rw_iter
  - lib/iov_iter.c:iov_iter_extract_pages
  - lib/iov_iter.c:iov_iter_extract_pages
  - lib/iov_iter.c:iov_iter_extract_pages
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - drivers/char/mem.c:write_iter_null
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/packet/af_packet.c:packet_snd
```
**Symbols:**

```
ffffffff8180fa10-ffffffff8180fb53: iov_iter_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void iov_iter_advance(struct iov_iter *i, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81855680)
Location: lib/iov_iter.c:530
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_process_madvise
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - block/bio.c:bio_iov_iter_get_pages
  - block/blk-map.c:bio_copy_user_iov
  - io_uring/rw.c:__io_read
  - io_uring/rw.c:loop_rw_iter
  - lib/iov_iter.c:iov_iter_extract_pages
  - lib/iov_iter.c:iov_iter_extract_pages
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - drivers/char/mem.c:write_iter_null
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/packet/af_packet.c:packet_snd
```
**Symbols:**

```
ffffffff81855680-ffffffff818557c3: iov_iter_advance (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void iov_iter_advance(struct iov_iter *i, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffff80001062f608)
Location: lib/iov_iter.c:1033
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/read_write.c:do_iter_read
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:generic_file_splice_read
  - fs/direct-io.c:do_direct_IO
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/fuse/dev.c:fuse_copy_fill
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_iov_iter_get_pages
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - drivers/char/mem.c:write_iter_null
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
```
**Symbols:**

```
ffff80001062f608-ffff80001062f978: iov_iter_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void iov_iter_advance(struct iov_iter *i, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c07d5fc0)
Location: lib/iov_iter.c:1033
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/read_write.c:do_iter_read
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:generic_file_splice_read
  - fs/direct-io.c:do_direct_IO
  - fs/io_uring.c:io_import_iovec
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/fuse/dev.c:fuse_copy_fill
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_iov_iter_get_pages
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - drivers/char/mem.c:write_iter_null
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
```
**Symbols:**

```
c07d5fc0-c07d638c: iov_iter_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void iov_iter_advance(struct iov_iter *i, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c0000000007d3430)
Location: lib/iov_iter.c:1033
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/read_write.c:do_iter_read
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:generic_file_splice_read
  - fs/direct-io.c:do_direct_IO
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/fuse/dev.c:fuse_copy_fill
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_iov_iter_get_pages
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - drivers/char/mem.c:write_iter_null
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
```
**Symbols:**

```
c0000000007d3430-c0000000007d3948: iov_iter_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void iov_iter_advance(struct iov_iter *i, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffe00045ea76)
Location: lib/iov_iter.c:1033
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/read_write.c:do_iter_read
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:generic_file_splice_read
  - fs/direct-io.c:do_direct_IO
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/fuse/dev.c:fuse_copy_fill
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_iov_iter_get_pages
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - drivers/char/mem.c:write_iter_null
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
```
**Symbols:**

```
ffffffe00045ea76-ffffffe00045ed6e: iov_iter_advance (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void iov_iter_advance(struct iov_iter *i, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8151d7c0)
Location: lib/iov_iter.c:1033
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/read_write.c:do_iter_read
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:generic_file_splice_read
  - fs/direct-io.c:do_direct_IO
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/fuse/dev.c:fuse_copy_fill
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_iov_iter_get_pages
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - drivers/char/mem.c:write_iter_null
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
```
**Symbols:**

```
ffffffff8151d7c0-ffffffff8151db78: iov_iter_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void iov_iter_advance(struct iov_iter *i, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8150dab0)
Location: lib/iov_iter.c:1033
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/read_write.c:do_iter_read
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:generic_file_splice_read
  - fs/direct-io.c:do_direct_IO
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/fuse/dev.c:fuse_copy_fill
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_iov_iter_get_pages
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - drivers/char/mem.c:write_iter_null
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
```
**Symbols:**

```
ffffffff8150dab0-ffffffff8150de68: iov_iter_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void iov_iter_advance(struct iov_iter *i, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81519850)
Location: lib/iov_iter.c:1033
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/read_write.c:do_iter_read
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:generic_file_splice_read
  - fs/direct-io.c:do_direct_IO
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/fuse/dev.c:fuse_copy_fill
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_iov_iter_get_pages
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - drivers/char/mem.c:write_iter_null
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
```
**Symbols:**

```
ffffffff81519850-ffffffff81519c08: iov_iter_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void iov_iter_advance(struct iov_iter *i, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81533060)
Location: lib/iov_iter.c:1033
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/read_write.c:do_iter_read
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:generic_file_splice_read
  - fs/direct-io.c:do_direct_IO
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/fuse/dev.c:fuse_copy_fill
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_iov_iter_get_pages
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - drivers/char/mem.c:write_iter_null
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
```
**Symbols:**

```
ffffffff81533060-ffffffff81533418: iov_iter_advance (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
