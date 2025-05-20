# Function: <code>__split_large_page</code>

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
In arch/x86/mm/pageattr.c (ffffffff8106d534)
Location: arch/x86/mm/pageattr.c:610
Inline: True
Inline callers:
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
In arch/x86/mm/pageattr.c (ffffffff8106d377)
Location: arch/x86/mm/pageattr.c:616
Inline: True
Inline callers:
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
In arch/x86/mm/pageattr.c (ffffffff81070fb8)
Location: arch/x86/mm/pageattr.c:616
Inline: True
Inline callers:
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
In arch/x86/mm/pageattr.c (ffffffff810706fe)
Location: arch/x86/mm/pageattr.c:652
Inline: True
Inline callers:
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
In arch/x86/mm/pageattr.c (ffffffff81075dbe)
Location: arch/x86/mm/pageattr.c:652
Inline: True
Inline callers:
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
In arch/x86/mm/pageattr.c (ffffffff81078900)
Location: arch/x86/mm/pageattr.c:680
Inline: True
Inline callers:
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
In arch/x86/mm/pageattr.c (ffffffff8107f0f0)
Location: arch/x86/mm/pageattr.c:930
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __split_large_page(struct cpa_data *cpa, pte_t *kpte, long unsigned int address, struct page *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pageattr.c (0)
Location: arch/x86/mm/pageattr.c:940
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
```
**Symbols:**

```
ffffffff810828c0-ffffffff81082e9b: __split_large_page (STB_LOCAL)
ffffffff81084b3d-ffffffff81084c37: __split_large_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __split_large_page(struct cpa_data *cpa, pte_t *kpte, long unsigned int address, struct page *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pageattr.c (0)
Location: arch/x86/mm/pageattr.c:940
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
```
**Symbols:**

```
ffffffff81083990-ffffffff81083f6b: __split_large_page (STB_LOCAL)
ffffffff81085825-ffffffff8108591f: __split_large_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __split_large_page(struct cpa_data *cpa, pte_t *kpte, long unsigned int address, struct page *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/mm/pat/set_memory.c:960
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
```
**Symbols:**

```
ffffffff8108d760-ffffffff8108dbc0: __split_large_page (STB_LOCAL)
ffffffff8108f6a5-ffffffff8108f6c0: __split_large_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __split_large_page(struct cpa_data *cpa, pte_t *kpte, long unsigned int address, struct page *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/mm/pat/set_memory.c:960
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
```
**Symbols:**

```
ffffffff8108d630-ffffffff8108da90: __split_large_page (STB_LOCAL)
ffffffff81bd9895-ffffffff81bd98b0: __split_large_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __split_large_page(struct cpa_data *cpa, pte_t *kpte, long unsigned int address, struct page *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/mm/pat/set_memory.c:968
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
```
**Symbols:**

```
ffffffff8108e1f0-ffffffff8108e670: __split_large_page (STB_LOCAL)
ffffffff81bcb8fd-ffffffff81bcb918: __split_large_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __split_large_page(struct cpa_data *cpa, pte_t *kpte, long unsigned int address, struct page *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/mm/pat/set_memory.c:968
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
```
**Symbols:**

```
ffffffff8109dce0-ffffffff8109e18a: __split_large_page (STB_LOCAL)
ffffffff81ca1377-ffffffff81ca13ad: __split_large_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __split_large_page(struct cpa_data *cpa, pte_t *kpte, long unsigned int address, struct page *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/mm/pat/set_memory.c:960
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
```
**Symbols:**

```
ffffffff810b1610-ffffffff810b1ac9: __split_large_page (STB_LOCAL)
ffffffff81e5096a-ffffffff81e5099d: __split_large_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __split_large_page(struct cpa_data *cpa, pte_t *kpte, long unsigned int address, struct page *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/mm/pat/set_memory.c:1037
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
```
**Symbols:**

```
ffffffff810cbd50-ffffffff810cc231: __split_large_page (STB_LOCAL)
ffffffff82054de8-ffffffff82054dfd: __split_large_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __split_large_page(struct cpa_data *cpa, pte_t *kpte, long unsigned int address, struct page *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/mm/pat/set_memory.c:1038
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
```
**Symbols:**

```
ffffffff810cf390-ffffffff810cf854: __split_large_page (STB_LOCAL)
ffffffff820d33be-ffffffff820d33d3: __split_large_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __split_large_page(struct cpa_data *cpa, pte_t *kpte, long unsigned int address, struct page *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/mm/pat/set_memory.c:1042
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
```
**Symbols:**

```
ffffffff810d7a70-ffffffff810d7f34: __split_large_page (STB_LOCAL)
ffffffff821ae22c-ffffffff821ae241: __split_large_page.cold (STB_LOCAL)
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
int __split_large_page(struct cpa_data *cpa, pte_t *kpte, long unsigned int address, struct page *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pageattr.c (0)
Location: arch/x86/mm/pageattr.c:940
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
```
**Symbols:**

```
ffffffff81082990-ffffffff81082f6b: __split_large_page (STB_LOCAL)
ffffffff81084825-ffffffff8108491f: __split_large_page.cold (STB_LOCAL)
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
In arch/x86/mm/pageattr.c (ffffffff81071845)
Location: arch/x86/mm/pageattr.c:940
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __split_large_page(struct cpa_data *cpa, pte_t *kpte, long unsigned int address, struct page *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pageattr.c (0)
Location: arch/x86/mm/pageattr.c:940
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
```
**Symbols:**

```
ffffffff81082940-ffffffff81082f1b: __split_large_page (STB_LOCAL)
ffffffff810847d5-ffffffff810848cf: __split_large_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __split_large_page(struct cpa_data *cpa, pte_t *kpte, long unsigned int address, struct page *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pageattr.c (0)
Location: arch/x86/mm/pageattr.c:940
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
```
**Symbols:**

```
ffffffff81084a60-ffffffff81085037: __split_large_page (STB_LOCAL)
ffffffff81086925-ffffffff81086a1f: __split_large_page.cold (STB_LOCAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
