# Function: <code>__bpf_trace_sys_enter</code>

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
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_sys_enter(void *__data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81003880)
Location: include/trace/events/syscalls.h:18
Inline: True
```
**Symbols:**

```
ffffffff81003880-ffffffff8100388b: __bpf_trace_sys_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_sys_enter(void *__data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81003910)
Location: include/trace/events/syscalls.h:18
Inline: True
```
**Symbols:**

```
ffffffff81003910-ffffffff8100391b: __bpf_trace_sys_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_sys_enter(void *__data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81003a50)
Location: include/trace/events/syscalls.h:18
Inline: False
```
**Symbols:**

```
ffffffff81003a50-ffffffff81003a5b: __bpf_trace_sys_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_sys_enter(void *__data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81003a50)
Location: include/trace/events/syscalls.h:18
Inline: False
```
**Symbols:**

```
ffffffff81003a50-ffffffff81003a5b: __bpf_trace_sys_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_sys_enter(void *__data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81004d10)
Location: include/trace/events/syscalls.h:18
Inline: True
```
**Symbols:**

```
ffffffff81004d10-ffffffff81004d1b: __bpf_trace_sys_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_sys_enter(void *__data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff8113b350)
Location: include/trace/events/syscalls.h:18
Inline: True
```
**Symbols:**

```
ffffffff8113b350-ffffffff8113b35b: __bpf_trace_sys_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_sys_enter(void *__data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff8113c630)
Location: include/trace/events/syscalls.h:18
Inline: True
```
**Symbols:**

```
ffffffff8113c630-ffffffff8113c63b: __bpf_trace_sys_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_sys_enter(void *__data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff8115f750)
Location: include/trace/events/syscalls.h:18
Inline: True
```
**Symbols:**

```
ffffffff8115f750-ffffffff8115f75b: __bpf_trace_sys_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_sys_enter(void *__data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff81189c70)
Location: include/trace/events/syscalls.h:18
Inline: True
```
**Symbols:**

```
ffffffff81189c70-ffffffff81189c85: __bpf_trace_sys_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_sys_enter(void *__data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff811c6150)
Location: include/trace/events/syscalls.h:18
Inline: True
```
**Symbols:**

```
ffffffff811c6150-ffffffff811c6165: __bpf_trace_sys_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_sys_enter(void *__data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff811d8d50)
Location: include/trace/events/syscalls.h:18
Inline: True
```
**Symbols:**

```
ffffffff811d8d50-ffffffff811d8d65: __bpf_trace_sys_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_sys_enter(void *__data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff811ee860)
Location: include/trace/events/syscalls.h:18
Inline: True
```
**Symbols:**

```
ffffffff811ee860-ffffffff811ee875: __bpf_trace_sys_enter (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_sys_enter(void *__data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/ptrace.c (ffff800010089d50)
Location: include/trace/events/syscalls.h:18
Inline: True
```
**Symbols:**

```
ffff800010089d50-ffff800010089d64: __bpf_trace_sys_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_sys_enter(void *__data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/ptrace.c (c030b918)
Location: include/trace/events/syscalls.h:18
Inline: False
```
**Symbols:**

```
c030b918-c030b940: __bpf_trace_sys_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_sys_enter(void *__data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/ptrace.c (c000000000011a70)
Location: include/trace/events/syscalls.h:18
Inline: False
```
**Symbols:**

```
c000000000011a70-c000000000011a9c: __bpf_trace_sys_enter (STB_LOCAL)
```
</details>
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
void __bpf_trace_sys_enter(void *__data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81003a50)
Location: include/trace/events/syscalls.h:18
Inline: False
```
**Symbols:**

```
ffffffff81003a50-ffffffff81003a5b: __bpf_trace_sys_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_sys_enter(void *__data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81001f30)
Location: include/trace/events/syscalls.h:18
Inline: False
```
**Symbols:**

```
ffffffff81001f30-ffffffff81001f3b: __bpf_trace_sys_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_sys_enter(void *__data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81003a50)
Location: include/trace/events/syscalls.h:18
Inline: False
```
**Symbols:**

```
ffffffff81003a50-ffffffff81003a5b: __bpf_trace_sys_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_sys_enter(void *__data, struct pt_regs *regs, long int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81003b20)
Location: include/trace/events/syscalls.h:18
Inline: False
```
**Symbols:**

```
ffffffff81003b20-ffffffff81003b2b: __bpf_trace_sys_enter (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
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
