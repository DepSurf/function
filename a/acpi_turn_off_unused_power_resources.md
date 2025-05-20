# Function: <code>acpi_turn_off_unused_power_resources</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void acpi_turn_off_unused_power_resources();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff81509f10)
Location: drivers/acpi/power.c:871
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_pm_end
```
**Symbols:**

```
ffffffff81509f10-ffffffff81509ffe: acpi_turn_off_unused_power_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void acpi_turn_off_unused_power_resources();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff8154c410)
Location: drivers/acpi/power.c:871
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_pm_end
```
**Symbols:**

```
ffffffff8154c410-ffffffff8154c4f6: acpi_turn_off_unused_power_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void acpi_turn_off_unused_power_resources();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff81582930)
Location: drivers/acpi/power.c:871
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_pm_end
```
**Symbols:**

```
ffffffff81582930-ffffffff81582a16: acpi_turn_off_unused_power_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_turn_off_unused_power_resources();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff8159aa60)
Location: drivers/acpi/power.c:893
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_pm_end
```
**Symbols:**

```
ffffffff8159aa60-ffffffff8159ab46: acpi_turn_off_unused_power_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void acpi_turn_off_unused_power_resources();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (0)
Location: drivers/acpi/power.c:1015
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_pm_end
```
**Symbols:**

```
ffffffff815cc3b9-ffffffff815cc3e1: acpi_turn_off_unused_power_resources.cold (STB_LOCAL)
ffffffff815cc170-ffffffff815cc22f: acpi_turn_off_unused_power_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void acpi_turn_off_unused_power_resources();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (0)
Location: drivers/acpi/power.c:1015
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_pm_end
```
**Symbols:**

```
ffffffff815ed639-ffffffff815ed661: acpi_turn_off_unused_power_resources.cold (STB_LOCAL)
ffffffff815ed3f0-ffffffff815ed4af: acpi_turn_off_unused_power_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void acpi_turn_off_unused_power_resources();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (0)
Location: drivers/acpi/power.c:1013
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_pm_end
```
**Symbols:**

```
ffffffff816991d9-ffffffff816991f9: acpi_turn_off_unused_power_resources.cold (STB_LOCAL)
ffffffff81698f90-ffffffff8169904f: acpi_turn_off_unused_power_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void acpi_turn_off_unused_power_resources();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (0)
Location: drivers/acpi/power.c:1013
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_pm_end
```
**Symbols:**

```
ffffffff81c023cf-ffffffff81c023ef: acpi_turn_off_unused_power_resources.cold (STB_LOCAL)
ffffffff816b60d0-ffffffff816b618f: acpi_turn_off_unused_power_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void acpi_turn_off_unused_power_resources(bool init);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (0)
Location: drivers/acpi/power.c:1036
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/scan.c:acpi_scan_init
```
**Symbols:**

```
ffffffff81bf3bc8-ffffffff81bf3be8: acpi_turn_off_unused_power_resources.cold (STB_LOCAL)
ffffffff81698160-ffffffff8169823f: acpi_turn_off_unused_power_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_turn_off_unused_power_resources();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff8170df00)
Location: drivers/acpi/power.c:1005
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/scan.c:acpi_scan_init
```
**Symbols:**

```
ffffffff8170df00-ffffffff8170dfbe: acpi_turn_off_unused_power_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_turn_off_unused_power_resources();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff8183c880)
Location: drivers/acpi/power.c:1023
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/scan.c:acpi_scan_init
```
**Symbols:**

```
ffffffff8183c880-ffffffff8183c94a: acpi_turn_off_unused_power_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_turn_off_unused_power_resources();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff81972280)
Location: drivers/acpi/power.c:1028
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/scan.c:acpi_scan_init
```
**Symbols:**

```
ffffffff81972280-ffffffff8197234a: acpi_turn_off_unused_power_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_turn_off_unused_power_resources();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff819b8930)
Location: drivers/acpi/power.c:1044
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/scan.c:acpi_scan_init
```
**Symbols:**

```
ffffffff819b8930-ffffffff819b8a1f: acpi_turn_off_unused_power_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_turn_off_unused_power_resources();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff81a02f60)
Location: drivers/acpi/power.c:1044
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/scan.c:acpi_scan_init
```
**Symbols:**

```
ffffffff81a02f60-ffffffff81a0304f: acpi_turn_off_unused_power_resources (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void acpi_turn_off_unused_power_resources();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (0)
Location: drivers/acpi/power.c:1015
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_pm_end
```
**Symbols:**

```
ffffffff815dc78c-ffffffff815dc7b8: acpi_turn_off_unused_power_resources.cold (STB_LOCAL)
ffffffff815dc4e0-ffffffff815dc59f: acpi_turn_off_unused_power_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void acpi_turn_off_unused_power_resources();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (0)
Location: drivers/acpi/power.c:1015
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_pm_end
```
**Symbols:**

```
ffffffff815c7dcc-ffffffff815c7df8: acpi_turn_off_unused_power_resources.cold (STB_LOCAL)
ffffffff815c7b20-ffffffff815c7bdf: acpi_turn_off_unused_power_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void acpi_turn_off_unused_power_resources();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (0)
Location: drivers/acpi/power.c:1015
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_pm_end
```
**Symbols:**

```
ffffffff815e1919-ffffffff815e1941: acpi_turn_off_unused_power_resources.cold (STB_LOCAL)
ffffffff815e16d0-ffffffff815e178f: acpi_turn_off_unused_power_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void acpi_turn_off_unused_power_resources();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (0)
Location: drivers/acpi/power.c:1015
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_pm_end
```
**Symbols:**

```
ffffffff815fb7d9-ffffffff815fb801: acpi_turn_off_unused_power_resources.cold (STB_LOCAL)
ffffffff815fb590-ffffffff815fb64f: acpi_turn_off_unused_power_resources (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool init</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool init</code>
</li>
</ul>
</details>
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
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
