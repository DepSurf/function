# Function: <code>trace_event_format</code>

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
<summary>In <code>5.13</code>: ✅</summary>

```c
const char *trace_event_format(struct trace_iterator *iter, const char *fmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811c02a0)
Location: kernel/trace/trace.c:3841
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:trace_output_call
  - kernel/trace/trace_output.c:trace_event_printf
```
**Symbols:**

```
ffffffff811c02a0-ffffffff811c03f0: trace_event_format (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const char *trace_event_format(struct trace_iterator *iter, const char *fmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811eacb0)
Location: kernel/trace/trace.c:3913
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:trace_output_call
  - kernel/trace/trace_output.c:trace_event_printf
```
**Symbols:**

```
ffffffff811eacb0-ffffffff811eae00: trace_event_format (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const char *trace_event_format(struct trace_iterator *iter, const char *fmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81222ca0)
Location: kernel/trace/trace.c:3916
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:trace_output_call
  - kernel/trace/trace_output.c:trace_event_printf
```
**Symbols:**

```
ffffffff81222ca0-ffffffff81222e16: trace_event_format (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *trace_event_format(struct trace_iterator *iter, const char *fmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8126dd10)
Location: kernel/trace/trace.c:3940
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:trace_output_call
  - kernel/trace/trace_output.c:trace_event_printf
```
**Symbols:**

```
ffffffff8126dd10-ffffffff8126de86: trace_event_format (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *trace_event_format(struct trace_iterator *iter, const char *fmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81284f30)
Location: kernel/trace/trace.c:4034
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:trace_output_call
  - kernel/trace/trace_output.c:trace_event_printf
```
**Symbols:**

```
ffffffff81284f30-ffffffff812850a4: trace_event_format (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const char *trace_event_format(struct trace_iterator *iter, const char *fmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff812a0030)
Location: kernel/trace/trace.c:4002
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:trace_output_call
  - kernel/trace/trace_output.c:trace_event_printf
```
**Symbols:**

```
ffffffff812a0030-ffffffff812a01a4: trace_event_format (STB_GLOBAL)
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
