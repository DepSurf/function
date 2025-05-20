# Function: <code>cgroup_parent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81111e0c)
Location: kernel/cgroup.c:344
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_e_css
  - kernel/cgroup.c:cgroup_addrm_files
  - kernel/cgroup.c:cgroup_addrm_files
  - kernel/cgroup.c:init_and_link_css
  - kernel/cgroup.c:create_css
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup.c:cgroup_get_e_css
  - kernel/cgroup.c:cgroup_update_populated
  - kernel/cgroup.c:__cgroup_procs_write
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:cgroup_subtree_control_write
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff8111b235)
Location: kernel/cgroup.c:361
Inline: True
Inline callers:
  - kernel/cgroup.c:init_and_link_css
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:cgroup_transfer_tasks
  - kernel/cgroup.c:cgroup_addrm_files
  - kernel/cgroup.c:cgroup_addrm_files
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup.c:cgroup_propagate_control
  - kernel/cgroup.c:cgroup_controllers_show
  - kernel/cgroup.c:cgroup_attach_task
  - kernel/cgroup.c:find_css_set
  - kernel/cgroup.c:cgroup_update_populated
  - kernel/cgroup.c:cgroup_get_e_css
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81129f65)
Location: kernel/cgroup.c:364
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_bpf_update
  - kernel/cgroup.c:init_and_link_css
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:cgroup_transfer_tasks
  - kernel/cgroup.c:cgroup_addrm_files
  - kernel/cgroup.c:cgroup_addrm_files
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup.c:cgroup_propagate_control
  - kernel/cgroup.c:cgroup_controllers_show
  - kernel/cgroup.c:cgroup_attach_task
  - kernel/cgroup.c:find_css_set
  - kernel/cgroup.c:cgroup_update_populated
  - kernel/cgroup.c:cgroup_get_e_css
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81128be5)
Location: kernel/cgroup/cgroup.c:319
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_bpf_update
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_free_work_fn
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_controllers_show
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
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
In kernel/sched/cputime.c (ffffffff810bc31f)
Location: include/linux/cgroup.h:530
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810c2f00)
Location: include/linux/cgroup.h:530
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810cbe46)
Location: include/linux/cgroup.h:530
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810cf5fd)
Location: include/linux/cgroup.h:530
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810d5216)
Location: include/linux/cgroup.h:530
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/cgroup/cgroup.c (ffffffff81133e50)
Location: include/linux/cgroup.h:530
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_work_fn
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
  - kernel/cgroup/cgroup.c:cgroup_control
```
```
In kernel/cgroup/stat.c (ffffffff811356c0)
Location: include/linux/cgroup.h:530
Inline: True
Inline callers:
  - kernel/cgroup/stat.c:cgroup_stat_show_cputime
  - kernel/cgroup/stat.c:cgroup_stat_flush_locked
  - kernel/cgroup/stat.c:cgroup_stat_flush_locked
  - kernel/cgroup/stat.c:cgroup_stat_flush_locked
  - kernel/cgroup/stat.c:cgroup_cpu_stat_updated
  - kernel/cgroup/stat.c:cgroup_cpu_stat_updated
```
```
In kernel/bpf/cgroup.c (ffffffff811b28c7)
Location: include/linux/cgroup.h:530
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:compute_effective_progs
  - kernel/bpf/cgroup.c:compute_effective_progs
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
In kernel/sched/cputime.c (ffffffff810c39f3)
Location: include/linux/cgroup.h:530
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810c93cd)
Location: include/linux/cgroup.h:530
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810d354e)
Location: include/linux/cgroup.h:530
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810d714f)
Location: include/linux/cgroup.h:530
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810dd1e6)
Location: include/linux/cgroup.h:530
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/cgroup/cgroup.c (ffffffff81142535)
Location: include/linux/cgroup.h:530
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
  - kernel/cgroup/cgroup.c:cgroup_control
