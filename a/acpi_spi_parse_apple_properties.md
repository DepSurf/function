# Function: <code>acpi_spi_parse_apple_properties</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff816f6c8f)
Location: drivers/spi/spi.c:1695
Inline: True
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
In drivers/spi/spi.c (ffffffff817320ea)
Location: drivers/spi/spi.c:1709
Inline: True
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
In drivers/spi/spi.c (ffffffff81754ada)
Location: drivers/spi/spi.c:1775
Inline: True
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
In drivers/spi/spi.c (ffffffff8179042d)
Location: drivers/spi/spi.c:1883
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_register_spi_device
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
In drivers/spi/spi.c (ffffffff817b4016)
Location: drivers/spi/spi.c:1886
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_spi_parse_apple_properties(struct acpi_device *dev, struct acpi_spi_lookup *lookup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff818784d0)
Location: drivers/spi/spi.c:2066
Inline: False
Direct callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffffffff818784d0-ffffffff81878653: acpi_spi_parse_apple_properties (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_spi_parse_apple_properties(struct acpi_device *dev, struct acpi_spi_lookup *lookup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81886d40)
Location: drivers/spi/spi.c:2099
Inline: False
Direct callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffffffff81886d40-ffffffff81886ec3: acpi_spi_parse_apple_properties (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_spi_parse_apple_properties(struct acpi_device *dev, struct acpi_spi_lookup *lookup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81869570)
Location: drivers/spi/spi.c:2118
Inline: False
Direct callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffffffff81869570-ffffffff818696f3: acpi_spi_parse_apple_properties (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void acpi_spi_parse_apple_properties(struct acpi_device *dev, struct acpi_spi_lookup *lookup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2246
Inline: False
Direct callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffffffff818f90a0-ffffffff818f923b: acpi_spi_parse_apple_properties (STB_LOCAL)
ffffffff81d0f894-ffffffff81d0f8a8: acpi_spi_parse_apple_properties.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void acpi_spi_parse_apple_properties(struct acpi_device *dev, struct acpi_spi_lookup *lookup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2332
Inline: False
Direct callers:
  - drivers/spi/spi.c:acpi_spi_device_alloc
```
**Symbols:**

```
ffffffff81a4a2a0-ffffffff81a4a454: acpi_spi_parse_apple_properties (STB_LOCAL)
ffffffff81eda576-ffffffff81eda58b: acpi_spi_parse_apple_properties.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void acpi_spi_parse_apple_properties(struct acpi_device *dev, struct acpi_spi_lookup *lookup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2512
Inline: False
Direct callers:
  - drivers/spi/spi.c:acpi_spi_device_alloc
```
**Symbols:**

```
ffffffff81bd0f50-ffffffff81bd1104: acpi_spi_parse_apple_properties (STB_LOCAL)
ffffffff8209cfa9-ffffffff8209cfbe: acpi_spi_parse_apple_properties.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void acpi_spi_parse_apple_properties(struct acpi_device *dev, struct acpi_spi_lookup *lookup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2521
Inline: False
Direct callers:
  - drivers/spi/spi.c:acpi_spi_device_alloc
```
**Symbols:**

```
ffffffff81c28bc0-ffffffff81c28d74: acpi_spi_parse_apple_properties (STB_LOCAL)
ffffffff8211de91-ffffffff8211dea6: acpi_spi_parse_apple_properties.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void acpi_spi_parse_apple_properties(struct acpi_device *dev, struct acpi_spi_lookup *lookup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2655
Inline: False
Direct callers:
  - drivers/spi/spi.c:acpi_spi_device_alloc
```
**Symbols:**

```
ffffffff81cdb710-ffffffff81cdb8c4: acpi_spi_parse_apple_properties (STB_LOCAL)
ffffffff821ff457-ffffffff821ff46c: acpi_spi_parse_apple_properties.cold (STB_LOCAL)
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
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1886
Inline: True
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
In drivers/spi/spi.c (ffffffff81778af6)
Location: drivers/spi/spi.c:1886
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_register_spi_device
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
In drivers/spi/spi.c (ffffffff817588a6)
Location: drivers/spi/spi.c:1886
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_register_spi_device
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
In drivers/spi/spi.c (ffffffff817a8e96)
Location: drivers/spi/spi.c:1886
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_register_spi_device
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
In drivers/spi/spi.c (ffffffff817c2d26)
Location: drivers/spi/spi.c:1886
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_register_spi_device
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
