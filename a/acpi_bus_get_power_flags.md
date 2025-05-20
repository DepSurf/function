# Function: <code>acpi_bus_get_power_flags</code>

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
In drivers/acpi/scan.c (ffffffff81480a4d)
Location: drivers/acpi/scan.c:932
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
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
In drivers/acpi/scan.c (ffffffff814cf3f1)
Location: drivers/acpi/scan.c:952
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
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
In drivers/acpi/scan.c (ffffffff814f135b)
Location: drivers/acpi/scan.c:953
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
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
In drivers/acpi/scan.c (ffffffff814fed25)
Location: drivers/acpi/scan.c:944
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
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
In drivers/acpi/scan.c (ffffffff81540d25)
Location: drivers/acpi/scan.c:945
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
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
In drivers/acpi/scan.c (ffffffff81576bee)
Location: drivers/acpi/scan.c:946
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
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
In drivers/acpi/scan.c (ffffffff8158e7de)
Location: drivers/acpi/scan.c:946
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
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
In drivers/acpi/scan.c (ffffffff815bf53d)
Location: drivers/acpi/scan.c:944
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
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
In drivers/acpi/scan.c (ffffffff815e07fd)
Location: drivers/acpi/scan.c:944
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_bus_get_power_flags(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81689990)
Location: drivers/acpi/scan.c:940
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
```
**Symbols:**

```
ffffffff81689990-ffffffff81689ab7: acpi_bus_get_power_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_bus_get_power_flags(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff816a7550)
Location: drivers/acpi/scan.c:1009
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
```
**Symbols:**

```
ffffffff816a7550-ffffffff816a767d: acpi_bus_get_power_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_bus_get_power_flags(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81689fb0)
Location: drivers/acpi/scan.c:1009
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
```
**Symbols:**

```
ffffffff81689fb0-ffffffff8168a204: acpi_bus_get_power_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_bus_get_power_flags(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff816ff490)
Location: drivers/acpi/scan.c:1017
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
```
**Symbols:**

```
ffffffff816ff490-ffffffff816ff707: acpi_bus_get_power_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_bus_get_power_flags(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8182cf20)
Location: drivers/acpi/scan.c:1043
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
```
**Symbols:**

```
ffffffff8182cf20-ffffffff8182d1d5: acpi_bus_get_power_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_bus_get_power_flags(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8195fc50)
Location: drivers/acpi/scan.c:1026
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
```
**Symbols:**

```
ffffffff8195fc50-ffffffff8195feff: acpi_bus_get_power_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_bus_get_power_flags(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819a6040)
Location: drivers/acpi/scan.c:1028
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
```
**Symbols:**

```
ffffffff819a6040-ffffffff819a62ef: acpi_bus_get_power_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_bus_get_power_flags(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819eea20)
Location: drivers/acpi/scan.c:1031
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
```
**Symbols:**

```
ffffffff819eea20-ffffffff819eeccf: acpi_bus_get_power_flags (STB_LOCAL)
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
In drivers/acpi/scan.c (ffff80001076d104)
Location: drivers/acpi/scan.c:944
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
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
In drivers/acpi/scan.c (ffffffff815d2bfd)
Location: drivers/acpi/scan.c:944
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
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
In drivers/acpi/scan.c (ffffffff815bc7bd)
Location: drivers/acpi/scan.c:944
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
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
In drivers/acpi/scan.c (ffffffff815d4add)
Location: drivers/acpi/scan.c:944
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
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
In drivers/acpi/scan.c (ffffffff815ee99d)
Location: drivers/acpi/scan.c:944
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
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
