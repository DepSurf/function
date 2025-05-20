# Function: <code>kernfs_vfs_user_xattr_set</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kernfs_vfs_user_xattr_set(const struct xattr_handler *handler, struct dentry *unused, struct inode *inode, const char *suffix, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff813cd480)
Location: fs/kernfs/inode.c:387
Inline: False
```
**Symbols:**

```
ffffffff813cd480-ffffffff813cd56e: kernfs_vfs_user_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kernfs_vfs_user_xattr_set(const struct xattr_handler *handler, struct dentry *unused, struct inode *inode, const char *suffix, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff813df0b0)
Location: fs/kernfs/inode.c:387
Inline: False
```
**Symbols:**

```
ffffffff813df0b0-ffffffff813df19e: kernfs_vfs_user_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kernfs_vfs_user_xattr_set(const struct xattr_handler *handler, struct user_namespace *mnt_userns, struct dentry *unused, struct inode *inode, const char *suffix, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff813e5c30)
Location: fs/kernfs/inode.c:391
Inline: False
```
**Symbols:**

```
ffffffff813e5c30-ffffffff813e5d69: kernfs_vfs_user_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kernfs_vfs_user_xattr_set(const struct xattr_handler *handler, struct user_namespace *mnt_userns, struct dentry *unused, struct inode *inode, const char *suffix, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff814377b0)
Location: fs/kernfs/inode.c:391
Inline: False
```
**Symbols:**

```
ffffffff814377b0-ffffffff814378e9: kernfs_vfs_user_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kernfs_vfs_user_xattr_set(const struct xattr_handler *handler, struct user_namespace *mnt_userns, struct dentry *unused, struct inode *inode, const char *suffix, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff814b2520)
Location: fs/kernfs/inode.c:397
Inline: False
```
**Symbols:**

```
ffffffff814b2520-ffffffff814b2673: kernfs_vfs_user_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kernfs_vfs_user_xattr_set(const struct xattr_handler *handler, struct user_namespace *mnt_userns, struct dentry *unused, struct inode *inode, const char *suffix, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff815490a0)
Location: fs/kernfs/inode.c:393
Inline: False
```
**Symbols:**

```
ffffffff815490a0-ffffffff815491f3: kernfs_vfs_user_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kernfs_vfs_user_xattr_set(const struct xattr_handler *handler, struct mnt_idmap *idmap, struct dentry *unused, struct inode *inode, const char *suffix, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff81580c80)
Location: fs/kernfs/inode.c:393
Inline: False
```
**Symbols:**

```
ffffffff81580c80-ffffffff81580dde: kernfs_vfs_user_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kernfs_vfs_user_xattr_set(const struct xattr_handler *handler, struct mnt_idmap *idmap, struct dentry *unused, struct inode *inode, const char *suffix, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff815b9710)
Location: fs/kernfs/inode.c:404
Inline: False
```
**Symbols:**

```
ffffffff815b9710-ffffffff815b9872: kernfs_vfs_user_xattr_set (STB_LOCAL)
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
