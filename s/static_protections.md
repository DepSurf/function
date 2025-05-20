# Function: <code>static_protections</code>

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
In arch/x86/mm/pageattr.c (ffffffff8106d4d9)
Location: arch/x86/mm/pageattr.c:251
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
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
In arch/x86/mm/pageattr.c (ffffffff8106da31)
Location: arch/x86/mm/pageattr.c:257
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
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
In arch/x86/mm/pageattr.c (ffffffff810716bd)
Location: arch/x86/mm/pageattr.c:257
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
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
In arch/x86/mm/pageattr.c (ffffffff81070eb9)
Location: arch/x86/mm/pageattr.c:277
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
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
In arch/x86/mm/pageattr.c (ffffffff81076608)
Location: arch/x86/mm/pageattr.c:277
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
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
In arch/x86/mm/pageattr.c (ffffffff81078fb4)
Location: arch/x86/mm/pageattr.c:295
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
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
In arch/x86/mm/pageattr.c (ffffffff8107f8b6)
Location: arch/x86/mm/pageattr.c:516
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810832ae)
Location: arch/x86/mm/pageattr.c:517
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__split_large_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8108437e)
Location: arch/x86/mm/pageattr.c:517
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__split_large_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
pgprot_t static_protections(pgprot_t prot, long unsigned int start, long unsigned int pfn, long unsigned int npg, long unsigned int lpsize, int warnlvl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108ddce)
Location: arch/x86/mm/pat/set_memory.c:526
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
**Symbols:**

```
ffffffff8108d5a0-ffffffff8108d751: static_protections (STB_LOCAL)
ffffffff8108f5ed-ffffffff8108f6a5: static_protections.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
pgprot_t static_protections(pgprot_t prot, long unsigned int start, long unsigned int pfn, long unsigned int npg, long unsigned int lpsize, int warnlvl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108dc9e)
Location: arch/x86/mm/pat/set_memory.c:526
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
**Symbols:**

```
ffffffff8108d470-ffffffff8108d621: static_protections (STB_LOCAL)
ffffffff81bd97dd-ffffffff81bd9895: static_protections.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
pgprot_t static_protections(pgprot_t prot, long unsigned int start, long unsigned int pfn, long unsigned int npg, long unsigned int lpsize, int warnlvl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108e885)
Location: arch/x86/mm/pat/set_memory.c:534
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
**Symbols:**

```
ffffffff8108e030-ffffffff8108e1e2: static_protections (STB_LOCAL)
ffffffff81bcb845-ffffffff81bcb8fd: static_protections.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
pgprot_t static_protections(pgprot_t prot, long unsigned int start, long unsigned int pfn, long unsigned int npg, long unsigned int lpsize, int warnlvl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8109e369)
Location: arch/x86/mm/pat/set_memory.c:534
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
**Symbols:**

```
ffffffff8109d9d0-ffffffff8109dcdb: static_protections (STB_LOCAL)
ffffffff81ca1353-ffffffff81ca1377: static_protections.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
pgprot_t static_protections(pgprot_t prot, long unsigned int start, long unsigned int pfn, long unsigned int npg, long unsigned int lpsize, int warnlvl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810b1cca)
Location: arch/x86/mm/pat/set_memory.c:537
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
**Symbols:**

```
ffffffff810b12d0-ffffffff810b1602: static_protections (STB_LOCAL)
ffffffff81e5093e-ffffffff81e5096a: static_protections.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
pgprot_t static_protections(pgprot_t prot, long unsigned int start, long unsigned int pfn, long unsigned int npg, long unsigned int lpsize, int warnlvl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810cc447)
Location: arch/x86/mm/pat/set_memory.c:572
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
**Symbols:**

```
ffffffff810cba20-ffffffff810cbd3f: static_protections (STB_LOCAL)
ffffffff82054dbc-ffffffff82054de8: static_protections.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
pgprot_t static_protections(pgprot_t prot, long unsigned int start, long unsigned int pfn, long unsigned int npg, long unsigned int lpsize, int warnlvl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810cfa6a)
Location: arch/x86/mm/pat/set_memory.c:573
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
**Symbols:**

```
ffffffff810cf040-ffffffff810cf371: static_protections (STB_LOCAL)
ffffffff820d3392-ffffffff820d33be: static_protections.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
pgprot_t static_protections(pgprot_t prot, long unsigned int start, long unsigned int pfn, long unsigned int npg, long unsigned int lpsize, int warnlvl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d814a)
Location: arch/x86/mm/pat/set_memory.c:573
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
**Symbols:**

```
ffffffff810d7720-ffffffff810d7a51: static_protections (STB_LOCAL)
ffffffff821ae200-ffffffff821ae22c: static_protections.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8108337e)
Location: arch/x86/mm/pageattr.c:517
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__split_large_page
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81071df7)
Location: arch/x86/mm/pageattr.c:517
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8108332e)
Location: arch/x86/mm/pageattr.c:517
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__split_large_page
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81085584)
Location: arch/x86/mm/pageattr.c:517
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__split_large_page
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
