# Function: <code>print_bpf_insn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8117471e)
Location: kernel/bpf/verifier.c:325
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81182ec2)
Location: kernel/bpf/verifier.c:331
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8118f974)
Location: kernel/bpf/verifier.c:299
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81195e19)
Location: kernel/bpf/verifier.c:307
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void print_bpf_insn(bpf_insn_print_cb verbose, struct bpf_verifier_env *env, const struct bpf_insn *insn, bool allow_ptr_leaks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/disasm.c (ffffffff811aeb00)
Location: kernel/bpf/disasm.c:95
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff811aeb00-ffffffff811aefa5: print_bpf_insn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void print_bpf_insn(const struct bpf_insn_cbs *cbs, const struct bpf_insn *insn, bool allow_ptr_leaks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/disasm.c (ffffffff811c6340)
Location: kernel/bpf/disasm.c:125
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff811c6340-ffffffff811c68d7: print_bpf_insn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void print_bpf_insn(const struct bpf_insn_cbs *cbs, const struct bpf_insn *insn, bool allow_ptr_leaks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/disasm.c (ffffffff811d8e60)
Location: kernel/bpf/disasm.c:125
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff811d8e60-ffffffff811d93f7: print_bpf_insn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void print_bpf_insn(const struct bpf_insn_cbs *cbs, const struct bpf_insn *insn, bool allow_ptr_leaks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/disasm.c (ffffffff811ed9b0)
Location: kernel/bpf/disasm.c:117
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:backtrack_insn
```
**Symbols:**

```
ffffffff811ed9b0-ffffffff811edf43: print_bpf_insn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void print_bpf_insn(const struct bpf_insn_cbs *cbs, const struct bpf_insn *insn, bool allow_ptr_leaks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/disasm.c (ffffffff811fa0c0)
Location: kernel/bpf/disasm.c:117
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
ffffffff811fa0c0-ffffffff811fa653: print_bpf_insn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void print_bpf_insn(const struct bpf_insn_cbs *cbs, const struct bpf_insn *insn, bool allow_ptr_leaks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/disasm.c (ffffffff8121e720)
Location: kernel/bpf/disasm.c:117
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:backtrack_insn
```
**Symbols:**

```
ffffffff8121e720-ffffffff8121ecbf: print_bpf_insn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void print_bpf_insn(const struct bpf_insn_cbs *cbs, const struct bpf_insn *insn, bool allow_ptr_leaks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/disasm.c (ffffffff81221dc0)
Location: kernel/bpf/disasm.c:117
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:backtrack_insn
```
**Symbols:**

```
ffffffff81221dc0-ffffffff8122235f: print_bpf_insn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void print_bpf_insn(const struct bpf_insn_cbs *cbs, const struct bpf_insn *insn, bool allow_ptr_leaks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/disasm.c (ffffffff812265c0)
Location: kernel/bpf/disasm.c:131
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:backtrack_insn
```
**Symbols:**

```
ffffffff812265c0-ffffffff81226ce9: print_bpf_insn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void print_bpf_insn(const struct bpf_insn_cbs *cbs, const struct bpf_insn *insn, bool allow_ptr_leaks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/disasm.c (ffffffff8125e680)
Location: kernel/bpf/disasm.c:131
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:backtrack_insn
```
**Symbols:**

```
ffffffff8125e680-ffffffff8125edec: print_bpf_insn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void print_bpf_insn(const struct bpf_insn_cbs *cbs, const struct bpf_insn *insn, bool allow_ptr_leaks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/disasm.c (ffffffff812a8b90)
Location: kernel/bpf/disasm.c:131
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:backtrack_insn
```
**Symbols:**

```
ffffffff812a8b90-ffffffff812a9355: print_bpf_insn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void print_bpf_insn(const struct bpf_insn_cbs *cbs, const struct bpf_insn *insn, bool allow_ptr_leaks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/disasm.c (ffffffff81307610)
Location: kernel/bpf/disasm.c:131
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:backtrack_insn
```
**Symbols:**

```
ffffffff81307610-ffffffff81307dd5: print_bpf_insn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void print_bpf_insn(const struct bpf_insn_cbs *cbs, const struct bpf_insn *insn, bool allow_ptr_leaks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/disasm.c (ffffffff81336510)
Location: kernel/bpf/disasm.c:131
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:backtrack_insn
```
**Symbols:**

```
ffffffff81336510-ffffffff81336caa: print_bpf_insn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void print_bpf_insn(const struct bpf_insn_cbs *cbs, const struct bpf_insn *insn, bool allow_ptr_leaks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/disasm.c (ffffffff8135ab70)
Location: kernel/bpf/disasm.c:169
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:backtrack_insn
```
**Symbols:**

```
ffffffff8135ab70-ffffffff8135b480: print_bpf_insn (STB_GLOBAL)
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
void print_bpf_insn(const struct bpf_insn_cbs *cbs, const struct bpf_insn *insn, bool allow_ptr_leaks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/disasm.c (ffff80001027fe60)
Location: kernel/bpf/disasm.c:117
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:backtrack_insn
```
**Symbols:**

```
ffff80001027fe60-ffff800010280458: print_bpf_insn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void print_bpf_insn(const struct bpf_insn_cbs *cbs, const struct bpf_insn *insn, bool allow_ptr_leaks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/disasm.c (c04b0e90)
Location: kernel/bpf/disasm.c:117
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
c04b0e90-c04b14cc: print_bpf_insn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void print_bpf_insn(const struct bpf_insn_cbs *cbs, const struct bpf_insn *insn, bool allow_ptr_leaks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/disasm.c (c000000000329fe0)
Location: kernel/bpf/disasm.c:117
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
c000000000329fe0-c00000000032a788: print_bpf_insn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void print_bpf_insn(const struct bpf_insn_cbs *cbs, const struct bpf_insn *insn, bool allow_ptr_leaks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/disasm.c (ffffffe0001b676a)
Location: kernel/bpf/disasm.c:117
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:backtrack_insn
```
**Symbols:**

```
ffffffe0001b676a-ffffffe0001b6c6a: print_bpf_insn (STB_GLOBAL)
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
void print_bpf_insn(const struct bpf_insn_cbs *cbs, const struct bpf_insn *insn, bool allow_ptr_leaks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/disasm.c (ffffffff811f26e0)
Location: kernel/bpf/disasm.c:117
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
ffffffff811f26e0-ffffffff811f2c73: print_bpf_insn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void print_bpf_insn(const struct bpf_insn_cbs *cbs, const struct bpf_insn *insn, bool allow_ptr_leaks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/disasm.c (ffffffff811e5430)
Location: kernel/bpf/disasm.c:117
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
ffffffff811e5430-ffffffff811e59c3: print_bpf_insn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void print_bpf_insn(const struct bpf_insn_cbs *cbs, const struct bpf_insn *insn, bool allow_ptr_leaks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/disasm.c (ffffffff811f04b0)
Location: kernel/bpf/disasm.c:117
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
ffffffff811f04b0-ffffffff811f0a43: print_bpf_insn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void print_bpf_insn(const struct bpf_insn_cbs *cbs, const struct bpf_insn *insn, bool allow_ptr_leaks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/disasm.c (ffffffff811fe9c0)
Location: kernel/bpf/disasm.c:117
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
ffffffff811fe9c0-ffffffff811fef53: print_bpf_insn (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct bpf_insn_cbs *cbs</code>
</li>
<li>
<b>Param removed. </b>
<code>bpf_insn_print_cb verbose</code>
</li>
<li>
<b>Param removed. </b>
<code>struct bpf_verifier_env *env</code>
</li>
<li>
<b>Param reordered. </b>
<code>verbose, env, insn, allow_ptr_leaks</code> ➡️ <code>cbs, insn, allow_ptr_leaks</code>
</li>
</ul>
</details>
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
