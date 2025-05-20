# Function: <code>acpi_info_matches_ids</code>

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
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff816a8568)
Location: drivers/acpi/scan.c:755
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_check_dep
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
In drivers/acpi/scan.c (ffffffff8168ac2a)
Location: drivers/acpi/scan.c:756
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_check_dep
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
In drivers/acpi/scan.c (ffffffff81700356)
Location: drivers/acpi/scan.c:764
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_check_dep
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool acpi_info_matches_ids(struct acpi_device_info *info, const const char * *ids);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8182ce70)
Location: drivers/acpi/scan.c:782
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_check_dep
  - drivers/acpi/scan.c:acpi_scan_check_dep
```
**Symbols:**

```
ffffffff8182ce70-ffffffff8182cf18: acpi_info_matches_ids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool acpi_info_matches_ids(struct acpi_device_info *info, const const char * *ids);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8195fb90)
Location: drivers/acpi/scan.c:760
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_check_dep
  - drivers/acpi/scan.c:acpi_scan_check_dep
```
**Symbols:**

```
ffffffff8195fb90-ffffffff8195fc38: acpi_info_matches_ids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool acpi_info_matches_ids(struct acpi_device_info *info, const const char * *ids);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819a5f80)
Location: drivers/acpi/scan.c:759
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_check_dep
  - drivers/acpi/scan.c:acpi_scan_check_dep
```
**Symbols:**

```
ffffffff819a5f80-ffffffff819a6028: acpi_info_matches_ids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool acpi_info_matches_ids(struct acpi_device_info *info, const const char * *ids);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819ee960)
Location: drivers/acpi/scan.c:759
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_check_dep
  - drivers/acpi/scan.c:acpi_scan_check_dep
```
**Symbols:**

```
ffffffff819ee960-ffffffff819eea08: acpi_info_matches_ids (STB_LOCAL)
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
