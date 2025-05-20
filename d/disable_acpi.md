# Function: <code>disable_acpi</code>

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
In arch/x86/xen/setup.c (ffffffff81f621a8)
Location: arch/x86/include/asm/acpi.h:59
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_arch_setup
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff81f6dec4)
Location: arch/x86/include/asm/acpi.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
```
```
In drivers/acpi/bus.c (ffffffff81fa19cb)
Location: arch/x86/include/asm/acpi.h:59
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_early_init
  - drivers/acpi/bus.c:acpi_subsystem_init
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
In arch/x86/xen/setup.c (ffffffff81f89e22)
Location: arch/x86/include/asm/acpi.h:59
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_arch_setup
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff81f96cc5)
Location: arch/x86/include/asm/acpi.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
```
```
In drivers/acpi/bus.c (ffffffff81fcda72)
Location: arch/x86/include/asm/acpi.h:59
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_subsystem_init
  - drivers/acpi/bus.c:acpi_early_init
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
In arch/x86/xen/setup.c (ffffffff81fc521c)
Location: arch/x86/include/asm/acpi.h:59
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_arch_setup
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff81fd21c3)
Location: arch/x86/include/asm/acpi.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
```
```
In drivers/acpi/bus.c (ffffffff8200aa81)
Location: arch/x86/include/asm/acpi.h:59
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_subsystem_init
  - drivers/acpi/bus.c:acpi_early_init
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
In arch/x86/xen/setup.c (ffffffff820a503c)
Location: arch/x86/include/asm/acpi.h:61
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_arch_setup
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff820b2e98)
Location: arch/x86/include/asm/acpi.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
```
```
In drivers/acpi/bus.c (ffffffff820ec21d)
Location: arch/x86/include/asm/acpi.h:61
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_subsystem_init
  - drivers/acpi/bus.c:acpi_early_init
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
In arch/x86/xen/setup.c (ffffffff826ab743)
Location: arch/x86/include/asm/acpi.h:61
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_arch_setup
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff826b96db)
Location: arch/x86/include/asm/acpi.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
```
```
In drivers/acpi/bus.c (ffffffff826f50fa)
Location: arch/x86/include/asm/acpi.h:61
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_subsystem_init
  - drivers/acpi/bus.c:acpi_early_init
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
In arch/x86/xen/setup.c (ffffffff826d48ad)
Location: arch/x86/include/asm/acpi.h:62
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_arch_setup
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff826e2add)
Location: arch/x86/include/asm/acpi.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:parse_acpi
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
  - arch/x86/kernel/acpi/boot.c:dmi_disable_acpi
```
```
In arch/x86/kernel/jailhouse.c (ffffffff826e9f71)
Location: arch/x86/include/asm/acpi.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
```
```
In drivers/acpi/bus.c (ffffffff8271ef0f)
Location: arch/x86/include/asm/acpi.h:62
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/bus.c:acpi_subsystem_init
  - drivers/acpi/bus.c:acpi_early_init
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
In arch/x86/xen/setup.c (ffffffff8288a862)
Location: arch/x86/include/asm/acpi.h:62
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_arch_setup
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff82899329)
Location: arch/x86/include/asm/acpi.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:parse_acpi
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
  - arch/x86/kernel/acpi/boot.c:dmi_disable_acpi
```
```
In arch/x86/kernel/jailhouse.c (ffffffff828a0b8b)
Location: arch/x86/include/asm/acpi.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
```
```
In drivers/acpi/bus.c (ffffffff828d6f23)
Location: arch/x86/include/asm/acpi.h:62
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/bus.c:acpi_subsystem_init
  - drivers/acpi/bus.c:acpi_early_init
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
In arch/x86/xen/setup.c (ffffffff828a1c1f)
Location: arch/x86/include/asm/acpi.h:45
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_arch_setup
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff828b1008)
Location: arch/x86/include/asm/acpi.h:45
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:parse_acpi
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
  - arch/x86/kernel/acpi/boot.c:dmi_disable_acpi
```
```
In arch/x86/kernel/jailhouse.c (ffffffff828b8dab)
Location: arch/x86/include/asm/acpi.h:45
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
```
```
In drivers/acpi/bus.c (ffffffff828f0d9a)
Location: arch/x86/include/asm/acpi.h:45
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/bus.c:acpi_subsystem_init
  - drivers/acpi/bus.c:acpi_early_init
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
In arch/x86/xen/setup.c (ffffffff828a4cdf)
Location: arch/x86/include/asm/acpi.h:45
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_arch_setup
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff828b4457)
Location: arch/x86/include/asm/acpi.h:45
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:parse_acpi
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
  - arch/x86/kernel/acpi/boot.c:dmi_disable_acpi
