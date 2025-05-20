# Function: <code>tnum_rshift</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct tnum tnum_rshift(struct tnum a, u8 shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811a97a0)
Location: kernel/bpf/tnum.c:41
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffff811a97a0-ffffffff811a97be: tnum_rshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct tnum tnum_rshift(struct tnum a, u8 shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811c0c80)
Location: kernel/bpf/tnum.c:41
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffff811c0c80-ffffffff811c0c9a: tnum_rshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct tnum tnum_rshift(struct tnum a, u8 shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811d2180)
Location: kernel/bpf/tnum.c:41
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffff811d2180-ffffffff811d219a: tnum_rshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct tnum tnum_rshift(struct tnum a, u8 shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811e68e0)
Location: kernel/bpf/tnum.c:42
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff811e68e0-ffffffff811e68f9: tnum_rshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct tnum tnum_rshift(struct tnum a, u8 shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811f3030)
Location: kernel/bpf/tnum.c:42
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff811f3030-ffffffff811f3049: tnum_rshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_rshift(struct tnum a, u8 shift);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81215575)
Location: kernel/bpf/tnum.c:42
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_const_subreg
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff812152a0-ffffffff812152b9: tnum_rshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_rshift(struct tnum a, u8 shift);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81217215)
Location: kernel/bpf/tnum.c:42
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_const_subreg
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff81216f40-ffffffff81216f59: tnum_rshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_rshift(struct tnum a, u8 shift);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff8121a665)
Location: kernel/bpf/tnum.c:42
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_const_subreg
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff8121a390-ffffffff8121a3a9: tnum_rshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct tnum tnum_rshift(struct tnum a, u8 shift);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff812512cf)
Location: kernel/bpf/tnum.c:42
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_mul
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff81cb90c2-ffffffff81cb90f7: tnum_rshift.cold (STB_LOCAL)
ffffffff81251130-ffffffff8125116e: tnum_rshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct tnum tnum_rshift(struct tnum a, u8 shift);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81298d61)
Location: kernel/bpf/tnum.c:42
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_mul
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff81e6a387-ffffffff81e6a3bc: tnum_rshift.cold (STB_LOCAL)
ffffffff81298b60-ffffffff81298ba8: tnum_rshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct tnum tnum_rshift(struct tnum a, u8 shift);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff812f4a11)
Location: kernel/bpf/tnum.c:42
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_mul
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff82061454-ffffffff82061489: tnum_rshift.cold (STB_LOCAL)
ffffffff812f47a0-ffffffff812f47e8: tnum_rshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct tnum tnum_rshift(struct tnum a, u8 shift);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81321ea1)
Location: kernel/bpf/tnum.c:42
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_mul
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff820e09ec-ffffffff820e0a23: tnum_rshift.cold (STB_LOCAL)
ffffffff81321c40-ffffffff81321c7e: tnum_rshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct tnum tnum_rshift(struct tnum a, u8 shift);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff813447b1)
Location: kernel/bpf/tnum.c:42
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_mul
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff821bd0fe-ffffffff821bd135: tnum_rshift.cold (STB_LOCAL)
ffffffff81344550-ffffffff8134458e: tnum_rshift (STB_GLOBAL)
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
struct tnum tnum_rshift(struct tnum a, u8 shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffff800010276c50)
Location: kernel/bpf/tnum.c:42
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffff800010276c50-ffff800010276c8c: tnum_rshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct tnum tnum_rshift(struct tnum a, u8 shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (c04a9224)
Location: kernel/bpf/tnum.c:42
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
c04a9224-c04a9290: tnum_rshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct tnum tnum_rshift(struct tnum a, u8 shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (c00000000031f160)
Location: kernel/bpf/tnum.c:42
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
c00000000031f160-c00000000031f174: tnum_rshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct tnum tnum_rshift(struct tnum a, u8 shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffe0001aef84)
Location: kernel/bpf/tnum.c:42
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffe0001aef84-ffffffe0001aefbc: tnum_rshift (STB_GLOBAL)
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
struct tnum tnum_rshift(struct tnum a, u8 shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811eb650)
Location: kernel/bpf/tnum.c:42
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff811eb650-ffffffff811eb669: tnum_rshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct tnum tnum_rshift(struct tnum a, u8 shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811de3e0)
Location: kernel/bpf/tnum.c:42
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff811de3e0-ffffffff811de3f9: tnum_rshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct tnum tnum_rshift(struct tnum a, u8 shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811e9420)
Location: kernel/bpf/tnum.c:42
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff811e9420-ffffffff811e9439: tnum_rshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct tnum tnum_rshift(struct tnum a, u8 shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811f77f0)
Location: kernel/bpf/tnum.c:42
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff811f77f0-ffffffff811f7809: tnum_rshift (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
