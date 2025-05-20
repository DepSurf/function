# Function: <code>__ghes_panic</code>

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
In drivers/acpi/apei/ghes.c (ffffffff814b6684)
Location: drivers/acpi/apei/ghes.c:826
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
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
In drivers/acpi/apei/ghes.c (ffffffff8150605d)
Location: drivers/acpi/apei/ghes.c:831
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
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
In drivers/acpi/apei/ghes.c (ffffffff8152a25d)
Location: drivers/acpi/apei/ghes.c:831
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
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
In drivers/acpi/apei/ghes.c (ffffffff8153c4b0)
Location: drivers/acpi/apei/ghes.c:718
Inline: True
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff8153c4b0-ffffffff8153c4ed: __ghes_panic.isra.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff8159f000)
Location: drivers/acpi/apei/ghes.c:674
Inline: True
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff8159f000-ffffffff8159f03d: __ghes_panic.isra.10 (STB_LOCAL)
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
Location: drivers/acpi/apei/ghes.c:690
Inline: True
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff815d6d10-ffffffff815d6d3e: __ghes_panic.isra.13 (STB_LOCAL)
ffffffff815d7cc5-ffffffff815d7cdd: __ghes_panic.isra.13.cold.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void __ghes_panic(struct ghes *ghes, struct acpi_hest_generic_status *estatus, u64 buf_paddr, enum fixed_addresses fixmap_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/ghes.c (0)
Location: drivers/acpi/apei/ghes.c:701
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff815f06f0-ffffffff815f0743: __ghes_panic (STB_LOCAL)
ffffffff815f1639-ffffffff815f165a: __ghes_panic.cold.31 (STB_LOCAL)
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
In drivers/acpi/apei/ghes.c (ffffffff81622d67)
Location: drivers/acpi/apei/ghes.c:693
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff8162343a-ffffffff81623464: __ghes_panic.part.0 (STB_LOCAL)
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
In drivers/acpi/apei/ghes.c (ffffffff81644837)
Location: drivers/acpi/apei/ghes.c:706
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff81644f29-ffffffff81644f53: __ghes_panic.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void __ghes_panic(struct ghes *ghes, struct acpi_hest_generic_status *estatus, u64 buf_paddr, enum fixed_addresses fixmap_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/ghes.c (0)
Location: drivers/acpi/apei/ghes.c:730
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff816f1160-ffffffff816f11b6: __ghes_panic (STB_LOCAL)
ffffffff816f24e7-ffffffff816f2508: __ghes_panic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void __ghes_panic(struct ghes *ghes, struct acpi_hest_generic_status *estatus, u64 buf_paddr, enum fixed_addresses fixmap_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/ghes.c (0)
Location: drivers/acpi/apei/ghes.c:793
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff8170e440-ffffffff8170e496: __ghes_panic (STB_LOCAL)
ffffffff81c0373b-ffffffff81c0375c: __ghes_panic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __ghes_panic(struct ghes *ghes, struct acpi_hest_generic_status *estatus, u64 buf_paddr, enum fixed_addresses fixmap_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/ghes.c (0)
Location: drivers/acpi/apei/ghes.c:840
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff816efb50-ffffffff816efba6: __ghes_panic (STB_LOCAL)
ffffffff81bf5115-ffffffff81bf5136: __ghes_panic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __ghes_panic(struct ghes *ghes, struct acpi_hest_generic_status *estatus, u64 buf_paddr, enum fixed_addresses fixmap_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/ghes.c (0)
Location: drivers/acpi/apei/ghes.c:840
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff81769bf0-ffffffff81769c46: __ghes_panic (STB_LOCAL)
ffffffff81cf2590-ffffffff81cf25b1: __ghes_panic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __ghes_panic(struct ghes *ghes, struct acpi_hest_generic_status *estatus, u64 buf_paddr, enum fixed_addresses fixmap_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/ghes.c (0)
Location: drivers/acpi/apei/ghes.c:840
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff8189e710-ffffffff8189e763: __ghes_panic (STB_LOCAL)
ffffffff81eba70f-ffffffff81eba730: __ghes_panic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __ghes_panic(struct ghes *ghes, struct acpi_hest_generic_status *estatus, u64 buf_paddr, enum fixed_addresses fixmap_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff819e77b0)
Location: drivers/acpi/apei/ghes.c:862
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff819e77b0-ffffffff819e781c: __ghes_panic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __ghes_panic(struct ghes *ghes, struct acpi_hest_generic_status *estatus, u64 buf_paddr, enum fixed_addresses fixmap_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff81a2fec0)
Location: drivers/acpi/apei/ghes.c:860
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff81a2fec0-ffffffff81a2ff2c: __ghes_panic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __ghes_panic(struct ghes *ghes, struct acpi_hest_generic_status *estatus, u64 buf_paddr, enum fixed_addresses fixmap_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff81a7b4d0)
Location: drivers/acpi/apei/ghes.c:898
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff81a7b4d0-ffffffff81a7b53c: __ghes_panic (STB_LOCAL)
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
void __ghes_panic(struct ghes *ghes, struct acpi_hest_generic_status *estatus, u64 buf_paddr, enum fixed_addresses fixmap_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffff8000107afa50)
Location: drivers/acpi/apei/ghes.c:706
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_in_nmi_queue_one_entry
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffff8000107afa50-ffff8000107afacc: __ghes_panic (STB_LOCAL)
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
In drivers/acpi/apei/ghes.c (ffffffff81638677)
Location: drivers/acpi/apei/ghes.c:706
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff81638d69-ffffffff81638d93: __ghes_panic.part.0 (STB_LOCAL)
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
In drivers/acpi/apei/ghes.c (ffffffff816529b7)
Location: drivers/acpi/apei/ghes.c:706
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff816530b9-ffffffff816530e3: __ghes_panic.part.0 (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
