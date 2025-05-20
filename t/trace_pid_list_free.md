# Function: <code>trace_pid_list_free</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void trace_pid_list_free(struct trace_pid_list *pid_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/pid_list.c (ffffffff8122ba70)
Location: kernel/trace/pid_list.c:457
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
**Symbols:**

```
ffffffff8122ba70-ffffffff8122bb6e: trace_pid_list_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void trace_pid_list_free(struct trace_pid_list *pid_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/pid_list.c (ffffffff81277470)
Location: kernel/trace/pid_list.c:457
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
**Symbols:**

```
ffffffff81277470-ffffffff8127756e: trace_pid_list_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void trace_pid_list_free(struct trace_pid_list *pid_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/pid_list.c (ffffffff8128ee90)
Location: kernel/trace/pid_list.c:457
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
**Symbols:**

```
ffffffff8128ee90-ffffffff8128efa4: trace_pid_list_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void trace_pid_list_free(struct trace_pid_list *pid_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/pid_list.c (ffffffff812aa3f0)
Location: kernel/trace/pid_list.c:457
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
**Symbols:**

```
ffffffff812aa3f0-ffffffff812aa504: trace_pid_list_free (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
