# Function: <code>bvec_advance</code>

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
In fs/mpage.c (ffffffff81317627)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/mpage.c:mpage_end_io
```
```
In fs/crypto/bio.c (ffffffff813393f3)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
```
```
In fs/iomap/buffered-io.c (ffffffff8134b5e7)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/page-io.c (ffffffff813b2340)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff813b31b6)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/ext4/readpage.c:mpage_end_io
```
```
In block/bio.c (ffffffff814c7aed)
Location: include/linux/bvec.h:136
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
In block/bounce.c (ffffffff814ec648)
Location: include/linux/bvec.h:136
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
In fs/mpage.c (ffffffff8132a4a7)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/mpage.c:mpage_end_io
```
```
In fs/crypto/bio.c (ffffffff8134f262)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (ffffffff813517b7)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff813638a7)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/page-io.c (ffffffff813cb390)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff813cc22d)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In block/bio.c (ffffffff814e0bed)
Location: include/linux/bvec.h:136
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
In block/bounce.c (ffffffff81505a98)
Location: include/linux/bvec.h:136
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
In fs/mpage.c (ffffffff8136428a)
Location: include/linux/bvec.h:150
Inline: True
Inline callers:
  - fs/mpage.c:mpage_end_io
```
```
In fs/crypto/bio.c (ffffffff813957d1)
Location: include/linux/bvec.h:150
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (ffffffff81398367)
Location: include/linux/bvec.h:150
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff813ab364)
Location: include/linux/bvec.h:150
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/page-io.c (ffffffff81417500)
Location: include/linux/bvec.h:150
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff81418390)
Location: include/linux/bvec.h:150
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/squashfs/block.c (ffffffff814498a2)
Location: include/linux/bvec.h:150
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:copy_bio_to_actor
  - fs/squashfs/block.c:copy_bio_to_actor
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff8144eb3c)
Location: include/linux/bvec.h:150
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff8144ef03)
Location: include/linux/bvec.h:150
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff8144f230)
Location: include/linux/bvec.h:150
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff8144f57f)
Location: include/linux/bvec.h:150
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff8144f860)
Location: include/linux/bvec.h:150
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In block/bio.c (ffffffff8153faa9)
Location: include/linux/bvec.h:150
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:bio_free_pages
```
```
In block/blk-map.c (ffffffff81549a92)
Location: include/linux/bvec.h:150
Inline: True
Inline callers:
  - block/blk-map.c:bio_copy_kern_endio_read
  - block/blk-map.c:bio_copy_to_iter
  - block/blk-map.c:bio_copy_from_iter
```
```
In block/bounce.c (ffffffff8156626b)
Location: include/linux/bvec.h:150
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
In fs/mpage.c (ffffffff8137118a)
Location: include/linux/bvec.h:164
Inline: True
Inline callers:
  - fs/mpage.c:mpage_end_io
```
```
In fs/crypto/bio.c (ffffffff813a6af1)
Location: include/linux/bvec.h:164
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (ffffffff813a9be7)
Location: include/linux/bvec.h:164
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff813bc894)
Location: include/linux/bvec.h:164
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/page-io.c (ffffffff8142b010)
Location: include/linux/bvec.h:164
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff8142bef0)
Location: include/linux/bvec.h:164
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/squashfs/block.c (ffffffff81466013)
Location: include/linux/bvec.h:164
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:copy_bio_to_actor
  - fs/squashfs/block.c:copy_bio_to_actor
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff8146b12c)
Location: include/linux/bvec.h:164
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff8146b4c3)
Location: include/linux/bvec.h:164
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff8146b7d0)
Location: include/linux/bvec.h:164
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff8146baff)
Location: include/linux/bvec.h:164
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff8146bdc0)
Location: include/linux/bvec.h:164
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In block/bio.c (ffffffff8155c2c9)
Location: include/linux/bvec.h:164
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:bio_free_pages
```
```
In block/blk-map.c (ffffffff81565962)
Location: include/linux/bvec.h:164
Inline: True
Inline callers:
  - block/blk-map.c:bio_copy_kern_endio_read
  - block/blk-map.c:bio_copy_to_iter
  - block/blk-map.c:bio_copy_from_iter
```
```
In block/bounce.c (ffffffff815811eb)
Location: include/linux/bvec.h:164
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
In fs/mpage.c (ffffffff81377b3a)
Location: include/linux/bvec.h:164
Inline: True
Inline callers:
  - fs/mpage.c:mpage_end_io
