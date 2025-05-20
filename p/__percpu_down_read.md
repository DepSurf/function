# Function: <code>__percpu_down_read</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int __percpu_down_read(struct percpu_rw_semaphore *sem, int try);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810d56e0)
Location: kernel/locking/percpu-rwsem.c:42
Inline: True
Direct callers:
  - kernel/signal.c:exit_signals
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
  - fs/locks.c:locks_remove_file
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/ext4/inode.c:ext4_writepages
```
**Symbols:**

```
ffffffff810d56e0-ffffffff810d575e: __percpu_down_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int __percpu_down_read(struct percpu_rw_semaphore *sem, int try);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810d4690)
Location: kernel/locking/percpu-rwsem.c:41
Inline: True
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/signal.c:exit_signals
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - fs/locks.c:locks_remove_file
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/ext4/inode.c:ext4_writepages
```
**Symbols:**

```
ffffffff810d4690-ffffffff810d4700: __percpu_down_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __percpu_down_read(struct percpu_rw_semaphore *sem, int try);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810dc600)
Location: kernel/locking/percpu-rwsem.c:41
Inline: True
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/signal.c:exit_signals
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - fs/locks.c:locks_remove_file
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/ext4/inode.c:ext4_writepages
```
**Symbols:**

```
ffffffff810dc600-ffffffff810dc67c: __percpu_down_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int __percpu_down_read(struct percpu_rw_semaphore *sem, int try);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810e4c50)
Location: kernel/locking/percpu-rwsem.c:41
Inline: True
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/signal.c:exit_signals
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - fs/locks.c:locks_remove_file
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
ffffffff810e4c50-ffffffff810e4ccc: __percpu_down_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int __percpu_down_read(struct percpu_rw_semaphore *sem, int try);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810f0230)
Location: kernel/locking/percpu-rwsem.c:41
Inline: True
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/cpu.c:cpus_read_trylock
  - kernel/signal.c:exit_signals
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - fs/locks.c:locks_remove_file
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
ffffffff810f0230-ffffffff810f02ac: __percpu_down_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int __percpu_down_read(struct percpu_rw_semaphore *sem, int try);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810f88a0)
Location: kernel/locking/percpu-rwsem.c:44
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/cpu.c:cpus_read_trylock
  - kernel/signal.c:exit_signals
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - fs/exec.c:de_thread
  - fs/locks.c:locks_remove_file
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
ffffffff810f88a0-ffffffff810f8911: __percpu_down_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __percpu_down_read(struct percpu_rw_semaphore *sem, int try);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff811046e0)
Location: kernel/locking/percpu-rwsem.c:44
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/cpu.c:cpus_read_trylock
  - kernel/signal.c:exit_signals
  - kernel/cgroup/cpuset.c:cpuset_read_lock
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - fs/exec.c:de_thread
  - fs/locks.c:locks_remove_file
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
ffffffff811046e0-ffffffff81104751: __percpu_down_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool __percpu_down_read(struct percpu_rw_semaphore *sem, bool try);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff8110f360)
Location: kernel/locking/percpu-rwsem.c:165
Inline: True
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/cpu.c:cpus_read_trylock
  - kernel/signal.c:exit_signals
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cpuset.c:cpuset_read_lock
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
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
ffffffff8110f360-ffffffff8110f3b8: __percpu_down_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool __percpu_down_read(struct percpu_rw_semaphore *sem, bool try);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff8110c520)
Location: kernel/locking/percpu-rwsem.c:165
Inline: True
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/cpu.c:cpus_read_trylock
  - kernel/signal.c:exit_signals
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cpuset.c:cpuset_read_lock
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
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
  - fs/pipe.c:pipe_write
  - fs/inode.c:touch_atime
  - fs/namespace.c:mnt_want_write
  - fs/splice.c:do_splice
  - fs/remap_range.c:vfs_clone_file_range
  - fs/aio.c:aio_write
  - fs/io_uring.c:io_write
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
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - fs/fuse/dax.c:__fuse_dax_fault
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff8110c520-ffffffff8110c578: __percpu_down_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool __percpu_down_read(struct percpu_rw_semaphore *sem, bool try);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff8110e350)
Location: kernel/locking/percpu-rwsem.c:165
Inline: True
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/cpu.c:cpus_read_trylock
  - kernel/signal.c:exit_signals
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cpuset.c:cpuset_read_lock
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
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
  - fs/pipe.c:pipe_write
  - fs/inode.c:touch_atime
  - fs/namespace.c:mnt_want_write
  - fs/splice.c:do_splice
  - fs/remap_range.c:vfs_clone_file_range
  - fs/aio.c:aio_write
  - fs/io_uring.c:io_write
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
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - fs/fuse/dax.c:__fuse_dax_fault
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff8110e350-ffffffff8110e3a8: __percpu_down_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool __percpu_down_read(struct percpu_rw_semaphore *sem, bool try);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff8112da90)
Location: kernel/locking/percpu-rwsem.c:165
Inline: True
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/cpu.c:cpus_read_trylock
  - kernel/signal.c:exit_signals
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cpuset.c:cpuset_read_lock
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
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
  - fs/pipe.c:pipe_write
  - fs/inode.c:touch_atime
  - fs/namespace.c:mnt_want_write
  - fs/splice.c:do_splice
  - fs/remap_range.c:vfs_clone_file_range
  - fs/aio.c:aio_write
  - fs/io_uring.c:io_write
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
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - fs/fuse/dax.c:__fuse_dax_fault
  - drivers/block/loop.c:lo_write_bvec
