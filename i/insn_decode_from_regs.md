# Function: <code>insn_decode_from_regs</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool insn_decode_from_regs(struct insn *insn, struct pt_regs *regs, unsigned char *buf, int buf_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81606f80)
Location: arch/x86/lib/insn-eval.c:1510
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/sev.c:vc_init_em_ctxt
```
**Symbols:**

```
ffffffff81606f80-ffffffff81607007: insn_decode_from_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool insn_decode_from_regs(struct insn *insn, struct pt_regs *regs, unsigned char *buf, int buf_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81675a90)
Location: arch/x86/lib/insn-eval.c:1510
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/sev.c:vc_init_em_ctxt
```
**Symbols:**

```
ffffffff81675a90-ffffffff81675b17: insn_decode_from_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool insn_decode_from_regs(struct insn *insn, struct pt_regs *regs, unsigned char *buf, int buf_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81790730)
Location: arch/x86/lib/insn-eval.c:1555
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/sev.c:vc_decode_insn
```
**Symbols:**

```
ffffffff81790730-ffffffff817907cf: insn_decode_from_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool insn_decode_from_regs(struct insn *insn, struct pt_regs *regs, unsigned char *buf, int buf_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff8204e350)
Location: arch/x86/lib/insn-eval.c:1555
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/sev.c:vc_decode_insn
```
**Symbols:**

```
ffffffff8204e350-ffffffff8204e3ef: insn_decode_from_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool insn_decode_from_regs(struct insn *insn, struct pt_regs *regs, unsigned char *buf, int buf_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff820ccbe0)
Location: arch/x86/lib/insn-eval.c:1555
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/sev.c:vc_init_em_ctxt
```
**Symbols:**

```
ffffffff820ccbe0-ffffffff820ccc7f: insn_decode_from_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool insn_decode_from_regs(struct insn *insn, struct pt_regs *regs, unsigned char *buf, int buf_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff821a7400)
Location: arch/x86/lib/insn-eval.c:1555
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/sev.c:vc_init_em_ctxt
```
**Symbols:**

```
ffffffff821a7400-ffffffff821a749f: insn_decode_from_regs (STB_GLOBAL)
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
