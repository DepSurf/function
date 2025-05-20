# Function: <code>cm_get_battery_temperature</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/charger-manager.c (ffffffff81680f00)
Location: drivers/power/charger-manager.c:612
Inline: True
Direct callers:
  - drivers/power/charger-manager.c:charger_get_property
```
**Symbols:**

```
ffffffff81680f00-ffffffff81680f8d: cm_get_battery_temperature.isra.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/charger-manager.c (ffffffff816e1cf0)
Location: drivers/power/charger-manager.c:612
Inline: True
Direct callers:
  - drivers/power/charger-manager.c:charger_get_property
```
**Symbols:**

```
ffffffff816e1cf0-ffffffff816e1d7e: cm_get_battery_temperature.isra.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff81712160)
Location: drivers/power/supply/charger-manager.c:612
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_get_property
```
**Symbols:**

```
ffffffff81712160-ffffffff817121ee: cm_get_battery_temperature.isra.24 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff8172a530)
Location: drivers/power/supply/charger-manager.c:612
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_get_property
```
**Symbols:**

```
ffffffff8172a530-ffffffff8172a5be: cm_get_battery_temperature.isra.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff8179bcc0)
Location: drivers/power/supply/charger-manager.c:612
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_get_property
```
**Symbols:**

```
ffffffff8179bcc0-ffffffff8179bd4e: cm_get_battery_temperature.isra.24 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff817e3210)
Location: drivers/power/supply/charger-manager.c:612
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_get_property
```
**Symbols:**

```
ffffffff817e3210-ffffffff817e329e: cm_get_battery_temperature.isra.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff8180ea50)
Location: drivers/power/supply/charger-manager.c:612
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_get_property
```
**Symbols:**

```
ffffffff8180ea50-ffffffff8180eade: cm_get_battery_temperature.isra.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff81850640)
Location: drivers/power/supply/charger-manager.c:610
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_get_property
```
**Symbols:**

```
ffffffff81850640-ffffffff818506d7: cm_get_battery_temperature.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff81882440)
Location: drivers/power/supply/charger-manager.c:610
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_get_property
```
**Symbols:**

```
ffffffff81882440-ffffffff818824d7: cm_get_battery_temperature.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cm_get_battery_temperature(struct charger_manager *cm, int *temp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff81950d90)
Location: drivers/power/supply/charger-manager.c:610
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:_cm_monitor
```
**Symbols:**

```
ffffffff81950d90-ffffffff81950e26: cm_get_battery_temperature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cm_get_battery_temperature(struct charger_manager *cm, int *temp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff819562c0)
Location: drivers/power/supply/charger-manager.c:502
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:_cm_monitor
```
**Symbols:**

```
ffffffff819562c0-ffffffff81956356: cm_get_battery_temperature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cm_get_battery_temperature(struct charger_manager *cm, int *temp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff81939e00)
Location: drivers/power/supply/charger-manager.c:502
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:_cm_monitor
```
**Symbols:**

```
ffffffff81939e00-ffffffff81939e9f: cm_get_battery_temperature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int cm_get_battery_temperature(struct charger_manager *cm, int *temp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (0)
Location: drivers/power/supply/charger-manager.c:502
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:_cm_monitor
```
**Symbols:**

```
ffffffff819de530-ffffffff819de5e1: cm_get_battery_temperature (STB_LOCAL)
ffffffff81d265b5-ffffffff81d265ca: cm_get_battery_temperature.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int cm_get_battery_temperature(struct charger_manager *cm, int *temp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (0)
Location: drivers/power/supply/charger-manager.c:502
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:_cm_monitor
```
**Symbols:**

```
ffffffff81b42f90-ffffffff81b4305d: cm_get_battery_temperature (STB_LOCAL)
ffffffff81ef2525-ffffffff81ef253a: cm_get_battery_temperature.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int cm_get_battery_temperature(struct charger_manager *cm, int *temp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (0)
Location: drivers/power/supply/charger-manager.c:502
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:_cm_monitor
```
**Symbols:**

```
ffffffff81cd99c0-ffffffff81cd9a8d: cm_get_battery_temperature (STB_LOCAL)
ffffffff820a7930-ffffffff820a7945: cm_get_battery_temperature.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int cm_get_battery_temperature(struct charger_manager *cm, int *temp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (0)
Location: drivers/power/supply/charger-manager.c:502
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:_cm_monitor
```
**Symbols:**

```
ffffffff81d41c30-ffffffff81d41cfd: cm_get_battery_temperature (STB_LOCAL)
ffffffff82128d11-ffffffff82128d26: cm_get_battery_temperature.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int cm_get_battery_temperature(struct charger_manager *cm, int *temp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (0)
Location: drivers/power/supply/charger-manager.c:502
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:_cm_monitor
```
**Symbols:**

```
ffffffff81df85e0-ffffffff81df86ad: cm_get_battery_temperature (STB_LOCAL)
ffffffff8220a6b8-ffffffff8220a6cd: cm_get_battery_temperature.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffff800010aced40)
Location: drivers/power/supply/charger-manager.c:610
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_get_property
```
**Symbols:**

```
ffff800010aced40-ffff800010acedf8: cm_get_battery_temperature.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cm_get_battery_temperature(struct charger_manager *cm, int *temp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (c0bae9a8)
Location: drivers/power/supply/charger-manager.c:610
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_get_property
```
**Symbols:**

```
c0bae9a8-c0baea44: cm_get_battery_temperature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (c000000000bb1ff0)
Location: drivers/power/supply/charger-manager.c:610
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_get_property
```
**Symbols:**

```
c000000000bb1ff0-c000000000bb2120: cm_get_battery_temperature.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffe0006cb8ea)
Location: drivers/power/supply/charger-manager.c:610
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_get_property
```
**Symbols:**

```
ffffffe0006cb8ea-ffffffe0006cb97c: cm_get_battery_temperature.isra.0 (STB_LOCAL)
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
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff818778f0)
Location: drivers/power/supply/charger-manager.c:610
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_get_property
```
**Symbols:**

```
ffffffff818778f0-ffffffff81877987: cm_get_battery_temperature.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff81893290)
Location: drivers/power/supply/charger-manager.c:610
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_get_property
```
**Symbols:**

```
ffffffff81893290-ffffffff81893327: cm_get_battery_temperature.isra.0 (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
