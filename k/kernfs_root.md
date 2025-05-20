# Function: <code>kernfs_root</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff81288479)
Location: fs/kernfs/kernfs-internal.h:40
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_sop_show_options
```
```
In fs/kernfs/dir.c (ffffffff812892f8)
Location: fs/kernfs/kernfs-internal.h:40
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_put_active
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/dir.c:kernfs_new_node
  - fs/kernfs/dir.c:kernfs_add_one
  - fs/kernfs/dir.c:kernfs_remove_self
```
```
In fs/kernfs/file.c (ffffffff8128bb25)
Location: fs/kernfs/kernfs-internal.h:40
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff812b59ad)
Location: fs/kernfs/kernfs-internal.h:40
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_sop_show_path
  - fs/kernfs/mount.c:kernfs_sop_show_options
```
```
In fs/kernfs/dir.c (ffffffff812b8265)
Location: fs/kernfs/kernfs-internal.h:40
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:__kernfs_remove
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/dir.c:kernfs_add_one
  - fs/kernfs/dir.c:kernfs_new_node
  - fs/kernfs/dir.c:kernfs_put_active
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
```
```
In fs/kernfs/file.c (ffffffff812b952c)
Location: fs/kernfs/kernfs-internal.h:40
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_fop_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff812cb23d)
Location: fs/kernfs/kernfs-internal.h:40
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_sop_show_path
  - fs/kernfs/mount.c:kernfs_sop_show_options
```
```
In fs/kernfs/dir.c (ffffffff812cda05)
Location: fs/kernfs/kernfs-internal.h:40
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:__kernfs_remove
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/dir.c:kernfs_add_one
  - fs/kernfs/dir.c:kernfs_new_node
  - fs/kernfs/dir.c:kernfs_put_active
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
```
```
In fs/kernfs/file.c (ffffffff812cec6c)
Location: fs/kernfs/kernfs-internal.h:40
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_fop_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff812d86ad)
Location: fs/kernfs/kernfs-internal.h:40
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_sop_show_path
  - fs/kernfs/mount.c:kernfs_sop_show_options
```
```
In fs/kernfs/dir.c (ffffffff812db068)
Location: fs/kernfs/kernfs-internal.h:40
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/dir.c:kernfs_add_one
  - fs/kernfs/dir.c:kernfs_new_node
  - fs/kernfs/dir.c:kernfs_put_active
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
```
```
In fs/kernfs/file.c (ffffffff812dc2dc)
Location: fs/kernfs/kernfs-internal.h:40
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_fop_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff812fcdeb)
Location: fs/kernfs/kernfs-internal.h:40
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_sop_show_path
  - fs/kernfs/mount.c:kernfs_sop_show_options
```
```
In fs/kernfs/dir.c (ffffffff812ff958)
Location: fs/kernfs/kernfs-internal.h:40
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/dir.c:kernfs_add_one
  - fs/kernfs/dir.c:kernfs_new_node
  - fs/kernfs/dir.c:kernfs_put_active
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
```
```
In fs/kernfs/file.c (ffffffff81300a6c)
Location: fs/kernfs/kernfs-internal.h:40
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_fop_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff8132a9f9)
Location: fs/kernfs/kernfs-internal.h:40
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_sop_show_path
  - fs/kernfs/mount.c:kernfs_sop_show_options
```
```
In fs/kernfs/dir.c (ffffffff8132d608)
Location: fs/kernfs/kernfs-internal.h:40
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/dir.c:kernfs_add_one
  - fs/kernfs/dir.c:kernfs_new_node
  - fs/kernfs/dir.c:kernfs_put_active
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
```
```
In fs/kernfs/file.c (ffffffff8132e76c)
Location: fs/kernfs/kernfs-internal.h:40
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_fop_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff81341d59)
Location: fs/kernfs/kernfs-internal.h:40
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_sop_show_path
  - fs/kernfs/mount.c:kernfs_sop_show_options
```
```
In fs/kernfs/dir.c (ffffffff813449a8)
Location: fs/kernfs/kernfs-internal.h:40
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/dir.c:kernfs_add_one
  - fs/kernfs/dir.c:kernfs_new_node
  - fs/kernfs/dir.c:kernfs_put_active
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
```
```
In fs/kernfs/file.c (ffffffff81345b18)
Location: fs/kernfs/kernfs-internal.h:40
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_fop_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff8136a18c)
Location: fs/kernfs/kernfs-internal.h:42
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_sop_show_path
  - fs/kernfs/mount.c:kernfs_sop_show_options
