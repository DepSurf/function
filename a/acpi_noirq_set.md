# Function: <code>acpi_noirq_set</code>

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
In arch/x86/kernel/acpi/boot.c (ffffffff81f6de30)
Location: arch/x86/include/asm/acpi.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:parse_pci
```
```
In arch/x86/pci/common.c (ffffffff81fba0b4)
Location: arch/x86/include/asm/acpi.h:68
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_setup
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
In arch/x86/kernel/acpi/boot.c (ffffffff81f96282)
Location: arch/x86/include/asm/acpi.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:parse_pci
```
```
In arch/x86/pci/common.c (ffffffff81fe7cab)
Location: arch/x86/include/asm/acpi.h:68
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_setup
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
In arch/x86/kernel/acpi/boot.c (ffffffff81fd18af)
Location: arch/x86/include/asm/acpi.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:parse_pci
```
```
In arch/x86/pci/common.c (ffffffff820264e6)
Location: arch/x86/include/asm/acpi.h:68
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_setup
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
In arch/x86/kernel/acpi/boot.c (ffffffff820b235f)
Location: arch/x86/include/asm/acpi.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:parse_pci
```
```
In arch/x86/pci/common.c (ffffffff82109a36)
Location: arch/x86/include/asm/acpi.h:70
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_setup
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
In arch/x86/kernel/acpi/boot.c (ffffffff826b8b93)
Location: arch/x86/include/asm/acpi.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:parse_pci
```
```
In arch/x86/pci/common.c (ffffffff8271339d)
Location: arch/x86/include/asm/acpi.h:70
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_setup
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
In arch/x86/kernel/acpi/boot.c (ffffffff826e2bf2)
Location: arch/x86/include/asm/acpi.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:parse_pci
  - arch/x86/kernel/acpi/boot.c:parse_acpi
  - arch/x86/kernel/acpi/boot.c:disable_acpi_pci
  - arch/x86/kernel/acpi/boot.c:disable_acpi_irq
```
```
In arch/x86/pci/xen.c (ffffffff8273c657)
Location: arch/x86/include/asm/acpi.h:71
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:pci_xen_init
```
```
In arch/x86/pci/common.c (ffffffff8273d609)
Location: arch/x86/include/asm/acpi.h:71
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_setup
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
In arch/x86/kernel/acpi/boot.c (ffffffff8289943e)
Location: arch/x86/include/asm/acpi.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:parse_pci
  - arch/x86/kernel/acpi/boot.c:parse_acpi
  - arch/x86/kernel/acpi/boot.c:disable_acpi_pci
  - arch/x86/kernel/acpi/boot.c:disable_acpi_irq
```
```
In arch/x86/pci/xen.c (ffffffff828f6672)
Location: arch/x86/include/asm/acpi.h:71
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:pci_xen_init
```
```
In arch/x86/pci/common.c (ffffffff828f7624)
Location: arch/x86/include/asm/acpi.h:71
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_setup
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
In arch/x86/kernel/acpi/boot.c (ffffffff828b111e)
Location: arch/x86/include/asm/acpi.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:parse_pci
  - arch/x86/kernel/acpi/boot.c:parse_acpi
  - arch/x86/kernel/acpi/boot.c:disable_acpi_pci
  - arch/x86/kernel/acpi/boot.c:disable_acpi_irq
```
```
In arch/x86/pci/xen.c (ffffffff829120b2)
Location: arch/x86/include/asm/acpi.h:54
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:pci_xen_init
```
```
In arch/x86/pci/common.c (ffffffff82913060)
Location: arch/x86/include/asm/acpi.h:54
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_setup
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
In arch/x86/kernel/acpi/boot.c (ffffffff828b456d)
Location: arch/x86/include/asm/acpi.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:parse_pci
  - arch/x86/kernel/acpi/boot.c:parse_acpi
  - arch/x86/kernel/acpi/boot.c:disable_acpi_pci
  - arch/x86/kernel/acpi/boot.c:disable_acpi_irq
