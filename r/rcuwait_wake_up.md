# Function: <code>rcuwait_wake_up</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rcuwait_wake_up(struct rcuwait *w);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81088850)
Location: kernel/exit.c:292
Inline: False
```
**Symbols:**

```
ffffffff81088850-ffffffff8108886a: rcuwait_wake_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rcuwait_wake_up(struct rcuwait *w);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8108f580)
Location: kernel/exit.c:292
Inline: False
```
**Symbols:**

```
ffffffff8108f580-ffffffff8108f598: rcuwait_wake_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rcuwait_wake_up(struct rcuwait *w);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81093110)
Location: kernel/exit.c:292
Inline: False
```
**Symbols:**

```
ffffffff81093110-ffffffff81093128: rcuwait_wake_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rcuwait_wake_up(struct rcuwait *w);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109b3c0)
Location: kernel/exit.c:293
Inline: False
```
**Symbols:**

```
ffffffff8109b3c0-ffffffff8109b3de: rcuwait_wake_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rcuwait_wake_up(struct rcuwait *w);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109fa00)
Location: kernel/exit.c:295
Inline: False
```
**Symbols:**

```
ffffffff8109fa00-ffffffff8109fa1f: rcuwait_wake_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rcuwait_wake_up(struct rcuwait *w);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a6010)
Location: kernel/exit.c:237
Inline: False
```
**Symbols:**

```
ffffffff810a6010-ffffffff810a602f: rcuwait_wake_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rcuwait_wake_up(struct rcuwait *w);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810abc30)
Location: kernel/exit.c:230
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/workqueue.c:worker_thread
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cpuset.c:cpuset_read_unlock
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - fs/super.c:__sb_end_write
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/locks.c:locks_remove_file
  - fs/locks.c:generic_delete_lease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
```
**Symbols:**

```
ffffffff810abc30-ffffffff810abc51: rcuwait_wake_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rcuwait_wake_up(struct rcuwait *w);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a7220)
Location: kernel/exit.c:232
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/workqueue.c:worker_thread
  - kernel/sched/core.c:balance_push
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cpuset.c:cpuset_read_unlock
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
  - mm/filemap.c:filemap_page_mkwrite
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/pipe.c:pipe_write
  - fs/inode.c:touch_atime
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_want_write
  - fs/splice.c:do_splice
  - fs/remap_range.c:vfs_clone_file_range
  - fs/aio.c:aio_complete_rw
  - fs/io_uring.c:io_complete_rw_iopoll
  - fs/io_uring.c:io_complete_rw_common
  - fs/locks.c:locks_remove_file
  - fs/locks.c:generic_delete_lease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/coredump.c:do_coredump
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - fs/fuse/dax.c:__fuse_dax_fault
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff810a7220-ffffffff810a7252: rcuwait_wake_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rcuwait_wake_up(struct rcuwait *w);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a82b0)
Location: kernel/exit.c:232
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/workqueue.c:worker_thread
  - kernel/sched/core.c:balance_push
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cpuset.c:cpuset_read_unlock
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
  - mm/filemap.c:filemap_page_mkwrite
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/pipe.c:pipe_write
  - fs/inode.c:touch_atime
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_want_write
  - fs/splice.c:do_splice
  - fs/remap_range.c:vfs_clone_file_range
  - fs/aio.c:aio_complete_rw
  - fs/io_uring.c:io_complete_rw_iopoll
  - fs/locks.c:locks_remove_file
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/coredump.c:do_coredump
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - fs/fuse/dax.c:__fuse_dax_fault
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff810a82b0-ffffffff810a82e2: rcuwait_wake_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rcuwait_wake_up(struct rcuwait *w);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810b9d10)
Location: kernel/exit.c:232
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/workqueue.c:worker_thread
  - kernel/sched/core.c:balance_push
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cpuset.c:cpuset_read_unlock
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
  - mm/filemap.c:filemap_page_mkwrite
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/pipe.c:pipe_write
  - fs/inode.c:touch_atime
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_want_write
  - fs/splice.c:do_splice
  - fs/remap_range.c:vfs_clone_file_range
  - fs/aio.c:aio_complete_rw
  - fs/io_uring.c:kiocb_done
  - fs/io_uring.c:io_complete_rw_iopoll
  - fs/io_uring.c:io_complete_rw
  - fs/locks.c:locks_remove_file
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/coredump.c:do_coredump
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - fs/fuse/dax.c:__fuse_dax_fault
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff810b9d10-ffffffff810b9d42: rcuwait_wake_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rcuwait_wake_up(struct rcuwait *w);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810d0830)
Location: kernel/exit.c:236
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/workqueue.c:worker_thread
  - kernel/sched/core.c:balance_push
  - kernel/locking/percpu-rwsem.c:__percpu_down_read
  - kernel/rcu/update.c:call_rcu_tasks_iw_wakeup
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cpuset.c:cpuset_read_unlock
  - kernel/irq_work.c:irq_work_single
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
  - mm/filemap.c:filemap_page_mkwrite
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/pipe.c:pipe_write
  - fs/inode.c:touch_atime
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_want_write
  - fs/splice.c:do_splice
  - fs/remap_range.c:vfs_clone_file_range
  - fs/aio.c:aio_complete_rw
  - fs/locks.c:locks_remove_file
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/coredump.c:do_coredump
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - fs/fuse/dax.c:__fuse_dax_fault
```
**Symbols:**

```
ffffffff810d0830-ffffffff810d086c: rcuwait_wake_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rcuwait_wake_up(struct rcuwait *w);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810ef1b0)
Location: kernel/exit.c:288
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/workqueue.c:worker_thread
  - kernel/sched/core.c:balance_push
  - kernel/locking/percpu-rwsem.c:__percpu_down_read
  - kernel/rcu/update.c:call_rcu_tasks_iw_wakeup
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cpuset.c:cpuset_read_unlock
  - kernel/irq_work.c:irq_work_single
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
  - mm/filemap.c:filemap_page_mkwrite
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/pipe.c:pipe_write
  - fs/inode.c:touch_atime
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_want_write
  - fs/splice.c:do_splice
  - fs/remap_range.c:vfs_clone_file_range
  - fs/aio.c:aio_complete_rw
  - fs/locks.c:locks_remove_file
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/coredump.c:do_coredump
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - fs/fuse/dax.c:__fuse_dax_fault
```
**Symbols:**

```
ffffffff810ef1b0-ffffffff810ef1ec: rcuwait_wake_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rcuwait_wake_up(struct rcuwait *w);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810fb1d0)
Location: kernel/exit.c:289
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/workqueue.c:worker_thread
  - kernel/sched/core.c:balance_push
  - kernel/locking/percpu-rwsem.c:__percpu_down_read
  - kernel/rcu/update.c:call_rcu_tasks_iw_wakeup
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:cgroup_css_set_put_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/irq_work.c:irq_work_single
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
  - mm/filemap.c:filemap_page_mkwrite
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/pipe.c:pipe_write
  - fs/inode.c:touch_atime
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_want_write
  - fs/splice.c:do_splice
  - fs/remap_range.c:vfs_clone_file_range
  - fs/aio.c:aio_complete_rw
  - fs/locks.c:locks_remove_file
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/coredump.c:do_coredump
  - fs/quota/quota.c:quotactl_block
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - fs/fuse/dax.c:__fuse_dax_fault
```
**Symbols:**

```
ffffffff810fb1d0-ffffffff810fb20c: rcuwait_wake_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rcuwait_wake_up(struct rcuwait *w);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81104680)
Location: kernel/exit.c:292
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/workqueue.c:worker_thread
  - kernel/sched/core.c:balance_push
  - kernel/locking/percpu-rwsem.c:__percpu_down_read
  - kernel/rcu/update.c:call_rcu_tasks_iw_wakeup
  - kernel/rcu/update.c:call_rcu_tasks_generic_timer
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:cgroup_css_set_put_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/irq_work.c:irq_work_single
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
  - mm/filemap.c:filemap_page_mkwrite
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_iter_write
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:vfs_write
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/pipe.c:pipe_write
  - fs/inode.c:touch_atime
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_want_write
  - fs/splice.c:do_splice
  - fs/splice.c:direct_splice_actor
  - fs/remap_range.c:vfs_clone_file_range
  - fs/aio.c:aio_complete_rw
  - fs/locks.c:locks_remove_file
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/backing-file.c:backing_aio_rw_complete
  - fs/coredump.c:do_coredump
  - fs/quota/quota.c:quotactl_block
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - fs/fuse/dax.c:__fuse_dax_fault
```
**Symbols:**

```
ffffffff81104680-ffffffff811046bc: rcuwait_wake_up (STB_GLOBAL)
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
void rcuwait_wake_up(struct rcuwait *w);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffff8000100fcee0)
Location: kernel/exit.c:237
Inline: False
Direct callers:
  - kernel/locking/percpu-rwsem.c:__percpu_up_read
