# Function: <code>raw_tp_prog_func_proto</code>

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
const struct bpf_func_proto *raw_tp_prog_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811a5870)
Location: kernel/trace/bpf_trace.c:840
Inline: False
```
**Symbols:**

```
ffffffff811a5870-ffffffff811a58a0: raw_tp_prog_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const struct bpf_func_proto *raw_tp_prog_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b3b80)
Location: kernel/trace/bpf_trace.c:876
Inline: False
```
**Symbols:**

```
ffffffff811b3b80-ffffffff811b3bb0: raw_tp_prog_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const struct bpf_func_proto *raw_tp_prog_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c2990)
Location: kernel/trace/bpf_trace.c:1025
Inline: False
```
**Symbols:**

```
ffffffff811c2990-ffffffff811c29c0: raw_tp_prog_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const struct bpf_func_proto *raw_tp_prog_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811ce100)
Location: kernel/trace/bpf_trace.c:1049
Inline: False
```
**Symbols:**

```
ffffffff811ce100-ffffffff811ce130: raw_tp_prog_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
const struct bpf_func_proto *raw_tp_prog_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811eaaaf)
Location: kernel/trace/bpf_trace.c:1492
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:tracing_prog_func_proto
```
**Symbols:**

```
ffffffff811ea9e0-ffffffff811eaa10: raw_tp_prog_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
const struct bpf_func_proto *raw_tp_prog_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e8c13)
Location: kernel/trace/bpf_trace.c:1721
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:tracing_prog_func_proto
```
**Symbols:**

```
ffffffff811e8ac0-ffffffff811e8af0: raw_tp_prog_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
const struct bpf_func_proto *raw_tp_prog_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e9b00)
Location: kernel/trace/bpf_trace.c:1415
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:tracing_prog_func_proto
```
**Symbols:**

```
ffffffff811e99a0-ffffffff811e99d0: raw_tp_prog_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
const struct bpf_func_proto *raw_tp_prog_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff8121a55d)
Location: kernel/trace/bpf_trace.c:1492
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:tracing_prog_func_proto
```
**Symbols:**

```
ffffffff8121a3e0-ffffffff8121a410: raw_tp_prog_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
const struct bpf_func_proto *raw_tp_prog_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff8125918c)
Location: kernel/trace/bpf_trace.c:1671
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:tracing_prog_func_proto
```
**Symbols:**

```
ffffffff81258de0-ffffffff81258e20: raw_tp_prog_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
const struct bpf_func_proto *raw_tp_prog_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812a918c)
Location: kernel/trace/bpf_trace.c:1888
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:tracing_prog_func_proto
```
**Symbols:**

```
ffffffff812a8dc0-ffffffff812a8e00: raw_tp_prog_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
const struct bpf_func_proto *raw_tp_prog_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812cb70c)
Location: kernel/trace/bpf_trace.c:1897
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:tracing_prog_func_proto
```
**Symbols:**

```
ffffffff812cb5e0-ffffffff812cb620: raw_tp_prog_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
const struct bpf_func_proto *raw_tp_prog_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812e89cc)
Location: kernel/trace/bpf_trace.c:2002
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:tracing_prog_func_proto
```
**Symbols:**

```
ffffffff812e88a0-ffffffff812e88e0: raw_tp_prog_func_proto (STB_LOCAL)
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
const struct bpf_func_proto *raw_tp_prog_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffff80001024d110)
Location: kernel/trace/bpf_trace.c:1049
Inline: False
```
**Symbols:**

```
ffff80001024d110-ffff80001024d16c: raw_tp_prog_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const struct bpf_func_proto *raw_tp_prog_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c0480ffc)
Location: kernel/trace/bpf_trace.c:1049
Inline: False
```
**Symbols:**

```
c0480ffc-c048104c: raw_tp_prog_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const struct bpf_func_proto *raw_tp_prog_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c0000000002ea060)
Location: kernel/trace/bpf_trace.c:1049
Inline: False
```
**Symbols:**

```
c0000000002ea060-c0000000002ea0bc: raw_tp_prog_func_proto (STB_LOCAL)
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
const struct bpf_func_proto *raw_tp_prog_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c6720)
Location: kernel/trace/bpf_trace.c:1049
Inline: False
```
**Symbols:**

```
ffffffff811c6720-ffffffff811c6750: raw_tp_prog_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const struct bpf_func_proto *raw_tp_prog_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b9500)
Location: kernel/trace/bpf_trace.c:1049
Inline: False
```
**Symbols:**

```
ffffffff811b9500-ffffffff811b9530: raw_tp_prog_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const struct bpf_func_proto *raw_tp_prog_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c44f0)
Location: kernel/trace/bpf_trace.c:1049
Inline: False
```
**Symbols:**

```
ffffffff811c44f0-ffffffff811c4520: raw_tp_prog_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const struct bpf_func_proto *raw_tp_prog_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811d1e10)
Location: kernel/trace/bpf_trace.c:1049
Inline: False
```
**Symbols:**

```
ffffffff811d1e10-ffffffff811d1e40: raw_tp_prog_func_proto (STB_LOCAL)
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
