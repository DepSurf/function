# Function: <code>irq_work_is_busy</code>

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
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e6b63)
Location: include/linux/irq_work.h:44
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
```
```
In kernel/irq_work.c (ffffffff811f5eb4)
Location: include/linux/irq_work.h:44
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_sync
```
```
In kernel/bpf/stackmap.c (ffffffff8123349c)
Location: include/linux/irq_work.h:44
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
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
In kernel/trace/bpf_trace.c (ffffffff811e7e03)
Location: include/linux/irq_work.h:44
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
```
```
In kernel/irq_work.c (ffffffff811f6da0)
Location: include/linux/irq_work.h:44
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_sync
```
```
In kernel/bpf/stackmap.c (ffffffff8123725c)
Location: include/linux/irq_work.h:44
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
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
In kernel/trace/bpf_trace.c (ffffffff81218a83)
Location: include/linux/irq_work.h:44
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
```
```
In kernel/irq_work.c (ffffffff81228370)
Location: include/linux/irq_work.h:44
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_sync
```
```
In kernel/bpf/stackmap.c (ffffffff8127183c)
Location: include/linux/irq_work.h:44
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
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
In kernel/trace/bpf_trace.c (ffffffff81256de3)
Location: include/linux/irq_work.h:47
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
```
```
In kernel/irq_work.c (ffffffff8126935f)
Location: include/linux/irq_work.h:47
Inline: True
```
```
In kernel/bpf/task_iter.c (ffffffff8129a5bf)
Location: include/linux/irq_work.h:47
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:bpf_find_vma
```
```
In kernel/bpf/stackmap.c (ffffffff812c095f)
Location: include/linux/irq_work.h:47
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
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
In kernel/trace/bpf_trace.c (ffffffff812a6c57)
Location: include/linux/irq_work.h:47
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
```
```
In kernel/irq_work.c (ffffffff812be19f)
Location: include/linux/irq_work.h:47
Inline: True
```
```
In kernel/bpf/task_iter.c (ffffffff812f6756)
Location: include/linux/irq_work.h:47
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:bpf_find_vma
```
```
In kernel/bpf/stackmap.c (ffffffff813241ff)
Location: include/linux/irq_work.h:47
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
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
In kernel/trace/bpf_trace.c (ffffffff812c8d17)
Location: include/linux/irq_work.h:47
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
```
```
In kernel/irq_work.c (ffffffff812e4d5f)
Location: include/linux/irq_work.h:47
Inline: True
```
```
In kernel/bpf/task_iter.c (ffffffff81324629)
Location: include/linux/irq_work.h:47
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:bpf_find_vma
```
```
In kernel/bpf/stackmap.c (ffffffff8135443f)
Location: include/linux/irq_work.h:47
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
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
In kernel/trace/bpf_trace.c (ffffffff812e5ce7)
Location: include/linux/irq_work.h:47
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
```
```
In kernel/irq_work.c (ffffffff81302e0f)
Location: include/linux/irq_work.h:47
Inline: True
```
```
In kernel/bpf/task_iter.c (ffffffff81349875)
Location: include/linux/irq_work.h:47
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:bpf_iter_task_vma_new
  - kernel/bpf/task_iter.c:bpf_find_vma
```
```
In kernel/bpf/stackmap.c (ffffffff8137cdaf)
Location: include/linux/irq_work.h:47
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
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
