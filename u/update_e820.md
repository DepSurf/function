# Function: <code>update_e820</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void update_e820();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff81f67f36)
Location: arch/x86/kernel/e820.c:567
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory
  - arch/x86/kernel/acpi/boot.c:arch_reserve_mem_area
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
```
**Symbols:**

```
ffffffff81f67f36-ffffffff81f67f70: update_e820 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void update_e820();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff81f8fdeb)
Location: arch/x86/kernel/e820.c:567
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory
  - arch/x86/kernel/acpi/boot.c:arch_reserve_mem_area
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
```
**Symbols:**

```
ffffffff81f8fdeb-ffffffff81f8fe25: update_e820 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void update_e820();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff81fcb1c0)
Location: arch/x86/kernel/e820.c:569
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory
  - arch/x86/kernel/acpi/boot.c:arch_reserve_mem_area
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
```
**Symbols:**

```
ffffffff81fcb1c0-ffffffff81fcb1f7: update_e820 (STB_GLOBAL)
```
</details>
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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
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
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
