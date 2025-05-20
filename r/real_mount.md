# Function: <code>real_mount</code>

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
In fs/namei.c (0)
Location: fs/mount.h:72
Inline: True
```
```
In fs/dcache.c (ffffffff81224fed)
Location: fs/mount.h:72
Inline: True
Inline callers:
  - fs/dcache.c:prepend_path
```
```
In fs/namespace.c (ffffffff8122be08)
Location: fs/mount.h:72
Inline: True
Inline callers:
  - fs/namespace.c:SyS_oldumount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:mount_subtree
```
```
In fs/fs_pin.c (0)
Location: fs/mount.h:72
Inline: True
```
```
In fs/proc_namespace.c (0)
Location: fs/mount.h:72
Inline: True
```
```
In fs/notify/fsnotify.c (ffffffff8124f6a6)
Location: fs/mount.h:72
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/vfsmount_mark.c (0)
Location: fs/mount.h:72
Inline: True
```
```
In fs/notify/fdinfo.c (0)
Location: fs/mount.h:72
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: fs/mount.h:72
Inline: True
```
```
In fs/fhandle.c (0)
Location: fs/mount.h:72
Inline: True
```
```
In fs/proc/fd.c (0)
Location: fs/mount.h:72
Inline: True
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
In fs/namei.c (ffffffff8123e2d4)
Location: fs/mount.h:72
Inline: True
```
```
In fs/dcache.c (ffffffff8124b705)
Location: fs/mount.h:72
Inline: True
Inline callers:
  - fs/dcache.c:prepend_path
```
```
In fs/namespace.c (ffffffff812586a2)
Location: fs/mount.h:72
Inline: True
Inline callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:path_is_under
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:SyS_oldumount
  - fs/namespace.c:may_umount
  - fs/namespace.c:mnt_clone_internal
```
```
In fs/fs_pin.c (0)
Location: fs/mount.h:72
Inline: True
```
```
In fs/proc_namespace.c (ffffffff81277639)
Location: fs/mount.h:72
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_mountinfo
```
```
In fs/notify/fsnotify.c (ffffffff81277df9)
Location: fs/mount.h:72
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/vfsmount_mark.c (0)
Location: fs/mount.h:72
Inline: True
```
```
In fs/notify/fdinfo.c (0)
Location: fs/mount.h:72
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: fs/mount.h:72
Inline: True
```
```
In fs/fhandle.c (0)
Location: fs/mount.h:72
Inline: True
```
```
In fs/proc/fd.c (0)
Location: fs/mount.h:72
Inline: True
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
In fs/namei.c (ffffffff812510b4)
Location: fs/mount.h:75
Inline: True
```
```
In fs/dcache.c (ffffffff8125e6e5)
Location: fs/mount.h:75
Inline: True
Inline callers:
  - fs/dcache.c:prepend_path
```
```
In fs/namespace.c (ffffffff8126bb33)
Location: fs/mount.h:75
Inline: True
Inline callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:path_is_under
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:SyS_oldumount
  - fs/namespace.c:may_umount
  - fs/namespace.c:mnt_clone_internal
```
```
In fs/fs_pin.c (0)
Location: fs/mount.h:75
Inline: True
```
```
In fs/proc_namespace.c (ffffffff8128b326)
Location: fs/mount.h:75
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_mountinfo
```
```
In fs/notify/fsnotify.c (ffffffff8128bad9)
Location: fs/mount.h:75
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/vfsmount_mark.c (0)
Location: fs/mount.h:75
Inline: True
```
```
In fs/notify/fdinfo.c (0)
Location: fs/mount.h:75
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: fs/mount.h:75
Inline: True
```
```
In fs/fhandle.c (0)
Location: fs/mount.h:75
Inline: True
```
```
In fs/proc/fd.c (0)
Location: fs/mount.h:75
Inline: True
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
In fs/namei.c (ffffffff8125cffe)
Location: fs/mount.h:76
Inline: True
```
```
In fs/dcache.c (ffffffff8126bf4a)
Location: fs/mount.h:76
Inline: True
Inline callers:
  - fs/dcache.c:prepend_path
