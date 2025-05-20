# Function: <code>sysfs_add_battery</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sysfs_add_battery(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff814b1d1e)
Location: drivers/acpi/battery.c:599
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
```
**Symbols:**

```
ffffffff814b1d1e-ffffffff814b1de3: sysfs_add_battery (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sysfs_add_battery(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff81501638)
Location: drivers/acpi/battery.c:599
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
```
**Symbols:**

```
ffffffff81501638-ffffffff815016fd: sysfs_add_battery (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sysfs_add_battery(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff81524378)
Location: drivers/acpi/battery.c:623
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
```
**Symbols:**

```
ffffffff81524378-ffffffff8152443d: sysfs_add_battery (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sysfs_add_battery(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff81536680)
Location: drivers/acpi/battery.c:629
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
```
**Symbols:**

```
ffffffff81536680-ffffffff8153675a: sysfs_add_battery (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sysfs_add_battery(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff81597e10)
Location: drivers/acpi/battery.c:633
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
```
**Symbols:**

```
ffffffff81597e10-ffffffff81597eea: sysfs_add_battery (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sysfs_add_battery(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (0)
Location: drivers/acpi/battery.c:794
Inline: True
Direct callers:
  - drivers/acpi/battery.c:battery_notify
```
**Symbols:**

```
ffffffff815cfc90-ffffffff815cfe29: sysfs_add_battery (STB_LOCAL)
ffffffff815d0821-ffffffff815d083c: sysfs_add_battery.cold.27 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sysfs_add_battery(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (ffffffff815e9344)
Location: drivers/acpi/battery.c:807
Inline: True
Direct callers:
  - drivers/acpi/battery.c:battery_notify
```
**Symbols:**

```
ffffffff815e9270-ffffffff815e9410: sysfs_add_battery (STB_LOCAL)
ffffffff815e9e55-ffffffff815e9e70: sysfs_add_battery.cold.27 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int sysfs_add_battery(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (0)
Location: drivers/acpi/battery.c:794
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
```
**Symbols:**

```
ffffffff8161aaa0-ffffffff8161ac3f: sysfs_add_battery (STB_LOCAL)
ffffffff8161bb01-ffffffff8161bb20: sysfs_add_battery.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int sysfs_add_battery(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (0)
Location: drivers/acpi/battery.c:817
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
```
**Symbols:**

```
ffffffff8163c4d0-ffffffff8163c6a1: sysfs_add_battery (STB_LOCAL)
ffffffff8163d5a4-ffffffff8163d5c3: sysfs_add_battery.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int sysfs_add_battery(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (0)
Location: drivers/acpi/battery.c:817
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:acpi_battery_notify
```
**Symbols:**

```
ffffffff816e9360-ffffffff816e9531: sysfs_add_battery (STB_LOCAL)
ffffffff816ea786-ffffffff816ea7a5: sysfs_add_battery.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int sysfs_add_battery(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (0)
Location: drivers/acpi/battery.c:806
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:acpi_battery_notify
```
**Symbols:**

```
ffffffff81706b40-ffffffff81706d14: sysfs_add_battery (STB_LOCAL)
ffffffff81c031e7-ffffffff81c03206: sysfs_add_battery.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int sysfs_add_battery(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (0)
Location: drivers/acpi/battery.c:812
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:acpi_battery_notify
```
**Symbols:**

```
ffffffff816e8160-ffffffff816e8318: sysfs_add_battery (STB_LOCAL)
ffffffff81bf4be0-ffffffff81bf4bff: sysfs_add_battery.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sysfs_add_battery(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (0)
Location: drivers/acpi/battery.c:815
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:acpi_battery_notify
```
**Symbols:**

```
ffffffff817617a0-ffffffff81761958: sysfs_add_battery (STB_LOCAL)
ffffffff81cf1e51-ffffffff81cf1e70: sysfs_add_battery.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sysfs_add_battery(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (0)
Location: drivers/acpi/battery.c:810
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:acpi_battery_notify
```
**Symbols:**

```
ffffffff81895570-ffffffff8189573b: sysfs_add_battery (STB_LOCAL)
ffffffff81eb9e16-ffffffff81eb9e35: sysfs_add_battery.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sysfs_add_battery(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff819dd350)
Location: drivers/acpi/battery.c:813
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:acpi_battery_notify
```
**Symbols:**

```
ffffffff819dd350-ffffffff819dd547: sysfs_add_battery (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sysfs_add_battery(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff81a25060)
Location: drivers/acpi/battery.c:824
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:acpi_battery_notify
```
**Symbols:**

```
ffffffff81a25060-ffffffff81a25257: sysfs_add_battery (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sysfs_add_battery(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff81a6fea0)
Location: drivers/acpi/battery.c:824
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:acpi_battery_notify
```
**Symbols:**

```
ffffffff81a6fea0-ffffffff81a70097: sysfs_add_battery (STB_LOCAL)
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
int sysfs_add_battery(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffff8000107a7510)
Location: drivers/acpi/battery.c:817
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
```
**Symbols:**

```
ffff8000107a7510-ffff8000107a7708: sysfs_add_battery (STB_LOCAL)
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
int sysfs_add_battery(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (0)
Location: drivers/acpi/battery.c:817
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
```
**Symbols:**

```
ffffffff81630310-ffffffff816304e1: sysfs_add_battery (STB_LOCAL)
ffffffff816313e4-ffffffff81631403: sysfs_add_battery.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int sysfs_add_battery(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (0)
Location: drivers/acpi/battery.c:817
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
```
**Symbols:**

```
ffffffff8164a650-ffffffff8164a821: sysfs_add_battery (STB_LOCAL)
ffffffff8164b724-ffffffff8164b743: sysfs_add_battery.cold (STB_LOCAL)
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
