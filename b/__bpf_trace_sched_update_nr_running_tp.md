# Function: <code>__bpf_trace_sched_update_nr_running_tp</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_trace_sched_update_nr_running_tp(void *__data, struct rq *rq, int change);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: include/trace/events/sched.h:733
Inline: False
```
**Symbols:**

```
ffffffff810db170-ffffffff810db17d: __bpf_trace_sched_update_nr_running_tp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_trace_sched_update_nr_running_tp(void *__data, struct rq *rq, int change);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: include/trace/events/sched.h:731
Inline: False
```
**Symbols:**

```
ffffffff810eef50-ffffffff810eef5d: __bpf_trace_sched_update_nr_running_tp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_sched_update_nr_running_tp(void *__data, struct rq *rq, int change);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: include/trace/events/sched.h:734
Inline: False
```
**Symbols:**

```
ffffffff8110c1c0-ffffffff8110c1d7: __bpf_trace_sched_update_nr_running_tp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_sched_update_nr_running_tp(void *__data, struct rq *rq, int change);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: include/trace/events/sched.h:734
Inline: False
```
**Symbols:**

```
ffffffff811326b0-ffffffff811326c7: __bpf_trace_sched_update_nr_running_tp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_trace_sched_update_nr_running_tp(void *__data, struct rq *rq, int change);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: include/trace/events/sched.h:734
Inline: False
```
**Symbols:**

```
ffffffff81140900-ffffffff81140917: __bpf_trace_sched_update_nr_running_tp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_sched_update_nr_running_tp(void *__data, struct rq *rq, int change);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: include/trace/events/sched.h:783
Inline: False
```
**Symbols:**

```
ffffffff8114b9d0-ffffffff8114b9e7: __bpf_trace_sched_update_nr_running_tp (STB_LOCAL)
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