```
```
In kernel/cgroup/rstat.c (ffffffff811440f0)
Location: include/linux/cgroup.h:530
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
```
```
In kernel/bpf/cgroup.c (ffffffff811d1f6b)
Location: include/linux/cgroup.h:530
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:compute_effective_progs
  - kernel/bpf/cgroup.c:compute_effective_progs
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
In kernel/sched/cputime.c (ffffffff810cccb3)
Location: include/linux/cgroup.h:532
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810d37bd)
Location: include/linux/cgroup.h:532
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810dc8ed)
Location: include/linux/cgroup.h:532
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810e169b)
Location: include/linux/cgroup.h:532
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810e6e46)
Location: include/linux/cgroup.h:532
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/sched/psi.c (ffffffff810ef719)
Location: include/linux/cgroup.h:532
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/cgroup/cgroup.c (ffffffff8114dfb5)
Location: include/linux/cgroup.h:532
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
  - kernel/cgroup/cgroup.c:cgroup_e_css
  - kernel/cgroup/cgroup.c:cgroup_control
```
```
In kernel/cgroup/rstat.c (ffffffff8114fc00)
Location: include/linux/cgroup.h:532
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
```
```
In kernel/bpf/cgroup.c (ffffffff811e1d1e)
Location: include/linux/cgroup.h:532
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:compute_effective_progs
  - kernel/bpf/cgroup.c:compute_effective_progs
```
```
In net/core/filter.c (ffffffff818d2dad)
Location: include/linux/cgroup.h:532
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
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
In kernel/sched/cputime.c (ffffffff810d5095)
Location: include/linux/cgroup.h:545
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810dacb0)
Location: include/linux/cgroup.h:545
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810e388e)
Location: include/linux/cgroup.h:545
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810e8154)
Location: include/linux/cgroup.h:545
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810edada)
Location: include/linux/cgroup.h:545
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/sched/psi.c (ffffffff810f6ba4)
Location: include/linux/cgroup.h:545
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/cgroup/cgroup.c (ffffffff81159d55)
Location: include/linux/cgroup.h:545
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
  - kernel/cgroup/cgroup.c:cgroup_e_css
  - kernel/cgroup/cgroup.c:cgroup_control
```
```
In kernel/cgroup/rstat.c (ffffffff8115bb00)
Location: include/linux/cgroup.h:545
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
```
```
In kernel/cgroup/freezer.c (ffffffff8115dd9f)
Location: include/linux/cgroup.h:545
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
```
In kernel/bpf/cgroup.c (ffffffff811f8e7d)
Location: include/linux/cgroup.h:545
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:compute_effective_progs
  - kernel/bpf/cgroup.c:compute_effective_progs
```
```
In net/core/filter.c (ffffffff8191fea2)
Location: include/linux/cgroup.h:545
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
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
In kernel/sched/cputime.c (ffffffff810df654)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810e4bd0)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810ef2c4)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810f3523)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810f96b9)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/sched/psi.c (ffffffff81102934)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/cgroup/cgroup.c (ffffffff811659e5)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
  - kernel/cgroup/cgroup.c:cgroup_e_css
  - kernel/cgroup/cgroup.c:cgroup_control
```
```
In kernel/cgroup/rstat.c (ffffffff81167720)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
```
```
In kernel/cgroup/freezer.c (ffffffff8116998b)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
```
In kernel/bpf/cgroup.c (ffffffff81205f45)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:compute_effective_progs
  - kernel/bpf/cgroup.c:compute_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In net/core/filter.c (ffffffff819520ca)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
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
In kernel/sched/cputime.c (ffffffff810e79a4)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810ee1e0)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810f8cbd)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810fcc0e)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff811037c9)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/sched/psi.c (ffffffff8110d954)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/cgroup/cgroup.c (ffffffff81176b25)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_enable_threaded
  - kernel/cgroup/cgroup.c:cgroup_enable_threaded
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:link_css_set
  - kernel/cgroup/cgroup.c:find_existing_css_set
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
  - kernel/cgroup/cgroup.c:cgroup_e_css
```
```
In kernel/cgroup/rstat.c (ffffffff81178f80)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/rstat.c:cgroup_base_stat_flush
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
```
```
In kernel/cgroup/freezer.c (ffffffff8117b4a5)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
```
```
In kernel/bpf/helpers.c (ffffffff812148a4)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_current_ancestor_cgroup_id
```
```
In kernel/bpf/cgroup.c (ffffffff8122cd6e)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:replace_effective_prog
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:compute_effective_progs
  - kernel/bpf/cgroup.c:compute_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In net/core/filter.c (ffffffff81a2c17a)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
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
In kernel/sched/cputime.c (ffffffff810e5694)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810ebfee)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810f6ed0)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810fb11e)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff81101ee9)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/sched/psi.c (ffffffff8110ac44)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/cgroup/cgroup.c (ffffffff81173825)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_enable_threaded
  - kernel/cgroup/cgroup.c:cgroup_enable_threaded
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:link_css_set
  - kernel/cgroup/cgroup.c:find_existing_css_set
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
  - kernel/cgroup/cgroup.c:cgroup_e_css
