# Function: <code>trace_dump_stack</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void trace_dump_stack(int skip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8114f980)
Location: kernel/trace/trace.c:1900
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_stacktrace
  - kernel/trace/trace_functions.c:ftrace_stacktrace_count
  - kernel/trace/trace_events_trigger.c:stacktrace_count_trigger
```
**Symbols:**

```
ffffffff8114f980-ffffffff8114f9c3: trace_dump_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void trace_dump_stack(int skip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811589f0)
Location: kernel/trace/trace.c:2272
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_stacktrace_count
  - kernel/trace/trace_functions.c:ftrace_stacktrace
  - kernel/trace/trace_events_trigger.c:stacktrace_count_trigger
```
**Symbols:**

```
ffffffff811589f0-ffffffff81158a34: trace_dump_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void trace_dump_stack(int skip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81162fb0)
Location: kernel/trace/trace.c:2496
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_stacktrace_count
  - kernel/trace/trace_functions.c:ftrace_stacktrace
  - kernel/trace/trace_events_trigger.c:stacktrace_count_trigger
```
**Symbols:**

```
ffffffff81162fb0-ffffffff81162ff4: trace_dump_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void trace_dump_stack(int skip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81166450)
Location: kernel/trace/trace.c:2702
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:stacktrace_count_trigger
```
**Symbols:**

```
ffffffff81166450-ffffffff81166494: trace_dump_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void trace_dump_stack(int skip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811733e0)
Location: kernel/trace/trace.c:2712
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:stacktrace_count_trigger
```
**Symbols:**

```
ffffffff811733e0-ffffffff81173424: trace_dump_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void trace_dump_stack(int skip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811823c0)
Location: kernel/trace/trace.c:2713
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:stacktrace_count_trigger
```
**Symbols:**

```
ffffffff811823c0-ffffffff81182403: trace_dump_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void trace_dump_stack(int skip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118e140)
Location: kernel/trace/trace.c:2714
Inline: True
Direct callers:
  - kernel/trace/trace_events_trigger.c:stacktrace_count_trigger
```
**Symbols:**

```
ffffffff8118e140-ffffffff8118e183: trace_dump_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void trace_dump_stack(int skip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119bac0)
Location: kernel/trace/trace.c:2891
Inline: True
Direct callers:
  - kernel/trace/trace_events_trigger.c:stacktrace_count_trigger
```
**Symbols:**

```
ffffffff8119bac0-ffffffff8119bb03: trace_dump_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void trace_dump_stack(int skip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a74b0)
Location: kernel/trace/trace.c:2917
Inline: True
Direct callers:
  - kernel/trace/trace_events_trigger.c:stacktrace_count_trigger
```
**Symbols:**

```
ffffffff811a74b0-ffffffff811a74f3: trace_dump_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void trace_dump_stack(int skip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bd500)
Location: kernel/trace/trace.c:3028
Inline: True
Direct callers:
  - kernel/trace/trace_events_trigger.c:stacktrace_count_trigger
```
**Symbols:**

```
ffffffff811bd500-ffffffff811bd543: trace_dump_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void trace_dump_stack(int skip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bb110)
Location: kernel/trace/trace.c:3046
Inline: True
Direct callers:
  - kernel/trace/trace_events_trigger.c:stacktrace_count_trigger
```
**Symbols:**

```
ffffffff811bb110-ffffffff811bb153: trace_dump_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void trace_dump_stack(int skip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811be700)
Location: kernel/trace/trace.c:3067
Inline: True
Direct callers:
  - kernel/trace/trace_events_trigger.c:stacktrace_count_trigger
```
**Symbols:**

```
ffffffff811be700-ffffffff811be74b: trace_dump_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void trace_dump_stack(int skip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811e8fc0)
Location: kernel/trace/trace.c:3127
Inline: True
Direct callers:
  - kernel/trace/trace_events_trigger.c:stacktrace_trigger
