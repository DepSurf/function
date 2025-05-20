# Function: <code>mntput</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void mntput(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8122d040)
Location: fs/namespace.c:1137
Inline: True
Inline callers:
  - fs/namespace.c:drop_mountpoint
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:mount_subtree
Direct callers:
  - kernel/acct.c:SyS_acct
  - kernel/acct.c:SyS_acct
  - fs/file_table.c:__fput
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_down
  - fs/namei.c:follow_mount
  - fs/namei.c:done_path_create
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:trailing_symlink
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:link_path_walk
  - fs/namei.c:link_path_walk
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:filename_create
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:nd_jump_link
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/libfs.c:simple_pin_fs
  - fs/libfs.c:simple_release_fs
  - fs/nsfs.c:ns_get_path
  - fs/nsfs.c:ns_get_path
  - fs/nsfs.c:ns_get_path
  - fs/fhandle.c:do_handle_open
```
**Symbols:**

```
ffffffff8122d040-ffffffff8122d073: mntput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void mntput(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81258925)
Location: fs/namespace.c:1137
Inline: True
Inline callers:
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:drop_mountpoint
Direct callers:
  - kernel/acct.c:SyS_acct
  - kernel/acct.c:SyS_acct
  - fs/file_table.c:__fput
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:link_path_walk
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/libfs.c:simple_release_fs
  - fs/libfs.c:simple_pin_fs
  - fs/nsfs.c:ns_get_path
  - fs/nsfs.c:ns_get_path
  - fs/nsfs.c:ns_get_path
  - fs/fhandle.c:do_handle_open
```
**Symbols:**

```
ffffffff812557e0-ffffffff81255813: mntput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void mntput(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8126bdd5)
Location: fs/namespace.c:1182
Inline: True
Inline callers:
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:drop_mountpoint
Direct callers:
  - kernel/acct.c:SyS_acct
  - kernel/acct.c:SyS_acct
  - fs/file_table.c:__fput
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:link_path_walk
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/libfs.c:simple_release_fs
  - fs/libfs.c:simple_pin_fs
  - fs/fhandle.c:do_handle_open
```
**Symbols:**

```
ffffffff81268bd0-ffffffff81268c03: mntput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void mntput(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812795c5)
Location: fs/namespace.c:1183
Inline: True
Inline callers:
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:drop_mountpoint
Direct callers:
  - kernel/acct.c:SyS_acct
  - kernel/acct.c:SyS_acct
  - fs/file_table.c:__fput
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:path_lookupat
  - fs/namei.c:link_path_walk
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/libfs.c:simple_release_fs
  - fs/libfs.c:simple_pin_fs
  - fs/fhandle.c:do_handle_open
  - fs/devpts/inode.c:devpts_mntget
  - fs/devpts/inode.c:devpts_mntget
  - drivers/tty/pty.c:ptm_open_peer
```
**Symbols:**

```
ffffffff81276370-ffffffff812763a4: mntput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void mntput(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8129bff5)
Location: fs/namespace.c:1248
Inline: True
Inline callers:
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:drop_mountpoint
Direct callers:
  - kernel/acct.c:SyS_acct
  - kernel/acct.c:SyS_acct
  - fs/file_table.c:__fput
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:path_lookupat
  - fs/namei.c:link_path_walk
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/libfs.c:simple_release_fs
  - fs/libfs.c:simple_pin_fs
  - fs/fhandle.c:do_handle_open
  - fs/devpts/inode.c:devpts_mntget
  - drivers/tty/pty.c:ptm_open_peer
```
**Symbols:**

```
ffffffff81298cc0-ffffffff81298cf4: mntput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void mntput(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812c2542)
Location: fs/namespace.c:1274
Inline: True
Inline callers:
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:drop_mountpoint
Direct callers:
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - fs/file_table.c:__fput
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:link_path_walk
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/libfs.c:simple_release_fs
  - fs/libfs.c:simple_pin_fs
  - fs/fhandle.c:do_handle_open
  - fs/devpts/inode.c:devpts_mntget
  - drivers/tty/pty.c:ptm_open_peer
```
**Symbols:**

```
ffffffff812beeb0-ffffffff812beee3: mntput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void mntput(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d77e2)
Location: fs/namespace.c:1186
Inline: True
Inline callers:
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:drop_mountpoint
Direct callers:
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - fs/file_table.c:__fput
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/libfs.c:simple_release_fs
  - fs/libfs.c:simple_pin_fs
  - fs/fhandle.c:do_handle_open
  - fs/devpts/inode.c:devpts_mntget
  - drivers/tty/pty.c:ptm_open_peer
