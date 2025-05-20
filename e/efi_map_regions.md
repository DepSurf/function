# Function: <code>efi_map_regions</code>

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
In arch/x86/platform/efi/efi.c (ffffffff81f7a82b)
Location: arch/x86/platform/efi/efi.c:775
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
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
In arch/x86/platform/efi/efi.c (ffffffff81fa30f0)
Location: arch/x86/platform/efi/efi.c:752
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
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
In arch/x86/platform/efi/efi.c (ffffffff81fdea2f)
Location: arch/x86/platform/efi/efi.c:788
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
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
In arch/x86/platform/efi/efi.c (ffffffff820bf82d)
Location: arch/x86/platform/efi/efi.c:784
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
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
In arch/x86/platform/efi/efi.c (ffffffff826c7959)
Location: arch/x86/platform/efi/efi.c:785
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
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
In arch/x86/platform/efi/efi.c (0)
Location: arch/x86/platform/efi/efi.c:785
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
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
In arch/x86/platform/efi/efi.c (0)
Location: arch/x86/platform/efi/efi.c:784
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
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
In arch/x86/platform/efi/efi.c (0)
Location: arch/x86/platform/efi/efi.c:786
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
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
In arch/x86/platform/efi/efi.c (0)
Location: arch/x86/platform/efi/efi.c:810
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *efi_map_regions(int *count, int *pg_shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff82ce9e64)
Location: arch/x86/platform/efi/efi.c:736
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
```
**Symbols:**

```
ffffffff82ce9e64-ffffffff82cea00b: efi_map_regions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *efi_map_regions(int *count, int *pg_shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff82fd78cf)
Location: arch/x86/platform/efi/efi.c:670
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
```
**Symbols:**

```
ffffffff82fd78cf-ffffffff82fd7a6b: efi_map_regions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *efi_map_regions(int *count, int *pg_shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff831e1f7a)
Location: arch/x86/platform/efi/efi.c:670
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
```
**Symbols:**

```
ffffffff831e1f7a-ffffffff831e2116: efi_map_regions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *efi_map_regions(int *count, int *pg_shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff832c58a2)
Location: arch/x86/platform/efi/efi.c:670
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
```
**Symbols:**

```
ffffffff832c58a2-ffffffff832c5a7e: efi_map_regions (STB_LOCAL)
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
In arch/x86/platform/efi/efi.c (ffffffff834785fa)
Location: arch/x86/platform/efi/efi.c:673
Inline: True
Direct callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
```
**Symbols:**

```
ffffffff834785fa-ffffffff83478825: efi_map_regions.constprop.0 (STB_LOCAL)
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
In arch/x86/platform/efi/efi.c (ffffffff83ea27d0)
Location: arch/x86/platform/efi/efi.c:698
Inline: True
Direct callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
```
**Symbols:**

```
ffffffff83ea27d0-ffffffff83ea298b: efi_map_regions.constprop.0 (STB_LOCAL)
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
In arch/x86/platform/efi/efi.c (ffffffff836c6a20)
Location: arch/x86/platform/efi/efi.c:701
Inline: True
Direct callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
```
**Symbols:**

```
ffffffff836c6a20-ffffffff836c6bd9: efi_map_regions.constprop.0 (STB_LOCAL)
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
In arch/x86/platform/efi/efi.c (ffffffff838f7620)
Location: arch/x86/platform/efi/efi.c:701
Inline: True
Direct callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
```
**Symbols:**

```
ffffffff838f7620-ffffffff838f77d9: efi_map_regions.constprop.0 (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (0)
Location: arch/x86/platform/efi/efi.c:810
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
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
In arch/x86/platform/efi/efi.c (0)
Location: arch/x86/platform/efi/efi.c:810
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (0)
Location: arch/x86/platform/efi/efi.c:810
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
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
In arch/x86/platform/efi/efi.c (0)
Location: arch/x86/platform/efi/efi.c:810
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
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
</ul>
