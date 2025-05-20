# Function: <code>is_syscall_trace_event</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811bef17)
Location: include/linux/syscalls.h:177
Inline: True
Inline callers:
  - kernel/events/core.c:perf_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811a5f95)
Location: include/linux/syscalls.h:190
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
```
In kernel/events/core.c (ffffffff811df2cc)
Location: include/linux/syscalls.h:190
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b4345)
Location: include/linux/syscalls.h:191
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
```
In kernel/events/core.c (ffffffff811ef715)
Location: include/linux/syscalls.h:191
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
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
In kernel/trace/bpf_trace.c (ffffffff811c3361)
Location: include/linux/syscalls.h:191
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
```
In kernel/events/core.c (ffffffff81206fc7)
Location: include/linux/syscalls.h:191
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
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
In kernel/trace/bpf_trace.c (ffffffff811ceb11)
Location: include/linux/syscalls.h:191
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
```
In kernel/events/core.c (ffffffff81214337)
Location: include/linux/syscalls.h:191
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
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
In kernel/trace/bpf_trace.c (ffffffff811eb031)
Location: include/linux/syscalls.h:191
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
```
In kernel/events/core.c (ffffffff812312ae)
Location: include/linux/syscalls.h:191
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_bpf_prog
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
In kernel/trace/bpf_trace.c (ffffffff811e91d1)
Location: include/linux/syscalls.h:190
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
```
In kernel/events/core.c (ffffffff8123af08)
Location: include/linux/syscalls.h:190
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_bpf_prog
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
In kernel/trace/bpf_trace.c (ffffffff811ea0c1)
Location: include/linux/syscalls.h:193
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
```
In kernel/events/core.c (ffffffff8123f6c8)
Location: include/linux/syscalls.h:193
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_bpf_prog
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
In kernel/trace/bpf_trace.c (ffffffff8121aef1)
Location: include/linux/syscalls.h:193
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
```
In kernel/events/core.c (ffffffff8128c564)
Location: include/linux/syscalls.h:193
Inline: True
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
In kernel/trace/bpf_trace.c (ffffffff81259c44)
Location: include/linux/syscalls.h:194
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
```
In kernel/events/core.c (ffffffff812e114d)
Location: include/linux/syscalls.h:194
Inline: True
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
In kernel/trace/bpf_trace.c (ffffffff812a9ee4)
Location: include/linux/syscalls.h:194
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
```
In kernel/events/core.c (ffffffff81349670)
Location: include/linux/syscalls.h:194
Inline: True
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
In kernel/trace/bpf_trace.c (ffffffff812cc753)
Location: include/linux/syscalls.h:196
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
```
In kernel/events/core.c (ffffffff8137a680)
Location: include/linux/syscalls.h:196
Inline: True
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
In kernel/trace/bpf_trace.c (ffffffff812e9bd3)
Location: include/linux/syscalls.h:200
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
```
In kernel/events/core.c (ffffffff813a3880)
Location: include/linux/syscalls.h:200
Inline: True
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
In kernel/trace/bpf_trace.c (ffff80001024edfc)
Location: include/linux/syscalls.h:191
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
```
In kernel/events/core.c (ffff80001029e368)
Location: include/linux/syscalls.h:191
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
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
In kernel/trace/bpf_trace.c (c0481d48)
Location: include/linux/syscalls.h:191
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
```
In kernel/events/core.c (c04cdb60)
Location: include/linux/syscalls.h:191
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
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
In kernel/trace/bpf_trace.c (c0000000002eb454)
Location: include/linux/syscalls.h:191
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
```
In kernel/events/core.c (c00000000034f2a4)
Location: include/linux/syscalls.h:191
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
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
In kernel/events/core.c (ffffffe0001c9012)
Location: include/linux/syscalls.h:191
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
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
In kernel/trace/bpf_trace.c (ffffffff811c7131)
Location: include/linux/syscalls.h:191
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
```
In kernel/events/core.c (ffffffff8120c987)
Location: include/linux/syscalls.h:191
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
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
In kernel/trace/bpf_trace.c (ffffffff811b9f11)
Location: include/linux/syscalls.h:191
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
```
In kernel/events/core.c (ffffffff811ff757)
Location: include/linux/syscalls.h:191
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
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
In kernel/trace/bpf_trace.c (ffffffff811c4f01)
Location: include/linux/syscalls.h:191
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
```
In kernel/events/core.c (ffffffff8120a727)
Location: include/linux/syscalls.h:191
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
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
In kernel/trace/bpf_trace.c (ffffffff811d3161)
Location: include/linux/syscalls.h:191
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
```
In kernel/events/core.c (ffffffff812194fa)
Location: include/linux/syscalls.h:191
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
```
</details>
</li>
</ul>

## Differences
