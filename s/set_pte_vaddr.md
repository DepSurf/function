# Function: <code>set_pte_vaddr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void set_pte_vaddr(long unsigned int vaddr, pte_t pteval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81069690)
Location: arch/x86/mm/init_64.c:287
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:set_pte_mfn
```
**Symbols:**

```
ffffffff81069690-ffffffff81069721: set_pte_vaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void set_pte_vaddr(long unsigned int vaddr, pte_t pteval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81069420)
Location: arch/x86/mm/init_64.c:216
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:set_pte_mfn
```
**Symbols:**

```
ffffffff81069420-ffffffff810694aa: set_pte_vaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void set_pte_vaddr(long unsigned int vaddr, pte_t pteval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8106d000)
Location: arch/x86/mm/init_64.c:206
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:set_pte_mfn
```
**Symbols:**

```
ffffffff8106d000-ffffffff8106d08a: set_pte_vaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void set_pte_vaddr(long unsigned int vaddr, pte_t pteval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8106c660)
Location: arch/x86/mm/init_64.c:277
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
```
**Symbols:**

```
ffffffff8106c660-ffffffff8106c6c1: set_pte_vaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void set_pte_vaddr(long unsigned int vaddr, pte_t pteval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81071130)
Location: arch/x86/mm/init_64.c:277
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:cea_map_percpu_pages
```
**Symbols:**

```
ffffffff81071130-ffffffff81071191: set_pte_vaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void set_pte_vaddr(long unsigned int vaddr, pte_t pteval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81073eb0)
Location: arch/x86/mm/init_64.c:288
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
**Symbols:**

```
ffffffff81073eb0-ffffffff81073f11: set_pte_vaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void set_pte_vaddr(long unsigned int vaddr, pte_t pteval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81079da0)
Location: arch/x86/mm/init_64.c:287
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
**Symbols:**

```
ffffffff81079da0-ffffffff81079e01: set_pte_vaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void set_pte_vaddr(long unsigned int vaddr, pte_t pteval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107dad0)
Location: arch/x86/mm/init_64.c:319
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
**Symbols:**

```
ffffffff8107dad0-ffffffff8107db33: set_pte_vaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void set_pte_vaddr(long unsigned int vaddr, pte_t pteval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107eb60)
Location: arch/x86/mm/init_64.c:319
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
**Symbols:**

```
ffffffff8107eb60-ffffffff8107ebc3: set_pte_vaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void set_pte_vaddr(long unsigned int vaddr, pte_t pteval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/mm/init_64.c:324
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
  - arch/x86/mm/pgtable.c:native_set_fixmap
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
**Symbols:**

```
ffffffff81086555-ffffffff81086566: set_pte_vaddr.cold (STB_LOCAL)
ffffffff810854d0-ffffffff81085568: set_pte_vaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void set_pte_vaddr(long unsigned int vaddr, pte_t pteval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/mm/init_64.c:319
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
  - arch/x86/mm/pgtable.c:native_set_fixmap
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
**Symbols:**

```
ffffffff81bd91cf-ffffffff81bd91e0: set_pte_vaddr.cold (STB_LOCAL)
ffffffff81086580-ffffffff81086618: set_pte_vaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void set_pte_vaddr(long unsigned int vaddr, pte_t pteval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/mm/init_64.c:319
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
  - arch/x86/mm/pgtable.c:native_set_fixmap
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
**Symbols:**

```
ffffffff81bcb154-ffffffff81bcb165: set_pte_vaddr.cold (STB_LOCAL)
ffffffff81087320-ffffffff8108739b: set_pte_vaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void set_pte_vaddr(long unsigned int vaddr, pte_t pteval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/mm/init_64.c:320
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
  - arch/x86/mm/pgtable.c:native_set_fixmap
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
**Symbols:**

```
ffffffff81ca0795-ffffffff81ca07c2: set_pte_vaddr.cold (STB_LOCAL)
ffffffff81096640-ffffffff810966cb: set_pte_vaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void set_pte_vaddr(long unsigned int vaddr, pte_t pteval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/mm/init_64.c:319
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:native_set_fixmap
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
**Symbols:**

```
ffffffff81e4fcb2-ffffffff81e4fcdf: set_pte_vaddr.cold (STB_LOCAL)
ffffffff810a8f40-ffffffff810a8fda: set_pte_vaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void set_pte_vaddr(long unsigned int vaddr, pte_t pteval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/mm/init_64.c:325
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:native_set_fixmap
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
**Symbols:**

```
ffffffff82054961-ffffffff8205497d: set_pte_vaddr.cold (STB_LOCAL)
ffffffff810c25f0-ffffffff810c26b1: set_pte_vaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void set_pte_vaddr(long unsigned int vaddr, pte_t pteval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/mm/init_64.c:325
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:native_set_fixmap
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
**Symbols:**

```
ffffffff820d2f6f-ffffffff820d2f8b: set_pte_vaddr.cold (STB_LOCAL)
ffffffff810c5cd0-ffffffff810c5d91: set_pte_vaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void set_pte_vaddr(long unsigned int vaddr, pte_t pteval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/mm/init_64.c:325
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:native_set_fixmap
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
**Symbols:**

```
ffffffff821adddd-ffffffff821addf9: set_pte_vaddr.cold (STB_LOCAL)
ffffffff810ce120-ffffffff810ce1e1: set_pte_vaddr (STB_GLOBAL)
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
void set_pte_vaddr(long unsigned int vaddr, pte_t pteval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107db60)
Location: arch/x86/mm/init_64.c:319
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
**Symbols:**

```
ffffffff8107db60-ffffffff8107dbc3: set_pte_vaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void set_pte_vaddr(long unsigned int vaddr, pte_t pteval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8106ce60)
Location: arch/x86/mm/init_64.c:319
Inline: False
Direct callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
**Symbols:**

```
ffffffff8106ce60-ffffffff8106cec3: set_pte_vaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void set_pte_vaddr(long unsigned int vaddr, pte_t pteval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107db10)
Location: arch/x86/mm/init_64.c:319
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
**Symbols:**

```
ffffffff8107db10-ffffffff8107db73: set_pte_vaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void set_pte_vaddr(long unsigned int vaddr, pte_t pteval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107fc00)
Location: arch/x86/mm/init_64.c:319
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
**Symbols:**

```
ffffffff8107fc00-ffffffff8107fc63: set_pte_vaddr (STB_GLOBAL)
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
