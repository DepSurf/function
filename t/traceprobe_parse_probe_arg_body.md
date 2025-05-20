# Function: <code>traceprobe_parse_probe_arg_body</code>

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
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int traceprobe_parse_probe_arg_body(char *arg, ssize_t *size, struct probe_arg *parg, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_probe.c (0)
Location: kernel/trace/trace_probe.c:379
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
```
**Symbols:**

```
ffffffff811bb4b0-ffffffff811bb989: traceprobe_parse_probe_arg_body (STB_LOCAL)
ffffffff811bbead-ffffffff811bbf12: traceprobe_parse_probe_arg_body.cold.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int traceprobe_parse_probe_arg_body(char *arg, ssize_t *size, struct probe_arg *parg, unsigned int flags, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811ca940)
Location: kernel/trace/trace_probe.c:494
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
```
**Symbols:**

```
ffffffff811ca940-ffffffff811cb0d7: traceprobe_parse_probe_arg_body (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int traceprobe_parse_probe_arg_body(char *arg, ssize_t *size, struct probe_arg *parg, unsigned int flags, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811d6820)
Location: kernel/trace/trace_probe.c:543
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
```
**Symbols:**

```
ffffffff811d6820-ffffffff811d6ff0: traceprobe_parse_probe_arg_body (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int traceprobe_parse_probe_arg_body(char *arg, ssize_t *size, struct probe_arg *parg, unsigned int flags, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811f3120)
Location: kernel/trace/trace_probe.c:543
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
```
**Symbols:**

```
ffffffff811f3120-ffffffff811f3904: traceprobe_parse_probe_arg_body (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int traceprobe_parse_probe_arg_body(char *arg, ssize_t *size, struct probe_arg *parg, unsigned int flags, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811f1ad0)
Location: kernel/trace/trace_probe.c:543
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
```
**Symbols:**

```
ffffffff811f1ad0-ffffffff811f22b4: traceprobe_parse_probe_arg_body (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int traceprobe_parse_probe_arg_body(char *arg, ssize_t *size, struct probe_arg *parg, unsigned int flags, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811f2980)
Location: kernel/trace/trace_probe.c:543
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
```
**Symbols:**

```
ffffffff811f2980-ffffffff811f3147: traceprobe_parse_probe_arg_body (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int traceprobe_parse_probe_arg_body(const char *argv, ssize_t *size, struct probe_arg *parg, unsigned int flags, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff81223bd0)
Location: kernel/trace/trace_probe.c:555
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
```
**Symbols:**

```
ffffffff81223bd0-ffffffff812243eb: traceprobe_parse_probe_arg_body (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int traceprobe_parse_probe_arg_body(const char *argv, ssize_t *size, struct probe_arg *parg, unsigned int flags, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_probe.c (0)
Location: kernel/trace/trace_probe.c:560
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
```
**Symbols:**

```
ffffffff81263b80-ffffffff812642b1: traceprobe_parse_probe_arg_body (STB_LOCAL)
ffffffff81e68741-ffffffff81e6874d: traceprobe_parse_probe_arg_body.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int traceprobe_parse_probe_arg_body(const char *argv, ssize_t *size, struct probe_arg *parg, unsigned int flags, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_probe.c (0)
Location: kernel/trace/trace_probe.c:571
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
```
**Symbols:**

```
ffffffff812b55c0-ffffffff812b5d53: traceprobe_parse_probe_arg_body (STB_LOCAL)
ffffffff8205f08e-ffffffff8205f0a9: traceprobe_parse_probe_arg_body.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int traceprobe_parse_probe_arg_body(const char *argv, ssize_t *size, struct probe_arg *parg, struct traceprobe_parse_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_probe.c (0)
Location: kernel/trace/trace_probe.c:871
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
```
**Symbols:**

```
ffffffff812d8500-ffffffff812d8da1: traceprobe_parse_probe_arg_body (STB_LOCAL)
ffffffff820ddc3c-ffffffff820ddc5f: traceprobe_parse_probe_arg_body.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int traceprobe_parse_probe_arg_body(const char *argv, ssize_t *size, struct probe_arg *parg, struct traceprobe_parse_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_probe.c (0)
Location: kernel/trace/trace_probe.c:1094
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
```
**Symbols:**

```
ffffffff812f6260-ffffffff812f6ce4: traceprobe_parse_probe_arg_body (STB_LOCAL)
ffffffff821b9a68-ffffffff821b9a7d: traceprobe_parse_probe_arg_body.cold (STB_LOCAL)
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
int traceprobe_parse_probe_arg_body(char *arg, ssize_t *size, struct probe_arg *parg, unsigned int flags, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffff800010256b98)
Location: kernel/trace/trace_probe.c:543
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
```
**Symbols:**

```
ffff800010256b98-ffff8000102572ac: traceprobe_parse_probe_arg_body (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int traceprobe_parse_probe_arg_body(char *arg, ssize_t *size, struct probe_arg *parg, unsigned int flags, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (c0489c84)
Location: kernel/trace/trace_probe.c:543
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
```
**Symbols:**

```
c0489c84-c048a438: traceprobe_parse_probe_arg_body (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int traceprobe_parse_probe_arg_body(char *arg, ssize_t *size, struct probe_arg *parg, unsigned int flags, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (c0000000002f7bb0)
Location: kernel/trace/trace_probe.c:543
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
```
**Symbols:**

```
c0000000002f7bb0-c0000000002f8bb4: traceprobe_parse_probe_arg_body (STB_LOCAL)
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
int traceprobe_parse_probe_arg_body(char *arg, ssize_t *size, struct probe_arg *parg, unsigned int flags, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811cee40)
Location: kernel/trace/trace_probe.c:543
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
```
**Symbols:**

```
ffffffff811cee40-ffffffff811cf610: traceprobe_parse_probe_arg_body (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int traceprobe_parse_probe_arg_body(char *arg, ssize_t *size, struct probe_arg *parg, unsigned int flags, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811c1c10)
Location: kernel/trace/trace_probe.c:543
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
```
**Symbols:**

```
ffffffff811c1c10-ffffffff811c23e0: traceprobe_parse_probe_arg_body (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int traceprobe_parse_probe_arg_body(char *arg, ssize_t *size, struct probe_arg *parg, unsigned int flags, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811ccc10)
Location: kernel/trace/trace_probe.c:543
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
```
**Symbols:**

```
ffffffff811ccc10-ffffffff811cd3e0: traceprobe_parse_probe_arg_body (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int traceprobe_parse_probe_arg_body(char *arg, ssize_t *size, struct probe_arg *parg, unsigned int flags, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811dae70)
Location: kernel/trace/trace_probe.c:543
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
```
**Symbols:**

```
ffffffff811dae70-ffffffff811db640: traceprobe_parse_probe_arg_body (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int offset</code>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char *argv</code>
</li>
<li>
<b>Param removed. </b>
<code>char *arg</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct traceprobe_parse_context *ctx</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int offset</code>
</li>
</ul>
</details>
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
