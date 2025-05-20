# Function: <code>do_blockdev_direct_IO</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t do_blockdev_direct_IO(struct kiocb *iocb, struct inode *inode, struct block_device *bdev, struct iov_iter *iter, loff_t offset, get_block_t *get_block, dio_iodone_t *end_io, dio_submit_t *submit_io, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff8124a0a0)
Location: fs/direct-io.c:1108
Inline: False
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
**Symbols:**

```
ffffffff8124a0a0-ffffffff8124d4aa: do_blockdev_direct_IO (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t do_blockdev_direct_IO(struct kiocb *iocb, struct inode *inode, struct block_device *bdev, struct iov_iter *iter, get_block_t *get_block, dio_iodone_t *end_io, dio_submit_t *submit_io, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81272b90)
Location: fs/direct-io.c:1117
Inline: False
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
**Symbols:**

```
ffffffff81272b90-ffffffff81275bac: do_blockdev_direct_IO (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t do_blockdev_direct_IO(struct kiocb *iocb, struct inode *inode, struct block_device *bdev, struct iov_iter *iter, get_block_t *get_block, dio_iodone_t *end_io, dio_submit_t *submit_io, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81286690)
Location: fs/direct-io.c:1107
Inline: False
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
**Symbols:**

```
ffffffff81286690-ffffffff812898da: do_blockdev_direct_IO (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t do_blockdev_direct_IO(struct kiocb *iocb, struct inode *inode, struct block_device *bdev, struct iov_iter *iter, get_block_t *get_block, dio_iodone_t *end_io, dio_submit_t *submit_io, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81293d10)
Location: fs/direct-io.c:1110
Inline: False
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
**Symbols:**

```
ffffffff81293d10-ffffffff812965ec: do_blockdev_direct_IO (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t do_blockdev_direct_IO(struct kiocb *iocb, struct inode *inode, struct block_device *bdev, struct iov_iter *iter, get_block_t *get_block, dio_iodone_t *end_io, dio_submit_t *submit_io, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff812b6c70)
Location: fs/direct-io.c:1150
Inline: False
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
**Symbols:**

```
ffffffff812b6c70-ffffffff812b9812: do_blockdev_direct_IO (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t do_blockdev_direct_IO(struct kiocb *iocb, struct inode *inode, struct block_device *bdev, struct iov_iter *iter, get_block_t *get_block, dio_iodone_t *end_io, dio_submit_t *submit_io, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff812df670)
Location: fs/direct-io.c:1171
Inline: False
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
**Symbols:**

```
ffffffff812df670-ffffffff812e232a: do_blockdev_direct_IO (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t do_blockdev_direct_IO(struct kiocb *iocb, struct inode *inode, struct block_device *bdev, struct iov_iter *iter, get_block_t *get_block, dio_iodone_t *end_io, dio_submit_t *submit_io, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff812f4170)
Location: fs/direct-io.c:1172
Inline: False
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
**Symbols:**

```
ffffffff812f4170-ffffffff812f6f6e: do_blockdev_direct_IO (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t do_blockdev_direct_IO(struct kiocb *iocb, struct inode *inode, struct block_device *bdev, struct iov_iter *iter, get_block_t *get_block, dio_iodone_t *end_io, dio_submit_t *submit_io, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81316890)
Location: fs/direct-io.c:1165
Inline: False
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
**Symbols:**

```
ffffffff81316890-ffffffff81317550: do_blockdev_direct_IO (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t do_blockdev_direct_IO(struct kiocb *iocb, struct inode *inode, struct block_device *bdev, struct iov_iter *iter, get_block_t *get_block, dio_iodone_t *end_io, dio_submit_t *submit_io, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81329710)
Location: fs/direct-io.c:1164
Inline: False
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
**Symbols:**

```
ffffffff81329710-ffffffff8132a3ce: do_blockdev_direct_IO (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t do_blockdev_direct_IO(struct kiocb *iocb, struct inode *inode, struct block_device *bdev, struct iov_iter *iter, get_block_t *get_block, dio_iodone_t *end_io, dio_submit_t *submit_io, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff813634f0)
Location: fs/direct-io.c:1145
Inline: False
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
**Symbols:**

```
ffffffff813634f0-ffffffff813640fa: do_blockdev_direct_IO (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t do_blockdev_direct_IO(struct kiocb *iocb, struct inode *inode, struct block_device *bdev, struct iov_iter *iter, get_block_t *get_block, dio_iodone_t *end_io, dio_submit_t *submit_io, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81370720)
Location: fs/direct-io.c:1126
Inline: False
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
**Symbols:**

```
ffffffff81370720-ffffffff81370ffb: do_blockdev_direct_IO (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t do_blockdev_direct_IO(struct kiocb *iocb, struct inode *inode, struct block_device *bdev, struct iov_iter *iter, get_block_t *get_block, dio_iodone_t *end_io, dio_submit_t *submit_io, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81377000)
Location: fs/direct-io.c:1129
Inline: False
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
**Symbols:**

```
ffffffff81377000-ffffffff813779c0: do_blockdev_direct_IO (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t do_blockdev_direct_IO(struct kiocb *iocb, struct inode *inode, struct block_device *bdev, struct iov_iter *iter, get_block_t *get_block, dio_iodone_t *end_io, dio_submit_t *submit_io, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/direct-io.c (0)
Location: fs/direct-io.c:1129
Inline: False
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
**Symbols:**

```
ffffffff813c35d0-ffffffff813c403a: do_blockdev_direct_IO (STB_LOCAL)
ffffffff81cc4dde-ffffffff81cc5000: do_blockdev_direct_IO.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: ✅</summary>

```c
ssize_t do_blockdev_direct_IO(struct kiocb *iocb, struct inode *inode, struct block_device *bdev, struct iov_iter *iter, get_block_t *get_block, dio_iodone_t *end_io, dio_submit_t *submit_io, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffff8000103e4b68)
Location: fs/direct-io.c:1164
Inline: False
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
**Symbols:**

```
ffff8000103e4b68-ffff8000103e5774: do_blockdev_direct_IO (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t do_blockdev_direct_IO(struct kiocb *iocb, struct inode *inode, struct block_device *bdev, struct iov_iter *iter, get_block_t *get_block, dio_iodone_t *end_io, dio_submit_t *submit_io, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (c05bca30)
Location: fs/direct-io.c:1164
Inline: False
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
**Symbols:**

```
c05bca30-c05bd6bc: do_blockdev_direct_IO (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t do_blockdev_direct_IO(struct kiocb *iocb, struct inode *inode, struct block_device *bdev, struct iov_iter *iter, get_block_t *get_block, dio_iodone_t *end_io, dio_submit_t *submit_io, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (c0000000004eae10)
Location: fs/direct-io.c:1164
Inline: False
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
**Symbols:**

```
c0000000004eae10-c0000000004ebbec: do_blockdev_direct_IO (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t do_blockdev_direct_IO(struct kiocb *iocb, struct inode *inode, struct block_device *bdev, struct iov_iter *iter, get_block_t *get_block, dio_iodone_t *end_io, dio_submit_t *submit_io, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffe00029a742)
Location: fs/direct-io.c:1164
Inline: False
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
**Symbols:**

```
ffffffe00029a742-ffffffe00029b016: do_blockdev_direct_IO (STB_LOCAL)
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
ssize_t do_blockdev_direct_IO(struct kiocb *iocb, struct inode *inode, struct block_device *bdev, struct iov_iter *iter, get_block_t *get_block, dio_iodone_t *end_io, dio_submit_t *submit_io, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81321cf0)
Location: fs/direct-io.c:1164
Inline: False
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
**Symbols:**

```
ffffffff81321cf0-ffffffff813229ae: do_blockdev_direct_IO (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t do_blockdev_direct_IO(struct kiocb *iocb, struct inode *inode, struct block_device *bdev, struct iov_iter *iter, get_block_t *get_block, dio_iodone_t *end_io, dio_submit_t *submit_io, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81312890)
Location: fs/direct-io.c:1164
Inline: False
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
**Symbols:**

```
ffffffff81312890-ffffffff8131354e: do_blockdev_direct_IO (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t do_blockdev_direct_IO(struct kiocb *iocb, struct inode *inode, struct block_device *bdev, struct iov_iter *iter, get_block_t *get_block, dio_iodone_t *end_io, dio_submit_t *submit_io, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff8131f7c0)
Location: fs/direct-io.c:1164
Inline: False
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
**Symbols:**

```
ffffffff8131f7c0-ffffffff8132047e: do_blockdev_direct_IO (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t do_blockdev_direct_IO(struct kiocb *iocb, struct inode *inode, struct block_device *bdev, struct iov_iter *iter, get_block_t *get_block, dio_iodone_t *end_io, dio_submit_t *submit_io, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff813314e0)
Location: fs/direct-io.c:1164
Inline: False
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
**Symbols:**

```
ffffffff813314e0-ffffffff8133219e: do_blockdev_direct_IO (STB_LOCAL)
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
