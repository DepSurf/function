# Function: <code>acpi_scan_check_dep</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u32 acpi_scan_check_dep(acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff816a8470)
Location: drivers/acpi/scan.c:1879
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
```
**Symbols:**

```
ffffffff816a8470-ffffffff816a8700: acpi_scan_check_dep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 acpi_scan_check_dep(acpi_handle handle, bool check_dep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8168ab50)
Location: drivers/acpi/scan.c:1848
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
```
**Symbols:**

```
ffffffff8168ab50-ffffffff8168ad74: acpi_scan_check_dep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u32 acpi_scan_check_dep(acpi_handle handle, bool check_dep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81700270)
Location: drivers/acpi/scan.c:1946
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
```
**Symbols:**

```
ffffffff81700270-ffffffff817004d9: acpi_scan_check_dep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 acpi_scan_check_dep(acpi_handle handle, bool check_dep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8182ddf0)
Location: drivers/acpi/scan.c:1989
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
```
**Symbols:**

```
ffffffff8182ddf0-ffffffff8182e04c: acpi_scan_check_dep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 acpi_scan_check_dep(acpi_handle handle, bool check_dep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81960b50)
Location: drivers/acpi/scan.c:1973
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
```
**Symbols:**

```
ffffffff81960b50-ffffffff81960dac: acpi_scan_check_dep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 acpi_scan_check_dep(acpi_handle handle, bool check_dep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819a6f50)
Location: drivers/acpi/scan.c:1976
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
```
**Symbols:**

```
ffffffff819a6f50-ffffffff819a71ac: acpi_scan_check_dep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 acpi_scan_check_dep(acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819ef970)
Location: drivers/acpi/scan.c:1988
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
```
**Symbols:**

```
ffffffff819ef970-ffffffff819efb9a: acpi_scan_check_dep (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool check_dep</code>
</li>
</ul>
</details>
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
<code>bool check_dep</code>
</li>
</ul>
</details>
</li>
</ul>
