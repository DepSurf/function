# Function: <code>pin_2_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pin_2_irq(int idx, int ioapic, int pin, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81057790)
Location: arch/x86/kernel/apic/io_apic.c:1071
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_ioapic_dest
```
**Symbols:**

```
ffffffff81057790-ffffffff81057801: pin_2_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pin_2_irq(int idx, int ioapic, int pin, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81057a50)
Location: arch/x86/kernel/apic/io_apic.c:1072
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:setup_ioapic_dest
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
```
**Symbols:**

```
ffffffff81057a50-ffffffff81057ac1: pin_2_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pin_2_irq(int idx, int ioapic, int pin, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105a7e0)
Location: arch/x86/kernel/apic/io_apic.c:1071
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:setup_ioapic_dest
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
```
**Symbols:**

```
ffffffff8105a7e0-ffffffff8105a851: pin_2_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pin_2_irq(int idx, int ioapic, int pin, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81059df0)
Location: arch/x86/kernel/apic/io_apic.c:1071
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:setup_ioapic_dest
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
```
**Symbols:**

```
ffffffff81059df0-ffffffff81059e61: pin_2_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pin_2_irq(int idx, int ioapic, int pin, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105e2e0)
Location: arch/x86/kernel/apic/io_apic.c:1073
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
```
**Symbols:**

```
ffffffff8105e2e0-ffffffff8105e351: pin_2_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int pin_2_irq(int idx, int ioapic, int pin, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:1074
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
```
**Symbols:**

```
ffffffff81061300-ffffffff81061354: pin_2_irq (STB_LOCAL)
ffffffff81062132-ffffffff81062156: pin_2_irq.cold.24 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int pin_2_irq(int idx, int ioapic, int pin, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:1074
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
```
**Symbols:**

```
ffffffff81066fe0-ffffffff81067034: pin_2_irq (STB_LOCAL)
ffffffff81067e27-ffffffff81067e4b: pin_2_irq.cold.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pin_2_irq(int idx, int ioapic, int pin, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:1077
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
```
**Symbols:**

```
ffffffff8106a7a0-ffffffff8106a808: pin_2_irq (STB_LOCAL)
ffffffff8106b5f0-ffffffff8106b608: pin_2_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pin_2_irq(int idx, int ioapic, int pin, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:1077
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
```
**Symbols:**

```
ffffffff8106b140-ffffffff8106b1a8: pin_2_irq (STB_LOCAL)
ffffffff8106bf54-ffffffff8106bf6c: pin_2_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pin_2_irq(int idx, int ioapic, int pin, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8107269a)
Location: arch/x86/kernel/apic/io_apic.c:1064
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector
  - arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC_irqs
```
**Symbols:**

```
ffffffff81072530-ffffffff81072598: pin_2_irq (STB_LOCAL)
ffffffff8107328a-ffffffff810732a2: pin_2_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pin_2_irq(int idx, int ioapic, int pin, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81073b9a)
Location: arch/x86/kernel/apic/io_apic.c:1073
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector
  - arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC_irqs
```
**Symbols:**

```
ffffffff81073a30-ffffffff81073a98: pin_2_irq (STB_LOCAL)
ffffffff81bd73d2-ffffffff81bd73ea: pin_2_irq.cold (STB_LOCAL)
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
In arch/x86/kernel/apic/io_apic.c (ffffffff831d641c)
Location: arch/x86/kernel/apic/io_apic.c:1073
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector
  - arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pin_2_irq(int idx, int ioapic, int pin, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81080603)
Location: arch/x86/kernel/apic/io_apic.c:1073
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector
  - arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
```
**Symbols:**

```
ffffffff81080390-ffffffff8108043b: pin_2_irq (STB_LOCAL)
ffffffff81c9e069-ffffffff81c9e082: pin_2_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pin_2_irq(int idx, int ioapic, int pin, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810902f6)
Location: arch/x86/kernel/apic/io_apic.c:1074
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector
  - arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
```
**Symbols:**

```
ffffffff8108fcb0-ffffffff8108fd76: pin_2_irq (STB_LOCAL)
ffffffff81e4d529-ffffffff81e4d548: pin_2_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff83e901ba)
Location: arch/x86/kernel/apic/io_apic.c:1074
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector
  - arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff836b3a4d)
Location: arch/x86/kernel/apic/io_apic.c:1075
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector
  - arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff838e434a)
Location: arch/x86/kernel/apic/io_apic.c:1075
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector
  - arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int pin_2_irq(int idx, int ioapic, int pin, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:1077
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
```
**Symbols:**

```
ffffffff8106ac30-ffffffff8106ac98: pin_2_irq (STB_LOCAL)
ffffffff8106ba44-ffffffff8106ba5c: pin_2_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pin_2_irq(int idx, int ioapic, int pin, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:1077
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
```
**Symbols:**

```
ffffffff8105af90-ffffffff8105aff8: pin_2_irq (STB_LOCAL)
ffffffff8105bd74-ffffffff8105bd8c: pin_2_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pin_2_irq(int idx, int ioapic, int pin, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:1077
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
```
**Symbols:**

```
ffffffff8106b0e0-ffffffff8106b148: pin_2_irq (STB_LOCAL)
ffffffff8106bef4-ffffffff8106bf0c: pin_2_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pin_2_irq(int idx, int ioapic, int pin, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:1077
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
```
**Symbols:**

```
ffffffff8106c7e0-ffffffff8106c848: pin_2_irq (STB_LOCAL)
ffffffff8106d5f4-ffffffff8106d60c: pin_2_irq.cold (STB_LOCAL)
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
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
