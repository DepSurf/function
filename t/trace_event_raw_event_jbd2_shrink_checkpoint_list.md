# Function: <code>trace_event_raw_event_jbd2_shrink_checkpoint_list</code>

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
void trace_event_raw_event_jbd2_shrink_checkpoint_list(void *__data, journal_t *journal, tid_t first_tid, tid_t tid, tid_t last_tid, long unsigned int nr_freed, long unsigned int nr_scanned, tid_t next_tid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff814bf4c0)
Location: include/trace/events/jbd2.h:462
Inline: False
```
**Symbols:**

```
ffffffff814bf4c0-ffffffff814bf5c5: trace_event_raw_event_jbd2_shrink_checkpoint_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void trace_event_raw_event_jbd2_shrink_checkpoint_list(void *__data, journal_t *journal, tid_t first_tid, tid_t tid, tid_t last_tid, long unsigned int nr_freed, long unsigned int nr_scanned, tid_t next_tid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81547700)
Location: include/trace/events/jbd2.h:462
Inline: False
```
**Symbols:**

```
ffffffff81547700-ffffffff815477fa: trace_event_raw_event_jbd2_shrink_checkpoint_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void trace_event_raw_event_jbd2_shrink_checkpoint_list(void *__data, journal_t *journal, tid_t first_tid, tid_t tid, tid_t last_tid, long unsigned int nr_freed, long unsigned int nr_scanned, tid_t next_tid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff815e6bf0)
Location: include/trace/events/jbd2.h:462
Inline: False
```
**Symbols:**

```
ffffffff815e6bf0-ffffffff815e6cea: trace_event_raw_event_jbd2_shrink_checkpoint_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void trace_event_raw_event_jbd2_shrink_checkpoint_list(void *__data, journal_t *journal, tid_t first_tid, tid_t tid, tid_t last_tid, long unsigned int nr_freed, tid_t next_tid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8161e520)
Location: include/trace/events/jbd2.h:462
Inline: False
```
**Symbols:**

```
ffffffff8161e520-ffffffff8161e60a: trace_event_raw_event_jbd2_shrink_checkpoint_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void trace_event_raw_event_jbd2_shrink_checkpoint_list(void *__data, journal_t *journal, tid_t first_tid, tid_t tid, tid_t last_tid, long unsigned int nr_freed, tid_t next_tid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81657430)
Location: include/trace/events/jbd2.h:462
Inline: False
```
**Symbols:**

```
ffffffff81657430-ffffffff8165751a: trace_event_raw_event_jbd2_shrink_checkpoint_list (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int nr_scanned</code>
</li>
<li>
<b>Param reordered. </b>
<code>__data, journal, first_tid, tid, last_tid, nr_freed, nr_scanned, next_tid</code> ➡️ <code>__data, journal, first_tid, tid, last_tid, nr_freed, next_tid</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
