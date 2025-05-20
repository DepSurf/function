# Function: <code>acpi_fan_get_fif</code>

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
In drivers/acpi/fan.c (ffffffff814ab9af)
Location: drivers/acpi/fan.c:233
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
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
In drivers/acpi/fan.c (ffffffff814fac91)
Location: drivers/acpi/fan.c:233
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
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
In drivers/acpi/fan.c (ffffffff8151d926)
Location: drivers/acpi/fan.c:243
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
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
In drivers/acpi/fan.c (ffffffff8152ea1c)
Location: drivers/acpi/fan.c:243
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
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
In drivers/acpi/fan.c (ffffffff8158f6f1)
Location: drivers/acpi/fan.c:243
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
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
In drivers/acpi/fan.c (ffffffff815c6ad1)
Location: drivers/acpi/fan.c:243
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
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
In drivers/acpi/fan.c (ffffffff815e0091)
Location: drivers/acpi/fan.c:243
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
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
In drivers/acpi/fan.c (ffffffff81611bb9)
Location: drivers/acpi/fan.c:230
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
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
In drivers/acpi/fan.c (ffffffff81633069)
Location: drivers/acpi/fan.c:230
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int acpi_fan_get_fif(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/fan.c (0)
Location: drivers/acpi/fan.c:235
Inline: False
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
**Symbols:**

```
ffffffff816df990-ffffffff816dfa65: acpi_fan_get_fif (STB_LOCAL)
ffffffff816e0144-ffffffff816e0182: acpi_fan_get_fif.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int acpi_fan_get_fif(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/fan.c (0)
Location: drivers/acpi/fan.c:236
Inline: False
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
**Symbols:**

```
ffffffff816fd920-ffffffff816fd9f5: acpi_fan_get_fif (STB_LOCAL)
ffffffff81c028bf-ffffffff81c028fd: acpi_fan_get_fif.cold (STB_LOCAL)
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
In drivers/acpi/fan.c (ffffffff816dfc04)
Location: drivers/acpi/fan.c:235
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
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
In drivers/acpi/fan.c (ffffffff81757e21)
Location: drivers/acpi/fan.c:235
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
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
In drivers/acpi/fan_core.c (ffffffff8188aaef)
Location: drivers/acpi/fan_core.c:245
Inline: True
Inline callers:
  - drivers/acpi/fan_core.c:acpi_fan_probe
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
In drivers/acpi/fan_core.c (ffffffff819d15e9)
Location: drivers/acpi/fan_core.c:214
Inline: True
Inline callers:
  - drivers/acpi/fan_core.c:acpi_fan_probe
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
In drivers/acpi/fan_core.c (ffffffff81a18bd9)
Location: drivers/acpi/fan_core.c:214
Inline: True
Inline callers:
  - drivers/acpi/fan_core.c:acpi_fan_probe
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
In drivers/acpi/fan_core.c (ffffffff81a63ea9)
Location: drivers/acpi/fan_core.c:214
Inline: True
Inline callers:
  - drivers/acpi/fan_core.c:acpi_fan_probe
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
In drivers/acpi/fan.c (ffff8000107a16c0)
Location: drivers/acpi/fan.c:230
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/fan.c (ffffffff81627349)
Location: drivers/acpi/fan.c:230
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
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
In drivers/acpi/fan.c (ffffffff816411f9)
Location: drivers/acpi/fan.c:230
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
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
