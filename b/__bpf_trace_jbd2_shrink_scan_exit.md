# Function: <code>__bpf_trace_jbd2_shrink_scan_exit</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_trace_jbd2_shrink_scan_exit(void *__data, journal_t *journal, long unsigned int nr_to_scan, long unsigned int nr_shrunk, long unsigned int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff814bd180)
Location: include/trace/events/jbd2.h:435
Inline: False
```
**Symbols:**

```
ffffffff814bd180-ffffffff814bd18b: __bpf_trace_jbd2_shrink_scan_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_jbd2_shrink_scan_exit(void *__data, journal_t *journal, long unsigned int nr_to_scan, long unsigned int nr_shrunk, long unsigned int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81548300)
Location: include/trace/events/jbd2.h:435
Inline: False
```
**Symbols:**

```
ffffffff81548300-ffffffff8154831a: __bpf_trace_jbd2_shrink_scan_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_jbd2_shrink_scan_exit(void *__data, journal_t *journal, long unsigned int nr_to_scan, long unsigned int nr_shrunk, long unsigned int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff815e79c0)
Location: include/trace/events/jbd2.h:435
Inline: False
```
**Symbols:**

```
ffffffff815e79c0-ffffffff815e79da: __bpf_trace_jbd2_shrink_scan_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_trace_jbd2_shrink_scan_exit(void *__data, journal_t *journal, long unsigned int nr_to_scan, long unsigned int nr_shrunk, long unsigned int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8161f310)
Location: include/trace/events/jbd2.h:435
Inline: False
```
**Symbols:**

```
ffffffff8161f310-ffffffff8161f32a: __bpf_trace_jbd2_shrink_scan_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_jbd2_shrink_scan_exit(void *__data, journal_t *journal, long unsigned int nr_to_scan, long unsigned int nr_shrunk, long unsigned int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81658220)
Location: include/trace/events/jbd2.h:435
Inline: False
```
**Symbols:**

```
ffffffff81658220-ffffffff8165823a: __bpf_trace_jbd2_shrink_scan_exit (STB_LOCAL)
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