```
```
In fs/namespace.c (ffffffff81279305)
Location: fs/mount.h:76
Inline: True
Inline callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:path_is_under
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:SyS_oldumount
  - fs/namespace.c:may_umount
  - fs/namespace.c:mnt_clone_internal
```
```
In fs/fs_pin.c (0)
Location: fs/mount.h:76
Inline: True
```
```
In fs/proc_namespace.c (ffffffff81298126)
Location: fs/mount.h:76
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_mountinfo
```
```
In fs/notify/fsnotify.c (ffffffff8129856d)
Location: fs/mount.h:76
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (0)
Location: fs/mount.h:76
Inline: True
```
```
In fs/notify/fdinfo.c (0)
Location: fs/mount.h:76
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: fs/mount.h:76
Inline: True
```
```
In fs/fhandle.c (0)
Location: fs/mount.h:76
Inline: True
```
```
In fs/proc/fd.c (0)
Location: fs/mount.h:76
Inline: True
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
In fs/namei.c (ffffffff8127e59e)
Location: fs/mount.h:77
Inline: True
Inline callers:
  - fs/namei.c:follow_up
```
```
In fs/dcache.c (ffffffff8128f83a)
Location: fs/mount.h:77
Inline: True
Inline callers:
  - fs/dcache.c:prepend_path
```
```
In fs/namespace.c (ffffffff8129bd45)
Location: fs/mount.h:77
Inline: True
Inline callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:path_is_under
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:SyS_oldumount
  - fs/namespace.c:may_umount
  - fs/namespace.c:mnt_clone_internal
```
```
In fs/fs_pin.c (0)
Location: fs/mount.h:77
Inline: True
```
```
In fs/proc_namespace.c (ffffffff812bb419)
Location: fs/mount.h:77
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_mountinfo
```
```
In fs/notify/fsnotify.c (ffffffff812bb884)
Location: fs/mount.h:77
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (0)
Location: fs/mount.h:77
Inline: True
```
```
In fs/notify/fdinfo.c (0)
Location: fs/mount.h:77
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: fs/mount.h:77
Inline: True
```
```
In fs/fhandle.c (0)
Location: fs/mount.h:77
Inline: True
```
```
In fs/proc/fd.c (0)
Location: fs/mount.h:77
Inline: True
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
In fs/namei.c (ffffffff812aa836)
Location: fs/mount.h:77
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:follow_up
```
```
In fs/namespace.c (ffffffff812c282d)
Location: fs/mount.h:77
Inline: True
Inline callers:
  - fs/namespace.c:mnt_may_suid
  - fs/namespace.c:our_mnt
  - fs/namespace.c:kern_mount_data
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:path_is_under
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_set_expiry
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:may_umount
  - fs/namespace.c:mnt_clone_internal
  - fs/namespace.c:is_current_mnt_ns
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:__mnt_want_write
  - fs/namespace.c:drop_mountpoint
```
```
In fs/d_path.c (ffffffff812d391d)
Location: fs/mount.h:77
Inline: True
```
```
In fs/fs_pin.c (ffffffff812d5785)
Location: fs/mount.h:77
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_insert_group
```
```
In fs/proc_namespace.c (ffffffff812e3bda)
Location: fs/mount.h:77
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
```
```
In fs/notify/fsnotify.c (ffffffff812e44c7)
Location: fs/mount.h:77
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:__fsnotify_vfsmount_delete
```
```
In fs/notify/mark.c (ffffffff812e60d9)
Location: fs/mount.h:77
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/notify/fdinfo.c (ffffffff812e6367)
Location: fs/mount.h:77
Inline: True
Inline callers:
  - fs/notify/fdinfo.c:fanotify_fdinfo
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff812e8a3f)
Location: fs/mount.h:77
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/fhandle.c (ffffffff8130d7fe)
Location: fs/mount.h:77
Inline: True
```
```
In fs/proc/fd.c (ffffffff81323327)
Location: fs/mount.h:77
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
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
In fs/namei.c (ffffffff812bba0b)
Location: fs/mount.h:77
Inline: True
Inline callers:
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_up
```
```
In fs/namespace.c (ffffffff812d7acd)
Location: fs/mount.h:77
Inline: True
Inline callers:
  - fs/namespace.c:mnt_may_suid
  - fs/namespace.c:our_mnt
  - fs/namespace.c:kern_mount_data
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:path_is_under
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_set_expiry
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:may_umount
  - fs/namespace.c:mnt_clone_internal
  - fs/namespace.c:is_current_mnt_ns
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:__mnt_want_write
  - fs/namespace.c:drop_mountpoint
