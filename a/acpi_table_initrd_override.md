# Function: <code>acpi_table_initrd_override</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff814c7c8c)
Location: drivers/acpi/tables.c:597
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_os_physical_table_override
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
In drivers/acpi/tables.c (ffffffff814e9b9c)
Location: drivers/acpi/tables.c:596
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_os_physical_table_override
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
In drivers/acpi/tables.c (ffffffff814f5845)
Location: drivers/acpi/tables.c:585
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_os_physical_table_override
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
In drivers/acpi/tables.c (ffffffff815360d5)
Location: drivers/acpi/tables.c:585
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_os_physical_table_override
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
In drivers/acpi/tables.c (ffffffff8156bb05)
Location: drivers/acpi/tables.c:591
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_os_physical_table_override
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
In drivers/acpi/tables.c (ffffffff815836d5)
Location: drivers/acpi/tables.c:590
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_os_physical_table_override
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
In drivers/acpi/tables.c (ffffffff815b42d5)
Location: drivers/acpi/tables.c:637
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_os_physical_table_override
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
In drivers/acpi/tables.c (ffffffff815d5515)
Location: drivers/acpi/tables.c:638
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_os_physical_table_override
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_table_initrd_override(struct acpi_table_header *existing_table, acpi_physical_address *address, u32 *length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/tables.c (0)
Location: drivers/acpi/tables.c:638
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_os_physical_table_override
```
**Symbols:**

```
ffffffff8167ef50-ffffffff8167f073: acpi_table_initrd_override (STB_LOCAL)
ffffffff8167f305-ffffffff8167f34b: acpi_table_initrd_override.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_table_initrd_override(struct acpi_table_header *existing_table, acpi_physical_address *address, u32 *length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/tables.c (0)
Location: drivers/acpi/tables.c:627
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_os_physical_table_override
```
**Symbols:**

```
ffffffff8169dbe0-ffffffff8169dd03: acpi_table_initrd_override (STB_LOCAL)
ffffffff81c00640-ffffffff81c00686: acpi_table_initrd_override.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_table_initrd_override(struct acpi_table_header *existing_table, acpi_physical_address *address, u32 *length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/tables.c (0)
Location: drivers/acpi/tables.c:627
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_os_physical_table_override
```
**Symbols:**

```
ffffffff81680930-ffffffff81680a53: acpi_table_initrd_override (STB_LOCAL)
ffffffff81bf2126-ffffffff81bf2169: acpi_table_initrd_override.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_table_initrd_override(struct acpi_table_header *existing_table, acpi_physical_address *address, u32 *length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/tables.c (0)
Location: drivers/acpi/tables.c:638
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_os_physical_table_override
```
**Symbols:**

```
ffffffff816f58e0-ffffffff816f5a03: acpi_table_initrd_override (STB_LOCAL)
ffffffff81ceea78-ffffffff81ceeabb: acpi_table_initrd_override.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_table_initrd_override(struct acpi_table_header *existing_table, acpi_physical_address *address, u32 *length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/tables.c (0)
Location: drivers/acpi/tables.c:683
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_os_physical_table_override
```
**Symbols:**

```
ffffffff81822210-ffffffff8182233d: acpi_table_initrd_override (STB_LOCAL)
ffffffff81eb618f-ffffffff81eb61d3: acpi_table_initrd_override.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_table_initrd_override(struct acpi_table_header *existing_table, acpi_physical_address *address, u32 *length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff81952fa0)
Location: drivers/acpi/tables.c:693
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_os_physical_table_override
```
**Symbols:**

```
ffffffff81952fa0-ffffffff8195310d: acpi_table_initrd_override (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_table_initrd_override(struct acpi_table_header *existing_table, acpi_physical_address *address, u32 *length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff819993a0)
Location: drivers/acpi/tables.c:704
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_os_physical_table_override
```
**Symbols:**

```
ffffffff819993a0-ffffffff8199950d: acpi_table_initrd_override (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_table_initrd_override(struct acpi_table_header *existing_table, acpi_physical_address *address, u32 *length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff819e1af0)
Location: drivers/acpi/tables.c:532
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_os_physical_table_override
```
**Symbols:**

```
ffffffff819e1af0-ffffffff819e1c5d: acpi_table_initrd_override (STB_LOCAL)
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
In drivers/acpi/tables.c (ffff800010762b80)
Location: drivers/acpi/tables.c:638
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_os_physical_table_override
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff815c9265)
Location: drivers/acpi/tables.c:638
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_os_physical_table_override
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
In drivers/acpi/tables.c (ffffffff815b2445)
Location: drivers/acpi/tables.c:745
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_os_physical_table_override
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
In drivers/acpi/tables.c (ffffffff815c97f5)
Location: drivers/acpi/tables.c:638
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_os_physical_table_override
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
In drivers/acpi/tables.c (ffffffff815e3655)
Location: drivers/acpi/tables.c:638
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_os_physical_table_override
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