```
```
In fs/crypto/bio.c (ffffffff813adb81)
Location: include/linux/bvec.h:164
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (ffffffff813b1126)
Location: include/linux/bvec.h:164
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff813c2e45)
Location: include/linux/bvec.h:164
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/page-io.c (ffffffff81431b80)
Location: include/linux/bvec.h:164
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff81432bb0)
Location: include/linux/bvec.h:164
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/squashfs/block.c (ffffffff8146b7b2)
Location: include/linux/bvec.h:164
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:copy_bio_to_actor
  - fs/squashfs/block.c:copy_bio_to_actor
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff814707ec)
Location: include/linux/bvec.h:164
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff81470b85)
Location: include/linux/bvec.h:164
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff81470e80)
Location: include/linux/bvec.h:164
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff8147118b)
Location: include/linux/bvec.h:164
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff81471450)
Location: include/linux/bvec.h:164
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In block/bio.c (ffffffff81564b10)
Location: include/linux/bvec.h:164
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:bio_free_pages
```
```
In block/blk-map.c (ffffffff8156e9bd)
Location: include/linux/bvec.h:164
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
In fs/mpage.c (ffffffff813c41ba)
Location: include/linux/bvec.h:165
Inline: True
Inline callers:
  - fs/mpage.c:mpage_end_io
```
```
In fs/crypto/bio.c (ffffffff813fd501)
Location: include/linux/bvec.h:165
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (ffffffff81400e25)
Location: include/linux/bvec.h:165
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff81412509)
Location: include/linux/bvec.h:165
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/page-io.c (ffffffff814853d0)
Location: include/linux/bvec.h:165
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff81486380)
Location: include/linux/bvec.h:165
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/squashfs/block.c (ffffffff814c2002)
Location: include/linux/bvec.h:165
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:copy_bio_to_actor
  - fs/squashfs/block.c:copy_bio_to_actor
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff814c725c)
Location: include/linux/bvec.h:165
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff814c75f5)
Location: include/linux/bvec.h:165
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff814c78f0)
Location: include/linux/bvec.h:165
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff814c7c1b)
Location: include/linux/bvec.h:165
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff814c7ee0)
Location: include/linux/bvec.h:165
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In block/bio.c (ffffffff815c8e90)
Location: include/linux/bvec.h:165
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:bio_free_pages
```
```
In block/blk-map.c (ffffffff815d2fed)
Location: include/linux/bvec.h:165
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
In fs/mpage.c (ffffffff8144af4e)
Location: include/linux/bvec.h:165
Inline: True
Inline callers:
  - fs/mpage.c:mpage_end_io
```
```
In fs/crypto/bio.c (ffffffff81470d11)
Location: include/linux/bvec.h:165
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (ffffffff81474f2b)
Location: include/linux/bvec.h:165
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/ext4/page-io.c (ffffffff815087d9)
Location: include/linux/bvec.h:165
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff81509c05)
Location: include/linux/bvec.h:165
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/squashfs/block.c (ffffffff8154ca5c)
Location: include/linux/bvec.h:165
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:copy_bio_to_actor
  - fs/squashfs/block.c:copy_bio_to_actor
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff81552628)
Location: include/linux/bvec.h:165
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff815529ef)
Location: include/linux/bvec.h:165
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff81552d2b)
Location: include/linux/bvec.h:165
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff8155307c)
Location: include/linux/bvec.h:165
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff815533a8)
Location: include/linux/bvec.h:165
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In block/bio.c (ffffffff81673f53)
Location: include/linux/bvec.h:165
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:bio_free_pages
  - block/bio.c:__bio_release_pages
```
```
In block/blk-map.c (ffffffff8167ec91)
Location: include/linux/bvec.h:165
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
In fs/mpage.c (ffffffff814d967e)
Location: include/linux/bvec.h:165
Inline: True
Inline callers:
  - fs/mpage.c:mpage_end_io
```
```
In fs/crypto/bio.c (ffffffff815027e0)
Location: include/linux/bvec.h:165
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (ffffffff81507290)
Location: include/linux/bvec.h:165
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/ext4/page-io.c (ffffffff815a32d9)
Location: include/linux/bvec.h:165
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff815a4869)
Location: include/linux/bvec.h:165
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/squashfs/block.c (ffffffff815ec8f7)
Location: include/linux/bvec.h:165
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:copy_bio_to_actor
  - fs/squashfs/block.c:copy_bio_to_actor
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff815f3b93)
Location: include/linux/bvec.h:165
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff815f3fec)
Location: include/linux/bvec.h:165
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff815f4343)
Location: include/linux/bvec.h:165
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff815f4724)
Location: include/linux/bvec.h:165
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff815f4acc)
Location: include/linux/bvec.h:165
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In block/bio.c (ffffffff8172fbc3)
Location: include/linux/bvec.h:165
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:bio_free_pages
  - block/bio.c:__bio_release_pages
