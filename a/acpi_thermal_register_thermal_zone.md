# Function: <code>acpi_thermal_register_thermal_zone</code>

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
In drivers/acpi/thermal.c (ffffffff814b0c29)
Location: drivers/acpi/thermal.c:884
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
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
In drivers/acpi/thermal.c (ffffffff81500568)
Location: drivers/acpi/thermal.c:884
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
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
In drivers/acpi/thermal.c (ffffffff81523264)
Location: drivers/acpi/thermal.c:885
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
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
In drivers/acpi/thermal.c (ffffffff8153548b)
Location: drivers/acpi/thermal.c:885
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
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
In drivers/acpi/thermal.c (ffffffff81596cf2)
Location: drivers/acpi/thermal.c:885
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
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
In drivers/acpi/thermal.c (ffffffff815ce0b7)
Location: drivers/acpi/thermal.c:885
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
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
In drivers/acpi/thermal.c (ffffffff815e7672)
Location: drivers/acpi/thermal.c:885
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
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
In drivers/acpi/thermal.c (ffffffff81619326)
Location: drivers/acpi/thermal.c:871
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
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
In drivers/acpi/thermal.c (ffffffff8163a92a)
Location: drivers/acpi/thermal.c:866
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int acpi_thermal_register_thermal_zone(struct acpi_thermal *tz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/thermal.c (0)
Location: drivers/acpi/thermal.c:868
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
**Symbols:**

```
ffffffff816e6e20-ffffffff816e6f29: acpi_thermal_register_thermal_zone (STB_LOCAL)
ffffffff816e786b-ffffffff816e789f: acpi_thermal_register_thermal_zone.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int acpi_thermal_register_thermal_zone(struct acpi_thermal *tz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/thermal.c (0)
Location: drivers/acpi/thermal.c:810
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
**Symbols:**

```
ffffffff817045d0-ffffffff81704753: acpi_thermal_register_thermal_zone (STB_LOCAL)
ffffffff81c02eb2-ffffffff81c02ed6: acpi_thermal_register_thermal_zone.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int acpi_thermal_register_thermal_zone(struct acpi_thermal *tz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/thermal.c (0)
Location: drivers/acpi/thermal.c:790
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
**Symbols:**

```
ffffffff816e5cd0-ffffffff816e5e4d: acpi_thermal_register_thermal_zone (STB_LOCAL)
ffffffff81bf48cc-ffffffff81bf48f0: acpi_thermal_register_thermal_zone.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int acpi_thermal_register_thermal_zone(struct acpi_thermal *tz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/thermal.c (0)
Location: drivers/acpi/thermal.c:790
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
**Symbols:**

```
ffffffff8175ef20-ffffffff8175f0d0: acpi_thermal_register_thermal_zone (STB_LOCAL)
ffffffff81cf1a24-ffffffff81cf1a48: acpi_thermal_register_thermal_zone.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int acpi_thermal_register_thermal_zone(struct acpi_thermal *tz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/thermal.c (0)
Location: drivers/acpi/thermal.c:789
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
**Symbols:**

```
ffffffff818927c0-ffffffff81892983: acpi_thermal_register_thermal_zone (STB_LOCAL)
ffffffff81eb99a1-ffffffff81eb99c5: acpi_thermal_register_thermal_zone.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_thermal_register_thermal_zone(struct acpi_thermal *tz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/thermal.c (ffffffff819d9310)
Location: drivers/acpi/thermal.c:790
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
**Symbols:**

```
ffffffff819d9310-ffffffff819d94f3: acpi_thermal_register_thermal_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int acpi_thermal_register_thermal_zone(struct acpi_thermal *tz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/thermal.c (0)
Location: drivers/acpi/thermal.c:742
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
**Symbols:**

```
ffffffff81a21fe0-ffffffff81a22229: acpi_thermal_register_thermal_zone (STB_LOCAL)
ffffffff821134ba-ffffffff82113520: acpi_thermal_register_thermal_zone.cold (STB_LOCAL)
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
In drivers/acpi/thermal.c (ffffffff81a6d089)
Location: drivers/acpi/thermal.c:664
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
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
In drivers/acpi/thermal.c (ffff8000107a58ac)
Location: drivers/acpi/thermal.c:866
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
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
In drivers/acpi/thermal.c (ffffffff8162ec0a)
Location: drivers/acpi/thermal.c:866
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
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
In drivers/acpi/thermal.c (ffffffff81648aaa)
Location: drivers/acpi/thermal.c:866
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
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
</ul>
