# Function: <code>css_next_child</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_child(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81113ef9)
Location: kernel/cgroup.c:3765
Inline: True
Inline callers:
  - kernel/cgroup.c:rebind_subsystems
  - kernel/cgroup.c:css_rightmost_descendant
  - kernel/cgroup.c:css_next_descendant_post
  - kernel/cgroup.c:css_next_descendant_post
  - kernel/cgroup.c:css_has_online_children
Direct callers:
  - kernel/cgroup.c:css_rightmost_descendant
  - kernel/cgroup.c:css_next_descendant_post
  - kernel/cgroup.c:css_has_online_children
  - kernel/cgroup_freezer.c:freezer_read
  - kernel/cgroup_freezer.c:freezer_read
  - kernel/cpuset.c:cpuset_css_online
  - kernel/cpuset.c:cpuset_css_online
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
  - mm/memcontrol.c:memcg_activate_kmem
```
**Symbols:**

```
ffffffff81116200-ffffffff81116270: css_next_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_child(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff8111d935)
Location: kernel/cgroup.c:3954
Inline: True
Inline callers:
  - kernel/cgroup.c:css_has_online_children
  - kernel/cgroup.c:css_rightmost_descendant
  - kernel/cgroup.c:rebind_subsystems
Direct callers:
  - kernel/cgroup.c:css_has_online_children
  - kernel/cgroup.c:css_rightmost_descendant
  - kernel/cgroup_freezer.c:freezer_read
  - kernel/cgroup_freezer.c:freezer_read
  - kernel/cpuset.c:cpuset_css_online
  - kernel/cpuset.c:cpuset_css_online
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
```
**Symbols:**

```
ffffffff8111cc10-ffffffff8111cc80: css_next_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_child(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81125c65)
Location: kernel/cgroup.c:3965
Inline: True
Inline callers:
  - kernel/cgroup.c:css_has_online_children
  - kernel/cgroup.c:css_rightmost_descendant
  - kernel/cgroup.c:rebind_subsystems
Direct callers:
  - kernel/cgroup.c:css_has_online_children
  - kernel/cgroup.c:css_rightmost_descendant
  - kernel/cgroup_freezer.c:freezer_read
  - kernel/cgroup_freezer.c:freezer_read
  - kernel/cpuset.c:cpuset_css_online
  - kernel/cpuset.c:cpuset_css_online
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
```
**Symbols:**

```
ffffffff81124f40-ffffffff81124fb0: css_next_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_child(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811279d5)
Location: kernel/cgroup/cgroup.c:3452
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_has_online_children
  - kernel/cgroup/cgroup.c:css_rightmost_descendant
  - kernel/cgroup/cgroup.c:rebind_subsystems
Direct callers:
  - kernel/cgroup/cgroup.c:css_has_online_children
  - kernel/cgroup/cgroup.c:css_rightmost_descendant
  - kernel/cgroup/freezer.c:freezer_read
  - kernel/cgroup/freezer.c:freezer_read
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
```
**Symbols:**

```
ffffffff81125920-ffffffff8112598c: css_next_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_child(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81133de5)
Location: kernel/cgroup/cgroup.c:3821
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_has_online_children
  - kernel/cgroup/cgroup.c:css_rightmost_descendant
  - kernel/cgroup/cgroup.c:rebind_subsystems
Direct callers:
  - kernel/cgroup/cgroup.c:css_has_online_children
  - kernel/cgroup/cgroup.c:css_rightmost_descendant
  - kernel/cgroup/freezer.c:update_if_frozen
  - kernel/cgroup/freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
```
**Symbols:**

```
ffffffff81131bf0-ffffffff81131c5c: css_next_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_child(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811424e5)
Location: kernel/cgroup/cgroup.c:3858
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_has_online_children
  - kernel/cgroup/cgroup.c:css_rightmost_descendant
  - kernel/cgroup/cgroup.c:rebind_subsystems
Direct callers:
  - kernel/cgroup/cgroup.c:css_has_online_children
  - kernel/cgroup/cgroup.c:css_rightmost_descendant
  - kernel/cgroup/freezer.c:update_if_frozen
  - kernel/cgroup/freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
```
**Symbols:**

```
ffffffff81140310-ffffffff8114037f: css_next_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_child(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114df65)
Location: kernel/cgroup/cgroup.c:3922
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_has_online_children
  - kernel/cgroup/cgroup.c:css_rightmost_descendant
  - kernel/cgroup/cgroup.c:rebind_subsystems
Direct callers:
  - kernel/cgroup/cgroup.c:css_has_online_children
  - kernel/cgroup/cgroup.c:css_rightmost_descendant
  - kernel/cgroup/freezer.c:update_if_frozen
  - kernel/cgroup/freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
