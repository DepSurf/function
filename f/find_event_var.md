# Function: <code>find_event_var</code>

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
struct hist_field *find_event_var(struct hist_trigger_data *hist_data, char *system, char *event_name, char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8119f430)
Location: kernel/trace/trace_events_hist.c:1584
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:find_synthetic_field_var
  - kernel/trace/trace_events_hist.c:parse_atom
```
**Symbols:**

```
ffffffff8119f430-ffffffff8119f564: find_event_var (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct hist_field *find_event_var(struct hist_trigger_data *hist_data, char *system, char *event_name, char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811adb20)
Location: kernel/trace/trace_events_hist.c:1668
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:find_synthetic_field_var
  - kernel/trace/trace_events_hist.c:parse_atom
```
**Symbols:**

```
ffffffff811adb20-ffffffff811adc54: find_event_var (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct hist_field *find_event_var(struct hist_trigger_data *hist_data, char *system, char *event_name, char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bba70)
Location: kernel/trace/trace_events_hist.c:1823
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:find_synthetic_field_var
  - kernel/trace/trace_events_hist.c:parse_atom
```
**Symbols:**

```
ffffffff811bba70-ffffffff811bbbac: find_event_var (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct hist_field *find_event_var(struct hist_trigger_data *hist_data, char *system, char *event_name, char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c72c0)
Location: kernel/trace/trace_events_hist.c:1901
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:find_synthetic_field_var
  - kernel/trace/trace_events_hist.c:parse_atom
```
**Symbols:**

```
ffffffff811c72c0-ffffffff811c73fc: find_event_var (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct hist_field *find_event_var(struct hist_trigger_data *hist_data, char *system, char *event_name, char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e3d10)
Location: kernel/trace/trace_events_hist.c:992
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:find_synthetic_field_var
  - kernel/trace/trace_events_hist.c:parse_atom
```
**Symbols:**

```
ffffffff811e3d10-ffffffff811e3e22: find_event_var (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct hist_field *find_event_var(struct hist_trigger_data *hist_data, char *system, char *event_name, char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e1700)
Location: kernel/trace/trace_events_hist.c:995
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:find_synthetic_field_var
  - kernel/trace/trace_events_hist.c:parse_atom
```
**Symbols:**

```
ffffffff811e1700-ffffffff811e1812: find_event_var (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct hist_field *find_event_var(struct hist_trigger_data *hist_data, char *system, char *event_name, char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e3120)
Location: kernel/trace/trace_events_hist.c:1011
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:find_synthetic_field_var
  - kernel/trace/trace_events_hist.c:parse_atom
```
**Symbols:**

```
ffffffff811e3120-ffffffff811e337f: find_event_var (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct hist_field *find_event_var(struct hist_trigger_data *hist_data, char *system, char *event_name, char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff81213190)
Location: kernel/trace/trace_events_hist.c:1035
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:find_synthetic_field_var
  - kernel/trace/trace_events_hist.c:parse_atom
```
**Symbols:**

```
ffffffff81213190-ffffffff81213484: find_event_var (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct hist_field *find_event_var(struct hist_trigger_data *hist_data, char *system, char *event_name, char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff81250540)
Location: kernel/trace/trace_events_hist.c:1209
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:find_synthetic_field_var
  - kernel/trace/trace_events_hist.c:parse_atom
```
**Symbols:**

```
ffffffff81250540-ffffffff8125088b: find_event_var (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct hist_field *find_event_var(struct hist_trigger_data *hist_data, char *system, char *event_name, char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8129f790)
Location: kernel/trace/trace_events_hist.c:1242
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:find_synthetic_field_var
  - kernel/trace/trace_events_hist.c:parse_atom
```
**Symbols:**

```
ffffffff8129f790-ffffffff8129fadb: find_event_var (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct hist_field *find_event_var(struct hist_trigger_data *hist_data, char *system, char *event_name, char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812bd7e0)
Location: kernel/trace/trace_events_hist.c:1239
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:find_synthetic_field_var
  - kernel/trace/trace_events_hist.c:parse_atom
```
**Symbols:**

```
ffffffff812bd7e0-ffffffff812bdb31: find_event_var (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct hist_field *find_event_var(struct hist_trigger_data *hist_data, char *system, char *event_name, char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812d9e10)
Location: kernel/trace/trace_events_hist.c:1232
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:find_synthetic_field_var
  - kernel/trace/trace_events_hist.c:parse_atom
```
**Symbols:**

```
ffffffff812d9e10-ffffffff812da161: find_event_var (STB_LOCAL)
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
struct hist_field *find_event_var(struct hist_trigger_data *hist_data, char *system, char *event_name, char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffff8000102475b8)
Location: kernel/trace/trace_events_hist.c:1901
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:find_synthetic_field_var
  - kernel/trace/trace_events_hist.c:parse_atom
```
**Symbols:**

```
ffff8000102475b8-ffff800010247714: find_event_var (STB_LOCAL)
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
struct hist_field *find_event_var(struct hist_trigger_data *hist_data, char *system, char *event_name, char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (c0000000002dcb10)
Location: kernel/trace/trace_events_hist.c:1901
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:find_synthetic_field_var
  - kernel/trace/trace_events_hist.c:parse_atom
```
**Symbols:**

```
c0000000002dcb10-c0000000002dcd64: find_event_var (STB_LOCAL)
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
struct hist_field *find_event_var(struct hist_trigger_data *hist_data, char *system, char *event_name, char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bf8e0)
Location: kernel/trace/trace_events_hist.c:1901
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:find_synthetic_field_var
  - kernel/trace/trace_events_hist.c:parse_atom
```
**Symbols:**

```
ffffffff811bf8e0-ffffffff811bfa1c: find_event_var (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct hist_field *find_event_var(struct hist_trigger_data *hist_data, char *system, char *event_name, char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811b26c0)
Location: kernel/trace/trace_events_hist.c:1901
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:find_synthetic_field_var
  - kernel/trace/trace_events_hist.c:parse_atom
```
**Symbols:**

```
ffffffff811b26c0-ffffffff811b27fc: find_event_var (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct hist_field *find_event_var(struct hist_trigger_data *hist_data, char *system, char *event_name, char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bd6b0)
Location: kernel/trace/trace_events_hist.c:1901
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:find_synthetic_field_var
  - kernel/trace/trace_events_hist.c:parse_atom
```
**Symbols:**

```
ffffffff811bd6b0-ffffffff811bd7ec: find_event_var (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct hist_field *find_event_var(struct hist_trigger_data *hist_data, char *system, char *event_name, char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811cb750)
Location: kernel/trace/trace_events_hist.c:1901
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:find_synthetic_field_var
  - kernel/trace/trace_events_hist.c:parse_atom
```
**Symbols:**

```
ffffffff811cb750-ffffffff811cb88c: find_event_var (STB_LOCAL)
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
