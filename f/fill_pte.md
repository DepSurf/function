# Function: <code>fill_pte</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
pte_t *fill_pte(pmd_t *pmd, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810690d0)
Location: arch/x86/mm/init_64.c:257
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:populate_extra_pte
```
**Symbols:**

```
ffffffff810690d0-ffffffff810691f6: fill_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
pte_t *fill_pte(pmd_t *pmd, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81068e30)
Location: arch/x86/mm/init_64.c:186
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pte
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
```
**Symbols:**

```
ffffffff81068e30-ffffffff81068f7d: fill_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
pte_t *fill_pte(pmd_t *pmd, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8106ca80)
Location: arch/x86/mm/init_64.c:176
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pte
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
```
**Symbols:**

```
ffffffff8106ca80-ffffffff8106cbcd: fill_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
pte_t *fill_pte(pmd_t *pmd, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8106bd10)
Location: arch/x86/mm/init_64.c:237
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pte
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
**Symbols:**

```
ffffffff8106bd10-ffffffff8106be55: fill_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
pte_t *fill_pte(pmd_t *pmd, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810706f0)
Location: arch/x86/mm/init_64.c:237
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pte
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
**Symbols:**

```
ffffffff810706f0-ffffffff81070862: fill_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
pte_t *fill_pte(pmd_t *pmd, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/mm/init_64.c:248
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pte
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
**Symbols:**

```
ffffffff81073540-ffffffff81073675: fill_pte (STB_LOCAL)
ffffffff8107490a-ffffffff8107491f: fill_pte.cold.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
pte_t *fill_pte(pmd_t *pmd, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/mm/init_64.c:247
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pte
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
**Symbols:**

```
ffffffff810795b0-ffffffff810796e5: fill_pte (STB_LOCAL)
ffffffff8107a81d-ffffffff8107a832: fill_pte.cold.24 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
pte_t *fill_pte(pmd_t *pmd, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/mm/init_64.c:279
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pte
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
**Symbols:**

```
ffffffff8107d2e0-ffffffff8107d415: fill_pte (STB_LOCAL)
ffffffff8107e58c-ffffffff8107e5a1: fill_pte.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
pte_t *fill_pte(pmd_t *pmd, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/mm/init_64.c:279
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pte
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
**Symbols:**

```
ffffffff8107e370-ffffffff8107e4a5: fill_pte (STB_LOCAL)
ffffffff8107f61c-ffffffff8107f631: fill_pte.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
pte_t *fill_pte(pmd_t *pmd, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/mm/init_64.c:284
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pte
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
```
**Symbols:**

```
ffffffff810849a0-ffffffff81084ad6: fill_pte (STB_LOCAL)
ffffffff81086540-ffffffff81086555: fill_pte.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
pte_t *fill_pte(pmd_t *pmd, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/mm/init_64.c:279
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pte
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
```
**Symbols:**

```
ffffffff81085eb0-ffffffff81085fe6: fill_pte (STB_LOCAL)
ffffffff81bd91ba-ffffffff81bd91cf: fill_pte.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
pte_t *fill_pte(pmd_t *pmd, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/mm/init_64.c:279
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pte
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
```
**Symbols:**

```
ffffffff81086ef0-ffffffff81087028: fill_pte (STB_LOCAL)
ffffffff81bcb13f-ffffffff81bcb154: fill_pte.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
pte_t *fill_pte(pmd_t *pmd, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/mm/init_64.c:280
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pte
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
```
**Symbols:**

```
ffffffff81096200-ffffffff81096338: fill_pte (STB_LOCAL)
ffffffff81ca0709-ffffffff81ca071e: fill_pte.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
pte_t *fill_pte(pmd_t *pmd, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/mm/init_64.c:279
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pte
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
```
**Symbols:**

```
ffffffff810a8a90-ffffffff810a8bdb: fill_pte (STB_LOCAL)
ffffffff81e4fc31-ffffffff81e4fc46: fill_pte.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
pte_t *fill_pte(pmd_t *pmd, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810c1d80)
Location: arch/x86/mm/init_64.c:285
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pte
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
```
**Symbols:**

```
ffffffff810c1d80-ffffffff810c1edd: fill_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
pte_t *fill_pte(pmd_t *pmd, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810c5460)
Location: arch/x86/mm/init_64.c:285
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pte
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
```
**Symbols:**

```
ffffffff810c5460-ffffffff810c55bd: fill_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
pte_t *fill_pte(pmd_t *pmd, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810cd8b0)
Location: arch/x86/mm/init_64.c:285
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pte
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
```
**Symbols:**

```
ffffffff810cd8b0-ffffffff810cda0d: fill_pte (STB_LOCAL)
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
pte_t *fill_pte(pmd_t *pmd, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/mm/init_64.c:279
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pte
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
**Symbols:**

```
ffffffff8107d370-ffffffff8107d4a5: fill_pte (STB_LOCAL)
ffffffff8107e61c-ffffffff8107e631: fill_pte.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
pte_t *fill_pte(pmd_t *pmd, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/mm/init_64.c:279
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pte
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
**Symbols:**

```
ffffffff8106c8e0-ffffffff8106c9e3: fill_pte (STB_LOCAL)
ffffffff8106d6e5-ffffffff8106d6fa: fill_pte.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
pte_t *fill_pte(pmd_t *pmd, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/mm/init_64.c:279
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pte
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
**Symbols:**

```
ffffffff8107d320-ffffffff8107d455: fill_pte (STB_LOCAL)
ffffffff8107e5cc-ffffffff8107e5e1: fill_pte.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
pte_t *fill_pte(pmd_t *pmd, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/mm/init_64.c:279
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pte
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
**Symbols:**

```
ffffffff8107f410-ffffffff8107f545: fill_pte (STB_LOCAL)
ffffffff810806bc-ffffffff810806d1: fill_pte.cold (STB_LOCAL)
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
