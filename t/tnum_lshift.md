# Function: <code>tnum_lshift</code>

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
struct tnum tnum_lshift(struct tnum a, u8 shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811a9780)
Location: kernel/bpf/tnum.c:36
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffff811a9780-ffffffff811a979e: tnum_lshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct tnum tnum_lshift(struct tnum a, u8 shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811c0c60)
Location: kernel/bpf/tnum.c:36
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffff811c0c60-ffffffff811c0c7a: tnum_lshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct tnum tnum_lshift(struct tnum a, u8 shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811d2160)
Location: kernel/bpf/tnum.c:36
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffff811d2160-ffffffff811d217a: tnum_lshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct tnum tnum_lshift(struct tnum a, u8 shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811e68c0)
Location: kernel/bpf/tnum.c:37
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff811e68c0-ffffffff811e68d9: tnum_lshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct tnum tnum_lshift(struct tnum a, u8 shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811f3010)
Location: kernel/bpf/tnum.c:37
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff811f3010-ffffffff811f3029: tnum_lshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_lshift(struct tnum a, u8 shift);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81215575)
Location: kernel/bpf/tnum.c:37
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_const_subreg
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff81215280-ffffffff81215299: tnum_lshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_lshift(struct tnum a, u8 shift);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81217215)
Location: kernel/bpf/tnum.c:37
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_const_subreg
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff81216f20-ffffffff81216f39: tnum_lshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_lshift(struct tnum a, u8 shift);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff8121a665)
Location: kernel/bpf/tnum.c:37
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_const_subreg
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff8121a370-ffffffff8121a389: tnum_lshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct tnum tnum_lshift(struct tnum a, u8 shift);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81251465)
Location: kernel/bpf/tnum.c:37
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_const_subreg
  - kernel/bpf/tnum.c:tnum_mul
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff81cb908d-ffffffff81cb90c2: tnum_lshift.cold (STB_LOCAL)
ffffffff812510f0-ffffffff8125112e: tnum_lshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct tnum tnum_lshift(struct tnum a, u8 shift);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81298f65)
Location: kernel/bpf/tnum.c:37
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_const_subreg
  - kernel/bpf/tnum.c:tnum_mul
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff81e6a352-ffffffff81e6a387: tnum_lshift.cold (STB_LOCAL)
ffffffff81298b10-ffffffff81298b58: tnum_lshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct tnum tnum_lshift(struct tnum a, u8 shift);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff812f4c95)
Location: kernel/bpf/tnum.c:37
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_const_subreg
  - kernel/bpf/tnum.c:tnum_mul
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff8206141f-ffffffff82061454: tnum_lshift.cold (STB_LOCAL)
ffffffff812f4740-ffffffff812f4788: tnum_lshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct tnum tnum_lshift(struct tnum a, u8 shift);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81322125)
Location: kernel/bpf/tnum.c:37
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_const_subreg
  - kernel/bpf/tnum.c:tnum_mul
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff820e09b5-ffffffff820e09ec: tnum_lshift.cold (STB_LOCAL)
ffffffff81321bf0-ffffffff81321c2e: tnum_lshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct tnum tnum_lshift(struct tnum a, u8 shift);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81344a35)
Location: kernel/bpf/tnum.c:37
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_with_subreg
  - kernel/bpf/tnum.c:tnum_mul
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff821bd0c7-ffffffff821bd0fe: tnum_lshift.cold (STB_LOCAL)
ffffffff81344500-ffffffff8134453e: tnum_lshift (STB_GLOBAL)
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
struct tnum tnum_lshift(struct tnum a, u8 shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffff800010276c10)
Location: kernel/bpf/tnum.c:37
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffff800010276c10-ffff800010276c4c: tnum_lshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct tnum tnum_lshift(struct tnum a, u8 shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (c04a91b4)
Location: kernel/bpf/tnum.c:37
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
c04a91b4-c04a9224: tnum_lshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct tnum tnum_lshift(struct tnum a, u8 shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (c00000000031f140)
Location: kernel/bpf/tnum.c:37
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
c00000000031f140-c00000000031f154: tnum_lshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct tnum tnum_lshift(struct tnum a, u8 shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffe0001aef4c)
Location: kernel/bpf/tnum.c:37
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffe0001aef4c-ffffffe0001aef84: tnum_lshift (STB_GLOBAL)
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
struct tnum tnum_lshift(struct tnum a, u8 shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811eb630)
Location: kernel/bpf/tnum.c:37
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff811eb630-ffffffff811eb649: tnum_lshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct tnum tnum_lshift(struct tnum a, u8 shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811de3c0)
Location: kernel/bpf/tnum.c:37
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff811de3c0-ffffffff811de3d9: tnum_lshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct tnum tnum_lshift(struct tnum a, u8 shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811e9400)
Location: kernel/bpf/tnum.c:37
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff811e9400-ffffffff811e9419: tnum_lshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct tnum tnum_lshift(struct tnum a, u8 shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811f77d0)
Location: kernel/bpf/tnum.c:37
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff811f77d0-ffffffff811f77e9: tnum_lshift (STB_GLOBAL)
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