```
```
In fs/kernfs/dir.c (ffffffff8136cbc4)
Location: fs/kernfs/kernfs-internal.h:42
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/dir.c:kernfs_add_one
  - fs/kernfs/dir.c:kernfs_new_node
  - fs/kernfs/dir.c:kernfs_put_active
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
```
```
In fs/kernfs/file.c (ffffffff8136db49)
Location: fs/kernfs/kernfs-internal.h:42
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_fop_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff8138237c)
Location: fs/kernfs/kernfs-internal.h:42
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_sop_show_path
  - fs/kernfs/mount.c:kernfs_sop_show_options
```
```
In fs/kernfs/dir.c (ffffffff81384d74)
Location: fs/kernfs/kernfs-internal.h:42
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/dir.c:kernfs_add_one
  - fs/kernfs/dir.c:kernfs_new_node
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
```
```
In fs/kernfs/file.c (ffffffff81385e89)
Location: fs/kernfs/kernfs-internal.h:42
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_fop_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff813cca7c)
Location: fs/kernfs/kernfs-internal.h:44
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_sop_show_path
  - fs/kernfs/mount.c:kernfs_sop_show_options
```
```
In fs/kernfs/inode.c (ffffffff813cd4c0)
Location: fs/kernfs/kernfs-internal.h:44
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/kernfs/dir.c (ffffffff813cf843)
Location: fs/kernfs/kernfs-internal.h:44
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_add_one
  - fs/kernfs/dir.c:kernfs_drain
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
```
```
In fs/kernfs/file.c (ffffffff813d0ba9)
Location: fs/kernfs/kernfs-internal.h:44
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_fop_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff813de6cc)
Location: fs/kernfs/kernfs-internal.h:44
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_sop_show_path
  - fs/kernfs/mount.c:kernfs_sop_show_options
```
```
In fs/kernfs/inode.c (ffffffff813df0f0)
Location: fs/kernfs/kernfs-internal.h:44
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/kernfs/dir.c (ffffffff813e1473)
Location: fs/kernfs/kernfs-internal.h:44
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_add_one
  - fs/kernfs/dir.c:kernfs_drain
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
```
```
In fs/kernfs/file.c (ffffffff813e2829)
Location: fs/kernfs/kernfs-internal.h:44
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_fop_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff813e541c)
Location: fs/kernfs/kernfs-internal.h:44
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_sop_show_path
  - fs/kernfs/mount.c:kernfs_sop_show_options
```
```
In fs/kernfs/inode.c (ffffffff813e5c71)
Location: fs/kernfs/kernfs-internal.h:44
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/kernfs/dir.c (ffffffff813e80a3)
Location: fs/kernfs/kernfs-internal.h:44
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_add_one
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
```
```
In fs/kernfs/file.c (ffffffff813e9439)
Location: fs/kernfs/kernfs-internal.h:44
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_fop_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff81436fec)
Location: fs/kernfs/kernfs-internal.h:45
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_sop_show_path
  - fs/kernfs/mount.c:kernfs_sop_show_options
```
```
In fs/kernfs/inode.c (ffffffff814377f1)
Location: fs/kernfs/kernfs-internal.h:45
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/kernfs/dir.c (ffffffff81439de3)
Location: fs/kernfs/kernfs-internal.h:45
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_add_one
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
```
```
In fs/kernfs/file.c (ffffffff8143b199)
Location: fs/kernfs/kernfs-internal.h:45
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_fop_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff814b1b7c)
Location: fs/kernfs/kernfs-internal.h:63
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_sop_show_path
  - fs/kernfs/mount.c:kernfs_sop_show_options
```
```
In fs/kernfs/inode.c (ffffffff814b2561)
Location: fs/kernfs/kernfs-internal.h:63
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_iop_permission
  - fs/kernfs/inode.c:kernfs_iop_getattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/kernfs/inode.c:kernfs_setattr
```
```
In fs/kernfs/dir.c (ffffffff814b3f3b)
Location: fs/kernfs/kernfs-internal.h:63
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove
  - fs/kernfs/dir.c:kernfs_remove
  - fs/kernfs/dir.c:kernfs_activate
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/dir.c:kernfs_iop_lookup
  - fs/kernfs/dir.c:kernfs_dop_revalidate
  - fs/kernfs/dir.c:kernfs_dop_revalidate
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_ns
  - fs/kernfs/dir.c:kernfs_add_one
  - fs/kernfs/dir.c:kernfs_add_one
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
```
```
In fs/kernfs/file.c (ffffffff814b5bb3)
Location: fs/kernfs/kernfs-internal.h:63
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_fop_open
```
```
In fs/kernfs/symlink.c (ffffffff814b6a61)
Location: fs/kernfs/kernfs-internal.h:63
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff8154861c)
Location: fs/kernfs/kernfs-internal.h:63
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_sop_show_path
  - fs/kernfs/mount.c:kernfs_sop_show_options