```
```
In arch/x86/kernel/jailhouse.c (ffffffff828bf299)
Location: arch/x86/include/asm/acpi.h:45
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
```
```
In drivers/acpi/bus.c (ffffffff828f9f04)
Location: arch/x86/include/asm/acpi.h:45
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/bus.c:acpi_subsystem_init
  - drivers/acpi/bus.c:acpi_early_init
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
In arch/x86/xen/setup.c (ffffffff82ccb034)
Location: arch/x86/include/asm/acpi.h:44
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_arch_setup
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff82cd983e)
Location: arch/x86/include/asm/acpi.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:parse_acpi
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
  - arch/x86/kernel/acpi/boot.c:dmi_disable_acpi
  - arch/x86/kernel/acpi/boot.c:acpi_process_madt
  - arch/x86/kernel/acpi/boot.c:early_acpi_process_madt
```
```
In arch/x86/kernel/jailhouse.c (ffffffff82ce371c)
Location: arch/x86/include/asm/acpi.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
```
```
In drivers/acpi/bus.c (ffffffff82d10f86)
Location: arch/x86/include/asm/acpi.h:44
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/bus.c:acpi_subsystem_init
  - drivers/acpi/bus.c:acpi_early_init
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
In arch/x86/xen/setup.c (ffffffff82fb6ea2)
Location: arch/x86/include/asm/acpi.h:44
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_arch_setup
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff82fc5d93)
Location: arch/x86/include/asm/acpi.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:parse_acpi
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
  - arch/x86/kernel/acpi/boot.c:dmi_disable_acpi
  - arch/x86/kernel/acpi/boot.c:acpi_process_madt
  - arch/x86/kernel/acpi/boot.c:early_acpi_process_madt
```
```
In arch/x86/kernel/jailhouse.c (ffffffff82fd0a15)
Location: arch/x86/include/asm/acpi.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
```
```
In drivers/acpi/bus.c (ffffffff82ffea59)
Location: arch/x86/include/asm/acpi.h:44
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/bus.c:acpi_subsystem_init
  - drivers/acpi/bus.c:acpi_early_init
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
In arch/x86/xen/setup.c (ffffffff831c1646)
Location: arch/x86/include/asm/acpi.h:44
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_arch_setup
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff831d04b4)
Location: arch/x86/include/asm/acpi.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:parse_acpi
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
  - arch/x86/kernel/acpi/boot.c:dmi_disable_acpi
```
```
In arch/x86/kernel/jailhouse.c (ffffffff831db6e7)
Location: arch/x86/include/asm/acpi.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
```
```
In drivers/acpi/bus.c (ffffffff832099e9)
Location: arch/x86/include/asm/acpi.h:44
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/bus.c:acpi_subsystem_init
  - drivers/acpi/bus.c:acpi_early_init
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
In arch/x86/xen/setup.c (ffffffff832a20f3)
Location: arch/x86/include/asm/acpi.h:44
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_arch_setup
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff832b2855)
Location: arch/x86/include/asm/acpi.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:parse_acpi
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
  - arch/x86/kernel/acpi/boot.c:dmi_disable_acpi
```
```
In arch/x86/kernel/jailhouse.c (ffffffff832bea80)
Location: arch/x86/include/asm/acpi.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
```
```
In drivers/acpi/bus.c (ffffffff832f1d66)
Location: arch/x86/include/asm/acpi.h:44
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/bus.c:acpi_subsystem_init
  - drivers/acpi/bus.c:acpi_early_init
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
In arch/x86/xen/setup.c (ffffffff83451181)
Location: arch/x86/include/asm/acpi.h:44
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_arch_setup
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff83463e71)
Location: arch/x86/include/asm/acpi.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:parse_acpi
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
  - arch/x86/kernel/acpi/boot.c:dmi_disable_acpi
```
```
In arch/x86/kernel/jailhouse.c (ffffffff834706e8)
Location: arch/x86/include/asm/acpi.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
```
```
In drivers/acpi/bus.c (ffffffff834a9d73)
Location: arch/x86/include/asm/acpi.h:44
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/bus.c:acpi_subsystem_init
  - drivers/acpi/bus.c:acpi_early_init
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
In arch/x86/xen/setup.c (ffffffff83e6daf8)
Location: arch/x86/include/asm/acpi.h:45
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_arch_setup
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff83e86b7d)
Location: arch/x86/include/asm/acpi.h:45
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:parse_acpi
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
  - arch/x86/kernel/acpi/boot.c:dmi_disable_acpi
