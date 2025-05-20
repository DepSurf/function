# Function: <code>arch_apei_flush_tlb_one</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void arch_apei_flush_tlb_one(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/apei.c (ffffffff8104fe60)
Location: arch/x86/kernel/acpi/apei.c:59
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
```
**Symbols:**

```
ffffffff8104fe60-ffffffff8104fe72: arch_apei_flush_tlb_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void arch_apei_flush_tlb_one(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/apei.c (ffffffff8104ffe0)
Location: arch/x86/kernel/acpi/apei.c:59
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
```
**Symbols:**

```
ffffffff8104ffe0-ffffffff8104fff2: arch_apei_flush_tlb_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void arch_apei_flush_tlb_one(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/apei.c (ffffffff81052800)
Location: arch/x86/kernel/acpi/apei.c:56
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
```
**Symbols:**

```
ffffffff81052800-ffffffff81052812: arch_apei_flush_tlb_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void arch_apei_flush_tlb_one(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/apei.c (ffffffff81052320)
Location: arch/x86/kernel/acpi/apei.c:56
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
```
**Symbols:**

```
ffffffff81052320-ffffffff81052332: arch_apei_flush_tlb_one (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
