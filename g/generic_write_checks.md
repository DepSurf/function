# Function: <code>generic_write_checks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
ssize_t generic_write_checks(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118d730)
Location: mm/filemap.c:2328
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff8118d730-ffffffff8118d818: generic_write_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t generic_write_checks(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811a29e2)
Location: mm/filemap.c:2505
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff811a0340-ffffffff811a0428: generic_write_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
ssize_t generic_write_checks(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b2822)
Location: mm/filemap.c:2621
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
Direct callers:
  - fs/ext4/file.c:ext4_write_checks
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff811af750-ffffffff811af838: generic_write_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t generic_write_checks(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b9492)
Location: mm/filemap.c:2755
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
Direct callers:
  - fs/ext4/file.c:ext4_write_checks
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff811b6630-ffffffff811b6730: generic_write_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t generic_write_checks(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811cf912)
Location: mm/filemap.c:2925
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
Direct callers:
  - fs/ext4/file.c:ext4_write_checks
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff811ca9b0-ffffffff811caab1: generic_write_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
ssize_t generic_write_checks(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811f0a42)
Location: mm/filemap.c:2925
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
Direct callers:
  - fs/ext4/file.c:ext4_write_checks
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff811eba00-ffffffff811ebb0b: generic_write_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
ssize_t generic_write_checks(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81201257)
Location: mm/filemap.c:2938
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
Direct callers:
  - fs/ext4/file.c:ext4_write_checks
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff811fc610-ffffffff811fc6b6: generic_write_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
ssize_t generic_write_checks(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81218e48)
Location: mm/filemap.c:2984
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
Direct callers:
  - fs/ext4/file.c:ext4_write_checks
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff81213d60-ffffffff81213e11: generic_write_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
ssize_t generic_write_checks(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812266f5)
Location: mm/filemap.c:2938
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
Direct callers:
  - fs/ext4/file.c:ext4_write_checks
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff81221560-ffffffff81221626: generic_write_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t generic_write_checks(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81251693)
Location: mm/filemap.c:2947
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
Direct callers:
  - fs/ext4/file.c:ext4_generic_write_checks
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_cache_write_iter
```
**Symbols:**

```
ffffffff8124e1f0-ffffffff8124e2a6: generic_write_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t generic_write_checks(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81320610)
Location: fs/read_write.c:1637
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - fs/ext4/file.c:ext4_generic_write_checks
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/dax.c:fuse_dax_write_iter
```
**Symbols:**

```
ffffffff81320610-ffffffff813206c9: generic_write_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t generic_write_checks(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81326750)
Location: fs/read_write.c:1642
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - fs/ext4/file.c:ext4_generic_write_checks
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/dax.c:fuse_dax_write_iter
```
**Symbols:**

```
ffffffff81326750-ffffffff81326809: generic_write_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t generic_write_checks(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81373cf0)
Location: fs/read_write.c:1633
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - fs/ext4/file.c:ext4_generic_write_checks
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/dax.c:fuse_dax_write_iter
```
**Symbols:**

```
ffffffff81373cf0-ffffffff81373da9: generic_write_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t generic_write_checks(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813f2ba0)
Location: fs/read_write.c:1680
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - fs/ext4/file.c:ext4_generic_write_checks
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/dax.c:fuse_dax_write_iter
```
**Symbols:**

```
ffffffff813f2ba0-ffffffff813f2c5f: generic_write_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t generic_write_checks(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8147b820)
Location: fs/read_write.c:1686
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - fs/ext4/file.c:ext4_generic_write_checks
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/dax.c:fuse_dax_write_iter
```
**Symbols:**

```
ffffffff8147b820-ffffffff8147b8e5: generic_write_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t generic_write_checks(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814b03b0)
Location: fs/read_write.c:1685
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - fs/ext4/file.c:ext4_generic_write_checks
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/dax.c:fuse_dax_write_iter
```
**Symbols:**

```
ffffffff814b03b0-ffffffff814b0475: generic_write_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t generic_write_checks(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814e1b70)
Location: fs/read_write.c:1702
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - mm/shmem.c:shmem_file_write_iter
  - fs/ext4/file.c:ext4_generic_write_checks
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/dax.c:fuse_dax_write_iter
```
**Symbols:**

```
ffffffff814e1b70-ffffffff814e1c35: generic_write_checks (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
ssize_t generic_write_checks(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102b3a38)
Location: mm/filemap.c:2938
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
Direct callers:
  - fs/ext4/file.c:ext4_write_checks
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffff8000102ae0f8-ffff8000102ae1d8: generic_write_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
ssize_t generic_write_checks(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04e0cac)
Location: mm/filemap.c:2938
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
c04dc28c-c04dc3cc: generic_write_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
ssize_t generic_write_checks(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c00000000036a7ec)
Location: mm/filemap.c:2938
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
Direct callers:
  - fs/ext4/file.c:ext4_write_checks
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
c000000000363580-c0000000003636c8: generic_write_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
ssize_t generic_write_checks(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d8ff2)
Location: mm/filemap.c:2938
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
Direct callers:
  - fs/ext4/file.c:ext4_write_checks
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffe0001d4d96-ffffffe0001d4e14: generic_write_checks (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
ssize_t generic_write_checks(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121ed45)
Location: mm/filemap.c:2938
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
Direct callers:
  - fs/ext4/file.c:ext4_write_checks
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff81219bb0-ffffffff81219c76: generic_write_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
ssize_t generic_write_checks(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81211f05)
Location: mm/filemap.c:2938
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
Direct callers:
  - fs/ext4/file.c:ext4_write_checks
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff8120cdc0-ffffffff8120ce86: generic_write_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
ssize_t generic_write_checks(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121cae5)
Location: mm/filemap.c:2938
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
Direct callers:
  - fs/ext4/file.c:ext4_write_checks
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff81217950-ffffffff81217a16: generic_write_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
ssize_t generic_write_checks(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8122bb75)
Location: mm/filemap.c:2938
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
Direct callers:
  - fs/ext4/file.c:ext4_write_checks
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff81226a10-ffffffff81226ad6: generic_write_checks (STB_GLOBAL)
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
