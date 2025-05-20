# Function: <code>is_bad_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int is_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff81229a10)
Location: fs/bad_inode.c:195
Inline: False
Direct callers:
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpage
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:__fuse_direct_read
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_ioctl_common
```
**Symbols:**

```
ffffffff81229a10-ffffffff81229a28: is_bad_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool is_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff81252160)
Location: fs/bad_inode.c:195
Inline: False
Direct callers:
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/file.c:fuse_ioctl_common
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:__fuse_direct_read
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpage
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
```
**Symbols:**

```
ffffffff81252160-ffffffff81252176: is_bad_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool is_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff812653b0)
Location: fs/bad_inode.c:223
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:xattr_resolve_name
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/file.c:fuse_ioctl_common
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:__fuse_direct_read
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpage
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
```
**Symbols:**

```
ffffffff812653b0-ffffffff812653c6: is_bad_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool is_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff81272bc0)
Location: fs/bad_inode.c:223
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:xattr_resolve_name
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/file.c:fuse_ioctl_common
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:__fuse_direct_read
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpage
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
```
**Symbols:**

```
ffffffff81272bc0-ffffffff81272bd6: is_bad_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool is_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff812954f0)
Location: fs/bad_inode.c:224
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:xattr_resolve_name
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/file.c:fuse_ioctl_common
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:__fuse_direct_read
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpage
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
```
**Symbols:**

```
ffffffff812954f0-ffffffff81295506: is_bad_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool is_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff812bb700)
Location: fs/bad_inode.c:224
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:xattr_resolve_name
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/file.c:fuse_ioctl_common
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:__fuse_direct_read
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpage
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
```
**Symbols:**

```
ffffffff812bb700-ffffffff812bb716: is_bad_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool is_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff812d08f0)
Location: fs/bad_inode.c:224
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:xattr_resolve_name
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/file.c:fuse_ioctl_common
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:__fuse_direct_read
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpage
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/inode.c:fuse_destroy_inode
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff812d08f0-ffffffff812d0906: is_bad_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool is_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff812ed990)
Location: fs/bad_inode.c:224
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:xattr_resolve_name
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/file.c:fuse_ioctl_common
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpage
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff812ed990-ffffffff812ed9a6: is_bad_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool is_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff812ff450)
Location: fs/bad_inode.c:224
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:xattr_resolve_name
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/file.c:fuse_ioctl_common
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpage
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff812ff450-ffffffff812ff466: is_bad_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool is_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff813384d0)
Location: fs/bad_inode.c:225
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:xattr_resolve_name
  - fs/fs-writeback.c:write_inode
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/file.c:fuse_file_compat_ioctl
  - fs/fuse/file.c:fuse_file_ioctl
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_readpage
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/inode.c:fuse_evict_inode
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff813384d0-ffffffff813384e6: is_bad_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool is_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff81343e60)
Location: fs/bad_inode.c:225
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:xattr_supported_namespace
  - fs/xattr.c:xattr_resolve_name
  - fs/fs-writeback.c:write_inode
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
**Symbols:**

```
ffffffff81343e60-ffffffff81343e76: is_bad_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool is_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff8134a210)
Location: fs/bad_inode.c:233
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:xattr_supported_namespace
  - fs/xattr.c:xattr_resolve_name
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
**Symbols:**

```
ffffffff8134a210-ffffffff8134a226: is_bad_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool is_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff81397f70)
Location: fs/bad_inode.c:233
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:xattr_supported_namespace
  - fs/xattr.c:xattr_resolve_name
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/orphan.c:ext4_orphan_add
```
**Symbols:**

```
ffffffff81397f70-ffffffff81397f86: is_bad_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool is_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff8141a510)
Location: fs/bad_inode.c:233
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:xattr_supported_namespace
  - fs/xattr.c:xattr_resolve_name
  - fs/fs-writeback.c:write_inode
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/orphan.c:ext4_orphan_add
```
**Symbols:**

```
ffffffff8141a510-ffffffff8141a52c: is_bad_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool is_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff814a6370)
Location: fs/bad_inode.c:233
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:xattr_supported_namespace
  - fs/xattr.c:xattr_resolve_name
  - fs/fs-writeback.c:write_inode
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_set_acl
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/ext4/orphan.c:ext4_orphan_add
```
**Symbols:**

```
ffffffff814a6370-ffffffff814a638c: is_bad_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool is_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff814db330)
Location: fs/bad_inode.c:233
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:xattr_supports_user_prefix
  - fs/xattr.c:xattr_resolve_name
  - fs/fs-writeback.c:write_inode
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_set_acl
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/orphan.c:ext4_orphan_add
```
**Symbols:**

```
ffffffff814db330-ffffffff814db34c: is_bad_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool is_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff8150d920)
Location: fs/bad_inode.c:231
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:xattr_supports_user_prefix
  - fs/xattr.c:xattr_resolve_name
  - fs/fs-writeback.c:write_inode
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_set_acl
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/orphan.c:ext4_orphan_add
```
**Symbols:**

```
ffffffff8150d920-ffffffff8150d93c: is_bad_inode (STB_GLOBAL)
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
bool is_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffff8000103b08b0)
Location: fs/bad_inode.c:224
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:xattr_resolve_name
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/file.c:fuse_ioctl_common
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpage
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:parse_dirplusfile
```
**Symbols:**

```
ffff8000103b08b0-ffff8000103b08e8: is_bad_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool is_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (c05901a0)
Location: fs/bad_inode.c:224
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:xattr_resolve_name
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/file.c:fuse_ioctl_common
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpage
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:parse_dirplusfile
```
**Symbols:**

```
c05901a0-c05901d0: is_bad_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool is_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (c0000000004ac250)
Location: fs/bad_inode.c:224
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:xattr_resolve_name
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/file.c:fuse_ioctl_common
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpage
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:parse_dirplusfile
```
**Symbols:**

```
c0000000004ac250-c0000000004ac27c: is_bad_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool is_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffe000274c12)
Location: fs/bad_inode.c:224
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:xattr_resolve_name
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/file.c:fuse_ioctl_common
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpage
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffe000274c12-ffffffe000274c42: is_bad_inode (STB_GLOBAL)
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
bool is_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff812f7a30)
Location: fs/bad_inode.c:224
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:xattr_resolve_name
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/file.c:fuse_ioctl_common
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpage
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff812f7a30-ffffffff812f7a46: is_bad_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool is_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff812e8650)
Location: fs/bad_inode.c:224
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:xattr_resolve_name
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/file.c:fuse_ioctl_common
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpage
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff812e8650-ffffffff812e8666: is_bad_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool is_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff812f5840)
Location: fs/bad_inode.c:224
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:xattr_resolve_name
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/file.c:fuse_ioctl_common
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpage
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff812f5840-ffffffff812f5856: is_bad_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool is_bad_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff813069d0)
Location: fs/bad_inode.c:224
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:xattr_resolve_name
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/file.c:fuse_ioctl_common
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpage
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff813069d0-ffffffff813069e6: is_bad_inode (STB_GLOBAL)
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
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
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
