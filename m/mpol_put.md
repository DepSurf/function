# Function: <code>mpol_put</code>

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
In kernel/fork.c (ffffffff8107ebf4)
Location: include/linux/mempolicy.h:64
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff81083f6f)
Location: include/linux/mempolicy.h:64
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/sched/debug.c (ffffffff810c8a3b)
Location: include/linux/mempolicy.h:64
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In mm/shmem.c (ffffffff811a6b61)
Location: include/linux/mempolicy.h:64
Inline: True
Inline callers:
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_remount_fs
  - mm/shmem.c:shmem_put_super
```
```
In mm/mmap.c (ffffffff811c4307)
Location: include/linux/mempolicy.h:64
Inline: True
Inline callers:
  - mm/mmap.c:remove_vma
  - mm/mmap.c:vma_adjust
  - mm/mmap.c:copy_vma
```
```
In mm/mempolicy.c (ffffffff811e0e0f)
Location: include/linux/mempolicy.h:64
Inline: True
Inline callers:
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:sp_free
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
```
```
In fs/proc/task_mmu.c (ffffffff81276b52)
Location: include/linux/mempolicy.h:64
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:vma_stop
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
In kernel/fork.c (ffffffff810808b7)
Location: include/linux/mempolicy.h:64
Inline: True
```
```
In kernel/sched/debug.c (ffffffff810cca2e)
Location: include/linux/mempolicy.h:64
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In mm/shmem.c (ffffffff811bd45c)
Location: include/linux/mempolicy.h:64
Inline: True
Inline callers:
  - mm/shmem.c:shmem_put_super
  - mm/shmem.c:shmem_remount_fs
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
```
```
In mm/mmap.c (ffffffff811e2a28)
Location: include/linux/mempolicy.h:64
Inline: True
Inline callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:vma_adjust
  - mm/mmap.c:remove_vma
