# Function: <code>ghes_do_proc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff814b5e20)
Location: drivers/acpi/apei/ghes.c:423
Inline: True
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff814b5e20-ffffffff814b6121: ghes_do_proc.isra.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff815057e0)
Location: drivers/acpi/apei/ghes.c:428
Inline: True
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff815057e0-ffffffff81505af1: ghes_do_proc.isra.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff815299d0)
Location: drivers/acpi/apei/ghes.c:428
Inline: True
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff815299d0-ffffffff81529cf7: ghes_do_proc.isra.10 (STB_LOCAL)
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
In drivers/acpi/apei/ghes.c (ffffffff8153cb60)
Location: drivers/acpi/apei/ghes.c:461
Inline: True
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff8153cb60-ffffffff8153cef8: ghes_do_proc.isra.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ghes_do_proc(struct ghes *ghes, const struct acpi_hest_generic_status *estatus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff8159f670)
Location: drivers/acpi/apei/ghes.c:417
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff8159f670-ffffffff8159faa3: ghes_do_proc (STB_LOCAL)
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
In drivers/acpi/apei/ghes.c (0)
Location: drivers/acpi/apei/ghes.c:462
Inline: True
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff815d7330-ffffffff815d770a: ghes_do_proc.isra.14 (STB_LOCAL)
ffffffff815d7d0f-ffffffff815d7d29: ghes_do_proc.isra.14.cold.23 (STB_LOCAL)
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
In drivers/acpi/apei/ghes.c (0)
Location: drivers/acpi/apei/ghes.c:488
Inline: True
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff815f0ab0-ffffffff815f0e87: ghes_do_proc.isra.17 (STB_LOCAL)
ffffffff815f165a-ffffffff815f1674: ghes_do_proc.isra.17.cold.32 (STB_LOCAL)
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
In drivers/acpi/apei/ghes.c (0)
Location: drivers/acpi/apei/ghes.c:480
Inline: True
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff81622860-ffffffff81622c5e: ghes_do_proc.isra.0 (STB_LOCAL)
ffffffff81623469-ffffffff81623483: ghes_do_proc.isra.0.cold (STB_LOCAL)
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
In drivers/acpi/apei/ghes.c (0)
Location: drivers/acpi/apei/ghes.c:493
Inline: True
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff81644340-ffffffff8164472e: ghes_do_proc.isra.0 (STB_LOCAL)
ffffffff81644f58-ffffffff81644f72: ghes_do_proc.isra.0.cold (STB_LOCAL)
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
In drivers/acpi/apei/ghes.c (ffffffff816f1680)
Location: drivers/acpi/apei/ghes.c:514
Inline: True
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff816f1680-ffffffff816f1941: ghes_do_proc.constprop.0 (STB_LOCAL)
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
In drivers/acpi/apei/ghes.c (ffffffff8170ea20)
Location: drivers/acpi/apei/ghes.c:576
Inline: True
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff8170ea20-ffffffff8170ed0a: ghes_do_proc.constprop.0 (STB_LOCAL)
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
In drivers/acpi/apei/ghes.c (0)
Location: drivers/acpi/apei/ghes.c:625
Inline: True
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff816f0040-ffffffff816f05ed: ghes_do_proc.constprop.0 (STB_LOCAL)
ffffffff81bf516e-ffffffff81bf51b5: ghes_do_proc.constprop.0.cold (STB_LOCAL)
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
In drivers/acpi/apei/ghes.c (0)
Location: drivers/acpi/apei/ghes.c:625
Inline: True
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff8176a130-ffffffff8176a6ff: ghes_do_proc.constprop.0 (STB_LOCAL)
ffffffff81cf25e9-ffffffff81cf2630: ghes_do_proc.constprop.0.cold (STB_LOCAL)
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
In drivers/acpi/apei/ghes.c (0)
Location: drivers/acpi/apei/ghes.c:625
Inline: True
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff8189ecc0-ffffffff8189f26f: ghes_do_proc.constprop.0 (STB_LOCAL)
ffffffff81eba764-ffffffff81eba778: ghes_do_proc.constprop.0.cold (STB_LOCAL)
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
In drivers/acpi/apei/ghes.c (ffffffff819e8010)
Location: drivers/acpi/apei/ghes.c:641
Inline: True
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff819e8010-ffffffff819e8511: ghes_do_proc.constprop.0 (STB_LOCAL)
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
In drivers/acpi/apei/ghes.c (ffffffff81a30730)
Location: drivers/acpi/apei/ghes.c:639
Inline: True
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff81a30730-ffffffff81a30c25: ghes_do_proc.isra.0 (STB_LOCAL)
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
In drivers/acpi/apei/ghes.c (ffffffff81a7bc40)
Location: drivers/acpi/apei/ghes.c:676
Inline: True
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff81a7bc40-ffffffff81a7c091: ghes_do_proc.isra.0 (STB_LOCAL)
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
In drivers/acpi/apei/ghes.c (ffff8000107af4c8)
Location: drivers/acpi/apei/ghes.c:493
Inline: True
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffff8000107af4c8-ffff8000107af880: ghes_do_proc.isra.0 (STB_LOCAL)
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
In drivers/acpi/apei/ghes.c (0)
Location: drivers/acpi/apei/ghes.c:493
Inline: True
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff81638180-ffffffff8163856e: ghes_do_proc.isra.0 (STB_LOCAL)
ffffffff81638d98-ffffffff81638db2: ghes_do_proc.isra.0.cold (STB_LOCAL)
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
In drivers/acpi/apei/ghes.c (0)
Location: drivers/acpi/apei/ghes.c:493
Inline: True
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff816524c0-ffffffff816528ae: ghes_do_proc.isra.0 (STB_LOCAL)
ffffffff816530e8-ffffffff81653102: ghes_do_proc.isra.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
