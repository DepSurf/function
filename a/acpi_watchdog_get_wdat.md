# Function: <code>acpi_watchdog_get_wdat</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
const struct acpi_table_wdat *acpi_watchdog_get_wdat();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_watchdog.c (ffffffff81586c10)
Location: drivers/acpi/acpi_watchdog.c:61
Inline: False
Direct callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
  - drivers/acpi/acpi_watchdog.c:acpi_has_watchdog
```
**Symbols:**

```
ffffffff81586c10-ffffffff81586cb2: acpi_watchdog_get_wdat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const struct acpi_table_wdat *acpi_watchdog_get_wdat();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_watchdog.c (ffffffff8159ef30)
Location: drivers/acpi/acpi_watchdog.c:61
Inline: False
Direct callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
  - drivers/acpi/acpi_watchdog.c:acpi_has_watchdog
```
**Symbols:**

```
ffffffff8159ef30-ffffffff8159efd2: acpi_watchdog_get_wdat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
const struct acpi_table_wdat *acpi_watchdog_get_wdat();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_watchdog.c (0)
Location: drivers/acpi/acpi_watchdog.c:58
Inline: False
Direct callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
  - drivers/acpi/acpi_watchdog.c:acpi_has_watchdog
```
**Symbols:**

```
ffffffff815d0470-ffffffff815d0518: acpi_watchdog_get_wdat (STB_LOCAL)
ffffffff815d0536-ffffffff815d054a: acpi_watchdog_get_wdat.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
const struct acpi_table_wdat *acpi_watchdog_get_wdat();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_watchdog.c (0)
Location: drivers/acpi/acpi_watchdog.c:60
Inline: False
Direct callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
  - drivers/acpi/acpi_watchdog.c:acpi_has_watchdog
```
**Symbols:**

```
ffffffff815f16e0-ffffffff815f1789: acpi_watchdog_get_wdat (STB_LOCAL)
ffffffff815f17a6-ffffffff815f17ba: acpi_watchdog_get_wdat.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const struct acpi_table_wdat *acpi_watchdog_get_wdat();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_watchdog.c (ffffffff8169d6c0)
Location: drivers/acpi/acpi_watchdog.c:60
Inline: False
Direct callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
  - drivers/acpi/acpi_watchdog.c:acpi_has_watchdog
```
**Symbols:**

```
ffffffff8169d6c0-ffffffff8169d777: acpi_watchdog_get_wdat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const struct acpi_table_wdat *acpi_watchdog_get_wdat();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_watchdog.c (ffffffff816bafb0)
Location: drivers/acpi/acpi_watchdog.c:60
Inline: False
Direct callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
  - drivers/acpi/acpi_watchdog.c:acpi_has_watchdog
```
**Symbols:**

```
ffffffff816bafb0-ffffffff816bb067: acpi_watchdog_get_wdat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const struct acpi_table_wdat *acpi_watchdog_get_wdat();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_watchdog.c (ffffffff8169d0f0)
Location: drivers/acpi/acpi_watchdog.c:60
Inline: False
Direct callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
  - drivers/acpi/acpi_watchdog.c:acpi_has_watchdog
```
**Symbols:**

```
ffffffff8169d0f0-ffffffff8169d1a7: acpi_watchdog_get_wdat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
const struct acpi_table_wdat *acpi_watchdog_get_wdat();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_watchdog.c (0)
Location: drivers/acpi/acpi_watchdog.c:60
Inline: False
Direct callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
  - drivers/acpi/acpi_watchdog.c:acpi_has_watchdog
```
**Symbols:**

```
ffffffff81713480-ffffffff8171354b: acpi_watchdog_get_wdat (STB_LOCAL)
ffffffff81cf0f2d-ffffffff81cf0f42: acpi_watchdog_get_wdat.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
const struct acpi_table_wdat *acpi_watchdog_get_wdat();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_watchdog.c (0)
Location: drivers/acpi/acpi_watchdog.c:60
Inline: False
Direct callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
  - drivers/acpi/acpi_watchdog.c:acpi_has_watchdog
