# Function: <code>set_memory_np</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int set_memory_np(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106f3b0)
Location: arch/x86/mm/pageattr.c:1713
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
**Symbols:**

```
ffffffff8106f3b0-ffffffff8106f3e1: set_memory_np (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int set_memory_np(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106f110)
Location: arch/x86/mm/pageattr.c:1721
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
**Symbols:**

```
ffffffff8106f110-ffffffff8106f141: set_memory_np (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int set_memory_np(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81072d80)
Location: arch/x86/mm/pageattr.c:1721
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
**Symbols:**

```
ffffffff81072d80-ffffffff81072db1: set_memory_np (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int set_memory_np(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81072310)
Location: arch/x86/mm/pageattr.c:1767
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:arch_unmap_kpfn
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
**Symbols:**

```
ffffffff81072310-ffffffff8107233b: set_memory_np (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int set_memory_np(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81077b80)
Location: arch/x86/mm/pageattr.c:1767
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_unmap_kpfn
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
**Symbols:**

```
ffffffff81077b80-ffffffff81077bab: set_memory_np (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int set_memory_np(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8107a5c0)
Location: arch/x86/mm/pageattr.c:1797
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
**Symbols:**

```
ffffffff8107a5c0-ffffffff8107a5eb: set_memory_np (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int set_memory_np(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81080d70)
Location: arch/x86/mm/pageattr.c:1990
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
**Symbols:**

```
ffffffff81080d70-ffffffff81080d9b: set_memory_np (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int set_memory_np(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81084850)
Location: arch/x86/mm/pageattr.c:2001
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
**Symbols:**

```
ffffffff81084850-ffffffff8108487b: set_memory_np (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int set_memory_np(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81085550)
Location: arch/x86/mm/pageattr.c:1907
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
**Symbols:**

```
ffffffff81085550-ffffffff8108557b: set_memory_np (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int set_memory_np(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108f270)
Location: arch/x86/mm/pat/set_memory.c:1943
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
**Symbols:**

```
ffffffff8108f270-ffffffff8108f29b: set_memory_np (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int set_memory_np(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108f060)
Location: arch/x86/mm/pat/set_memory.c:1943
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
**Symbols:**

```
ffffffff8108f060-ffffffff8108f08b: set_memory_np (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int set_memory_np(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108fbf0)
Location: arch/x86/mm/pat/set_memory.c:1951
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
**Symbols:**

```
ffffffff8108fbf0-ffffffff8108fc1b: set_memory_np (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int set_memory_np(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8109f6d0)
Location: arch/x86/mm/pat/set_memory.c:1951
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
**Symbols:**

```
ffffffff8109f6d0-ffffffff8109f6fb: set_memory_np (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int set_memory_np(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810b32f3)
Location: arch/x86/mm/pat/set_memory.c:1988
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_mce_nospec
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
**Symbols:**

```
ffffffff810b3470-ffffffff810b34ad: set_memory_np (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int set_memory_np(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810cdd73)
Location: arch/x86/mm/pat/set_memory.c:2094
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_mce_nospec
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
**Symbols:**

```
ffffffff810cdfc0-ffffffff810cdffd: set_memory_np (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int set_memory_np(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d1337)
Location: arch/x86/mm/pat/set_memory.c:2095
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_mce_nospec
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
**Symbols:**

```
ffffffff810d1580-ffffffff810d15bd: set_memory_np (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int set_memory_np(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d9a17)
Location: arch/x86/mm/pat/set_memory.c:2094
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_mce_nospec
Direct callers:
  - arch/x86/hyperv/ivm.c:hv_vtom_clear_present
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
**Symbols:**

```
ffffffff810d9c60-ffffffff810d9c9d: set_memory_np (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int set_memory_np(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81084550)
Location: arch/x86/mm/pageattr.c:1907
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
**Symbols:**

```
ffffffff81084550-ffffffff8108457b: set_memory_np (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int set_memory_np(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81073160)
Location: arch/x86/mm/pageattr.c:1907
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
**Symbols:**

```
ffffffff81073160-ffffffff8107318b: set_memory_np (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int set_memory_np(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81084500)
Location: arch/x86/mm/pageattr.c:1907
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
**Symbols:**

```
ffffffff81084500-ffffffff8108452b: set_memory_np (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int set_memory_np(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81086640)
Location: arch/x86/mm/pageattr.c:1907
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
**Symbols:**

```
ffffffff81086640-ffffffff8108666b: set_memory_np (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
