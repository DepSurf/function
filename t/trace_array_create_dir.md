# Function: <code>trace_array_create_dir</code>

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
int trace_array_create_dir(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bca60)
Location: kernel/trace/trace.c:8676
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffff811bca60-ffffffff811bcafa: trace_array_create_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int trace_array_create_dir(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bc550)
Location: kernel/trace/trace.c:9012
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffff811bc550-ffffffff811bc5f2: trace_array_create_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int trace_array_create_dir(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811e6fb0)
Location: kernel/trace/trace.c:9176
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffff811e6fb0-ffffffff811e7052: trace_array_create_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int trace_array_create_dir(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8121ef41)
Location: kernel/trace/trace.c:9209
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs_work_func
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffff8121ef00-ffffffff8121efd4: trace_array_create_dir (STB_LOCAL)
ffffffff81e6628d-ffffffff81e662a2: trace_array_create_dir.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int trace_array_create_dir(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff81269961)
Location: kernel/trace/trace.c:9300
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs_work_func
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffff81269920-ffffffff812699f4: trace_array_create_dir (STB_LOCAL)
ffffffff8205d521-ffffffff8205d536: trace_array_create_dir.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int trace_array_create_dir(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff81280af1)
Location: kernel/trace/trace.c:9459
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs_work_func
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffff81280ab0-ffffffff81280b84: trace_array_create_dir (STB_LOCAL)
ffffffff820dbeda-ffffffff820dbeef: trace_array_create_dir.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int trace_array_create_dir(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8129ace1)
Location: kernel/trace/trace.c:9638
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs_work_func
  - kernel/trace/trace.c:trace_array_create_systems
```
**Symbols:**

```
ffffffff8129aca0-ffffffff8129ad74: trace_array_create_dir (STB_LOCAL)
ffffffff821b7d24-ffffffff821b7d39: trace_array_create_dir.cold (STB_LOCAL)
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
