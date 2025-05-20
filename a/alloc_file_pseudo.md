# Function: <code>alloc_file_pseudo</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct file *alloc_file_pseudo(struct inode *inode, struct vfsmount *mnt, const char *name, int flags, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812b0ce0)
Location: fs/file_table.c:214
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - fs/aio.c:aio_setup_ring
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff812b0ce0-ffffffff812b0dda: alloc_file_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct file *alloc_file_pseudo(struct inode *inode, struct vfsmount *mnt, const char *name, int flags, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812cd660)
Location: fs/file_table.c:215
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - fs/aio.c:aio_setup_ring
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff812cd660-ffffffff812cd760: alloc_file_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct file *alloc_file_pseudo(struct inode *inode, struct vfsmount *mnt, const char *name, int flags, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812df080)
Location: fs/file_table.c:215
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - fs/aio.c:aio_setup_ring
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff812df080-ffffffff812df180: alloc_file_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct file *alloc_file_pseudo(struct inode *inode, struct vfsmount *mnt, const char *name, int flags, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff81315c20)
Location: fs/file_table.c:216
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - fs/aio.c:aio_setup_ring
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff81315c20-ffffffff81315d20: alloc_file_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct file *alloc_file_pseudo(struct inode *inode, struct vfsmount *mnt, const char *name, int flags, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff81321150)
Location: fs/file_table.c:215
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - fs/aio.c:aio_setup_ring
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff81321150-ffffffff81321250: alloc_file_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct file *alloc_file_pseudo(struct inode *inode, struct vfsmount *mnt, const char *name, int flags, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff81327540)
Location: fs/file_table.c:214
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - fs/anon_inodes.c:__anon_inode_getfile
  - fs/aio.c:aio_setup_ring
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff81327540-ffffffff81327637: alloc_file_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct file *alloc_file_pseudo(struct inode *inode, struct vfsmount *mnt, const char *name, int flags, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff81374810)
Location: fs/file_table.c:215
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - fs/anon_inodes.c:__anon_inode_getfile
  - fs/aio.c:aio_setup_ring
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff81374810-ffffffff81374907: alloc_file_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct file *alloc_file_pseudo(struct inode *inode, struct vfsmount *mnt, const char *name, int flags, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff813f3c20)
Location: fs/file_table.c:251
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - fs/anon_inodes.c:__anon_inode_getfile
  - fs/aio.c:aio_setup_ring
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff813f3c20-ffffffff813f3d34: alloc_file_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct file *alloc_file_pseudo(struct inode *inode, struct vfsmount *mnt, const char *name, int flags, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff8147cad0)
Location: fs/file_table.c:254
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - fs/anon_inodes.c:__anon_inode_getfile
  - fs/aio.c:aio_setup_ring
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff8147cad0-ffffffff8147cbe4: alloc_file_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct file *alloc_file_pseudo(struct inode *inode, struct vfsmount *mnt, const char *name, int flags, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff814b1770)
Location: fs/file_table.c:318
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - fs/anon_inodes.c:__anon_inode_getfile
  - fs/aio.c:aio_setup_ring
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff814b1770-ffffffff814b1884: alloc_file_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct file *alloc_file_pseudo(struct inode *inode, struct vfsmount *mnt, const char *name, int flags, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff814e2f40)
Location: fs/file_table.c:315
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - fs/anon_inodes.c:__anon_inode_getfile
  - fs/aio.c:aio_setup_ring
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff814e2f40-ffffffff814e3031: alloc_file_pseudo (STB_GLOBAL)
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
struct file *alloc_file_pseudo(struct inode *inode, struct vfsmount *mnt, const char *name, int flags, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffff800010385898)
Location: fs/file_table.c:215
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - fs/aio.c:aio_setup_ring
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffff800010385898-ffff8000103859a4: alloc_file_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct file *alloc_file_pseudo(struct inode *inode, struct vfsmount *mnt, const char *name, int flags, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (c056e690)
Location: fs/file_table.c:215
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - fs/aio.c:aio_setup_ring
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
c056e690-c056e7a8: alloc_file_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct file *alloc_file_pseudo(struct inode *inode, struct vfsmount *mnt, const char *name, int flags, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (c00000000047b9b0)
Location: fs/file_table.c:215
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - fs/aio.c:aio_setup_ring
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - net/socket.c:sock_alloc_file
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
c00000000047b9b0-c00000000047bb34: alloc_file_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct file *alloc_file_pseudo(struct inode *inode, struct vfsmount *mnt, const char *name, int flags, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffe000258532)
Location: fs/file_table.c:215
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - fs/aio.c:aio_setup_ring
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffe000258532-ffffffe000258608: alloc_file_pseudo (STB_GLOBAL)
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
struct file *alloc_file_pseudo(struct inode *inode, struct vfsmount *mnt, const char *name, int flags, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812d7660)
Location: fs/file_table.c:215
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - fs/aio.c:aio_setup_ring
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff812d7660-ffffffff812d7760: alloc_file_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct file *alloc_file_pseudo(struct inode *inode, struct vfsmount *mnt, const char *name, int flags, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812c82e0)
Location: fs/file_table.c:215
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - fs/aio.c:aio_setup_ring
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff812c82e0-ffffffff812c83e0: alloc_file_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct file *alloc_file_pseudo(struct inode *inode, struct vfsmount *mnt, const char *name, int flags, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812d5470)
Location: fs/file_table.c:215
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - fs/aio.c:aio_setup_ring
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff812d5470-ffffffff812d5570: alloc_file_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct file *alloc_file_pseudo(struct inode *inode, struct vfsmount *mnt, const char *name, int flags, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812e62c0)
Location: fs/file_table.c:215
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - fs/aio.c:aio_setup_ring
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff812e62c0-ffffffff812e63c0: alloc_file_pseudo (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
