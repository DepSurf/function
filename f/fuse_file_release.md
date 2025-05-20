# Function: <code>fuse_file_release</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fuse_file_release(struct inode *inode, struct fuse_file *ff, unsigned int open_flags, fl_owner_t id, bool isdir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81498da0)
Location: fs/fuse/file.c:298
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_release
  - fs/fuse/ioctl.c:fuse_fileattr_set
  - fs/fuse/ioctl.c:fuse_fileattr_get
```
**Symbols:**

```
ffffffff81498da0-ffffffff81498e33: fuse_file_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fuse_file_release(struct inode *inode, struct fuse_file *ff, unsigned int open_flags, fl_owner_t id, bool isdir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814f0830)
Location: fs/fuse/file.c:301
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_release
  - fs/fuse/ioctl.c:fuse_fileattr_set
  - fs/fuse/ioctl.c:fuse_fileattr_get
```
**Symbols:**

```
ffffffff814f0830-ffffffff814f08c3: fuse_file_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fuse_file_release(struct inode *inode, struct fuse_file *ff, unsigned int open_flags, fl_owner_t id, bool isdir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81580070)
Location: fs/fuse/file.c:304
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_release
  - fs/fuse/ioctl.c:fuse_fileattr_set
  - fs/fuse/ioctl.c:fuse_fileattr_get
```
**Symbols:**

```
ffffffff81580070-ffffffff81580111: fuse_file_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fuse_file_release(struct inode *inode, struct fuse_file *ff, unsigned int open_flags, fl_owner_t id, bool isdir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81625de0)
Location: fs/fuse/file.c:304
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_release
  - fs/fuse/ioctl.c:fuse_fileattr_set
  - fs/fuse/ioctl.c:fuse_fileattr_get
```
**Symbols:**

```
ffffffff81625de0-ffffffff81625e81: fuse_file_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fuse_file_release(struct inode *inode, struct fuse_file *ff, unsigned int open_flags, fl_owner_t id, bool isdir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8165e1d0)
Location: fs/fuse/file.c:305
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_release
  - fs/fuse/ioctl.c:fuse_fileattr_set
  - fs/fuse/ioctl.c:fuse_fileattr_get
```
**Symbols:**

```
ffffffff8165e1d0-ffffffff8165e271: fuse_file_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fuse_file_release(struct inode *inode, struct fuse_file *ff, unsigned int open_flags, fl_owner_t id, bool isdir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81697f10)
Location: fs/fuse/file.c:306
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_release
  - fs/fuse/ioctl.c:fuse_fileattr_set
  - fs/fuse/ioctl.c:fuse_fileattr_get
```
**Symbols:**

```
ffffffff81697f10-ffffffff81697fb1: fuse_file_release (STB_GLOBAL)
```
</details>
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
