# Function: <code>hmat_parse_proximity_domain</code>

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
In drivers/acpi/hmat/hmat.c (ffffffff828f3b70)
Location: drivers/acpi/hmat/hmat.c:365
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
In drivers/acpi/hmat/hmat.c (ffffffff828fccb7)
Location: drivers/acpi/hmat/hmat.c:386
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
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
In drivers/acpi/numa/hmat.c (ffffffff82d13bb7)
Location: drivers/acpi/numa/hmat.c:407
Inline: True
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_parse_subtable
```
**Symbols:**

```
ffffffff82d13bb7-ffffffff82d13cd7: hmat_parse_proximity_domain.constprop.0 (STB_LOCAL)
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
In drivers/acpi/numa/hmat.c (ffffffff830017a6)
Location: drivers/acpi/numa/hmat.c:420
Inline: True
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_parse_subtable
```
**Symbols:**

```
ffffffff830017a6-ffffffff830018d0: hmat_parse_proximity_domain.constprop.0 (STB_LOCAL)
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
In drivers/acpi/numa/hmat.c (ffffffff8320c722)
Location: drivers/acpi/numa/hmat.c:420
Inline: True
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_parse_subtable
```
**Symbols:**

```
ffffffff8320c722-ffffffff8320c84c: hmat_parse_proximity_domain.constprop.0 (STB_LOCAL)
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
In drivers/acpi/numa/hmat.c (ffffffff832f4ee1)
Location: drivers/acpi/numa/hmat.c:420
Inline: True
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_parse_subtable
```
**Symbols:**

```
ffffffff832f4ee1-ffffffff832f5005: hmat_parse_proximity_domain.constprop.0 (STB_LOCAL)
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
In drivers/acpi/numa/hmat.c (ffffffff834ad33c)
Location: drivers/acpi/numa/hmat.c:420
Inline: True
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_parse_subtable
```
**Symbols:**

```
ffffffff834ad33c-ffffffff834ad449: hmat_parse_proximity_domain.constprop.0 (STB_LOCAL)
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
In drivers/acpi/numa/hmat.c (ffffffff83ee6100)
Location: drivers/acpi/numa/hmat.c:419
Inline: True
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_parse_subtable
```
**Symbols:**

```
ffffffff83ee6100-ffffffff83ee6227: hmat_parse_proximity_domain.constprop.0 (STB_LOCAL)
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
In drivers/acpi/numa/hmat.c (ffffffff8370bad0)
Location: drivers/acpi/numa/hmat.c:419
Inline: True
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_parse_subtable
```
**Symbols:**

```
ffffffff8370bad0-ffffffff8370bbf7: hmat_parse_proximity_domain.isra.0 (STB_LOCAL)
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
In drivers/acpi/numa/hmat.c (ffffffff8393ef60)
Location: drivers/acpi/numa/hmat.c:503
Inline: True
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_parse_subtable
```
**Symbols:**

```
ffffffff8393ef60-ffffffff8393f087: hmat_parse_proximity_domain.isra.0 (STB_LOCAL)
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
In drivers/acpi/hmat/hmat.c (ffff80001147f92c)
Location: drivers/acpi/hmat/hmat.c:386
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
In drivers/acpi/hmat/hmat.c (ffffffff828e50fa)
Location: drivers/acpi/hmat/hmat.c:386
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
In drivers/acpi/hmat/hmat.c (ffffffff828dd2fe)
Location: drivers/acpi/hmat/hmat.c:386
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
In drivers/acpi/hmat/hmat.c (ffffffff828fdd0b)
Location: drivers/acpi/hmat/hmat.c:386
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
```
</details>
</li>
</ul>

## Differences
