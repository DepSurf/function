# Function: <code>css_next_descendant_pre</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_descendant_pre(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81116270)
Location: kernel/cgroup.c:3833
Inline: True
Direct callers:
  - kernel/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup_freezer.c:freezer_write
  - kernel/cgroup_freezer.c:freezer_write
  - kernel/cpuset.c:update_domain_attr_tree
  - kernel/cpuset.c:update_domain_attr_tree
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_iter
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
```
**Symbols:**

```
ffffffff81116270-ffffffff811162ce: css_next_descendant_pre (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_descendant_pre(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff8111cc80)
Location: kernel/cgroup.c:4022
Inline: True
Direct callers:
  - kernel/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup.c:cgroup_propagate_control
  - kernel/cgroup_freezer.c:freezer_write
  - kernel/cgroup_freezer.c:freezer_write
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:update_domain_attr_tree
  - kernel/cpuset.c:update_domain_attr_tree
  - mm/memcontrol.c:mem_cgroup_iter
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
```
**Symbols:**

```
ffffffff8111cc80-ffffffff8111ccde: css_next_descendant_pre (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_descendant_pre(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81124fb0)
Location: kernel/cgroup.c:4033
Inline: True
Direct callers:
  - kernel/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup.c:cgroup_propagate_control
  - kernel/cgroup_freezer.c:freezer_write
  - kernel/cgroup_freezer.c:freezer_write
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:update_domain_attr_tree
  - kernel/cpuset.c:update_domain_attr_tree
  - kernel/bpf/cgroup.c:__cgroup_bpf_update
  - kernel/bpf/cgroup.c:__cgroup_bpf_update
  - kernel/bpf/cgroup.c:__cgroup_bpf_update
  - kernel/bpf/cgroup.c:__cgroup_bpf_update
  - mm/memcontrol.c:mem_cgroup_iter
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
```
**Symbols:**

```
ffffffff81124fb0-ffffffff8112500e: css_next_descendant_pre (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_descendant_pre(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81125990)
Location: kernel/cgroup/cgroup.c:3520
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/bpf/cgroup.c:__cgroup_bpf_update
  - kernel/bpf/cgroup.c:__cgroup_bpf_update
  - kernel/bpf/cgroup.c:__cgroup_bpf_update
  - kernel/bpf/cgroup.c:__cgroup_bpf_update
  - mm/memcontrol.c:mem_cgroup_iter
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
```
**Symbols:**

```
ffffffff81125990-ffffffff811259f7: css_next_descendant_pre (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_descendant_pre(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81131c60)
Location: kernel/cgroup/cgroup.c:3889
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - mm/memcontrol.c:mem_cgroup_iter
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
```
**Symbols:**

```
ffffffff81131c60-ffffffff81131cc7: css_next_descendant_pre (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_descendant_pre(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81140585)
Location: kernel/cgroup/cgroup.c:3926
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - mm/memcontrol.c:mem_cgroup_iter
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
```
**Symbols:**

```
ffffffff81140380-ffffffff811403ea: css_next_descendant_pre (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_descendant_pre(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114db5f)
Location: kernel/cgroup/cgroup.c:3990
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - mm/memcontrol.c:mem_cgroup_iter
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
```
**Symbols:**

```
ffffffff8114bdf0-ffffffff8114be5a: css_next_descendant_pre (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_descendant_pre(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81159916)
Location: kernel/cgroup/cgroup.c:4246
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - mm/memcontrol.c:mem_cgroup_iter
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
```
**Symbols:**

```
ffffffff811576a0-ffffffff8115770a: css_next_descendant_pre (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_descendant_pre(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81165589)
Location: kernel/cgroup/cgroup.c:4248
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - mm/memcontrol.c:mem_cgroup_iter
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
```
**Symbols:**

```
ffffffff81163310-ffffffff8116337a: css_next_descendant_pre (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_descendant_pre(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81171d92)
Location: kernel/cgroup/cgroup.c:4190
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_enable_threaded
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/cgroup/cgroup.c:cgroup_enable_threaded
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_root_domains
  - kernel/cgroup/cpuset.c:rebuild_root_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/bpf/cgroup.c:replace_effective_prog
  - kernel/bpf/cgroup.c:replace_effective_prog
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - mm/memcontrol.c:mem_cgroup_iter
  - security/device_cgroup.c:propagate_exception
  - security/device_cgroup.c:propagate_exception
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
```
**Symbols:**

```
ffffffff81170430-ffffffff811704d0: css_next_descendant_pre (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_descendant_pre(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116ea02)
Location: kernel/cgroup/cgroup.c:4191
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_enable_threaded
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/cgroup/cgroup.c:cgroup_enable_threaded
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_root_domains
  - kernel/cgroup/cpuset.c:rebuild_root_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/bpf/cgroup.c:replace_effective_prog
  - kernel/bpf/cgroup.c:replace_effective_prog
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - mm/memcontrol.c:mem_cgroup_iter
  - security/device_cgroup.c:propagate_exception
  - security/device_cgroup.c:propagate_exception
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
```
**Symbols:**

```
ffffffff8116cf40-ffffffff8116cfda: css_next_descendant_pre (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_descendant_pre(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116f831)
Location: kernel/cgroup/cgroup.c:4204
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/bpf/cgroup.c:cgroup_bpf_replace
  - kernel/bpf/cgroup.c:cgroup_bpf_replace
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - mm/memcontrol.c:mem_cgroup_iter
  - security/device_cgroup.c:propagate_exception
  - security/device_cgroup.c:propagate_exception
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
```
**Symbols:**

```
ffffffff8116dba0-ffffffff8116dc3a: css_next_descendant_pre (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_descendant_pre(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81195a55)
Location: kernel/cgroup/cgroup.c:4379
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/bpf/cgroup.c:cgroup_bpf_replace
  - kernel/bpf/cgroup.c:cgroup_bpf_replace
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - mm/memcontrol.c:mem_cgroup_iter
  - security/device_cgroup.c:propagate_exception
  - security/device_cgroup.c:propagate_exception
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
```
**Symbols:**

```
ffffffff81193b80-ffffffff81193c1a: css_next_descendant_pre (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_descendant_pre(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811c3da3)
Location: kernel/cgroup/cgroup.c:4390
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_replace
  - kernel/bpf/cgroup.c:cgroup_bpf_replace
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - mm/list_lru.c:memcg_reparent_list_lrus
  - mm/list_lru.c:memcg_reparent_list_lrus
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - security/device_cgroup.c:propagate_exception
  - security/device_cgroup.c:propagate_exception
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
```
**Symbols:**

```
ffffffff811c4770-ffffffff811c4837: css_next_descendant_pre (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_descendant_pre(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81205de3)
Location: kernel/cgroup/cgroup.c:4587
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_next
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_start
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_replace
  - kernel/bpf/cgroup.c:cgroup_bpf_replace
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - mm/list_lru.c:memcg_reparent_list_lrus
  - mm/list_lru.c:memcg_reparent_list_lrus
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - security/device_cgroup.c:propagate_exception
  - security/device_cgroup.c:propagate_exception
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
```
**Symbols:**

```
ffffffff81206b90-ffffffff81206c57: css_next_descendant_pre (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_descendant_pre(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8121b728)
Location: kernel/cgroup/cgroup.c:4564
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_next
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_start
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_replace
  - kernel/bpf/cgroup.c:cgroup_bpf_replace
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - mm/list_lru.c:memcg_reparent_list_lrus
  - mm/list_lru.c:memcg_reparent_list_lrus
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - security/device_cgroup.c:propagate_exception
  - security/device_cgroup.c:propagate_exception
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
```
**Symbols:**

```
ffffffff8121c750-ffffffff8121c81e: css_next_descendant_pre (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_descendant_pre(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81233558)
Location: kernel/cgroup/cgroup.c:4594
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/bpf/cgroup_iter.c:bpf_iter_css_next
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_next
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_start
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_replace
  - kernel/bpf/cgroup.c:cgroup_bpf_replace
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - mm/list_lru.c:memcg_reparent_list_lrus
  - mm/list_lru.c:memcg_reparent_list_lrus
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - security/device_cgroup.c:propagate_exception
  - security/device_cgroup.c:propagate_exception
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
```
**Symbols:**

```
ffffffff812342e0-ffffffff812343ae: css_next_descendant_pre (STB_GLOBAL)
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
struct cgroup_subsys_state *css_next_descendant_pre(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d7054)
Location: kernel/cgroup/cgroup.c:4248
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - mm/memcontrol.c:mem_cgroup_iter
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
```
**Symbols:**

```
ffff8000101d4ac0-ffff8000101d4b48: css_next_descendant_pre (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_descendant_pre(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c0419cd4)
Location: kernel/cgroup/cgroup.c:4248
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - mm/memcontrol.c:mem_cgroup_iter
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
```
**Symbols:**

```
c0417654-c04176d4: css_next_descendant_pre (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_descendant_pre(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c000000000243588)
Location: kernel/cgroup/cgroup.c:4248
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
```
**Symbols:**

```
c000000000240130-c000000000240224: css_next_descendant_pre (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_descendant_pre(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe00015016e)
Location: kernel/cgroup/cgroup.c:4248
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - mm/memcontrol.c:mem_cgroup_iter
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
```
**Symbols:**

```
ffffffe00014dee4-ffffffe00014df50: css_next_descendant_pre (STB_GLOBAL)
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
struct cgroup_subsys_state *css_next_descendant_pre(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115dba9)
Location: kernel/cgroup/cgroup.c:4248
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - mm/memcontrol.c:mem_cgroup_iter
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
```
**Symbols:**

```
ffffffff8115b930-ffffffff8115b99a: css_next_descendant_pre (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_descendant_pre(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81150e89)
Location: kernel/cgroup/cgroup.c:4248
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - mm/memcontrol.c:mem_cgroup_iter
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
```
**Symbols:**

```
ffffffff8114ec20-ffffffff8114ec8a: css_next_descendant_pre (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_descendant_pre(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115b979)
Location: kernel/cgroup/cgroup.c:4248
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - mm/memcontrol.c:mem_cgroup_iter
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
```
**Symbols:**

```
ffffffff81159700-ffffffff8115976a: css_next_descendant_pre (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_descendant_pre(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81168a39)
Location: kernel/cgroup/cgroup.c:4248
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - mm/memcontrol.c:mem_cgroup_iter
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
```
**Symbols:**

```
ffffffff81166770-ffffffff811667da: css_next_descendant_pre (STB_GLOBAL)
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
No changes between <code>4.8</code> and <code>4.10</code> ✅
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
