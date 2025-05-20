# Function: <code>do_iter_read</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t do_iter_read(struct file *file, struct iov_iter *iter, loff_t *pos, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81250dd0)
Location: fs/read_write.c:897
Inline: False
Direct callers:
  - fs/read_write.c:compat_readv
  - fs/read_write.c:vfs_readv
  - fs/read_write.c:vfs_iter_read
```
**Symbols:**

```
ffffffff81250dd0-ffffffff81250f4a: do_iter_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t do_iter_read(struct file *file, struct iov_iter *iter, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812729d0)
Location: fs/read_write.c:902
Inline: False
Direct callers:
  - fs/read_write.c:compat_readv
  - fs/read_write.c:vfs_readv
  - fs/read_write.c:vfs_iter_read
```
**Symbols:**

```
ffffffff812729d0-ffffffff81272b50: do_iter_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t do_iter_read(struct file *file, struct iov_iter *iter, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812988b0)
Location: fs/read_write.c:929
Inline: False
Direct callers:
  - fs/read_write.c:compat_readv
  - fs/read_write.c:vfs_readv
  - fs/read_write.c:vfs_iter_read
```
**Symbols:**

```
ffffffff812988b0-ffffffff81298a3a: do_iter_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t do_iter_read(struct file *file, struct iov_iter *iter, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812ad730)
Location: fs/read_write.c:926
Inline: False
Direct callers:
  - fs/read_write.c:compat_readv
  - fs/read_write.c:vfs_readv
  - fs/read_write.c:vfs_iter_read
```
**Symbols:**

```
ffffffff812ad730-ffffffff812ad8bb: do_iter_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t do_iter_read(struct file *file, struct iov_iter *iter, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812ca3b0)
Location: fs/read_write.c:940
Inline: False
Direct callers:
  - fs/read_write.c:compat_readv
  - fs/read_write.c:vfs_readv
  - fs/read_write.c:vfs_iter_read
```
**Symbols:**

```
ffffffff812ca3b0-ffffffff812ca54a: do_iter_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t do_iter_read(struct file *file, struct iov_iter *iter, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812dbdd0)
Location: fs/read_write.c:940
Inline: False
Direct callers:
  - fs/read_write.c:compat_readv
  - fs/read_write.c:vfs_readv
  - fs/read_write.c:vfs_iter_read
```
**Symbols:**

```
ffffffff812dbdd0-ffffffff812dbf6a: do_iter_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t do_iter_read(struct file *file, struct iov_iter *iter, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81312a20)
Location: fs/read_write.c:968
Inline: False
Direct callers:
  - fs/read_write.c:compat_readv
  - fs/read_write.c:vfs_readv
  - fs/read_write.c:vfs_iter_read
```
**Symbols:**

```
ffffffff81312a20-ffffffff81312b4c: do_iter_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t do_iter_read(struct file *file, struct iov_iter *iter, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8131e0d0)
Location: fs/read_write.c:784
Inline: False
Direct callers:
  - fs/read_write.c:vfs_readv
  - fs/read_write.c:vfs_iter_read
```
**Symbols:**

```
ffffffff8131e0d0-ffffffff8131e219: do_iter_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t do_iter_read(struct file *file, struct iov_iter *iter, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81323b10)
Location: fs/read_write.c:782
Inline: False
Direct callers:
  - fs/read_write.c:vfs_readv
  - fs/read_write.c:vfs_iter_read
```
**Symbols:**

```
ffffffff81323b10-ffffffff81323c59: do_iter_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t do_iter_read(struct file *file, struct iov_iter *iter, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81371720)
Location: fs/read_write.c:773
Inline: False
Direct callers:
  - fs/read_write.c:vfs_readv
  - fs/read_write.c:vfs_iter_read
```
**Symbols:**

```
ffffffff81371720-ffffffff81371879: do_iter_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t do_iter_read(struct file *file, struct iov_iter *iter, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813ef710)
Location: fs/read_write.c:784
Inline: False
Direct callers:
  - fs/read_write.c:vfs_readv
  - fs/read_write.c:vfs_iter_read
