# Function: <code>alloc_pmd_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int alloc_pmd_page(pud_t *pud);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106c1f0)
Location: arch/x86/mm/pageattr.c:895
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:populate_pmd
```
**Symbols:**

```
ffffffff8106c1f0-ffffffff8106c24d: alloc_pmd_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int alloc_pmd_page(pud_t *pud);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106c060)
Location: arch/x86/mm/pageattr.c:879
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:populate_pmd
```
**Symbols:**

```
ffffffff8106c060-ffffffff8106c0c4: alloc_pmd_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int alloc_pmd_page(pud_t *pud);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106fc80)
Location: arch/x86/mm/pageattr.c:879
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:populate_pmd
```
**Symbols:**

```
ffffffff8106fc80-ffffffff8106fce4: alloc_pmd_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int alloc_pmd_page(pud_t *pud);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106f3b0)
Location: arch/x86/mm/pageattr.c:915
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:populate_pmd
```
**Symbols:**

```
ffffffff8106f3b0-ffffffff8106f414: alloc_pmd_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int alloc_pmd_page(pud_t *pud);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81074750)
Location: arch/x86/mm/pageattr.c:915
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:populate_pmd
```
**Symbols:**

```
ffffffff81074750-ffffffff810747be: alloc_pmd_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int alloc_pmd_page(pud_t *pud);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810771c0)
Location: arch/x86/mm/pageattr.c:938
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:populate_pmd
```
**Symbols:**

```
ffffffff810771c0-ffffffff8107722b: alloc_pmd_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int alloc_pmd_page(pud_t *pud);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8107d8f0)
Location: arch/x86/mm/pageattr.c:1200
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:populate_pmd
```
**Symbols:**

```
ffffffff8107d8f0-ffffffff8107d95b: alloc_pmd_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int alloc_pmd_page(pud_t *pud);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810811f0)
Location: arch/x86/mm/pageattr.c:1210
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:populate_pmd
```
**Symbols:**

```
ffffffff810811f0-ffffffff8108125b: alloc_pmd_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int alloc_pmd_page(pud_t *pud);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810822b0)
Location: arch/x86/mm/pageattr.c:1210
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:populate_pmd
```
**Symbols:**

```
ffffffff810822b0-ffffffff8108231b: alloc_pmd_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int alloc_pmd_page(pud_t *pud);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108bde0)
Location: arch/x86/mm/pat/set_memory.c:1230
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pmd
```
**Symbols:**

```
ffffffff8108bde0-ffffffff8108be4e: alloc_pmd_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int alloc_pmd_page(pud_t *pud);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108bfc0)
Location: arch/x86/mm/pat/set_memory.c:1230
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pmd
```
**Symbols:**

```
ffffffff8108bfc0-ffffffff8108c02e: alloc_pmd_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int alloc_pmd_page(pud_t *pud);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108ca90)
Location: arch/x86/mm/pat/set_memory.c:1238
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pmd
```
**Symbols:**

```
ffffffff8108ca90-ffffffff8108caff: alloc_pmd_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int alloc_pmd_page(pud_t *pud);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8109c2f0)
Location: arch/x86/mm/pat/set_memory.c:1238
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pmd
```
**Symbols:**

```
ffffffff8109c2f0-ffffffff8109c35f: alloc_pmd_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int alloc_pmd_page(pud_t *pud);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810afa70)
Location: arch/x86/mm/pat/set_memory.c:1230
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pmd
```
**Symbols:**

```
ffffffff810afa70-ffffffff810afaf5: alloc_pmd_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int alloc_pmd_page(pud_t *pud);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810ca0a0)
Location: arch/x86/mm/pat/set_memory.c:1307
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pmd
```
**Symbols:**

```
ffffffff810ca0a0-ffffffff810ca126: alloc_pmd_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int alloc_pmd_page(pud_t *pud);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810cd6f0)
Location: arch/x86/mm/pat/set_memory.c:1308
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pmd
```
**Symbols:**

```
ffffffff810cd6f0-ffffffff810cd776: alloc_pmd_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int alloc_pmd_page(pud_t *pud);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d5f40)
Location: arch/x86/mm/pat/set_memory.c:1312
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pmd
```
**Symbols:**

```
ffffffff810d5f40-ffffffff810d5fc6: alloc_pmd_page (STB_LOCAL)
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
int alloc_pmd_page(pud_t *pud);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810812b0)
Location: arch/x86/mm/pageattr.c:1210
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:populate_pmd
```
**Symbols:**

```
ffffffff810812b0-ffffffff8108131b: alloc_pmd_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int alloc_pmd_page(pud_t *pud);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81070200)
Location: arch/x86/mm/pageattr.c:1210
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:populate_pgd
  - arch/x86/mm/pageattr.c:populate_pgd
  - arch/x86/mm/pageattr.c:populate_pmd
```
**Symbols:**

```
ffffffff81070200-ffffffff8107025a: alloc_pmd_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int alloc_pmd_page(pud_t *pud);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81081260)
Location: arch/x86/mm/pageattr.c:1210
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:populate_pmd
```
**Symbols:**

```
ffffffff81081260-ffffffff810812cb: alloc_pmd_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int alloc_pmd_page(pud_t *pud);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81083380)
Location: arch/x86/mm/pageattr.c:1210
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:populate_pmd
```
**Symbols:**

```
ffffffff81083380-ffffffff810833eb: alloc_pmd_page (STB_LOCAL)
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
