# Function: <code>create_trace_option_files</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void create_trace_option_files(struct trace_array *tr, struct tracer *tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811525a0)
Location: kernel/trace/trace.c:6369
Inline: False
Direct callers:
  - kernel/trace/trace.c:register_tracer
  - kernel/trace/trace.c:__update_tracer_options
```
**Symbols:**

```
ffffffff811525a0-ffffffff811527fd: create_trace_option_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void create_trace_option_files(struct trace_array *tr, struct tracer *tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8115b7b0)
Location: kernel/trace/trace.c:6772
Inline: False
Direct callers:
  - kernel/trace/trace.c:__update_tracer_options
  - kernel/trace/trace.c:register_tracer
```
**Symbols:**

```
ffffffff8115b7b0-ffffffff8115ba03: create_trace_option_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void create_trace_option_files(struct trace_array *tr, struct tracer *tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81165fc0)
Location: kernel/trace/trace.c:7055
Inline: False
Direct callers:
  - kernel/trace/trace.c:__update_tracer_options
  - kernel/trace/trace.c:register_tracer
```
**Symbols:**

```
ffffffff81165fc0-ffffffff81166213: create_trace_option_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void create_trace_option_files(struct trace_array *tr, struct tracer *tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811694e0)
Location: kernel/trace/trace.c:7419
Inline: False
Direct callers:
  - kernel/trace/trace.c:__update_tracer_options
  - kernel/trace/trace.c:register_tracer
```
**Symbols:**

```
ffffffff811694e0-ffffffff81169710: create_trace_option_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void create_trace_option_files(struct trace_array *tr, struct tracer *tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81176490)
Location: kernel/trace/trace.c:7422
Inline: False
Direct callers:
  - kernel/trace/trace.c:__update_tracer_options
  - kernel/trace/trace.c:register_tracer
```
**Symbols:**

```
ffffffff81176490-ffffffff811766c0: create_trace_option_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void create_trace_option_files(struct trace_array *tr, struct tracer *tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81185620)
Location: kernel/trace/trace.c:7510
Inline: False
Direct callers:
  - kernel/trace/trace.c:__update_tracer_options
  - kernel/trace/trace.c:register_tracer
```
**Symbols:**

```
ffffffff81185620-ffffffff8118585b: create_trace_option_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void create_trace_option_files(struct trace_array *tr, struct tracer *tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81192f50)
Location: kernel/trace/trace.c:7532
Inline: False
Direct callers:
  - kernel/trace/trace.c:__update_tracer_options
  - kernel/trace/trace.c:register_tracer
```
**Symbols:**

```
ffffffff81192f50-ffffffff8119318b: create_trace_option_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void create_trace_option_files(struct trace_array *tr, struct tracer *tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a0a50)
Location: kernel/trace/trace.c:8017
Inline: False
Direct callers:
  - kernel/trace/trace.c:__update_tracer_options
  - kernel/trace/trace.c:register_tracer
```
**Symbols:**

```
ffffffff811a0a50-ffffffff811a0c77: create_trace_option_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void create_trace_option_files(struct trace_array *tr, struct tracer *tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811ac480)
Location: kernel/trace/trace.c:8068
Inline: False
Direct callers:
  - kernel/trace/trace.c:__update_tracer_options
  - kernel/trace/trace.c:register_tracer
