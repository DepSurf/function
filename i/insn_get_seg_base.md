# Function: <code>insn_get_seg_base</code>

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
long unsigned int insn_get_seg_base(struct pt_regs *regs, int seg_reg_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81983540)
Location: arch/x86/lib/insn-eval.c:627
Inline: True
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff81983540-ffffffff819835ec: insn_get_seg_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long unsigned int insn_get_seg_base(struct pt_regs *regs, int seg_reg_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff819dfaf0)
Location: arch/x86/lib/insn-eval.c:627
Inline: True
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff819dfaf0-ffffffff819dfb99: insn_get_seg_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long unsigned int insn_get_seg_base(struct pt_regs *regs, int seg_reg_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a1a9b0)
Location: arch/x86/lib/insn-eval.c:627
Inline: True
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff81a1a9b0-ffffffff81a1aa59: insn_get_seg_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long unsigned int insn_get_seg_base(struct pt_regs *regs, int seg_reg_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a8a6c0)
Location: arch/x86/lib/insn-eval.c:633
Inline: True
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff81a8a6c0-ffffffff81a8a794: insn_get_seg_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int insn_get_seg_base(struct pt_regs *regs, int seg_reg_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81ac1980)
Location: arch/x86/lib/insn-eval.c:633
Inline: True
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff81ac1980-ffffffff81ac1a54: insn_get_seg_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int insn_get_seg_base(struct pt_regs *regs, int seg_reg_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff815fdea0)
Location: arch/x86/lib/insn-eval.c:633
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff815fdea0-ffffffff815fdffb: insn_get_seg_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int insn_get_seg_base(struct pt_regs *regs, int seg_reg_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81622d90)
Location: arch/x86/lib/insn-eval.c:663
Inline: False
Direct callers:
  - arch/x86/kernel/sev-es.c:vc_handle_mmio_movs
  - arch/x86/kernel/sev-es.c:vc_handle_mmio_movs
  - arch/x86/kernel/sev-es.c:vc_handle_ioio
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff81622d90-ffffffff81622eeb: insn_get_seg_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int insn_get_seg_base(struct pt_regs *regs, int seg_reg_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81606520)
Location: arch/x86/lib/insn-eval.c:659
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_ioio
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff81606520-ffffffff8160667b: insn_get_seg_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int insn_get_seg_base(struct pt_regs *regs, int seg_reg_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81674f60)
Location: arch/x86/lib/insn-eval.c:659
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_ioio
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff81674f60-ffffffff816750bb: insn_get_seg_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long unsigned int insn_get_seg_base(struct pt_regs *regs, int seg_reg_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff8178f8f0)
Location: arch/x86/lib/insn-eval.c:681
Inline: True
Direct callers:
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_ioio
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff8178f8f0-ffffffff8178fabf: insn_get_seg_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long unsigned int insn_get_seg_base(struct pt_regs *regs, int seg_reg_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff8204d460)
Location: arch/x86/lib/insn-eval.c:681
Inline: True
Direct callers:
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_ioio
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff8204d460-ffffffff8204d62f: insn_get_seg_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long unsigned int insn_get_seg_base(struct pt_regs *regs, int seg_reg_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff820cbd20)
Location: arch/x86/lib/insn-eval.c:681
Inline: True
Direct callers:
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_ioio
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff820cbd20-ffffffff820cbef6: insn_get_seg_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int insn_get_seg_base(struct pt_regs *regs, int seg_reg_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff821a6550)
Location: arch/x86/lib/insn-eval.c:681
Inline: True
Direct callers:
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_ioio
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff821a6550-ffffffff821a6726: insn_get_seg_base (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
long unsigned int insn_get_seg_base(struct pt_regs *regs, int seg_reg_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a607d0)
Location: arch/x86/lib/insn-eval.c:633
Inline: True
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff81a607d0-ffffffff81a608a4: insn_get_seg_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long unsigned int insn_get_seg_base(struct pt_regs *regs, int seg_reg_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a1d890)
Location: arch/x86/lib/insn-eval.c:633
Inline: True
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff81a1d890-ffffffff81a1d998: insn_get_seg_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long unsigned int insn_get_seg_base(struct pt_regs *regs, int seg_reg_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81accbc0)
Location: arch/x86/lib/insn-eval.c:633
Inline: True
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff81accbc0-ffffffff81accc94: insn_get_seg_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long unsigned int insn_get_seg_base(struct pt_regs *regs, int seg_reg_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81ad90d0)
Location: arch/x86/lib/insn-eval.c:633
Inline: True
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
**Symbols:**

```
ffffffff81ad90d0-ffffffff81ad91a4: insn_get_seg_base (STB_GLOBAL)
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
