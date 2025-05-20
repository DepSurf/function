# Function: <code>bpf_prog_alloc_no_stats</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_alloc_no_stats(unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d06c0)
Location: kernel/bpf/core.c:77
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff811d06c0-ffffffff811d07a4: bpf_prog_alloc_no_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_alloc_no_stats(unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811dcc50)
Location: kernel/bpf/core.c:77
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff811dcc50-ffffffff811dcd34: bpf_prog_alloc_no_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_alloc_no_stats(unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f9670)
Location: kernel/bpf/core.c:78
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff811f9670-ffffffff811f9749: bpf_prog_alloc_no_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_alloc_no_stats(unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f86b0)
Location: kernel/bpf/core.c:78
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff811f86b0-ffffffff811f87cc: bpf_prog_alloc_no_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_alloc_no_stats(unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f94a0)
Location: kernel/bpf/core.c:80
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff811f94a0-ffffffff811f9601: bpf_prog_alloc_no_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_alloc_no_stats(unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8122ab30)
Location: kernel/bpf/core.c:80
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff8122ab30-ffffffff8122ac98: bpf_prog_alloc_no_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_alloc_no_stats(unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8126c460)
Location: kernel/bpf/core.c:84
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff8126c460-ffffffff8126c606: bpf_prog_alloc_no_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_alloc_no_stats(unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812c1490)
Location: kernel/bpf/core.c:89
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff812c1490-ffffffff812c1697: bpf_prog_alloc_no_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_alloc_no_stats(unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812e8260)
Location: kernel/bpf/core.c:90
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff812e8260-ffffffff812e84c8: bpf_prog_alloc_no_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_alloc_no_stats(unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff813065b0)
Location: kernel/bpf/core.c:91
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff813065b0-ffffffff81306834: bpf_prog_alloc_no_stats (STB_GLOBAL)
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
struct bpf_prog *bpf_prog_alloc_no_stats(unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffff80001025d608)
Location: kernel/bpf/core.c:77
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffff80001025d608-ffff80001025d778: bpf_prog_alloc_no_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_alloc_no_stats(unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c0490e88)
Location: kernel/bpf/core.c:77
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
c0490e88-c0490f58: bpf_prog_alloc_no_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_alloc_no_stats(unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c000000000302030)
Location: kernel/bpf/core.c:77
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
c000000000302030-c000000000302144: bpf_prog_alloc_no_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_alloc_no_stats(unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffe00019bc82)
Location: kernel/bpf/core.c:77
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffe00019bc82-ffffffe00019bd4a: bpf_prog_alloc_no_stats (STB_GLOBAL)
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
struct bpf_prog *bpf_prog_alloc_no_stats(unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d5270)
Location: kernel/bpf/core.c:77
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff811d5270-ffffffff811d5354: bpf_prog_alloc_no_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_alloc_no_stats(unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c8030)
Location: kernel/bpf/core.c:77
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff811c8030-ffffffff811c8114: bpf_prog_alloc_no_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_alloc_no_stats(unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d3040)
Location: kernel/bpf/core.c:77
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff811d3040-ffffffff811d3124: bpf_prog_alloc_no_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_alloc_no_stats(unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811e1330)
Location: kernel/bpf/core.c:77
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff811e1330-ffffffff811e1414: bpf_prog_alloc_no_stats (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
