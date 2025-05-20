# Function: <code>crash_setup_regs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8110d96f)
Location: arch/x86/include/asm/kexec.h:92
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_kexec
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8111539a)
Location: arch/x86/include/asm/kexec.h:92
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8111caba)
Location: arch/x86/include/asm/kexec.h:92
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void crash_setup_regs(struct pt_regs *newregs, struct pt_regs *oldregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8111d680)
Location: arch/x86/include/asm/kexec.h:92
Inline: False
Direct callers:
  - kernel/kexec_core.c:__crash_kexec
```
**Symbols:**

```
ffffffff8111d680-ffffffff8111d6fe: crash_setup_regs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void crash_setup_regs(struct pt_regs *newregs, struct pt_regs *oldregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81128dd0)
Location: arch/x86/include/asm/kexec.h:93
Inline: False
Direct callers:
  - kernel/kexec_core.c:__crash_kexec
```
**Symbols:**

```
ffffffff81128dd0-ffffffff81128e4d: crash_setup_regs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8113696f)
Location: arch/x86/include/asm/kexec.h:93
Inline: True
Inline callers:
  - kernel/kexec_core.c:__crash_kexec
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff811424ef)
Location: arch/x86/include/asm/kexec.h:94
Inline: True
Inline callers:
  - kernel/kexec_core.c:__crash_kexec
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8114d90f)
Location: arch/x86/include/asm/kexec.h:78
Inline: True
Inline callers:
  - kernel/kexec_core.c:__crash_kexec
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8115961f)
Location: arch/x86/include/asm/kexec.h:78
Inline: True
Inline callers:
  - kernel/kexec_core.c:__crash_kexec
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81169e9f)
Location: arch/x86/include/asm/kexec.h:74
Inline: True
Inline callers:
  - kernel/kexec_core.c:__crash_kexec
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff811665df)
Location: arch/x86/include/asm/kexec.h:74
Inline: True
Inline callers:
  - kernel/kexec_core.c:__crash_kexec
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
In kernel/kexec_core.c (ffffffff8116737f)
Location: arch/x86/include/asm/kexec.h:74
Inline: True
Inline callers:
  - kernel/kexec_core.c:__crash_kexec
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8118cbef)
Location: arch/x86/include/asm/kexec.h:74
Inline: True
Inline callers:
  - kernel/kexec_core.c:__crash_kexec
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff811bc143)
Location: arch/x86/include/asm/kexec.h:74
Inline: True
Inline callers:
  - kernel/kexec_core.c:__crash_kexec
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void crash_setup_regs(struct pt_regs *newregs, struct pt_regs *oldregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff811fe010)
Location: arch/x86/include/asm/kexec.h:74
Inline: False
Direct callers:
  - kernel/kexec_core.c:__crash_kexec
```
**Symbols:**

```
ffffffff811fe010-ffffffff811fe0a1: crash_setup_regs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void crash_setup_regs(struct pt_regs *newregs, struct pt_regs *oldregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff812132d0)
Location: arch/x86/include/asm/kexec.h:74
Inline: False
Direct callers:
  - kernel/kexec_core.c:__crash_kexec
```
**Symbols:**

```
ffffffff812132d0-ffffffff81213361: crash_setup_regs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void crash_setup_regs(struct pt_regs *newregs, struct pt_regs *oldregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8122b200)
Location: arch/x86/include/asm/kexec.h:74
Inline: False
Direct callers:
  - kernel/kexec_core.c:__crash_kexec
```
**Symbols:**

```
ffffffff8122b200-ffffffff8122b294: crash_setup_regs (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffff8000101c98d4)
Location: arch/arm64/include/asm/kexec.h:37
Inline: True
Inline callers:
  - kernel/kexec_core.c:__crash_kexec
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/machine_kexec.c (c03150c4)
Location: arch/arm/include/asm/kexec.h:36
Inline: True
Inline callers:
  - arch/arm/kernel/machine_kexec.c:machine_crash_nonpanic_core
```
```
In kernel/kexec_core.c (c041094c)
Location: arch/arm/include/asm/kexec.h:36
Inline: True
Inline callers:
  - kernel/kexec_core.c:__crash_kexec
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (c000000000232348)
Location: arch/powerpc/include/asm/kexec.h:63
Inline: True
Inline callers:
  - kernel/kexec_core.c:__crash_kexec
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81151c3f)
Location: arch/x86/include/asm/kexec.h:78
Inline: True
Inline callers:
  - kernel/kexec_core.c:__crash_kexec
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81144f1f)
Location: arch/x86/include/asm/kexec.h:78
Inline: True
Inline callers:
  - kernel/kexec_core.c:__crash_kexec
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8114faef)
Location: arch/x86/include/asm/kexec.h:78
Inline: True
Inline callers:
  - kernel/kexec_core.c:__crash_kexec
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8115c94f)
Location: arch/x86/include/asm/kexec.h:78
Inline: True
Inline callers:
  - kernel/kexec_core.c:__crash_kexec
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