```
```
In fs/d_path.c (ffffffff812e8b6d)
Location: fs/mount.h:77
Inline: True
```
```
In fs/fs_pin.c (ffffffff812eab55)
Location: fs/mount.h:77
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_insert_group
```
```
In fs/proc_namespace.c (ffffffff812f885a)
Location: fs/mount.h:77
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
```
```
In fs/notify/fsnotify.c (ffffffff812f9344)
Location: fs/mount.h:77
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:__fsnotify_vfsmount_delete
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff812fdfc5)
Location: fs/mount.h:77
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/fhandle.c (ffffffff81322d5e)
Location: fs/mount.h:77
Inline: True
```
```
In fs/proc/fd.c (ffffffff8133a5f7)
Location: fs/mount.h:77
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
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
In fs/namei.c (ffffffff812d7d29)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_up
```
```
In fs/namespace.c (ffffffff812f5fad)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/namespace.c:mnt_may_suid
  - fs/namespace.c:our_mnt
  - fs/namespace.c:kern_mount
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:path_is_under
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_set_expiry
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:may_umount
  - fs/namespace.c:mnt_clone_internal
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:is_current_mnt_ns
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:__mnt_want_write
  - fs/namespace.c:mnt_init
```
```
In fs/d_path.c (ffffffff81307547)
Location: fs/mount.h:79
Inline: True
```
```
In fs/fs_pin.c (ffffffff813095e0)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_insert
```
```
In fs/proc_namespace.c (ffffffff81318e8a)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
```
```
In fs/notify/fsnotify.c (ffffffff813196a9)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:__fsnotify_vfsmount_delete
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8131ed1d)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/fhandle.c (ffffffff8134a77d)
Location: fs/mount.h:79
Inline: True
```
```
In fs/proc/fd.c (ffffffff813627b3)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
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
In fs/namei.c (ffffffff812e98a9)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_up
```
```
In fs/namespace.c (ffffffff81307b2d)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/namespace.c:mnt_may_suid
  - fs/namespace.c:our_mnt
  - fs/namespace.c:kern_mount
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:path_is_under
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_set_expiry
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:may_umount
  - fs/namespace.c:mnt_clone_internal
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:is_current_mnt_ns
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:__mnt_want_write
  - fs/namespace.c:mnt_init
```
```
In fs/d_path.c (ffffffff8131a5a7)
Location: fs/mount.h:79
Inline: True
```
```
In fs/fs_pin.c (ffffffff8131c650)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_insert
```
```
In fs/proc_namespace.c (ffffffff8132bcba)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
```
```
In fs/notify/fsnotify.c (ffffffff8132c4d9)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:__fsnotify_vfsmount_delete
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81331ac9)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/fhandle.c (ffffffff81362a1d)
Location: fs/mount.h:79
Inline: True
```
```
In fs/proc/fd.c (ffffffff8137aa13)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
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
In fs/stat.c (ffffffff8131a828)
Location: fs/mount.h:85
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx
```
```
In fs/namei.c (ffffffff813226dc)
Location: fs/mount.h:85
Inline: True
Inline callers:
  - fs/namei.c:follow_dotdot
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_up
```
```
In fs/namespace.c (ffffffff8134100d)
Location: fs/mount.h:85
Inline: True
Inline callers:
  - fs/namespace.c:mnt_may_suid
  - fs/namespace.c:our_mnt
  - fs/namespace.c:kern_unmount_array
  - fs/namespace.c:kern_unmount_array
  - fs/namespace.c:kern_mount
  - fs/namespace.c:init_mount_tree
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:path_is_under
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_set_expiry
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount_fc
  - fs/namespace.c:do_new_mount_fc
  - fs/namespace.c:do_new_mount_fc
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_reconfigure_mnt
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:__do_loopback
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:may_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mnt_clone_internal
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:is_current_mnt_ns
  - fs/namespace.c:lookup_mnt
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:__mnt_want_write
```
```
In fs/d_path.c (ffffffff813544b3)
Location: fs/mount.h:85
Inline: True
Inline callers:
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In fs/fs_pin.c (ffffffff81356390)
Location: fs/mount.h:85
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_insert
```
```
In fs/proc_namespace.c (ffffffff81365b5a)
Location: fs/mount.h:85
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
```
```
In fs/notify/fsnotify.c (ffffffff81366437)
Location: fs/mount.h:85
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:__fsnotify_vfsmount_delete
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8136c4ee)
Location: fs/mount.h:85
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/fhandle.c (ffffffff813a8bd5)
Location: fs/mount.h:85
Inline: True
Inline callers:
  - fs/fhandle.c:do_sys_name_to_handle
