# Function: <code>create_sort_keys</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811732df)
Location: kernel/trace/trace_events_hist.c:652
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8117ece0)
Location: kernel/trace/trace_events_hist.c:652
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff81181b1b)
Location: kernel/trace/trace_events_hist.c:653
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8118f4b3)
Location: kernel/trace/trace_events_hist.c:693
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811a27a0)
Location: kernel/trace/trace_events_hist.c:4151
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811b0856)
Location: kernel/trace/trace_events_hist.c:4236
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811be305)
Location: kernel/trace/trace_events_hist.c:4709
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c9a05)
Location: kernel/trace/trace_events_hist.c:4823
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int create_sort_keys(struct hist_trigger_data *hist_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e2200)
Location: kernel/trace/trace_events_hist.c:3926
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
```
**Symbols:**

```
ffffffff811e2200-ffffffff811e24ae: create_sort_keys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int create_sort_keys(struct hist_trigger_data *hist_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811dfe20)
Location: kernel/trace/trace_events_hist.c:3951
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
```
**Symbols:**

```
ffffffff811dfe20-ffffffff811e00ce: create_sort_keys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int create_sort_keys(struct hist_trigger_data *hist_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e0f20)
Location: kernel/trace/trace_events_hist.c:4019
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
```
**Symbols:**

```
ffffffff811e0f20-ffffffff811e11c7: create_sort_keys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int create_sort_keys(struct hist_trigger_data *hist_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff81210c70)
Location: kernel/trace/trace_events_hist.c:4114
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
```
**Symbols:**

```
ffffffff81210c70-ffffffff81210f25: create_sort_keys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int create_sort_keys(struct hist_trigger_data *hist_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff81250d90)
Location: kernel/trace/trace_events_hist.c:4493
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
```
**Symbols:**

```
ffffffff81250d90-ffffffff8125108f: create_sort_keys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int create_sort_keys(struct hist_trigger_data *hist_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8129ffe0)
Location: kernel/trace/trace_events_hist.c:4624
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
```
**Symbols:**

```
ffffffff8129ffe0-ffffffff812a02df: create_sort_keys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int create_sort_keys(struct hist_trigger_data *hist_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812bdd50)
Location: kernel/trace/trace_events_hist.c:4701
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
```
**Symbols:**

```
ffffffff812bdd50-ffffffff812be06b: create_sort_keys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int create_sort_keys(struct hist_trigger_data *hist_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812da3b0)
Location: kernel/trace/trace_events_hist.c:4694
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
```
**Symbols:**

```
ffffffff812da3b0-ffffffff812da6cb: create_sort_keys (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffff800010249948)
Location: kernel/trace/trace_events_hist.c:4823
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (c0000000002e2d68)
Location: kernel/trace/trace_events_hist.c:4823
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c2025)
Location: kernel/trace/trace_events_hist.c:4823
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811b4e05)
Location: kernel/trace/trace_events_hist.c:4823
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bfdf5)
Location: kernel/trace/trace_events_hist.c:4823
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811cde95)
Location: kernel/trace/trace_events_hist.c:4823
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
