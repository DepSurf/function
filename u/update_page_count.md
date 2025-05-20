# Function: <code>update_page_count</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void update_page_count(int level, long unsigned int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106d0e0)
Location: arch/x86/mm/pageattr.c:59
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
```
**Symbols:**

```
ffffffff8106d0e0-ffffffff8106d11b: update_page_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void update_page_count(int level, long unsigned int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106cf10)
Location: arch/x86/mm/pageattr.c:59
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
**Symbols:**

```
ffffffff8106cf10-ffffffff8106cf4b: update_page_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void update_page_count(int level, long unsigned int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81070b50)
Location: arch/x86/mm/pageattr.c:59
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
**Symbols:**

```
ffffffff81070b50-ffffffff81070b8b: update_page_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void update_page_count(int level, long unsigned int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81070290)
Location: arch/x86/mm/pageattr.c:60
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
**Symbols:**

```
ffffffff81070290-ffffffff810702cb: update_page_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void update_page_count(int level, long unsigned int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81075780)
Location: arch/x86/mm/pageattr.c:60
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
**Symbols:**

```
ffffffff81075780-ffffffff810757bb: update_page_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void update_page_count(int level, long unsigned int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81078260)
Location: arch/x86/mm/pageattr.c:61
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
**Symbols:**

```
ffffffff81078260-ffffffff8107829b: update_page_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void update_page_count(int level, long unsigned int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8107ea10)
Location: arch/x86/mm/pageattr.c:72
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
**Symbols:**

```
ffffffff8107ea10-ffffffff8107ea4b: update_page_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void update_page_count(int level, long unsigned int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810822f0)
Location: arch/x86/mm/pageattr.c:73
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
**Symbols:**

```
ffffffff810822f0-ffffffff8108232b: update_page_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void update_page_count(int level, long unsigned int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810833b0)
Location: arch/x86/mm/pageattr.c:73
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
**Symbols:**

```
ffffffff810833b0-ffffffff810833eb: update_page_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void update_page_count(int level, long unsigned int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108cfb0)
Location: arch/x86/mm/pat/set_memory.c:80
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pte_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
**Symbols:**

```
ffffffff8108cfb0-ffffffff8108cfeb: update_page_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void update_page_count(int level, long unsigned int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108ce80)
Location: arch/x86/mm/pat/set_memory.c:80
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pte_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
**Symbols:**

```
ffffffff8108ce80-ffffffff8108cebb: update_page_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void update_page_count(int level, long unsigned int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108da70)
Location: arch/x86/mm/pat/set_memory.c:82
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
**Symbols:**

```
ffffffff8108da70-ffffffff8108daab: update_page_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void update_page_count(int level, long unsigned int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8109d300)
Location: arch/x86/mm/pat/set_memory.c:82
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
**Symbols:**

```
ffffffff8109d300-ffffffff8109d35f: update_page_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void update_page_count(int level, long unsigned int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810b0bb0)
Location: arch/x86/mm/pat/set_memory.c:85
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
**Symbols:**

```
ffffffff810b0bb0-ffffffff810b0c15: update_page_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void update_page_count(int level, long unsigned int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810cb2a0)
Location: arch/x86/mm/pat/set_memory.c:86
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
**Symbols:**

```
ffffffff810cb2a0-ffffffff810cb305: update_page_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void update_page_count(int level, long unsigned int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810ce8c0)
Location: arch/x86/mm/pat/set_memory.c:87
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
**Symbols:**

```
ffffffff810ce8c0-ffffffff810ce916: update_page_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void update_page_count(int level, long unsigned int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d6fa0)
Location: arch/x86/mm/pat/set_memory.c:87
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
**Symbols:**

```
ffffffff810d6fa0-ffffffff810d6ff6: update_page_count (STB_GLOBAL)
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
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/book3s64/radix_pgtable.c (c000000000eeb8cc)
Location: arch/powerpc/include/asm/book3s/64/pgalloc.h:176
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_pgtable.c:create_physical_mapping
```
</details>
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
void update_page_count(int level, long unsigned int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810823b0)
Location: arch/x86/mm/pageattr.c:73
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
**Symbols:**

```
ffffffff810823b0-ffffffff810823eb: update_page_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void update_page_count(int level, long unsigned int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810711a0)
Location: arch/x86/mm/pageattr.c:73
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
**Symbols:**

```
ffffffff810711a0-ffffffff810711db: update_page_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void update_page_count(int level, long unsigned int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81082360)
Location: arch/x86/mm/pageattr.c:73
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
**Symbols:**

```
ffffffff81082360-ffffffff8108239b: update_page_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void update_page_count(int level, long unsigned int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81084480)
Location: arch/x86/mm/pageattr.c:73
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
**Symbols:**

```
ffffffff81084480-ffffffff810844b9: update_page_count (STB_GLOBAL)
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
