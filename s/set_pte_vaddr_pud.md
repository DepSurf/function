# Function: <code>set_pte_vaddr_pud</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void set_pte_vaddr_pud(pud_t *pud_page, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81069640)
Location: arch/x86/mm/init_64.c:268
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:xen_set_fixmap
  - arch/x86/mm/init_64.c:set_pte_vaddr
```
**Symbols:**

```
ffffffff81069640-ffffffff8106968d: set_pte_vaddr_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void set_pte_vaddr_pud(pud_t *pud_page, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810693d0)
Location: arch/x86/mm/init_64.c:197
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:xen_set_fixmap
  - arch/x86/mm/init_64.c:set_pte_vaddr
```
**Symbols:**

```
ffffffff810693d0-ffffffff8106941d: set_pte_vaddr_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void set_pte_vaddr_pud(pud_t *pud_page, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8106cfb0)
Location: arch/x86/mm/init_64.c:187
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:xen_set_fixmap
  - arch/x86/mm/init_64.c:set_pte_vaddr
```
**Symbols:**

```
ffffffff8106cfb0-ffffffff8106cffd: set_pte_vaddr_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void set_pte_vaddr_pud(pud_t *pud_page, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8106c640)
Location: arch/x86/mm/init_64.c:270
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
```
**Symbols:**

```
ffffffff8106c640-ffffffff8106c65f: set_pte_vaddr_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void set_pte_vaddr_pud(pud_t *pud_page, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81071110)
Location: arch/x86/mm/init_64.c:270
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
```
**Symbols:**

```
ffffffff81071110-ffffffff8107112f: set_pte_vaddr_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void set_pte_vaddr_pud(pud_t *pud_page, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81073e90)
Location: arch/x86/mm/init_64.c:281
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
```
**Symbols:**

```
ffffffff81073e90-ffffffff81073eaf: set_pte_vaddr_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void set_pte_vaddr_pud(pud_t *pud_page, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81079d80)
Location: arch/x86/mm/init_64.c:280
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
```
**Symbols:**

```
ffffffff81079d80-ffffffff81079d9f: set_pte_vaddr_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void set_pte_vaddr_pud(pud_t *pud_page, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107dab0)
Location: arch/x86/mm/init_64.c:312
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
```
**Symbols:**

```
ffffffff8107dab0-ffffffff8107dacf: set_pte_vaddr_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void set_pte_vaddr_pud(pud_t *pud_page, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107eb40)
Location: arch/x86/mm/init_64.c:312
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
```
**Symbols:**

```
ffffffff8107eb40-ffffffff8107eb5f: set_pte_vaddr_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void set_pte_vaddr_pud(pud_t *pud_page, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81085480)
Location: arch/x86/mm/init_64.c:317
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
```
**Symbols:**

```
ffffffff81085480-ffffffff810854cb: set_pte_vaddr_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void set_pte_vaddr_pud(pud_t *pud_page, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81086530)
Location: arch/x86/mm/init_64.c:312
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
```
**Symbols:**

```
ffffffff81086530-ffffffff8108657b: set_pte_vaddr_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void set_pte_vaddr_pud(pud_t *pud_page, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810872d0)
Location: arch/x86/mm/init_64.c:312
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
```
**Symbols:**

```
ffffffff810872d0-ffffffff8108731b: set_pte_vaddr_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void set_pte_vaddr_pud(pud_t *pud_page, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810965f0)
Location: arch/x86/mm/init_64.c:313
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
```
**Symbols:**

```
ffffffff810965f0-ffffffff8109663b: set_pte_vaddr_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void set_pte_vaddr_pud(pud_t *pud_page, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810a8ed0)
Location: arch/x86/mm/init_64.c:312
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
```
**Symbols:**

```
ffffffff810a8ed0-ffffffff810a8f34: set_pte_vaddr_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void set_pte_vaddr_pud(pud_t *pud_page, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810c2570)
Location: arch/x86/mm/init_64.c:318
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
```
**Symbols:**

```
ffffffff810c2570-ffffffff810c25d4: set_pte_vaddr_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void set_pte_vaddr_pud(pud_t *pud_page, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810c5c50)
Location: arch/x86/mm/init_64.c:318
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
```
**Symbols:**

```
ffffffff810c5c50-ffffffff810c5cb4: set_pte_vaddr_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void set_pte_vaddr_pud(pud_t *pud_page, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810ce0a0)
Location: arch/x86/mm/init_64.c:318
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
```
**Symbols:**

```
ffffffff810ce0a0-ffffffff810ce104: set_pte_vaddr_pud (STB_GLOBAL)
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
void set_pte_vaddr_pud(pud_t *pud_page, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107db40)
Location: arch/x86/mm/init_64.c:312
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
```
**Symbols:**

```
ffffffff8107db40-ffffffff8107db5f: set_pte_vaddr_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void set_pte_vaddr_pud(pud_t *pud_page, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8106ce40)
Location: arch/x86/mm/init_64.c:312
Inline: False
```
**Symbols:**

```
ffffffff8106ce40-ffffffff8106ce5f: set_pte_vaddr_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void set_pte_vaddr_pud(pud_t *pud_page, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107daf0)
Location: arch/x86/mm/init_64.c:312
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
```
**Symbols:**

```
ffffffff8107daf0-ffffffff8107db0f: set_pte_vaddr_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void set_pte_vaddr_pud(pud_t *pud_page, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107fbe0)
Location: arch/x86/mm/init_64.c:312
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
```
**Symbols:**

```
ffffffff8107fbe0-ffffffff8107fbff: set_pte_vaddr_pud (STB_GLOBAL)
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
