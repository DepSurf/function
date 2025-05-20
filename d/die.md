# Function: <code>die</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void die(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81032070)
Location: arch/x86/kernel/dumpstack.c:306
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_double_fault
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_bounds
```
**Symbols:**

```
ffffffff81032070-ffffffff810320d5: die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void die(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810311c0)
Location: arch/x86/kernel/dumpstack.c:319
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_double_fault
  - arch/x86/kernel/traps.c:do_trap
```
**Symbols:**

```
ffffffff810311c0-ffffffff81031225: die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void die(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81030e10)
Location: arch/x86/kernel/dumpstack.c:285
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_device_not_available
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_double_fault
  - arch/x86/kernel/traps.c:handle_stack_overflow
  - arch/x86/kernel/traps.c:do_trap
```
**Symbols:**

```
ffffffff81030e10-ffffffff81030e75: die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void die(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff8102f120)
Location: arch/x86/kernel/dumpstack.c:287
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_device_not_available
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_double_fault
  - arch/x86/kernel/traps.c:handle_stack_overflow
  - arch/x86/kernel/traps.c:do_trap
```
**Symbols:**

```
ffffffff8102f120-ffffffff8102f16b: die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void die(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81031120)
Location: arch/x86/kernel/dumpstack.c:349
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_device_not_available
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_double_fault
  - arch/x86/kernel/traps.c:handle_stack_overflow
  - arch/x86/kernel/traps.c:do_trap
```
**Symbols:**

```
ffffffff81031120-ffffffff8103116b: die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void die(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81031dc0)
Location: arch/x86/kernel/dumpstack.c:407
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_device_not_available
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_double_fault
  - arch/x86/kernel/traps.c:handle_stack_overflow
  - arch/x86/kernel/traps.c:do_trap
```
**Symbols:**

```
ffffffff81031dc0-ffffffff81031e0b: die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void die(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81033130)
Location: arch/x86/kernel/dumpstack.c:398
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_device_not_available
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_double_fault
  - arch/x86/kernel/traps.c:handle_stack_overflow
  - arch/x86/kernel/traps.c:do_trap
```
**Symbols:**

```
ffffffff81033130-ffffffff8103317b: die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void die(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81034f90)
Location: arch/x86/kernel/dumpstack.c:398
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_device_not_available
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_double_fault
  - arch/x86/kernel/traps.c:handle_stack_overflow
  - arch/x86/kernel/traps.c:do_trap
```
**Symbols:**

```
ffffffff81034f90-ffffffff81034fdd: die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void die(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810357c0)
Location: arch/x86/kernel/dumpstack.c:403
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_device_not_available
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_double_fault
  - arch/x86/kernel/traps.c:handle_stack_overflow
  - arch/x86/kernel/traps.c:do_trap
```
**Symbols:**

```
ffffffff810357c0-ffffffff8103580d: die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void die(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810376f0)
Location: arch/x86/kernel/dumpstack.c:422
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_device_not_available
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/traps.c:exc_bounds
  - arch/x86/kernel/traps.c:exc_double_fault
  - arch/x86/kernel/traps.c:handle_stack_overflow
  - arch/x86/kernel/traps.c:exc_alignment_check
  - arch/x86/kernel/traps.c:do_trap
```
**Symbols:**

```
ffffffff810376f0-ffffffff8103773d: die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void die(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81038770)
Location: arch/x86/kernel/dumpstack.c:439
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_device_not_available
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/traps.c:exc_bounds
  - arch/x86/kernel/traps.c:exc_double_fault
  - arch/x86/kernel/traps.c:handle_stack_overflow
  - arch/x86/kernel/traps.c:exc_alignment_check
  - arch/x86/kernel/traps.c:do_trap
```
**Symbols:**

```
ffffffff81038770-ffffffff810387bd: die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void die(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff8103a290)
Location: arch/x86/kernel/dumpstack.c:439
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_device_not_available
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/traps.c:exc_bounds
  - arch/x86/kernel/traps.c:exc_double_fault
  - arch/x86/kernel/traps.c:handle_stack_overflow
  - arch/x86/kernel/traps.c:exc_alignment_check
  - arch/x86/kernel/traps.c:do_trap
```
**Symbols:**

```
ffffffff8103a290-ffffffff8103a2dd: die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void die(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff8103fc40)
Location: arch/x86/kernel/dumpstack.c:439
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_device_not_available
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/traps.c:exc_bounds
  - arch/x86/kernel/traps.c:exc_double_fault
  - arch/x86/kernel/traps.c:handle_stack_overflow
  - arch/x86/kernel/traps.c:exc_alignment_check
  - arch/x86/kernel/traps.c:do_trap
```
**Symbols:**

```
ffffffff8103fc40-ffffffff8103fc8d: die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void die(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810473e0)
Location: arch/x86/kernel/dumpstack.c:433
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_device_not_available
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/traps.c:exc_bounds
  - arch/x86/kernel/traps.c:exc_double_fault
  - arch/x86/kernel/traps.c:handle_stack_overflow
  - arch/x86/kernel/traps.c:exc_alignment_check
  - arch/x86/kernel/traps.c:do_trap
```
**Symbols:**

```
ffffffff810473e0-ffffffff81047437: die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void die(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81051db0)
Location: arch/x86/kernel/dumpstack.c:439
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_device_not_available
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/traps.c:exc_bounds
  - arch/x86/kernel/traps.c:exc_double_fault
  - arch/x86/kernel/traps.c:handle_stack_overflow
  - arch/x86/kernel/traps.c:exc_alignment_check
  - arch/x86/kernel/traps.c:do_trap
