# Function: <code>acpi_scan_init_hotplug</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81481003)
Location: drivers/acpi/scan.c:1540
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814cfa26)
Location: drivers/acpi/scan.c:1598
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
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
In drivers/acpi/scan.c (ffffffff814f1990)
Location: drivers/acpi/scan.c:1628
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
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
In drivers/acpi/scan.c (ffffffff814ff33a)
Location: drivers/acpi/scan.c:1653
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
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
In drivers/acpi/scan.c (ffffffff81541422)
Location: drivers/acpi/scan.c:1752
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
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
In drivers/acpi/scan.c (ffffffff815772f2)
Location: drivers/acpi/scan.c:1766
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
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
In drivers/acpi/scan.c (ffffffff8158eef6)
Location: drivers/acpi/scan.c:1779
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
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
In drivers/acpi/scan.c (ffffffff815bfc79)
Location: drivers/acpi/scan.c:1778
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
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
In drivers/acpi/scan.c (ffffffff815e0f39)
Location: drivers/acpi/scan.c:1778
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_scan_init_hotplug(struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8168b330)
Location: drivers/acpi/scan.c:1787
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
```
**Symbols:**

```
ffffffff8168b330-ffffffff8168b402: acpi_scan_init_hotplug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_scan_init_hotplug(struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff816a9150)
Location: drivers/acpi/scan.c:1860
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_bus_check_add
```
**Symbols:**

```
ffffffff816a9150-ffffffff816a9225: acpi_scan_init_hotplug (STB_LOCAL)
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
In drivers/acpi/scan.c (ffffffff8168c676)
Location: drivers/acpi/scan.c:1829
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
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
In drivers/acpi/scan.c (ffffffff81701eb6)
Location: drivers/acpi/scan.c:1927
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
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
In drivers/acpi/scan.c (ffffffff8182fb80)
Location: drivers/acpi/scan.c:1970
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
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
In drivers/acpi/scan.c (ffffffff81962c20)
Location: drivers/acpi/scan.c:1954
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
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
In drivers/acpi/scan.c (ffffffff819a9069)
Location: drivers/acpi/scan.c:1957
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
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
In drivers/acpi/scan.c (ffffffff819f1aa8)
Location: drivers/acpi/scan.c:1969
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
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
In drivers/acpi/scan.c (ffff80001076d774)
Location: drivers/acpi/scan.c:1778
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
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
In drivers/acpi/scan.c (ffffffff815d3267)
Location: drivers/acpi/scan.c:1778
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
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
In drivers/acpi/scan.c (ffffffff815bce27)
Location: drivers/acpi/scan.c:1778
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
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
In drivers/acpi/scan.c (ffffffff815d5219)
Location: drivers/acpi/scan.c:1778
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
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
In drivers/acpi/scan.c (ffffffff815ef0d9)
Location: drivers/acpi/scan.c:1778
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
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
</ul>
