# Function: <code>hmat_parse_cache</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/hmat/hmat.c (ffffffff828f3f23)
Location: drivers/acpi/hmat/hmat.c:313
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
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
In drivers/acpi/hmat/hmat.c (ffffffff828fd0fe)
Location: drivers/acpi/hmat/hmat.c:323
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/hmat.c (ffffffff82d14174)
Location: drivers/acpi/numa/hmat.c:344
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_parse_subtable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/hmat.c (ffffffff83001dd6)
Location: drivers/acpi/numa/hmat.c:357
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_parse_subtable
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
In drivers/acpi/numa/hmat.c (ffffffff8320cd31)
Location: drivers/acpi/numa/hmat.c:357
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_parse_subtable
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
In drivers/acpi/numa/hmat.c (ffffffff832f5117)
Location: drivers/acpi/numa/hmat.c:357
Inline: True
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_parse_subtable
```
**Symbols:**

```
ffffffff832f5117-ffffffff832f5261: hmat_parse_cache.constprop.0 (STB_LOCAL)
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
In drivers/acpi/numa/hmat.c (ffffffff834ad7cb)
Location: drivers/acpi/numa/hmat.c:357
Inline: True
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_parse_subtable
```
**Symbols:**

```
ffffffff834ad7cb-ffffffff834ad918: hmat_parse_cache.constprop.0 (STB_LOCAL)
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
In drivers/acpi/numa/hmat.c (ffffffff83ee6240)
Location: drivers/acpi/numa/hmat.c:356
Inline: True
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_parse_subtable
```
**Symbols:**

```
ffffffff83ee6240-ffffffff83ee63ab: hmat_parse_cache.constprop.0 (STB_LOCAL)
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
In drivers/acpi/numa/hmat.c (ffffffff8370bc10)
Location: drivers/acpi/numa/hmat.c:356
Inline: True
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_parse_subtable
```
**Symbols:**

```
ffffffff8370bc10-ffffffff8370bd7b: hmat_parse_cache.isra.0 (STB_LOCAL)
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
In drivers/acpi/numa/hmat.c (ffffffff8393f330)
Location: drivers/acpi/numa/hmat.c:440
Inline: True
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_parse_subtable
```
**Symbols:**

```
ffffffff8393f330-ffffffff8393f4cd: hmat_parse_cache.isra.0 (STB_LOCAL)
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
In drivers/acpi/hmat/hmat.c (ffff80001147fda4)
Location: drivers/acpi/hmat/hmat.c:323
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
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
In drivers/acpi/hmat/hmat.c (ffffffff828e5541)
Location: drivers/acpi/hmat/hmat.c:323
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
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
In drivers/acpi/hmat/hmat.c (ffffffff828dd745)
Location: drivers/acpi/hmat/hmat.c:323
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
```
</details>
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/hmat/hmat.c (ffffffff828fe152)
Location: drivers/acpi/hmat/hmat.c:323
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
```
</details>
</li>
</ul>

## Differences
