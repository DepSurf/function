# Function: <code>dget_parent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct dentry *dget_parent(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81223a30)
Location: fs/dcache.c:803
Inline: True
Direct callers:
  - fs/namei.c:follow_dotdot
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - security/tomoyo/condition.c:tomoyo_get_attributes
```
**Symbols:**

```
ffffffff81223a30-ffffffff81223ab9: dget_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct dentry *dget_parent(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124c0e0)
Location: fs/dcache.c:811
Inline: True
Direct callers:
  - fs/namei.c:path_parent_directory
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/crypto/crypto.c:fscrypt_d_revalidate
  - fs/ext4/file.c:ext4_file_open
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - security/tomoyo/condition.c:tomoyo_get_attributes
```
**Symbols:**

```
ffffffff8124c0e0-ffffffff8124c165: dget_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct dentry *dget_parent(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8125f0c0)
Location: fs/dcache.c:811
Inline: True
Direct callers:
  - fs/namei.c:path_parent_directory
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/crypto/crypto.c:fscrypt_d_revalidate
  - fs/ext4/file.c:ext4_file_open
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - security/tomoyo/condition.c:tomoyo_get_attributes
```
**Symbols:**

```
ffffffff8125f0c0-ffffffff8125f145: dget_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct dentry *dget_parent(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126ca10)
Location: fs/dcache.c:843
Inline: True
Direct callers:
  - fs/namei.c:path_parent_directory
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/crypto/crypto.c:fscrypt_d_revalidate
  - fs/ext4/file.c:ext4_file_open
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - security/tomoyo/condition.c:tomoyo_get_attributes
```
**Symbols:**

```
ffffffff8126ca10-ffffffff8126ca9a: dget_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct dentry *dget_parent(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8128ed60)
Location: fs/dcache.c:855
Inline: True
Direct callers:
  - fs/namei.c:path_parent_directory
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/crypto/crypto.c:fscrypt_d_revalidate
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - security/tomoyo/condition.c:tomoyo_get_attributes
```
**Symbols:**

```
ffffffff8128ed60-ffffffff8128edea: dget_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct dentry *dget_parent(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812b5f20)
Location: fs/dcache.c:863
Inline: True
Direct callers:
  - fs/namei.c:path_parent_directory
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/crypto/crypto.c:fscrypt_d_revalidate
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - security/tomoyo/condition.c:tomoyo_get_attributes
```
**Symbols:**

```
ffffffff812b5f20-ffffffff812b5fa5: dget_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct dentry *dget_parent(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812cb580)
Location: fs/dcache.c:876
Inline: True
Direct callers:
  - fs/namei.c:path_parent_directory
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/crypto/crypto.c:fscrypt_d_revalidate
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - security/tomoyo/condition.c:tomoyo_get_attributes
```
**Symbols:**

```
ffffffff812cb580-ffffffff812cb605: dget_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct dentry *dget_parent(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e7e10)
Location: fs/dcache.c:902
Inline: True
Direct callers:
  - fs/namei.c:path_parent_directory
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - security/tomoyo/condition.c:tomoyo_get_attributes
```
**Symbols:**

```
ffffffff812e7e10-ffffffff812e7e97: dget_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct dentry *dget_parent(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f99a0)
Location: fs/dcache.c:902
Inline: True
Direct callers:
  - fs/namei.c:path_parent_directory
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - security/tomoyo/condition.c:tomoyo_get_attributes
```
**Symbols:**

```
ffffffff812f99a0-ffffffff812f9a27: dget_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct dentry *dget_parent(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81332d00)
Location: fs/dcache.c:921
Inline: True
Direct callers:
  - fs/namei.c:path_pts
  - fs/namei.c:follow_dotdot
  - fs/ext4/fsync.c:ext4_sync_parent
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_one
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - security/tomoyo/condition.c:tomoyo_get_attributes
```
**Symbols:**

```
ffffffff81332d00-ffffffff81332d8f: dget_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct dentry *dget_parent(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8133e210)
Location: fs/dcache.c:928
Inline: True
Direct callers:
  - fs/namei.c:path_pts
  - fs/namei.c:follow_dotdot
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/ext4/fsync.c:ext4_sync_parent
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_one
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - security/tomoyo/condition.c:tomoyo_get_attributes
```
**Symbols:**

```
ffffffff8133e210-ffffffff8133e2b8: dget_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct dentry *dget_parent(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81344600)
Location: fs/dcache.c:931
Inline: True
Direct callers:
  - fs/namei.c:path_pts
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_one
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - security/tomoyo/condition.c:tomoyo_get_attributes
```
**Symbols:**

```
ffffffff81344600-ffffffff813446a8: dget_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct dentry *dget_parent(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff813920f0)
Location: fs/dcache.c:931
Inline: True
Direct callers:
  - fs/namei.c:path_pts
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_one
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - security/tomoyo/condition.c:tomoyo_get_attributes
```
**Symbols:**

```
ffffffff813920f0-ffffffff81392198: dget_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct dentry *dget_parent(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81413d40)
Location: fs/dcache.c:956
Inline: True
Direct callers:
  - fs/namei.c:path_pts
  - fs/namei.c:handle_dots
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_one
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - security/tomoyo/condition.c:tomoyo_get_attributes
  - security/landlock/fs.c:collect_domain_accesses
  - security/landlock/fs.c:check_access_path_dual
