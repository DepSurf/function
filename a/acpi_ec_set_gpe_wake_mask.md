# Function: <code>acpi_ec_set_gpe_wake_mask</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_ec_set_gpe_wake_mask(u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81594030)
Location: drivers/acpi/ec.c:1043
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
```
**Symbols:**

```
ffffffff81594030-ffffffff8159405f: acpi_ec_set_gpe_wake_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void acpi_ec_set_gpe_wake_mask(u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815c5080)
Location: drivers/acpi/ec.c:1057
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
```
**Symbols:**

```
ffffffff815c5080-ffffffff815c50af: acpi_ec_set_gpe_wake_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void acpi_ec_set_gpe_wake_mask(u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815e6280)
Location: drivers/acpi/ec.c:1959
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
```
**Symbols:**

```
ffffffff815e6280-ffffffff815e62b8: acpi_ec_set_gpe_wake_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_ec_set_gpe_wake_mask(u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81691810)
Location: drivers/acpi/ec.c:1994
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
```
**Symbols:**

```
ffffffff81691810-ffffffff81691848: acpi_ec_set_gpe_wake_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_ec_set_gpe_wake_mask(u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff816af550)
Location: drivers/acpi/ec.c:1981
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
```
**Symbols:**

```
ffffffff816af550-ffffffff816af588: acpi_ec_set_gpe_wake_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_ec_set_gpe_wake_mask(u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81691b60)
Location: drivers/acpi/ec.c:2016
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
```
**Symbols:**

```
ffffffff81691b60-ffffffff81691b98: acpi_ec_set_gpe_wake_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void acpi_ec_set_gpe_wake_mask(u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:2033
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
```
**Symbols:**

```
ffffffff81cefc58-ffffffff81cefc72: acpi_ec_set_gpe_wake_mask.cold (STB_LOCAL)
ffffffff81707600-ffffffff81707659: acpi_ec_set_gpe_wake_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void acpi_ec_set_gpe_wake_mask(u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:1991
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
```
**Symbols:**

```
ffffffff81eb77f9-ffffffff81eb7813: acpi_ec_set_gpe_wake_mask.cold (STB_LOCAL)
ffffffff818357b0-ffffffff8183582d: acpi_ec_set_gpe_wake_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void acpi_ec_set_gpe_wake_mask(u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:2029
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
```
**Symbols:**

```
ffffffff82091b33-ffffffff82091b4d: acpi_ec_set_gpe_wake_mask.cold (STB_LOCAL)
ffffffff819696f0-ffffffff8196976d: acpi_ec_set_gpe_wake_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void acpi_ec_set_gpe_wake_mask(u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:2048
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
```
**Symbols:**

```
ffffffff82112437-ffffffff82112451: acpi_ec_set_gpe_wake_mask.cold (STB_LOCAL)
ffffffff819afce0-ffffffff819afd5d: acpi_ec_set_gpe_wake_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void acpi_ec_set_gpe_wake_mask(u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:2069
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
```
**Symbols:**

```
ffffffff821f019f-ffffffff821f01b9: acpi_ec_set_gpe_wake_mask.cold (STB_LOCAL)
ffffffff819fa190-ffffffff819fa20d: acpi_ec_set_gpe_wake_mask (STB_GLOBAL)
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
void acpi_ec_set_gpe_wake_mask(u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffff800010773000)
Location: drivers/acpi/ec.c:1959
Inline: False
```
**Symbols:**

```
ffff800010773000-ffff800010773018: acpi_ec_set_gpe_wake_mask (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void acpi_ec_set_gpe_wake_mask(u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815d8170)
Location: drivers/acpi/ec.c:1959
Inline: False
```
**Symbols:**

```
ffffffff815d8170-ffffffff815d817b: acpi_ec_set_gpe_wake_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void acpi_ec_set_gpe_wake_mask(u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815c1d30)
Location: drivers/acpi/ec.c:1959
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
```
**Symbols:**

```
ffffffff815c1d30-ffffffff815c1d68: acpi_ec_set_gpe_wake_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void acpi_ec_set_gpe_wake_mask(u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815da560)
Location: drivers/acpi/ec.c:1959
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
```
**Symbols:**

```
ffffffff815da560-ffffffff815da598: acpi_ec_set_gpe_wake_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void acpi_ec_set_gpe_wake_mask(u8 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815f4420)
Location: drivers/acpi/ec.c:1959
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
```
**Symbols:**

```
ffffffff815f4420-ffffffff815f4458: acpi_ec_set_gpe_wake_mask (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
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
