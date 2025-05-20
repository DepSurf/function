# Function: <code>bpf_prog_free_unused_jited_linfo</code>

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
void bpf_prog_free_unused_jited_linfo(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811bff20)
Location: kernel/bpf/core.c:129
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff811bff20-ffffffff811bff5e: bpf_prog_free_unused_jited_linfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bpf_prog_free_unused_jited_linfo(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d08d0)
Location: kernel/bpf/core.c:151
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff811d08d0-ffffffff811d090d: bpf_prog_free_unused_jited_linfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bpf_prog_free_unused_jited_linfo(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811dce60)
Location: kernel/bpf/core.c:151
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff811dce60-ffffffff811dce9d: bpf_prog_free_unused_jited_linfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_free_unused_jited_linfo(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fb1e3)
Location: kernel/bpf/core.c:152
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
Direct callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff811f9880-ffffffff811f98c3: bpf_prog_free_unused_jited_linfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_free_unused_jited_linfo(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fa39f)
Location: kernel/bpf/core.c:154
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
Direct callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff811f8900-ffffffff811f8943: bpf_prog_free_unused_jited_linfo (STB_GLOBAL)
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
void bpf_prog_free_unused_jited_linfo(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffff80001025d8c8)
Location: kernel/bpf/core.c:151
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffff80001025d8c8-ffff80001025d918: bpf_prog_free_unused_jited_linfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bpf_prog_free_unused_jited_linfo(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c04910b4)
Location: kernel/bpf/core.c:151
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
c04910b4-c04910f8: bpf_prog_free_unused_jited_linfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bpf_prog_free_unused_jited_linfo(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c000000000302330)
Location: kernel/bpf/core.c:151
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
c000000000302330-c0000000003023b0: bpf_prog_free_unused_jited_linfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bpf_prog_free_unused_jited_linfo(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffe00019be7c)
Location: kernel/bpf/core.c:151
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffe00019be7c-ffffffe00019bebe: bpf_prog_free_unused_jited_linfo (STB_GLOBAL)
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
void bpf_prog_free_unused_jited_linfo(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d5480)
Location: kernel/bpf/core.c:151
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff811d5480-ffffffff811d54bd: bpf_prog_free_unused_jited_linfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bpf_prog_free_unused_jited_linfo(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c8240)
Location: kernel/bpf/core.c:151
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff811c8240-ffffffff811c827d: bpf_prog_free_unused_jited_linfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bpf_prog_free_unused_jited_linfo(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d3250)
Location: kernel/bpf/core.c:151
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff811d3250-ffffffff811d328d: bpf_prog_free_unused_jited_linfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bpf_prog_free_unused_jited_linfo(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811e1540)
Location: kernel/bpf/core.c:151
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff811e1540-ffffffff811e157d: bpf_prog_free_unused_jited_linfo (STB_GLOBAL)
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
