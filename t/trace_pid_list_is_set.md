# Function: <code>trace_pid_list_is_set</code>

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
bool trace_pid_list_is_set(struct trace_pid_list *pid_list, unsigned int pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/pid_list.c (ffffffff8122b400)
Location: kernel/trace/pid_list.c:129
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
  - kernel/trace/trace.c:trace_ignore_this_task
  - kernel/trace/trace.c:trace_ignore_this_task
```
**Symbols:**

```
ffffffff8122b400-ffffffff8122b4cd: trace_pid_list_is_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool trace_pid_list_is_set(struct trace_pid_list *pid_list, unsigned int pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/pid_list.c (ffffffff81276dc0)
Location: kernel/trace/pid_list.c:129
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
  - kernel/trace/trace.c:trace_ignore_this_task
  - kernel/trace/trace.c:trace_ignore_this_task
```
**Symbols:**

```
ffffffff81276dc0-ffffffff81276e8d: trace_pid_list_is_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool trace_pid_list_is_set(struct trace_pid_list *pid_list, unsigned int pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/pid_list.c (ffffffff8128e7b0)
Location: kernel/trace/pid_list.c:129
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
  - kernel/trace/trace.c:trace_ignore_this_task
  - kernel/trace/trace.c:trace_ignore_this_task
```
**Symbols:**

```
ffffffff8128e7b0-ffffffff8128e87d: trace_pid_list_is_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool trace_pid_list_is_set(struct trace_pid_list *pid_list, unsigned int pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/pid_list.c (ffffffff812a9c80)
Location: kernel/trace/pid_list.c:129
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_filter_add_remove_task
  - kernel/trace/trace.c:trace_ignore_this_task
  - kernel/trace/trace.c:trace_ignore_this_task
```
**Symbols:**

```
ffffffff812a9c80-ffffffff812a9d4d: trace_pid_list_is_set (STB_GLOBAL)
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
