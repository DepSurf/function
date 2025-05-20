# Function: <code>__bpf_trace_jbd2_journal_shrink</code>

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
void __bpf_trace_jbd2_journal_shrink(void *__data, journal_t *journal, long unsigned int nr_to_scan, long unsigned int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff814bd160)
Location: include/trace/events/jbd2.h:397
Inline: False
```
**Symbols:**

```
ffffffff814bd160-ffffffff814bd16b: __bpf_trace_jbd2_journal_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_jbd2_journal_shrink(void *__data, journal_t *journal, long unsigned int nr_to_scan, long unsigned int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff815482c0)
Location: include/trace/events/jbd2.h:397
Inline: False
```
**Symbols:**

```
ffffffff815482c0-ffffffff815482d7: __bpf_trace_jbd2_journal_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_jbd2_journal_shrink(void *__data, journal_t *journal, long unsigned int nr_to_scan, long unsigned int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff815e7960)
Location: include/trace/events/jbd2.h:397
Inline: False
```
**Symbols:**

```
ffffffff815e7960-ffffffff815e7977: __bpf_trace_jbd2_journal_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_trace_jbd2_journal_shrink(void *__data, journal_t *journal, long unsigned int nr_to_scan, long unsigned int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8161f2b0)
Location: include/trace/events/jbd2.h:397
Inline: False
```
**Symbols:**

```
ffffffff8161f2b0-ffffffff8161f2c7: __bpf_trace_jbd2_journal_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_jbd2_journal_shrink(void *__data, journal_t *journal, long unsigned int nr_to_scan, long unsigned int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff816581c0)
Location: include/trace/events/jbd2.h:397
Inline: False
```
**Symbols:**

```
ffffffff816581c0-ffffffff816581d7: __bpf_trace_jbd2_journal_shrink (STB_LOCAL)
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
