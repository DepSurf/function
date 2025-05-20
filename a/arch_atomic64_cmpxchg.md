# Function: <code>arch_atomic64_cmpxchg</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff8106e6ef)
Location: arch/x86/include/asm/atomic64_64.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In kernel/locking/mutex.c (ffffffff819ee0c4)
Location: arch/x86/include/asm/atomic64_64.h:175
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock
  - kernel/locking/mutex.c:mutex_unlock
```
```
In kernel/locking/rwsem-xadd.c (ffffffff819efe7c)
Location: arch/x86/include/asm/atomic64_64.h:175
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811213f2)
Location: arch/x86/include/asm/atomic64_64.h:175
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
```
```
In kernel/events/core.c (ffffffff811dd100)
Location: arch/x86/include/asm/atomic64_64.h:175
Inline: True
Inline callers:
  - kernel/events/core.c:free_event
```
```
In fs/inode.c (ffffffff812b89c2)
Location: arch/x86/include/asm/atomic64_64.h:175
Inline: True
Inline callers:
  - fs/inode.c:generic_update_time
```
```
In fs/nsfs.c (ffffffff812d5b63)
Location: arch/x86/include/asm/atomic64_64.h:175
Inline: True
```
```
In fs/ext4/dir.c (ffffffff813382de)
Location: arch/x86/include/asm/atomic64_64.h:175
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8134e337)
Location: arch/x86/include/asm/atomic64_64.h:175
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff813554b3)
Location: arch/x86/include/asm/atomic64_64.h:175
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff8136d87a)
Location: arch/x86/include/asm/atomic64_64.h:175
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff813a7fe8)
Location: arch/x86/include/asm/atomic64_64.h:175
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff813aed86)
Location: arch/x86/include/asm/atomic64_64.h:175
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/namei_vfat.c (ffffffff813b2810)
Location: arch/x86/include/asm/atomic64_64.h:175
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In security/integrity/ima/ima_api.c (ffffffff814536ba)
Location: arch/x86/include/asm/atomic64_64.h:175
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In drivers/tty/tty_ldsem.c (ffffffff8161a75e)
Location: arch/x86/include/asm/atomic64_64.h:175
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In net/core/skbuff.c (ffffffff8187b623)
Location: arch/x86/include/asm/atomic64_64.h:175
Inline: True
```
```
In net/core/sock_diag.c (ffffffff818b8e8f)
Location: arch/x86/include/asm/atomic64_64.h:175
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/xdp/xdp_umem.c (ffffffff819cd136)
Location: arch/x86/include/asm/atomic64_64.h:175
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In arch/x86/kernel/pvclock.c (ffffffff8107470f)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In kernel/locking/mutex.c (ffffffff81a29334)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock
  - kernel/locking/mutex.c:mutex_unlock
