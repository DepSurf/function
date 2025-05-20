# Function: <code>parse_action_params</code>

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
int parse_action_params(char *params, struct action_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8119d220)
Location: kernel/trace/trace_events_hist.c:3390
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
**Symbols:**

```
ffffffff8119d220-ffffffff8119d2e5: parse_action_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int parse_action_params(char *params, struct action_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811ab720)
Location: kernel/trace/trace_events_hist.c:3497
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
```
**Symbols:**

```
ffffffff811ab720-ffffffff811ab7e5: parse_action_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int parse_action_params(struct trace_array *tr, char *params, struct action_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811b9450)
Location: kernel/trace/trace_events_hist.c:3833
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
```
**Symbols:**

```
ffffffff811b9450-ffffffff811b95a4: parse_action_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int parse_action_params(struct trace_array *tr, char *params, struct action_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c4a80)
Location: kernel/trace/trace_events_hist.c:3950
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
```
**Symbols:**

```
ffffffff811c4a80-ffffffff811c4bd4: parse_action_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int parse_action_params(struct trace_array *tr, char *params, struct action_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e12a0)
Location: kernel/trace/trace_events_hist.c:3046
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
```
**Symbols:**

```
ffffffff811e12a0-ffffffff811e13f4: parse_action_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int parse_action_params(struct trace_array *tr, char *params, struct action_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811dec60)
Location: kernel/trace/trace_events_hist.c:3056
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
```
**Symbols:**

```
ffffffff811dec60-ffffffff811dedb4: parse_action_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int parse_action_params(struct trace_array *tr, char *params, struct action_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e0030)
Location: kernel/trace/trace_events_hist.c:3122
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
```
**Symbols:**

```
ffffffff811e0030-ffffffff811e0184: parse_action_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int parse_action_params(struct trace_array *tr, char *params, struct action_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:3178
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
```
**Symbols:**

```
ffffffff81210460-ffffffff81210600: parse_action_params (STB_LOCAL)
ffffffff81cb6ef9-ffffffff81cb6f16: parse_action_params.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int parse_action_params(struct trace_array *tr, char *params, struct action_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:3555
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
```
**Symbols:**

```
ffffffff8124fd40-ffffffff8124ff34: parse_action_params (STB_LOCAL)
ffffffff81e6818d-ffffffff81e681aa: parse_action_params.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int parse_action_params(struct trace_array *tr, char *params, struct action_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:3606
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
```
**Symbols:**

```
ffffffff8129f0e0-ffffffff8129f2d9: parse_action_params (STB_LOCAL)
ffffffff8205eb89-ffffffff8205eba6: parse_action_params.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int parse_action_params(struct trace_array *tr, char *params, struct action_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:3644
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
```
**Symbols:**

```
ffffffff812bcdb0-ffffffff812bcfa8: parse_action_params (STB_LOCAL)
ffffffff820dd6c6-ffffffff820dd6e3: parse_action_params.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int parse_action_params(struct trace_array *tr, char *params, struct action_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:3637
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
```
**Symbols:**

```
ffffffff812d90b0-ffffffff812d92a8: parse_action_params (STB_LOCAL)
ffffffff821b94ca-ffffffff821b94e7: parse_action_params.cold (STB_LOCAL)
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
int parse_action_params(struct trace_array *tr, char *params, struct action_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffff800010244750)
Location: kernel/trace/trace_events_hist.c:3950
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
```
**Symbols:**

```
ffff800010244750-ffff8000102448ec: parse_action_params (STB_LOCAL)
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
int parse_action_params(struct trace_array *tr, char *params, struct action_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (c0000000002d8280)
Location: kernel/trace/trace_events_hist.c:3950
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
```
**Symbols:**

```
c0000000002d8280-c0000000002d84a4: parse_action_params (STB_LOCAL)
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
int parse_action_params(struct trace_array *tr, char *params, struct action_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bd0a0)
Location: kernel/trace/trace_events_hist.c:3950
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
```
**Symbols:**

```
ffffffff811bd0a0-ffffffff811bd1f4: parse_action_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int parse_action_params(struct trace_array *tr, char *params, struct action_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811afe80)
Location: kernel/trace/trace_events_hist.c:3950
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
```
**Symbols:**

```
ffffffff811afe80-ffffffff811affd4: parse_action_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int parse_action_params(struct trace_array *tr, char *params, struct action_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bae70)
Location: kernel/trace/trace_events_hist.c:3950
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
```
**Symbols:**

```
ffffffff811bae70-ffffffff811bafc4: parse_action_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int parse_action_params(struct trace_array *tr, char *params, struct action_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c8f10)
Location: kernel/trace/trace_events_hist.c:3950
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
```
**Symbols:**

```
ffffffff811c8f10-ffffffff811c9064: parse_action_params (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct trace_array *tr</code>
</li>
<li>
<b>Param reordered. </b>
<code>params, data</code> ➡️ <code>tr, params, data</code>
</li>
</ul>
</details>
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
