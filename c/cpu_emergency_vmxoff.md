# Function: <code>cpu_emergency_vmxoff</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff8105034c)
Location: arch/x86/include/asm/virtext.h:64
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/crash.c (ffffffff8105d62d)
Location: arch/x86/include/asm/virtext.h:64
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:kdump_nmi_callback
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff810504cc)
Location: arch/x86/include/asm/virtext.h:64
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/crash.c (ffffffff8105d728)
Location: arch/x86/include/asm/virtext.h:64
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff81052d3c)
Location: arch/x86/include/asm/virtext.h:64
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/crash.c (ffffffff810607a5)
Location: arch/x86/include/asm/virtext.h:64
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff8105284c)
Location: arch/x86/include/asm/virtext.h:64
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81053125)
Location: arch/x86/include/asm/virtext.h:64
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff8105f825)
Location: arch/x86/include/asm/virtext.h:64
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff8105655a)
Location: arch/x86/include/asm/virtext.h:64
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81056e58)
Location: arch/x86/include/asm/virtext.h:64
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff81063858)
Location: arch/x86/include/asm/virtext.h:64
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff8105937d)
Location: arch/x86/include/asm/virtext.h:64
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81059ccf)
Location: arch/x86/include/asm/virtext.h:64
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff81066509)
Location: arch/x86/include/asm/virtext.h:64
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff8105f02d)
Location: arch/x86/include/asm/virtext.h:64
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff8105f94f)
Location: arch/x86/include/asm/virtext.h:64
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff8106c519)
Location: arch/x86/include/asm/virtext.h:64
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff8106243d)
Location: arch/x86/include/asm/virtext.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81062dbe)
Location: arch/x86/include/asm/virtext.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff81070519)
Location: arch/x86/include/asm/virtext.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff81062cad)
Location: arch/x86/include/asm/virtext.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff8106347e)
Location: arch/x86/include/asm/virtext.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff81071519)
Location: arch/x86/include/asm/virtext.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff81068d4d)
Location: arch/x86/include/asm/virtext.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81069281)
Location: arch/x86/include/asm/virtext.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
```
In arch/x86/kernel/crash.c (ffffffff81078623)
Location: arch/x86/include/asm/virtext.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff8106a99d)
Location: arch/x86/include/asm/virtext.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff8106aea1)
Location: arch/x86/include/asm/virtext.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
```
In arch/x86/kernel/crash.c (ffffffff81078628)
Location: arch/x86/include/asm/virtext.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff8106b47c)
Location: arch/x86/include/asm/virtext.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff8106bc91)
Location: arch/x86/include/asm/virtext.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
```
In arch/x86/kernel/crash.c (ffffffff810794e8)
Location: arch/x86/include/asm/virtext.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff81075f6c)
Location: arch/x86/include/asm/virtext.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81076771)
Location: arch/x86/include/asm/virtext.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
```
In arch/x86/kernel/crash.c (ffffffff81087548)
Location: arch/x86/include/asm/virtext.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff81084c7c)
Location: arch/x86/include/asm/virtext.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81085350)
Location: arch/x86/include/asm/virtext.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
```
In arch/x86/kernel/crash.c (ffffffff8109768c)
Location: arch/x86/include/asm/virtext.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void cpu_emergency_vmxoff();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff81097e61)
Location: arch/x86/include/asm/virtext.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff81097ca0-ffffffff81097d31: cpu_emergency_vmxoff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void cpu_emergency_vmxoff();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff8109af01)
Location: arch/x86/include/asm/virtext.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff8109ad40-ffffffff8109adda: cpu_emergency_vmxoff (STB_LOCAL)
```
</details>
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff8106279d)
Location: arch/x86/include/asm/virtext.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81062f6e)
Location: arch/x86/include/asm/virtext.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff81070519)
Location: arch/x86/include/asm/virtext.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff81052b9f)
Location: arch/x86/include/asm/virtext.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81053297)
Location: arch/x86/include/asm/virtext.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff81060523)
Location: arch/x86/include/asm/virtext.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff81062c4d)
Location: arch/x86/include/asm/virtext.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff8106341e)
Location: arch/x86/include/asm/virtext.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff81070519)
Location: arch/x86/include/asm/virtext.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/reboot.c (ffffffff8106420d)
Location: arch/x86/include/asm/virtext.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff810649de)
Location: arch/x86/include/asm/virtext.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff81072533)
Location: arch/x86/include/asm/virtext.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
