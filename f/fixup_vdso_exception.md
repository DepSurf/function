# Function: <code>fixup_vdso_exception</code>

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
bool fixup_vdso_exception(struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/extable.c (ffffffff81004eb0)
Location: arch/x86/entry/vdso/extable.c:12
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81004eb0-ffffffff81004f6b: fixup_vdso_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool fixup_vdso_exception(struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/extable.c (ffffffff81004e50)
Location: arch/x86/entry/vdso/extable.c:12
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81004e50-ffffffff81004f0b: fixup_vdso_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool fixup_vdso_exception(struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/extable.c (ffffffff81005460)
Location: arch/x86/entry/vdso/extable.c:12
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81005460-ffffffff8100551b: fixup_vdso_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool fixup_vdso_exception(struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/extable.c (ffffffff81004580)
Location: arch/x86/entry/vdso/extable.c:12
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81004580-ffffffff8100465c: fixup_vdso_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool fixup_vdso_exception(struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/extable.c (ffffffff81004f10)
Location: arch/x86/entry/vdso/extable.c:12
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81004f10-ffffffff81004fec: fixup_vdso_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool fixup_vdso_exception(struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/extable.c (ffffffff81004710)
Location: arch/x86/entry/vdso/extable.c:12
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81004710-ffffffff810047ec: fixup_vdso_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool fixup_vdso_exception(struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/extable.c (ffffffff81007020)
Location: arch/x86/entry/vdso/extable.c:12
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81007020-ffffffff810070fc: fixup_vdso_exception (STB_GLOBAL)
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
