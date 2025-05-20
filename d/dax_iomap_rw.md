# Function: <code>dax_iomap_rw</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t dax_iomap_rw(struct kiocb *iocb, struct iov_iter *iter, struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8129a990)
Location: fs/dax.c:1081
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffff8129a990-ffffffff8129aa35: dax_iomap_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t dax_iomap_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff812a9570)
Location: fs/dax.c:1037
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
**Symbols:**

```
ffffffff812a9570-ffffffff812a960f: dax_iomap_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t dax_iomap_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff812ccb40)
Location: fs/dax.c:1049
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
**Symbols:**

```
ffffffff812ccb40-ffffffff812ccbdf: dax_iomap_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t dax_iomap_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff812f6dc0)
Location: fs/dax.c:1286
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
**Symbols:**

```
ffffffff812f6dc0-ffffffff812f6e5f: dax_iomap_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t dax_iomap_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8130be70)
Location: fs/dax.c:1189
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
**Symbols:**

```
ffffffff8130be70-ffffffff8130bf0f: dax_iomap_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t dax_iomap_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813333a0)
Location: fs/dax.c:1194
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
**Symbols:**

```
ffffffff813333a0-ffffffff8133343f: dax_iomap_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t dax_iomap_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81346f50)
Location: fs/dax.c:1195
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
**Symbols:**

```
ffffffff81346f50-ffffffff81346ffd: dax_iomap_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t dax_iomap_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8138c620)
Location: fs/dax.c:1182
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
**Symbols:**

```
ffffffff8138c620-ffffffff8138c6cd: dax_iomap_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t dax_iomap_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8139dd50)
Location: fs/dax.c:1197
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/fuse/dax.c:fuse_dax_write_iter
  - fs/fuse/dax.c:fuse_dax_read_iter
```
**Symbols:**

```
ffffffff8139dd50-ffffffff8139ddfd: dax_iomap_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t dax_iomap_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813a4f60)
Location: fs/dax.c:1209
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/fuse/dax.c:fuse_dax_write_iter
  - fs/fuse/dax.c:fuse_dax_read_iter
```
**Symbols:**

```
ffffffff813a4f60-ffffffff813a500d: dax_iomap_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t dax_iomap_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dax.c (0)
Location: fs/dax.c:1270
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/fuse/dax.c:fuse_dax_write_iter
  - fs/fuse/dax.c:fuse_dax_read_iter
```
**Symbols:**

```
ffffffff81cc603f-ffffffff81cc6054: dax_iomap_rw.cold (STB_LOCAL)
ffffffff813f4aa0-ffffffff813f4b9c: dax_iomap_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t dax_iomap_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dax.c (0)
Location: fs/dax.c:1232
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/fuse/dax.c:fuse_dax_write_iter
  - fs/fuse/dax.c:fuse_dax_read_iter
```
**Symbols:**

```
ffffffff81e78281-ffffffff81e78296: dax_iomap_rw.cold (STB_LOCAL)
ffffffff81468190-ffffffff814682a1: dax_iomap_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t dax_iomap_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dax.c (0)
Location: fs/dax.c:1519
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/fuse/dax.c:fuse_dax_write_iter
  - fs/fuse/dax.c:fuse_dax_read_iter
```
**Symbols:**

```
ffffffff8206a16e-ffffffff8206a183: dax_iomap_rw.cold (STB_LOCAL)
ffffffff814f84f0-ffffffff814f8611: dax_iomap_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t dax_iomap_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dax.c (0)
Location: fs/dax.c:1562
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/fuse/dax.c:fuse_dax_write_iter
  - fs/fuse/dax.c:fuse_dax_read_iter
```
**Symbols:**

```
ffffffff820ea153-ffffffff820ea168: dax_iomap_rw.cold (STB_LOCAL)
ffffffff8152fda0-ffffffff8152fec1: dax_iomap_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ssize_t dax_iomap_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dax.c (0)
Location: fs/dax.c:1548
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/fuse/dax.c:fuse_dax_write_iter
  - fs/fuse/dax.c:fuse_dax_read_iter
```
**Symbols:**

```
ffffffff821c6bf8-ffffffff821c6c0d: dax_iomap_rw.cold (STB_LOCAL)
ffffffff81564c80-ffffffff81564da1: dax_iomap_rw (STB_GLOBAL)
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
ssize_t dax_iomap_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffff800010407230)
Location: fs/dax.c:1195
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
**Symbols:**

```
ffff800010407230-ffff8000104072fc: dax_iomap_rw (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t dax_iomap_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (c000000000512a20)
Location: fs/dax.c:1195
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
**Symbols:**

```
c000000000512a20-c000000000512b88: dax_iomap_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t dax_iomap_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffe0002b214a)
Location: fs/dax.c:1195
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
**Symbols:**

```
ffffffe0002b214a-ffffffe0002b21f6: dax_iomap_rw (STB_GLOBAL)
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
ssize_t dax_iomap_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8133f530)
Location: fs/dax.c:1195
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
**Symbols:**

```
ffffffff8133f530-ffffffff8133f5dd: dax_iomap_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t dax_iomap_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813301f0)
Location: fs/dax.c:1195
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
**Symbols:**

```
ffffffff813301f0-ffffffff8133029d: dax_iomap_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t dax_iomap_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8133d000)
Location: fs/dax.c:1195
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
**Symbols:**

```
ffffffff8133d000-ffffffff8133d0ad: dax_iomap_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t dax_iomap_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81350710)
Location: fs/dax.c:1195
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
**Symbols:**

```
ffffffff81350710-ffffffff813507bd: dax_iomap_rw (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct iomap_ops *ops</code> ➡️ <code>const struct iomap_ops *ops</code>
</li>
</ul>
</details>
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