```
**Symbols:**

```
ffffffff8114bd80-ffffffff8114bdef: css_next_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_child(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81159d0d)
Location: kernel/cgroup/cgroup.c:4178
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_has_online_children
  - kernel/cgroup/cgroup.c:css_rightmost_descendant
  - kernel/cgroup/cgroup.c:rebind_subsystems
Direct callers:
  - kernel/cgroup/cgroup.c:css_has_online_children
  - kernel/cgroup/cgroup.c:css_rightmost_descendant
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
```
**Symbols:**

```
ffffffff81157630-ffffffff8115769a: css_next_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_child(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116599d)
Location: kernel/cgroup/cgroup.c:4180
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_has_online_children
  - kernel/cgroup/cgroup.c:css_rightmost_descendant
  - kernel/cgroup/cgroup.c:rebind_subsystems
Direct callers:
  - kernel/cgroup/cgroup.c:css_has_online_children
  - kernel/cgroup/cgroup.c:css_rightmost_descendant
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
```
**Symbols:**

```
ffffffff811632a0-ffffffff8116330a: css_next_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_child(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81176a99)
Location: kernel/cgroup/cgroup.c:4121
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_has_online_children
  - kernel/cgroup/cgroup.c:css_has_online_children
  - kernel/cgroup/cgroup.c:css_rightmost_descendant
  - kernel/cgroup/cgroup.c:css_rightmost_descendant
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:rebind_subsystems
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
```
**Symbols:**

```
ffffffff81174560-ffffffff811745ca: css_next_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_child(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8117379b)
Location: kernel/cgroup/cgroup.c:4122
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_has_online_children
  - kernel/cgroup/cgroup.c:css_has_online_children
  - kernel/cgroup/cgroup.c:css_rightmost_descendant
  - kernel/cgroup/cgroup.c:css_rightmost_descendant
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:rebind_subsystems
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
**Symbols:**

```
ffffffff81171230-ffffffff81171294: css_next_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_child(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8117436b)
Location: kernel/cgroup/cgroup.c:4135
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_has_online_children
  - kernel/cgroup/cgroup.c:css_has_online_children
  - kernel/cgroup/cgroup.c:css_rightmost_descendant
  - kernel/cgroup/cgroup.c:css_rightmost_descendant
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:rebind_subsystems
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
**Symbols:**

```
ffffffff81171ea0-ffffffff81171f04: css_next_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_child(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8119b3fb)
Location: kernel/cgroup/cgroup.c:4310
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_has_online_children
  - kernel/cgroup/cgroup.c:css_has_online_children
  - kernel/cgroup/cgroup.c:css_rightmost_descendant
  - kernel/cgroup/cgroup.c:css_rightmost_descendant
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:rebind_subsystems
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
**Symbols:**

```
ffffffff81198950-ffffffff811989b4: css_next_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_child(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811cb5f2)
Location: kernel/cgroup/cgroup.c:4321
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_has_online_children
  - kernel/cgroup/cgroup.c:css_has_online_children
  - kernel/cgroup/cgroup.c:css_rightmost_descendant
  - kernel/cgroup/cgroup.c:css_rightmost_descendant
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_restore_control
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:rebind_subsystems
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
**Symbols:**

```
ffffffff811c8a70-ffffffff811c8af0: css_next_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_child(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8120ea62)
Location: kernel/cgroup/cgroup.c:4518
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_has_online_children
  - kernel/cgroup/cgroup.c:css_has_online_children
  - kernel/cgroup/cgroup.c:css_rightmost_descendant
  - kernel/cgroup/cgroup.c:css_rightmost_descendant
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_restore_control
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:rebind_subsystems
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
**Symbols:**

```
ffffffff8120baf0-ffffffff8120bb70: css_next_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_child(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81224467)
Location: kernel/cgroup/cgroup.c:4495
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_has_online_children
  - kernel/cgroup/cgroup.c:css_has_online_children
  - kernel/cgroup/cgroup.c:css_rightmost_descendant
  - kernel/cgroup/cgroup.c:css_rightmost_descendant
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_restore_control
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:rebind_subsystems
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
**Symbols:**

```
ffffffff812210f0-ffffffff81221178: css_next_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_child(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8123c157)
Location: kernel/cgroup/cgroup.c:4525
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_has_online_children
  - kernel/cgroup/cgroup.c:css_has_online_children
  - kernel/cgroup/cgroup.c:css_rightmost_descendant
  - kernel/cgroup/cgroup.c:css_rightmost_descendant
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_apply_cftypes
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_restore_control
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:rebind_subsystems
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:compute_partition_effective_cpumask
  - kernel/cgroup/cpuset.c:compute_partition_effective_cpumask
  - kernel/cgroup/cpuset.c:compute_partition_effective_cpumask
  - kernel/cgroup/cpuset.c:compute_partition_effective_cpumask
  - kernel/cgroup/cpuset.c:update_parent_effective_cpumask
  - kernel/cgroup/cpuset.c:update_parent_effective_cpumask
  - kernel/cgroup/cpuset.c:tasks_nocpu_error
  - kernel/cgroup/cpuset.c:tasks_nocpu_error
  - kernel/cgroup/cpuset.c:tasks_nocpu_error
  - kernel/cgroup/cpuset.c:tasks_nocpu_error
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
**Symbols:**

