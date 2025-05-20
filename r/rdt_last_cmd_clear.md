# Function: <code>rdt_last_cmd_clear</code>

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
void rdt_last_cmd_clear();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff810472a5)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:58
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff810463c0-ffffffff810463e1: rdt_last_cmd_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void rdt_last_cmd_clear();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81049852)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:58
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff81048970-ffffffff81048991: rdt_last_cmd_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void rdt_last_cmd_clear();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810598c1)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:62
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff81057ed0-ffffffff81057ef1: rdt_last_cmd_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void rdt_last_cmd_clear();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ce41)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:56
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff8105b150-ffffffff8105b171: rdt_last_cmd_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void rdt_last_cmd_clear();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105afd8)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:56
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff8105ba60-ffffffff8105ba81: rdt_last_cmd_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void rdt_last_cmd_clear();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8106111d)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:56
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff81061720-ffffffff81061741: rdt_last_cmd_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void rdt_last_cmd_clear();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105f56f)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:56
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff8105fb30-ffffffff8105fb51: rdt_last_cmd_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void rdt_last_cmd_clear();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105fc4b)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:56
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff810600c0-ffffffff810600e1: rdt_last_cmd_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void rdt_last_cmd_clear();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8106a25c)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:59
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff81069200-ffffffff81069221: rdt_last_cmd_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void rdt_last_cmd_clear();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8107748a)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:59
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff81076430-ffffffff81076455: rdt_last_cmd_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void rdt_last_cmd_clear();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108800a)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:59
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff81086ec0-ffffffff81086ee5: rdt_last_cmd_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void rdt_last_cmd_clear();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81089a44)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:59
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mbm_local_bytes_config_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mbm_total_bytes_config_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff81089d70-ffffffff81089d95: rdt_last_cmd_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void rdt_last_cmd_clear();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81090b54)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:64
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mbm_local_bytes_config_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mbm_local_bytes_config_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mbm_total_bytes_config_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mbm_total_bytes_config_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff81090e90-ffffffff81090ec0: rdt_last_cmd_clear (STB_GLOBAL)
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
void rdt_last_cmd_clear();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ab58)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:56
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff8105b5e0-ffffffff8105b601: rdt_last_cmd_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void rdt_last_cmd_clear();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104abd8)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:56
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff8104b7b0-ffffffff8104b7d1: rdt_last_cmd_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void rdt_last_cmd_clear();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105af88)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:56
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff8105ba10-ffffffff8105ba31: rdt_last_cmd_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void rdt_last_cmd_clear();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c448)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:56
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff8105cf00-ffffffff8105cf21: rdt_last_cmd_clear (STB_GLOBAL)
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
