# Function: <code>parse_probe_arg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int parse_probe_arg(char *arg, const struct fetch_type *t, struct fetch_param *f, bool is_return, bool is_kprobe, const struct fetch_type *ftbl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff8116da00)
Location: kernel/trace/trace_probe.c:358
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
```
**Symbols:**

```
ffffffff8116da00-ffffffff8116ddae: parse_probe_arg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int parse_probe_arg(char *arg, const struct fetch_type *t, struct fetch_param *f, bool is_return, bool is_kprobe, const struct fetch_type *ftbl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff8117afd0)
Location: kernel/trace/trace_probe.c:385
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:parse_probe_arg
```
**Symbols:**

```
ffffffff8117afd0-ffffffff8117b3e0: parse_probe_arg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int parse_probe_arg(char *arg, const struct fetch_type *t, struct fetch_param *f, bool is_return, bool is_kprobe, const struct fetch_type *ftbl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff81186be0)
Location: kernel/trace/trace_probe.c:389
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:parse_probe_arg
```
**Symbols:**

```
ffffffff81186be0-ffffffff81186ff0: parse_probe_arg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int parse_probe_arg(char *arg, const struct fetch_type *t, struct fetch_param *f, bool is_return, bool is_kprobe, const struct fetch_type *ftbl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff81189870)
Location: kernel/trace/trace_probe.c:390
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:parse_probe_arg
```
**Symbols:**

```
ffffffff81189870-ffffffff81189c5c: parse_probe_arg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int parse_probe_arg(char *arg, const struct fetch_type *t, struct fetch_param *f, bool is_return, bool is_kprobe, const struct fetch_type *ftbl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811974f0)
Location: kernel/trace/trace_probe.c:388
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:parse_probe_arg
```
**Symbols:**

```
ffffffff811974f0-ffffffff811978e2: parse_probe_arg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int parse_probe_arg(char *arg, const struct fetch_type *t, struct fetch_param *f, bool is_return, bool is_kprobe, const struct fetch_type *ftbl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_probe.c (0)
Location: kernel/trace/trace_probe.c:388
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:parse_probe_arg
```
**Symbols:**

```
ffffffff811accf0-ffffffff811ad0e9: parse_probe_arg (STB_LOCAL)
ffffffff811ad7cf-ffffffff811ad7e9: parse_probe_arg.cold.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811bb0b0)
Location: kernel/trace/trace_probe.c:234
Inline: True
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
```
**Symbols:**

```
ffffffff811bb0b0-ffffffff811bb4b0: parse_probe_arg.isra.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811ca2a0)
Location: kernel/trace/trace_probe.c:321
Inline: True
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
```
**Symbols:**

```
ffffffff811ca2a0-ffffffff811ca936: parse_probe_arg.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811d6080)
Location: kernel/trace/trace_probe.c:354
Inline: True
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
```
**Symbols:**

```
ffffffff811d6080-ffffffff811d681b: parse_probe_arg.isra.0 (STB_LOCAL)
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
In kernel/trace/trace_probe.c (ffffffff811f2b90)
Location: kernel/trace/trace_probe.c:354
Inline: True
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
```
**Symbols:**

```
ffffffff811f2b90-ffffffff811f311a: parse_probe_arg.isra.0 (STB_LOCAL)
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
In kernel/trace/trace_probe.c (ffffffff811f1540)
Location: kernel/trace/trace_probe.c:354
Inline: True
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
```
**Symbols:**

```
ffffffff811f1540-ffffffff811f1aca: parse_probe_arg.isra.0 (STB_LOCAL)
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
In kernel/trace/trace_probe.c (ffffffff811f23f0)
Location: kernel/trace/trace_probe.c:354
Inline: True
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
```
**Symbols:**

```
ffffffff811f23f0-ffffffff811f297b: parse_probe_arg.isra.0 (STB_LOCAL)
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
In kernel/trace/trace_probe.c (ffffffff81223630)
Location: kernel/trace/trace_probe.c:366
Inline: True
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
```
**Symbols:**

```
ffffffff81223630-ffffffff81223bc8: parse_probe_arg.isra.0 (STB_LOCAL)
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
In kernel/trace/trace_probe.c (ffffffff81263680)
Location: kernel/trace/trace_probe.c:366
Inline: True
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
```
**Symbols:**

```
ffffffff81263680-ffffffff81263b78: parse_probe_arg.isra.0 (STB_LOCAL)
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
In kernel/trace/trace_probe.c (ffffffff812b50b0)
Location: kernel/trace/trace_probe.c:377
Inline: True
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
```
**Symbols:**

```
ffffffff812b50b0-ffffffff812b55ab: parse_probe_arg.isra.0 (STB_LOCAL)
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
In kernel/trace/trace_probe.c (ffffffff812d7e70)
Location: kernel/trace/trace_probe.c:666
Inline: True
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
```
**Symbols:**

```
ffffffff812d7e70-ffffffff812d84ec: parse_probe_arg.isra.0 (STB_LOCAL)
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
In kernel/trace/trace_probe.c (ffffffff812f5cf0)
Location: kernel/trace/trace_probe.c:887
Inline: True
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
```
**Symbols:**

```
ffffffff812f5cf0-ffffffff812f6241: parse_probe_arg.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_probe.c (ffff800010256440)
Location: kernel/trace/trace_probe.c:354
Inline: True
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
```
**Symbols:**

```
ffff800010256440-ffff800010256b98: parse_probe_arg.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int parse_probe_arg(char *arg, const struct fetch_type *type, struct fetch_insn **pcode, struct fetch_insn *end, unsigned int flags, int offs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (c04894f8)
Location: kernel/trace/trace_probe.c:354
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:parse_probe_arg
```
**Symbols:**

```
c04894f8-c0489c84: parse_probe_arg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_probe.c (c0000000002f7040)
Location: kernel/trace/trace_probe.c:354
Inline: True
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
```
**Symbols:**

```
c0000000002f7040-c0000000002f7bac: parse_probe_arg.isra.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811ce6a0)
Location: kernel/trace/trace_probe.c:354
Inline: True
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
```
**Symbols:**

```
ffffffff811ce6a0-ffffffff811cee3b: parse_probe_arg.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811c1470)
Location: kernel/trace/trace_probe.c:354
Inline: True
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
```
**Symbols:**

```
ffffffff811c1470-ffffffff811c1c0b: parse_probe_arg.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811cc470)
Location: kernel/trace/trace_probe.c:354
Inline: True
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
```
**Symbols:**

```
ffffffff811cc470-ffffffff811ccc0b: parse_probe_arg.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811da6d0)
Location: kernel/trace/trace_probe.c:354
Inline: True
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
```
**Symbols:**

```
ffffffff811da6d0-ffffffff811dae6b: parse_probe_arg.isra.0 (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
</ul>
