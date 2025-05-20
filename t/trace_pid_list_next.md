# Function: <code>trace_pid_list_next</code>

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
int trace_pid_list_next(struct trace_pid_list *pid_list, unsigned int pid, unsigned int *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/pid_list.c (ffffffff8122b7f0)
Location: kernel/trace/pid_list.c:273
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_start
  - kernel/trace/pid_list.c:trace_pid_list_first
```
**Symbols:**

```
ffffffff8122b7f0-ffffffff8122b94b: trace_pid_list_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int trace_pid_list_next(struct trace_pid_list *pid_list, unsigned int pid, unsigned int *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/pid_list.c (ffffffff812771e0)
Location: kernel/trace/pid_list.c:273
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_start
  - kernel/trace/pid_list.c:trace_pid_list_first
```
**Symbols:**

```
ffffffff812771e0-ffffffff8127731e: trace_pid_list_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int trace_pid_list_next(struct trace_pid_list *pid_list, unsigned int pid, unsigned int *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/pid_list.c (ffffffff8128ebd0)
Location: kernel/trace/pid_list.c:273
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_start
  - kernel/trace/pid_list.c:trace_pid_list_first
```
**Symbols:**

```
ffffffff8128ebd0-ffffffff8128ed3d: trace_pid_list_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int trace_pid_list_next(struct trace_pid_list *pid_list, unsigned int pid, unsigned int *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/pid_list.c (ffffffff812aa0a0)
Location: kernel/trace/pid_list.c:273
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_start
  - kernel/trace/pid_list.c:trace_pid_list_first
```
**Symbols:**

```
ffffffff812aa0a0-ffffffff812aa20d: trace_pid_list_next (STB_GLOBAL)
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
