# Function: <code>__vfs_removexattr_locked</code>

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
int __vfs_removexattr_locked(struct dentry *dentry, const char *name, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81343460)
Location: fs/xattr.c:457
Inline: False
Direct callers:
  - fs/xattr.c:vfs_removexattr
```
**Symbols:**

```
ffffffff81343460-ffffffff81343513: __vfs_removexattr_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __vfs_removexattr_locked(struct dentry *dentry, const char *name, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8134f5f0)
Location: fs/xattr.c:495
Inline: False
Direct callers:
  - fs/xattr.c:vfs_removexattr
```
**Symbols:**

```
ffffffff8134f5f0-ffffffff8134f6a3: __vfs_removexattr_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __vfs_removexattr_locked(struct user_namespace *mnt_userns, struct dentry *dentry, const char *name, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff813560e0)
Location: fs/xattr.c:513
Inline: False
Direct callers:
  - fs/xattr.c:vfs_removexattr
```
**Symbols:**

```
ffffffff813560e0-ffffffff813561a2: __vfs_removexattr_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __vfs_removexattr_locked(struct user_namespace *mnt_userns, struct dentry *dentry, const char *name, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff813a4610)
Location: fs/xattr.c:514
Inline: False
Direct callers:
  - fs/xattr.c:vfs_removexattr
```
**Symbols:**

```
ffffffff813a4610-ffffffff813a46d2: __vfs_removexattr_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __vfs_removexattr_locked(struct user_namespace *mnt_userns, struct dentry *dentry, const char *name, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81428570)
Location: fs/xattr.c:515
Inline: False
Direct callers:
  - fs/xattr.c:vfs_removexattr
```
**Symbols:**

```
ffffffff81428570-ffffffff814286fd: __vfs_removexattr_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __vfs_removexattr_locked(struct user_namespace *mnt_userns, struct dentry *dentry, const char *name, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814b5a90)
Location: fs/xattr.c:542
Inline: False
Direct callers:
  - fs/xattr.c:vfs_removexattr
```
**Symbols:**

```
ffffffff814b5a90-ffffffff814b5c1d: __vfs_removexattr_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __vfs_removexattr_locked(struct mnt_idmap *idmap, struct dentry *dentry, const char *name, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814ea2e0)
Location: fs/xattr.c:535
Inline: False
Direct callers:
  - fs/xattr.c:vfs_removexattr
```
**Symbols:**

```
ffffffff814ea2e0-ffffffff814ea46d: __vfs_removexattr_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __vfs_removexattr_locked(struct mnt_idmap *idmap, struct dentry *dentry, const char *name, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8151e180)
Location: fs/xattr.c:535
Inline: False
Direct callers:
  - fs/xattr.c:vfs_removexattr
```
**Symbols:**

```
ffffffff8151e180-ffffffff8151e30d: __vfs_removexattr_locked (STB_GLOBAL)
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
<code>dentry, name, delegated_inode</code> ➡️ <code>mnt_userns, dentry, name, delegated_inode</code>
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
