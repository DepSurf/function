# Function: <code>fuse_file_open</code>

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
struct fuse_file *fuse_file_open(struct fuse_mount *fm, u64 nodeid, unsigned int open_flags, bool isdir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81498860)
Location: fs/fuse/file.c:127
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/ioctl.c:fuse_fileattr_set
  - fs/fuse/ioctl.c:fuse_fileattr_get
```
**Symbols:**

```
ffffffff81498860-ffffffff814989d5: fuse_file_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct fuse_file *fuse_file_open(struct fuse_mount *fm, u64 nodeid, unsigned int open_flags, bool isdir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814f0300)
Location: fs/fuse/file.c:127
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/ioctl.c:fuse_fileattr_set
  - fs/fuse/ioctl.c:fuse_fileattr_get
```
**Symbols:**

```
ffffffff814f0300-ffffffff814f0475: fuse_file_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct fuse_file *fuse_file_open(struct fuse_mount *fm, u64 nodeid, unsigned int open_flags, bool isdir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8157fa90)
Location: fs/fuse/file.c:127
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/ioctl.c:fuse_fileattr_set
  - fs/fuse/ioctl.c:fuse_fileattr_get
```
**Symbols:**

```
ffffffff8157fa90-ffffffff8157fc28: fuse_file_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct fuse_file *fuse_file_open(struct fuse_mount *fm, u64 nodeid, unsigned int open_flags, bool isdir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff816257a0)
Location: fs/fuse/file.c:127
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/ioctl.c:fuse_priv_ioctl_prepare
```
**Symbols:**

```
ffffffff816257a0-ffffffff81625938: fuse_file_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct fuse_file *fuse_file_open(struct fuse_mount *fm, u64 nodeid, unsigned int open_flags, bool isdir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8165db30)
Location: fs/fuse/file.c:128
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/ioctl.c:fuse_priv_ioctl_prepare
```
**Symbols:**

```
ffffffff8165db30-ffffffff8165dcc8: fuse_file_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct fuse_file *fuse_file_open(struct fuse_mount *fm, u64 nodeid, unsigned int open_flags, bool isdir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81697870)
Location: fs/fuse/file.c:129
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/ioctl.c:fuse_priv_ioctl_prepare
```
**Symbols:**

```
ffffffff81697870-ffffffff81697a08: fuse_file_open (STB_GLOBAL)
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
