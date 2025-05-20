# Function: <code>kern_path</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kern_path(const char *name, unsigned int flags, struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8121c360)
Location: fs/namei.c:2252
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/bpf/inode.c:bpf_obj_get_user
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/ext4/super.c:handle_mount_opt
  - fs/ecryptfs/main.c:ecryptfs_mount
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_new_mount
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff8121c360-ffffffff8121c390: kern_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kern_path(const char *name, unsigned int flags, struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812437e0)
Location: fs/namei.c:2389
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/events/core.c:perf_event_set_addr_filter
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/ext4/super.c:handle_mount_opt
  - fs/ecryptfs/main.c:ecryptfs_mount
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff812437e0-ffffffff81243810: kern_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kern_path(const char *name, unsigned int flags, struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81256760)
Location: fs/namei.c:2378
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/events/core.c:perf_event_set_addr_filter
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/ext4/super.c:handle_mount_opt
  - fs/ecryptfs/main.c:ecryptfs_mount
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff81256760-ffffffff81256790: kern_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kern_path(const char *name, unsigned int flags, struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81262900)
Location: fs/namei.c:2423
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/events/core.c:perf_event_parse_addr_filter
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/configfs/symlink.c:configfs_symlink
  - fs/ext4/super.c:handle_mount_opt
  - fs/ecryptfs/main.c:ecryptfs_mount
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff81262900-ffffffff81262930: kern_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kern_path(const char *name, unsigned int flags, struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81285150)
Location: fs/namei.c:2421
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/events/core.c:perf_event_parse_addr_filter
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/configfs/symlink.c:configfs_symlink
  - fs/ext4/super.c:handle_mount_opt
  - fs/ecryptfs/main.c:ecryptfs_mount
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff81285150-ffffffff81285180: kern_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kern_path(const char *name, unsigned int flags, struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ac270)
Location: fs/namei.c:2408
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/events/core.c:perf_event_parse_addr_filter
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/configfs/symlink.c:configfs_symlink
  - fs/ext4/super.c:handle_mount_opt
  - fs/ecryptfs/main.c:ecryptfs_mount
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff812ac270-ffffffff812ac2a8: kern_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kern_path(const char *name, unsigned int flags, struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812c1370)
Location: fs/namei.c:2432
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/events/core.c:perf_event_parse_addr_filter
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/configfs/symlink.c:configfs_symlink
  - fs/ext4/super.c:handle_mount_opt
  - fs/ecryptfs/main.c:ecryptfs_mount
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff812c1370-ffffffff812c13a8: kern_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kern_path(const char *name, unsigned int flags, struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812de5d0)
Location: fs/namei.c:2430
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/events/core.c:perf_event_set_filter
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/configfs/symlink.c:configfs_symlink
  - fs/ext4/super.c:handle_mount_opt
  - fs/ecryptfs/main.c:ecryptfs_mount
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff812de5d0-ffffffff812de604: kern_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kern_path(const char *name, unsigned int flags, struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f00e0)
Location: fs/namei.c:2423
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/events/core.c:perf_event_set_filter
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/configfs/symlink.c:configfs_symlink
  - fs/ext4/super.c:handle_mount_opt
  - fs/ecryptfs/main.c:ecryptfs_mount
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff812f00e0-ffffffff812f0114: kern_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kern_path(const char *name, unsigned int flags, struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81328440)
Location: fs/namei.c:2451
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/events/core.c:perf_event_parse_addr_filter
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/configfs/symlink.c:configfs_symlink
  - fs/ext4/super.c:handle_mount_opt
  - fs/ecryptfs/main.c:ecryptfs_mount
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff81328440-ffffffff81328474: kern_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kern_path(const char *name, unsigned int flags, struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81333600)
Location: fs/namei.c:2449
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/events/core.c:perf_event_parse_addr_filter
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/init.c:init_utimes
  - fs/init.c:init_link
  - fs/init.c:init_stat
  - fs/init.c:init_eaccess
  - fs/init.c:init_chmod
  - fs/init.c:init_chown
  - fs/init.c:init_chroot
  - fs/init.c:init_chdir
  - fs/init.c:init_umount
  - fs/init.c:init_mount
  - fs/block_dev.c:lookup_bdev
  - fs/configfs/symlink.c:configfs_symlink
  - fs/ext4/super.c:handle_mount_opt
  - fs/ecryptfs/main.c:ecryptfs_mount
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff81333600-ffffffff81333634: kern_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kern_path(const char *name, unsigned int flags, struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813396c0)
Location: fs/namei.c:2539
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/events/core.c:perf_event_parse_addr_filter
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/init.c:init_utimes
  - fs/init.c:init_link
  - fs/init.c:init_stat
  - fs/init.c:init_eaccess
  - fs/init.c:init_chmod
  - fs/init.c:init_chown
  - fs/init.c:init_chroot
  - fs/init.c:init_chdir
  - fs/init.c:init_umount
  - fs/init.c:init_mount
  - fs/block_dev.c:lookup_bdev
  - fs/configfs/symlink.c:configfs_symlink
  - fs/ext4/super.c:handle_mount_opt
  - fs/ecryptfs/main.c:ecryptfs_mount
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff813396c0-ffffffff813396f4: kern_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kern_path(const char *name, unsigned int flags, struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81386d30)
Location: fs/namei.c:2565
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/events/core.c:perf_event_parse_addr_filter
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/init.c:init_utimes
  - fs/init.c:init_link
  - fs/init.c:init_stat
  - fs/init.c:init_eaccess
  - fs/init.c:init_chmod
  - fs/init.c:init_chown
  - fs/init.c:init_chroot
  - fs/init.c:init_chdir
  - fs/init.c:init_umount
  - fs/init.c:init_mount
  - fs/configfs/symlink.c:configfs_symlink
  - fs/ext4/super.c:handle_mount_opt
  - fs/ecryptfs/main.c:ecryptfs_mount
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
  - block/bdev.c:lookup_bdev
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff81386d30-ffffffff81386d79: kern_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kern_path(const char *name, unsigned int flags, struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81407a80)
Location: fs/namei.c:2611
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/events/core.c:perf_event_parse_addr_filter
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/init.c:init_utimes
  - fs/init.c:init_link
  - fs/init.c:init_stat
  - fs/init.c:init_eaccess
  - fs/init.c:init_chmod
  - fs/init.c:init_chown
  - fs/init.c:init_chroot
  - fs/init.c:init_chdir
  - fs/init.c:init_umount
  - fs/init.c:init_mount
  - fs/configfs/symlink.c:configfs_symlink
  - fs/ecryptfs/main.c:ecryptfs_mount
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
  - block/bdev.c:lookup_bdev
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff81407a80-ffffffff81407ad6: kern_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kern_path(const char *name, unsigned int flags, struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81491f00)
Location: fs/namei.c:2590
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/events/core.c:perf_event_parse_addr_filter
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/init.c:init_utimes
  - fs/init.c:init_link
  - fs/init.c:init_stat
  - fs/init.c:init_eaccess
  - fs/init.c:init_chmod
  - fs/init.c:init_chown
  - fs/init.c:init_chroot
  - fs/init.c:init_chdir
  - fs/init.c:init_umount
  - fs/init.c:init_mount
  - fs/configfs/symlink.c:configfs_symlink
  - fs/ecryptfs/main.c:ecryptfs_mount
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
  - block/bdev.c:lookup_bdev
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff81491f00-ffffffff81491f56: kern_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kern_path(const char *name, unsigned int flags, struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c6f40)
Location: fs/namei.c:2603
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/events/core.c:perf_event_parse_addr_filter
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/init.c:init_utimes
  - fs/init.c:init_link
  - fs/init.c:init_stat
  - fs/init.c:init_eaccess
  - fs/init.c:init_chmod
  - fs/init.c:init_chown
  - fs/init.c:init_chroot
  - fs/init.c:init_chdir
  - fs/init.c:init_umount
  - fs/init.c:init_mount
  - fs/configfs/symlink.c:configfs_symlink
  - fs/ecryptfs/main.c:ecryptfs_mount
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount_old
  - security/apparmor/mount.c:aa_bind_mount
  - block/bdev.c:lookup_bdev
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff814c6f40-ffffffff814c6f96: kern_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kern_path(const char *name, unsigned int flags, struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f9890)
Location: fs/namei.c:2620
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/trace/bpf_trace.c:bpf_uprobe_multi_link_attach
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/events/core.c:perf_event_parse_addr_filter
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/init.c:init_utimes
  - fs/init.c:init_link
  - fs/init.c:init_stat
  - fs/init.c:init_eaccess
  - fs/init.c:init_chmod
  - fs/init.c:init_chown
  - fs/init.c:init_chroot
  - fs/init.c:init_chdir
  - fs/init.c:init_umount
  - fs/init.c:init_mount
  - fs/configfs/symlink.c:configfs_symlink
  - fs/ecryptfs/main.c:ecryptfs_mount
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount_old
  - security/apparmor/mount.c:aa_bind_mount
  - block/bdev.c:lookup_bdev
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff814f9890-ffffffff814f98e6: kern_path (STB_GLOBAL)
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
int kern_path(const char *name, unsigned int flags, struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff8000103997b8)
Location: fs/namei.c:2423
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/events/core.c:perf_event_set_filter
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/configfs/symlink.c:configfs_symlink
  - fs/ext4/super.c:handle_mount_opt
  - fs/ecryptfs/main.c:ecryptfs_mount
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffff8000103997b8-ffff80001039980c: kern_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kern_path(const char *name, unsigned int flags, struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c057fd70)
Location: fs/namei.c:2423
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/events/core.c:perf_event_set_filter
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/configfs/symlink.c:configfs_symlink
  - fs/ext4/super.c:handle_mount_opt
  - fs/ecryptfs/main.c:ecryptfs_mount
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
c057fd70-c057fdb8: kern_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kern_path(const char *name, unsigned int flags, struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c000000000494160)
Location: fs/namei.c:2423
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/events/core.c:perf_event_set_filter
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/configfs/symlink.c:configfs_symlink
  - fs/ext4/super.c:handle_mount_opt
  - fs/ecryptfs/main.c:ecryptfs_mount
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
c000000000494160-c0000000004941b4: kern_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int kern_path(const char *name, unsigned int flags, struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe0002670fe)
Location: fs/namei.c:2423
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/events/core.c:perf_event_set_filter
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/configfs/symlink.c:configfs_symlink
  - fs/ext4/super.c:handle_mount_opt
  - fs/ecryptfs/main.c:ecryptfs_mount
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffe0002670fe-ffffffe000267148: kern_path (STB_GLOBAL)
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
int kern_path(const char *name, unsigned int flags, struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e86c0)
Location: fs/namei.c:2423
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/events/core.c:perf_event_set_filter
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/configfs/symlink.c:configfs_symlink
  - fs/ext4/super.c:handle_mount_opt
  - fs/ecryptfs/main.c:ecryptfs_mount
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff812e86c0-ffffffff812e86f4: kern_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kern_path(const char *name, unsigned int flags, struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d9300)
Location: fs/namei.c:2423
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/events/core.c:perf_event_set_filter
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/configfs/symlink.c:configfs_symlink
  - fs/ext4/super.c:handle_mount_opt
  - fs/ecryptfs/main.c:ecryptfs_mount
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff812d9300-ffffffff812d9334: kern_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kern_path(const char *name, unsigned int flags, struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e64d0)
Location: fs/namei.c:2423
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/events/core.c:perf_event_set_filter
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/configfs/symlink.c:configfs_symlink
  - fs/ext4/super.c:handle_mount_opt
  - fs/ecryptfs/main.c:ecryptfs_mount
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff812e64d0-ffffffff812e6504: kern_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kern_path(const char *name, unsigned int flags, struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f7450)
Location: fs/namei.c:2423
Inline: False
Direct callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/events/core.c:perf_event_set_filter
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/configfs/symlink.c:configfs_symlink
  - fs/ext4/super.c:handle_mount_opt
  - fs/ecryptfs/main.c:ecryptfs_mount
  - security/tomoyo/load_policy.c:tomoyo_load_policy
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff812f7450-ffffffff812f7484: kern_path (STB_GLOBAL)
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
