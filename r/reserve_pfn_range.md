# Function: <code>reserve_pfn_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int reserve_pfn_range(u64 paddr, long unsigned int size, pgprot_t *vma_prot, int strict_prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81070670)
Location: arch/x86/mm/pat.c:798
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:track_pfn_copy
  - arch/x86/mm/pat.c:track_pfn_remap
```
**Symbols:**

```
ffffffff81070670-ffffffff810708ea: reserve_pfn_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int reserve_pfn_range(u64 paddr, long unsigned int size, pgprot_t *vma_prot, int strict_prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81070400)
Location: arch/x86/mm/pat.c:820
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:track_pfn_copy
```
**Symbols:**

```
ffffffff81070400-ffffffff8107066d: reserve_pfn_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int reserve_pfn_range(u64 paddr, long unsigned int size, pgprot_t *vma_prot, int strict_prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81074090)
Location: arch/x86/mm/pat.c:834
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:track_pfn_copy
```
**Symbols:**

```
ffffffff81074090-ffffffff810742fd: reserve_pfn_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int reserve_pfn_range(u64 paddr, long unsigned int size, pgprot_t *vma_prot, int strict_prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81073610)
Location: arch/x86/mm/pat.c:831
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:track_pfn_copy
```
**Symbols:**

```
ffffffff81073610-ffffffff81073878: reserve_pfn_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int reserve_pfn_range(u64 paddr, long unsigned int size, pgprot_t *vma_prot, int strict_prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81078fd0)
Location: arch/x86/mm/pat.c:853
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:track_pfn_copy
```
**Symbols:**

```
ffffffff81078fd0-ffffffff8107923e: reserve_pfn_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int reserve_pfn_range(u64 paddr, long unsigned int size, pgprot_t *vma_prot, int strict_prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (0)
Location: arch/x86/mm/pat.c:869
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:track_pfn_copy
```
**Symbols:**

```
ffffffff8107b9a0-ffffffff8107bb46: reserve_pfn_range (STB_LOCAL)
ffffffff8107c076-ffffffff8107c175: reserve_pfn_range.cold.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int reserve_pfn_range(u64 paddr, long unsigned int size, pgprot_t *vma_prot, int strict_prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (0)
Location: arch/x86/mm/pat.c:878
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:track_pfn_copy
```
**Symbols:**

```
ffffffff81082310-ffffffff810824b6: reserve_pfn_range (STB_LOCAL)
ffffffff810829e6-ffffffff81082ae5: reserve_pfn_range.cold.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int reserve_pfn_range(u64 paddr, long unsigned int size, pgprot_t *vma_prot, int strict_prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (0)
Location: arch/x86/mm/pat.c:879
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:track_pfn_copy
```
**Symbols:**

```
ffffffff81085f90-ffffffff81086132: reserve_pfn_range (STB_LOCAL)
ffffffff81086625-ffffffff81086722: reserve_pfn_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int reserve_pfn_range(u64 paddr, long unsigned int size, pgprot_t *vma_prot, int strict_prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (0)
Location: arch/x86/mm/pat.c:879
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:track_pfn_copy
```
**Symbols:**

```
ffffffff81086c80-ffffffff81086e22: reserve_pfn_range (STB_LOCAL)
ffffffff81087315-ffffffff81087412: reserve_pfn_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int reserve_pfn_range(u64 paddr, long unsigned int size, pgprot_t *vma_prot, int strict_prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (0)
Location: arch/x86/mm/pat/memtype.c:906
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:track_pfn_copy
```
**Symbols:**

```
ffffffff810903a0-ffffffff8109051a: reserve_pfn_range (STB_LOCAL)
ffffffff81090a06-ffffffff81090afb: reserve_pfn_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int reserve_pfn_range(u64 paddr, long unsigned int size, pgprot_t *vma_prot, int strict_prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (0)
Location: arch/x86/mm/pat/memtype.c:906
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:track_pfn_copy
```
**Symbols:**

```
ffffffff810900a0-ffffffff8109021a: reserve_pfn_range (STB_LOCAL)
ffffffff81bd9b03-ffffffff81bd9bf8: reserve_pfn_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int reserve_pfn_range(u64 paddr, long unsigned int size, pgprot_t *vma_prot, int strict_prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (0)
Location: arch/x86/mm/pat/memtype.c:908
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:track_pfn_copy
```
**Symbols:**

```
ffffffff81090c10-ffffffff81090d8b: reserve_pfn_range (STB_LOCAL)
ffffffff81bcbb67-ffffffff81bcbc5c: reserve_pfn_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int reserve_pfn_range(u64 paddr, long unsigned int size, pgprot_t *vma_prot, int strict_prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (0)
Location: arch/x86/mm/pat/memtype.c:913
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:track_pfn_copy
```
**Symbols:**

```
ffffffff810a0750-ffffffff810a08e2: reserve_pfn_range (STB_LOCAL)
ffffffff81ca1740-ffffffff81ca183f: reserve_pfn_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int reserve_pfn_range(u64 paddr, long unsigned int size, pgprot_t *vma_prot, int strict_prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (0)
Location: arch/x86/mm/pat/memtype.c:921
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:track_pfn_copy
```
**Symbols:**

```
ffffffff810b46e0-ffffffff810b4887: reserve_pfn_range (STB_LOCAL)
ffffffff81e50d67-ffffffff81e50e5f: reserve_pfn_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int reserve_pfn_range(u64 paddr, long unsigned int size, pgprot_t *vma_prot, int strict_prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (0)
Location: arch/x86/mm/pat/memtype.c:874
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:track_pfn_copy
```
**Symbols:**

```
ffffffff810cf3b0-ffffffff810cf629: reserve_pfn_range (STB_LOCAL)
ffffffff82054f45-ffffffff82054f5a: reserve_pfn_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int reserve_pfn_range(u64 paddr, long unsigned int size, pgprot_t *vma_prot, int strict_prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (0)
Location: arch/x86/mm/pat/memtype.c:874
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:track_pfn_copy
```
**Symbols:**

```
ffffffff810d2960-ffffffff810d2be3: reserve_pfn_range (STB_LOCAL)
ffffffff820d3514-ffffffff820d3529: reserve_pfn_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int reserve_pfn_range(u64 paddr, long unsigned int size, pgprot_t *vma_prot, int strict_prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (0)
Location: arch/x86/mm/pat/memtype.c:874
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:track_pfn_copy
```
**Symbols:**

```
ffffffff810db0f0-ffffffff810db373: reserve_pfn_range (STB_LOCAL)
ffffffff821ae382-ffffffff821ae397: reserve_pfn_range.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int reserve_pfn_range(u64 paddr, long unsigned int size, pgprot_t *vma_prot, int strict_prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (0)
Location: arch/x86/mm/pat.c:879
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:track_pfn_copy
```
**Symbols:**

```
ffffffff81085c80-ffffffff81085e22: reserve_pfn_range (STB_LOCAL)
ffffffff81086315-ffffffff81086412: reserve_pfn_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int reserve_pfn_range(u64 paddr, long unsigned int size, pgprot_t *vma_prot, int strict_prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (0)
Location: arch/x86/mm/pat.c:879
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:track_pfn_copy
```
**Symbols:**

```
ffffffff81074a00-ffffffff81074ba2: reserve_pfn_range (STB_LOCAL)
ffffffff81075095-ffffffff81075192: reserve_pfn_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int reserve_pfn_range(u64 paddr, long unsigned int size, pgprot_t *vma_prot, int strict_prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (0)
Location: arch/x86/mm/pat.c:879
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:track_pfn_copy
```
**Symbols:**

```
ffffffff81085c30-ffffffff81085dd2: reserve_pfn_range (STB_LOCAL)
ffffffff810862c5-ffffffff810863c2: reserve_pfn_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int reserve_pfn_range(u64 paddr, long unsigned int size, pgprot_t *vma_prot, int strict_prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (0)
Location: arch/x86/mm/pat.c:879
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:track_pfn_copy
```
**Symbols:**

```
ffffffff81087d80-ffffffff81087f22: reserve_pfn_range (STB_LOCAL)
ffffffff81088412-ffffffff8108850f: reserve_pfn_range.cold (STB_LOCAL)
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
