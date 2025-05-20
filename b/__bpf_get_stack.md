# Function: <code>__bpf_get_stack</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __bpf_get_stack(struct pt_regs *regs, struct task_struct *task, struct perf_callchain_entry *trace_in, void *buf, u32 size, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff81233c70)
Location: kernel/bpf/stackmap.c:567
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:bpf_get_stack_pe
  - kernel/bpf/stackmap.c:bpf_get_stack_pe
  - kernel/bpf/stackmap.c:bpf_get_stack_pe
  - kernel/bpf/stackmap.c:bpf_get_task_stack
  - kernel/bpf/stackmap.c:bpf_get_stack
```
**Symbols:**

```
ffffffff81233c70-ffffffff81233e7f: __bpf_get_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __bpf_get_stack(struct pt_regs *regs, struct task_struct *task, struct perf_callchain_entry *trace_in, void *buf, u32 size, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff81237a30)
Location: kernel/bpf/stackmap.c:432
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:bpf_get_stack_pe
  - kernel/bpf/stackmap.c:bpf_get_stack_pe
  - kernel/bpf/stackmap.c:bpf_get_stack_pe
  - kernel/bpf/stackmap.c:bpf_get_task_stack
  - kernel/bpf/stackmap.c:bpf_get_stack
```
**Symbols:**

```
ffffffff81237a30-ffffffff81237c3f: __bpf_get_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __bpf_get_stack(struct pt_regs *regs, struct task_struct *task, struct perf_callchain_entry *trace_in, void *buf, u32 size, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff81272000)
Location: kernel/bpf/stackmap.c:439
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:bpf_get_stack_pe
  - kernel/bpf/stackmap.c:bpf_get_stack_pe
  - kernel/bpf/stackmap.c:bpf_get_stack_pe
  - kernel/bpf/stackmap.c:bpf_get_task_stack
  - kernel/bpf/stackmap.c:bpf_get_stack
```
**Symbols:**

```
ffffffff81272000-ffffffff8127220f: __bpf_get_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __bpf_get_stack(struct pt_regs *regs, struct task_struct *task, struct perf_callchain_entry *trace_in, void *buf, u32 size, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff812c1190)
Location: kernel/bpf/stackmap.c:388
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:bpf_get_stack_pe
  - kernel/bpf/stackmap.c:bpf_get_stack_pe
  - kernel/bpf/stackmap.c:bpf_get_stack_pe
  - kernel/bpf/stackmap.c:bpf_get_task_stack
  - kernel/bpf/stackmap.c:bpf_get_stack
```
**Symbols:**

```
ffffffff812c1190-ffffffff812c13c7: __bpf_get_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __bpf_get_stack(struct pt_regs *regs, struct task_struct *task, struct perf_callchain_entry *trace_in, void *buf, u32 size, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff81324a60)
Location: kernel/bpf/stackmap.c:388
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:bpf_get_stack_pe
  - kernel/bpf/stackmap.c:bpf_get_stack_pe
  - kernel/bpf/stackmap.c:bpf_get_stack_pe
  - kernel/bpf/stackmap.c:bpf_get_task_stack
  - kernel/bpf/stackmap.c:bpf_get_stack
```
**Symbols:**

```
ffffffff81324a60-ffffffff81324c97: __bpf_get_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __bpf_get_stack(struct pt_regs *regs, struct task_struct *task, struct perf_callchain_entry *trace_in, void *buf, u32 size, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff81354cc0)
Location: kernel/bpf/stackmap.c:385
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:bpf_get_stack_pe
  - kernel/bpf/stackmap.c:bpf_get_stack_pe
  - kernel/bpf/stackmap.c:bpf_get_stack_pe
  - kernel/bpf/stackmap.c:bpf_get_task_stack
  - kernel/bpf/stackmap.c:bpf_get_stack
```
**Symbols:**

```
ffffffff81354cc0-ffffffff81354ef7: __bpf_get_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __bpf_get_stack(struct pt_regs *regs, struct task_struct *task, struct perf_callchain_entry *trace_in, void *buf, u32 size, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff8137d630)
Location: kernel/bpf/stackmap.c:385
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:bpf_get_stack_pe
  - kernel/bpf/stackmap.c:bpf_get_stack_pe
  - kernel/bpf/stackmap.c:bpf_get_stack_pe
  - kernel/bpf/stackmap.c:bpf_get_task_stack
  - kernel/bpf/stackmap.c:bpf_get_stack
```
**Symbols:**

```
ffffffff8137d630-ffffffff8137d8d0: __bpf_get_stack (STB_LOCAL)
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
