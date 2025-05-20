# Function: <code>insn_decode</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool insn_decode(struct insn *insn, struct pt_regs *regs, unsigned char *buf, int buf_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff816236d0)
Location: arch/x86/lib/insn-eval.c:1508
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/sev-es.c:vc_decode_insn
```
**Symbols:**

```
ffffffff816236d0-ffffffff81623751: insn_decode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int insn_decode(struct insn *insn, const void *kaddr, int buf_len, enum insn_mode m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff81607c40)
Location: arch/x86/lib/insn.c:735
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:get_kernel_gp_address
  - arch/x86/kernel/alternative.c:text_poke_loc_init
  - arch/x86/kernel/alternative.c:optimize_nops
  - arch/x86/kernel/cpu/mce/severity.c:is_copy_from_user
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
  - arch/x86/kernel/sev.c:vc_init_em_ctxt
```
**Symbols:**

```
ffffffff81607c40-ffffffff81607d2f: insn_decode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int insn_decode(struct insn *insn, const void *kaddr, int buf_len, enum insn_mode m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff81676880)
Location: arch/x86/lib/insn.c:736
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:get_kernel_gp_address
  - arch/x86/kernel/jump_label.c:arch_jump_entry_size
  - arch/x86/kernel/alternative.c:text_poke_loc_init
  - arch/x86/kernel/alternative.c:optimize_nops
  - arch/x86/kernel/cpu/mce/severity.c:is_copy_from_user
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
  - arch/x86/kernel/sev.c:vc_init_em_ctxt
```
**Symbols:**

```
ffffffff81676880-ffffffff8167696f: insn_decode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int insn_decode(struct insn *insn, const void *kaddr, int buf_len, enum insn_mode m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff81791780)
Location: arch/x86/lib/insn.c:736
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:handle_mmio
  - arch/x86/kernel/traps.c:get_kernel_gp_address
  - arch/x86/kernel/jump_label.c:arch_jump_entry_size
  - arch/x86/kernel/alternative.c:text_poke_loc_init
  - arch/x86/kernel/alternative.c:apply_returns
  - arch/x86/kernel/alternative.c:apply_retpolines
  - arch/x86/kernel/alternative.c:optimize_nops
  - arch/x86/kernel/cpu/mce/severity.c:is_copy_from_user
  - arch/x86/kernel/kprobes/core.c:__copy_instruction
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
  - arch/x86/kernel/sev.c:vc_decode_insn
```
**Symbols:**

```
ffffffff81791780-ffffffff81791809: insn_decode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int insn_decode(struct insn *insn, const void *kaddr, int buf_len, enum insn_mode m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff8204f450)
Location: arch/x86/lib/insn.c:736
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:handle_mmio
  - arch/x86/kernel/traps.c:get_kernel_gp_address
  - arch/x86/kernel/jump_label.c:arch_jump_entry_size
  - arch/x86/kernel/alternative.c:text_poke_loc_init
  - arch/x86/kernel/alternative.c:apply_returns
  - arch/x86/kernel/alternative.c:apply_retpolines
  - arch/x86/kernel/alternative.c:optimize_nops
  - arch/x86/kernel/cpu/mce/severity.c:is_copy_from_user
  - arch/x86/kernel/kprobes/core.c:__copy_instruction
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/uprobes.c:uprobe_init_insn
  - arch/x86/kernel/sev.c:vc_decode_insn
  - arch/x86/kernel/callthunks.c:call_get_dest
  - arch/x86/mm/extable.c:ex_handler_zeropad
```
**Symbols:**

```
ffffffff8204f450-ffffffff8204f4d9: insn_decode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int insn_decode(struct insn *insn, const void *kaddr, int buf_len, enum insn_mode m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff820cdcd0)
Location: arch/x86/lib/insn.c:736
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:handle_mmio
  - arch/x86/kernel/traps.c:get_kernel_gp_address
  - arch/x86/kernel/jump_label.c:arch_jump_entry_size
  - arch/x86/kernel/alternative.c:text_poke_loc_init
  - arch/x86/kernel/alternative.c:apply_returns
  - arch/x86/kernel/alternative.c:apply_retpolines
  - arch/x86/kernel/alternative.c:apply_relocation
  - arch/x86/kernel/alternative.c:optimize_nops
  - arch/x86/kernel/alternative.c:skip_nops
  - arch/x86/kernel/cpu/mce/severity.c:is_copy_from_user
  - arch/x86/kernel/kprobes/core.c:__copy_instruction
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/uprobes.c:uprobe_init_insn
  - arch/x86/kernel/sev.c:vc_init_em_ctxt
  - arch/x86/kernel/callthunks.c:call_get_dest
  - arch/x86/mm/extable.c:ex_handler_zeropad
```
**Symbols:**

```
ffffffff820cdcd0-ffffffff820cdd59: insn_decode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int insn_decode(struct insn *insn, const void *kaddr, int buf_len, enum insn_mode m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn.c (ffffffff821a84f0)
Location: arch/x86/lib/insn.c:736
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:handle_mmio
  - arch/x86/kernel/traps.c:get_kernel_gp_address
  - arch/x86/kernel/jump_label.c:arch_jump_entry_size
  - arch/x86/kernel/alternative.c:text_poke_loc_init
  - arch/x86/kernel/alternative.c:apply_returns
  - arch/x86/kernel/alternative.c:apply_retpolines
  - arch/x86/kernel/alternative.c:apply_relocation
  - arch/x86/kernel/alternative.c:optimize_nops
  - arch/x86/kernel/alternative.c:skip_nops
  - arch/x86/kernel/cpu/mce/severity.c:is_copy_from_user
  - arch/x86/kernel/kprobes/core.c:__copy_instruction
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/uprobes.c:uprobe_init_insn
  - arch/x86/kernel/sev.c:vc_init_em_ctxt
  - arch/x86/kernel/callthunks.c:call_get_dest
  - arch/x86/mm/extable.c:ex_handler_zeropad
```
**Symbols:**

```
ffffffff821a84f0-ffffffff821a8579: insn_decode (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const void *kaddr</code>
</li>
<li>
<b>Param added. </b>
<code>int buf_len</code>
</li>
<li>
<b>Param added. </b>
<code>enum insn_mode m</code>
</li>
<li>
<b>Param removed. </b>
<code>struct pt_regs *regs</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned char *buf</code>
</li>
<li>
<b>Param removed. </b>
<code>int buf_size</code>
</li>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>int</code>
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
