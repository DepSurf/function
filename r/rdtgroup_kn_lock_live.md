# Function: <code>rdtgroup_kn_lock_live</code>

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
struct rdtgroup *rdtgroup_kn_lock_live(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81043fd0)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:699
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_show
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/intel_rdt_schemata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/intel_rdt_schemata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff81043fd0-ffffffff8104403b: rdtgroup_kn_lock_live (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct rdtgroup *rdtgroup_kn_lock_live(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81042ec0)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1033
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_show
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_mondata_show
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff81042ec0-ffffffff81042f2b: rdtgroup_kn_lock_live (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct rdtgroup *rdtgroup_kn_lock_live(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81046490)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1101
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_show
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_mondata_show
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff81046490-ffffffff810464fb: rdtgroup_kn_lock_live (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct rdtgroup *rdtgroup_kn_lock_live(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81048a40)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1198
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_show
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_mondata_show
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff81048a40-ffffffff81048aab: rdtgroup_kn_lock_live (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct rdtgroup *rdtgroup_kn_lock_live(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81058420)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1927
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff81058420-ffffffff8105848b: rdtgroup_kn_lock_live (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct rdtgroup *rdtgroup_kn_lock_live(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b9a0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1885
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff8105b9a0-ffffffff8105ba13: rdtgroup_kn_lock_live (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct rdtgroup *rdtgroup_kn_lock_live(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c2b0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1883
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff8105c2b0-ffffffff8105c323: rdtgroup_kn_lock_live (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct rdtgroup *rdtgroup_kn_lock_live(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81062380)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1987
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff81062380-ffffffff810623f7: rdtgroup_kn_lock_live (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct rdtgroup *rdtgroup_kn_lock_live(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810608d0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2038
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff810608d0-ffffffff81060947: rdtgroup_kn_lock_live (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct rdtgroup *rdtgroup_kn_lock_live(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810609e0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2038
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff810609e0-ffffffff81060a57: rdtgroup_kn_lock_live (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct rdtgroup *rdtgroup_kn_lock_live(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8106a6a0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1991
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff8106a6a0-ffffffff8106a717: rdtgroup_kn_lock_live (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct rdtgroup *rdtgroup_kn_lock_live(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81077930)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1991
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff81077930-ffffffff810779ad: rdtgroup_kn_lock_live (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct rdtgroup *rdtgroup_kn_lock_live(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810884c0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2031
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff810884c0-ffffffff8108853d: rdtgroup_kn_lock_live (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct rdtgroup *rdtgroup_kn_lock_live(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108b3f0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2328
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff8108b3f0-ffffffff8108b46d: rdtgroup_kn_lock_live (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct rdtgroup *rdtgroup_kn_lock_live(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810925e0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2411
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmid_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_closid_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff810925e0-ffffffff8109265d: rdtgroup_kn_lock_live (STB_GLOBAL)
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
struct rdtgroup *rdtgroup_kn_lock_live(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105be30)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1883
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff8105be30-ffffffff8105bea3: rdtgroup_kn_lock_live (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct rdtgroup *rdtgroup_kn_lock_live(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104c000)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1883
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff8104c000-ffffffff8104c073: rdtgroup_kn_lock_live (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct rdtgroup *rdtgroup_kn_lock_live(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c260)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1883
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff8105c260-ffffffff8105c2d3: rdtgroup_kn_lock_live (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct rdtgroup *rdtgroup_kn_lock_live(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105d770)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1883
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff8105d770-ffffffff8105d7e3: rdtgroup_kn_lock_live (STB_GLOBAL)
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
