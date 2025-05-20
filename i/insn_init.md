# Function: <code>insn_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void insn_init(struct insn *insn, const void *kaddr, int buf_len, int x86_64);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff813f71a0)
Location: arch/x86/lib/insn.c:53
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/lbr.c:branch_type
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/core.c:__copy_instruction
  - arch/x86/kernel/kprobes/core.c:__copy_instruction
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
```
**Symbols:**

```
ffffffff813f71a0-ffffffff813f720c: insn_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void insn_init(struct insn *insn, const void *kaddr, int buf_len, int x86_64);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff8143ddf0)
Location: arch/x86/lib/insn.c:53
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/lbr.c:branch_type
  - arch/x86/kernel/kprobes/core.c:__copy_instruction
  - arch/x86/kernel/kprobes/core.c:__copy_instruction
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
```
**Symbols:**

```
ffffffff8143ddf0-ffffffff8143de5c: insn_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void insn_init(struct insn *insn, const void *kaddr, int buf_len, int x86_64);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff8145ad70)
Location: arch/x86/lib/insn.c:53
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/lbr.c:branch_type
  - arch/x86/kernel/kprobes/core.c:__copy_instruction
  - arch/x86/kernel/kprobes/core.c:__copy_instruction
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
```
**Symbols:**

```
ffffffff8145ad70-ffffffff8145addc: insn_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void insn_init(struct insn *insn, const void *kaddr, int buf_len, int x86_64);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff818fcb00)
Location: arch/x86/lib/insn.c:53
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/lbr.c:branch_type
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
```
**Symbols:**

```
ffffffff818fcb00-ffffffff818fcb74: insn_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void insn_init(struct insn *insn, const void *kaddr, int buf_len, int x86_64);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff819845b0)
Location: arch/x86/lib/insn.c:53
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/lbr.c:branch_type
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
```
**Symbols:**

```
ffffffff819845b0-ffffffff81984624: insn_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void insn_init(struct insn *insn, const void *kaddr, int buf_len, int x86_64);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff819e0ae0)
Location: arch/x86/lib/insn.c:53
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/lbr.c:branch_type
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
```
**Symbols:**

```
ffffffff819e0ae0-ffffffff819e0b54: insn_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void insn_init(struct insn *insn, const void *kaddr, int buf_len, int x86_64);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff81a1ba90)
Location: arch/x86/lib/insn.c:53
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/lbr.c:branch_type
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/mpx.c:mpx_fault_info
```
**Symbols:**

```
ffffffff81a1ba90-ffffffff81a1bb04: insn_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void insn_init(struct insn *insn, const void *kaddr, int buf_len, int x86_64);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff81a8b860)
Location: arch/x86/lib/insn.c:40
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/lbr.c:branch_type
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/mpx.c:mpx_fault_info
```
**Symbols:**

```
ffffffff81a8b860-ffffffff81a8b8cc: insn_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void insn_init(struct insn *insn, const void *kaddr, int buf_len, int x86_64);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff81ac2b20)
Location: arch/x86/lib/insn.c:40
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/lbr.c:branch_type
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/mpx.c:mpx_fault_info
```
**Symbols:**

```
ffffffff81ac2b20-ffffffff81ac2b8c: insn_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void insn_init(struct insn *insn, const void *kaddr, int buf_len, int x86_64);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff815ff160)
Location: arch/x86/lib/insn.c:42
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/lbr.c:branch_type
  - arch/x86/kernel/traps.c:get_kernel_gp_address
  - arch/x86/kernel/alternative.c:text_poke_loc_init
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/uprobes.c:uprobe_init_insn
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff815ff160-ffffffff815ff1cc: insn_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void insn_init(struct insn *insn, const void *kaddr, int buf_len, int x86_64);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff81624130)
Location: arch/x86/lib/insn.c:42
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/lbr.c:branch_type
  - arch/x86/kernel/traps.c:get_kernel_gp_address
  - arch/x86/kernel/alternative.c:text_poke_loc_init
  - arch/x86/kernel/cpu/mce/severity.c:is_copy_from_user
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/uprobes.c:uprobe_init_insn
  - arch/x86/kernel/sev-es.c:vc_decode_insn
  - arch/x86/lib/insn-eval.c:insn_decode
