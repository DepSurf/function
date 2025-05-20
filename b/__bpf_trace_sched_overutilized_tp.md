# Function: <code>__bpf_trace_sched_overutilized_tp</code>

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
void __bpf_trace_sched_overutilized_tp(void *__data, struct root_domain *rd, bool overutilized);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810da600)
Location: include/trace/events/sched.h:721
Inline: False
```
**Symbols:**

```
ffffffff810da600-ffffffff810da60e: __bpf_trace_sched_overutilized_tp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_trace_sched_overutilized_tp(void *__data, struct root_domain *rd, bool overutilized);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810edfe0)
Location: include/trace/events/sched.h:719
Inline: False
```
**Symbols:**

```
ffffffff810edfe0-ffffffff810edfee: __bpf_trace_sched_overutilized_tp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_sched_overutilized_tp(void *__data, struct root_domain *rd, bool overutilized);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8110a6f0)
Location: include/trace/events/sched.h:722
Inline: False
```
**Symbols:**

```
ffffffff8110a6f0-ffffffff8110a708: __bpf_trace_sched_overutilized_tp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_sched_overutilized_tp(void *__data, struct root_domain *rd, bool overutilized);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8112f440)
Location: include/trace/events/sched.h:722
Inline: False
```
**Symbols:**

```
ffffffff8112f440-ffffffff8112f458: __bpf_trace_sched_overutilized_tp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_trace_sched_overutilized_tp(void *__data, struct root_domain *rd, bool overutilized);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8113cd10)
Location: include/trace/events/sched.h:722
Inline: False
```
**Symbols:**

```
ffffffff8113cd10-ffffffff8113cd28: __bpf_trace_sched_overutilized_tp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_sched_overutilized_tp(void *__data, struct root_domain *rd, bool overutilized);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81147e50)
Location: include/trace/events/sched.h:771
Inline: False
```
**Symbols:**

```
ffffffff81147e50-ffffffff81147e68: __bpf_trace_sched_overutilized_tp (STB_LOCAL)
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
