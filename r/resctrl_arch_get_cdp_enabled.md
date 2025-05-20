# Function: <code>resctrl_arch_get_cdp_enabled</code>

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
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81067e75)
Location: arch/x86/kernel/cpu/resctrl/internal.h:434
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:schemata_list_add
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:schemata_list_add
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_overlaps
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106f155)
Location: arch/x86/kernel/cpu/resctrl/internal.h:434
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81074cf5)
Location: arch/x86/kernel/cpu/resctrl/internal.h:434
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:schemata_list_add
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:schemata_list_add
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_overlaps
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8107c9a6)
Location: arch/x86/kernel/cpu/resctrl/internal.h:434
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81084e45)
Location: arch/x86/kernel/cpu/resctrl/internal.h:425
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:schemata_list_add
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:schemata_list_add
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_overlaps
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108dcf6)
Location: arch/x86/kernel/cpu/resctrl/internal.h:425
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810876b5)
Location: arch/x86/kernel/cpu/resctrl/internal.h:451
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:schemata_list_add
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:schemata_list_add
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_overlaps
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81090ba6)
Location: arch/x86/kernel/cpu/resctrl/internal.h:451
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108e615)
Location: arch/x86/kernel/cpu/resctrl/internal.h:451
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:schemata_list_add
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:schemata_list_add
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_overlaps
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81097f36)
Location: arch/x86/kernel/cpu/resctrl/internal.h:451
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
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
