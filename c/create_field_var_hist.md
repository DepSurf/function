# Function: <code>create_field_var_hist</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811a2fa2)
Location: kernel/trace/trace_events_hist.c:2922
Inline: True
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
In kernel/trace/trace_events_hist.c (ffffffff811b1b0f)
Location: kernel/trace/trace_events_hist.c:3038
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct hist_field *create_field_var_hist(struct hist_trigger_data *target_hist_data, char *subsys_name, char *event_name, char *field_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bfc60)
Location: kernel/trace/trace_events_hist.c:3195
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_action_create
```
**Symbols:**

```
ffffffff811bfc60-ffffffff811c022c: create_field_var_hist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct hist_field *create_field_var_hist(struct hist_trigger_data *target_hist_data, char *subsys_name, char *event_name, char *field_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811cb4b0)
Location: kernel/trace/trace_events_hist.c:3312
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_action_create
```
**Symbols:**

```
ffffffff811cb4b0-ffffffff811cba7c: create_field_var_hist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct hist_field *create_field_var_hist(struct hist_trigger_data *target_hist_data, char *subsys_name, char *event_name, char *field_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e7260)
Location: kernel/trace/trace_events_hist.c:2407
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_action_create
```
**Symbols:**

```
ffffffff811e7260-ffffffff811e7652: create_field_var_hist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct hist_field *create_field_var_hist(struct hist_trigger_data *target_hist_data, char *subsys_name, char *event_name, char *field_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e4c20)
Location: kernel/trace/trace_events_hist.c:2417
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_action_create
```
**Symbols:**

```
ffffffff811e4c20-ffffffff811e5012: create_field_var_hist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct hist_field *create_field_var_hist(struct hist_trigger_data *target_hist_data, char *subsys_name, char *event_name, char *field_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e6200)
Location: kernel/trace/trace_events_hist.c:2474
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_action_create
```
**Symbols:**

```
ffffffff811e6200-ffffffff811e66bb: create_field_var_hist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct hist_field *create_field_var_hist(struct hist_trigger_data *target_hist_data, char *subsys_name, char *event_name, char *field_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812170c0)
Location: kernel/trace/trace_events_hist.c:2528
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_action_create
```
**Symbols:**

```
ffffffff812170c0-ffffffff8121761f: create_field_var_hist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct hist_field *create_field_var_hist(struct hist_trigger_data *target_hist_data, char *subsys_name, char *event_name, char *field_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:2905
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_action_create
```
**Symbols:**

```
ffffffff812554a0-ffffffff81255bca: create_field_var_hist (STB_LOCAL)
ffffffff81e68291-ffffffff81e6829d: create_field_var_hist.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct hist_field *create_field_var_hist(struct hist_trigger_data *target_hist_data, char *subsys_name, char *event_name, char *field_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812a4960)
Location: kernel/trace/trace_events_hist.c:2956
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_action_create
```
**Symbols:**

```
ffffffff812a4960-ffffffff812a5095: create_field_var_hist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct hist_field *create_field_var_hist(struct hist_trigger_data *target_hist_data, char *subsys_name, char *event_name, char *field_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812c2840)
Location: kernel/trace/trace_events_hist.c:2978
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_action_create
```
**Symbols:**

```
ffffffff812c2840-ffffffff812c31c0: create_field_var_hist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct hist_field *create_field_var_hist(struct hist_trigger_data *target_hist_data, char *subsys_name, char *event_name, char *field_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812df0f0)
Location: kernel/trace/trace_events_hist.c:2971
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_action_create
```
**Symbols:**

```
ffffffff812df0f0-ffffffff812dface: create_field_var_hist (STB_LOCAL)
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
struct hist_field *create_field_var_hist(struct hist_trigger_data *target_hist_data, char *subsys_name, char *event_name, char *field_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffff80001024a918)
Location: kernel/trace/trace_events_hist.c:3312
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_action_create
```
**Symbols:**

```
ffff80001024a918-ffff80001024ae74: create_field_var_hist (STB_LOCAL)
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
struct hist_field *create_field_var_hist(struct hist_trigger_data *target_hist_data, char *subsys_name, char *event_name, char *field_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (c0000000002e5a90)
Location: kernel/trace/trace_events_hist.c:3312
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
```
**Symbols:**

```
c0000000002e5a90-c0000000002e6294: create_field_var_hist (STB_LOCAL)
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
struct hist_field *create_field_var_hist(struct hist_trigger_data *target_hist_data, char *subsys_name, char *event_name, char *field_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c3ad0)
Location: kernel/trace/trace_events_hist.c:3312
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_action_create
```
**Symbols:**

```
ffffffff811c3ad0-ffffffff811c409c: create_field_var_hist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct hist_field *create_field_var_hist(struct hist_trigger_data *target_hist_data, char *subsys_name, char *event_name, char *field_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811b68b0)
Location: kernel/trace/trace_events_hist.c:3312
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_action_create
```
**Symbols:**

```
ffffffff811b68b0-ffffffff811b6e7c: create_field_var_hist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct hist_field *create_field_var_hist(struct hist_trigger_data *target_hist_data, char *subsys_name, char *event_name, char *field_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c18a0)
Location: kernel/trace/trace_events_hist.c:3312
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_action_create
```
**Symbols:**

```
ffffffff811c18a0-ffffffff811c1e6c: create_field_var_hist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct hist_field *create_field_var_hist(struct hist_trigger_data *target_hist_data, char *subsys_name, char *event_name, char *field_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811cf940)
Location: kernel/trace/trace_events_hist.c:3312
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_action_create
```
**Symbols:**

```
ffffffff811cf940-ffffffff811cff0c: create_field_var_hist (STB_LOCAL)
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