```
**Symbols:**

```
ffffffff812d4180-ffffffff812d41b3: mntput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void mntput(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f5c66)
Location: fs/namespace.c:1196
Inline: True
Inline callers:
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
Direct callers:
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - fs/file_table.c:__fput
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/libfs.c:simple_release_fs
  - fs/libfs.c:simple_pin_fs
  - fs/fhandle.c:do_handle_open
  - fs/devpts/inode.c:devpts_mntget
  - drivers/tty/pty.c:ptm_open_peer
```
**Symbols:**

```
ffffffff812f1220-ffffffff812f1253: mntput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void mntput(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff813077e6)
Location: fs/namespace.c:1196
Inline: True
Inline callers:
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
Direct callers:
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - fs/file_table.c:__fput
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/libfs.c:simple_release_fs
  - fs/libfs.c:simple_pin_fs
  - fs/fhandle.c:do_handle_open
  - fs/devpts/inode.c:devpts_mntget
  - drivers/tty/pty.c:ptm_open_peer
```
**Symbols:**

```
ffffffff81302dc0-ffffffff81302df3: mntput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void mntput(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133c7f2)
Location: fs/namespace.c:1212
Inline: True
Inline callers:
  - fs/namespace.c:kern_unmount_array
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount_fc
  - fs/namespace.c:do_new_mount_fc
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:lookup_mnt
Direct callers:
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - fs/file_table.c:__fput
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_tmpfile
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:follow_dotdot
  - fs/namei.c:step_into
  - fs/namei.c:step_into
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:choose_mountpoint
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/libfs.c:simple_release_fs
  - fs/libfs.c:simple_pin_fs
  - fs/fhandle.c:handle_to_path
  - fs/devpts/inode.c:devpts_mntget
  - drivers/tty/pty.c:ptm_open_peer
```
**Symbols:**

```
ffffffff8133c770-ffffffff8133c7a3: mntput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void mntput(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff813486b2)
Location: fs/namespace.c:1215
Inline: True
Inline callers:
  - fs/namespace.c:kern_unmount_array
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount_fc
  - fs/namespace.c:do_new_mount_fc
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:lookup_mnt
Direct callers:
  - kernel/usermode_driver.c:blob_to_mnt
  - kernel/usermode_driver.c:blob_to_mnt
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - fs/file_table.c:__fput
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_tmpfile
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:follow_dotdot
  - fs/namei.c:step_into
  - fs/namei.c:step_into
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:choose_mountpoint
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/libfs.c:simple_release_fs
  - fs/libfs.c:simple_pin_fs
  - fs/fhandle.c:handle_to_path
  - fs/devpts/inode.c:devpts_mntget
  - drivers/tty/pty.c:ptm_open_peer
```
**Symbols:**

```
ffffffff81348630-ffffffff81348663: mntput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void mntput(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134ea82)
Location: fs/namespace.c:1225
Inline: True
Inline callers:
  - fs/namespace.c:kern_unmount_array
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:__do_sys_open_tree
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:lookup_mnt
Direct callers:
  - kernel/usermode_driver.c:umd_load_blob
  - kernel/usermode_driver.c:umd_load_blob
  - kernel/usermode_driver.c:umd_load_blob
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - fs/file_table.c:__fput
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:step_into
  - fs/namei.c:step_into
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/libfs.c:simple_release_fs
  - fs/libfs.c:simple_pin_fs
  - fs/fhandle.c:handle_to_path
  - fs/devpts/inode.c:devpts_mntget
  - drivers/tty/pty.c:ptm_open_peer
```
**Symbols:**

```
ffffffff8134ea00-ffffffff8134ea33: mntput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void mntput(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8139cae2)
Location: fs/namespace.c:1234
Inline: True
Inline callers:
  - fs/namespace.c:kern_unmount_array
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:__do_sys_open_tree
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:lookup_mnt
Direct callers:
  - kernel/usermode_driver.c:umd_load_blob
  - kernel/usermode_driver.c:umd_load_blob
  - kernel/usermode_driver.c:umd_load_blob
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - fs/file_table.c:__fput
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
  - fs/namei.c:do_mknodat
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:step_into
  - fs/namei.c:step_into
  - fs/namei.c:step_into
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/libfs.c:simple_release_fs
  - fs/libfs.c:simple_pin_fs
  - fs/fhandle.c:handle_to_path
  - fs/devpts/inode.c:devpts_mntget
  - drivers/tty/pty.c:ptm_open_peer