```
```
In kernel/cgroup/rstat.c (ffffffff81175c90)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/rstat.c:cgroup_base_stat_flush
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
```
```
In kernel/cgroup/freezer.c (ffffffff81178345)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
```
```
In kernel/bpf/helpers.c (ffffffff81216384)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_current_ancestor_cgroup_id
```
```
In kernel/bpf/cgroup.c (ffffffff8123524e)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:replace_effective_prog
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:compute_effective_progs
  - kernel/bpf/cgroup.c:compute_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In net/core/filter.c (ffffffff81a2e8a5)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
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
In kernel/sched/cputime.c (ffffffff810e7657)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810ee98d)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810f9023)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810fd329)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff8110425c)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/sched/psi.c (ffffffff8110c854)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/cgroup/cgroup.c (ffffffff811743f5)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:find_existing_css_set
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
  - kernel/cgroup/cgroup.c:cgroup_e_css
```
```
In kernel/cgroup/rstat.c (ffffffff81176810)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
```
```
In kernel/cgroup/freezer.c (ffffffff81178eb5)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
```
```
In kernel/bpf/helpers.c (ffffffff81219097)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_current_ancestor_cgroup_id
```
```
In kernel/bpf/cgroup.c (ffffffff81238a58)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_replace
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:compute_effective_progs
  - kernel/bpf/cgroup.c:compute_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In block/blk-cgroup.c (ffffffff8158bc72)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_rstat_flush
```
```
In net/core/filter.c (ffffffff81a15eee)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
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
In kernel/sched/cputime.c (ffffffff810fecee)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff81106fd4)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff8111451b)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff811196f9)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff8112135e)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/sched/psi.c (ffffffff8112b62e)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/cgroup/cgroup.c (ffffffff8119b485)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:find_existing_css_set
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
  - kernel/cgroup/cgroup.c:cgroup_e_css
```
```
In kernel/cgroup/rstat.c (ffffffff8119e090)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
```
```
In kernel/cgroup/freezer.c (ffffffff811a07e5)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
```
```
In kernel/bpf/helpers.c (ffffffff8124fc39)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_current_ancestor_cgroup_id
```
```
In kernel/bpf/cgroup.c (ffffffff812730ae)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_replace
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:compute_effective_progs
  - kernel/bpf/cgroup.c:compute_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In block/blk-cgroup.c (ffffffff815f1086)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_rstat_flush
```
```
In net/core/filter.c (ffffffff81acc06d)
Location: include/linux/cgroup.h:553
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
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
In kernel/sched/fair.c (ffffffff81124165)
Location: include/linux/cgroup.h:554
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/build_policy.c (ffffffff8113618f)
Location: include/linux/cgroup.h:554
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:account_system_index_time
  - kernel/sched/build_policy.c:account_guest_time
  - kernel/sched/build_policy.c:account_guest_time
  - kernel/sched/build_policy.c:account_user_time
  - kernel/sched/build_policy.c:update_curr_rt
```
```
In kernel/sched/build_utility.c (ffffffff8114bdaa)
Location: include/linux/cgroup.h:554
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_task_change
  - kernel/sched/build_utility.c:psi_task_change
  - kernel/sched/build_utility.c:put_prev_task_stop
```
```
In kernel/cgroup/cgroup.c (ffffffff811cb695)
Location: include/linux/cgroup.h:554
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_controllers_show
  - kernel/cgroup/cgroup.c:link_css_set
  - kernel/cgroup/cgroup.c:find_existing_css_set
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
  - kernel/cgroup/cgroup.c:cgroup_e_css
  - kernel/cgroup/cgroup.c:cgroup_is_valid_domain
  - kernel/cgroup/cgroup.c:cgroup_is_valid_domain
