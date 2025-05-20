# Function: <code>acpi_bus_osc_negotiate_platform_control</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff832096a5)
Location: drivers/acpi/bus.c:287
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_init
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
In drivers/acpi/bus.c (ffffffff832f1a00)
Location: drivers/acpi/bus.c:287
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_bus_osc_negotiate_platform_control();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff81eb6c5a)
Location: drivers/acpi/bus.c:304
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_init
```
**Symbols:**

```
ffffffff81eb6c5a-ffffffff81eb6db0: acpi_bus_osc_negotiate_platform_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void acpi_bus_osc_negotiate_platform_control();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/bus.c (0)
Location: drivers/acpi/bus.c:305
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_init
```
**Symbols:**

```
ffffffff8195dc10-ffffffff8195dd72: acpi_bus_osc_negotiate_platform_control (STB_LOCAL)
ffffffff820918d1-ffffffff820918e5: acpi_bus_osc_negotiate_platform_control.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void acpi_bus_osc_negotiate_platform_control();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/bus.c (0)
Location: drivers/acpi/bus.c:302
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_init
```
**Symbols:**

```
ffffffff819a3dd0-ffffffff819a3f32: acpi_bus_osc_negotiate_platform_control (STB_LOCAL)
ffffffff821121c7-ffffffff821121db: acpi_bus_osc_negotiate_platform_control.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void acpi_bus_osc_negotiate_platform_control();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/bus.c (0)
Location: drivers/acpi/bus.c:302
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_init
```
**Symbols:**

```
ffffffff819ec500-ffffffff819ec662: acpi_bus_osc_negotiate_platform_control (STB_LOCAL)
ffffffff821efecb-ffffffff821efedf: acpi_bus_osc_negotiate_platform_control.cold (STB_LOCAL)
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
