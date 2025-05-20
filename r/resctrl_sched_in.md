# Function: <code>resctrl_sched_in</code>

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
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102d8d0)
Location: arch/x86/include/asm/resctrl_sched.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81057e93)
Location: arch/x86/include/asm/resctrl_sched.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:move_myself
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102f6a1)
Location: arch/x86/include/asm/resctrl_sched.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b114)
Location: arch/x86/include/asm/resctrl_sched.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:move_myself
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81030001)
Location: arch/x86/include/asm/resctrl_sched.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ba24)
Location: arch/x86/include/asm/resctrl_sched.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:move_myself
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81032883)
Location: arch/x86/include/asm/resctrl.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105f4e3)
Location: arch/x86/include/asm/resctrl.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:move_myself
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_cpu_closid_rmid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff810334dc)
Location: arch/x86/include/asm/resctrl.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ef17)
Location: arch/x86/include/asm/resctrl.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81034fd3)
Location: arch/x86/include/asm/resctrl.h:84
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81061255)
Location: arch/x86/include/asm/resctrl.h:84
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8103a2e6)
Location: arch/x86/include/asm/resctrl.h:84
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8106af15)
Location: arch/x86/include/asm/resctrl.h:84
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
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
In arch/x86/kernel/process_64.c (ffffffff8104133e)
Location: arch/x86/include/asm/resctrl.h:84
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8107820b)
Location: arch/x86/include/asm/resctrl.h:84
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
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
In arch/x86/kernel/process_64.c (ffffffff8104aa8e)
Location: arch/x86/include/asm/resctrl.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81088e2d)
Location: arch/x86/include/asm/resctrl.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
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
In arch/x86/kernel/process_64.c (ffffffff8104b2ce)
Location: arch/x86/include/asm/resctrl.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108bd2d)
Location: arch/x86/include/asm/resctrl.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_cpu_closid_rmid
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void resctrl_sched_in(struct task_struct *tsk);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8105253e)
Location: arch/x86/include/asm/resctrl.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8109071a)
Location: arch/x86/include/asm/resctrl.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_cpu_closid_rmid
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
**Symbols:**

```
ffffffff81090650-ffffffff810906d7: resctrl_sched_in (STB_LOCAL)
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81030161)
Location: arch/x86/include/asm/resctrl_sched.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b5a4)
Location: arch/x86/include/asm/resctrl_sched.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:move_myself
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8101fbbc)
Location: arch/x86/include/asm/resctrl_sched.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104b714)
Location: arch/x86/include/asm/resctrl_sched.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:move_myself
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102ffc1)
Location: arch/x86/include/asm/resctrl_sched.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b9d4)
Location: arch/x86/include/asm/resctrl_sched.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:move_myself
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81030e11)
Location: arch/x86/include/asm/resctrl_sched.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ceab)
Location: arch/x86/include/asm/resctrl_sched.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:move_myself
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
