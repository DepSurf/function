# Function: <code>unlock_new_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void unlock_new_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81226f70)
Location: fs/inode.c:942
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/block_dev.c:bdget
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_get_inode
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffff81226f70-ffffffff81226fe2: unlock_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void unlock_new_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8124f6b0)
Location: fs/inode.c:951
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/block_dev.c:bdget
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/squashfs/inode.c:squashfs_iget
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_get_inode
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffff8124f6b0-ffffffff8124f722: unlock_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void unlock_new_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812626e0)
Location: fs/inode.c:953
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/block_dev.c:bdget
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/squashfs/inode.c:squashfs_iget
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_get_inode
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffff812626e0-ffffffff81262752: unlock_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void unlock_new_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8126ff80)
Location: fs/inode.c:954
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/block_dev.c:bdget
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/squashfs/inode.c:squashfs_iget
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_get_inode
  - fs/fuse/inode.c:fuse_iget
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff8126ff80-ffffffff8126ffdb: unlock_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void unlock_new_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812928b0)
Location: fs/inode.c:954
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/block_dev.c:bdget
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/squashfs/inode.c:squashfs_iget
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_get_inode
  - fs/fuse/inode.c:fuse_iget
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff812928b0-ffffffff8129290e: unlock_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void unlock_new_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812b9270)
Location: fs/inode.c:959
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/block_dev.c:bdget
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/squashfs/inode.c:squashfs_iget
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_get_inode
  - fs/fuse/inode.c:fuse_iget
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff812b9270-ffffffff812b92ce: unlock_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void unlock_new_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812ce630)
Location: fs/inode.c:967
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/block_dev.c:bdget
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/squashfs/inode.c:squashfs_iget
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_get_inode
  - fs/fuse/inode.c:fuse_iget
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff812ce630-ffffffff812ce690: unlock_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void unlock_new_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:980
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/block_dev.c:bdget
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/squashfs/inode.c:squashfs_iget
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_get_inode
  - fs/fuse/inode.c:fuse_iget
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff812ecf83-ffffffff812ecf9d: unlock_new_inode.cold (STB_LOCAL)
ffffffff812eb5c0-ffffffff812eb622: unlock_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void unlock_new_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812fcf60)
Location: fs/inode.c:991
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/block_dev.c:bdget
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/squashfs/inode.c:squashfs_iget
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_get_inode
  - fs/fuse/inode.c:fuse_iget
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff812fcf60-ffffffff812fcfc0: unlock_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void unlock_new_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81335ac0)
Location: fs/inode.c:992
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/block_dev.c:bdget
  - fs/kernfs/inode.c:kernfs_init_inode
  - fs/kernfs/inode.c:kernfs_init_inode
  - fs/kernfs/inode.c:kernfs_init_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_add_nondir
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/squashfs/inode.c:squashfs_iget
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup_interpose
  - fs/fuse/inode.c:fuse_iget
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff81335ac0-ffffffff81335b20: unlock_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void unlock_new_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81341440)
Location: fs/inode.c:991
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/kernfs/inode.c:kernfs_init_inode
  - fs/kernfs/inode.c:kernfs_init_inode
  - fs/kernfs/inode.c:kernfs_init_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_add_nondir
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/squashfs/inode.c:squashfs_iget
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup_interpose
  - fs/fuse/inode.c:fuse_iget
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff81341440-ffffffff813414a0: unlock_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void unlock_new_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81347840)
Location: fs/inode.c:998
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_add_nondir
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/squashfs/inode.c:squashfs_iget
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/inode.c:fuse_iget
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff81347840-ffffffff813478a0: unlock_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void unlock_new_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81395410)
Location: fs/inode.c:1002
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_add_nondir
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/squashfs/inode.c:squashfs_iget
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/inode.c:fuse_iget
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff81395410-ffffffff81395470: unlock_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void unlock_new_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814163e0)
Location: fs/inode.c:1083
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_add_nondir
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/squashfs/inode.c:squashfs_iget
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/inode.c:fuse_iget
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff814163e0-ffffffff81416448: unlock_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void unlock_new_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814a17c0)
Location: fs/inode.c:1081
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_add_nondir
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/squashfs/inode.c:squashfs_iget
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/inode.c:fuse_iget
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff814a17c0-ffffffff814a1828: unlock_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void unlock_new_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814d6a00)
Location: fs/inode.c:1081
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_add_nondir
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/squashfs/inode.c:squashfs_iget
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/inode.c:fuse_iget
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff814d6a00-ffffffff814d6a68: unlock_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void unlock_new_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81508df0)
Location: fs/inode.c:1066
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_add_nondir
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/squashfs/inode.c:squashfs_iget
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/inode.c:fuse_iget
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff81508df0-ffffffff81508e58: unlock_new_inode (STB_GLOBAL)
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
void unlock_new_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffff8000103ad3c8)
Location: fs/inode.c:991
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/block_dev.c:bdget
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/squashfs/inode.c:squashfs_iget
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_get_inode
  - fs/fuse/inode.c:fuse_iget
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffff8000103ad3c8-ffff8000103ad47c: unlock_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void unlock_new_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c058ca18)
Location: fs/inode.c:991
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/block_dev.c:bdget
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/squashfs/inode.c:squashfs_iget
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_get_inode
  - fs/fuse/inode.c:fuse_iget
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
c058ca18-c058ca98: unlock_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void unlock_new_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c0000000004a69f0)
Location: fs/inode.c:991
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/block_dev.c:bdget
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/squashfs/inode.c:squashfs_iget
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_get_inode
  - fs/fuse/inode.c:fuse_iget
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
c0000000004a69f0-c0000000004a6ad8: unlock_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void unlock_new_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffe000272078)
Location: fs/inode.c:991
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/block_dev.c:bdget
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/squashfs/inode.c:squashfs_iget
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_get_inode
  - fs/fuse/inode.c:fuse_iget
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffe000272078-ffffffe00027210a: unlock_new_inode (STB_GLOBAL)
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
void unlock_new_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f5540)
Location: fs/inode.c:991
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/block_dev.c:bdget
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/squashfs/inode.c:squashfs_iget
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_get_inode
  - fs/fuse/inode.c:fuse_iget
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff812f5540-ffffffff812f55a0: unlock_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void unlock_new_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812e6160)
Location: fs/inode.c:991
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/block_dev.c:bdget
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/squashfs/inode.c:squashfs_iget
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_get_inode
  - fs/fuse/inode.c:fuse_iget
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff812e6160-ffffffff812e61c0: unlock_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void unlock_new_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f3350)
Location: fs/inode.c:991
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/block_dev.c:bdget
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/squashfs/inode.c:squashfs_iget
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_get_inode
  - fs/fuse/inode.c:fuse_iget
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff812f3350-ffffffff812f33b0: unlock_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void unlock_new_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813039f0)
Location: fs/inode.c:991
Inline: False
Direct callers:
  - fs/bad_inode.c:iget_failed
  - fs/block_dev.c:bdget
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/squashfs/inode.c:squashfs_iget
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_get_inode
  - fs/fuse/inode.c:fuse_iget
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff813039f0-ffffffff81303a4e: unlock_new_inode (STB_GLOBAL)
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