```
**Symbols:**

```
ffffffff81624130-ffffffff8162419c: insn_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void insn_init(struct insn *insn, const void *kaddr, int buf_len, int x86_64);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff81607c92)
Location: arch/x86/lib/insn.c:60
Inline: True
Inline callers:
  - arch/x86/lib/insn.c:insn_decode
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/lbr.c:branch_type
  - arch/x86/lib/insn-eval.c:insn_decode_from_regs
  - arch/x86/lib/insn.c:insn_decode
```
**Symbols:**

```
ffffffff816077d0-ffffffff8160783b: insn_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void insn_init(struct insn *insn, const void *kaddr, int buf_len, int x86_64);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff816768d2)
Location: arch/x86/lib/insn.c:61
Inline: True
Inline callers:
  - arch/x86/lib/insn.c:insn_decode
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/lbr.c:branch_type
  - arch/x86/lib/insn-eval.c:insn_decode_from_regs
  - arch/x86/lib/insn.c:insn_decode
```
**Symbols:**

```
ffffffff81676400-ffffffff8167646b: insn_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void insn_init(struct insn *insn, const void *kaddr, int buf_len, int x86_64);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff81790940)
Location: arch/x86/lib/insn.c:61
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/lbr.c:branch_type
  - arch/x86/lib/insn-eval.c:insn_decode_from_regs
  - arch/x86/lib/insn.c:insn_decode
  - arch/x86/lib/insn.c:insn_decode
```
**Symbols:**

```
ffffffff81790940-ffffffff817909bf: insn_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void insn_init(struct insn *insn, const void *kaddr, int buf_len, int x86_64);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff8204e580)
Location: arch/x86/lib/insn.c:61
Inline: False
Direct callers:
  - arch/x86/events/utils.c:get_branch_type
  - arch/x86/events/utils.c:get_branch_type
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/lib/insn-eval.c:insn_decode_from_regs
  - arch/x86/lib/insn.c:insn_decode
  - arch/x86/lib/insn.c:insn_decode
```
**Symbols:**

```
ffffffff8204e580-ffffffff8204e5ff: insn_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void insn_init(struct insn *insn, const void *kaddr, int buf_len, int x86_64);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff820cce00)
Location: arch/x86/lib/insn.c:61
Inline: False
Direct callers:
  - arch/x86/events/utils.c:get_branch_type
  - arch/x86/events/utils.c:get_branch_type
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/lib/insn-eval.c:insn_decode_from_regs
  - arch/x86/lib/insn.c:insn_decode
  - arch/x86/lib/insn.c:insn_decode
```
**Symbols:**

```
ffffffff820cce00-ffffffff820cce7f: insn_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void insn_init(struct insn *insn, const void *kaddr, int buf_len, int x86_64);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff821a7620)
Location: arch/x86/lib/insn.c:61
Inline: False
Direct callers:
  - arch/x86/events/utils.c:get_branch_type
  - arch/x86/events/utils.c:get_branch_type
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/lib/insn-eval.c:insn_decode_from_regs
  - arch/x86/lib/insn.c:insn_decode
  - arch/x86/lib/insn.c:insn_decode
```
**Symbols:**

```
ffffffff821a7620-ffffffff821a769f: insn_init (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void insn_init(struct insn *insn, const void *kaddr, int buf_len, int x86_64);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff81a61970)
Location: arch/x86/lib/insn.c:40
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/lbr.c:branch_type
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/mpx.c:mpx_fault_info
```
**Symbols:**

```
ffffffff81a61970-ffffffff81a619dc: insn_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void insn_init(struct insn *insn, const void *kaddr, int buf_len, int x86_64);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff81a1e9e0)
Location: arch/x86/lib/insn.c:40
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/lbr.c:branch_type
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/mpx.c:mpx_fault_info
```
**Symbols:**

```
ffffffff81a1e9e0-ffffffff81a1ea4c: insn_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void insn_init(struct insn *insn, const void *kaddr, int buf_len, int x86_64);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff81acdd60)
Location: arch/x86/lib/insn.c:40
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/lbr.c:branch_type
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/mpx.c:mpx_fault_info
```
**Symbols:**

```
ffffffff81acdd60-ffffffff81acddcc: insn_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void insn_init(struct insn *insn, const void *kaddr, int buf_len, int x86_64);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff81ada270)
Location: arch/x86/lib/insn.c:40
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/lbr.c:branch_type
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/mpx.c:mpx_fault_info
```
**Symbols:**

```
ffffffff81ada270-ffffffff81ada2dc: insn_init (STB_GLOBAL)
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
