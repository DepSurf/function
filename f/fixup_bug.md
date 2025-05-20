# Function: <code>fixup_bug</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int fixup_bug(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102c8d0)
Location: arch/x86/kernel/traps.c:185
Inline: True
Direct callers:
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/mm/extable.c:early_fixup_exception
```
**Symbols:**

```
ffffffff8102c8d0-ffffffff8102c919: fixup_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int fixup_bug(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102d437)
Location: arch/x86/kernel/traps.c:173
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_error_trap
Direct callers:
  - arch/x86/kernel/traps.c:do_error_trap
  - arch/x86/mm/extable.c:early_fixup_exception
```
**Symbols:**

```
ffffffff8102d1b0-ffffffff8102d1e1: fixup_bug.part.8 (STB_LOCAL)
ffffffff8102da40-ffffffff8102da58: fixup_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int fixup_bug(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102e6b7)
Location: arch/x86/kernel/traps.c:173
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_error_trap
Direct callers:
  - arch/x86/mm/extable.c:early_fixup_exception
```
**Symbols:**

```
ffffffff8102ea00-ffffffff8102ea39: fixup_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int fixup_bug(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102f7a5)
Location: arch/x86/kernel/traps.c:173
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_error_trap
  - arch/x86/kernel/traps.c:do_error_trap
Direct callers:
  - arch/x86/mm/extable.c:early_fixup_exception
```
**Symbols:**

```
ffffffff8102fbe0-ffffffff8102fc19: fixup_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int fixup_bug(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff810315c2)
Location: arch/x86/kernel/traps.c:174
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_error_trap
  - arch/x86/kernel/traps.c:do_error_trap
Direct callers:
  - arch/x86/mm/extable.c:early_fixup_exception
```
**Symbols:**

```
ffffffff810319b0-ffffffff810319e9: fixup_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int fixup_bug(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81031e82)
Location: arch/x86/kernel/traps.c:174
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_error_trap
  - arch/x86/kernel/traps.c:do_error_trap
Direct callers:
  - arch/x86/mm/extable.c:early_fixup_exception
```
**Symbols:**

```
ffffffff81032270-ffffffff810322a9: fixup_bug (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
int fixup_bug(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81031fe2)
Location: arch/x86/kernel/traps.c:174
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_error_trap
  - arch/x86/kernel/traps.c:do_error_trap
Direct callers:
  - arch/x86/mm/extable.c:early_fixup_exception
```
**Symbols:**

```
ffffffff810323d0-ffffffff81032409: fixup_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int fixup_bug(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff810219e2)
Location: arch/x86/kernel/traps.c:174
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_error_trap
  - arch/x86/kernel/traps.c:do_error_trap
Direct callers:
  - arch/x86/mm/extable.c:early_fixup_exception
```
**Symbols:**

```
ffffffff81021d30-ffffffff81021d69: fixup_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int fixup_bug(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81031e42)
Location: arch/x86/kernel/traps.c:174
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_error_trap
  - arch/x86/kernel/traps.c:do_error_trap
Direct callers:
  - arch/x86/mm/extable.c:early_fixup_exception
```
**Symbols:**

```
ffffffff81032230-ffffffff81032269: fixup_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int fixup_bug(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81032d12)
Location: arch/x86/kernel/traps.c:174
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_error_trap
  - arch/x86/kernel/traps.c:do_error_trap
Direct callers:
  - arch/x86/mm/extable.c:early_fixup_exception
```
**Symbols:**

```
ffffffff81033170-ffffffff810331a9: fixup_bug (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
