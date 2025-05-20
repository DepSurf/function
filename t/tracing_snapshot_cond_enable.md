# Function: <code>tracing_snapshot_cond_enable</code>

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
int tracing_snapshot_cond_enable(struct trace_array *tr, void *cond_data, cond_update_fn_t update);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81199cd0)
Location: kernel/trace/trace.c:1099
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:action_create
```
**Symbols:**

```
ffffffff81199cd0-ffffffff81199df2: tracing_snapshot_cond_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tracing_snapshot_cond_enable(struct trace_array *tr, void *cond_data, cond_update_fn_t update);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a5680)
Location: kernel/trace/trace.c:1117
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:action_create
```
**Symbols:**

```
ffffffff811a5680-ffffffff811a57a2: tracing_snapshot_cond_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tracing_snapshot_cond_enable(struct trace_array *tr, void *cond_data, cond_update_fn_t update);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bf270)
Location: kernel/trace/trace.c:1149
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:action_create
```
**Symbols:**

```
ffffffff811bf270-ffffffff811bf382: tracing_snapshot_cond_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tracing_snapshot_cond_enable(struct trace_array *tr, void *cond_data, cond_update_fn_t update);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bcea0)
Location: kernel/trace/trace.c:1300
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:action_create
```
**Symbols:**

```
ffffffff811bcea0-ffffffff811bcfb2: tracing_snapshot_cond_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tracing_snapshot_cond_enable(struct trace_array *tr, void *cond_data, cond_update_fn_t update);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bc9a0)
Location: kernel/trace/trace.c:1297
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:action_create
```
**Symbols:**

```
ffffffff811bc9a0-ffffffff811bcab2: tracing_snapshot_cond_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tracing_snapshot_cond_enable(struct trace_array *tr, void *cond_data, cond_update_fn_t update);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:1310
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:action_create
```
**Symbols:**

```
ffffffff81cb51fd-ffffffff81cb5227: tracing_snapshot_cond_enable.cold (STB_LOCAL)
ffffffff811e7440-ffffffff811e7569: tracing_snapshot_cond_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tracing_snapshot_cond_enable(struct trace_array *tr, void *cond_data, cond_update_fn_t update);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:1300
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:action_create
```
**Symbols:**

```
ffffffff81e662ae-ffffffff81e662d8: tracing_snapshot_cond_enable.cold (STB_LOCAL)
ffffffff8121f3c0-ffffffff8121f51a: tracing_snapshot_cond_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int tracing_snapshot_cond_enable(struct trace_array *tr, void *cond_data, cond_update_fn_t update);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:1301
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:action_create
```
**Symbols:**

```
ffffffff8205d536-ffffffff8205d560: tracing_snapshot_cond_enable.cold (STB_LOCAL)
ffffffff81269e20-ffffffff81269f86: tracing_snapshot_cond_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int tracing_snapshot_cond_enable(struct trace_array *tr, void *cond_data, cond_update_fn_t update);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:1352
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:action_create
```
**Symbols:**

```
ffffffff820dbeef-ffffffff820dbf19: tracing_snapshot_cond_enable.cold (STB_LOCAL)
ffffffff81280fa0-ffffffff81281106: tracing_snapshot_cond_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int tracing_snapshot_cond_enable(struct trace_array *tr, void *cond_data, cond_update_fn_t update);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:1362
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:action_create
```
**Symbols:**

```
ffffffff821b7dbc-ffffffff821b7dd1: tracing_snapshot_cond_enable.cold (STB_LOCAL)
ffffffff8129c9f0-ffffffff8129cb5a: tracing_snapshot_cond_enable (STB_GLOBAL)
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
int tracing_snapshot_cond_enable(struct trace_array *tr, void *cond_data, cond_update_fn_t update);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff800010221198)
Location: kernel/trace/trace.c:1117
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:action_create
```
**Symbols:**

```
ffff800010221198-ffff8000102212b8: tracing_snapshot_cond_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tracing_snapshot_cond_enable(struct trace_array *tr, void *cond_data, cond_update_fn_t update);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c046075c)
Location: kernel/trace/trace.c:1117
Inline: False
```
**Symbols:**

```
c046075c-c0460880: tracing_snapshot_cond_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tracing_snapshot_cond_enable(struct trace_array *tr, void *cond_data, cond_update_fn_t update);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002a7490)
Location: kernel/trace/trace.c:1117
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:action_create
```
**Symbols:**

```
c0000000002a7490-c0000000002a7688: tracing_snapshot_cond_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tracing_snapshot_cond_enable(struct trace_array *tr, void *cond_data, cond_update_fn_t update);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe00017d126)
Location: kernel/trace/trace.c:1117
Inline: False
```
**Symbols:**

```
ffffffe00017d126-ffffffe00017d218: tracing_snapshot_cond_enable (STB_GLOBAL)
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
int tracing_snapshot_cond_enable(struct trace_array *tr, void *cond_data, cond_update_fn_t update);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119dca0)
Location: kernel/trace/trace.c:1117
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:action_create
```
**Symbols:**

```
ffffffff8119dca0-ffffffff8119ddc2: tracing_snapshot_cond_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tracing_snapshot_cond_enable(struct trace_array *tr, void *cond_data, cond_update_fn_t update);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81190d00)
Location: kernel/trace/trace.c:1117
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:action_create
```
**Symbols:**

```
ffffffff81190d00-ffffffff81190e22: tracing_snapshot_cond_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tracing_snapshot_cond_enable(struct trace_array *tr, void *cond_data, cond_update_fn_t update);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119ba70)
Location: kernel/trace/trace.c:1117
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:action_create
```
**Symbols:**

```
ffffffff8119ba70-ffffffff8119bb92: tracing_snapshot_cond_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tracing_snapshot_cond_enable(struct trace_array *tr, void *cond_data, cond_update_fn_t update);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a9710)
Location: kernel/trace/trace.c:1117
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:action_create
```
**Symbols:**

```
ffffffff811a9710-ffffffff811a9832: tracing_snapshot_cond_enable (STB_GLOBAL)
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
