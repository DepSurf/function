# Function: <code>kernfs_vfs_xattr_set</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
int kernfs_vfs_xattr_set(const struct xattr_handler *handler, struct dentry *unused, struct inode *inode, const char *suffix, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8136add0)
Location: fs/kernfs/inode.c:320
Inline: False
```
**Symbols:**

```
ffffffff8136add0-ffffffff8136ae0f: kernfs_vfs_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kernfs_vfs_xattr_set(const struct xattr_handler *handler, struct dentry *unused, struct inode *inode, const char *suffix, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff81382f90)
Location: fs/kernfs/inode.c:319
Inline: False
```
**Symbols:**

```
ffffffff81382f90-ffffffff81382fcf: kernfs_vfs_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kernfs_vfs_xattr_set(const struct xattr_handler *handler, struct dentry *unused, struct inode *inode, const char *suffix, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff813cd570)
Location: fs/kernfs/inode.c:321
Inline: False
```
**Symbols:**

```
ffffffff813cd570-ffffffff813cd5d3: kernfs_vfs_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kernfs_vfs_xattr_set(const struct xattr_handler *handler, struct dentry *unused, struct inode *inode, const char *suffix, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff813df1a0)
Location: fs/kernfs/inode.c:321
Inline: False
```
**Symbols:**

```
ffffffff813df1a0-ffffffff813df203: kernfs_vfs_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kernfs_vfs_xattr_set(const struct xattr_handler *handler, struct user_namespace *mnt_userns, struct dentry *unused, struct inode *inode, const char *suffix, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff813e5d70)
Location: fs/kernfs/inode.c:324
Inline: False
```
**Symbols:**

```
ffffffff813e5d70-ffffffff813e5dcd: kernfs_vfs_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kernfs_vfs_xattr_set(const struct xattr_handler *handler, struct user_namespace *mnt_userns, struct dentry *unused, struct inode *inode, const char *suffix, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff814378f0)
Location: fs/kernfs/inode.c:324
Inline: False
```
**Symbols:**

```
ffffffff814378f0-ffffffff8143794d: kernfs_vfs_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kernfs_vfs_xattr_set(const struct xattr_handler *handler, struct user_namespace *mnt_userns, struct dentry *unused, struct inode *inode, const char *suffix, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff814b2680)
Location: fs/kernfs/inode.c:330
Inline: False
```
**Symbols:**

```
ffffffff814b2680-ffffffff814b26ef: kernfs_vfs_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kernfs_vfs_xattr_set(const struct xattr_handler *handler, struct user_namespace *mnt_userns, struct dentry *unused, struct inode *inode, const char *suffix, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff81549210)
Location: fs/kernfs/inode.c:326
Inline: False
```
**Symbols:**

```
ffffffff81549210-ffffffff8154927f: kernfs_vfs_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kernfs_vfs_xattr_set(const struct xattr_handler *handler, struct mnt_idmap *idmap, struct dentry *unused, struct inode *inode, const char *suffix, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff81580df0)
Location: fs/kernfs/inode.c:326
Inline: False
```
**Symbols:**

```
ffffffff81580df0-ffffffff81580e5f: kernfs_vfs_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kernfs_vfs_xattr_set(const struct xattr_handler *handler, struct mnt_idmap *idmap, struct dentry *unused, struct inode *inode, const char *suffix, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff815b9890)
Location: fs/kernfs/inode.c:331
Inline: False
```
**Symbols:**

```
ffffffff815b9890-ffffffff815b990e: kernfs_vfs_xattr_set (STB_LOCAL)
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
int kernfs_vfs_xattr_set(const struct xattr_handler *handler, struct dentry *unused, struct inode *inode, const char *suffix, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffff8000104514f8)
Location: fs/kernfs/inode.c:319
Inline: False
```
**Symbols:**

```
ffff8000104514f8-ffff800010451564: kernfs_vfs_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kernfs_vfs_xattr_set(const struct xattr_handler *handler, struct dentry *unused, struct inode *inode, const char *suffix, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (c0614484)
Location: fs/kernfs/inode.c:319
Inline: False
```
**Symbols:**

```
c0614484-c06144cc: kernfs_vfs_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kernfs_vfs_xattr_set(const struct xattr_handler *handler, struct dentry *unused, struct inode *inode, const char *suffix, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (c000000000569c20)
Location: fs/kernfs/inode.c:319
Inline: False
```
**Symbols:**

```
c000000000569c20-c000000000569c84: kernfs_vfs_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int kernfs_vfs_xattr_set(const struct xattr_handler *handler, struct dentry *unused, struct inode *inode, const char *suffix, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffe0002e4362)
Location: fs/kernfs/inode.c:319
Inline: False
```
**Symbols:**

```
ffffffe0002e4362-ffffffe0002e43c0: kernfs_vfs_xattr_set (STB_LOCAL)
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
int kernfs_vfs_xattr_set(const struct xattr_handler *handler, struct dentry *unused, struct inode *inode, const char *suffix, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8137b570)
Location: fs/kernfs/inode.c:319
Inline: False
```
**Symbols:**

```
ffffffff8137b570-ffffffff8137b5af: kernfs_vfs_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kernfs_vfs_xattr_set(const struct xattr_handler *handler, struct dentry *unused, struct inode *inode, const char *suffix, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8136c040)
Location: fs/kernfs/inode.c:319
Inline: False
```
**Symbols:**

```
ffffffff8136c040-ffffffff8136c07f: kernfs_vfs_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kernfs_vfs_xattr_set(const struct xattr_handler *handler, struct dentry *unused, struct inode *inode, const char *suffix, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff81379040)
Location: fs/kernfs/inode.c:319
Inline: False
```
**Symbols:**

```
ffffffff81379040-ffffffff8137907f: kernfs_vfs_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kernfs_vfs_xattr_set(const struct xattr_handler *handler, struct dentry *unused, struct inode *inode, const char *suffix, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8138caf0)
Location: fs/kernfs/inode.c:319
Inline: False
```
**Symbols:**

```
ffffffff8138caf0-ffffffff8138cb2f: kernfs_vfs_xattr_set (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
<li>
<b>Param reordered. </b>
<code>handler, unused, inode, suffix, value, size, flags</code> ➡️ <code>handler, mnt_userns, unused, inode, suffix, value, size, flags</code>
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
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
