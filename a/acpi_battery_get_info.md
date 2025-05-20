# Function: <code>acpi_battery_get_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_battery_get_info(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff814b1b80)
Location: drivers/acpi/battery.c:433
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
```
**Symbols:**

```
ffffffff814b1b80-ffffffff814b1d1e: acpi_battery_get_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_battery_get_info(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff8150149e)
Location: drivers/acpi/battery.c:433
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
```
**Symbols:**

```
ffffffff8150149e-ffffffff81501638: acpi_battery_get_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_battery_get_info(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff81524832)
Location: drivers/acpi/battery.c:471
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
```
**Symbols:**

```
ffffffff81524832-ffffffff81524a00: acpi_battery_get_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int acpi_battery_get_info(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff81536aa0)
Location: drivers/acpi/battery.c:477
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
```
**Symbols:**

```
ffffffff81536aa0-ffffffff81536cec: acpi_battery_get_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int acpi_battery_get_info(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff81598230)
Location: drivers/acpi/battery.c:481
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
```
**Symbols:**

```
ffffffff81598230-ffffffff8159847c: acpi_battery_get_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int acpi_battery_get_info(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (0)
Location: drivers/acpi/battery.c:504
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
```
**Symbols:**

```
ffffffff815cf670-ffffffff815cf8bc: acpi_battery_get_info (STB_LOCAL)
ffffffff815d07b9-ffffffff815d07cd: acpi_battery_get_info.cold.24 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int acpi_battery_get_info(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (0)
Location: drivers/acpi/battery.c:518
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
```
**Symbols:**

```
ffffffff815e8c50-ffffffff815e8e9c: acpi_battery_get_info (STB_LOCAL)
ffffffff815e9ded-ffffffff815e9e01: acpi_battery_get_info.cold.24 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int acpi_battery_get_info(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (0)
Location: drivers/acpi/battery.c:505
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
```
**Symbols:**

```
ffffffff8161ae70-ffffffff8161b0b9: acpi_battery_get_info (STB_LOCAL)
ffffffff8161bb5d-ffffffff8161bb71: acpi_battery_get_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int acpi_battery_get_info(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (0)
Location: drivers/acpi/battery.c:528
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
```
**Symbols:**

```
ffffffff8163c8e0-ffffffff8163cb29: acpi_battery_get_info (STB_LOCAL)
ffffffff8163d600-ffffffff8163d614: acpi_battery_get_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int acpi_battery_get_info(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (0)
Location: drivers/acpi/battery.c:528
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:acpi_battery_notify
```
**Symbols:**

```
ffffffff816e9a10-ffffffff816e9c59: acpi_battery_get_info (STB_LOCAL)
ffffffff816ea7bd-ffffffff816ea7d1: acpi_battery_get_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int acpi_battery_get_info(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (0)
Location: drivers/acpi/battery.c:517
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:acpi_battery_notify
```
**Symbols:**

```
ffffffff81707200-ffffffff8170744c: acpi_battery_get_info (STB_LOCAL)
ffffffff81c0321e-ffffffff81c03232: acpi_battery_get_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int acpi_battery_get_info(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (0)
Location: drivers/acpi/battery.c:515
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:acpi_battery_notify
```
**Symbols:**

```
ffffffff816e87e0-ffffffff816e8a4c: acpi_battery_get_info (STB_LOCAL)
ffffffff81bf4c17-ffffffff81bf4c2b: acpi_battery_get_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int acpi_battery_get_info(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (0)
Location: drivers/acpi/battery.c:518
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:acpi_battery_notify
```
**Symbols:**

```
ffffffff81761e20-ffffffff8176208c: acpi_battery_get_info (STB_LOCAL)
ffffffff81cf1e9d-ffffffff81cf1eb1: acpi_battery_get_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int acpi_battery_get_info(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (0)
Location: drivers/acpi/battery.c:513
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:acpi_battery_notify
```
**Symbols:**

```
ffffffff81895c80-ffffffff81895f0a: acpi_battery_get_info (STB_LOCAL)
ffffffff81eb9e62-ffffffff81eb9e73: acpi_battery_get_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_battery_get_info(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff819dda90)
Location: drivers/acpi/battery.c:513
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:acpi_battery_notify
```
**Symbols:**

```
ffffffff819dda90-ffffffff819ddd3c: acpi_battery_get_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_battery_get_info(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff81a25790)
Location: drivers/acpi/battery.c:524
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:acpi_battery_notify
```
**Symbols:**

```
ffffffff81a25790-ffffffff81a25a33: acpi_battery_get_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_battery_get_info(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff81a705d0)
Location: drivers/acpi/battery.c:524
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:acpi_battery_notify
```
**Symbols:**

```
ffffffff81a705d0-ffffffff81a70873: acpi_battery_get_info (STB_LOCAL)
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
int acpi_battery_get_info(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffff8000107a7168)
Location: drivers/acpi/battery.c:528
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
```
**Symbols:**

```
ffff8000107a7168-ffff8000107a7420: acpi_battery_get_info (STB_LOCAL)
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
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int acpi_battery_get_info(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (0)
Location: drivers/acpi/battery.c:528
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
```
**Symbols:**

```
ffffffff81630720-ffffffff81630969: acpi_battery_get_info (STB_LOCAL)
ffffffff81631440-ffffffff81631454: acpi_battery_get_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int acpi_battery_get_info(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (0)
Location: drivers/acpi/battery.c:528
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
```
**Symbols:**

```
ffffffff8164aa60-ffffffff8164aca9: acpi_battery_get_info (STB_LOCAL)
ffffffff8164b780-ffffffff8164b794: acpi_battery_get_info.cold (STB_LOCAL)
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
