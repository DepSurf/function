# Function: <code>parse_pred</code>

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
int parse_pred(const char *str, void *data, int pos, struct filter_parse_error *pe, struct filter_pred **pred_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff81198b50)
Location: kernel/trace/trace_events_filter.c:1138
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:process_preds
```
**Symbols:**

```
ffffffff81198b50-ffffffff8119945c: parse_pred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int parse_pred(const char *str, void *data, int pos, struct filter_parse_error *pe, struct filter_pred **pred_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811a6c90)
Location: kernel/trace/trace_events_filter.c:1128
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:process_preds
```
**Symbols:**

```
ffffffff811a6c90-ffffffff811a75ce: parse_pred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int parse_pred(const char *str, void *data, int pos, struct filter_parse_error *pe, struct filter_pred **pred_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811b4c30)
Location: kernel/trace/trace_events_filter.c:1150
Inline: False
```
**Symbols:**

```
ffffffff811b4c30-ffffffff811b549f: parse_pred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int parse_pred(const char *str, void *data, int pos, struct filter_parse_error *pe, struct filter_pred **pred_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811c0270)
Location: kernel/trace/trace_events_filter.c:1152
Inline: False
```
**Symbols:**

```
ffffffff811c0270-ffffffff811c0af4: parse_pred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int parse_pred(const char *str, void *data, int pos, struct filter_parse_error *pe, struct filter_pred **pred_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811d9ff0)
Location: kernel/trace/trace_events_filter.c:1152
Inline: False
```
**Symbols:**

```
ffffffff811d9ff0-ffffffff811da874: parse_pred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int parse_pred(const char *str, void *data, int pos, struct filter_parse_error *pe, struct filter_pred **pred_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_filter.c (0)
Location: kernel/trace/trace_events_filter.c:1152
Inline: False
```
**Symbols:**

```
ffffffff811d70f0-ffffffff811d79a7: parse_pred (STB_LOCAL)
ffffffff81be630b-ffffffff81be6317: parse_pred.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int parse_pred(const char *str, void *data, int pos, struct filter_parse_error *pe, struct filter_pred **pred_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_filter.c (0)
Location: kernel/trace/trace_events_filter.c:1152
Inline: False
```
**Symbols:**

```
ffffffff811d83e0-ffffffff811d8c98: parse_pred (STB_LOCAL)
ffffffff81bd7fc6-ffffffff81bd7fd2: parse_pred.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int parse_pred(const char *str, void *data, int pos, struct filter_parse_error *pe, struct filter_pred **pred_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff81205460)
Location: kernel/trace/trace_events_filter.c:1223
Inline: False
```
**Symbols:**

```
ffffffff81205460-ffffffff81205fab: parse_pred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int parse_pred(const char *str, void *data, int pos, struct filter_parse_error *pe, struct filter_pred **pred_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff81240c80)
Location: kernel/trace/trace_events_filter.c:1249
Inline: False
```
**Symbols:**

```
ffffffff81240c80-ffffffff8124178c: parse_pred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int parse_pred(const char *str, void *data, int pos, struct filter_parse_error *pe, struct filter_pred **pred_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff8128e780)
Location: kernel/trace/trace_events_filter.c:1346
Inline: False
```
**Symbols:**

```
ffffffff8128e780-ffffffff8128f10d: parse_pred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int parse_pred(const char *str, void *data, int pos, struct filter_parse_error *pe, struct filter_pred **pred_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff812ab6c0)
Location: kernel/trace/trace_events_filter.c:1362
Inline: False
```
**Symbols:**

```
ffffffff812ab6c0-ffffffff812ac2c1: parse_pred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int parse_pred(const char *str, void *data, int pos, struct filter_parse_error *pe, struct filter_pred **pred_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff812c7810)
Location: kernel/trace/trace_events_filter.c:1499
Inline: False
```
**Symbols:**

```
ffffffff812c7810-ffffffff812c874d: parse_pred (STB_LOCAL)
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
int parse_pred(const char *str, void *data, int pos, struct filter_parse_error *pe, struct filter_pred **pred_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffff80001023f8d0)
Location: kernel/trace/trace_events_filter.c:1152
Inline: False
```
**Symbols:**

```
ffff80001023f8d0-ffff80001024019c: parse_pred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int parse_pred(const char *str, void *data, int pos, struct filter_parse_error *pe, struct filter_pred **pred_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (c047b184)
Location: kernel/trace/trace_events_filter.c:1152
Inline: False
```
**Symbols:**

```
c047b184-c047bb08: parse_pred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int parse_pred(const char *str, void *data, int pos, struct filter_parse_error *pe, struct filter_pred **pred_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (c0000000002d0020)
Location: kernel/trace/trace_events_filter.c:1152
Inline: False
```
**Symbols:**

```
c0000000002d0020-c0000000002d0aa4: parse_pred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int parse_pred(const char *str, void *data, int pos, struct filter_parse_error *pe, struct filter_pred **pred_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffe000194e42)
Location: kernel/trace/trace_events_filter.c:1152
Inline: False
```
**Symbols:**

```
ffffffe000194e42-ffffffe000195516: parse_pred (STB_LOCAL)
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
int parse_pred(const char *str, void *data, int pos, struct filter_parse_error *pe, struct filter_pred **pred_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811b8890)
Location: kernel/trace/trace_events_filter.c:1152
Inline: False
```
**Symbols:**

```
ffffffff811b8890-ffffffff811b9114: parse_pred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int parse_pred(const char *str, void *data, int pos, struct filter_parse_error *pe, struct filter_pred **pred_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811ab670)
Location: kernel/trace/trace_events_filter.c:1152
Inline: False
```
**Symbols:**

```
ffffffff811ab670-ffffffff811abef4: parse_pred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int parse_pred(const char *str, void *data, int pos, struct filter_parse_error *pe, struct filter_pred **pred_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811b6660)
Location: kernel/trace/trace_events_filter.c:1152
Inline: False
```
**Symbols:**

```
ffffffff811b6660-ffffffff811b6ee4: parse_pred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int parse_pred(const char *str, void *data, int pos, struct filter_parse_error *pe, struct filter_pred **pred_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811c4700)
Location: kernel/trace/trace_events_filter.c:1152
Inline: False
```
**Symbols:**

```
ffffffff811c4700-ffffffff811c4f84: parse_pred (STB_LOCAL)
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
