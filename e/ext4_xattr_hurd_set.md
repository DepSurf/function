# Function: <code>ext4_xattr_hurd_set</code>

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
int ext4_xattr_hurd_set(const struct xattr_handler *handler, struct dentry *unused, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr_hurd.c (ffffffff8143b0e0)
Location: fs/ext4/xattr_hurd.c:34
Inline: False
```
**Symbols:**

```
ffffffff8143b0e0-ffffffff8143b11c: ext4_xattr_hurd_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_xattr_hurd_set(const struct xattr_handler *handler, struct dentry *unused, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr_hurd.c (ffffffff81453c50)
Location: fs/ext4/xattr_hurd.c:34
Inline: False
```
**Symbols:**

```
ffffffff81453c50-ffffffff81453c8c: ext4_xattr_hurd_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_xattr_hurd_set(const struct xattr_handler *handler, struct user_namespace *mnt_userns, struct dentry *unused, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr_hurd.c (ffffffff81459580)
Location: fs/ext4/xattr_hurd.c:34
Inline: False
```
**Symbols:**

```
ffffffff81459580-ffffffff814595bd: ext4_xattr_hurd_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_xattr_hurd_set(const struct xattr_handler *handler, struct user_namespace *mnt_userns, struct dentry *unused, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr_hurd.c (ffffffff814ad690)
Location: fs/ext4/xattr_hurd.c:34
Inline: False
```
**Symbols:**

```
ffffffff814ad690-ffffffff814ad6cd: ext4_xattr_hurd_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_xattr_hurd_set(const struct xattr_handler *handler, struct user_namespace *mnt_userns, struct dentry *unused, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr_hurd.c (ffffffff81535730)
Location: fs/ext4/xattr_hurd.c:34
Inline: False
```
**Symbols:**

```
ffffffff81535730-ffffffff81535791: ext4_xattr_hurd_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_xattr_hurd_set(const struct xattr_handler *handler, struct user_namespace *mnt_userns, struct dentry *unused, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr_hurd.c (ffffffff815d3b30)
Location: fs/ext4/xattr_hurd.c:34
Inline: False
```
**Symbols:**

```
ffffffff815d3b30-ffffffff815d3b91: ext4_xattr_hurd_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_xattr_hurd_set(const struct xattr_handler *handler, struct mnt_idmap *idmap, struct dentry *unused, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr_hurd.c (ffffffff8160b720)
Location: fs/ext4/xattr_hurd.c:34
Inline: False
```
**Symbols:**

```
ffffffff8160b720-ffffffff8160b781: ext4_xattr_hurd_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_xattr_hurd_set(const struct xattr_handler *handler, struct mnt_idmap *idmap, struct dentry *unused, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr_hurd.c (ffffffff816444e0)
Location: fs/ext4/xattr_hurd.c:34
Inline: False
```
**Symbols:**

```
ffffffff816444e0-ffffffff81644541: ext4_xattr_hurd_set (STB_LOCAL)
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
