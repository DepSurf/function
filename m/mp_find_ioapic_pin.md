# Function: <code>mp_find_ioapic_pin</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mp_find_ioapic_pin(int ioapic, u32 gsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81057310)
Location: arch/x86/kernel/apic/io_apic.c:2676
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
```
**Symbols:**

```
ffffffff81057310-ffffffff81057368: mp_find_ioapic_pin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mp_find_ioapic_pin(int ioapic, u32 gsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810575b0)
Location: arch/x86/kernel/apic/io_apic.c:2673
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
  - arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
```
**Symbols:**

```
ffffffff810575b0-ffffffff81057608: mp_find_ioapic_pin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mp_find_ioapic_pin(int ioapic, u32 gsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105a340)
Location: arch/x86/kernel/apic/io_apic.c:2674
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
  - arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
```
**Symbols:**

```
ffffffff8105a340-ffffffff8105a398: mp_find_ioapic_pin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mp_find_ioapic_pin(int ioapic, u32 gsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810599a0)
Location: arch/x86/kernel/apic/io_apic.c:2672
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
  - arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
```
**Symbols:**

```
ffffffff810599a0-ffffffff810599da: mp_find_ioapic_pin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mp_find_ioapic_pin(int ioapic, u32 gsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105de90)
Location: arch/x86/kernel/apic/io_apic.c:2682
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
```
**Symbols:**

```
ffffffff8105de90-ffffffff8105deca: mp_find_ioapic_pin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mp_find_ioapic_pin(int ioapic, u32 gsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81060ed0)
Location: arch/x86/kernel/apic/io_apic.c:2675
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
```
**Symbols:**

```
ffffffff81060ed0-ffffffff81060f0a: mp_find_ioapic_pin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mp_find_ioapic_pin(int ioapic, u32 gsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81066bb0)
Location: arch/x86/kernel/apic/io_apic.c:2676
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
```
**Symbols:**

```
ffffffff81066bb0-ffffffff81066bea: mp_find_ioapic_pin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int mp_find_ioapic_pin(int ioapic, u32 gsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:2739
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
```
**Symbols:**

```
ffffffff8106b5ae-ffffffff8106b5da: mp_find_ioapic_pin.cold (STB_LOCAL)
ffffffff8106a370-ffffffff8106a3a1: mp_find_ioapic_pin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mp_find_ioapic_pin(int ioapic, u32 gsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106ad10)
Location: arch/x86/kernel/apic/io_apic.c:2742
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
```
**Symbols:**

```
ffffffff8106ad10-ffffffff8106ad4a: mp_find_ioapic_pin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mp_find_ioapic_pin(int ioapic, u32 gsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81072120)
Location: arch/x86/kernel/apic/io_apic.c:2735
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
```
**Symbols:**

```
ffffffff81072120-ffffffff8107215a: mp_find_ioapic_pin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mp_find_ioapic_pin(int ioapic, u32 gsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810735e0)
Location: arch/x86/kernel/apic/io_apic.c:2758
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
  - arch/x86/kernel/apic/io_apic.c:__acpi_get_override_irq
```
**Symbols:**

```
ffffffff810735e0-ffffffff8107361a: mp_find_ioapic_pin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mp_find_ioapic_pin(int ioapic, u32 gsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810740b0)
Location: arch/x86/kernel/apic/io_apic.c:2760
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
  - arch/x86/kernel/apic/io_apic.c:__acpi_get_override_irq
```
**Symbols:**

```
ffffffff810740b0-ffffffff810740ea: mp_find_ioapic_pin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int mp_find_ioapic_pin(int ioapic, u32 gsi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810815c9)
Location: arch/x86/kernel/apic/io_apic.c:2760
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
  - arch/x86/kernel/apic/io_apic.c:__acpi_get_override_irq
Direct callers:
  - arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
```
**Symbols:**

```
ffffffff81081900-ffffffff8108195f: mp_find_ioapic_pin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int mp_find_ioapic_pin(int ioapic, u32 gsi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810910a6)
Location: arch/x86/kernel/apic/io_apic.c:2774
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
  - arch/x86/kernel/apic/io_apic.c:__acpi_get_override_irq
Direct callers:
  - arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
```
**Symbols:**

```
ffffffff81091430-ffffffff810914a3: mp_find_ioapic_pin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int mp_find_ioapic_pin(int ioapic, u32 gsi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a5ca1)
Location: arch/x86/kernel/apic/io_apic.c:2774
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
  - arch/x86/kernel/apic/io_apic.c:__acpi_get_override_irq
Direct callers:
  - arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
```
**Symbols:**

```
ffffffff810a6090-ffffffff810a6103: mp_find_ioapic_pin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int mp_find_ioapic_pin(int ioapic, u32 gsi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a8ea4)
Location: arch/x86/kernel/apic/io_apic.c:2781
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
  - arch/x86/kernel/apic/io_apic.c:__acpi_get_override_irq
Direct callers:
  - arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
```
**Symbols:**

```
ffffffff810a9290-ffffffff810a9306: mp_find_ioapic_pin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int mp_find_ioapic_pin(int ioapic, u32 gsi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810aff34)
Location: arch/x86/kernel/apic/io_apic.c:2777
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
  - arch/x86/kernel/apic/io_apic.c:__acpi_get_override_irq
Direct callers:
  - arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
```
**Symbols:**

```
ffffffff810b0320-ffffffff810b0396: mp_find_ioapic_pin (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int mp_find_ioapic_pin(int ioapic, u32 gsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106a800)
Location: arch/x86/kernel/apic/io_apic.c:2748
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
```
**Symbols:**

```
ffffffff8106a800-ffffffff8106a83a: mp_find_ioapic_pin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int mp_find_ioapic_pin(int ioapic, u32 gsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105ab60)
Location: arch/x86/kernel/apic/io_apic.c:2742
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
```
**Symbols:**

```
ffffffff8105ab60-ffffffff8105ab9a: mp_find_ioapic_pin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mp_find_ioapic_pin(int ioapic, u32 gsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106acb0)
Location: arch/x86/kernel/apic/io_apic.c:2742
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
```
**Symbols:**

```
ffffffff8106acb0-ffffffff8106acea: mp_find_ioapic_pin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mp_find_ioapic_pin(int ioapic, u32 gsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106c3b0)
Location: arch/x86/kernel/apic/io_apic.c:2742
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
```
**Symbols:**

```
ffffffff8106c3b0-ffffffff8106c3ea: mp_find_ioapic_pin (STB_GLOBAL)
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
