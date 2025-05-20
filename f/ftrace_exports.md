# Function: <code>ftrace_exports</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void ftrace_exports(struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81162f47)
Location: kernel/trace/trace.c:2257
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_function
```
**Symbols:**

```
ffffffff81162e60-ffffffff81162e8f: ftrace_exports (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void ftrace_exports(struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81166387)
Location: kernel/trace/trace.c:2434
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_function
```
**Symbols:**

```
ffffffff811662a0-ffffffff811662cf: ftrace_exports (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void ftrace_exports(struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81173317)
Location: kernel/trace/trace.c:2442
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_function
```
**Symbols:**

```
ffffffff81173230-ffffffff8117325e: ftrace_exports (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void ftrace_exports(struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811822f7)
Location: kernel/trace/trace.c:2454
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_function
```
**Symbols:**

```
ffffffff81182210-ffffffff8118223e: ftrace_exports (STB_GLOBAL)
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
In kernel/trace/trace.c (ffffffff8118fc87)
Location: kernel/trace/trace.c:2455
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_function
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
In kernel/trace/trace.c (ffffffff8119da23)
Location: kernel/trace/trace.c:2639
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_function
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
In kernel/trace/trace.c (ffffffff811a93f3)
Location: kernel/trace/trace.c:2665
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_function
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
In kernel/trace/trace.c (ffffffff811c14f7)
Location: kernel/trace/trace.c:2776
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_function
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ftrace_exports(struct ring_buffer_event *event, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811b7860)
Location: kernel/trace/trace.c:312
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_commit
```
**Symbols:**

```
ffffffff811b7860-ffffffff811b78c4: ftrace_exports (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ftrace_exports(struct ring_buffer_event *event, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811b8390)
Location: kernel/trace/trace.c:312
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_commit
```
**Symbols:**

```
ffffffff811b8390-ffffffff811b83f4: ftrace_exports (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ftrace_exports(struct ring_buffer_event *event, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811e2880)
Location: kernel/trace/trace.c:325
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_commit
```
**Symbols:**

```
ffffffff811e2880-ffffffff811e28e4: ftrace_exports (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ftrace_exports(struct ring_buffer_event *event, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81219780)
Location: kernel/trace/trace.c:335
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_commit
```
**Symbols:**

```
ffffffff81219780-ffffffff8121981a: ftrace_exports (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ftrace_exports(struct ring_buffer_event *event, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81263630)
Location: kernel/trace/trace.c:334
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_commit
```
**Symbols:**

```
ffffffff81263630-ffffffff812636ca: ftrace_exports (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ftrace_exports(struct ring_buffer_event *event, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8127a790)
Location: kernel/trace/trace.c:375
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_commit
```
**Symbols:**

```
ffffffff8127a790-ffffffff8127a82a: ftrace_exports (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ftrace_exports(struct ring_buffer_event *event, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81295320)
Location: kernel/trace/trace.c:370
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_commit
```
**Symbols:**

```
ffffffff81295320-ffffffff812953ba: ftrace_exports (STB_LOCAL)
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
In kernel/trace/trace.c (ffff8000102260e8)
Location: kernel/trace/trace.c:2665
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_function
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
In kernel/trace/trace.c (c0463680)
Location: kernel/trace/trace.c:2665
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_function
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
In kernel/trace/trace.c (c0000000002abb50)
Location: kernel/trace/trace.c:2665
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_function
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
In kernel/trace/trace.c (ffffffe000180f86)
Location: kernel/trace/trace.c:2665
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_function
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
In kernel/trace/trace.c (ffffffff811a1a13)
Location: kernel/trace/trace.c:2665
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_function
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
In kernel/trace/trace.c (ffffffff811949e3)
Location: kernel/trace/trace.c:2665
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_function
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
In kernel/trace/trace.c (ffffffff8119f7e3)
Location: kernel/trace/trace.c:2665
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_function
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
In kernel/trace/trace.c (ffffffff811ad563)
Location: kernel/trace/trace.c:2665
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_function
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
