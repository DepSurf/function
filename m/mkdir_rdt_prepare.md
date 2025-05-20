# Function: <code>mkdir_rdt_prepare</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mkdir_rdt_prepare(struct kernfs_node *parent_kn, struct kernfs_node *prgrp_kn, const char *name, umode_t mode, enum rdt_group_type rtype, struct rdtgroup **r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81043b70)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1516
Inline: False
```
**Symbols:**

```
ffffffff81043b70-ffffffff81043ce1: mkdir_rdt_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mkdir_rdt_prepare(struct kernfs_node *parent_kn, struct kernfs_node *prgrp_kn, const char *name, umode_t mode, enum rdt_group_type rtype, struct rdtgroup **r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81047270)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1587
Inline: False
```
**Symbols:**

```
ffffffff81047270-ffffffff81047498: mkdir_rdt_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mkdir_rdt_prepare(struct kernfs_node *parent_kn, struct kernfs_node *prgrp_kn, const char *name, umode_t mode, enum rdt_group_type rtype, struct rdtgroup **r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81049820)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1687
Inline: False
```
**Symbols:**

```
ffffffff81049820-ffffffff81049a4b: mkdir_rdt_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mkdir_rdt_prepare(struct kernfs_node *parent_kn, struct kernfs_node *prgrp_kn, const char *name, umode_t mode, enum rdt_group_type rtype, struct rdtgroup **r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81059890)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2572
Inline: False
```
**Symbols:**

```
ffffffff81059890-ffffffff81059af8: mkdir_rdt_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int mkdir_rdt_prepare(struct kernfs_node *parent_kn, struct kernfs_node *prgrp_kn, const char *name, umode_t mode, enum rdt_group_type rtype, struct rdtgroup **r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ce10)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2640
Inline: False
```
**Symbols:**

```
ffffffff8105ce10-ffffffff8105d07b: mkdir_rdt_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105d760)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2646
Inline: True
```
**Symbols:**

```
ffffffff8105d760-ffffffff8105d990: mkdir_rdt_prepare.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mkdir_rdt_prepare(struct kernfs_node *parent_kn, const char *name, umode_t mode, enum rdt_group_type rtype, struct rdtgroup **r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81063030)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2745
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
```
**Symbols:**

```
ffffffff81063030-ffffffff81063260: mkdir_rdt_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mkdir_rdt_prepare(struct kernfs_node *parent_kn, const char *name, umode_t mode, enum rdt_group_type rtype, struct rdtgroup **r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810614a0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2776
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
```
**Symbols:**

```
ffffffff810614a0-ffffffff810616d8: mkdir_rdt_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mkdir_rdt_prepare(struct kernfs_node *parent_kn, const char *name, umode_t mode, enum rdt_group_type rtype, struct rdtgroup **r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81061ba0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2772
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
```
**Symbols:**

```
ffffffff81061ba0-ffffffff81061dd8: mkdir_rdt_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mkdir_rdt_prepare(struct kernfs_node *parent_kn, const char *name, umode_t mode, enum rdt_group_type rtype, struct rdtgroup **r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2831
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
```
**Symbols:**

```
ffffffff8106b920-ffffffff8106bb68: mkdir_rdt_prepare (STB_LOCAL)
ffffffff81c9cb54-ffffffff81c9cb68: mkdir_rdt_prepare.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mkdir_rdt_prepare(struct kernfs_node *parent_kn, const char *name, umode_t mode, enum rdt_group_type rtype, struct rdtgroup **r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2831
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
```
**Symbols:**

```
ffffffff81078c30-ffffffff81078e80: mkdir_rdt_prepare (STB_LOCAL)
ffffffff81e4be89-ffffffff81e4be9d: mkdir_rdt_prepare.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int mkdir_rdt_prepare(struct kernfs_node *parent_kn, const char *name, umode_t mode, enum rdt_group_type rtype, struct rdtgroup **r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2881
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
```
**Symbols:**

```
ffffffff810896a0-ffffffff810898f0: mkdir_rdt_prepare (STB_LOCAL)
ffffffff820534e2-ffffffff820534f6: mkdir_rdt_prepare.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int mkdir_rdt_prepare(struct kernfs_node *parent_kn, const char *name, umode_t mode, enum rdt_group_type rtype, struct rdtgroup **r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:3168
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
```
**Symbols:**

```
ffffffff8108c6d0-ffffffff8108c920: mkdir_rdt_prepare (STB_LOCAL)
ffffffff820d1b04-ffffffff820d1b18: mkdir_rdt_prepare.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int mkdir_rdt_prepare(struct kernfs_node *parent_kn, const char *name, umode_t mode, enum rdt_group_type rtype, struct rdtgroup **r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:3296
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
```
**Symbols:**

```
ffffffff810929b0-ffffffff81092c58: mkdir_rdt_prepare (STB_LOCAL)
ffffffff821ac71c-ffffffff821ac746: mkdir_rdt_prepare.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105d2e0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2646
Inline: True
```
**Symbols:**

```
ffffffff8105d2e0-ffffffff8105d510: mkdir_rdt_prepare.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104d4b0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2646
Inline: True
```
**Symbols:**

```
ffffffff8104d4b0-ffffffff8104d6e0: mkdir_rdt_prepare.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105d710)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2646
Inline: True
```
**Symbols:**

```
ffffffff8105d710-ffffffff8105d940: mkdir_rdt_prepare.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ec30)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2646
Inline: True
```
**Symbols:**

```
ffffffff8105ec30-ffffffff8105ee60: mkdir_rdt_prepare.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