```
**Symbols:**

```
ffffffff8139ca60-ffffffff8139ca93: mntput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void mntput(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8141f9e0)
Location: fs/namespace.c:1275
Inline: True
Inline callers:
  - fs/namespace.c:kern_unmount_array
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:lookup_mnt
Direct callers:
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - fs/file_table.c:__fput
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
  - fs/namei.c:do_mknodat
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
  - fs/namei.c:step_into
  - fs/namei.c:step_into
  - fs/namei.c:step_into
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/libfs.c:simple_release_fs
  - fs/libfs.c:simple_pin_fs
  - fs/fhandle.c:handle_to_path
  - fs/devpts/inode.c:devpts_mntget
  - drivers/tty/pty.c:ptm_open_peer
```
**Symbols:**

```
ffffffff8141f950-ffffffff8141f997: mntput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void mntput(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814abf10)
Location: fs/namespace.c:1380
Inline: True
Inline callers:
  - fs/namespace.c:kern_unmount_array
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:lookup_mnt
Direct callers:
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - fs/file_table.c:__fput
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
  - fs/namei.c:do_mknodat
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
  - fs/namei.c:step_into
  - fs/namei.c:step_into
  - fs/namei.c:step_into
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/libfs.c:simple_release_fs
  - fs/libfs.c:simple_pin_fs
  - fs/fhandle.c:handle_to_path
  - fs/devpts/inode.c:devpts_mntget
  - drivers/tty/pty.c:ptm_open_peer
```
**Symbols:**

```
ffffffff814abe70-ffffffff814abeb7: mntput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void mntput(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814e0cd0)
Location: fs/namespace.c:1343
Inline: True
Inline callers:
  - fs/namespace.c:kern_unmount_array
  - fs/namespace.c:kern_unmount
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:lookup_mnt
Direct callers:
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - fs/file_table.c:__fput
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
  - fs/namei.c:do_mknodat
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
  - fs/namei.c:step_into
  - fs/namei.c:step_into
  - fs/namei.c:step_into
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/libfs.c:simple_release_fs
  - fs/libfs.c:simple_pin_fs
  - fs/fhandle.c:do_handle_open
  - fs/devpts/inode.c:devpts_mntget
  - ipc/namespace.c:free_ipc
  - drivers/tty/pty.c:ptm_open_peer
```
**Symbols:**

```
ffffffff814e0c30-ffffffff814e0c77: mntput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void mntput(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81514da0)
Location: fs/namespace.c:1356
Inline: True
Inline callers:
  - fs/namespace.c:kern_unmount_array
  - fs/namespace.c:kern_unmount
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:lookup_mnt
Direct callers:
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - fs/file_table.c:__fput
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
  - fs/namei.c:do_mknodat
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:__kern_path_locked
  - fs/namei.c:__kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
  - fs/namei.c:step_into
  - fs/namei.c:step_into
  - fs/namei.c:step_into
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:__traverse_mounts
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/libfs.c:simple_release_fs
  - fs/libfs.c:simple_pin_fs
  - fs/fhandle.c:handle_to_path
  - fs/devpts/inode.c:devpts_mntget
  - ipc/namespace.c:free_ipc
  - drivers/tty/pty.c:ptm_open_peer
```
**Symbols:**

```
ffffffff81514d00-ffffffff81514d47: mntput (STB_GLOBAL)
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
void mntput(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103bac98)
Location: fs/namespace.c:1196
Inline: True
Inline callers:
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:__arm64_sys_open_tree
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
Direct callers:
  - kernel/acct.c:__arm64_sys_acct
  - kernel/acct.c:__arm64_sys_acct
  - fs/file_table.c:__fput
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/libfs.c:simple_release_fs
  - fs/libfs.c:simple_pin_fs
  - fs/fhandle.c:do_handle_open
  - fs/devpts/inode.c:devpts_mntget
  - drivers/tty/pty.c:ptm_open_peer
