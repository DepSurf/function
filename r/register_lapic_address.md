# Function: <code>register_lapic_address</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void register_lapic_address(long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81f71908)
Location: arch/x86/kernel/apic/apic.c:1785
Inline: True
Direct callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/platform/sfi/sfi.c:sfi_platform_init
```
**Symbols:**

```
ffffffff81f71908-ffffffff81f719b5: register_lapic_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void register_lapic_address(long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81f9a0e7)
Location: arch/x86/kernel/apic/apic.c:1824
Inline: True
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/platform/sfi/sfi.c:sfi_platform_init
```
**Symbols:**

```
ffffffff81f9a0e7-ffffffff81f9a194: register_lapic_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void register_lapic_address(long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81fd55c1)
Location: arch/x86/kernel/apic/apic.c:1825
Inline: True
Direct callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/platform/sfi/sfi.c:sfi_platform_init
```
**Symbols:**

```
ffffffff81fd55c1-ffffffff81fd5665: register_lapic_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void register_lapic_address(long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff820b62ed)
Location: arch/x86/kernel/apic/apic.c:1901
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/platform/sfi/sfi.c:sfi_platform_init
```
**Symbols:**

```
ffffffff820b62ed-ffffffff820b6396: register_lapic_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void register_lapic_address(long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff826bcae9)
Location: arch/x86/kernel/apic/apic.c:1986
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/platform/sfi/sfi.c:sfi_platform_init
```
**Symbols:**

```
ffffffff826bcae9-ffffffff826bcb98: register_lapic_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void register_lapic_address(long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff826e6894)
Location: arch/x86/kernel/apic/apic.c:1999
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/platform/sfi/sfi.c:sfi_platform_init
```
**Symbols:**

```
ffffffff826e6894-ffffffff826e694a: register_lapic_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void register_lapic_address(long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8289d3dd)
Location: arch/x86/kernel/apic/apic.c:2007
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/platform/sfi/sfi.c:sfi_platform_init
```
**Symbols:**

```
ffffffff8289d3dd-ffffffff8289d493: register_lapic_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void register_lapic_address(long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff828b548a)
Location: arch/x86/kernel/apic/apic.c:2085
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/platform/sfi/sfi.c:sfi_platform_init
```
**Symbols:**

```
ffffffff828b548a-ffffffff828b5542: register_lapic_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void register_lapic_address(long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff828b88f4)
Location: arch/x86/kernel/apic/apic.c:2142
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/platform/sfi/sfi.c:sfi_platform_init
```
**Symbols:**

```
ffffffff828b88f4-ffffffff828b89ac: register_lapic_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void register_lapic_address(long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff82cdd981)
Location: arch/x86/kernel/apic/apic.c:2095
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_process_madt
  - arch/x86/kernel/mpparse.c:smp_read_mpc
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/platform/sfi/sfi.c:sfi_platform_init
```
**Symbols:**

```
ffffffff82cdd981-ffffffff82cdda1d: register_lapic_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void register_lapic_address(long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff82fc9d28)
Location: arch/x86/kernel/apic/apic.c:2121
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_process_madt
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/platform/sfi/sfi.c:sfi_platform_init
```
**Symbols:**

```
ffffffff82fc9d28-ffffffff82fc9dc4: register_lapic_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void register_lapic_address(long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff831d4641)
Location: arch/x86/kernel/apic/apic.c:2122
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
**Symbols:**

```
ffffffff831d4641-ffffffff831d46dd: register_lapic_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void register_lapic_address(long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff832b71cd)
Location: arch/x86/kernel/apic/apic.c:2119
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
**Symbols:**

```
ffffffff832b71cd-ffffffff832b7269: register_lapic_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void register_lapic_address(long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff83468d40)
Location: arch/x86/kernel/apic/apic.c:2127
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
**Symbols:**

```
ffffffff83468d40-ffffffff83468de9: register_lapic_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void register_lapic_address(long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff83e8d600)
Location: arch/x86/kernel/apic/apic.c:2161
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - arch/x86/kernel/mpparse.c:check_physptr
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
**Symbols:**

```
ffffffff83e8d600-ffffffff83e8d6e8: register_lapic_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void register_lapic_address(long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff836b0e90)
Location: arch/x86/kernel/apic/apic.c:2163
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - arch/x86/kernel/mpparse.c:check_physptr
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
**Symbols:**

```
ffffffff836b0e90-ffffffff836b0f83: register_lapic_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void register_lapic_address(long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff838e18d1)
Location: arch/x86/kernel/apic/apic.c:2107
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
Direct callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/mpparse.c:check_physptr
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
**Symbols:**

```
ffffffff838e1940-ffffffff838e1980: register_lapic_address (STB_GLOBAL)
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
void register_lapic_address(long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff828a68fb)
Location: arch/x86/kernel/apic/apic.c:2142
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/platform/sfi/sfi.c:sfi_platform_init
```
**Symbols:**

```
ffffffff828a68fb-ffffffff828a69b3: register_lapic_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void register_lapic_address(long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8289ea1b)
Location: arch/x86/kernel/apic/apic.c:2142
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/platform/sfi/sfi.c:sfi_platform_init
```
**Symbols:**

```
ffffffff8289ea1b-ffffffff8289eacf: register_lapic_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void register_lapic_address(long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff828b980b)
Location: arch/x86/kernel/apic/apic.c:2142
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/platform/sfi/sfi.c:sfi_platform_init
```
**Symbols:**

```
ffffffff828b980b-ffffffff828b98c3: register_lapic_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void register_lapic_address(long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff828b990c)
Location: arch/x86/kernel/apic/apic.c:2142
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - arch/x86/kernel/mpparse.c:default_get_smp_config
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/platform/sfi/sfi.c:sfi_platform_init
```
**Symbols:**

```
ffffffff828b990c-ffffffff828b99c4: register_lapic_address (STB_GLOBAL)
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
