# Function: <code>trace_iter_expand_format</code>

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
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811c0392)
Location: kernel/trace/trace.c:3599
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_format
  - kernel/trace/trace.c:trace_check_vprintf
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
In kernel/trace/trace.c (ffffffff811eada2)
Location: kernel/trace/trace.c:3659
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_format
  - kernel/trace/trace.c:trace_check_vprintf
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
In kernel/trace/trace.c (ffffffff81222dac)
Location: kernel/trace/trace.c:3657
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_format
  - kernel/trace/trace.c:trace_check_vprintf
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8126de1c)
Location: kernel/trace/trace.c:3681
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_format
  - kernel/trace/trace.c:trace_check_vprintf
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
char *trace_iter_expand_format(struct trace_iterator *iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8128503a)
Location: kernel/trace/trace.c:3775
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_format
  - kernel/trace/trace.c:trace_check_vprintf
```
**Symbols:**

```
ffffffff81284840-ffffffff812848aa: trace_iter_expand_format (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
char *trace_iter_expand_format(struct trace_iterator *iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff812a013a)
Location: kernel/trace/trace.c:3752
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_format
  - kernel/trace/trace.c:trace_check_vprintf
```
**Symbols:**

```
ffffffff8129f940-ffffffff8129f9aa: trace_iter_expand_format (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
