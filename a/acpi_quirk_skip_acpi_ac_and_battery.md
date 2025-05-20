# Function: <code>acpi_quirk_skip_acpi_ac_and_battery</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool acpi_quirk_skip_acpi_ac_and_battery();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/x86/utils.c (0)
Location: drivers/acpi/x86/utils.c:408
Inline: False
Direct callers:
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/battery.c:acpi_battery_init_async
```
**Symbols:**

```
ffffffff81eb8af7-ffffffff81eb8b0b: acpi_quirk_skip_acpi_ac_and_battery.cold (STB_LOCAL)
ffffffff81840dc0-ffffffff81840e7e: acpi_quirk_skip_acpi_ac_and_battery (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool acpi_quirk_skip_acpi_ac_and_battery();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/x86/utils.c (0)
Location: drivers/acpi/x86/utils.c:447
Inline: False
Direct callers:
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/battery.c:acpi_battery_init_async
```
**Symbols:**

```
ffffffff82091cee-ffffffff82091d02: acpi_quirk_skip_acpi_ac_and_battery.cold (STB_LOCAL)
ffffffff819777f0-ffffffff819778ae: acpi_quirk_skip_acpi_ac_and_battery (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool acpi_quirk_skip_acpi_ac_and_battery();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/x86/utils.c (0)
Location: drivers/acpi/x86/utils.c:493
Inline: False
Direct callers:
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/battery.c:acpi_battery_init_async
```
**Symbols:**

```
ffffffff821125ca-ffffffff821125de: acpi_quirk_skip_acpi_ac_and_battery.cold (STB_LOCAL)
ffffffff819be340-ffffffff819be3fe: acpi_quirk_skip_acpi_ac_and_battery (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool acpi_quirk_skip_acpi_ac_and_battery();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/x86/utils.c (0)
Location: drivers/acpi/x86/utils.c:492
Inline: False
Direct callers:
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/battery.c:acpi_battery_init_async
```
**Symbols:**

```
ffffffff821f0332-ffffffff821f0346: acpi_quirk_skip_acpi_ac_and_battery.cold (STB_LOCAL)
ffffffff81a08c30-ffffffff81a08cee: acpi_quirk_skip_acpi_ac_and_battery (STB_GLOBAL)
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