```
```
In block/blk-map.c (ffffffff8173bc45)
Location: include/linux/bvec.h:165
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
In fs/squashfs/block.c (ffffffff81624876)
Location: include/linux/bvec.h:204
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_bio_read_cached
  - fs/squashfs/block.c:copy_bio_to_actor
  - fs/squashfs/block.c:copy_bio_to_actor
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff8162bc83)
Location: include/linux/bvec.h:204
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff8162c0dc)
Location: include/linux/bvec.h:204
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff8162c438)
Location: include/linux/bvec.h:204
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff8162c7f4)
Location: include/linux/bvec.h:204
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff8162cb62)
Location: include/linux/bvec.h:204
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In block/bio.c (ffffffff8176bdf1)
Location: include/linux/bvec.h:204
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:bio_free_pages
  - block/bio.c:__bio_release_pages
```
```
In block/blk-map.c (ffffffff81778385)
Location: include/linux/bvec.h:204
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
In fs/squashfs/block.c (ffffffff8165d906)
Location: include/linux/bvec.h:204
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_bio_read_cached
  - fs/squashfs/block.c:copy_bio_to_actor
  - fs/squashfs/block.c:copy_bio_to_actor
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff81665053)
Location: include/linux/bvec.h:204
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff816654dc)
Location: include/linux/bvec.h:204
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff81665868)
Location: include/linux/bvec.h:204
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff81665c84)
Location: include/linux/bvec.h:204
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff81666022)
Location: include/linux/bvec.h:204
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In block/bio.c (ffffffff817ab165)
Location: include/linux/bvec.h:204
Inline: True
Inline callers:
  - block/bio.c:bio_free_pages
```
```
In block/blk-map.c (ffffffff817ba765)
Location: include/linux/bvec.h:204
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
In fs/mpage.c (ffff8000103e5c14)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/mpage.c:mpage_end_io
```
```
In fs/crypto/bio.c (ffff800010410e70)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (ffff80001041390c)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffff80001042b00c)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/page-io.c (ffff8000104a3204)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffff8000104a4664)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In block/bio.c (ffff8000105dd71c)
Location: include/linux/bvec.h:136
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
In fs/mpage.c (c05bd838)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/mpage.c:mpage_end_io
```
```
In fs/crypto/bio.c (c05dd218)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (c05dfbb4)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (c05f2d9c)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/page-io.c (c0665250)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (c0666240)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In block/bio.c (c078ab5c)
Location: include/linux/bvec.h:136
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
In block/bounce.c (c07b2e3c)
Location: include/linux/bvec.h:136
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
In fs/mpage.c (c0000000004ebde4)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/mpage.c:mpage_end_io
```
```
In fs/crypto/bio.c (c00000000051e578)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (c0000000005218c4)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (c00000000053a9c4)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/page-io.c (c0000000005d0154)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (c0000000005d15fc)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In block/bio.c (c00000000076efec)
Location: include/linux/bvec.h:136
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
In fs/mpage.c (ffffffe00029b190)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/mpage.c:mpage_end_io
```
```
In fs/crypto/bio.c (ffffffe0002b905c)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (ffffffe0002bb2d2)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffe0002c7dfc)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/page-io.c (ffffffe000324aee)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffe00032583c)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In block/bio.c (ffffffe0004207e0)
Location: include/linux/bvec.h:136
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
In fs/mpage.c (ffffffff81322a87)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/mpage.c:mpage_end_io
```
```
In fs/crypto/bio.c (ffffffff81347842)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (ffffffff81349d97)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff8135be87)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/page-io.c (ffffffff813c3970)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff813c480d)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In block/bio.c (ffffffff814d91cd)
Location: include/linux/bvec.h:136
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
In block/bounce.c (ffffffff814fe078)
Location: include/linux/bvec.h:136
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
In fs/mpage.c (ffffffff81313627)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/mpage.c:mpage_end_io
```
```
In fs/crypto/bio.c (ffffffff81338522)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (ffffffff8133aa77)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff8134cb27)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/page-io.c (ffffffff813b4400)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff813b528d)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In block/bio.c (ffffffff814c9b7d)
Location: include/linux/bvec.h:136
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
In block/bounce.c (ffffffff814ee588)
Location: include/linux/bvec.h:136
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
In fs/mpage.c (ffffffff81320557)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/mpage.c:mpage_end_io
```
```
In fs/crypto/bio.c (ffffffff81345312)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (ffffffff81347867)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff81359957)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/page-io.c (ffffffff813c0e00)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff813c1c9d)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In block/bio.c (ffffffff814d525d)
Location: include/linux/bvec.h:136
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
In block/bounce.c (ffffffff814fa108)
Location: include/linux/bvec.h:136
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
In fs/mpage.c (ffffffff81332277)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/mpage.c:mpage_end_io
```
```
In fs/crypto/bio.c (ffffffff813585f2)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (ffffffff8135ab67)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff8136d047)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/page-io.c (ffffffff813d5f30)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff813d6e1d)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In block/bio.c (ffffffff814ede0d)
Location: include/linux/bvec.h:136
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
In block/bounce.c (ffffffff81513168)
Location: include/linux/bvec.h:136
Inline: True
Inline callers:
  - block/bounce.c:bounce_end_io
```
</details>
</li>
</ul>

## Differences
