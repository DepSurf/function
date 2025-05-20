# Function: <code>fuse_read_fill</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void fuse_read_fill(struct fuse_req *req, struct file *file, loff_t pos, size_t count, int opcode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8131684c)
Location: fs/fuse/file.c:499
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_direct_io
Direct callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
```
**Symbols:**

```
ffffffff81318850-ffffffff813188bf: fuse_read_fill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void fuse_read_fill(struct fuse_req *req, struct file *file, loff_t pos, size_t count, int opcode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8134c963)
Location: fs/fuse/file.c:513
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_do_readpage
Direct callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
```
**Symbols:**

```
ffffffff8134d290-ffffffff8134d2ff: fuse_read_fill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void fuse_read_fill(struct fuse_req *req, struct file *file, loff_t pos, size_t count, int opcode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81362273)
Location: fs/fuse/file.c:514
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_do_readpage
Direct callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
```
**Symbols:**

```
ffffffff81362ba0-ffffffff81362c0f: fuse_read_fill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void fuse_read_fill(struct fuse_req *req, struct file *file, loff_t pos, size_t count, int opcode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81376c65)
Location: fs/fuse/file.c:509
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_do_readpage
Direct callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
```
**Symbols:**

```
ffffffff81377530-ffffffff8137759f: fuse_read_fill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void fuse_read_fill(struct fuse_req *req, struct file *file, loff_t pos, size_t count, int opcode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8139ba27)
Location: fs/fuse/file.c:509
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_do_readpage
Direct callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
```
**Symbols:**

```
ffffffff8139c2d0-ffffffff8139c33f: fuse_read_fill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void fuse_read_fill(struct fuse_req *req, struct file *file, loff_t pos, size_t count, int opcode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813ca690)
Location: fs/fuse/file.c:509
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_send_read
Direct callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
```
**Symbols:**

```
ffffffff813cb700-ffffffff813cb76f: fuse_read_fill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void fuse_read_fill(struct fuse_req *req, struct file *file, loff_t pos, size_t count, int opcode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813e41e6)
Location: fs/fuse/file.c:514
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_do_readpage
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff813e47b0-ffffffff813e481f: fuse_read_fill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void fuse_read_fill(struct fuse_req *req, struct file *file, loff_t pos, size_t count, int opcode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8140ffdb)
Location: fs/fuse/file.c:526
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_do_readpage
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff81410480-ffffffff814104ef: fuse_read_fill (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
