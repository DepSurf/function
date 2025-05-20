# Function: <code>percpu_up_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void percpu_up_read(struct percpu_rw_semaphore *brw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810ca100)
Location: kernel/locking/percpu-rwsem.c:98
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
  - fs/super.c:__sb_end_write
```
**Symbols:**

```
ffffffff810ca100-ffffffff810ca136: percpu_up_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void percpu_up_read(struct percpu_rw_semaphore *brw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810ceac0)
Location: kernel/locking/percpu-rwsem.c:99
Inline: True
Direct callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
  - fs/super.c:__sb_end_write
  - fs/ext4/inode.c:ext4_writepages
```
**Symbols:**

```
ffffffff810ceac0-ffffffff810ceaf6: percpu_up_read (STB_GLOBAL)
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
In kernel/fork.c (ffffffff81085d0b)
Location: include/linux/percpu-rwsem.h:104
Inline: True
```
```
In kernel/signal.c (ffffffff810988df)
Location: include/linux/percpu-rwsem.h:104
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In kernel/events/uprobes.c (ffffffff811aa5c5)
Location: include/linux/percpu-rwsem.h:104
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
```
```
In fs/super.c (ffffffff81248338)
Location: include/linux/percpu-rwsem.h:104
Inline: True
Inline callers:
  - fs/super.c:__sb_end_write
```
```
In fs/exec.c (ffffffff8124ce77)
Location: include/linux/percpu-rwsem.h:104
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812df156)
Location: include/linux/percpu-rwsem.h:104
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
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
In kernel/fork.c (ffffffff81082721)
Location: include/linux/percpu-rwsem.h:104
Inline: True
```
```
In kernel/cpu.c (ffffffff810866e5)
Location: include/linux/percpu-rwsem.h:104
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
```
```
In kernel/signal.c (ffffffff81095b7a)
Location: include/linux/percpu-rwsem.h:104
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In kernel/events/uprobes.c (ffffffff811b1b25)
Location: include/linux/percpu-rwsem.h:104
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
```
```
In mm/memory_hotplug.c (ffffffff8122c4db)
Location: include/linux/percpu-rwsem.h:104
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In fs/super.c (ffffffff81253c44)
Location: include/linux/percpu-rwsem.h:104
Inline: True
Inline callers:
  - fs/super.c:__sb_end_write
```
```
In fs/exec.c (ffffffff81258e92)
Location: include/linux/percpu-rwsem.h:104
Inline: True
```
```
In fs/ext4/inode.c (ffffffff8130334e)
Location: include/linux/percpu-rwsem.h:104
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
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
In kernel/fork.c (ffffffff81089522)
Location: include/linux/percpu-rwsem.h:105
Inline: True
```
```
In kernel/cpu.c (ffffffff8108d345)
Location: include/linux/percpu-rwsem.h:105
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
```
```
In kernel/signal.c (ffffffff8109c9ca)
Location: include/linux/percpu-rwsem.h:105
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In kernel/events/uprobes.c (ffffffff811c5739)
Location: include/linux/percpu-rwsem.h:105
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
```
```
In mm/memory_hotplug.c (ffffffff81247cbb)
Location: include/linux/percpu-rwsem.h:105
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In fs/super.c (ffffffff81275cc8)
Location: include/linux/percpu-rwsem.h:105
Inline: True
Inline callers:
  - fs/super.c:__sb_end_write
```
```
In fs/exec.c (ffffffff8127b028)
Location: include/linux/percpu-rwsem.h:105
Inline: True
```
```
In fs/ext4/inode.c (ffffffff81327d3e)
Location: include/linux/percpu-rwsem.h:105
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
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
In kernel/fork.c (ffffffff8108ad30)
Location: include/linux/percpu-rwsem.h:105
Inline: True
```
```
In kernel/cpu.c (ffffffff8108f4f5)
Location: include/linux/percpu-rwsem.h:105
Inline: True
Inline callers:
  - kernel/cpu.c:cpus_read_unlock
```
```
In kernel/signal.c (ffffffff810a0dca)
Location: include/linux/percpu-rwsem.h:105
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In kernel/events/uprobes.c (ffffffff811e5c75)
Location: include/linux/percpu-rwsem.h:105
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
```
```
In mm/memory_hotplug.c (ffffffff8126baf5)
Location: include/linux/percpu-rwsem.h:105
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_online_mems
```
```
In fs/super.c (ffffffff8129c225)
Location: include/linux/percpu-rwsem.h:105
Inline: True
Inline callers:
  - fs/super.c:__sb_end_write