```
**Symbols:**

```
ffffffff81051db0-ffffffff81051e4c: die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void die(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81052af0)
Location: arch/x86/kernel/dumpstack.c:442
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_device_not_available
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/traps.c:exc_bounds
  - arch/x86/kernel/traps.c:exc_double_fault
  - arch/x86/kernel/traps.c:handle_stack_overflow
  - arch/x86/kernel/traps.c:exc_alignment_check
  - arch/x86/kernel/traps.c:do_trap
```
**Symbols:**

```
ffffffff81052af0-ffffffff81052b8c: die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void die(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81059d10)
Location: arch/x86/kernel/dumpstack.c:442
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_device_not_available
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/traps.c:exc_bounds
  - arch/x86/kernel/traps.c:exc_double_fault
  - arch/x86/kernel/traps.c:handle_stack_overflow
  - arch/x86/kernel/traps.c:exc_alignment_check
  - arch/x86/kernel/traps.c:do_trap
```
**Symbols:**

```
ffffffff81059d10-ffffffff81059dac: die (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void die(const char *str, struct pt_regs *regs, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/traps.c (ffff800010094910)
Location: arch/arm64/kernel/traps.c:177
Inline: False
Direct callers:
  - arch/arm64/mm/fault.c:die_kernel_fault
```
**Symbols:**

```
ffff800010094910-ffff800010094bc4: die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void die(const char *str, struct pt_regs *regs, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/traps.c (c030f2d4)
Location: arch/arm/kernel/traps.c:347
Inline: False
Direct callers:
  - arch/arm/kernel/traps.c:bad_mode
```
**Symbols:**

```
c030f2d4-c030f660: die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void die(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/traps.c (c00000000002c9e0)
Location: arch/powerpc/kernel/traps.c:286
Inline: False
Direct callers:
  - arch/powerpc/kernel/traps.c:kernel_bad_stack
  - arch/powerpc/kernel/traps.c:unrecoverable_exception
  - arch/powerpc/kernel/traps.c:altivec_assist_exception
  - arch/powerpc/kernel/traps.c:facility_unavailable_exception
  - arch/powerpc/kernel/traps.c:facility_unavailable_exception
  - arch/powerpc/kernel/traps.c:vsx_unavailable_exception
  - arch/powerpc/kernel/traps.c:altivec_unavailable_exception
  - arch/powerpc/kernel/traps.c:kernel_fp_unavailable_exception
  - arch/powerpc/kernel/traps.c:program_check_exception
  - arch/powerpc/kernel/traps.c:SMIException
  - arch/powerpc/kernel/traps.c:machine_check_exception
  - arch/powerpc/kernel/traps.c:machine_check_exception
  - arch/powerpc/kernel/traps.c:system_reset_exception
  - arch/powerpc/kernel/traps.c:_exception
  - arch/powerpc/kernel/traps.c:_exception_pkey
  - arch/powerpc/mm/fault.c:bad_page_fault
  - arch/powerpc/platforms/powernv/opal.c:opal_machine_check
  - arch/powerpc/platforms/pseries/ras.c:pSeries_machine_check_exception
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvmppc_bad_interrupt
```
**Symbols:**

```
c00000000002c9e0-c00000000002cac4: die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void die(struct pt_regs *regs, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/traps.c (ffffffe0000b6b90)
Location: arch/riscv/kernel/traps.c:29
Inline: False
Direct callers:
  - arch/riscv/kernel/traps.c:do_trap_break
  - arch/riscv/mm/fault.c:do_page_fault
```
**Symbols:**

```
ffffffe0000b6b90-ffffffe0000b6ce8: die (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void die(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81035920)
Location: arch/x86/kernel/dumpstack.c:403
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_device_not_available
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_double_fault
  - arch/x86/kernel/traps.c:handle_stack_overflow
  - arch/x86/kernel/traps.c:do_trap
```
**Symbols:**

```
ffffffff81035920-ffffffff8103596d: die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void die(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81025270)
Location: arch/x86/kernel/dumpstack.c:403
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_device_not_available
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_double_fault
  - arch/x86/kernel/traps.c:handle_stack_overflow
  - arch/x86/kernel/traps.c:do_trap
```
**Symbols:**

```
ffffffff81025270-ffffffff810252bd: die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void die(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81035780)
Location: arch/x86/kernel/dumpstack.c:403
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_device_not_available
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_double_fault
  - arch/x86/kernel/traps.c:handle_stack_overflow
  - arch/x86/kernel/traps.c:do_trap
```
**Symbols:**

```
ffffffff81035780-ffffffff810357cd: die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void die(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81036760)
Location: arch/x86/kernel/dumpstack.c:403
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_device_not_available
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_double_fault
  - arch/x86/kernel/traps.c:handle_stack_overflow
  - arch/x86/kernel/traps.c:do_trap
```
**Symbols:**

```
ffffffff81036760-ffffffff810367ad: die (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long int err</code> ➡️ <code>int err</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>armhf</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long int err</code> ➡️ <code>int err</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>riscv64</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long int err</code>
</li>
<li>
<b>Param reordered. </b>
<code>str, regs, err</code> ➡️ <code>regs, str</code>
</li>
</ul>
</details>
</li>
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
