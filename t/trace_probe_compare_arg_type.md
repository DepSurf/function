# Function: <code>trace_probe_compare_arg_type</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int trace_probe_compare_arg_type(struct trace_probe *a, struct trace_probe *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811d7bc0)
Location: kernel/trace/trace_probe.c:1099
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
ffffffff811d7bc0-ffffffff811d7c88: trace_probe_compare_arg_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int trace_probe_compare_arg_type(struct trace_probe *a, struct trace_probe *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811f4560)
Location: kernel/trace/trace_probe.c:1099
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
```
**Symbols:**

```
ffffffff811f4560-ffffffff811f4633: trace_probe_compare_arg_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int trace_probe_compare_arg_type(struct trace_probe *a, struct trace_probe *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811f2f10)
Location: kernel/trace/trace_probe.c:1099
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
```
**Symbols:**

```
ffffffff811f2f10-ffffffff811f2fe3: trace_probe_compare_arg_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int trace_probe_compare_arg_type(struct trace_probe *a, struct trace_probe *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811f3d90)
Location: kernel/trace/trace_probe.c:1099
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
```
**Symbols:**

```
ffffffff811f3d90-ffffffff811f3e63: trace_probe_compare_arg_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int trace_probe_compare_arg_type(struct trace_probe *a, struct trace_probe *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff812250e0)
Location: kernel/trace/trace_probe.c:1156
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
```
**Symbols:**

```
ffffffff812250e0-ffffffff812251b3: trace_probe_compare_arg_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int trace_probe_compare_arg_type(struct trace_probe *a, struct trace_probe *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff81264fd0)
Location: kernel/trace/trace_probe.c:1162
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
```
**Symbols:**

```
ffffffff81264fd0-ffffffff81265089: trace_probe_compare_arg_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int trace_probe_compare_arg_type(struct trace_probe *a, struct trace_probe *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff812b6bb0)
Location: kernel/trace/trace_probe.c:1185
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
```
**Symbols:**

```
ffffffff812b6bb0-ffffffff812b6c69: trace_probe_compare_arg_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int trace_probe_compare_arg_type(struct trace_probe *a, struct trace_probe *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff812da0a0)
Location: kernel/trace/trace_probe.c:1666
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
  - kernel/trace/trace_fprobe.c:append_trace_fprobe
```
**Symbols:**

```
ffffffff812da0a0-ffffffff812da159: trace_probe_compare_arg_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int trace_probe_compare_arg_type(struct trace_probe *a, struct trace_probe *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff812f8030)
Location: kernel/trace/trace_probe.c:1903
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
  - kernel/trace/trace_fprobe.c:append_trace_fprobe
```
**Symbols:**

```
ffffffff812f8030-ffffffff812f80e9: trace_probe_compare_arg_type (STB_GLOBAL)
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
int trace_probe_compare_arg_type(struct trace_probe *a, struct trace_probe *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffff800010257f40)
Location: kernel/trace/trace_probe.c:1099
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
ffff800010257f40-ffff80001025802c: trace_probe_compare_arg_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int trace_probe_compare_arg_type(struct trace_probe *a, struct trace_probe *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (c048b05c)
Location: kernel/trace/trace_probe.c:1099
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
c048b05c-c048b11c: trace_probe_compare_arg_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int trace_probe_compare_arg_type(struct trace_probe *a, struct trace_probe *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (c0000000002fa040)
Location: kernel/trace/trace_probe.c:1099
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
c0000000002fa040-c0000000002fa318: trace_probe_compare_arg_type (STB_GLOBAL)
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
int trace_probe_compare_arg_type(struct trace_probe *a, struct trace_probe *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811d01e0)
Location: kernel/trace/trace_probe.c:1099
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
ffffffff811d01e0-ffffffff811d02a8: trace_probe_compare_arg_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int trace_probe_compare_arg_type(struct trace_probe *a, struct trace_probe *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811c2fb0)
Location: kernel/trace/trace_probe.c:1099
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
ffffffff811c2fb0-ffffffff811c3078: trace_probe_compare_arg_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int trace_probe_compare_arg_type(struct trace_probe *a, struct trace_probe *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811cdfb0)
Location: kernel/trace/trace_probe.c:1099
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
ffffffff811cdfb0-ffffffff811ce078: trace_probe_compare_arg_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int trace_probe_compare_arg_type(struct trace_probe *a, struct trace_probe *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811dc210)
Location: kernel/trace/trace_probe.c:1099
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
ffffffff811dc210-ffffffff811dc2d8: trace_probe_compare_arg_type (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
