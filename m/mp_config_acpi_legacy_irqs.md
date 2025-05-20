# Function: <code>mp_config_acpi_legacy_irqs</code>

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
In arch/x86/kernel/acpi/boot.c (ffffffff81f6e7fb)
Location: arch/x86/kernel/acpi/boot.c:1045
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
In arch/x86/kernel/acpi/boot.c (ffffffff81f96c12)
Location: arch/x86/kernel/acpi/boot.c:1061
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
In arch/x86/kernel/acpi/boot.c (ffffffff81fd2110)
Location: arch/x86/kernel/acpi/boot.c:1058
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
In arch/x86/kernel/acpi/boot.c (ffffffff820b2d1a)
Location: arch/x86/kernel/acpi/boot.c:1074
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
In arch/x86/kernel/acpi/boot.c (ffffffff826b9554)
Location: arch/x86/kernel/acpi/boot.c:1097
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
In arch/x86/kernel/acpi/boot.c (ffffffff826e32ab)
Location: arch/x86/kernel/acpi/boot.c:1103
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
In arch/x86/kernel/acpi/boot.c (ffffffff82899c11)
Location: arch/x86/kernel/acpi/boot.c:1105
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
In arch/x86/kernel/acpi/boot.c (ffffffff828b191e)
Location: arch/x86/kernel/acpi/boot.c:1091
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
In arch/x86/kernel/acpi/boot.c (ffffffff828b4d6d)
Location: arch/x86/kernel/acpi/boot.c:1091
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
void mp_config_acpi_legacy_irqs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff82cd9a0e)
Location: arch/x86/kernel/acpi/boot.c:1092
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_parse_madt_ioapic_entries
```
**Symbols:**

```
ffffffff82cd9a0e-ffffffff82cd9b5b: mp_config_acpi_legacy_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mp_config_acpi_legacy_irqs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff82fc5f63)
Location: arch/x86/kernel/acpi/boot.c:1092
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_parse_madt_ioapic_entries
```
**Symbols:**

```
ffffffff82fc5f63-ffffffff82fc60b0: mp_config_acpi_legacy_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mp_config_acpi_legacy_irqs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff831d0684)
Location: arch/x86/kernel/acpi/boot.c:1092
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
```
**Symbols:**

```
ffffffff831d0684-ffffffff831d07c9: mp_config_acpi_legacy_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mp_config_acpi_legacy_irqs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff832b2b7d)
Location: arch/x86/kernel/acpi/boot.c:1080
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
```
**Symbols:**

```
ffffffff832b2b7d-ffffffff832b2cf0: mp_config_acpi_legacy_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mp_config_acpi_legacy_irqs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff83463b4e)
Location: arch/x86/kernel/acpi/boot.c:1171
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
```
**Symbols:**

```
ffffffff83463b4e-ffffffff83463cd7: mp_config_acpi_legacy_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mp_config_acpi_legacy_irqs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff83e86750)
Location: arch/x86/kernel/acpi/boot.c:1184
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
```
**Symbols:**

```
ffffffff83e86750-ffffffff83e86947: mp_config_acpi_legacy_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mp_config_acpi_legacy_irqs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff836a9c90)
Location: arch/x86/kernel/acpi/boot.c:1193
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
```
**Symbols:**

```
ffffffff836a9c90-ffffffff836a9e87: mp_config_acpi_legacy_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mp_config_acpi_legacy_irqs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff838da430)
Location: arch/x86/kernel/acpi/boot.c:1188
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
```
**Symbols:**

```
ffffffff838da430-ffffffff838da627: mp_config_acpi_legacy_irqs (STB_LOCAL)
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
In arch/x86/kernel/acpi/boot.c (ffffffff828a2d8c)
Location: arch/x86/kernel/acpi/boot.c:1091
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
In arch/x86/kernel/acpi/boot.c (ffffffff8289aece)
Location: arch/x86/kernel/acpi/boot.c:1091
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
In arch/x86/kernel/acpi/boot.c (ffffffff828b5c89)
Location: arch/x86/kernel/acpi/boot.c:1091
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
In arch/x86/kernel/acpi/boot.c (ffffffff828b5d70)
Location: arch/x86/kernel/acpi/boot.c:1091
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
