# Function: <code>rdtgroup_mkdir_ctrl_mon</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81043e00)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1639
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff810475b0)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1721
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81049b19)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1821
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81059bc9)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2714
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105d143)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2782
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105da49)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2786
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rdtgroup_mkdir_ctrl_mon(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81063260)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2881
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir
```
**Symbols:**

```
ffffffff81063260-ffffffff810633ee: rdtgroup_mkdir_ctrl_mon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rdtgroup_mkdir_ctrl_mon(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810616e0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2913
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir
```
**Symbols:**

```
ffffffff810616e0-ffffffff81061876: rdtgroup_mkdir_ctrl_mon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rdtgroup_mkdir_ctrl_mon(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81061de0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2909
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir
```
**Symbols:**

```
ffffffff81061de0-ffffffff81062057: rdtgroup_mkdir_ctrl_mon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int rdtgroup_mkdir_ctrl_mon(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2968
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir
```
**Symbols:**

```
ffffffff8106bb70-ffffffff8106be33: rdtgroup_mkdir_ctrl_mon (STB_LOCAL)
ffffffff81c9cb68-ffffffff81c9cbaf: rdtgroup_mkdir_ctrl_mon.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int rdtgroup_mkdir_ctrl_mon(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2968
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir
```
**Symbols:**

```
ffffffff81078e80-ffffffff81079149: rdtgroup_mkdir_ctrl_mon (STB_LOCAL)
ffffffff81e4be9d-ffffffff81e4befe: rdtgroup_mkdir_ctrl_mon.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int rdtgroup_mkdir_ctrl_mon(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:3018
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir
```
**Symbols:**

```
ffffffff81089900-ffffffff81089bde: rdtgroup_mkdir_ctrl_mon (STB_LOCAL)
ffffffff820534f6-ffffffff8205355a: rdtgroup_mkdir_ctrl_mon.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int rdtgroup_mkdir_ctrl_mon(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:3305
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir
```
**Symbols:**

```
ffffffff8108c930-ffffffff8108cc54: rdtgroup_mkdir_ctrl_mon (STB_LOCAL)
ffffffff820d1b18-ffffffff820d1b6c: rdtgroup_mkdir_ctrl_mon.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int rdtgroup_mkdir_ctrl_mon(struct kernfs_node *parent_kn, const char *name, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:3440
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir
```
**Symbols:**

```
ffffffff81092c70-ffffffff81092f94: rdtgroup_mkdir_ctrl_mon (STB_LOCAL)
ffffffff821ac746-ffffffff821ac79a: rdtgroup_mkdir_ctrl_mon.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105d5c9)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2786
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104d799)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2786
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105d9f9)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2786
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ef19)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2786
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
