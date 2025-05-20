# Function: <code>resctrl_to_arch_res</code>

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
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff832b0844)
Location: arch/x86/kernel/cpu/resctrl/internal.h:399
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:rdt_ctrl_update
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_arch_get_num_closid
  - arch/x86/kernel/cpu/resctrl/core.c:cat_wrmsr
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel
  - arch/x86/kernel/cpu/resctrl/core.c:rdt_get_cache_alloc_cfg
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810687d7)
Location: arch/x86/kernel/cpu/resctrl/internal.h:399
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_domain_reconfigure_cdp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:max_threshold_occ_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:max_threshold_occ_show
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8106cc31)
Location: arch/x86/kernel/cpu/resctrl/internal.h:399
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:__mon_event_count
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106f5db)
Location: arch/x86/kernel/cpu/resctrl/internal.h:399
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
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
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: arch/x86/kernel/cpu/resctrl/internal.h:399
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/internal.h:399
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/kernel/cpu/resctrl/internal.h:399
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: arch/x86/kernel/cpu/resctrl/internal.h:399
Inline: True
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
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: arch/x86/kernel/cpu/resctrl/internal.h:390
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/internal.h:390
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/kernel/cpu/resctrl/internal.h:390
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: arch/x86/kernel/cpu/resctrl/internal.h:390
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: arch/x86/kernel/cpu/resctrl/internal.h:390
Inline: True
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
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: arch/x86/kernel/cpu/resctrl/internal.h:415
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/internal.h:415
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/kernel/cpu/resctrl/internal.h:415
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: arch/x86/kernel/cpu/resctrl/internal.h:415
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: arch/x86/kernel/cpu/resctrl/internal.h:415
Inline: True
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
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: arch/x86/kernel/cpu/resctrl/internal.h:415
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/internal.h:415
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/kernel/cpu/resctrl/internal.h:415
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: arch/x86/kernel/cpu/resctrl/internal.h:415
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: arch/x86/kernel/cpu/resctrl/internal.h:415
Inline: True
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
