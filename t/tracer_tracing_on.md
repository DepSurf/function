# Function: <code>tracer_tracing_on</code>

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
In kernel/trace/trace.c (ffffffff8114aab7)
Location: kernel/trace/trace.c:506
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_on
  - kernel/trace/trace.c:rb_simple_write
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
In kernel/trace/trace.c (ffffffff811538c8)
Location: kernel/trace/trace.c:741
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_on
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
In kernel/trace/trace.c (ffffffff8115daa8)
Location: kernel/trace/trace.c:768
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_on
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void tracer_tracing_on(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81160c01)
Location: kernel/trace/trace.c:760
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_on
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceon
```
**Symbols:**

```
ffffffff81164d20-ffffffff81164d43: tracer_tracing_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void tracer_tracing_on(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8116dcc1)
Location: kernel/trace/trace.c:760
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_on
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceon
```
**Symbols:**

```
ffffffff81171c80-ffffffff81171ca3: tracer_tracing_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void tracer_tracing_on(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8117cbc5)
Location: kernel/trace/trace.c:759
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_on
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceon
```
**Symbols:**

```
ffffffff81180dd0-ffffffff81180df3: tracer_tracing_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void tracer_tracing_on(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118a460)
Location: kernel/trace/trace.c:760
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_on
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceon
```
**Symbols:**

```
ffffffff8118e790-ffffffff8118e7b3: tracer_tracing_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void tracer_tracing_on(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81197b66)
Location: kernel/trace/trace.c:764
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_on
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceon
```
**Symbols:**

```
ffffffff8119c190-ffffffff8119c1b3: tracer_tracing_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void tracer_tracing_on(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a3506)
Location: kernel/trace/trace.c:782
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_on
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceon
```
**Symbols:**

```
ffffffff811a7b80-ffffffff811a7ba3: tracer_tracing_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void tracer_tracing_on(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bcf76)
Location: kernel/trace/trace.c:803
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_on
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceon
  - kernel/trace/trace_functions.c:ftrace_traceon_count
```
**Symbols:**

```
ffffffff811bff40-ffffffff811bff66: tracer_tracing_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void tracer_tracing_on(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bab86)
Location: kernel/trace/trace.c:954
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_on
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceon
  - kernel/trace/trace_functions.c:ftrace_traceon_count
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff811bdb70-ffffffff811bdb96: tracer_tracing_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void tracer_tracing_on(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811badf6)
Location: kernel/trace/trace.c:957
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_on
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceon
  - kernel/trace/trace_functions.c:ftrace_traceon_count
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff811bd680-ffffffff811bd6a6: tracer_tracing_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void tracer_tracing_on(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811e55a6)
Location: kernel/trace/trace.c:970
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_on
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceon
  - kernel/trace/trace_functions.c:ftrace_traceon_count
  - kernel/trace/trace_events_trigger.c:traceon_count_trigger
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff811e8170-ffffffff811e8196: tracer_tracing_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void tracer_tracing_on(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8121c98d)
Location: kernel/trace/trace.c:958
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_on
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceon
  - kernel/trace/trace_functions.c:ftrace_traceon_count
  - kernel/trace/trace_events_trigger.c:traceon_count_trigger
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff8121fca0-ffffffff8121fccc: tracer_tracing_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void tracer_tracing_on(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81267262)
Location: kernel/trace/trace.c:957
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_on
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceon
  - kernel/trace/trace_functions.c:ftrace_traceon_count
  - kernel/trace/trace_events_trigger.c:traceon_count_trigger
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff8126a900-ffffffff8126a92c: tracer_tracing_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void tracer_tracing_on(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8127e322)
Location: kernel/trace/trace.c:998
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_on
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceon
  - kernel/trace/trace_functions.c:ftrace_traceon_count
  - kernel/trace/trace_events_trigger.c:traceon_count_trigger
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff81281a80-ffffffff81281aac: tracer_tracing_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void tracer_tracing_on(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81298f62)
Location: kernel/trace/trace.c:1000
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_on
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceon
  - kernel/trace/trace_functions.c:ftrace_traceon_count
  - kernel/trace/trace_events_trigger.c:traceon_count_trigger
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff8129c930-ffffffff8129c95c: tracer_tracing_on (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void tracer_tracing_on(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff80001021e7a8)
Location: kernel/trace/trace.c:782
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_on
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceon
```
**Symbols:**

```
ffff8000102241a0-ffff8000102241d0: tracer_tracing_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void tracer_tracing_on(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c045c678)
Location: kernel/trace/trace.c:782
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_on
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceon
  - kernel/trace/trace_functions.c:ftrace_traceon_count
```
**Symbols:**

```
c046191c-c046194c: tracer_tracing_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void tracer_tracing_on(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002a1a20)
Location: kernel/trace/trace.c:782
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_on
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceon
```
**Symbols:**

```
c0000000002a9090-c0000000002a90e0: tracer_tracing_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void tracer_tracing_on(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe00017b156)
Location: kernel/trace/trace.c:782
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_on
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceon
```
**Symbols:**

```
ffffffe00017f6de-ffffffe00017f708: tracer_tracing_on (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void tracer_tracing_on(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119bb26)
Location: kernel/trace/trace.c:782
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_on
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceon
```
**Symbols:**

```
ffffffff811a01a0-ffffffff811a01c3: tracer_tracing_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void tracer_tracing_on(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118eba6)
Location: kernel/trace/trace.c:782
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_on
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceon
```
**Symbols:**

```
ffffffff811931b0-ffffffff811931d3: tracer_tracing_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void tracer_tracing_on(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811998f6)
Location: kernel/trace/trace.c:782
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_on
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceon
```
**Symbols:**

```
ffffffff8119df70-ffffffff8119df93: tracer_tracing_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void tracer_tracing_on(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a7596)
Location: kernel/trace/trace.c:782
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_on
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceon
```
**Symbols:**

```
ffffffff811abc50-ffffffff811abc73: tracer_tracing_on (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
