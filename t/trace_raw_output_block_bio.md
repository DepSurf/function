# Function: <code>trace_raw_output_block_bio</code>

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
enum print_line_t trace_raw_output_block_bio(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8155e0e0)
Location: include/trace/events/block.h:261
Inline: False
```
**Symbols:**

```
ffffffff8155e0e0-ffffffff8155e154: trace_raw_output_block_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum print_line_t trace_raw_output_block_bio(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81566940)
Location: include/trace/events/block.h:261
Inline: False
```
**Symbols:**

```
ffffffff81566940-ffffffff815669b3: trace_raw_output_block_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
enum print_line_t trace_raw_output_block_bio(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815cad60)
Location: include/trace/events/block.h:261
Inline: False
```
**Symbols:**

```
ffffffff815cad60-ffffffff815cadd3: trace_raw_output_block_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
enum print_line_t trace_raw_output_block_bio(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff816764a0)
Location: include/trace/events/block.h:284
Inline: False
```
**Symbols:**

```
ffffffff816764a0-ffffffff81676537: trace_raw_output_block_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum print_line_t trace_raw_output_block_bio(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81732570)
Location: include/trace/events/block.h:284
Inline: False
```
**Symbols:**

```
ffffffff81732570-ffffffff81732607: trace_raw_output_block_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum print_line_t trace_raw_output_block_bio(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8176e980)
Location: include/trace/events/block.h:310
Inline: False
```
**Symbols:**

```
ffffffff8176e980-ffffffff8176ea17: trace_raw_output_block_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum print_line_t trace_raw_output_block_bio(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817b0c10)
Location: include/trace/events/block.h:312
Inline: False
```
**Symbols:**

```
ffffffff817b0c10-ffffffff817b0ca7: trace_raw_output_block_bio (STB_LOCAL)
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
