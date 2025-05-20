# Function: <code>percpu_down_read_preempt_disable</code>

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
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81085cd7)
Location: include/linux/percpu-rwsem.h:31
Inline: True
```
```
In kernel/signal.c (ffffffff81098897)
Location: include/linux/percpu-rwsem.h:31
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In kernel/events/uprobes.c (ffffffff811aa589)
Location: include/linux/percpu-rwsem.h:31
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
```
```
In fs/super.c (ffffffff81248c0e)
Location: include/linux/percpu-rwsem.h:31
Inline: True
```
```
In fs/exec.c (ffffffff8124ccbc)
Location: include/linux/percpu-rwsem.h:31
Inline: True
```
```
In fs/locks.c (ffffffff812a40ee)
Location: include/linux/percpu-rwsem.h:31
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
In fs/ext4/inode.c (ffffffff812df0f8)
Location: include/linux/percpu-rwsem.h:31
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
Location: include/linux/percpu-rwsem.h:31
Inline: True
```
```
In kernel/cpu.c (ffffffff810866c1)
Location: include/linux/percpu-rwsem.h:31
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
```
```
In kernel/signal.c (ffffffff81095b32)
Location: include/linux/percpu-rwsem.h:31
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In kernel/events/uprobes.c (ffffffff811b1ae9)
Location: include/linux/percpu-rwsem.h:31
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
```
```
In mm/memory_hotplug.c (ffffffff8122c48f)
Location: include/linux/percpu-rwsem.h:31
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In fs/super.c (ffffffff81254512)
Location: include/linux/percpu-rwsem.h:31
Inline: True
```
```
In fs/exec.c (ffffffff81258cf3)
Location: include/linux/percpu-rwsem.h:31
Inline: True
```
```
In fs/locks.c (ffffffff812b2d00)
Location: include/linux/percpu-rwsem.h:31
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
In fs/ext4/inode.c (ffffffff813032f2)
Location: include/linux/percpu-rwsem.h:31
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
Location: include/linux/percpu-rwsem.h:32
Inline: True
```
```
In kernel/cpu.c (ffffffff8108d321)
Location: include/linux/percpu-rwsem.h:32
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
```
```
In kernel/signal.c (ffffffff8109c982)
Location: include/linux/percpu-rwsem.h:32
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In kernel/events/uprobes.c (ffffffff811c56f9)
Location: include/linux/percpu-rwsem.h:32
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
```
```
In mm/memory_hotplug.c (ffffffff81247c6f)
Location: include/linux/percpu-rwsem.h:32
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In fs/super.c (ffffffff81276622)
Location: include/linux/percpu-rwsem.h:32
Inline: True
```
```
In fs/exec.c (ffffffff8127ae82)
Location: include/linux/percpu-rwsem.h:32
Inline: True
```
```
In fs/locks.c (ffffffff812d67a0)
Location: include/linux/percpu-rwsem.h:32
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
In fs/ext4/inode.c (ffffffff81327ce2)
Location: include/linux/percpu-rwsem.h:32
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
Location: include/linux/percpu-rwsem.h:32
Inline: True
```
```
In kernel/cpu.c (ffffffff81090c85)
Location: include/linux/percpu-rwsem.h:32
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
```
```
In kernel/signal.c (ffffffff810a0d82)
Location: include/linux/percpu-rwsem.h:32
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In kernel/events/uprobes.c (ffffffff811e5c35)
Location: include/linux/percpu-rwsem.h:32
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
```
```
In mm/memory_hotplug.c (ffffffff8126bba5)
Location: include/linux/percpu-rwsem.h:32
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In fs/super.c (ffffffff8129c30d)
Location: include/linux/percpu-rwsem.h:32
Inline: True
```
```
In fs/exec.c (ffffffff812a2566)
Location: include/linux/percpu-rwsem.h:32
Inline: True
```
```
In fs/locks.c (ffffffff81301430)
Location: include/linux/percpu-rwsem.h:32
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
In fs/ext4/inode.c (ffffffff813501ff)
Location: include/linux/percpu-rwsem.h:32
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
Location: include/linux/percpu-rwsem.h:32
Inline: True
```
```
In kernel/cpu.c (ffffffff81098d45)
Location: include/linux/percpu-rwsem.h:32
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
```
```
In kernel/signal.c (ffffffff810a91c2)
Location: include/linux/percpu-rwsem.h:32
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In kernel/events/uprobes.c (ffffffff811f6785)
Location: include/linux/percpu-rwsem.h:32
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
```
```
In mm/memory_hotplug.c (ffffffff812804a5)
Location: include/linux/percpu-rwsem.h:32
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In fs/super.c (ffffffff812b144d)
Location: include/linux/percpu-rwsem.h:32
Inline: True
```
```
In fs/exec.c (ffffffff812b7145)
Location: include/linux/percpu-rwsem.h:32
Inline: True
```
```
In fs/locks.c (ffffffff81316f1c)
Location: include/linux/percpu-rwsem.h:32
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
In fs/ext4/inode.c (ffffffff8136855f)
Location: include/linux/percpu-rwsem.h:32
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
