# Function: <code>acpi_parse_madt_ioapic_entries</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff81f6e71b)
Location: arch/x86/kernel/acpi/boot.c:1115
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff81f96b29)
Location: arch/x86/kernel/acpi/boot.c:1131
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff81fd2027)
Location: arch/x86/kernel/acpi/boot.c:1128
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff820b2c2e)
Location: arch/x86/kernel/acpi/boot.c:1144
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff826b9468)
Location: arch/x86/kernel/acpi/boot.c:1167
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff826e31c8)
Location: arch/x86/kernel/acpi/boot.c:1173
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff82899b2e)
Location: arch/x86/kernel/acpi/boot.c:1175
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff828b183b)
Location: arch/x86/kernel/acpi/boot.c:1161
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff828b4c8a)
Location: arch/x86/kernel/acpi/boot.c:1161
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int acpi_parse_madt_ioapic_entries();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff82cd9b5b)
Location: arch/x86/kernel/acpi/boot.c:1162
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_process_madt
```
**Symbols:**

```
ffffffff82cd9b5b-ffffffff82cd9c88: acpi_parse_madt_ioapic_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int acpi_parse_madt_ioapic_entries();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff82fc60b0)
Location: arch/x86/kernel/acpi/boot.c:1162
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_process_madt
```
**Symbols:**

```
ffffffff82fc60b0-ffffffff82fc61dd: acpi_parse_madt_ioapic_entries (STB_LOCAL)
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
In arch/x86/kernel/acpi/boot.c (ffffffff831d0bf6)
Location: arch/x86/kernel/acpi/boot.c:1162
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff832b3141)
Location: arch/x86/kernel/acpi/boot.c:1150
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff834646f4)
Location: arch/x86/kernel/acpi/boot.c:1241
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
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
In arch/x86/kernel/acpi/boot.c (ffffffff83e8768b)
Location: arch/x86/kernel/acpi/boot.c:1254
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
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
In arch/x86/kernel/acpi/boot.c (ffffffff836aac2b)
Location: arch/x86/kernel/acpi/boot.c:1263
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
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
In arch/x86/kernel/acpi/boot.c (ffffffff838db3d5)
Location: arch/x86/kernel/acpi/boot.c:1258
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff828a2ca9)
Location: arch/x86/kernel/acpi/boot.c:1161
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff8289adeb)
Location: arch/x86/kernel/acpi/boot.c:1161
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff828b5ba6)
Location: arch/x86/kernel/acpi/boot.c:1161
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff828b5c8d)
Location: arch/x86/kernel/acpi/boot.c:1161
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
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
</ul>
