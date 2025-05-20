# Function: <code>insn_fetch_from_user_inatomic</code>

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
int insn_fetch_from_user_inatomic(struct pt_regs *regs, unsigned char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81623650)
Location: arch/x86/lib/insn-eval.c:1480
Inline: False
Direct callers:
  - arch/x86/kernel/sev-es.c:vc_decode_insn
```
**Symbols:**

```
ffffffff81623650-ffffffff816236c1: insn_fetch_from_user_inatomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int insn_fetch_from_user_inatomic(struct pt_regs *regs, unsigned char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81606f00)
Location: arch/x86/lib/insn-eval.c:1482
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_init_em_ctxt
```
**Symbols:**

```
ffffffff81606f00-ffffffff81606f71: insn_fetch_from_user_inatomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int insn_fetch_from_user_inatomic(struct pt_regs *regs, unsigned char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81675a20)
Location: arch/x86/lib/insn-eval.c:1483
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_init_em_ctxt
```
**Symbols:**

```
ffffffff81675a20-ffffffff81675a8c: insn_fetch_from_user_inatomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int insn_fetch_from_user_inatomic(struct pt_regs *regs, unsigned char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff817906a0)
Location: arch/x86/lib/insn-eval.c:1528
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_decode_insn
```
**Symbols:**

```
ffffffff817906a0-ffffffff81790724: insn_fetch_from_user_inatomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int insn_fetch_from_user_inatomic(struct pt_regs *regs, unsigned char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff8204e2b0)
Location: arch/x86/lib/insn-eval.c:1528
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_decode_insn
```
**Symbols:**

```
ffffffff8204e2b0-ffffffff8204e334: insn_fetch_from_user_inatomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int insn_fetch_from_user_inatomic(struct pt_regs *regs, unsigned char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff820ccb40)
Location: arch/x86/lib/insn-eval.c:1528
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_init_em_ctxt
```
**Symbols:**

```
ffffffff820ccb40-ffffffff820ccbc6: insn_fetch_from_user_inatomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int insn_fetch_from_user_inatomic(struct pt_regs *regs, unsigned char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff821a7370)
Location: arch/x86/lib/insn-eval.c:1528
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_init_em_ctxt
```
**Symbols:**

```
ffffffff821a7370-ffffffff821a73ea: insn_fetch_from_user_inatomic (STB_GLOBAL)
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
