# Function: <code>trace_seq_to_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81151458)
Location: kernel/trace/trace.c:1006
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8115a522)
Location: kernel/trace/trace.c:1241
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81164d34)
Location: kernel/trace/trace.c:1285
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81168067)
Location: kernel/trace/trace.c:1284
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8117500a)
Location: kernel/trace/trace.c:1284
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81183fb6)
Location: kernel/trace/trace.c:1293
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81191926)
Location: kernel/trace/trace.c:1294
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119f329)
Location: kernel/trace/trace.c:1465
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811aace9)
Location: kernel/trace/trace.c:1483
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811c2fb0)
Location: kernel/trace/trace.c:1518
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811c0bdc)
Location: kernel/trace/trace.c:1669
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811c1b68)
Location: kernel/trace/trace.c:1666
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811ec708)
Location: kernel/trace/trace.c:1681
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81224965)
Location: kernel/trace/trace.c:1672
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t trace_seq_to_buffer(struct trace_seq *s, void *buf, size_t cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81264930)
Location: kernel/trace/trace.c:1678
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
**Symbols:**

```
ffffffff81264930-ffffffff8126499e: trace_seq_to_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t trace_seq_to_buffer(struct trace_seq *s, void *buf, size_t cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8127b960)
Location: kernel/trace/trace.c:1729
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
**Symbols:**

```
ffffffff8127b960-ffffffff8127b9ce: trace_seq_to_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t trace_seq_to_buffer(struct trace_seq *s, void *buf, size_t cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff812965b0)
Location: kernel/trace/trace.c:1739
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
**Symbols:**

```
ffffffff812965b0-ffffffff8129661e: trace_seq_to_buffer (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff800010227b08)
Location: kernel/trace/trace.c:1483
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0465168)
Location: kernel/trace/trace.c:1483
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002ae0a0)
Location: kernel/trace/trace.c:1483
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe0001824fa)
Location: kernel/trace/trace.c:1483
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a3309)
Location: kernel/trace/trace.c:1483
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811962d9)
Location: kernel/trace/trace.c:1483
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a10d9)
Location: kernel/trace/trace.c:1483
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811aee69)
Location: kernel/trace/trace.c:1483
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
