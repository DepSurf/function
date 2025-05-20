# Function: <code>acpi_add_power_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_add_power_resource(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff814890df)
Location: drivers/acpi/power.c:781
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/power.c:acpi_extract_power_resources
```
**Symbols:**

```
ffffffff814890df-ffffffff81489378: acpi_add_power_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_add_power_resource(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff814d7ec3)
Location: drivers/acpi/power.c:781
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/power.c:acpi_extract_power_resources
```
**Symbols:**

```
ffffffff814d7ec3-ffffffff814d816b: acpi_add_power_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_add_power_resource(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff814fa5ab)
Location: drivers/acpi/power.c:781
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/power.c:acpi_extract_power_resources
```
**Symbols:**

```
ffffffff814fa5ab-ffffffff814fa853: acpi_add_power_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int acpi_add_power_resource(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff81509820)
Location: drivers/acpi/power.c:782
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/power.c:acpi_extract_power_resources
```
**Symbols:**

```
ffffffff81509820-ffffffff81509ca0: acpi_add_power_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int acpi_add_power_resource(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff8154beb0)
Location: drivers/acpi/power.c:782
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/power.c:acpi_extract_power_resources
```
**Symbols:**

```
ffffffff8154beb0-ffffffff8154c195: acpi_add_power_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int acpi_add_power_resource(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (0)
Location: drivers/acpi/power.c:782
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/power.c:acpi_extract_power_resources
```
**Symbols:**

```
ffffffff81582a35-ffffffff81582b65: acpi_add_power_resource.cold.12 (STB_LOCAL)
ffffffff815824e0-ffffffff815826a9: acpi_add_power_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int acpi_add_power_resource(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (0)
Location: drivers/acpi/power.c:804
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/power.c:acpi_extract_power_resources
```
**Symbols:**

```
ffffffff8159ab65-ffffffff8159ac96: acpi_add_power_resource.cold.13 (STB_LOCAL)
ffffffff8159a5a0-ffffffff8159a754: acpi_add_power_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int acpi_add_power_resource(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (0)
Location: drivers/acpi/power.c:925
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/power.c:acpi_extract_power_resources
```
**Symbols:**

```
ffffffff815cc269-ffffffff815cc399: acpi_add_power_resource.cold (STB_LOCAL)
ffffffff815cbce0-ffffffff815cbeaa: acpi_add_power_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int acpi_add_power_resource(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (0)
Location: drivers/acpi/power.c:925
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/power.c:acpi_extract_power_resources
```
**Symbols:**

```
ffffffff815ed4e9-ffffffff815ed619: acpi_add_power_resource.cold (STB_LOCAL)
ffffffff815ecf60-ffffffff815ed12a: acpi_add_power_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int acpi_add_power_resource(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (0)
Location: drivers/acpi/power.c:923
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/power.c:acpi_extract_power_resources
```
**Symbols:**

```
ffffffff81699089-ffffffff816991b9: acpi_add_power_resource.cold (STB_LOCAL)
ffffffff81698b60-ffffffff81698d81: acpi_add_power_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int acpi_add_power_resource(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (0)
Location: drivers/acpi/power.c:923
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/power.c:acpi_extract_power_resources
```
**Symbols:**

```
ffffffff81c02279-ffffffff81c023af: acpi_add_power_resource.cold (STB_LOCAL)
ffffffff816b5ca0-ffffffff816b5eca: acpi_add_power_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct acpi_device *acpi_add_power_resource(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (0)
Location: drivers/acpi/power.c:915
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/power.c:acpi_extract_power_resources
```
**Symbols:**

```
ffffffff81bf3a71-ffffffff81bf3ba8: acpi_add_power_resource.cold (STB_LOCAL)
ffffffff81697c60-ffffffff81697e69: acpi_add_power_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct acpi_device *acpi_add_power_resource(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (0)
Location: drivers/acpi/power.c:915
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/power.c:acpi_extract_power_resources
```
**Symbols:**

```
ffffffff81cf07e0-ffffffff81cf0913: acpi_add_power_resource.cold (STB_LOCAL)
ffffffff8170da40-ffffffff8170dc1b: acpi_add_power_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct acpi_device *acpi_add_power_resource(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (0)
Location: drivers/acpi/power.c:929
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/power.c:acpi_extract_power_resources
```
**Symbols:**

```
ffffffff81eb8669-ffffffff81eb877a: acpi_add_power_resource.cold (STB_LOCAL)
ffffffff8183c3b0-ffffffff8183c5ad: acpi_add_power_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct acpi_device *acpi_add_power_resource(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff81971c60)
Location: drivers/acpi/power.c:929
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/power.c:acpi_extract_power_resources
```
**Symbols:**

```
ffffffff81971c60-ffffffff81971f7c: acpi_add_power_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct acpi_device *acpi_add_power_resource(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff819b8300)
Location: drivers/acpi/power.c:930
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/power.c:acpi_extract_power_resources
```
**Symbols:**

```
ffffffff819b8300-ffffffff819b861c: acpi_add_power_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct acpi_device *acpi_add_power_resource(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff81a028d0)
Location: drivers/acpi/power.c:930
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/power.c:acpi_extract_power_resources
```
**Symbols:**

```
ffffffff81a028d0-ffffffff81a02c1b: acpi_add_power_resource (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int acpi_add_power_resource(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffff800010778620)
Location: drivers/acpi/power.c:925
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/power.c:acpi_extract_power_resources
```
**Symbols:**

```
ffff800010778620-ffff8000107788b0: acpi_add_power_resource (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int acpi_add_power_resource(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (0)
Location: drivers/acpi/power.c:925
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/power.c:acpi_extract_power_resources
```
**Symbols:**

```
ffffffff815dc63c-ffffffff815dc76c: acpi_add_power_resource.cold (STB_LOCAL)
ffffffff815dc050-ffffffff815dc21a: acpi_add_power_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int acpi_add_power_resource(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (0)
Location: drivers/acpi/power.c:925
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/power.c:acpi_extract_power_resources
```
**Symbols:**

```
ffffffff815c7c7c-ffffffff815c7dac: acpi_add_power_resource.cold (STB_LOCAL)
ffffffff815c7690-ffffffff815c785a: acpi_add_power_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int acpi_add_power_resource(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (0)
Location: drivers/acpi/power.c:925
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/power.c:acpi_extract_power_resources
```
**Symbols:**

```
ffffffff815e17c9-ffffffff815e18f9: acpi_add_power_resource.cold (STB_LOCAL)
ffffffff815e1240-ffffffff815e140a: acpi_add_power_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int acpi_add_power_resource(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (0)
Location: drivers/acpi/power.c:925
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/power.c:acpi_extract_power_resources
```
**Symbols:**

```
ffffffff815fb689-ffffffff815fb7b9: acpi_add_power_resource.cold (STB_LOCAL)
ffffffff815fb100-ffffffff815fb2ca: acpi_add_power_resource (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
<b>Return type changed. </b>
<code>int</code> ➡️ <code>struct acpi_device *</code>
</li>
</ul>
</details>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
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
