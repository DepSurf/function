# Function: <code>acpi_os_map_cleanup</code>

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
In drivers/acpi/osl.c (ffffffff81479b45)
Location: drivers/acpi/osl.c:434
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
Direct callers:
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
```
**Symbols:**

```
ffffffff81479b45-ffffffff81479b83: acpi_os_map_cleanup.part.7 (STB_LOCAL)
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
In drivers/acpi/osl.c (ffffffff8189503d)
Location: drivers/acpi/osl.c:378
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
Direct callers:
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
```
**Symbols:**

```
ffffffff814c810a-ffffffff814c8148: acpi_os_map_cleanup.part.10 (STB_LOCAL)
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
In drivers/acpi/osl.c (ffffffff818c9796)
Location: drivers/acpi/osl.c:379
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
Direct callers:
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
```
**Symbols:**

```
ffffffff814ea01a-ffffffff814ea058: acpi_os_map_cleanup.part.12 (STB_LOCAL)
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
In drivers/acpi/osl.c (ffffffff81900d3d)
Location: drivers/acpi/osl.c:378
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
Direct callers:
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
```
**Symbols:**

```
ffffffff814f5d00-ffffffff814f5d3e: acpi_os_map_cleanup.part.14 (STB_LOCAL)
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
In drivers/acpi/osl.c (ffffffff8198ad3d)
Location: drivers/acpi/osl.c:378
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
Direct callers:
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
```
**Symbols:**

```
ffffffff81536640-ffffffff8153667e: acpi_os_map_cleanup.part.11 (STB_LOCAL)
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
In drivers/acpi/osl.c (ffffffff819e767e)
Location: drivers/acpi/osl.c:383
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
Direct callers:
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
```
**Symbols:**

```
ffffffff8156c2a0-ffffffff8156c2eb: acpi_os_map_cleanup.part.11 (STB_LOCAL)
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
In drivers/acpi/osl.c (ffffffff81a22aee)
Location: drivers/acpi/osl.c:383
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
Direct callers:
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
```
**Symbols:**

```
ffffffff81583ed0-ffffffff81583f1b: acpi_os_map_cleanup.part.11 (STB_LOCAL)
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
In drivers/acpi/osl.c (ffffffff81a92ba8)
Location: drivers/acpi/osl.c:369
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
Direct callers:
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
```
**Symbols:**

```
ffffffff815b4ac0-ffffffff815b4b10: acpi_os_map_cleanup.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void acpi_os_map_cleanup(struct acpi_ioremap *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815d5ab0)
Location: drivers/acpi/osl.c:387
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
```
**Symbols:**

```
ffffffff815d5ab0-ffffffff815d5b00: acpi_os_map_cleanup (STB_LOCAL)
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
In drivers/acpi/osl.c (ffffffff81bc26c6)
Location: drivers/acpi/osl.c:387
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In drivers/acpi/osl.c (ffff800010d9dbf4)
Location: drivers/acpi/osl.c:387
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
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
void acpi_os_map_cleanup(struct acpi_ioremap *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815c9750)
Location: drivers/acpi/osl.c:387
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
```
**Symbols:**

```
ffffffff815c9750-ffffffff815c97a0: acpi_os_map_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void acpi_os_map_cleanup(struct acpi_ioremap *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815b27e0)
Location: drivers/acpi/osl.c:387
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
```
**Symbols:**

```
ffffffff815b27e0-ffffffff815b2830: acpi_os_map_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void acpi_os_map_cleanup(struct acpi_ioremap *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815c9d90)
Location: drivers/acpi/osl.c:387
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
```
**Symbols:**

```
ffffffff815c9d90-ffffffff815c9de0: acpi_os_map_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void acpi_os_map_cleanup(struct acpi_ioremap *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815e3bf0)
Location: drivers/acpi/osl.c:387
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
```
**Symbols:**

```
ffffffff815e3bf0-ffffffff815e3c40: acpi_os_map_cleanup (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
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
