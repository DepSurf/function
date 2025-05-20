# Function: <code>ptrace_register_breakpoint</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct perf_event *ptrace_register_breakpoint(struct task_struct *tsk, int len, int type, long unsigned int addr, bool disabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103bbf0)
Location: arch/x86/kernel/ptrace.c:612
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr
```
**Symbols:**

```
ffffffff8103bbf0-ffffffff8103bccc: ptrace_register_breakpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct perf_event *ptrace_register_breakpoint(struct task_struct *tsk, int len, int type, long unsigned int addr, bool disabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103b9d0)
Location: arch/x86/kernel/ptrace.c:565
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr
```
**Symbols:**

```
ffffffff8103b9d0-ffffffff8103baac: ptrace_register_breakpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct perf_event *ptrace_register_breakpoint(struct task_struct *tsk, int len, int type, long unsigned int addr, bool disabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103b1c0)
Location: arch/x86/kernel/ptrace.c:565
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr
```
**Symbols:**

```
ffffffff8103b1c0-ffffffff8103b29c: ptrace_register_breakpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct perf_event *ptrace_register_breakpoint(struct task_struct *tsk, int len, int type, long unsigned int addr, bool disabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81039210)
Location: arch/x86/kernel/ptrace.c:566
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr
```
**Symbols:**

```
ffffffff81039210-ffffffff810392ef: ptrace_register_breakpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct perf_event *ptrace_register_breakpoint(struct task_struct *tsk, int len, int type, long unsigned int addr, bool disabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103bc10)
Location: arch/x86/kernel/ptrace.c:566
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr
```
**Symbols:**

```
ffffffff8103bc10-ffffffff8103bcef: ptrace_register_breakpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct perf_event *ptrace_register_breakpoint(struct task_struct *tsk, int len, int type, long unsigned int addr, bool disabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103d0f0)
Location: arch/x86/kernel/ptrace.c:566
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr
```
**Symbols:**

```
ffffffff8103d0f0-ffffffff8103d1d1: ptrace_register_breakpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct perf_event *ptrace_register_breakpoint(struct task_struct *tsk, int len, int type, long unsigned int addr, bool disabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103e620)
Location: arch/x86/kernel/ptrace.c:557
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr
```
**Symbols:**

```
ffffffff8103e620-ffffffff8103e701: ptrace_register_breakpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct perf_event *ptrace_register_breakpoint(struct task_struct *tsk, int len, int type, long unsigned int addr, bool disabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81040d20)
Location: arch/x86/kernel/ptrace.c:531
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr
```
**Symbols:**

```
ffffffff81040d20-ffffffff81040df8: ptrace_register_breakpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct perf_event *ptrace_register_breakpoint(struct task_struct *tsk, int len, int type, long unsigned int addr, bool disabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff810414b0)
Location: arch/x86/kernel/ptrace.c:531
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr
```
**Symbols:**

```
ffffffff810414b0-ffffffff81041588: ptrace_register_breakpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct perf_event *ptrace_register_breakpoint(struct task_struct *tsk, int len, int type, long unsigned int addr, bool disabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81044860)
Location: arch/x86/kernel/ptrace.c:543
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr
  - arch/x86/kernel/ptrace.c:ptrace_write_dr7
```
**Symbols:**

```
ffffffff81044860-ffffffff81044941: ptrace_register_breakpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct perf_event *ptrace_register_breakpoint(struct task_struct *tsk, int len, int type, long unsigned int addr, bool disabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81044330)
Location: arch/x86/kernel/ptrace.c:508
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr
  - arch/x86/kernel/ptrace.c:ptrace_write_dr7
```
**Symbols:**

```
ffffffff81044330-ffffffff81044411: ptrace_register_breakpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct perf_event *ptrace_register_breakpoint(struct task_struct *tsk, int len, int type, long unsigned int addr, bool disabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81045f70)
Location: arch/x86/kernel/ptrace.c:508
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr
```
**Symbols:**

```
ffffffff81045f70-ffffffff81046054: ptrace_register_breakpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct perf_event *ptrace_register_breakpoint(struct task_struct *tsk, int len, int type, long unsigned int addr, bool disabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8104c600)
Location: arch/x86/kernel/ptrace.c:508
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr
```
**Symbols:**

```
ffffffff8104c600-ffffffff8104c6e4: ptrace_register_breakpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct perf_event *ptrace_register_breakpoint(struct task_struct *tsk, int len, int type, long unsigned int addr, bool disabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81057690)
Location: arch/x86/kernel/ptrace.c:507
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr
```
**Symbols:**

```
ffffffff81057690-ffffffff81057798: ptrace_register_breakpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct perf_event *ptrace_register_breakpoint(struct task_struct *tsk, int len, int type, long unsigned int addr, bool disabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81064e50)
Location: arch/x86/kernel/ptrace.c:526
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr
```
**Symbols:**

```
ffffffff81064e50-ffffffff81064f58: ptrace_register_breakpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct perf_event *ptrace_register_breakpoint(struct task_struct *tsk, int len, int type, long unsigned int addr, bool disabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81066740)
Location: arch/x86/kernel/ptrace.c:526
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr
```
**Symbols:**

```
ffffffff81066740-ffffffff81066848: ptrace_register_breakpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct perf_event *ptrace_register_breakpoint(struct task_struct *tsk, int len, int type, long unsigned int addr, bool disabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8106dbc0)
Location: arch/x86/kernel/ptrace.c:527
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr
```
**Symbols:**

```
ffffffff8106dbc0-ffffffff8106dcc8: ptrace_register_breakpoint (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
struct perf_event *ptrace_register_breakpoint(struct task_struct *tsk, int len, int type, long unsigned int addr, bool disabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81041630)
Location: arch/x86/kernel/ptrace.c:531
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr
```
**Symbols:**

```
ffffffff81041630-ffffffff81041708: ptrace_register_breakpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct perf_event *ptrace_register_breakpoint(struct task_struct *tsk, int len, int type, long unsigned int addr, bool disabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81030cf0)
Location: arch/x86/kernel/ptrace.c:531
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr
```
**Symbols:**

```
ffffffff81030cf0-ffffffff81030dc8: ptrace_register_breakpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct perf_event *ptrace_register_breakpoint(struct task_struct *tsk, int len, int type, long unsigned int addr, bool disabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81041470)
Location: arch/x86/kernel/ptrace.c:531
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr
```
**Symbols:**

```
ffffffff81041470-ffffffff81041548: ptrace_register_breakpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct perf_event *ptrace_register_breakpoint(struct task_struct *tsk, int len, int type, long unsigned int addr, bool disabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81042850)
Location: arch/x86/kernel/ptrace.c:531
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr
```
**Symbols:**

```
ffffffff81042850-ffffffff81042928: ptrace_register_breakpoint (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
