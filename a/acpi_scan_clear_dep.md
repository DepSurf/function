# Function: <code>acpi_scan_clear_dep</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int acpi_scan_clear_dep(struct acpi_dep_data *dep, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff816ffc10)
Location: drivers/acpi/scan.c:2263
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_dev_clear_dependencies
```
**Symbols:**

```
ffffffff816ffc10-ffffffff816ffcdb: acpi_scan_clear_dep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_scan_clear_dep(struct acpi_dep_data *dep, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8182d760)
Location: drivers/acpi/scan.c:2307
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_dev_clear_dependencies
```
**Symbols:**

```
ffffffff8182d760-ffffffff8182d832: acpi_scan_clear_dep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_scan_clear_dep(struct acpi_dep_data *dep, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81960510)
Location: drivers/acpi/scan.c:2304
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_dev_clear_dependencies
```
**Symbols:**

```
ffffffff81960510-ffffffff819605e2: acpi_scan_clear_dep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int acpi_scan_clear_dep(struct acpi_dep_data *dep, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:2309
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_dev_clear_dependencies
```
**Symbols:**

```
ffffffff819a68f0-ffffffff819a69e9: acpi_scan_clear_dep (STB_LOCAL)
ffffffff82112231-ffffffff82112246: acpi_scan_clear_dep.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int acpi_scan_clear_dep(struct acpi_dep_data *dep, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:2342
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_dev_clear_dependencies
```
**Symbols:**

```
ffffffff819ef2d0-ffffffff819ef403: acpi_scan_clear_dep (STB_LOCAL)
ffffffff821eff49-ffffffff821eff5e: acpi_scan_clear_dep.cold (STB_LOCAL)
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
