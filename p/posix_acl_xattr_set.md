# Function: <code>posix_acl_xattr_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int posix_acl_xattr_set(const struct xattr_handler *handler, struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff8126e550)
Location: fs/posix_acl.c:810
Inline: False
```
**Symbols:**

```
ffffffff8126e550-ffffffff8126e68e: posix_acl_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int posix_acl_xattr_set(const struct xattr_handler *handler, struct dentry *unused, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81299ad0)
Location: fs/posix_acl.c:856
Inline: False
```
**Symbols:**

```
ffffffff81299ad0-ffffffff81299b5a: posix_acl_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int posix_acl_xattr_set(const struct xattr_handler *handler, struct dentry *unused, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff812ae5f0)
Location: fs/posix_acl.c:888
Inline: False
```
**Symbols:**

```
ffffffff812ae5f0-ffffffff812ae67a: posix_acl_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int posix_acl_xattr_set(const struct xattr_handler *handler, struct dentry *unused, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff812bb6f0)
Location: fs/posix_acl.c:879
Inline: False
```
**Symbols:**

```
ffffffff812bb6f0-ffffffff812bb785: posix_acl_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int posix_acl_xattr_set(const struct xattr_handler *handler, struct dentry *unused, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff812defe0)
Location: fs/posix_acl.c:879
Inline: False
```
**Symbols:**

```
ffffffff812defe0-ffffffff812df075: posix_acl_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int posix_acl_xattr_set(const struct xattr_handler *handler, struct dentry *unused, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff8130b790)
Location: fs/posix_acl.c:879
Inline: False
```
**Symbols:**

```
ffffffff8130b790-ffffffff8130b82b: posix_acl_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int posix_acl_xattr_set(const struct xattr_handler *handler, struct dentry *unused, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81320d00)
Location: fs/posix_acl.c:879
Inline: False
```
**Symbols:**

```
ffffffff81320d00-ffffffff81320d9b: posix_acl_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int posix_acl_xattr_set(const struct xattr_handler *handler, struct dentry *unused, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff813485a0)
Location: fs/posix_acl.c:880
Inline: False
```
**Symbols:**

```
ffffffff813485a0-ffffffff8134863c: posix_acl_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int posix_acl_xattr_set(const struct xattr_handler *handler, struct dentry *unused, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81360840)
Location: fs/posix_acl.c:880
Inline: False
```
**Symbols:**

```
ffffffff81360840-ffffffff813608dc: posix_acl_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int posix_acl_xattr_set(const struct xattr_handler *handler, struct dentry *unused, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff813a6800)
Location: fs/posix_acl.c:883
Inline: False
```
**Symbols:**

```
ffffffff813a6800-ffffffff813a68b9: posix_acl_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int posix_acl_xattr_set(const struct xattr_handler *handler, struct dentry *unused, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff813b7590)
Location: fs/posix_acl.c:883
Inline: False
```
**Symbols:**

```
ffffffff813b7590-ffffffff813b7649: posix_acl_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int posix_acl_xattr_set(const struct xattr_handler *handler, struct user_namespace *mnt_userns, struct dentry *unused, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff813be220)
Location: fs/posix_acl.c:926
Inline: False
```
**Symbols:**

```
ffffffff813be220-ffffffff813be2eb: posix_acl_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int posix_acl_xattr_set(const struct xattr_handler *handler, struct user_namespace *mnt_userns, struct dentry *unused, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff8140e050)
Location: fs/posix_acl.c:937
Inline: False
```
**Symbols:**

```
ffffffff8140e050-ffffffff8140e11b: posix_acl_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int posix_acl_xattr_set(const struct xattr_handler *handler, struct user_namespace *mnt_userns, struct dentry *unused, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81483620)
Location: fs/posix_acl.c:951
Inline: False
```
**Symbols:**

```
ffffffff81483620-ffffffff81483719: posix_acl_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int posix_acl_xattr_set(const struct xattr_handler *handler, struct dentry *unused, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffff800010426f28)
Location: fs/posix_acl.c:880
Inline: False
```
**Symbols:**

```
ffff800010426f28-ffff800010427000: posix_acl_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int posix_acl_xattr_set(const struct xattr_handler *handler, struct dentry *unused, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (c05ef7bc)
Location: fs/posix_acl.c:880
Inline: False
```
**Symbols:**

```
c05ef7bc-c05ef868: posix_acl_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int posix_acl_xattr_set(const struct xattr_handler *handler, struct dentry *unused, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (c000000000536bb0)
Location: fs/posix_acl.c:880
Inline: False
```
**Symbols:**

```
c000000000536bb0-c000000000536cc8: posix_acl_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int posix_acl_xattr_set(const struct xattr_handler *handler, struct dentry *unused, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffe0002c57ee)
Location: fs/posix_acl.c:880
Inline: False
```
**Symbols:**

```
ffffffe0002c57ee-ffffffe0002c588c: posix_acl_xattr_set (STB_LOCAL)
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
int posix_acl_xattr_set(const struct xattr_handler *handler, struct dentry *unused, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81358e20)
Location: fs/posix_acl.c:880
Inline: False
```
**Symbols:**

```
ffffffff81358e20-ffffffff81358ebc: posix_acl_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int posix_acl_xattr_set(const struct xattr_handler *handler, struct dentry *unused, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81349ad0)
Location: fs/posix_acl.c:880
Inline: False
```
**Symbols:**

```
ffffffff81349ad0-ffffffff81349b6c: posix_acl_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int posix_acl_xattr_set(const struct xattr_handler *handler, struct dentry *unused, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff813568f0)
Location: fs/posix_acl.c:880
Inline: False
```
**Symbols:**

```
ffffffff813568f0-ffffffff8135698c: posix_acl_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int posix_acl_xattr_set(const struct xattr_handler *handler, struct dentry *unused, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81369fd0)
Location: fs/posix_acl.c:880
Inline: False
```
**Symbols:**

```
ffffffff81369fd0-ffffffff8136a06c: posix_acl_xattr_set (STB_LOCAL)
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
<code>struct dentry *unused</code>
</li>
<li>
<b>Param added. </b>
<code>struct inode *inode</code>
</li>
<li>
<b>Param removed. </b>
<code>struct dentry *dentry</code>
</li>
<li>
<b>Param reordered. </b>
<code>handler, dentry, name, value, size, flags</code> ➡️ <code>handler, unused, inode, name, value, size, flags</code>
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
<li>
<b>Param reordered. </b>
<code>handler, unused, inode, name, value, size, flags</code> ➡️ <code>handler, mnt_userns, unused, inode, name, value, size, flags</code>
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
