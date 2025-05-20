# Function: <code>do_iter_write</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t do_iter_write(struct file *file, struct iov_iter *iter, loff_t *pos, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81251480)
Location: fs/read_write.c:934
Inline: True
Direct callers:
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_iter_write
```
**Symbols:**

```
ffffffff81251480-ffffffff8125160c: do_iter_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t do_iter_write(struct file *file, struct iov_iter *iter, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81272de0)
Location: fs/read_write.c:939
Inline: True
Direct callers:
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_iter_write
```
**Symbols:**

```
ffffffff81272de0-ffffffff81272f72: do_iter_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
ssize_t do_iter_write(struct file *file, struct iov_iter *iter, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81298ea0)
Location: fs/read_write.c:966
Inline: True
Direct callers:
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_iter_write
```
**Symbols:**

```
ffffffff81298ea0-ffffffff81299032: do_iter_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
ssize_t do_iter_write(struct file *file, struct iov_iter *iter, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812add20)
Location: fs/read_write.c:963
Inline: True
Direct callers:
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_iter_write
```
**Symbols:**

```
ffffffff812add20-ffffffff812adeb6: do_iter_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
ssize_t do_iter_write(struct file *file, struct iov_iter *iter, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812ca9b0)
Location: fs/read_write.c:977
Inline: True
Direct callers:
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_iter_write
```
**Symbols:**

```
ffffffff812ca9b0-ffffffff812cab48: do_iter_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
ssize_t do_iter_write(struct file *file, struct iov_iter *iter, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812dc3d0)
Location: fs/read_write.c:977
Inline: True
Direct callers:
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_iter_write
```
**Symbols:**

```
ffffffff812dc3d0-ffffffff812dc568: do_iter_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t do_iter_write(struct file *file, struct iov_iter *iter, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81313200)
Location: fs/read_write.c:1033
Inline: False
Direct callers:
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_iter_write
```
**Symbols:**

```
ffffffff81313200-ffffffff81313338: do_iter_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t do_iter_write(struct file *file, struct iov_iter *iter, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8131eb20)
Location: fs/read_write.c:849
Inline: False
Direct callers:
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_iter_write
```
**Symbols:**

```
ffffffff8131eb20-ffffffff8131ec5e: do_iter_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t do_iter_write(struct file *file, struct iov_iter *iter, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81324560)
Location: fs/read_write.c:847
Inline: False
Direct callers:
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_iter_write
```
**Symbols:**

```
ffffffff81324560-ffffffff8132469e: do_iter_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t do_iter_write(struct file *file, struct iov_iter *iter, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81372190)
Location: fs/read_write.c:838
Inline: False
Direct callers:
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_iter_write
```
**Symbols:**

```
ffffffff81372190-ffffffff813722de: do_iter_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t do_iter_write(struct file *file, struct iov_iter *iter, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813f0220)
Location: fs/read_write.c:849
Inline: False
Direct callers:
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_iter_write
```
**Symbols:**

```
ffffffff813f0220-ffffffff813f0384: do_iter_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t do_iter_write(struct file *file, struct iov_iter *iter, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814785a0)
Location: fs/read_write.c:842
Inline: False
Direct callers:
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_iter_write
```
**Symbols:**

```
ffffffff814785a0-ffffffff81478704: do_iter_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t do_iter_write(struct file *file, struct iov_iter *iter, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814acfc0)
Location: fs/read_write.c:841
Inline: False
Direct callers:
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_iter_write
```
**Symbols:**

```
ffffffff814acfc0-ffffffff814ad152: do_iter_write (STB_LOCAL)
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
ssize_t do_iter_write(struct file *file, struct iov_iter *iter, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffff800010381db0)
Location: fs/read_write.c:977
Inline: True
Direct callers:
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_iter_write
```
**Symbols:**

```
ffff800010381db0-ffff800010381f50: do_iter_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
ssize_t do_iter_write(struct file *file, struct iov_iter *iter, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c056c1ac)
Location: fs/read_write.c:977
Inline: True
Direct callers:
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_iter_write
```
**Symbols:**

```
c056c1ac-c056c354: do_iter_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
ssize_t do_iter_write(struct file *file, struct iov_iter *iter, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c0000000004782f0)
Location: fs/read_write.c:977
Inline: True
Direct callers:
  - fs/read_write.c:compat_writev
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_iter_write
```
**Symbols:**

```
c0000000004782f0-c000000000478564: do_iter_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
ssize_t do_iter_write(struct file *file, struct iov_iter *iter, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffe000256944)
Location: fs/read_write.c:977
Inline: True
Direct callers:
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_iter_write
```
**Symbols:**

```
ffffffe000256944-ffffffe000256a82: do_iter_write (STB_LOCAL)
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
ssize_t do_iter_write(struct file *file, struct iov_iter *iter, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d49b0)
Location: fs/read_write.c:977
Inline: True
Direct callers:
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_iter_write
```
**Symbols:**

```
ffffffff812d49b0-ffffffff812d4b48: do_iter_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
ssize_t do_iter_write(struct file *file, struct iov_iter *iter, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c5630)
Location: fs/read_write.c:977
Inline: True
Direct callers:
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_iter_write
```
**Symbols:**

```
ffffffff812c5630-ffffffff812c57c8: do_iter_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
ssize_t do_iter_write(struct file *file, struct iov_iter *iter, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d27c0)
Location: fs/read_write.c:977
Inline: True
Direct callers:
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_iter_write
```
**Symbols:**

```
ffffffff812d27c0-ffffffff812d2958: do_iter_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
ssize_t do_iter_write(struct file *file, struct iov_iter *iter, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812e3620)
Location: fs/read_write.c:977
Inline: True
Direct callers:
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_iter_write
```
**Symbols:**

```
ffffffff812e3620-ffffffff812e37b8: do_iter_write (STB_LOCAL)
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
