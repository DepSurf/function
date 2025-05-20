# Function: <code>acpi_bus_osc_support</code>

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
In drivers/acpi/bus.c (ffffffff81fa185f)
Location: drivers/acpi/bus.c:305
Inline: True
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
In drivers/acpi/bus.c (ffffffff81fcd71d)
Location: drivers/acpi/bus.c:313
Inline: True
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
In drivers/acpi/bus.c (ffffffff8200a700)
Location: drivers/acpi/bus.c:313
Inline: True
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
In drivers/acpi/bus.c (ffffffff820ebe7f)
Location: drivers/acpi/bus.c:295
Inline: True
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
In drivers/acpi/bus.c (ffffffff826f4d5b)
Location: drivers/acpi/bus.c:322
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
In drivers/acpi/bus.c (ffffffff8271ed66)
Location: drivers/acpi/bus.c:329
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_init
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
In drivers/acpi/bus.c (ffffffff828d6d7a)
Location: drivers/acpi/bus.c:298
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_init
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
In drivers/acpi/bus.c (ffffffff828f0bef)
Location: drivers/acpi/bus.c:285
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_init
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
In drivers/acpi/bus.c (ffffffff828f9d59)
Location: drivers/acpi/bus.c:285
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_bus_osc_support();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff816885af)
Location: drivers/acpi/bus.c:285
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_init
```
**Symbols:**

```
ffffffff816885af-ffffffff81688698: acpi_bus_osc_support (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_bus_osc_support();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff81c00efd)
Location: drivers/acpi/bus.c:285
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_init
```
**Symbols:**

```
ffffffff81c00efd-ffffffff81c00fe6: acpi_bus_osc_support (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In drivers/acpi/bus.c (ffff80001147cd28)
Location: drivers/acpi/bus.c:285
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_init
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
In drivers/acpi/bus.c (ffffffff828e2a41)
Location: drivers/acpi/bus.c:285
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_init
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
In drivers/acpi/bus.c (ffffffff828daab0)
Location: drivers/acpi/bus.c:285
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_init
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
In drivers/acpi/bus.c (ffffffff828f5955)
Location: drivers/acpi/bus.c:285
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_init
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
In drivers/acpi/bus.c (ffffffff828fadad)
Location: drivers/acpi/bus.c:285
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_init
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
