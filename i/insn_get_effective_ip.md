# Function: <code>insn_get_effective_ip</code>

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
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81623655)
Location: arch/x86/lib/insn-eval.c:1418
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81606f05)
Location: arch/x86/lib/insn-eval.c:1420
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int insn_get_effective_ip(struct pt_regs *regs, long unsigned int *ip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81675a25)
Location: arch/x86/lib/insn-eval.c:1420
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user
Direct callers:
  - arch/x86/kernel/traps.c:exc_general_protection
```
**Symbols:**

```
ffffffff81675950-ffffffff816759a6: insn_get_effective_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int insn_get_effective_ip(struct pt_regs *regs, long unsigned int *ip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff817906a5)
Location: arch/x86/lib/insn-eval.c:1465
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user
Direct callers:
  - arch/x86/kernel/traps.c:exc_general_protection
```
**Symbols:**

```
ffffffff81790560-ffffffff8179061b: insn_get_effective_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int insn_get_effective_ip(struct pt_regs *regs, long unsigned int *ip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff8204e2b5)
Location: arch/x86/lib/insn-eval.c:1465
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user
Direct callers:
  - arch/x86/kernel/traps.c:exc_general_protection
```
**Symbols:**

```
ffffffff8204e150-ffffffff8204e20b: insn_get_effective_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int insn_get_effective_ip(struct pt_regs *regs, long unsigned int *ip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff820ccb45)
Location: arch/x86/lib/insn-eval.c:1465
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user
Direct callers:
  - arch/x86/kernel/traps.c:exc_general_protection
```
**Symbols:**

```
ffffffff820cc9e0-ffffffff820cca9b: insn_get_effective_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int insn_get_effective_ip(struct pt_regs *regs, long unsigned int *ip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff821a7375)
Location: arch/x86/lib/insn-eval.c:1465
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user
Direct callers:
  - arch/x86/kernel/traps.c:exc_general_protection
```
**Symbols:**

```
ffffffff821a7210-ffffffff821a72cb: insn_get_effective_ip (STB_GLOBAL)
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
