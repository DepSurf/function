# Function: <code>tnum_clear_subreg</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_clear_subreg(struct tnum a);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81215575)
Location: kernel/bpf/tnum.c:203
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_const_subreg
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:__reg_combine_32_into_64
  - kernel/bpf/verifier.c:__reg_bound_offset
```
**Symbols:**

```
ffffffff81215550-ffffffff8121556e: tnum_clear_subreg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_clear_subreg(struct tnum a);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81217215)
Location: kernel/bpf/tnum.c:203
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_const_subreg
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:__reg_combine_32_into_64
  - kernel/bpf/verifier.c:__reg_bound_offset
```
**Symbols:**

```
ffffffff812171f0-ffffffff8121720e: tnum_clear_subreg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_clear_subreg(struct tnum a);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff8121a665)
Location: kernel/bpf/tnum.c:203
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_const_subreg
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:__reg_combine_32_into_64
  - kernel/bpf/verifier.c:__reg_bound_offset
```
**Symbols:**

```
ffffffff8121a640-ffffffff8121a65e: tnum_clear_subreg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_clear_subreg(struct tnum a);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81251465)
Location: kernel/bpf/tnum.c:206
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_const_subreg
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:__reg_combine_32_into_64
  - kernel/bpf/verifier.c:__reg_bound_offset
```
**Symbols:**

```
ffffffff81251440-ffffffff8125145e: tnum_clear_subreg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_clear_subreg(struct tnum a);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81298f65)
Location: kernel/bpf/tnum.c:206
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_const_subreg
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:__reg_combine_32_into_64
  - kernel/bpf/verifier.c:reg_bounds_sync
```
**Symbols:**

```
ffffffff81298f30-ffffffff81298f56: tnum_clear_subreg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_clear_subreg(struct tnum a);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff812f4c95)
Location: kernel/bpf/tnum.c:206
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_const_subreg
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:__reg_combine_32_into_64
  - kernel/bpf/verifier.c:reg_bounds_sync
```
**Symbols:**

```
ffffffff812f4c50-ffffffff812f4c76: tnum_clear_subreg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_clear_subreg(struct tnum a);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81322125)
Location: kernel/bpf/tnum.c:206
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_const_subreg
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:__reg_combine_32_into_64
  - kernel/bpf/verifier.c:reg_bounds_sync
```
**Symbols:**

```
ffffffff813220e0-ffffffff81322106: tnum_clear_subreg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_clear_subreg(struct tnum a);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81344a35)
Location: kernel/bpf/tnum.c:200
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_with_subreg
Direct callers:
  - kernel/bpf/verifier.c:reg_bounds_sync
```
**Symbols:**

```
ffffffff813449f0-ffffffff81344a16: tnum_clear_subreg (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
