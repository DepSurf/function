# Function: <code>find_good_pkt_pointers</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811836ac)
Location: kernel/bpf/verifier.c:1613
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8118e970)
Location: kernel/bpf/verifier.c:1824
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff8118e970-ffffffff8118ea07: find_good_pkt_pointers.isra.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811944f0)
Location: kernel/bpf/verifier.c:2174
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff811944f0-ffffffff811945ab: find_good_pkt_pointers.isra.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void find_good_pkt_pointers(struct bpf_verifier_state *state, struct bpf_reg_state *dst_reg, enum bpf_reg_type type, bool range_right_open);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811a1340)
Location: kernel/bpf/verifier.c:2550
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff811a1340-ffffffff811a1434: find_good_pkt_pointers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void find_good_pkt_pointers(struct bpf_verifier_state *vstate, struct bpf_reg_state *dst_reg, enum bpf_reg_type type, bool range_right_open);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811b6800)
Location: kernel/bpf/verifier.c:3337
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff811b6800-ffffffff811b68fc: find_good_pkt_pointers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void find_good_pkt_pointers(struct bpf_verifier_state *vstate, struct bpf_reg_state *dst_reg, enum bpf_reg_type type, bool range_right_open);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811c59b0)
Location: kernel/bpf/verifier.c:3942
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff811c59b0-ffffffff811c5aee: find_good_pkt_pointers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void find_good_pkt_pointers(struct bpf_verifier_state *vstate, struct bpf_reg_state *dst_reg, enum bpf_reg_type type, bool range_right_open);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d6860)
Location: kernel/bpf/verifier.c:5101
Inline: False
```
**Symbols:**

```
ffffffff811d6860-ffffffff811d699d: find_good_pkt_pointers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void find_good_pkt_pointers(struct bpf_verifier_state *vstate, struct bpf_reg_state *dst_reg, enum bpf_reg_type type, bool range_right_open);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e2f40)
Location: kernel/bpf/verifier.c:5111
Inline: False
```
**Symbols:**

```
ffffffff811e2f40-ffffffff811e307d: find_good_pkt_pointers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void find_good_pkt_pointers(struct bpf_verifier_state *vstate, struct bpf_reg_state *dst_reg, enum bpf_reg_type type, bool range_right_open);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81202030)
Location: kernel/bpf/verifier.c:6182
Inline: False
```
**Symbols:**

```
ffffffff81202030-ffffffff812020aa: find_good_pkt_pointers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void find_good_pkt_pointers(struct bpf_verifier_state *vstate, struct bpf_reg_state *dst_reg, enum bpf_reg_type type, bool range_right_open);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81201ac0)
Location: kernel/bpf/verifier.c:6786
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
```
**Symbols:**

```
ffffffff81201ac0-ffffffff81201b35: find_good_pkt_pointers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void find_good_pkt_pointers(struct bpf_verifier_state *vstate, struct bpf_reg_state *dst_reg, enum bpf_reg_type type, bool range_right_open);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81202a10)
Location: kernel/bpf/verifier.c:7949
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
```
**Symbols:**

```
ffffffff81202a10-ffffffff81202b36: find_good_pkt_pointers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void find_good_pkt_pointers(struct bpf_verifier_state *vstate, struct bpf_reg_state *dst_reg, enum bpf_reg_type type, bool range_right_open);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81234a40)
Location: kernel/bpf/verifier.c:8242
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
```
**Symbols:**

```
ffffffff81234a40-ffffffff81234bec: find_good_pkt_pointers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void find_good_pkt_pointers(struct bpf_verifier_state *vstate, struct bpf_reg_state *dst_reg, enum bpf_reg_type type, bool range_right_open);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812782e0)
Location: kernel/bpf/verifier.c:9230
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
```
**Symbols:**

```
ffffffff812782e0-ffffffff812784b3: find_good_pkt_pointers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void find_good_pkt_pointers(struct bpf_verifier_state *vstate, struct bpf_reg_state *dst_reg, enum bpf_reg_type type, bool range_right_open);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812ce8e0)
Location: kernel/bpf/verifier.c:11149
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
```
**Symbols:**

```
ffffffff812ce8e0-ffffffff812cea63: find_good_pkt_pointers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void find_good_pkt_pointers(struct bpf_verifier_state *vstate, struct bpf_reg_state *dst_reg, enum bpf_reg_type type, bool range_right_open);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812f5e70)
Location: kernel/bpf/verifier.c:13072
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
```
**Symbols:**

```
ffffffff812f5e70-ffffffff812f5ff3: find_good_pkt_pointers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void find_good_pkt_pointers(struct bpf_verifier_state *vstate, struct bpf_reg_state *dst_reg, enum bpf_reg_type type, bool range_right_open);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:14063
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
```
**Symbols:**

```
ffffffff81315130-ffffffff813152e4: find_good_pkt_pointers (STB_LOCAL)
ffffffff821ba8c3-ffffffff821ba939: find_good_pkt_pointers.cold (STB_LOCAL)
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
void find_good_pkt_pointers(struct bpf_verifier_state *vstate, struct bpf_reg_state *dst_reg, enum bpf_reg_type type, bool range_right_open);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff800010266e48)
Location: kernel/bpf/verifier.c:5111
Inline: False
```
**Symbols:**

```
ffff800010266e48-ffff800010266fdc: find_good_pkt_pointers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void find_good_pkt_pointers(struct bpf_verifier_state *vstate, struct bpf_reg_state *dst_reg, enum bpf_reg_type type, bool range_right_open);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c049827c)
Location: kernel/bpf/verifier.c:5111
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
```
**Symbols:**

```
c049827c-c04983f4: find_good_pkt_pointers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void find_good_pkt_pointers(struct bpf_verifier_state *vstate, struct bpf_reg_state *dst_reg, enum bpf_reg_type type, bool range_right_open);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c00000000030c3a0)
Location: kernel/bpf/verifier.c:5111
Inline: False
```
**Symbols:**

```
c00000000030c3a0-c00000000030c590: find_good_pkt_pointers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void find_good_pkt_pointers(struct bpf_verifier_state *vstate, struct bpf_reg_state *dst_reg, enum bpf_reg_type type, bool range_right_open);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a233e)
Location: kernel/bpf/verifier.c:5111
Inline: False
```
**Symbols:**

```
ffffffe0001a233e-ffffffe0001a2490: find_good_pkt_pointers (STB_LOCAL)
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
void find_good_pkt_pointers(struct bpf_verifier_state *vstate, struct bpf_reg_state *dst_reg, enum bpf_reg_type type, bool range_right_open);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811db560)
Location: kernel/bpf/verifier.c:5111
Inline: False
```
**Symbols:**

```
ffffffff811db560-ffffffff811db69d: find_good_pkt_pointers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void find_good_pkt_pointers(struct bpf_verifier_state *vstate, struct bpf_reg_state *dst_reg, enum bpf_reg_type type, bool range_right_open);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811ce320)
Location: kernel/bpf/verifier.c:5111
Inline: False
```
**Symbols:**

```
ffffffff811ce320-ffffffff811ce45d: find_good_pkt_pointers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void find_good_pkt_pointers(struct bpf_verifier_state *vstate, struct bpf_reg_state *dst_reg, enum bpf_reg_type type, bool range_right_open);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d9330)
Location: kernel/bpf/verifier.c:5111
Inline: False
```
**Symbols:**

```
ffffffff811d9330-ffffffff811d946d: find_good_pkt_pointers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void find_good_pkt_pointers(struct bpf_verifier_state *vstate, struct bpf_reg_state *dst_reg, enum bpf_reg_type type, bool range_right_open);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e7740)
Location: kernel/bpf/verifier.c:5111
Inline: False
```
**Symbols:**

```
ffffffff811e7740-ffffffff811e787d: find_good_pkt_pointers (STB_LOCAL)
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
<code>struct bpf_verifier_state *vstate</code>
</li>
<li>
<b>Param removed. </b>
<code>struct bpf_verifier_state *state</code>
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
