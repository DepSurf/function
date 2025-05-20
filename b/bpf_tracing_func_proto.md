# Function: <code>bpf_tracing_func_proto</code>

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
const struct bpf_func_proto *bpf_tracing_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/bpf_trace.c (0)
Location: kernel/trace/bpf_trace.c:1058
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:tracing_prog_func_proto
  - kernel/trace/bpf_trace.c:pe_prog_func_proto
  - kernel/trace/bpf_trace.c:tp_prog_func_proto
  - kernel/trace/bpf_trace.c:kprobe_prog_func_proto
```
**Symbols:**

```
ffffffff811eb0fb-ffffffff811eb129: bpf_tracing_func_proto.cold (STB_LOCAL)
ffffffff811ea690-ffffffff811ea966: bpf_tracing_func_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
const struct bpf_func_proto *bpf_tracing_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/bpf_trace.c (0)
Location: kernel/trace/bpf_trace.c:1271
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:tracing_prog_func_proto
  - kernel/trace/bpf_trace.c:pe_prog_func_proto
  - kernel/trace/bpf_trace.c:tp_prog_func_proto
  - kernel/trace/bpf_trace.c:kprobe_prog_func_proto
```
**Symbols:**

```
ffffffff81be6399-ffffffff81be63df: bpf_tracing_func_proto.cold (STB_LOCAL)
ffffffff811e8690-ffffffff811e8a50: bpf_tracing_func_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
const struct bpf_func_proto *bpf_tracing_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/bpf_trace.c (0)
Location: kernel/trace/bpf_trace.c:952
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:tracing_prog_func_proto
  - kernel/trace/bpf_trace.c:pe_prog_func_proto
  - kernel/trace/bpf_trace.c:tp_prog_func_proto
  - kernel/trace/bpf_trace.c:kprobe_prog_func_proto
```
**Symbols:**

```
ffffffff81bd8054-ffffffff81bd809a: bpf_tracing_func_proto.cold (STB_LOCAL)
ffffffff811e9470-ffffffff811e9921: bpf_tracing_func_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
const struct bpf_func_proto *bpf_tracing_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/bpf_trace.c (0)
Location: kernel/trace/bpf_trace.c:1021
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:tracing_prog_func_proto
  - kernel/trace/bpf_trace.c:pe_prog_func_proto
  - kernel/trace/bpf_trace.c:tp_prog_func_proto
  - kernel/trace/bpf_trace.c:kprobe_prog_func_proto
```
**Symbols:**

```
ffffffff81219df0-ffffffff8121a322: bpf_tracing_func_proto (STB_LOCAL)
ffffffff81cb71f0-ffffffff81cb724a: bpf_tracing_func_proto.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
const struct bpf_func_proto *bpf_tracing_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/bpf_trace.c (0)
Location: kernel/trace/bpf_trace.c:1185
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:tracing_prog_func_proto
  - kernel/trace/bpf_trace.c:pe_prog_func_proto
  - kernel/trace/bpf_trace.c:tp_prog_func_proto
  - kernel/trace/bpf_trace.c:kprobe_prog_func_proto
```
**Symbols:**

```
ffffffff812586b0-ffffffff81258ca3: bpf_tracing_func_proto (STB_LOCAL)
ffffffff81e6829d-ffffffff81e6830e: bpf_tracing_func_proto.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const struct bpf_func_proto *bpf_tracing_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812a8480)
Location: kernel/trace/bpf_trace.c:1391
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:tracing_prog_func_proto
  - kernel/trace/bpf_trace.c:pe_prog_func_proto
  - kernel/trace/bpf_trace.c:tp_prog_func_proto
  - kernel/trace/bpf_trace.c:kprobe_prog_func_proto
```
**Symbols:**

```
ffffffff812a8480-ffffffff812a8c60: bpf_tracing_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const struct bpf_func_proto *bpf_tracing_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812cad60)
Location: kernel/trace/bpf_trace.c:1404
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:tracing_prog_func_proto
  - kernel/trace/bpf_trace.c:pe_prog_func_proto
  - kernel/trace/bpf_trace.c:tp_prog_func_proto
  - kernel/trace/bpf_trace.c:kprobe_prog_func_proto
```
**Symbols:**

```
ffffffff812cad60-ffffffff812cb493: bpf_tracing_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const struct bpf_func_proto *bpf_tracing_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812e8000)
Location: kernel/trace/bpf_trace.c:1505
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:tracing_prog_func_proto
  - kernel/trace/bpf_trace.c:pe_prog_func_proto
  - kernel/trace/bpf_trace.c:tp_prog_func_proto
  - kernel/trace/bpf_trace.c:kprobe_prog_func_proto
```
**Symbols:**

```
ffffffff812e8000-ffffffff812e8733: bpf_tracing_func_proto (STB_LOCAL)
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
