# Function: <code>generic_processor_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int generic_processor_info(int apicid, int version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81054440)
Location: arch/x86/kernel/apic/apic.c:1991
Inline: False
Direct callers:
  - arch/x86/platform/sfi/sfi.c:sfi_parse_cpus
```
**Symbols:**

```
ffffffff81054440-ffffffff810546e4: generic_processor_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int generic_processor_info(int apicid, int version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810545d0)
Location: arch/x86/kernel/apic/apic.c:2030
Inline: False
Direct callers:
  - arch/x86/platform/sfi/sfi.c:sfi_parse_cpus
```
**Symbols:**

```
ffffffff810545d0-ffffffff8105487a: generic_processor_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int generic_processor_info(int apicid, int version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81057640)
Location: arch/x86/kernel/apic/apic.c:2200
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/platform/sfi/sfi.c:sfi_parse_cpus
```
**Symbols:**

```
ffffffff81057640-ffffffff81057655: generic_processor_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int generic_processor_info(int apicid, int version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81056a20)
Location: arch/x86/kernel/apic/apic.c:2150
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/platform/sfi/sfi.c:sfi_parse_cpus
```
**Symbols:**

```
ffffffff81056a20-ffffffff81056d80: generic_processor_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int generic_processor_info(int apicid, int version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8105a780)
Location: arch/x86/kernel/apic/apic.c:2212
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/platform/sfi/sfi.c:sfi_parse_cpus
```
**Symbols:**

```
ffffffff8105a780-ffffffff8105aaea: generic_processor_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int generic_processor_info(int apicid, int version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:2242
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/mpparse.c:MP_processor_info
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/platform/sfi/sfi.c:sfi_parse_cpus
```
**Symbols:**

```
ffffffff8105db22-ffffffff8105dbe6: generic_processor_info.cold.25 (STB_LOCAL)
ffffffff8105d670-ffffffff8105d918: generic_processor_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int generic_processor_info(int apicid, int version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:2250
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/mpparse.c:MP_processor_info
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/platform/sfi/sfi.c:sfi_parse_cpus
```
**Symbols:**

```
ffffffff810637b3-ffffffff81063877: generic_processor_info.cold.26 (STB_LOCAL)
ffffffff81063300-ffffffff810635a8: generic_processor_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int generic_processor_info(int apicid, int version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:2339
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/mpparse.c:MP_processor_info
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/platform/sfi/sfi.c:sfi_parse_cpus
```
**Symbols:**

```
ffffffff81066e70-ffffffff81066f37: generic_processor_info.cold (STB_LOCAL)
ffffffff810669a0-ffffffff81066c2a: generic_processor_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int generic_processor_info(int apicid, int version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:2396
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/mpparse.c:MP_processor_info
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/platform/sfi/sfi.c:sfi_parse_cpus
```
**Symbols:**

```
ffffffff810674e5-ffffffff810675ac: generic_processor_info.cold (STB_LOCAL)
ffffffff81067010-ffffffff8106729a: generic_processor_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int generic_processor_info(int apicid, int version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:2357
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_lapic
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/mpparse.c:MP_processor_info
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/platform/sfi/sfi.c:sfi_parse_cpus
```
**Symbols:**

```
ffffffff8106e239-ffffffff8106e300: generic_processor_info.cold (STB_LOCAL)
ffffffff8106dc20-ffffffff8106dea8: generic_processor_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int generic_processor_info(int apicid, int version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:2388
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_lapic
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/mpparse.c:MP_processor_info
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/platform/sfi/sfi.c:sfi_parse_cpus
```
**Symbols:**

```
ffffffff81bd6f93-ffffffff81bd705e: generic_processor_info.cold (STB_LOCAL)
ffffffff8106f3c0-ffffffff8106f642: generic_processor_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int generic_processor_info(int apicid, int version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:2396
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_lapic
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/mpparse.c:MP_processor_info
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
**Symbols:**

```
ffffffff81bc914d-ffffffff81bc9214: generic_processor_info.cold (STB_LOCAL)
ffffffff8106fef0-ffffffff81070178: generic_processor_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int generic_processor_info(int apicid, int version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:2393
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_lapic
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/mpparse.c:MP_processor_info
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
**Symbols:**

```
ffffffff81c9dbcc-ffffffff81c9dcaf: generic_processor_info.cold (STB_LOCAL)
ffffffff8107b960-ffffffff8107bc93: generic_processor_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int generic_processor_info(int apicid, int version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:2401
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_lapic
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/mpparse.c:MP_processor_info
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
**Symbols:**

```
ffffffff81e4d052-ffffffff81e4d130: generic_processor_info.cold (STB_LOCAL)
ffffffff8108ab40-ffffffff8108aec9: generic_processor_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int generic_processor_info(int apicid, int version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:2435
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_lapic
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/mpparse.c:MP_processor_info
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
**Symbols:**

```
ffffffff82053c74-ffffffff82053c8e: generic_processor_info.cold (STB_LOCAL)
ffffffff8109ec40-ffffffff8109f082: generic_processor_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int generic_processor_info(int apicid, int version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:2449
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_lapic
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/mpparse.c:MP_processor_info
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
**Symbols:**

```
ffffffff820d226b-ffffffff820d2285: generic_processor_info.cold (STB_LOCAL)
ffffffff810a1bb0-ffffffff810a201b: generic_processor_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int generic_processor_info(int apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:2415
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_lapic
  - arch/x86/kernel/mpparse.c:MP_processor_info
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
**Symbols:**

```
ffffffff821acf0b-ffffffff821acf1f: generic_processor_info.cold (STB_LOCAL)
ffffffff810a8c00-ffffffff810a8dfd: generic_processor_info (STB_GLOBAL)
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
int generic_processor_info(int apicid, int version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:2396
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/mpparse.c:MP_processor_info
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/platform/sfi/sfi.c:sfi_parse_cpus
```
**Symbols:**

```
ffffffff81066fd5-ffffffff8106709c: generic_processor_info.cold (STB_LOCAL)
ffffffff81066b00-ffffffff81066d8a: generic_processor_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int generic_processor_info(int apicid, int version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:2396
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/mpparse.c:MP_processor_info
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/platform/sfi/sfi.c:sfi_parse_cpus
```
**Symbols:**

```
ffffffff81057392-ffffffff81057459: generic_processor_info.cold (STB_LOCAL)
ffffffff81056ed0-ffffffff8105715a: generic_processor_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int generic_processor_info(int apicid, int version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:2396
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/mpparse.c:MP_processor_info
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/platform/sfi/sfi.c:sfi_parse_cpus
```
**Symbols:**

```
ffffffff81067485-ffffffff8106754c: generic_processor_info.cold (STB_LOCAL)
ffffffff81066fb0-ffffffff8106723a: generic_processor_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int generic_processor_info(int apicid, int version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:2396
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/mpparse.c:MP_processor_info
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
  - arch/x86/platform/sfi/sfi.c:sfi_parse_cpus
```
**Symbols:**

```
ffffffff81068a65-ffffffff81068b2c: generic_processor_info.cold (STB_LOCAL)
ffffffff81068590-ffffffff8106881a: generic_processor_info (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int version</code>
</li>
</ul>
</details>
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
