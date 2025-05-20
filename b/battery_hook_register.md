# Function: <code>battery_hook_register</code>

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
void battery_hook_register(struct acpi_battery_hook *hook);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (0)
Location: drivers/acpi/battery.c:697
Inline: True
```
**Symbols:**

```
ffffffff815d07e4-ffffffff815d0821: battery_hook_register.cold.26 (STB_LOCAL)
ffffffff815cfa00-ffffffff815cfa92: battery_hook_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void battery_hook_register(struct acpi_battery_hook *hook);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (ffffffff815e9e28)
Location: drivers/acpi/battery.c:710
Inline: True
```
**Symbols:**

```
ffffffff815e9e18-ffffffff815e9e55: battery_hook_register.cold.26 (STB_LOCAL)
ffffffff815e8fe0-ffffffff815e9072: battery_hook_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void battery_hook_register(struct acpi_battery_hook *hook);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (ffffffff8161bb30)
Location: drivers/acpi/battery.c:697
Inline: True
```
**Symbols:**

```
ffffffff8161bb20-ffffffff8161bb5d: battery_hook_register.cold (STB_LOCAL)
ffffffff8161ac40-ffffffff8161acd2: battery_hook_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void battery_hook_register(struct acpi_battery_hook *hook);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (ffffffff8163d5d3)
Location: drivers/acpi/battery.c:720
Inline: True
```
**Symbols:**

```
ffffffff8163d5c3-ffffffff8163d600: battery_hook_register.cold (STB_LOCAL)
ffffffff8163c6b0-ffffffff8163c742: battery_hook_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void battery_hook_register(struct acpi_battery_hook *hook);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (0)
Location: drivers/acpi/battery.c:720
Inline: False
```
**Symbols:**

```
ffffffff816ea749-ffffffff816ea786: battery_hook_register.cold (STB_LOCAL)
ffffffff816e91a0-ffffffff816e9232: battery_hook_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void battery_hook_register(struct acpi_battery_hook *hook);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (0)
Location: drivers/acpi/battery.c:709
Inline: False
```
**Symbols:**

```
ffffffff81c031aa-ffffffff81c031e7: battery_hook_register.cold (STB_LOCAL)
ffffffff81706980-ffffffff81706a12: battery_hook_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void battery_hook_register(struct acpi_battery_hook *hook);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (0)
Location: drivers/acpi/battery.c:715
Inline: False
```
**Symbols:**

```
ffffffff81bf4ba3-ffffffff81bf4be0: battery_hook_register.cold (STB_LOCAL)
ffffffff816e7fa0-ffffffff816e8032: battery_hook_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void battery_hook_register(struct acpi_battery_hook *hook);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (0)
Location: drivers/acpi/battery.c:718
Inline: False
```
**Symbols:**

```
ffffffff81cf1e14-ffffffff81cf1e51: battery_hook_register.cold (STB_LOCAL)
ffffffff817615e0-ffffffff81761672: battery_hook_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void battery_hook_register(struct acpi_battery_hook *hook);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (0)
Location: drivers/acpi/battery.c:713
Inline: False
```
**Symbols:**

```
ffffffff81eb9dcd-ffffffff81eb9e16: battery_hook_register.cold (STB_LOCAL)
ffffffff818950c0-ffffffff81895157: battery_hook_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void battery_hook_register(struct acpi_battery_hook *hook);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff819dce10)
Location: drivers/acpi/battery.c:714
Inline: False
```
**Symbols:**

```
ffffffff819dce10-ffffffff819dceef: battery_hook_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void battery_hook_register(struct acpi_battery_hook *hook);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff81a24ad0)
Location: drivers/acpi/battery.c:725
Inline: False
```
**Symbols:**

```
ffffffff81a24ad0-ffffffff81a24baf: battery_hook_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void battery_hook_register(struct acpi_battery_hook *hook);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff81a6f910)
Location: drivers/acpi/battery.c:725
Inline: False
```
**Symbols:**

```
ffffffff81a6f910-ffffffff81a6f9ef: battery_hook_register (STB_GLOBAL)
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
void battery_hook_register(struct acpi_battery_hook *hook);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffff8000107a7708)
Location: drivers/acpi/battery.c:720
Inline: True
```
**Symbols:**

```
ffff8000107a7708-ffff8000107a77d0: battery_hook_register (STB_GLOBAL)
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
void battery_hook_register(struct acpi_battery_hook *hook);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (ffffffff81631413)
Location: drivers/acpi/battery.c:720
Inline: True
```
**Symbols:**

```
ffffffff81631403-ffffffff81631440: battery_hook_register.cold (STB_LOCAL)
ffffffff816304f0-ffffffff81630582: battery_hook_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void battery_hook_register(struct acpi_battery_hook *hook);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (ffffffff8164b753)
Location: drivers/acpi/battery.c:720
Inline: True
```
**Symbols:**

```
ffffffff8164b743-ffffffff8164b780: battery_hook_register.cold (STB_LOCAL)
ffffffff8164a830-ffffffff8164a8c2: battery_hook_register (STB_GLOBAL)
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