```
```
In fs/proc/fd.c (ffffffff813c3ab3)
Location: fs/mount.h:85
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
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
In fs/stat.c (ffffffff81325eb1)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx
```
```
In fs/namei.c (ffffffff8132dc76)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/namei.c:follow_dotdot
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_up
```
```
In fs/namespace.c (ffffffff8134d0fd)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/namespace.c:mnt_may_suid
  - fs/namespace.c:our_mnt
  - fs/namespace.c:kern_unmount_array
  - fs/namespace.c:kern_unmount_array
  - fs/namespace.c:kern_mount
  - fs/namespace.c:init_mount_tree
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:path_is_under
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:mnt_set_expiry
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount_fc
  - fs/namespace.c:do_new_mount_fc
  - fs/namespace.c:do_new_mount_fc
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_reconfigure_mnt
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:__do_loopback
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:path_umount
  - fs/namespace.c:path_umount
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:may_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mnt_clone_internal
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:is_current_mnt_ns
  - fs/namespace.c:lookup_mnt
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:__mnt_want_write
```
```
In fs/d_path.c (ffffffff81360c6d)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/d_path.c:prepend_path
```
```
In fs/fs_pin.c (ffffffff81362cd0)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_insert
```
```
In fs/proc_namespace.c (ffffffff81372a2a)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
```
```
In fs/notify/fsnotify.c (ffffffff813734ce)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:__fsnotify_vfsmount_delete
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81379e33)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/fhandle.c (ffffffff813b9f35)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/fhandle.c:do_sys_name_to_handle
```
```
In fs/proc/fd.c (ffffffff813d5c5e)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
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
In fs/stat.c (ffffffff8132bfc1)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx
```
```
In fs/namei.c (ffffffff81333e9a)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/namei.c:follow_up
```
```
In fs/namespace.c (ffffffff81353cdd)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/namespace.c:mnt_may_suid
  - fs/namespace.c:our_mnt
  - fs/namespace.c:kern_unmount_array
  - fs/namespace.c:kern_unmount_array
  - fs/namespace.c:kern_mount
  - fs/namespace.c:mount_setattr_prepare
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:path_is_under
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:mnt_set_expiry
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:__do_sys_open_tree
  - fs/namespace.c:__do_sys_open_tree
  - fs/namespace.c:__do_loopback
  - fs/namespace.c:iterate_mounts
  - fs/namespace.c:iterate_mounts
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:path_umount
  - fs/namespace.c:path_umount
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:may_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mnt_clone_internal
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:lookup_mnt
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:__mnt_want_write
  - fs/namespace.c:mnt_init
