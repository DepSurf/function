# Function: <code>__vfs_setxattr</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __vfs_setxattr(struct dentry *dentry, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8126d810)
Location: fs/xattr.c:137
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - security/smack/smack_lsm.c:smack_d_instantiate
```
**Symbols:**

```
ffffffff8126d810-ffffffff8126d891: __vfs_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __vfs_setxattr(struct dentry *dentry, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8127b040)
Location: fs/xattr.c:137
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - security/smack/smack_lsm.c:smack_d_instantiate
```
**Symbols:**

```
ffffffff8127b040-ffffffff8127b0c0: __vfs_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __vfs_setxattr(struct dentry *dentry, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8129dab0)
Location: fs/xattr.c:138
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - security/smack/smack_lsm.c:smack_d_instantiate
```
**Symbols:**

```
ffffffff8129dab0-ffffffff8129db32: __vfs_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __vfs_setxattr(struct dentry *dentry, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812c4160)
Location: fs/xattr.c:138
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - security/smack/smack_lsm.c:smack_d_instantiate
```
**Symbols:**

```
ffffffff812c4160-ffffffff812c41e2: __vfs_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __vfs_setxattr(struct dentry *dentry, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812d9360)
Location: fs/xattr.c:137
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - security/smack/smack_lsm.c:smack_d_instantiate
```
**Symbols:**

```
ffffffff812d9360-ffffffff812d93e2: __vfs_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __vfs_setxattr(struct dentry *dentry, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812f78f0)
Location: fs/xattr.c:138
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - security/smack/smack_lsm.c:smack_d_instantiate
```
**Symbols:**

```
ffffffff812f78f0-ffffffff812f7972: __vfs_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __vfs_setxattr(struct dentry *dentry, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff813094f0)
Location: fs/xattr.c:138
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - security/smack/smack_lsm.c:smack_d_instantiate
```
**Symbols:**

```
ffffffff813094f0-ffffffff81309572: __vfs_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __vfs_setxattr(struct dentry *dentry, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81342a00)
Location: fs/xattr.c:138
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_xattr
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - security/smack/smack_lsm.c:smack_d_instantiate
```
**Symbols:**

```
ffffffff81342a00-ffffffff81342a82: __vfs_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __vfs_setxattr(struct dentry *dentry, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8134ec30)
Location: fs/xattr.c:165
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_xattr
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - security/smack/smack_lsm.c:smack_d_instantiate
```
**Symbols:**

```
ffffffff8134ec30-ffffffff8134ecb2: __vfs_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __vfs_setxattr(struct user_namespace *mnt_userns, struct dentry *dentry, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81355820)
Location: fs/xattr.c:167
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - security/smack/smack_lsm.c:smack_d_instantiate
```
**Symbols:**

```
ffffffff81355820-ffffffff813558a6: __vfs_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __vfs_setxattr(struct user_namespace *mnt_userns, struct dentry *dentry, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff813a3c40)
Location: fs/xattr.c:167
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - security/smack/smack_lsm.c:smack_d_instantiate
```
**Symbols:**

```
ffffffff813a3c40-ffffffff813a3cc6: __vfs_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __vfs_setxattr(struct user_namespace *mnt_userns, struct dentry *dentry, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81427a60)
Location: fs/xattr.c:169
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - security/smack/smack_lsm.c:smack_d_instantiate
```
**Symbols:**

```
ffffffff81427a60-ffffffff81427af9: __vfs_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __vfs_setxattr(struct user_namespace *mnt_userns, struct dentry *dentry, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814b5080)
Location: fs/xattr.c:186
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - security/smack/smack_lsm.c:smack_d_instantiate
```
**Symbols:**

```
ffffffff814b5080-ffffffff814b5163: __vfs_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __vfs_setxattr(struct mnt_idmap *idmap, struct dentry *dentry, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814e9ef0)
Location: fs/xattr.c:185
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - security/smack/smack_lsm.c:smack_d_instantiate
```
**Symbols:**

```
ffffffff814e9ef0-ffffffff814e9fd3: __vfs_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __vfs_setxattr(struct mnt_idmap *idmap, struct dentry *dentry, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8151dd90)
Location: fs/xattr.c:185
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
**Symbols:**

```
ffffffff8151dd90-ffffffff8151de73: __vfs_setxattr (STB_GLOBAL)
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
int __vfs_setxattr(struct dentry *dentry, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffff8000103bd678)
Location: fs/xattr.c:138
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - security/smack/smack_lsm.c:smack_d_instantiate
```
**Symbols:**

```
ffff8000103bd678-ffff8000103bd70c: __vfs_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __vfs_setxattr(struct dentry *dentry, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (c059aba4)
Location: fs/xattr.c:138
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - security/smack/smack_lsm.c:smack_d_instantiate
```
**Symbols:**

```
c059aba4-c059ac34: __vfs_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __vfs_setxattr(struct dentry *dentry, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (c0000000004bb1e0)
Location: fs/xattr.c:138
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - security/smack/smack_lsm.c:smack_d_instantiate
```
**Symbols:**

```
c0000000004bb1e0-c0000000004bb2dc: __vfs_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __vfs_setxattr(struct dentry *dentry, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffe00027e918)
Location: fs/xattr.c:138
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - security/smack/smack_lsm.c:smack_d_instantiate
```
**Symbols:**

```
ffffffe00027e918-ffffffe00027e998: __vfs_setxattr (STB_GLOBAL)
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
int __vfs_setxattr(struct dentry *dentry, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81301ad0)
Location: fs/xattr.c:138
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - security/smack/smack_lsm.c:smack_d_instantiate
```
**Symbols:**

```
ffffffff81301ad0-ffffffff81301b52: __vfs_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __vfs_setxattr(struct dentry *dentry, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812f26f0)
Location: fs/xattr.c:138
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - security/smack/smack_lsm.c:smack_d_instantiate
```
**Symbols:**

```
ffffffff812f26f0-ffffffff812f2772: __vfs_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __vfs_setxattr(struct dentry *dentry, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812ff8c0)
Location: fs/xattr.c:138
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - security/smack/smack_lsm.c:smack_d_instantiate
```
**Symbols:**

```
ffffffff812ff8c0-ffffffff812ff942: __vfs_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __vfs_setxattr(struct dentry *dentry, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81310c00)
Location: fs/xattr.c:138
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - security/smack/smack_lsm.c:smack_d_instantiate
```
**Symbols:**

```
ffffffff81310c00-ffffffff81310c82: __vfs_setxattr (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
<li>
<b>Param reordered. </b>
<code>dentry, inode, name, value, size, flags</code> ➡️ <code>mnt_userns, dentry, inode, name, value, size, flags</code>
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
