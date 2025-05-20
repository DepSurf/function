# Function: <code>__ghes_check_estatus</code>

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
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff815f0516)
Location: drivers/acpi/apei/ghes.c:307
Inline: True
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
  - drivers/acpi/apei/ghes.c:__ghes_peek_estatus
```
**Symbols:**

```
ffffffff815f04e0-ffffffff815f0570: __ghes_check_estatus.isra.14 (STB_LOCAL)
ffffffff815f15cb-ffffffff815f160d: __ghes_check_estatus.isra.14.cold.28 (STB_LOCAL)
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
In drivers/acpi/apei/ghes.c (ffffffff81622379)
Location: drivers/acpi/apei/ghes.c:299
Inline: True
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff81622340-ffffffff816223d3: __ghes_check_estatus.isra.0 (STB_LOCAL)
ffffffff816233e7-ffffffff81623429: __ghes_check_estatus.isra.0.cold (STB_LOCAL)
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
In drivers/acpi/apei/ghes.c (ffffffff81643e59)
Location: drivers/acpi/apei/ghes.c:312
Inline: True
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff81643e20-ffffffff81643eb3: __ghes_check_estatus.isra.0 (STB_LOCAL)
ffffffff81644ed6-ffffffff81644f18: __ghes_check_estatus.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __ghes_check_estatus(struct ghes *ghes, struct acpi_hest_generic_status *estatus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/ghes.c (0)
Location: drivers/acpi/apei/ghes.c:307
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff816f0cb0-ffffffff816f0d43: __ghes_check_estatus (STB_LOCAL)
ffffffff816f2479-ffffffff816f24bb: __ghes_check_estatus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __ghes_check_estatus(struct ghes *ghes, struct acpi_hest_generic_status *estatus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/ghes.c (0)
Location: drivers/acpi/apei/ghes.c:319
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff8170df50-ffffffff8170dfe3: __ghes_check_estatus (STB_LOCAL)
ffffffff81c036cd-ffffffff81c0370f: __ghes_check_estatus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __ghes_check_estatus(struct ghes *ghes, struct acpi_hest_generic_status *estatus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/ghes.c (0)
Location: drivers/acpi/apei/ghes.c:319
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff816ef6f0-ffffffff816ef783: __ghes_check_estatus (STB_LOCAL)
ffffffff81bf50be-ffffffff81bf5100: __ghes_check_estatus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __ghes_check_estatus(struct ghes *ghes, struct acpi_hest_generic_status *estatus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/ghes.c (0)
Location: drivers/acpi/apei/ghes.c:319
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff81769750-ffffffff817697e3: __ghes_check_estatus (STB_LOCAL)
ffffffff81cf24dd-ffffffff81cf251f: __ghes_check_estatus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __ghes_check_estatus(struct ghes *ghes, struct acpi_hest_generic_status *estatus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/ghes.c (0)
Location: drivers/acpi/apei/ghes.c:319
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff8189e0e0-ffffffff8189e187: __ghes_check_estatus (STB_LOCAL)
ffffffff81eba657-ffffffff81eba68a: __ghes_check_estatus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __ghes_check_estatus(struct ghes *ghes, struct acpi_hest_generic_status *estatus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff819e70b0)
Location: drivers/acpi/apei/ghes.c:335
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff819e70b0-ffffffff819e7173: __ghes_check_estatus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __ghes_check_estatus(struct ghes *ghes, struct acpi_hest_generic_status *estatus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff81a2f7c0)
Location: drivers/acpi/apei/ghes.c:333
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff81a2f7c0-ffffffff81a2f883: __ghes_check_estatus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __ghes_check_estatus(struct ghes *ghes, struct acpi_hest_generic_status *estatus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff81a7ab00)
Location: drivers/acpi/apei/ghes.c:361
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff81a7ab00-ffffffff81a7abc3: __ghes_check_estatus (STB_LOCAL)
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
In drivers/acpi/apei/ghes.c (ffff8000107af180)
Location: drivers/acpi/apei/ghes.c:312
Inline: True
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_in_nmi_queue_one_entry
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffff8000107af180-ffff8000107af28c: __ghes_check_estatus.isra.0 (STB_LOCAL)
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
In drivers/acpi/apei/ghes.c (ffffffff81637c99)
Location: drivers/acpi/apei/ghes.c:312
Inline: True
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff81637c60-ffffffff81637cf3: __ghes_check_estatus.isra.0 (STB_LOCAL)
ffffffff81638d16-ffffffff81638d58: __ghes_check_estatus.isra.0.cold (STB_LOCAL)
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
In drivers/acpi/apei/ghes.c (ffffffff81651fc9)
Location: drivers/acpi/apei/ghes.c:312
Inline: True
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff81651f90-ffffffff81652023: __ghes_check_estatus.isra.0 (STB_LOCAL)
ffffffff81653066-ffffffff816530a8: __ghes_check_estatus.isra.0.cold (STB_LOCAL)
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