```
```
In kernel/cgroup/rstat.c (ffffffff811ce430)
Location: include/linux/cgroup.h:554
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
```
```
In kernel/cgroup/freezer.c (ffffffff811d0f45)
Location: include/linux/cgroup.h:554
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
```
```
In kernel/bpf/helpers.c (ffffffff8129706f)
Location: include/linux/cgroup.h:554
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_current_ancestor_cgroup_id
```
```
In kernel/bpf/cgroup.c (ffffffff812c374e)
Location: include/linux/cgroup.h:554
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_replace
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:compute_effective_progs
  - kernel/bpf/cgroup.c:compute_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In block/blk-cgroup.c (ffffffff816a2d95)
Location: include/linux/cgroup.h:554
Inline: True
```
```
In net/core/filter.c (ffffffff81c488be)
Location: include/linux/cgroup.h:554
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
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
In kernel/sched/fair.c (ffffffff8114c106)
Location: include/linux/cgroup.h:496
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/build_policy.c (ffffffff8116076f)
Location: include/linux/cgroup.h:496
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:__account_forceidle_time
  - kernel/sched/build_policy.c:account_system_index_time
  - kernel/sched/build_policy.c:account_guest_time
  - kernel/sched/build_policy.c:account_guest_time
  - kernel/sched/build_policy.c:account_user_time
  - kernel/sched/build_policy.c:update_curr_rt
```
```
In kernel/sched/build_utility.c (ffffffff8117ad80)
Location: include/linux/cgroup.h:496
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_cgroup_alloc
  - kernel/sched/build_utility.c:put_prev_task_stop
```
```
In kernel/cgroup/cgroup.c (ffffffff8120eb15)
Location: include/linux/cgroup.h:496
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_controllers_show
  - kernel/cgroup/cgroup.c:link_css_set
  - kernel/cgroup/cgroup.c:find_existing_css_set
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
  - kernel/cgroup/cgroup.c:cgroup_e_css
  - kernel/cgroup/cgroup.c:cgroup_is_valid_domain
  - kernel/cgroup/cgroup.c:cgroup_is_valid_domain
```
```
In kernel/cgroup/rstat.c (ffffffff81211c2a)
Location: include/linux/cgroup.h:496
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
```
```
In kernel/cgroup/freezer.c (ffffffff81214ac5)
Location: include/linux/cgroup.h:496
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
```
```
In kernel/bpf/cgroup.c (ffffffff81327e42)
Location: include/linux/cgroup.h:496
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_replace
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:compute_effective_progs
  - kernel/bpf/cgroup.c:compute_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In block/blk-cgroup.c (ffffffff81763b23)
Location: include/linux/cgroup.h:496
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_bio_start
  - block/blk-cgroup.c:blkcg_rstat_flush
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
In kernel/sched/fair.c (ffffffff8115a396)
Location: include/linux/cgroup.h:495
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/build_policy.c (ffffffff81170e95)
Location: include/linux/cgroup.h:495
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:__account_forceidle_time
  - kernel/sched/build_policy.c:account_system_index_time
  - kernel/sched/build_policy.c:account_guest_time
  - kernel/sched/build_policy.c:account_guest_time
  - kernel/sched/build_policy.c:account_user_time
  - kernel/sched/build_policy.c:update_curr_rt
```
```
In kernel/sched/build_utility.c (ffffffff8118b8f0)
Location: include/linux/cgroup.h:495
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_cgroup_alloc
  - kernel/sched/build_utility.c:put_prev_task_stop
```
```
In kernel/cgroup/cgroup.c (ffffffff81224525)
Location: include/linux/cgroup.h:495
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_controllers_show
  - kernel/cgroup/cgroup.c:link_css_set
  - kernel/cgroup/cgroup.c:find_existing_css_set
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
  - kernel/cgroup/cgroup.c:cgroup_e_css
  - kernel/cgroup/cgroup.c:cgroup_is_valid_domain
  - kernel/cgroup/cgroup.c:cgroup_is_valid_domain
