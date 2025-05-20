# Function: <code>mongroup_create_dir</code>

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
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff810424f0)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:893
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_all
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
```
**Symbols:**

```
ffffffff810424f0-ffffffff81042560: mongroup_create_dir.constprop.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81045990)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:961
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_all
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
```
**Symbols:**

```
ffffffff81045990-ffffffff81045a00: mongroup_create_dir.constprop.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81047cd0)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:962
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_all
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
```
**Symbols:**

```
ffffffff81047cd0-ffffffff81047d52: mongroup_create_dir.constprop.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810572a0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1688
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_mount
```
**Symbols:**

```
ffffffff810572a0-ffffffff81057322: mongroup_create_dir.constprop.23 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105a590)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1686
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
```
**Symbols:**

```
ffffffff8105a590-ffffffff8105a616: mongroup_create_dir.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mongroup_create_dir(struct kernfs_node *parent_kn, struct rdtgroup *prgrp, char *name, struct kernfs_node **dest_kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105aa90)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1684
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
```
**Symbols:**

```
ffffffff8105aa90-ffffffff8105ab19: mongroup_create_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mongroup_create_dir(struct kernfs_node *parent_kn, struct rdtgroup *prgrp, char *name, struct kernfs_node **dest_kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105fe40)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1775
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
```
**Symbols:**

```
ffffffff8105fe40-ffffffff8105fec9: mongroup_create_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mongroup_create_dir(struct kernfs_node *parent_kn, struct rdtgroup *prgrp, char *name, struct kernfs_node **dest_kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105e040)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1827
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
```
**Symbols:**

```
ffffffff8105e040-ffffffff8105e0c1: mongroup_create_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mongroup_create_dir(struct kernfs_node *parent_kn, struct rdtgroup *prgrp, char *name, struct kernfs_node **dest_kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105e860)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1827
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
```
**Symbols:**

```
ffffffff8105e860-ffffffff8105e8e1: mongroup_create_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mongroup_create_dir(struct kernfs_node *parent_kn, struct rdtgroup *prgrp, char *name, struct kernfs_node **dest_kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81068190)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1790
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
```
**Symbols:**

```
ffffffff81068190-ffffffff81068211: mongroup_create_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mongroup_create_dir(struct kernfs_node *parent_kn, struct rdtgroup *prgrp, char *name, struct kernfs_node **dest_kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810751c0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1790
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
```
**Symbols:**

```
ffffffff810751c0-ffffffff81075273: mongroup_create_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mongroup_create_dir(struct kernfs_node *parent_kn, struct rdtgroup *prgrp, char *name, struct kernfs_node **dest_kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81085380)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1795
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
```
**Symbols:**

```
ffffffff81085380-ffffffff81085433: mongroup_create_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mongroup_create_dir(struct kernfs_node *parent_kn, struct rdtgroup *prgrp, char *name, struct kernfs_node **dest_kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81088040)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2076
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
```
**Symbols:**

```
ffffffff81088040-ffffffff810880f3: mongroup_create_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mongroup_create_dir(struct kernfs_node *parent_kn, struct rdtgroup *prgrp, char *name, struct kernfs_node **dest_kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108f120)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2167
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
```
**Symbols:**

```
ffffffff8108f120-ffffffff8108f1d3: mongroup_create_dir (STB_LOCAL)
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
int mongroup_create_dir(struct kernfs_node *parent_kn, struct rdtgroup *prgrp, char *name, struct kernfs_node **dest_kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105a610)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1684
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
```
**Symbols:**

```
ffffffff8105a610-ffffffff8105a699: mongroup_create_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int mongroup_create_dir(struct kernfs_node *parent_kn, struct rdtgroup *prgrp, char *name, struct kernfs_node **dest_kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104a690)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1684
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
```
**Symbols:**

```
ffffffff8104a690-ffffffff8104a719: mongroup_create_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mongroup_create_dir(struct kernfs_node *parent_kn, struct rdtgroup *prgrp, char *name, struct kernfs_node **dest_kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105aa40)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1684
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
```
**Symbols:**

```
ffffffff8105aa40-ffffffff8105aac9: mongroup_create_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mongroup_create_dir(struct kernfs_node *parent_kn, struct rdtgroup *prgrp, char *name, struct kernfs_node **dest_kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105bf00)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1684
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
```
**Symbols:**

```
ffffffff8105bf00-ffffffff8105bf89: mongroup_create_dir (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
