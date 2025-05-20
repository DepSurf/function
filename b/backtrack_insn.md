# Function: <code>backtrack_insn</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int backtrack_insn(struct bpf_verifier_env *env, int idx, u32 *reg_mask, u64 *stack_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811da1b0)
Location: kernel/bpf/verifier.c:1442
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
ffffffff811da1b0-ffffffff811da513: backtrack_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e6fa4)
Location: kernel/bpf/verifier.c:1443
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int backtrack_insn(struct bpf_verifier_env *env, int idx, u32 *reg_mask, u64 *stack_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81206f80)
Location: kernel/bpf/verifier.c:1752
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
ffffffff81206f80-ffffffff812072e0: backtrack_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int backtrack_insn(struct bpf_verifier_env *env, int idx, u32 *reg_mask, u64 *stack_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81206d60)
Location: kernel/bpf/verifier.c:1804
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
ffffffff81206d60-ffffffff812070c0: backtrack_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int backtrack_insn(struct bpf_verifier_env *env, int idx, u32 *reg_mask, u64 *stack_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81208950)
Location: kernel/bpf/verifier.c:2106
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
ffffffff81208950-ffffffff81208cbb: backtrack_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int backtrack_insn(struct bpf_verifier_env *env, int idx, u32 *reg_mask, u64 *stack_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:2174
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
ffffffff8123c390-ffffffff8123c743: backtrack_insn (STB_LOCAL)
ffffffff81cb7f3a-ffffffff81cb7fa9: backtrack_insn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int backtrack_insn(struct bpf_verifier_env *env, int idx, u32 *reg_mask, u64 *stack_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:2524
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
ffffffff8127eb90-ffffffff8127ef10: backtrack_insn (STB_LOCAL)
ffffffff81e69081-ffffffff81e690f0: backtrack_insn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int backtrack_insn(struct bpf_verifier_env *env, int idx, u32 *reg_mask, u64 *stack_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:2780
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
ffffffff812d4160-ffffffff812d4524: backtrack_insn (STB_LOCAL)
ffffffff8205fc56-ffffffff8205fcc5: backtrack_insn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int backtrack_insn(struct bpf_verifier_env *env, int idx, int subseq_idx, struct backtrack_state *bt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:3390
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
ffffffff8130b420-ffffffff8130c403: backtrack_insn (STB_LOCAL)
ffffffff820df83c-ffffffff820df942: backtrack_insn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int backtrack_insn(struct bpf_verifier_env *env, int idx, int subseq_idx, struct bpf_jmp_history_entry *hist, struct backtrack_state *bt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:3544
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
ffffffff813276d0-ffffffff8132877d: backtrack_insn (STB_LOCAL)
ffffffff821bb7f7-ffffffff821bb8f6: backtrack_insn.cold (STB_LOCAL)
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
int backtrack_insn(struct bpf_verifier_env *env, int idx, u32 *reg_mask, u64 *stack_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff80001026a180)
Location: kernel/bpf/verifier.c:1443
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
ffff80001026a180-ffff80001026a564: backtrack_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c049c930)
Location: kernel/bpf/verifier.c:1443
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c00000000031066c)
Location: kernel/bpf/verifier.c:1443
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int backtrack_insn(struct bpf_verifier_env *env, int idx, u32 *reg_mask, u64 *stack_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a49f0)
Location: kernel/bpf/verifier.c:1443
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
ffffffe0001a49f0-ffffffe0001a4d3c: backtrack_insn (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811df5c4)
Location: kernel/bpf/verifier.c:1443
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d2384)
Location: kernel/bpf/verifier.c:1443
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811dd394)
Location: kernel/bpf/verifier.c:1443
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811eb7a4)
Location: kernel/bpf/verifier.c:1443
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
```
</details>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int subseq_idx</code>
</li>
<li>
<b>Param added. </b>
<code>struct backtrack_state *bt</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 *reg_mask</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 *stack_mask</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_jmp_history_entry *hist</code>
</li>
<li>
<b>Param reordered. </b>
<code>env, idx, subseq_idx, bt</code> ➡️ <code>env, idx, subseq_idx, hist, bt</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
