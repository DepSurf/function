# Function: <code>traceprobe_set_print_fmt</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
int traceprobe_set_print_fmt(struct trace_probe *tp, bool is_return);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811bbd90)
Location: kernel/trace/trace_probe.c:690
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
ffffffff811bbd90-ffffffff811bbdef: traceprobe_set_print_fmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int traceprobe_set_print_fmt(struct trace_probe *tp, bool is_return);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811cb760)
Location: kernel/trace/trace_probe.c:845
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
ffffffff811cb760-ffffffff811cb7c1: traceprobe_set_print_fmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int traceprobe_set_print_fmt(struct trace_probe *tp, bool is_return);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811d7660)
Location: kernel/trace/trace_probe.c:903
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
ffffffff811d7660-ffffffff811d76c9: traceprobe_set_print_fmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int traceprobe_set_print_fmt(struct trace_probe *tp, bool is_return);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811f3f80)
Location: kernel/trace/trace_probe.c:903
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
ffffffff811f3f80-ffffffff811f3fe9: traceprobe_set_print_fmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int traceprobe_set_print_fmt(struct trace_probe *tp, bool is_return);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811f2930)
Location: kernel/trace/trace_probe.c:903
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
ffffffff811f2930-ffffffff811f2999: traceprobe_set_print_fmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int traceprobe_set_print_fmt(struct trace_probe *tp, bool is_return);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811f37c0)
Location: kernel/trace/trace_probe.c:903
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
```
**Symbols:**

```
ffffffff811f37c0-ffffffff811f3829: traceprobe_set_print_fmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int traceprobe_set_print_fmt(struct trace_probe *tp, enum probe_print_type ptype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff81224a80)
Location: kernel/trace/trace_probe.c:935
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
```
**Symbols:**

```
ffffffff81224a80-ffffffff81224ae7: traceprobe_set_print_fmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int traceprobe_set_print_fmt(struct trace_probe *tp, enum probe_print_type ptype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff81264890)
Location: kernel/trace/trace_probe.c:942
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
```
**Symbols:**

```
ffffffff81264890-ffffffff81264903: traceprobe_set_print_fmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int traceprobe_set_print_fmt(struct trace_probe *tp, enum probe_print_type ptype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff812b63f0)
Location: kernel/trace/trace_probe.c:965
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
```
**Symbols:**

```
ffffffff812b63f0-ffffffff812b6463: traceprobe_set_print_fmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int traceprobe_set_print_fmt(struct trace_probe *tp, enum probe_print_type ptype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff812d98e0)
Location: kernel/trace/trace_probe.c:1446
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_fprobe.c:__trace_fprobe_create
```
**Symbols:**

```
ffffffff812d98e0-ffffffff812d9953: traceprobe_set_print_fmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int traceprobe_set_print_fmt(struct trace_probe *tp, enum probe_print_type ptype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff812f7840)
Location: kernel/trace/trace_probe.c:1683
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_fprobe.c:__trace_fprobe_create
```
**Symbols:**

```
ffffffff812f7840-ffffffff812f78b3: traceprobe_set_print_fmt (STB_GLOBAL)
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
int traceprobe_set_print_fmt(struct trace_probe *tp, bool is_return);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffff8000102579b8)
Location: kernel/trace/trace_probe.c:903
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
ffff8000102579b8-ffff800010257a38: traceprobe_set_print_fmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int traceprobe_set_print_fmt(struct trace_probe *tp, bool is_return);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (c048ab4c)
Location: kernel/trace/trace_probe.c:903
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
c048ab4c-c048abb4: traceprobe_set_print_fmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int traceprobe_set_print_fmt(struct trace_probe *tp, bool is_return);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (c0000000002f9870)
Location: kernel/trace/trace_probe.c:903
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
c0000000002f9870-c0000000002f9910: traceprobe_set_print_fmt (STB_GLOBAL)
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
int traceprobe_set_print_fmt(struct trace_probe *tp, bool is_return);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811cfc80)
Location: kernel/trace/trace_probe.c:903
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
ffffffff811cfc80-ffffffff811cfce9: traceprobe_set_print_fmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int traceprobe_set_print_fmt(struct trace_probe *tp, bool is_return);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811c2a50)
Location: kernel/trace/trace_probe.c:903
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
ffffffff811c2a50-ffffffff811c2ab9: traceprobe_set_print_fmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int traceprobe_set_print_fmt(struct trace_probe *tp, bool is_return);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811cda50)
Location: kernel/trace/trace_probe.c:903
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
ffffffff811cda50-ffffffff811cdab9: traceprobe_set_print_fmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int traceprobe_set_print_fmt(struct trace_probe *tp, bool is_return);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811dbcb0)
Location: kernel/trace/trace_probe.c:903
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
ffffffff811dbcb0-ffffffff811dbd19: traceprobe_set_print_fmt (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<b>Param added. </b>
<code>enum probe_print_type ptype</code>
</li>
<li>
<b>Param removed. </b>
<code>bool is_return</code>
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
