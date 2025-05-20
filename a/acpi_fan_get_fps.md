# Function: <code>acpi_fan_get_fps</code>

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
In drivers/acpi/fan.c (ffffffff814aba6e)
Location: drivers/acpi/fan.c:271
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
In drivers/acpi/fan.c (ffffffff814fad55)
Location: drivers/acpi/fan.c:271
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
In drivers/acpi/fan.c (ffffffff8151d9ea)
Location: drivers/acpi/fan.c:281
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
In drivers/acpi/fan.c (ffffffff8152eb4c)
Location: drivers/acpi/fan.c:281
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
In drivers/acpi/fan.c (ffffffff8158f81a)
Location: drivers/acpi/fan.c:281
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
In drivers/acpi/fan.c (ffffffff815c6bea)
Location: drivers/acpi/fan.c:281
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
In drivers/acpi/fan.c (ffffffff815e01aa)
Location: drivers/acpi/fan.c:281
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
In drivers/acpi/fan.c (ffffffff81611c4e)
Location: drivers/acpi/fan.c:268
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
In drivers/acpi/fan.c (ffffffff816330fe)
Location: drivers/acpi/fan.c:268
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
int acpi_fan_get_fps(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/fan.c (0)
Location: drivers/acpi/fan.c:306
Inline: False
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
**Symbols:**

```
ffffffff816dfbe0-ffffffff816dfe43: acpi_fan_get_fps (STB_LOCAL)
ffffffff816e0182-ffffffff816e01b5: acpi_fan_get_fps.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int acpi_fan_get_fps(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/fan.c (0)
Location: drivers/acpi/fan.c:307
Inline: False
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
**Symbols:**

```
ffffffff816fdb70-ffffffff816fddd3: acpi_fan_get_fps (STB_LOCAL)
ffffffff81c028fd-ffffffff81c02930: acpi_fan_get_fps.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int acpi_fan_get_fps(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/fan.c (0)
Location: drivers/acpi/fan.c:306
Inline: False
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
**Symbols:**

```
ffffffff816df7e0-ffffffff816dfa43: acpi_fan_get_fps (STB_LOCAL)
ffffffff81bf42bb-ffffffff81bf42ee: acpi_fan_get_fps.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int acpi_fan_get_fps(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/fan.c (0)
Location: drivers/acpi/fan.c:306
Inline: False
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
**Symbols:**

```
ffffffff81757660-ffffffff817578c3: acpi_fan_get_fps (STB_LOCAL)
ffffffff81cf1164-ffffffff81cf1197: acpi_fan_get_fps.cold (STB_LOCAL)
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
In drivers/acpi/fan_core.c (ffffffff8188abe1)
Location: drivers/acpi/fan_core.c:295
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
In drivers/acpi/fan_core.c (ffffffff819d174c)
Location: drivers/acpi/fan_core.c:265
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
In drivers/acpi/fan_core.c (ffffffff81a18d3c)
Location: drivers/acpi/fan_core.c:265
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
In drivers/acpi/fan_core.c (ffffffff81a6400c)
Location: drivers/acpi/fan_core.c:265
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
In drivers/acpi/fan.c (ffff8000107a1734)
Location: drivers/acpi/fan.c:268
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
In drivers/acpi/fan.c (ffffffff816273de)
Location: drivers/acpi/fan.c:268
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
In drivers/acpi/fan.c (ffffffff8164128e)
Location: drivers/acpi/fan.c:268
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
