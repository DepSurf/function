# Function: <code>tnum_arshift</code>

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
struct tnum tnum_arshift(struct tnum a, u8 min_shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811c0ca0)
Location: kernel/bpf/tnum.c:46
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffff811c0ca0-ffffffff811c0cba: tnum_arshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct tnum tnum_arshift(struct tnum a, u8 min_shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811d21a0)
Location: kernel/bpf/tnum.c:46
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffff811d21a0-ffffffff811d21ba: tnum_arshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct tnum tnum_arshift(struct tnum a, u8 min_shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811e6900)
Location: kernel/bpf/tnum.c:47
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff811e6900-ffffffff811e6919: tnum_arshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct tnum tnum_arshift(struct tnum a, u8 min_shift, u8 insn_bitness);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811f3050)
Location: kernel/bpf/tnum.c:47
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff811f3050-ffffffff811f307b: tnum_arshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct tnum tnum_arshift(struct tnum a, u8 min_shift, u8 insn_bitness);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff812152c0)
Location: kernel/bpf/tnum.c:47
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff812152c0-ffffffff812152eb: tnum_arshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct tnum tnum_arshift(struct tnum a, u8 min_shift, u8 insn_bitness);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81216f60)
Location: kernel/bpf/tnum.c:47
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff81216f60-ffffffff81216f8b: tnum_arshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct tnum tnum_arshift(struct tnum a, u8 min_shift, u8 insn_bitness);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff8121a3b0)
Location: kernel/bpf/tnum.c:47
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff8121a3b0-ffffffff8121a3db: tnum_arshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct tnum tnum_arshift(struct tnum a, u8 min_shift, u8 insn_bitness);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/tnum.c (0)
Location: kernel/bpf/tnum.c:47
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff81cb90f7-ffffffff81cb9171: tnum_arshift.cold (STB_LOCAL)
ffffffff81251170-ffffffff812511c7: tnum_arshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct tnum tnum_arshift(struct tnum a, u8 min_shift, u8 insn_bitness);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/tnum.c (0)
Location: kernel/bpf/tnum.c:47
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff81e6a3bc-ffffffff81e6a43a: tnum_arshift.cold (STB_LOCAL)
ffffffff81298bb0-ffffffff81298c18: tnum_arshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct tnum tnum_arshift(struct tnum a, u8 min_shift, u8 insn_bitness);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/tnum.c (0)
Location: kernel/bpf/tnum.c:47
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff82061489-ffffffff82061507: tnum_arshift.cold (STB_LOCAL)
ffffffff812f4800-ffffffff812f4868: tnum_arshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct tnum tnum_arshift(struct tnum a, u8 min_shift, u8 insn_bitness);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/tnum.c (0)
Location: kernel/bpf/tnum.c:47
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff820e0a23-ffffffff820e0a94: tnum_arshift.cold (STB_LOCAL)
ffffffff81321c90-ffffffff81321cf8: tnum_arshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct tnum tnum_arshift(struct tnum a, u8 min_shift, u8 insn_bitness);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/tnum.c (0)
Location: kernel/bpf/tnum.c:47
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff821bd135-ffffffff821bd1a6: tnum_arshift.cold (STB_LOCAL)
ffffffff813445a0-ffffffff81344608: tnum_arshift (STB_GLOBAL)
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
struct tnum tnum_arshift(struct tnum a, u8 min_shift, u8 insn_bitness);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffff800010276c90)
Location: kernel/bpf/tnum.c:47
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffff800010276c90-ffff800010276cf0: tnum_arshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct tnum tnum_arshift(struct tnum a, u8 min_shift, u8 insn_bitness);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (c04a9290)
Location: kernel/bpf/tnum.c:47
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
c04a9290-c04a932c: tnum_arshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct tnum tnum_arshift(struct tnum a, u8 min_shift, u8 insn_bitness);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (c00000000031f180)
Location: kernel/bpf/tnum.c:47
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
c00000000031f180-c00000000031f1b4: tnum_arshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct tnum tnum_arshift(struct tnum a, u8 min_shift, u8 insn_bitness);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffe0001aefbc)
Location: kernel/bpf/tnum.c:47
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffe0001aefbc-ffffffe0001af042: tnum_arshift (STB_GLOBAL)
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
struct tnum tnum_arshift(struct tnum a, u8 min_shift, u8 insn_bitness);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811eb670)
Location: kernel/bpf/tnum.c:47
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff811eb670-ffffffff811eb69b: tnum_arshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct tnum tnum_arshift(struct tnum a, u8 min_shift, u8 insn_bitness);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811de400)
Location: kernel/bpf/tnum.c:47
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff811de400-ffffffff811de42b: tnum_arshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct tnum tnum_arshift(struct tnum a, u8 min_shift, u8 insn_bitness);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811e9440)
Location: kernel/bpf/tnum.c:47
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff811e9440-ffffffff811e946b: tnum_arshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct tnum tnum_arshift(struct tnum a, u8 min_shift, u8 insn_bitness);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811f7810)
Location: kernel/bpf/tnum.c:47
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff811f7810-ffffffff811f783b: tnum_arshift (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 insn_bitness</code>
</li>
</ul>
</details>
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
