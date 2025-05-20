# Function: <code>ec_remove_handlers</code>

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
In drivers/acpi/ec.c (ffffffff8148487f)
Location: drivers/acpi/ec.c:1324
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void ec_remove_handlers(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff814d3122)
Location: drivers/acpi/ec.c:1338
Inline: True
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_alloc
```
**Symbols:**

```
ffffffff814d3122-ffffffff814d319b: ec_remove_handlers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ec_remove_handlers(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff814f5666)
Location: drivers/acpi/ec.c:1444
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_remove
```
**Symbols:**

```
ffffffff814f5666-ffffffff814f56fb: ec_remove_handlers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ec_remove_handlers(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81502560)
Location: drivers/acpi/ec.c:1469
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_remove
```
**Symbols:**

```
ffffffff81502560-ffffffff815025fd: ec_remove_handlers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ec_remove_handlers(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815449d0)
Location: drivers/acpi/ec.c:1470
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_remove
```
**Symbols:**

```
ffffffff815449d0-ffffffff81544a6d: ec_remove_handlers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void ec_remove_handlers(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:1476
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_remove
```
**Symbols:**

```
ffffffff8157aa20-ffffffff8157aab2: ec_remove_handlers (STB_LOCAL)
ffffffff8157c41d-ffffffff8157c43f: ec_remove_handlers.cold.30 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void ec_remove_handlers(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:1488
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_remove
```
**Symbols:**

```
ffffffff815926a0-ffffffff81592732: ec_remove_handlers (STB_LOCAL)
ffffffff815940fd-ffffffff8159411f: ec_remove_handlers.cold.29 (STB_LOCAL)
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
In drivers/acpi/ec.c (ffffffff815c3611)
Location: drivers/acpi/ec.c:1502
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove
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
In drivers/acpi/ec.c (ffffffff815e4851)
Location: drivers/acpi/ec.c:1476
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void ec_remove_handlers(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:1519
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_remove
```
**Symbols:**

```
ffffffff8168fd90-ffffffff8168fe3e: ec_remove_handlers (STB_LOCAL)
ffffffff81691a02-ffffffff81691a24: ec_remove_handlers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void ec_remove_handlers(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:1506
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_remove
```
**Symbols:**

```
ffffffff816ada60-ffffffff816adb0e: ec_remove_handlers (STB_LOCAL)
ffffffff81c01643-ffffffff81c01665: ec_remove_handlers.cold (STB_LOCAL)
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
In drivers/acpi/ec.c (ffffffff81690031)
Location: drivers/acpi/ec.c:1507
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove
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
In drivers/acpi/ec.c (ffffffff817059e1)
Location: drivers/acpi/ec.c:1524
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove
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
In drivers/acpi/ec.c (ffffffff81833bee)
Location: drivers/acpi/ec.c:1530
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ec_remove_handlers(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81967210)
Location: drivers/acpi/ec.c:1535
Inline: False
```
**Symbols:**

```
ffffffff81967210-ffffffff819672e5: ec_remove_handlers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ec_remove_handlers(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff819ad7e0)
Location: drivers/acpi/ec.c:1554
Inline: False
```
**Symbols:**

```
ffffffff819ad7e0-ffffffff819ad8b5: ec_remove_handlers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ec_remove_handlers(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff819f7c60)
Location: drivers/acpi/ec.c:1554
Inline: False
```
**Symbols:**

```
ffffffff819f7c60-ffffffff819f7d35: ec_remove_handlers (STB_LOCAL)
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
In drivers/acpi/ec.c (ffff800010771454)
Location: drivers/acpi/ec.c:1476
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815d6741)
Location: drivers/acpi/ec.c:1476
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815c0301)
Location: drivers/acpi/ec.c:1476
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815d8b31)
Location: drivers/acpi/ec.c:1476
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove
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
In drivers/acpi/ec.c (ffffffff815f29f1)
Location: drivers/acpi/ec.c:1476
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