```
```
In fs/kernfs/inode.c (ffffffff815490e1)
Location: fs/kernfs/kernfs-internal.h:63
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_iop_permission
  - fs/kernfs/inode.c:kernfs_iop_getattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/kernfs/inode.c:kernfs_setattr
```
```
In fs/kernfs/dir.c (ffffffff8154ad2b)
Location: fs/kernfs/kernfs-internal.h:63
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove
  - fs/kernfs/dir.c:kernfs_remove
  - fs/kernfs/dir.c:kernfs_show
  - fs/kernfs/dir.c:kernfs_activate
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/dir.c:kernfs_iop_lookup
  - fs/kernfs/dir.c:kernfs_dop_revalidate
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_ns
  - fs/kernfs/dir.c:kernfs_add_one
  - fs/kernfs/dir.c:kernfs_add_one
  - fs/kernfs/dir.c:kernfs_drain
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
```
```
In fs/kernfs/file.c (ffffffff8154cd43)
Location: fs/kernfs/kernfs-internal.h:63
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_fop_open
```
```
In fs/kernfs/symlink.c (ffffffff8154dd51)
Location: fs/kernfs/kernfs-internal.h:63
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff815801dc)
Location: fs/kernfs/kernfs-internal.h:65
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_sop_show_path
  - fs/kernfs/mount.c:kernfs_sop_show_options
```
```
In fs/kernfs/inode.c (ffffffff81580cc1)
Location: fs/kernfs/kernfs-internal.h:65
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_iop_permission
  - fs/kernfs/inode.c:kernfs_iop_getattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/kernfs/inode.c:kernfs_setattr
```
```
In fs/kernfs/dir.c (ffffffff8158297f)
Location: fs/kernfs/kernfs-internal.h:65
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove
  - fs/kernfs/dir.c:kernfs_remove
  - fs/kernfs/dir.c:kernfs_show
  - fs/kernfs/dir.c:kernfs_activate
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/dir.c:kernfs_iop_lookup
  - fs/kernfs/dir.c:kernfs_dop_revalidate
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_ns
  - fs/kernfs/dir.c:kernfs_add_one
  - fs/kernfs/dir.c:kernfs_add_one
  - fs/kernfs/dir.c:kernfs_drain
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
```
```
In fs/kernfs/file.c (ffffffff81584a16)
Location: fs/kernfs/kernfs-internal.h:65
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_fop_open
```
```
In fs/kernfs/symlink.c (ffffffff81585a11)
Location: fs/kernfs/kernfs-internal.h:65
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff815b8bcc)
Location: fs/kernfs/kernfs-internal.h:65
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_sop_show_path
  - fs/kernfs/mount.c:kernfs_sop_show_options
```
```
In fs/kernfs/inode.c (ffffffff815b973e)
Location: fs/kernfs/kernfs-internal.h:65
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_iop_permission
  - fs/kernfs/inode.c:kernfs_iop_getattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/kernfs/inode.c:kernfs_setattr
```
```
In fs/kernfs/dir.c (ffffffff815bb5af)
Location: fs/kernfs/kernfs-internal.h:65
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove
  - fs/kernfs/dir.c:kernfs_remove
  - fs/kernfs/dir.c:kernfs_show
  - fs/kernfs/dir.c:kernfs_activate
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/dir.c:kernfs_iop_lookup
  - fs/kernfs/dir.c:kernfs_dop_revalidate
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_ns
  - fs/kernfs/dir.c:kernfs_add_one
  - fs/kernfs/dir.c:kernfs_add_one
  - fs/kernfs/dir.c:kernfs_new_node
  - fs/kernfs/dir.c:kernfs_drain
  - fs/kernfs/dir.c:kernfs_unlink_sibling
  - fs/kernfs/dir.c:kernfs_unlink_sibling
  - fs/kernfs/dir.c:kernfs_link_sibling
  - fs/kernfs/dir.c:kernfs_link_sibling
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
```
```
In fs/kernfs/file.c (ffffffff815bd466)
Location: fs/kernfs/kernfs-internal.h:65
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_fop_open
```
```
In fs/kernfs/symlink.c (ffffffff815be4f4)
Location: fs/kernfs/kernfs-internal.h:65
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffff8000104506c0)
Location: fs/kernfs/kernfs-internal.h:42
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_sop_show_path
  - fs/kernfs/mount.c:kernfs_sop_show_options
