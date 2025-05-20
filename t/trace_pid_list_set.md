# Function: <code>trace_pid_list_set</code>

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
int trace_pid_list_set(struct trace_pid_list *pid_list, unsigned int pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/pid_list.c (ffffffff8122b4d0)
Location: kernel/trace/pid_list.c:168
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_filter_add_remove_task
```
**Symbols:**

```
ffffffff8122b4d0-ffffffff8122b682: trace_pid_list_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int trace_pid_list_set(struct trace_pid_list *pid_list, unsigned int pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/pid_list.c (ffffffff81276ea0)
Location: kernel/trace/pid_list.c:168
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_filter_add_remove_task
```
**Symbols:**

```
ffffffff81276ea0-ffffffff81277052: trace_pid_list_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int trace_pid_list_set(struct trace_pid_list *pid_list, unsigned int pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/pid_list.c (ffffffff8128e890)
Location: kernel/trace/pid_list.c:168
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_filter_add_remove_task
```
**Symbols:**

```
ffffffff8128e890-ffffffff8128ea42: trace_pid_list_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int trace_pid_list_set(struct trace_pid_list *pid_list, unsigned int pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/pid_list.c (ffffffff812a9d60)
Location: kernel/trace/pid_list.c:168
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_filter_add_remove_task
```
**Symbols:**

```
ffffffff812a9d60-ffffffff812a9f12: trace_pid_list_set (STB_GLOBAL)
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
