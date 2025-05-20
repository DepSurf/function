# Function: <code>file_open_root</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct file *file_open_root(struct dentry *dentry, struct vfsmount *mnt, const char *filename, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8120a540)
Location: fs/open.c:1002
Inline: False
Direct callers:
  - kernel/sysctl_binary.c:do_sysctl
  - fs/fhandle.c:do_handle_open
```
**Symbols:**

```
ffffffff8120a540-ffffffff8120a6ba: file_open_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct file *file_open_root(struct dentry *dentry, struct vfsmount *mnt, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81230210)
Location: fs/open.c:995
Inline: False
Direct callers:
  - kernel/sysctl_binary.c:do_sysctl
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:do_handle_open
```
**Symbols:**

```
ffffffff81230210-ffffffff81230364: file_open_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct file *file_open_root(struct dentry *dentry, struct vfsmount *mnt, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812427c0)
Location: fs/open.c:1012
Inline: False
Direct callers:
  - kernel/sysctl_binary.c:do_sysctl
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:do_handle_open
```
**Symbols:**

```
ffffffff812427c0-ffffffff81242914: file_open_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct file *file_open_root(struct dentry *dentry, struct vfsmount *mnt, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8124deb0)
Location: fs/open.c:1018
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:do_handle_open
```
**Symbols:**

```
ffffffff8124deb0-ffffffff8124e043: file_open_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct file *file_open_root(struct dentry *dentry, struct vfsmount *mnt, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8126fe30)
Location: fs/open.c:1018
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:do_handle_open
```
**Symbols:**

```
ffffffff8126fe30-ffffffff8126ffc3: file_open_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct file *file_open_root(struct dentry *dentry, struct vfsmount *mnt, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81295b50)
Location: fs/open.c:1060
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:do_handle_open
```
**Symbols:**

```
ffffffff81295b50-ffffffff81295c9d: file_open_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct file *file_open_root(struct dentry *dentry, struct vfsmount *mnt, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812aa940)
Location: fs/open.c:1047
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:do_handle_open
```
**Symbols:**

```
ffffffff812aa940-ffffffff812aaa8d: file_open_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct file *file_open_root(struct dentry *dentry, struct vfsmount *mnt, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c7110)
Location: fs/open.c:1067
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:do_handle_open
```
**Symbols:**

```
ffffffff812c7110-ffffffff812c7264: file_open_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct file *file_open_root(struct dentry *dentry, struct vfsmount *mnt, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d8b20)
Location: fs/open.c:1072
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:do_handle_open
```
**Symbols:**

```
ffffffff812d8b20-ffffffff812d8c74: file_open_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct file *file_open_root(struct dentry *dentry, struct vfsmount *mnt, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8130e930)
Location: fs/open.c:1152
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file_from_path_initns
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:do_handle_open
  - fs/proc/proc_sysctl.c:process_sysctl_arg
```
**Symbols:**

```
ffffffff8130e930-ffffffff8130eab8: file_open_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct file *file_open_root(struct dentry *dentry, struct vfsmount *mnt, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8131ac00)
Location: fs/open.c:1145
Inline: False
Direct callers:
  - kernel/usermode_driver.c:blob_to_mnt
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:do_handle_open
  - fs/proc/proc_sysctl.c:process_sysctl_arg
```
**Symbols:**

```
ffffffff8131ac00-ffffffff8131ad88: file_open_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct file *file_open_root(struct dentry *dentry, struct vfsmount *mnt, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff813209e0)
Location: fs/open.c:1167
Inline: False
Direct callers:
  - kernel/usermode_driver.c:umd_load_blob
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:do_handle_open
  - fs/proc/proc_sysctl.c:process_sysctl_arg
```
**Symbols:**

```
ffffffff813209e0-ffffffff81320b86: file_open_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct file *file_open_root(const struct path *root, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8136e270)
Location: fs/open.c:1185
Inline: False
Direct callers:
  - kernel/usermode_driver.c:umd_load_blob
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:do_handle_open
  - fs/proc/proc_sysctl.c:process_sysctl_arg
