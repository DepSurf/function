# Function: <code>blk_fill_rwbs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_fill_rwbs(char *rwbs, u32 rw, int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff8115abc0)
Location: kernel/trace/blktrace.c:1776
Inline: False
Direct callers:
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_with_error
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_bio_remap
  - block/blk-core.c:trace_event_raw_event_block_split
  - block/blk-core.c:trace_event_raw_event_block_bio_merge
  - block/blk-core.c:trace_event_raw_event_block_bio_queue
  - block/blk-core.c:trace_event_raw_event_block_bio_bounce
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_get_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_complete
  - block/blk-core.c:trace_event_raw_event_block_rq_with_error
```
**Symbols:**

```
ffffffff8115abc0-ffffffff8115ac81: blk_fill_rwbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_fill_rwbs(char *rwbs, int op, u32 rw, int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811654c0)
Location: kernel/trace/blktrace.c:1780
Inline: False
Direct callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_with_error
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_bio_remap
  - block/blk-core.c:trace_event_raw_event_block_split
  - block/blk-core.c:trace_event_raw_event_block_get_rq
  - block/blk-core.c:trace_event_raw_event_block_bio_queue
  - block/blk-core.c:trace_event_raw_event_block_bio_merge
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_bio_bounce
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_complete
  - block/blk-core.c:trace_event_raw_event_block_rq_with_error
```
**Symbols:**

```
ffffffff811654c0-ffffffff8116557a: blk_fill_rwbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_fill_rwbs(char *rwbs, unsigned int op, int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff81170910)
Location: kernel/trace/blktrace.c:1780
Inline: False
Direct callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_with_error
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_bio_remap
  - block/blk-core.c:trace_event_raw_event_block_split
  - block/blk-core.c:trace_event_raw_event_block_get_rq
  - block/blk-core.c:trace_event_raw_event_block_bio_queue
  - block/blk-core.c:trace_event_raw_event_block_bio_merge
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_bio_bounce
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_complete
  - block/blk-core.c:trace_event_raw_event_block_rq_with_error
```
**Symbols:**

```
ffffffff81170910-ffffffff811709dc: blk_fill_rwbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_fill_rwbs(char *rwbs, unsigned int op, int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811739b0)
Location: kernel/trace/blktrace.c:1733
Inline: False
Direct callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_bio_remap
  - block/blk-core.c:trace_event_raw_event_block_split
  - block/blk-core.c:trace_event_raw_event_block_get_rq
  - block/blk-core.c:trace_event_raw_event_block_bio_queue
  - block/blk-core.c:trace_event_raw_event_block_bio_merge
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_bio_bounce
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_complete
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
**Symbols:**

```
ffffffff811739b0-ffffffff81173a79: blk_fill_rwbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_fill_rwbs(char *rwbs, unsigned int op, int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff81180b70)
Location: kernel/trace/blktrace.c:1888
Inline: False
Direct callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_bio_remap
  - block/blk-core.c:trace_event_raw_event_block_split
  - block/blk-core.c:trace_event_raw_event_block_get_rq
  - block/blk-core.c:trace_event_raw_event_block_bio_queue
  - block/blk-core.c:trace_event_raw_event_block_bio_merge
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_bio_bounce
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_complete
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
**Symbols:**

```
ffffffff81180b70-ffffffff81180c3f: blk_fill_rwbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_fill_rwbs(char *rwbs, unsigned int op, int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff8118fd00)
Location: kernel/trace/blktrace.c:1892
Inline: False
Direct callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_bio_remap
  - block/blk-core.c:trace_event_raw_event_block_split
  - block/blk-core.c:trace_event_raw_event_block_get_rq
  - block/blk-core.c:trace_event_raw_event_block_bio_queue
  - block/blk-core.c:trace_event_raw_event_block_bio_merge
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_bio_bounce
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_complete
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
**Symbols:**

```
ffffffff8118fd00-ffffffff8118fdca: blk_fill_rwbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_fill_rwbs(char *rwbs, unsigned int op, int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff8119d4d0)
Location: kernel/trace/blktrace.c:1880
Inline: False
Direct callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_bio_remap
  - block/blk-core.c:trace_event_raw_event_block_split
  - block/blk-core.c:trace_event_raw_event_block_get_rq
  - block/blk-core.c:trace_event_raw_event_block_bio_queue
  - block/blk-core.c:trace_event_raw_event_block_bio_merge
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_bio_bounce
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_complete
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
**Symbols:**

```
ffffffff8119d4d0-ffffffff8119d5c7: blk_fill_rwbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_fill_rwbs(char *rwbs, unsigned int op, int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811ab210)
Location: kernel/trace/blktrace.c:1875
Inline: False
Direct callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_bio_remap
  - block/blk-core.c:trace_event_raw_event_block_split
  - block/blk-core.c:trace_event_raw_event_block_get_rq
  - block/blk-core.c:trace_event_raw_event_block_bio_queue
  - block/blk-core.c:trace_event_raw_event_block_bio_merge
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_bio_bounce
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_complete
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
**Symbols:**