```
**Symbols:**

```
ffff8000103b6198-ffff8000103b61d8: mntput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void mntput(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0598a0c)
Location: fs/namespace.c:1196
Inline: True
Inline callers:
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:__se_sys_open_tree
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
Direct callers:
  - kernel/acct.c:__se_sys_acct
  - kernel/acct.c:__se_sys_acct
  - fs/file_table.c:__fput
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:kern_path_locked
  - fs/namei.c:path_lookupat
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/libfs.c:simple_release_fs
  - fs/libfs.c:simple_pin_fs
  - fs/fhandle.c:__se_sys_open_by_handle_at
  - fs/devpts/inode.c:devpts_mntget
  - drivers/tty/pty.c:ptm_open_peer
```
**Symbols:**

```
c05944d4-c059450c: mntput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void mntput(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004b8564)
Location: fs/namespace.c:1196
Inline: True
Inline callers:
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:__se_sys_open_tree
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
Direct callers:
  - kernel/acct.c:__se_sys_acct
  - kernel/acct.c:__se_sys_acct
  - fs/file_table.c:__fput
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/libfs.c:simple_release_fs
  - fs/libfs.c:simple_pin_fs
  - fs/fhandle.c:do_handle_open
  - fs/devpts/inode.c:devpts_mntget
  - drivers/tty/pty.c:ptm_open_peer
```
**Symbols:**

```
c0000000004b2700-c0000000004b273c: mntput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void mntput(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe00027ab94)
Location: fs/namespace.c:1196
Inline: True
Inline callers:
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:__se_sys_open_tree
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
Direct callers:
  - kernel/acct.c:__se_sys_acct
  - kernel/acct.c:__se_sys_acct
  - fs/file_table.c:__fput
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:path_lookupat
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/libfs.c:simple_release_fs
  - fs/libfs.c:simple_pin_fs
  - fs/fhandle.c:__se_sys_open_by_handle_at
  - fs/devpts/inode.c:devpts_mntget
  - drivers/tty/pty.c:ptm_open_peer
```
**Symbols:**

```
ffffffe000278ea8-ffffffe000278ee2: mntput (STB_GLOBAL)
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
void mntput(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ffdc6)
Location: fs/namespace.c:1196
Inline: True
Inline callers:
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
Direct callers:
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - fs/file_table.c:__fput
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/libfs.c:simple_release_fs
  - fs/libfs.c:simple_pin_fs
  - fs/fhandle.c:do_handle_open
  - fs/devpts/inode.c:devpts_mntget
  - drivers/tty/pty.c:ptm_open_peer
```
**Symbols:**

```
ffffffff812fb3a0-ffffffff812fb3d3: mntput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void mntput(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f09e6)
Location: fs/namespace.c:1196
Inline: True
Inline callers:
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
Direct callers:
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - fs/file_table.c:__fput
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/libfs.c:simple_release_fs
  - fs/libfs.c:simple_pin_fs
  - fs/fhandle.c:do_handle_open
  - fs/devpts/inode.c:devpts_mntget
  - drivers/tty/pty.c:ptm_open_peer
```
**Symbols:**

```
ffffffff812ebfc0-ffffffff812ebff3: mntput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void mntput(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fdbb6)
Location: fs/namespace.c:1196
Inline: True
Inline callers:
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
Direct callers:
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - fs/file_table.c:__fput
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/libfs.c:simple_release_fs
  - fs/libfs.c:simple_pin_fs
  - fs/fhandle.c:do_handle_open
  - fs/devpts/inode.c:devpts_mntget
  - drivers/tty/pty.c:ptm_open_peer
```
**Symbols:**

```
ffffffff812f9190-ffffffff812f91c3: mntput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void mntput(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8130eef6)
Location: fs/namespace.c:1196
Inline: True
Inline callers:
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
Direct callers:
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - fs/file_table.c:__fput
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:kern_path_locked
  - fs/namei.c:kern_path_locked
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_managed
  - fs/namei.c:follow_up
  - fs/namei.c:nd_jump_link
  - fs/namei.c:nd_jump_root
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/namei.c:terminate_walk
  - fs/libfs.c:simple_release_fs
  - fs/libfs.c:simple_pin_fs
  - fs/fhandle.c:do_handle_open
  - fs/devpts/inode.c:devpts_mntget
  - drivers/tty/pty.c:ptm_open_peer
```
**Symbols:**

```
ffffffff8130a4b0-ffffffff8130a4e3: mntput (STB_GLOBAL)
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