```
**Symbols:**

```
ffffffff81cb52a5-ffffffff81cb52ba: trace_dump_stack.cold (STB_LOCAL)
ffffffff811e8f90-ffffffff811e8ff3: trace_dump_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void trace_dump_stack(int skip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8122116e)
Location: kernel/trace/trace.c:3125
Inline: True
```
**Symbols:**

```
ffffffff81e6634c-ffffffff81e66361: trace_dump_stack.cold (STB_LOCAL)
ffffffff81221130-ffffffff812211bc: trace_dump_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void trace_dump_stack(int skip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8126bdae)
Location: kernel/trace/trace.c:3149
Inline: True
```
**Symbols:**

```
ffffffff8205d5df-ffffffff8205d5f4: trace_dump_stack.cold (STB_LOCAL)
ffffffff8126bd70-ffffffff8126bdfc: trace_dump_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void trace_dump_stack(int skip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81282cf0)
Location: kernel/trace/trace.c:3240
Inline: True
```
**Symbols:**

```
ffffffff81282cf0-ffffffff81282d50: trace_dump_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void trace_dump_stack(int skip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8129dde0)
Location: kernel/trace/trace.c:3217
Inline: True
```
**Symbols:**

```
ffffffff8129dde0-ffffffff8129de40: trace_dump_stack (STB_GLOBAL)
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
void trace_dump_stack(int skip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff800010222b30)
Location: kernel/trace/trace.c:2917
Inline: True
Direct callers:
  - kernel/trace/trace_events_trigger.c:stacktrace_count_trigger
```
**Symbols:**

```
ffff800010222b30-ffff800010222b7c: trace_dump_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void trace_dump_stack(int skip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c045f418)
Location: kernel/trace/trace.c:2917
Inline: True
Direct callers:
  - kernel/trace/trace_events_trigger.c:stacktrace_count_trigger
```
**Symbols:**

```
c045f418-c045f484: trace_dump_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void trace_dump_stack(int skip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002a5770)
Location: kernel/trace/trace.c:2917
Inline: True
Direct callers:
  - kernel/trace/trace_events_trigger.c:stacktrace_count_trigger
```
**Symbols:**

```
c0000000002a5770-c0000000002a57c4: trace_dump_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void trace_dump_stack(int skip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe00017e2be)
Location: kernel/trace/trace.c:2917
Inline: True
Direct callers:
  - kernel/trace/trace_events_trigger.c:stacktrace_count_trigger
```
**Symbols:**

```
ffffffe00017e2be-ffffffe00017e304: trace_dump_stack (STB_GLOBAL)
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
void trace_dump_stack(int skip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119fad0)
Location: kernel/trace/trace.c:2917
Inline: True
Direct callers:
  - kernel/trace/trace_events_trigger.c:stacktrace_count_trigger
```
**Symbols:**

```
ffffffff8119fad0-ffffffff8119fb13: trace_dump_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void trace_dump_stack(int skip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81192b10)
Location: kernel/trace/trace.c:2917
Inline: True
Direct callers:
  - kernel/trace/trace_events_trigger.c:stacktrace_count_trigger
```
**Symbols:**

```
ffffffff81192b10-ffffffff81192b4b: trace_dump_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void trace_dump_stack(int skip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119d8a0)
Location: kernel/trace/trace.c:2917
Inline: True
Direct callers:
  - kernel/trace/trace_events_trigger.c:stacktrace_count_trigger
```
**Symbols:**

```
ffffffff8119d8a0-ffffffff8119d8e3: trace_dump_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void trace_dump_stack(int skip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811ab560)
Location: kernel/trace/trace.c:2917
Inline: True
Direct callers:
  - kernel/trace/trace_events_trigger.c:stacktrace_count_trigger
```
**Symbols:**

```
ffffffff811ab560-ffffffff811ab5a3: trace_dump_stack (STB_GLOBAL)
```
</details>
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
