# Function: <code>mp_register_ioapic</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mp_register_ioapic(int id, u32 address, u32 gsi_base, struct ioapic_domain_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81057d70)
Location: arch/x86/kernel/apic/io_apic.c:2727
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_parse_ioapic
  - arch/x86/kernel/mpparse.c:MP_ioapic_info
  - arch/x86/platform/sfi/sfi.c:sfi_parse_ioapic
```
**Symbols:**

```
ffffffff81057d70-ffffffff810582ec: mp_register_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mp_register_ioapic(int id, u32 address, u32 gsi_base, struct ioapic_domain_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81058080)
Location: arch/x86/kernel/apic/io_apic.c:2724
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_parse_ioapic
  - arch/x86/kernel/mpparse.c:MP_ioapic_info
  - arch/x86/platform/sfi/sfi.c:sfi_parse_ioapic
```
**Symbols:**

```
ffffffff81058080-ffffffff8105861e: mp_register_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mp_register_ioapic(int id, u32 address, u32 gsi_base, struct ioapic_domain_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105ae10)
Location: arch/x86/kernel/apic/io_apic.c:2725
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_parse_ioapic
  - arch/x86/kernel/mpparse.c:MP_ioapic_info
  - arch/x86/platform/sfi/sfi.c:sfi_parse_ioapic
```
**Symbols:**

```
ffffffff8105ae10-ffffffff8105b3ae: mp_register_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mp_register_ioapic(int id, u32 address, u32 gsi_base, struct ioapic_domain_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105a3d0)
Location: arch/x86/kernel/apic/io_apic.c:2723
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_parse_ioapic
  - arch/x86/kernel/mpparse.c:MP_ioapic_info
  - arch/x86/platform/sfi/sfi.c:sfi_parse_ioapic
```
**Symbols:**

```
ffffffff8105a3d0-ffffffff8105a914: mp_register_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mp_register_ioapic(int id, u32 address, u32 gsi_base, struct ioapic_domain_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105e8d0)
Location: arch/x86/kernel/apic/io_apic.c:2733
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_parse_ioapic
  - arch/x86/kernel/mpparse.c:MP_ioapic_info
  - arch/x86/platform/sfi/sfi.c:sfi_parse_ioapic
