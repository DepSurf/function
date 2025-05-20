# Function: <code>acpi_bus_init_power_state</code>

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
In drivers/acpi/scan.c (ffffffff81480adb)
Location: drivers/acpi/scan.c:894
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
In drivers/acpi/scan.c (ffffffff814cf47f)
Location: drivers/acpi/scan.c:914
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
In drivers/acpi/scan.c (ffffffff814f13e9)
Location: drivers/acpi/scan.c:915
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
In drivers/acpi/scan.c (ffffffff814fedad)
Location: drivers/acpi/scan.c:906
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
In drivers/acpi/scan.c (ffffffff81540dad)
Location: drivers/acpi/scan.c:907
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
In drivers/acpi/scan.c (ffffffff81576c7d)
Location: drivers/acpi/scan.c:908
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
In drivers/acpi/scan.c (ffffffff8158e86d)
Location: drivers/acpi/scan.c:908
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
In drivers/acpi/scan.c (ffffffff815bf5c5)
Location: drivers/acpi/scan.c:906
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
In drivers/acpi/scan.c (ffffffff815e0885)
Location: drivers/acpi/scan.c:906
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
void acpi_bus_init_power_state(struct acpi_device *device, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81689840)
Location: drivers/acpi/scan.c:905
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
```
**Symbols:**

```
ffffffff81689840-ffffffff81689989: acpi_bus_init_power_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_bus_init_power_state(struct acpi_device *device, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff816a7400)
Location: drivers/acpi/scan.c:974
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
```
**Symbols:**

```
ffffffff816a7400-ffffffff816a7549: acpi_bus_init_power_state (STB_LOCAL)
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
In drivers/acpi/scan.c (ffffffff8168a064)
Location: drivers/acpi/scan.c:974
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
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
In drivers/acpi/scan.c (ffffffff816ff546)
Location: drivers/acpi/scan.c:982
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
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
In drivers/acpi/scan.c (ffffffff8182d00a)
Location: drivers/acpi/scan.c:1008
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
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
In drivers/acpi/scan.c (ffffffff8195fd37)
Location: drivers/acpi/scan.c:991
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
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
In drivers/acpi/scan.c (ffffffff819a6127)
Location: drivers/acpi/scan.c:993
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
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
In drivers/acpi/scan.c (ffffffff819eeb07)
Location: drivers/acpi/scan.c:996
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
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
In drivers/acpi/scan.c (ffff80001076d1bc)
Location: drivers/acpi/scan.c:906
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
In drivers/acpi/scan.c (ffffffff815d2c85)
Location: drivers/acpi/scan.c:906
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
In drivers/acpi/scan.c (ffffffff815bc845)
Location: drivers/acpi/scan.c:906
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
In drivers/acpi/scan.c (ffffffff815d4b65)
Location: drivers/acpi/scan.c:906
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
In drivers/acpi/scan.c (ffffffff815eea25)
Location: drivers/acpi/scan.c:906
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
