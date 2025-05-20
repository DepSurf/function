# Function: <code>unlock_mount_hash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8122bbcc)
Location: fs/mount.h:115
Inline: True
Inline callers:
  - fs/namespace.c:may_umount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:vfs_kern_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:sb_prepare_remount_readonly
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:SyS_pivot_root
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812587f5)
Location: fs/mount.h:115
Inline: True
Inline callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_kern_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8126bcb3)
Location: fs/mount.h:123
Inline: True
Inline callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_kern_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81279495)
Location: fs/mount.h:124
Inline: True
Inline callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:sb_prepare_remount_readonly
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8129bed5)
Location: fs/mount.h:125
Inline: True
Inline callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:sb_prepare_remount_readonly
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812c1ff8)
Location: fs/mount.h:125
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:may_umount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:sb_prepare_remount_readonly
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d7298)
Location: fs/mount.h:125
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:may_umount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:sb_prepare_remount_readonly
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f56fa)
Location: fs/mount.h:127
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:may_umount
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8130727a)
Location: fs/mount.h:127
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:may_umount
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81340ad8)
Location: fs/mount.h:133
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_reconfigure_mnt
  - fs/namespace.c:do_reconfigure_mnt
  - fs/namespace.c:do_reconfigure_mnt
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134cb68)
Location: fs/mount.h:132
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_reconfigure_mnt
  - fs/namespace.c:do_reconfigure_mnt
  - fs/namespace.c:do_reconfigure_mnt
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81353750)
Location: fs/namespace.c:105
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:__do_sys_open_tree
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff813a1ba0)
Location: fs/namespace.c:105
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_set_group
  - fs/namespace.c:__do_sys_open_tree
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void unlock_mount_hash();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81424f08)
Location: fs/namespace.c:106
Inline: True
Inline callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_set_group
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:sb_prepare_remount_readonly
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
```
**Symbols:**

```
ffffffff8141cd90-ffffffff8141cdaf: unlock_mount_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void unlock_mount_hash();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814b1646)
Location: fs/namespace.c:123
Inline: True
Inline callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_set_group
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:__legitimize_mnt
  - fs/namespace.c:__legitimize_mnt
  - fs/namespace.c:sb_prepare_remount_readonly
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
```
**Symbols:**

```
ffffffff814a8f90-ffffffff814a8faf: unlock_mount_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void unlock_mount_hash();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814e6686)
Location: fs/namespace.c:107
Inline: True
Inline callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_set_group
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:__legitimize_mnt
  - fs/namespace.c:__legitimize_mnt
  - fs/namespace.c:sb_prepare_remount_readonly
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
```
**Symbols:**

```
ffffffff814ddf60-ffffffff814ddf7f: unlock_mount_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void unlock_mount_hash();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8151a4c2)
Location: fs/namespace.c:111
Inline: True
Inline callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_set_group
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:__legitimize_mnt
  - fs/namespace.c:__legitimize_mnt
  - fs/namespace.c:sb_prepare_remount_readonly
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
```
**Symbols:**

```
ffffffff815109b0-ffffffff815109cf: unlock_mount_hash (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103baae8)
Location: fs/mount.h:127
Inline: True
Inline callers:
  - fs/namespace.c:__arm64_sys_pivot_root
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:__arm64_sys_open_tree
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:may_umount
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void unlock_mount_hash();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0597c24)
Location: fs/mount.h:127
Inline: True
Inline callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:set_mount_attributes
  - fs/namespace.c:__se_sys_open_tree
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:sb_prepare_remount_readonly
Direct callers:
  - fs/namespace.c:__se_sys_pivot_root
```
**Symbols:**

```
c0592454-c0592494: unlock_mount_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004b836c)
Location: fs/mount.h:127
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:__se_sys_open_tree
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:may_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe00027cf1a)
Location: fs/mount.h:127
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:__se_sys_open_tree
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:may_umount
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ff85a)
Location: fs/mount.h:127
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:may_umount
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f047a)
Location: fs/mount.h:127
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:may_umount
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fd64a)
Location: fs/mount.h:127
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:may_umount
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8130e9a8)
Location: fs/mount.h:127
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:may_umount
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
