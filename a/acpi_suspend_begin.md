# Function: <code>acpi_suspend_begin</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_suspend_begin(suspend_state_t pm_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff8147b88f)
Location: drivers/acpi/sleep.c:477
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_begin_old
```
**Symbols:**

```
ffffffff8147b88f-ffffffff8147b903: acpi_suspend_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_suspend_begin(suspend_state_t pm_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff814c9efa)
Location: drivers/acpi/sleep.c:500
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_begin_old
```
**Symbols:**

```
ffffffff814c9efa-ffffffff814c9f6e: acpi_suspend_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_suspend_begin(suspend_state_t pm_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff814ebe55)
Location: drivers/acpi/sleep.c:483
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_begin_old
```
**Symbols:**

```
ffffffff814ebe55-ffffffff814ebec9: acpi_suspend_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int acpi_suspend_begin(suspend_state_t pm_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff814f8280)
Location: drivers/acpi/sleep.c:503
Inline: False
```
**Symbols:**

```
ffffffff814f8280-ffffffff814f82fa: acpi_suspend_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int acpi_suspend_begin(suspend_state_t pm_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff81539740)
Location: drivers/acpi/sleep.c:525
Inline: False
```
**Symbols:**

```
ffffffff81539740-ffffffff815397ba: acpi_suspend_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int acpi_suspend_begin(suspend_state_t pm_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (0)
Location: drivers/acpi/sleep.c:554
Inline: False
```
**Symbols:**

```
ffffffff8156f390-ffffffff8156f403: acpi_suspend_begin (STB_LOCAL)
ffffffff81570083-ffffffff8157009b: acpi_suspend_begin.cold.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int acpi_suspend_begin(suspend_state_t pm_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (0)
Location: drivers/acpi/sleep.c:554
Inline: False
```
**Symbols:**

```
ffffffff81586f70-ffffffff81586fe3: acpi_suspend_begin (STB_LOCAL)
ffffffff81587c43-ffffffff81587c5b: acpi_suspend_begin.cold.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int acpi_suspend_begin(suspend_state_t pm_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (0)
Location: drivers/acpi/sleep.c:544
Inline: False
```
**Symbols:**

```
ffffffff815b7bd0-ffffffff815b7c3a: acpi_suspend_begin (STB_LOCAL)
ffffffff815b8924-ffffffff815b893c: acpi_suspend_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int acpi_suspend_begin(suspend_state_t pm_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (0)
Location: drivers/acpi/sleep.c:536
Inline: False
```
**Symbols:**

```
ffffffff815d8e10-ffffffff815d8e7a: acpi_suspend_begin (STB_LOCAL)
ffffffff815d9b62-ffffffff815d9b7a: acpi_suspend_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int acpi_suspend_begin(suspend_state_t pm_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (0)
Location: drivers/acpi/sleep.c:539
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_begin_old
```
**Symbols:**

```
ffffffff81683bf0-ffffffff81683c71: acpi_suspend_begin (STB_LOCAL)
ffffffff81683ea1-ffffffff81683ecb: acpi_suspend_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int acpi_suspend_begin(suspend_state_t pm_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (0)
Location: drivers/acpi/sleep.c:535
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_begin_old
```
**Symbols:**

```
ffffffff816a1ae0-ffffffff816a1b61: acpi_suspend_begin (STB_LOCAL)
ffffffff81c00e10-ffffffff81c00e3a: acpi_suspend_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int acpi_suspend_begin(suspend_state_t pm_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (0)
Location: drivers/acpi/sleep.c:535
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_begin_old
```
**Symbols:**

```
ffffffff81684250-ffffffff816842d1: acpi_suspend_begin (STB_LOCAL)
ffffffff81bf2739-ffffffff81bf2763: acpi_suspend_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int acpi_suspend_begin(suspend_state_t pm_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (0)
Location: drivers/acpi/sleep.c:535
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_begin_old
```
**Symbols:**

```
ffffffff816f94f0-ffffffff816f95d8: acpi_suspend_begin (STB_LOCAL)
ffffffff81cef0f3-ffffffff81cef147: acpi_suspend_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int acpi_suspend_begin(suspend_state_t pm_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (0)
Location: drivers/acpi/sleep.c:554
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_begin_old
```
**Symbols:**

```
ffffffff81826e50-ffffffff81826f3d: acpi_suspend_begin (STB_LOCAL)
ffffffff81eb6afd-ffffffff81eb6b50: acpi_suspend_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int acpi_suspend_begin(suspend_state_t pm_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (0)
Location: drivers/acpi/sleep.c:558
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_begin_old
```
**Symbols:**

```
ffffffff819584b0-ffffffff819585b5: acpi_suspend_begin (STB_LOCAL)
ffffffff820917d6-ffffffff82091800: acpi_suspend_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int acpi_suspend_begin(suspend_state_t pm_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (0)
Location: drivers/acpi/sleep.c:558
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_begin_old
```
**Symbols:**

```
ffffffff8199ebd0-ffffffff8199ecd5: acpi_suspend_begin (STB_LOCAL)
ffffffff82112149-ffffffff82112173: acpi_suspend_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int acpi_suspend_begin(suspend_state_t pm_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (0)
Location: drivers/acpi/sleep.c:558
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_begin_old
```
**Symbols:**

```
ffffffff819e7270-ffffffff819e7375: acpi_suspend_begin (STB_LOCAL)
ffffffff821efe4d-ffffffff821efe77: acpi_suspend_begin.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int acpi_suspend_begin(suspend_state_t pm_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (0)
Location: drivers/acpi/sleep.c:536
Inline: False
```
**Symbols:**

```
ffffffff815b51c0-ffffffff815b522a: acpi_suspend_begin (STB_LOCAL)
ffffffff815b5ebc-ffffffff815b5ed4: acpi_suspend_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int acpi_suspend_begin(suspend_state_t pm_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (0)
Location: drivers/acpi/sleep.c:536
Inline: False
```
**Symbols:**

```
ffffffff815cd0f0-ffffffff815cd15a: acpi_suspend_begin (STB_LOCAL)
ffffffff815cde42-ffffffff815cde5a: acpi_suspend_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int acpi_suspend_begin(suspend_state_t pm_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (0)
Location: drivers/acpi/sleep.c:536
Inline: False
```
**Symbols:**

```
ffffffff815e6f90-ffffffff815e6ffa: acpi_suspend_begin (STB_LOCAL)
ffffffff815e7d02-ffffffff815e7d1a: acpi_suspend_begin.cold (STB_LOCAL)
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
