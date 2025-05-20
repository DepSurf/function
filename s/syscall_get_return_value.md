# Function: <code>syscall_get_return_value</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (0)
Location: arch/x86/include/asm/syscall.h:73
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (0)
Location: arch/x86/include/asm/syscall.h:73
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (0)
Location: arch/x86/include/asm/syscall.h:73
Inline: True
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
In kernel/trace/trace_syscalls.c (0)
Location: arch/x86/include/asm/syscall.h:73
Inline: True
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
In kernel/trace/trace_syscalls.c (0)
Location: arch/x86/include/asm/syscall.h:73
Inline: True
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
In kernel/trace/trace_syscalls.c (ffffffff81196841)
Location: arch/x86/include/asm/syscall.h:77
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
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
In kernel/trace/trace_syscalls.c (ffffffff811a4981)
Location: arch/x86/include/asm/syscall.h:77
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
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
In kernel/ptrace.c (ffffffff810a6c9d)
Location: arch/x86/include/asm/syscall.h:74
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
```
```
In kernel/trace/trace_syscalls.c (ffffffff811b28d3)
Location: arch/x86/include/asm/syscall.h:74
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
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
In kernel/ptrace.c (ffffffff810ad580)
Location: arch/x86/include/asm/syscall.h:78
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
```
```
In kernel/trace/trace_syscalls.c (ffffffff811bdec3)
Location: arch/x86/include/asm/syscall.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
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
In kernel/ptrace.c (ffffffff810b4d86)
Location: arch/x86/include/asm/syscall.h:69
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
```
```
In kernel/trace/trace_syscalls.c (ffffffff811d7c68)
Location: arch/x86/include/asm/syscall.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
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
In kernel/ptrace.c (ffffffff810aff66)
Location: arch/x86/include/asm/syscall.h:69
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
```
```
In kernel/entry/common.c (ffffffff8113b8c8)
Location: arch/x86/include/asm/syscall.h:69
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
```
In kernel/trace/trace_syscalls.c (ffffffff811d4d38)
Location: arch/x86/include/asm/syscall.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
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
In kernel/ptrace.c (ffffffff810b14f7)
Location: arch/x86/include/asm/syscall.h:69
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
```
```
In kernel/entry/common.c (ffffffff8113cb9d)
Location: arch/x86/include/asm/syscall.h:69
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
```
In kernel/trace/trace_syscalls.c (ffffffff811d6588)
Location: arch/x86/include/asm/syscall.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
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
In kernel/ptrace.c (ffffffff810c37d7)
Location: arch/x86/include/asm/syscall.h:68
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
```
```
In kernel/entry/common.c (ffffffff8115fcbd)
Location: arch/x86/include/asm/syscall.h:68
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
```
In kernel/trace/trace_syscalls.c (ffffffff81203418)
Location: arch/x86/include/asm/syscall.h:68
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
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
In kernel/ptrace.c (ffffffff810daf50)
Location: arch/x86/include/asm/syscall.h:68
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
```
```
In kernel/entry/common.c (ffffffff8118a1ce)
Location: arch/x86/include/asm/syscall.h:68
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
```
In kernel/trace/trace_syscalls.c (ffffffff8123e240)
Location: arch/x86/include/asm/syscall.h:68
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
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
In kernel/ptrace.c (ffffffff810fb085)
Location: arch/x86/include/asm/syscall.h:68
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
```
```
In kernel/entry/common.c (ffffffff811c670e)
Location: arch/x86/include/asm/syscall.h:68
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
```
In kernel/trace/trace_syscalls.c (ffffffff8128bc0d)
Location: arch/x86/include/asm/syscall.h:68
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
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
In kernel/ptrace.c (ffffffff81106fc5)
Location: arch/x86/include/asm/syscall.h:68
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
```
```
In kernel/entry/common.c (ffffffff811d932e)
Location: arch/x86/include/asm/syscall.h:68
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
```
In kernel/trace/trace_syscalls.c (ffffffff812a8b1d)
Location: arch/x86/include/asm/syscall.h:68
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
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
In kernel/ptrace.c (ffffffff81110915)
Location: arch/x86/include/asm/syscall.h:66
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
```
```
In kernel/entry/common.c (ffffffff811eec6e)
Location: arch/x86/include/asm/syscall.h:66
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
```
In kernel/trace/trace_syscalls.c (ffffffff812c4825)
Location: arch/x86/include/asm/syscall.h:66
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (0)
Location: arch/arm64/include/asm/syscall.h:40
Inline: True
```
```
In kernel/trace/trace_syscalls.c (ffff80001023d9a8)
Location: arch/arm64/include/asm/syscall.h:40
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (0)
Location: arch/arm/include/asm/syscall.h:41
Inline: True
```
```
In kernel/trace/trace_syscalls.c (c0478a14)
Location: arch/arm/include/asm/syscall.h:41
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (c00000000014e238)
Location: arch/powerpc/include/asm/syscall.h:48
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
```
```
In kernel/trace/trace_syscalls.c (c0000000002cc76c)
Location: arch/powerpc/include/asm/syscall.h:48
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (0)
Location: arch/riscv/include/asm/syscall.h:52
Inline: True
```
```
In kernel/trace/trace_syscalls.c (ffffffe00019327a)
Location: arch/riscv/include/asm/syscall.h:52
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
```
</details>
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
In kernel/ptrace.c (ffffffff810a78f0)
Location: arch/x86/include/asm/syscall.h:78
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
```
```
In kernel/trace/trace_syscalls.c (ffffffff811b64e3)
Location: arch/x86/include/asm/syscall.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
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
In kernel/ptrace.c (ffffffff810962d0)
Location: arch/x86/include/asm/syscall.h:78
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
```
```
In kernel/trace/trace_syscalls.c (ffffffff811a92e3)
Location: arch/x86/include/asm/syscall.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
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
In kernel/ptrace.c (ffffffff810a6e50)
Location: arch/x86/include/asm/syscall.h:78
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
```
```
In kernel/trace/trace_syscalls.c (ffffffff811b42b3)
Location: arch/x86/include/asm/syscall.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
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
In kernel/ptrace.c (ffffffff810af120)
Location: arch/x86/include/asm/syscall.h:78
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
```
```
In kernel/trace/trace_syscalls.c (ffffffff811c2353)
Location: arch/x86/include/asm/syscall.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
```
</details>
</li>
</ul>

## Differences
