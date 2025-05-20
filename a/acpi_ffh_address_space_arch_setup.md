# Function: <code>acpi_ffh_address_space_arch_setup</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int acpi_ffh_address_space_arch_setup(void *handler_ctxt, void **region_ctxt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_ffh.c (ffffffff8197a340)
Location: drivers/acpi/acpi_ffh.c:16
Inline: True
Direct callers:
  - drivers/acpi/acpi_ffh.c:acpi_ffh_address_space_setup
```
**Symbols:**

```
ffffffff8197a340-ffffffff8197a354: acpi_ffh_address_space_arch_setup (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int acpi_ffh_address_space_arch_setup(void *handler_ctxt, void **region_ctxt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_ffh.c (ffffffff819c0dd0)
Location: drivers/acpi/acpi_ffh.c:14
Inline: True
Direct callers:
  - drivers/acpi/acpi_ffh.c:acpi_ffh_address_space_setup
```
**Symbols:**

```
ffffffff819c0dd0-ffffffff819c0de4: acpi_ffh_address_space_arch_setup (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int acpi_ffh_address_space_arch_setup(void *handler_ctxt, void **region_ctxt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_ffh.c (ffffffff81a0b7f0)
Location: drivers/acpi/acpi_ffh.c:14
Inline: True
Direct callers:
  - drivers/acpi/acpi_ffh.c:acpi_ffh_address_space_setup
```
**Symbols:**

```
ffffffff81a0b7f0-ffffffff81a0b804: acpi_ffh_address_space_arch_setup (STB_WEAK)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
