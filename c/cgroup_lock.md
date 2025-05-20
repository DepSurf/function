# Function: <code>cgroup_lock</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
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
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8137bcf5)
Location: include/linux/cgroup.h:368
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_change_state
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
In kernel/cgroup/cgroup.c (ffffffff812260df)
Location: include/linux/cgroup.h:367
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_rm_cftypes
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_path_ns
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81228c90)
Location: include/linux/cgroup.h:367
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
```
In kernel/bpf/local_storage.c (ffffffff813318ef)
Location: include/linux/cgroup.h:367
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
```
```
In kernel/bpf/cgroup_iter.c (ffffffff813554d3)
Location: include/linux/cgroup.h:367
Inline: True
Inline callers:
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_start
```
```
In kernel/bpf/cgroup.c (ffffffff8135a806)
Location: include/linux/cgroup.h:367
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
  - kernel/bpf/cgroup.c:bpf_cgroup_link_fill_link_info
  - kernel/bpf/cgroup.c:bpf_cgroup_link_show_fdinfo
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_replace
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:bpf_cgroup_atype_put
```
```
In mm/vmscan.c (ffffffff813ab095)
Location: include/linux/cgroup.h:367
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_change_state
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
In kernel/cgroup/cgroup.c (ffffffff8123dd6f)
Location: include/linux/cgroup.h:366
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_rm_cftypes
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_path_ns
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81240ae0)
Location: include/linux/cgroup.h:366
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
```
In kernel/bpf/local_storage.c (ffffffff81355e8f)
Location: include/linux/cgroup.h:366
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
```
```
In kernel/bpf/cgroup_iter.c (ffffffff8137dea3)
Location: include/linux/cgroup.h:366
Inline: True
Inline callers:
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_start
```
```
In kernel/bpf/cgroup.c (ffffffff813833f6)
Location: include/linux/cgroup.h:366
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
  - kernel/bpf/cgroup.c:bpf_cgroup_link_fill_link_info
  - kernel/bpf/cgroup.c:bpf_cgroup_link_show_fdinfo
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_replace
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:bpf_cgroup_atype_put
```
```
In mm/vmscan.c (ffffffff813d4935)
Location: include/linux/cgroup.h:366
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_change_state
```
</details>
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
