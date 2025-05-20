# Function: <code>bpf_patch_insn_single</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct bpf_prog *bpf_patch_insn_single(struct bpf_prog *prog, u32 off, const struct bpf_insn *patch, u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8117e9f0)
Location: kernel/bpf/core.c:166
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
```
**Symbols:**

```
ffffffff8117e9f0-ffffffff8117eb3c: bpf_patch_insn_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct bpf_prog *bpf_patch_insn_single(struct bpf_prog *prog, u32 off, const struct bpf_insn *patch, u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8118a860)
Location: kernel/bpf/core.c:248
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
**Symbols:**

```
ffffffff8118a860-ffffffff8118a9ac: bpf_patch_insn_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct bpf_prog *bpf_patch_insn_single(struct bpf_prog *prog, u32 off, const struct bpf_insn *patch, u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8118ef90)
Location: kernel/bpf/core.c:251
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
**Symbols:**

```
ffffffff8118ef90-ffffffff8118f0da: bpf_patch_insn_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct bpf_prog *bpf_patch_insn_single(struct bpf_prog *prog, u32 off, const struct bpf_insn *patch, u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8119d400)
Location: kernel/bpf/core.c:247
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
**Symbols:**

```
ffffffff8119d400-ffffffff8119d54a: bpf_patch_insn_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct bpf_prog *bpf_patch_insn_single(struct bpf_prog *prog, u32 off, const struct bpf_insn *patch, u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811b1b60)
Location: kernel/bpf/core.c:295
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
**Symbols:**

```
ffffffff811b1b60-ffffffff811b1c7d: bpf_patch_insn_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct bpf_prog *bpf_patch_insn_single(struct bpf_prog *prog, u32 off, const struct bpf_insn *patch, u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c03a0)
Location: kernel/bpf/core.c:403
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
**Symbols:**

```
ffffffff811c03a0-ffffffff811c0522: bpf_patch_insn_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct bpf_prog *bpf_patch_insn_single(struct bpf_prog *prog, u32 off, const struct bpf_insn *patch, u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d0d50)
Location: kernel/bpf/core.c:432
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
**Symbols:**

```
ffffffff811d0d50-ffffffff811d0efa: bpf_patch_insn_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct bpf_prog *bpf_patch_insn_single(struct bpf_prog *prog, u32 off, const struct bpf_insn *patch, u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811dd2e0)
Location: kernel/bpf/core.c:432
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
**Symbols:**

```
ffffffff811dd2e0-ffffffff811dd48a: bpf_patch_insn_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct bpf_prog *bpf_patch_insn_single(struct bpf_prog *prog, u32 off, const struct bpf_insn *patch, u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f9d00)
Location: kernel/bpf/core.c:432
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
**Symbols:**

```
ffffffff811f9d00-ffffffff811f9eaa: bpf_patch_insn_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct bpf_prog *bpf_patch_insn_single(struct bpf_prog *prog, u32 off, const struct bpf_insn *patch, u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f8d30)
Location: kernel/bpf/core.c:428
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
**Symbols:**

```
ffffffff811f8d30-ffffffff811f8eda: bpf_patch_insn_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct bpf_prog *bpf_patch_insn_single(struct bpf_prog *prog, u32 off, const struct bpf_insn *patch, u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f9b20)
Location: kernel/bpf/core.c:434
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
**Symbols:**

```
ffffffff811f9b20-ffffffff811f9cbd: bpf_patch_insn_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct bpf_prog *bpf_patch_insn_single(struct bpf_prog *prog, u32 off, const struct bpf_insn *patch, u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8122b1f0)
Location: kernel/bpf/core.c:434
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
**Symbols:**

```
ffffffff8122b1f0-ffffffff8122b38d: bpf_patch_insn_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct bpf_prog *bpf_patch_insn_single(struct bpf_prog *prog, u32 off, const struct bpf_insn *patch, u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8126cc10)
Location: kernel/bpf/core.c:446
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
**Symbols:**

```
ffffffff8126cc10-ffffffff8126cdb4: bpf_patch_insn_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct bpf_prog *bpf_patch_insn_single(struct bpf_prog *prog, u32 off, const struct bpf_insn *patch, u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812c1d30)
Location: kernel/bpf/core.c:454
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
**Symbols:**

```
ffffffff812c1d30-ffffffff812c1ee8: bpf_patch_insn_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct bpf_prog *bpf_patch_insn_single(struct bpf_prog *prog, u32 off, const struct bpf_insn *patch, u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812e8bd0)
Location: kernel/bpf/core.c:455
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
**Symbols:**

```
ffffffff812e8bd0-ffffffff812e8da7: bpf_patch_insn_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct bpf_prog *bpf_patch_insn_single(struct bpf_prog *prog, u32 off, const struct bpf_insn *patch, u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81306f40)
Location: kernel/bpf/core.c:472
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
**Symbols:**

```
ffffffff81306f40-ffffffff81307117: bpf_patch_insn_single (STB_GLOBAL)
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
struct bpf_prog *bpf_patch_insn_single(struct bpf_prog *prog, u32 off, const struct bpf_insn *patch, u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffff80001025de30)
Location: kernel/bpf/core.c:432
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
**Symbols:**

```
ffff80001025de30-ffff80001025e000: bpf_patch_insn_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct bpf_prog *bpf_patch_insn_single(struct bpf_prog *prog, u32 off, const struct bpf_insn *patch, u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c0491530)
Location: kernel/bpf/core.c:432
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
**Symbols:**

```
c0491530-c04916c8: bpf_patch_insn_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct bpf_prog *bpf_patch_insn_single(struct bpf_prog *prog, u32 off, const struct bpf_insn *patch, u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c0000000003029b0)
Location: kernel/bpf/core.c:432
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
**Symbols:**

```
c0000000003029b0-c000000000302c08: bpf_patch_insn_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct bpf_prog *bpf_patch_insn_single(struct bpf_prog *prog, u32 off, const struct bpf_insn *patch, u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffe00019c2fa)
Location: kernel/bpf/core.c:432
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
**Symbols:**

```
ffffffe00019c2fa-ffffffe00019c4be: bpf_patch_insn_single (STB_GLOBAL)
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
struct bpf_prog *bpf_patch_insn_single(struct bpf_prog *prog, u32 off, const struct bpf_insn *patch, u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d5900)
Location: kernel/bpf/core.c:432
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
**Symbols:**

```
ffffffff811d5900-ffffffff811d5aaa: bpf_patch_insn_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct bpf_prog *bpf_patch_insn_single(struct bpf_prog *prog, u32 off, const struct bpf_insn *patch, u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c86c0)
Location: kernel/bpf/core.c:432
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
**Symbols:**

```
ffffffff811c86c0-ffffffff811c886a: bpf_patch_insn_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct bpf_prog *bpf_patch_insn_single(struct bpf_prog *prog, u32 off, const struct bpf_insn *patch, u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d36d0)
Location: kernel/bpf/core.c:432
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
**Symbols:**

```
ffffffff811d36d0-ffffffff811d387a: bpf_patch_insn_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct bpf_prog *bpf_patch_insn_single(struct bpf_prog *prog, u32 off, const struct bpf_insn *patch, u32 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811e19c0)
Location: kernel/bpf/core.c:432
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
**Symbols:**

```
ffffffff811e19c0-ffffffff811e1b6a: bpf_patch_insn_single (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
