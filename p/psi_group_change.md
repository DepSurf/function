# Function: <code>psi_group_change</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810ef597)
Location: kernel/sched/psi.c:446
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_change
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
In kernel/sched/psi.c (ffffffff810f6928)
Location: kernel/sched/psi.c:671
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_change
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
In kernel/sched/psi.c (ffffffff811026b8)
Location: kernel/sched/psi.c:672
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_change
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void psi_group_change(struct psi_group *group, int cpu, unsigned int clear, unsigned int set, bool wake_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/psi.c (0)
Location: kernel/sched/psi.c:672
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_change
```
**Symbols:**

```
ffffffff8110d240-ffffffff8110d429: psi_group_change (STB_LOCAL)
ffffffff8110dfa8-ffffffff8110dff8: psi_group_change.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void psi_group_change(struct psi_group *group, int cpu, unsigned int clear, unsigned int set, bool wake_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/psi.c (0)
Location: kernel/sched/psi.c:688
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_change
```
**Symbols:**

```
ffffffff8110a240-ffffffff8110a466: psi_group_change (STB_LOCAL)
ffffffff81bde859-ffffffff81bde8a9: psi_group_change.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void psi_group_change(struct psi_group *group, int cpu, unsigned int clear, unsigned int set, u64 now, bool wake_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/psi.c (0)
Location: kernel/sched/psi.c:680
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_change
```
**Symbols:**

```
ffffffff8110bdb0-ffffffff8110c074: psi_group_change (STB_LOCAL)
ffffffff81bd0a01-ffffffff81bd0a4a: psi_group_change.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void psi_group_change(struct psi_group *group, int cpu, unsigned int clear, unsigned int set, u64 now, bool wake_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/psi.c (0)
Location: kernel/sched/psi.c:691
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_task_change
```
**Symbols:**

```
ffffffff8112aa50-ffffffff8112ae5d: psi_group_change (STB_LOCAL)
ffffffff81ca9447-ffffffff81ca9557: psi_group_change.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void psi_group_change(struct psi_group *group, int cpu, unsigned int clear, unsigned int set, u64 now, bool wake_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/psi.c:690
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_change
  - kernel/sched/build_utility.c:psi_task_change
```
**Symbols:**

```
ffffffff8113f640-ffffffff8113fa9d: psi_group_change (STB_LOCAL)
ffffffff81e5715c-ffffffff81e57340: psi_group_change.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void psi_group_change(struct psi_group *group, int cpu, unsigned int clear, unsigned int set, u64 now, bool wake_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/psi.c:755
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:psi_cgroup_restart
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_change
```
**Symbols:**

```
ffffffff8116a100-ffffffff8116a629: psi_group_change (STB_LOCAL)
ffffffff82057c7d-ffffffff82057dd8: psi_group_change.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void psi_group_change(struct psi_group *group, int cpu, unsigned int clear, unsigned int set, u64 now, bool wake_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/psi.c:778
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:psi_cgroup_restart
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_change
```
**Symbols:**

```
ffffffff8117a7f0-ffffffff8117ad3d: psi_group_change (STB_LOCAL)
ffffffff820d64b2-ffffffff820d6552: psi_group_change.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void psi_group_change(struct psi_group *group, int cpu, unsigned int clear, unsigned int set, u64 now, bool wake_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/psi.c:767
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:psi_cgroup_restart
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_change
```
**Symbols:**

```
ffffffff81188220-ffffffff8118876d: psi_group_change (STB_LOCAL)
ffffffff821b1607-ffffffff821b16a7: psi_group_change.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffff800010167374)
Location: kernel/sched/psi.c:672
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_change
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (c03b41c0)
Location: kernel/sched/psi.c:672
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_change
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (c0000000001bef4c)
Location: kernel/sched/psi.c:672
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_change
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffe000109966)
Location: kernel/sched/psi.c:672
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_change
```
</details>
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
In kernel/sched/psi.c (ffffffff810fb9c8)
Location: kernel/sched/psi.c:672
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_change
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
In kernel/sched/psi.c (ffffffff810ebbe8)
Location: kernel/sched/psi.c:672
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_change
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
In kernel/sched/psi.c (ffffffff810f8b88)
Location: kernel/sched/psi.c:672
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_change
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
In kernel/sched/psi.c (ffffffff81103cd8)
Location: kernel/sched/psi.c:672
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_change
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 now</code>
</li>
<li>
<b>Param reordered. </b>
<code>group, cpu, clear, set, wake_clock</code> ➡️ <code>group, cpu, clear, set, now, wake_clock</code>
</li>
</ul>
</details>
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
