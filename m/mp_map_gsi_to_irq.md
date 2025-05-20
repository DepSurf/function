# Function: <code>mp_map_gsi_to_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mp_map_gsi_to_irq(u32 gsi, unsigned int flags, struct irq_alloc_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81057cb0)
Location: arch/x86/kernel/apic/io_apic.c:1104
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unregister_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
```
**Symbols:**

```
ffffffff81057cb0-ffffffff81057d6e: mp_map_gsi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mp_map_gsi_to_irq(u32 gsi, unsigned int flags, struct irq_alloc_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81057fc0)
Location: arch/x86/kernel/apic/io_apic.c:1105
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unregister_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
```
**Symbols:**

```
ffffffff81057fc0-ffffffff8105807e: mp_map_gsi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mp_map_gsi_to_irq(u32 gsi, unsigned int flags, struct irq_alloc_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105ad50)
Location: arch/x86/kernel/apic/io_apic.c:1104
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unregister_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
```
**Symbols:**

```
ffffffff8105ad50-ffffffff8105ae0e: mp_map_gsi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mp_map_gsi_to_irq(u32 gsi, unsigned int flags, struct irq_alloc_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105a310)
Location: arch/x86/kernel/apic/io_apic.c:1104
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unregister_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
```
**Symbols:**

```
ffffffff8105a310-ffffffff8105a3ce: mp_map_gsi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mp_map_gsi_to_irq(u32 gsi, unsigned int flags, struct irq_alloc_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105e810)
Location: arch/x86/kernel/apic/io_apic.c:1106
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unregister_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
```
**Symbols:**

```
ffffffff8105e810-ffffffff8105e8ce: mp_map_gsi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mp_map_gsi_to_irq(u32 gsi, unsigned int flags, struct irq_alloc_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810617c0)
Location: arch/x86/kernel/apic/io_apic.c:1107
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unregister_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
```
**Symbols:**

```
ffffffff810617c0-ffffffff8106187d: mp_map_gsi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mp_map_gsi_to_irq(u32 gsi, unsigned int flags, struct irq_alloc_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810674a0)
Location: arch/x86/kernel/apic/io_apic.c:1107
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unregister_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
```
**Symbols:**

```
ffffffff810674a0-ffffffff8106755d: mp_map_gsi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int mp_map_gsi_to_irq(u32 gsi, unsigned int flags, struct irq_alloc_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106ac40)
Location: arch/x86/kernel/apic/io_apic.c:1110
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unregister_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
```
**Symbols:**

```
ffffffff8106ac40-ffffffff8106ad01: mp_map_gsi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mp_map_gsi_to_irq(u32 gsi, unsigned int flags, struct irq_alloc_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106b5e0)
Location: arch/x86/kernel/apic/io_apic.c:1110
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unregister_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
```
**Symbols:**

```
ffffffff8106b5e0-ffffffff8106b6a1: mp_map_gsi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int mp_map_gsi_to_irq(u32 gsi, unsigned int flags, struct irq_alloc_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:1097
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unregister_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
```
**Symbols:**

```
ffffffff81073327-ffffffff81073340: mp_map_gsi_to_irq.cold (STB_LOCAL)
ffffffff81072a80-ffffffff81072b1b: mp_map_gsi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int mp_map_gsi_to_irq(u32 gsi, unsigned int flags, struct irq_alloc_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:1106
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unregister_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
```
**Symbols:**

```
ffffffff81bd745c-ffffffff81bd7475: mp_map_gsi_to_irq.cold (STB_LOCAL)
ffffffff81073ee0-ffffffff81073f7b: mp_map_gsi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int mp_map_gsi_to_irq(u32 gsi, unsigned int flags, struct irq_alloc_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:1106
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unregister_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
```
**Symbols:**

```
ffffffff81bc95fa-ffffffff81bc9613: mp_map_gsi_to_irq.cold (STB_LOCAL)
ffffffff81074980-ffffffff81074a25: mp_map_gsi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mp_map_gsi_to_irq(u32 gsi, unsigned int flags, struct irq_alloc_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:1106
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unregister_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
```
**Symbols:**

```
ffffffff81c9e1c4-ffffffff81c9e1dd: mp_map_gsi_to_irq.cold (STB_LOCAL)
ffffffff81081560-ffffffff8108166a: mp_map_gsi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mp_map_gsi_to_irq(u32 gsi, unsigned int flags, struct irq_alloc_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:1107
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unregister_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
```
**Symbols:**

```
ffffffff81e4d663-ffffffff81e4d67c: mp_map_gsi_to_irq.cold (STB_LOCAL)
ffffffff81091040-ffffffff81091149: mp_map_gsi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mp_map_gsi_to_irq(u32 gsi, unsigned int flags, struct irq_alloc_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a5c10)
Location: arch/x86/kernel/apic/io_apic.c:1107
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unregister_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
```
**Symbols:**

```
ffffffff810a5c10-ffffffff810a5d3c: mp_map_gsi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mp_map_gsi_to_irq(u32 gsi, unsigned int flags, struct irq_alloc_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a8e10)
Location: arch/x86/kernel/apic/io_apic.c:1108
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unregister_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
```
**Symbols:**

```
ffffffff810a8e10-ffffffff810a8f42: mp_map_gsi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mp_map_gsi_to_irq(u32 gsi, unsigned int flags, struct irq_alloc_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810afea0)
Location: arch/x86/kernel/apic/io_apic.c:1108
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unregister_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
```
**Symbols:**

```
ffffffff810afea0-ffffffff810affd2: mp_map_gsi_to_irq (STB_GLOBAL)
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
int mp_map_gsi_to_irq(u32 gsi, unsigned int flags, struct irq_alloc_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106b0d0)
Location: arch/x86/kernel/apic/io_apic.c:1110
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unregister_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
```
**Symbols:**

```
ffffffff8106b0d0-ffffffff8106b191: mp_map_gsi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int mp_map_gsi_to_irq(u32 gsi, unsigned int flags, struct irq_alloc_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105b410)
Location: arch/x86/kernel/apic/io_apic.c:1110
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unregister_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
```
**Symbols:**

```
ffffffff8105b410-ffffffff8105b4d1: mp_map_gsi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mp_map_gsi_to_irq(u32 gsi, unsigned int flags, struct irq_alloc_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106b580)
Location: arch/x86/kernel/apic/io_apic.c:1110
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unregister_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
```
**Symbols:**

```
ffffffff8106b580-ffffffff8106b641: mp_map_gsi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mp_map_gsi_to_irq(u32 gsi, unsigned int flags, struct irq_alloc_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106cc80)
Location: arch/x86/kernel/apic/io_apic.c:1110
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unregister_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
```
**Symbols:**

```
ffffffff8106cc80-ffffffff8106cd41: mp_map_gsi_to_irq (STB_GLOBAL)
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
