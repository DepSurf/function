# Function: <code>read_apic_id</code>

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
In arch/x86/kernel/smpboot.c (ffffffff810515cc)
Location: arch/x86/include/asm/apic.h:494
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81f7196b)
Location: arch/x86/include/asm/apic.h:494
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:hard_smp_processor_id
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81f71e96)
Location: arch/x86/include/asm/apic.h:494
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810571c5)
Location: arch/x86/include/asm/apic.h:494
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:native_disable_io_apic
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
In arch/x86/kernel/smpboot.c (ffffffff81f98002)
Location: arch/x86/include/asm/apic.h:501
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81054885)
Location: arch/x86/include/asm/apic.h:501
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:hard_smp_processor_id
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81f9a666)
Location: arch/x86/include/asm/apic.h:501
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81057465)
Location: arch/x86/include/asm/apic.h:501
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:native_disable_io_apic
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
In arch/x86/kernel/smpboot.c (ffffffff81fd3474)
Location: arch/x86/include/asm/apic.h:501
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81057665)
Location: arch/x86/include/asm/apic.h:501
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:hard_smp_processor_id
  - arch/x86/kernel/apic/apic.c:__generic_processor_info
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81fd5b2d)
Location: arch/x86/include/asm/apic.h:501
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105a1f5)
Location: arch/x86/include/asm/apic.h:501
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:native_disable_io_apic
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
In arch/x86/kernel/smpboot.c (ffffffff820b410b)
Location: arch/x86/include/asm/apic.h:497
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81056d85)
Location: arch/x86/include/asm/apic.h:497
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:hard_smp_processor_id
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
```
```
In arch/x86/kernel/apic/vector.c (ffffffff820b68a8)
Location: arch/x86/include/asm/apic.h:497
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81059845)
Location: arch/x86/include/asm/apic.h:497
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:native_disable_io_apic
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
In arch/x86/kernel/smpboot.c (ffffffff8105777f)
Location: arch/x86/include/asm/apic.h:488
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8105aaf5)
Location: arch/x86/include/asm/apic.h:488
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:hard_smp_processor_id
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
```
In arch/x86/kernel/apic/vector.c (ffffffff826bd1c9)
Location: arch/x86/include/asm/apic.h:488
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105dd35)
Location: arch/x86/include/asm/apic.h:488
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:native_disable_io_apic
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
In arch/x86/kernel/smpboot.c (ffffffff8105a65f)
Location: arch/x86/include/asm/apic.h:485
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8105d925)
Location: arch/x86/include/asm/apic.h:485
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:hard_smp_processor_id
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
```
In arch/x86/kernel/apic/vector.c (ffffffff826e711a)
Location: arch/x86/include/asm/apic.h:485
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81060d9d)
Location: arch/x86/include/asm/apic.h:485
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
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
In arch/x86/kernel/smpboot.c (ffffffff810602df)
Location: arch/x86/include/asm/apic.h:485
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810635b5)
Location: arch/x86/include/asm/apic.h:485
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:hard_smp_processor_id
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8289dc63)
Location: arch/x86/include/asm/apic.h:485
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81066a7d)
Location: arch/x86/include/asm/apic.h:485
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
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
In arch/x86/kernel/apic/apic.c (ffffffff81066c35)
Location: arch/x86/include/asm/apic.h:486
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:hard_smp_processor_id
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828b5afa)
Location: arch/x86/include/asm/apic.h:486
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106a232)
Location: arch/x86/include/asm/apic.h:486
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
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
In arch/x86/kernel/apic/apic.c (ffffffff810672a5)
Location: arch/x86/include/asm/apic.h:493
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:hard_smp_processor_id
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828b8fbe)
Location: arch/x86/include/asm/apic.h:493
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106abd2)
Location: arch/x86/include/asm/apic.h:493
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int read_apic_id();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8106deb5)
Location: arch/x86/include/asm/apic.h:493
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:hard_smp_processor_id
  - arch/x86/kernel/apic/apic.c:generic_processor_info
Direct callers:
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:__apic_intr_mode_select
  - arch/x86/kernel/apic/apic.c:__apic_intr_mode_select
```
```
In arch/x86/kernel/apic/vector.c (ffffffff82cddfc4)
Location: arch/x86/include/asm/apic.h:493
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81071fb5)
Location: arch/x86/include/asm/apic.h:493
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
```
**Symbols:**

```
ffffffff8106c3a0-ffffffff8106c3d0: read_apic_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int read_apic_id();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8106f655)
Location: arch/x86/include/asm/apic.h:483
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:hard_smp_processor_id
  - arch/x86/kernel/apic/apic.c:generic_processor_info
Direct callers:
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:__apic_intr_mode_select
  - arch/x86/kernel/apic/apic.c:__apic_intr_mode_select
