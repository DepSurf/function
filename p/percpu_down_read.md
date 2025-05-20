# Function: <code>percpu_down_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void percpu_down_read(struct percpu_rw_semaphore *brw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810ca0b0)
Location: kernel/locking/percpu-rwsem.c:70
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/signal.c:exit_signals
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
```
**Symbols:**

```
ffffffff810ca0b0-ffffffff810ca0ff: percpu_down_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void percpu_down_read(struct percpu_rw_semaphore *brw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810cea70)
Location: kernel/locking/percpu-rwsem.c:71
Inline: True
Direct callers:
  - kernel/signal.c:exit_signals
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
  - fs/ext4/inode.c:ext4_writepages
```
**Symbols:**

```
ffffffff810cea70-ffffffff810ceabf: percpu_down_read (STB_GLOBAL)
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
In kernel/fork.c (ffffffff81085cd7)
Location: include/linux/percpu-rwsem.h:56
Inline: True
```
```
In kernel/signal.c (ffffffff81098897)
Location: include/linux/percpu-rwsem.h:56
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In kernel/events/uprobes.c (ffffffff811aa589)
Location: include/linux/percpu-rwsem.h:56
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
```
```
In fs/super.c (ffffffff81248c0e)
Location: include/linux/percpu-rwsem.h:56
Inline: True
```
```
In fs/exec.c (ffffffff8124ccbc)
Location: include/linux/percpu-rwsem.h:56
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812df0f8)
Location: include/linux/percpu-rwsem.h:56
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
In kernel/fork.c (ffffffff810826ec)
Location: include/linux/percpu-rwsem.h:56
Inline: True
```
```
In kernel/cpu.c (ffffffff810866c1)
Location: include/linux/percpu-rwsem.h:56
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
```
```
In kernel/signal.c (ffffffff81095b32)
Location: include/linux/percpu-rwsem.h:56
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In kernel/events/uprobes.c (ffffffff811b1ae9)
Location: include/linux/percpu-rwsem.h:56
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
```
```
In mm/memory_hotplug.c (ffffffff8122c48f)
Location: include/linux/percpu-rwsem.h:56
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In fs/super.c (ffffffff81254512)
Location: include/linux/percpu-rwsem.h:56
Inline: True
```
```
In fs/exec.c (ffffffff81258cf3)
Location: include/linux/percpu-rwsem.h:56
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813032f2)
Location: include/linux/percpu-rwsem.h:56
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
In kernel/fork.c (ffffffff810894e9)
Location: include/linux/percpu-rwsem.h:57
Inline: True
```
```
In kernel/cpu.c (ffffffff8108d321)
Location: include/linux/percpu-rwsem.h:57
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
```
```
In kernel/signal.c (ffffffff8109c982)
Location: include/linux/percpu-rwsem.h:57
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In kernel/events/uprobes.c (ffffffff811c56f9)
Location: include/linux/percpu-rwsem.h:57
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
```
```
In mm/memory_hotplug.c (ffffffff81247c6f)
Location: include/linux/percpu-rwsem.h:57
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In fs/super.c (ffffffff81276622)
Location: include/linux/percpu-rwsem.h:57
Inline: True
```
```
In fs/exec.c (ffffffff8127ae82)
Location: include/linux/percpu-rwsem.h:57
Inline: True
```
```
In fs/ext4/inode.c (ffffffff81327ce2)
Location: include/linux/percpu-rwsem.h:57
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
In kernel/fork.c (ffffffff8108cf00)
Location: include/linux/percpu-rwsem.h:57
Inline: True
```
```
In kernel/cpu.c (ffffffff81090c85)
Location: include/linux/percpu-rwsem.h:57
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
```
```
In kernel/signal.c (ffffffff810a0d82)
Location: include/linux/percpu-rwsem.h:57
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In kernel/events/uprobes.c (ffffffff811e5c35)
Location: include/linux/percpu-rwsem.h:57
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
```
```
In mm/memory_hotplug.c (ffffffff8126bba5)
Location: include/linux/percpu-rwsem.h:57
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In fs/super.c (ffffffff8129c30d)
Location: include/linux/percpu-rwsem.h:57
Inline: True
```
```
In fs/exec.c (ffffffff812a2566)
Location: include/linux/percpu-rwsem.h:57
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813501ff)
Location: include/linux/percpu-rwsem.h:57
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
In kernel/fork.c (ffffffff81094a26)
Location: include/linux/percpu-rwsem.h:57
Inline: True
```
```
In kernel/cpu.c (ffffffff81098d45)
Location: include/linux/percpu-rwsem.h:57
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
```
```
In kernel/signal.c (ffffffff810a91c2)
Location: include/linux/percpu-rwsem.h:57
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In kernel/events/uprobes.c (ffffffff811f6785)
Location: include/linux/percpu-rwsem.h:57
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
```
```
In mm/memory_hotplug.c (ffffffff812804a5)
Location: include/linux/percpu-rwsem.h:57
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In fs/super.c (ffffffff812b144d)
Location: include/linux/percpu-rwsem.h:57
Inline: True
```
```
In fs/exec.c (ffffffff812b7145)
Location: include/linux/percpu-rwsem.h:57
Inline: True
```
```
In fs/ext4/inode.c (ffffffff8136855f)
Location: include/linux/percpu-rwsem.h:57
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
In kernel/fork.c (ffffffff810991d9)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffff8109d2c5)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
```
```
In kernel/signal.c (ffffffff810ad583)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In kernel/events/uprobes.c (ffffffff8120e535)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
```
```
In mm/memory_hotplug.c (ffffffff8129c7e5)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In fs/super.c (ffffffff812cdf02)
Location: include/linux/percpu-rwsem.h:36
Inline: True
```
```
In fs/exec.c (ffffffff812d4b41)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/locks.c (ffffffff8133e7ce)
Location: include/linux/percpu-rwsem.h:36
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
In fs/ext4/inode.c (ffffffff81391d5d)
Location: include/linux/percpu-rwsem.h:36
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
In kernel/fork.c (ffffffff8109f7d1)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffff810a3815)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
```
```
In kernel/signal.c (ffffffff810b3ba3)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In kernel/cgroup/cpuset.c (ffffffff81170655)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_read_lock
```
```
In kernel/events/uprobes.c (ffffffff8121bb75)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
```
```
In mm/memory_hotplug.c (ffffffff812ac485)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In fs/super.c (ffffffff812df952)
Location: include/linux/percpu-rwsem.h:36
Inline: True
```
```
In fs/exec.c (ffffffff812e66c1)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/locks.c (ffffffff81356dbe)
Location: include/linux/percpu-rwsem.h:36
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
In fs/ext4/inode.c (ffffffff813aa6ed)
Location: include/linux/percpu-rwsem.h:36
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
In kernel/cpu.c (ffffffff810aa8b5)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
```
```
In kernel/signal.c (ffffffff810bc655)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In kernel/cgroup/cgroup.c (ffffffff81177dc3)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
```
```
In kernel/cgroup/cpuset.c (ffffffff81182a25)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_read_lock
```
```
In kernel/events/uprobes.c (ffffffff81248245)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
```
```
In mm/memory_hotplug.c (ffffffff812e0805)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In fs/super.c (ffffffff813166e2)
Location: include/linux/percpu-rwsem.h:47
Inline: True
```
```
In fs/exec.c (ffffffff8131df77)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/locks.c (ffffffff8139e02a)
Location: include/linux/percpu-rwsem.h:47
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
In fs/ext4/inode.c (ffffffff813f6970)
Location: include/linux/percpu-rwsem.h:47
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
In kernel/cpu.c (ffffffff810a6145)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
```
```
In kernel/signal.c (ffffffff810b7945)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In kernel/cgroup/cgroup.c (ffffffff81174ae3)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
```
```
In kernel/cgroup/cpuset.c (ffffffff8117f965)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_read_lock
```
```
In kernel/events/uprobes.c (ffffffff81252955)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
```
```
In mm/filemap.c (ffffffff8125abc0)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In mm/memory_hotplug.c (ffffffff812eb495)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In fs/open.c (ffffffff81319ff2)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff81320af4)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
```
```
In fs/exec.c (ffffffff81329487)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/namespace.c (ffffffff813490d3)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/namespace.c:mnt_want_write
```
```
In fs/splice.c (ffffffff8135ed63)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff813667c0)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/aio.c (ffffffff81383238)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/aio.c:aio_write
```
```
In fs/io_uring.c (ffffffff81397e72)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/io_uring.c:io_write
```
```
In fs/locks.c (ffffffff813af9ba)
Location: include/linux/percpu-rwsem.h:47
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
In fs/coredump.c (ffffffff813b9483)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/file.c (ffffffff813fc12b)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff8141293c)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/mmp.c (ffffffff81421168)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/fuse/dax.c (ffffffff8149c5dc)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
```
```
In drivers/block/loop.c (ffffffff817fceac)
Location: include/linux/percpu-rwsem.h:47
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
In kernel/cpu.c (ffffffff810a6f95)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
```
```
In kernel/signal.c (ffffffff810b8ea5)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In kernel/cgroup/cgroup.c (ffffffff811756a3)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
```
```
In kernel/cgroup/cpuset.c (ffffffff81180445)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_read_lock
```
```
In kernel/events/uprobes.c (ffffffff812569b5)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
```
```
In mm/filemap.c (ffffffff8125f620)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In mm/memory_hotplug.c (ffffffff812c61a5)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In fs/open.c (ffffffff813200d2)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff81326bd5)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
```
```
In fs/exec.c (ffffffff8132f297)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/namespace.c (ffffffff8134fad3)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/namespace.c:mnt_want_write
```
```
In fs/splice.c (ffffffff813656ad)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff8136d070)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/aio.c (ffffffff8138a2c0)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/aio.c:aio_write
```
```
In fs/io_uring.c (ffffffff8139d8ce)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/io_uring.c:io_write
```
```
In fs/locks.c (ffffffff813b6c4a)
Location: include/linux/percpu-rwsem.h:47
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
In fs/coredump.c (ffffffff813c05f4)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/file.c (ffffffff8140256d)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff81418d9c)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/mmp.c (ffffffff81427918)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/fuse/dax.c (ffffffff814a260c)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
```
```
In drivers/block/loop.c (ffffffff817e193c)
Location: include/linux/percpu-rwsem.h:47
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
In kernel/cpu.c (ffffffff810b8935)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
```
```
In kernel/signal.c (ffffffff810cb435)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In kernel/cgroup/cgroup.c (ffffffff8119cc33)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
```
```
In kernel/cgroup/cpuset.c (ffffffff811a8205)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_read_lock
```
```
In kernel/events/uprobes.c (ffffffff81292755)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
```
```
In mm/filemap.c (ffffffff8129bd90)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In mm/memory_hotplug.c (ffffffff8130ac05)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In fs/open.c (ffffffff8136d682)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff81374195)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
```
```
In fs/exec.c (ffffffff8137ca77)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/namespace.c (ffffffff8139de33)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/namespace.c:mnt_want_write
```
```
In fs/splice.c (ffffffff813b3f9d)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff813bbd50)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/aio.c (ffffffff813d75d0)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/aio.c:aio_write
```
```
In fs/io_uring.c (ffffffff813ec0ef)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/io_uring.c:io_write
```
```
In fs/locks.c (ffffffff8140694a)
Location: include/linux/percpu-rwsem.h:47
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
In fs/coredump.c (ffffffff8141041c)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/file.c (ffffffff81454c34)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff8146bfcc)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/mmp.c (ffffffff8147b5bb)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/fuse/dax.c (ffffffff814fa6b7)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
```
```
In drivers/block/loop.c (ffffffff8186d0dc)
Location: include/linux/percpu-rwsem.h:47
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
In kernel/cpu.c (ffffffff810cf1f5)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
```
```
In kernel/signal.c (ffffffff810e4a85)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In kernel/cgroup/cgroup.c (ffffffff811ccf23)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
```
```
In kernel/cgroup/cpuset.c (ffffffff811d92e5)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_read_lock
```
```
In kernel/events/uprobes.c (ffffffff812e80e5)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
```
```
In mm/filemap.c (ffffffff812f1b21)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In mm/memory_hotplug.c (ffffffff81373aa5)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In fs/open.c (ffffffff813ec249)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff813f30d4)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
```
```
In fs/exec.c (ffffffff813fbda9)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/namespace.c (ffffffff81420e33)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/namespace.c:mnt_want_write
```
```
In fs/splice.c (ffffffff814392e1)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff81442612)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/aio.c (ffffffff81461235)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/aio.c:aio_write
```
```
In fs/locks.c (ffffffff8147b46c)
Location: include/linux/percpu-rwsem.h:47
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
In fs/coredump.c (ffffffff81485ec4)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/file.c (ffffffff814d2406)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff814ebf80)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/mmp.c (ffffffff814fda4b)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/fuse/dax.c (ffffffff8158abd9)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
```
```
In io_uring/io_uring.c (ffffffff816d7668)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_write
```
```
In drivers/block/loop.c (ffffffff819b6d69)
Location: include/linux/percpu-rwsem.h:47
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
In kernel/cpu.c (ffffffff810ed665)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
```
```
In kernel/signal.c (ffffffff811050d5)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In kernel/cgroup/cgroup.c (ffffffff812104e3)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
```
```
In kernel/cgroup/cpuset.c (ffffffff8121e565)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_read_lock
```
```
In kernel/events/hw_breakpoint.c (ffffffff8134ce83)
Location: include/linux/percpu-rwsem.h:47
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff81351e25)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
```
```
In mm/filemap.c (ffffffff8135cbdb)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In mm/memory_hotplug.c (ffffffff813f11d5)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In fs/open.c (ffffffff81474719)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff8147bdc2)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
```
```
In fs/exec.c (ffffffff81484e59)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/namespace.c (ffffffff814ad453)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/namespace.c:mnt_want_write
```
```
In fs/splice.c (ffffffff814c75d1)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff814d1302)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/aio.c (ffffffff814f11c5)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/aio.c:aio_write
```
```
In fs/locks.c (ffffffff8150dffc)
Location: include/linux/percpu-rwsem.h:47
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
In fs/coredump.c (ffffffff81519753)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/file.c (ffffffff8156af53)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff81585ced)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/mmp.c (ffffffff8159823b)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/fuse/dax.c (ffffffff81631336)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
```
```
In io_uring/rw.c (ffffffff817a4ac3)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - io_uring/rw.c:io_write
```
```
In drivers/block/loop.c (ffffffff81b2bfc5)
Location: include/linux/percpu-rwsem.h:47
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
In kernel/cpu.c (ffffffff810f91f5)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
```
```
In kernel/signal.c (ffffffff81111355)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In kernel/cgroup/cgroup.c (ffffffff81225ef3)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
```
```
In kernel/events/hw_breakpoint.c (ffffffff8137dcd3)
Location: include/linux/percpu-rwsem.h:47
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff81383035)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
```
```
In mm/filemap.c (ffffffff8138ec0e)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In mm/memory_hotplug.c (ffffffff81424c15)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In fs/open.c (ffffffff814a90f6)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff814b0989)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
```
```
In fs/exec.c (ffffffff814b9dd9)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/namespace.c (ffffffff814e2233)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/namespace.c:mnt_want_write
```
```
In fs/splice.c (ffffffff814fd4e7)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff815075f8)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/aio.c (ffffffff8152853e)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/aio.c:aio_write
```
```
In fs/locks.c (ffffffff815457cf)
Location: include/linux/percpu-rwsem.h:47
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
In fs/coredump.c (ffffffff8155102b)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/quota.c (ffffffff81560949)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/quota/quota.c:quotactl_block
```
```
In fs/ext4/file.c (ffffffff815a2e09)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff815bc5a4)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/mmp.c (ffffffff815cee02)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/fuse/dax.c (ffffffff8166956c)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
```
```
In io_uring/rw.c (ffffffff817e5ac6)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - io_uring/rw.c:io_write
```
```
In drivers/block/loop.c (ffffffff81b7c297)
Location: include/linux/percpu-rwsem.h:47
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
In kernel/cpu.c (ffffffff81102605)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
```
```
In kernel/signal.c (ffffffff8111ace5)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In kernel/cgroup/cgroup.c (ffffffff8123db83)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
```
```
In kernel/events/hw_breakpoint.c (ffffffff813a6f33)
Location: include/linux/percpu-rwsem.h:47
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff813ac405)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
```
```
In mm/filemap.c (ffffffff813b7ffe)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
```
```
In mm/memory_hotplug.c (ffffffff81451f55)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In fs/open.c (ffffffff814da148)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff814e214a)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_iter_write
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:vfs_write
```
```
In fs/exec.c (ffffffff814ec355)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/namespace.c (ffffffff81512f13)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/namespace.c:mnt_want_write
```
```
In fs/splice.c (ffffffff8153213a)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/splice.c:do_splice
  - fs/splice.c:direct_splice_actor