```
```
In fs/exec.c (ffffffff812a270c)
Location: include/linux/percpu-rwsem.h:105
Inline: True
```
```
In fs/ext4/inode.c (ffffffff8135023f)
Location: include/linux/percpu-rwsem.h:105
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
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
In kernel/fork.c (ffffffff81092d30)
Location: include/linux/percpu-rwsem.h:105
Inline: True
```
```
In kernel/cpu.c (ffffffff810977f5)
Location: include/linux/percpu-rwsem.h:105
Inline: True
Inline callers:
  - kernel/cpu.c:cpus_read_unlock
```
```
In kernel/signal.c (ffffffff810a920a)
Location: include/linux/percpu-rwsem.h:105
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In kernel/events/uprobes.c (ffffffff811f67c5)
Location: include/linux/percpu-rwsem.h:105
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
```
```
In mm/memory_hotplug.c (ffffffff812803f5)
Location: include/linux/percpu-rwsem.h:105
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_online_mems
```
```
In fs/super.c (ffffffff812b1365)
Location: include/linux/percpu-rwsem.h:105
Inline: True
Inline callers:
  - fs/super.c:__sb_end_write
```
```
In fs/exec.c (ffffffff812b72fb)
Location: include/linux/percpu-rwsem.h:105
Inline: True
```
```
In fs/ext4/inode.c (ffffffff8136859f)
Location: include/linux/percpu-rwsem.h:105
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
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
In kernel/fork.c (ffffffff81096d30)
Location: include/linux/percpu-rwsem.h:84
Inline: True
```
```
In kernel/cpu.c (ffffffff8109bdb5)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - kernel/cpu.c:cpus_read_unlock
```
```
In kernel/signal.c (ffffffff810ad5d0)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In kernel/events/uprobes.c (ffffffff8120e575)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
```
```
In mm/memory_hotplug.c (ffffffff8129c735)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_online_mems
```
```
In fs/super.c (ffffffff812cddff)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - fs/super.c:__sb_end_write
```
```
In fs/exec.c (ffffffff812d4cf2)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/locks.c (ffffffff8133e840)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
```
In fs/ext4/inode.c (ffffffff81391da0)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
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
In kernel/fork.c (ffffffff8109d560)
Location: include/linux/percpu-rwsem.h:84
Inline: True
```
```
In kernel/cpu.c (ffffffff810a2335)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - kernel/cpu.c:cpus_read_unlock
```
```
In kernel/signal.c (ffffffff810b3bf0)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In kernel/cgroup/cpuset.c (ffffffff81170695)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_read_unlock
```
```
In kernel/events/uprobes.c (ffffffff8121bbb5)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
```
```
In mm/memory_hotplug.c (ffffffff812ac3d5)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_online_mems
```
```
In fs/super.c (ffffffff812df82f)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - fs/super.c:__sb_end_write
```
```
In fs/exec.c (ffffffff812e6872)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/locks.c (ffffffff81356e30)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
```
In fs/ext4/inode.c (ffffffff813aa730)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
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
In kernel/cpu.c (ffffffff810aa8e5)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
```
```
In kernel/signal.c (ffffffff810bc6a6)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In kernel/cgroup/cgroup.c (ffffffff81177ec4)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
```
```
In kernel/cgroup/cpuset.c (ffffffff81182a65)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_read_unlock
```
```
In kernel/events/uprobes.c (ffffffff81248285)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
```
```
In mm/memory_hotplug.c (ffffffff812e0857)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In fs/super.c (ffffffff813165d8)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/super.c:__sb_end_write
```
```
In fs/exec.c (ffffffff8131e111)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/locks.c (ffffffff8139e09b)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:generic_delete_lease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
```
In fs/ext4/inode.c (ffffffff813f69ad)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
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
In kernel/cpu.c (ffffffff810a6175)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
```
```
In kernel/signal.c (ffffffff810b7996)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In kernel/acct.c (ffffffff81165d69)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff81174be4)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
```
```
In kernel/cgroup/cpuset.c (ffffffff8117f9a5)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_read_unlock
```
```
In kernel/events/uprobes.c (ffffffff81252995)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
```
```
In mm/filemap.c (ffffffff8125ac2c)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In mm/memory_hotplug.c (ffffffff812eb4e7)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In fs/open.c (ffffffff81319f93)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff813209f8)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
```
```
In fs/exec.c (ffffffff81329621)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/pipe.c (ffffffff8132acdd)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff813433fc)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/namespace.c (ffffffff81346a79)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_want_write
```
```
In fs/splice.c (ffffffff8135ed42)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff813667ec)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/aio.c (ffffffff81385732)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/io_uring.c (ffffffff8138a6f7)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/io_uring.c:io_complete_rw_iopoll
  - fs/io_uring.c:io_complete_rw_common
```
```
In fs/locks.c (ffffffff813afa2b)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:generic_delete_lease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
```
In fs/coredump.c (ffffffff813b9462)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/file.c (ffffffff813fb14d)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff814129b6)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/mmp.c (ffffffff814211f2)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/super.c (ffffffff8143ef15)
Location: include/linux/percpu-rwsem.h:97
Inline: True
```
```
In fs/fuse/dax.c (ffffffff8149c5fb)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
```
```
In drivers/block/loop.c (ffffffff817fcecc)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_write_bvec
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
In kernel/cpu.c (ffffffff810a6fc5)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
```
```
In kernel/signal.c (ffffffff810b8ef6)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In kernel/acct.c (ffffffff81166a99)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff811757a0)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
```
```
In kernel/cgroup/cpuset.c (ffffffff81180485)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_read_unlock
```
```
In kernel/events/uprobes.c (ffffffff812569f5)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
```
```
In mm/filemap.c (ffffffff8125f687)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In mm/memory_hotplug.c (ffffffff812c61f7)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In fs/open.c (ffffffff81320073)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff81326a86)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
```
```
In fs/exec.c (ffffffff8132f431)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/pipe.c (ffffffff81330990)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff813496ec)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/namespace.c (ffffffff8134cd5f)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_want_write
```
```
In fs/splice.c (ffffffff8136568c)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff8136d09c)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/aio.c (ffffffff8138c9a2)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/io_uring.c (ffffffff8139a8f3)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/io_uring.c:io_complete_rw_iopoll
```
```
In fs/locks.c (ffffffff813b6cbb)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
```
In fs/coredump.c (ffffffff813c0448)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/file.c (ffffffff8140161d)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff81418e16)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/mmp.c (ffffffff814279a2)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/super.c (ffffffff81444d55)
Location: include/linux/percpu-rwsem.h:97
Inline: True
```
```
In fs/fuse/dax.c (ffffffff814a262b)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
```
```
In drivers/block/loop.c (ffffffff817e195c)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_write_bvec
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
In kernel/cpu.c (ffffffff810b8965)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
```
```
In kernel/signal.c (ffffffff810cb486)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In kernel/acct.c (ffffffff8118c259)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff8119cd30)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
```
```
In kernel/cgroup/cpuset.c (ffffffff811a8245)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_read_unlock
```
```
In kernel/events/uprobes.c (ffffffff81292795)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
```
```
In mm/filemap.c (ffffffff8129bdfc)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In mm/memory_hotplug.c (ffffffff8130ac57)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In fs/open.c (ffffffff8136d613)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff81374026)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
```
```
In fs/exec.c (ffffffff8137cc11)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/pipe.c (ffffffff8137e110)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff8139743c)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/namespace.c (ffffffff8139accf)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_want_write
```
```
In fs/splice.c (ffffffff813b3f7c)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff813bbd7c)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/aio.c (ffffffff813d9ff2)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/io_uring.c (ffffffff813eb91a)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/io_uring.c:kiocb_done
  - fs/io_uring.c:io_complete_rw_iopoll
  - fs/io_uring.c:io_complete_rw
```
```
In fs/locks.c (ffffffff814069bb)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
```
In fs/coredump.c (ffffffff81410270)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/file.c (ffffffff81453ba6)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff8146c04a)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/mmp.c (ffffffff8147b66d)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/super.c (ffffffff81498be5)
Location: include/linux/percpu-rwsem.h:97
Inline: True
```
```
In fs/fuse/dax.c (ffffffff814fa6d6)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
```
```
In drivers/block/loop.c (ffffffff8186d0fc)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_write_bvec
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
In kernel/cpu.c (ffffffff810cf235)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
```
```
In kernel/signal.c (ffffffff810e4ae2)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In kernel/acct.c (ffffffff811bb651)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff811cd03a)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
```
```
In kernel/cgroup/cpuset.c (ffffffff811d9345)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_read_unlock
```
```
In kernel/events/uprobes.c (ffffffff812e8145)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
```
```
In mm/filemap.c (ffffffff812f1ba1)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In mm/memory_hotplug.c (ffffffff81373b08)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In fs/open.c (ffffffff813ec1ae)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff813f2fbe)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
```
```
In fs/exec.c (ffffffff813fbf55)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/pipe.c (ffffffff813fdd4d)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff81419613)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/namespace.c (ffffffff8141e6fe)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_want_write
```
```
In fs/splice.c (ffffffff814392a7)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff8144265a)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/aio.c (ffffffff814644de)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/locks.c (ffffffff8147b4f0)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
```
In fs/coredump.c (ffffffff81485f04)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/file.c (ffffffff814d1089)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff814ec014)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/mmp.c (ffffffff814fdb25)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/super.c (ffffffff81523abb)
Location: include/linux/percpu-rwsem.h:97
Inline: True
```
```
In fs/fuse/dax.c (ffffffff8158ac11)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
```
```
In io_uring/io_uring.c (ffffffff816ca791)
Location: include/linux/percpu-rwsem.h:97
Inline: True
```
```
In drivers/block/loop.c (ffffffff819b6daf)
Location: include/linux/percpu-rwsem.h:97
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
In kernel/cpu.c (ffffffff810ed6a5)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
```
```
In kernel/signal.c (ffffffff81105132)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In kernel/acct.c (ffffffff811fd471)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff812105fb)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
```
```
In kernel/cgroup/cpuset.c (ffffffff8121e5d5)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_read_unlock
```
```
In kernel/events/hw_breakpoint.c (ffffffff8134cd92)
Location: include/linux/percpu-rwsem.h:97
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff81351e95)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
```
```
In mm/filemap.c (ffffffff8135cc97)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In mm/memory_hotplug.c (ffffffff813f1238)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In fs/open.c (ffffffff8147467e)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff8147bc9a)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
```
```
In fs/exec.c (ffffffff81485005)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/pipe.c (ffffffff8148796d)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff814a5053)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/namespace.c (ffffffff814aae0e)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_want_write
```
```
In fs/splice.c (ffffffff814c7597)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff814d134a)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/aio.c (ffffffff814f481e)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/locks.c (ffffffff8150e080)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
```
In fs/coredump.c (ffffffff815196f4)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/file.c (ffffffff81569acd)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff81585d7e)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/mmp.c (ffffffff81598310)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/super.c (ffffffff815c0ca2)
Location: include/linux/percpu-rwsem.h:97
Inline: True
```
```
In fs/fuse/dax.c (ffffffff8163136e)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
```
```
In io_uring/rw.c (ffffffff817a38d5)
Location: include/linux/percpu-rwsem.h:97
Inline: True
```
```
In drivers/block/loop.c (ffffffff81b2c00b)
Location: include/linux/percpu-rwsem.h:97
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
In kernel/cpu.c (ffffffff810f9235)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
```
```
In kernel/signal.c (ffffffff811113ba)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In kernel/acct.c (ffffffff812125fe)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff8121ee1b)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_put_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
```
```
In kernel/events/hw_breakpoint.c (ffffffff8137dbe2)
Location: include/linux/percpu-rwsem.h:97
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff813830a5)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
```
```
In mm/filemap.c (ffffffff8138ecc5)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In mm/memory_hotplug.c (ffffffff81424c78)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In fs/open.c (ffffffff814a9048)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff814b0845)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
```
```
In fs/exec.c (ffffffff814b9f85)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/pipe.c (ffffffff814bc7dd)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff814da2d3)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/namespace.c (ffffffff814dfcc1)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_want_write
```
```
In fs/splice.c (ffffffff814fd4a9)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff81507640)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/aio.c (ffffffff8152b5f1)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/locks.c (ffffffff81545853)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
```
In fs/coredump.c (ffffffff81550fcc)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/quota.c (ffffffff8156097a)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/quota/quota.c:quotactl_block
```
```
In fs/ext4/file.c (ffffffff815a18bd)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff815bc639)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/mmp.c (ffffffff815cee39)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/super.c (ffffffff815f8422)
Location: include/linux/percpu-rwsem.h:97
Inline: True
```
```
In fs/fuse/dax.c (ffffffff816695a4)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
```
```
In io_uring/rw.c (ffffffff817e4908)
Location: include/linux/percpu-rwsem.h:97
Inline: True
```
```
In drivers/block/loop.c (ffffffff81b7c340)
Location: include/linux/percpu-rwsem.h:97
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
In kernel/cpu.c (ffffffff81102645)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
```
```
In kernel/signal.c (ffffffff8111ad4e)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In kernel/acct.c (ffffffff81229c7e)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff81236aab)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_put_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
```
```
In kernel/events/hw_breakpoint.c (ffffffff813a6e42)
Location: include/linux/percpu-rwsem.h:97
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff813ac475)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
```
```
In mm/filemap.c (ffffffff813b80b2)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In mm/memory_hotplug.c (ffffffff81451fb8)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In fs/open.c (ffffffff814da0a7)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff814e1f9f)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_iter_write
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:vfs_write
```
```
In fs/exec.c (ffffffff814ec501)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/pipe.c (ffffffff814eed18)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff8150c8be)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/namespace.c (ffffffff81512bc1)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_want_write
```
```
In fs/splice.c (ffffffff81532100)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/splice.c:do_splice
  - fs/splice.c:direct_splice_actor
```
```
In fs/remap_range.c (ffffffff8153c7ec)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/aio.c (ffffffff81560541)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/locks.c (ffffffff8157adb3)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
```
In fs/backing-file.c (ffffffff81581c7c)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/backing-file.c:backing_aio_rw_complete
```
```
In fs/coredump.c (ffffffff81586e5d)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/quota.c (ffffffff8159706a)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/quota/quota.c:quotactl_block
```
```
In fs/ext4/file.c (ffffffff815da66d)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff815f5419)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/mmp.c (ffffffff816076c9)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/super.c (ffffffff81630fd2)
Location: include/linux/percpu-rwsem.h:97
Inline: True
```
```
In fs/fuse/dax.c (ffffffff816a38a4)
Location: include/linux/percpu-rwsem.h:97
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
```
```
In io_uring/rw.c (ffffffff8182885e)
Location: include/linux/percpu-rwsem.h:97
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/fork.c (ffff8000100f14e8)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffff8000100f9088)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
```
```
In kernel/signal.c (ffff80001010fc08)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In kernel/cgroup/cpuset.c (ffff8000101e3e40)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_read_unlock
```
```
In kernel/events/uprobes.c (ffff8000102a7438)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
```
```
In mm/memory_hotplug.c (ffff80001034dda0)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In fs/super.c (ffff8000103862a0)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - fs/super.c:__sb_end_write
```
```
In fs/exec.c (ffff80001038eb2c)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/locks.c (ffff8000104199c8)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
```
In fs/ext4/inode.c (ffff80001047e6dc)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
```
**Symbols:**

