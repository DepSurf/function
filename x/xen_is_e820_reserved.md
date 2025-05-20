# Function: <code>xen_is_e820_reserved</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool xen_is_e820_reserved(phys_addr_t start, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff81f610c0)
Location: arch/x86/xen/setup.c:628
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu.c:xen_pt_check_e820
```
**Symbols:**

```
ffffffff81f610c0-ffffffff81f6110a: xen_is_e820_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool xen_is_e820_reserved(phys_addr_t start, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff81f89289)
Location: arch/x86/xen/setup.c:613
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu.c:xen_pt_check_e820
```
**Symbols:**

```
ffffffff81f89289-ffffffff81f892d3: xen_is_e820_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool xen_is_e820_reserved(phys_addr_t start, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff81fc467d)
Location: arch/x86/xen/setup.c:613
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu.c:xen_pt_check_e820
```
**Symbols:**

```
ffffffff81fc467d-ffffffff81fc46c7: xen_is_e820_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool xen_is_e820_reserved(phys_addr_t start, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff820a44c5)
Location: arch/x86/xen/setup.c:609
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu_pv.c:xen_pt_check_e820
```
**Symbols:**

```
ffffffff820a44c5-ffffffff820a4517: xen_is_e820_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool xen_is_e820_reserved(phys_addr_t start, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff826aaba3)
Location: arch/x86/xen/setup.c:608
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu_pv.c:xen_pt_check_e820
```
**Symbols:**

```
ffffffff826aaba3-ffffffff826aabf5: xen_is_e820_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool xen_is_e820_reserved(phys_addr_t start, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff826d3d17)
Location: arch/x86/xen/setup.c:608
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu_pv.c:xen_pt_check_e820
```
**Symbols:**

```
ffffffff826d3d17-ffffffff826d3d6a: xen_is_e820_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool xen_is_e820_reserved(phys_addr_t start, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff82889daa)
Location: arch/x86/xen/setup.c:608
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu_pv.c:xen_pt_check_e820
```
**Symbols:**

```
ffffffff82889daa-ffffffff82889dfd: xen_is_e820_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool xen_is_e820_reserved(phys_addr_t start, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff828a1167)
Location: arch/x86/xen/setup.c:617
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu_pv.c:xen_pt_check_e820
```
**Symbols:**

```
ffffffff828a1167-ffffffff828a11ba: xen_is_e820_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool xen_is_e820_reserved(phys_addr_t start, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff828a4227)
Location: arch/x86/xen/setup.c:617
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu_pv.c:xen_pt_check_e820
```
**Symbols:**

```
ffffffff828a4227-ffffffff828a427a: xen_is_e820_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool xen_is_e820_reserved(phys_addr_t start, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff82cca787)
Location: arch/x86/xen/setup.c:618
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu_pv.c:xen_pt_check_e820
```
**Symbols:**

```
ffffffff82cca787-ffffffff82cca7da: xen_is_e820_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool xen_is_e820_reserved(phys_addr_t start, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff82fb65f5)
Location: arch/x86/xen/setup.c:614
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu_pv.c:xen_pt_check_e820
```
**Symbols:**

```
ffffffff82fb65f5-ffffffff82fb6648: xen_is_e820_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool xen_is_e820_reserved(phys_addr_t start, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff831c0ce8)
Location: arch/x86/xen/setup.c:614
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu_pv.c:xen_pt_check_e820
```
**Symbols:**

```
ffffffff831c0ce8-ffffffff831c0d3b: xen_is_e820_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool xen_is_e820_reserved(phys_addr_t start, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff832a15a2)
Location: arch/x86/xen/setup.c:614
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu_pv.c:xen_pt_check_e820
```
**Symbols:**

```
ffffffff832a15a2-ffffffff832a15f5: xen_is_e820_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool xen_is_e820_reserved(phys_addr_t start, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff8345060c)
Location: arch/x86/xen/setup.c:610
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu_pv.c:xen_pt_check_e820
```
**Symbols:**

```
ffffffff8345060c-ffffffff8345066b: xen_is_e820_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool xen_is_e820_reserved(phys_addr_t start, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff83e6d40e)
Location: arch/x86/xen/setup.c:611
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pt_check_e820
```
**Symbols:**

```
ffffffff83e6cb10-ffffffff83e6cb85: xen_is_e820_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool xen_is_e820_reserved(phys_addr_t start, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff8368df47)
Location: arch/x86/xen/setup.c:612
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pt_check_e820
```
**Symbols:**

```
ffffffff8368d630-ffffffff8368d6a5: xen_is_e820_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool xen_is_e820_reserved(phys_addr_t start, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff838bdb15)
Location: arch/x86/xen/setup.c:615
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pt_check_e820
```
**Symbols:**

```
ffffffff838bd1f0-ffffffff838bd265: xen_is_e820_reserved (STB_GLOBAL)
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
bool xen_is_e820_reserved(phys_addr_t start, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff8289224d)
Location: arch/x86/xen/setup.c:617
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu_pv.c:xen_pt_check_e820
```
**Symbols:**

```
ffffffff8289224d-ffffffff828922a0: xen_is_e820_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool xen_is_e820_reserved(phys_addr_t start, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff828a5227)
Location: arch/x86/xen/setup.c:617
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu_pv.c:xen_pt_check_e820
```
**Symbols:**

```
ffffffff828a5227-ffffffff828a527a: xen_is_e820_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool xen_is_e820_reserved(phys_addr_t start, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff828a51fb)
Location: arch/x86/xen/setup.c:617
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu_pv.c:xen_pt_check_e820
```
**Symbols:**

```
ffffffff828a51fb-ffffffff828a524e: xen_is_e820_reserved (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
