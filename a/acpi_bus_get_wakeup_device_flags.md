# Function: <code>acpi_bus_get_wakeup_device_flags</code>

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
In drivers/acpi/scan.c (ffffffff81480c19)
Location: drivers/acpi/scan.c:864
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
In drivers/acpi/scan.c (ffffffff814cf5c1)
Location: drivers/acpi/scan.c:884
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
In drivers/acpi/scan.c (ffffffff814f152b)
Location: drivers/acpi/scan.c:885
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
In drivers/acpi/scan.c (ffffffff814feecd)
Location: drivers/acpi/scan.c:876
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
In drivers/acpi/scan.c (ffffffff81540ecc)
Location: drivers/acpi/scan.c:877
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
In drivers/acpi/scan.c (ffffffff81576d95)
Location: drivers/acpi/scan.c:878
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
In drivers/acpi/scan.c (ffffffff8158e985)
Location: drivers/acpi/scan.c:878
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
In drivers/acpi/scan.c (ffffffff815bf6e8)
Location: drivers/acpi/scan.c:877
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
In drivers/acpi/scan.c (ffffffff815e09a8)
Location: drivers/acpi/scan.c:877
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void acpi_bus_get_wakeup_device_flags(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:876
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
```
**Symbols:**

```
ffffffff81689cb0-ffffffff81689e03: acpi_bus_get_wakeup_device_flags (STB_LOCAL)
ffffffff8168c4b4-ffffffff8168c4cf: acpi_bus_get_wakeup_device_flags.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void acpi_bus_get_wakeup_device_flags(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:946
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
```
**Symbols:**

```
ffffffff816a7870-ffffffff816a7998: acpi_bus_get_wakeup_device_flags (STB_LOCAL)
ffffffff81c01085-ffffffff81c010a0: acpi_bus_get_wakeup_device_flags.cold (STB_LOCAL)
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
In drivers/acpi/scan.c (ffffffff8168c332)
Location: drivers/acpi/scan.c:946
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
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
In drivers/acpi/scan.c (ffffffff81701aef)
Location: drivers/acpi/scan.c:954
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
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
In drivers/acpi/scan.c (ffffffff8182f77f)
Location: drivers/acpi/scan.c:980
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
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
In drivers/acpi/scan.c (ffffffff81962806)
Location: drivers/acpi/scan.c:963
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
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
In drivers/acpi/scan.c (ffffffff819a8c06)
Location: drivers/acpi/scan.c:965
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
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
In drivers/acpi/scan.c (ffffffff819f1645)
Location: drivers/acpi/scan.c:968
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
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
In drivers/acpi/scan.c (ffff80001076d2c4)
Location: drivers/acpi/scan.c:877
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
In drivers/acpi/scan.c (ffffffff815d2da8)
Location: drivers/acpi/scan.c:877
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
In drivers/acpi/scan.c (ffffffff815bc968)
Location: drivers/acpi/scan.c:877
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
In drivers/acpi/scan.c (ffffffff815d4c88)
Location: drivers/acpi/scan.c:877
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
In drivers/acpi/scan.c (ffffffff815eeb48)
Location: drivers/acpi/scan.c:877
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
</ul>
