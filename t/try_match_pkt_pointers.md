# Function: <code>try_match_pkt_pointers</code>

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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811a4ea1)
Location: kernel/bpf/verifier.c:2887
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811bb8d2)
Location: kernel/bpf/verifier.c:3682
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811cb9f3)
Location: kernel/bpf/verifier.c:4387
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d7830)
Location: kernel/bpf/verifier.c:5690
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff811d7830-ffffffff811d7b18: try_match_pkt_pointers.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e3f20)
Location: kernel/bpf/verifier.c:5700
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff811e3f20-ffffffff811e4208: try_match_pkt_pointers.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81204e80)
Location: kernel/bpf/verifier.c:6769
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff81204e80-ffffffff81205168: try_match_pkt_pointers.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool try_match_pkt_pointers(const struct bpf_insn *insn, struct bpf_reg_state *dst_reg, struct bpf_reg_state *src_reg, struct bpf_verifier_state *this_branch, struct bpf_verifier_state *other_branch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81204e50)
Location: kernel/bpf/verifier.c:7426
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff81204e50-ffffffff812052bb: try_match_pkt_pointers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool try_match_pkt_pointers(const struct bpf_insn *insn, struct bpf_reg_state *dst_reg, struct bpf_reg_state *src_reg, struct bpf_verifier_state *this_branch, struct bpf_verifier_state *other_branch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812057e0)
Location: kernel/bpf/verifier.c:8565
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff812057e0-ffffffff81205c4b: try_match_pkt_pointers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool try_match_pkt_pointers(const struct bpf_insn *insn, struct bpf_reg_state *dst_reg, struct bpf_reg_state *src_reg, struct bpf_verifier_state *this_branch, struct bpf_verifier_state *other_branch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81238310)
Location: kernel/bpf/verifier.c:8858
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff81238310-ffffffff81238a46: try_match_pkt_pointers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool try_match_pkt_pointers(const struct bpf_insn *insn, struct bpf_reg_state *dst_reg, struct bpf_reg_state *src_reg, struct bpf_verifier_state *this_branch, struct bpf_verifier_state *other_branch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8127c750)
Location: kernel/bpf/verifier.c:9840
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff8127c750-ffffffff8127ce97: try_match_pkt_pointers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool try_match_pkt_pointers(const struct bpf_insn *insn, struct bpf_reg_state *dst_reg, struct bpf_reg_state *src_reg, struct bpf_verifier_state *this_branch, struct bpf_verifier_state *other_branch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812d2d80)
Location: kernel/bpf/verifier.c:11750
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff812d2d80-ffffffff812d34c7: try_match_pkt_pointers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool try_match_pkt_pointers(const struct bpf_insn *insn, struct bpf_reg_state *dst_reg, struct bpf_reg_state *src_reg, struct bpf_verifier_state *this_branch, struct bpf_verifier_state *other_branch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8130acd0)
Location: kernel/bpf/verifier.c:13683
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff8130acd0-ffffffff8130b404: try_match_pkt_pointers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool try_match_pkt_pointers(const struct bpf_insn *insn, struct bpf_reg_state *dst_reg, struct bpf_reg_state *src_reg, struct bpf_verifier_state *this_branch, struct bpf_verifier_state *other_branch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8132e800)
Location: kernel/bpf/verifier.c:14680
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff8132e800-ffffffff8132ef34: try_match_pkt_pointers (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffff800010266fe0)
Location: kernel/bpf/verifier.c:5700
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffff800010266fe0-ffff800010267328: try_match_pkt_pointers.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool try_match_pkt_pointers(const struct bpf_insn *insn, struct bpf_reg_state *dst_reg, struct bpf_reg_state *src_reg, struct bpf_verifier_state *this_branch, struct bpf_verifier_state *other_branch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c04983f4)
Location: kernel/bpf/verifier.c:5700
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
c04983f4-c04987f4: try_match_pkt_pointers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (c00000000030c590)
Location: kernel/bpf/verifier.c:5700
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
c00000000030c590-c00000000030c968: try_match_pkt_pointers.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a2490)
Location: kernel/bpf/verifier.c:5700
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffe0001a2490-ffffffe0001a2708: try_match_pkt_pointers.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811dc540)
Location: kernel/bpf/verifier.c:5700
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff811dc540-ffffffff811dc828: try_match_pkt_pointers.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811cf300)
Location: kernel/bpf/verifier.c:5700
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff811cf300-ffffffff811cf5e8: try_match_pkt_pointers.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811da310)
Location: kernel/bpf/verifier.c:5700
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff811da310-ffffffff811da5f8: try_match_pkt_pointers.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e8720)
Location: kernel/bpf/verifier.c:5700
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff811e8720-ffffffff811e8a08: try_match_pkt_pointers.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
