# Function: <code>submit_bio_wait</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int submit_bio_wait(int rw, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813b04a0)
Location: block/bio.c:868
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - fs/ext4/crypto.c:ext4_encrypted_zeroout
  - block/blk-flush.c:blkdev_issue_flush
  - drivers/md/md.c:sync_page_io
```
**Symbols:**

```
ffffffff813b04a0-ffffffff813b052d: submit_bio_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int submit_bio_wait(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813f3ef0)
Location: block/bio.c:870
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - fs/crypto/crypto.c:fscrypt_zeroout_range
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - drivers/md/md.c:sync_page_io
```
**Symbols:**

```
ffffffff813f3ef0-ffffffff813f3f75: submit_bio_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int submit_bio_wait(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8140d890)
Location: block/bio.c:924
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - fs/crypto/crypto.c:fscrypt_zeroout_range
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
  - drivers/md/md.c:sync_page_io
```
**Symbols:**

```
ffffffff8140d890-ffffffff8140d918: submit_bio_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int submit_bio_wait(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8141b600)
Location: block/bio.c:940
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
  - drivers/md/md.c:sync_page_io
```
**Symbols:**

```
ffffffff8141b600-ffffffff8141b688: submit_bio_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int submit_bio_wait(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81446210)
Location: block/bio.c:939
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
  - drivers/md/md.c:sync_page_io
```
**Symbols:**

```
ffffffff81446210-ffffffff81446297: submit_bio_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int submit_bio_wait(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814791e0)
Location: block/bio.c:997
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_report_zones
  - drivers/md/md.c:sync_page_io
```
**Symbols:**

```
ffffffff814791e0-ffffffff81479267: submit_bio_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int submit_bio_wait(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814972d0)
Location: block/bio.c:921
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap.c:iomap_read_page_sync
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:sync_page_io
```
**Symbols:**

```
ffffffff814972d0-ffffffff81497357: submit_bio_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int submit_bio_wait(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c4c20)
Location: block/bio.c:980
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:sync_page_io
```
**Symbols:**

```
ffffffff814c4c20-ffffffff814c4ca6: submit_bio_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int submit_bio_wait(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814ddac0)
Location: block/bio.c:1019
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:sync_page_io
```
**Symbols:**

```
ffffffff814ddac0-ffffffff814ddb46: submit_bio_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int submit_bio_wait(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8153d480)
Location: block/bio.c:1143
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/squashfs/block.c:squashfs_bio_read
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-zoned.c:blkdev_zone_mgmt
  - drivers/md/md.c:sync_page_io
```
**Symbols:**

```
ffffffff8153d480-ffffffff8153d536: submit_bio_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int submit_bio_wait(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8155a070)
Location: block/bio.c:1146
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/squashfs/block.c:squashfs_bio_read
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-zoned.c:blkdev_zone_mgmt
  - drivers/md/md.c:sync_page_io
```
**Symbols:**

```
ffffffff8155a070-ffffffff8155a126: submit_bio_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int submit_bio_wait(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81562990)
Location: block/bio.c:1146
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/squashfs/block.c:squashfs_bio_read
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-zoned.c:blkdev_zone_mgmt
  - drivers/md/md.c:sync_page_io
```
**Symbols:**

```
ffffffff81562990-ffffffff81562a46: submit_bio_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int submit_bio_wait(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff815c66b0)
Location: block/bio.c:1240
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/squashfs/block.c:squashfs_bio_read
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
  - drivers/md/md.c:sync_page_io
```
**Symbols:**

```
ffffffff815c66b0-ffffffff815c6766: submit_bio_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int submit_bio_wait(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff816714b0)
Location: block/bio.c:1308
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - fs/iomap/buffered-io.c:iomap_read_folio_sync
  - fs/squashfs/block.c:squashfs_bio_read
  - block/fops.c:__blkdev_direct_IO_simple
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:blkdev_issue_secure_erase
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
  - drivers/md/md.c:sync_page_io
