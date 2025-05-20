# Function: <code>rcu_read_lock_trace</code>

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
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff81222ad0)
Location: include/linux/rcupdate_trace.h:48
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable
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
In kernel/bpf/trampoline.c (ffffffff81227290)
Location: include/linux/rcupdate_trace.h:48
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable
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
In kernel/bpf/trampoline.c (ffffffff8125f390)
Location: include/linux/rcupdate_trace.h:48
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable
```
```
In net/bpf/test_run.c (ffffffff81b2bf1e)
Location: include/linux/rcupdate_trace.h:48
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
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
In kernel/bpf/bpf_iter.c (ffffffff8129a050)
Location: include/linux/rcupdate_trace.h:48
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
```
```
In kernel/bpf/trampoline.c (ffffffff812a9a60)
Location: include/linux/rcupdate_trace.h:48
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable
```
```
In net/bpf/test_run.c (ffffffff81cb6553)
Location: include/linux/rcupdate_trace.h:48
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
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
In kernel/trace/trace_uprobe.c (ffffffff812b7f3e)
Location: include/linux/rcupdate_trace.h:48
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/bpf/bpf_iter.c (ffffffff812f5f57)
Location: include/linux/rcupdate_trace.h:48
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
```
```
In kernel/bpf/trampoline.c (ffffffff81307e60)
Location: include/linux/rcupdate_trace.h:48
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable
  - kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable_recur
```
```
In net/bpf/test_run.c (ffffffff81e74a33)
Location: include/linux/rcupdate_trace.h:48
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
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
In kernel/trace/trace_uprobe.c (ffffffff812db56d)
Location: include/linux/rcupdate_trace.h:48
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/bpf/bpf_iter.c (ffffffff81323cf7)
Location: include/linux/rcupdate_trace.h:48
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
```
```
In kernel/bpf/trampoline.c (ffffffff81336d30)
Location: include/linux/rcupdate_trace.h:48
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable
  - kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable_recur
```
```
In net/bpf/test_run.c (ffffffff81ed0803)
Location: include/linux/rcupdate_trace.h:48
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
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
In kernel/trace/bpf_trace.c (ffffffff812e5769)
Location: include/linux/rcupdate_trace.h:48
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:uprobe_prog_run
```
```
In kernel/trace/trace_uprobe.c (ffffffff812f964e)
Location: include/linux/rcupdate_trace.h:48
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/bpf/bpf_iter.c (ffffffff81347c87)
Location: include/linux/rcupdate_trace.h:48
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
```
```
In kernel/bpf/trampoline.c (ffffffff8135cbb0)
Location: include/linux/rcupdate_trace.h:48
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable
  - kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable_recur
```
```
In net/bpf/test_run.c (ffffffff81f94163)
Location: include/linux/rcupdate_trace.h:48
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
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
