# Function: <code>check_charging_duration</code>

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
In drivers/power/charger-manager.c (ffffffff81681852)
Location: drivers/power/charger-manager.c:557
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
In drivers/power/charger-manager.c (ffffffff816e2895)
Location: drivers/power/charger-manager.c:557
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
In drivers/power/supply/charger-manager.c (ffffffff81712d05)
Location: drivers/power/supply/charger-manager.c:557
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
In drivers/power/supply/charger-manager.c (ffffffff8172ae61)
Location: drivers/power/supply/charger-manager.c:557
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
In drivers/power/supply/charger-manager.c (ffffffff8179c601)
Location: drivers/power/supply/charger-manager.c:557
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
In drivers/power/supply/charger-manager.c (ffffffff817e3ab8)
Location: drivers/power/supply/charger-manager.c:557
Inline: True
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
In drivers/power/supply/charger-manager.c (ffffffff8180f345)
Location: drivers/power/supply/charger-manager.c:557
Inline: True
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
In drivers/power/supply/charger-manager.c (ffffffff818512ad)
Location: drivers/power/supply/charger-manager.c:555
Inline: True
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
In drivers/power/supply/charger-manager.c (ffffffff81882c9d)
Location: drivers/power/supply/charger-manager.c:555
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int check_charging_duration(struct charger_manager *cm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (0)
Location: drivers/power/supply/charger-manager.c:555
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:_cm_monitor
```
**Symbols:**

```
ffffffff81950660-ffffffff819506fc: check_charging_duration (STB_LOCAL)
ffffffff8195235f-ffffffff819523cf: check_charging_duration.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int check_charging_duration(struct charger_manager *cm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (0)
Location: drivers/power/supply/charger-manager.c:452
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:_cm_monitor
  - drivers/power/supply/charger-manager.c:_cm_monitor
```
**Symbols:**

```
ffffffff81955d50-ffffffff81955dd7: check_charging_duration (STB_LOCAL)
ffffffff81c25416-ffffffff81c25450: check_charging_duration.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int check_charging_duration(struct charger_manager *cm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (0)
Location: drivers/power/supply/charger-manager.c:452
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:_cm_monitor
  - drivers/power/supply/charger-manager.c:_cm_monitor
```
**Symbols:**

```
ffffffff81939b20-ffffffff81939ba7: check_charging_duration (STB_LOCAL)
ffffffff81c174c0-ffffffff81c174fa: check_charging_duration.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int check_charging_duration(struct charger_manager *cm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (0)
Location: drivers/power/supply/charger-manager.c:452
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:_cm_monitor
  - drivers/power/supply/charger-manager.c:_cm_monitor
```
**Symbols:**

```
ffffffff819de2b0-ffffffff819de349: check_charging_duration (STB_LOCAL)
ffffffff81d26487-ffffffff81d264d6: check_charging_duration.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int check_charging_duration(struct charger_manager *cm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (0)
Location: drivers/power/supply/charger-manager.c:452
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:_cm_monitor
  - drivers/power/supply/charger-manager.c:_cm_monitor
```
**Symbols:**

```
ffffffff81b42d30-ffffffff81b42dd2: check_charging_duration (STB_LOCAL)
ffffffff81ef2460-ffffffff81ef24a7: check_charging_duration.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int check_charging_duration(struct charger_manager *cm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (0)
Location: drivers/power/supply/charger-manager.c:452
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:_cm_monitor
  - drivers/power/supply/charger-manager.c:_cm_monitor
```
**Symbols:**

```
ffffffff81cd96e0-ffffffff81cd97a7: check_charging_duration (STB_LOCAL)
ffffffff820a78d7-ffffffff820a78ec: check_charging_duration.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int check_charging_duration(struct charger_manager *cm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (0)
Location: drivers/power/supply/charger-manager.c:452
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:_cm_monitor
  - drivers/power/supply/charger-manager.c:_cm_monitor
```
**Symbols:**

```
ffffffff81d41950-ffffffff81d41a17: check_charging_duration (STB_LOCAL)
ffffffff82128cb8-ffffffff82128ccd: check_charging_duration.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int check_charging_duration(struct charger_manager *cm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (0)
Location: drivers/power/supply/charger-manager.c:452
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:_cm_monitor
  - drivers/power/supply/charger-manager.c:_cm_monitor
```
**Symbols:**

```
ffffffff81df8300-ffffffff81df83c7: check_charging_duration (STB_LOCAL)
ffffffff8220a65f-ffffffff8220a674: check_charging_duration.cold (STB_LOCAL)
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
In drivers/power/supply/charger-manager.c (ffff800010acf708)
Location: drivers/power/supply/charger-manager.c:555
Inline: True
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
In drivers/power/supply/charger-manager.c (c0baffe8)
Location: drivers/power/supply/charger-manager.c:555
Inline: True
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
In drivers/power/supply/charger-manager.c (c000000000bb30c0)
Location: drivers/power/supply/charger-manager.c:555
Inline: True
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
In drivers/power/supply/charger-manager.c (ffffffe0006cc126)
Location: drivers/power/supply/charger-manager.c:555
Inline: True
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
In drivers/power/supply/charger-manager.c (ffffffff8187814d)
Location: drivers/power/supply/charger-manager.c:555
Inline: True
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
In drivers/power/supply/charger-manager.c (ffffffff81893aed)
Location: drivers/power/supply/charger-manager.c:555
Inline: True
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
