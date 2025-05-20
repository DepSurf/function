# Function: <code>extract_package</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int extract_package(struct acpi_battery *battery, union acpi_object *package, const struct acpi_offsets *offsets, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff814b1ac0)
Location: drivers/acpi/battery.c:392
Inline: False
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_state
```
**Symbols:**

```
ffffffff814b1ac0-ffffffff814b1b80: extract_package (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int extract_package(struct acpi_battery *battery, union acpi_object *package, const struct acpi_offsets *offsets, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff815013de)
Location: drivers/acpi/battery.c:392
Inline: False
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
```
**Symbols:**

```
ffffffff815013de-ffffffff8150149e: extract_package (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int extract_package(struct acpi_battery *battery, union acpi_object *package, const struct acpi_offsets *offsets, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff815240fb)
Location: drivers/acpi/battery.c:392
Inline: False
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
```
**Symbols:**

```
ffffffff815240fb-ffffffff815241bb: extract_package (STB_LOCAL)
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
In drivers/acpi/battery.c (ffffffff8153694c)
Location: drivers/acpi/battery.c:398
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
```
**Symbols:**

```
ffffffff815367c0-ffffffff81536898: extract_package.part.7 (STB_LOCAL)
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
In drivers/acpi/battery.c (ffffffff815980dc)
Location: drivers/acpi/battery.c:402
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
```
**Symbols:**

```
ffffffff81597f50-ffffffff81598028: extract_package.part.7 (STB_LOCAL)
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
In drivers/acpi/battery.c (ffffffff815cf4fc)
Location: drivers/acpi/battery.c:421
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
```
**Symbols:**

```
ffffffff815cf380-ffffffff815cf44e: extract_package.part.10 (STB_LOCAL)
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
In drivers/acpi/battery.c (ffffffff815e8adc)
Location: drivers/acpi/battery.c:435
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
```
**Symbols:**

```
ffffffff815e8960-ffffffff815e8a2e: extract_package.part.10 (STB_LOCAL)
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
In drivers/acpi/battery.c (ffffffff8161a7fc)
Location: drivers/acpi/battery.c:422
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
```
**Symbols:**

```
ffffffff8161a670-ffffffff8161a745: extract_package.part.0 (STB_LOCAL)
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
In drivers/acpi/battery.c (ffffffff8163c22c)
Location: drivers/acpi/battery.c:445
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
```
**Symbols:**

```
ffffffff8163c0a0-ffffffff8163c175: extract_package.part.0 (STB_LOCAL)
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
In drivers/acpi/battery.c (ffffffff816e972c)
Location: drivers/acpi/battery.c:445
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
```
**Symbols:**

```
ffffffff816e95b0-ffffffff816e967d: extract_package.part.0 (STB_LOCAL)
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
In drivers/acpi/battery.c (ffffffff81706f0f)
Location: drivers/acpi/battery.c:434
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
```
**Symbols:**

```
ffffffff81706d90-ffffffff81706e5d: extract_package.part.0 (STB_LOCAL)
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
In drivers/acpi/battery.c (ffffffff816e850f)
Location: drivers/acpi/battery.c:427
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
```
**Symbols:**

```
ffffffff816e8390-ffffffff816e845d: extract_package.part.0 (STB_LOCAL)
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
In drivers/acpi/battery.c (ffffffff81761b4f)
Location: drivers/acpi/battery.c:430
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
```
**Symbols:**

```
ffffffff817619d0-ffffffff81761a9d: extract_package.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int extract_package(struct acpi_battery *battery, union acpi_object *package, const struct acpi_offsets *offsets, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff818952a0)
Location: drivers/acpi/battery.c:425
Inline: False
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
```
**Symbols:**

```
ffffffff818952a0-ffffffff818953a4: extract_package (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int extract_package(struct acpi_battery *battery, union acpi_object *package, const struct acpi_offsets *offsets, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff819dd060)
Location: drivers/acpi/battery.c:425
Inline: False
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
```
**Symbols:**

```
ffffffff819dd060-ffffffff819dd164: extract_package (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int extract_package(struct acpi_battery *battery, union acpi_object *package, const struct acpi_offsets *offsets, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff81a24d20)
Location: drivers/acpi/battery.c:427
Inline: False
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
```
**Symbols:**

```
ffffffff81a24d20-ffffffff81a24e76: extract_package (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int extract_package(struct acpi_battery *battery, union acpi_object *package, const struct acpi_offsets *offsets, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff81a6fb60)
Location: drivers/acpi/battery.c:427
Inline: False
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
```
**Symbols:**

```
ffffffff81a6fb60-ffffffff81a6fcb6: extract_package (STB_LOCAL)
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
In drivers/acpi/battery.c (ffff8000107a6fe8)
Location: drivers/acpi/battery.c:445
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
```
**Symbols:**

```
ffff8000107a6e30-ffff8000107a6f48: extract_package.part.0 (STB_LOCAL)
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

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (ffffffff8163006c)
Location: drivers/acpi/battery.c:445
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
```
**Symbols:**

```
ffffffff8162fee0-ffffffff8162ffb5: extract_package.part.0 (STB_LOCAL)
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
In drivers/acpi/battery.c (ffffffff8164a3ac)
Location: drivers/acpi/battery.c:445
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
```
**Symbols:**

```
ffffffff8164a220-ffffffff8164a2f5: extract_package.part.0 (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
