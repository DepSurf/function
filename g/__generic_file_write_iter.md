# Function: <code>__generic_file_write_iter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t __generic_file_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118f1e0)
Location: mm/filemap.c:2595
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - fs/block_dev.c:blkdev_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffff8118f1e0-ffffffff8118f3bf: __generic_file_write_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t __generic_file_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811a27e0)
Location: mm/filemap.c:2773
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffff811a27e0-ffffffff811a29a1: __generic_file_write_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t __generic_file_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b2620)
Location: mm/filemap.c:2889
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffff811b2620-ffffffff811b27e1: __generic_file_write_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t __generic_file_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b9290)
Location: mm/filemap.c:3023
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffff811b9290-ffffffff811b945f: __generic_file_write_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t __generic_file_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811cf710)
Location: mm/filemap.c:3199
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffff811cf710-ffffffff811cf8df: __generic_file_write_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t __generic_file_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811f0830)
Location: mm/filemap.c:3199
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffff811f0830-ffffffff811f0a07: __generic_file_write_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t __generic_file_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81201020)
Location: mm/filemap.c:3268
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffff81201020-ffffffff81201204: __generic_file_write_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t __generic_file_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81218c30)
Location: mm/filemap.c:3391
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffff81218c30-ffffffff81218dfd: __generic_file_write_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t __generic_file_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812264e0)
Location: mm/filemap.c:3348
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffff812264e0-ffffffff812266ad: __generic_file_write_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t __generic_file_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81251480)
Location: mm/filemap.c:3382
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - fs/block_dev.c:blkdev_write_iter
```
**Symbols:**

```
ffffffff81251480-ffffffff8125164d: __generic_file_write_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t __generic_file_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125cc60)
Location: mm/filemap.c:3476
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - fs/block_dev.c:blkdev_write_iter
```
**Symbols:**

```
ffffffff8125cc60-ffffffff8125ce2d: __generic_file_write_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t __generic_file_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812618e0)
Location: mm/filemap.c:3724
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - fs/block_dev.c:blkdev_write_iter
```
**Symbols:**

```
ffffffff812618e0-ffffffff81261aad: __generic_file_write_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t __generic_file_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8129a1e0)
Location: mm/filemap.c:3835
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - block/fops.c:blkdev_write_iter
```
**Symbols:**

```
ffffffff8129a1e0-ffffffff8129a3b8: __generic_file_write_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t __generic_file_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812f7250)
Location: mm/filemap.c:3841
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - block/fops.c:blkdev_write_iter
```
**Symbols:**

```
ffffffff812f7250-ffffffff812f73d1: __generic_file_write_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t __generic_file_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81360ae0)
Location: mm/filemap.c:3835
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - block/fops.c:blkdev_write_iter
```
**Symbols:**

```
ffffffff81360ae0-ffffffff81360c75: __generic_file_write_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t __generic_file_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81392f70)
Location: mm/filemap.c:3990
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - block/fops.c:blkdev_write_iter
```
**Symbols:**

```
ffffffff81392f70-ffffffff8139303b: __generic_file_write_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t __generic_file_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813bcc20)
Location: mm/filemap.c:3997
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
```
**Symbols:**

```
ffffffff813bcc20-ffffffff813bcceb: __generic_file_write_iter (STB_GLOBAL)
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
ssize_t __generic_file_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102b3808)
Location: mm/filemap.c:3348
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffff8000102b3808-ffff8000102b39e8: __generic_file_write_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t __generic_file_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04e0a64)
Location: mm/filemap.c:3348
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
c04e0a64-c04e0c60: __generic_file_write_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t __generic_file_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c00000000036a4a0)
Location: mm/filemap.c:3348
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
c00000000036a4a0-c00000000036a790: __generic_file_write_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t __generic_file_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d8e78)
Location: mm/filemap.c:3348
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffe0001d8e78-ffffffe0001d8fd2: __generic_file_write_iter (STB_GLOBAL)
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
ssize_t __generic_file_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121eb30)
Location: mm/filemap.c:3348
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffff8121eb30-ffffffff8121ecfd: __generic_file_write_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t __generic_file_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81211cf0)
Location: mm/filemap.c:3348
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffff81211cf0-ffffffff81211ebd: __generic_file_write_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t __generic_file_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121c8d0)
Location: mm/filemap.c:3348
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffff8121c8d0-ffffffff8121ca9d: __generic_file_write_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t __generic_file_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8122b960)
Location: mm/filemap.c:3348
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffff8122b960-ffffffff8122bb2d: __generic_file_write_iter (STB_GLOBAL)
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
