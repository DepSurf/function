# Function: <code>rdtgroup_kn_unlock</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void rdtgroup_kn_unlock(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81044040)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:718
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_show
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/intel_rdt_schemata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/intel_rdt_schemata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_schemata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff81044040-ffffffff810440cb: rdtgroup_kn_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rdtgroup_kn_unlock(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81042f30)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1052
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_show
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_mondata_show
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff81042f30-ffffffff81042fbb: rdtgroup_kn_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rdtgroup_kn_unlock(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81046500)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1120
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_show
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_mondata_show
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff81046500-ffffffff8104658b: rdtgroup_kn_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rdtgroup_kn_unlock(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81048ab0)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1217
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_show
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_mondata_show
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff81048ab0-ffffffff81048b3b: rdtgroup_kn_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rdtgroup_kn_unlock(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81058490)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1946
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff81058490-ffffffff81058538: rdtgroup_kn_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rdtgroup_kn_unlock(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ba20)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1904
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff8105ba20-ffffffff8105bad1: rdtgroup_kn_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rdtgroup_kn_unlock(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c330)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1902
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff8105c330-ffffffff8105c3e1: rdtgroup_kn_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rdtgroup_kn_unlock(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81062400)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2006
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff81062400-ffffffff810624a8: rdtgroup_kn_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rdtgroup_kn_unlock(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81060950)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2057
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff81060950-ffffffff810609f8: rdtgroup_kn_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rdtgroup_kn_unlock(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81060a60)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2057
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff81060a60-ffffffff81060b08: rdtgroup_kn_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rdtgroup_kn_unlock(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8106a720)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2010
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff8106a720-ffffffff8106a7c8: rdtgroup_kn_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rdtgroup_kn_unlock(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810779b0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2010
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff810779b0-ffffffff81077a68: rdtgroup_kn_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rdtgroup_kn_unlock(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81088550)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2050
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff81088550-ffffffff81088608: rdtgroup_kn_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rdtgroup_kn_unlock(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108b480)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2346
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff8108b480-ffffffff8108b4f9: rdtgroup_kn_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rdtgroup_kn_unlock(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81092670)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2429
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmid_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_closid_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff81092670-ffffffff810926e9: rdtgroup_kn_unlock (STB_GLOBAL)
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
void rdtgroup_kn_unlock(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105beb0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1902
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff8105beb0-ffffffff8105bf61: rdtgroup_kn_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rdtgroup_kn_unlock(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104c080)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1902
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff8104c080-ffffffff8104c131: rdtgroup_kn_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rdtgroup_kn_unlock(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c2e0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1902
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff8105c2e0-ffffffff8105c391: rdtgroup_kn_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rdtgroup_kn_unlock(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105d7f0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1902
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff8105d7f0-ffffffff8105d8a1: rdtgroup_kn_unlock (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
