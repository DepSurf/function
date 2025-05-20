# Function: <code>get_amd_iommu</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct amd_iommu *get_amd_iommu(unsigned int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff815ca225)
Location: drivers/iommu/amd_iommu_init.c:2745
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_max_counters
  - drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_max_banks
```
**Symbols:**

```
ffffffff815ca170-ffffffff815ca1ac: get_amd_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct amd_iommu *get_amd_iommu(unsigned int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff81630c15)
Location: drivers/iommu/amd_iommu_init.c:2942
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_max_counters
  - drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_max_banks
```
**Symbols:**

```
ffffffff81630b60-ffffffff81630b9c: get_amd_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct amd_iommu *get_amd_iommu(unsigned int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff8166bac5)
Location: drivers/iommu/amd_iommu_init.c:2943
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_max_counters
  - drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_max_banks
Direct callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
```
**Symbols:**

```
ffffffff8166ba10-ffffffff8166ba4b: get_amd_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct amd_iommu *get_amd_iommu(unsigned int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff8168a215)
Location: drivers/iommu/amd_iommu_init.c:2979
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_max_counters
  - drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_max_banks
Direct callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
```
**Symbols:**

```
ffffffff8168a160-ffffffff8168a19b: get_amd_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct amd_iommu *get_amd_iommu(unsigned int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816c1bc5)
Location: drivers/iommu/amd_iommu_init.c:3053
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_max_counters
  - drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_max_banks
Direct callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
```
**Symbols:**

```
ffffffff816c1b10-ffffffff816c1b4b: get_amd_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct amd_iommu *get_amd_iommu(unsigned int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816e4ae5)
Location: drivers/iommu/amd_iommu_init.c:3084
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_max_counters
  - drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_max_banks
Direct callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
```
**Symbols:**

```
ffffffff816e4a30-ffffffff816e4a6b: get_amd_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct amd_iommu *get_amd_iommu(unsigned int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8179ab85)
Location: drivers/iommu/amd/init.c:3054
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_pc_get_max_counters
  - drivers/iommu/amd/init.c:amd_iommu_pc_get_max_banks
Direct callers:
  - arch/x86/events/amd/iommu.c:init_one_iommu
```
**Symbols:**

```
ffffffff8179aad0-ffffffff8179ab0b: get_amd_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct amd_iommu *get_amd_iommu(unsigned int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff817a8ec5)
Location: drivers/iommu/amd/init.c:3269
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_pc_get_max_counters
  - drivers/iommu/amd/init.c:amd_iommu_pc_get_max_banks
Direct callers:
  - arch/x86/events/amd/iommu.c:init_one_iommu
```
**Symbols:**

```
ffffffff817a8e10-ffffffff817a8e4b: get_amd_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct amd_iommu *get_amd_iommu(unsigned int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8178ac15)
Location: drivers/iommu/amd/init.c:3217
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_pc_get_max_counters
  - drivers/iommu/amd/init.c:amd_iommu_pc_get_max_banks
Direct callers:
  - arch/x86/events/amd/iommu.c:init_one_iommu
```
**Symbols:**

```
ffffffff8178bbb0-ffffffff8178bbeb: get_amd_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct amd_iommu *get_amd_iommu(unsigned int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81811d85)
Location: drivers/iommu/amd/init.c:3257
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_pc_get_max_counters
  - drivers/iommu/amd/init.c:amd_iommu_pc_get_max_banks
Direct callers:
  - arch/x86/events/amd/iommu.c:init_one_iommu
```
**Symbols:**

```
ffffffff818131a0-ffffffff818131db: get_amd_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct amd_iommu *get_amd_iommu(unsigned int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81952bd5)
Location: drivers/iommu/amd/init.c:3267
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_pc_get_max_counters
  - drivers/iommu/amd/init.c:amd_iommu_pc_get_max_banks
Direct callers:
  - arch/x86/events/amd/iommu.c:init_one_iommu
```
**Symbols:**

```
ffffffff81954130-ffffffff81954175: get_amd_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct amd_iommu *get_amd_iommu(unsigned int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81ab80f5)
Location: drivers/iommu/amd/init.c:3568
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_pc_get_max_counters
  - drivers/iommu/amd/init.c:amd_iommu_pc_get_max_banks
Direct callers:
  - arch/x86/events/amd/iommu.c:init_one_iommu
```
**Symbols:**

```
ffffffff81ab9df0-ffffffff81ab9e35: get_amd_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct amd_iommu *get_amd_iommu(unsigned int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81b04445)
Location: drivers/iommu/amd/init.c:3648
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_pc_get_max_counters
  - drivers/iommu/amd/init.c:amd_iommu_pc_get_max_banks
Direct callers:
  - arch/x86/events/amd/iommu.c:init_one_iommu
```
**Symbols:**

```
ffffffff81b06390-ffffffff81b063d5: get_amd_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct amd_iommu *get_amd_iommu(unsigned int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81b58025)
Location: drivers/iommu/amd/init.c:3670
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_pc_get_max_counters
  - drivers/iommu/amd/init.c:amd_iommu_pc_get_max_banks
Direct callers:
  - arch/x86/events/amd/iommu.c:init_one_iommu
```
**Symbols:**

```
ffffffff81b5a1a0-ffffffff81b5a1e5: get_amd_iommu (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct amd_iommu *get_amd_iommu(unsigned int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816aa5c5)
Location: drivers/iommu/amd_iommu_init.c:3084
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_max_counters
  - drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_max_banks
Direct callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
```
**Symbols:**

```
ffffffff816aa510-ffffffff816aa54b: get_amd_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct amd_iommu *get_amd_iommu(unsigned int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff81687db5)
Location: drivers/iommu/amd_iommu_init.c:3084
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_max_counters
  - drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_max_banks
Direct callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
```
**Symbols:**

```
ffffffff81687d00-ffffffff81687d3b: get_amd_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct amd_iommu *get_amd_iommu(unsigned int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816d87a5)
Location: drivers/iommu/amd_iommu_init.c:3084
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_max_counters
  - drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_max_banks
Direct callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
```
**Symbols:**

```
ffffffff816d86f0-ffffffff816d872b: get_amd_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct amd_iommu *get_amd_iommu(unsigned int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816f2d55)
Location: drivers/iommu/amd_iommu_init.c:3084
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_max_counters
  - drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_max_banks
Direct callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
```
**Symbols:**

```
ffffffff816f2ca0-ffffffff816f2cdb: get_amd_iommu (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
