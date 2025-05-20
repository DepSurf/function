# Function: <code>lapic_get_maxlvt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int lapic_get_maxlvt();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81052d0c)
Location: arch/x86/kernel/apic/apic.c:290
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
Direct callers:
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
**Symbols:**

```
ffffffff810538d0-ffffffff810538f3: lapic_get_maxlvt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int lapic_get_maxlvt();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81052e9c)
Location: arch/x86/kernel/apic/apic.c:298
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
**Symbols:**

```
ffffffff810539e0-ffffffff81053a03: lapic_get_maxlvt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int lapic_get_maxlvt();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81055b8c)
Location: arch/x86/kernel/apic/apic.c:299
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
**Symbols:**

```
ffffffff810566d0-ffffffff810566f3: lapic_get_maxlvt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int lapic_get_maxlvt();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81056344)
Location: arch/x86/kernel/apic/apic.c:301
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_suspend
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
**Symbols:**

```
ffffffff81055ff0-ffffffff81056013: lapic_get_maxlvt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int lapic_get_maxlvt();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8105a034)
Location: arch/x86/kernel/apic/apic.c:295
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_suspend
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
**Symbols:**

```
ffffffff81059ca0-ffffffff81059cc6: lapic_get_maxlvt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int lapic_get_maxlvt();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81a026b0)
Location: arch/x86/kernel/apic/apic.c:296
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
**Symbols:**

```
ffffffff8105cf40-ffffffff8105cf66: lapic_get_maxlvt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int lapic_get_maxlvt();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81c02770)
Location: arch/x86/kernel/apic/apic.c:302
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
**Symbols:**

```
ffffffff81062bd0-ffffffff81062bf6: lapic_get_maxlvt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int lapic_get_maxlvt();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81c029de)
Location: arch/x86/kernel/apic/apic.c:303
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
Direct callers:
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
**Symbols:**

```
ffffffff81066270-ffffffff81066296: lapic_get_maxlvt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int lapic_get_maxlvt();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81c02a0e)
Location: arch/x86/kernel/apic/apic.c:303
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
Direct callers:
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
**Symbols:**

```
ffffffff810668a0-ffffffff810668c6: lapic_get_maxlvt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int lapic_get_maxlvt();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8106cf31)
Location: arch/x86/kernel/apic/apic.c:303
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
Direct callers:
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
**Symbols:**

```
ffffffff8106d490-ffffffff8106d4b6: lapic_get_maxlvt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int lapic_get_maxlvt();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8106e6d1)
Location: arch/x86/kernel/apic/apic.c:309
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
Direct callers:
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
**Symbols:**

```
ffffffff8106ec10-ffffffff8106ec36: lapic_get_maxlvt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int lapic_get_maxlvt();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8106f1c1)
Location: arch/x86/kernel/apic/apic.c:309
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
Direct callers:
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
**Symbols:**

```
ffffffff8106f720-ffffffff8106f746: lapic_get_maxlvt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int lapic_get_maxlvt();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8107abc3)
Location: arch/x86/kernel/apic/apic.c:306
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
Direct callers:
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
**Symbols:**

```
ffffffff8107b150-ffffffff8107b176: lapic_get_maxlvt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int lapic_get_maxlvt();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81089c53)
Location: arch/x86/kernel/apic/apic.c:306
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_supported
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
**Symbols:**

```
ffffffff8108a260-ffffffff8108a28c: lapic_get_maxlvt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int lapic_get_maxlvt();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8109db73)
Location: arch/x86/kernel/apic/apic.c:307
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_supported
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
**Symbols:**

```
ffffffff8109e240-ffffffff8109e26c: lapic_get_maxlvt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int lapic_get_maxlvt();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810a0b51)
Location: arch/x86/kernel/apic/apic.c:310
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_supported
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:send_init_sequence
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
**Symbols:**

```
ffffffff810a1220-ffffffff810a124c: lapic_get_maxlvt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int lapic_get_maxlvt();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810a7d91)
Location: arch/x86/kernel/apic/apic.c:277
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_reenable
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover_work_func
  - arch/x86/kernel/cpu/mce/intel.c:cmci_supported
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
**Symbols:**

```
ffffffff810a85f0-ffffffff810a8611: lapic_get_maxlvt (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int lapic_get_maxlvt();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81c029ee)
Location: arch/x86/kernel/apic/apic.c:303
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
Direct callers:
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
**Symbols:**

```
ffffffff81066390-ffffffff810663b6: lapic_get_maxlvt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int lapic_get_maxlvt();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81c0289e)
Location: arch/x86/kernel/apic/apic.c:303
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
Direct callers:
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
**Symbols:**

```
ffffffff81056790-ffffffff810567b6: lapic_get_maxlvt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int lapic_get_maxlvt();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81c0295e)
Location: arch/x86/kernel/apic/apic.c:303
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
Direct callers:
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
**Symbols:**

```
ffffffff81066840-ffffffff81066866: lapic_get_maxlvt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int lapic_get_maxlvt();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81c02c1e)
Location: arch/x86/kernel/apic/apic.c:303
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:lapic_setup_esr
  - arch/x86/kernel/apic/apic.c:clear_local_APIC
Direct callers:
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
**Symbols:**

```
ffffffff81067e20-ffffffff81067e46: lapic_get_maxlvt (STB_GLOBAL)
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
