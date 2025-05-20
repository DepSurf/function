# Function: <code>bpf_int_jit_compile</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void bpf_int_jit_compile(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff8107c3f0)
Location: arch/x86/net/bpf_jit_comp.c:1046
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
```
**Symbols:**

```
ffffffff8107c3f0-ffffffff8107c639: bpf_int_jit_compile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct bpf_prog *bpf_int_jit_compile(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff8107dd20)
Location: arch/x86/net/bpf_jit_comp.c:1092
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
```
**Symbols:**

```
ffffffff8107dd20-ffffffff8107dfc2: bpf_int_jit_compile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct bpf_prog *bpf_int_jit_compile(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810822c0)
Location: arch/x86/net/bpf_jit_comp.c:1092
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
```
**Symbols:**

```
ffffffff810822c0-ffffffff81082566: bpf_int_jit_compile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct bpf_prog *bpf_int_jit_compile(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810803a0)
Location: arch/x86/net/bpf_jit_comp.c:1087
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
```
**Symbols:**

```
ffffffff810803a0-ffffffff81080660: bpf_int_jit_compile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct bpf_prog *bpf_int_jit_compile(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff81086c50)
Location: arch/x86/net/bpf_jit_comp.c:1113
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
```
**Symbols:**

```
ffffffff81086c50-ffffffff81086efd: bpf_int_jit_compile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct bpf_prog *bpf_int_jit_compile(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff811b2c00)
Location: arch/x86/net/bpf_jit_comp.c:1063
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff8108a2b1-ffffffff8108a381: bpf_int_jit_compile.cold.7 (STB_LOCAL)
ffffffff81089f40-ffffffff8108a245: bpf_int_jit_compile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct bpf_prog *bpf_int_jit_compile(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff811c1780)
Location: arch/x86/net/bpf_jit_comp.c:1063
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff810921fb-ffffffff810922ca: bpf_int_jit_compile.cold.6 (STB_LOCAL)
ffffffff81091e80-ffffffff810921a8: bpf_int_jit_compile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct bpf_prog *bpf_int_jit_compile(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff811d1e80)
Location: arch/x86/net/bpf_jit_comp.c:1062
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff8109610a-ffffffff810961d0: bpf_int_jit_compile.cold (STB_LOCAL)
ffffffff81095d80-ffffffff810960b3: bpf_int_jit_compile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct bpf_prog *bpf_int_jit_compile(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff811de420)
Location: arch/x86/net/bpf_jit_comp.c:1062
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff8109c6ca-ffffffff8109c790: bpf_int_jit_compile.cold (STB_LOCAL)
ffffffff8109c340-ffffffff8109c673: bpf_int_jit_compile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct bpf_prog *bpf_int_jit_compile(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff811fb0c0)
Location: arch/x86/net/bpf_jit_comp.c:1811
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff810a32f7-ffffffff810a33bd: bpf_int_jit_compile.cold (STB_LOCAL)
ffffffff810a2de0-ffffffff810a314d: bpf_int_jit_compile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct bpf_prog *bpf_int_jit_compile(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff811fa260)
Location: arch/x86/net/bpf_jit_comp.c:2003
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff81bdb02f-ffffffff81bdb0bc: bpf_int_jit_compile.cold (STB_LOCAL)
ffffffff8109e7d0-ffffffff8109eb47: bpf_int_jit_compile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct bpf_prog *bpf_int_jit_compile(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff811fb220)
Location: arch/x86/net/bpf_jit_comp.c:2217
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff81bcd113-ffffffff81bcd1ae: bpf_int_jit_compile.cold (STB_LOCAL)
ffffffff8109f630-ffffffff8109f9f1: bpf_int_jit_compile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct bpf_prog *bpf_int_jit_compile(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff8122c930)
Location: arch/x86/net/bpf_jit_comp.c:2283
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff81ca386f-ffffffff81ca391f: bpf_int_jit_compile.cold (STB_LOCAL)
ffffffff810b0990-ffffffff810b0e45: bpf_int_jit_compile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct bpf_prog *bpf_int_jit_compile(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff8126e6a0)
Location: arch/x86/net/bpf_jit_comp.c:2319
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff81e52f63-ffffffff81e5303b: bpf_int_jit_compile.cold (STB_LOCAL)
ffffffff810c6860-ffffffff810c6e22: bpf_int_jit_compile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct bpf_prog *bpf_int_jit_compile(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff812c3d80)
Location: arch/x86/net/bpf_jit_comp.c:2439
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff82055a81-ffffffff82055a95: bpf_int_jit_compile.cold (STB_LOCAL)
ffffffff810e3800-ffffffff810e3e31: bpf_int_jit_compile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct bpf_prog *bpf_int_jit_compile(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff812eabd0)
Location: arch/x86/net/bpf_jit_comp.c:2442
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff820d4065-ffffffff820d407a: bpf_int_jit_compile.cold (STB_LOCAL)
ffffffff810eee90-ffffffff810ef481: bpf_int_jit_compile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct bpf_prog *bpf_int_jit_compile(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff813090f0)
Location: arch/x86/net/bpf_jit_comp.c:2944
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff821aef39-ffffffff821aef4e: bpf_int_jit_compile.cold (STB_LOCAL)
ffffffff810f8150-ffffffff810f8770: bpf_int_jit_compile (STB_GLOBAL)
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
struct bpf_prog *bpf_int_jit_compile(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/net/bpf_jit_comp.c (ffff8000100b4a00)
Location: arch/arm64/net/bpf_jit_comp.c:828
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffff8000100b4a00-ffff8000100b4e5c: bpf_int_jit_compile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct bpf_prog *bpf_int_jit_compile(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/net/bpf_jit_32.c (c032c4b8)
Location: arch/arm/net/bpf_jit_32.c:1858
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
c032c4b8-c032c804: bpf_int_jit_compile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct bpf_prog *bpf_int_jit_compile(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/net/bpf_jit_comp64.c (c000000000108a50)
Location: arch/powerpc/net/bpf_jit_comp64.c:1075
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
c000000000108a50-c0000000001090f4: bpf_int_jit_compile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct bpf_prog *bpf_int_jit_compile(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/riscv/net/bpf_jit_comp.c (ffffffe0000be0f0)
Location: arch/riscv/net/bpf_jit_comp.c:1556
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffe0000be0f0-ffffffe0000be322: bpf_int_jit_compile (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct bpf_prog *bpf_int_jit_compile(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff811d6a40)
Location: arch/x86/net/bpf_jit_comp.c:1062
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff81095fea-ffffffff810960b0: bpf_int_jit_compile.cold (STB_LOCAL)
ffffffff81095c60-ffffffff81095f93: bpf_int_jit_compile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct bpf_prog *bpf_int_jit_compile(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff811c9800)
Location: arch/x86/net/bpf_jit_comp.c:1062
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff81084a7a-ffffffff81084b40: bpf_int_jit_compile.cold (STB_LOCAL)
ffffffff810846f0-ffffffff81084a23: bpf_int_jit_compile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct bpf_prog *bpf_int_jit_compile(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff811d4810)
Location: arch/x86/net/bpf_jit_comp.c:1062
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff81095f9a-ffffffff81096060: bpf_int_jit_compile.cold (STB_LOCAL)
ffffffff81095c10-ffffffff81095f43: bpf_int_jit_compile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct bpf_prog *bpf_int_jit_compile(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff811e2b40)
Location: arch/x86/net/bpf_jit_comp.c:1062
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff8109db85-ffffffff8109dc4c: bpf_int_jit_compile.cold (STB_LOCAL)
ffffffff8109d810-ffffffff8109db2e: bpf_int_jit_compile (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>struct bpf_prog *</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_prog *fp</code>
</li>
<li>
<b>Param removed. </b>
<code>struct bpf_prog *prog</code>
</li>
</ul>
</details>
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