```
```
In arch/x86/kernel/apic/vector.c (ffffffff82fca382)
Location: arch/x86/include/asm/apic.h:483
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81073451)
Location: arch/x86/include/asm/apic.h:483
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
```
**Symbols:**

```
ffffffff8106db30-ffffffff8106db60: read_apic_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int read_apic_id();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81070185)
Location: arch/x86/include/asm/apic.h:484
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:hard_smp_processor_id
  - arch/x86/kernel/apic/apic.c:generic_processor_info
Direct callers:
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
```
```
In arch/x86/kernel/apic/vector.c (ffffffff831d4ca7)
Location: arch/x86/include/asm/apic.h:484
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81073f21)
Location: arch/x86/include/asm/apic.h:484
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
```
**Symbols:**

```
ffffffff8106e5a0-ffffffff8106e5d0: read_apic_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int read_apic_id();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8107bca5)
Location: arch/x86/include/asm/apic.h:484
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:hard_smp_processor_id
  - arch/x86/kernel/apic/apic.c:generic_processor_info
Direct callers:
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
```
```
In arch/x86/kernel/apic/vector.c (ffffffff832b7821)
Location: arch/x86/include/asm/apic.h:484
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81081741)
Location: arch/x86/include/asm/apic.h:484
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
```
**Symbols:**

```
ffffffff81079ef0-ffffffff81079f20: read_apic_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int read_apic_id();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8108aed5)
Location: arch/x86/include/asm/apic.h:486
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:hard_smp_processor_id
  - arch/x86/kernel/apic/apic.c:generic_processor_info
Direct callers:
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
```
```
In arch/x86/kernel/apic/vector.c (ffffffff83469499)
Location: arch/x86/include/asm/apic.h:486
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81091244)
Location: arch/x86/include/asm/apic.h:486
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
```
**Symbols:**

```
ffffffff81088d50-ffffffff81088d86: read_apic_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int read_apic_id();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8109f0a5)
Location: arch/x86/include/asm/apic.h:483
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:hard_smp_processor_id
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
```
```
In arch/x86/kernel/apic/vector.c (ffffffff83e8df3d)
Location: arch/x86/include/asm/apic.h:483
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a5e64)
Location: arch/x86/include/asm/apic.h:483
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
```
**Symbols:**

```
ffffffff8109c980-ffffffff8109c9b6: read_apic_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int read_apic_id();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810a2035)
Location: arch/x86/include/asm/apic.h:484
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:hard_smp_processor_id
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
```
```
In arch/x86/kernel/apic/vector.c (ffffffff836b17dd)
Location: arch/x86/include/asm/apic.h:484
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a9074)
Location: arch/x86/include/asm/apic.h:484
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
```
**Symbols:**

```
ffffffff8109f8a0-ffffffff8109f8d6: read_apic_id (STB_LOCAL)
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
In arch/x86/kernel/cpu/amd.c (ffffffff8107d811)
Location: arch/x86/include/asm/apic.h:509
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8107e58f)
Location: arch/x86/include/asm/apic.h:509
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/apic/apic.c (ffffffff838e1780)
Location: arch/x86/include/asm/apic.h:509
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:apic_read_boot_cpu_id
```
```
In arch/x86/kernel/apic/apic_common.c (ffffffff810a90f5)
Location: arch/x86/include/asm/apic.h:509
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_common.c:default_apic_id_registered
```
```
In arch/x86/kernel/apic/vector.c (ffffffff838e209d)
Location: arch/x86/include/asm/apic.h:509
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff838e324d)
Location: arch/x86/include/asm/apic.h:509
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
```
```
In arch/x86/kernel/vsmp_64.c (ffffffff810cc6c5)
Location: arch/x86/include/asm/apic.h:509
Inline: True
Inline callers:
  - arch/x86/kernel/vsmp_64.c:apicid_phys_pkg_id
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
In arch/x86/kernel/apic/apic.c (ffffffff81066d95)
Location: arch/x86/include/asm/apic.h:493
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:hard_smp_processor_id
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828a6fc5)
Location: arch/x86/include/asm/apic.h:493
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106a6c2)
Location: arch/x86/include/asm/apic.h:493
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
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
In arch/x86/kernel/apic/apic.c (ffffffff81057165)
Location: arch/x86/include/asm/apic.h:493
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:hard_smp_processor_id
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8289f0bc)
Location: arch/x86/include/asm/apic.h:493
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105aa22)
Location: arch/x86/include/asm/apic.h:493
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
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
In arch/x86/kernel/apic/apic.c (ffffffff81067245)
Location: arch/x86/include/asm/apic.h:493
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:hard_smp_processor_id
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828b9ed5)
Location: arch/x86/include/asm/apic.h:493
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106ab72)
Location: arch/x86/include/asm/apic.h:493
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
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
In arch/x86/kernel/apic/apic.c (ffffffff81068825)
Location: arch/x86/include/asm/apic.h:493
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:hard_smp_processor_id
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:register_lapic_address
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828b9feb)
Location: arch/x86/include/asm/apic.h:493
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106c272)
Location: arch/x86/include/asm/apic.h:493
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:native_restore_boot_irq_mode
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
