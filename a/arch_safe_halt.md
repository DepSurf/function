# Function: <code>arch_safe_halt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void arch_safe_halt();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81038dd9)
Location: arch/x86/include/asm/paravirt.h:115
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:default_idle
```
```
In arch/x86/kernel/kvm.c (ffffffff81063b2d)
Location: arch/x86/include/asm/paravirt.h:115
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff814ac53f)
Location: arch/x86/include/asm/paravirt.h:115
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_safe_halt
```
**Symbols:**

```
ffffffff814ac53f-ffffffff814ac54c: arch_safe_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void arch_safe_halt();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81037e5b)
Location: arch/x86/include/asm/paravirt.h:105
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:default_idle
```
```
In arch/x86/kernel/kvm.c (ffffffff8106374d)
Location: arch/x86/include/asm/paravirt.h:105
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff814fb899)
Location: arch/x86/include/asm/paravirt.h:105
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_safe_halt
```
**Symbols:**

```
ffffffff814fb899-ffffffff814fb8a6: arch_safe_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void arch_safe_halt();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff818d3a9b)
Location: arch/x86/include/asm/paravirt.h:96
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:default_idle
```
```
In arch/x86/kernel/kvm.c (ffffffff81066bfd)
Location: arch/x86/include/asm/paravirt.h:96
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff8151e56d)
Location: arch/x86/include/asm/paravirt.h:96
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_safe_halt
```
**Symbols:**

```
ffffffff8151e56d-ffffffff8151e57a: arch_safe_halt (STB_LOCAL)
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
In arch/x86/kernel/process.c (ffffffff8190abab)
Location: arch/x86/include/asm/paravirt.h:96
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:default_idle
```
```
In arch/x86/kernel/kvm.c (ffffffff81065ede)
Location: arch/x86/include/asm/paravirt.h:96
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff8152f713)
Location: arch/x86/include/asm/paravirt.h:96
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
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
In arch/x86/kernel/process.c (ffffffff81994f1b)
Location: arch/x86/include/asm/paravirt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:default_idle
```
```
In arch/x86/kernel/kvm.c (ffffffff8106a22f)
Location: arch/x86/include/asm/paravirt.h:92
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff81591823)
Location: arch/x86/include/asm/paravirt.h:92
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_safe_halt
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
In arch/x86/kernel/process.c (ffffffff819f14bb)
Location: arch/x86/include/asm/paravirt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:default_idle
```
```
In arch/x86/kernel/kvm.c (ffffffff8106cd9d)
Location: arch/x86/include/asm/paravirt.h:92
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff815c8b73)
Location: arch/x86/include/asm/paravirt.h:92
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_safe_halt
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
In arch/x86/kernel/process.c (ffffffff81a2c87d)
Location: arch/x86/include/asm/paravirt.h:154
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:default_idle
```
```
In arch/x86/kernel/kvm.c (ffffffff81072f6d)
Location: arch/x86/include/asm/paravirt.h:154
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff815e2143)
Location: arch/x86/include/asm/paravirt.h:154
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_safe_halt
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
In arch/x86/kernel/process.c (ffffffff81a9c9eb)
Location: arch/x86/include/asm/paravirt.h:154
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:default_idle
```
```
In arch/x86/kernel/kvm.c (ffffffff81076afb)
Location: arch/x86/include/asm/paravirt.h:154
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff816140d3)
Location: arch/x86/include/asm/paravirt.h:154
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_safe_halt
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
In arch/x86/kernel/process.c (ffffffff81ad423b)
Location: arch/x86/include/asm/paravirt.h:142
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:default_idle
```
```
In arch/x86/kernel/kvm.c (ffffffff81077b4b)
Location: arch/x86/include/asm/paravirt.h:142
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff816355c3)
Location: arch/x86/include/asm/paravirt.h:142
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_safe_halt
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
In arch/x86/kernel/process.c (ffffffff81bcc32b)
Location: arch/x86/include/asm/paravirt.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:default_idle
```
```
In arch/x86/kernel/kvm.c (ffffffff8107f16f)
Location: arch/x86/include/asm/paravirt.h:148
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff816e1e63)
Location: arch/x86/include/asm/paravirt.h:148
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_safe_halt
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
In arch/x86/kernel/process.c (ffffffff81c45135)
Location: arch/x86/include/asm/paravirt.h:148
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8107ed9f)
Location: arch/x86/include/asm/paravirt.h:148
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff816fff5c)
Location: arch/x86/include/asm/paravirt.h:148
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
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
In arch/x86/kernel/process.c (ffffffff81c383b5)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8107feff)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff816e1a78)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
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
In arch/x86/kernel/process.c (ffffffff81d56c45)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8108ed3f)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff81759fa2)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
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
In arch/x86/kernel/process.c (ffffffff81050b33)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8109ecf8)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff8188d02a)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8105e023)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff810b63c0)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff819d4a71)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff82142f70)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:default_idle
```
```
In arch/x86/kernel/kvm.c (ffffffff810b94c0)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff81a1adff)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_safe_halt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff82225660)
Location: arch/x86/include/asm/paravirt.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:default_idle
```
```
In arch/x86/kernel/kvm.c (ffffffff810c08e0)
Location: arch/x86/include/asm/paravirt.h:173
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff81a660ff)
Location: arch/x86/include/asm/paravirt.h:173
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_safe_halt
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81a730ab)
Location: arch/x86/include/asm/paravirt.h:142
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:default_idle
```
```
In arch/x86/kernel/kvm.c (ffffffff81076b4b)
Location: arch/x86/include/asm/paravirt.h:142
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff81604db3)
Location: arch/x86/include/asm/paravirt.h:142
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_safe_halt
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
In arch/x86/kernel/process.c (ffffffff81a2f45b)
Location: arch/x86/include/asm/irqflags.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:default_idle
```
```
In arch/x86/kernel/kvm.c (ffffffff81066448)
Location: arch/x86/include/asm/irqflags.h:101
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff815efeec)
Location: arch/x86/include/asm/irqflags.h:101
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
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
In arch/x86/kernel/process.c (ffffffff81adf4bb)
Location: arch/x86/include/asm/paravirt.h:142
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:default_idle
```
```
In arch/x86/kernel/kvm.c (ffffffff81076afb)
Location: arch/x86/include/asm/paravirt.h:142
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff816298a3)
Location: arch/x86/include/asm/paravirt.h:142
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_safe_halt
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
In arch/x86/kernel/process.c (ffffffff81aebc1b)
Location: arch/x86/include/asm/paravirt.h:142
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:default_idle
```
```
In arch/x86/kernel/kvm.c (ffffffff81078c5b)
Location: arch/x86/include/asm/paravirt.h:142
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff81643743)
Location: arch/x86/include/asm/paravirt.h:142
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_safe_halt
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
</ul>
