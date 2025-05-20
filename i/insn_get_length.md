# Function: <code>insn_get_length</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void insn_get_length(struct insn *insn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff813f7310)
Location: arch/x86/lib/insn.c:586
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/core.c:__copy_instruction
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
```
**Symbols:**

```
ffffffff813f7310-ffffffff813f733d: insn_get_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void insn_get_length(struct insn *insn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff8143df70)
Location: arch/x86/lib/insn.c:598
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/kernel/kprobes/core.c:__copy_instruction
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
```
**Symbols:**

```
ffffffff8143df70-ffffffff8143dfac: insn_get_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void insn_get_length(struct insn *insn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff8145aef0)
Location: arch/x86/lib/insn.c:598
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/kernel/kprobes/core.c:__copy_instruction
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
```
**Symbols:**

```
ffffffff8145aef0-ffffffff8145af2c: insn_get_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void insn_get_length(struct insn *insn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff818fcc90)
Location: arch/x86/lib/insn.c:598
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
```
**Symbols:**

```
ffffffff818fcc90-ffffffff818fcccc: insn_get_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void insn_get_length(struct insn *insn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff81984740)
Location: arch/x86/lib/insn.c:598
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
```
**Symbols:**

```
ffffffff81984740-ffffffff8198477c: insn_get_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void insn_get_length(struct insn *insn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff819e0c70)
Location: arch/x86/lib/insn.c:598
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
```
**Symbols:**

```
ffffffff819e0c70-ffffffff819e0cab: insn_get_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void insn_get_length(struct insn *insn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff81a1bc20)
Location: arch/x86/lib/insn.c:598
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/mpx.c:mpx_fault_info
```
**Symbols:**

```
ffffffff81a1bc20-ffffffff81a1bc5b: insn_get_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void insn_get_length(struct insn *insn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff81a8b9e0)
Location: arch/x86/lib/insn.c:585
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/mpx.c:mpx_fault_info
```
**Symbols:**

```
ffffffff81a8b9e0-ffffffff81a8ba1b: insn_get_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void insn_get_length(struct insn *insn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff81ac2ca0)
Location: arch/x86/lib/insn.c:585
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/mpx.c:mpx_fault_info
```
**Symbols:**

```
ffffffff81ac2ca0-ffffffff81ac2cdb: insn_get_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void insn_get_length(struct insn *insn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff815ff330)
Location: arch/x86/lib/insn.c:619
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/kernel/alternative.c:text_poke_loc_init
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/uprobes.c:uprobe_init_insn
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff815ff330-ffffffff815ff362: insn_get_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void insn_get_length(struct insn *insn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff81624300)
Location: arch/x86/lib/insn.c:619
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/kernel/alternative.c:text_poke_loc_init
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/uprobes.c:uprobe_init_insn
  - arch/x86/kernel/sev-es.c:vc_decode_insn
  - arch/x86/lib/insn-eval.c:insn_decode
```
**Symbols:**

```
ffffffff81624300-ffffffff81624332: insn_get_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int insn_get_length(struct insn *insn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff81607c60)
Location: arch/x86/lib/insn.c:698
Inline: True
Inline callers:
  - arch/x86/lib/insn.c:insn_decode
  - arch/x86/lib/insn.c:insn_decode
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/lib/insn-eval.c:insn_decode_from_regs
```
**Symbols:**

```
ffffffff81607bf0-ffffffff81607c3e: insn_get_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int insn_get_length(struct insn *insn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff816768a0)
Location: arch/x86/lib/insn.c:699
Inline: True
Inline callers:
  - arch/x86/lib/insn.c:insn_decode
  - arch/x86/lib/insn.c:insn_decode
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/lib/insn-eval.c:insn_decode_from_regs
```
**Symbols:**

```
ffffffff81676830-ffffffff8167687e: insn_get_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int insn_get_length(struct insn *insn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff817917a0)
Location: arch/x86/lib/insn.c:699
Inline: True
Inline callers:
  - arch/x86/lib/insn.c:insn_decode
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/lib/insn-eval.c:insn_decode_from_regs
```
**Symbols:**

```
ffffffff81791730-ffffffff81791776: insn_get_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int insn_get_length(struct insn *insn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff8204f470)
Location: arch/x86/lib/insn.c:699
Inline: True
Inline callers:
  - arch/x86/lib/insn.c:insn_decode
Direct callers:
  - arch/x86/events/utils.c:get_branch_type
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/lib/insn-eval.c:insn_decode_from_regs
```
**Symbols:**

```
ffffffff8204f3f0-ffffffff8204f436: insn_get_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int insn_get_length(struct insn *insn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff820cdcf0)
Location: arch/x86/lib/insn.c:699
Inline: True
Inline callers:
  - arch/x86/lib/insn.c:insn_decode
Direct callers:
  - arch/x86/events/utils.c:get_branch_type
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/lib/insn-eval.c:insn_decode_from_regs
```
**Symbols:**

```
ffffffff820cdc70-ffffffff820cdcb6: insn_get_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int insn_get_length(struct insn *insn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff821a8510)
Location: arch/x86/lib/insn.c:699
Inline: True
Inline callers:
  - arch/x86/lib/insn.c:insn_decode
Direct callers:
  - arch/x86/events/utils.c:get_branch_type
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/lib/insn-eval.c:insn_decode_from_regs
```
**Symbols:**

```
ffffffff821a8490-ffffffff821a84d6: insn_get_length (STB_GLOBAL)
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
void insn_get_length(struct insn *insn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff81a61af0)
Location: arch/x86/lib/insn.c:585
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/mpx.c:mpx_fault_info
```
**Symbols:**

```
ffffffff81a61af0-ffffffff81a61b2b: insn_get_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void insn_get_length(struct insn *insn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff81a1eb60)
Location: arch/x86/lib/insn.c:585
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/mpx.c:mpx_fault_info
```
**Symbols:**

```
ffffffff81a1eb60-ffffffff81a1eb9b: insn_get_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void insn_get_length(struct insn *insn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff81acdee0)
Location: arch/x86/lib/insn.c:585
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/mpx.c:mpx_fault_info
```
**Symbols:**

```
ffffffff81acdee0-ffffffff81acdf1b: insn_get_length (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void insn_get_length(struct insn *insn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff81ada3f0)
Location: arch/x86/lib/insn.c:585
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/mpx.c:mpx_fault_info
```
**Symbols:**

```
ffffffff81ada3f0-ffffffff81ada42b: insn_get_length (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
