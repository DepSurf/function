# Function: <code>dynevent_str_add</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dynevent_str_add(struct dynevent_cmd *cmd, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_dynevent.c (0)
Location: kernel/trace/trace_dynevent.c:325
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:__kprobe_event_gen_cmd_start
```
**Symbols:**

```
ffffffff811f1e62-ffffffff811f1e7b: dynevent_str_add.cold (STB_LOCAL)
ffffffff811f1d70-ffffffff811f1d8c: dynevent_str_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dynevent_str_add(struct dynevent_cmd *cmd, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_dynevent.c (0)
Location: kernel/trace/trace_dynevent.c:325
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:__kprobe_event_gen_cmd_start
```
**Symbols:**

```
ffffffff81be64c0-ffffffff81be64d9: dynevent_str_add.cold (STB_LOCAL)
ffffffff811f07a0-ffffffff811f07bc: dynevent_str_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dynevent_str_add(struct dynevent_cmd *cmd, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_dynevent.c (0)
Location: kernel/trace/trace_dynevent.c:336
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:__kprobe_event_gen_cmd_start
```
**Symbols:**

```
ffffffff81bd81a8-ffffffff81bd81c1: dynevent_str_add.cold (STB_LOCAL)
ffffffff811f1700-ffffffff811f171c: dynevent_str_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dynevent_str_add(struct dynevent_cmd *cmd, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_dynevent.c (0)
Location: kernel/trace/trace_dynevent.c:374
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:__kprobe_event_gen_cmd_start
```
**Symbols:**

```
ffffffff81cb764e-ffffffff81cb7667: dynevent_str_add.cold (STB_LOCAL)
ffffffff812228a0-ffffffff812228bc: dynevent_str_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dynevent_str_add(struct dynevent_cmd *cmd, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_dynevent.c (0)
Location: kernel/trace/trace_dynevent.c:369
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:__kprobe_event_gen_cmd_start
```
**Symbols:**

```
ffffffff81e68728-ffffffff81e68741: dynevent_str_add.cold (STB_LOCAL)
ffffffff812626d0-ffffffff812626f3: dynevent_str_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dynevent_str_add(struct dynevent_cmd *cmd, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff812b3f40)
Location: kernel/trace/trace_dynevent.c:371
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:__kprobe_event_gen_cmd_start
```
**Symbols:**

```
ffffffff812b3f40-ffffffff812b3f75: dynevent_str_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dynevent_str_add(struct dynevent_cmd *cmd, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff812d6840)
Location: kernel/trace/trace_dynevent.c:371
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:__kprobe_event_gen_cmd_start
```
**Symbols:**

```
ffffffff812d6840-ffffffff812d6875: dynevent_str_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dynevent_str_add(struct dynevent_cmd *cmd, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff812f4350)
Location: kernel/trace/trace_dynevent.c:371
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:__kprobe_event_gen_cmd_start
```
**Symbols:**

```
ffffffff812f4350-ffffffff812f4385: dynevent_str_add (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
