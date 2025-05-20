# Function: <code>reg_set_min_max</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void reg_set_min_max(struct bpf_reg_state *true_reg, struct bpf_reg_state *false_reg, u64 val, u8 opcode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8118de70)
Location: kernel/bpf/verifier.c:1877
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff8118de70-ffffffff8118df60: reg_set_min_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void reg_set_min_max(struct bpf_reg_state *true_reg, struct bpf_reg_state *false_reg, u64 val, u8 opcode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811942c0)
Location: kernel/bpf/verifier.c:2228
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff811942c0-ffffffff811944e9: reg_set_min_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811a5148)
Location: kernel/bpf/verifier.c:2641
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff811a4770-ffffffff811a4a52: reg_set_min_max.part.28 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811bbb33)
Location: kernel/bpf/verifier.c:3432
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff811b7260-ffffffff811b7549: reg_set_min_max.part.29 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811cbd7d)
Location: kernel/bpf/verifier.c:4115
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff811c65e0-ffffffff811c68f9: reg_set_min_max.part.44 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff811dea0e)
Location: kernel/bpf/verifier.c:5323
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff811d8180-ffffffff811d8550: reg_set_min_max.part.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff811eb1ce)
Location: kernel/bpf/verifier.c:5333
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff811e4870-ffffffff811e4c40: reg_set_min_max.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void reg_set_min_max(struct bpf_reg_state *true_reg, struct bpf_reg_state *false_reg, u64 val, u32 val32, u8 opcode, bool is_jmp32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81204300)
Location: kernel/bpf/verifier.c:6444
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff81204300-ffffffff8120489d: reg_set_min_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void reg_set_min_max(struct bpf_reg_state *true_reg, struct bpf_reg_state *false_reg, u64 val, u32 val32, u8 opcode, bool is_jmp32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81204290)
Location: kernel/bpf/verifier.c:7108
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff81204290-ffffffff81204855: reg_set_min_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void reg_set_min_max(struct bpf_reg_state *true_reg, struct bpf_reg_state *false_reg, u64 val, u32 val32, u8 opcode, bool is_jmp32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81205260)
Location: kernel/bpf/verifier.c:8271
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff81205260-ffffffff812057d6: reg_set_min_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void reg_set_min_max(struct bpf_reg_state *true_reg, struct bpf_reg_state *false_reg, u64 val, u32 val32, u8 opcode, bool is_jmp32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81237d90)
Location: kernel/bpf/verifier.c:8564
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff81237d90-ffffffff81238306: reg_set_min_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void reg_set_min_max(struct bpf_reg_state *true_reg, struct bpf_reg_state *false_reg, u64 val, u32 val32, u8 opcode, bool is_jmp32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8127c0b0)
Location: kernel/bpf/verifier.c:9552
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff8127c0b0-ffffffff8127c74a: reg_set_min_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void reg_set_min_max(struct bpf_reg_state *true_reg, struct bpf_reg_state *false_reg, u64 val, u32 val32, u8 opcode, bool is_jmp32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812d26d0)
Location: kernel/bpf/verifier.c:11475
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff812d26d0-ffffffff812d2d6a: reg_set_min_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void reg_set_min_max(struct bpf_reg_state *true_reg, struct bpf_reg_state *false_reg, u64 val, u32 val32, u8 opcode, bool is_jmp32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81307b90)
Location: kernel/bpf/verifier.c:13406
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff81307b90-ffffffff813081f8: reg_set_min_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int reg_set_min_max(struct bpf_verifier_env *env, struct bpf_reg_state *true_reg1, struct bpf_reg_state *true_reg2, struct bpf_reg_state *false_reg1, struct bpf_reg_state *false_reg2, u8 opcode, bool is_jmp32);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81330050)
Location: kernel/bpf/verifier.c:14577
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff81330050-ffffffff8133020d: reg_set_min_max (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffff80001026e804)
Location: kernel/bpf/verifier.c:5333
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffff800010267d10-ffff8000102680a0: reg_set_min_max.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (c04a0f2c)
Location: kernel/bpf/verifier.c:5333
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
c0499d60-c049a1fc: reg_set_min_max.part.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (c000000000315404)
Location: kernel/bpf/verifier.c:5333
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
c00000000030d750-c00000000030dbfc: reg_set_min_max.part.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffe0001a8714)
Location: kernel/bpf/verifier.c:5333
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffe0001a30c6-ffffffe0001a33e8: reg_set_min_max.part.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff811e37ee)
Location: kernel/bpf/verifier.c:5333
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff811dce90-ffffffff811dd260: reg_set_min_max.part.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff811d65ae)
Location: kernel/bpf/verifier.c:5333
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff811cfc50-ffffffff811d0020: reg_set_min_max.part.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff811e15be)
Location: kernel/bpf/verifier.c:5333
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff811dac60-ffffffff811db030: reg_set_min_max.part.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff811ef9ce)
Location: kernel/bpf/verifier.c:5333
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff811e9070-ffffffff811e9440: reg_set_min_max.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_verifier_env *env</code>
</li>
<li>
<b>Param added. </b>
<code>struct bpf_reg_state *true_reg1</code>
</li>
<li>
<b>Param added. </b>
<code>struct bpf_reg_state *true_reg2</code>
</li>
<li>
<b>Param added. </b>
<code>struct bpf_reg_state *false_reg1</code>
</li>
<li>
<b>Param added. </b>
<code>struct bpf_reg_state *false_reg2</code>
</li>
<li>
<b>Param removed. </b>
<code>struct bpf_reg_state *true_reg</code>
</li>
<li>
<b>Param removed. </b>
<code>struct bpf_reg_state *false_reg</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 val</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 val32</code>
</li>
<li>
<b>Param reordered. </b>
<code>true_reg, false_reg, val, val32, opcode, is_jmp32</code> ➡️ <code>env, true_reg1, true_reg2, false_reg1, false_reg2, opcode, is_jmp32</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
</ul>
