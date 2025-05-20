# Function: <code>bpf_prog_realloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_realloc(struct bpf_prog *fp_old, unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81171130)
Location: kernel/bpf/core.c:101
Inline: True
```
**Symbols:**

```
ffffffff81171130-ffffffff811711dc: bpf_prog_realloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_realloc(struct bpf_prog *fp_old, unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8117e910)
Location: kernel/bpf/core.c:102
Inline: True
Direct callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
```
**Symbols:**

```
ffffffff8117e910-ffffffff8117e9c0: bpf_prog_realloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_realloc(struct bpf_prog *fp_old, unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8118a520)
Location: kernel/bpf/core.c:102
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
```
**Symbols:**

```
ffffffff8118a520-ffffffff8118a61a: bpf_prog_realloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_realloc(struct bpf_prog *fp_old, unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8118ec60)
Location: kernel/bpf/core.c:106
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
```
**Symbols:**

```
ffffffff8118ec60-ffffffff8118ed5a: bpf_prog_realloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_realloc(struct bpf_prog *fp_old, unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8119d0d0)
Location: kernel/bpf/core.c:104
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
```
**Symbols:**

```
ffffffff8119d0d0-ffffffff8119d1c9: bpf_prog_realloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_realloc(struct bpf_prog *fp_old, unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811b1800)
Location: kernel/bpf/core.c:106
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
```
**Symbols:**

```
ffffffff811b1800-ffffffff811b1912: bpf_prog_realloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_realloc(struct bpf_prog *fp_old, unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c0040)
Location: kernel/bpf/core.c:194
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
```
**Symbols:**

```
ffffffff811c0040-ffffffff811c0152: bpf_prog_realloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_realloc(struct bpf_prog *fp_old, unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d09e0)
Location: kernel/bpf/core.c:216
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
```
**Symbols:**

```
ffffffff811d09e0-ffffffff811d0aeb: bpf_prog_realloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_realloc(struct bpf_prog *fp_old, unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811dcf70)
Location: kernel/bpf/core.c:216
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
```
**Symbols:**

```
ffffffff811dcf70-ffffffff811dd07b: bpf_prog_realloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_realloc(struct bpf_prog *fp_old, unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f99b0)
Location: kernel/bpf/core.c:217
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
  - net/core/filter.c:bpf_migrate_filter
```
**Symbols:**

```
ffffffff811f99b0-ffffffff811f9a98: bpf_prog_realloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_realloc(struct bpf_prog *fp_old, unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f8a30)
Location: kernel/bpf/core.c:219
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
  - net/core/filter.c:bpf_migrate_filter
```
**Symbols:**

```
ffffffff811f8a30-ffffffff811f8acb: bpf_prog_realloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_realloc(struct bpf_prog *fp_old, unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f9800)
Location: kernel/bpf/core.c:222
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
  - net/core/filter.c:bpf_prepare_filter
```
**Symbols:**

```
ffffffff811f9800-ffffffff811f98be: bpf_prog_realloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_realloc(struct bpf_prog *fp_old, unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8122aeb0)
Location: kernel/bpf/core.c:222
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
  - net/core/filter.c:bpf_prepare_filter
```
**Symbols:**

```
ffffffff8122aeb0-ffffffff8122af6e: bpf_prog_realloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_realloc(struct bpf_prog *fp_old, unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8126c860)
Location: kernel/bpf/core.c:227
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
  - net/core/filter.c:bpf_prepare_filter
```
**Symbols:**

```
ffffffff8126c860-ffffffff8126c926: bpf_prog_realloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_realloc(struct bpf_prog *fp_old, unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812c1950)
Location: kernel/bpf/core.c:235
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
  - net/core/filter.c:bpf_prepare_filter
```
**Symbols:**

```
ffffffff812c1950-ffffffff812c1a16: bpf_prog_realloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_realloc(struct bpf_prog *fp_old, unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812e87a0)
Location: kernel/bpf/core.c:236
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
  - net/core/filter.c:bpf_prepare_filter
```
**Symbols:**

```
ffffffff812e87a0-ffffffff812e889d: bpf_prog_realloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_realloc(struct bpf_prog *fp_old, unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81306b10)
Location: kernel/bpf/core.c:240
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
  - net/core/filter.c:bpf_prepare_filter
```
**Symbols:**

```
ffffffff81306b10-ffffffff81306c0d: bpf_prog_realloc (STB_GLOBAL)
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
struct bpf_prog *bpf_prog_realloc(struct bpf_prog *fp_old, unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffff80001025da10)
Location: kernel/bpf/core.c:216
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
```
**Symbols:**

```
ffff80001025da10-ffff80001025dbb8: bpf_prog_realloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_realloc(struct bpf_prog *fp_old, unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c04911d0)
Location: kernel/bpf/core.c:216
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
```
**Symbols:**

```
c04911d0-c04912ac: bpf_prog_realloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_realloc(struct bpf_prog *fp_old, unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c0000000003024e0)
Location: kernel/bpf/core.c:216
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
```
**Symbols:**

```
c0000000003024e0-c00000000030263c: bpf_prog_realloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_realloc(struct bpf_prog *fp_old, unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffe00019bf94)
Location: kernel/bpf/core.c:216
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
```
**Symbols:**

```
ffffffe00019bf94-ffffffe00019c068: bpf_prog_realloc (STB_GLOBAL)
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
struct bpf_prog *bpf_prog_realloc(struct bpf_prog *fp_old, unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d5590)
Location: kernel/bpf/core.c:216
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
```
**Symbols:**

```
ffffffff811d5590-ffffffff811d569b: bpf_prog_realloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_realloc(struct bpf_prog *fp_old, unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c8350)
Location: kernel/bpf/core.c:216
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
```
**Symbols:**

```
ffffffff811c8350-ffffffff811c845b: bpf_prog_realloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_realloc(struct bpf_prog *fp_old, unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d3360)
Location: kernel/bpf/core.c:216
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
```
**Symbols:**

```
ffffffff811d3360-ffffffff811d346b: bpf_prog_realloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_realloc(struct bpf_prog *fp_old, unsigned int size, gfp_t gfp_extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811e1650)
Location: kernel/bpf/core.c:216
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
```
**Symbols:**

```
ffffffff811e1650-ffffffff811e175b: bpf_prog_realloc (STB_GLOBAL)
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
