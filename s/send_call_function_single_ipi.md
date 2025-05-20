# Function: <code>send_call_function_single_ipi</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void send_call_function_single_ipi(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e3ea0)
Location: kernel/sched/core.c:2391
Inline: False
Direct callers:
  - kernel/smp.c:generic_exec_single
```
**Symbols:**

```
ffffffff810e3ea0-ffffffff810e3f4f: send_call_function_single_ipi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void send_call_function_single_ipi(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e18d0)
Location: kernel/sched/core.c:3070
Inline: False
Direct callers:
  - kernel/smp.c:generic_exec_single
```
**Symbols:**

```
ffffffff810e18d0-ffffffff810e1960: send_call_function_single_ipi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void send_call_function_single_ipi(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e36e0)
Location: kernel/sched/core.c:3091
Inline: False
Direct callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:generic_exec_single
```
**Symbols:**

```
ffffffff810e36e0-ffffffff810e3770: send_call_function_single_ipi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void send_call_function_single_ipi(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810fa230)
Location: kernel/sched/core.c:3658
Inline: False
Direct callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:generic_exec_single
```
**Symbols:**

```
ffffffff810fa230-ffffffff810fa2f6: send_call_function_single_ipi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void send_call_function_single_ipi(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81116820)
Location: kernel/sched/core.c:3757
Inline: False
Direct callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:generic_exec_single
```
**Symbols:**

```
ffffffff81116820-ffffffff81116910: send_call_function_single_ipi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void send_call_function_single_ipi(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8113dd40)
Location: kernel/sched/core.c:3821
Inline: False
Direct callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:generic_exec_single
```
**Symbols:**

```
ffffffff8113dd40-ffffffff8113de23: send_call_function_single_ipi (STB_GLOBAL)
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
In kernel/smp.c (ffffffff8120e1db)
Location: kernel/smp.c:110
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:__smp_call_single_queue
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
In kernel/smp.c (ffffffff8122596b)
Location: kernel/smp.c:112
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:__smp_call_single_queue
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
</ul>
