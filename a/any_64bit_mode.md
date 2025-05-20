# Function: <code>any_64bit_mode</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff815fe692)
Location: arch/x86/include/asm/ptrace.h:166
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_eff_addr_modrm
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:insn_get_seg_base
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81010f7f)
Location: arch/x86/include/asm/ptrace.h:168
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
```
```
In arch/x86/events/intel/lbr.c (ffffffff810136af)
Location: arch/x86/include/asm/ptrace.h:168
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:branch_type
```
```
In arch/x86/lib/insn-eval.c (ffffffff81623512)
Location: arch/x86/include/asm/ptrace.h:168
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_eff_addr_modrm
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:insn_get_seg_base
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81011f2f)
Location: arch/x86/include/asm/ptrace.h:171
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
```
```
In arch/x86/events/intel/lbr.c (ffffffff8101482e)
Location: arch/x86/include/asm/ptrace.h:171
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:branch_type
```
```
In arch/x86/lib/insn-eval.c (ffffffff81606dc2)
Location: arch/x86/include/asm/ptrace.h:171
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:insn_get_seg_base
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81012e1f)
Location: arch/x86/include/asm/ptrace.h:171
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
```
```
In arch/x86/events/intel/lbr.c (ffffffff81015bde)
Location: arch/x86/include/asm/ptrace.h:171
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:branch_type
```
```
In arch/x86/lib/insn-eval.c (ffffffff81675882)
Location: arch/x86/include/asm/ptrace.h:171
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:insn_get_seg_base
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81014013)
Location: arch/x86/include/asm/ptrace.h:171
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
```
```
In arch/x86/events/intel/lbr.c (ffffffff81017d30)
Location: arch/x86/include/asm/ptrace.h:171
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:branch_type
```
```
In arch/x86/lib/insn-eval.c (ffffffff81790459)
Location: arch/x86/include/asm/ptrace.h:171
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_eff_addr_modrm
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/utils.c (ffffffff8100b224)
Location: arch/x86/include/asm/ptrace.h:171
Inline: True
Inline callers:
  - arch/x86/events/utils.c:get_branch_type
```
```
In arch/x86/events/intel/ds.c (ffffffff81018063)
Location: arch/x86/include/asm/ptrace.h:171
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
```
```
In arch/x86/lib/insn-eval.c (ffffffff8204e039)
Location: arch/x86/include/asm/ptrace.h:171
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_eff_addr_modrm
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/utils.c (ffffffff8100a9f4)
Location: arch/x86/include/asm/ptrace.h:171
Inline: True
Inline callers:
  - arch/x86/events/utils.c:get_branch_type
```
```
In arch/x86/events/intel/ds.c (ffffffff81017943)
Location: arch/x86/include/asm/ptrace.h:171
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
```
```
In arch/x86/lib/insn-eval.c (ffffffff820cc923)
Location: arch/x86/include/asm/ptrace.h:171
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_eff_addr_modrm
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/utils.c (ffffffff81010170)
Location: arch/x86/include/asm/ptrace.h:171
Inline: True
Inline callers:
  - arch/x86/events/utils.c:get_branch_type
```
```
In arch/x86/events/intel/ds.c (ffffffff8101d483)
Location: arch/x86/include/asm/ptrace.h:171
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
```
```
In arch/x86/lib/insn-eval.c (ffffffff821a7153)
Location: arch/x86/include/asm/ptrace.h:171
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
  - arch/x86/lib/insn-eval.c:get_eff_addr_modrm
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
