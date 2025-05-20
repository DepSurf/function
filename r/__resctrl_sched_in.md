# Function: <code>__resctrl_sched_in</code>

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
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __resctrl_sched_in();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102d8d5)
Location: arch/x86/include/asm/resctrl_sched.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810562c0)
Location: arch/x86/include/asm/resctrl_sched.h:54
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:move_myself
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
```
**Symbols:**

```
ffffffff810562c0-ffffffff81056341: __resctrl_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __resctrl_sched_in();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102f6a6)
Location: arch/x86/include/asm/resctrl_sched.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81059880)
Location: arch/x86/include/asm/resctrl_sched.h:54
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:move_myself
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
```
**Symbols:**

```
ffffffff81059880-ffffffff81059900: __resctrl_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __resctrl_sched_in();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81030006)
Location: arch/x86/include/asm/resctrl_sched.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105a170)
Location: arch/x86/include/asm/resctrl_sched.h:54
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:move_myself
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
```
**Symbols:**

```
ffffffff8105a170-ffffffff8105a1f0: __resctrl_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate ⚠️</summary>

```c
void __resctrl_sched_in();
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81032380)
Location: arch/x86/include/asm/resctrl.h:54
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105f430)
Location: arch/x86/include/asm/resctrl.h:54
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:move_myself
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_cpu_closid_rmid
```
**Symbols:**

```
ffffffff81032380-ffffffff810323fd: __resctrl_sched_in (STB_LOCAL)
ffffffff8105f430-ffffffff8105f4ad: __resctrl_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate ⚠️</summary>

```c
void __resctrl_sched_in();
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81032de0)
Location: arch/x86/include/asm/resctrl.h:54
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105d740)
Location: arch/x86/include/asm/resctrl.h:54
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
```
**Symbols:**

```
ffffffff81032de0-ffffffff81032e5d: __resctrl_sched_in (STB_LOCAL)
ffffffff8105d740-ffffffff8105d7bd: __resctrl_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __resctrl_sched_in();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81034fd8)
Location: arch/x86/include/asm/resctrl.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105e070)
Location: arch/x86/include/asm/resctrl.h:54
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
```
**Symbols:**

```
ffffffff8105e070-ffffffff8105e0df: __resctrl_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __resctrl_sched_in();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8103a2e8)
Location: arch/x86/include/asm/resctrl.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81067810)
Location: arch/x86/include/asm/resctrl.h:54
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
```
**Symbols:**

```
ffffffff81067810-ffffffff81067879: __resctrl_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __resctrl_sched_in();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81041340)
Location: arch/x86/include/asm/resctrl.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810745a0)
Location: arch/x86/include/asm/resctrl.h:54
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
```
**Symbols:**

```
ffffffff810745a0-ffffffff8107463c: __resctrl_sched_in (STB_LOCAL)
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
In arch/x86/kernel/process_64.c (ffffffff8104aa90)
Location: arch/x86/include/asm/resctrl.h:52
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81088e32)
Location: arch/x86/include/asm/resctrl.h:52
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
In arch/x86/kernel/process_64.c (ffffffff8104b2d0)
Location: arch/x86/include/asm/resctrl.h:52
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108bd32)
Location: arch/x86/include/asm/resctrl.h:52
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_cpu_closid_rmid
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
In arch/x86/kernel/process_64.c (ffffffff81052540)
Location: arch/x86/include/asm/resctrl.h:52
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8109071c)
Location: arch/x86/include/asm/resctrl.h:52
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_cpu_closid_rmid
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
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __resctrl_sched_in();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81030166)
Location: arch/x86/include/asm/resctrl_sched.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81059cf0)
Location: arch/x86/include/asm/resctrl_sched.h:54
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:move_myself
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
```
**Symbols:**

```
ffffffff81059cf0-ffffffff81059d70: __resctrl_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __resctrl_sched_in();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8101fbc1)
Location: arch/x86/include/asm/resctrl_sched.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104af70)
Location: arch/x86/include/asm/resctrl_sched.h:54
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:move_myself
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
```
**Symbols:**

```
ffffffff8104af70-ffffffff8104b003: __resctrl_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __resctrl_sched_in();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102ffc6)
Location: arch/x86/include/asm/resctrl_sched.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105a120)
Location: arch/x86/include/asm/resctrl_sched.h:54
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:move_myself
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
```
**Symbols:**

```
ffffffff8105a120-ffffffff8105a1a0: __resctrl_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __resctrl_sched_in();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81030e16)
Location: arch/x86/include/asm/resctrl_sched.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b2c0)
Location: arch/x86/include/asm/resctrl_sched.h:54
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:move_myself
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
```
**Symbols:**

```
ffffffff8105b2c0-ffffffff8105b340: __resctrl_sched_in (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