```
**Symbols:**

```
ffffffff81413d40-ffffffff81413dfa: dget_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct dentry *dget_parent(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8149f160)
Location: fs/dcache.c:956
Inline: True
Direct callers:
  - fs/namei.c:path_pts
  - fs/namei.c:handle_dots
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_one
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - security/tomoyo/condition.c:tomoyo_get_attributes
  - security/landlock/fs.c:collect_domain_accesses
  - security/landlock/fs.c:is_access_to_paths_allowed
```
**Symbols:**

```
ffffffff8149f160-ffffffff8149f21a: dget_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct dentry *dget_parent(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814d4480)
Location: fs/dcache.c:956
Inline: True
Direct callers:
  - fs/namei.c:path_pts
  - fs/namei.c:handle_dots
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_one
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - security/tomoyo/condition.c:tomoyo_get_attributes
  - security/landlock/fs.c:collect_domain_accesses
  - security/landlock/fs.c:is_access_to_paths_allowed
```
**Symbols:**

```
ffffffff814d4480-ffffffff814d453a: dget_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct dentry *dget_parent(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81506890)
Location: fs/dcache.c:881
Inline: True
Direct callers:
  - fs/namei.c:path_pts
  - fs/namei.c:handle_dots
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_one
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - security/tomoyo/condition.c:tomoyo_get_attributes
  - security/landlock/fs.c:collect_domain_accesses
  - security/landlock/fs.c:is_access_to_paths_allowed
```
**Symbols:**

```
ffffffff81506890-ffffffff8150694a: dget_parent (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct dentry *dget_parent(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103a7e20)
Location: fs/dcache.c:902
Inline: True
Direct callers:
  - fs/namei.c:path_parent_directory
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - security/tomoyo/condition.c:tomoyo_get_attributes
```
**Symbols:**

```
ffff8000103a7e20-ffff8000103a7f18: dget_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct dentry *dget_parent(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0589d90)
Location: fs/dcache.c:902
Inline: True
Direct callers:
  - fs/namei.c:path_parent_directory
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - security/tomoyo/condition.c:tomoyo_get_attributes
```
**Symbols:**

```
c0589d90-c0589e38: dget_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct dentry *dget_parent(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0000000004a30a0)
Location: fs/dcache.c:902
Inline: True
Direct callers:
  - fs/namei.c:path_parent_directory
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/exportfs/expfs.c:reconnect_path
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - security/tomoyo/condition.c:tomoyo_get_attributes
```
**Symbols:**

```
c0000000004a30a0-c0000000004a320c: dget_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct dentry *dget_parent(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe00026e646)
Location: fs/dcache.c:902
Inline: True
Direct callers:
  - fs/namei.c:path_parent_directory
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - security/tomoyo/condition.c:tomoyo_get_attributes
```
**Symbols:**

```
ffffffe00026e646-ffffffe00026e746: dget_parent (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct dentry *dget_parent(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f1f80)
Location: fs/dcache.c:902
Inline: True
Direct callers:
  - fs/namei.c:path_parent_directory
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - security/tomoyo/condition.c:tomoyo_get_attributes
```
**Symbols:**

```
ffffffff812f1f80-ffffffff812f2007: dget_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct dentry *dget_parent(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e2bb0)
Location: fs/dcache.c:902
Inline: True
Direct callers:
  - fs/namei.c:path_parent_directory
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - security/tomoyo/condition.c:tomoyo_get_attributes
```
**Symbols:**

```
ffffffff812e2bb0-ffffffff812e2c37: dget_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct dentry *dget_parent(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812efd90)
Location: fs/dcache.c:902
Inline: True
Direct callers:
  - fs/namei.c:path_parent_directory
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - security/tomoyo/condition.c:tomoyo_get_attributes
```
**Symbols:**

```
ffffffff812efd90-ffffffff812efe17: dget_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct dentry *dget_parent(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff813010b0)
Location: fs/dcache.c:902
Inline: True
Direct callers:
  - fs/namei.c:path_parent_directory
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/exportfs/expfs.c:exportfs_encode_fh
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - security/tomoyo/condition.c:tomoyo_get_attributes
```
**Symbols:**

```
ffffffff813010b0-ffffffff81301150: dget_parent (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
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
