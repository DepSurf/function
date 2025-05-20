# Function: <code>ghes_new</code>

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
In drivers/acpi/apei/ghes.c (ffffffff814b6182)
Location: drivers/acpi/apei/ghes.c:237
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff81505b52)
Location: drivers/acpi/apei/ghes.c:242
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff81529d52)
Location: drivers/acpi/apei/ghes.c:242
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff8153d169)
Location: drivers/acpi/apei/ghes.c:264
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff8159fd49)
Location: drivers/acpi/apei/ghes.c:220
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff815d7965)
Location: drivers/acpi/apei/ghes.c:220
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff815f117f)
Location: drivers/acpi/apei/ghes.c:211
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
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
In drivers/acpi/apei/ghes.c (ffffffff81622f63)
Location: drivers/acpi/apei/ghes.c:203
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
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
In drivers/acpi/apei/ghes.c (ffffffff81644a33)
Location: drivers/acpi/apei/ghes.c:216
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct ghes *ghes_new(struct acpi_hest_generic *generic);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/ghes.c (0)
Location: drivers/acpi/apei/ghes.c:211
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
**Symbols:**

```
ffffffff816f11c0-ffffffff816f1296: ghes_new (STB_LOCAL)
ffffffff816f2508-ffffffff816f2524: ghes_new.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct ghes *ghes_new(struct acpi_hest_generic *generic);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/ghes.c (0)
Location: drivers/acpi/apei/ghes.c:223
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
**Symbols:**

```
ffffffff8170e4a0-ffffffff8170e576: ghes_new (STB_LOCAL)
ffffffff81c0375c-ffffffff81c03778: ghes_new.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct ghes *ghes_new(struct acpi_hest_generic *generic);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/ghes.c (0)
Location: drivers/acpi/apei/ghes.c:223
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
**Symbols:**

```
ffffffff816efbb0-ffffffff816efc86: ghes_new (STB_LOCAL)
ffffffff81bf5136-ffffffff81bf5152: ghes_new.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct ghes *ghes_new(struct acpi_hest_generic *generic);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/ghes.c (0)
Location: drivers/acpi/apei/ghes.c:223
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
**Symbols:**

```
ffffffff81769c50-ffffffff81769d26: ghes_new (STB_LOCAL)
ffffffff81cf25b1-ffffffff81cf25cd: ghes_new.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct ghes *ghes_new(struct acpi_hest_generic *generic);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/ghes.c (0)
Location: drivers/acpi/apei/ghes.c:223
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
**Symbols:**

```
ffffffff8189e770-ffffffff8189e85a: ghes_new (STB_LOCAL)
ffffffff81eba730-ffffffff81eba74e: ghes_new.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct ghes *ghes_new(struct acpi_hest_generic *generic);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff819e7830)
Location: drivers/acpi/apei/ghes.c:239
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
**Symbols:**

```
ffffffff819e7830-ffffffff819e7938: ghes_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct ghes *ghes_new(struct acpi_hest_generic *generic);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff81a2ff40)
Location: drivers/acpi/apei/ghes.c:237
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
**Symbols:**

```
ffffffff81a2ff40-ffffffff81a30048: ghes_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct ghes *ghes_new(struct acpi_hest_generic *generic);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff81a7b550)
Location: drivers/acpi/apei/ghes.c:265
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
**Symbols:**

```
ffffffff81a7b550-ffffffff81a7b687: ghes_new (STB_LOCAL)
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
In drivers/acpi/apei/ghes.c (ffff8000107b0560)
Location: drivers/acpi/apei/ghes.c:216
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
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
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff81638873)
Location: drivers/acpi/apei/ghes.c:216
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
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
In drivers/acpi/apei/ghes.c (ffffffff81652bc3)
Location: drivers/acpi/apei/ghes.c:216
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
