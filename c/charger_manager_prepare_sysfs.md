# Function: <code>charger_manager_prepare_sysfs</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff8180fbd4)
Location: drivers/power/supply/charger-manager.c:1366
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
In drivers/power/supply/charger-manager.c (ffffffff818518a6)
Location: drivers/power/supply/charger-manager.c:1364
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
In drivers/power/supply/charger-manager.c (ffffffff81883386)
Location: drivers/power/supply/charger-manager.c:1364
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int charger_manager_prepare_sysfs(struct charger_manager *cm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (0)
Location: drivers/power/supply/charger-manager.c:1364
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff81950950-ffffffff819509bb: charger_manager_prepare_sysfs (STB_LOCAL)
ffffffff819523fd-ffffffff81952532: charger_manager_prepare_sysfs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int charger_manager_prepare_sysfs(struct charger_manager *cm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (0)
Location: drivers/power/supply/charger-manager.c:1173
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff81955ed0-ffffffff81955f3b: charger_manager_prepare_sysfs (STB_LOCAL)
ffffffff81c25450-ffffffff81c25585: charger_manager_prepare_sysfs.cold (STB_LOCAL)
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
In drivers/power/supply/charger-manager.c (ffffffff8193b1fa)
Location: drivers/power/supply/charger-manager.c:1173
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
In drivers/power/supply/charger-manager.c (ffffffff819dfa17)
Location: drivers/power/supply/charger-manager.c:1173
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
In drivers/power/supply/charger-manager.c (ffffffff81b44239)
Location: drivers/power/supply/charger-manager.c:1170
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
In drivers/power/supply/charger-manager.c (ffffffff81cdaea3)
Location: drivers/power/supply/charger-manager.c:1170
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
In drivers/power/supply/charger-manager.c (ffffffff81d43172)
Location: drivers/power/supply/charger-manager.c:1170
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
In drivers/power/supply/charger-manager.c (ffffffff81df9b00)
Location: drivers/power/supply/charger-manager.c:1170
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
In drivers/power/supply/charger-manager.c (ffff800010ad0694)
Location: drivers/power/supply/charger-manager.c:1364
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
In drivers/power/supply/charger-manager.c (c0bb0ef8)
Location: drivers/power/supply/charger-manager.c:1364
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
In drivers/power/supply/charger-manager.c (c000000000bb456c)
Location: drivers/power/supply/charger-manager.c:1364
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
In drivers/power/supply/charger-manager.c (ffffffe0006ccebc)
Location: drivers/power/supply/charger-manager.c:1364
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
In drivers/power/supply/charger-manager.c (ffffffff81878836)
Location: drivers/power/supply/charger-manager.c:1364
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
In drivers/power/supply/charger-manager.c (ffffffff818941d6)
Location: drivers/power/supply/charger-manager.c:1364
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
