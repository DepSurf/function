# Function: <code>__percpu_up_read</code>

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
void __percpu_up_read(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810d5680)
Location: kernel/locking/percpu-rwsem.c:95
Inline: True
Direct callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
  - fs/super.c:__sb_end_write
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
ffffffff810d5680-ffffffff810d56aa: __percpu_up_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __percpu_up_read(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810d4610)
Location: kernel/locking/percpu-rwsem.c:94
Inline: True
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - fs/super.c:__sb_end_write
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
ffffffff810d4610-ffffffff810d462e: __percpu_up_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __percpu_up_read(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810dc570)
Location: kernel/locking/percpu-rwsem.c:94
Inline: True
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - fs/super.c:__sb_end_write
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
ffffffff810dc570-ffffffff810dc591: __percpu_up_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __percpu_up_read(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810e4bc0)
Location: kernel/locking/percpu-rwsem.c:94
Inline: True
Direct callers:
  - kernel/cpu.c:cpus_read_unlock
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
  - mm/memory_hotplug.c:put_online_mems
  - fs/super.c:__sb_end_write
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
ffffffff810e4bc0-ffffffff810e4be1: __percpu_up_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __percpu_up_read(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810f01a0)
Location: kernel/locking/percpu-rwsem.c:94
Inline: True
Direct callers:
  - kernel/cpu.c:cpus_read_unlock
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
  - mm/memory_hotplug.c:put_online_mems
  - fs/super.c:__sb_end_write
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
ffffffff810f01a0-ffffffff810f01c1: __percpu_up_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __percpu_up_read(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810f8810)
Location: kernel/locking/percpu-rwsem.c:97
Inline: True
Direct callers:
  - kernel/cpu.c:cpus_read_unlock
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
  - mm/memory_hotplug.c:put_online_mems
  - fs/super.c:__sb_end_write
  - fs/exec.c:de_thread
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
ffffffff810f8810-ffffffff810f8831: __percpu_up_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __percpu_up_read(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff81104650)
Location: kernel/locking/percpu-rwsem.c:97
Inline: True
Direct callers:
  - kernel/cpu.c:cpus_read_unlock
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/cgroup/cpuset.c:cpuset_read_unlock
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
  - mm/memory_hotplug.c:put_online_mems
  - fs/super.c:__sb_end_write
  - fs/exec.c:de_thread
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
ffffffff81104650-ffffffff81104671: __percpu_up_read (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __percpu_up_read(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffff80001016a430)
Location: kernel/locking/percpu-rwsem.c:97
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/cgroup/cpuset.c:cpuset_read_unlock
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - fs/super.c:__sb_end_write
  - fs/exec.c:de_thread
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
ffff80001016a430-ffff80001016a474: __percpu_up_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __percpu_up_read(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (c03b6298)
Location: kernel/locking/percpu-rwsem.c:97
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/cgroup/cpuset.c:cpuset_read_unlock
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
  - fs/super.c:__sb_end_write
  - fs/exec.c:de_thread
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
c03b6298-c03b62d0: __percpu_up_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __percpu_up_read(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (c0000000001c1eb0)
Location: kernel/locking/percpu-rwsem.c:97
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/cgroup/cpuset.c:cpuset_read_unlock
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - fs/super.c:__sb_end_write
  - fs/exec.c:de_thread
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
c0000000001c1eb0-c0000000001c1f00: __percpu_up_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __percpu_up_read(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffe00010b112)
Location: kernel/locking/percpu-rwsem.c:97
Inline: False
Direct callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/cgroup/cpuset.c:cpuset_read_unlock
  - fs/super.c:__sb_end_write
  - fs/exec.c:de_thread
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
ffffffe00010b112-ffffffe00010b160: __percpu_up_read (STB_GLOBAL)
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
void __percpu_up_read(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810fd960)
Location: kernel/locking/percpu-rwsem.c:97
Inline: True
Direct callers:
  - kernel/cpu.c:cpus_read_unlock
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/cgroup/cpuset.c:cpuset_read_unlock
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
  - mm/memory_hotplug.c:put_online_mems
  - fs/super.c:__sb_end_write
  - fs/exec.c:de_thread
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
ffffffff810fd960-ffffffff810fd981: __percpu_up_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __percpu_up_read(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810edb60)
Location: kernel/locking/percpu-rwsem.c:97
Inline: True
Direct callers:
  - kernel/cpu.c:cpus_read_unlock
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/cgroup/cpuset.c:cpuset_read_unlock
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
  - mm/memory_hotplug.c:put_online_mems
  - fs/super.c:__sb_end_write
  - fs/exec.c:de_thread
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
ffffffff810edb60-ffffffff810edb81: __percpu_up_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __percpu_up_read(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810fab20)
Location: kernel/locking/percpu-rwsem.c:97
Inline: True
Direct callers:
  - kernel/cpu.c:cpus_read_unlock
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/cgroup/cpuset.c:cpuset_read_unlock
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
  - mm/memory_hotplug.c:put_online_mems
  - fs/super.c:__sb_end_write
  - fs/exec.c:de_thread
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
ffffffff810fab20-ffffffff810fab41: __percpu_up_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __percpu_up_read(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff81105cf0)
Location: kernel/locking/percpu-rwsem.c:97
Inline: True
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/cgroup/cpuset.c:cpuset_read_unlock
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - fs/super.c:__sb_end_write
  - fs/exec.c:de_thread
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
ffffffff81105cf0-ffffffff81105d11: __percpu_up_read (STB_GLOBAL)
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
