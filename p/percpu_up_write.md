# Function: <code>percpu_up_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void percpu_up_write(struct percpu_rw_semaphore *brw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810ca080)
Location: kernel/locking/percpu-rwsem.c:147
Inline: False
Direct callers:
  - kernel/cgroup.c:__cgroup_procs_write
  - kernel/cgroup.c:__cgroup_procs_write
  - kernel/cgroup.c:cgroup_update_dfl_csses
  - kernel/events/uprobes.c:register_for_each_vma
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:thaw_super
  - fs/super.c:thaw_super
  - fs/super.c:thaw_super
```
**Symbols:**

```
ffffffff810ca080-ffffffff810ca0a1: percpu_up_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void percpu_up_write(struct percpu_rw_semaphore *brw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810cea40)
Location: kernel/locking/percpu-rwsem.c:148
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_transfer_tasks
  - kernel/cgroup.c:cgroup_attach_task_all
  - kernel/events/uprobes.c:register_for_each_vma
  - fs/super.c:thaw_super
  - fs/super.c:thaw_super
  - fs/super.c:thaw_super
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
```
**Symbols:**

```
ffffffff810cea40-ffffffff810cea61: percpu_up_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void percpu_up_write(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810d56b0)
Location: kernel/locking/percpu-rwsem.c:167
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_transfer_tasks
  - kernel/cgroup.c:cgroup_attach_task_all
  - kernel/events/uprobes.c:register_for_each_vma
  - fs/super.c:thaw_super
  - fs/super.c:thaw_super
  - fs/super.c:thaw_super
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/locks.c:locks_stop
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
```
**Symbols:**

```
ffffffff810d56b0-ffffffff810d56db: percpu_up_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void percpu_up_write(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810d4630)
Location: kernel/locking/percpu-rwsem.c:166
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - fs/super.c:thaw_super
  - fs/super.c:thaw_super
  - fs/super.c:thaw_super
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/locks.c:locks_stop
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
```
**Symbols:**

```
ffffffff810d4630-ffffffff810d4658: percpu_up_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void percpu_up_write(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810dc5a0)
Location: kernel/locking/percpu-rwsem.c:166
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - fs/super.c:thaw_super
  - fs/super.c:thaw_super
  - fs/super.c:thaw_super
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/locks.c:locks_stop
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
```
**Symbols:**

```
ffffffff810dc5a0-ffffffff810dc5c8: percpu_up_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void percpu_up_write(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810e4bf0)
Location: kernel/locking/percpu-rwsem.c:166
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/locks.c:locks_stop
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
```
**Symbols:**

```
ffffffff810e4bf0-ffffffff810e4c18: percpu_up_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void percpu_up_write(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810f01d0)
Location: kernel/locking/percpu-rwsem.c:166
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory_hotplug.c:__remove_memory
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/locks.c:locks_stop
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
```
**Symbols:**

```
ffffffff810f01d0-ffffffff810f01f8: percpu_up_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void percpu_up_write(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810f8840)
Location: kernel/locking/percpu-rwsem.c:169
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/locks.c:locks_stop
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
```
**Symbols:**

```
ffffffff810f8840-ffffffff810f886a: percpu_up_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void percpu_up_write(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff81104680)
Location: kernel/locking/percpu-rwsem.c:169
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_cancel_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:rebuild_sched_domains
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/locks.c:locks_stop
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
**Symbols:**

```
ffffffff81104680-ffffffff811046aa: percpu_up_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void percpu_up_write(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff8110f170)
Location: kernel/locking/percpu-rwsem.c:242
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_cancel_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/locks.c:locks_stop
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
**Symbols:**

```
ffffffff8110f170-ffffffff8110f1a9: percpu_up_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void percpu_up_write(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff8110c330)
Location: kernel/locking/percpu-rwsem.c:242
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_cancel_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/locks.c:locks_stop
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
**Symbols:**