```
```
In mm/mempolicy.c (ffffffff81201961)
Location: include/linux/mempolicy.h:64
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:sp_free
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
```
```
In fs/proc/task_mmu.c (ffffffff812a3212)
Location: include/linux/mempolicy.h:64
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:vma_stop
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
In kernel/fork.c (ffffffff81085177)
Location: include/linux/mempolicy.h:65
Inline: True
```
```
In kernel/sched/debug.c (ffffffff810d2a4a)
Location: include/linux/mempolicy.h:65
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In mm/shmem.c (ffffffff811cdb23)
Location: include/linux/mempolicy.h:65
Inline: True
Inline callers:
  - mm/shmem.c:shmem_put_super
  - mm/shmem.c:shmem_remount_fs
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
```
```
In mm/mmap.c (ffffffff811f29f8)
Location: include/linux/mempolicy.h:65
Inline: True
Inline callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
```
In mm/mempolicy.c (ffffffff81213451)
Location: include/linux/mempolicy.h:65
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:sp_free
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
```
```
In fs/proc/task_mmu.c (ffffffff812b8bf2)
Location: include/linux/mempolicy.h:65
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:vma_stop
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
In kernel/fork.c (ffffffff810820ba)
Location: include/linux/mempolicy.h:65
Inline: True
```
```
In kernel/sched/debug.c (ffffffff810d1b94)
Location: include/linux/mempolicy.h:65
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In mm/shmem.c (ffffffff811d77ec)
Location: include/linux/mempolicy.h:65
Inline: True
Inline callers:
  - mm/shmem.c:shmem_put_super
  - mm/shmem.c:shmem_remount_fs
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
```
```
In mm/mmap.c (ffffffff811fd989)
Location: include/linux/mempolicy.h:65
Inline: True
Inline callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
```
In mm/mempolicy.c (ffffffff8121e775)
Location: include/linux/mempolicy.h:65
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:sp_free
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
```
```
In fs/proc/task_mmu.c (ffffffff812c5fa2)
Location: include/linux/mempolicy.h:65
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:vma_stop
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
In kernel/fork.c (ffffffff8108891d)
Location: include/linux/mempolicy.h:66
Inline: True
```
```
In kernel/sched/debug.c (ffffffff810d9735)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In mm/shmem.c (ffffffff811ec66c)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - mm/shmem.c:shmem_put_super
  - mm/shmem.c:shmem_remount_fs
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
```
```
In mm/mmap.c (ffffffff81215f2c)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
```
In mm/mempolicy.c (ffffffff81239995)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:sp_free
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
```
```
In fs/proc/task_mmu.c (ffffffff812e9e62)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:vma_stop
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
In kernel/fork.c (ffffffff8108bb9d)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - kernel/fork.c:copy_mm
```
```
In kernel/sched/debug.c (ffffffff810e074a)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In mm/shmem.c (ffffffff8120dc6c)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - mm/shmem.c:shmem_put_super
  - mm/shmem.c:shmem_remount_fs
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
```
```
In mm/mmap.c (ffffffff81236d4a)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
```
In mm/mempolicy.c (ffffffff8125cf53)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:sp_free
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
```
```
In fs/proc/task_mmu.c (ffffffff81316ec2)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:vma_stop
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
In kernel/fork.c (ffffffff810944b3)
Location: include/linux/mempolicy.h:66
Inline: True
```
```
In kernel/sched/debug.c (ffffffff810eaf00)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In mm/shmem.c (ffffffff8122080c)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - mm/shmem.c:shmem_put_super
  - mm/shmem.c:shmem_remount_fs
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
```
```
In mm/mmap.c (ffffffff8124a600)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
```
In mm/mempolicy.c (ffffffff8127182e)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:sp_free
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
```
```
In fs/proc/task_mmu.c (ffffffff8132f99b)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:vma_stop
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
In kernel/fork.c (ffffffff810988fc)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/sched/debug.c (ffffffff810f1d24)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In mm/shmem.c (ffffffff8122fee0)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - mm/shmem.c:shmem_put_super
  - mm/shmem.c:shmem_remount_fs
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
```
```
In mm/mmap.c (ffffffff8125c96f)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
```
In mm/mempolicy.c (ffffffff8128ce46)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:sp_free
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
```
```
In fs/proc/task_mmu.c (ffffffff8135783d)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:vma_stop
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
In kernel/fork.c (ffffffff8109eeb7)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/sched/debug.c (ffffffff810fd9e4)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In mm/shmem.c (ffffffff8123de69)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - mm/shmem.c:shmem_free_fc
  - mm/shmem.c:shmem_put_super
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_parse_one
```
```
In mm/mmap.c (ffffffff8126b0cf)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
```
In mm/mempolicy.c (ffffffff8129ca76)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:sp_free
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
```
```
In fs/proc/task_mmu.c (ffffffff8136fa6d)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:vma_stop
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
In kernel/fork.c (ffffffff810a64e0)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/sched/debug.c (ffffffff81105b1d)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_show_numa
```
```
In mm/shmem.c (ffffffff8126b249)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - mm/shmem.c:shmem_free_fc
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_parse_one
```
```
In mm/mmap.c (ffffffff8129d2ef)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
```
In mm/mempolicy.c (ffffffff812d0708)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:sp_delete
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:vma_replace_policy
  - mm/mempolicy.c:vma_replace_policy
```
```
In fs/proc/task_mmu.c (ffffffff813b7859)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
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
In kernel/fork.c (ffffffff810a1e2d)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/sched/debug.c (ffffffff8110416d)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_show_numa
```
```
In mm/shmem.c (ffffffff81275be9)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - mm/shmem.c:shmem_free_fc
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_parse_one
```
```
In mm/mmap.c (ffffffff812a86ef)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
```
In mm/mempolicy.c (ffffffff812dc228)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:sp_delete
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:vma_replace_policy
  - mm/mempolicy.c:vma_replace_policy
```
```
In fs/proc/task_mmu.c (ffffffff813c91dd)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
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
In kernel/fork.c (ffffffff810a2c62)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/sched/debug.c (ffffffff81106e8d)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_show_numa
```
```
In mm/shmem.c (ffffffff8127af29)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - mm/shmem.c:shmem_free_fc
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_parse_one
```
```
In mm/mmap.c (ffffffff812ac0df)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
```
In mm/mempolicy.c (ffffffff812e3ac5)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:sp_delete
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:mbind_range
  - mm/mempolicy.c:mbind_range
