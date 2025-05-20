# Function: <code>fuse_direct_io</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t fuse_direct_io(struct fuse_io_priv *io, struct iov_iter *iter, loff_t *ppos, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81317d30)
Location: fs/fuse/file.c:1306
Inline: False
Direct callers:
  - fs/fuse/file.c:__fuse_direct_read
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_direct_IO
```
**Symbols:**

```
ffffffff81317d30-ffffffff813182e6: fuse_direct_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t fuse_direct_io(struct fuse_io_priv *io, struct iov_iter *iter, loff_t *ppos, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8134c650)
Location: fs/fuse/file.c:1319
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:__fuse_direct_read
```
**Symbols:**

```
ffffffff8134c650-ffffffff8134cd00: fuse_direct_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t fuse_direct_io(struct fuse_io_priv *io, struct iov_iter *iter, loff_t *ppos, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81361f60)
Location: fs/fuse/file.c:1320
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:__fuse_direct_read
```
**Symbols:**

```
ffffffff81361f60-ffffffff81362610: fuse_direct_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t fuse_direct_io(struct fuse_io_priv *io, struct iov_iter *iter, loff_t *ppos, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81376930)
Location: fs/fuse/file.c:1315
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:__fuse_direct_read
```
**Symbols:**

```
ffffffff81376930-ffffffff81376f81: fuse_direct_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t fuse_direct_io(struct fuse_io_priv *io, struct iov_iter *iter, loff_t *ppos, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8139b700)
Location: fs/fuse/file.c:1325
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:__fuse_direct_read
```
**Symbols:**

```
ffffffff8139b700-ffffffff8139bd34: fuse_direct_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t fuse_direct_io(struct fuse_io_priv *io, struct iov_iter *iter, loff_t *ppos, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813ca7a0)
Location: fs/fuse/file.c:1326
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:__fuse_direct_read
```
**Symbols:**

```
ffffffff813ca7a0-ffffffff813cace2: fuse_direct_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t fuse_direct_io(struct fuse_io_priv *io, struct iov_iter *iter, loff_t *ppos, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813e3ec0)
Location: fs/fuse/file.c:1328
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:__fuse_direct_read
```
**Symbols:**

```
ffffffff813e3ec0-ffffffff813e4503: fuse_direct_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t fuse_direct_io(struct fuse_io_priv *io, struct iov_iter *iter, loff_t *ppos, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8140fc90)
Location: fs/fuse/file.c:1337
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
```
**Symbols:**

```
ffffffff8140fc90-ffffffff814102ad: fuse_direct_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t fuse_direct_io(struct fuse_io_priv *io, struct iov_iter *iter, loff_t *ppos, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81429560)
Location: fs/fuse/file.c:1421
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
```
**Symbols:**

```
ffffffff81429560-ffffffff81429cbb: fuse_direct_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t fuse_direct_io(struct fuse_io_priv *io, struct iov_iter *iter, loff_t *ppos, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814794d0)
Location: fs/fuse/file.c:1394
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_direct_write_iter
```
**Symbols:**

```
ffffffff814794d0-ffffffff81479b3f: fuse_direct_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t fuse_direct_io(struct fuse_io_priv *io, struct iov_iter *iter, loff_t *ppos, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814941f0)
Location: fs/fuse/file.c:1426
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/dax.c:fuse_dax_write_iter
```
**Symbols:**

```
ffffffff814941f0-ffffffff81494860: fuse_direct_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t fuse_direct_io(struct fuse_io_priv *io, struct iov_iter *iter, loff_t *ppos, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814990a0)
Location: fs/fuse/file.c:1428
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/dax.c:fuse_dax_write_iter
```
**Symbols:**

```
ffffffff814990a0-ffffffff814998bd: fuse_direct_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t fuse_direct_io(struct fuse_io_priv *io, struct iov_iter *iter, loff_t *ppos, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (0)
Location: fs/fuse/file.c:1431
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/dax.c:fuse_dax_write_iter
```
**Symbols:**

```
ffffffff81cd215a-ffffffff81cd216f: fuse_direct_io.cold (STB_LOCAL)
ffffffff814f0b30-ffffffff814f12d3: fuse_direct_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t fuse_direct_io(struct fuse_io_priv *io, struct iov_iter *iter, loff_t *ppos, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (0)
Location: fs/fuse/file.c:1449
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/dax.c:fuse_dax_write_iter
```
**Symbols:**

```
ffffffff81e8528e-ffffffff81e852a9: fuse_direct_io.cold (STB_LOCAL)
ffffffff815803d0-ffffffff81580bee: fuse_direct_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t fuse_direct_io(struct fuse_io_priv *io, struct iov_iter *iter, loff_t *ppos, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (0)
Location: fs/fuse/file.c:1448
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/dax.c:fuse_dax_write_iter
```
**Symbols:**

```
ffffffff8207279c-ffffffff820727cd: fuse_direct_io.cold (STB_LOCAL)
ffffffff81626180-ffffffff816269bc: fuse_direct_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t fuse_direct_io(struct fuse_io_priv *io, struct iov_iter *iter, loff_t *ppos, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (0)
Location: fs/fuse/file.c:1425
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/dax.c:fuse_dax_write_iter
```
**Symbols:**

```
ffffffff820f2407-ffffffff820f2431: fuse_direct_io.cold (STB_LOCAL)
ffffffff8165e580-ffffffff8165ed90: fuse_direct_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ssize_t fuse_direct_io(struct fuse_io_priv *io, struct iov_iter *iter, loff_t *ppos, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (0)
Location: fs/fuse/file.c:1426
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/dax.c:fuse_dax_write_iter
```
**Symbols:**

```
ffffffff821cf6b7-ffffffff821cf6cc: fuse_direct_io.cold (STB_LOCAL)
ffffffff816982c0-ffffffff81698bc4: fuse_direct_io (STB_GLOBAL)
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
ssize_t fuse_direct_io(struct fuse_io_priv *io, struct iov_iter *iter, loff_t *ppos, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffff80001050d548)
Location: fs/fuse/file.c:1421
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
```
**Symbols:**

```
ffff80001050d548-ffff80001050dc20: fuse_direct_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t fuse_direct_io(struct fuse_io_priv *io, struct iov_iter *iter, loff_t *ppos, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c06c8d90)
Location: fs/fuse/file.c:1421
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
```
**Symbols:**

```
c06c8d90-c06c94b0: fuse_direct_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t fuse_direct_io(struct fuse_io_priv *io, struct iov_iter *iter, loff_t *ppos, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c000000000654180)
Location: fs/fuse/file.c:1421
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
```
**Symbols:**

```
c000000000654180-c000000000654a28: fuse_direct_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t fuse_direct_io(struct fuse_io_priv *io, struct iov_iter *iter, loff_t *ppos, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffe0003783ac)
Location: fs/fuse/file.c:1421
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
```
**Symbols:**

```
ffffffe0003783ac-ffffffe000378992: fuse_direct_io (STB_GLOBAL)
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
ssize_t fuse_direct_io(struct fuse_io_priv *io, struct iov_iter *iter, loff_t *ppos, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81421b40)
Location: fs/fuse/file.c:1421
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
```
**Symbols:**

```
ffffffff81421b40-ffffffff8142229b: fuse_direct_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t fuse_direct_io(struct fuse_io_priv *io, struct iov_iter *iter, loff_t *ppos, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814125c0)
Location: fs/fuse/file.c:1421
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
```
**Symbols:**

```
ffffffff814125c0-ffffffff81412d1b: fuse_direct_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t fuse_direct_io(struct fuse_io_priv *io, struct iov_iter *iter, loff_t *ppos, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8141dce0)
Location: fs/fuse/file.c:1421
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
```
**Symbols:**

```
ffffffff8141dce0-ffffffff8141e43b: fuse_direct_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t fuse_direct_io(struct fuse_io_priv *io, struct iov_iter *iter, loff_t *ppos, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81434a40)
Location: fs/fuse/file.c:1421
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
```
**Symbols:**

```
ffffffff81434a40-ffffffff8143519b: fuse_direct_io (STB_GLOBAL)
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
