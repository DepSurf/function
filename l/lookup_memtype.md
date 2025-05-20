# Function: <code>lookup_memtype</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
enum page_cache_mode lookup_memtype(u64 paddr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff8106fad0)
Location: arch/x86/mm/pat.c:612
Inline: True
Direct callers:
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:track_pfn_insert
```
**Symbols:**

```
ffffffff8106fad0-ffffffff8106fb85: lookup_memtype (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
enum page_cache_mode lookup_memtype(u64 paddr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff8106f8d0)
Location: arch/x86/mm/pat.c:656
Inline: True
Direct callers:
  - arch/x86/mm/pat.c:track_pfn_insert
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:reserve_pfn_range
```
**Symbols:**

```
ffffffff8106f8d0-ffffffff8106f988: lookup_memtype (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
enum page_cache_mode lookup_memtype(u64 paddr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81073500)
Location: arch/x86/mm/pat.c:656
Inline: True
Direct callers:
  - arch/x86/mm/pat.c:track_pfn_insert
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:reserve_pfn_range
```
**Symbols:**

```
ffffffff81073500-ffffffff810735b4: lookup_memtype (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
enum page_cache_mode lookup_memtype(u64 paddr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81072aa0)
Location: arch/x86/mm/pat.c:653
Inline: True
Direct callers:
  - arch/x86/mm/pat.c:track_pfn_insert
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:reserve_pfn_range
```
**Symbols:**

```
ffffffff81072aa0-ffffffff81072b48: lookup_memtype (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
enum page_cache_mode lookup_memtype(u64 paddr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81078400)
Location: arch/x86/mm/pat.c:653
Inline: True
Direct callers:
  - arch/x86/mm/pat.c:track_pfn_insert
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:pat_pfn_immune_to_uc_mtrr
```
**Symbols:**

```
ffffffff81078400-ffffffff810784ae: lookup_memtype (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
enum page_cache_mode lookup_memtype(u64 paddr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff8107b140)
Location: arch/x86/mm/pat.c:669
Inline: True
Direct callers:
  - arch/x86/mm/pat.c:track_pfn_insert
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:pat_pfn_immune_to_uc_mtrr
```
**Symbols:**

```
ffffffff8107b140-ffffffff8107b1f3: lookup_memtype (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
enum page_cache_mode lookup_memtype(u64 paddr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81081a80)
Location: arch/x86/mm/pat.c:678
Inline: True
Direct callers:
  - arch/x86/mm/pat.c:track_pfn_insert
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:pat_pfn_immune_to_uc_mtrr
```
**Symbols:**

```
ffffffff81081a80-ffffffff81081b33: lookup_memtype (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
enum page_cache_mode lookup_memtype(u64 paddr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81085710)
Location: arch/x86/mm/pat.c:679
Inline: True
Direct callers:
  - arch/x86/mm/pat.c:track_pfn_insert
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:pat_pfn_immune_to_uc_mtrr
```
**Symbols:**

```
ffffffff81085710-ffffffff810857d2: lookup_memtype (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
enum page_cache_mode lookup_memtype(u64 paddr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81086400)
Location: arch/x86/mm/pat.c:679
Inline: True
Direct callers:
  - arch/x86/mm/pat.c:track_pfn_insert
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:pat_pfn_immune_to_uc_mtrr
```
**Symbols:**

```
ffffffff81086400-ffffffff810864c2: lookup_memtype (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
enum page_cache_mode lookup_memtype(u64 paddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff8108fb80)
Location: arch/x86/mm/pat/memtype.c:706
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:track_pfn_insert
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:pat_pfn_immune_to_uc_mtrr
```
**Symbols:**

```
ffffffff8108fb80-ffffffff8108fc42: lookup_memtype (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
enum page_cache_mode lookup_memtype(u64 paddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff8108f880)
Location: arch/x86/mm/pat/memtype.c:706
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:track_pfn_insert
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:pat_pfn_immune_to_uc_mtrr
```
**Symbols:**

```
ffffffff8108f880-ffffffff8108f942: lookup_memtype (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum page_cache_mode lookup_memtype(u64 paddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff81090380)
Location: arch/x86/mm/pat/memtype.c:706
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:track_pfn_insert
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:pat_pfn_immune_to_uc_mtrr
```
**Symbols:**

```
ffffffff81090380-ffffffff81090442: lookup_memtype (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
enum page_cache_mode lookup_memtype(u64 paddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff8109fd70)
Location: arch/x86/mm/pat/memtype.c:711
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:track_pfn_insert
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:pat_pfn_immune_to_uc_mtrr
```
**Symbols:**

```
ffffffff8109fd70-ffffffff8109fe32: lookup_memtype (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
enum page_cache_mode lookup_memtype(u64 paddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff810b3980)
Location: arch/x86/mm/pat/memtype.c:719
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:track_pfn_insert
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:pat_pfn_immune_to_uc_mtrr
```
**Symbols:**

```
ffffffff810b3980-ffffffff810b3a67: lookup_memtype (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum page_cache_mode lookup_memtype(u64 paddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff810ce5c0)
Location: arch/x86/mm/pat/memtype.c:672
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:track_pfn_insert
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:pat_pfn_immune_to_uc_mtrr
```
**Symbols:**

```
ffffffff810ce5c0-ffffffff810ce6a7: lookup_memtype (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum page_cache_mode lookup_memtype(u64 paddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff810d1b80)
Location: arch/x86/mm/pat/memtype.c:672
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:track_pfn_insert
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:pat_pfn_immune_to_uc_mtrr
```
**Symbols:**

```
ffffffff810d1b80-ffffffff810d1c67: lookup_memtype (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum page_cache_mode lookup_memtype(u64 paddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff810da2b0)
Location: arch/x86/mm/pat/memtype.c:672
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:track_pfn_insert
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:pat_pfn_immune_to_uc_mtrr
```
**Symbols:**

```
ffffffff810da2b0-ffffffff810da397: lookup_memtype (STB_LOCAL)
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
enum page_cache_mode lookup_memtype(u64 paddr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81085400)
Location: arch/x86/mm/pat.c:679
Inline: True
Direct callers:
  - arch/x86/mm/pat.c:track_pfn_insert
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:pat_pfn_immune_to_uc_mtrr
```
**Symbols:**

```
ffffffff81085400-ffffffff810854c2: lookup_memtype (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
enum page_cache_mode lookup_memtype(u64 paddr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff810740d0)
Location: arch/x86/mm/pat.c:679
Inline: True
Direct callers:
  - arch/x86/mm/pat.c:track_pfn_insert
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:pat_pfn_immune_to_uc_mtrr
```
**Symbols:**

```
ffffffff810740d0-ffffffff81074192: lookup_memtype (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
enum page_cache_mode lookup_memtype(u64 paddr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff810853b0)
Location: arch/x86/mm/pat.c:679
Inline: True
Direct callers:
  - arch/x86/mm/pat.c:track_pfn_insert
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:pat_pfn_immune_to_uc_mtrr
```
**Symbols:**

```
ffffffff810853b0-ffffffff81085472: lookup_memtype (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
enum page_cache_mode lookup_memtype(u64 paddr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff810873e0)
Location: arch/x86/mm/pat.c:679
Inline: True
Direct callers:
  - arch/x86/mm/pat.c:track_pfn_insert
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:pat_pfn_immune_to_uc_mtrr
```
**Symbols:**

```
ffffffff810873e0-ffffffff810874ae: lookup_memtype (STB_LOCAL)
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
