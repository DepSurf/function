# Function: <code>bio_next_segment</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff813175e5)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/mpage.c:mpage_end_io
```
```
In fs/crypto/bio.c (ffffffff813393de)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
```
```
In fs/iomap/buffered-io.c (ffffffff8134b5b2)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/page-io.c (ffffffff813b232c)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff813b3182)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/ext4/readpage.c:mpage_end_io
```
```
In block/bio.c (ffffffff814c7aa5)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
  - block/bio.c:bio_free_pages
```
```
In block/bounce.c (ffffffff814ec5f2)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - block/bounce.c:bounce_end_io
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
In fs/mpage.c (ffffffff8132a465)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/mpage.c:mpage_end_io
```
```
In fs/crypto/bio.c (ffffffff8134f24d)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (ffffffff813517a3)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff81363872)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/page-io.c (ffffffff813cb37c)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff813cc1d5)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In block/bio.c (ffffffff814e0ba5)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
  - block/bio.c:bio_free_pages
```
```
In block/bounce.c (ffffffff81505a42)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - block/bounce.c:bounce_end_io
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
In fs/mpage.c (ffffffff813641f5)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/mpage.c:mpage_end_io
```
```
In fs/crypto/bio.c (ffffffff813957b0)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (ffffffff81398247)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff813ab307)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/page-io.c (ffffffff814174e2)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff814182b5)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/squashfs/block.c (ffffffff81449879)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:copy_bio_to_actor
  - fs/squashfs/block.c:copy_bio_to_actor
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff8144ea44)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff8144edf4)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff8144f212)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff8144f55d)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff8144f83f)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In block/bio.c (ffffffff8153fa05)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:bio_free_pages
```
```
In block/blk-map.c (ffffffff81549a25)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - block/blk-map.c:bio_copy_kern_endio_read
  - block/blk-map.c:bio_copy_to_iter
  - block/blk-map.c:bio_copy_from_iter
```
```
In block/bounce.c (ffffffff81566142)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - block/bounce.c:bounce_end_io
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
In fs/mpage.c (ffffffff813710f5)
Location: include/linux/bio.h:122
Inline: True
Inline callers:
  - fs/mpage.c:mpage_end_io
```
```
In fs/crypto/bio.c (ffffffff813a6ad0)
Location: include/linux/bio.h:122
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (ffffffff813a9ac7)
Location: include/linux/bio.h:122
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff813bc837)
Location: include/linux/bio.h:122
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/page-io.c (ffffffff8142afe7)
Location: include/linux/bio.h:122
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff8142be15)
Location: include/linux/bio.h:122
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/squashfs/block.c (ffffffff81465fec)
Location: include/linux/bio.h:122
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:copy_bio_to_actor
  - fs/squashfs/block.c:copy_bio_to_actor
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff8146b038)
Location: include/linux/bio.h:122
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff8146b3b4)
Location: include/linux/bio.h:122
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff8146b7b2)
Location: include/linux/bio.h:122
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff8146badd)
Location: include/linux/bio.h:122
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff8146bd9f)
Location: include/linux/bio.h:122
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In block/bio.c (ffffffff8155c225)
Location: include/linux/bio.h:122
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:bio_free_pages
```
```
In block/blk-map.c (ffffffff815658f5)
Location: include/linux/bio.h:122
Inline: True
Inline callers:
  - block/blk-map.c:bio_copy_kern_endio_read
  - block/blk-map.c:bio_copy_to_iter
  - block/blk-map.c:bio_copy_from_iter
```
```
In block/bounce.c (ffffffff815810c2)
Location: include/linux/bio.h:122
Inline: True
Inline callers:
  - block/bounce.c:bounce_end_io
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
In fs/mpage.c (ffffffff81377aa5)
Location: include/linux/bio.h:125
Inline: True
Inline callers:
  - fs/mpage.c:mpage_end_io