```
**Symbols:**

```
ffff8000100fcee0-ffff8000100fcf14: rcuwait_wake_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rcuwait_wake_up(struct rcuwait *w);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (c0359ff0)
Location: kernel/exit.c:237
Inline: False
Direct callers:
  - kernel/locking/percpu-rwsem.c:__percpu_up_read
```
**Symbols:**

```
c0359ff0-c035a01c: rcuwait_wake_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rcuwait_wake_up(struct rcuwait *w);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (c000000000143c70)
Location: kernel/exit.c:237
Inline: False
Direct callers:
  - kernel/locking/percpu-rwsem.c:__percpu_up_read
```
**Symbols:**

```
c000000000143c70-c000000000143cc4: rcuwait_wake_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rcuwait_wake_up(struct rcuwait *w);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffe0000c587c)
Location: kernel/exit.c:237
Inline: False
Direct callers:
  - kernel/locking/percpu-rwsem.c:__percpu_up_read
```
**Symbols:**

```
ffffffe0000c587c-ffffffe0000c58ac: rcuwait_wake_up (STB_GLOBAL)
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
void rcuwait_wake_up(struct rcuwait *w);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109f930)
Location: kernel/exit.c:237
Inline: False
```
**Symbols:**

```
ffffffff8109f930-ffffffff8109f94f: rcuwait_wake_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rcuwait_wake_up(struct rcuwait *w);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8108e360)
Location: kernel/exit.c:237
Inline: False
```
**Symbols:**

```
ffffffff8108e360-ffffffff8108e37f: rcuwait_wake_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rcuwait_wake_up(struct rcuwait *w);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109f8e0)
Location: kernel/exit.c:237
Inline: False
```
**Symbols:**

```
ffffffff8109f8e0-ffffffff8109f8ff: rcuwait_wake_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rcuwait_wake_up(struct rcuwait *w);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a7840)
Location: kernel/exit.c:237
Inline: False
```
**Symbols:**

```
ffffffff810a7840-ffffffff810a786d: rcuwait_wake_up (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
