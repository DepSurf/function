# Function: <code>create_var_ref</code>

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
struct hist_field *create_var_ref(struct hist_field *var_field, char *system, char *event_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811a0540)
Location: kernel/trace/trace_events_hist.c:2346
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:parse_atom
```
**Symbols:**

```
ffffffff811a0540-ffffffff811a059d: create_var_ref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct hist_field *create_var_ref(struct hist_trigger_data *hist_data, struct hist_field *var_field, char *system, char *event_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811ac570)
Location: kernel/trace/trace_events_hist.c:2459
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:parse_atom
```
**Symbols:**

```
ffffffff811ac570-ffffffff811ac608: create_var_ref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct hist_field *create_var_ref(struct hist_trigger_data *hist_data, struct hist_field *var_field, char *system, char *event_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811ba7b0)
Location: kernel/trace/trace_events_hist.c:2613
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:parse_atom
```
**Symbols:**

```
ffffffff811ba7b0-ffffffff811ba84b: create_var_ref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct hist_field *create_var_ref(struct hist_trigger_data *hist_data, struct hist_field *var_field, char *system, char *event_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c5e30)
Location: kernel/trace/trace_events_hist.c:2713
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:parse_atom
```
**Symbols:**

```
ffffffff811c5e30-ffffffff811c5f1a: create_var_ref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct hist_field *create_var_ref(struct hist_trigger_data *hist_data, struct hist_field *var_field, char *system, char *event_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e56c0)
Location: kernel/trace/trace_events_hist.c:1808
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:track_data_create
  - kernel/trace/trace_events_hist.c:parse_atom
```
**Symbols:**

```
ffffffff811e56c0-ffffffff811e57d2: create_var_ref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct hist_field *create_var_ref(struct hist_trigger_data *hist_data, struct hist_field *var_field, char *system, char *event_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e30f0)
Location: kernel/trace/trace_events_hist.c:1818
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:track_data_create
  - kernel/trace/trace_events_hist.c:parse_atom
```
**Symbols:**

```
ffffffff811e30f0-ffffffff811e3202: create_var_ref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct hist_field *create_var_ref(struct hist_trigger_data *hist_data, struct hist_field *var_field, char *system, char *event_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e3e30)
Location: kernel/trace/trace_events_hist.c:1844
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:track_data_create
  - kernel/trace/trace_events_hist.c:parse_atom
```
**Symbols:**

```
ffffffff811e3e30-ffffffff811e3f42: create_var_ref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct hist_field *create_var_ref(struct hist_trigger_data *hist_data, struct hist_field *var_field, char *system, char *event_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff81214340)
Location: kernel/trace/trace_events_hist.c:1878
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:track_data_create
  - kernel/trace/trace_events_hist.c:parse_atom
```
**Symbols:**

```
ffffffff81214340-ffffffff8121449a: create_var_ref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct hist_field *create_var_ref(struct hist_trigger_data *hist_data, struct hist_field *var_field, char *system, char *event_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812503e0)
Location: kernel/trace/trace_events_hist.c:2136
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_actions
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:parse_atom
```
**Symbols:**

```
ffffffff812503e0-ffffffff81250531: create_var_ref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct hist_field *create_var_ref(struct hist_trigger_data *hist_data, struct hist_field *var_field, char *system, char *event_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8129f600)
Location: kernel/trace/trace_events_hist.c:2174
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_actions
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:parse_atom
```
**Symbols:**

```
ffffffff8129f600-ffffffff8129f777: create_var_ref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct hist_field *create_var_ref(struct hist_trigger_data *hist_data, struct hist_field *var_field, char *system, char *event_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812bd2d0)
Location: kernel/trace/trace_events_hist.c:2188
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_actions
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:parse_atom
```
**Symbols:**

```
ffffffff812bd2d0-ffffffff812bd447: create_var_ref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct hist_field *create_var_ref(struct hist_trigger_data *hist_data, struct hist_field *var_field, char *system, char *event_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812d98a0)
Location: kernel/trace/trace_events_hist.c:2181
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_actions
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:parse_atom
```
**Symbols:**

```
ffffffff812d98a0-ffffffff812d9a46: create_var_ref (STB_LOCAL)
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
struct hist_field *create_var_ref(struct hist_trigger_data *hist_data, struct hist_field *var_field, char *system, char *event_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffff8000102461e0)
Location: kernel/trace/trace_events_hist.c:2713
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:parse_atom
```
**Symbols:**

```
ffff8000102461e0-ffff800010246308: create_var_ref (STB_LOCAL)
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
struct hist_field *create_var_ref(struct hist_trigger_data *hist_data, struct hist_field *var_field, char *system, char *event_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (c0000000002dfe10)
Location: kernel/trace/trace_events_hist.c:2713
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:parse_atom
```
**Symbols:**

```
c0000000002dfe10-c0000000002dff9c: create_var_ref (STB_LOCAL)
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
struct hist_field *create_var_ref(struct hist_trigger_data *hist_data, struct hist_field *var_field, char *system, char *event_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811be450)
Location: kernel/trace/trace_events_hist.c:2713
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:parse_atom
```
**Symbols:**

```
ffffffff811be450-ffffffff811be53a: create_var_ref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct hist_field *create_var_ref(struct hist_trigger_data *hist_data, struct hist_field *var_field, char *system, char *event_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811b1230)
Location: kernel/trace/trace_events_hist.c:2713
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:parse_atom
```
**Symbols:**

```
ffffffff811b1230-ffffffff811b131a: create_var_ref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct hist_field *create_var_ref(struct hist_trigger_data *hist_data, struct hist_field *var_field, char *system, char *event_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bc220)
Location: kernel/trace/trace_events_hist.c:2713
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:parse_atom
```
**Symbols:**

```
ffffffff811bc220-ffffffff811bc30a: create_var_ref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct hist_field *create_var_ref(struct hist_trigger_data *hist_data, struct hist_field *var_field, char *system, char *event_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811ca2c0)
Location: kernel/trace/trace_events_hist.c:2713
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:parse_atom
```
**Symbols:**

```
ffffffff811ca2c0-ffffffff811ca3aa: create_var_ref (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct hist_trigger_data *hist_data</code>
</li>
<li>
<b>Param reordered. </b>
<code>var_field, system, event_name</code> ➡️ <code>hist_data, var_field, system, event_name</code>
</li>
</ul>
</details>
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
