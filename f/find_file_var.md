# Function: <code>find_file_var</code>

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
struct hist_field *find_file_var(struct trace_event_file *file, const char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8119cc00)
Location: kernel/trace/trace_events_hist.c:1533
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:find_event_var
  - kernel/trace/trace_events_hist.c:find_event_var
```
**Symbols:**

```
ffffffff8119cc00-ffffffff8119cc57: find_file_var (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct hist_field *find_file_var(struct trace_event_file *file, const char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811ab040)
Location: kernel/trace/trace_events_hist.c:1617
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:find_event_var
  - kernel/trace/trace_events_hist.c:find_event_var
```
**Symbols:**

```
ffffffff811ab040-ffffffff811ab097: find_file_var (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct hist_field *find_file_var(struct trace_event_file *file, const char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811b90c0)
Location: kernel/trace/trace_events_hist.c:1771
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:find_event_var
  - kernel/trace/trace_events_hist.c:find_event_var
```
**Symbols:**

```
ffffffff811b90c0-ffffffff811b9117: find_file_var (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct hist_field *find_file_var(struct trace_event_file *file, const char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c46a0)
Location: kernel/trace/trace_events_hist.c:1847
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:find_event_var
  - kernel/trace/trace_events_hist.c:find_event_var
```
**Symbols:**

```
ffffffff811c46a0-ffffffff811c46f7: find_file_var (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff811e3d5e)
Location: kernel/trace/trace_events_hist.c:938
Inline: True
Inline callers:
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
In kernel/trace/trace_events_hist.c (ffffffff811e174e)
Location: kernel/trace/trace_events_hist.c:941
Inline: True
Inline callers:
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
In kernel/trace/trace_events_hist.c (ffffffff811e317b)
Location: kernel/trace/trace_events_hist.c:957
Inline: True
Inline callers:
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
In kernel/trace/trace_events_hist.c (ffffffff812131eb)
Location: kernel/trace/trace_events_hist.c:981
Inline: True
Inline callers:
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
In kernel/trace/trace_events_hist.c (ffffffff8125058c)
Location: kernel/trace/trace_events_hist.c:1155
Inline: True
Inline callers:
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
In kernel/trace/trace_events_hist.c (ffffffff8129f7dc)
Location: kernel/trace/trace_events_hist.c:1188
Inline: True
Inline callers:
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
In kernel/trace/trace_events_hist.c (ffffffff812bd82c)
Location: kernel/trace/trace_events_hist.c:1185
Inline: True
Inline callers:
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
In kernel/trace/trace_events_hist.c (ffffffff812d9e5c)
Location: kernel/trace/trace_events_hist.c:1178
Inline: True
Inline callers:
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
struct hist_field *find_file_var(struct trace_event_file *file, const char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffff8000102442a0)
Location: kernel/trace/trace_events_hist.c:1847
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:find_event_var
  - kernel/trace/trace_events_hist.c:find_event_var
```
**Symbols:**

```
ffff8000102442a0-ffff800010244328: find_file_var (STB_LOCAL)
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
struct hist_field *find_file_var(struct trace_event_file *file, const char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (c0000000002d7ad0)
Location: kernel/trace/trace_events_hist.c:1847
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:find_event_var
  - kernel/trace/trace_events_hist.c:find_event_var
```
**Symbols:**

```
c0000000002d7ad0-c0000000002d7b80: find_file_var (STB_LOCAL)
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
struct hist_field *find_file_var(struct trace_event_file *file, const char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bccc0)
Location: kernel/trace/trace_events_hist.c:1847
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:find_event_var
  - kernel/trace/trace_events_hist.c:find_event_var
```
**Symbols:**

```
ffffffff811bccc0-ffffffff811bcd17: find_file_var (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct hist_field *find_file_var(struct trace_event_file *file, const char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811afaa0)
Location: kernel/trace/trace_events_hist.c:1847
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:find_event_var
  - kernel/trace/trace_events_hist.c:find_event_var
```
**Symbols:**

```
ffffffff811afaa0-ffffffff811afaf7: find_file_var (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct hist_field *find_file_var(struct trace_event_file *file, const char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811baa90)
Location: kernel/trace/trace_events_hist.c:1847
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:find_event_var
  - kernel/trace/trace_events_hist.c:find_event_var
```
**Symbols:**

```
ffffffff811baa90-ffffffff811baae7: find_file_var (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct hist_field *find_file_var(struct trace_event_file *file, const char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c8b30)
Location: kernel/trace/trace_events_hist.c:1847
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:find_event_var
  - kernel/trace/trace_events_hist.c:find_event_var
```
**Symbols:**

```
ffffffff811c8b30-ffffffff811c8b87: find_file_var (STB_LOCAL)
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
