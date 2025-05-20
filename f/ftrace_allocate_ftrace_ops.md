# Function: <code>ftrace_allocate_ftrace_ops</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ftrace_allocate_ftrace_ops(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_functions.c (ffffffff811c80d0)
Location: kernel/trace/trace_functions.c:37
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffff811c80d0-ffffffff811c8133: ftrace_allocate_ftrace_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ftrace_allocate_ftrace_ops(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_functions.c (ffffffff811c95e0)
Location: kernel/trace/trace_functions.c:52
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffff811c95e0-ffffffff811c9643: ftrace_allocate_ftrace_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ftrace_allocate_ftrace_ops(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_functions.c (ffffffff811f5070)
Location: kernel/trace/trace_functions.c:52
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffff811f5070-ffffffff811f50d3: ftrace_allocate_ftrace_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ftrace_allocate_ftrace_ops(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_functions.c (ffffffff8122e840)
Location: kernel/trace/trace_functions.c:52
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffff8122e840-ffffffff8122e8ac: ftrace_allocate_ftrace_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ftrace_allocate_ftrace_ops(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_functions.c (ffffffff8127a7a0)
Location: kernel/trace/trace_functions.c:52
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffff8127a7a0-ffffffff8127a80c: ftrace_allocate_ftrace_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ftrace_allocate_ftrace_ops(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_functions.c (ffffffff812922c0)
Location: kernel/trace/trace_functions.c:52
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffff812922c0-ffffffff8129232c: ftrace_allocate_ftrace_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ftrace_allocate_ftrace_ops(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_functions.c (ffffffff812ad8d0)
Location: kernel/trace/trace_functions.c:52
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_create_systems
```
**Symbols:**

```
ffffffff812ad8d0-ffffffff812ad96b: ftrace_allocate_ftrace_ops (STB_GLOBAL)
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