```
**Symbols:**

```
ffffffff8112da90-ffffffff8112dae8: __percpu_down_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool __percpu_down_read(struct percpu_rw_semaphore *sem, bool try);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff81f25c90)
Location: kernel/locking/percpu-rwsem.c:167
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/cpu.c:cpus_read_trylock
  - kernel/signal.c:exit_signals
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cpuset.c:cpuset_read_lock
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
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
  - fs/pipe.c:pipe_write
  - fs/inode.c:touch_atime
  - fs/namespace.c:mnt_want_write
  - fs/splice.c:do_splice
  - fs/remap_range.c:vfs_clone_file_range
  - fs/aio.c:aio_write
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
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - fs/fuse/dax.c:__fuse_dax_fault
  - io_uring/io_uring.c:io_write
```
**Symbols:**

```
ffffffff81f25c90-ffffffff81f25db4: __percpu_down_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool __percpu_down_read(struct percpu_rw_semaphore *sem, bool try);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff820d16f0)
Location: kernel/locking/percpu-rwsem.c:167
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/cpu.c:cpus_read_trylock
  - kernel/signal.c:exit_signals
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cpuset.c:cpuset_read_lock
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
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
  - fs/pipe.c:pipe_write
  - fs/inode.c:touch_atime
  - fs/namespace.c:mnt_want_write
  - fs/splice.c:do_splice
  - fs/remap_range.c:vfs_clone_file_range
  - fs/aio.c:aio_write
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
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - fs/fuse/dax.c:__fuse_dax_fault
  - io_uring/rw.c:io_write
```
**Symbols:**

```
ffffffff820d16f0-ffffffff820d1816: __percpu_down_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool __percpu_down_read(struct percpu_rw_semaphore *sem, bool try);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff82155a60)
Location: kernel/locking/percpu-rwsem.c:167
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/cpu.c:cpus_read_trylock
  - kernel/signal.c:exit_signals
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
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
  - fs/pipe.c:pipe_write
  - fs/inode.c:touch_atime
  - fs/namespace.c:mnt_want_write
  - fs/splice.c:do_splice
  - fs/remap_range.c:vfs_clone_file_range
  - fs/aio.c:aio_write
  - fs/locks.c:locks_remove_file
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/coredump.c:do_coredump
  - fs/quota/quota.c:quotactl_block
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - fs/fuse/dax.c:__fuse_dax_fault
  - io_uring/rw.c:io_write
```
**Symbols:**

```
ffffffff82155a60-ffffffff82155b86: __percpu_down_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool __percpu_down_read(struct percpu_rw_semaphore *sem, bool try);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff822388a0)
Location: kernel/locking/percpu-rwsem.c:167
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/cpu.c:cpus_read_trylock
  - kernel/signal.c:exit_signals
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
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
  - fs/pipe.c:pipe_write
  - fs/inode.c:touch_atime
  - fs/namespace.c:mnt_want_write
  - fs/splice.c:do_splice
  - fs/splice.c:direct_splice_actor
  - fs/remap_range.c:vfs_clone_file_range
  - fs/aio.c:aio_write
  - fs/locks.c:locks_remove_file
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/coredump.c:do_coredump
  - fs/quota/quota.c:quotactl_block
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/mmp.c:write_mmp_block
  - fs/fuse/dax.c:__fuse_dax_fault
  - io_uring/rw.c:io_write
