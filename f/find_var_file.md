# Function: <code>find_var_file</code>

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
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct trace_event_file *find_var_file(struct trace_array *tr, char *system, char *event_name, char *var_name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8119f390)
Location: kernel/trace/trace_events_hist.c:1502
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:find_event_var
  - kernel/trace/trace_events_hist.c:find_event_var
```
**Symbols:**

```
ffffffff8119f390-ffffffff8119f42b: find_var_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct trace_event_file *find_var_file(struct trace_array *tr, char *system, char *event_name, char *var_name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811ada80)
Location: kernel/trace/trace_events_hist.c:1586
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:find_event_var
  - kernel/trace/trace_events_hist.c:find_event_var
```
**Symbols:**

```
ffffffff811ada80-ffffffff811adb1b: find_var_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct trace_event_file *find_var_file(struct trace_array *tr, char *system, char *event_name, char *var_name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bb9a0)
Location: kernel/trace/trace_events_hist.c:1740
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:find_event_var
  - kernel/trace/trace_events_hist.c:find_event_var
```
**Symbols:**

```
ffffffff811bb9a0-ffffffff811bba65: find_var_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct trace_event_file *find_var_file(struct trace_array *tr, char *system, char *event_name, char *var_name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c71f0)
Location: kernel/trace/trace_events_hist.c:1816
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:find_event_var
  - kernel/trace/trace_events_hist.c:find_event_var
```
**Symbols:**

```
ffffffff811c71f0-ffffffff811c72b5: find_var_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e3e00)
Location: kernel/trace/trace_events_hist.c:907
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:find_event_var
  - kernel/trace/trace_events_hist.c:find_match_var
Direct callers:
  - kernel/trace/trace_events_hist.c:find_event_var
  - kernel/trace/trace_events_hist.c:find_match_var
```
**Symbols:**

```
ffffffff811e3a70-ffffffff811e3b78: find_var_file.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e17f0)
Location: kernel/trace/trace_events_hist.c:910
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:find_event_var
  - kernel/trace/trace_events_hist.c:find_match_var
Direct callers:
  - kernel/trace/trace_events_hist.c:find_event_var
  - kernel/trace/trace_events_hist.c:find_match_var
```
**Symbols:**

```
ffffffff811e1390-ffffffff811e1498: find_var_file.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e3316)
Location: kernel/trace/trace_events_hist.c:926
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:find_event_var
  - kernel/trace/trace_events_hist.c:find_event_var
Direct callers:
  - kernel/trace/trace_events_hist.c:find_event_var
  - kernel/trace/trace_events_hist.c:find_event_var
```
**Symbols:**

```
ffffffff811e26f0-ffffffff811e27f8: find_var_file.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812133ca)
Location: kernel/trace/trace_events_hist.c:950
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:find_event_var
  - kernel/trace/trace_events_hist.c:find_event_var
Direct callers:
  - kernel/trace/trace_events_hist.c:find_event_var
  - kernel/trace/trace_events_hist.c:find_event_var
```
**Symbols:**

```
ffffffff81212a30-ffffffff81212b6b: find_var_file.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff81250794)
Location: kernel/trace/trace_events_hist.c:1124
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:find_event_var
  - kernel/trace/trace_events_hist.c:find_event_var
Direct callers:
  - kernel/trace/trace_events_hist.c:find_event_var
  - kernel/trace/trace_events_hist.c:find_event_var
```
**Symbols:**

```
ffffffff8124f890-ffffffff8124f9ef: find_var_file.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8129f9e4)
Location: kernel/trace/trace_events_hist.c:1157
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:find_event_var
  - kernel/trace/trace_events_hist.c:find_event_var
Direct callers:
  - kernel/trace/trace_events_hist.c:find_event_var
  - kernel/trace/trace_events_hist.c:find_event_var
```
**Symbols:**

```
ffffffff8129ea20-ffffffff8129eb7f: find_var_file.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812bda37)
Location: kernel/trace/trace_events_hist.c:1154
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:find_event_var
  - kernel/trace/trace_events_hist.c:find_event_var
Direct callers:
  - kernel/trace/trace_events_hist.c:find_event_var
  - kernel/trace/trace_events_hist.c:find_event_var
```
**Symbols:**

```
ffffffff812bc6a0-ffffffff812bc7fd: find_var_file.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812da067)
Location: kernel/trace/trace_events_hist.c:1147
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:find_event_var
  - kernel/trace/trace_events_hist.c:find_event_var
Direct callers:
  - kernel/trace/trace_events_hist.c:find_event_var
  - kernel/trace/trace_events_hist.c:find_event_var
```
**Symbols:**

```
ffffffff812d8b90-ffffffff812d8ced: find_var_file.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct trace_event_file *find_var_file(struct trace_array *tr, char *system, char *event_name, char *var_name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffff8000102474c0)
Location: kernel/trace/trace_events_hist.c:1816
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:find_event_var
  - kernel/trace/trace_events_hist.c:find_event_var
```
**Symbols:**

```
ffff8000102474c0-ffff8000102475b8: find_var_file (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct trace_event_file *find_var_file(struct trace_array *tr, char *system, char *event_name, char *var_name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (c0000000002dc9c0)
Location: kernel/trace/trace_events_hist.c:1816
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:find_event_var
  - kernel/trace/trace_events_hist.c:find_event_var
  - kernel/trace/trace_events_hist.c:find_event_var
```
**Symbols:**

```
c0000000002dc9c0-c0000000002dcb10: find_var_file (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct trace_event_file *find_var_file(struct trace_array *tr, char *system, char *event_name, char *var_name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bf810)
Location: kernel/trace/trace_events_hist.c:1816
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:find_event_var
  - kernel/trace/trace_events_hist.c:find_event_var
```
**Symbols:**

```
ffffffff811bf810-ffffffff811bf8d5: find_var_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct trace_event_file *find_var_file(struct trace_array *tr, char *system, char *event_name, char *var_name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811b25f0)
Location: kernel/trace/trace_events_hist.c:1816
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:find_event_var
  - kernel/trace/trace_events_hist.c:find_event_var
```
**Symbols:**

```
ffffffff811b25f0-ffffffff811b26b5: find_var_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct trace_event_file *find_var_file(struct trace_array *tr, char *system, char *event_name, char *var_name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bd5e0)
Location: kernel/trace/trace_events_hist.c:1816
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:find_event_var
  - kernel/trace/trace_events_hist.c:find_event_var
```
**Symbols:**

```
ffffffff811bd5e0-ffffffff811bd6a5: find_var_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct trace_event_file *find_var_file(struct trace_array *tr, char *system, char *event_name, char *var_name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811cb680)
Location: kernel/trace/trace_events_hist.c:1816
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:find_event_var
  - kernel/trace/trace_events_hist.c:find_event_var
```
**Symbols:**

```
ffffffff811cb680-ffffffff811cb745: find_var_file (STB_LOCAL)
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