```
```
In fs/d_path.c (ffffffff8136775a)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/d_path.c:prepend_path
```
```
In fs/fs_pin.c (ffffffff81369770)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_insert
```
```
In fs/proc_namespace.c (ffffffff813793da)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
```
```
In fs/notify/fsnotify.c (ffffffff81379db8)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:__fsnotify_vfsmount_delete
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81380945)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/fhandle.c (ffffffff813c1095)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/fhandle.c:do_sys_name_to_handle
```
```
In fs/proc/fd.c (ffffffff813dcc72)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
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
In fs/stat.c (ffffffff81379731)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx
```
```
In fs/namei.c (ffffffff813817ea)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/namei.c:follow_up
```
```
In fs/namespace.c (ffffffff813a212d)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/namespace.c:mnt_may_suid
  - fs/namespace.c:our_mnt
  - fs/namespace.c:kern_unmount_array
  - fs/namespace.c:kern_unmount_array
  - fs/namespace.c:kern_mount
  - fs/namespace.c:mount_setattr_prepare
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:path_is_under
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:mnt_set_expiry
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_set_group
  - fs/namespace.c:do_set_group
  - fs/namespace.c:do_set_group
  - fs/namespace.c:do_set_group
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:__do_sys_open_tree
  - fs/namespace.c:__do_sys_open_tree
  - fs/namespace.c:__do_loopback
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:path_umount
  - fs/namespace.c:path_umount
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:may_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mnt_clone_internal
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:is_current_mnt_ns
  - fs/namespace.c:lookup_mnt
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:__mnt_want_write
  - fs/namespace.c:mnt_init
```
```
In fs/d_path.c (ffffffff813b62ef)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/d_path.c:prepend_path
```
```
In fs/fs_pin.c (ffffffff813b8470)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_insert
```
```
In fs/proc_namespace.c (ffffffff813c5f3a)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
```
```
In fs/notify/fsnotify.c (ffffffff813c69a8)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/notify/fsnotify.c:__fsnotify_vfsmount_delete
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff813cd79f)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/fhandle.c (ffffffff81410b05)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/fhandle.c:do_sys_name_to_handle
```
```
In fs/proc/fd.c (ffffffff8142e352)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
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
In fs/stat.c (0)
Location: fs/mount.h:84
Inline: True
```
```
In fs/namei.c (ffffffff814059ab)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
  - fs/namei.c:follow_up
```
```
In fs/namespace.c (ffffffff8141f9e5)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/namespace.c:kern_unmount_array
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:path_is_under
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:__do_loopback
  - fs/namespace.c:iterate_mounts
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:path_umount
  - fs/namespace.c:may_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mnt_clone_internal
  - fs/namespace.c:lookup_mnt
  - fs/namespace.c:mnt_init
```
```
In fs/d_path.c (ffffffff8143b8b6)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/d_path.c:prepend_path
```
```
In fs/fs_pin.c (0)
Location: fs/mount.h:84
Inline: True
```
```
In fs/proc_namespace.c (ffffffff8144cf0c)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_mountinfo
```
```
In fs/notify/fsnotify.c (ffffffff8144da46)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:__fsnotify_parent
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: fs/mount.h:84
Inline: True
```
```
In fs/fhandle.c (0)
Location: fs/mount.h:84
Inline: True
```
```
In fs/proc/fd.c (0)
Location: fs/mount.h:84
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
In fs/stat.c (0)
Location: fs/mount.h:84
Inline: True
```
```
In fs/namei.c (ffffffff8148fc86)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/namei.c:handle_dots
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_up
```
```
In fs/namespace.c (ffffffff814abf15)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/namespace.c:kern_unmount_array
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:path_is_under
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:__do_loopback
  - fs/namespace.c:iterate_mounts
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:path_umount
  - fs/namespace.c:may_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mnt_clone_internal
  - fs/namespace.c:lookup_mnt
  - fs/namespace.c:mnt_init
```
```
In fs/d_path.c (ffffffff814c9ec6)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/d_path.c:prepend_path
```
```
In fs/fs_pin.c (0)
Location: fs/mount.h:84
Inline: True
```
```
In fs/proc_namespace.c (ffffffff814db4cc)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_mountinfo
```
```
In fs/notify/fsnotify.c (ffffffff814dc106)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:__fsnotify_parent
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: fs/mount.h:84
Inline: True
```
```
In fs/fhandle.c (0)
Location: fs/mount.h:84
Inline: True
```
```
In fs/proc/fd.c (0)
Location: fs/mount.h:84
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
In fs/stat.c (0)
Location: fs/mount.h:84
Inline: True
```
```
In fs/namei.c (ffffffff814c5014)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
  - fs/namei.c:follow_up
