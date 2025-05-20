# Function: <code>traceprobe_parse_probe_arg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int traceprobe_parse_probe_arg(char *arg, ssize_t *size, struct probe_arg *parg, bool is_return, bool is_kprobe, const struct fetch_type *ftbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff8116ddb0)
Location: kernel/trace/trace_probe.c:504
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
```
**Symbols:**

```
ffffffff8116ddb0-ffffffff8116e041: traceprobe_parse_probe_arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int traceprobe_parse_probe_arg(char *arg, ssize_t *size, struct probe_arg *parg, bool is_return, bool is_kprobe, const struct fetch_type *ftbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff8117b3e0)
Location: kernel/trace/trace_probe.c:531
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
```
**Symbols:**

```
ffffffff8117b3e0-ffffffff8117b69f: traceprobe_parse_probe_arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int traceprobe_parse_probe_arg(char *arg, ssize_t *size, struct probe_arg *parg, bool is_return, bool is_kprobe, const struct fetch_type *ftbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff81186ff0)
Location: kernel/trace/trace_probe.c:535
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
```
**Symbols:**

```
ffffffff81186ff0-ffffffff811872af: traceprobe_parse_probe_arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int traceprobe_parse_probe_arg(char *arg, ssize_t *size, struct probe_arg *parg, bool is_return, bool is_kprobe, const struct fetch_type *ftbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff81189c60)
Location: kernel/trace/trace_probe.c:536
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
```
**Symbols:**

```
ffffffff81189c60-ffffffff81189f05: traceprobe_parse_probe_arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int traceprobe_parse_probe_arg(char *arg, ssize_t *size, struct probe_arg *parg, bool is_return, bool is_kprobe, const struct fetch_type *ftbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811978f0)
Location: kernel/trace/trace_probe.c:534
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
```
**Symbols:**

```
ffffffff811978f0-ffffffff81197b95: traceprobe_parse_probe_arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int traceprobe_parse_probe_arg(char *arg, ssize_t *size, struct probe_arg *parg, bool is_return, bool is_kprobe, const struct fetch_type *ftbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_probe.c (0)
Location: kernel/trace/trace_probe.c:534
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
```
**Symbols:**

```
ffffffff811ad7e9-ffffffff811ad834: traceprobe_parse_probe_arg.cold.9 (STB_LOCAL)
ffffffff811ad0f0-ffffffff811ad351: traceprobe_parse_probe_arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int traceprobe_parse_probe_arg(struct trace_probe *tp, int i, char *arg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_probe.c (0)
Location: kernel/trace/trace_probe.c:538
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
ffffffff811bbf54-ffffffff811bbf6a: traceprobe_parse_probe_arg.cold.7 (STB_LOCAL)
ffffffff811bba70-ffffffff811bbc30: traceprobe_parse_probe_arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int traceprobe_parse_probe_arg(struct trace_probe *tp, int i, char *arg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811cb3c0)
Location: kernel/trace/trace_probe.c:693
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
ffffffff811cb3c0-ffffffff811cb5f8: traceprobe_parse_probe_arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int traceprobe_parse_probe_arg(struct trace_probe *tp, int i, char *arg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811d72d0)
Location: kernel/trace/trace_probe.c:748
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
ffffffff811d72d0-ffffffff811d74f3: traceprobe_parse_probe_arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int traceprobe_parse_probe_arg(struct trace_probe *tp, int i, char *arg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811f3bf0)
Location: kernel/trace/trace_probe.c:748
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
ffffffff811f3bf0-ffffffff811f3e16: traceprobe_parse_probe_arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int traceprobe_parse_probe_arg(struct trace_probe *tp, int i, char *arg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811f25a0)
Location: kernel/trace/trace_probe.c:748
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
ffffffff811f25a0-ffffffff811f27c6: traceprobe_parse_probe_arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int traceprobe_parse_probe_arg(struct trace_probe *tp, int i, char *arg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811f3430)
Location: kernel/trace/trace_probe.c:748
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
```
**Symbols:**

```
ffffffff811f3430-ffffffff811f3655: traceprobe_parse_probe_arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int traceprobe_parse_probe_arg(struct trace_probe *tp, int i, const char *arg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff812246f0)
Location: kernel/trace/trace_probe.c:770
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
```
**Symbols:**

```
ffffffff812246f0-ffffffff8122491e: traceprobe_parse_probe_arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int traceprobe_parse_probe_arg(struct trace_probe *tp, int i, const char *arg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff81264500)
Location: kernel/trace/trace_probe.c:777
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
```
**Symbols:**

```
ffffffff81264500-ffffffff81264704: traceprobe_parse_probe_arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int traceprobe_parse_probe_arg(struct trace_probe *tp, int i, const char *arg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff812b6020)
Location: kernel/trace/trace_probe.c:802
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
```
**Symbols:**

```
ffffffff812b6020-ffffffff812b623e: traceprobe_parse_probe_arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int traceprobe_parse_probe_arg(struct trace_probe *tp, int i, const char *arg, struct traceprobe_parse_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff812d9070)
Location: kernel/trace/trace_probe.c:1139
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_fprobe.c:__trace_fprobe_create
```
**Symbols:**

```
ffffffff812d9070-ffffffff812d9327: traceprobe_parse_probe_arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int traceprobe_parse_probe_arg(struct trace_probe *tp, int i, const char *arg, struct traceprobe_parse_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff812f6fb0)
Location: kernel/trace/trace_probe.c:1376
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_fprobe.c:__trace_fprobe_create
```
**Symbols:**

```
ffffffff812f6fb0-ffffffff812f7267: traceprobe_parse_probe_arg (STB_GLOBAL)
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
int traceprobe_parse_probe_arg(struct trace_probe *tp, int i, char *arg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffff8000102575a8)
Location: kernel/trace/trace_probe.c:748
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
ffff8000102575a8-ffff800010257804: traceprobe_parse_probe_arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int traceprobe_parse_probe_arg(struct trace_probe *tp, int i, char *arg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (c048a768)
Location: kernel/trace/trace_probe.c:748
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
c048a768-c048a9b8: traceprobe_parse_probe_arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int traceprobe_parse_probe_arg(struct trace_probe *tp, int i, char *arg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (c0000000002f8fc0)
Location: kernel/trace/trace_probe.c:748
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
c0000000002f8fc0-c0000000002f9618: traceprobe_parse_probe_arg (STB_GLOBAL)
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
int traceprobe_parse_probe_arg(struct trace_probe *tp, int i, char *arg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811cf8f0)
Location: kernel/trace/trace_probe.c:748
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
ffffffff811cf8f0-ffffffff811cfb13: traceprobe_parse_probe_arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int traceprobe_parse_probe_arg(struct trace_probe *tp, int i, char *arg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811c26c0)
Location: kernel/trace/trace_probe.c:748
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
ffffffff811c26c0-ffffffff811c28e3: traceprobe_parse_probe_arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int traceprobe_parse_probe_arg(struct trace_probe *tp, int i, char *arg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811cd6c0)
Location: kernel/trace/trace_probe.c:748
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
ffffffff811cd6c0-ffffffff811cd8e3: traceprobe_parse_probe_arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int traceprobe_parse_probe_arg(struct trace_probe *tp, int i, char *arg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811db920)
Location: kernel/trace/trace_probe.c:748
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
ffffffff811db920-ffffffff811dbb43: traceprobe_parse_probe_arg (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct trace_probe *tp</code>
</li>
<li>
<b>Param added. </b>
<code>int i</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>ssize_t *size</code>
</li>
<li>
<b>Param removed. </b>
<code>struct probe_arg *parg</code>
</li>
<li>
<b>Param removed. </b>
<code>bool is_return</code>
</li>
<li>
<b>Param removed. </b>
<code>bool is_kprobe</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct fetch_type *ftbl</code>
</li>
<li>
<b>Param reordered. </b>
<code>arg, size, parg, is_return, is_kprobe, ftbl</code> ➡️ <code>tp, i, arg, flags</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char *arg</code> ➡️ <code>const char *arg</code>
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
