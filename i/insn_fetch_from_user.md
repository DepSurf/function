# Function: <code>insn_fetch_from_user</code>

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
int insn_fetch_from_user(struct pt_regs *regs, unsigned char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff816235e0)
Location: arch/x86/lib/insn-eval.c:1451
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff816235e0-ffffffff8162364d: insn_fetch_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int insn_fetch_from_user(struct pt_regs *regs, unsigned char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81606e90)
Location: arch/x86/lib/insn-eval.c:1453
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff81606e90-ffffffff81606efd: insn_fetch_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int insn_fetch_from_user(struct pt_regs *regs, unsigned char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff816759b0)
Location: arch/x86/lib/insn-eval.c:1455
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff816759b0-ffffffff81675a1b: insn_fetch_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int insn_fetch_from_user(struct pt_regs *regs, unsigned char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81790620)
Location: arch/x86/lib/insn-eval.c:1500
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff81790620-ffffffff81790694: insn_fetch_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int insn_fetch_from_user(struct pt_regs *regs, unsigned char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff8204e220)
Location: arch/x86/lib/insn-eval.c:1500
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff8204e220-ffffffff8204e294: insn_fetch_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int insn_fetch_from_user(struct pt_regs *regs, unsigned char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff820ccab0)
Location: arch/x86/lib/insn-eval.c:1500
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff820ccab0-ffffffff820ccb24: insn_fetch_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int insn_fetch_from_user(struct pt_regs *regs, unsigned char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff821a72e0)
Location: arch/x86/lib/insn-eval.c:1500
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff821a72e0-ffffffff821a7354: insn_fetch_from_user (STB_GLOBAL)
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