```
ffffffff811ab210-ffffffff811ab305: blk_fill_rwbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_fill_rwbs(char *rwbs, unsigned int op, int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811b6a00)
Location: kernel/trace/blktrace.c:1930
Inline: False
Direct callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_bio_remap
  - block/blk-core.c:trace_event_raw_event_block_split
  - block/blk-core.c:trace_event_raw_event_block_get_rq
  - block/blk-core.c:trace_event_raw_event_block_bio_queue
  - block/blk-core.c:trace_event_raw_event_block_bio_merge
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_bio_bounce
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_complete
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
**Symbols:**

```
ffffffff811b6a00-ffffffff811b6af5: blk_fill_rwbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_fill_rwbs(char *rwbs, unsigned int op, int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811cf540)
Location: kernel/trace/blktrace.c:1958
Inline: False
Direct callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_bio_remap
  - block/blk-core.c:trace_event_raw_event_block_split
  - block/blk-core.c:trace_event_raw_event_block_get_rq
  - block/blk-core.c:trace_event_raw_event_block_bio_queue
  - block/blk-core.c:trace_event_raw_event_block_bio_merge
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_bio_bounce
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_complete
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
**Symbols:**

```
ffffffff811cf540-ffffffff811cf669: blk_fill_rwbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_fill_rwbs(char *rwbs, unsigned int op, int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811cc9e0)
Location: kernel/trace/blktrace.c:1868
Inline: False
Direct callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_bio
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_bio_remap
  - block/blk-core.c:trace_event_raw_event_block_split
  - block/blk-core.c:trace_event_raw_event_block_bio
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_complete
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
**Symbols:**

```
ffffffff811cc9e0-ffffffff811ccb04: blk_fill_rwbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_fill_rwbs(char *rwbs, unsigned int op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811cdd10)
Location: kernel/trace/blktrace.c:1877
Inline: False
Direct callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_bio
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_bio_remap
  - block/blk-core.c:trace_event_raw_event_block_split
  - block/blk-core.c:trace_event_raw_event_block_bio
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_complete
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
**Symbols:**

```
ffffffff811cdd10-ffffffff811cde34: blk_fill_rwbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_fill_rwbs(char *rwbs, unsigned int op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811fa6e0)
Location: kernel/trace/blktrace.c:1895
Inline: False
Direct callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_bio
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_bio_remap
  - block/blk-core.c:trace_event_raw_event_block_split
  - block/blk-core.c:trace_event_raw_event_block_bio
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_complete
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
**Symbols:**

```
ffffffff811fa6e0-ffffffff811fa804: blk_fill_rwbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_fill_rwbs(char *rwbs, unsigned int op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff81234800)
Location: kernel/trace/blktrace.c:1895
Inline: False
Direct callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_bio
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_completion
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_bio_remap
  - block/blk-core.c:trace_event_raw_event_block_split
  - block/blk-core.c:trace_event_raw_event_block_bio
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_completion
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
**Symbols:**

```
ffffffff81234800-ffffffff81234909: blk_fill_rwbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_fill_rwbs(char *rwbs, blk_opf_t opf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff812810c0)
Location: kernel/trace/blktrace.c:1880
Inline: False
Direct callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_bio
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_completion
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_bio_remap
  - block/blk-core.c:trace_event_raw_event_block_split
  - block/blk-core.c:trace_event_raw_event_block_bio
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_completion
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
**Symbols:**

```
ffffffff812810c0-ffffffff812811c9: blk_fill_rwbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_fill_rwbs(char *rwbs, blk_opf_t opf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff8129dd90)
Location: kernel/trace/blktrace.c:1876
Inline: False
Direct callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_bio
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_completion
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_bio_remap
  - block/blk-core.c:trace_event_raw_event_block_split
  - block/blk-core.c:trace_event_raw_event_block_bio
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_completion
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
**Symbols:**

```
ffffffff8129dd90-ffffffff8129de77: blk_fill_rwbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_fill_rwbs(char *rwbs, blk_opf_t opf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff812b9470)
Location: kernel/trace/blktrace.c:1876
Inline: False
Direct callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_bio
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_completion
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_bio_remap
  - block/blk-core.c:trace_event_raw_event_block_split
  - block/blk-core.c:trace_event_raw_event_block_bio
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_completion
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
**Symbols:**

```
ffffffff812b9470-ffffffff812b9557: blk_fill_rwbs (STB_GLOBAL)
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
void blk_fill_rwbs(char *rwbs, unsigned int op, int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffff8000102348e8)
Location: kernel/trace/blktrace.c:1930
Inline: False
Direct callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_bio_remap
  - block/blk-core.c:trace_event_raw_event_block_split
  - block/blk-core.c:trace_event_raw_event_block_get_rq
  - block/blk-core.c:trace_event_raw_event_block_bio_queue
  - block/blk-core.c:trace_event_raw_event_block_bio_merge
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_bio_bounce
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_complete
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
**Symbols:**

