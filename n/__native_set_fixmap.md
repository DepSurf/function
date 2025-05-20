# Function: <code>__native_set_fixmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __native_set_fixmap(enum fixed_addresses idx, pte_t pte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81071100)
Location: arch/x86/mm/pgtable.c:547
Inline: True
Direct callers:
  - arch/x86/xen/mmu.c:xen_set_fixmap
  - arch/x86/xen/mmu.c:xen_set_fixmap
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
**Symbols:**

```
ffffffff81071100-ffffffff81071133: __native_set_fixmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __native_set_fixmap(enum fixed_addresses idx, pte_t pte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81070ff0)
Location: arch/x86/mm/pgtable.c:533
Inline: True
Direct callers:
  - arch/x86/xen/mmu.c:xen_set_fixmap
  - arch/x86/xen/mmu.c:xen_set_fixmap
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
**Symbols:**

```
ffffffff81070ff0-ffffffff81071023: __native_set_fixmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __native_set_fixmap(enum fixed_addresses idx, pte_t pte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81074b70)
Location: arch/x86/mm/pgtable.c:533
Inline: True
Direct callers:
  - arch/x86/xen/mmu.c:xen_set_fixmap
  - arch/x86/xen/mmu.c:xen_set_fixmap
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
**Symbols:**

```
ffffffff81074b70-ffffffff81074ba3: __native_set_fixmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __native_set_fixmap(enum fixed_addresses idx, pte_t pte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81074140)
Location: arch/x86/mm/pgtable.c:574
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
**Symbols:**

```
ffffffff81074140-ffffffff81074173: __native_set_fixmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __native_set_fixmap(enum fixed_addresses idx, pte_t pte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81079bd0)
Location: arch/x86/mm/pgtable.c:571
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
**Symbols:**

```
ffffffff81079bd0-ffffffff81079c03: __native_set_fixmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __native_set_fixmap(enum fixed_addresses idx, pte_t pte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8107c760)
Location: arch/x86/mm/pgtable.c:576
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
**Symbols:**

```
ffffffff8107c760-ffffffff8107c793: __native_set_fixmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __native_set_fixmap(enum fixed_addresses idx, pte_t pte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81083190)
Location: arch/x86/mm/pgtable.c:642
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
**Symbols:**

```
ffffffff81083190-ffffffff810831c3: __native_set_fixmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __native_set_fixmap(enum fixed_addresses idx, pte_t pte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81086e00)
Location: arch/x86/mm/pgtable.c:629
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
**Symbols:**

```
ffffffff81086e00-ffffffff81086e33: __native_set_fixmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __native_set_fixmap(enum fixed_addresses idx, pte_t pte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81087af0)
Location: arch/x86/mm/pgtable.c:625
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
**Symbols:**

```
ffffffff81087af0-ffffffff81087b23: __native_set_fixmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __native_set_fixmap(enum fixed_addresses idx, pte_t pte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81089ff2)
Location: arch/x86/mm/pgtable.c:632
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:native_set_fixmap
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
**Symbols:**

```
ffffffff81089880-ffffffff8108988b: __native_set_fixmap.part.0 (STB_LOCAL)
ffffffff81089f50-ffffffff81089f86: __native_set_fixmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __native_set_fixmap(enum fixed_addresses idx, pte_t pte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8108a272)
Location: arch/x86/mm/pgtable.c:632
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:native_set_fixmap
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
**Symbols:**

```
ffffffff81089a60-ffffffff81089a6b: __native_set_fixmap.part.0 (STB_LOCAL)
ffffffff8108a1d0-ffffffff8108a206: __native_set_fixmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __native_set_fixmap(enum fixed_addresses idx, pte_t pte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8108aec7)
Location: arch/x86/mm/pgtable.c:632
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:native_set_fixmap
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
**Symbols:**

```
ffffffff8108a700-ffffffff8108a70b: __native_set_fixmap.part.0 (STB_LOCAL)
ffffffff8108ae30-ffffffff8108ae64: __native_set_fixmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __native_set_fixmap(enum fixed_addresses idx, pte_t pte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8109a467)
Location: arch/x86/mm/pgtable.c:632
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:native_set_fixmap
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
```
**Symbols:**

```
ffffffff8109a3d0-ffffffff8109a401: __native_set_fixmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __native_set_fixmap(enum fixed_addresses idx, pte_t pte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810ad68a)
Location: arch/x86/mm/pgtable.c:642
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
**Symbols:**

```
ffffffff810ad610-ffffffff810ad64d: __native_set_fixmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __native_set_fixmap(enum fixed_addresses idx, pte_t pte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810c77ef)
Location: arch/x86/mm/pgtable.c:649
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
**Symbols:**

```
ffffffff810c7770-ffffffff810c77ad: __native_set_fixmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __native_set_fixmap(enum fixed_addresses idx, pte_t pte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810caf5e)
Location: arch/x86/mm/pgtable.c:649
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
**Symbols:**

```
ffffffff810caed0-ffffffff810caf0d: __native_set_fixmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __native_set_fixmap(enum fixed_addresses idx, pte_t pte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810d34ae)
Location: arch/x86/mm/pgtable.c:661
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
**Symbols:**

```
ffffffff810d3420-ffffffff810d345d: __native_set_fixmap (STB_GLOBAL)
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
void __native_set_fixmap(enum fixed_addresses idx, pte_t pte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81086af0)
Location: arch/x86/mm/pgtable.c:625
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
**Symbols:**

```
ffffffff81086af0-ffffffff81086b23: __native_set_fixmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __native_set_fixmap(enum fixed_addresses idx, pte_t pte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81075780)
Location: arch/x86/mm/pgtable.c:625
Inline: True
Direct callers:
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
**Symbols:**

```
ffffffff81075780-ffffffff810757b3: __native_set_fixmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __native_set_fixmap(enum fixed_addresses idx, pte_t pte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81086aa0)
Location: arch/x86/mm/pgtable.c:625
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
**Symbols:**

```
ffffffff81086aa0-ffffffff81086ad3: __native_set_fixmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __native_set_fixmap(enum fixed_addresses idx, pte_t pte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81088bd0)
Location: arch/x86/mm/pgtable.c:625
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
**Symbols:**

```
ffffffff81088bd0-ffffffff81088c03: __native_set_fixmap (STB_GLOBAL)
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
