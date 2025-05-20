# Function: <code>create_var</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct hist_field *create_var(struct hist_trigger_data *hist_data, struct trace_event_file *file, char *name, int size, const char *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811a00f0)
Location: kernel/trace/trace_events_hist.c:3121
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_field_var
```
**Symbols:**

```
ffffffff811a00f0-ffffffff811a023d: create_var (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct hist_field *create_var(struct hist_trigger_data *hist_data, struct trace_event_file *file, char *name, int size, const char *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811aee80)
Location: kernel/trace/trace_events_hist.c:3237
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_field_var
```
**Symbols:**

```
ffffffff811aee80-ffffffff811aefcd: create_var (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct hist_field *create_var(struct hist_trigger_data *hist_data, struct trace_event_file *file, char *name, int size, const char *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bdaf0)
Location: kernel/trace/trace_events_hist.c:3389
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_field_var
```
**Symbols:**

```
ffffffff811bdaf0-ffffffff811bdc19: create_var (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct hist_field *create_var(struct hist_trigger_data *hist_data, struct trace_event_file *file, char *name, int size, const char *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c64d0)
Location: kernel/trace/trace_events_hist.c:3506
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_field_var
```
**Symbols:**

```
ffffffff811c64d0-ffffffff811c65f9: create_var (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct hist_field *create_var(struct hist_trigger_data *hist_data, struct trace_event_file *file, char *name, int size, const char *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e4710)
Location: kernel/trace/trace_events_hist.c:2601
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:track_data_create
  - kernel/trace/trace_events_hist.c:track_data_create
  - kernel/trace/trace_events_hist.c:create_field_var
```
**Symbols:**

```
ffffffff811e4710-ffffffff811e48c1: create_var (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct hist_field *create_var(struct hist_trigger_data *hist_data, struct trace_event_file *file, char *name, int size, const char *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e1ff0)
Location: kernel/trace/trace_events_hist.c:2611
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:track_data_create
  - kernel/trace/trace_events_hist.c:track_data_create
  - kernel/trace/trace_events_hist.c:create_field_var
```
**Symbols:**

```
ffffffff811e1ff0-ffffffff811e21a1: create_var (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct hist_field *create_var(struct hist_trigger_data *hist_data, struct trace_event_file *file, char *name, int size, const char *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e3420)
Location: kernel/trace/trace_events_hist.c:2671
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:track_data_create
  - kernel/trace/trace_events_hist.c:track_data_create
  - kernel/trace/trace_events_hist.c:create_field_var
```
**Symbols:**

```
ffffffff811e3420-ffffffff811e35d1: create_var (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct hist_field *create_var(struct hist_trigger_data *hist_data, struct trace_event_file *file, char *name, int size, const char *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:2727
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:track_data_create
  - kernel/trace/trace_events_hist.c:track_data_create
  - kernel/trace/trace_events_hist.c:create_field_var
```
**Symbols:**

```
ffffffff81213530-ffffffff81213751: create_var (STB_LOCAL)
ffffffff81cb7056-ffffffff81cb706b: create_var.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct hist_field *create_var(struct hist_trigger_data *hist_data, struct trace_event_file *file, char *name, int size, const char *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:3104
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_actions
  - kernel/trace/trace_events_hist.c:create_actions
  - kernel/trace/trace_events_hist.c:create_field_var
```
**Symbols:**

```
ffffffff8124f0f0-ffffffff8124f307: create_var (STB_LOCAL)
ffffffff81e68178-ffffffff81e6818d: create_var.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct hist_field *create_var(struct hist_trigger_data *hist_data, struct trace_event_file *file, char *name, int size, const char *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:3155
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_actions
  - kernel/trace/trace_events_hist.c:create_actions
  - kernel/trace/trace_events_hist.c:create_field_var
```
**Symbols:**

```
ffffffff8129e270-ffffffff8129e487: create_var (STB_LOCAL)
ffffffff8205eb74-ffffffff8205eb89: create_var.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct hist_field *create_var(struct hist_trigger_data *hist_data, struct trace_event_file *file, char *name, int size, const char *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:3193
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_actions
  - kernel/trace/trace_events_hist.c:create_actions
  - kernel/trace/trace_events_hist.c:create_field_var
```
**Symbols:**

```
ffffffff812bbef0-ffffffff812bc107: create_var (STB_LOCAL)
ffffffff820dd6b1-ffffffff820dd6c6: create_var.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct hist_field *create_var(struct hist_trigger_data *hist_data, struct trace_event_file *file, char *name, int size, const char *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:3186
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_actions
  - kernel/trace/trace_events_hist.c:create_actions
  - kernel/trace/trace_events_hist.c:create_field_var
```
**Symbols:**

```
ffffffff812d83b0-ffffffff812d85f6: create_var (STB_LOCAL)
ffffffff821b94b5-ffffffff821b94ca: create_var.cold (STB_LOCAL)
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
struct hist_field *create_var(struct hist_trigger_data *hist_data, struct trace_event_file *file, char *name, int size, const char *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffff800010249c80)
Location: kernel/trace/trace_events_hist.c:3506
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_field_var
```
**Symbols:**

```
ffff800010249c80-ffff800010249dac: create_var (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct hist_field *create_var(struct hist_trigger_data *hist_data, struct trace_event_file *file, char *name, int size, const char *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (c0000000002de580)
Location: kernel/trace/trace_events_hist.c:3506
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_field_var
```
**Symbols:**

```
c0000000002de580-c0000000002de758: create_var (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
struct hist_field *create_var(struct hist_trigger_data *hist_data, struct trace_event_file *file, char *name, int size, const char *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811beaf0)
Location: kernel/trace/trace_events_hist.c:3506
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_field_var
```
**Symbols:**

```
ffffffff811beaf0-ffffffff811bec19: create_var (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct hist_field *create_var(struct hist_trigger_data *hist_data, struct trace_event_file *file, char *name, int size, const char *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811b18d0)
Location: kernel/trace/trace_events_hist.c:3506
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_field_var
```
**Symbols:**

```
ffffffff811b18d0-ffffffff811b19f9: create_var (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct hist_field *create_var(struct hist_trigger_data *hist_data, struct trace_event_file *file, char *name, int size, const char *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bc8c0)
Location: kernel/trace/trace_events_hist.c:3506
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_field_var
```
**Symbols:**

```
ffffffff811bc8c0-ffffffff811bc9e9: create_var (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct hist_field *create_var(struct hist_trigger_data *hist_data, struct trace_event_file *file, char *name, int size, const char *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811ca960)
Location: kernel/trace/trace_events_hist.c:3506
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_field_var
```
**Symbols:**

```
ffffffff811ca960-ffffffff811caa89: create_var (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