```
```
In fs/crypto/bio.c (ffffffff813adb60)
Location: include/linux/bio.h:125
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (ffffffff813b1008)
Location: include/linux/bio.h:125
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff813c2df9)
Location: include/linux/bio.h:125
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/page-io.c (ffffffff81431b57)
Location: include/linux/bio.h:125
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff81432ad5)
Location: include/linux/bio.h:125
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/squashfs/block.c (ffffffff8146b78b)
Location: include/linux/bio.h:125
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:copy_bio_to_actor
  - fs/squashfs/block.c:copy_bio_to_actor
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff814706f8)
Location: include/linux/bio.h:125
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff81470a76)
Location: include/linux/bio.h:125
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff81470e62)
Location: include/linux/bio.h:125
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff8147116d)
Location: include/linux/bio.h:125
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff8147142f)
Location: include/linux/bio.h:125
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In block/bio.c (ffffffff81564ac5)
Location: include/linux/bio.h:125
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:bio_free_pages
```
```
In block/blk-map.c (ffffffff8156ea07)
Location: include/linux/bio.h:125
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:bio_copy_kern_endio_read
  - block/blk-map.c:bio_copy_user_iov
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
In fs/mpage.c (ffffffff813c4125)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/mpage.c:mpage_end_io
```
```
In fs/crypto/bio.c (ffffffff813fd4e0)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (ffffffff81400ce8)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff814124af)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/page-io.c (ffffffff814853a7)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff814862a5)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/squashfs/block.c (ffffffff814c1fdb)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:copy_bio_to_actor
  - fs/squashfs/block.c:copy_bio_to_actor
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff814c7168)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff814c74e6)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff814c78d2)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff814c7bfd)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff814c7ebf)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In block/bio.c (ffffffff815c8e45)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:bio_free_pages
```
```
In block/blk-map.c (ffffffff815d3037)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:bio_copy_kern_endio_read
  - block/blk-map.c:bio_copy_user_iov
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
In fs/mpage.c (ffffffff8144aebc)
Location: include/linux/bio.h:79
Inline: True
Inline callers:
  - fs/mpage.c:mpage_end_io
```
```
In fs/crypto/bio.c (ffffffff81470ce3)
Location: include/linux/bio.h:79
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (ffffffff81474d8a)
Location: include/linux/bio.h:79
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/ext4/page-io.c (ffffffff8150879f)
Location: include/linux/bio.h:79
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff81509b7c)
Location: include/linux/bio.h:79
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/squashfs/block.c (ffffffff8154ca2a)
Location: include/linux/bio.h:79
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:copy_bio_to_actor
  - fs/squashfs/block.c:copy_bio_to_actor
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff8155250a)
Location: include/linux/bio.h:79
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff815528c1)
Location: include/linux/bio.h:79
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff81552cde)
Location: include/linux/bio.h:79
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff8155305f)
Location: include/linux/bio.h:79
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff81553346)
Location: include/linux/bio.h:79
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In block/bio.c (ffffffff81673f03)
Location: include/linux/bio.h:79
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:bio_free_pages
  - block/bio.c:__bio_release_pages
```
```
In block/blk-map.c (ffffffff8167ecdc)
Location: include/linux/bio.h:79
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:bio_copy_kern_endio_read
  - block/blk-map.c:bio_copy_user_iov
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
In fs/mpage.c (ffffffff814d95ec)
Location: include/linux/bio.h:79
Inline: True
Inline callers:
  - fs/mpage.c:mpage_end_io
```
```
In fs/crypto/bio.c (ffffffff81502818)
Location: include/linux/bio.h:79
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (ffffffff8150716d)
Location: include/linux/bio.h:79
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/ext4/page-io.c (ffffffff815a329f)
Location: include/linux/bio.h:79
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff815a47fc)
Location: include/linux/bio.h:79
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/squashfs/block.c (ffffffff815ec8e6)
Location: include/linux/bio.h:79
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:copy_bio_to_actor
  - fs/squashfs/block.c:copy_bio_to_actor
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff815f3a6a)
Location: include/linux/bio.h:79
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff815f3eb1)
Location: include/linux/bio.h:79
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff815f42f6)
Location: include/linux/bio.h:79
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff815f4707)
Location: include/linux/bio.h:79
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff815f4a65)
Location: include/linux/bio.h:79
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In block/bio.c (ffffffff8172fb73)
Location: include/linux/bio.h:79
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:bio_free_pages
  - block/bio.c:__bio_release_pages
```
```
In block/blk-map.c (ffffffff8173bc90)
Location: include/linux/bio.h:79
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:bio_copy_kern_endio_read
  - block/blk-map.c:bio_copy_user_iov
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
In fs/squashfs/block.c (ffffffff81624846)
Location: include/linux/bio.h:81
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_bio_read_cached
  - fs/squashfs/block.c:copy_bio_to_actor
  - fs/squashfs/block.c:copy_bio_to_actor
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff8162bb5a)
Location: include/linux/bio.h:81
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff8162bfa1)
Location: include/linux/bio.h:81
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff8162c3e7)
Location: include/linux/bio.h:81
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff8162c7d7)
Location: include/linux/bio.h:81
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff8162cafd)
Location: include/linux/bio.h:81
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In block/bio.c (ffffffff8176bd95)
Location: include/linux/bio.h:81
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:bio_free_pages
  - block/bio.c:__bio_release_pages
