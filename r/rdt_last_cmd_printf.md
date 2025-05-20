# Function: <code>rdt_last_cmd_printf</code>

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
<summary>In <code>4.15</code>: ✅</summary>

```c
void rdt_last_cmd_printf(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81046410)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:70
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_bw
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_bw
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_bw
```
**Symbols:**

```
ffffffff81046410-ffffffff81046488: rdt_last_cmd_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rdt_last_cmd_printf(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff810489c0)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:70
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_bw
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_bw
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_bw
```
**Symbols:**

```
ffffffff810489c0-ffffffff81048a39: rdt_last_cmd_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rdt_last_cmd_printf(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81057f20)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:74
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
**Symbols:**

```
ffffffff81057f20-ffffffff81057f99: rdt_last_cmd_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rdt_last_cmd_printf(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b1a0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:68
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
**Symbols:**

```
ffffffff8105b1a0-ffffffff8105b219: rdt_last_cmd_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rdt_last_cmd_printf(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105bab0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:68
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
**Symbols:**

```
ffffffff8105bab0-ffffffff8105bb29: rdt_last_cmd_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rdt_last_cmd_printf(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81061770)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:68
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_init
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_cstates_constrain
```
**Symbols:**

```
ffffffff81061770-ffffffff810617e9: rdt_last_cmd_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rdt_last_cmd_printf(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105fb80)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:68
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_init
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_cstates_constrain
```
**Symbols:**

```
ffffffff8105fb80-ffffffff8105fbf9: rdt_last_cmd_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rdt_last_cmd_printf(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81060110)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:68
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc
```
**Symbols:**

```
ffffffff81060110-ffffffff81060189: rdt_last_cmd_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rdt_last_cmd_printf(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81069250)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:71
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc
```
**Symbols:**

```
ffffffff81069250-ffffffff810692c9: rdt_last_cmd_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rdt_last_cmd_printf(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81076490)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:71
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc
```
**Symbols:**

```
ffffffff81076490-ffffffff81076525: rdt_last_cmd_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rdt_last_cmd_printf(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81086f40)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:71
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
**Symbols:**

```
ffffffff81086f40-ffffffff81086fd5: rdt_last_cmd_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rdt_last_cmd_printf(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81089df0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:71
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
**Symbols:**

```
ffffffff81089df0-ffffffff81089e85: rdt_last_cmd_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rdt_last_cmd_printf(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81090f10)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:76
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
**Symbols:**

```
ffffffff81090f10-ffffffff81090fa5: rdt_last_cmd_printf (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void rdt_last_cmd_printf(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b630)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:68
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
**Symbols:**

```
ffffffff8105b630-ffffffff8105b6a9: rdt_last_cmd_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rdt_last_cmd_printf(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104b800)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:68
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
**Symbols:**

```
ffffffff8104b800-ffffffff8104b879: rdt_last_cmd_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rdt_last_cmd_printf(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ba60)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:68
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
**Symbols:**

```
ffffffff8105ba60-ffffffff8105bad9: rdt_last_cmd_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rdt_last_cmd_printf(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105cf50)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:68
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
**Symbols:**

```
ffffffff8105cf50-ffffffff8105cfc9: rdt_last_cmd_printf (STB_GLOBAL)
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
