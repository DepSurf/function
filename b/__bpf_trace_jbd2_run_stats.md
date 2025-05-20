# Function: <code>__bpf_trace_jbd2_run_stats</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
void __bpf_trace_jbd2_run_stats(void *__data, dev_t dev, long unsigned int tid, struct transaction_run_stats_s *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8139abe0)
Location: include/trace/events/jbd2.h:234
Inline: False
```
**Symbols:**

```
ffffffff8139abe0-ffffffff8139abed: __bpf_trace_jbd2_run_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_trace_jbd2_run_stats(void *__data, dev_t dev, long unsigned int tid, struct transaction_run_stats_s *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813b3950)
Location: include/trace/events/jbd2.h:234
Inline: False
```
**Symbols:**

```
ffffffff813b3950-ffffffff813b395d: __bpf_trace_jbd2_run_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_jbd2_run_stats(void *__data, dev_t dev, long unsigned int tid, struct transaction_run_stats_s *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813ddf60)
Location: include/trace/events/jbd2.h:234
Inline: False
```
**Symbols:**

```
ffffffff813ddf60-ffffffff813ddf6d: __bpf_trace_jbd2_run_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_jbd2_run_stats(void *__data, dev_t dev, long unsigned int tid, struct transaction_run_stats_s *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813f7fb0)
Location: include/trace/events/jbd2.h:234
Inline: False
```
**Symbols:**

```
ffffffff813f7fb0-ffffffff813f7fbd: __bpf_trace_jbd2_run_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_jbd2_run_stats(void *__data, dev_t dev, long unsigned int tid, struct transaction_run_stats_s *stats);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff814453c0)
Location: include/trace/events/jbd2.h:248
Inline: True
```
**Symbols:**

```
ffffffff814453c0-ffffffff814453cd: __bpf_trace_jbd2_run_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_jbd2_run_stats(void *__data, dev_t dev, long unsigned int tid, struct transaction_run_stats_s *stats);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81461a80)
Location: include/trace/events/jbd2.h:248
Inline: True
```
**Symbols:**

```
ffffffff81461a80-ffffffff81461a8d: __bpf_trace_jbd2_run_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_jbd2_run_stats(void *__data, dev_t dev, long unsigned int tid, struct transaction_run_stats_s *stats);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81467220)
Location: include/trace/events/jbd2.h:248
Inline: True
```
**Symbols:**

```
ffffffff81467220-ffffffff8146722d: __bpf_trace_jbd2_run_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_jbd2_run_stats(void *__data, dev_t dev, long unsigned int tid, struct transaction_run_stats_s *stats);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff814bd150)
Location: include/trace/events/jbd2.h:248
Inline: True
```
**Symbols:**

```
ffffffff814bd150-ffffffff814bd15d: __bpf_trace_jbd2_run_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_jbd2_run_stats(void *__data, dev_t dev, long unsigned int tid, struct transaction_run_stats_s *stats);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff815482a0)
Location: include/trace/events/jbd2.h:248
Inline: True
```
**Symbols:**

```
ffffffff815482a0-ffffffff815482b9: __bpf_trace_jbd2_run_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_jbd2_run_stats(void *__data, dev_t dev, tid_t tid, struct transaction_run_stats_s *stats);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff815e7930)
Location: include/trace/events/jbd2.h:248
Inline: True
```
**Symbols:**

```
ffffffff815e7930-ffffffff815e794b: __bpf_trace_jbd2_run_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_jbd2_run_stats(void *__data, dev_t dev, tid_t tid, struct transaction_run_stats_s *stats);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8161f280)
Location: include/trace/events/jbd2.h:248
Inline: True
```
**Symbols:**

```
ffffffff8161f280-ffffffff8161f29b: __bpf_trace_jbd2_run_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_jbd2_run_stats(void *__data, dev_t dev, tid_t tid, struct transaction_run_stats_s *stats);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81658190)
Location: include/trace/events/jbd2.h:248
Inline: True
```
**Symbols:**

```
ffffffff81658190-ffffffff816581ab: __bpf_trace_jbd2_run_stats (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __bpf_trace_jbd2_run_stats(void *__data, dev_t dev, long unsigned int tid, struct transaction_run_stats_s *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffff8000104d3748)
Location: include/trace/events/jbd2.h:234
Inline: False
```
**Symbols:**

```
ffff8000104d3748-ffff8000104d3760: __bpf_trace_jbd2_run_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_jbd2_run_stats(void *__data, dev_t dev, long unsigned int tid, struct transaction_run_stats_s *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (c0696984)
Location: include/trace/events/jbd2.h:234
Inline: False
```
**Symbols:**

```
c0696984-c06969bc: __bpf_trace_jbd2_run_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_jbd2_run_stats(void *__data, dev_t dev, long unsigned int tid, struct transaction_run_stats_s *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (c00000000060e7b0)
Location: include/trace/events/jbd2.h:234
Inline: False
```
**Symbols:**

```
c00000000060e7b0-c00000000060e7dc: __bpf_trace_jbd2_run_stats (STB_LOCAL)
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
void __bpf_trace_jbd2_run_stats(void *__data, dev_t dev, long unsigned int tid, struct transaction_run_stats_s *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813f0590)
Location: include/trace/events/jbd2.h:234
Inline: False
```
**Symbols:**

```
ffffffff813f0590-ffffffff813f059d: __bpf_trace_jbd2_run_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_jbd2_run_stats(void *__data, dev_t dev, long unsigned int tid, struct transaction_run_stats_s *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813e1010)
Location: include/trace/events/jbd2.h:234
Inline: False
```
**Symbols:**

```
ffffffff813e1010-ffffffff813e101d: __bpf_trace_jbd2_run_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_jbd2_run_stats(void *__data, dev_t dev, long unsigned int tid, struct transaction_run_stats_s *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813ed910)
Location: include/trace/events/jbd2.h:234
Inline: False
```
**Symbols:**

```
ffffffff813ed910-ffffffff813ed91d: __bpf_trace_jbd2_run_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_jbd2_run_stats(void *__data, dev_t dev, long unsigned int tid, struct transaction_run_stats_s *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff814032e0)
Location: include/trace/events/jbd2.h:234
Inline: False
```
**Symbols:**

```
ffffffff814032e0-ffffffff814032ed: __bpf_trace_jbd2_run_stats (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long unsigned int tid</code> ➡️ <code>tid_t tid</code>
</li>
</ul>
</details>
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