```
**Symbols:**

```
ffffffff81842b40-ffffffff81842c10: acpi_watchdog_get_wdat (STB_LOCAL)
ffffffff81eb8dd8-ffffffff81eb8ded: acpi_watchdog_get_wdat.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
const struct acpi_table_wdat *acpi_watchdog_get_wdat();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_watchdog.c (0)
Location: drivers/acpi/acpi_watchdog.c:60
Inline: False
Direct callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
  - drivers/acpi/acpi_watchdog.c:acpi_has_watchdog
```
**Symbols:**

```
ffffffff81979b10-ffffffff81979be0: acpi_watchdog_get_wdat (STB_LOCAL)
ffffffff82091e34-ffffffff82091e49: acpi_watchdog_get_wdat.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
const struct acpi_table_wdat *acpi_watchdog_get_wdat();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_watchdog.c (0)
Location: drivers/acpi/acpi_watchdog.c:60
Inline: False
Direct callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
  - drivers/acpi/acpi_watchdog.c:acpi_has_watchdog
```
**Symbols:**

```
ffffffff819c05a0-ffffffff819c0670: acpi_watchdog_get_wdat (STB_LOCAL)
ffffffff8211271e-ffffffff82112733: acpi_watchdog_get_wdat.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
const struct acpi_table_wdat *acpi_watchdog_get_wdat();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_watchdog.c (0)
Location: drivers/acpi/acpi_watchdog.c:60
Inline: False
Direct callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
  - drivers/acpi/acpi_watchdog.c:acpi_has_watchdog
```
**Symbols:**

```
ffffffff81a0b020-ffffffff81a0b0f0: acpi_watchdog_get_wdat (STB_LOCAL)
ffffffff821f0486-ffffffff821f049b: acpi_watchdog_get_wdat.cold (STB_LOCAL)
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
const struct acpi_table_wdat *acpi_watchdog_get_wdat();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_watchdog.c (ffff80001077c5a8)
Location: drivers/acpi/acpi_watchdog.c:60
Inline: False
Direct callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
  - drivers/acpi/acpi_watchdog.c:acpi_has_watchdog
```
**Symbols:**

```
ffff80001077c5a8-ffff80001077c630: acpi_watchdog_get_wdat (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
const struct acpi_table_wdat *acpi_watchdog_get_wdat();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_watchdog.c (0)
Location: drivers/acpi/acpi_watchdog.c:60
Inline: False
Direct callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
  - drivers/acpi/acpi_watchdog.c:acpi_has_watchdog
```
**Symbols:**

```
ffffffff815e0370-ffffffff815e0419: acpi_watchdog_get_wdat (STB_LOCAL)
ffffffff815e0436-ffffffff815e044a: acpi_watchdog_get_wdat.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
const struct acpi_table_wdat *acpi_watchdog_get_wdat();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_watchdog.c (0)
Location: drivers/acpi/acpi_watchdog.c:60
Inline: False
Direct callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
  - drivers/acpi/acpi_watchdog.c:acpi_has_watchdog
```
**Symbols:**

```
ffffffff815cb9f0-ffffffff815cba99: acpi_watchdog_get_wdat (STB_LOCAL)
ffffffff815cbab6-ffffffff815cbaca: acpi_watchdog_get_wdat.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
const struct acpi_table_wdat *acpi_watchdog_get_wdat();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_watchdog.c (0)
Location: drivers/acpi/acpi_watchdog.c:60
Inline: False
Direct callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
  - drivers/acpi/acpi_watchdog.c:acpi_has_watchdog
```
**Symbols:**

```
ffffffff815e59c0-ffffffff815e5a69: acpi_watchdog_get_wdat (STB_LOCAL)
ffffffff815e5a86-ffffffff815e5a9a: acpi_watchdog_get_wdat.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
const struct acpi_table_wdat *acpi_watchdog_get_wdat();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_watchdog.c (0)
Location: drivers/acpi/acpi_watchdog.c:60
Inline: False
Direct callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
  - drivers/acpi/acpi_watchdog.c:acpi_has_watchdog
```
**Symbols:**

```
ffffffff815ff870-ffffffff815ff919: acpi_watchdog_get_wdat (STB_LOCAL)
ffffffff815ff936-ffffffff815ff94a: acpi_watchdog_get_wdat.cold (STB_LOCAL)
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
