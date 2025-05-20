# Function: <code>get_madt_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct acpi_table_madt *get_madt_table();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff81482730)
Location: drivers/acpi/processor_core.c:19
Inline: False
Direct callers:
  - drivers/acpi/processor_core.c:acpi_get_phys_id
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
```
**Symbols:**

```
ffffffff81482730-ffffffff8148277d: get_madt_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct acpi_table_madt *get_madt_table();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff814d1222)
Location: drivers/acpi/processor_core.c:19
Inline: False
Direct callers:
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
```
**Symbols:**

```
ffffffff814d1222-ffffffff814d126f: get_madt_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct acpi_table_madt *get_madt_table();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff814f3314)
Location: drivers/acpi/processor_core.c:19
Inline: False
Direct callers:
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
  - drivers/acpi/processor_core.c:__acpi_get_phys_id
```
**Symbols:**

```
ffffffff814f3314-ffffffff814f3361: get_madt_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct acpi_table_madt *get_madt_table();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff81501230)
Location: drivers/acpi/processor_core.c:19
Inline: False
Direct callers:
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
```
**Symbols:**

```
ffffffff81501230-ffffffff8150128a: get_madt_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct acpi_table_madt *get_madt_table();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff81543660)
Location: drivers/acpi/processor_core.c:19
Inline: False
Direct callers:
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
```
**Symbols:**

```
ffffffff81543660-ffffffff815436ba: get_madt_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct acpi_table_madt *get_madt_table();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff815795c0)
Location: drivers/acpi/processor_core.c:19
Inline: False
Direct callers:
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
```
**Symbols:**

```
ffffffff815795c0-ffffffff8157961a: get_madt_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct acpi_table_madt *get_madt_table();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff81591240)
Location: drivers/acpi/processor_core.c:19
Inline: False
Direct callers:
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
```
**Symbols:**

```
ffffffff81591240-ffffffff8159129a: get_madt_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct acpi_table_madt *get_madt_table();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff815c20a0)
Location: drivers/acpi/processor_core.c:20
Inline: False
Direct callers:
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
```
**Symbols:**

```
ffffffff815c20a0-ffffffff815c20fa: get_madt_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct acpi_table_madt *get_madt_table();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff815e3380)
Location: drivers/acpi/processor_core.c:20
Inline: False
Direct callers:
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
```
**Symbols:**

```
ffffffff815e3380-ffffffff815e33da: get_madt_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff8168eb58)
Location: drivers/acpi/processor_core.c:20
Inline: True
Inline callers:
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
  - drivers/acpi/processor_core.c:acpi_get_cpuid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff816ac828)
Location: drivers/acpi/processor_core.c:17
Inline: True
Inline callers:
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
  - drivers/acpi/processor_core.c:acpi_get_cpuid
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
In drivers/acpi/processor_core.c (ffffffff8168ee78)
Location: drivers/acpi/processor_core.c:17
Inline: True
Inline callers:
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
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
In drivers/acpi/processor_core.c (ffffffff817048b8)
Location: drivers/acpi/processor_core.c:17
Inline: True
Inline callers:
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
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
In drivers/acpi/processor_core.c (ffffffff818329d4)
Location: drivers/acpi/processor_core.c:17
Inline: True
Inline callers:
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
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
In drivers/acpi/processor_core.c (ffffffff819662b4)
Location: drivers/acpi/processor_core.c:17
Inline: True
Inline callers:
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
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
In drivers/acpi/processor_core.c (ffffffff819ac844)
Location: drivers/acpi/processor_core.c:17
Inline: True
Inline callers:
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
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
In drivers/acpi/processor_core.c (ffffffff819f6b74)
Location: drivers/acpi/processor_core.c:17
Inline: True
Inline callers:
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
  - drivers/acpi/processor_core.c:acpi_get_cpuid
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffff80001076fb68)
Location: drivers/acpi/processor_core.c:20
Inline: True
```
</details>
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
struct acpi_table_madt *get_madt_table();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff815d52c0)
Location: drivers/acpi/processor_core.c:20
Inline: False
Direct callers:
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
```
**Symbols:**

```
ffffffff815d52c0-ffffffff815d531a: get_madt_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct acpi_table_madt *get_madt_table();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff815bee80)
Location: drivers/acpi/processor_core.c:20
Inline: False
Direct callers:
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
```
**Symbols:**

```
ffffffff815bee80-ffffffff815beeda: get_madt_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct acpi_table_madt *get_madt_table();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff815d7660)
Location: drivers/acpi/processor_core.c:20
Inline: False
Direct callers:
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
```
**Symbols:**

```
ffffffff815d7660-ffffffff815d76ba: get_madt_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct acpi_table_madt *get_madt_table();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff815f1520)
Location: drivers/acpi/processor_core.c:20
Inline: False
Direct callers:
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
```
**Symbols:**

```
ffffffff815f1520-ffffffff815f157a: get_madt_table (STB_LOCAL)
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