```
**Symbols:**

```
ffffffff816714b0-ffffffff81671572: submit_bio_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int submit_bio_wait(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8172cc70)
Location: block/bio.c:1371
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - fs/iomap/buffered-io.c:iomap_read_folio_sync
  - fs/squashfs/block.c:squashfs_bio_read
  - block/fops.c:__blkdev_direct_IO_simple
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:blkdev_issue_secure_erase
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
  - drivers/md/md.c:sync_page_io
```
**Symbols:**

```
ffffffff8172cc70-ffffffff8172cd32: submit_bio_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int submit_bio_wait(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81768ff0)
Location: block/bio.c:1356
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - mm/page_io.c:swap_readpage_bdev_sync
  - mm/page_io.c:swap_writepage_bdev_sync
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - fs/iomap/buffered-io.c:iomap_read_folio_sync
  - fs/squashfs/block.c:squashfs_bio_read
  - fs/squashfs/block.c:squashfs_bio_read_cached
  - block/fops.c:__blkdev_direct_IO_simple
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:blkdev_issue_secure_erase
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
  - drivers/md/md.c:sync_page_io
```
**Symbols:**

```
ffffffff81768ff0-ffffffff817690b2: submit_bio_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int submit_bio_wait(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff817ab020)
Location: block/bio.c:1368
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - mm/page_io.c:swap_read_folio_bdev_sync
  - mm/page_io.c:swap_writepage_bdev_sync
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - fs/iomap/buffered-io.c:iomap_read_folio_sync
  - fs/squashfs/block.c:squashfs_bio_read
  - fs/squashfs/block.c:squashfs_bio_read_cached
  - block/fops.c:__blkdev_direct_IO_simple
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:blkdev_issue_secure_erase
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
  - drivers/md/md.c:sync_page_io
```
**Symbols:**

```
ffffffff817ab020-ffffffff817ab0dd: submit_bio_wait (STB_GLOBAL)
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
int submit_bio_wait(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffff8000105d9f80)
Location: block/bio.c:1019
Inline: False
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:sync_page_io
```
**Symbols:**

```
ffff8000105d9f80-ffff8000105da014: submit_bio_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int submit_bio_wait(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c0787764)
Location: block/bio.c:1019
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:sync_page_io
```
**Symbols:**

```
c0787764-c0787800: submit_bio_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int submit_bio_wait(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c00000000076a690)
Location: block/bio.c:1019
Inline: False
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:sync_page_io
```
**Symbols:**

```
c00000000076a690-c00000000076a750: submit_bio_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int submit_bio_wait(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffe00041dae6)
Location: block/bio.c:1019
Inline: False
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:sync_page_io
```
**Symbols:**

```
ffffffe00041dae6-ffffffe00041db5c: submit_bio_wait (STB_GLOBAL)
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
int submit_bio_wait(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d60a0)
Location: block/bio.c:1019
Inline: False
Direct callers:
  - kernel/power/swap.c:swap_read_pages
  - kernel/power/swap.c:hib_submit_io
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:sync_page_io
```
**Symbols:**

```
ffffffff814d60a0-ffffffff814d6126: submit_bio_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int submit_bio_wait(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c6ac0)
Location: block/bio.c:1019
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:sync_page_io
```
**Symbols:**

```
ffffffff814c6ac0-ffffffff814c6b46: submit_bio_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int submit_bio_wait(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d2130)
Location: block/bio.c:1019
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:sync_page_io
```
**Symbols:**

```
ffffffff814d2130-ffffffff814d21b6: submit_bio_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int submit_bio_wait(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814eabe0)
Location: block/bio.c:1019
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_submit_io
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - block/blk-flush.c:blkdev_issue_flush
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:sync_page_io
```
**Symbols:**

```
ffffffff814eabe0-ffffffff814eac66: submit_bio_wait (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int rw</code>
</li>
<li>
<b>Param reordered. </b>
<code>rw, bio</code> ➡️ <code>bio</code>
</li>
</ul>
</details>
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
