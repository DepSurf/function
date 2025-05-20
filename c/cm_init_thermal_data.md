# Function: <code>cm_init_thermal_data</code>

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
In drivers/power/charger-manager.c (ffffffff81681ffc)
Location: drivers/power/charger-manager.c:1444
Inline: True
Inline callers:
  - drivers/power/charger-manager.c:charger_manager_probe
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
In drivers/power/charger-manager.c (ffffffff816e2f40)
Location: drivers/power/charger-manager.c:1444
Inline: True
Inline callers:
  - drivers/power/charger-manager.c:charger_manager_probe
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
In drivers/power/supply/charger-manager.c (ffffffff817133b0)
Location: drivers/power/supply/charger-manager.c:1444
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
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
In drivers/power/supply/charger-manager.c (ffffffff8172b5ae)
Location: drivers/power/supply/charger-manager.c:1439
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
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
In drivers/power/supply/charger-manager.c (ffffffff8179cd57)
Location: drivers/power/supply/charger-manager.c:1439
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
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
In drivers/power/supply/charger-manager.c (ffffffff817e4243)
Location: drivers/power/supply/charger-manager.c:1439
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
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
In drivers/power/supply/charger-manager.c (ffffffff8180faf4)
Location: drivers/power/supply/charger-manager.c:1426
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
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
In drivers/power/supply/charger-manager.c (ffffffff818517d9)
Location: drivers/power/supply/charger-manager.c:1424
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
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
In drivers/power/supply/charger-manager.c (ffffffff818832b9)
Location: drivers/power/supply/charger-manager.c:1424
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cm_init_thermal_data(struct charger_manager *cm, struct power_supply *fuel_gauge, enum power_supply_property *properties, size_t *num_properties);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff81950860)
Location: drivers/power/supply/charger-manager.c:1424
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff81950860-ffffffff81950943: cm_init_thermal_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cm_init_thermal_data(struct charger_manager *cm, struct power_supply *fuel_gauge, enum power_supply_property *properties, size_t *num_properties);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff81955de0)
Location: drivers/power/supply/charger-manager.c:1233
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff81955de0-ffffffff81955ec3: cm_init_thermal_data (STB_LOCAL)
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
In drivers/power/supply/charger-manager.c (ffffffff8193b15d)
Location: drivers/power/supply/charger-manager.c:1233
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
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
In drivers/power/supply/charger-manager.c (ffffffff819df94d)
Location: drivers/power/supply/charger-manager.c:1233
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
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
In drivers/power/supply/charger-manager.c (ffffffff81b4416d)
Location: drivers/power/supply/charger-manager.c:1230
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
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
In drivers/power/supply/charger-manager.c (ffffffff81cdade1)
Location: drivers/power/supply/charger-manager.c:1230
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
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
In drivers/power/supply/charger-manager.c (ffffffff81d430a0)
Location: drivers/power/supply/charger-manager.c:1230
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
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
In drivers/power/supply/charger-manager.c (ffffffff81df9a66)
Location: drivers/power/supply/charger-manager.c:1230
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
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
In drivers/power/supply/charger-manager.c (ffff800010ad05e4)
Location: drivers/power/supply/charger-manager.c:1424
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (c0bb0e3c)
Location: drivers/power/supply/charger-manager.c:1424
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (c000000000bb4480)
Location: drivers/power/supply/charger-manager.c:1424
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffe0006cce1c)
Location: drivers/power/supply/charger-manager.c:1424
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
</details>
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
In drivers/power/supply/charger-manager.c (ffffffff81878769)
Location: drivers/power/supply/charger-manager.c:1424
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
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
In drivers/power/supply/charger-manager.c (ffffffff81894109)
Location: drivers/power/supply/charger-manager.c:1424
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
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
