# Function: <code>trace_raw_output_mmap_lock_acquire_returned</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
enum print_line_t trace_raw_output_mmap_lock_acquire_returned(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap_lock.c (ffffffff81295bc0)
Location: include/trace/events/mmap_lock.h:44
Inline: False
```
**Symbols:**

```
ffffffff81295bc0-ffffffff81295c32: trace_raw_output_mmap_lock_acquire_returned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum print_line_t trace_raw_output_mmap_lock_acquire_returned(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap_lock.c (ffffffff8129b4f0)
Location: include/trace/events/mmap_lock.h:44
Inline: False
```
**Symbols:**

```
ffffffff8129b4f0-ffffffff8129b561: trace_raw_output_mmap_lock_acquire_returned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
enum print_line_t trace_raw_output_mmap_lock_acquire_returned(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmap_lock.c (0)
Location: include/trace/events/mmap_lock.h:44
Inline: False
```
**Symbols:**

```
ffffffff812dc0c0-ffffffff812dc164: trace_raw_output_mmap_lock_acquire_returned (STB_LOCAL)
ffffffff81cbc1b9-ffffffff81cbc1eb: trace_raw_output_mmap_lock_acquire_returned.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
enum print_line_t trace_raw_output_mmap_lock_acquire_returned(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmap_lock.c (0)
Location: include/trace/events/mmap_lock.h:52
Inline: False
```
**Symbols:**

```
ffffffff8133bed0-ffffffff8133bf86: trace_raw_output_mmap_lock_acquire_returned (STB_LOCAL)
ffffffff81e6dd29-ffffffff81e6dd5b: trace_raw_output_mmap_lock_acquire_returned.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
enum print_line_t trace_raw_output_mmap_lock_acquire_returned(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmap_lock.c (0)
Location: include/trace/events/mmap_lock.h:52
Inline: False
```
**Symbols:**

```
ffffffff813b39e0-ffffffff813b3a96: trace_raw_output_mmap_lock_acquire_returned (STB_LOCAL)
ffffffff82063df5-ffffffff82063e27: trace_raw_output_mmap_lock_acquire_returned.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
enum print_line_t trace_raw_output_mmap_lock_acquire_returned(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmap_lock.c (0)
Location: include/trace/events/mmap_lock.h:52
Inline: False
```
**Symbols:**

```
ffffffff813e8640-ffffffff813e86f6: trace_raw_output_mmap_lock_acquire_returned (STB_LOCAL)
ffffffff820e34de-ffffffff820e3510: trace_raw_output_mmap_lock_acquire_returned.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
enum print_line_t trace_raw_output_mmap_lock_acquire_returned(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmap_lock.c (0)
Location: include/trace/events/mmap_lock.h:52
Inline: False
```
**Symbols:**

```
ffffffff814132b0-ffffffff81413366: trace_raw_output_mmap_lock_acquire_returned (STB_LOCAL)
ffffffff821bff33-ffffffff821bff65: trace_raw_output_mmap_lock_acquire_returned.cold (STB_LOCAL)
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
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