```
```
In kernel/cgroup/rstat.c (ffffffff8122758a)
Location: include/linux/cgroup.h:495
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
```
```
In kernel/cgroup/freezer.c (ffffffff8122a3e5)
Location: include/linux/cgroup.h:495
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
```
```
In kernel/bpf/cgroup.c (ffffffff81358180)
Location: include/linux/cgroup.h:495
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_replace
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:compute_effective_progs
  - kernel/bpf/cgroup.c:compute_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In block/blk-cgroup.c (ffffffff817a2bc8)
Location: include/linux/cgroup.h:495
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_bio_start
  - block/blk-cgroup.c:blkcg_rstat_flush
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
In kernel/sched/fair.c (ffffffff81164b78)
Location: include/linux/cgroup.h:493
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/fair.c:update_curr_common
```
```
In kernel/sched/build_policy.c (ffffffff8118206c)
Location: include/linux/cgroup.h:493
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:__account_forceidle_time
  - kernel/sched/build_policy.c:account_system_index_time
  - kernel/sched/build_policy.c:account_guest_time
  - kernel/sched/build_policy.c:account_guest_time
  - kernel/sched/build_policy.c:account_user_time
```
```
In kernel/sched/build_utility.c (ffffffff8119a24f)
Location: include/linux/cgroup.h:493
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_cgroup_alloc
```
```
In kernel/cgroup/cgroup.c (ffffffff8123c215)
Location: include/linux/cgroup.h:493
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_controllers_show
  - kernel/cgroup/cgroup.c:link_css_set
  - kernel/cgroup/cgroup.c:find_existing_css_set
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
  - kernel/cgroup/cgroup.c:cgroup_e_css
  - kernel/cgroup/cgroup.c:cgroup_is_valid_domain
  - kernel/cgroup/cgroup.c:cgroup_is_valid_domain
```
```
In kernel/cgroup/rstat.c (ffffffff8123f39a)
Location: include/linux/cgroup.h:493
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
```
```
In kernel/cgroup/freezer.c (ffffffff812423a5)
Location: include/linux/cgroup.h:493
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
```
```
In kernel/bpf/cgroup.c (ffffffff81380d00)
Location: include/linux/cgroup.h:493
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_replace
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:compute_effective_progs
  - kernel/bpf/cgroup.c:compute_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In block/blk-cgroup.c (ffffffff817e6708)
Location: include/linux/cgroup.h:493
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_bio_start
  - block/blk-cgroup.c:blkcg_rstat_flush
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
In kernel/sched/cputime.c (ffff80001013ef88)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffff800010144910)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffff8000101504e8)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffff800010155730)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffff80001015e068)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/sched/psi.c (ffff8000101676a8)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/cgroup/cgroup.c (ffff8000101d7490)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
  - kernel/cgroup/cgroup.c:cgroup_e_css
  - kernel/cgroup/cgroup.c:cgroup_control
```
```
In kernel/cgroup/rstat.c (ffff8000101d9de8)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
```
```
In kernel/cgroup/freezer.c (ffff8000101dcee8)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
```
In kernel/bpf/cgroup.c (ffff80001028f23c)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:compute_effective_progs
  - kernel/bpf/cgroup.c:compute_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In net/core/filter.c (ffff800010bf42b0)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
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
In kernel/sched/cputime.c (c038ef5c)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (c0392230)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (c039e170)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (c03a30a8)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (c03a9f14)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/sched/psi.c (c03b455c)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/cgroup/cgroup.c (c041a20c)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:css_visible
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
  - kernel/cgroup/cgroup.c:cgroup_e_css
  - kernel/cgroup/cgroup.c:cgroup_control
```
```
In kernel/cgroup/rstat.c (c041c758)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
```
```
In kernel/cgroup/freezer.c (c041ef54)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
```
In kernel/bpf/cgroup.c (c04bea74)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:compute_effective_progs
  - kernel/bpf/cgroup.c:compute_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In net/core/filter.c (c0d0ca7c)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
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
In kernel/sched/cputime.c (c00000000018e134)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (c000000000195b54)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (c0000000001a44b4)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (c0000000001a9948)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (c0000000001b2ca8)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/sched/psi.c (c0000000001bf414)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/cgroup/cgroup.c (c000000000243cdc)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:link_css_set
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
  - kernel/cgroup/cgroup.c:cgroup_e_css
  - kernel/cgroup/cgroup.c:cgroup_control
