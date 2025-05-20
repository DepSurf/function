# Function: <code>trace_pid_list_first</code>

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
int trace_pid_list_first(struct trace_pid_list *pid_list, unsigned int *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/pid_list.c (ffffffff8122b950)
Location: kernel/trace/pid_list.c:327
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_start
  - kernel/trace/trace_events.c:trace_create_new_event
  - kernel/trace/trace_events.c:trace_create_new_event
```
**Symbols:**

```
ffffffff8122b950-ffffffff8122b96a: trace_pid_list_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int trace_pid_list_first(struct trace_pid_list *pid_list, unsigned int *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/pid_list.c (ffffffff81277330)
Location: kernel/trace/pid_list.c:327
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_start
  - kernel/trace/trace_events.c:trace_create_new_event
  - kernel/trace/trace_events.c:trace_create_new_event
```
**Symbols:**

```
ffffffff81277330-ffffffff8127734a: trace_pid_list_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int trace_pid_list_first(struct trace_pid_list *pid_list, unsigned int *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/pid_list.c (ffffffff8128ed50)
Location: kernel/trace/pid_list.c:327
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_start
  - kernel/trace/trace_events.c:trace_create_new_event
  - kernel/trace/trace_events.c:trace_create_new_event
```
**Symbols:**

```
ffffffff8128ed50-ffffffff8128ed6a: trace_pid_list_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int trace_pid_list_first(struct trace_pid_list *pid_list, unsigned int *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/pid_list.c (ffffffff812aa220)
Location: kernel/trace/pid_list.c:327
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_start
  - kernel/trace/trace_events.c:trace_create_new_event
  - kernel/trace/trace_events.c:trace_create_new_event
```
**Symbols:**

```
ffffffff812aa220-ffffffff812aa23a: trace_pid_list_first (STB_GLOBAL)
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