```
```
In fs/namespace.c (ffffffff814e0cd5)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/namespace.c:kern_unmount_array
  - fs/namespace.c:kern_unmount
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:path_is_under
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:__do_loopback
  - fs/namespace.c:iterate_mounts
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:path_umount
  - fs/namespace.c:may_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mnt_clone_internal
  - fs/namespace.c:lookup_mnt
  - fs/namespace.c:mnt_init
```
```
In fs/d_path.c (ffffffff81500106)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/d_path.c:prepend_path
```
```
In fs/fs_pin.c (0)
Location: fs/mount.h:84
Inline: True
```
```
In fs/proc_namespace.c (ffffffff8150fa6c)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_mountinfo
```
```
In fs/notify/fsnotify.c (ffffffff815128f6)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:__fsnotify_parent
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: fs/mount.h:84
Inline: True
```
```
In fs/fhandle.c (0)
Location: fs/mount.h:84
Inline: True
```
```
In fs/proc/fd.c (0)
Location: fs/mount.h:84
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
In fs/stat.c (0)
Location: fs/mount.h:82
Inline: True
```
```
In fs/namei.c (ffffffff814f77f4)
Location: fs/mount.h:82
Inline: True
Inline callers:
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
  - fs/namei.c:follow_up
```
```
In fs/namespace.c (ffffffff81514da5)
Location: fs/mount.h:82
Inline: True
Inline callers:
  - fs/namespace.c:kern_unmount_array
  - fs/namespace.c:kern_unmount
  - fs/namespace.c:__ia32_sys_listmount
  - fs/namespace.c:__x64_sys_listmount
  - fs/namespace.c:do_statmount
  - fs/namespace.c:do_statmount
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:path_is_under
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:__do_loopback
  - fs/namespace.c:iterate_mounts
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:path_umount
  - fs/namespace.c:may_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mnt_clone_internal
  - fs/namespace.c:lookup_mnt
  - fs/namespace.c:mnt_init
```
```
In fs/d_path.c (ffffffff81534d26)
Location: fs/mount.h:82
Inline: True
Inline callers:
  - fs/d_path.c:prepend_path
```
```
In fs/fs_pin.c (0)
Location: fs/mount.h:82
Inline: True
```
```
In fs/proc_namespace.c (ffffffff81543f4c)
Location: fs/mount.h:82
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_mountinfo
```
```
In fs/notify/fsnotify.c (ffffffff81546da6)
Location: fs/mount.h:82
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:__fsnotify_parent
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: fs/mount.h:82
Inline: True
```
```
In fs/fhandle.c (0)
Location: fs/mount.h:82
Inline: True
```
```
In fs/proc/fd.c (0)
Location: fs/mount.h:82
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
In fs/namei.c (ffff800010392d3c)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_up
```
```
In fs/namespace.c (ffff8000103bb020)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/namespace.c:mnt_may_suid
  - fs/namespace.c:our_mnt
  - fs/namespace.c:kern_mount
  - fs/namespace.c:__arm64_sys_pivot_root
  - fs/namespace.c:__arm64_sys_pivot_root
  - fs/namespace.c:__arm64_sys_pivot_root
  - fs/namespace.c:path_is_under
  - fs/namespace.c:__arm64_sys_fsmount
  - fs/namespace.c:__arm64_sys_fsmount
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_set_expiry
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:__arm64_sys_open_tree
  - fs/namespace.c:__arm64_sys_open_tree
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:may_umount
  - fs/namespace.c:mnt_clone_internal
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:is_current_mnt_ns
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_clone_write
  - fs/namespace.c:__mnt_want_write
  - fs/namespace.c:mnt_init
