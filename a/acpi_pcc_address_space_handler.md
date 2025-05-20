# Function: <code>acpi_pcc_address_space_handler</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
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
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_pcc_address_space_handler(u32 function, acpi_physical_address addr, u32 bits, acpi_integer *value, void *handler_context, void *region_context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_pcc.c (0)
Location: drivers/acpi/acpi_pcc.c:83
Inline: False
```
**Symbols:**

```
ffffffff81842f20-ffffffff81842fe1: acpi_pcc_address_space_handler (STB_LOCAL)
ffffffff81eb8f15-ffffffff81eb8f2a: acpi_pcc_address_space_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_pcc_address_space_handler(u32 function, acpi_physical_address addr, u32 bits, acpi_integer *value, void *handler_context, void *region_context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_pcc.c (ffffffff8197a0e0)
Location: drivers/acpi/acpi_pcc.c:105
Inline: False
```
**Symbols:**

```
ffffffff8197a0e0-ffffffff8197a19a: acpi_pcc_address_space_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_pcc_address_space_handler(u32 function, acpi_physical_address addr, u32 bits, acpi_integer *value, void *handler_context, void *region_context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_pcc.c (ffffffff819c0b70)
Location: drivers/acpi/acpi_pcc.c:105
Inline: False
```
**Symbols:**

```
ffffffff819c0b70-ffffffff819c0c2a: acpi_pcc_address_space_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_pcc_address_space_handler(u32 function, acpi_physical_address addr, u32 bits, acpi_integer *value, void *handler_context, void *region_context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_pcc.c (ffffffff81a0b560)
Location: drivers/acpi/acpi_pcc.c:105
Inline: False
```
**Symbols:**

```
ffffffff81a0b560-ffffffff81a0b61a: acpi_pcc_address_space_handler (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