```
ffff8000102348e8-ffff800010234a08: blk_fill_rwbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_fill_rwbs(char *rwbs, unsigned int op, int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (c04707ac)
Location: kernel/trace/blktrace.c:1930
Inline: False
Direct callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_bio_remap
  - block/blk-core.c:trace_event_raw_event_block_split
  - block/blk-core.c:trace_event_raw_event_block_get_rq
  - block/blk-core.c:trace_event_raw_event_block_bio_queue
  - block/blk-core.c:trace_event_raw_event_block_bio_merge
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_bio_bounce
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_complete
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
**Symbols:**

```
c04707ac-c04708c8: blk_fill_rwbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_fill_rwbs(char *rwbs, unsigned int op, int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (c0000000002c0030)
Location: kernel/trace/blktrace.c:1930
Inline: False
Direct callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_bio_remap
  - block/blk-core.c:trace_event_raw_event_block_split
  - block/blk-core.c:trace_event_raw_event_block_get_rq
  - block/blk-core.c:trace_event_raw_event_block_bio_queue
  - block/blk-core.c:trace_event_raw_event_block_bio_merge
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_bio_bounce
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_complete
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
**Symbols:**

```
c0000000002c0030-c0000000002c01bc: blk_fill_rwbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_fill_rwbs(char *rwbs, unsigned int op, int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffe00018c264)
Location: kernel/trace/blktrace.c:1930
Inline: False
Direct callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_bio_remap
  - block/blk-core.c:trace_event_raw_event_block_split
  - block/blk-core.c:trace_event_raw_event_block_get_rq
  - block/blk-core.c:trace_event_raw_event_block_bio_queue
  - block/blk-core.c:trace_event_raw_event_block_bio_merge
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_bio_bounce
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_complete
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
**Symbols:**

```
ffffffe00018c264-ffffffe00018c368: blk_fill_rwbs (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void blk_fill_rwbs(char *rwbs, unsigned int op, int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811af020)
Location: kernel/trace/blktrace.c:1930
Inline: False
Direct callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_bio_remap
  - block/blk-core.c:trace_event_raw_event_block_split
  - block/blk-core.c:trace_event_raw_event_block_get_rq
  - block/blk-core.c:trace_event_raw_event_block_bio_queue
  - block/blk-core.c:trace_event_raw_event_block_bio_merge
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_bio_bounce
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_complete
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
**Symbols:**

```
ffffffff811af020-ffffffff811af115: blk_fill_rwbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_fill_rwbs(char *rwbs, unsigned int op, int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811a1e70)
Location: kernel/trace/blktrace.c:1930
Inline: False
Direct callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_bio_remap
  - block/blk-core.c:trace_event_raw_event_block_split
  - block/blk-core.c:trace_event_raw_event_block_get_rq
  - block/blk-core.c:trace_event_raw_event_block_bio_queue
  - block/blk-core.c:trace_event_raw_event_block_bio_merge
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_bio_bounce
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_complete
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
**Symbols:**

```
ffffffff811a1e70-ffffffff811a1f65: blk_fill_rwbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_fill_rwbs(char *rwbs, unsigned int op, int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811acdf0)
Location: kernel/trace/blktrace.c:1930
Inline: False
Direct callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_bio_remap
  - block/blk-core.c:trace_event_raw_event_block_split
  - block/blk-core.c:trace_event_raw_event_block_get_rq
  - block/blk-core.c:trace_event_raw_event_block_bio_queue
  - block/blk-core.c:trace_event_raw_event_block_bio_merge
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_bio_bounce
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_complete
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
**Symbols:**

```
ffffffff811acdf0-ffffffff811acee5: blk_fill_rwbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_fill_rwbs(char *rwbs, unsigned int op, int bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811bacc0)
Location: kernel/trace/blktrace.c:1930
Inline: False
Direct callers:
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:trace_event_raw_event_block_rq_remap
  - block/blk-core.c:trace_event_raw_event_block_bio_remap
  - block/blk-core.c:trace_event_raw_event_block_split
  - block/blk-core.c:trace_event_raw_event_block_get_rq
  - block/blk-core.c:trace_event_raw_event_block_bio_queue
  - block/blk-core.c:trace_event_raw_event_block_bio_merge
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_bio_bounce
  - block/blk-core.c:trace_event_raw_event_block_rq
  - block/blk-core.c:trace_event_raw_event_block_rq_complete
  - block/blk-core.c:trace_event_raw_event_block_rq_requeue
```
**Symbols:**

```
ffffffff811bacc0-ffffffff811badb5: blk_fill_rwbs (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int op</code>
</li>
<li>
<b>Param reordered. </b>
<code>rwbs, rw, bytes</code> ➡️ <code>rwbs, op, rw, bytes</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u32 rw</code>
</li>
<li>
<b>Param reordered. </b>
<code>rwbs, op, rw, bytes</code> ➡️ <code>rwbs, op, bytes</code>
</li>
<li>
<b>Param type changed. </b>
<code>int op</code> ➡️ <code>unsigned int op</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int bytes</code>
</li>
</ul>
</details>
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
<b>Param added. </b>
<code>blk_opf_t opf</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int op</code>
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
