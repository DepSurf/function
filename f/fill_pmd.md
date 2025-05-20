# Function: <code>fill_pmd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
pmd_t *fill_pmd(pud_t *pud, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81069200)
Location: arch/x86/mm/init_64.c:245
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:populate_extra_pmd
```
**Symbols:**

```
ffffffff81069200-ffffffff81069337: fill_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
pmd_t *fill_pmd(pud_t *pud, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81068f80)
Location: arch/x86/mm/init_64.c:174
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
```
**Symbols:**

```
ffffffff81068f80-ffffffff810690de: fill_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
pmd_t *fill_pmd(pud_t *pud, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8106cbd0)
Location: arch/x86/mm/init_64.c:164
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
```
**Symbols:**

```
ffffffff8106cbd0-ffffffff8106cd2e: fill_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
pmd_t *fill_pmd(pud_t *pud, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8106bfa0)
Location: arch/x86/mm/init_64.c:225
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
**Symbols:**

```
ffffffff8106bfa0-ffffffff8106c0f9: fill_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
pmd_t *fill_pmd(pud_t *pud, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810709d0)
Location: arch/x86/mm/init_64.c:225
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
**Symbols:**

```
ffffffff810709d0-ffffffff81070b57: fill_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
pmd_t *fill_pmd(pud_t *pud, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810737b0)
Location: arch/x86/mm/init_64.c:236
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
**Symbols:**

```
ffffffff810737b0-ffffffff81073900: fill_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
pmd_t *fill_pmd(pud_t *pud, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81079a00)
Location: arch/x86/mm/init_64.c:235
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
**Symbols:**

```
ffffffff81079a00-ffffffff81079b50: fill_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
pmd_t *fill_pmd(pud_t *pud, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107d720)
Location: arch/x86/mm/init_64.c:267
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
**Symbols:**

```
ffffffff8107d720-ffffffff8107d870: fill_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
pmd_t *fill_pmd(pud_t *pud, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107e7b0)
Location: arch/x86/mm/init_64.c:267
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
**Symbols:**

```
ffffffff8107e7b0-ffffffff8107e900: fill_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
pmd_t *fill_pmd(pud_t *pud, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81084ae0)
Location: arch/x86/mm/init_64.c:272
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
```
**Symbols:**

```
ffffffff81084ae0-ffffffff81084c31: fill_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
pmd_t *fill_pmd(pud_t *pud, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81085ff0)
Location: arch/x86/mm/init_64.c:267
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
```
**Symbols:**

```
ffffffff81085ff0-ffffffff81086141: fill_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
pmd_t *fill_pmd(pud_t *pud, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81086d90)
Location: arch/x86/mm/init_64.c:267
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
```
**Symbols:**

```
ffffffff81086d90-ffffffff81086ee3: fill_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
pmd_t *fill_pmd(pud_t *pud, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810960a0)
Location: arch/x86/mm/init_64.c:268
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
```
**Symbols:**

```
ffffffff810960a0-ffffffff810961f3: fill_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
pmd_t *fill_pmd(pud_t *pud, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810a8920)
Location: arch/x86/mm/init_64.c:267
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
```
**Symbols:**

```
ffffffff810a8920-ffffffff810a8a86: fill_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
pmd_t *fill_pmd(pud_t *pud, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810c1ef0)
Location: arch/x86/mm/init_64.c:273
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
```
**Symbols:**

```
ffffffff810c1ef0-ffffffff810c208b: fill_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
pmd_t *fill_pmd(pud_t *pud, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810c55d0)
Location: arch/x86/mm/init_64.c:273
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
```
**Symbols:**

```
ffffffff810c55d0-ffffffff810c576b: fill_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
pmd_t *fill_pmd(pud_t *pud, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810cda20)
Location: arch/x86/mm/init_64.c:273
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
```
**Symbols:**

```
ffffffff810cda20-ffffffff810cdbbb: fill_pmd (STB_LOCAL)
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
pmd_t *fill_pmd(pud_t *pud, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107d7b0)
Location: arch/x86/mm/init_64.c:267
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
**Symbols:**

```
ffffffff8107d7b0-ffffffff8107d900: fill_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
pmd_t *fill_pmd(pud_t *pud, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/mm/init_64.c:267
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
**Symbols:**

```
ffffffff8106c7d0-ffffffff8106c8d3: fill_pmd (STB_LOCAL)
ffffffff8106d6cd-ffffffff8106d6e5: fill_pmd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
pmd_t *fill_pmd(pud_t *pud, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107d760)
Location: arch/x86/mm/init_64.c:267
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
**Symbols:**

```
ffffffff8107d760-ffffffff8107d8b0: fill_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
pmd_t *fill_pmd(pud_t *pud, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107f850)
Location: arch/x86/mm/init_64.c:267
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
**Symbols:**

```
ffffffff8107f850-ffffffff8107f9a0: fill_pmd (STB_LOCAL)
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