```
```
In fs/d_path.c (ffff8000103d170c)
Location: fs/mount.h:79
Inline: True
```
```
In fs/fs_pin.c (ffff8000103d4094)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_insert
```
```
In fs/proc_namespace.c (ffff8000103e7404)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
```
```
In fs/notify/fsnotify.c (ffff8000103e7dc8)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:__fsnotify_vfsmount_delete
```
```
In fs/notify/fanotify/fanotify_user.c (ffff8000103eedcc)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/fhandle.c (ffff800010429968)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/fhandle.c:__arm64_sys_name_to_handle_at
```
```
In fs/proc/fd.c (ffff800010446fc4)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
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
In fs/namei.c (c0579490)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/namei.c:follow_dotdot_rcu
```
```
In fs/namespace.c (c0598dac)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/namespace.c:mnt_may_suid
  - fs/namespace.c:our_mnt
  - fs/namespace.c:kern_mount
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:path_is_under
  - fs/namespace.c:__se_sys_fsmount
  - fs/namespace.c:__se_sys_fsmount
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_set_expiry
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:__se_sys_open_tree
  - fs/namespace.c:__se_sys_open_tree
  - fs/namespace.c:__do_loopback
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:may_umount
  - fs/namespace.c:mnt_clone_internal
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:is_current_mnt_ns
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_clone_write
  - fs/namespace.c:__mnt_want_write
  - fs/namespace.c:mnt_init
```
```
In fs/d_path.c (c05ac5b0)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In fs/fs_pin.c (c05ae220)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_insert
```
```
In fs/proc_namespace.c (c05befa0)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
```
```
In fs/notify/fsnotify.c (c05bf91c)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:__fsnotify_vfsmount_delete
```
```
In fs/notify/fanotify/fanotify_user.c (c05c5e64)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
```
```
In fs/fhandle.c (c05f1ee4)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/fhandle.c:do_sys_name_to_handle
```
```
In fs/proc/fd.c (c060bff8)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
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
In fs/namei.c (c00000000048c10c)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_up
```
```
In fs/namespace.c (c0000000004b89cc)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/namespace.c:mnt_may_suid
  - fs/namespace.c:our_mnt
  - fs/namespace.c:kern_mount
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:path_is_under
  - fs/namespace.c:__se_sys_fsmount
  - fs/namespace.c:__se_sys_fsmount
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_set_expiry
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:__se_sys_open_tree
  - fs/namespace.c:__se_sys_open_tree
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:may_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mnt_clone_internal
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:is_current_mnt_ns
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_clone_write
  - fs/namespace.c:__mnt_want_write
  - fs/namespace.c:mnt_init
```
```
In fs/d_path.c (c0000000004d42f0)
Location: fs/mount.h:79
Inline: True
```
```
In fs/fs_pin.c (c0000000004d6c08)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_insert
```
```
In fs/proc_namespace.c (c0000000004ed9b0)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
```
```
In fs/notify/fsnotify.c (c0000000004ee7e4)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:__fsnotify_vfsmount_delete
```
```
In fs/notify/fanotify/fanotify_user.c (c0000000004f77fc)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/fhandle.c (c000000000539800)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/fhandle.c:__se_sys_name_to_handle_at
```
```
In fs/proc/fd.c (c00000000055ced8)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
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
In fs/namei.c (ffffffe000261e34)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_up
```
```
In fs/namespace.c (ffffffe00027d0fa)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/namespace.c:mnt_may_suid
  - fs/namespace.c:our_mnt
  - fs/namespace.c:kern_mount
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:path_is_under
  - fs/namespace.c:__se_sys_fsmount
  - fs/namespace.c:__se_sys_fsmount
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_set_expiry
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:__se_sys_open_tree
  - fs/namespace.c:__se_sys_open_tree
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:may_umount
  - fs/namespace.c:mnt_clone_internal
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:is_current_mnt_ns
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_clone_write
  - fs/namespace.c:__mnt_want_write
  - fs/namespace.c:mnt_init
```
```
In fs/d_path.c (ffffffe00028ce26)
Location: fs/mount.h:79
Inline: True
```
```
In fs/fs_pin.c (ffffffe00028e6c0)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_insert
```
```
In fs/proc_namespace.c (ffffffe00029c396)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
```
```
In fs/notify/fsnotify.c (ffffffe00029cbba)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:__fsnotify_vfsmount_delete
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffe0002a2cc8)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
```
```
In fs/fhandle.c (ffffffe0002c73aa)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/fhandle.c:__se_sys_name_to_handle_at
```
```
In fs/proc/fd.c (ffffffe0002dcdc6)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
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
In fs/namei.c (ffffffff812e1e89)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_up
```
```
In fs/namespace.c (ffffffff8130010d)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/namespace.c:mnt_may_suid
  - fs/namespace.c:our_mnt
  - fs/namespace.c:kern_mount
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:path_is_under
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_set_expiry
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:may_umount
  - fs/namespace.c:mnt_clone_internal
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:is_current_mnt_ns
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:__mnt_want_write
  - fs/namespace.c:mnt_init
