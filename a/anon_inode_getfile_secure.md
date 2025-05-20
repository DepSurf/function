# Function: <code>anon_inode_getfile_secure</code>

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
In <code>5.3</code>: Absent ⚠️
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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct file *anon_inode_getfile_secure(const char *name, const struct file_operations *fops, void *priv, int flags, const struct inode *context_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff8145a450)
Location: fs/anon_inodes.c:171
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_create
```
**Symbols:**

```
ffffffff8145a450-ffffffff8145a478: anon_inode_getfile_secure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct file *anon_inode_getfile_secure(const char *name, const struct file_operations *fops, void *priv, int flags, const struct inode *context_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff814e9950)
Location: fs/anon_inodes.c:171
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_create
```
**Symbols:**

```
ffffffff814e9950-ffffffff814e9978: anon_inode_getfile_secure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct file *anon_inode_getfile_secure(const char *name, const struct file_operations *fops, void *priv, int flags, const struct inode *context_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff815206f0)
Location: fs/anon_inodes.c:171
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_create
```
**Symbols:**

```
ffffffff815206f0-ffffffff81520718: anon_inode_getfile_secure (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
