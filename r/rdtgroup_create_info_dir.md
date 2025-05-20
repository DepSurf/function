# Function: <code>rdtgroup_create_info_dir</code>

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
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff8104395d)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:543
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff8104286e)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:845
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
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
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81045cd3)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:909
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
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
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81048639)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:910
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810575a0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1636
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_mount
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105a7bc)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1634
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ae8c)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1632
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rdtgroup_create_info_dir(struct kernfs_node *parent_kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ff90)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1723
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
```
**Symbols:**

```
ffffffff8105ff90-ffffffff81060101: rdtgroup_create_info_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rdtgroup_create_info_dir(struct kernfs_node *parent_kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105e150)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1782
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
```
**Symbols:**

```
ffffffff8105e150-ffffffff8105e2a9: rdtgroup_create_info_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105fd18)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1782
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8106a32d)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1742
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81077539)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1742
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810880b9)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1747
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108afb6)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2028
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81091fd4)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2119
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105aa0c)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1632
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104aa8c)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1632
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ae3c)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1632
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c2fc)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1632
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
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
</ul>