```
**Symbols:**

```
ffffffff822388a0-ffffffff822389c6: __percpu_down_read (STB_GLOBAL)
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
int __percpu_down_read(struct percpu_rw_semaphore *sem, int try);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffff80001016a478)
Location: kernel/locking/percpu-rwsem.c:44
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/cpu.c:cpus_read_trylock
  - kernel/signal.c:exit_signals
  - kernel/cgroup/cpuset.c:cpuset_read_lock
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - fs/exec.c:de_thread
  - fs/locks.c:locks_remove_file
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
ffff80001016a478-ffff80001016a530: __percpu_down_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __percpu_down_read(struct percpu_rw_semaphore *sem, int try);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (c03b644c)
Location: kernel/locking/percpu-rwsem.c:44
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/cpu.c:cpus_read_trylock
  - kernel/signal.c:exit_signals
  - kernel/cgroup/cpuset.c:cpuset_read_lock
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
  - fs/exec.c:de_thread
  - fs/locks.c:locks_remove_file
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/ext4/inode.c:ext4_writepages
```
**Symbols:**

```
c03b644c-c03b64dc: __percpu_down_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __percpu_down_read(struct percpu_rw_semaphore *sem, int try);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (c0000000001c2120)
Location: kernel/locking/percpu-rwsem.c:44
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/cpu.c:cpus_read_trylock
  - kernel/signal.c:exit_signals
  - kernel/cgroup/cpuset.c:cpuset_read_lock
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - fs/exec.c:de_thread
  - fs/locks.c:locks_remove_file
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
c0000000001c2120-c0000000001c21e0: __percpu_down_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __percpu_down_read(struct percpu_rw_semaphore *sem, int try);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffe00010b2a0)
Location: kernel/locking/percpu-rwsem.c:44
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/signal.c:exit_signals
  - kernel/cgroup/cpuset.c:cpuset_read_lock
  - fs/exec.c:de_thread
  - fs/locks.c:locks_remove_file
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
ffffffe00010b2a0-ffffffe00010b32a: __percpu_down_read (STB_GLOBAL)
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
int __percpu_down_read(struct percpu_rw_semaphore *sem, int try);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810fd9f0)
Location: kernel/locking/percpu-rwsem.c:44
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/cpu.c:cpus_read_trylock
  - kernel/signal.c:exit_signals
  - kernel/cgroup/cpuset.c:cpuset_read_lock
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - fs/exec.c:de_thread
  - fs/locks.c:locks_remove_file
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
ffffffff810fd9f0-ffffffff810fda61: __percpu_down_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __percpu_down_read(struct percpu_rw_semaphore *sem, int try);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810edbf0)
Location: kernel/locking/percpu-rwsem.c:44
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/cpu.c:cpus_read_trylock
  - kernel/signal.c:exit_signals
  - kernel/cgroup/cpuset.c:cpuset_read_lock
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - fs/exec.c:de_thread
  - fs/locks.c:locks_remove_file
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
ffffffff810edbf0-ffffffff810edc61: __percpu_down_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __percpu_down_read(struct percpu_rw_semaphore *sem, int try);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810fabb0)
Location: kernel/locking/percpu-rwsem.c:44
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/cpu.c:cpus_read_trylock
  - kernel/signal.c:exit_signals
  - kernel/cgroup/cpuset.c:cpuset_read_lock
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - fs/exec.c:de_thread
  - fs/locks.c:locks_remove_file
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
ffffffff810fabb0-ffffffff810fac21: __percpu_down_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __percpu_down_read(struct percpu_rw_semaphore *sem, int try);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff81105d80)
Location: kernel/locking/percpu-rwsem.c:44
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/cpu.c:cpus_read_trylock
  - kernel/signal.c:exit_signals
  - kernel/cgroup/cpuset.c:cpuset_read_lock
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - fs/exec.c:de_thread
  - fs/locks.c:locks_remove_file
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
ffffffff81105d80-ffffffff81105dff: __percpu_down_read (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int try</code> ➡️ <code>bool try</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
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