```
```
In arch/x86/pci/xen.c (ffffffff8291be4b)
Location: arch/x86/include/asm/acpi.h:54
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:pci_xen_init
```
```
In arch/x86/pci/common.c (ffffffff8291cdf5)
Location: arch/x86/include/asm/acpi.h:54
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_setup
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
In arch/x86/kernel/acpi/boot.c (ffffffff82cd9954)
Location: arch/x86/include/asm/acpi.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:parse_pci
  - arch/x86/kernel/acpi/boot.c:parse_acpi
  - arch/x86/kernel/acpi/boot.c:disable_acpi_pci
  - arch/x86/kernel/acpi/boot.c:disable_acpi_irq
```
```
In arch/x86/pci/xen.c (ffffffff82d31bab)
Location: arch/x86/include/asm/acpi.h:53
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:pci_xen_init
```
```
In arch/x86/pci/common.c (ffffffff82d32b66)
Location: arch/x86/include/asm/acpi.h:53
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_setup
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
In arch/x86/kernel/acpi/boot.c (ffffffff82fc5ea9)
Location: arch/x86/include/asm/acpi.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:parse_pci
  - arch/x86/kernel/acpi/boot.c:parse_acpi
  - arch/x86/kernel/acpi/boot.c:disable_acpi_pci
  - arch/x86/kernel/acpi/boot.c:disable_acpi_irq
```
```
In arch/x86/pci/xen.c (ffffffff83020be3)
Location: arch/x86/include/asm/acpi.h:53
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:pci_xen_init
```
```
In arch/x86/pci/common.c (ffffffff83021b55)
Location: arch/x86/include/asm/acpi.h:53
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_setup
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
In arch/x86/kernel/acpi/boot.c (ffffffff831d05ca)
Location: arch/x86/include/asm/acpi.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:parse_pci
  - arch/x86/kernel/acpi/boot.c:parse_acpi
  - arch/x86/kernel/acpi/boot.c:disable_acpi_pci
  - arch/x86/kernel/acpi/boot.c:disable_acpi_irq
```
```
In arch/x86/pci/xen.c (ffffffff8322bdb1)
Location: arch/x86/include/asm/acpi.h:53
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:pci_xen_init
```
```
In arch/x86/pci/common.c (ffffffff8322cd12)
Location: arch/x86/include/asm/acpi.h:53
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_setup
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
In arch/x86/kernel/acpi/boot.c (ffffffff832b296b)
Location: arch/x86/include/asm/acpi.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:parse_pci
  - arch/x86/kernel/acpi/boot.c:parse_acpi
  - arch/x86/kernel/acpi/boot.c:disable_acpi_pci
  - arch/x86/kernel/acpi/boot.c:disable_acpi_irq
```
```
In arch/x86/pci/xen.c (ffffffff833165d6)
Location: arch/x86/include/asm/acpi.h:53
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:pci_xen_init
```
```
In arch/x86/pci/common.c (ffffffff83317690)
Location: arch/x86/include/asm/acpi.h:53
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_setup
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
In arch/x86/kernel/acpi/boot.c (ffffffff83463f9a)
Location: arch/x86/include/asm/acpi.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:parse_pci
  - arch/x86/kernel/acpi/boot.c:parse_acpi
  - arch/x86/kernel/acpi/boot.c:disable_acpi_pci
  - arch/x86/kernel/acpi/boot.c:disable_acpi_irq
```
```
In arch/x86/pci/xen.c (ffffffff834d0f73)
Location: arch/x86/include/asm/acpi.h:53
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:pci_xen_init
```
```
In arch/x86/pci/common.c (ffffffff834d23b2)
Location: arch/x86/include/asm/acpi.h:53
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_setup
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
In arch/x86/kernel/acpi/boot.c (ffffffff83e86c98)
Location: arch/x86/include/asm/acpi.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:parse_pci
  - arch/x86/kernel/acpi/boot.c:parse_acpi
  - arch/x86/kernel/acpi/boot.c:disable_acpi_pci
  - arch/x86/kernel/acpi/boot.c:disable_acpi_irq