```
```
In fs/kernfs/dir.c (ffff800010453d70)
Location: fs/kernfs/kernfs-internal.h:42
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/dir.c:kernfs_add_one
  - fs/kernfs/dir.c:kernfs_new_node
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
```
```
In fs/kernfs/file.c (ffff800010454b08)
Location: fs/kernfs/kernfs-internal.h:42
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_fop_open
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (c0613728)
Location: fs/kernfs/kernfs-internal.h:42
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_sop_show_path
  - fs/kernfs/mount.c:kernfs_sop_show_options
```
```
In fs/kernfs/dir.c (c0616858)
Location: fs/kernfs/kernfs-internal.h:42
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/dir.c:kernfs_add_one
  - fs/kernfs/dir.c:kernfs_new_node
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
```
```
In fs/kernfs/file.c (c0616e50)
Location: fs/kernfs/kernfs-internal.h:42
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_fop_open
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (c00000000056881c)
Location: fs/kernfs/kernfs-internal.h:42
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_sop_show_path
  - fs/kernfs/mount.c:kernfs_sop_show_options
```
```
In fs/kernfs/dir.c (c00000000056d2f4)
Location: fs/kernfs/kernfs-internal.h:42
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/dir.c:kernfs_add_one
  - fs/kernfs/dir.c:kernfs_new_node
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
```
```
In fs/kernfs/file.c (c00000000056f110)
Location: fs/kernfs/kernfs-internal.h:42
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_fop_open
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffe0002e36b2)
Location: fs/kernfs/kernfs-internal.h:42
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_sop_show_path
  - fs/kernfs/mount.c:kernfs_sop_show_options
```
```
In fs/kernfs/dir.c (ffffffe0002e620e)
Location: fs/kernfs/kernfs-internal.h:42
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/dir.c:kernfs_add_one
  - fs/kernfs/dir.c:kernfs_new_node
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
```
```
In fs/kernfs/file.c (ffffffe0002e7274)
Location: fs/kernfs/kernfs-internal.h:42
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_fop_open
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff8137a95c)
Location: fs/kernfs/kernfs-internal.h:42
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_sop_show_path
  - fs/kernfs/mount.c:kernfs_sop_show_options
```
```
In fs/kernfs/dir.c (ffffffff8137d354)
Location: fs/kernfs/kernfs-internal.h:42
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/dir.c:kernfs_add_one
  - fs/kernfs/dir.c:kernfs_new_node
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
```
```
In fs/kernfs/file.c (ffffffff8137e469)
Location: fs/kernfs/kernfs-internal.h:42
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_fop_open
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff8136b42c)
Location: fs/kernfs/kernfs-internal.h:42
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_sop_show_path
  - fs/kernfs/mount.c:kernfs_sop_show_options
```
```
In fs/kernfs/dir.c (ffffffff8136de14)
Location: fs/kernfs/kernfs-internal.h:42
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/dir.c:kernfs_add_one
  - fs/kernfs/dir.c:kernfs_new_node
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
```
```
In fs/kernfs/file.c (ffffffff8136ef03)
Location: fs/kernfs/kernfs-internal.h:42
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_fop_open
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff8137842c)
Location: fs/kernfs/kernfs-internal.h:42
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_sop_show_path
  - fs/kernfs/mount.c:kernfs_sop_show_options
```
```
In fs/kernfs/dir.c (ffffffff8137ae24)
Location: fs/kernfs/kernfs-internal.h:42
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/dir.c:kernfs_add_one
  - fs/kernfs/dir.c:kernfs_new_node
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
```
```
In fs/kernfs/file.c (ffffffff8137bf39)
Location: fs/kernfs/kernfs-internal.h:42
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_fop_open
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff8138bedc)
Location: fs/kernfs/kernfs-internal.h:42
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_sop_show_path
  - fs/kernfs/mount.c:kernfs_sop_show_options
```
```
In fs/kernfs/dir.c (ffffffff8138e924)
Location: fs/kernfs/kernfs-internal.h:42
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/dir.c:kernfs_add_one
  - fs/kernfs/dir.c:kernfs_new_node
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
```
```
In fs/kernfs/file.c (ffffffff8138edf0)
Location: fs/kernfs/kernfs-internal.h:42
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_fop_open
```
</details>
</li>
</ul>

## Differences
