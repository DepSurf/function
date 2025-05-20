# Function: <code>mp_find_ioapic</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mp_find_ioapic(u32 gsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810572b0)
Location: arch/x86/kernel/apic/io_apic.c:2658
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
ffffffff810572b0-ffffffff81057303: mp_find_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mp_find_ioapic(u32 gsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81057550)
Location: arch/x86/kernel/apic/io_apic.c:2655
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
ffffffff81057550-ffffffff810575a3: mp_find_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mp_find_ioapic(u32 gsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105a2e0)
Location: arch/x86/kernel/apic/io_apic.c:2656
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
ffffffff8105a2e0-ffffffff8105a333: mp_find_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mp_find_ioapic(u32 gsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81059940)
Location: arch/x86/kernel/apic/io_apic.c:2654
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
ffffffff81059940-ffffffff81059992: mp_find_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mp_find_ioapic(u32 gsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105de30)
Location: arch/x86/kernel/apic/io_apic.c:2664
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
ffffffff8105de30-ffffffff8105de82: mp_find_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int mp_find_ioapic(u32 gsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:2657
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
ffffffff81062106-ffffffff8106211c: mp_find_ioapic.cold.22 (STB_LOCAL)
ffffffff81060e80-ffffffff81060ec4: mp_find_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int mp_find_ioapic(u32 gsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:2658
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
ffffffff81067dfb-ffffffff81067e11: mp_find_ioapic.cold.20 (STB_LOCAL)
ffffffff81066b60-ffffffff81066ba4: mp_find_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int mp_find_ioapic(u32 gsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:2721
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
ffffffff8106b597-ffffffff8106b5ae: mp_find_ioapic.cold (STB_LOCAL)
ffffffff8106a320-ffffffff8106a36e: mp_find_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int mp_find_ioapic(u32 gsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:2724
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
ffffffff8106bf27-ffffffff8106bf3e: mp_find_ioapic.cold (STB_LOCAL)
ffffffff8106acc0-ffffffff8106ad0e: mp_find_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mp_find_ioapic(u32 gsi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81072183)
Location: arch/x86/kernel/apic/io_apic.c:2717
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
Direct callers:
  - arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
```
**Symbols:**

```
ffffffff81073245-ffffffff8107325c: mp_find_ioapic.cold (STB_LOCAL)
ffffffff810720d0-ffffffff8107211e: mp_find_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mp_find_ioapic(u32 gsi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81073ee5)
Location: arch/x86/kernel/apic/io_apic.c:2740
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
ffffffff81bd738d-ffffffff81bd73a4: mp_find_ioapic.cold (STB_LOCAL)
ffffffff81073590-ffffffff810735de: mp_find_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mp_find_ioapic(u32 gsi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81074985)
Location: arch/x86/kernel/apic/io_apic.c:2742
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
ffffffff81bc9540-ffffffff81bc9557: mp_find_ioapic.cold (STB_LOCAL)
ffffffff81074060-ffffffff810740a7: mp_find_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mp_find_ioapic(u32 gsi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81081565)
Location: arch/x86/kernel/apic/io_apic.c:2742
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
ffffffff81c9e1f2-ffffffff81c9e209: mp_find_ioapic.cold (STB_LOCAL)
ffffffff81081880-ffffffff810818fc: mp_find_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mp_find_ioapic(u32 gsi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81091045)
Location: arch/x86/kernel/apic/io_apic.c:2756
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
ffffffff81e4d691-ffffffff81e4d6a8: mp_find_ioapic.cold (STB_LOCAL)
ffffffff810913a0-ffffffff81091421: mp_find_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int mp_find_ioapic(u32 gsi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a5c15)
Location: arch/x86/kernel/apic/io_apic.c:2756
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
ffffffff810a5ff0-ffffffff810a6077: mp_find_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int mp_find_ioapic(u32 gsi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a8e15)
Location: arch/x86/kernel/apic/io_apic.c:2763
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
ffffffff810a91f0-ffffffff810a927a: mp_find_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int mp_find_ioapic(u32 gsi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810afea5)
Location: arch/x86/kernel/apic/io_apic.c:2759
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
ffffffff810b0280-ffffffff810b030a: mp_find_ioapic (STB_GLOBAL)
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
int mp_find_ioapic(u32 gsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:2730
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
ffffffff8106ba17-ffffffff8106ba2e: mp_find_ioapic.cold (STB_LOCAL)
ffffffff8106a7b0-ffffffff8106a7fe: mp_find_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int mp_find_ioapic(u32 gsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:2724
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
ffffffff8105bd47-ffffffff8105bd5e: mp_find_ioapic.cold (STB_LOCAL)
ffffffff8105ab10-ffffffff8105ab5e: mp_find_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int mp_find_ioapic(u32 gsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:2724
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
ffffffff8106bec7-ffffffff8106bede: mp_find_ioapic.cold (STB_LOCAL)
ffffffff8106ac60-ffffffff8106acae: mp_find_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int mp_find_ioapic(u32 gsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:2724
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
ffffffff8106d5c7-ffffffff8106d5de: mp_find_ioapic.cold (STB_LOCAL)
ffffffff8106c360-ffffffff8106c3ae: mp_find_ioapic (STB_GLOBAL)
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
