# Function: <code>__blockdev_direct_IO</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t __blockdev_direct_IO(struct kiocb *iocb, struct inode *inode, struct block_device *bdev, struct iov_iter *iter, loff_t offset, get_block_t *get_block, dio_iodone_t *end_io, dio_submit_t *submit_io, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff8124d4b0)
Location: fs/direct-io.c:1323
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/indirect.c:ext4_ind_direct_IO
  - fs/ext4/indirect.c:ext4_ind_direct_IO
  - fs/fat/inode.c:fat_direct_IO
```
**Symbols:**

```
ffffffff8124d4b0-ffffffff8124d4f5: __blockdev_direct_IO (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t __blockdev_direct_IO(struct kiocb *iocb, struct inode *inode, struct block_device *bdev, struct iov_iter *iter, get_block_t *get_block, dio_iodone_t *end_io, dio_submit_t *submit_io, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81275bb0)
Location: fs/direct-io.c:1338
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/fat/inode.c:fat_direct_IO
```
**Symbols:**

```
ffffffff81275bb0-ffffffff81275bec: __blockdev_direct_IO (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t __blockdev_direct_IO(struct kiocb *iocb, struct inode *inode, struct block_device *bdev, struct iov_iter *iter, get_block_t *get_block, dio_iodone_t *end_io, dio_submit_t *submit_io, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff812898e0)
Location: fs/direct-io.c:1328
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/fat/inode.c:fat_direct_IO
```
**Symbols:**

```
ffffffff812898e0-ffffffff8128991c: __blockdev_direct_IO (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t __blockdev_direct_IO(struct kiocb *iocb, struct inode *inode, struct block_device *bdev, struct iov_iter *iter, get_block_t *get_block, dio_iodone_t *end_io, dio_submit_t *submit_io, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff812965f0)
Location: fs/direct-io.c:1333
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/fat/inode.c:fat_direct_IO
```
**Symbols:**

```
ffffffff812965f0-ffffffff81296620: __blockdev_direct_IO (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t __blockdev_direct_IO(struct kiocb *iocb, struct inode *inode, struct block_device *bdev, struct iov_iter *iter, get_block_t *get_block, dio_iodone_t *end_io, dio_submit_t *submit_io, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff812b9820)
Location: fs/direct-io.c:1381
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/fat/inode.c:fat_direct_IO
```
**Symbols:**

```
ffffffff812b9820-ffffffff812b9850: __blockdev_direct_IO (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t __blockdev_direct_IO(struct kiocb *iocb, struct inode *inode, struct block_device *bdev, struct iov_iter *iter, get_block_t *get_block, dio_iodone_t *end_io, dio_submit_t *submit_io, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff812e2330)
Location: fs/direct-io.c:1399
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/fat/inode.c:fat_direct_IO
```
**Symbols:**

```
ffffffff812e2330-ffffffff812e2360: __blockdev_direct_IO (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t __blockdev_direct_IO(struct kiocb *iocb, struct inode *inode, struct block_device *bdev, struct iov_iter *iter, get_block_t *get_block, dio_iodone_t *end_io, dio_submit_t *submit_io, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff812f6f70)
Location: fs/direct-io.c:1402
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/fat/inode.c:fat_direct_IO
```
**Symbols:**

```
ffffffff812f6f70-ffffffff812f6fa0: __blockdev_direct_IO (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t __blockdev_direct_IO(struct kiocb *iocb, struct inode *inode, struct block_device *bdev, struct iov_iter *iter, get_block_t *get_block, dio_iodone_t *end_io, dio_submit_t *submit_io, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81317550)
Location: fs/direct-io.c:1395
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/fat/inode.c:fat_direct_IO
```
**Symbols:**

```
ffffffff81317550-ffffffff81317580: __blockdev_direct_IO (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t __blockdev_direct_IO(struct kiocb *iocb, struct inode *inode, struct block_device *bdev, struct iov_iter *iter, get_block_t *get_block, dio_iodone_t *end_io, dio_submit_t *submit_io, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff8132a3d0)
Location: fs/direct-io.c:1394
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/fat/inode.c:fat_direct_IO
```
**Symbols:**

```
ffffffff8132a3d0-ffffffff8132a400: __blockdev_direct_IO (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t __blockdev_direct_IO(struct kiocb *iocb, struct inode *inode, struct block_device *bdev, struct iov_iter *iter, get_block_t *get_block, dio_iodone_t *end_io, dio_submit_t *submit_io, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81364100)
Location: fs/direct-io.c:1375
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_direct_IO
```
**Symbols:**

```
ffffffff81364100-ffffffff81364130: __blockdev_direct_IO (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t __blockdev_direct_IO(struct kiocb *iocb, struct inode *inode, struct block_device *bdev, struct iov_iter *iter, get_block_t *get_block, dio_iodone_t *end_io, dio_submit_t *submit_io, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81371000)
Location: fs/direct-io.c:1347
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_direct_IO
```
**Symbols:**

```
ffffffff81371000-ffffffff8137102d: __blockdev_direct_IO (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t __blockdev_direct_IO(struct kiocb *iocb, struct inode *inode, struct block_device *bdev, struct iov_iter *iter, get_block_t *get_block, dio_iodone_t *end_io, dio_submit_t *submit_io, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff813779c0)
Location: fs/direct-io.c:1350
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_direct_IO
```
**Symbols:**

```
ffffffff813779c0-ffffffff813779ed: __blockdev_direct_IO (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t __blockdev_direct_IO(struct kiocb *iocb, struct inode *inode, struct block_device *bdev, struct iov_iter *iter, get_block_t *get_block, dio_iodone_t *end_io, dio_submit_t *submit_io, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff813c4040)
Location: fs/direct-io.c:1350
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_direct_IO
```
**Symbols:**

```
ffffffff813c4040-ffffffff813c406d: __blockdev_direct_IO (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t __blockdev_direct_IO(struct kiocb *iocb, struct inode *inode, struct block_device *bdev, struct iov_iter *iter, get_block_t *get_block, dio_iodone_t *end_io, dio_submit_t *submit_io, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/direct-io.c (0)
Location: fs/direct-io.c:1118
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_direct_IO
```
**Symbols:**

```
ffffffff81e777d1-ffffffff81e77a09: __blockdev_direct_IO.cold (STB_LOCAL)
ffffffff8144a350-ffffffff8144ae77: __blockdev_direct_IO (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t __blockdev_direct_IO(struct kiocb *iocb, struct inode *inode, struct block_device *bdev, struct iov_iter *iter, get_block_t *get_block, dio_iodone_t *end_io, dio_submit_t *submit_io, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/direct-io.c (0)
Location: fs/direct-io.c:1122
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_direct_IO
```
**Symbols:**

```
ffffffff82069774-ffffffff82069a52: __blockdev_direct_IO.cold (STB_LOCAL)
ffffffff814d8a60-ffffffff814d959f: __blockdev_direct_IO (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t __blockdev_direct_IO(struct kiocb *iocb, struct inode *inode, struct block_device *bdev, struct iov_iter *iter, get_block_t *get_block, dio_iodone_t *end_io, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/direct-io.c (0)
Location: fs/direct-io.c:1104
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_direct_IO
```
**Symbols:**

```
ffffffff820e999c-ffffffff820e9cce: __blockdev_direct_IO.cold (STB_LOCAL)
ffffffff81511940-ffffffff8151230b: __blockdev_direct_IO (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ssize_t __blockdev_direct_IO(struct kiocb *iocb, struct inode *inode, struct block_device *bdev, struct iov_iter *iter, get_block_t *get_block, dio_iodone_t *end_io, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/direct-io.c (0)
Location: fs/direct-io.c:1104
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_direct_IO
```
**Symbols:**

```
ffffffff821c6507-ffffffff821c6783: __blockdev_direct_IO.cold (STB_LOCAL)
ffffffff81545de0-ffffffff815467be: __blockdev_direct_IO (STB_GLOBAL)
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
ssize_t __blockdev_direct_IO(struct kiocb *iocb, struct inode *inode, struct block_device *bdev, struct iov_iter *iter, get_block_t *get_block, dio_iodone_t *end_io, dio_submit_t *submit_io, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffff8000103e5778)
Location: fs/direct-io.c:1394
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/fat/inode.c:fat_direct_IO
```
**Symbols:**

```
ffff8000103e5778-ffff8000103e5810: __blockdev_direct_IO (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t __blockdev_direct_IO(struct kiocb *iocb, struct inode *inode, struct block_device *bdev, struct iov_iter *iter, get_block_t *get_block, dio_iodone_t *end_io, dio_submit_t *submit_io, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (c05bd6bc)
Location: fs/direct-io.c:1394
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/fat/inode.c:fat_direct_IO
```
**Symbols:**

```
c05bd6bc-c05bd70c: __blockdev_direct_IO (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t __blockdev_direct_IO(struct kiocb *iocb, struct inode *inode, struct block_device *bdev, struct iov_iter *iter, get_block_t *get_block, dio_iodone_t *end_io, dio_submit_t *submit_io, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (c0000000004ebbf0)
Location: fs/direct-io.c:1394
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/fat/inode.c:fat_direct_IO
```
**Symbols:**

```
c0000000004ebbf0-c0000000004ebc34: __blockdev_direct_IO (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t __blockdev_direct_IO(struct kiocb *iocb, struct inode *inode, struct block_device *bdev, struct iov_iter *iter, get_block_t *get_block, dio_iodone_t *end_io, dio_submit_t *submit_io, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffe00029b016)
Location: fs/direct-io.c:1394
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/fat/inode.c:fat_direct_IO
```
**Symbols:**

```
ffffffe00029b016-ffffffe00029b078: __blockdev_direct_IO (STB_GLOBAL)
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
ssize_t __blockdev_direct_IO(struct kiocb *iocb, struct inode *inode, struct block_device *bdev, struct iov_iter *iter, get_block_t *get_block, dio_iodone_t *end_io, dio_submit_t *submit_io, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff813229b0)
Location: fs/direct-io.c:1394
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/fat/inode.c:fat_direct_IO
```
**Symbols:**

```
ffffffff813229b0-ffffffff813229e0: __blockdev_direct_IO (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t __blockdev_direct_IO(struct kiocb *iocb, struct inode *inode, struct block_device *bdev, struct iov_iter *iter, get_block_t *get_block, dio_iodone_t *end_io, dio_submit_t *submit_io, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81313550)
Location: fs/direct-io.c:1394
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/fat/inode.c:fat_direct_IO
```
**Symbols:**

```
ffffffff81313550-ffffffff81313580: __blockdev_direct_IO (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t __blockdev_direct_IO(struct kiocb *iocb, struct inode *inode, struct block_device *bdev, struct iov_iter *iter, get_block_t *get_block, dio_iodone_t *end_io, dio_submit_t *submit_io, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81320480)
Location: fs/direct-io.c:1394
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/fat/inode.c:fat_direct_IO
```
**Symbols:**

```
ffffffff81320480-ffffffff813204b0: __blockdev_direct_IO (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t __blockdev_direct_IO(struct kiocb *iocb, struct inode *inode, struct block_device *bdev, struct iov_iter *iter, get_block_t *get_block, dio_iodone_t *end_io, dio_submit_t *submit_io, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff813321a0)
Location: fs/direct-io.c:1394
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/fat/inode.c:fat_direct_IO
```
**Symbols:**

```
ffffffff813321a0-ffffffff813321d0: __blockdev_direct_IO (STB_GLOBAL)
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
<code>loff_t offset</code>
</li>
<li>
<b>Param reordered. </b>
<code>iocb, inode, bdev, iter, offset, get_block, end_io, submit_io, flags</code> ➡️ <code>iocb, inode, bdev, iter, get_block, end_io, submit_io, flags</code>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>dio_submit_t *submit_io</code>
</li>
<li>
<b>Param reordered. </b>
<code>iocb, inode, bdev, iter, get_block, end_io, submit_io, flags</code> ➡️ <code>iocb, inode, bdev, iter, get_block, end_io, flags</code>
</li>
</ul>
</details>
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