```
```
In arch/x86/pci/xen.c (ffffffff83f15132)
Location: arch/x86/include/asm/acpi.h:54
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:pci_xen_init
```
```
In arch/x86/pci/common.c (ffffffff83f16e5d)
Location: arch/x86/include/asm/acpi.h:54
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_setup
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
In arch/x86/kernel/acpi/boot.c (ffffffff836aa238)
Location: arch/x86/include/asm/acpi.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:parse_pci
  - arch/x86/kernel/acpi/boot.c:parse_acpi
  - arch/x86/kernel/acpi/boot.c:disable_acpi_pci
  - arch/x86/kernel/acpi/boot.c:disable_acpi_irq
```
```
In arch/x86/pci/xen.c (ffffffff8373b8b2)
Location: arch/x86/include/asm/acpi.h:56
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:pci_xen_init
```
```
In arch/x86/pci/common.c (ffffffff8373d58d)
Location: arch/x86/include/asm/acpi.h:56
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_setup
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
In arch/x86/kernel/acpi/boot.c (ffffffff838da9d8)
Location: arch/x86/include/asm/acpi.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:parse_pci
  - arch/x86/kernel/acpi/boot.c:parse_acpi
  - arch/x86/kernel/acpi/boot.c:disable_acpi_pci
  - arch/x86/kernel/acpi/boot.c:disable_acpi_irq
```
```
In arch/x86/pci/xen.c (ffffffff83970252)
Location: arch/x86/include/asm/acpi.h:59
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:pci_xen_init
```
```
In arch/x86/pci/common.c (ffffffff83971f7d)
Location: arch/x86/include/asm/acpi.h:59
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_setup
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
In arch/x86/kernel/acpi/boot.c (ffffffff828a258c)
Location: arch/x86/include/asm/acpi.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:parse_pci
  - arch/x86/kernel/acpi/boot.c:parse_acpi
  - arch/x86/kernel/acpi/boot.c:disable_acpi_pci
  - arch/x86/kernel/acpi/boot.c:disable_acpi_irq
```
```
In arch/x86/pci/xen.c (ffffffff82900b4f)
Location: arch/x86/include/asm/acpi.h:54
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:pci_xen_init
```
```
In arch/x86/pci/common.c (ffffffff82901af9)
Location: arch/x86/include/asm/acpi.h:54
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_setup
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
In arch/x86/kernel/acpi/boot.c (ffffffff8289a6ce)
Location: arch/x86/include/asm/acpi.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:parse_pci
  - arch/x86/kernel/acpi/boot.c:parse_acpi
  - arch/x86/kernel/acpi/boot.c:disable_acpi_pci
  - arch/x86/kernel/acpi/boot.c:disable_acpi_irq
```
```
In arch/x86/pci/common.c (ffffffff828f9e46)
Location: arch/x86/include/asm/acpi.h:54
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_setup
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
In arch/x86/kernel/acpi/boot.c (ffffffff828b5489)
Location: arch/x86/include/asm/acpi.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:parse_pci
  - arch/x86/kernel/acpi/boot.c:parse_acpi
  - arch/x86/kernel/acpi/boot.c:disable_acpi_pci
  - arch/x86/kernel/acpi/boot.c:disable_acpi_irq
```
```
In arch/x86/pci/xen.c (ffffffff82916156)
Location: arch/x86/include/asm/acpi.h:54
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:pci_xen_init
```
```
In arch/x86/pci/common.c (ffffffff82917100)
Location: arch/x86/include/asm/acpi.h:54
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_setup
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
In arch/x86/kernel/acpi/boot.c (ffffffff828b5570)
Location: arch/x86/include/asm/acpi.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:parse_pci
  - arch/x86/kernel/acpi/boot.c:parse_acpi
  - arch/x86/kernel/acpi/boot.c:disable_acpi_pci
  - arch/x86/kernel/acpi/boot.c:disable_acpi_irq
```
```
In arch/x86/pci/xen.c (ffffffff8291cead)
Location: arch/x86/include/asm/acpi.h:54
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:pci_xen_init
```
```
In arch/x86/pci/common.c (ffffffff8291de57)
Location: arch/x86/include/asm/acpi.h:54
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_setup
```
</details>
</li>
</ul>

## Differences