```
ffffffff8110c330-ffffffff8110c369: percpu_up_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void percpu_up_write(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff8110e170)
Location: kernel/locking/percpu-rwsem.c:242
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_cancel_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/locks.c:locks_stop
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
**Symbols:**

```
ffffffff8110e170-ffffffff8110e1a9: percpu_up_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void percpu_up_write(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff8112d8c0)
Location: kernel/locking/percpu-rwsem.c:242
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_cancel_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/locks.c:locks_stop
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
**Symbols:**

```
ffffffff8112d8c0-ffffffff8112d8f9: percpu_up_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void percpu_up_write(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff8114e8e0)
Location: kernel/locking/percpu-rwsem.c:248
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_cancel_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/locks.c:locks_stop
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
**Symbols:**

```
ffffffff8114e8e0-ffffffff8114e924: percpu_up_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void percpu_up_write(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff8117d990)
Location: kernel/locking/percpu-rwsem.c:254
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_cancel_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/locks.c:locks_stop
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
**Symbols:**

```
ffffffff8117d990-ffffffff8117d9d6: percpu_up_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void percpu_up_write(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff8118e630)
Location: kernel/locking/percpu-rwsem.c:254
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/locks.c:locks_stop
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
**Symbols:**

```
ffffffff8118e630-ffffffff8118e676: percpu_up_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void percpu_up_write(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff8119cfe0)
Location: kernel/locking/percpu-rwsem.c:254
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/locks.c:locks_stop
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
```
**Symbols:**

```
ffffffff8119cfe0-ffffffff8119d026: percpu_up_write (STB_GLOBAL)
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
void percpu_up_write(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffff80001016a2b0)
Location: kernel/locking/percpu-rwsem.c:169
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_cancel_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:rebuild_sched_domains
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/locks.c:locks_stop
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
**Symbols:**

```
ffff80001016a2b0-ffff80001016a2f0: percpu_up_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void percpu_up_write(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (c03b63d8)
Location: kernel/locking/percpu-rwsem.c:169
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_cancel_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:rebuild_sched_domains
  - kernel/events/uprobes.c:register_for_each_vma
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/locks.c:locks_stop
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
**Symbols:**

```
c03b63d8-c03b6410: percpu_up_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void percpu_up_write(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (c0000000001c2060)
Location: kernel/locking/percpu-rwsem.c:169
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_cancel_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:rebuild_sched_domains
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/locks.c:locks_stop
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
**Symbols:**

```
c0000000001c2060-c0000000001c20bc: percpu_up_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void percpu_up_write(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffe00010b226)
Location: kernel/locking/percpu-rwsem.c:169
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_cancel_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:rebuild_sched_domains
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/locks.c:locks_stop
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
**Symbols:**

```
ffffffe00010b226-ffffffe00010b264: percpu_up_write (STB_GLOBAL)
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
void percpu_up_write(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810fd990)
Location: kernel/locking/percpu-rwsem.c:169
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_cancel_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:rebuild_sched_domains
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/locks.c:locks_stop
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
**Symbols:**

```
ffffffff810fd990-ffffffff810fd9ba: percpu_up_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void percpu_up_write(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810edb90)
Location: kernel/locking/percpu-rwsem.c:169
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_cancel_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:rebuild_sched_domains
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/locks.c:locks_stop
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
**Symbols:**

```
ffffffff810edb90-ffffffff810edbba: percpu_up_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void percpu_up_write(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810fab50)
Location: kernel/locking/percpu-rwsem.c:169
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_cancel_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:rebuild_sched_domains
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/locks.c:locks_stop
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
**Symbols:**

```
ffffffff810fab50-ffffffff810fab7a: percpu_up_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void percpu_up_write(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff81105d20)
Location: kernel/locking/percpu-rwsem.c:169
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_cancel_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:rebuild_sched_domains
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/locks.c:locks_stop
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
**Symbols:**

```
ffffffff81105d20-ffffffff81105d4a: percpu_up_write (STB_GLOBAL)
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
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct percpu_rw_semaphore *sem</code>
</li>
<li>
<b>Param removed. </b>
<code>struct percpu_rw_semaphore *brw</code>
</li>
</ul>
</details>
</li>
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
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