```
**Symbols:**

```
ffffffff811ac480-ffffffff811ac6a7: create_trace_option_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void create_trace_option_files(struct trace_array *tr, struct tracer *tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:8271
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:register_tracer
```
**Symbols:**

```
ffffffff811be2c0-ffffffff811be4ed: create_trace_option_files (STB_LOCAL)
ffffffff811c529c-ffffffff811c52db: create_trace_option_files.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void create_trace_option_files(struct trace_array *tr, struct tracer *tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:8345
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:trace_array_create_dir
  - kernel/trace/trace.c:register_tracer
```
**Symbols:**

```
ffffffff811bbef0-ffffffff811bc11d: create_trace_option_files (STB_LOCAL)
ffffffff81be55d8-ffffffff81be5617: create_trace_option_files.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void create_trace_option_files(struct trace_array *tr, struct tracer *tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:8681
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:register_tracer
```
**Symbols:**

```
ffffffff811bb730-ffffffff811bb95d: create_trace_option_files (STB_LOCAL)
ffffffff81bd7486-ffffffff81bd74c5: create_trace_option_files.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void create_trace_option_files(struct trace_array *tr, struct tracer *tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:8845
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:register_tracer
```
**Symbols:**

```
ffffffff811e5e10-ffffffff811e604f: create_trace_option_files (STB_LOCAL)
ffffffff81cb4e24-ffffffff81cb4e95: create_trace_option_files.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void create_trace_option_files(struct trace_array *tr, struct tracer *tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:8877
Inline: False
```
**Symbols:**

```
ffffffff8121d610-ffffffff8121d86f: create_trace_option_files (STB_LOCAL)
ffffffff81e65e77-ffffffff81e65eee: create_trace_option_files.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void create_trace_option_files(struct trace_array *tr, struct tracer *tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:8972
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs_work_func
  - kernel/trace/trace.c:register_tracer
```
**Symbols:**

```
ffffffff81267d30-ffffffff81267fb0: create_trace_option_files (STB_LOCAL)
ffffffff8205d469-ffffffff8205d492: create_trace_option_files.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void create_trace_option_files(struct trace_array *tr, struct tracer *tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:9135
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs_work_func
  - kernel/trace/trace.c:register_tracer
```
**Symbols:**

```
ffffffff8127ee20-ffffffff8127f095: create_trace_option_files (STB_LOCAL)
ffffffff820dbe20-ffffffff820dbe48: create_trace_option_files.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void create_trace_option_files(struct trace_array *tr, struct tracer *tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:9217
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs_work_func
  - kernel/trace/trace.c:register_tracer
```
**Symbols:**

```
ffffffff81299760-ffffffff812999d5: create_trace_option_files (STB_LOCAL)
ffffffff821b7c93-ffffffff821b7cbb: create_trace_option_files.cold (STB_LOCAL)
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
void create_trace_option_files(struct trace_array *tr, struct tracer *tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff800010229498)
Location: kernel/trace/trace.c:8068
Inline: False
Direct callers:
  - kernel/trace/trace.c:__update_tracer_options
  - kernel/trace/trace.c:register_tracer
```
**Symbols:**

```
ffff800010229498-ffff8000102296b0: create_trace_option_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void create_trace_option_files(struct trace_array *tr, struct tracer *tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0466aa4)
Location: kernel/trace/trace.c:8068
Inline: False
Direct callers:
  - kernel/trace/trace.c:__update_tracer_options
  - kernel/trace/trace.c:register_tracer
```
**Symbols:**

```
c0466aa4-c0466cd8: create_trace_option_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void create_trace_option_files(struct trace_array *tr, struct tracer *tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002b0a30)
Location: kernel/trace/trace.c:8068
Inline: False
Direct callers:
  - kernel/trace/trace.c:__update_tracer_options
  - kernel/trace/trace.c:register_tracer
```
**Symbols:**

```
c0000000002b0a30-c0000000002b0d5c: create_trace_option_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void create_trace_option_files(struct trace_array *tr, struct tracer *tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe000183bbe)
Location: kernel/trace/trace.c:8068
Inline: False
Direct callers:
  - kernel/trace/trace.c:__update_tracer_options
  - kernel/trace/trace.c:register_tracer
```
**Symbols:**

```
ffffffe000183bbe-ffffffe000183d80: create_trace_option_files (STB_LOCAL)
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
void create_trace_option_files(struct trace_array *tr, struct tracer *tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a4aa0)
Location: kernel/trace/trace.c:8068
Inline: False
Direct callers:
  - kernel/trace/trace.c:__update_tracer_options
  - kernel/trace/trace.c:register_tracer
```
**Symbols:**

```
ffffffff811a4aa0-ffffffff811a4cc7: create_trace_option_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void create_trace_option_files(struct trace_array *tr, struct tracer *tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81197a50)
Location: kernel/trace/trace.c:8068
Inline: False
Direct callers:
  - kernel/trace/trace.c:__update_tracer_options
  - kernel/trace/trace.c:register_tracer
```
**Symbols:**

```
ffffffff81197a50-ffffffff81197c77: create_trace_option_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void create_trace_option_files(struct trace_array *tr, struct tracer *tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a2870)
Location: kernel/trace/trace.c:8068
Inline: False
Direct callers:
  - kernel/trace/trace.c:__update_tracer_options
  - kernel/trace/trace.c:register_tracer
```
**Symbols:**

```
ffffffff811a2870-ffffffff811a2a97: create_trace_option_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void create_trace_option_files(struct trace_array *tr, struct tracer *tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811b0600)
Location: kernel/trace/trace.c:8068
Inline: False
Direct callers:
  - kernel/trace/trace.c:__update_tracer_options
  - kernel/trace/trace.c:register_tracer
```
**Symbols:**

```
ffffffff811b0600-ffffffff811b0827: create_trace_option_files (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
