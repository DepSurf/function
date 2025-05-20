# Function: <code>acpi_battery_set_alarm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_battery_set_alarm(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff814b1987)
Location: drivers/acpi/battery.c:539
Inline: False
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_alarm_store
```
**Symbols:**

```
ffffffff814b1987-ffffffff814b19f3: acpi_battery_set_alarm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_battery_set_alarm(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff815012a5)
Location: drivers/acpi/battery.c:539
Inline: False
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_alarm_store
```
**Symbols:**

```
ffffffff815012a5-ffffffff81501311: acpi_battery_set_alarm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_battery_set_alarm(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff81523fc2)
Location: drivers/acpi/battery.c:563
Inline: False
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_alarm_store
```
**Symbols:**

```
ffffffff81523fc2-ffffffff8152402e: acpi_battery_set_alarm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int acpi_battery_set_alarm(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff81536520)
Location: drivers/acpi/battery.c:569
Inline: False
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_alarm_store
```
**Symbols:**

```
ffffffff81536520-ffffffff8153658e: acpi_battery_set_alarm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int acpi_battery_set_alarm(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff815984f0)
Location: drivers/acpi/battery.c:573
Inline: True
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_alarm_store
```
**Symbols:**

```
ffffffff815984f0-ffffffff815985c1: acpi_battery_set_alarm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int acpi_battery_set_alarm(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff815cfaa0)
Location: drivers/acpi/battery.c:600
Inline: True
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_alarm_store
```
**Symbols:**

```
ffffffff815cfaa0-ffffffff815cfb71: acpi_battery_set_alarm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int acpi_battery_set_alarm(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff815e9080)
Location: drivers/acpi/battery.c:613
Inline: True
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_alarm_store
```
**Symbols:**

```
ffffffff815e9080-ffffffff815e9151: acpi_battery_set_alarm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int acpi_battery_set_alarm(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff8161ace0)
Location: drivers/acpi/battery.c:600
Inline: True
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_alarm_store
```
**Symbols:**

```
ffffffff8161ace0-ffffffff8161adb1: acpi_battery_set_alarm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int acpi_battery_set_alarm(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff8163c750)
Location: drivers/acpi/battery.c:623
Inline: True
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_alarm_store
```
**Symbols:**

```
ffffffff8163c750-ffffffff8163c821: acpi_battery_set_alarm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (ffffffff816e98a0)
Location: drivers/acpi/battery.c:623
Inline: True
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_alarm_store
```
**Symbols:**

```
ffffffff816e98a0-ffffffff816e9955: acpi_battery_set_alarm.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (ffffffff81707090)
Location: drivers/acpi/battery.c:612
Inline: True
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_alarm_store
```
**Symbols:**

```
ffffffff81707090-ffffffff81707148: acpi_battery_set_alarm.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (ffffffff816e8690)
Location: drivers/acpi/battery.c:614
Inline: True
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_alarm_store
```
**Symbols:**

```
ffffffff816e8690-ffffffff816e8721: acpi_battery_set_alarm.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (ffffffff81761ce0)
Location: drivers/acpi/battery.c:617
Inline: True
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_alarm_store
```
**Symbols:**

```
ffffffff81761ce0-ffffffff81761d6e: acpi_battery_set_alarm.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (ffffffff81895a80)
Location: drivers/acpi/battery.c:612
Inline: True
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_alarm_store
```
**Symbols:**

```
ffffffff81895a80-ffffffff81895b3c: acpi_battery_set_alarm.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (ffffffff819dd860)
Location: drivers/acpi/battery.c:612
Inline: True
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_alarm_store
```
**Symbols:**

```
ffffffff819dd860-ffffffff819dd919: acpi_battery_set_alarm.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (ffffffff81a25560)
Location: drivers/acpi/battery.c:623
Inline: True
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_alarm_store
```
**Symbols:**

```
ffffffff81a25560-ffffffff81a25619: acpi_battery_set_alarm.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (ffffffff81a703a0)
Location: drivers/acpi/battery.c:623
Inline: True
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_alarm_store
```
**Symbols:**

```
ffffffff81a703a0-ffffffff81a70459: acpi_battery_set_alarm.isra.0 (STB_LOCAL)
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
int acpi_battery_set_alarm(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffff8000107a6c30)
Location: drivers/acpi/battery.c:623
Inline: False
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_alarm_store
```
**Symbols:**

```
ffff8000107a6c30-ffff8000107a6ca4: acpi_battery_set_alarm (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int acpi_battery_set_alarm(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff81630590)
Location: drivers/acpi/battery.c:623
Inline: True
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_alarm_store
```
**Symbols:**

```
ffffffff81630590-ffffffff81630661: acpi_battery_set_alarm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int acpi_battery_set_alarm(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff8164a8d0)
Location: drivers/acpi/battery.c:623
Inline: True
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_alarm_store
```
**Symbols:**

```
ffffffff8164a8d0-ffffffff8164a9a1: acpi_battery_set_alarm (STB_LOCAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
