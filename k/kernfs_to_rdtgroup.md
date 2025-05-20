# Function: <code>kernfs_to_rdtgroup</code>

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
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff8104404c)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:681
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_kn_lock_live
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
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81042f3c)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1015
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_kn_lock_live
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
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff8104650c)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1083
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_kn_lock_live
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
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81048ab5)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_kn_lock_live
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81058495)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1909
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ba25)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1867
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c335)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1865
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81062405)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1969
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81060955)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2020
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81060a65)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2020
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8106a725)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1973
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810779b5)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1973
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81088555)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2013
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810899ab)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2290
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81090abb)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2373
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105beb5)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1865
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104c085)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1865
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c2e5)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1865
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105d7f5)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1865
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live
```
</details>
</li>
</ul>

## Differences
