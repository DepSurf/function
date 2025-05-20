# Function: <code>vfs_tmpfile</code>

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
struct dentry *vfs_tmpfile(struct dentry *dentry, umode_t mode, int open_flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8125cde0)
Location: fs/namei.c:3401
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff8125cde0-ffffffff8125cec6: vfs_tmpfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *vfs_tmpfile(struct dentry *dentry, umode_t mode, int open_flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8127f1f0)
Location: fs/namei.c:3399
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff8127f1f0-ffffffff8127f2e0: vfs_tmpfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *vfs_tmpfile(struct dentry *dentry, umode_t mode, int open_flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812a89d0)
Location: fs/namei.c:3421
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff812a89d0-ffffffff812a8ac9: vfs_tmpfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *vfs_tmpfile(struct dentry *dentry, umode_t mode, int open_flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812bd910)
Location: fs/namei.c:3435
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff812bd910-ffffffff812bda09: vfs_tmpfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *vfs_tmpfile(struct dentry *dentry, umode_t mode, int open_flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812da9a0)
Location: fs/namei.c:3433
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff812da9a0-ffffffff812daaa3: vfs_tmpfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dentry *vfs_tmpfile(struct dentry *dentry, umode_t mode, int open_flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ec4b0)
Location: fs/namei.c:3428
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff812ec4b0-ffffffff812ec5b3: vfs_tmpfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *vfs_tmpfile(struct dentry *dentry, umode_t mode, int open_flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81323c20)
Location: fs/namei.c:3257
Inline: False
Direct callers:
  - fs/namei.c:do_tmpfile
```
**Symbols:**

```
ffffffff81323c20-ffffffff81323d54: vfs_tmpfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *vfs_tmpfile(struct dentry *dentry, umode_t mode, int open_flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8132f220)
Location: fs/namei.c:3259
Inline: False
Direct callers:
  - fs/namei.c:do_tmpfile
```
**Symbols:**

```
ffffffff8132f220-ffffffff8132f354: vfs_tmpfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dentry *vfs_tmpfile(struct user_namespace *mnt_userns, struct dentry *dentry, umode_t mode, int open_flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813358a0)
Location: fs/namei.c:3390
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff813358a0-ffffffff813359b2: vfs_tmpfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dentry *vfs_tmpfile(struct user_namespace *mnt_userns, struct dentry *dentry, umode_t mode, int open_flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813833e0)
Location: fs/namei.c:3457
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff813833e0-ffffffff813834f2: vfs_tmpfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dentry *vfs_tmpfile(struct user_namespace *mnt_userns, struct dentry *dentry, umode_t mode, int open_flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81402500)
Location: fs/namei.c:3551
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff81402500-ffffffff81402644: vfs_tmpfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vfs_tmpfile(struct user_namespace *mnt_userns, const struct path *parentpath, struct file *file, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8148cfa0)
Location: fs/namei.c:3586
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:vfs_tmpfile_open
```
**Symbols:**

```
ffffffff8148cfa0-ffffffff8148d12d: vfs_tmpfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vfs_tmpfile(struct mnt_idmap *idmap, const struct path *parentpath, struct file *file, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c0de0)
Location: fs/namei.c:3665
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:kernel_tmpfile_open
```
**Symbols:**

```
ffffffff814c0de0-ffffffff814c0f79: vfs_tmpfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vfs_tmpfile(struct mnt_idmap *idmap, const struct path *parentpath, struct file *file, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f32a0)
Location: fs/namei.c:3674
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:kernel_tmpfile_open
```
**Symbols:**

```
ffffffff814f32a0-ffffffff814f343f: vfs_tmpfile (STB_LOCAL)
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
struct dentry *vfs_tmpfile(struct dentry *dentry, umode_t mode, int open_flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010395cc8)
Location: fs/namei.c:3428
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffff800010395cc8-ffff800010395e24: vfs_tmpfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *vfs_tmpfile(struct dentry *dentry, umode_t mode, int open_flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c0579da4)
Location: fs/namei.c:3428
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
c0579da4-c0579ea8: vfs_tmpfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *vfs_tmpfile(struct dentry *dentry, umode_t mode, int open_flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c00000000048b340)
Location: fs/namei.c:3428
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
c00000000048b340-c00000000048b4f4: vfs_tmpfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *vfs_tmpfile(struct dentry *dentry, umode_t mode, int open_flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe00026438a)
Location: fs/namei.c:3428
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffe00026438a-ffffffe000264490: vfs_tmpfile (STB_GLOBAL)
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
struct dentry *vfs_tmpfile(struct dentry *dentry, umode_t mode, int open_flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e4a90)
Location: fs/namei.c:3428
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff812e4a90-ffffffff812e4b93: vfs_tmpfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dentry *vfs_tmpfile(struct dentry *dentry, umode_t mode, int open_flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d56d0)
Location: fs/namei.c:3428
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff812d56d0-ffffffff812d57d3: vfs_tmpfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dentry *vfs_tmpfile(struct dentry *dentry, umode_t mode, int open_flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e28a0)
Location: fs/namei.c:3428
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff812e28a0-ffffffff812e29a3: vfs_tmpfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dentry *vfs_tmpfile(struct dentry *dentry, umode_t mode, int open_flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f0ba0)
Location: fs/namei.c:3428
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff812f0ba0-ffffffff812f0ca1: vfs_tmpfile (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
<li>
<b>Param reordered. </b>
<code>dentry, mode, open_flag</code> ➡️ <code>mnt_userns, dentry, mode, open_flag</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct path *parentpath</code>
</li>
<li>
<b>Param added. </b>
<code>struct file *file</code>
</li>
<li>
<b>Param removed. </b>
<code>struct dentry *dentry</code>
</li>
<li>
<b>Param removed. </b>
<code>int open_flag</code>
</li>
<li>
<b>Param reordered. </b>
<code>mnt_userns, dentry, mode, open_flag</code> ➡️ <code>mnt_userns, parentpath, file, mode</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct dentry *</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mnt_idmap *idmap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
</ul>
</details>
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
