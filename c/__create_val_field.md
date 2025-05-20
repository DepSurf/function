# Function: <code>__create_val_field</code>

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
int __create_val_field(struct hist_trigger_data *hist_data, unsigned int val_idx, struct trace_event_file *file, char *var_name, char *field_str, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811a0f90)
Location: kernel/trace/trace_events_hist.c:3831
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
**Symbols:**

```
ffffffff811a0f90-ffffffff811a0feb: __create_val_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __create_val_field(struct hist_trigger_data *hist_data, unsigned int val_idx, struct trace_event_file *file, char *var_name, char *field_str, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811ae6f0)
Location: kernel/trace/trace_events_hist.c:3916
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
```
**Symbols:**

```
ffffffff811ae6f0-ffffffff811ae74b: __create_val_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __create_val_field(struct hist_trigger_data *hist_data, unsigned int val_idx, struct trace_event_file *file, char *var_name, char *field_str, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:4386
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
```
**Symbols:**

```
ffffffff811bc6f0-ffffffff811bc746: __create_val_field (STB_LOCAL)
ffffffff811c0e58-ffffffff811c0e70: __create_val_field.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __create_val_field(struct hist_trigger_data *hist_data, unsigned int val_idx, struct trace_event_file *file, char *var_name, char *field_str, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c7f50)
Location: kernel/trace/trace_events_hist.c:4508
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
```
**Symbols:**

```
ffffffff811c7f50-ffffffff811c7fab: __create_val_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __create_val_field(struct hist_trigger_data *hist_data, unsigned int val_idx, struct trace_event_file *file, char *var_name, char *field_str, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e5f20)
Location: kernel/trace/trace_events_hist.c:3610
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_var_fields
  - kernel/trace/trace_events_hist.c:create_val_fields
```
**Symbols:**

```
ffffffff811e5f20-ffffffff811e5f7b: __create_val_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __create_val_field(struct hist_trigger_data *hist_data, unsigned int val_idx, struct trace_event_file *file, char *var_name, char *field_str, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e3950)
Location: kernel/trace/trace_events_hist.c:3629
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_val_fields
  - kernel/trace/trace_events_hist.c:create_var_field
```
**Symbols:**

```
ffffffff811e3950-ffffffff811e39ab: __create_val_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __create_val_field(struct hist_trigger_data *hist_data, unsigned int val_idx, struct trace_event_file *file, char *var_name, char *field_str, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e4e70)
Location: kernel/trace/trace_events_hist.c:3697
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_var_fields
  - kernel/trace/trace_events_hist.c:create_val_fields
```
**Symbols:**

```
ffffffff811e4e70-ffffffff811e4ecb: __create_val_field (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff81215ac1)
Location: kernel/trace/trace_events_hist.c:3754
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_val_fields
  - kernel/trace/trace_events_hist.c:create_var_field
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __create_val_field(struct hist_trigger_data *hist_data, unsigned int val_idx, struct trace_event_file *file, char *var_name, char *field_str, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812522d0)
Location: kernel/trace/trace_events_hist.c:4131
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_var_fields
```
**Symbols:**

```
ffffffff812522d0-ffffffff81252399: __create_val_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __create_val_field(struct hist_trigger_data *hist_data, unsigned int val_idx, struct trace_event_file *file, char *var_name, char *field_str, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812a15f0)
Location: kernel/trace/trace_events_hist.c:4187
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_var_fields
  - kernel/trace/trace_events_hist.c:create_val_fields
```
**Symbols:**

```
ffffffff812a15f0-ffffffff812a16b9: __create_val_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __create_val_field(struct hist_trigger_data *hist_data, unsigned int val_idx, struct trace_event_file *file, char *var_name, char *field_str, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812bf1d0)
Location: kernel/trace/trace_events_hist.c:4230
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_var_fields
  - kernel/trace/trace_events_hist.c:create_val_fields
```
**Symbols:**

```
ffffffff812bf1d0-ffffffff812bf31a: __create_val_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __create_val_field(struct hist_trigger_data *hist_data, unsigned int val_idx, struct trace_event_file *file, char *var_name, char *field_str, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812db830)
Location: kernel/trace/trace_events_hist.c:4223
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_var_fields
  - kernel/trace/trace_events_hist.c:create_val_fields
```
**Symbols:**

```
ffffffff812db830-ffffffff812db97a: __create_val_field (STB_LOCAL)
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
int __create_val_field(struct hist_trigger_data *hist_data, unsigned int val_idx, struct trace_event_file *file, char *var_name, char *field_str, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffff800010248198)
Location: kernel/trace/trace_events_hist.c:4508
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
```
**Symbols:**

```
ffff800010248198-ffff800010248210: __create_val_field (STB_LOCAL)
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
int __create_val_field(struct hist_trigger_data *hist_data, unsigned int val_idx, struct trace_event_file *file, char *var_name, char *field_str, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (c0000000002e1eb0)
Location: kernel/trace/trace_events_hist.c:4508
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
```
**Symbols:**

```
c0000000002e1eb0-c0000000002e1f84: __create_val_field (STB_LOCAL)
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
int __create_val_field(struct hist_trigger_data *hist_data, unsigned int val_idx, struct trace_event_file *file, char *var_name, char *field_str, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c0570)
Location: kernel/trace/trace_events_hist.c:4508
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
```
**Symbols:**

```
ffffffff811c0570-ffffffff811c05cb: __create_val_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __create_val_field(struct hist_trigger_data *hist_data, unsigned int val_idx, struct trace_event_file *file, char *var_name, char *field_str, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811b3350)
Location: kernel/trace/trace_events_hist.c:4508
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
```
**Symbols:**

```
ffffffff811b3350-ffffffff811b33ab: __create_val_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __create_val_field(struct hist_trigger_data *hist_data, unsigned int val_idx, struct trace_event_file *file, char *var_name, char *field_str, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811be340)
Location: kernel/trace/trace_events_hist.c:4508
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
```
**Symbols:**

```
ffffffff811be340-ffffffff811be39b: __create_val_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __create_val_field(struct hist_trigger_data *hist_data, unsigned int val_idx, struct trace_event_file *file, char *var_name, char *field_str, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811cc3e0)
Location: kernel/trace/trace_events_hist.c:4508
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
```
**Symbols:**

```
ffffffff811cc3e0-ffffffff811cc43b: __create_val_field (STB_LOCAL)
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
