# Function: <code>__memcpy</code>

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

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:longjmp_break_handler
  - arch/x86/kernel/kprobes/core.c:setjmp_pre_handler
```
**Symbols:**

```
ffffffff8145b050-ffffffff8145b06a: __memcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:longjmp_break_handler
  - arch/x86/kernel/kprobes/core.c:setjmp_pre_handler
```
**Symbols:**

```
ffffffff818fcde0-ffffffff818fcdfa: __memcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:longjmp_break_handler
  - arch/x86/kernel/kprobes/core.c:setjmp_pre_handler
```
**Symbols:**

```
ffffffff81984890-ffffffff819848aa: __memcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:longjmp_break_handler
  - arch/x86/kernel/kprobes/core.c:setjmp_pre_handler
```
**Symbols:**

```
ffffffff819e0dc0-ffffffff819e0dda: __memcpy (STB_GLOBAL)
```
</details>
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
<summary>In <code>5.8</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:fixup_bad_iret
  - arch/x86/kernel/traps.c:fixup_bad_iret
  - arch/x86/kernel/traps.c:fixup_bad_iret
```
**Symbols:**

```
ffffffff81bbfb00-ffffffff81bbfb1a: __memcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:fixup_bad_iret
  - arch/x86/kernel/traps.c:fixup_bad_iret
  - arch/x86/kernel/traps.c:fixup_bad_iret
```
**Symbols:**

```
ffffffff81c38ac0-ffffffff81c38ada: __memcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:fixup_bad_iret
  - arch/x86/kernel/traps.c:fixup_bad_iret
  - arch/x86/kernel/traps.c:fixup_bad_iret
```
**Symbols:**

```
ffffffff81c2ae80-ffffffff81c2ae9a: __memcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:fixup_bad_iret
  - arch/x86/kernel/traps.c:fixup_bad_iret
  - arch/x86/kernel/traps.c:fixup_bad_iret
```
**Symbols:**

```
ffffffff81d49410-ffffffff81d4942a: __memcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __memcpy();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/memcpy_64.S (ffffffff81f188c0)
Location: arch/x86/lib/memcpy_64.S
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:fixup_bad_iret
  - arch/x86/kernel/traps.c:fixup_bad_iret
  - arch/x86/kernel/traps.c:fixup_bad_iret
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
**Symbols:**

```
ffffffff81f188c0-ffffffff81f188de: __memcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __memcpy();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/memcpy_64.S (ffffffff820c0290)
Location: arch/x86/lib/memcpy_64.S
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:fixup_bad_iret
  - arch/x86/kernel/traps.c:fixup_bad_iret
  - arch/x86/kernel/traps.c:fixup_bad_iret
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff820c0290-ffffffff820c02ae: __memcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __memcpy();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/memcpy_64.S (ffffffff82142a80)
Location: arch/x86/lib/memcpy_64.S
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:fixup_bad_iret
  - arch/x86/kernel/traps.c:fixup_bad_iret
  - arch/x86/kernel/traps.c:fixup_bad_iret
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff82142a80-ffffffff82142a8f: __memcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __memcpy();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/memcpy_64.S (ffffffff82225170)
Location: arch/x86/lib/memcpy_64.S
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:fixup_bad_iret
  - arch/x86/kernel/traps.c:fixup_bad_iret
  - arch/x86/kernel/traps.c:fixup_bad_iret
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff82225170-ffffffff8222517f: __memcpy (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
