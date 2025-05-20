# Function: <code>rdt_last_cmd_puts</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void rdt_last_cmd_puts(const char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff8104734c)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:64
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_bw
```
**Symbols:**

```
ffffffff810463f0-ffffffff8104640a: rdt_last_cmd_puts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void rdt_last_cmd_puts(const char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81049980)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:64
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_bw
```
**Symbols:**

```
ffffffff810489a0-ffffffff810489ba: rdt_last_cmd_puts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void rdt_last_cmd_puts(const char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810599f5)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:68
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff81057f00-ffffffff81057f1a: rdt_last_cmd_puts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void rdt_last_cmd_puts(const char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105cf78)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:62
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff8105b180-ffffffff8105b19a: rdt_last_cmd_puts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void rdt_last_cmd_puts(const char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c5cb)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:62
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff8105ba90-ffffffff8105baaa: rdt_last_cmd_puts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void rdt_last_cmd_puts(const char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8106333a)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:62
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init_alloc
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_test_exclusive
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_test_exclusive
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_move_task
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_move_task
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_init
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_cstates_constrain
```
**Symbols:**

```
ffffffff81061750-ffffffff8106176a: rdt_last_cmd_puts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void rdt_last_cmd_puts(const char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810617ba)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:62
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init_alloc
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_test_exclusive
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_test_exclusive
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_init
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_cstates_constrain
```
**Symbols:**

```
ffffffff8105fb60-ffffffff8105fb7a: rdt_last_cmd_puts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void rdt_last_cmd_puts(const char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81062045)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:62
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc
```
**Symbols:**

```
ffffffff810600f0-ffffffff8106010a: rdt_last_cmd_puts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void rdt_last_cmd_puts(const char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8106bdef)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc
```
**Symbols:**

```
ffffffff81069230-ffffffff8106924a: rdt_last_cmd_puts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void rdt_last_cmd_puts(const char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81079108)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc
```
**Symbols:**

```
ffffffff81076460-ffffffff81076484: rdt_last_cmd_puts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void rdt_last_cmd_puts(const char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81089bc1)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff81086f00-ffffffff81086f24: rdt_last_cmd_puts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void rdt_last_cmd_puts(const char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81089bdb)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mon_config_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mon_config_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mon_config_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff81089db0-ffffffff81089dd4: rdt_last_cmd_puts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void rdt_last_cmd_puts(const char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81090cf4)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:70
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mon_config_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mon_config_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mon_config_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff81090ed0-ffffffff81090ef4: rdt_last_cmd_puts (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void rdt_last_cmd_puts(const char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c14b)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:62
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff8105b610-ffffffff8105b62a: rdt_last_cmd_puts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void rdt_last_cmd_puts(const char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104c31b)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:62
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff8104b7e0-ffffffff8104b7fa: rdt_last_cmd_puts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void rdt_last_cmd_puts(const char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c57b)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:62
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff8105ba40-ffffffff8105ba5a: rdt_last_cmd_puts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void rdt_last_cmd_puts(const char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105da8b)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:62
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff8105cf30-ffffffff8105cf4a: rdt_last_cmd_puts (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
