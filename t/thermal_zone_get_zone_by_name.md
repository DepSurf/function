# Function: <code>thermal_zone_get_zone_by_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct thermal_zone_device *thermal_zone_get_zone_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81683530)
Location: drivers/thermal/thermal_core.c:2036
Inline: False
Direct callers:
  - drivers/power/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff81683530-ffffffff816835f1: thermal_zone_get_zone_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct thermal_zone_device *thermal_zone_get_zone_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff816e4a20)
Location: drivers/thermal/thermal_core.c:2044
Inline: False
Direct callers:
  - drivers/power/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff816e4a20-ffffffff816e4ae1: thermal_zone_get_zone_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct thermal_zone_device *thermal_zone_get_zone_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81715490)
Location: drivers/thermal/thermal_core.c:1333
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff81715490-ffffffff81715551: thermal_zone_get_zone_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct thermal_zone_device *thermal_zone_get_zone_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8172dde0)
Location: drivers/thermal/thermal_core.c:1372
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff8172dde0-ffffffff8172deaa: thermal_zone_get_zone_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct thermal_zone_device *thermal_zone_get_zone_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8179f410)
Location: drivers/thermal/thermal_core.c:1371
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff8179f410-ffffffff8179f4da: thermal_zone_get_zone_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct thermal_zone_device *thermal_zone_get_zone_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff817e69f0)
Location: drivers/thermal/thermal_core.c:1369
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff817e69f0-ffffffff817e6aba: thermal_zone_get_zone_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct thermal_zone_device *thermal_zone_get_zone_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81812520)
Location: drivers/thermal/thermal_core.c:1374
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff81812520-ffffffff818125ea: thermal_zone_get_zone_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct thermal_zone_device *thermal_zone_get_zone_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff818544b0)
Location: drivers/thermal/thermal_core.c:1429
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff818544b0-ffffffff8185457a: thermal_zone_get_zone_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct thermal_zone_device *thermal_zone_get_zone_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81885f10)
Location: drivers/thermal/thermal_core.c:1439
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff81885f10-ffffffff81885fda: thermal_zone_get_zone_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct thermal_zone_device *thermal_zone_get_zone_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81954510)
Location: drivers/thermal/thermal_core.c:1427
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:cm_init_thermal_data
```
**Symbols:**

```
ffffffff81954510-ffffffff819545da: thermal_zone_get_zone_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct thermal_zone_device *thermal_zone_get_zone_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81959480)
Location: drivers/thermal/thermal_core.c:1501
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:cm_init_thermal_data
```
**Symbols:**

```
ffffffff81959480-ffffffff8195954a: thermal_zone_get_zone_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct thermal_zone_device *thermal_zone_get_zone_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8193cfa0)
Location: drivers/thermal/thermal_core.c:1443
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff8193cfa0-ffffffff8193d06a: thermal_zone_get_zone_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct thermal_zone_device *thermal_zone_get_zone_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff819e1840)
Location: drivers/thermal/thermal_core.c:1398
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff819e1840-ffffffff819e190a: thermal_zone_get_zone_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct thermal_zone_device *thermal_zone_get_zone_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81b468f0)
Location: drivers/thermal/thermal_core.c:1401
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff81b468f0-ffffffff81b469c5: thermal_zone_get_zone_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct thermal_zone_device *thermal_zone_get_zone_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81cddf60)
Location: drivers/thermal/thermal_core.c:1439
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff81cddf60-ffffffff81cde035: thermal_zone_get_zone_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct thermal_zone_device *thermal_zone_get_zone_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81d465b0)
Location: drivers/thermal/thermal_core.c:1470
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff81d465b0-ffffffff81d46685: thermal_zone_get_zone_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct thermal_zone_device *thermal_zone_get_zone_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81dfcf90)
Location: drivers/thermal/thermal_core.c:1538
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff81dfcf90-ffffffff81dfd065: thermal_zone_get_zone_by_name (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct thermal_zone_device *thermal_zone_get_zone_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffff800010ad2f78)
Location: drivers/thermal/thermal_core.c:1439
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/thermal/of-thermal.c:of_thermal_destroy_zones
  - drivers/thermal/of-thermal.c:thermal_zone_of_sensor_register
```
**Symbols:**

```
ffff800010ad2f78-ffff800010ad305c: thermal_zone_get_zone_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct thermal_zone_device *thermal_zone_get_zone_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (c0bb36b4)
Location: drivers/thermal/thermal_core.c:1439
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/thermal/of-thermal.c:of_thermal_destroy_zones
  - drivers/thermal/of-thermal.c:thermal_zone_of_sensor_register
```
**Symbols:**

```
c0bb36b4-c0bb3760: thermal_zone_get_zone_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct thermal_zone_device *thermal_zone_get_zone_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (c000000000bb7880)
Location: drivers/thermal/thermal_core.c:1439
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/thermal/of-thermal.c:of_thermal_destroy_zones
  - drivers/thermal/of-thermal.c:thermal_zone_of_sensor_register
```
**Symbols:**

```
c000000000bb7880-c000000000bb79c8: thermal_zone_get_zone_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct thermal_zone_device *thermal_zone_get_zone_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffe0006cf484)
Location: drivers/thermal/thermal_core.c:1439
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/thermal/of-thermal.c:of_thermal_destroy_zones
  - drivers/thermal/of-thermal.c:thermal_zone_of_sensor_register
```
**Symbols:**

```
ffffffe0006cf484-ffffffe0006cf53a: thermal_zone_get_zone_by_name (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct thermal_zone_device *thermal_zone_get_zone_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8182bd90)
Location: drivers/thermal/thermal_core.c:1439
Inline: True
```
**Symbols:**

```
ffffffff8182bd90-ffffffff8182be5a: thermal_zone_get_zone_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct thermal_zone_device *thermal_zone_get_zone_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff817f3420)
Location: drivers/thermal/thermal_core.c:1439
Inline: True
```
**Symbols:**

```
ffffffff817f3420-ffffffff817f34ea: thermal_zone_get_zone_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct thermal_zone_device *thermal_zone_get_zone_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8187b3c0)
Location: drivers/thermal/thermal_core.c:1439
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff8187b3c0-ffffffff8187b48a: thermal_zone_get_zone_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct thermal_zone_device *thermal_zone_get_zone_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81896dc0)
Location: drivers/thermal/thermal_core.c:1439
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff81896dc0-ffffffff81896e8a: thermal_zone_get_zone_by_name (STB_GLOBAL)
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
