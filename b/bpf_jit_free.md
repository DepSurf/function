# Function: <code>bpf_jit_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void bpf_jit_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff8107c640)
Location: arch/x86/net/bpf_jit_comp.c:1118
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
```
**Symbols:**

```
ffffffff8107c640-ffffffff8107c68c: bpf_jit_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void bpf_jit_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff8107dfd0)
Location: arch/x86/net/bpf_jit_comp.c:1186
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
```
**Symbols:**

```
ffffffff8107dfd0-ffffffff8107e01c: bpf_jit_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void bpf_jit_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff81082570)
Location: arch/x86/net/bpf_jit_comp.c:1188
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
```
**Symbols:**

```
ffffffff81082570-ffffffff810825bc: bpf_jit_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void bpf_jit_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8118f530)
Location: kernel/bpf/core.c:532
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
```
**Symbols:**

```
ffffffff8118f530-ffffffff8118f5cc: bpf_jit_free (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void bpf_jit_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8119d9a0)
Location: kernel/bpf/core.c:541
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
```
**Symbols:**

```
ffffffff8119d9a0-ffffffff8119da3c: bpf_jit_free (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void bpf_jit_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811b2140)
Location: kernel/bpf/core.c:620
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff811b2140-ffffffff811b21c6: bpf_jit_free (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bpf_jit_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c0a80)
Location: kernel/bpf/core.c:802
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff811c0a80-ffffffff811c0b06: bpf_jit_free (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bpf_jit_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d15c0)
Location: kernel/bpf/core.c:844
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff811d15c0-ffffffff811d1616: bpf_jit_free (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bpf_jit_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811ddb40)
Location: kernel/bpf/core.c:844
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff811ddb40-ffffffff811ddb96: bpf_jit_free (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bpf_jit_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fa670)
Location: kernel/bpf/core.c:903
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff811fa670-ffffffff811fa70e: bpf_jit_free (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bpf_jit_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f9750)
Location: kernel/bpf/core.c:900
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff811f9750-ffffffff811f97ee: bpf_jit_free (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bpf_jit_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fa5f0)
Location: kernel/bpf/core.c:906
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff811fa5f0-ffffffff811fa695: bpf_jit_free (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bpf_jit_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8122bd00)
Location: kernel/bpf/core.c:908
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff8122bd00-ffffffff8122bda5: bpf_jit_free (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bpf_jit_free(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810c6ea0)
Location: arch/x86/net/bpf_jit_comp.c:2516
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff810c6ea0-ffffffff810c6f3e: bpf_jit_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bpf_jit_free(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810e3ef0)
Location: arch/x86/net/bpf_jit_comp.c:2636
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff810e3ef0-ffffffff810e3f8e: bpf_jit_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_jit_free(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810ef540)
Location: arch/x86/net/bpf_jit_comp.c:2639
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff810ef540-ffffffff810ef5de: bpf_jit_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_jit_free(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810f8820)
Location: arch/x86/net/bpf_jit_comp.c:3148
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff810f8820-ffffffff810f88be: bpf_jit_free (STB_GLOBAL)
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
void bpf_jit_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffff80001025e9a0)
Location: kernel/bpf/core.c:844
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffff80001025e9a0-ffff80001025ea48: bpf_jit_free (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bpf_jit_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c0491fe0)
Location: kernel/bpf/core.c:844
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
c0491fe0-c0492078: bpf_jit_free (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bpf_jit_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/net/bpf_jit_comp64.c (c000000000109100)
Location: arch/powerpc/net/bpf_jit_comp64.c:1248
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
c000000000109100-c000000000109180: bpf_jit_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bpf_jit_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffe00019cc6a)
Location: kernel/bpf/core.c:844
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffe00019cc6a-ffffffe00019cce2: bpf_jit_free (STB_WEAK)
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
void bpf_jit_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d6160)
Location: kernel/bpf/core.c:844
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff811d6160-ffffffff811d61b6: bpf_jit_free (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bpf_jit_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c8f20)
Location: kernel/bpf/core.c:844
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff811c8f20-ffffffff811c8f76: bpf_jit_free (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bpf_jit_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d3f30)
Location: kernel/bpf/core.c:844
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff811d3f30-ffffffff811d3f86: bpf_jit_free (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bpf_jit_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811e2250)
Location: kernel/bpf/core.c:844
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff811e2250-ffffffff811e22a6: bpf_jit_free (STB_WEAK)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_prog *prog</code>
</li>
<li>
<b>Param removed. </b>
<code>struct bpf_prog *fp</code>
</li>
</ul>
</details>
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
