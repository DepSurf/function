# Function: <code>trace_run_command</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int trace_run_command(const char *buf, int (*createfn)(int, char **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81177320)
Location: kernel/trace/trace.c:8274
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_parse_run_command
```
**Symbols:**

```
ffffffff81177320-ffffffff811773a2: trace_run_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int trace_run_command(const char *buf, int (*createfn)(int, char **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81186330)
Location: kernel/trace/trace.c:8379
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_parse_run_command
```
**Symbols:**

```
ffffffff81186330-ffffffff811863b4: trace_run_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int trace_run_command(const char *buf, int (*createfn)(int, char **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81193cc0)
Location: kernel/trace/trace.c:8453
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_parse_run_command
```
**Symbols:**

```
ffffffff81193cc0-ffffffff81193d44: trace_run_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int trace_run_command(const char *buf, int (*createfn)(int, char **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a17f0)
Location: kernel/trace/trace.c:8958
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
```
**Symbols:**

```
ffffffff811a17f0-ffffffff811a187a: trace_run_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int trace_run_command(const char *buf, int (*createfn)(int, char **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811ad2a0)
Location: kernel/trace/trace.c:9014
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
```
**Symbols:**

```
ffffffff811ad2a0-ffffffff811ad32a: trace_run_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int trace_run_command(const char *buf, int (*createfn)(int, char **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811c4fb0)
Location: kernel/trace/trace.c:9300
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:kprobe_event_delete
  - kernel/trace/trace_kprobe.c:trace_kprobe_run_command
```
**Symbols:**

```
ffffffff811c4fb0-ffffffff811c503a: trace_run_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int trace_run_command(const char *buf, int (*createfn)(int, char **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811c2bf0)
Location: kernel/trace/trace.c:9433
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:kprobe_event_delete
  - kernel/trace/trace_kprobe.c:trace_kprobe_run_command
```
**Symbols:**

```
ffffffff811c2bf0-ffffffff811c2c7a: trace_run_command (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int trace_run_command(const char *buf, int (*createfn)(int, char **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff80001022a500)
Location: kernel/trace/trace.c:9014
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
```
**Symbols:**

```
ffff80001022a500-ffff80001022a598: trace_run_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int trace_run_command(const char *buf, int (*createfn)(int, char **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0467b9c)
Location: kernel/trace/trace.c:9014
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
```
**Symbols:**

```
c0467b9c-c0467c3c: trace_run_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int trace_run_command(const char *buf, int (*createfn)(int, char **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002b2190)
Location: kernel/trace/trace.c:9014
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
```
**Symbols:**

```
c0000000002b2190-c0000000002b2270: trace_run_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int trace_run_command(const char *buf, int (*createfn)(int, char **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe000184adc)
Location: kernel/trace/trace.c:9014
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_parse_run_command
```
**Symbols:**

```
ffffffe000184adc-ffffffe000184b38: trace_run_command (STB_GLOBAL)
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
int trace_run_command(const char *buf, int (*createfn)(int, char **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a58c0)
Location: kernel/trace/trace.c:9014
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
```
**Symbols:**

```
ffffffff811a58c0-ffffffff811a594a: trace_run_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int trace_run_command(const char *buf, int (*createfn)(int, char **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81198850)
Location: kernel/trace/trace.c:9014
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
```
**Symbols:**

```
ffffffff81198850-ffffffff811988da: trace_run_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int trace_run_command(const char *buf, int (*createfn)(int, char **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a3690)
Location: kernel/trace/trace.c:9014
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
```
**Symbols:**

```
ffffffff811a3690-ffffffff811a371a: trace_run_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int trace_run_command(const char *buf, int (*createfn)(int, char **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811b1420)
Location: kernel/trace/trace.c:9014
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
```
**Symbols:**

```
ffffffff811b1420-ffffffff811b14aa: trace_run_command (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