```
```
In fs/remap_range.c (ffffffff8153c82a)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/aio.c (ffffffff8155d5be)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/aio.c:aio_write
```
```
In fs/locks.c (ffffffff8157ad2f)
Location: include/linux/percpu-rwsem.h:47
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
In fs/backing-file.c (ffffffff81581b31)
Location: include/linux/percpu-rwsem.h:47
Inline: True
```
```
In fs/coredump.c (ffffffff81586ebc)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/quota.c (ffffffff81597039)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/quota/quota.c:quotactl_block
```
```
In fs/ext4/file.c (ffffffff815dbb29)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/inode.c (ffffffff815f5384)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/mmp.c (ffffffff81607692)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/fuse/dax.c (ffffffff816a386c)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
```
```
In io_uring/rw.c (ffffffff81829d80)
Location: include/linux/percpu-rwsem.h:47
Inline: True
Inline callers:
  - io_uring/rw.c:io_write
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
In kernel/fork.c (ffff8000100f3e70)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffff8000100f9050)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
```
```
In kernel/signal.c (ffff80001010fbac)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In kernel/cgroup/cpuset.c (ffff8000101e3de8)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_read_lock
```
```
In kernel/events/uprobes.c (ffff8000102a73e0)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
```
```
In mm/memory_hotplug.c (ffff80001034dd48)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In fs/super.c (ffff800010386314)
Location: include/linux/percpu-rwsem.h:36
Inline: True
```
```
In fs/exec.c (ffff80001038e9c0)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/locks.c (ffff800010419910)
Location: include/linux/percpu-rwsem.h:36
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
In fs/ext4/inode.c (ffff80001047e6a0)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
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
In kernel/fork.c (c0352848)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (c0357270)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
```
```
In kernel/signal.c (c036792c)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In kernel/cgroup/cpuset.c (c0424e74)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_read_lock
```
```
In kernel/events/uprobes.c (c04d6510)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
```
```
In fs/super.c (c056fd60)
Location: include/linux/percpu-rwsem.h:36
Inline: True
```
```
In fs/exec.c (c0574f28)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/locks.c (c05e5cb8)
Location: include/linux/percpu-rwsem.h:36
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
In fs/ext4/inode.c (c06465ec)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
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
In kernel/fork.c (c00000000013a1c4)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (c00000000013fca8)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
```
```
In kernel/signal.c (c0000000001571c0)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In kernel/cgroup/cpuset.c (c0000000002541cc)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_read_lock
```
```
In kernel/events/uprobes.c (c00000000035a88c)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
```
```
In mm/memory_hotplug.c (c00000000042de04)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In fs/super.c (c00000000047db38)
Location: include/linux/percpu-rwsem.h:36
Inline: True
```
```
In fs/exec.c (c0000000004858f8)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/locks.c (c000000000529490)
Location: include/linux/percpu-rwsem.h:36
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
In fs/ext4/inode.c (c0000000005a2ea8)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
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
In kernel/fork.c (ffffffe0000c0668)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffe0000cff1e)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In kernel/cgroup/cpuset.c (ffffffe00015a254)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_read_lock
```
```
In fs/super.c (ffffffe000258efa)
Location: include/linux/percpu-rwsem.h:36
Inline: True
```
```
In fs/exec.c (ffffffe00025e49e)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/locks.c (ffffffe0002c0038)
Location: include/linux/percpu-rwsem.h:36
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
In fs/ext4/inode.c (ffffffe000307ae0)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
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
In kernel/fork.c (ffffffff810990f1)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffff8109d135)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
```
```
In kernel/signal.c (ffffffff810adf13)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In kernel/cgroup/cpuset.c (ffffffff81168c75)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_read_lock
```
```
In kernel/events/uprobes.c (ffffffff812141c5)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
```
```
In mm/memory_hotplug.c (ffffffff812a4a65)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In fs/super.c (ffffffff812d7f32)
Location: include/linux/percpu-rwsem.h:36
Inline: True
```
```
In fs/exec.c (ffffffff812deca1)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/locks.c (ffffffff8134f39e)
Location: include/linux/percpu-rwsem.h:36
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
In fs/ext4/inode.c (ffffffff813a2ccd)
Location: include/linux/percpu-rwsem.h:36
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
In kernel/fork.c (ffffffff81087b41)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffff8108bb65)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
```
```
In kernel/signal.c (ffffffff8109c873)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In kernel/cgroup/cpuset.c (ffffffff8115be85)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_read_lock
```
```
In kernel/events/uprobes.c (ffffffff81206f35)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
```
```
In mm/memory_hotplug.c (ffffffff81296535)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In fs/super.c (ffffffff812c8bb2)
Location: include/linux/percpu-rwsem.h:36
Inline: True
```
```
In fs/exec.c (ffffffff812cedc6)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/locks.c (ffffffff8134007e)
Location: include/linux/percpu-rwsem.h:36
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
In fs/ext4/inode.c (ffffffff8139375d)
Location: include/linux/percpu-rwsem.h:36
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
In kernel/fork.c (ffffffff810990a1)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffff8109d0e5)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
```
```
In kernel/signal.c (ffffffff810ad473)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In kernel/cgroup/cpuset.c (ffffffff81166a45)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_read_lock
```
```
In kernel/events/uprobes.c (ffffffff81211f65)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
```
```
In mm/memory_hotplug.c (ffffffff812a2875)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In fs/super.c (ffffffff812d5d42)
Location: include/linux/percpu-rwsem.h:36
Inline: True
```
```
In fs/exec.c (ffffffff812dcab1)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/locks.c (ffffffff8134ce6e)
Location: include/linux/percpu-rwsem.h:36
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
In fs/ext4/inode.c (ffffffff813a052d)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
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
In kernel/fork.c (ffffffff810a0ccb)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffff810a4f15)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
```
```
In kernel/signal.c (ffffffff810b5631)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In kernel/cgroup/cpuset.c (ffffffff811740c5)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_read_lock
```
```
In kernel/events/uprobes.c (ffffffff81220eb5)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
```
```
In mm/memory_hotplug.c (ffffffff812b23f5)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In fs/super.c (ffffffff812e767e)
Location: include/linux/percpu-rwsem.h:36
Inline: True
```
```
In fs/exec.c (ffffffff812ed84c)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/locks.c (ffffffff813603cc)
Location: include/linux/percpu-rwsem.h:36
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
In fs/ext4/inode.c (ffffffff813b4ced)
Location: include/linux/percpu-rwsem.h:36
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
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
