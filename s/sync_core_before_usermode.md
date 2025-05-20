# Function: <code>sync_core_before_usermode</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bb640)
Location: arch/x86/include/asm/sync_core.h:14
Inline: True
Inline callers:
  - kernel/sched/core.c:finish_task_switch
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
In kernel/sched/core.c (ffffffff810c4bdf)
Location: arch/x86/include/asm/sync_core.h:14
Inline: True
Inline callers:
  - kernel/sched/core.c:finish_task_switch
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
In kernel/sched/core.c (ffffffff810ca7d3)
Location: arch/x86/include/asm/sync_core.h:14
Inline: True
Inline callers:
  - kernel/sched/core.c:finish_task_switch
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
In kernel/sched/core.c (ffffffff810d3d7a)
Location: arch/x86/include/asm/sync_core.h:14
Inline: True
Inline callers:
  - kernel/sched/core.c:finish_task_switch
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
In kernel/sched/core.c (ffffffff810df113)
Location: arch/x86/include/asm/sync_core.h:14
Inline: True
Inline callers:
  - kernel/sched/core.c:finish_task_switch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void sync_core_before_usermode();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d6b00)
Location: arch/x86/include/asm/sync_core.h:96
Inline: False
```
```
In kernel/sched/membarrier.c (ffffffff81108acb)
Location: arch/x86/include/asm/sync_core.h:96
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:ipi_sync_core
```
**Symbols:**

```
ffffffff810d6b00-ffffffff810d6b2a: sync_core_before_usermode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void sync_core_before_usermode();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d87d0)
Location: arch/x86/include/asm/sync_core.h:96
Inline: False
```
```
In kernel/sched/membarrier.c (ffffffff8110a9ab)
Location: arch/x86/include/asm/sync_core.h:96
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:ipi_sync_core
```
**Symbols:**

```
ffffffff810d87d0-ffffffff810d8801: sync_core_before_usermode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void sync_core_before_usermode();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ec060)
Location: arch/x86/include/asm/sync_core.h:96
Inline: False
```
```
In kernel/sched/membarrier.c (ffffffff8112913b)
Location: arch/x86/include/asm/sync_core.h:96
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:ipi_sync_core
```
**Symbols:**

```
ffffffff810ec060-ffffffff810ec091: sync_core_before_usermode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void sync_core_before_usermode();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81106510)
Location: arch/x86/include/asm/sync_core.h:96
Inline: False
```
```
In kernel/sched/build_utility.c (ffffffff8113c08b)
Location: arch/x86/include/asm/sync_core.h:96
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:ipi_sync_core
```
**Symbols:**

```
ffffffff81106510-ffffffff81106552: sync_core_before_usermode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void sync_core_before_usermode();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8112c1d0)
Location: arch/x86/include/asm/sync_core.h:96
Inline: False
```
```
In kernel/sched/build_utility.c (ffffffff81166cab)
Location: arch/x86/include/asm/sync_core.h:96
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:ipi_sync_core
```
**Symbols:**

```
ffffffff8112c1d0-ffffffff8112c212: sync_core_before_usermode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void sync_core_before_usermode();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811392d0)
Location: arch/x86/include/asm/sync_core.h:96
Inline: False
```
```
In kernel/sched/build_utility.c (ffffffff8117711b)
Location: arch/x86/include/asm/sync_core.h:96
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:ipi_sync_core
```
**Symbols:**

```
ffffffff811392d0-ffffffff81139312: sync_core_before_usermode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void sync_core_before_usermode();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811440d0)
Location: arch/x86/include/asm/sync_core.h:96
Inline: False
```
```
In kernel/sched/build_utility.c (ffffffff8118508b)
Location: arch/x86/include/asm/sync_core.h:96
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:ipi_sync_core
```
**Symbols:**

```
ffffffff811440d0-ffffffff81144112: sync_core_before_usermode (STB_LOCAL)
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
In kernel/sched/core.c (0)
Location: include/linux/sync_core.h:15
Inline: True
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
In kernel/sched/core.c (0)
Location: include/linux/sync_core.h:15
Inline: True
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
In kernel/sched/core.c (0)
Location: include/linux/sync_core.h:15
Inline: True
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
In kernel/sched/core.c (0)
Location: include/linux/sync_core.h:15
Inline: True
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
In kernel/sched/core.c (ffffffff810ce06a)
Location: arch/x86/include/asm/sync_core.h:14
Inline: True
Inline callers:
  - kernel/sched/core.c:finish_task_switch
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
In kernel/sched/core.c (ffffffff810bc932)
Location: arch/x86/include/asm/sync_core.h:14
Inline: True
Inline callers:
  - kernel/sched/core.c:finish_task_switch
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
In kernel/sched/core.c (ffffffff810cd49a)
Location: arch/x86/include/asm/sync_core.h:14
Inline: True
Inline callers:
  - kernel/sched/core.c:finish_task_switch
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
In kernel/sched/core.c (ffffffff810d47e4)
Location: arch/x86/include/asm/sync_core.h:14
Inline: True
Inline callers:
  - kernel/sched/core.c:finish_task_switch
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
