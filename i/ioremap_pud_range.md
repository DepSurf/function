# Function: <code>ioremap_pud_range</code>

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
In lib/ioremap.c (ffffffff813eb0b1)
Location: lib/ioremap.c:97
Inline: True
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
In lib/ioremap.c (ffffffff81431404)
Location: lib/ioremap.c:97
Inline: True
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
In lib/ioremap.c (ffffffff8144d674)
Location: lib/ioremap.c:97
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
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
In lib/ioremap.c (ffffffff818ed38c)
Location: lib/ioremap.c:104
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
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
In lib/ioremap.c (ffffffff81973445)
Location: lib/ioremap.c:106
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
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
In lib/ioremap.c (ffffffff819cf953)
Location: lib/ioremap.c:106
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
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
In lib/ioremap.c (ffffffff81a08dc2)
Location: lib/ioremap.c:138
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ioremap_pud_range(p4d_t *p4d, long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ioremap.c (ffffffff81a78670)
Location: lib/ioremap.c:146
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff81a78670-ffffffff81a78a9b: ioremap_pud_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ioremap_pud_range(p4d_t *p4d, long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ioremap.c (ffffffff81aafa20)
Location: lib/ioremap.c:146
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff81aafa20-ffffffff81aafe4b: ioremap_pud_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ioremap_pud_range(p4d_t *p4d, long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot, pgtbl_mod_mask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ioremap.c (ffffffff815e9920)
Location: lib/ioremap.c:150
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff815e9920-ffffffff815e9c80: ioremap_pud_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/ioremap.c (ffffffff812b8411)
Location: mm/ioremap.c:152
Inline: True
Inline callers:
  - mm/ioremap.c:ioremap_page_range
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/ioremap.c (ffff800010d89544)
Location: lib/ioremap.c:146
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/ioremap.c (c0e8430c)
Location: lib/ioremap.c:146
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ioremap_pud_range(pgd_t *p4d, long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ioremap.c (c000000000ec9ef0)
Location: lib/ioremap.c:146
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
c000000000ec9ef0-c000000000eca4f4: ioremap_pud_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/ioremap.c (ffffffe0008b30f8)
Location: lib/ioremap.c:146
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int ioremap_pud_range(p4d_t *p4d, long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ioremap.c (ffffffff81a4e870)
Location: lib/ioremap.c:146
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff81a4e870-ffffffff81a4ec9b: ioremap_pud_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ioremap_pud_range(p4d_t *p4d, long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ioremap.c (ffffffff81a0b960)
Location: lib/ioremap.c:146
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff81a0b960-ffffffff81a0bd98: ioremap_pud_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ioremap_pud_range(p4d_t *p4d, long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ioremap.c (ffffffff81abac60)
Location: lib/ioremap.c:146
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff81abac60-ffffffff81abb08b: ioremap_pud_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ioremap_pud_range(p4d_t *p4d, long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ioremap.c (ffffffff81ac70b0)
Location: lib/ioremap.c:146
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff81ac70b0-ffffffff81ac74db: ioremap_pud_range (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>pgtbl_mod_mask *mask</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>p4d_t *p4d</code> ➡️ <code>pgd_t *p4d</code>
</li>
</ul>
</details>
</li>
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
