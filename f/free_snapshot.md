# Function: <code>free_snapshot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_snapshot(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8114e220)
Location: kernel/trace/trace.c:695
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_snapshot_write
```
**Symbols:**

```
ffffffff8114e220-ffffffff8114e259: free_snapshot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_snapshot(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81156e80)
Location: kernel/trace/trace.c:930
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
```
**Symbols:**

```
ffffffff81156e80-ffffffff81156eb9: free_snapshot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_snapshot(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81161fc0)
Location: kernel/trace/trace.c:973
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
```
**Symbols:**

```
ffffffff81161fc0-ffffffff81161ff9: free_snapshot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_snapshot(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811653e0)
Location: kernel/trace/trace.c:971
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
```
**Symbols:**

```
ffffffff811653e0-ffffffff81165419: free_snapshot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_snapshot(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81172320)
Location: kernel/trace/trace.c:971
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
```
**Symbols:**

```
ffffffff81172320-ffffffff81172359: free_snapshot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_snapshot(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811814b0)
Location: kernel/trace/trace.c:970
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
```
**Symbols:**

```
ffffffff811814b0-ffffffff811814e9: free_snapshot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_snapshot(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118ee70)
Location: kernel/trace/trace.c:971
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
```
**Symbols:**

```
ffffffff8118ee70-ffffffff8118eea9: free_snapshot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_snapshot(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119c7f0)
Location: kernel/trace/trace.c:1028
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
```
**Symbols:**

```
ffffffff8119c7f0-ffffffff8119c829: free_snapshot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_snapshot(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a81a0)
Location: kernel/trace/trace.c:1046
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
```
**Symbols:**

```
ffffffff811a81a0-ffffffff811a81d9: free_snapshot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811c19ef)
Location: kernel/trace/trace.c:1078
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bf5fc)
Location: kernel/trace/trace.c:1229
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bdf2c)
Location: kernel/trace/trace.c:1226
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811ee021)
Location: kernel/trace/trace.c:1239
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81226375)
Location: kernel/trace/trace.c:1229
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8127164e)
Location: kernel/trace/trace.c:1230
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff812889d6)
Location: kernel/trace/trace.c:1281
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff812a3d2d)
Location: kernel/trace/trace.c:1290
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
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
void free_snapshot(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff800010224be0)
Location: kernel/trace/trace.c:1046
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
```
**Symbols:**

```
ffff800010224be0-ffff800010224c24: free_snapshot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void free_snapshot(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0462070)
Location: kernel/trace/trace.c:1046
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
```
**Symbols:**

```
c0462070-c04620b4: free_snapshot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_snapshot(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002a9c10)
Location: kernel/trace/trace.c:1046
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
```
**Symbols:**

```
c0000000002a9c10-c0000000002a9c70: free_snapshot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void free_snapshot(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe00017fd22)
Location: kernel/trace/trace.c:1046
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
```
**Symbols:**

```
ffffffe00017fd22-ffffffe00017fd64: free_snapshot (STB_LOCAL)
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
void free_snapshot(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a07c0)
Location: kernel/trace/trace.c:1046
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
```
**Symbols:**

```
ffffffff811a07c0-ffffffff811a07f9: free_snapshot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_snapshot(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811937d0)
Location: kernel/trace/trace.c:1046
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
```
**Symbols:**

```
ffffffff811937d0-ffffffff81193809: free_snapshot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_snapshot(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119e590)
Location: kernel/trace/trace.c:1046
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
```
**Symbols:**

```
ffffffff8119e590-ffffffff8119e5c9: free_snapshot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_snapshot(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811ac270)
Location: kernel/trace/trace.c:1046
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
```
**Symbols:**

```
ffffffff811ac270-ffffffff811ac2a9: free_snapshot (STB_LOCAL)
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
