# Function: <code>spectre_v2_in_eibrs_mode</code>

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
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81053d46)
Location: arch/x86/kernel/cpu/bugs.c:770
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_show_state
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8106e31f)
Location: arch/x86/kernel/cpu/bugs.c:1135
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_show_state
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation
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
In arch/x86/kernel/cpu/bugs.c (ffffffff8106faf1)
Location: arch/x86/kernel/cpu/cpu.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_show_state
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81076603)
Location: arch/x86/kernel/cpu/cpu.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
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
In arch/x86/kernel/cpu/bugs.c (ffffffff81076f1f)
Location: arch/x86/kernel/cpu/cpu.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_show_state
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8107da29)
Location: arch/x86/kernel/cpu/cpu.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
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
