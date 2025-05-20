# Function: <code>rdtgroup_add_files</code>

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
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff810436d0)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:128
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_init
```
**Symbols:**

```
ffffffff810436d0-ffffffff810437b4: rdtgroup_add_files.constprop.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int rdtgroup_add_files(struct kernfs_node *kn, long unsigned int fflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81042020)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:794
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_mkdir_info_resdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_init
```
**Symbols:**

```
ffffffff81042020-ffffffff81042102: rdtgroup_add_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int rdtgroup_add_files(struct kernfs_node *kn, long unsigned int fflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff810454f0)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:858
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_mkdir_info_resdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_init
```
**Symbols:**

```
ffffffff810454f0-ffffffff810455d2: rdtgroup_add_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int rdtgroup_add_files(struct kernfs_node *kn, long unsigned int fflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (0)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:859
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_mkdir_info_resdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_init
```
**Symbols:**

```
ffffffff81047960-ffffffff81047a08: rdtgroup_add_files (STB_LOCAL)
ffffffff81049e50-ffffffff81049e91: rdtgroup_add_files.cold.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int rdtgroup_add_files(struct kernfs_node *kn, long unsigned int fflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1488
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
```
**Symbols:**

```
ffffffff81056e90-ffffffff81056f38: rdtgroup_add_files (STB_LOCAL)
ffffffff8105a1d0-ffffffff8105a211: rdtgroup_add_files.cold.24 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int rdtgroup_add_files(struct kernfs_node *kn, long unsigned int fflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1486
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
```
**Symbols:**

```
ffffffff8105a070-ffffffff8105a120: rdtgroup_add_files (STB_LOCAL)
ffffffff8105d480-ffffffff8105d4c9: rdtgroup_add_files.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int rdtgroup_add_files(struct kernfs_node *kn, long unsigned int fflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1484
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
```
**Symbols:**

```
ffffffff8105a960-ffffffff8105aa10: rdtgroup_add_files (STB_LOCAL)
ffffffff8105dd70-ffffffff8105ddb9: rdtgroup_add_files.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int rdtgroup_add_files(struct kernfs_node *kn, long unsigned int fflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1575
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_setup_root
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_create_info_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
```
**Symbols:**

```
ffffffff8105f970-ffffffff8105fa20: rdtgroup_add_files (STB_LOCAL)
ffffffff810636c0-ffffffff81063709: rdtgroup_add_files.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int rdtgroup_add_files(struct kernfs_node *kn, long unsigned int fflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1608
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_setup_root
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_create_info_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
```
**Symbols:**

```
ffffffff8105dd50-ffffffff8105de05: rdtgroup_add_files (STB_LOCAL)
ffffffff81bd64ce-ffffffff81bd6517: rdtgroup_add_files.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int rdtgroup_add_files(struct kernfs_node *kn, long unsigned int fflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1608
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
```
**Symbols:**

```
ffffffff8105e570-ffffffff8105e625: rdtgroup_add_files (STB_LOCAL)
ffffffff81bc8780-ffffffff81bc87c9: rdtgroup_add_files.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int rdtgroup_add_files(struct kernfs_node *kn, long unsigned int fflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1568
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
```
**Symbols:**

```
ffffffff81067cf0-ffffffff81067da5: rdtgroup_add_files (STB_LOCAL)
ffffffff81c9c6ca-ffffffff81c9c713: rdtgroup_add_files.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int rdtgroup_add_files(struct kernfs_node *kn, long unsigned int fflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1568
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
```
**Symbols:**

```
ffffffff81074b30-ffffffff81074c01: rdtgroup_add_files (STB_LOCAL)
ffffffff81e4ba17-ffffffff81e4ba45: rdtgroup_add_files.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rdtgroup_add_files(struct kernfs_node *kn, long unsigned int fflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81084ce0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1573
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
```
**Symbols:**

```
ffffffff81084ce0-ffffffff81084deb: rdtgroup_add_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rdtgroup_add_files(struct kernfs_node *kn, long unsigned int fflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81087210)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1845
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
```
**Symbols:**

```
ffffffff81087210-ffffffff81087310: rdtgroup_add_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int rdtgroup_add_files(struct kernfs_node *kn, long unsigned int fflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1933
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
```
**Symbols:**

```
ffffffff8108e810-ffffffff8108e93b: rdtgroup_add_files (STB_LOCAL)
ffffffff821ac2e2-ffffffff821ac2f7: rdtgroup_add_files.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int rdtgroup_add_files(struct kernfs_node *kn, long unsigned int fflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1484
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
```
**Symbols:**

```
ffffffff8105a4e0-ffffffff8105a590: rdtgroup_add_files (STB_LOCAL)
ffffffff8105d8f0-ffffffff8105d939: rdtgroup_add_files.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int rdtgroup_add_files(struct kernfs_node *kn, long unsigned int fflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1484
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
```
**Symbols:**

```
ffffffff8104a560-ffffffff8104a610: rdtgroup_add_files (STB_LOCAL)
ffffffff8104dac0-ffffffff8104db09: rdtgroup_add_files.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int rdtgroup_add_files(struct kernfs_node *kn, long unsigned int fflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1484
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
```
**Symbols:**

```
ffffffff8105a910-ffffffff8105a9c0: rdtgroup_add_files (STB_LOCAL)
ffffffff8105dd20-ffffffff8105dd69: rdtgroup_add_files.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int rdtgroup_add_files(struct kernfs_node *kn, long unsigned int fflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1484
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
```
**Symbols:**

```
ffffffff8105bdd0-ffffffff8105be80: rdtgroup_add_files (STB_LOCAL)
ffffffff8105f240-ffffffff8105f289: rdtgroup_add_files.cold (STB_LOCAL)
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
