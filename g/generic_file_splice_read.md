# Function: <code>generic_file_splice_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t generic_file_splice_read(struct file *in, loff_t *ppos, struct pipe_inode_info *pipe, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8123f2a0)
Location: fs/splice.c:520
Inline: False
```
**Symbols:**

```
ffffffff8123f2a0-ffffffff8123f318: generic_file_splice_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t generic_file_splice_read(struct file *in, loff_t *ppos, struct pipe_inode_info *pipe, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812675b0)
Location: fs/splice.c:521
Inline: False
```
**Symbols:**

```
ffffffff812675b0-ffffffff8126763d: generic_file_splice_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t generic_file_splice_read(struct file *in, loff_t *ppos, struct pipe_inode_info *pipe, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81278ff0)
Location: fs/splice.c:298
Inline: False
```
**Symbols:**

```
ffffffff81278ff0-ffffffff81279147: generic_file_splice_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t generic_file_splice_read(struct file *in, loff_t *ppos, struct pipe_inode_info *pipe, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81286550)
Location: fs/splice.c:295
Inline: False
```
**Symbols:**

```
ffffffff81286550-ffffffff812866bb: generic_file_splice_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t generic_file_splice_read(struct file *in, loff_t *ppos, struct pipe_inode_info *pipe, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812a9050)
Location: fs/splice.c:295
Inline: False
```
**Symbols:**

```
ffffffff812a9050-ffffffff812a91c1: generic_file_splice_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t generic_file_splice_read(struct file *in, loff_t *ppos, struct pipe_inode_info *pipe, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812cfb80)
Location: fs/splice.c:296
Inline: False
```
**Symbols:**

```
ffffffff812cfb80-ffffffff812cfd07: generic_file_splice_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t generic_file_splice_read(struct file *in, loff_t *ppos, struct pipe_inode_info *pipe, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812e4f70)
Location: fs/splice.c:296
Inline: False
Direct callers:
  - net/socket.c:sock_splice_read
```
**Symbols:**

```
ffffffff812e4f70-ffffffff812e5118: generic_file_splice_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t generic_file_splice_read(struct file *in, loff_t *ppos, struct pipe_inode_info *pipe, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81303760)
Location: fs/splice.c:295
Inline: False
Direct callers:
  - net/socket.c:sock_splice_read
```
**Symbols:**

```
ffffffff81303760-ffffffff8130391a: generic_file_splice_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t generic_file_splice_read(struct file *in, loff_t *ppos, struct pipe_inode_info *pipe, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff813167e0)
Location: fs/splice.c:295
Inline: False
Direct callers:
  - net/socket.c:sock_splice_read
```
**Symbols:**

```
ffffffff813167e0-ffffffff8131699a: generic_file_splice_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t generic_file_splice_read(struct file *in, loff_t *ppos, struct pipe_inode_info *pipe, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81350450)
Location: fs/splice.c:299
Inline: False
Direct callers:
  - net/socket.c:sock_splice_read
```
**Symbols:**

```
ffffffff81350450-ffffffff813505ee: generic_file_splice_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t generic_file_splice_read(struct file *in, loff_t *ppos, struct pipe_inode_info *pipe, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8135d2f0)
Location: fs/splice.c:298
Inline: False
Direct callers:
  - net/socket.c:sock_splice_read
```
**Symbols:**

```
ffffffff8135d2f0-ffffffff8135d491: generic_file_splice_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t generic_file_splice_read(struct file *in, loff_t *ppos, struct pipe_inode_info *pipe, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81363d50)
Location: fs/splice.c:298
Inline: False
Direct callers:
  - net/socket.c:sock_splice_read
```
**Symbols:**

```
ffffffff81363d50-ffffffff81363eee: generic_file_splice_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t generic_file_splice_read(struct file *in, loff_t *ppos, struct pipe_inode_info *pipe, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff813b2580)
Location: fs/splice.c:298
Inline: False
Direct callers:
  - net/socket.c:sock_splice_read
```
**Symbols:**

```
ffffffff813b2580-ffffffff813b2721: generic_file_splice_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t generic_file_splice_read(struct file *in, loff_t *ppos, struct pipe_inode_info *pipe, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81437580)
Location: fs/splice.c:298
Inline: False
Direct callers:
  - net/socket.c:sock_splice_read
```
**Symbols:**

```
ffffffff81437580-ffffffff81437731: generic_file_splice_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t generic_file_splice_read(struct file *in, loff_t *ppos, struct pipe_inode_info *pipe, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff814c5690)
Location: fs/splice.c:298
Inline: False
Direct callers:
  - net/socket.c:sock_splice_read
```
**Symbols:**

```
ffffffff814c5690-ffffffff814c5834: generic_file_splice_read (STB_GLOBAL)
```
</details>
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
ssize_t generic_file_splice_read(struct file *in, loff_t *ppos, struct pipe_inode_info *pipe, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffff8000103cd148)
Location: fs/splice.c:295
Inline: False
Direct callers:
  - net/socket.c:sock_splice_read
```
**Symbols:**

```
ffff8000103cd148-ffff8000103cd2ec: generic_file_splice_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t generic_file_splice_read(struct file *in, loff_t *ppos, struct pipe_inode_info *pipe, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (c05a8cf0)
Location: fs/splice.c:295
Inline: False
Direct callers:
  - net/socket.c:sock_splice_read
```
**Symbols:**

```
c05a8cf0-c05a8e7c: generic_file_splice_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t generic_file_splice_read(struct file *in, loff_t *ppos, struct pipe_inode_info *pipe, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (c0000000004ceec0)
Location: fs/splice.c:295
Inline: False
Direct callers:
  - net/socket.c:sock_splice_read
```
**Symbols:**

```
c0000000004ceec0-c0000000004cf0e8: generic_file_splice_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t generic_file_splice_read(struct file *in, loff_t *ppos, struct pipe_inode_info *pipe, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffe00028a576)
Location: fs/splice.c:295
Inline: False
Direct callers:
  - net/socket.c:sock_splice_read
```
**Symbols:**

```
ffffffe00028a576-ffffffe00028a6c2: generic_file_splice_read (STB_GLOBAL)
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
ssize_t generic_file_splice_read(struct file *in, loff_t *ppos, struct pipe_inode_info *pipe, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8130edc0)
Location: fs/splice.c:295
Inline: False
Direct callers:
  - net/socket.c:sock_splice_read
```
**Symbols:**

```
ffffffff8130edc0-ffffffff8130ef7a: generic_file_splice_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t generic_file_splice_read(struct file *in, loff_t *ppos, struct pipe_inode_info *pipe, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812ff9d0)
Location: fs/splice.c:295
Inline: False
Direct callers:
  - net/socket.c:sock_splice_read
```
**Symbols:**

```
ffffffff812ff9d0-ffffffff812ffb8a: generic_file_splice_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t generic_file_splice_read(struct file *in, loff_t *ppos, struct pipe_inode_info *pipe, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8130cbb0)
Location: fs/splice.c:295
Inline: False
Direct callers:
  - net/socket.c:sock_splice_read
```
**Symbols:**

```
ffffffff8130cbb0-ffffffff8130cd6a: generic_file_splice_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t generic_file_splice_read(struct file *in, loff_t *ppos, struct pipe_inode_info *pipe, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8131e3c0)
Location: fs/splice.c:295
Inline: False
Direct callers:
  - net/socket.c:sock_splice_read
```
**Symbols:**

```
ffffffff8131e3c0-ffffffff8131e57a: generic_file_splice_read (STB_GLOBAL)
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
