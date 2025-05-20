# Function: <code>generic_file_read_iter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t generic_file_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118eaa0)
Location: mm/filemap.c:1756
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_read_iter
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:fuse_file_read_iter
```
**Symbols:**

```
ffffffff8118eaa0-ffffffff8118f051: generic_file_read_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t generic_file_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811a2c90)
Location: mm/filemap.c:1901
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_read_iter
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:fuse_file_read_iter
```
**Symbols:**

```
ffffffff811a2c90-ffffffff811a3473: generic_file_read_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t generic_file_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b29b0)
Location: mm/filemap.c:2017
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_read_iter
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:fuse_file_read_iter
```
**Symbols:**

```
ffffffff811b29b0-ffffffff811b3299: generic_file_read_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t generic_file_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b9650)
Location: mm/filemap.c:2145
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:fuse_file_read_iter
```
**Symbols:**

```
ffffffff811b9650-ffffffff811ba045: generic_file_read_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t generic_file_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ce9c0)
Location: mm/filemap.c:2315
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:fuse_file_read_iter
```
**Symbols:**

```
ffffffff811ce9c0-ffffffff811cf5ae: generic_file_read_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t generic_file_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811f0570)
Location: mm/filemap.c:2312
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:fuse_file_read_iter
```
**Symbols:**

```
ffffffff811f0570-ffffffff811f06b7: generic_file_read_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t generic_file_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81200d60)
Location: mm/filemap.c:2300
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:fuse_file_read_iter
```
**Symbols:**

```
ffffffff81200d60-ffffffff81200ea7: generic_file_read_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t generic_file_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81218980)
Location: mm/filemap.c:2294
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:fuse_file_read_iter
```
**Symbols:**

```
ffffffff81218980-ffffffff81218ab5: generic_file_read_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t generic_file_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81226230)
Location: mm/filemap.c:2274
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:fuse_file_read_iter
```
**Symbols:**

```
ffffffff81226230-ffffffff81226365: generic_file_read_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t generic_file_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81252a20)
Location: mm/filemap.c:2276
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:fuse_file_read_iter
```
**Symbols:**

```
ffffffff81252a20-ffffffff81252b55: generic_file_read_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t generic_file_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125c950)
Location: mm/filemap.c:2587
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:fuse_file_read_iter
```
**Symbols:**

```
ffffffff8125c950-ffffffff8125ca88: generic_file_read_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t generic_file_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81262720)
Location: mm/filemap.c:2650
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:fuse_file_read_iter
```
**Symbols:**

```
ffffffff81262720-ffffffff81262860: generic_file_read_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t generic_file_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8129ed60)
Location: mm/filemap.c:2731
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:fuse_file_read_iter
  - block/fops.c:blkdev_read_iter
```
**Symbols:**

```
ffffffff8129ed60-ffffffff8129eea7: generic_file_read_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t generic_file_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812f5740)
Location: mm/filemap.c:2784
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:fuse_file_read_iter
```
**Symbols:**

```
ffffffff812f5740-ffffffff812f58bb: generic_file_read_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t generic_file_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8135f5f0)
Location: mm/filemap.c:2791
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:fuse_file_read_iter
```
**Symbols:**

```
ffffffff8135f5f0-ffffffff8135f75b: generic_file_read_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t generic_file_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81392190)
Location: mm/filemap.c:2798
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:fuse_file_read_iter
```
**Symbols:**

```
ffffffff81392190-ffffffff81392298: generic_file_read_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t generic_file_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813ba220)
Location: mm/filemap.c:2745
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:fuse_file_read_iter
```
**Symbols:**

```
ffffffff813ba220-ffffffff813ba328: generic_file_read_iter (STB_GLOBAL)
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
ssize_t generic_file_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102b3500)
Location: mm/filemap.c:2274
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:fuse_file_read_iter
```
**Symbols:**

```
ffff8000102b3500-ffff8000102b3680: generic_file_read_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t generic_file_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04e06bc)
Location: mm/filemap.c:2274
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:fuse_file_read_iter
```
**Symbols:**

```
c04e06bc-c04e0864: generic_file_read_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t generic_file_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c00000000036a070)
Location: mm/filemap.c:2274
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:fuse_file_read_iter
```
**Symbols:**

```
c00000000036a070-c00000000036a290: generic_file_read_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t generic_file_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d8c16)
Location: mm/filemap.c:2274
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:fuse_file_read_iter
```
**Symbols:**

```
ffffffe0001d8c16-ffffffe0001d8d46: generic_file_read_iter (STB_GLOBAL)
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
ssize_t generic_file_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121e880)
Location: mm/filemap.c:2274
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:fuse_file_read_iter
```
**Symbols:**

```
ffffffff8121e880-ffffffff8121e9b5: generic_file_read_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t generic_file_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81211a40)
Location: mm/filemap.c:2274
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:fuse_file_read_iter
```
**Symbols:**

```
ffffffff81211a40-ffffffff81211b75: generic_file_read_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t generic_file_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121c620)
Location: mm/filemap.c:2274
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:fuse_file_read_iter
```
**Symbols:**

```
ffffffff8121c620-ffffffff8121c755: generic_file_read_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t generic_file_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8122b6b0)
Location: mm/filemap.c:2274
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ecryptfs/file.c:ecryptfs_read_update_atime
  - fs/fuse/file.c:fuse_file_read_iter
```
**Symbols:**

```
ffffffff8122b6b0-ffffffff8122b7e5: generic_file_read_iter (STB_GLOBAL)
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
