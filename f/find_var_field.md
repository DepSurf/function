# Function: <code>find_var_field</code>

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
struct hist_field *find_var_field(struct hist_trigger_data *hist_data, const char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8119cba0)
Location: kernel/trace/trace_events_hist.c:1460
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:find_file_var
```
**Symbols:**

```
ffffffff8119cba0-ffffffff8119cbfc: find_var_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct hist_field *find_var_field(struct hist_trigger_data *hist_data, const char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811aafe0)
Location: kernel/trace/trace_events_hist.c:1544
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:find_file_var
```
**Symbols:**

```
ffffffff811aafe0-ffffffff811ab03c: find_var_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct hist_field *find_var_field(struct hist_trigger_data *hist_data, const char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811b9060)
Location: kernel/trace/trace_events_hist.c:1698
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:find_file_var
```
**Symbols:**

```
ffffffff811b9060-ffffffff811b90bc: find_var_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct hist_field *find_var_field(struct hist_trigger_data *hist_data, const char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c4640)
Location: kernel/trace/trace_events_hist.c:1772
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:find_file_var
```
**Symbols:**

```
ffffffff811c4640-ffffffff811c469c: find_var_field (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff811e61cc)
Location: kernel/trace/trace_events_hist.c:863
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_var_fields
  - kernel/trace/trace_events_hist.c:create_var_fields
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:track_data_create
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:find_event_var
  - kernel/trace/trace_events_hist.c:find_match_var
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
In kernel/trace/trace_events_hist.c (ffffffff811e3b15)
Location: kernel/trace/trace_events_hist.c:866
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_var_field
  - kernel/trace/trace_events_hist.c:create_var_field
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:track_data_create
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:find_event_var
  - kernel/trace/trace_events_hist.c:find_match_var
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
In kernel/trace/trace_events_hist.c (ffffffff811e5127)
Location: kernel/trace/trace_events_hist.c:882
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_var_fields
  - kernel/trace/trace_events_hist.c:create_var_fields
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:track_data_create
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:find_event_var
  - kernel/trace/trace_events_hist.c:find_event_var
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
In kernel/trace/trace_events_hist.c (ffffffff812151ed)
Location: kernel/trace/trace_events_hist.c:906
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_var_field
  - kernel/trace/trace_events_hist.c:create_var_field
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:track_data_create
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:find_event_var
  - kernel/trace/trace_events_hist.c:find_event_var
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
In kernel/trace/trace_events_hist.c (ffffffff812549b0)
Location: kernel/trace/trace_events_hist.c:1080
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_actions
  - kernel/trace/trace_events_hist.c:create_var_fields
  - kernel/trace/trace_events_hist.c:create_var_fields
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:find_event_var
  - kernel/trace/trace_events_hist.c:find_event_var
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
In kernel/trace/trace_events_hist.c (ffffffff812a3e30)
Location: kernel/trace/trace_events_hist.c:1113
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_actions
  - kernel/trace/trace_events_hist.c:create_var_fields
  - kernel/trace/trace_events_hist.c:create_var_fields
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:find_event_var
  - kernel/trace/trace_events_hist.c:find_event_var
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
In kernel/trace/trace_events_hist.c (ffffffff812c1ce0)
Location: kernel/trace/trace_events_hist.c:1110
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_actions
  - kernel/trace/trace_events_hist.c:create_var_fields
  - kernel/trace/trace_events_hist.c:create_var_fields
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:find_event_var
  - kernel/trace/trace_events_hist.c:find_event_var
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
In kernel/trace/trace_events_hist.c (ffffffff812de120)
Location: kernel/trace/trace_events_hist.c:1103
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_actions
  - kernel/trace/trace_events_hist.c:create_var_fields
  - kernel/trace/trace_events_hist.c:create_var_fields
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:find_event_var
  - kernel/trace/trace_events_hist.c:find_event_var
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
struct hist_field *find_var_field(struct hist_trigger_data *hist_data, const char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffff800010244210)
Location: kernel/trace/trace_events_hist.c:1772
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:find_file_var
```
**Symbols:**

```
ffff800010244210-ffff8000102442a0: find_var_field (STB_LOCAL)
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
struct hist_field *find_var_field(struct hist_trigger_data *hist_data, const char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (c0000000002d7890)
Location: kernel/trace/trace_events_hist.c:1772
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:find_file_var
```
**Symbols:**

```
c0000000002d7890-c0000000002d7ac8: find_var_field (STB_LOCAL)
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
struct hist_field *find_var_field(struct hist_trigger_data *hist_data, const char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bcc60)
Location: kernel/trace/trace_events_hist.c:1772
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:find_file_var
```
**Symbols:**

```
ffffffff811bcc60-ffffffff811bccbc: find_var_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct hist_field *find_var_field(struct hist_trigger_data *hist_data, const char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811afa40)
Location: kernel/trace/trace_events_hist.c:1772
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:find_file_var
```
**Symbols:**

```
ffffffff811afa40-ffffffff811afa9c: find_var_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct hist_field *find_var_field(struct hist_trigger_data *hist_data, const char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811baa30)
Location: kernel/trace/trace_events_hist.c:1772
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:find_file_var
```
**Symbols:**

```
ffffffff811baa30-ffffffff811baa8c: find_var_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct hist_field *find_var_field(struct hist_trigger_data *hist_data, const char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c8ad0)
Location: kernel/trace/trace_events_hist.c:1772
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:find_file_var
```
**Symbols:**

```
ffffffff811c8ad0-ffffffff811c8b2c: find_var_field (STB_LOCAL)
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