```
```
In block/blk-map.c (ffffffff817783d0)
Location: include/linux/bio.h:81
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:bio_copy_kern_endio_read
  - block/blk-map.c:bio_copy_user_iov
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
In fs/squashfs/block.c (ffffffff8165d8d6)
Location: include/linux/bio.h:81
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_bio_read_cached
  - fs/squashfs/block.c:copy_bio_to_actor
  - fs/squashfs/block.c:copy_bio_to_actor
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff81664f2a)
Location: include/linux/bio.h:81
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff816653a1)
Location: include/linux/bio.h:81
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff81665817)
Location: include/linux/bio.h:81
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff81665c67)
Location: include/linux/bio.h:81
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff81665fbd)
Location: include/linux/bio.h:81
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In block/bio.c (ffffffff817ab125)
Location: include/linux/bio.h:81
Inline: True
Inline callers:
  - block/bio.c:bio_free_pages
```
```
In block/blk-map.c (ffffffff817ba7b0)
Location: include/linux/bio.h:81
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:bio_copy_kern_endio_read
  - block/blk-map.c:bio_copy_from_iter
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
In fs/mpage.c (ffff8000103e5bd0)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/mpage.c:mpage_end_io
```
```
In fs/crypto/bio.c (ffff800010410de8)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (ffff8000104138f0)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffff80001042afc0)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/page-io.c (ffff8000104a31f0)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffff8000104a4608)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In block/bio.c (ffff8000105dd6d0)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
  - block/bio.c:bio_free_pages
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
In fs/mpage.c (c05bd7f4)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/mpage.c:mpage_end_io
```
```
In fs/crypto/bio.c (c05dd1f4)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (c05dfb94)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (c05f2d6c)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/page-io.c (c0665228)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (c06661e4)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In block/bio.c (c078ab08)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
  - block/bio.c:bio_free_pages
```
```
In block/bounce.c (c07b2db8)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - block/bounce.c:bounce_end_io
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
In fs/mpage.c (c0000000004ebd80)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/mpage.c:mpage_end_io
```
```
In fs/crypto/bio.c (c00000000051e554)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (c0000000005218ac)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (c00000000053a94c)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/page-io.c (c0000000005d0128)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (c0000000005d1570)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In block/bio.c (c00000000076ef88)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
  - block/bio.c:bio_free_pages
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
In fs/mpage.c (ffffffe00029b16a)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/mpage.c:mpage_end_io
```
```
In fs/crypto/bio.c (ffffffe0002b905c)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (ffffffe0002bb2d2)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffe0002c7dcc)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/page-io.c (ffffffe000324aee)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffe0003257fa)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In block/bio.c (ffffffe0004207a8)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
  - block/bio.c:bio_free_pages
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
In fs/mpage.c (ffffffff81322a45)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/mpage.c:mpage_end_io
```
```
In fs/crypto/bio.c (ffffffff8134782d)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (ffffffff81349d83)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff8135be52)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/page-io.c (ffffffff813c395c)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff813c47b5)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In block/bio.c (ffffffff814d9185)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
  - block/bio.c:bio_free_pages
```
```
In block/bounce.c (ffffffff814fe022)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - block/bounce.c:bounce_end_io
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
In fs/mpage.c (ffffffff813135e5)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/mpage.c:mpage_end_io
```
```
In fs/crypto/bio.c (ffffffff8133850d)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (ffffffff8133aa63)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff8134caf2)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/page-io.c (ffffffff813b43ec)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff813b5235)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In block/bio.c (ffffffff814c9b35)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
  - block/bio.c:bio_free_pages
```
```
In block/bounce.c (ffffffff814ee532)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - block/bounce.c:bounce_end_io
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
In fs/mpage.c (ffffffff81320515)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/mpage.c:mpage_end_io
```
```
In fs/crypto/bio.c (ffffffff813452fd)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (ffffffff81347853)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff81359922)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/page-io.c (ffffffff813c0dec)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff813c1c45)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In block/bio.c (ffffffff814d5215)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
  - block/bio.c:bio_free_pages
```
```
In block/bounce.c (ffffffff814fa0b2)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - block/bounce.c:bounce_end_io
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
In fs/mpage.c (ffffffff81332235)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/mpage.c:mpage_end_io
```
```
In fs/crypto/bio.c (ffffffff813585dd)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (ffffffff8135ab53)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff8136d012)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/page-io.c (ffffffff813d5f1c)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff813d6dc5)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In block/bio.c (ffffffff814eddc5)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:bio_copy_kern_endio_read
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_uncopy_user
  - block/bio.c:bio_free_pages
```
```
In block/bounce.c (ffffffff81513112)
Location: include/linux/bio.h:124
Inline: True
Inline callers:
  - block/bounce.c:bounce_end_io
```
</details>
</li>
</ul>

## Differences
