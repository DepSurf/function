# Function: <code>generic_copy_file_range</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
ssize_t generic_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812cbe7a)
Location: fs/read_write.c:1615
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
Direct callers:
  - fs/fuse/file.c:fuse_copy_file_range
```
**Symbols:**

```
ffffffff812c87e0-ffffffff812c8817: generic_copy_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
ssize_t generic_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812dd89a)
Location: fs/read_write.c:1615
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
Direct callers:
  - fs/fuse/file.c:fuse_copy_file_range
```
**Symbols:**

```
ffffffff812da1f0-ffffffff812da227: generic_copy_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t generic_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8131487a)
Location: fs/read_write.c:1699
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
Direct callers:
  - fs/fuse/file.c:fuse_copy_file_range
```
**Symbols:**

```
ffffffff813109e0-ffffffff81310a17: generic_copy_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
ssize_t generic_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81320982)
Location: fs/read_write.c:1384
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
Direct callers:
  - fs/fuse/file.c:fuse_copy_file_range
```
**Symbols:**

```
ffffffff8131ca40-ffffffff8131ca77: generic_copy_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t generic_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81326a13)
Location: fs/read_write.c:1389
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
Direct callers:
  - fs/fuse/file.c:fuse_copy_file_range
```
**Symbols:**

```
ffffffff81322bb0-ffffffff81322be3: generic_copy_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t generic_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81373fb3)
Location: fs/read_write.c:1380
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
Direct callers:
  - fs/fuse/file.c:fuse_copy_file_range
```
**Symbols:**

```
ffffffff813700a0-ffffffff813700d3: generic_copy_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
ssize_t generic_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813f306e)
Location: fs/read_write.c:1394
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
Direct callers:
  - fs/fuse/file.c:fuse_copy_file_range
```
**Symbols:**

```
ffffffff813eeb60-ffffffff813eeba5: generic_copy_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
ssize_t generic_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8147bc51)
Location: fs/read_write.c:1387
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
Direct callers:
  - fs/fuse/file.c:fuse_copy_file_range
```
**Symbols:**

```
ffffffff81477450-ffffffff81477495: generic_copy_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
ssize_t generic_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814b07f4)
Location: fs/read_write.c:1386
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
Direct callers:
  - fs/fuse/file.c:fuse_copy_file_range
```
**Symbols:**

```
ffffffff814abdd0-ffffffff814abe15: generic_copy_file_range (STB_GLOBAL)
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
ssize_t generic_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffff8000103837a0)
Location: fs/read_write.c:1615
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
Direct callers:
  - fs/fuse/file.c:fuse_copy_file_range
```
**Symbols:**

```
ffff80001037f6a8-ffff80001037f704: generic_copy_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
ssize_t generic_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c056cc34)
Location: fs/read_write.c:1615
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
Direct callers:
  - fs/fuse/file.c:fuse_copy_file_range
```
**Symbols:**

```
c0569f40-c0569f90: generic_copy_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
ssize_t generic_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c000000000479b38)
Location: fs/read_write.c:1615
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
Direct callers:
  - fs/fuse/file.c:fuse_copy_file_range
```
**Symbols:**

```
c000000000475550-c0000000004755a8: generic_copy_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
ssize_t generic_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffe0002570f0)
Location: fs/read_write.c:1615
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
Direct callers:
  - fs/fuse/file.c:fuse_copy_file_range
```
**Symbols:**

```
ffffffe000255166-ffffffe0002551be: generic_copy_file_range (STB_GLOBAL)
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
ssize_t generic_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d5e7a)
Location: fs/read_write.c:1615
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
Direct callers:
  - fs/fuse/file.c:fuse_copy_file_range
```
**Symbols:**

```
ffffffff812d27d0-ffffffff812d2807: generic_copy_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
ssize_t generic_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c6afa)
Location: fs/read_write.c:1615
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
Direct callers:
  - fs/fuse/file.c:fuse_copy_file_range
```
**Symbols:**

```
ffffffff812c3450-ffffffff812c3487: generic_copy_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
ssize_t generic_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d3c8a)
Location: fs/read_write.c:1615
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
Direct callers:
  - fs/fuse/file.c:fuse_copy_file_range
```
**Symbols:**

```
ffffffff812d05e0-ffffffff812d0617: generic_copy_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
ssize_t generic_copy_file_range(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812e4aea)
Location: fs/read_write.c:1615
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
Direct callers:
  - fs/fuse/file.c:fuse_copy_file_range
```
**Symbols:**

```
ffffffff812e1410-ffffffff812e1447: generic_copy_file_range (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
