# Function: <code>trace_pid_list_alloc</code>

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
struct trace_pid_list *trace_pid_list_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/pid_list.c (ffffffff8122b970)
Location: kernel/trace/pid_list.c:411
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_pid_write
```
**Symbols:**

```
ffffffff8122b970-ffffffff8122ba66: trace_pid_list_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct trace_pid_list *trace_pid_list_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/pid_list.c (ffffffff81277360)
Location: kernel/trace/pid_list.c:411
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_pid_write
```
**Symbols:**

```
ffffffff81277360-ffffffff81277456: trace_pid_list_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct trace_pid_list *trace_pid_list_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/pid_list.c (ffffffff8128ed80)
Location: kernel/trace/pid_list.c:411
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_pid_write
```
**Symbols:**

```
ffffffff8128ed80-ffffffff8128ee76: trace_pid_list_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct trace_pid_list *trace_pid_list_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/pid_list.c (ffffffff812aa250)
Location: kernel/trace/pid_list.c:411
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_pid_write
```
**Symbols:**

```
ffffffff812aa250-ffffffff812aa3d7: trace_pid_list_alloc (STB_GLOBAL)
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
