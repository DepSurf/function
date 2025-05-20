# Function: <code>tnum_and</code>

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
struct tnum tnum_and(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811a9820)
Location: kernel/bpf/tnum.c:70
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffff811a9820-ffffffff811a9847: tnum_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct tnum tnum_and(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811c0d20)
Location: kernel/bpf/tnum.c:80
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffff811c0d20-ffffffff811c0d43: tnum_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct tnum tnum_and(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811d2220)
Location: kernel/bpf/tnum.c:80
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffff811d2220-ffffffff811d2243: tnum_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct tnum tnum_and(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811e6980)
Location: kernel/bpf/tnum.c:81
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff811e6980-ffffffff811e69a3: tnum_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct tnum tnum_and(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811f30e0)
Location: kernel/bpf/tnum.c:86
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff811f30e0-ffffffff811f3103: tnum_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct tnum tnum_and(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81215350)
Location: kernel/bpf/tnum.c:86
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff81215350-ffffffff81215373: tnum_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct tnum tnum_and(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81216ff0)
Location: kernel/bpf/tnum.c:86
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff81216ff0-ffffffff81217013: tnum_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct tnum tnum_and(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff8121a440)
Location: kernel/bpf/tnum.c:86
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff8121a440-ffffffff8121a463: tnum_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct tnum tnum_and(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81251230)
Location: kernel/bpf/tnum.c:86
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff81251230-ffffffff81251253: tnum_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct tnum tnum_and(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81298ca0)
Location: kernel/bpf/tnum.c:86
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff81298ca0-ffffffff81298ccd: tnum_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct tnum tnum_and(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff812f4920)
Location: kernel/bpf/tnum.c:86
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff812f4920-ffffffff812f494d: tnum_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct tnum tnum_and(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81321db0)
Location: kernel/bpf/tnum.c:86
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff81321db0-ffffffff81321ddd: tnum_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct tnum tnum_and(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff813446c0)
Location: kernel/bpf/tnum.c:86
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:regs_refine_cond_op
  - kernel/bpf/verifier.c:regs_refine_cond_op
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff813446c0-ffffffff813446ed: tnum_and (STB_GLOBAL)
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
struct tnum tnum_and(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffff800010276da0)
Location: kernel/bpf/tnum.c:86
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffff800010276da0-ffff800010276dec: tnum_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct tnum tnum_and(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (c04a9444)
Location: kernel/bpf/tnum.c:86
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
c04a9444-c04a94c0: tnum_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct tnum tnum_and(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (c00000000031f220)
Location: kernel/bpf/tnum.c:86
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
c00000000031f220-c00000000031f244: tnum_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct tnum tnum_and(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffe0001af0e0)
Location: kernel/bpf/tnum.c:86
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffe0001af0e0-ffffffe0001af12a: tnum_and (STB_GLOBAL)
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
struct tnum tnum_and(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811eb700)
Location: kernel/bpf/tnum.c:86
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff811eb700-ffffffff811eb723: tnum_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct tnum tnum_and(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811de490)
Location: kernel/bpf/tnum.c:86
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff811de490-ffffffff811de4b3: tnum_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct tnum tnum_and(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811e94d0)
Location: kernel/bpf/tnum.c:86
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff811e94d0-ffffffff811e94f3: tnum_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct tnum tnum_and(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811f78a0)
Location: kernel/bpf/tnum.c:86
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff811f78a0-ffffffff811f78c3: tnum_and (STB_GLOBAL)
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
