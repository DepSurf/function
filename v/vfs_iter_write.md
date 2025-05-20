# Function: <code>vfs_iter_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfs_iter_write(struct file *file, struct iov_iter *iter, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8120c1d0)
Location: fs/read_write.c:352
Inline: True
Direct callers:
  - fs/splice.c:iter_file_splice_write
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff8120c1d0-ffffffff8120c28c: vfs_iter_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfs_iter_write(struct file *file, struct iov_iter *iter, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812326d0)
Location: fs/read_write.c:381
Inline: True
Direct callers:
  - fs/splice.c:iter_file_splice_write
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff812326d0-ffffffff812327dd: vfs_iter_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfs_iter_write(struct file *file, struct iov_iter *iter, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81245040)
Location: fs/read_write.c:381
Inline: True
Direct callers:
  - fs/splice.c:iter_file_splice_write
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff81245040-ffffffff8124514d: vfs_iter_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t vfs_iter_write(struct file *file, struct iov_iter *iter, loff_t *ppos, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81251610)
Location: fs/read_write.c:961
Inline: False
Direct callers:
  - fs/splice.c:iter_file_splice_write
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff81251610-ffffffff81251633: vfs_iter_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t vfs_iter_write(struct file *file, struct iov_iter *iter, loff_t *ppos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81272f80)
Location: fs/read_write.c:966
Inline: False
Direct callers:
  - fs/splice.c:iter_file_splice_write
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff81272f80-ffffffff81272fa3: vfs_iter_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t vfs_iter_write(struct file *file, struct iov_iter *iter, loff_t *ppos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81299040)
Location: fs/read_write.c:993
Inline: False
Direct callers:
  - fs/splice.c:iter_file_splice_write
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff81299040-ffffffff81299063: vfs_iter_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t vfs_iter_write(struct file *file, struct iov_iter *iter, loff_t *ppos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812adec0)
Location: fs/read_write.c:990
Inline: False
Direct callers:
  - fs/splice.c:iter_file_splice_write
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff812adec0-ffffffff812adee3: vfs_iter_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t vfs_iter_write(struct file *file, struct iov_iter *iter, loff_t *ppos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812cab50)
Location: fs/read_write.c:1004
Inline: False
Direct callers:
  - fs/splice.c:iter_file_splice_write
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff812cab50-ffffffff812cab73: vfs_iter_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t vfs_iter_write(struct file *file, struct iov_iter *iter, loff_t *ppos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812dc570)
Location: fs/read_write.c:1004
Inline: False
Direct callers:
  - fs/splice.c:iter_file_splice_write
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff812dc570-ffffffff812dc593: vfs_iter_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t vfs_iter_write(struct file *file, struct iov_iter *iter, loff_t *ppos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81313340)
Location: fs/read_write.c:1088
Inline: False
Direct callers:
  - fs/splice.c:iter_file_splice_write
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff81313340-ffffffff81313363: vfs_iter_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t vfs_iter_write(struct file *file, struct iov_iter *iter, loff_t *ppos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8131ec60)
Location: fs/read_write.c:904
Inline: False
Direct callers:
  - fs/splice.c:iter_file_splice_write
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff8131ec60-ffffffff8131ec83: vfs_iter_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t vfs_iter_write(struct file *file, struct iov_iter *iter, loff_t *ppos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813246a0)
Location: fs/read_write.c:902
Inline: False
Direct callers:
  - fs/splice.c:iter_file_splice_write
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff813246a0-ffffffff813246c3: vfs_iter_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t vfs_iter_write(struct file *file, struct iov_iter *iter, loff_t *ppos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813722e0)
Location: fs/read_write.c:893
Inline: False
Direct callers:
  - fs/splice.c:iter_file_splice_write
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff813722e0-ffffffff81372303: vfs_iter_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t vfs_iter_write(struct file *file, struct iov_iter *iter, loff_t *ppos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813f0390)
Location: fs/read_write.c:904
Inline: False
Direct callers:
  - fs/splice.c:iter_file_splice_write
```
**Symbols:**

```
ffffffff813f0390-ffffffff813f03cb: vfs_iter_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t vfs_iter_write(struct file *file, struct iov_iter *iter, loff_t *ppos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81478720)
Location: fs/read_write.c:897
Inline: False
Direct callers:
  - fs/splice.c:iter_file_splice_write
```
**Symbols:**

```
ffffffff81478720-ffffffff8147875b: vfs_iter_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t vfs_iter_write(struct file *file, struct iov_iter *iter, loff_t *ppos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814ad170)
Location: fs/read_write.c:896
Inline: False
Direct callers:
  - fs/splice.c:iter_file_splice_write
```
**Symbols:**

```
ffffffff814ad170-ffffffff814ad1ae: vfs_iter_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t vfs_iter_write(struct file *file, struct iov_iter *iter, loff_t *ppos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814de790)
Location: fs/read_write.c:873
Inline: False
```
**Symbols:**

```
ffffffff814de790-ffffffff814de9b4: vfs_iter_write (STB_GLOBAL)
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
ssize_t vfs_iter_write(struct file *file, struct iov_iter *iter, loff_t *ppos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffff800010381f50)
Location: fs/read_write.c:1004
Inline: False
Direct callers:
  - fs/splice.c:iter_file_splice_write
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffff800010381f50-ffff800010381fb0: vfs_iter_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t vfs_iter_write(struct file *file, struct iov_iter *iter, loff_t *ppos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c056c354)
Location: fs/read_write.c:1004
Inline: False
Direct callers:
  - fs/splice.c:iter_file_splice_write
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
c056c354-c056c388: vfs_iter_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t vfs_iter_write(struct file *file, struct iov_iter *iter, loff_t *ppos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c000000000478570)
Location: fs/read_write.c:1004
Inline: False
Direct callers:
  - fs/splice.c:iter_file_splice_write
  - drivers/block/loop.c:lo_write_bvec
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
c000000000478570-c00000000047859c: vfs_iter_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t vfs_iter_write(struct file *file, struct iov_iter *iter, loff_t *ppos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffe000256a82)
Location: fs/read_write.c:1004
Inline: False
Direct callers:
  - fs/splice.c:iter_file_splice_write
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffe000256a82-ffffffe000256ace: vfs_iter_write (STB_GLOBAL)
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
ssize_t vfs_iter_write(struct file *file, struct iov_iter *iter, loff_t *ppos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d4b50)
Location: fs/read_write.c:1004
Inline: False
Direct callers:
  - fs/splice.c:iter_file_splice_write
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff812d4b50-ffffffff812d4b73: vfs_iter_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t vfs_iter_write(struct file *file, struct iov_iter *iter, loff_t *ppos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c57d0)
Location: fs/read_write.c:1004
Inline: False
Direct callers:
  - fs/splice.c:iter_file_splice_write
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff812c57d0-ffffffff812c57f3: vfs_iter_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t vfs_iter_write(struct file *file, struct iov_iter *iter, loff_t *ppos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d2960)
Location: fs/read_write.c:1004
Inline: False
Direct callers:
  - fs/splice.c:iter_file_splice_write
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff812d2960-ffffffff812d2983: vfs_iter_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t vfs_iter_write(struct file *file, struct iov_iter *iter, loff_t *ppos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812e37c0)
Location: fs/read_write.c:1004
Inline: False
Direct callers:
  - fs/splice.c:iter_file_splice_write
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff812e37c0-ffffffff812e37e3: vfs_iter_write (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int flags</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int flags</code> ➡️ <code>rwf_t flags</code>
</li>
</ul>
</details>
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
