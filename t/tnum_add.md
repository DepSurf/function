# Function: <code>tnum_add</code>

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
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_add(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811a98d5)
Location: kernel/bpf/tnum.c:46
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_mul
  - kernel/bpf/tnum.c:tnum_mul
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
```
**Symbols:**

```
ffffffff811a97c0-ffffffff811a97ec: tnum_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_add(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811c0db3)
Location: kernel/bpf/tnum.c:56
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_mul
  - kernel/bpf/tnum.c:tnum_mul
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811c0cc0-ffffffff811c0ce8: tnum_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_add(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811d22b3)
Location: kernel/bpf/tnum.c:56
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_mul
  - kernel/bpf/tnum.c:tnum_mul
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811d21c0-ffffffff811d21e8: tnum_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_add(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811e6a11)
Location: kernel/bpf/tnum.c:57
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_mul
  - kernel/bpf/tnum.c:tnum_mul
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
```
**Symbols:**

```
ffffffff811e6920-ffffffff811e6948: tnum_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_add(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811f3171)
Location: kernel/bpf/tnum.c:62
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_mul
  - kernel/bpf/tnum.c:tnum_mul
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
```
**Symbols:**

```
ffffffff811f3080-ffffffff811f30a8: tnum_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_add(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff812153ea)
Location: kernel/bpf/tnum.c:62
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_mul
  - kernel/bpf/tnum.c:tnum_mul
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
```
**Symbols:**

```
ffffffff812152f0-ffffffff81215318: tnum_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_add(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff8121708a)
Location: kernel/bpf/tnum.c:62
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_mul
  - kernel/bpf/tnum.c:tnum_mul
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
```
**Symbols:**

```
ffffffff81216f90-ffffffff81216fb8: tnum_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_add(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff8121a4d7)
Location: kernel/bpf/tnum.c:62
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_mul
  - kernel/bpf/tnum.c:tnum_mul
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
```
**Symbols:**

```
ffffffff8121a3e0-ffffffff8121a407: tnum_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_add(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff812512c5)
Location: kernel/bpf/tnum.c:62
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_mul
  - kernel/bpf/tnum.c:tnum_mul
  - kernel/bpf/tnum.c:tnum_mul
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
```
**Symbols:**

```
ffffffff812511d0-ffffffff812511f7: tnum_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_add(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81298d55)
Location: kernel/bpf/tnum.c:62
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_mul
  - kernel/bpf/tnum.c:tnum_mul
  - kernel/bpf/tnum.c:tnum_mul
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
```
**Symbols:**

```
ffffffff81298c20-ffffffff81298c51: tnum_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_add(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff812f4a05)
Location: kernel/bpf/tnum.c:62
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_mul
  - kernel/bpf/tnum.c:tnum_mul
  - kernel/bpf/tnum.c:tnum_mul
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
```
**Symbols:**

```
ffffffff812f4880-ffffffff812f48b1: tnum_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_add(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81321e95)
Location: kernel/bpf/tnum.c:62
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_mul
  - kernel/bpf/tnum.c:tnum_mul
  - kernel/bpf/tnum.c:tnum_mul
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
```
**Symbols:**

```
ffffffff81321d10-ffffffff81321d41: tnum_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_add(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff813447a5)
Location: kernel/bpf/tnum.c:62
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_mul
  - kernel/bpf/tnum.c:tnum_mul
  - kernel/bpf/tnum.c:tnum_mul
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
```
**Symbols:**

```
ffffffff81344620-ffffffff81344651: tnum_add (STB_GLOBAL)
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
struct tnum tnum_add(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffff800010276ec8)
Location: kernel/bpf/tnum.c:62
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_mul
  - kernel/bpf/tnum.c:tnum_mul
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
```
**Symbols:**

```
ffff800010276cf0-ffff800010276d44: tnum_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_add(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (c04a9608)
Location: kernel/bpf/tnum.c:62
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_mul
  - kernel/bpf/tnum.c:tnum_mul
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
```
**Symbols:**

```
c04a932c-c04a93b4: tnum_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_add(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (c00000000031f2b4)
Location: kernel/bpf/tnum.c:62
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_mul
  - kernel/bpf/tnum.c:tnum_mul
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
```
**Symbols:**

```
c00000000031f1c0-c00000000031f1ec: tnum_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_add(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffe0001af1f0)
Location: kernel/bpf/tnum.c:62
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_mul
  - kernel/bpf/tnum.c:tnum_mul
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
```
**Symbols:**

```
ffffffe0001af042-ffffffe0001af090: tnum_add (STB_GLOBAL)
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
struct tnum tnum_add(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811eb791)
Location: kernel/bpf/tnum.c:62
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_mul
  - kernel/bpf/tnum.c:tnum_mul
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
```
**Symbols:**

```
ffffffff811eb6a0-ffffffff811eb6c8: tnum_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_add(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811de521)
Location: kernel/bpf/tnum.c:62
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_mul
  - kernel/bpf/tnum.c:tnum_mul
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
```
**Symbols:**

```
ffffffff811de430-ffffffff811de458: tnum_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_add(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811e9561)
Location: kernel/bpf/tnum.c:62
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_mul
  - kernel/bpf/tnum.c:tnum_mul
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
```
**Symbols:**

```
ffffffff811e9470-ffffffff811e9498: tnum_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_add(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811f7931)
Location: kernel/bpf/tnum.c:62
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_mul
  - kernel/bpf/tnum.c:tnum_mul
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
```
**Symbols:**

```
ffffffff811f7840-ffffffff811f7868: tnum_add (STB_GLOBAL)
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