```
ffff8000100f14e8-ffff8000100f1528: percpu_up_read.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/fork.c (c0350a20)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (c03572b0)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
```
```
In kernel/signal.c (c036798c)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In kernel/cgroup/cpuset.c (c0424ec4)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_read_unlock
```
```
In kernel/events/uprobes.c (c04d6564)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
```
```
In fs/super.c (c056f1d0)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - fs/super.c:__sb_end_write
```
```
In fs/exec.c (c05750a0)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/locks.c (c05e5d50)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
```
In fs/ext4/inode.c (c0646654)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
```
**Symbols:**

```
c0350a20-c0350a60: percpu_up_read.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/fork.c (c000000000137240)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (c00000000013fcf4)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
```
```
In kernel/signal.c (c000000000157220)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In kernel/cgroup/cpuset.c (c000000000254250)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_read_unlock
```
```
In kernel/events/uprobes.c (c00000000035a910)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
```
```
In mm/memory_hotplug.c (c00000000042de7c)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In fs/super.c (c00000000047c810)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - fs/super.c:__sb_end_write
```
```
In fs/exec.c (c000000000485a94)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/locks.c (c000000000529578)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
```
In fs/ext4/inode.c (c0000000005a2eec)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
```
**Symbols:**

```
c000000000137240-c0000000001372a4: percpu_up_read.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/fork.c (ffffffe0000bed36)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffe0000cff72)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In kernel/cgroup/cpuset.c (ffffffe00015a2b4)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_read_unlock
```
```
In fs/super.c (ffffffe000258d3e)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - fs/super.c:__sb_end_write
```
```
In fs/exec.c (ffffffe00025e41e)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/locks.c (ffffffe0002c00f4)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
```
In fs/ext4/inode.c (ffffffe000307b3e)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
```
**Symbols:**

```
ffffffe0000bed36-ffffffe0000bed80: percpu_up_read.constprop.0 (STB_LOCAL)
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
In kernel/fork.c (ffffffff81096e80)
Location: include/linux/percpu-rwsem.h:84
Inline: True
```
```
In kernel/cpu.c (ffffffff8109bc55)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - kernel/cpu.c:cpus_read_unlock
```
```
In kernel/signal.c (ffffffff810adf60)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In kernel/cgroup/cpuset.c (ffffffff81168cb5)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_read_unlock
```
```
In kernel/events/uprobes.c (ffffffff81214205)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
```
```
In mm/memory_hotplug.c (ffffffff812a49b5)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_online_mems
```
```
In fs/super.c (ffffffff812d7e0f)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - fs/super.c:__sb_end_write
```
```
In fs/exec.c (ffffffff812dee52)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/locks.c (ffffffff8134f410)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
```
In fs/ext4/inode.c (ffffffff813a2d10)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
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
In kernel/fork.c (ffffffff81085900)
Location: include/linux/percpu-rwsem.h:84
Inline: True
```
```
In kernel/cpu.c (ffffffff8108a685)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - kernel/cpu.c:cpus_read_unlock
```
```
In kernel/signal.c (ffffffff8109c8c0)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In kernel/cgroup/cpuset.c (ffffffff8115bec5)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_read_unlock
```
```
In kernel/events/uprobes.c (ffffffff81206f75)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
```
```
In mm/memory_hotplug.c (ffffffff81296485)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_online_mems
```
```
In fs/super.c (ffffffff812c8a8f)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - fs/super.c:__sb_end_write
```
```
In fs/exec.c (ffffffff812cef71)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/locks.c (ffffffff813400f0)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
```
In fs/ext4/inode.c (ffffffff813937a0)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
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
In kernel/fork.c (ffffffff81096e30)
Location: include/linux/percpu-rwsem.h:84
Inline: True
```
```
In kernel/cpu.c (ffffffff8109bc05)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - kernel/cpu.c:cpus_read_unlock
```
```
In kernel/signal.c (ffffffff810ad4c0)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In kernel/cgroup/cpuset.c (ffffffff81166a85)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_read_unlock
```
```
In kernel/events/uprobes.c (ffffffff81211fa5)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
```
```
In mm/memory_hotplug.c (ffffffff812a27c5)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_online_mems
```
```
In fs/super.c (ffffffff812d5c1f)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - fs/super.c:__sb_end_write
```
```
In fs/exec.c (ffffffff812dcc62)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/locks.c (ffffffff8134cee0)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
```
In fs/ext4/inode.c (ffffffff813a0570)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/fork.c (ffffffff8109ecd0)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffff810a4f50)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
```
```
In kernel/signal.c (ffffffff810b568d)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In kernel/cgroup/cpuset.c (ffffffff81174115)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_read_unlock
```
```
In kernel/events/uprobes.c (ffffffff81220f05)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
```
```
In mm/memory_hotplug.c (ffffffff812b2452)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In fs/super.c (ffffffff812e6c33)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - fs/super.c:__sb_end_write
```
```
In fs/exec.c (ffffffff812eda09)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/locks.c (ffffffff8136044a)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
```
In fs/ext4/inode.c (ffffffff813b4d3f)
Location: include/linux/percpu-rwsem.h:84
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
```
**Symbols:**

```
ffffffff8109ecd0-ffffffff8109ed0f: percpu_up_read.constprop.0 (STB_LOCAL)
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
</ul>