```
**Symbols:**

```
ffffffff813ef710-ffffffff813ef878: do_iter_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t do_iter_read(struct file *file, struct iov_iter *iter, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81477cc0)
Location: fs/read_write.c:777
Inline: False
Direct callers:
  - fs/read_write.c:vfs_readv
  - fs/read_write.c:vfs_iter_read
```
**Symbols:**

```
ffffffff81477cc0-ffffffff81477e28: do_iter_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t do_iter_read(struct file *file, struct iov_iter *iter, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814ac210)
Location: fs/read_write.c:776
Inline: False
Direct callers:
  - fs/read_write.c:vfs_readv
  - fs/read_write.c:vfs_iter_read
```
**Symbols:**

```
ffffffff814ac210-ffffffff814ac3b4: do_iter_read (STB_LOCAL)
```
</details>
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
ssize_t do_iter_read(struct file *file, struct iov_iter *iter, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffff800010381828)
Location: fs/read_write.c:940
Inline: False
Direct callers:
  - fs/read_write.c:compat_readv
  - fs/read_write.c:vfs_readv
  - fs/read_write.c:vfs_iter_read
```
**Symbols:**

```
ffff800010381828-ffff8000103819dc: do_iter_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t do_iter_read(struct file *file, struct iov_iter *iter, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c056bfc8)
Location: fs/read_write.c:940
Inline: False
Direct callers:
  - fs/read_write.c:vfs_readv
  - fs/read_write.c:vfs_iter_read
```
**Symbols:**

```
c056bfc8-c056c178: do_iter_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t do_iter_read(struct file *file, struct iov_iter *iter, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c000000000477c30)
Location: fs/read_write.c:940
Inline: False
Direct callers:
  - fs/read_write.c:compat_readv
  - fs/read_write.c:vfs_readv
  - fs/read_write.c:vfs_iter_read
```
**Symbols:**

```
c000000000477c30-c000000000477efc: do_iter_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t do_iter_read(struct file *file, struct iov_iter *iter, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffe0002567a4)
Location: fs/read_write.c:940
Inline: False
Direct callers:
  - fs/read_write.c:vfs_readv
  - fs/read_write.c:vfs_iter_read
```
**Symbols:**

```
ffffffe0002567a4-ffffffe0002568f8: do_iter_read (STB_LOCAL)
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
ssize_t do_iter_read(struct file *file, struct iov_iter *iter, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d43b0)
Location: fs/read_write.c:940
Inline: False
Direct callers:
  - fs/read_write.c:compat_readv
  - fs/read_write.c:vfs_readv
  - fs/read_write.c:vfs_iter_read
```
**Symbols:**

```
ffffffff812d43b0-ffffffff812d454a: do_iter_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t do_iter_read(struct file *file, struct iov_iter *iter, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c5030)
Location: fs/read_write.c:940
Inline: False
Direct callers:
  - fs/read_write.c:compat_readv
  - fs/read_write.c:vfs_readv
  - fs/read_write.c:vfs_iter_read
```
**Symbols:**

```
ffffffff812c5030-ffffffff812c51ca: do_iter_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t do_iter_read(struct file *file, struct iov_iter *iter, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d21c0)
Location: fs/read_write.c:940
Inline: False
Direct callers:
  - fs/read_write.c:compat_readv
  - fs/read_write.c:vfs_readv
  - fs/read_write.c:vfs_iter_read
```
**Symbols:**

```
ffffffff812d21c0-ffffffff812d235a: do_iter_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t do_iter_read(struct file *file, struct iov_iter *iter, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812e3020)
Location: fs/read_write.c:940
Inline: False
Direct callers:
  - fs/read_write.c:compat_readv
  - fs/read_write.c:vfs_readv
  - fs/read_write.c:vfs_iter_read
```
**Symbols:**

```
ffffffff812e3020-ffffffff812e31ba: do_iter_read (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