```
**Symbols:**

```
ffffffff8105e8d0-ffffffff8105ee5a: mp_register_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int mp_register_ioapic(int id, u32 address, u32 gsi_base, struct ioapic_domain_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:2726
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_parse_ioapic
  - arch/x86/kernel/mpparse.c:MP_ioapic_info
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/platform/sfi/sfi.c:sfi_parse_ioapic
```
**Symbols:**

```
ffffffff810621e3-ffffffff810622f1: mp_register_ioapic.cold.27 (STB_LOCAL)
ffffffff81061880-ffffffff81061d1c: mp_register_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int mp_register_ioapic(int id, u32 address, u32 gsi_base, struct ioapic_domain_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:2727
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_parse_ioapic
  - arch/x86/kernel/mpparse.c:MP_ioapic_info
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/platform/sfi/sfi.c:sfi_parse_ioapic
```
**Symbols:**

```
ffffffff81067ed8-ffffffff81067fe6: mp_register_ioapic.cold.25 (STB_LOCAL)
ffffffff81067560-ffffffff810679fc: mp_register_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int mp_register_ioapic(int id, u32 address, u32 gsi_base, struct ioapic_domain_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:2790
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_parse_ioapic
  - arch/x86/kernel/mpparse.c:MP_ioapic_info
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/platform/sfi/sfi.c:sfi_parse_ioapic
```
**Symbols:**

```
ffffffff8106b695-ffffffff8106b7d7: mp_register_ioapic.cold (STB_LOCAL)
ffffffff8106ad10-ffffffff8106b16b: mp_register_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int mp_register_ioapic(int id, u32 address, u32 gsi_base, struct ioapic_domain_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:2793
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_parse_ioapic
  - arch/x86/kernel/mpparse.c:MP_ioapic_info
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/platform/sfi/sfi.c:sfi_parse_ioapic
```
**Symbols:**

```
ffffffff8106bff9-ffffffff8106c13b: mp_register_ioapic.cold (STB_LOCAL)
ffffffff8106b6b0-ffffffff8106bb0b: mp_register_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int mp_register_ioapic(int id, u32 address, u32 gsi_base, struct ioapic_domain_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:2786
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_ioapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_ioapic
  - arch/x86/kernel/mpparse.c:MP_ioapic_info
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/platform/sfi/sfi.c:sfi_parse_ioapic
```
**Symbols:**

```
ffffffff81073340-ffffffff8107345d: mp_register_ioapic.cold (STB_LOCAL)
ffffffff81072b20-ffffffff81072deb: mp_register_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int mp_register_ioapic(int id, u32 address, u32 gsi_base, struct ioapic_domain_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:2809
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_ioapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_ioapic
  - arch/x86/kernel/mpparse.c:MP_ioapic_info
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/platform/sfi/sfi.c:sfi_parse_ioapic
```
**Symbols:**

```
ffffffff81bd7475-ffffffff81bd7592: mp_register_ioapic.cold (STB_LOCAL)
ffffffff81073f80-ffffffff8107424b: mp_register_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int mp_register_ioapic(int id, u32 address, u32 gsi_base, struct ioapic_domain_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:2811
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_ioapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_ioapic
  - arch/x86/kernel/mpparse.c:MP_ioapic_info
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
**Symbols:**

```
ffffffff81bc9613-ffffffff81bc9730: mp_register_ioapic.cold (STB_LOCAL)
ffffffff81074a30-ffffffff81074cfb: mp_register_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mp_register_ioapic(int id, u32 address, u32 gsi_base, struct ioapic_domain_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:2811
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_ioapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_ioapic
  - arch/x86/kernel/mpparse.c:MP_ioapic_info
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
**Symbols:**

```
ffffffff81c9e209-ffffffff81c9e27b: mp_register_ioapic.cold (STB_LOCAL)
ffffffff81081960-ffffffff81081f9b: mp_register_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mp_register_ioapic(int id, u32 address, u32 gsi_base, struct ioapic_domain_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:2825
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_ioapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_ioapic
  - arch/x86/kernel/mpparse.c:MP_ioapic_info
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
**Symbols:**

```
ffffffff81e4d6a8-ffffffff81e4d718: mp_register_ioapic.cold (STB_LOCAL)
ffffffff810914b0-ffffffff81091afc: mp_register_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mp_register_ioapic(int id, u32 address, u32 gsi_base, struct ioapic_domain_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a6120)
Location: arch/x86/kernel/apic/io_apic.c:2825
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_ioapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_ioapic
  - arch/x86/kernel/mpparse.c:check_physptr
  - arch/x86/kernel/mpparse.c:construct_default_ISA_mptable
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
**Symbols:**

```
ffffffff810a6120-ffffffff810a68cd: mp_register_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mp_register_ioapic(int id, u32 address, u32 gsi_base, struct ioapic_domain_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a9320)
Location: arch/x86/kernel/apic/io_apic.c:2832
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_ioapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_ioapic
  - arch/x86/kernel/mpparse.c:check_physptr
  - arch/x86/kernel/mpparse.c:construct_default_ISA_mptable
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
**Symbols:**

```
ffffffff810a9320-ffffffff810a9abf: mp_register_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mp_register_ioapic(int id, u32 address, u32 gsi_base, struct ioapic_domain_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810b03b0)
Location: arch/x86/kernel/apic/io_apic.c:2828
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_ioapic
  - arch/x86/kernel/acpi/boot.c:acpi_parse_ioapic
  - arch/x86/kernel/mpparse.c:check_physptr
  - arch/x86/kernel/mpparse.c:construct_default_ISA_mptable
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
**Symbols:**

```
ffffffff810b03b0-ffffffff810b0b4f: mp_register_ioapic (STB_GLOBAL)
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
int mp_register_ioapic(int id, u32 address, u32 gsi_base, struct ioapic_domain_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:2799
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_parse_ioapic
  - arch/x86/kernel/mpparse.c:MP_ioapic_info
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/platform/sfi/sfi.c:sfi_parse_ioapic
```
**Symbols:**

```
ffffffff8106bae9-ffffffff8106bc2b: mp_register_ioapic.cold (STB_LOCAL)
ffffffff8106b1a0-ffffffff8106b5fb: mp_register_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int mp_register_ioapic(int id, u32 address, u32 gsi_base, struct ioapic_domain_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:2793
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_parse_ioapic
  - arch/x86/kernel/mpparse.c:MP_ioapic_info
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/platform/sfi/sfi.c:sfi_parse_ioapic
```
**Symbols:**

```
ffffffff8105be19-ffffffff8105bf4d: mp_register_ioapic.cold (STB_LOCAL)
ffffffff8105b4e0-ffffffff8105b92d: mp_register_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int mp_register_ioapic(int id, u32 address, u32 gsi_base, struct ioapic_domain_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:2793
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_parse_ioapic
  - arch/x86/kernel/mpparse.c:MP_ioapic_info
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/platform/sfi/sfi.c:sfi_parse_ioapic
```
**Symbols:**

```
ffffffff8106bf99-ffffffff8106c0db: mp_register_ioapic.cold (STB_LOCAL)
ffffffff8106b650-ffffffff8106baab: mp_register_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int mp_register_ioapic(int id, u32 address, u32 gsi_base, struct ioapic_domain_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:2793
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_parse_ioapic
  - arch/x86/kernel/mpparse.c:MP_ioapic_info
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/platform/sfi/sfi.c:sfi_parse_ioapic
```
**Symbols:**

```
ffffffff8106d699-ffffffff8106d7db: mp_register_ioapic.cold (STB_LOCAL)
ffffffff8106cd50-ffffffff8106d1ab: mp_register_ioapic (STB_GLOBAL)
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
