# Function: <code>tracing_snapshot_instance</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tracing_snapshot_instance(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81165c30)
Location: kernel/trace/trace.c:897
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_count_snapshot
  - kernel/trace/trace.c:ftrace_snapshot
  - kernel/trace/trace.c:tracing_snapshot_alloc
```
**Symbols:**

```
ffffffff81165c30-ffffffff81165da2: tracing_snapshot_instance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tracing_snapshot_instance(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81172bc0)
Location: kernel/trace/trace.c:897
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_count_snapshot
  - kernel/trace/trace.c:ftrace_snapshot
  - kernel/trace/trace.c:tracing_snapshot_alloc
```
**Symbols:**

```
ffffffff81172bc0-ffffffff81172d32: tracing_snapshot_instance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tracing_snapshot_instance(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81181bc0)
Location: kernel/trace/trace.c:896
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_count_snapshot
  - kernel/trace/trace.c:ftrace_snapshot
  - kernel/trace/trace.c:tracing_snapshot_alloc
```
**Symbols:**

```
ffffffff81181bc0-ffffffff81181d1c: tracing_snapshot_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tracing_snapshot_instance(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118f580)
Location: kernel/trace/trace.c:897
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_count_snapshot
  - kernel/trace/trace.c:ftrace_snapshot
  - kernel/trace/trace.c:tracing_snapshot_alloc
```
**Symbols:**

```
ffffffff8118f580-ffffffff8118f6dc: tracing_snapshot_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void tracing_snapshot_instance(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119d17d)
Location: kernel/trace/trace.c:931
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_count_snapshot
  - kernel/trace/trace.c:ftrace_snapshot
```
**Symbols:**

```
ffffffff8119d0f0-ffffffff8119d0fd: tracing_snapshot_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void tracing_snapshot_instance(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a8b2d)
Location: kernel/trace/trace.c:949
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_count_snapshot
  - kernel/trace/trace.c:ftrace_snapshot
```
**Symbols:**

```
ffffffff811a8aa0-ffffffff811a8aad: tracing_snapshot_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void tracing_snapshot_instance(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811c0cad)
Location: kernel/trace/trace.c:981
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_count_snapshot
  - kernel/trace/trace.c:ftrace_snapshot
Direct callers:
  - kernel/trace/trace_events_trigger.c:snapshot_count_trigger
```
**Symbols:**

```
ffffffff811c0bf0-ffffffff811c0bfd: tracing_snapshot_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void tracing_snapshot_instance(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811be8dd)
Location: kernel/trace/trace.c:1132
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_count_snapshot
  - kernel/trace/trace.c:ftrace_snapshot
Direct callers:
  - kernel/trace/trace_events_trigger.c:snapshot_count_trigger
```
**Symbols:**

```
ffffffff811be820-ffffffff811be82d: tracing_snapshot_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void tracing_snapshot_instance(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bed9d)
Location: kernel/trace/trace.c:1129
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_count_snapshot
  - kernel/trace/trace.c:ftrace_snapshot
```
**Symbols:**

```
ffffffff811bece0-ffffffff811beced: tracing_snapshot_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void tracing_snapshot_instance(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811e95cd)
Location: kernel/trace/trace.c:1142
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_count_snapshot
  - kernel/trace/trace.c:ftrace_snapshot
```
**Symbols:**

```
ffffffff811e9500-ffffffff811e950d: tracing_snapshot_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void tracing_snapshot_instance(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff83485dcb)
Location: kernel/trace/trace.c:1132
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_boot_snapshot
  - kernel/trace/trace.c:ftrace_count_snapshot
  - kernel/trace/trace.c:ftrace_snapshot
```
**Symbols:**

```
ffffffff81221950-ffffffff81221965: tracing_snapshot_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void tracing_snapshot_instance(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff83eb4c48)
Location: kernel/trace/trace.c:1131
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_boot_snapshot
  - kernel/trace/trace.c:ftrace_count_snapshot
  - kernel/trace/trace.c:ftrace_snapshot
```
**Symbols:**

```
ffffffff8126c850-ffffffff8126c865: tracing_snapshot_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void tracing_snapshot_instance(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff836d9f79)
Location: kernel/trace/trace.c:1182
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_boot_snapshot
  - kernel/trace/trace.c:ftrace_count_snapshot
  - kernel/trace/trace.c:ftrace_snapshot
```
**Symbols:**

```
ffffffff812839e0-ffffffff812839f5: tracing_snapshot_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void tracing_snapshot_instance(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8390c4e2)
Location: kernel/trace/trace.c:1184
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_boot_snapshot
  - kernel/trace/trace.c:ftrace_count_snapshot
  - kernel/trace/trace.c:ftrace_snapshot
```
**Symbols:**

```
ffffffff8129eae0-ffffffff8129eaf5: tracing_snapshot_instance (STB_GLOBAL)
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
void tracing_snapshot_instance(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff800010225710)
Location: kernel/trace/trace.c:949
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_count_snapshot
  - kernel/trace/trace.c:ftrace_snapshot
```
**Symbols:**

```
ffff800010225658-ffff800010225670: tracing_snapshot_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void tracing_snapshot_instance(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0462c04)
Location: kernel/trace/trace.c:949
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_count_snapshot
  - kernel/trace/trace.c:ftrace_snapshot
```
**Symbols:**

```
c0462b40-c0462b58: tracing_snapshot_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void tracing_snapshot_instance(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002aae28)
Location: kernel/trace/trace.c:949
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_count_snapshot
  - kernel/trace/trace.c:ftrace_snapshot
```
**Symbols:**

```
c0000000002aad30-c0000000002aad40: tracing_snapshot_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void tracing_snapshot_instance(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe0001805ce)
Location: kernel/trace/trace.c:949
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_count_snapshot
  - kernel/trace/trace.c:ftrace_snapshot
```
**Symbols:**

```
ffffffe000180522-ffffffe00018053c: tracing_snapshot_instance (STB_GLOBAL)
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
void tracing_snapshot_instance(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a114d)
Location: kernel/trace/trace.c:949
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_count_snapshot
  - kernel/trace/trace.c:ftrace_snapshot
```
**Symbols:**

```
ffffffff811a10c0-ffffffff811a10cd: tracing_snapshot_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void tracing_snapshot_instance(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119411d)
Location: kernel/trace/trace.c:949
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_count_snapshot
  - kernel/trace/trace.c:ftrace_snapshot
```
**Symbols:**

```
ffffffff81194090-ffffffff8119409d: tracing_snapshot_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void tracing_snapshot_instance(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119ef1d)
Location: kernel/trace/trace.c:949
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_count_snapshot
  - kernel/trace/trace.c:ftrace_snapshot
```
**Symbols:**

```
ffffffff8119ee90-ffffffff8119ee9d: tracing_snapshot_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void tracing_snapshot_instance(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811acc1d)
Location: kernel/trace/trace.c:949
Inline: True
Inline callers:
  - kernel/trace/trace.c:ftrace_count_snapshot
  - kernel/trace/trace.c:ftrace_snapshot
```
**Symbols:**

```
ffffffff811acb90-ffffffff811acb9d: tracing_snapshot_instance (STB_GLOBAL)
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