```
```
In fs/proc/task_mmu.c (ffffffff813d02ad)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
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
In kernel/fork.c (ffffffff810b43ab)
Location: include/linux/mempolicy.h:63
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/sched/debug.c (ffffffff81124a7c)
Location: include/linux/mempolicy.h:63
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_show_numa
```
```
In mm/shmem.c (ffffffff812b8dd9)
Location: include/linux/mempolicy.h:63
Inline: True
Inline callers:
  - mm/shmem.c:shmem_free_fc
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_parse_one
```
```
In mm/mmap.c (ffffffff812ed7fc)
Location: include/linux/mempolicy.h:63
Inline: True
Inline callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
```
In mm/mempolicy.c (ffffffff8132ada5)
Location: include/linux/mempolicy.h:63
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:sp_delete
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:mbind_range
  - mm/mempolicy.c:mbind_range
```
```
In fs/proc/task_mmu.c (ffffffff814218cd)
Location: include/linux/mempolicy.h:63
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
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
In kernel/fork.c (ffffffff810ca719)
Location: include/linux/mempolicy.h:63
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In mm/shmem.c (ffffffff81314b87)
Location: include/linux/mempolicy.h:63
Inline: True
Inline callers:
  - mm/shmem.c:shmem_free_fc
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_parse_one
```
```
In mm/mmap.c (ffffffff81350b9e)
Location: include/linux/mempolicy.h:63
Inline: True
Inline callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
```
In mm/mempolicy.c (ffffffff8139a784)
Location: include/linux/mempolicy.h:63
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:sp_delete
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:mbind_range
  - mm/mempolicy.c:mbind_range
```
```
In fs/proc/task_mmu.c (ffffffff81498725)
Location: include/linux/mempolicy.h:63
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
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
In kernel/fork.c (ffffffff810e7d82)
Location: include/linux/mempolicy.h:63
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In mm/shmem.c (ffffffff81388a67)
Location: include/linux/mempolicy.h:63
Inline: True
Inline callers:
  - mm/shmem.c:shmem_free_fc
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_parse_one
```
```
In mm/mmap.c (ffffffff813ca5ae)
Location: include/linux/mempolicy.h:63
Inline: True
Inline callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_expand
  - mm/mmap.c:remove_vma
```
```
In mm/mempolicy.c (ffffffff8141a77a)
Location: include/linux/mempolicy.h:63
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:sp_delete
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:mbind_range
  - mm/mempolicy.c:mbind_range
```
```
In fs/proc/task_mmu.c (ffffffff8152cae9)
Location: include/linux/mempolicy.h:63
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
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
In kernel/fork.c (ffffffff810f39ba)
Location: include/linux/mempolicy.h:63
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In mm/shmem.c (ffffffff813bac97)
Location: include/linux/mempolicy.h:63
Inline: True
Inline callers:
  - mm/shmem.c:shmem_free_fc
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_parse_one
```
```
In mm/mmap.c (ffffffff813feb84)
Location: include/linux/mempolicy.h:63
Inline: True
Inline callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:vma_complete
  - mm/mmap.c:remove_vma
```
```
In mm/mempolicy.c (ffffffff8144dcf0)
Location: include/linux/mempolicy.h:63
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:sp_delete
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:vma_replace_policy
  - mm/mempolicy.c:vma_replace_policy
```
```
In fs/proc/task_mmu.c (ffffffff815658fb)
Location: include/linux/mempolicy.h:63
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
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
In kernel/fork.c (ffffffff810fcd8b)
Location: include/linux/mempolicy.h:65
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In mm/shmem.c (ffffffff813e5477)
Location: include/linux/mempolicy.h:65
Inline: True
Inline callers:
  - mm/shmem.c:shmem_free_fc
  - mm/shmem.c:shmem_put_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_parse_one
