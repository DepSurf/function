# Function: <code>hmat_parse_locality</code>

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
In drivers/acpi/hmat/hmat.c (ffffffff828f3c5b)
Location: drivers/acpi/hmat/hmat.c:254
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
In drivers/acpi/hmat/hmat.c (ffffffff828fcdc3)
Location: drivers/acpi/hmat/hmat.c:264
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
In drivers/acpi/numa/hmat.c (ffffffff82d13ed0)
Location: drivers/acpi/numa/hmat.c:285
Inline: True
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_parse_subtable
```
**Symbols:**

```
ffffffff82d13ed0-ffffffff82d1412d: hmat_parse_locality.constprop.0 (STB_LOCAL)
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
In drivers/acpi/numa/hmat.c (ffffffff83001b64)
Location: drivers/acpi/numa/hmat.c:294
Inline: True
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_parse_subtable
```
**Symbols:**

```
ffffffff83001b64-ffffffff83001d8f: hmat_parse_locality.constprop.0 (STB_LOCAL)
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
In drivers/acpi/numa/hmat.c (ffffffff8320c95e)
Location: drivers/acpi/numa/hmat.c:294
Inline: True
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_parse_subtable
```
**Symbols:**

```
ffffffff8320c95e-ffffffff8320ccea: hmat_parse_locality.constprop.0 (STB_LOCAL)
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
In drivers/acpi/numa/hmat.c (ffffffff832f5261)
Location: drivers/acpi/numa/hmat.c:294
Inline: True
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_parse_subtable
```
**Symbols:**

```
ffffffff832f5261-ffffffff832f5605: hmat_parse_locality.constprop.0 (STB_LOCAL)
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
In drivers/acpi/numa/hmat.c (ffffffff834ad449)
Location: drivers/acpi/numa/hmat.c:294
Inline: True
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_parse_subtable
```
**Symbols:**

```
ffffffff834ad449-ffffffff834ad7cb: hmat_parse_locality.constprop.0 (STB_LOCAL)
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
In drivers/acpi/numa/hmat.c (ffffffff83ee6530)
Location: drivers/acpi/numa/hmat.c:293
Inline: True
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_parse_subtable
```
**Symbols:**

```
ffffffff83ee6530-ffffffff83ee6a97: hmat_parse_locality.constprop.0 (STB_LOCAL)
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
In drivers/acpi/numa/hmat.c (ffffffff8370bf00)
Location: drivers/acpi/numa/hmat.c:293
Inline: True
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_parse_subtable
```
**Symbols:**

```
ffffffff8370bf00-ffffffff8370c457: hmat_parse_locality.isra.0 (STB_LOCAL)
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
In drivers/acpi/numa/hmat.c (ffffffff8393f8b0)
Location: drivers/acpi/numa/hmat.c:385
Inline: True
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_parse_subtable
```
**Symbols:**

```
ffffffff8393f8b0-ffffffff8393fe38: hmat_parse_locality.isra.0 (STB_LOCAL)
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
In drivers/acpi/hmat/hmat.c (ffff80001147fa4c)
Location: drivers/acpi/hmat/hmat.c:264
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
In drivers/acpi/hmat/hmat.c (ffffffff828e5206)
Location: drivers/acpi/hmat/hmat.c:264
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
In drivers/acpi/hmat/hmat.c (ffffffff828dd40a)
Location: drivers/acpi/hmat/hmat.c:264
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
In drivers/acpi/hmat/hmat.c (ffffffff828fde17)
Location: drivers/acpi/hmat/hmat.c:264
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
```
</details>
</li>
</ul>

## Differences
