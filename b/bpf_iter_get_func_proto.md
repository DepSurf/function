# Function: <code>bpf_iter_get_func_proto</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const struct bpf_func_proto *bpf_iter_get_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_iter.c (ffffffff81251ee0)
Location: kernel/bpf/bpf_iter.c:364
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:tracing_prog_func_proto
```
**Symbols:**

```
ffffffff81251ee0-ffffffff81251f5d: bpf_iter_get_func_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const struct bpf_func_proto *bpf_iter_get_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_iter.c (ffffffff81299b90)
Location: kernel/bpf/bpf_iter.c:364
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:tracing_prog_func_proto
```
**Symbols:**

```
ffffffff81299b90-ffffffff81299c13: bpf_iter_get_func_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const struct bpf_func_proto *bpf_iter_get_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_iter.c (ffffffff812f5a00)
Location: kernel/bpf/bpf_iter.c:373
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:tracing_prog_func_proto
```
**Symbols:**

```
ffffffff812f5a00-ffffffff812f5a83: bpf_iter_get_func_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const struct bpf_func_proto *bpf_iter_get_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_iter.c (ffffffff813237a0)
Location: kernel/bpf/bpf_iter.c:373
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:tracing_prog_func_proto
```
**Symbols:**

```
ffffffff813237a0-ffffffff81323823: bpf_iter_get_func_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const struct bpf_func_proto *bpf_iter_get_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_iter.c (ffffffff81347700)
Location: kernel/bpf/bpf_iter.c:373
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:tracing_prog_func_proto
```
**Symbols:**

```
ffffffff81347700-ffffffff81347783: bpf_iter_get_func_proto (STB_GLOBAL)
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
