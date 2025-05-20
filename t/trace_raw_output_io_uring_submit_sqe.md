# Function: <code>trace_raw_output_io_uring_submit_sqe</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
enum print_line_t trace_raw_output_io_uring_submit_sqe(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8137aac0)
Location: include/trace/events/io_uring.h:331
Inline: False
```
**Symbols:**

```
ffffffff8137aac0-ffffffff8137ab2a: trace_raw_output_io_uring_submit_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
enum print_line_t trace_raw_output_io_uring_submit_sqe(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81388d90)
Location: include/trace/events/io_uring.h:331
Inline: False
```
**Symbols:**

```
ffffffff81388d90-ffffffff81388dfa: trace_raw_output_io_uring_submit_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum print_line_t trace_raw_output_io_uring_submit_sqe(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8138fea0)
Location: include/trace/events/io_uring.h:334
Inline: False
```
**Symbols:**

```
ffffffff8138fea0-ffffffff8138ff09: trace_raw_output_io_uring_submit_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
enum print_line_t trace_raw_output_io_uring_submit_sqe(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (0)
Location: include/trace/events/io_uring.h:335
Inline: False
```
**Symbols:**

```
ffffffff813de370-ffffffff813de405: trace_raw_output_io_uring_submit_sqe (STB_LOCAL)
ffffffff81cc5819-ffffffff81cc5843: trace_raw_output_io_uring_submit_sqe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
enum print_line_t trace_raw_output_io_uring_submit_sqe(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: include/trace/events/io_uring.h:390
Inline: False
```
**Symbols:**

```
ffffffff816c8f00-ffffffff816c8fab: trace_raw_output_io_uring_submit_sqe (STB_LOCAL)
ffffffff81e8f0fc-ffffffff81e8f126: trace_raw_output_io_uring_submit_sqe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
enum print_line_t trace_raw_output_io_uring_submit_sqe(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: include/trace/events/io_uring.h:371
Inline: False
```
**Symbols:**

```
ffffffff81788c40-ffffffff81788ceb: trace_raw_output_io_uring_submit_sqe (STB_LOCAL)
ffffffff820774dc-ffffffff82077506: trace_raw_output_io_uring_submit_sqe.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