```
ffffffff81238dd0-ffffffff81238e58: css_next_child (STB_GLOBAL)
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
struct cgroup_subsys_state *css_next_child(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d7420)
Location: kernel/cgroup/cgroup.c:4180
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_has_online_children
  - kernel/cgroup/cgroup.c:css_rightmost_descendant
  - kernel/cgroup/cgroup.c:rebind_subsystems
Direct callers:
  - kernel/cgroup/cgroup.c:css_has_online_children
  - kernel/cgroup/cgroup.c:css_rightmost_descendant
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
```
**Symbols:**

```
ffff8000101d4a28-ffff8000101d4abc: css_next_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_child(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c041a1ac)
Location: kernel/cgroup/cgroup.c:4180
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_has_online_children
  - kernel/cgroup/cgroup.c:css_rightmost_descendant
  - kernel/cgroup/cgroup.c:rebind_subsystems
Direct callers:
  - kernel/cgroup/cgroup.c:css_has_online_children
  - kernel/cgroup/cgroup.c:css_rightmost_descendant
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
```
**Symbols:**

```
c04175cc-c0417654: css_next_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_child(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c000000000243c10)
Location: kernel/cgroup/cgroup.c:4180
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_has_online_children
  - kernel/cgroup/cgroup.c:css_rightmost_descendant
  - kernel/cgroup/cgroup.c:rebind_subsystems
Direct callers:
  - kernel/cgroup/cgroup.c:css_has_online_children
  - kernel/cgroup/cgroup.c:css_rightmost_descendant
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
```
**Symbols:**

```
c000000000240080-c000000000240124: css_next_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_child(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe000150596)
Location: kernel/cgroup/cgroup.c:4180
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_has_online_children
  - kernel/cgroup/cgroup.c:css_rightmost_descendant
  - kernel/cgroup/cgroup.c:rebind_subsystems
Direct callers:
  - kernel/cgroup/cgroup.c:css_has_online_children
  - kernel/cgroup/cgroup.c:css_rightmost_descendant
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
```
**Symbols:**

```
ffffffe00014de64-ffffffe00014dee4: css_next_child (STB_GLOBAL)
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
struct cgroup_subsys_state *css_next_child(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115dfbd)
Location: kernel/cgroup/cgroup.c:4180
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_has_online_children
  - kernel/cgroup/cgroup.c:css_rightmost_descendant
  - kernel/cgroup/cgroup.c:rebind_subsystems
Direct callers:
  - kernel/cgroup/cgroup.c:css_has_online_children
  - kernel/cgroup/cgroup.c:css_rightmost_descendant
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
```
**Symbols:**

```
ffffffff8115b8c0-ffffffff8115b92a: css_next_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_child(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115129d)
Location: kernel/cgroup/cgroup.c:4180
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_has_online_children
  - kernel/cgroup/cgroup.c:css_rightmost_descendant
  - kernel/cgroup/cgroup.c:rebind_subsystems
Direct callers:
  - kernel/cgroup/cgroup.c:css_has_online_children
  - kernel/cgroup/cgroup.c:css_rightmost_descendant
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
```
**Symbols:**

```
ffffffff8114ebb0-ffffffff8114ec1a: css_next_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_child(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115bd8d)
Location: kernel/cgroup/cgroup.c:4180
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_has_online_children
  - kernel/cgroup/cgroup.c:css_rightmost_descendant
  - kernel/cgroup/cgroup.c:rebind_subsystems
Direct callers:
  - kernel/cgroup/cgroup.c:css_has_online_children
  - kernel/cgroup/cgroup.c:css_rightmost_descendant
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
```
**Symbols:**

```
ffffffff81159690-ffffffff811596fa: css_next_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_child(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81168ea4)
Location: kernel/cgroup/cgroup.c:4180
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_has_online_children
  - kernel/cgroup/cgroup.c:css_rightmost_descendant
  - kernel/cgroup/cgroup.c:rebind_subsystems
Direct callers:
  - kernel/cgroup/cgroup.c:css_has_online_children
  - kernel/cgroup/cgroup.c:css_rightmost_descendant
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
```
**Symbols:**

```
ffffffff81166700-ffffffff8116676a: css_next_child (STB_GLOBAL)
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