```
```
In arch/x86/kernel/jailhouse.c (ffffffff83e972d6)
Location: arch/x86/include/asm/acpi.h:45
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
```
```
In drivers/acpi/bus.c (ffffffff83ee1b47)
Location: arch/x86/include/asm/acpi.h:45
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/bus.c:acpi_subsystem_init
  - drivers/acpi/bus.c:acpi_early_init
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
In arch/x86/xen/setup.c (ffffffff8368e693)
Location: arch/x86/include/asm/acpi.h:47
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_arch_setup
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff836aa11d)
Location: arch/x86/include/asm/acpi.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:parse_acpi
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
  - arch/x86/kernel/acpi/boot.c:dmi_disable_acpi
```
```
In arch/x86/kernel/jailhouse.c (ffffffff836bae86)
Location: arch/x86/include/asm/acpi.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
```
```
In drivers/acpi/bus.c (ffffffff83707507)
Location: arch/x86/include/asm/acpi.h:47
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/bus.c:acpi_subsystem_init
  - drivers/acpi/bus.c:acpi_early_init
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
In arch/x86/xen/setup.c (ffffffff838be283)
Location: arch/x86/include/asm/acpi.h:50
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_arch_setup
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff838da8bd)
Location: arch/x86/include/asm/acpi.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:parse_acpi
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
  - arch/x86/kernel/acpi/boot.c:dmi_disable_acpi
```
```
In arch/x86/kernel/jailhouse.c (ffffffff838eb876)
Location: arch/x86/include/asm/acpi.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
```
```
In drivers/acpi/bus.c (ffffffff8393a8d7)
Location: arch/x86/include/asm/acpi.h:50
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/bus.c:acpi_subsystem_init
  - drivers/acpi/bus.c:acpi_early_init
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/acpi.c (ffff800011436974)
Location: arch/arm64/include/asm/acpi.h:73
Inline: True
Inline callers:
  - arch/arm64/kernel/acpi.c:acpi_boot_table_init
```
```
In drivers/acpi/bus.c (ffff80001147cec4)
Location: arch/arm64/include/asm/acpi.h:73
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/bus.c:acpi_subsystem_init
  - drivers/acpi/bus.c:acpi_early_init
```
</details>
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
In arch/x86/xen/setup.c (ffffffff82892cf7)
Location: arch/x86/include/asm/acpi.h:45
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_arch_setup
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff828a2476)
Location: arch/x86/include/asm/acpi.h:45
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:parse_acpi
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
  - arch/x86/kernel/acpi/boot.c:dmi_disable_acpi
```
```
In arch/x86/kernel/jailhouse.c (ffffffff828aa26f)
Location: arch/x86/include/asm/acpi.h:45
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
```
```
In drivers/acpi/bus.c (ffffffff828e2bd7)
Location: arch/x86/include/asm/acpi.h:45
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/bus.c:acpi_subsystem_init
  - drivers/acpi/bus.c:acpi_early_init
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
In arch/x86/kernel/acpi/boot.c (ffffffff8289a5b8)
Location: arch/x86/include/asm/acpi.h:45
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:parse_acpi
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
  - arch/x86/kernel/acpi/boot.c:dmi_disable_acpi
```
```
In arch/x86/kernel/jailhouse.c (ffffffff828a2550)
Location: arch/x86/include/asm/acpi.h:45
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
```
```
In drivers/acpi/bus.c (ffffffff828dac46)
Location: arch/x86/include/asm/acpi.h:45
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/bus.c:acpi_subsystem_init
  - drivers/acpi/bus.c:acpi_early_init
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
In arch/x86/xen/setup.c (ffffffff828a5cdf)
Location: arch/x86/include/asm/acpi.h:45
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_arch_setup
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff828b5373)
Location: arch/x86/include/asm/acpi.h:45
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:parse_acpi
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
  - arch/x86/kernel/acpi/boot.c:dmi_disable_acpi
```
```
In arch/x86/kernel/jailhouse.c (ffffffff828bd16e)
Location: arch/x86/include/asm/acpi.h:45
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
```
```
In drivers/acpi/bus.c (ffffffff828f5b00)
Location: arch/x86/include/asm/acpi.h:45
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/bus.c:acpi_subsystem_init
  - drivers/acpi/bus.c:acpi_early_init
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
In arch/x86/xen/setup.c (ffffffff828a5cb3)
Location: arch/x86/include/asm/acpi.h:45
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_arch_setup
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff828b545a)
Location: arch/x86/include/asm/acpi.h:45
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:parse_acpi
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
  - arch/x86/kernel/acpi/boot.c:dmi_disable_acpi
```
```
In arch/x86/kernel/jailhouse.c (ffffffff828c02bb)
Location: arch/x86/include/asm/acpi.h:45
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_init_platform
```
```
In drivers/acpi/bus.c (ffffffff828faf58)
Location: arch/x86/include/asm/acpi.h:45
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/bus.c:acpi_subsystem_init
  - drivers/acpi/bus.c:acpi_early_init
```
</details>
</li>
</ul>

## Differences
