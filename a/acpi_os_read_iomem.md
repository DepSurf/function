# Function: <code>acpi_os_read_iomem</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int acpi_os_read_iomem(void *virt_addr, u64 *value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81536bd0)
Location: drivers/acpi/osl.c:666
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
**Symbols:**

```
ffffffff81536b00-ffffffff81536b4a: acpi_os_read_iomem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int acpi_os_read_iomem(void *virt_addr, u64 *value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8156c7dd)
Location: drivers/acpi/osl.c:671
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
**Symbols:**

```
ffffffff8156c710-ffffffff8156c75a: acpi_os_read_iomem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int acpi_os_read_iomem(void *virt_addr, u64 *value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8158440d)
Location: drivers/acpi/osl.c:674
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
**Symbols:**

```
ffffffff81584340-ffffffff8158438a: acpi_os_read_iomem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int acpi_os_read_iomem(void *virt_addr, u64 *value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815b5012)
Location: drivers/acpi/osl.c:660
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
Direct callers:
  - drivers/acpi/acpi_lpit.c:lpit_read_residency_counter_us
```
**Symbols:**

```
ffffffff815b4f40-ffffffff815b4f8a: acpi_os_read_iomem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int acpi_os_read_iomem(void *virt_addr, u64 *value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815d6242)
Location: drivers/acpi/osl.c:680
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
Direct callers:
  - drivers/acpi/acpi_lpit.c:lpit_read_residency_counter_us
```
**Symbols:**

```
ffffffff815d6170-ffffffff815d61ba: acpi_os_read_iomem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int acpi_os_read_iomem(void *virt_addr, u64 *value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8167ff42)
Location: drivers/acpi/osl.c:680
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
Direct callers:
  - drivers/acpi/acpi_lpit.c:low_power_idle_system_residency_us_show
```
**Symbols:**

```
ffffffff8167fe70-ffffffff8167feba: acpi_os_read_iomem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int acpi_os_read_iomem(void *virt_addr, u64 *value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8169ea01)
Location: drivers/acpi/osl.c:684
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
Direct callers:
  - drivers/acpi/acpi_lpit.c:low_power_idle_system_residency_us_show
```
**Symbols:**

```
ffffffff8169e920-ffffffff8169e96a: acpi_os_read_iomem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int acpi_os_read_iomem(void *virt_addr, u64 *value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff816816b3)
Location: drivers/acpi/osl.c:685
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
Direct callers:
  - drivers/acpi/acpi_lpit.c:lpit_read_residency_counter_us
```
**Symbols:**

```
ffffffff816815d0-ffffffff8168161a: acpi_os_read_iomem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int acpi_os_read_iomem(void *virt_addr, u64 *value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff816f67a3)
Location: drivers/acpi/osl.c:685
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
Direct callers:
  - drivers/acpi/acpi_lpit.c:lpit_read_residency_counter_us
```
**Symbols:**

```
ffffffff816f66c0-ffffffff816f670a: acpi_os_read_iomem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int acpi_os_read_iomem(void *virt_addr, u64 *value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81823604)
Location: drivers/acpi/osl.c:687
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
Direct callers:
  - drivers/acpi/acpi_lpit.c:lpit_read_residency_counter_us
```
**Symbols:**

```
ffffffff818234f0-ffffffff8182354e: acpi_os_read_iomem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int acpi_os_read_iomem(void *virt_addr, u64 *value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81954854)
Location: drivers/acpi/osl.c:687
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
Direct callers:
  - drivers/acpi/acpi_lpit.c:lpit_read_residency_counter_us
```
**Symbols:**

```
ffffffff81954730-ffffffff8195478e: acpi_os_read_iomem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int acpi_os_read_iomem(void *virt_addr, u64 *value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8199ac64)
Location: drivers/acpi/osl.c:687
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
Direct callers:
  - drivers/acpi/acpi_lpit.c:lpit_read_residency_counter_us
```
**Symbols:**

```
ffffffff8199ab40-ffffffff8199ab9e: acpi_os_read_iomem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int acpi_os_read_iomem(void *virt_addr, u64 *value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff819e30e4)
Location: drivers/acpi/osl.c:684
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
Direct callers:
  - drivers/acpi/acpi_lpit.c:lpit_read_residency_counter_us
```
**Symbols:**

```
ffffffff819e2fc0-ffffffff819e301e: acpi_os_read_iomem (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int acpi_os_read_iomem(void *virt_addr, u64 *value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffff800010763a88)
Location: drivers/acpi/osl.c:680
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
**Symbols:**

```
ffff800010763a88-ffff800010763b90: acpi_os_read_iomem (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int acpi_os_read_iomem(void *virt_addr, u64 *value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815c9fa2)
Location: drivers/acpi/osl.c:680
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
Direct callers:
  - drivers/acpi/acpi_lpit.c:lpit_read_residency_counter_us
```
**Symbols:**

```
ffffffff815c9ed0-ffffffff815c9f1a: acpi_os_read_iomem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int acpi_os_read_iomem(void *virt_addr, u64 *value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815b3022)
Location: drivers/acpi/osl.c:680
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
Direct callers:
  - drivers/acpi/acpi_lpit.c:lpit_read_residency_counter_us
```
**Symbols:**

```
ffffffff815b2f50-ffffffff815b2f9a: acpi_os_read_iomem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int acpi_os_read_iomem(void *virt_addr, u64 *value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815ca522)
Location: drivers/acpi/osl.c:680
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
Direct callers:
  - drivers/acpi/acpi_lpit.c:lpit_read_residency_counter_us
```
**Symbols:**

```
ffffffff815ca450-ffffffff815ca49a: acpi_os_read_iomem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int acpi_os_read_iomem(void *virt_addr, u64 *value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815e4396)
Location: drivers/acpi/osl.c:680
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
Direct callers:
  - drivers/acpi/acpi_lpit.c:lpit_read_residency_counter_us
```
**Symbols:**

```
ffffffff815e42b0-ffffffff815e42fa: acpi_os_read_iomem (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
