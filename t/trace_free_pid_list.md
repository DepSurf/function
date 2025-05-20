# Function: <code>trace_free_pid_list</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void trace_free_pid_list(struct trace_pid_list *pid_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81156ce7)
Location: kernel/trace/trace.c:322
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
**Symbols:**

```
ffffffff811566d0-ffffffff811566ec: trace_free_pid_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void trace_free_pid_list(struct trace_pid_list *pid_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81161e27)
Location: kernel/trace/trace.c:324
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
**Symbols:**

```
ffffffff811617e0-ffffffff811617fc: trace_free_pid_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void trace_free_pid_list(struct trace_pid_list *pid_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8116522b)
Location: kernel/trace/trace.c:316
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
**Symbols:**

```
ffffffff81164b60-ffffffff81164b7c: trace_free_pid_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void trace_free_pid_list(struct trace_pid_list *pid_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8117217b)
Location: kernel/trace/trace.c:316
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
**Symbols:**

```
ffffffff81171aa0-ffffffff81171abc: trace_free_pid_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void trace_free_pid_list(struct trace_pid_list *pid_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118138d)
Location: kernel/trace/trace.c:317
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
**Symbols:**

```
ffffffff81180bf0-ffffffff81180c0c: trace_free_pid_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void trace_free_pid_list(struct trace_pid_list *pid_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118ed4d)
Location: kernel/trace/trace.c:318
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
**Symbols:**

```
ffffffff8118e5b0-ffffffff8118e5cc: trace_free_pid_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void trace_free_pid_list(struct trace_pid_list *pid_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119c69d)
Location: kernel/trace/trace.c:320
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
**Symbols:**

```
ffffffff8119bfd0-ffffffff8119bfee: trace_free_pid_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void trace_free_pid_list(struct trace_pid_list *pid_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a808d)
Location: kernel/trace/trace.c:338
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
**Symbols:**

```
ffffffff811a79c0-ffffffff811a79de: trace_free_pid_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void trace_free_pid_list(struct trace_pid_list *pid_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811c0434)
Location: kernel/trace/trace.c:353
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
Direct callers:
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
**Symbols:**

```
ffffffff811bfd20-ffffffff811bfd40: trace_free_pid_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void trace_free_pid_list(struct trace_pid_list *pid_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811be05a)
Location: kernel/trace/trace.c:504
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
Direct callers:
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
**Symbols:**

```
ffffffff811bd950-ffffffff811bd970: trace_free_pid_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void trace_free_pid_list(struct trace_pid_list *pid_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bdb80)
Location: kernel/trace/trace.c:506
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
Direct callers:
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
**Symbols:**

```
ffffffff811bd450-ffffffff811bd470: trace_free_pid_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void trace_free_pid_list(struct trace_pid_list *pid_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811e86d0)
Location: kernel/trace/trace.c:519
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
Direct callers:
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
**Symbols:**

```
ffffffff811e7f40-ffffffff811e7f60: trace_free_pid_list (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void trace_free_pid_list(struct trace_pid_list *pid_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff800010224ae0)
Location: kernel/trace/trace.c:338
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
**Symbols:**

```
ffff800010223ef8-ffff800010223f24: trace_free_pid_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void trace_free_pid_list(struct trace_pid_list *pid_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0461f88)
Location: kernel/trace/trace.c:338
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
**Symbols:**

```
c0461664-c0461688: trace_free_pid_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void trace_free_pid_list(struct trace_pid_list *pid_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002a9a6c)
Location: kernel/trace/trace.c:338
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
**Symbols:**

```
c0000000002a8ca0-c0000000002a8ce8: trace_free_pid_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void trace_free_pid_list(struct trace_pid_list *pid_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe00017fc2c)
Location: kernel/trace/trace.c:338
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
**Symbols:**

```
ffffffe00017f48e-ffffffe00017f4b8: trace_free_pid_list (STB_GLOBAL)
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
void trace_free_pid_list(struct trace_pid_list *pid_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a06ad)
Location: kernel/trace/trace.c:338
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
**Symbols:**

```
ffffffff8119ffe0-ffffffff8119fffe: trace_free_pid_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void trace_free_pid_list(struct trace_pid_list *pid_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811936bd)
Location: kernel/trace/trace.c:338
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
**Symbols:**

```
ffffffff81192ff0-ffffffff8119300e: trace_free_pid_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void trace_free_pid_list(struct trace_pid_list *pid_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119e47d)
Location: kernel/trace/trace.c:338
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
**Symbols:**

```
ffffffff8119ddb0-ffffffff8119ddce: trace_free_pid_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void trace_free_pid_list(struct trace_pid_list *pid_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811ac15d)
Location: kernel/trace/trace.c:338
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
**Symbols:**

```
ffffffff811aba90-ffffffff811abaae: trace_free_pid_list (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
