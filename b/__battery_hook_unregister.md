# Function: <code>__battery_hook_unregister</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __battery_hook_unregister(struct acpi_battery_hook *hook, int lock);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (0)
Location: drivers/acpi/battery.c:673
Inline: True
Direct callers:
  - drivers/acpi/battery.c:battery_hook_exit
  - drivers/acpi/battery.c:battery_hook_unregister
```
**Symbols:**

```
ffffffff815cf930-ffffffff815cf9d8: __battery_hook_unregister (STB_LOCAL)
ffffffff815d07cd-ffffffff815d07e4: __battery_hook_unregister.cold.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __battery_hook_unregister(struct acpi_battery_hook *hook, int lock);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (ffffffff815e9e01)
Location: drivers/acpi/battery.c:686
Inline: True
Direct callers:
  - drivers/acpi/battery.c:battery_hook_exit
  - drivers/acpi/battery.c:battery_hook_unregister
```
**Symbols:**

```
ffffffff815e8f10-ffffffff815e8fb8: __battery_hook_unregister (STB_LOCAL)
ffffffff815e9e01-ffffffff815e9e18: __battery_hook_unregister.cold.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __battery_hook_unregister(struct acpi_battery_hook *hook, int lock);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (ffffffff8161baea)
Location: drivers/acpi/battery.c:673
Inline: True
Direct callers:
  - drivers/acpi/battery.c:sysfs_add_battery
  - drivers/acpi/battery.c:battery_hook_exit
  - drivers/acpi/battery.c:battery_hook_unregister
```
**Symbols:**

```
ffffffff8161a9d0-ffffffff8161aa71: __battery_hook_unregister (STB_LOCAL)
ffffffff8161baea-ffffffff8161bb01: __battery_hook_unregister.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __battery_hook_unregister(struct acpi_battery_hook *hook, int lock);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (ffffffff8163d58d)
Location: drivers/acpi/battery.c:696
Inline: True
Direct callers:
  - drivers/acpi/battery.c:sysfs_add_battery
  - drivers/acpi/battery.c:battery_hook_exit
  - drivers/acpi/battery.c:battery_hook_unregister
