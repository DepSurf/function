# Function: <code>finish_open</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int finish_open(struct file *file, struct dentry *dentry, int (*open)(struct inode *, struct file *), int *opened);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8120a390)
Location: fs/open.c:795
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffffffff8120a390-ffffffff8120a3cb: finish_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int finish_open(struct file *file, struct dentry *dentry, int (*open)(struct inode *, struct file *), int *opened);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81230050)
Location: fs/open.c:795
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffffffff81230050-ffffffff8123008b: finish_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int finish_open(struct file *file, struct dentry *dentry, int (*open)(struct inode *, struct file *), int *opened);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81242600)
Location: fs/open.c:812
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffffffff81242600-ffffffff8124263b: finish_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int finish_open(struct file *file, struct dentry *dentry, int (*open)(struct inode *, struct file *), int *opened);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8124d970)
Location: fs/open.c:812
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffffffff8124d970-ffffffff8124d9ab: finish_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int finish_open(struct file *file, struct dentry *dentry, int (*open)(struct inode *, struct file *), int *opened);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8126f9e0)
Location: fs/open.c:812
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffffffff8126f9e0-ffffffff8126fa1b: finish_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int finish_open(struct file *file, struct dentry *dentry, int (*open)(struct inode *, struct file *), int *opened);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81295390)
Location: fs/open.c:854
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffffffff81295390-ffffffff812953cb: finish_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int finish_open(struct file *file, struct dentry *dentry, int (*open)(struct inode *, struct file *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812aa120)
Location: fs/open.c:844
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffffffff812aa120-ffffffff812aa140: finish_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int finish_open(struct file *file, struct dentry *dentry, int (*open)(struct inode *, struct file *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c68d0)
Location: fs/open.c:864
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffffffff812c68d0-ffffffff812c68f0: finish_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int finish_open(struct file *file, struct dentry *dentry, int (*open)(struct inode *, struct file *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d82e0)
Location: fs/open.c:869
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffffffff812d82e0-ffffffff812d8300: finish_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int finish_open(struct file *file, struct dentry *dentry, int (*open)(struct inode *, struct file *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8130e380)
Location: fs/open.c:897
Inline: True
Direct callers:
  - fs/namei.c:do_tmpfile
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffffffff8130e380-ffffffff8130e3a0: finish_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int finish_open(struct file *file, struct dentry *dentry, int (*open)(struct inode *, struct file *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8131a450)
Location: fs/open.c:886
Inline: True
Direct callers:
  - fs/namei.c:do_tmpfile
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffffffff8131a450-ffffffff8131a470: finish_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int finish_open(struct file *file, struct dentry *dentry, int (*open)(struct inode *, struct file *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81320530)
Location: fs/open.c:894
Inline: True
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffffffff81320530-ffffffff81320550: finish_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int finish_open(struct file *file, struct dentry *dentry, int (*open)(struct inode *, struct file *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8136daf0)
Location: fs/open.c:912
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffffffff8136daf0-ffffffff8136db10: finish_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int finish_open(struct file *file, struct dentry *dentry, int (*open)(struct inode *, struct file *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff813ebc00)
Location: fs/open.c:935
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffffffff813ebc00-ffffffff813ebc2a: finish_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int finish_open(struct file *file, struct dentry *dentry, int (*open)(struct inode *, struct file *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81474070)
Location: fs/open.c:967
Inline: False
Direct callers:
  - mm/shmem.c:shmem_tmpfile
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ramfs/inode.c:ramfs_tmpfile
  - fs/hugetlbfs/inode.c:hugetlbfs_tmpfile
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffffffff81474070-ffffffff8147409a: finish_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int finish_open(struct file *file, struct dentry *dentry, int (*open)(struct inode *, struct file *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814a8960)
Location: fs/open.c:1003
Inline: False
Direct callers:
  - mm/shmem.c:shmem_tmpfile
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ramfs/inode.c:ramfs_tmpfile
  - fs/hugetlbfs/inode.c:hugetlbfs_tmpfile
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffffffff814a8960-ffffffff814a898d: finish_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int finish_open(struct file *file, struct dentry *dentry, int (*open)(struct inode *, struct file *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814d9a80)
Location: fs/open.c:1042
Inline: False
Direct callers:
  - mm/shmem.c:shmem_tmpfile
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ramfs/inode.c:ramfs_tmpfile
  - fs/hugetlbfs/inode.c:hugetlbfs_tmpfile
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffffffff814d9a80-ffffffff814d9aad: finish_open (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int finish_open(struct file *file, struct dentry *dentry, int (*open)(struct inode *, struct file *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffff80001037de68)
Location: fs/open.c:869
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffff80001037de68-ffff80001037debc: finish_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int finish_open(struct file *file, struct dentry *dentry, int (*open)(struct inode *, struct file *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (c0567c5c)
Location: fs/open.c:869
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
c0567c5c-c0567c90: finish_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int finish_open(struct file *file, struct dentry *dentry, int (*open)(struct inode *, struct file *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c000000000472d70)
Location: fs/open.c:869
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
c000000000472d70-c000000000472d9c: finish_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int finish_open(struct file *file, struct dentry *dentry, int (*open)(struct inode *, struct file *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffe000253a06)
Location: fs/open.c:869
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffffffe000253a06-ffffffe000253a52: finish_open (STB_GLOBAL)
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
int finish_open(struct file *file, struct dentry *dentry, int (*open)(struct inode *, struct file *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d08c0)
Location: fs/open.c:869
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffffffff812d08c0-ffffffff812d08e0: finish_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int finish_open(struct file *file, struct dentry *dentry, int (*open)(struct inode *, struct file *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c1540)
Location: fs/open.c:869
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffffffff812c1540-ffffffff812c1560: finish_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int finish_open(struct file *file, struct dentry *dentry, int (*open)(struct inode *, struct file *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812ce6d0)
Location: fs/open.c:869
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffffffff812ce6d0-ffffffff812ce6f0: finish_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int finish_open(struct file *file, struct dentry *dentry, int (*open)(struct inode *, struct file *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812df4e0)
Location: fs/open.c:869
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffffffff812df4e0-ffffffff812df500: finish_open (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int *opened</code>
</li>
</ul>
</details>
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
