# Function: <code>fuse_xattr_set</code>

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
int fuse_xattr_set(const struct xattr_handler *handler, struct dentry *dentry, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff81367c10)
Location: fs/fuse/xattr.c:209
Inline: False
```
**Symbols:**

```
ffffffff81367c10-ffffffff81367c3c: fuse_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fuse_xattr_set(const struct xattr_handler *handler, struct dentry *dentry, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff8137c1e0)
Location: fs/fuse/xattr.c:184
Inline: False
```
**Symbols:**

```
ffffffff8137c1e0-ffffffff8137c20c: fuse_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fuse_xattr_set(const struct xattr_handler *handler, struct dentry *dentry, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff813a1080)
Location: fs/fuse/xattr.c:184
Inline: False
```
**Symbols:**

```
ffffffff813a1080-ffffffff813a10ac: fuse_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fuse_xattr_set(const struct xattr_handler *handler, struct dentry *dentry, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff813d0460)
Location: fs/fuse/xattr.c:184
Inline: False
```
**Symbols:**

```
ffffffff813d0460-ffffffff813d048c: fuse_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fuse_xattr_set(const struct xattr_handler *handler, struct dentry *dentry, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff813e99d0)
Location: fs/fuse/xattr.c:184
Inline: False
```
**Symbols:**

```
ffffffff813e99d0-ffffffff813e99fc: fuse_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fuse_xattr_set(const struct xattr_handler *handler, struct dentry *dentry, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff81415b30)
Location: fs/fuse/xattr.c:184
Inline: False
```
**Symbols:**

```
ffffffff81415b30-ffffffff81415b5c: fuse_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fuse_xattr_set(const struct xattr_handler *handler, struct dentry *dentry, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff8142f980)
Location: fs/fuse/xattr.c:184
Inline: False
```
**Symbols:**

```
ffffffff8142f980-ffffffff8142f9ac: fuse_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fuse_xattr_set(const struct xattr_handler *handler, struct dentry *dentry, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff8147f7e0)
Location: fs/fuse/xattr.c:184
Inline: False
```
**Symbols:**

```
ffffffff8147f7e0-ffffffff8147f80c: fuse_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fuse_xattr_set(const struct xattr_handler *handler, struct dentry *dentry, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff8149ae80)
Location: fs/fuse/xattr.c:190
Inline: False
```
**Symbols:**

```
ffffffff8149ae80-ffffffff8149aebd: fuse_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fuse_xattr_set(const struct xattr_handler *handler, struct user_namespace *mnt_userns, struct dentry *dentry, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff814a00d0)
Location: fs/fuse/xattr.c:193
Inline: False
```
**Symbols:**

```
ffffffff814a00d0-ffffffff814a0111: fuse_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fuse_xattr_set(const struct xattr_handler *handler, struct user_namespace *mnt_userns, struct dentry *dentry, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff814f80e0)
Location: fs/fuse/xattr.c:193
Inline: False
```
**Symbols:**

```
ffffffff814f80e0-ffffffff814f8121: fuse_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fuse_xattr_set(const struct xattr_handler *handler, struct user_namespace *mnt_userns, struct dentry *dentry, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff81588130)
Location: fs/fuse/xattr.c:191
Inline: False
```
**Symbols:**

```
ffffffff81588130-ffffffff815881a7: fuse_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fuse_xattr_set(const struct xattr_handler *handler, struct user_namespace *mnt_userns, struct dentry *dentry, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff8162e4c0)
Location: fs/fuse/xattr.c:191
Inline: False
```
**Symbols:**

```
ffffffff8162e4c0-ffffffff8162e537: fuse_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fuse_xattr_set(const struct xattr_handler *handler, struct mnt_idmap *idmap, struct dentry *dentry, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff81666700)
Location: fs/fuse/xattr.c:191
Inline: False
```
**Symbols:**

```
ffffffff81666700-ffffffff81666777: fuse_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fuse_xattr_set(const struct xattr_handler *handler, struct mnt_idmap *idmap, struct dentry *dentry, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff816a09e0)
Location: fs/fuse/xattr.c:191
Inline: False
```
**Symbols:**

```
ffffffff816a09e0-ffffffff816a0a57: fuse_xattr_set (STB_LOCAL)
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
int fuse_xattr_set(const struct xattr_handler *handler, struct dentry *dentry, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffff800010514320)
Location: fs/fuse/xattr.c:184
Inline: False
```
**Symbols:**

```
ffff800010514320-ffff8000105143a0: fuse_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fuse_xattr_set(const struct xattr_handler *handler, struct dentry *dentry, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (c06cf18c)
Location: fs/fuse/xattr.c:184
Inline: False
```
**Symbols:**

```
c06cf18c-c06cf1e0: fuse_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fuse_xattr_set(const struct xattr_handler *handler, struct dentry *dentry, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (c00000000065c600)
Location: fs/fuse/xattr.c:184
Inline: False
```
**Symbols:**

```
c00000000065c600-c00000000065c634: fuse_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fuse_xattr_set(const struct xattr_handler *handler, struct dentry *dentry, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffe00037df2c)
Location: fs/fuse/xattr.c:184
Inline: False
```
**Symbols:**

```
ffffffe00037df2c-ffffffe00037df86: fuse_xattr_set (STB_LOCAL)
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
int fuse_xattr_set(const struct xattr_handler *handler, struct dentry *dentry, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff81427f60)
Location: fs/fuse/xattr.c:184
Inline: False
```
**Symbols:**

```
ffffffff81427f60-ffffffff81427f8c: fuse_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fuse_xattr_set(const struct xattr_handler *handler, struct dentry *dentry, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff814189e0)
Location: fs/fuse/xattr.c:184
Inline: False
```
**Symbols:**

```
ffffffff814189e0-ffffffff81418a0c: fuse_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fuse_xattr_set(const struct xattr_handler *handler, struct dentry *dentry, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff81424100)
Location: fs/fuse/xattr.c:184
Inline: False
```
**Symbols:**

```
ffffffff81424100-ffffffff8142412c: fuse_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fuse_xattr_set(const struct xattr_handler *handler, struct dentry *dentry, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff8143af40)
Location: fs/fuse/xattr.c:184
Inline: False
```
**Symbols:**

```
ffffffff8143af40-ffffffff8143af6c: fuse_xattr_set (STB_LOCAL)
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
<code>handler, dentry, inode, name, value, size, flags</code> ➡️ <code>handler, mnt_userns, dentry, inode, name, value, size, flags</code>
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