```
**Symbols:**

```
ffffffff8163c400-ffffffff8163c4a1: __battery_hook_unregister (STB_LOCAL)
ffffffff8163d58d-ffffffff8163d5a4: __battery_hook_unregister.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void __battery_hook_unregister(struct acpi_battery_hook *hook, int lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (0)
Location: drivers/acpi/battery.c:696
Inline: False
Direct callers:
  - drivers/acpi/battery.c:sysfs_add_battery
  - drivers/acpi/battery.c:battery_hook_exit
  - drivers/acpi/battery.c:battery_hook_register
  - drivers/acpi/battery.c:battery_hook_unregister
```
**Symbols:**

```
ffffffff816e90d0-ffffffff816e9171: __battery_hook_unregister (STB_LOCAL)
ffffffff816ea732-ffffffff816ea749: __battery_hook_unregister.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void __battery_hook_unregister(struct acpi_battery_hook *hook, int lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (0)
Location: drivers/acpi/battery.c:685
Inline: False
Direct callers:
  - drivers/acpi/battery.c:sysfs_add_battery
  - drivers/acpi/battery.c:battery_hook_exit
  - drivers/acpi/battery.c:battery_hook_register
  - drivers/acpi/battery.c:battery_hook_unregister
```
**Symbols:**

```
ffffffff817068b0-ffffffff81706951: __battery_hook_unregister (STB_LOCAL)
ffffffff81c03193-ffffffff81c031aa: __battery_hook_unregister.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __battery_hook_unregister(struct acpi_battery_hook *hook, int lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (0)
Location: drivers/acpi/battery.c:691
Inline: False
Direct callers:
  - drivers/acpi/battery.c:sysfs_add_battery
  - drivers/acpi/battery.c:battery_hook_exit
  - drivers/acpi/battery.c:battery_hook_register
  - drivers/acpi/battery.c:battery_hook_unregister
```
**Symbols:**

```
ffffffff816e7ed0-ffffffff816e7f71: __battery_hook_unregister (STB_LOCAL)
ffffffff81bf4b8c-ffffffff81bf4ba3: __battery_hook_unregister.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __battery_hook_unregister(struct acpi_battery_hook *hook, int lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (0)
Location: drivers/acpi/battery.c:694
Inline: False
Direct callers:
  - drivers/acpi/battery.c:sysfs_add_battery
  - drivers/acpi/battery.c:battery_hook_exit
  - drivers/acpi/battery.c:battery_hook_register
  - drivers/acpi/battery.c:battery_hook_unregister
```
**Symbols:**

```
ffffffff81761510-ffffffff817615b1: __battery_hook_unregister (STB_LOCAL)
ffffffff81cf1dfd-ffffffff81cf1e14: __battery_hook_unregister.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __battery_hook_unregister(struct acpi_battery_hook *hook, int lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (0)
Location: drivers/acpi/battery.c:689
Inline: False
Direct callers:
  - drivers/acpi/battery.c:sysfs_add_battery
  - drivers/acpi/battery.c:battery_hook_exit
  - drivers/acpi/battery.c:battery_hook_register
  - drivers/acpi/battery.c:battery_hook_unregister
```
**Symbols:**

```
ffffffff81894ff0-ffffffff81895096: __battery_hook_unregister (STB_LOCAL)
ffffffff81eb9daa-ffffffff81eb9dcd: __battery_hook_unregister.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __battery_hook_unregister(struct acpi_battery_hook *hook, int lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff819dcc80)
Location: drivers/acpi/battery.c:689
Inline: False
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_exit
  - drivers/acpi/battery.c:sysfs_add_battery
  - drivers/acpi/battery.c:battery_hook_register
  - drivers/acpi/battery.c:battery_hook_unregister
```
**Symbols:**

```
ffffffff819dcc80-ffffffff819dcdc9: __battery_hook_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __battery_hook_unregister(struct acpi_battery_hook *hook, int lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff81a24940)
Location: drivers/acpi/battery.c:700
Inline: False
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_exit
  - drivers/acpi/battery.c:sysfs_add_battery
  - drivers/acpi/battery.c:battery_hook_register
  - drivers/acpi/battery.c:battery_hook_unregister
```
**Symbols:**

```
ffffffff81a24940-ffffffff81a24a89: __battery_hook_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __battery_hook_unregister(struct acpi_battery_hook *hook, int lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff81a6f780)
Location: drivers/acpi/battery.c:700
Inline: False
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_exit
  - drivers/acpi/battery.c:sysfs_add_battery
  - drivers/acpi/battery.c:battery_hook_register
  - drivers/acpi/battery.c:battery_hook_unregister
```
**Symbols:**

```
ffffffff81a6f780-ffffffff81a6f8c9: __battery_hook_unregister (STB_LOCAL)
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
void __battery_hook_unregister(struct acpi_battery_hook *hook, int lock);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffff8000107a7420)
Location: drivers/acpi/battery.c:696
Inline: True
Direct callers:
  - drivers/acpi/battery.c:sysfs_add_battery
  - drivers/acpi/battery.c:battery_hook_exit
  - drivers/acpi/battery.c:battery_hook_unregister
```
**Symbols:**

```
ffff8000107a7420-ffff8000107a74e0: __battery_hook_unregister (STB_LOCAL)
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
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __battery_hook_unregister(struct acpi_battery_hook *hook, int lock);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (ffffffff816313cd)
Location: drivers/acpi/battery.c:696
Inline: True
Direct callers:
  - drivers/acpi/battery.c:sysfs_add_battery
  - drivers/acpi/battery.c:battery_hook_exit
  - drivers/acpi/battery.c:battery_hook_unregister
```
**Symbols:**

```
ffffffff81630240-ffffffff816302e1: __battery_hook_unregister (STB_LOCAL)
ffffffff816313cd-ffffffff816313e4: __battery_hook_unregister.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __battery_hook_unregister(struct acpi_battery_hook *hook, int lock);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (ffffffff8164b70d)
Location: drivers/acpi/battery.c:696
Inline: True
Direct callers:
  - drivers/acpi/battery.c:sysfs_add_battery
  - drivers/acpi/battery.c:battery_hook_exit
  - drivers/acpi/battery.c:battery_hook_unregister
```
**Symbols:**

```
ffffffff8164a580-ffffffff8164a621: __battery_hook_unregister (STB_LOCAL)
ffffffff8164b70d-ffffffff8164b724: __battery_hook_unregister.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
