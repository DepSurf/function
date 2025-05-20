# Function: <code>tracing_snapshot_instance_cond</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tracing_snapshot_instance_cond(struct trace_array *tr, void *cond_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119cf80)
Location: kernel/trace/trace.c:901
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_count_snapshot
  - kernel/trace/trace.c:ftrace_snapshot
  - kernel/trace/trace.c:tracing_snapshot_cond
```
**Symbols:**

```
ffffffff8119cf80-ffffffff8119d0e2: tracing_snapshot_instance_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tracing_snapshot_instance_cond(struct trace_array *tr, void *cond_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a8930)
Location: kernel/trace/trace.c:919
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_count_snapshot
  - kernel/trace/trace.c:ftrace_snapshot
  - kernel/trace/trace.c:tracing_snapshot_cond
```
**Symbols:**

```
ffffffff811a8930-ffffffff811a8a92: tracing_snapshot_instance_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tracing_snapshot_instance_cond(struct trace_array *tr, void *cond_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811c0a80)
Location: kernel/trace/trace.c:950
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_count_snapshot
  - kernel/trace/trace.c:ftrace_snapshot
  - kernel/trace/trace.c:tracing_snapshot_cond
```
**Symbols:**

```
ffffffff811c0a80-ffffffff811c0bea: tracing_snapshot_instance_cond (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tracing_snapshot_instance_cond(struct trace_array *tr, void *cond_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811be6b0)
Location: kernel/trace/trace.c:1101
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_count_snapshot
  - kernel/trace/trace.c:ftrace_snapshot
  - kernel/trace/trace.c:tracing_snapshot_cond
```
**Symbols:**

```
ffffffff811be6b0-ffffffff811be81a: tracing_snapshot_instance_cond (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tracing_snapshot_instance_cond(struct trace_array *tr, void *cond_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bea90)
Location: kernel/trace/trace.c:1098
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_count_snapshot
  - kernel/trace/trace.c:ftrace_snapshot
  - kernel/trace/trace.c:tracing_snapshot_cond
```
**Symbols:**

```
ffffffff811bea90-ffffffff811becd1: tracing_snapshot_instance_cond (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void tracing_snapshot_instance_cond(struct trace_array *tr, void *cond_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:1111
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_count_snapshot
  - kernel/trace/trace.c:ftrace_snapshot
  - kernel/trace/trace.c:tracing_snapshot_cond
```
**Symbols:**

```
ffffffff811e9380-ffffffff811e94ff: tracing_snapshot_instance_cond (STB_LOCAL)
ffffffff81cb52d4-ffffffff81cb530c: tracing_snapshot_instance_cond.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void tracing_snapshot_instance_cond(struct trace_array *tr, void *cond_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:1101
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_boot_snapshot
  - kernel/trace/trace.c:ftrace_count_snapshot
  - kernel/trace/trace.c:ftrace_snapshot
  - kernel/trace/trace.c:tracing_snapshot_cond
```
**Symbols:**

```
ffffffff812217a0-ffffffff81221950: tracing_snapshot_instance_cond (STB_LOCAL)
ffffffff81e663a0-ffffffff81e663da: tracing_snapshot_instance_cond.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void tracing_snapshot_instance_cond(struct trace_array *tr, void *cond_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:1100
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_boot_snapshot
  - kernel/trace/trace.c:ftrace_count_snapshot
  - kernel/trace/trace.c:ftrace_snapshot
  - kernel/trace/trace.c:tracing_snapshot_cond
```
**Symbols:**

```
ffffffff8126c690-ffffffff8126c839: tracing_snapshot_instance_cond (STB_LOCAL)
ffffffff8205d633-ffffffff8205d65d: tracing_snapshot_instance_cond.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void tracing_snapshot_instance_cond(struct trace_array *tr, void *cond_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:1151
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_boot_snapshot
  - kernel/trace/trace.c:ftrace_count_snapshot
  - kernel/trace/trace.c:ftrace_snapshot
  - kernel/trace/trace.c:tracing_snapshot_cond
```
**Symbols:**

```
ffffffff81283810-ffffffff812839c5: tracing_snapshot_instance_cond (STB_LOCAL)
ffffffff820dbf73-ffffffff820dbf9d: tracing_snapshot_instance_cond.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void tracing_snapshot_instance_cond(struct trace_array *tr, void *cond_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:1153
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_boot_snapshot
  - kernel/trace/trace.c:ftrace_count_snapshot
  - kernel/trace/trace.c:ftrace_snapshot
  - kernel/trace/trace.c:tracing_snapshot_cond
```
**Symbols:**

```
ffffffff8129e910-ffffffff8129eac2: tracing_snapshot_instance_cond (STB_LOCAL)
ffffffff821b7e01-ffffffff821b7e2b: tracing_snapshot_instance_cond.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void tracing_snapshot_instance_cond(struct trace_array *tr, void *cond_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff8000102254a8)
Location: kernel/trace/trace.c:919
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_count_snapshot
  - kernel/trace/trace.c:ftrace_snapshot
  - kernel/trace/trace.c:tracing_snapshot_cond
```
**Symbols:**

```
ffff8000102254a8-ffff800010225654: tracing_snapshot_instance_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tracing_snapshot_instance_cond(struct trace_array *tr, void *cond_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c04629b0)
Location: kernel/trace/trace.c:919
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_count_snapshot
  - kernel/trace/trace.c:ftrace_snapshot
  - kernel/trace/trace.c:tracing_snapshot_cond
```
**Symbols:**

```
c04629b0-c0462b40: tracing_snapshot_instance_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tracing_snapshot_instance_cond(struct trace_array *tr, void *cond_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002aab40)
Location: kernel/trace/trace.c:919
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_count_snapshot
  - kernel/trace/trace.c:ftrace_count_snapshot
  - kernel/trace/trace.c:ftrace_snapshot
  - kernel/trace/trace.c:tracing_snapshot_cond
```
**Symbols:**

```
c0000000002aab40-c0000000002aad30: tracing_snapshot_instance_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tracing_snapshot_instance_cond(struct trace_array *tr, void *cond_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe00018039e)
Location: kernel/trace/trace.c:919
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_count_snapshot
  - kernel/trace/trace.c:ftrace_snapshot
  - kernel/trace/trace.c:tracing_snapshot_cond
```
**Symbols:**

```
ffffffe00018039e-ffffffe000180522: tracing_snapshot_instance_cond (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void tracing_snapshot_instance_cond(struct trace_array *tr, void *cond_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a0f50)
Location: kernel/trace/trace.c:919
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_count_snapshot
  - kernel/trace/trace.c:ftrace_snapshot
  - kernel/trace/trace.c:tracing_snapshot_cond
```
**Symbols:**

```
ffffffff811a0f50-ffffffff811a10b2: tracing_snapshot_instance_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tracing_snapshot_instance_cond(struct trace_array *tr, void *cond_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81193f40)
Location: kernel/trace/trace.c:919
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_count_snapshot
  - kernel/trace/trace.c:ftrace_snapshot
  - kernel/trace/trace.c:tracing_snapshot_cond
```
**Symbols:**

```
ffffffff81193f40-ffffffff81194082: tracing_snapshot_instance_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tracing_snapshot_instance_cond(struct trace_array *tr, void *cond_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119ed20)
Location: kernel/trace/trace.c:919
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_count_snapshot
  - kernel/trace/trace.c:ftrace_snapshot
  - kernel/trace/trace.c:tracing_snapshot_cond
```
**Symbols:**

```
ffffffff8119ed20-ffffffff8119ee82: tracing_snapshot_instance_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tracing_snapshot_instance_cond(struct trace_array *tr, void *cond_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811aca20)
Location: kernel/trace/trace.c:919
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_count_snapshot
  - kernel/trace/trace.c:ftrace_snapshot
  - kernel/trace/trace.c:tracing_snapshot_cond
```
**Symbols:**

```
ffffffff811aca20-ffffffff811acb82: tracing_snapshot_instance_cond (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
