# Function: <code>fill_pud</code>

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
In arch/x86/mm/init_64.c (ffffffff81f77ade)
Location: arch/x86/mm/init_64.c:233
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:populate_extra_pmd
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
In arch/x86/mm/init_64.c (ffffffff81fa0223)
Location: arch/x86/mm/init_64.c:162
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:populate_extra_pmd
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
In arch/x86/mm/init_64.c (ffffffff81fdb78d)
Location: arch/x86/mm/init_64.c:152
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:populate_extra_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
pud_t *fill_pud(p4d_t *p4d, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8106be60)
Location: arch/x86/mm/init_64.c:213
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:set_pte_vaddr
```
**Symbols:**

```
ffffffff8106be60-ffffffff8106bf97: fill_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
pud_t *fill_pud(p4d_t *p4d, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81070870)
Location: arch/x86/mm/init_64.c:213
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:set_pte_vaddr
```
**Symbols:**

```
ffffffff81070870-ffffffff810709cf: fill_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
pud_t *fill_pud(p4d_t *p4d, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81073680)
Location: arch/x86/mm/init_64.c:224
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:set_pte_vaddr
```
**Symbols:**

```
ffffffff81073680-ffffffff810737a6: fill_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
pud_t *fill_pud(p4d_t *p4d, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810796f0)
Location: arch/x86/mm/init_64.c:223
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:set_pte_vaddr
```
**Symbols:**

```
ffffffff810796f0-ffffffff81079816: fill_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
pud_t *fill_pud(p4d_t *p4d, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107d420)
Location: arch/x86/mm/init_64.c:255
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:set_pte_vaddr
```
**Symbols:**

```
ffffffff8107d420-ffffffff8107d546: fill_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
pud_t *fill_pud(p4d_t *p4d, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107e4b0)
Location: arch/x86/mm/init_64.c:255
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:set_pte_vaddr
```
**Symbols:**

```
ffffffff8107e4b0-ffffffff8107e5d6: fill_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
pud_t *fill_pud(p4d_t *p4d, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81084c40)
Location: arch/x86/mm/init_64.c:260
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
```
**Symbols:**

```
ffffffff81084c40-ffffffff81084d66: fill_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
pud_t *fill_pud(p4d_t *p4d, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81086150)
Location: arch/x86/mm/init_64.c:255
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
```
**Symbols:**

```
ffffffff81086150-ffffffff81086276: fill_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
pud_t *fill_pud(p4d_t *p4d, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81086c60)
Location: arch/x86/mm/init_64.c:255
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
```
**Symbols:**

```
ffffffff81086c60-ffffffff81086d88: fill_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
pud_t *fill_pud(p4d_t *p4d, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81095f70)
Location: arch/x86/mm/init_64.c:256
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
```
**Symbols:**

```
ffffffff81095f70-ffffffff81096098: fill_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
pud_t *fill_pud(p4d_t *p4d, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810a87e0)
Location: arch/x86/mm/init_64.c:255
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
```
**Symbols:**

```
ffffffff810a87e0-ffffffff810a891b: fill_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
pud_t *fill_pud(p4d_t *p4d, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810c1ae0)
Location: arch/x86/mm/init_64.c:261
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
```
**Symbols:**

```
ffffffff810c1ae0-ffffffff810c1c33: fill_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
pud_t *fill_pud(p4d_t *p4d, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810c51c0)
Location: arch/x86/mm/init_64.c:261
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
```
**Symbols:**

```
ffffffff810c51c0-ffffffff810c5313: fill_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
pud_t *fill_pud(p4d_t *p4d, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810cd740)
Location: arch/x86/mm/init_64.c:261
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
```
**Symbols:**

```
ffffffff810cd740-ffffffff810cd893: fill_pud (STB_LOCAL)
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
pud_t *fill_pud(p4d_t *p4d, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107d4b0)
Location: arch/x86/mm/init_64.c:255
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:set_pte_vaddr
```
**Symbols:**

```
ffffffff8107d4b0-ffffffff8107d5d6: fill_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
pud_t *fill_pud(p4d_t *p4d, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/mm/init_64.c:255
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:set_pte_vaddr
```
**Symbols:**

```
ffffffff8106cbb0-ffffffff8106cc68: fill_pud (STB_LOCAL)
ffffffff8106d6fa-ffffffff8106d727: fill_pud.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
pud_t *fill_pud(p4d_t *p4d, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107d460)
Location: arch/x86/mm/init_64.c:255
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:set_pte_vaddr
```
**Symbols:**

```
ffffffff8107d460-ffffffff8107d586: fill_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
pud_t *fill_pud(p4d_t *p4d, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107f550)
Location: arch/x86/mm/init_64.c:255
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:set_pte_vaddr
```
**Symbols:**

```
ffffffff8107f550-ffffffff8107f676: fill_pud (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