```
**Symbols:**

```
ffffffff8136e270-ffffffff8136e40e: file_open_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct file *file_open_root(const struct path *root, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff813ec5c0)
Location: fs/open.c:1250
Inline: False
Direct callers:
  - kernel/usermode_driver.c:umd_load_blob
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:do_handle_open
  - fs/proc/proc_sysctl.c:process_sysctl_arg
```
**Symbols:**

```
ffffffff813ec5c0-ffffffff813ec782: file_open_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct file *file_open_root(const struct path *root, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81474ae0)
Location: fs/open.c:1282
Inline: False
Direct callers:
  - kernel/usermode_driver.c:umd_load_blob
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:do_handle_open
  - fs/proc/proc_sysctl.c:process_sysctl_arg
```
**Symbols:**

```
ffffffff81474ae0-ffffffff81474ca2: file_open_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct file *file_open_root(const struct path *root, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814a94b0)
Location: fs/open.c:1379
Inline: False
Direct callers:
  - kernel/usermode_driver.c:umd_load_blob
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:do_handle_open
  - fs/proc/proc_sysctl.c:process_sysctl_arg
```
**Symbols:**

```
ffffffff814a94b0-ffffffff814a9638: file_open_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct file *file_open_root(const struct path *root, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814da510)
Location: fs/open.c:1376
Inline: False
Direct callers:
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:do_handle_open
  - fs/proc/proc_sysctl.c:process_sysctl_arg
```
**Symbols:**

```
ffffffff814da510-ffffffff814da698: file_open_root (STB_GLOBAL)
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
struct file *file_open_root(struct dentry *dentry, struct vfsmount *mnt, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffff80001037d5e0)
Location: fs/open.c:1072
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:do_handle_open
```
**Symbols:**

```
ffff80001037d5e0-ffff80001037d744: file_open_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct file *file_open_root(struct dentry *dentry, struct vfsmount *mnt, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c05687c8)
Location: fs/open.c:1072
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:__se_sys_open_by_handle_at
```
**Symbols:**

```
c05687c8-c0568914: file_open_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct file *file_open_root(struct dentry *dentry, struct vfsmount *mnt, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c0000000004737e0)
Location: fs/open.c:1072
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:do_handle_open
```
**Symbols:**

```
c0000000004737e0-c0000000004739d8: file_open_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct file *file_open_root(struct dentry *dentry, struct vfsmount *mnt, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffe000253c0e)
Location: fs/open.c:1072
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:__se_sys_open_by_handle_at
```
**Symbols:**

```
ffffffe000253c0e-ffffffe000253d4a: file_open_root (STB_GLOBAL)
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
struct file *file_open_root(struct dentry *dentry, struct vfsmount *mnt, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d1100)
Location: fs/open.c:1072
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:do_handle_open
```
**Symbols:**

```
ffffffff812d1100-ffffffff812d1254: file_open_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct file *file_open_root(struct dentry *dentry, struct vfsmount *mnt, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c1d80)
Location: fs/open.c:1072
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:do_handle_open
```
**Symbols:**

```
ffffffff812c1d80-ffffffff812c1ed4: file_open_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct file *file_open_root(struct dentry *dentry, struct vfsmount *mnt, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812cef10)
Location: fs/open.c:1072
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:do_handle_open
```
**Symbols:**

```
ffffffff812cef10-ffffffff812cf064: file_open_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct file *file_open_root(struct dentry *dentry, struct vfsmount *mnt, const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812dfd20)
Location: fs/open.c:1072
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
  - fs/fhandle.c:do_handle_open
```
**Symbols:**

```
ffffffff812dfd20-ffffffff812dfe74: file_open_root (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>umode_t mode</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct path *root</code>
</li>
<li>
<b>Param removed. </b>
<code>struct dentry *dentry</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vfsmount *mnt</code>
</li>
<li>
<b>Param reordered. </b>
<code>dentry, mnt, filename, flags, mode</code> ➡️ <code>root, filename, flags, mode</code>
</li>
</ul>
</details>
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
