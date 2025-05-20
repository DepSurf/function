# Function: <code>bpf_prog_free_jited_linfo</code>

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
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_free_jited_linfo(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c1886)
Location: kernel/bpf/core.c:123
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/core.c:bpf_prog_free_linfo
  - kernel/bpf/core.c:bpf_prog_free_unused_jited_linfo
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff811bfef0-ffffffff811bff1f: bpf_prog_free_jited_linfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_free_jited_linfo(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d1fac)
Location: kernel/bpf/core.c:145
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/core.c:bpf_prog_free_linfo
  - kernel/bpf/core.c:bpf_prog_free_unused_jited_linfo
Direct callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff811d08a0-ffffffff811d08cf: bpf_prog_free_jited_linfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_free_jited_linfo(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811de54c)
Location: kernel/bpf/core.c:145
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/core.c:bpf_prog_free_linfo
  - kernel/bpf/core.c:bpf_prog_free_unused_jited_linfo
Direct callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff811dce30-ffffffff811dce5f: bpf_prog_free_jited_linfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_free_jited_linfo(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fb201)
Location: kernel/bpf/core.c:146
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/core.c:bpf_prog_free_linfo
Direct callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff811f9840-ffffffff811f9872: bpf_prog_free_jited_linfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_free_jited_linfo(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fa3bd)
Location: kernel/bpf/core.c:148
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/core.c:bpf_prog_free_linfo
Direct callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff811f88c0-ffffffff811f88f2: bpf_prog_free_jited_linfo (STB_GLOBAL)
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_free_jited_linfo(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffff80001025f808)
Location: kernel/bpf/core.c:145
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/core.c:bpf_prog_free_linfo
  - kernel/bpf/core.c:bpf_prog_free_unused_jited_linfo
Direct callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffff80001025d890-ffff80001025d8c8: bpf_prog_free_jited_linfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_free_jited_linfo(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c0492bf4)
Location: kernel/bpf/core.c:145
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/core.c:bpf_prog_free_linfo
  - kernel/bpf/core.c:bpf_prog_free_unused_jited_linfo
Direct callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
c0491080-c04910b4: bpf_prog_free_jited_linfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_free_jited_linfo(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c0000000003048a0)
Location: kernel/bpf/core.c:145
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/core.c:bpf_prog_free_linfo
  - kernel/bpf/core.c:bpf_prog_free_unused_jited_linfo
Direct callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
c0000000003022d0-c000000000302324: bpf_prog_free_jited_linfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_free_jited_linfo(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffe00019d678)
Location: kernel/bpf/core.c:145
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/core.c:bpf_prog_free_linfo
  - kernel/bpf/core.c:bpf_prog_free_unused_jited_linfo
Direct callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffe00019be4a-ffffffe00019be7c: bpf_prog_free_jited_linfo (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_free_jited_linfo(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d6b6c)
Location: kernel/bpf/core.c:145
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/core.c:bpf_prog_free_linfo
  - kernel/bpf/core.c:bpf_prog_free_unused_jited_linfo
Direct callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff811d5450-ffffffff811d547f: bpf_prog_free_jited_linfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_free_jited_linfo(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c992c)
Location: kernel/bpf/core.c:145
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/core.c:bpf_prog_free_linfo
  - kernel/bpf/core.c:bpf_prog_free_unused_jited_linfo
Direct callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff811c8210-ffffffff811c823f: bpf_prog_free_jited_linfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_free_jited_linfo(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d493c)
Location: kernel/bpf/core.c:145
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/core.c:bpf_prog_free_linfo
  - kernel/bpf/core.c:bpf_prog_free_unused_jited_linfo
Direct callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff811d3220-ffffffff811d324f: bpf_prog_free_jited_linfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_free_jited_linfo(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811e2c6c)
Location: kernel/bpf/core.c:145
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/core.c:bpf_prog_free_linfo
  - kernel/bpf/core.c:bpf_prog_free_unused_jited_linfo
Direct callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff811e1510-ffffffff811e153f: bpf_prog_free_jited_linfo (STB_GLOBAL)
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
