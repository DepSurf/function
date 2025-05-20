# Function: <code>resctrl_arch_update_domains</code>

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
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int resctrl_arch_update_domains(struct rdt_resource *r, u32 closid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:279
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff81c9cd4f-ffffffff81c9cd64: resctrl_arch_update_domains.cold (STB_LOCAL)
ffffffff8106d1e0-ffffffff8106d3df: resctrl_arch_update_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int resctrl_arch_update_domains(struct rdt_resource *r, u32 closid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:279
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff81e4c0ac-ffffffff81e4c0c0: resctrl_arch_update_domains.cold (STB_LOCAL)
ffffffff8107a6b0-ffffffff8107a8ff: resctrl_arch_update_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int resctrl_arch_update_domains(struct rdt_resource *r, u32 closid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:305
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff820536e1-ffffffff820536f6: resctrl_arch_update_domains.cold (STB_LOCAL)
ffffffff8108b930-ffffffff8108bb67: resctrl_arch_update_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int resctrl_arch_update_domains(struct rdt_resource *r, u32 closid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:305
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff820d1cd4-ffffffff820d1ce9: resctrl_arch_update_domains.cold (STB_LOCAL)
ffffffff8108e880-ffffffff8108ea79: resctrl_arch_update_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int resctrl_arch_update_domains(struct rdt_resource *r, u32 closid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:307
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff821ac938-ffffffff821ac94d: resctrl_arch_update_domains.cold (STB_LOCAL)
ffffffff81095c10-ffffffff81095e09: resctrl_arch_update_domains (STB_GLOBAL)
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
<b>Regular</b>
<ul>
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