```
```
In mm/mmap.c (ffffffff8142aff2)
Location: include/linux/mempolicy.h:65
Inline: True
Inline callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:vma_complete
  - mm/mmap.c:remove_vma
```
```
In mm/mempolicy.c (ffffffff81487bb6)
Location: include/linux/mempolicy.h:65
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:mbind_range
  - mm/mempolicy.c:mbind_range
```
```
In fs/proc/task_mmu.c (ffffffff8159cacd)
Location: include/linux/mempolicy.h:65
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
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
In kernel/fork.c (ffff8000100f43a4)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/sched/debug.c (ffff800010163200)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In mm/shmem.c (ffff8000102cf994)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - mm/shmem.c:shmem_free_fc
  - mm/shmem.c:shmem_put_super
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_parse_one
```
```
In mm/mmap.c (ffff8000103027c0)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
```
In mm/mempolicy.c (ffff80001033ba68)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:sp_free
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
```
```
In fs/proc/task_mmu.c (ffff800010439f18)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:vma_stop
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
In kernel/fork.c (0)
Location: include/linux/mempolicy.h:217
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/mempolicy.h:217
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/mempolicy.h:217
Inline: True
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
In kernel/fork.c (c0000000001397a8)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/sched/debug.c (c0000000001b9a28)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In mm/shmem.c (c00000000038d700)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - mm/shmem.c:shmem_free_fc
  - mm/shmem.c:shmem_put_super
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_parse_one
```
```
In mm/mmap.c (c0000000003cee04)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
```
In mm/mempolicy.c (c0000000004168c4)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:sp_free
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
```
```
In fs/proc/task_mmu.c (c00000000054be9c)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:vma_stop
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
In kernel/fork.c (0)
Location: include/linux/mempolicy.h:217
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/mempolicy.h:217
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/mempolicy.h:217
Inline: True
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
In kernel/fork.c (ffffffff810987d7)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/sched/debug.c (ffffffff810f6d04)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In mm/shmem.c (ffffffff812364b9)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - mm/shmem.c:shmem_free_fc
  - mm/shmem.c:shmem_put_super
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_parse_one
```
```
In mm/mmap.c (ffffffff8126371f)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
```
In mm/mempolicy.c (ffffffff81295056)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:sp_free
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
```
```
In fs/proc/task_mmu.c (ffffffff8136804d)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:vma_stop
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
In kernel/fork.c (ffffffff81087241)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/sched/debug.c (ffffffff810e6ed4)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In mm/shmem.c (ffffffff81229519)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - mm/shmem.c:shmem_free_fc
  - mm/shmem.c:shmem_put_super
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_parse_one
```
```
In mm/mmap.c (ffffffff81255b3f)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
```
In mm/mempolicy.c (ffffffff81286c66)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:sp_free
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
```
```
In fs/proc/task_mmu.c (ffffffff81358efd)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:vma_stop
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
In kernel/fork.c (ffffffff81098787)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/sched/debug.c (ffffffff810f3f14)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In mm/shmem.c (ffffffff81234259)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - mm/shmem.c:shmem_free_fc
  - mm/shmem.c:shmem_put_super
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_parse_one
```
```
In mm/mmap.c (ffffffff812614bf)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
```
In mm/mempolicy.c (ffffffff81292e66)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:sp_free
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
```
```
In fs/proc/task_mmu.c (ffffffff81365b1d)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:vma_stop
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
In kernel/fork.c (ffffffff810a03ae)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/sched/debug.c (ffffffff810fef07)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In mm/shmem.c (ffffffff81243979)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - mm/shmem.c:shmem_free_fc
  - mm/shmem.c:shmem_put_super
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_parse_one
```
```
In mm/mmap.c (ffffffff81270e8f)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
```
In mm/mempolicy.c (ffffffff812a2c5d)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:sp_free
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
```
```
In fs/proc/task_mmu.c (ffffffff813791ad)
Location: include/linux/mempolicy.h:66
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:vma_stop
```
</details>
</li>
</ul>

## Differences
