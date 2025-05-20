# Function: <code>cgroup_is_dead</code>

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
In kernel/cgroup.c (0)
Location: kernel/cgroup.c:440
Inline: True
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
In kernel/cgroup.c (ffffffff8111b03a)
Location: kernel/cgroup.c:482
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_get
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
In kernel/cgroup.c (ffffffff8112337a)
Location: kernel/cgroup.c:485
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_get
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
In kernel/cgroup/cgroup.c (ffffffff81122e05)
Location: kernel/cgroup/cgroup-internal.h:120
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_get_live
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: kernel/cgroup/cgroup-internal.h:120
Inline: True
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
In kernel/cgroup/cgroup.c (ffffffff8112ea95)
Location: kernel/cgroup/cgroup-internal.h:121
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_get_live
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: kernel/cgroup/cgroup-internal.h:121
Inline: True
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
In kernel/cgroup/cgroup.c (ffffffff81143184)
Location: kernel/cgroup/cgroup-internal.h:121
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_restore_control
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_live
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81145cf6)
Location: kernel/cgroup/cgroup-internal.h:121
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
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
In kernel/cgroup/cgroup.c (ffffffff8114ecb4)
Location: kernel/cgroup/cgroup-internal.h:149
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_live
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811518b6)
Location: kernel/cgroup/cgroup-internal.h:149
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
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
In kernel/cgroup/cgroup.c (ffffffff8115a81c)
Location: kernel/cgroup/cgroup-internal.h:168
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_live
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115d27a)
Location: kernel/cgroup/cgroup-internal.h:168
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/freezer.c (ffffffff8115e4ba)
Location: kernel/cgroup/cgroup-internal.h:168
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
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
In kernel/cgroup/cgroup.c (ffffffff811664cc)
Location: kernel/cgroup/cgroup-internal.h:168
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_live
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81168e7a)
Location: kernel/cgroup/cgroup-internal.h:168
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/freezer.c (ffffffff8116a0da)
Location: kernel/cgroup/cgroup-internal.h:168
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
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
In kernel/cgroup/cgroup.c (ffffffff81177eb3)
Location: kernel/cgroup/cgroup-internal.h:168
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_enable_threaded
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8117ac2a)
Location: kernel/cgroup/cgroup-internal.h:168
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/freezer.c (ffffffff8117bc2a)
Location: kernel/cgroup/cgroup-internal.h:168
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
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
In kernel/cgroup/cgroup.c (ffffffff81174bd3)
Location: kernel/cgroup/cgroup-internal.h:168
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_enable_threaded
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_live
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81177a2a)
Location: kernel/cgroup/cgroup-internal.h:168
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/freezer.c (ffffffff81178a7a)
Location: kernel/cgroup/cgroup-internal.h:168
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
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
In kernel/cgroup/cgroup.c (ffffffff8117578f)
Location: kernel/cgroup/cgroup-internal.h:168
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_live
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8117858a)
Location: kernel/cgroup/cgroup-internal.h:168
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/freezer.c (ffffffff811795ea)
Location: kernel/cgroup/cgroup-internal.h:168
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
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
In kernel/cgroup/cgroup.c (ffffffff8119cd1f)
Location: kernel/cgroup/cgroup-internal.h:187
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8119feea)
Location: kernel/cgroup/cgroup-internal.h:187
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/freezer.c (ffffffff811a0f0b)
Location: kernel/cgroup/cgroup-internal.h:187
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
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
In kernel/cgroup/cgroup.c (ffffffff811cd029)
Location: kernel/cgroup/cgroup-internal.h:186
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_restore_control
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811d05b6)
Location: kernel/cgroup/cgroup-internal.h:186
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
```
```
In kernel/cgroup/freezer.c (ffffffff811d172a)
Location: kernel/cgroup/cgroup-internal.h:186
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
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
In kernel/cgroup/cgroup.c (ffffffff812105ed)
Location: kernel/cgroup/cgroup-internal.h:184
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_restore_control
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81214066)
Location: kernel/cgroup/cgroup-internal.h:184
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
```
```
In kernel/cgroup/freezer.c (ffffffff8121530a)
Location: kernel/cgroup/cgroup-internal.h:184
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
```
```
In kernel/bpf/cgroup_iter.c (ffffffff81325631)
Location: kernel/cgroup/cgroup-internal.h:184
Inline: True
Inline callers:
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_show
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
In kernel/cgroup/cgroup.c (ffffffff81226000)
Location: kernel/cgroup/cgroup-internal.h:184
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_restore_control
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81229996)
Location: kernel/cgroup/cgroup-internal.h:184
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
```
```
In kernel/cgroup/freezer.c (ffffffff8122ac3a)
Location: kernel/cgroup/cgroup-internal.h:184
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
```
```
In kernel/bpf/cgroup_iter.c (ffffffff81355871)
Location: kernel/cgroup/cgroup-internal.h:184
Inline: True
Inline callers:
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_show
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
In kernel/cgroup/cgroup.c (ffffffff8123dc90)
Location: kernel/cgroup/cgroup-internal.h:184
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_restore_control
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff812417e6)
Location: kernel/cgroup/cgroup-internal.h:184
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
```
```
In kernel/cgroup/freezer.c (ffffffff81242bfa)
Location: kernel/cgroup/cgroup-internal.h:184
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
```
```
In kernel/bpf/cgroup_iter.c (ffffffff8137e271)
Location: kernel/cgroup/cgroup-internal.h:184
Inline: True
Inline callers:
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_show
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
In kernel/cgroup/cgroup.c (ffff8000101d81e8)
Location: kernel/cgroup/cgroup-internal.h:168
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_live
```
```
In kernel/cgroup/cgroup-v1.c (ffff8000101dbf94)
Location: kernel/cgroup/cgroup-internal.h:168
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/freezer.c (ffff8000101ddaa8)
Location: kernel/cgroup/cgroup-internal.h:168
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
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
In kernel/cgroup/cgroup.c (c041ae28)
Location: kernel/cgroup/cgroup-internal.h:168
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_live
```
```
In kernel/cgroup/cgroup-v1.c (c041e2bc)
Location: kernel/cgroup/cgroup-internal.h:168
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/freezer.c (c041f660)
Location: kernel/cgroup/cgroup-internal.h:168
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
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
In kernel/cgroup/cgroup.c (c000000000245130)
Location: kernel/cgroup/cgroup-internal.h:168
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_live
```
```
In kernel/cgroup/cgroup-v1.c (c0000000002496c8)
Location: kernel/cgroup/cgroup-internal.h:168
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/freezer.c (c00000000024b868)
Location: kernel/cgroup/cgroup-internal.h:168
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
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
In kernel/cgroup/cgroup.c (ffffffe00015122e)
Location: kernel/cgroup/cgroup-internal.h:168
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_live
```
```
In kernel/cgroup/cgroup-v1.c (ffffffe000154060)
Location: kernel/cgroup/cgroup-internal.h:168
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/freezer.c (ffffffe000155388)
Location: kernel/cgroup/cgroup-internal.h:168
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
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
In kernel/cgroup/cgroup.c (ffffffff8115eaec)
Location: kernel/cgroup/cgroup-internal.h:168
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_live
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8116149a)
Location: kernel/cgroup/cgroup-internal.h:168
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/freezer.c (ffffffff811626fa)
Location: kernel/cgroup/cgroup-internal.h:168
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
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
In kernel/cgroup/cgroup.c (ffffffff81151d96)
Location: kernel/cgroup/cgroup-internal.h:168
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_live
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811546fa)
Location: kernel/cgroup/cgroup-internal.h:168
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/freezer.c (ffffffff8115594a)
Location: kernel/cgroup/cgroup-internal.h:168
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
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
In kernel/cgroup/cgroup.c (ffffffff8115c8bc)
Location: kernel/cgroup/cgroup-internal.h:168
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_live
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115f26a)
Location: kernel/cgroup/cgroup-internal.h:168
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/freezer.c (ffffffff811604ca)
Location: kernel/cgroup/cgroup-internal.h:168
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
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
In kernel/cgroup/cgroup.c (ffffffff811699d2)
Location: kernel/cgroup/cgroup-internal.h:168
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_save_control
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_live
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8116c50a)
Location: kernel/cgroup/cgroup-internal.h:168
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/freezer.c (ffffffff8116d82a)
Location: kernel/cgroup/cgroup-internal.h:168
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
```
</details>
</li>
</ul>

## Differences
