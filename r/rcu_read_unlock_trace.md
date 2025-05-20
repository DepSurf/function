# Function: <code>rcu_read_unlock_trace</code>

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
In kernel/bpf/trampoline.c (ffffffff81222af0)
Location: include/linux/rcupdate_trace.h:69
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable
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
In kernel/bpf/trampoline.c (ffffffff81227329)
Location: include/linux/rcupdate_trace.h:69
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable
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
In kernel/bpf/trampoline.c (ffffffff8125f429)
Location: include/linux/rcupdate_trace.h:69
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable
```
```
In net/bpf/test_run.c (ffffffff81b2bf5c)
Location: include/linux/rcupdate_trace.h:69
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
In kernel/bpf/bpf_iter.c (ffffffff8129a08a)
Location: include/linux/rcupdate_trace.h:69
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
```
```
In kernel/bpf/trampoline.c (ffffffff812a9b50)
Location: include/linux/rcupdate_trace.h:69
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable
```
```
In net/bpf/test_run.c (ffffffff81cb6591)
Location: include/linux/rcupdate_trace.h:69
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
In kernel/trace/trace_uprobe.c (ffffffff812b8011)
Location: include/linux/rcupdate_trace.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/bpf/bpf_iter.c (ffffffff812f5fb5)
Location: include/linux/rcupdate_trace.h:69
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
```
```
In kernel/bpf/trampoline.c (ffffffff81308723)
Location: include/linux/rcupdate_trace.h:69
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable_recur
```
```
In net/bpf/test_run.c (ffffffff81e74a71)
Location: include/linux/rcupdate_trace.h:69
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
In kernel/trace/trace_uprobe.c (ffffffff812db642)
Location: include/linux/rcupdate_trace.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/bpf/bpf_iter.c (ffffffff81323d57)
Location: include/linux/rcupdate_trace.h:69
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
```
```
In kernel/bpf/trampoline.c (ffffffff813376b2)
Location: include/linux/rcupdate_trace.h:69
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable_recur
```
```
In net/bpf/test_run.c (ffffffff81ed0841)
Location: include/linux/rcupdate_trace.h:69
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
In kernel/trace/bpf_trace.c (ffffffff812e57d3)
Location: include/linux/rcupdate_trace.h:69
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:uprobe_prog_run
```
```
In kernel/trace/trace_uprobe.c (ffffffff812f9721)
Location: include/linux/rcupdate_trace.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/bpf/bpf_iter.c (ffffffff81347ce7)
Location: include/linux/rcupdate_trace.h:69
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
```
```
In kernel/bpf/trampoline.c (ffffffff8135d4f2)
Location: include/linux/rcupdate_trace.h:69
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable_recur
```
```
In net/bpf/test_run.c (ffffffff81f941a1)
Location: include/linux/rcupdate_trace.h:69
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