```
```
In kernel/cgroup/rstat.c (c000000000247014)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
```
```
In kernel/cgroup/freezer.c (c00000000024ac50)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
```
In kernel/bpf/cgroup.c (c00000000033bea4)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:compute_effective_progs
  - kernel/bpf/cgroup.c:compute_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In net/core/filter.c (c000000000cd93f4)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
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
In kernel/sched/cputime.c (ffffffe0000ed712)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffe0000f14f4)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffe0000f8c6c)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffe0000fd2ce)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffe000102576)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/sched/psi.c (ffffffe000109c38)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/cgroup/cgroup.c (ffffffe0001505f2)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
  - kernel/cgroup/cgroup.c:cgroup_e_css
  - kernel/cgroup/cgroup.c:cgroup_control
```
```
In kernel/cgroup/rstat.c (ffffffe0001526c2)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
```
```
In kernel/cgroup/freezer.c (ffffffe000154b30)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
```
In kernel/bpf/cgroup.c (ffffffe0001c2318)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:compute_effective_progs
  - kernel/bpf/cgroup.c:compute_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In net/core/filter.c (ffffffe000775760)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
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
In kernel/sched/cputime.c (ffffffff810d9844)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810ded80)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810e8c4d)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810ec923)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810f2ab9)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/sched/psi.c (ffffffff810fbc44)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/cgroup/cgroup.c (ffffffff8115e005)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
  - kernel/cgroup/cgroup.c:cgroup_e_css
  - kernel/cgroup/cgroup.c:cgroup_control
```
```
In kernel/cgroup/rstat.c (ffffffff8115fd40)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
```
```
In kernel/cgroup/freezer.c (ffffffff81161fab)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
```
In kernel/bpf/cgroup.c (ffffffff811fe565)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:compute_effective_progs
  - kernel/bpf/cgroup.c:compute_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In net/core/filter.c (ffffffff818f209a)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
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
In kernel/sched/cputime.c (ffffffff810c8224)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810cdd90)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810d8684)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810dc9c3)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810e2bc9)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/sched/psi.c (ffffffff810ebe64)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/cgroup/cgroup.c (ffffffff811512e5)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
  - kernel/cgroup/cgroup.c:cgroup_e_css
  - kernel/cgroup/cgroup.c:cgroup_control
```
```
In kernel/cgroup/rstat.c (ffffffff81152fc0)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
```
```
In kernel/cgroup/freezer.c (ffffffff8115520b)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
```
In kernel/bpf/cgroup.c (ffffffff811f12b5)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:compute_effective_progs
  - kernel/bpf/cgroup.c:compute_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In net/core/filter.c (ffffffff818abeca)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
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
In kernel/sched/cputime.c (ffffffff810d5b84)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810db100)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810e57f4)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810e9a53)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810efbe9)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/sched/psi.c (ffffffff810f8e04)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/cgroup/cgroup.c (ffffffff8115bdd5)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
  - kernel/cgroup/cgroup.c:cgroup_e_css
  - kernel/cgroup/cgroup.c:cgroup_control
```
```
In kernel/cgroup/rstat.c (ffffffff8115db10)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
```
```
In kernel/cgroup/freezer.c (ffffffff8115fd7b)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
```
In kernel/bpf/cgroup.c (ffffffff811fc335)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:compute_effective_progs
  - kernel/bpf/cgroup.c:compute_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In net/core/filter.c (ffffffff819430ca)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
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
In kernel/sched/cputime.c (ffffffff810e1489)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810e6dc5)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810efb12)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810f4a08)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810fac3e)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/sched/psi.c (ffffffff81103f54)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/cgroup/cgroup.c (ffffffff81168f05)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
  - kernel/cgroup/cgroup.c:cgroup_e_css
  - kernel/cgroup/cgroup.c:cgroup_control
```
```
In kernel/cgroup/rstat.c (ffffffff8116ad70)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
```
```
In kernel/cgroup/freezer.c (ffffffff8116d0ab)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
```
In kernel/bpf/cgroup.c (ffffffff8120afa5)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:compute_effective_progs
  - kernel/bpf/cgroup.c:compute_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In net/core/filter.c (ffffffff819649ba)
Location: include/linux/cgroup.h:547
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
```
</details>
</li>
</ul>

## Differences
