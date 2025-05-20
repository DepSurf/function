# Function: <code>bpf_jit_binary_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void bpf_jit_binary_free(struct bpf_binary_header *hdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811713a0)
Location: kernel/bpf/core.c:172
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - arch/x86/net/bpf_jit_comp.c:bpf_jit_free
```
**Symbols:**

```
ffffffff811713a0-ffffffff811713b0: bpf_jit_binary_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void bpf_jit_binary_free(struct bpf_binary_header *hdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8117ebe0)
Location: kernel/bpf/core.c:242
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_jit_free
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffffffff8117ebe0-ffffffff8117ebf0: bpf_jit_binary_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void bpf_jit_binary_free(struct bpf_binary_header *hdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8118aa50)
Location: kernel/bpf/core.c:324
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_jit_free
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffffffff8118aa50-ffffffff8118aa60: bpf_jit_binary_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void bpf_jit_binary_free(struct bpf_binary_header *hdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8118f57c)
Location: kernel/bpf/core.c:523
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffffffff8118f520-ffffffff8118f530: bpf_jit_binary_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void bpf_jit_binary_free(struct bpf_binary_header *hdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8119d9ec)
Location: kernel/bpf/core.c:532
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffffffff8119d990-ffffffff8119d9a0: bpf_jit_binary_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void bpf_jit_binary_free(struct bpf_binary_header *hdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811b2188)
Location: kernel/bpf/core.c:611
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffffffff811b2130-ffffffff811b2140: bpf_jit_binary_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bpf_jit_binary_free(struct bpf_binary_header *hdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c0a60)
Location: kernel/bpf/core.c:790
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/bpf/core.c:bpf_jit_free
```
**Symbols:**

```
ffffffff811c0a60-ffffffff811c0a7c: bpf_jit_binary_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bpf_jit_binary_free(struct bpf_binary_header *hdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d15a0)
Location: kernel/bpf/core.c:832
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/bpf/core.c:bpf_jit_free
```
**Symbols:**

```
ffffffff811d15a0-ffffffff811d15bc: bpf_jit_binary_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bpf_jit_binary_free(struct bpf_binary_header *hdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811ddb20)
Location: kernel/bpf/core.c:832
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/bpf/core.c:bpf_jit_free
```
**Symbols:**

```
ffffffff811ddb20-ffffffff811ddb3c: bpf_jit_binary_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_jit_binary_free(struct bpf_binary_header *hdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fa6cd)
Location: kernel/bpf/core.c:891
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffffffff811fa650-ffffffff811fa66f: bpf_jit_binary_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void bpf_jit_binary_free(struct bpf_binary_header *hdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f97ad)
Location: kernel/bpf/core.c:888
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffffffff811f9730-ffffffff811f974f: bpf_jit_binary_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void bpf_jit_binary_free(struct bpf_binary_header *hdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fa650)
Location: kernel/bpf/core.c:894
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffffffff811fa5d0-ffffffff811fa5ef: bpf_jit_binary_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void bpf_jit_binary_free(struct bpf_binary_header *hdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8122bd60)
Location: kernel/bpf/core.c:896
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffffffff8122bce0-ffffffff8122bcff: bpf_jit_binary_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void bpf_jit_binary_free(struct bpf_binary_header *hdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8126d8d9)
Location: kernel/bpf/core.c:1072
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
```
**Symbols:**

```
ffffffff8126d820-ffffffff8126d845: bpf_jit_binary_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void bpf_jit_binary_free(struct bpf_binary_header *hdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812c2cf9)
Location: kernel/bpf/core.c:1046
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
```
**Symbols:**

```
ffffffff812c2c20-ffffffff812c2c45: bpf_jit_binary_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void bpf_jit_binary_free(struct bpf_binary_header *hdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812e9be9)
Location: kernel/bpf/core.c:1047
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
```
**Symbols:**

```
ffffffff812e9b10-ffffffff812e9b35: bpf_jit_binary_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_jit_binary_free(struct bpf_binary_header *hdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81308139)
Location: kernel/bpf/core.c:1090
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
```
**Symbols:**

```
ffffffff81308060-ffffffff81308085: bpf_jit_binary_free (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void bpf_jit_binary_free(struct bpf_binary_header *hdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffff80001025e9dc)
Location: kernel/bpf/core.c:832
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
Direct callers:
  - arch/arm64/net/bpf_jit_comp.c:bpf_int_jit_compile
  - arch/arm64/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffff80001025e930-ffff80001025e99c: bpf_jit_binary_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bpf_jit_binary_free(struct bpf_binary_header *hdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c0491f9c)
Location: kernel/bpf/core.c:832
Inline: False
Direct callers:
  - arch/arm/net/bpf_jit_32.c:bpf_int_jit_compile
  - arch/arm/net/bpf_jit_32.c:bpf_int_jit_compile
  - kernel/bpf/core.c:bpf_jit_free
```
**Symbols:**

```
c0491f9c-c0491fe0: bpf_jit_binary_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void bpf_jit_binary_free(struct bpf_binary_header *hdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c0000000003038b4)
Location: kernel/bpf/core.c:832
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
Direct callers:
  - arch/powerpc/net/bpf_jit_comp64.c:bpf_jit_free
```
**Symbols:**

```
c000000000303800-c00000000030385c: bpf_jit_binary_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void bpf_jit_binary_free(struct bpf_binary_header *hdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffe00019cca6)
Location: kernel/bpf/core.c:832
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
Direct callers:
  - arch/riscv/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffffffe00019cc24-ffffffe00019cc6a: bpf_jit_binary_free (STB_GLOBAL)
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
void bpf_jit_binary_free(struct bpf_binary_header *hdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d6140)
Location: kernel/bpf/core.c:832
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/bpf/core.c:bpf_jit_free
```
**Symbols:**

```
ffffffff811d6140-ffffffff811d615c: bpf_jit_binary_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bpf_jit_binary_free(struct bpf_binary_header *hdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c8f00)
Location: kernel/bpf/core.c:832
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/bpf/core.c:bpf_jit_free
```
**Symbols:**

```
ffffffff811c8f00-ffffffff811c8f1c: bpf_jit_binary_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bpf_jit_binary_free(struct bpf_binary_header *hdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d3f10)
Location: kernel/bpf/core.c:832
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/bpf/core.c:bpf_jit_free
```
**Symbols:**

```
ffffffff811d3f10-ffffffff811d3f2c: bpf_jit_binary_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bpf_jit_binary_free(struct bpf_binary_header *hdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811e2230)
Location: kernel/bpf/core.c:832
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/bpf/core.c:bpf_jit_free
```
**Symbols:**

```
ffffffff811e2230-ffffffff811e224c: bpf_jit_binary_free (STB_GLOBAL)
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
