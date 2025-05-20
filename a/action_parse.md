# Function: <code>action_parse</code>

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
int action_parse(struct trace_array *tr, char *str, struct action_data *data, enum handler_id handler);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811b95b0)
Location: kernel/trace/trace_events_hist.c:3879
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:track_data_parse
```
**Symbols:**

```
ffffffff811b95b0-ffffffff811b986c: action_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int action_parse(struct trace_array *tr, char *str, struct action_data *data, enum handler_id handler);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c4be0)
Location: kernel/trace/trace_events_hist.c:3996
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:track_data_parse
```
**Symbols:**

```
ffffffff811c4be0-ffffffff811c4e9c: action_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int action_parse(struct trace_array *tr, char *str, struct action_data *data, enum handler_id handler);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e14f0)
Location: kernel/trace/trace_events_hist.c:3092
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:track_data_parse
```
**Symbols:**

```
ffffffff811e14f0-ffffffff811e17ac: action_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int action_parse(struct trace_array *tr, char *str, struct action_data *data, enum handler_id handler);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811df0d0)
Location: kernel/trace/trace_events_hist.c:3102
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:track_data_parse
```
**Symbols:**

```
ffffffff811df0d0-ffffffff811df38c: action_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int action_parse(struct trace_array *tr, char *str, struct action_data *data, enum handler_id handler);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e0280)
Location: kernel/trace/trace_events_hist.c:3168
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:track_data_parse
```
**Symbols:**

```
ffffffff811e0280-ffffffff811e0537: action_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int action_parse(struct trace_array *tr, char *str, struct action_data *data, enum handler_id handler);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff81210600)
Location: kernel/trace/trace_events_hist.c:3224
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:track_data_parse
```
**Symbols:**

```
ffffffff81210600-ffffffff812108b7: action_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int action_parse(struct trace_array *tr, char *str, struct action_data *data, enum handler_id handler);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812531c0)
Location: kernel/trace/trace_events_hist.c:3601
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:track_data_parse
```
**Symbols:**

```
ffffffff812531c0-ffffffff812534d0: action_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int action_parse(struct trace_array *tr, char *str, struct action_data *data, enum handler_id handler);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812a2760)
Location: kernel/trace/trace_events_hist.c:3653
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:track_data_parse
```
**Symbols:**

```
ffffffff812a2760-ffffffff812a2a70: action_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int action_parse(struct trace_array *tr, char *str, struct action_data *data, enum handler_id handler);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812c05c0)
Location: kernel/trace/trace_events_hist.c:3691
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:track_data_parse
```
**Symbols:**

```
ffffffff812c05c0-ffffffff812c08d0: action_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int action_parse(struct trace_array *tr, char *str, struct action_data *data, enum handler_id handler);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812dcc10)
Location: kernel/trace/trace_events_hist.c:3684
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:parse_actions
  - kernel/trace/trace_events_hist.c:onmatch_parse
```
**Symbols:**

```
ffffffff812dcc10-ffffffff812dcf27: action_parse (STB_LOCAL)
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
int action_parse(struct trace_array *tr, char *str, struct action_data *data, enum handler_id handler);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffff8000102448f0)
Location: kernel/trace/trace_events_hist.c:3996
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:track_data_parse
```
**Symbols:**

```
ffff8000102448f0-ffff800010244c28: action_parse (STB_LOCAL)
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
int action_parse(struct trace_array *tr, char *str, struct action_data *data, enum handler_id handler);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (c0000000002d84b0)
Location: kernel/trace/trace_events_hist.c:3996
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:track_data_parse
```
**Symbols:**

```
c0000000002d84b0-c0000000002d89ac: action_parse (STB_LOCAL)
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
int action_parse(struct trace_array *tr, char *str, struct action_data *data, enum handler_id handler);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bd200)
Location: kernel/trace/trace_events_hist.c:3996
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:track_data_parse
```
**Symbols:**

```
ffffffff811bd200-ffffffff811bd4bc: action_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int action_parse(struct trace_array *tr, char *str, struct action_data *data, enum handler_id handler);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811affe0)
Location: kernel/trace/trace_events_hist.c:3996
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:track_data_parse
```
**Symbols:**

```
ffffffff811affe0-ffffffff811b029c: action_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int action_parse(struct trace_array *tr, char *str, struct action_data *data, enum handler_id handler);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bafd0)
Location: kernel/trace/trace_events_hist.c:3996
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:track_data_parse
```
**Symbols:**

```
ffffffff811bafd0-ffffffff811bb28c: action_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int action_parse(struct trace_array *tr, char *str, struct action_data *data, enum handler_id handler);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c9070)
Location: kernel/trace/trace_events_hist.c:3996
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:track_data_parse
```
**Symbols:**

```
ffffffff811c9070-ffffffff811c932c: action_parse (STB_LOCAL)
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
