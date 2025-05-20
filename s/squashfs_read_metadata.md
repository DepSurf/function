# Function: <code>squashfs_read_metadata</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int squashfs_read_metadata(struct super_block *sb, void *buffer, u64 *block, int *offset, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff813219c0)
Location: fs/squashfs/cache.c:344
Inline: False
Direct callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:read_indexes
  - fs/squashfs/fragment.c:squashfs_frag_lookup
  - fs/squashfs/id.c:squashfs_get_id
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr_id.c:squashfs_xattr_lookup
```
**Symbols:**

```
ffffffff813219c0-ffffffff81321af2: squashfs_read_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int squashfs_read_metadata(struct super_block *sb, void *buffer, u64 *block, int *offset, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff81337850)
Location: fs/squashfs/cache.c:344
Inline: False
Direct callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:read_indexes
  - fs/squashfs/fragment.c:squashfs_frag_lookup
  - fs/squashfs/id.c:squashfs_get_id
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr_id.c:squashfs_xattr_lookup
```
**Symbols:**

```
ffffffff81337850-ffffffff81337982: squashfs_read_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int squashfs_read_metadata(struct super_block *sb, void *buffer, u64 *block, int *offset, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff8134c590)
Location: fs/squashfs/cache.c:344
Inline: False
Direct callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:read_indexes
  - fs/squashfs/fragment.c:squashfs_frag_lookup
  - fs/squashfs/id.c:squashfs_get_id
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr_id.c:squashfs_xattr_lookup
```
**Symbols:**

```
ffffffff8134c590-ffffffff8134c6a0: squashfs_read_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int squashfs_read_metadata(struct super_block *sb, void *buffer, u64 *block, int *offset, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff81370c10)
Location: fs/squashfs/cache.c:344
Inline: False
Direct callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:read_indexes
  - fs/squashfs/fragment.c:squashfs_frag_lookup
  - fs/squashfs/id.c:squashfs_get_id
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr_id.c:squashfs_xattr_lookup
```
**Symbols:**

```
ffffffff81370c10-ffffffff81370d20: squashfs_read_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int squashfs_read_metadata(struct super_block *sb, void *buffer, u64 *block, int *offset, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff8139f420)
Location: fs/squashfs/cache.c:344
Inline: False
Direct callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:read_indexes
  - fs/squashfs/fragment.c:squashfs_frag_lookup
  - fs/squashfs/id.c:squashfs_get_id
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr_id.c:squashfs_xattr_lookup
```
**Symbols:**

```
ffffffff8139f420-ffffffff8139f553: squashfs_read_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int squashfs_read_metadata(struct super_block *sb, void *buffer, u64 *block, int *offset, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff813b81b0)
Location: fs/squashfs/cache.c:344
Inline: False
Direct callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:read_indexes
  - fs/squashfs/fragment.c:squashfs_frag_lookup
  - fs/squashfs/id.c:squashfs_get_id
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr_id.c:squashfs_xattr_lookup
```
**Symbols:**

```
ffffffff813b81b0-ffffffff813b82e3: squashfs_read_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int squashfs_read_metadata(struct super_block *sb, void *buffer, u64 *block, int *offset, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff813e2980)
Location: fs/squashfs/cache.c:331
Inline: False
Direct callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:read_indexes
  - fs/squashfs/fragment.c:squashfs_frag_lookup
  - fs/squashfs/id.c:squashfs_get_id
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr_id.c:squashfs_xattr_lookup
```
**Symbols:**

```
ffffffff813e2980-ffffffff813e2ac1: squashfs_read_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int squashfs_read_metadata(struct super_block *sb, void *buffer, u64 *block, int *offset, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff813fc9b0)
Location: fs/squashfs/cache.c:331
Inline: False
Direct callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:read_indexes
  - fs/squashfs/fragment.c:squashfs_frag_lookup
  - fs/squashfs/id.c:squashfs_get_id
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr_id.c:squashfs_xattr_lookup
```
**Symbols:**

```
ffffffff813fc9b0-ffffffff813fcaf1: squashfs_read_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int squashfs_read_metadata(struct super_block *sb, void *buffer, u64 *block, int *offset, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff8144a320)
Location: fs/squashfs/cache.c:331
Inline: False
Direct callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/export.c:squashfs_inode_lookup
  - fs/squashfs/file.c:read_indexes
  - fs/squashfs/fragment.c:squashfs_frag_lookup
  - fs/squashfs/id.c:squashfs_get_id
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:get_dir_index_using_name
  - fs/squashfs/namei.c:get_dir_index_using_name
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr_id.c:squashfs_xattr_lookup
```
**Symbols:**

```
ffffffff8144a320-ffffffff8144a461: squashfs_read_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int squashfs_read_metadata(struct super_block *sb, void *buffer, u64 *block, int *offset, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff81466a10)
Location: fs/squashfs/cache.c:331
Inline: False
Direct callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/file.c:read_indexes
  - fs/squashfs/fragment.c:squashfs_frag_lookup
  - fs/squashfs/id.c:squashfs_get_id
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:get_dir_index_using_name
  - fs/squashfs/namei.c:get_dir_index_using_name
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr_id.c:squashfs_xattr_lookup
```
**Symbols:**

```
ffffffff81466a10-ffffffff81466b51: squashfs_read_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int squashfs_read_metadata(struct super_block *sb, void *buffer, u64 *block, int *offset, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff8146c120)
Location: fs/squashfs/cache.c:331
Inline: False
Direct callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:read_indexes
  - fs/squashfs/fragment.c:squashfs_frag_lookup
  - fs/squashfs/id.c:squashfs_get_id
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:get_dir_index_using_name
  - fs/squashfs/namei.c:get_dir_index_using_name
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr_id.c:squashfs_xattr_lookup
```
**Symbols:**

```
ffffffff8146c120-ffffffff8146c267: squashfs_read_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int squashfs_read_metadata(struct super_block *sb, void *buffer, u64 *block, int *offset, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff814c2980)
Location: fs/squashfs/cache.c:331
Inline: False
Direct callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:read_indexes
  - fs/squashfs/fragment.c:squashfs_frag_lookup
  - fs/squashfs/id.c:squashfs_get_id
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:get_dir_index_using_name
  - fs/squashfs/namei.c:get_dir_index_using_name
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr_id.c:squashfs_xattr_lookup
```
**Symbols:**

```
ffffffff814c2980-ffffffff814c2ac7: squashfs_read_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int squashfs_read_metadata(struct super_block *sb, void *buffer, u64 *block, int *offset, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff8154d480)
Location: fs/squashfs/cache.c:331
Inline: False
Direct callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/file.c:squashfs_read_folio
  - fs/squashfs/file.c:read_indexes
  - fs/squashfs/fragment.c:squashfs_frag_lookup
  - fs/squashfs/id.c:squashfs_get_id
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:get_dir_index_using_name
  - fs/squashfs/namei.c:get_dir_index_using_name
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr_id.c:squashfs_xattr_lookup
```
**Symbols:**

```
ffffffff8154d480-ffffffff8154d5e3: squashfs_read_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int squashfs_read_metadata(struct super_block *sb, void *buffer, u64 *block, int *offset, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff815ed410)
Location: fs/squashfs/cache.c:331
Inline: False
Direct callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/file.c:read_blocklist
  - fs/squashfs/file.c:read_indexes
  - fs/squashfs/fragment.c:squashfs_frag_lookup
  - fs/squashfs/id.c:squashfs_get_id
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:get_dir_index_using_name
  - fs/squashfs/namei.c:get_dir_index_using_name
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr_id.c:squashfs_xattr_lookup
```
**Symbols:**

```
ffffffff815ed410-ffffffff815ed573: squashfs_read_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int squashfs_read_metadata(struct super_block *sb, void *buffer, u64 *block, int *offset, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff816253d0)
Location: fs/squashfs/cache.c:331
Inline: False
Direct callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/file.c:read_blocklist
  - fs/squashfs/file.c:read_indexes
  - fs/squashfs/fragment.c:squashfs_frag_lookup
  - fs/squashfs/id.c:squashfs_get_id
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:get_dir_index_using_name
  - fs/squashfs/namei.c:get_dir_index_using_name
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr_id.c:squashfs_xattr_lookup
```
**Symbols:**

```
ffffffff816253d0-ffffffff81625533: squashfs_read_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int squashfs_read_metadata(struct super_block *sb, void *buffer, u64 *block, int *offset, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff8165e4e0)
Location: fs/squashfs/cache.c:331
Inline: False
Direct callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/file.c:read_blocklist
  - fs/squashfs/file.c:read_indexes
  - fs/squashfs/fragment.c:squashfs_frag_lookup
  - fs/squashfs/id.c:squashfs_get_id
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:get_dir_index_using_name
  - fs/squashfs/namei.c:get_dir_index_using_name
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr_id.c:squashfs_xattr_lookup
```
**Symbols:**

```
ffffffff8165e4e0-ffffffff8165e643: squashfs_read_metadata (STB_GLOBAL)
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
int squashfs_read_metadata(struct super_block *sb, void *buffer, u64 *block, int *offset, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffff8000104da8a8)
Location: fs/squashfs/cache.c:331
Inline: False
Direct callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:read_indexes
  - fs/squashfs/fragment.c:squashfs_frag_lookup
  - fs/squashfs/id.c:squashfs_get_id
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr_id.c:squashfs_xattr_lookup
```
**Symbols:**

```
ffff8000104da8a8-ffff8000104daa2c: squashfs_read_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int squashfs_read_metadata(struct super_block *sb, void *buffer, u64 *block, int *offset, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (c069bf78)
Location: fs/squashfs/cache.c:331
Inline: False
Direct callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:read_indexes
  - fs/squashfs/fragment.c:squashfs_frag_lookup
  - fs/squashfs/id.c:squashfs_get_id
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr_id.c:squashfs_xattr_lookup
```
**Symbols:**

```
c069bf78-c069c0d8: squashfs_read_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int squashfs_read_metadata(struct super_block *sb, void *buffer, u64 *block, int *offset, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (c000000000615560)
Location: fs/squashfs/cache.c:331
Inline: False
Direct callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:read_indexes
  - fs/squashfs/fragment.c:squashfs_frag_lookup
  - fs/squashfs/id.c:squashfs_get_id
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_xattr_get
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr_id.c:squashfs_xattr_lookup
```
**Symbols:**

```
c000000000615560-c000000000615788: squashfs_read_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int squashfs_read_metadata(struct super_block *sb, void *buffer, u64 *block, int *offset, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffe00034f838)
Location: fs/squashfs/cache.c:331
Inline: False
Direct callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:read_indexes
  - fs/squashfs/fragment.c:squashfs_frag_lookup
  - fs/squashfs/id.c:squashfs_get_id
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr_id.c:squashfs_xattr_lookup
```
**Symbols:**

```
ffffffe00034f838-ffffffe00034f95a: squashfs_read_metadata (STB_GLOBAL)
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
int squashfs_read_metadata(struct super_block *sb, void *buffer, u64 *block, int *offset, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff813f4f90)
Location: fs/squashfs/cache.c:331
Inline: False
Direct callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:read_indexes
  - fs/squashfs/fragment.c:squashfs_frag_lookup
  - fs/squashfs/id.c:squashfs_get_id
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr_id.c:squashfs_xattr_lookup
```
**Symbols:**

```
ffffffff813f4f90-ffffffff813f50d1: squashfs_read_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int squashfs_read_metadata(struct super_block *sb, void *buffer, u64 *block, int *offset, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff813e5a10)
Location: fs/squashfs/cache.c:331
Inline: False
Direct callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:read_indexes
  - fs/squashfs/fragment.c:squashfs_frag_lookup
  - fs/squashfs/id.c:squashfs_get_id
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr_id.c:squashfs_xattr_lookup
```
**Symbols:**

```
ffffffff813e5a10-ffffffff813e5b51: squashfs_read_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int squashfs_read_metadata(struct super_block *sb, void *buffer, u64 *block, int *offset, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff813f2310)
Location: fs/squashfs/cache.c:331
Inline: False
Direct callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:read_indexes
  - fs/squashfs/fragment.c:squashfs_frag_lookup
  - fs/squashfs/id.c:squashfs_get_id
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr_id.c:squashfs_xattr_lookup
```
**Symbols:**

```
ffffffff813f2310-ffffffff813f2451: squashfs_read_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int squashfs_read_metadata(struct super_block *sb, void *buffer, u64 *block, int *offset, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff81407f00)
Location: fs/squashfs/cache.c:331
Inline: False
Direct callers:
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/dir.c:squashfs_readdir
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:read_indexes
  - fs/squashfs/fragment.c:squashfs_frag_lookup
  - fs/squashfs/id.c:squashfs_get_id
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr.c:squashfs_listxattr
  - fs/squashfs/xattr_id.c:squashfs_xattr_lookup
```
**Symbols:**

```
ffffffff81407f00-ffffffff81408041: squashfs_read_metadata (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
