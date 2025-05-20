# Function: <code>percpu_up_read_preempt_enable</code>

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
In kernel/fork.c (ffffffff81085d0b)
Location: include/linux/percpu-rwsem.h:85
Inline: True
```
```
In kernel/signal.c (ffffffff810988df)
Location: include/linux/percpu-rwsem.h:85
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In kernel/events/uprobes.c (ffffffff811aa5c5)
Location: include/linux/percpu-rwsem.h:85
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
```
```
In fs/super.c (ffffffff81248338)
Location: include/linux/percpu-rwsem.h:85
Inline: True
Inline callers:
  - fs/super.c:__sb_end_write
```
```
In fs/exec.c (ffffffff8124ce77)
Location: include/linux/percpu-rwsem.h:85
Inline: True
```
```
In fs/locks.c (ffffffff812a414c)
Location: include/linux/percpu-rwsem.h:85
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
In fs/ext4/inode.c (ffffffff812df156)
Location: include/linux/percpu-rwsem.h:85
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
Location: include/linux/percpu-rwsem.h:85
Inline: True
```
```
In kernel/cpu.c (ffffffff810866e5)
Location: include/linux/percpu-rwsem.h:85
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
```
```
In kernel/signal.c (ffffffff81095b7a)
Location: include/linux/percpu-rwsem.h:85
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In kernel/events/uprobes.c (ffffffff811b1b25)
Location: include/linux/percpu-rwsem.h:85
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
```
```
In mm/memory_hotplug.c (ffffffff8122c4db)
Location: include/linux/percpu-rwsem.h:85
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In fs/super.c (ffffffff81253c44)
Location: include/linux/percpu-rwsem.h:85
Inline: True
Inline callers:
  - fs/super.c:__sb_end_write
```
```
In fs/exec.c (ffffffff81258e92)
Location: include/linux/percpu-rwsem.h:85
Inline: True
```
```
In fs/locks.c (ffffffff812b2d6e)
Location: include/linux/percpu-rwsem.h:85
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
In fs/ext4/inode.c (ffffffff8130334e)
Location: include/linux/percpu-rwsem.h:85
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
Location: include/linux/percpu-rwsem.h:86
Inline: True
```
```
In kernel/cpu.c (ffffffff8108d345)
Location: include/linux/percpu-rwsem.h:86
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
```
```
In kernel/signal.c (ffffffff8109c9ca)
Location: include/linux/percpu-rwsem.h:86
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In kernel/events/uprobes.c (ffffffff811c5739)
Location: include/linux/percpu-rwsem.h:86
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
```
```
In mm/memory_hotplug.c (ffffffff81247cbb)
Location: include/linux/percpu-rwsem.h:86
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In fs/super.c (ffffffff81275cc8)
Location: include/linux/percpu-rwsem.h:86
Inline: True
Inline callers:
  - fs/super.c:__sb_end_write
```
```
In fs/exec.c (ffffffff8127b028)
Location: include/linux/percpu-rwsem.h:86
Inline: True
```
```
In fs/locks.c (ffffffff812d6810)
Location: include/linux/percpu-rwsem.h:86
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
In fs/ext4/inode.c (ffffffff81327d3e)
Location: include/linux/percpu-rwsem.h:86
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
In kernel/fork.c (ffffffff8108ad34)
Location: include/linux/percpu-rwsem.h:86
Inline: True
```
```
In kernel/cpu.c (ffffffff8108f4f9)
Location: include/linux/percpu-rwsem.h:86
Inline: True
Inline callers:
  - kernel/cpu.c:cpus_read_unlock
```
```
In kernel/signal.c (ffffffff810a0dca)
Location: include/linux/percpu-rwsem.h:86
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In kernel/events/uprobes.c (ffffffff811e5c79)
Location: include/linux/percpu-rwsem.h:86
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
```
```
In mm/memory_hotplug.c (ffffffff8126baf9)
Location: include/linux/percpu-rwsem.h:86
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_online_mems
```
```
In fs/super.c (ffffffff8129c228)
Location: include/linux/percpu-rwsem.h:86
Inline: True
Inline callers:
  - fs/super.c:__sb_end_write
```
```
In fs/exec.c (ffffffff812a270c)
Location: include/linux/percpu-rwsem.h:86
Inline: True
```
```
In fs/locks.c (ffffffff8130149e)
Location: include/linux/percpu-rwsem.h:86
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
In fs/ext4/inode.c (ffffffff8135023f)
Location: include/linux/percpu-rwsem.h:86
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
In kernel/fork.c (ffffffff81092d34)
Location: include/linux/percpu-rwsem.h:86
Inline: True
```
```
In kernel/cpu.c (ffffffff810977f9)
Location: include/linux/percpu-rwsem.h:86
Inline: True
Inline callers:
  - kernel/cpu.c:cpus_read_unlock
```
```
In kernel/signal.c (ffffffff810a920a)
Location: include/linux/percpu-rwsem.h:86
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In kernel/events/uprobes.c (ffffffff811f67c9)
Location: include/linux/percpu-rwsem.h:86
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
```
```
In mm/memory_hotplug.c (ffffffff812803f9)
Location: include/linux/percpu-rwsem.h:86
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_online_mems
```
```
In fs/super.c (ffffffff812b1368)
Location: include/linux/percpu-rwsem.h:86
Inline: True
Inline callers:
  - fs/super.c:__sb_end_write
```
```
In fs/exec.c (ffffffff812b72fb)
Location: include/linux/percpu-rwsem.h:86
Inline: True
```
```
In fs/locks.c (ffffffff81316f8a)
Location: include/linux/percpu-rwsem.h:86
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
In fs/ext4/inode.c (ffffffff8136859f)
Location: include/linux/percpu-rwsem.h:86
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