```
```
In kernel/locking/rwsem-xadd.c (ffffffff81a2b8ae)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112cb12)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
```
```
In kernel/events/core.c (ffffffff811ed500)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - kernel/events/core.c:free_event
```
```
In fs/inode.c (ffffffff812cdb12)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/inode.c:generic_update_time
```
```
In fs/nsfs.c (ffffffff812eaf33)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
```
```
In fs/ext4/dir.c (ffffffff8134f573)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff813664d3)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff8136d7e2)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff81385cfa)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff813c0dd6)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff813c7f65)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff813c98a4)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff813cbf01)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/dir.c (ffffffff813ddfa8)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/readdir.c (ffffffff813eaaa7)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In security/integrity/ima/ima_api.c (ffffffff8147089a)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In block/blk-cgroup.c (ffffffff814c0a8b)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In net/core/skbuff.c (ffffffff8189c463)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
```
```
In net/core/sock_diag.c (ffffffff818dfadf)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/xdp/xdp_umem.c (ffffffff81a06497)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In arch/x86/kernel/pvclock.c (ffffffff81078267)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In kernel/locking/mutex.c (ffffffff81a999c4)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock
  - kernel/locking/mutex.c:mutex_unlock
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811374e2)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
```
```
In kernel/events/core.c (ffffffff81204f40)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - kernel/events/core.c:free_event
```
```
In fs/inode.c (ffffffff812ea8b2)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/inode.c:generic_update_time
```
```
In fs/nsfs.c (ffffffff813099a6)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
```
```
In fs/io_uring.c (ffffffff81330ee1)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/ext4/dir.c (ffffffff81377b01)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8138f856)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff81396dcc)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff813afcdb)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff813eb626)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff813f2b4e)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff813f4443)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff813f6710)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/dir.c (ffffffff81409658)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/readdir.c (ffffffff81416a5a)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In security/integrity/ima/ima_api.c (ffffffff8149e24a)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In block/blk-cgroup.c (ffffffff814ef2e0)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In net/core/skbuff.c (ffffffff818e6ce3)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
```
```
In net/core/sock_diag.c (ffffffff8192e12e)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/xdp/xdp_umem.c (ffffffff81a75dc1)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In arch/x86/kernel/pvclock.c (ffffffff810792d7)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In kernel/locking/mutex.c (ffffffff81ad146e)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_unlock
  - kernel/locking/mutex.c:mutex_trylock_recursive
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81142f2e)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
```
```
In kernel/futex.c (ffffffff8114a8c2)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/core.c (ffffffff81211b30)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - kernel/events/core.c:free_event
```
```
In fs/inode.c (ffffffff812fc2e2)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/inode.c:generic_update_time
```
```
In fs/nsfs.c (ffffffff8131ca16)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
```
```
In fs/io_uring.c (ffffffff81344f7f)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/ext4/dir.c (ffffffff8138fe81)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff813a82b6)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff813af7fc)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff813c8c9b)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff81404fd6)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff8140cb0f)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff8140e313)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff814105e0)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/dir.c (ffffffff81422fb8)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/readdir.c (ffffffff8143097a)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In security/integrity/ima/ima_api.c (ffffffff814b86eb)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In block/blk-cgroup.c (ffffffff81508770)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In net/core/skbuff.c (ffffffff819190c3)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
```
```
In net/core/sock_diag.c (ffffffff819603be)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/xdp/xdp_umem.c (ffffffff81aacb24)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In arch/x86/kernel/pvclock.c (ffffffff810805bd)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In kernel/locking/mutex.c (ffffffff8110e1c1)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
  - kernel/locking/mutex.c:ww_mutex_unlock
  - kernel/locking/mutex.c:mutex_trylock_recursive
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81152c7e)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
```
```
In kernel/futex.c (ffffffff8115b3ea)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/core.c (ffffffff8123da60)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - kernel/events/core.c:free_event
```
```
In fs/inode.c (ffffffff813352d0)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
```
```
In fs/nsfs.c (ffffffff8135669e)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In fs/io_uring.c (ffffffff81385801)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/ext4/dir.c (ffffffff813db451)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff813f4363)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff813fb85c)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff8141475b)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff81452f94)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff8145a179)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff8145c107)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff8145e8ed)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/dir.c (ffffffff814726e8)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/readdir.c (ffffffff8148054c)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In security/integrity/ima/ima_api.c (ffffffff8151832b)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In block/blk-cgroup.c (ffffffff81569a8a)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In net/core/skbuff.c (ffffffff819ecd2e)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
```
```
In net/core/net_namespace.c (ffffffff819f9934)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_gen_cookie
```
```
In net/core/sock_diag.c (ffffffff81a3391e)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/xdp/xdp_umem.c (ffffffff81ba856e)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
```
In net/mptcp/options.c (ffffffff81bb14be)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
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
In arch/x86/kernel/pvclock.c (ffffffff810801cd)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In kernel/locking/mutex.c (ffffffff8110b481)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
  - kernel/locking/mutex.c:ww_mutex_unlock
  - kernel/locking/mutex.c:mutex_trylock_recursive
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff8111cc13)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_commit
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:desc_push_tail
  - kernel/printk/printk_ringbuffer.c:desc_push_tail
  - kernel/printk/printk_ringbuffer.c:data_make_reusable
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8114ef0e)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
```
```
In kernel/futex.c (ffffffff8115752e)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/core.c (ffffffff81247e20)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - kernel/events/core.c:free_event
```
```
In fs/inode.c (ffffffff81340c40)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
```
```
In fs/nsfs.c (ffffffff81363043)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In fs/io_uring.c (ffffffff81396835)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_buffer_account_pin
```
```
In fs/ext4/dir.c (ffffffff813ece81)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff81406af3)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff8140dfd8)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff81427dab)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff8146f444)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff814764c9)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff81478007)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff8147a5bd)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/dir.c (ffffffff8148d058)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/readdir.c (ffffffff8149bc2f)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In security/integrity/ima/ima_api.c (ffffffff815352fb)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In block/blk-cgroup.c (ffffffff8158433a)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In net/core/skbuff.c (ffffffff819ec9ee)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
```
```
In net/core/net_namespace.c (ffffffff819f9453)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - net/core/net_namespace.c:__net_gen_cookie
```
```
In net/core/sock_diag.c (ffffffff81a35cbd)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - net/core/sock_diag.c:__sock_gen_cookie
```
```
In net/xdp/xdp_umem.c (ffffffff81bb82d4)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
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
In arch/x86/kernel/pvclock.c (ffffffff81081060)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In kernel/locking/mutex.c (ffffffff8110d2a1)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
  - kernel/locking/mutex.c:mutex_trylock
  - kernel/locking/mutex.c:ww_mutex_unlock
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff8111cd8c)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_commit
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:prb_reserve
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8115039e)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
```
```
In kernel/futex.c (ffffffff8115894c)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/core.c (ffffffff8124bce0)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - kernel/events/core.c:free_event
```
```
In fs/inode.c (ffffffff81347061)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
```
```
In fs/nsfs.c (ffffffff81369ae3)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In fs/io_uring.c (ffffffff8139183a)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/io_uring.c:io_buffer_account_pin
```
```
In fs/ext4/dir.c (ffffffff813f33b1)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8140cf6d)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff81414198)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff8142ea22)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff81474914)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff8147bf39)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff8147da9d)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_update_time
```
```
In fs/fat/namei_vfat.c (ffffffff8147fffd)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/dir.c (ffffffff814928d8)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/readdir.c (ffffffff814a0d4f)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In security/integrity/ima/ima_api.c (ffffffff8153d91b)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In block/blk-cgroup.c (ffffffff8158b13d)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In net/core/skbuff.c (ffffffff819d2ece)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
```
```
In net/core/sock_diag.c (ffffffff81a1ce10)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - net/core/sock_diag.c:__sock_gen_cookie
```
```
In net/xdp/xdp_umem.c (ffffffff81ba7492)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
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
In arch/x86/kernel/pvclock.c (ffffffff8108fff6)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In kernel/ucount.c (ffffffff810ea223)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff8113cfe8)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_commit
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:prb_reserve
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811745f8)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
```
```
In kernel/futex.c (ffffffff8117d850)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/core.c (ffffffff812875a0)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - kernel/events/core.c:free_event
```
```
In fs/inode.c (ffffffff81394a91)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
```
```
In fs/nsfs.c (ffffffff813b87d3)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In fs/io_uring.c (ffffffff813df743)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/io_uring.c:io_buffer_account_pin
```
```
In fs/ext4/dir.c (ffffffff814453f2)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8145fdad)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff814674f8)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff814831c2)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff814cb654)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff814d3576)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff814d531d)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_update_time
```
```
In fs/fat/namei_vfat.c (ffffffff814d789d)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/dir.c (ffffffff814ea2b8)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/readdir.c (ffffffff814f8c8f)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In security/integrity/ima/ima_api.c (ffffffff8159c7ab)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In block/blk-cgroup.c (ffffffff815f013d)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In net/core/skbuff.c (ffffffff81a82bae)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
```
```
In net/core/sock_diag.c (ffffffff81ad0690)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - net/core/sock_diag.c:__sock_gen_cookie
```
```
In net/xdp/xdp_umem.c (ffffffff81c750ac)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
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
In arch/x86/kernel/pvclock.c (ffffffff810a0f46)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In kernel/ucount.c (ffffffff81104e94)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff81160549)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_commit
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:data_push_tail
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811a9410)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
```
```
In kernel/futex/core.c (ffffffff811b2b71)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/events/core.c (ffffffff812dbd35)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - kernel/events/core.c:free_event
```
```
In fs/inode.c (ffffffff81416d33)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
```
```
In fs/nsfs.c (ffffffff8143e09e)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In fs/ext4/dir.c (ffffffff814c14b4)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff814de51c)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff814e7105)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff81507cac)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff81557bed)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff8156098a)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff81562328)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_update_time
```
```
In fs/fat/namei_vfat.c (ffffffff81564f0b)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/dir.c (ffffffff81578e58)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/readdir.c (ffffffff815892d2)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In security/integrity/ima/ima_api.c (ffffffff81641826)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In block/blk-cgroup.c (ffffffff816a121b)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In io_uring/io_uring.c (ffffffff816cd3cb)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_buffer_account_pin
```
```
In lib/sbitmap.c (ffffffff81773928)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_queue_get_batch
```
```
In net/core/skbuff.c (ffffffff81bf78c5)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_account_pinned_pages
```
```
In net/core/sock_diag.c (ffffffff81c4df10)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - net/core/sock_diag.c:__sock_gen_cookie
```
```
In net/xdp/xdp_umem.c (ffffffff81e19250)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
```
In net/mptcp/options.c (ffffffff81e2b21d)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
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
In arch/x86/kernel/pvclock.c (ffffffff810b8db6)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In kernel/ucount.c (ffffffff8112a7cf)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff81193a19)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_commit
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:data_push_tail
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811e9300)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
```
```
In kernel/futex/core.c (ffffffff811f3a11)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/events/core.c (ffffffff81344025)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - kernel/events/core.c:free_event
```
```
In fs/nsfs.c (ffffffff814ccaae)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In net/core/sock_diag.c (ffffffff81e02d5d)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff81ff04a6)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
```
In net/mptcp/options.c (ffffffff820033cd)
Location: arch/x86/include/asm/atomic64_64.h:182
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
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
In kernel/ucount.c (ffffffff8113784f)
Location: arch/x86/include/asm/atomic64_64.h:101
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff811a5279)
Location: arch/x86/include/asm/atomic64_64.h:101
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_commit
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:data_push_tail
```
```
In kernel/futex/core.c (ffffffff81208195)
Location: arch/x86/include/asm/atomic64_64.h:101
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/events/core.c (ffffffff813750b5)
Location: arch/x86/include/asm/atomic64_64.h:101
Inline: True
```
```
In fs/nsfs.c (ffffffff81502cee)
Location: arch/x86/include/asm/atomic64_64.h:101
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In net/core/sock_diag.c (ffffffff81e752dd)
Location: arch/x86/include/asm/atomic64_64.h:101
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff8206c654)
Location: arch/x86/include/asm/atomic64_64.h:101
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
```
In net/mptcp/options.c (ffffffff8207f55d)
Location: arch/x86/include/asm/atomic64_64.h:101
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
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
In kernel/ucount.c (ffffffff81142a5f)
Location: arch/x86/include/asm/atomic64_64.h:101
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff811b4d69)
Location: arch/x86/include/asm/atomic64_64.h:101
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_commit
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:data_push_tail
```
```
In kernel/futex/core.c (ffffffff8121f049)
Location: arch/x86/include/asm/atomic64_64.h:101
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/events/core.c (ffffffff8139e3e5)
Location: arch/x86/include/asm/atomic64_64.h:101
Inline: True
```
```
In fs/nsfs.c (ffffffff81537918)
Location: arch/x86/include/asm/atomic64_64.h:101
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In net/core/sock_diag.c (ffffffff81f34b7d)
Location: arch/x86/include/asm/atomic64_64.h:101
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff82140452)
Location: arch/x86/include/asm/atomic64_64.h:101
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
```
In net/mptcp/options.c (ffffffff82154a50)
Location: arch/x86/include/asm/atomic64_64.h:101
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff810782d7)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In kernel/locking/mutex.c (ffffffff81a702de)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_unlock
  - kernel/locking/mutex.c:mutex_trylock_recursive
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8113b6de)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
```
```
In kernel/futex.c (ffffffff81142ee2)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/core.c (ffffffff8120a180)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - kernel/events/core.c:free_event
```
```
In fs/inode.c (ffffffff812f48c2)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/inode.c:generic_update_time
```
```
In fs/nsfs.c (ffffffff81314ff6)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
```
```
In fs/io_uring.c (ffffffff8133d55f)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/ext4/dir.c (ffffffff81388461)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff813a0896)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff813a7ddc)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff813c127b)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff813fd5b6)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff814050ef)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff814068f3)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff81408bc0)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/dir.c (ffffffff8141b598)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/readdir.c (ffffffff81428f5a)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In security/integrity/ima/ima_api.c (ffffffff814b0ccb)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In block/blk-cgroup.c (ffffffff81500d50)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In net/core/skbuff.c (ffffffff818b90c3)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
```
```
In net/core/sock_diag.c (ffffffff8190038e)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/xdp/xdp_umem.c (ffffffff81a4beb4)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In arch/x86/kernel/pvclock.c (ffffffff81067b87)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In kernel/locking/mutex.c (ffffffff81a2c6ce)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_unlock
  - kernel/locking/mutex.c:mutex_trylock_recursive
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112e11e)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
```
```
In kernel/futex.c (ffffffff81136242)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/core.c (ffffffff811fcf70)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - kernel/events/core.c:free_event
```
```
In fs/inode.c (ffffffff812e54e2)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/inode.c:generic_update_time
```
```
In fs/nsfs.c (ffffffff81305be6)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
```
```
In fs/io_uring.c (ffffffff8132e21f)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/ext4/dir.c (ffffffff81378ef1)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff81391326)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff8139886c)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff813b1d0b)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff813ee036)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff813f5b6f)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff813f7373)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff813f9640)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/dir.c (ffffffff8140c018)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/readdir.c (ffffffff814199da)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In security/integrity/ima/ima_api.c (ffffffff814a16eb)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In block/blk-cgroup.c (ffffffff814f1260)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In net/core/skbuff.c (ffffffff81873013)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
```
```
In net/core/sock_diag.c (ffffffff818ba1be)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/xdp/xdp_umem.c (ffffffff81a08aa4)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In arch/x86/kernel/pvclock.c (ffffffff81078287)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In kernel/locking/mutex.c (ffffffff81adc6ee)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_unlock
  - kernel/locking/mutex.c:mutex_trylock_recursive
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811393fe)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
```
```
In kernel/futex.c (ffffffff81140d92)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/core.c (ffffffff81207f20)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - kernel/events/core.c:free_event
```
```
In fs/inode.c (ffffffff812f26d2)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/inode.c:generic_update_time
```
```
In fs/nsfs.c (ffffffff81312de6)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
```
```
In fs/io_uring.c (ffffffff8133b02f)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/ext4/dir.c (ffffffff81385dc1)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8139e0f6)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff813a563c)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff813be72b)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff813fa936)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff8140246f)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff81403c73)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff81405f40)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/dir.c (ffffffff81417738)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/readdir.c (ffffffff814250fa)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In security/integrity/ima/ima_api.c (ffffffff814acd5b)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In block/blk-cgroup.c (ffffffff814fcde0)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In net/core/skbuff.c (ffffffff8190a0c3)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
```
```
In net/core/sock_diag.c (ffffffff819513be)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/xdp/xdp_umem.c (ffffffff81ab7d64)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In arch/x86/kernel/pvclock.c (ffffffff8107a387)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In kernel/locking/mutex.c (ffffffff81ae8ade)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_unlock
  - kernel/locking/mutex.c:mutex_trylock_recursive
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81145e9e)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
```
```
In kernel/futex.c (ffffffff8114dfed)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/core.c (ffffffff81216cc0)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - kernel/events/core.c:free_event
```
```
In fs/inode.c (ffffffff81303de2)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/inode.c:generic_update_time
```
```
In fs/nsfs.c (ffffffff81324621)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
```
```
In fs/io_uring.c (ffffffff8134e1df)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/ext4/dir.c (ffffffff81399ab1)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff813b2666)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff813b9d7c)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff813d380b)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff81410596)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff8141843f)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff814198e3)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff8141bc00)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/dir.c (ffffffff8142e528)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/readdir.c (ffffffff8143bf92)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In security/integrity/ima/ima_api.c (ffffffff814c57ab)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In block/blk-cgroup.c (ffffffff81515e90)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In net/core/skbuff.c (ffffffff8192b1c3)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
```
```
In net/core/sock_diag.c (ffffffff81972dae)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/xdp/xdp_umem.c (ffffffff81ac4184)
Location: arch/x86/include/asm/atomic64_64.h:178
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
</details>
</li>
</ul>

## Differences
