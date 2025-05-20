# Function: <code>__ghes_peek_estatus</code>

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
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int __ghes_peek_estatus(struct ghes *ghes, struct acpi_hest_generic_status *estatus, u64 *buf_paddr, enum fixed_addresses fixmap_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/ghes.c (0)
Location: drivers/acpi/apei/ghes.c:331
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff815f0570-ffffffff815f061b: __ghes_peek_estatus (STB_LOCAL)
ffffffff815f160d-ffffffff815f1628: __ghes_peek_estatus.cold.29 (STB_LOCAL)
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
Location: drivers/acpi/apei/ghes.c:323
Inline: True
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff81622290-ffffffff81622335: __ghes_peek_estatus.isra.0 (STB_LOCAL)
ffffffff816233cb-ffffffff816233e7: __ghes_peek_estatus.isra.0.cold (STB_LOCAL)
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
Location: drivers/acpi/apei/ghes.c:336
Inline: True
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff81643d70-ffffffff81643e15: __ghes_peek_estatus.isra.0 (STB_LOCAL)
ffffffff81644eba-ffffffff81644ed6: __ghes_peek_estatus.isra.0.cold (STB_LOCAL)
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
In drivers/acpi/apei/ghes.c (0)
Location: drivers/acpi/apei/ghes.c:331
Inline: True
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff816f12a0-ffffffff816f1345: __ghes_peek_estatus.isra.0 (STB_LOCAL)
ffffffff816f2524-ffffffff816f2540: __ghes_peek_estatus.isra.0.cold (STB_LOCAL)
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
In drivers/acpi/apei/ghes.c (0)
Location: drivers/acpi/apei/ghes.c:343
Inline: True
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff8170e580-ffffffff8170e625: __ghes_peek_estatus.isra.0 (STB_LOCAL)
ffffffff81c03778-ffffffff81c03794: __ghes_peek_estatus.isra.0.cold (STB_LOCAL)
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
Location: drivers/acpi/apei/ghes.c:343
Inline: True
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff816efc90-ffffffff816efd35: __ghes_peek_estatus.isra.0 (STB_LOCAL)
ffffffff81bf5152-ffffffff81bf516e: __ghes_peek_estatus.isra.0.cold (STB_LOCAL)
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
Location: drivers/acpi/apei/ghes.c:343
Inline: True
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff81769d30-ffffffff81769dd5: __ghes_peek_estatus.isra.0 (STB_LOCAL)
ffffffff81cf25cd-ffffffff81cf25e9: __ghes_peek_estatus.isra.0.cold (STB_LOCAL)
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
Location: drivers/acpi/apei/ghes.c:343
Inline: True
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff8189e860-ffffffff8189e90b: __ghes_peek_estatus.isra.0 (STB_LOCAL)
ffffffff81eba74e-ffffffff81eba764: __ghes_peek_estatus.isra.0.cold (STB_LOCAL)
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
In drivers/acpi/apei/ghes.c (ffffffff819e7950)
Location: drivers/acpi/apei/ghes.c:359
Inline: True
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff819e7950-ffffffff819e7a0a: __ghes_peek_estatus.isra.0 (STB_LOCAL)
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
In drivers/acpi/apei/ghes.c (ffffffff81a30060)
Location: drivers/acpi/apei/ghes.c:357
Inline: True
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff81a30060-ffffffff81a3011a: __ghes_peek_estatus.isra.0 (STB_LOCAL)
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
In drivers/acpi/apei/ghes.c (ffffffff81a7b6a0)
Location: drivers/acpi/apei/ghes.c:385
Inline: True
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff81a7b6a0-ffffffff81a7b75a: __ghes_peek_estatus.isra.0 (STB_LOCAL)
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
In drivers/acpi/apei/ghes.c (ffff8000107af0b8)
Location: drivers/acpi/apei/ghes.c:336
Inline: True
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_in_nmi_queue_one_entry
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffff8000107af0b8-ffff8000107af180: __ghes_peek_estatus.isra.0 (STB_LOCAL)
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
Location: drivers/acpi/apei/ghes.c:336
Inline: True
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff81637bb0-ffffffff81637c55: __ghes_peek_estatus.isra.0 (STB_LOCAL)
ffffffff81638cfa-ffffffff81638d16: __ghes_peek_estatus.isra.0.cold (STB_LOCAL)
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
Location: drivers/acpi/apei/ghes.c:336
Inline: True
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff81651ee0-ffffffff81651f85: __ghes_peek_estatus.isra.0 (STB_LOCAL)
ffffffff8165304a-ffffffff81653066: __ghes_peek_estatus.isra.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
