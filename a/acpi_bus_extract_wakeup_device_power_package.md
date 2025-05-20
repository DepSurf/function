# Function: <code>acpi_bus_extract_wakeup_device_power_package</code>

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
In drivers/acpi/scan.c (ffffffff81480c35)
Location: drivers/acpi/scan.c:745
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
In drivers/acpi/scan.c (ffffffff814cf5dd)
Location: drivers/acpi/scan.c:765
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
In drivers/acpi/scan.c (ffffffff814f1547)
Location: drivers/acpi/scan.c:766
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
In drivers/acpi/scan.c (ffffffff814fef9c)
Location: drivers/acpi/scan.c:764
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
In drivers/acpi/scan.c (ffffffff81541018)
Location: drivers/acpi/scan.c:765
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
In drivers/acpi/scan.c (ffffffff81576ee6)
Location: drivers/acpi/scan.c:766
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
In drivers/acpi/scan.c (ffffffff8158ea9c)
Location: drivers/acpi/scan.c:766
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
In drivers/acpi/scan.c (ffffffff815bf829)
Location: drivers/acpi/scan.c:767
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
In drivers/acpi/scan.c (ffffffff815e0ae9)
Location: drivers/acpi/scan.c:767
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
int acpi_bus_extract_wakeup_device_power_package(struct acpi_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81689ac0)
Location: drivers/acpi/scan.c:766
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_get_wakeup_device_flags
```
**Symbols:**

```
ffffffff81689ac0-ffffffff81689caf: acpi_bus_extract_wakeup_device_power_package (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int acpi_bus_extract_wakeup_device_power_package(struct acpi_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff816a7680)
Location: drivers/acpi/scan.c:836
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_get_wakeup_device_flags
```
**Symbols:**

```
ffffffff816a7680-ffffffff816a786f: acpi_bus_extract_wakeup_device_power_package (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int acpi_bus_extract_wakeup_device_power_package(struct acpi_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8168a210)
Location: drivers/acpi/scan.c:835
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
```
**Symbols:**

```
ffffffff8168a210-ffffffff8168a402: acpi_bus_extract_wakeup_device_power_package (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int acpi_bus_extract_wakeup_device_power_package(struct acpi_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff816ff710)
Location: drivers/acpi/scan.c:843
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
```
**Symbols:**

```
ffffffff816ff710-ffffffff816ff902: acpi_bus_extract_wakeup_device_power_package (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_bus_extract_wakeup_device_power_package(struct acpi_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8182d1e0)
Location: drivers/acpi/scan.c:869
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
```
**Symbols:**

```
ffffffff8182d1e0-ffffffff8182d3ce: acpi_bus_extract_wakeup_device_power_package (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_bus_extract_wakeup_device_power_package(struct acpi_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8195ff10)
Location: drivers/acpi/scan.c:852
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
```
**Symbols:**

```
ffffffff8195ff10-ffffffff819600fe: acpi_bus_extract_wakeup_device_power_package (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_bus_extract_wakeup_device_power_package(struct acpi_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819a6300)
Location: drivers/acpi/scan.c:851
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
```
**Symbols:**

```
ffffffff819a6300-ffffffff819a64ee: acpi_bus_extract_wakeup_device_power_package (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_bus_extract_wakeup_device_power_package(struct acpi_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819eece0)
Location: drivers/acpi/scan.c:854
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
```
**Symbols:**

```
ffffffff819eece0-ffffffff819eeece: acpi_bus_extract_wakeup_device_power_package (STB_LOCAL)
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
In drivers/acpi/scan.c (ffff80001076d3e4)
Location: drivers/acpi/scan.c:767
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
In drivers/acpi/scan.c (ffffffff815d2e67)
Location: drivers/acpi/scan.c:767
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
In drivers/acpi/scan.c (ffffffff815bca27)
Location: drivers/acpi/scan.c:767
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
In drivers/acpi/scan.c (ffffffff815d4dc9)
Location: drivers/acpi/scan.c:767
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
In drivers/acpi/scan.c (ffffffff815eec89)
Location: drivers/acpi/scan.c:767
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