```
```
In fs/d_path.c (ffffffff81312b87)
Location: fs/mount.h:79
Inline: True
```
```
In fs/fs_pin.c (ffffffff81314c30)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_insert
```
```
In fs/proc_namespace.c (ffffffff8132429a)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
```
```
In fs/notify/fsnotify.c (ffffffff81324ab9)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:__fsnotify_vfsmount_delete
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8132a0a9)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/fhandle.c (ffffffff8135affd)
Location: fs/mount.h:79
Inline: True
```
```
In fs/proc/fd.c (ffffffff81372ff3)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
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
In fs/namei.c (ffffffff812d2ac9)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_up
```
```
In fs/namespace.c (ffffffff812f0d2d)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/namespace.c:mnt_may_suid
  - fs/namespace.c:our_mnt
  - fs/namespace.c:kern_mount
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:path_is_under
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_set_expiry
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:may_umount
  - fs/namespace.c:mnt_clone_internal
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:is_current_mnt_ns
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:__mnt_want_write
  - fs/namespace.c:mnt_init
```
```
In fs/d_path.c (ffffffff81303797)
Location: fs/mount.h:79
Inline: True
```
```
In fs/fs_pin.c (ffffffff81305840)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_insert
```
```
In fs/proc_namespace.c (ffffffff81314e3a)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
```
```
In fs/notify/fsnotify.c (ffffffff81315659)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:__fsnotify_vfsmount_delete
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8131ac49)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/fhandle.c (ffffffff8134bc9d)
Location: fs/mount.h:79
Inline: True
```
```
In fs/proc/fd.c (ffffffff81363ac3)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
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
In fs/namei.c (ffffffff812dfc99)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_up
```
```
In fs/namespace.c (ffffffff812fdefd)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/namespace.c:mnt_may_suid
  - fs/namespace.c:our_mnt
  - fs/namespace.c:kern_mount
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:path_is_under
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_set_expiry
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:may_umount
  - fs/namespace.c:mnt_clone_internal
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:is_current_mnt_ns
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:__mnt_want_write
  - fs/namespace.c:mnt_init
```
```
In fs/d_path.c (ffffffff81310977)
Location: fs/mount.h:79
Inline: True
```
```
In fs/fs_pin.c (ffffffff81312a20)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_insert
```
```
In fs/proc_namespace.c (ffffffff81321d6a)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
```
```
In fs/notify/fsnotify.c (ffffffff81322589)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:__fsnotify_vfsmount_delete
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81327b79)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/fhandle.c (ffffffff81358acd)
Location: fs/mount.h:79
Inline: True
```
```
In fs/proc/fd.c (ffffffff81370ac3)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
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
In fs/namei.c (ffffffff812f1359)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_up
```
```
In fs/namespace.c (ffffffff8130f23d)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/namespace.c:mnt_may_suid
  - fs/namespace.c:our_mnt
  - fs/namespace.c:kern_mount
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:path_is_under
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_set_expiry
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:may_umount
  - fs/namespace.c:mnt_clone_internal
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:is_current_mnt_ns
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_clone_write
  - fs/namespace.c:__mnt_want_write
  - fs/namespace.c:mnt_init
```
```
In fs/d_path.c (ffffffff8132200a)
Location: fs/mount.h:79
Inline: True
```
```
In fs/fs_pin.c (ffffffff81324250)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_insert
```
```
In fs/proc_namespace.c (ffffffff81333aca)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
```
```
In fs/notify/fsnotify.c (ffffffff813343e9)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:__fsnotify_vfsmount_delete
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81339f99)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/fhandle.c (ffffffff8136c1cd)
Location: fs/mount.h:79
Inline: True
```
```
In fs/proc/fd.c (ffffffff81384498)
Location: fs/mount.h:79
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
</details>
</li>
</ul>

## Differences
