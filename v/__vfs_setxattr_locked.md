# Function: <code>__vfs_setxattr_locked</code>

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
int __vfs_setxattr_locked(struct dentry *dentry, const char *name, const void *value, size_t size, int flags, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81343ab0)
Location: fs/xattr.c:221
Inline: False
Direct callers:
  - fs/xattr.c:vfs_setxattr
```
**Symbols:**

```
ffffffff81343ab0-ffffffff81343b98: __vfs_setxattr_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __vfs_setxattr_locked(struct dentry *dentry, const char *name, const void *value, size_t size, int flags, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8134fb50)
Location: fs/xattr.c:248
Inline: False
Direct callers:
  - fs/xattr.c:vfs_setxattr
  - fs/ecryptfs/inode.c:ecryptfs_setxattr
```
**Symbols:**

```
ffffffff8134fb50-ffffffff8134fc38: __vfs_setxattr_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __vfs_setxattr_locked(struct user_namespace *mnt_userns, struct dentry *dentry, const char *name, const void *value, size_t size, int flags, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81356680)
Location: fs/xattr.c:256
Inline: False
Direct callers:
  - fs/xattr.c:vfs_setxattr
  - fs/ecryptfs/inode.c:ecryptfs_setxattr
```
**Symbols:**

```
ffffffff81356680-ffffffff81356776: __vfs_setxattr_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __vfs_setxattr_locked(struct user_namespace *mnt_userns, struct dentry *dentry, const char *name, const void *value, size_t size, int flags, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff813a4bd0)
Location: fs/xattr.c:256
Inline: False
Direct callers:
  - fs/xattr.c:vfs_setxattr
  - fs/ecryptfs/inode.c:ecryptfs_setxattr
```
**Symbols:**

```
ffffffff813a4bd0-ffffffff813a4cc6: __vfs_setxattr_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __vfs_setxattr_locked(struct user_namespace *mnt_userns, struct dentry *dentry, const char *name, const void *value, size_t size, int flags, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81429050)
Location: fs/xattr.c:258
Inline: False
Direct callers:
  - fs/xattr.c:vfs_setxattr
  - fs/ecryptfs/inode.c:ecryptfs_setxattr
```
**Symbols:**

```
ffffffff81429050-ffffffff81429174: __vfs_setxattr_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __vfs_setxattr_locked(struct user_namespace *mnt_userns, struct dentry *dentry, const char *name, const void *value, size_t size, int flags, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814b56d0)
Location: fs/xattr.c:278
Inline: False
Direct callers:
  - fs/xattr.c:vfs_setxattr
  - fs/ecryptfs/inode.c:ecryptfs_setxattr
```
**Symbols:**

```
ffffffff814b56d0-ffffffff814b57f4: __vfs_setxattr_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __vfs_setxattr_locked(struct mnt_idmap *idmap, struct dentry *dentry, const char *name, const void *value, size_t size, int flags, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814eaca0)
Location: fs/xattr.c:276
Inline: False
Direct callers:
  - fs/xattr.c:vfs_setxattr
  - fs/ecryptfs/inode.c:ecryptfs_setxattr
```
**Symbols:**

```
ffffffff814eaca0-ffffffff814eadc4: __vfs_setxattr_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __vfs_setxattr_locked(struct mnt_idmap *idmap, struct dentry *dentry, const char *name, const void *value, size_t size, int flags, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8151eb40)
Location: fs/xattr.c:276
Inline: False
Direct callers:
  - fs/xattr.c:vfs_setxattr
  - fs/ecryptfs/inode.c:ecryptfs_setxattr
```
**Symbols:**

```
ffffffff8151eb40-ffffffff8151ec64: __vfs_setxattr_locked (STB_GLOBAL)
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
<code>dentry, name, value, size, flags, delegated_inode</code> ➡️ <code>mnt_userns, dentry, name, value, size, flags, delegated_inode</code>
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
