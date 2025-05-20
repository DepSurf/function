# Function: <code>mp_unregister_ioapic</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mp_unregister_ioapic(u32 gsi_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810582f0)
Location: arch/x86/kernel/apic/io_apic.c:2821
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unregister_ioapic
```
**Symbols:**

```
ffffffff810582f0-ffffffff81058447: mp_unregister_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mp_unregister_ioapic(u32 gsi_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81058620)
Location: arch/x86/kernel/apic/io_apic.c:2818
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unregister_ioapic
```
**Symbols:**

```
ffffffff81058620-ffffffff81058778: mp_unregister_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mp_unregister_ioapic(u32 gsi_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105b3b0)
Location: arch/x86/kernel/apic/io_apic.c:2819
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unregister_ioapic
```
**Symbols:**

```
ffffffff8105b3b0-ffffffff8105b508: mp_unregister_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mp_unregister_ioapic(u32 gsi_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105a920)
Location: arch/x86/kernel/apic/io_apic.c:2817
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unregister_ioapic
```
**Symbols:**

```
ffffffff8105a920-ffffffff8105aa75: mp_unregister_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mp_unregister_ioapic(u32 gsi_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105ee60)
Location: arch/x86/kernel/apic/io_apic.c:2827
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unregister_ioapic
```
**Symbols:**

```
ffffffff8105ee60-ffffffff8105efbb: mp_unregister_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int mp_unregister_ioapic(u32 gsi_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:2820
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unregister_ioapic
```
**Symbols:**

```
ffffffff810622f1-ffffffff8106230c: mp_unregister_ioapic.cold.28 (STB_LOCAL)
ffffffff81061d20-ffffffff81061e6a: mp_unregister_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int mp_unregister_ioapic(u32 gsi_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:2821
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unregister_ioapic
```
**Symbols:**

```
ffffffff81067fe6-ffffffff81068001: mp_unregister_ioapic.cold.26 (STB_LOCAL)
ffffffff81067a00-ffffffff81067b4a: mp_unregister_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int mp_unregister_ioapic(u32 gsi_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:2884
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unregister_ioapic
```
**Symbols:**

```
ffffffff8106b7d7-ffffffff8106b7f3: mp_unregister_ioapic.cold (STB_LOCAL)
ffffffff8106b170-ffffffff8106b2cc: mp_unregister_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int mp_unregister_ioapic(u32 gsi_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:2887
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unregister_ioapic
```
**Symbols:**

```
ffffffff8106c13b-ffffffff8106c157: mp_unregister_ioapic.cold (STB_LOCAL)
ffffffff8106bb10-ffffffff8106bc6c: mp_unregister_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int mp_unregister_ioapic(u32 gsi_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:2880
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unregister_ioapic
```
**Symbols:**

```
ffffffff8107345d-ffffffff81073479: mp_unregister_ioapic.cold (STB_LOCAL)
ffffffff81072df0-ffffffff81072f6a: mp_unregister_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int mp_unregister_ioapic(u32 gsi_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:2903
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unregister_ioapic
```
**Symbols:**

```
ffffffff81bd7592-ffffffff81bd75ae: mp_unregister_ioapic.cold (STB_LOCAL)
ffffffff81074250-ffffffff810743ca: mp_unregister_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int mp_unregister_ioapic(u32 gsi_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:2905
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unregister_ioapic
```
**Symbols:**

```
ffffffff81bc9730-ffffffff81bc974c: mp_unregister_ioapic.cold (STB_LOCAL)
ffffffff81074d00-ffffffff81074e7a: mp_unregister_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mp_unregister_ioapic(u32 gsi_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:2905
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unregister_ioapic
```
**Symbols:**

```
ffffffff81c9e27b-ffffffff81c9e297: mp_unregister_ioapic.cold (STB_LOCAL)
ffffffff81081fa0-ffffffff810822f3: mp_unregister_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mp_unregister_ioapic(u32 gsi_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:2919
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unregister_ioapic
```
**Symbols:**

```
ffffffff81e4d718-ffffffff81e4d734: mp_unregister_ioapic.cold (STB_LOCAL)
ffffffff81091b00-ffffffff81091e98: mp_unregister_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mp_unregister_ioapic(u32 gsi_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a68e0)
Location: arch/x86/kernel/apic/io_apic.c:2919
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unregister_ioapic
```
**Symbols:**

```
ffffffff810a68e0-ffffffff810a6ca2: mp_unregister_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mp_unregister_ioapic(u32 gsi_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a9ad0)
Location: arch/x86/kernel/apic/io_apic.c:2926
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unregister_ioapic
```
**Symbols:**

```
ffffffff810a9ad0-ffffffff810a9f00: mp_unregister_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mp_unregister_ioapic(u32 gsi_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810b0b60)
Location: arch/x86/kernel/apic/io_apic.c:2922
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unregister_ioapic
```
**Symbols:**

```
ffffffff810b0b60-ffffffff810b0f90: mp_unregister_ioapic (STB_GLOBAL)
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
int mp_unregister_ioapic(u32 gsi_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:2893
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unregister_ioapic
```
**Symbols:**

```
ffffffff8106bc2b-ffffffff8106bc47: mp_unregister_ioapic.cold (STB_LOCAL)
ffffffff8106b600-ffffffff8106b75c: mp_unregister_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int mp_unregister_ioapic(u32 gsi_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:2887
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unregister_ioapic
```
**Symbols:**

```
ffffffff8105bf4d-ffffffff8105bf69: mp_unregister_ioapic.cold (STB_LOCAL)
ffffffff8105b930-ffffffff8105ba85: mp_unregister_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int mp_unregister_ioapic(u32 gsi_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:2887
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unregister_ioapic
```
**Symbols:**

```
ffffffff8106c0db-ffffffff8106c0f7: mp_unregister_ioapic.cold (STB_LOCAL)
ffffffff8106bab0-ffffffff8106bc0c: mp_unregister_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int mp_unregister_ioapic(u32 gsi_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:2887
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unregister_ioapic
```
**Symbols:**

```
ffffffff8106d7db-ffffffff8106d7f7: mp_unregister_ioapic.cold (STB_LOCAL)
ffffffff8106d1b0-ffffffff8106d30c: mp_unregister_ioapic (STB_GLOBAL)
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
