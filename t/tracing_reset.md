# Function: <code>tracing_reset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tracing_reset(struct trace_buffer *buf, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8114e160)
Location: kernel/trace/trace.c:1303
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_snapshot_write
```
**Symbols:**

```
ffffffff8114e160-ffffffff8114e198: tracing_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tracing_reset(struct trace_buffer *buf, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81156dc0)
Location: kernel/trace/trace.c:1548
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_open
```
**Symbols:**

```
ffffffff81156dc0-ffffffff81156df8: tracing_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tracing_reset(struct trace_buffer *buf, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81161f00)
Location: kernel/trace/trace.c:1592
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_open
```
**Symbols:**

```
ffffffff81161f00-ffffffff81161f38: tracing_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tracing_reset(struct trace_buffer *buf, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81165320)
Location: kernel/trace/trace.c:1662
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_open
```
**Symbols:**

```
ffffffff81165320-ffffffff81165358: tracing_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tracing_reset(struct trace_buffer *buf, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81172270)
Location: kernel/trace/trace.c:1662
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_open
```
**Symbols:**

```
ffffffff81172270-ffffffff811722a8: tracing_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tracing_reset(struct trace_buffer *buf, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81181400)
Location: kernel/trace/trace.c:1673
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_open
```
**Symbols:**

```
ffffffff81181400-ffffffff81181438: tracing_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tracing_reset(struct trace_buffer *buf, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118edc0)
Location: kernel/trace/trace.c:1674
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_open
```
**Symbols:**

```
ffffffff8118edc0-ffffffff8118edf8: tracing_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tracing_reset(struct trace_buffer *buf, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119c740)
Location: kernel/trace/trace.c:1857
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_open
```
**Symbols:**

```
ffffffff8119c740-ffffffff8119c77a: tracing_reset (STB_GLOBAL)
```
</details>
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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
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
</ul>
